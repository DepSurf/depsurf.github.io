# Function: <code>p4d_val</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
p4dval_t p4d_val(p4d_t p4d)
```

```json
{
  "name": "p4d_val",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578871005,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ]
    },
    {
      "addr": 18446744071579001967,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579029849,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_set_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579138542,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579331993,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579392708,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:free_pud_table",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:ident_p4d_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_p4d_init"
      ]
    },
    {
      "addr": 18446744071579397078,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609147338,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579408599,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579420290,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591186933,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579454643,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579466554,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579491054,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "arch/x86/platform/uv/bios_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/bios_uv.c:p4d_page_vaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581504199,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:get_gate_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581521233,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_p4d_range",
        "mm/memory.c:apply_to_p4d_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581593243,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581596451,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581605238,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581608300,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581610997,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581616363,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581626927,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581719836,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581762442,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591197766,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581880468,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581914540,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581992780,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582022937,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582042997,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_p4d_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582458596,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585044823,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591150556,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:548",
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
      "addr": 18446744071578871005,
      "name": "p4d_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579393764,
      "name": "p4d_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
p4dval_t p4d_val(p4d_t p4d)
```

```json
{
  "name": "p4d_val",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591238374,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:470",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ]
    },
    {
      "addr": 18446744071579003768,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:470",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579033849,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:470",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_set_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591251060,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:470",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579333577,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:470",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397001,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:470",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:free_pud_table",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:ident_p4d_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_p4d_init"
      ]
    },
    {
      "addr": 18446744071579403446,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:470",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612217680,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:470",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579409063,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:470",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579421752,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:470",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591682248,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:470",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579451507,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:470",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579462910,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:470",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581190811,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:470",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581544359,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:470",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:get_gate_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581596162,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:470",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_invalidate_pte",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__apply_to_page_range",
        "mm/memory.c:__apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581639259,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:470",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581642671,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:470",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581652386,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:470",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581655724,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:470",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581658373,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:470",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581663355,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:470",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581672623,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:470",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581697064,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:470",
      "file": "mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ioremap.c:ioremap_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581767744,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:470",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581810522,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:470",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591692657,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:470",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581926487,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:470",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581961420,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:470",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582042348,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:470",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582071369,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:470",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582091957,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:470",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_p4d_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582515508,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:470",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591236540,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:470",
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
      "addr": 18446744071591238374,
      "name": "p4d_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591266423,
      "name": "p4d_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
p4dval_t p4d_val(p4d_t p4d)
```

```json
{
  "name": "p4d_val",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591181191,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ]
    },
    {
      "addr": 18446744071614248111,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579036521,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_set_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591194827,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579336279,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579400251,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_p4d_table",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:ident_p4d_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_p4d_init"
      ]
    },
    {
      "addr": 18446744071579406650,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614358858,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579413134,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pgd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579424810,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591625693,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579453972,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579465111,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581220272,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581574913,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:get_gate_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581618813,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_invalidate_pte",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_pud_range",
        "mm/memory.c:apply_to_pud_range",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581660840,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581664237,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581673330,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581677215,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581680181,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581685359,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581699007,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
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
      "addr": 18446744071581795499,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581838911,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591635279,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581951855,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581987358,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582068828,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582096374,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582117029,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_p4d_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582545085,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591179219,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
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
      "addr": 18446744071591181191,
      "name": "p4d_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591208734,
      "name": "p4d_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
p4dval_t p4d_val(p4d_t p4d)
```

```json
{
  "name": "p4d_val",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592037336,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ]
    },
    {
      "addr": 18446744071615168233,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579055449,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_set_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592060619,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579391590,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579462563,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_p4d_table",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:ident_p4d_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_p4d_init"
      ]
    },
    {
      "addr": 18446744071579469203,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615289376,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579475995,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pgd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579488435,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592799131,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579519364,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579530577,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581460259,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581839554,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:get_gate_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581886426,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_invalidate_pte",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_pud_range",
        "mm/memory.c:apply_to_pud_range",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:walk_to_pmd",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581929176,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581932591,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581942671,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581946412,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581949461,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581954817,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581970801,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
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
      "addr": 18446744071582079478,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582129781,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592809309,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate",
        "mm/sparse-vmemmap.c:vmemmap_remap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582256569,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582289443,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582382896,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582411171,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582433413,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_p4d_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582861203,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592035286,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:500",
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
      "addr": 18446744071592037336,
      "name": "p4d_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071592082372,
      "name": "p4d_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
p4dval_t p4d_val(p4d_t p4d)
```

```json
{
  "name": "p4d_val",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593803401,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ]
    },
    {
      "addr": 18446744071616934279,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579071720,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_set_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593827125,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579458100,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579539041,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_p4d_table",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:ident_p4d_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_p4d_init"
      ]
    },
    {
      "addr": 18446744071579546095,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617068751,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579553989,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pgd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579568444,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594699250,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579603488,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579617487,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581807508,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617165681,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582231664,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:get_gate_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582242760,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_pte",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_pud_range",
        "mm/memory.c:apply_to_pud_range",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:walk_to_pmd",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582337499,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582341108,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582352257,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582355698,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582358901,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582370076,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582393974,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
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
      "addr": 18446744071582519171,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582576801,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582629714,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582743705,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582773909,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582885741,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582924083,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582950101,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_p4d_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583431743,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593800707,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
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
      "addr": 18446744071593803401,
      "name": "p4d_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579532784,
      "name": "p4d_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
  "name": "p4d_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627491532,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627539609,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579104485,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_set_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579270813,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579547257,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579642471,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:preallocate_vmalloc_pages",
        "arch/x86/mm/init_64.c:remove_p4d_table",
        "arch/x86/mm/init_64.c:remove_p4d_table",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:ident_p4d_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579645330,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627717418,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579676684,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596439583,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579716498,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579729537,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582234122,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582514633,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:walk_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627851901,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582722570,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_p4d_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582738408,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_pte",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_pud_range",
        "mm/memory.c:apply_to_pud_range",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:walk_to_pmd",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582838585,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582842724,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582853555,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582857686,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582861173,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582871548,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582900236,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
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
      "addr": 18446744071583037390,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583095703,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583121562,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_should_optimize",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596453951,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:compound_section_tail_page",
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583275352,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583435151,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583479635,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583507365,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_p4d_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584019752,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595746467,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
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
  "name": "p4d_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619235660,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619285785,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579104805,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_set_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579277133,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579562553,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579656519,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:preallocate_vmalloc_pages",
        "arch/x86/mm/init_64.c:remove_p4d_table",
        "arch/x86/mm/init_64.c:remove_p4d_table",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:ident_p4d_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579659746,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619474890,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579690556,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596980399,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579730082,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579776018,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582437352,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582716637,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:walk_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619628797,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582938353,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_p4d_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582953990,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_pte",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_pud_range",
        "mm/memory.c:apply_to_pud_range",
        "mm/memory.c:remap_p4d_range",
        "mm/memory.c:walk_to_pmd",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583053372,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_p4d_range",
        "mm/mprotect.c:change_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583058471,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583069939,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583073190,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583076677,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583088383,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583115372,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
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
      "addr": 18446744071583245457,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583305546,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583331834,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_should_optimize",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596995279,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:compound_section_tail_page",
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583491840,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583650146,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583696214,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583722245,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_p4d_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584238831,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596270755,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:501",
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
  "name": "p4d_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621525740,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621578281,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579130613,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_set_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579307149,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579590089,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579690391,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:preallocate_vmalloc_pages",
        "arch/x86/mm/init_64.c:remove_p4d_table",
        "arch/x86/mm/init_64.c:remove_p4d_table",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:ident_p4d_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579693730,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621771370,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579725084,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:populate_pud",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597908831,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579765026,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579810914,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582605864,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582885981,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:walk_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621932814,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583113590,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:get_gate_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583126063,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_pte",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_pud_range",
        "mm/memory.c:apply_to_pud_range",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:walk_to_pmd",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583235004,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_p4d_range",
        "mm/mprotect.c:change_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583240183,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583251841,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583255238,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583258933,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583270815,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583298268,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
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
      "addr": 18446744071583479985,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583543418,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597924767,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:compound_section_tail_page",
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583682932,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583845066,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583890422,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583922949,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_p4d_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584450944,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071597155491,
      "name": "p4d_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:499",
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
p4dval_t p4d_val(p4d_t p4d)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
p4dval_t p4d_val(p4d_t p4d)
```
</details>
</li>
</ul>
