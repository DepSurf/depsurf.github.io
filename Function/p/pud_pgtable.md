# Function: <code>pud_pgtable</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
pmd_t * pud_pgtable(pud_t pud)
```

```json
{
  "name": "pud_pgtable",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615134522,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:839",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615167900,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:839",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud",
        "arch/x86/xen/mmu_pv.c:xen_pud_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579118859,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:839",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592060708,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:839",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579391779,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:839",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579462814,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:839",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate_hugepages",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pmd"
      ]
    },
    {
      "addr": 18446744071579469311,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:839",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615289414,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:839",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579477981,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:839",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579486353,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:839",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579519539,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:839",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592093037,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:839",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581460380,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:839",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581839718,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:839",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:get_gate_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581886526,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:839",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_invalidate_pte",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_pmd_range",
        "mm/memory.c:apply_to_pmd_range",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:walk_to_pmd",
        "mm/memory.c:copy_pmd_range",
        "mm/memory.c:copy_pmd_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581928120,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:839",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581934974,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:839",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581942794,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:839",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581945538,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:839",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581954904,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:839",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581970955,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:839",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vunmap_range_noflush",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582079653,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:839",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582129874,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:839",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592809204,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:839",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate",
        "mm/sparse-vmemmap.c:vmemmap_remap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582256637,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:839",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582289530,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:839",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582383010,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:839",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582411235,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:839",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582861290,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:839",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592035370,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:839",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579458448,
      "name": "pud_pgtable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
pmd_t * pud_pgtable(pud_t pud)
```

```json
{
  "name": "pud_pgtable",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071616897836,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:837",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616933925,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:837",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud",
        "arch/x86/xen/mmu_pv.c:xen_pud_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579151429,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:837",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593827216,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:837",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579458286,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:837",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579539280,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:837",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate_hugepages",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pmd"
      ]
    },
    {
      "addr": 18446744071579546201,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:837",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617068788,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:837",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579556525,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:837",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579566195,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:837",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579603656,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:837",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593860540,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:837",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581807627,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:837",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617165787,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:837",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582231847,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:837",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:get_gate_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582242859,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:837",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_pte",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_pmd_range",
        "mm/memory.c:apply_to_pmd_range",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:walk_to_pmd",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582337747,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:837",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582344228,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:837",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582352379,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:837",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582354902,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:837",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582370166,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:837",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582394126,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:837",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vunmap_p4d_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582519458,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:837",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582576897,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:837",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582629816,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:837",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_range"
      ],
      "caller_func": [
        "mm/sparse-vmemmap.c:__populate_section_memmap",
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ]
    },
    {
      "addr": 18446744071582743772,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:837",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582773999,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:837",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582885853,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:837",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582924146,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:837",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583431833,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:837",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593800789,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:837",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579533744,
      "name": "pud_pgtable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071582628544,
      "name": "pud_pgtable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_pgtable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627491648,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627539727,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_pud_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579200038,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579270880,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579547444,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579642715,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579645439,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627717455,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579663545,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579674372,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579716666,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627738183,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582234245,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582513454,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:walk_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627852008,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582715124,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:get_gate_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582738507,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_pte",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_pmd_range",
        "mm/memory.c:apply_to_pmd_range",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:walk_to_pmd",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582838834,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582845514,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582853679,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582856885,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582871639,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582900389,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vunmap_p4d_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583037582,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583095800,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583121612,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_should_optimize",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596454001,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:compound_section_tail_page",
        "mm/sparse-vmemmap.c:vmemmap_populate_hugepages",
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583275419,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583435258,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583479702,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584019843,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595746550,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_pgtable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619235776,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:856",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619285897,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:856",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_pud_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579204085,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:856",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579277200,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:856",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579562740,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:856",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579656763,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:856",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579659849,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:856",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619474927,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:856",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579677689,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:856",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579688260,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:856",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579730244,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:856",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619497303,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:856",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582437473,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:856",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582715486,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:856",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:walk_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619628904,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:856",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582938554,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:856",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:get_gate_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582954085,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:856",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_pte",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_pmd_range",
        "mm/memory.c:apply_to_pmd_range",
        "mm/memory.c:remap_p4d_range",
        "mm/memory.c:walk_to_pmd",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583053574,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:856",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583061100,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:856",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583070063,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:856",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583072521,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:856",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583088474,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:856",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583115519,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:856",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vunmap_p4d_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583245702,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:856",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583305643,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:856",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583331884,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:856",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_should_optimize",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596995329,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:856",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:compound_section_tail_page",
        "mm/sparse-vmemmap.c:vmemmap_populate_hugepages",
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583491907,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:856",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583650253,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:856",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583696281,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:856",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584238922,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:856",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596270832,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:856",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_pgtable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621525856,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1078",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621578393,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1078",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_pud_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579233429,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1078",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579307216,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1078",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579590276,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1078",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579690635,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1078",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579693833,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1078",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621771407,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1078",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579711817,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1078",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579722788,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1078",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579765188,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1078",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621794135,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1078",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582605985,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1078",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582884821,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1078",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:walk_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621932921,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1078",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583113784,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1078",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:get_gate_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583126158,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1078",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_pte",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_pmd_range",
        "mm/memory.c:apply_to_pmd_range",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:walk_to_pmd",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583235206,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1078",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583242627,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1078",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583251965,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1078",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583254569,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1078",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583270906,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1078",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583298415,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1078",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vunmap_p4d_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583480230,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1078",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583543515,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1078",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597924817,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1078",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:compound_section_tail_page",
        "mm/sparse-vmemmap.c:vmemmap_populate_hugepages",
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583682996,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1078",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583845175,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1078",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583890489,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1078",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584451035,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1078",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071597155568,
      "name": "pud_pgtable",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1078",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
pmd_t * pud_pgtable(pud_t pud)
```
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
pmd_t * pud_pgtable(pud_t pud)
```
</details>
</li>
</ul>
