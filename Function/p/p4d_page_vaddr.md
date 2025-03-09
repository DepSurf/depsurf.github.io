# Function: <code>p4d_page_vaddr</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "p4d_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596305747,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596334760,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579230528,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579290534,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds",
        "arch/x86/mm/init_64.c:sync_global_pgds",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579293556,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596395066,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579311690,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579329669,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588293444,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596408492,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580879122,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages_fast",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580883533,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pgd_range",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580939922,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580944255,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580949861,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580951507,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580957329,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580964624,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580998291,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581040156,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
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
      "addr": 18446744071588304333,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581157852,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581249166,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581618180,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586888442,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588205465,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_page_range"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int p4d_page_vaddr(p4d_t p4d)
```

```json
{
  "name": "p4d_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602594826,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:826",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602623639,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:826",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602652070,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:826",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579246098,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:826",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579310079,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:826",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds",
        "arch/x86/mm/init_64.c:sync_global_pgds",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud"
      ]
    },
    {
      "addr": 18446744071579312518,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:826",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602713748,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:826",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579334274,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:826",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:826",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579354663,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:826",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588858488,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:826",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579370069,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:826",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ]
    },
    {
      "addr": 18446744071579380928,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:826",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog"
      ]
    },
    {
      "addr": 18446744071580963940,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:826",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580977104,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:826",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pgd_range",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581039807,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:826",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581044544,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:826",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581050993,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:826",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581052914,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:826",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581058975,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:826",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581071072,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:826",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581109389,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:826",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581150165,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:826",
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
      "addr": 18446744071588869668,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:826",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581245258,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:826",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581287367,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:826",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581380864,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:826",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581762596,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:826",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587377310,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:826",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588754501,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:826",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_page_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579304544,
      "name": "p4d_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579370069,
      "name": "p4d_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579380928,
      "name": "p4d_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int p4d_page_vaddr(p4d_t p4d)
```

```json
{
  "name": "p4d_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602763177,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602792304,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602822029,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579258558,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321527,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud"
      ]
    },
    {
      "addr": 18446744071579324884,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602886384,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579345110,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579366285,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589237633,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579382691,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602897258,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579395177,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings"
      ],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog"
      ]
    },
    {
      "addr": 18446744071581100287,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581112328,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pgd_range",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581178527,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581182229,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581189642,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581191756,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581197683,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581208156,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581245347,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581293612,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
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
      "addr": 18446744071589248681,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581396680,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581434423,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581501929,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581530878,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581930850,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587681163,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589132643,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_page_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579316912,
      "name": "p4d_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579394928,
      "name": "p4d_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071581109824,
      "name": "p4d_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int p4d_page_vaddr(p4d_t p4d)
```

```json
{
  "name": "p4d_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604557270,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:893",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604586169,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:893",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604617173,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:893",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579282222,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:893",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579345831,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:893",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud"
      ]
    },
    {
      "addr": 18446744071579348948,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:893",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604683394,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:893",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579371702,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:893",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579381315,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:893",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pgd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579393879,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:893",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589481671,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:893",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579410260,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:893",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604694642,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:893",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579423481,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:893",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings"
      ],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog"
      ]
    },
    {
      "addr": 18446744071581178293,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:893",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581191448,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:893",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pgd_range",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581258685,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:893",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581264664,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:893",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581272615,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:893",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581274879,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:893",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581281027,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:893",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581289324,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:893",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581328867,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:893",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581376636,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:893",
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
      "addr": 18446744071589490967,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:893",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581480312,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:893",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581517943,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:893",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581587177,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:893",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581616670,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:893",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582015266,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:893",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587820388,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:893",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589367247,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:893",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_page_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579341648,
      "name": "p4d_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579423232,
      "name": "p4d_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int p4d_page_vaddr(p4d_t p4d)
```

```json
{
  "name": "p4d_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604651604,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604681574,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604713348,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579296487,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579361511,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud"
      ]
    },
    {
      "addr": 18446744071579363673,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604782882,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579386806,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579396735,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pgd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579408837,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589941403,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579426051,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604794666,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579439527,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings"
      ],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog"
      ]
    },
    {
      "addr": 18446744071581248485,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581264262,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581334460,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581339245,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581347079,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581349343,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581355651,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581363996,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581448262,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581487538,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
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
      "addr": 18446744071589951931,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581627738,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581698611,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581728733,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582151861,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588123492,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589824163,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_pud_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579357024,
      "name": "p4d_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579439280,
      "name": "p4d_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int p4d_page_vaddr(p4d_t p4d)
```

```json
{
  "name": "p4d_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604663876,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604694016,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604725650,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579302039,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579365751,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud"
      ]
    },
    {
      "addr": 18446744071579367913,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604808649,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579390198,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579400047,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pgd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579412021,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590168955,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579429219,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604820389,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579442919,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings"
      ],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog"
      ]
    },
    {
      "addr": 18446744071581307093,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581323043,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581394044,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581398534,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581406391,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581409449,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581415187,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423644,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581512486,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581551954,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
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
      "addr": 18446744071590179465,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581659130,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581698554,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581772051,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581802285,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582229141,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588328292,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590050387,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_pud_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579361264,
      "name": "p4d_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579442672,
      "name": "p4d_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int p4d_page_vaddr(p4d_t p4d)
```

```json
{
  "name": "p4d_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609015099,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579001967,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d"
      ]
    },
    {
      "addr": 18446744071579138542,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579331993,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579392753,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:ident_p4d_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_p4d_table",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud"
      ]
    },
    {
      "addr": 18446744071579397078,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609147338,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579408599,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579420290,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
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
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579454643,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609158789,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579466554,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings"
      ],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ]
    },
    {
      "addr": 18446744071579491054,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/platform/uv/bios_uv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_epilog",
        "arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_prolog",
        "arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_prolog"
      ]
    },
    {
      "addr": 18446744071581504199,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:get_gate_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581521233,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
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
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581596451,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581605238,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581608300,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581616363,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581626927,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
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
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581762442,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
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
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581880468,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581914540,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581992780,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582022937,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582458596,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585044823,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591150556,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
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
      "addr": 18446744071578999072,
      "name": "p4d_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579387264,
      "name": "p4d_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579465792,
      "name": "p4d_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579491054,
      "name": "p4d_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
long unsigned int p4d_page_vaddr(p4d_t p4d)
```

```json
{
  "name": "p4d_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612077103,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579003768,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d"
      ]
    },
    {
      "addr": 18446744071591251060,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579333577,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397046,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:ident_p4d_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:preallocate_vmalloc_pages",
        "arch/x86/mm/init_64.c:remove_p4d_table",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4"
      ]
    },
    {
      "addr": 18446744071579403446,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612217680,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579409063,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579421752,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
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
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579451507,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612229387,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579462910,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings"
      ],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ]
    },
    {
      "addr": 18446744071581190811,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581544359,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:get_gate_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581596162,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
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
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581642671,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581652386,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581655724,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581663355,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581672623,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
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
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ioremap.c:ioremap_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581767744,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581810522,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
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
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581926487,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581961420,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582042348,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582071369,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582515508,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591236540,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
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
      "addr": 18446744071579000896,
      "name": "p4d_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579392608,
      "name": "p4d_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579462208,
      "name": "p4d_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
long unsigned int p4d_page_vaddr(p4d_t p4d)
```

```json
{
  "name": "p4d_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614215610,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614248111,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591194827,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579336279,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579400296,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:ident_p4d_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:preallocate_vmalloc_pages",
        "arch/x86/mm/init_64.c:remove_p4d_table",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4"
      ]
    },
    {
      "addr": 18446744071579406650,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614358858,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579413134,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pgd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579424810,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
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
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579453972,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614370143,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579465111,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings"
      ],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ]
    },
    {
      "addr": 18446744071581220272,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581574913,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
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
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
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
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581664237,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581673330,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581677215,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581685359,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581699007,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
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
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581838911,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
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
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581951855,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581987358,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582068828,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582096374,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582545085,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591179219,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:909",
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
      "addr": 18446744071579396048,
      "name": "p4d_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579464544,
      "name": "p4d_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int p4d_page_vaddr(p4d_t p4d)
```

```json
{
  "name": "p4d_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604590148,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604620297,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604651953,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579297847,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579361655,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud"
      ]
    },
    {
      "addr": 18446744071579363817,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604722591,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579386102,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579395951,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pgd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579407861,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589771243,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579425059,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604734269,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579438759,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings"
      ],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog"
      ]
    },
    {
      "addr": 18446744071581275941,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581291891,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581362892,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581367382,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581375239,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581378297,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581384035,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581392492,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581481222,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581520690,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
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
      "addr": 18446744071589781753,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581627866,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581667290,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581740787,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581771021,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582197877,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587935076,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589652643,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_pud_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579357168,
      "name": "p4d_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579438512,
      "name": "p4d_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "p4d_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604581818,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604619659,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579233950,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579292631,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579295132,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604690495,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579307040,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:populate_pgd",
        "arch/x86/mm/pageattr.c:populate_pgd",
        "arch/x86/mm/pageattr.c:populate_pgd",
        "arch/x86/mm/pageattr.c:populate_pgd",
        "arch/x86/mm/pageattr.c:lookup_pmd_address",
        "arch/x86/mm/pageattr.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579337633,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589494064,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579354112,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604701890,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579367827,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581222421,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581236415,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pgd_range",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581305227,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581310904,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581318641,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581320687,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581326878,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581335193,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423554,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581462821,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
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
      "addr": 18446744071589504421,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581569066,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581606902,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581679612,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581709642,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582135375,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587648339,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589378446,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_pud_range"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int p4d_page_vaddr(p4d_t p4d)
```

```json
{
  "name": "p4d_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604667972,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604698112,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604729716,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579299047,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579361575,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud"
      ]
    },
    {
      "addr": 18446744071579363737,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604800158,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579386022,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579395871,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pgd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579407781,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590214651,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579424979,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604811836,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579438679,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings"
      ],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog"
      ]
    },
    {
      "addr": 18446744071581267141,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581283091,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581354092,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581358582,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581366439,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581369497,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581375235,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581383692,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581472534,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581512002,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
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
      "addr": 18446744071590225161,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581619178,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581658602,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581732099,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581762333,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582188357,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588266852,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590096019,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_pud_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579357088,
      "name": "p4d_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579438432,
      "name": "p4d_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int p4d_page_vaddr(p4d_t p4d)
```

```json
{
  "name": "p4d_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604667977,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604698118,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604729762,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579307879,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579370007,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud"
      ]
    },
    {
      "addr": 18446744071579372169,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604812777,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579394534,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579404383,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pgd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579416645,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590265019,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579434163,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604824546,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579447879,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings"
      ],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog"
      ]
    },
    {
      "addr": 18446744071581330997,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581347107,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581418028,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581422488,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581430333,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581433369,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581439091,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581447708,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581537361,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581577058,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
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
      "addr": 18446744071590275519,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581682458,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581724986,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581800387,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581831213,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582264476,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588402020,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590146275,
      "name": "p4d_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:910",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_pud_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579365520,
      "name": "p4d_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579447632,
      "name": "p4d_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
long unsigned int p4d_page_vaddr(p4d_t p4d)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
long unsigned int p4d_page_vaddr(p4d_t p4d)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
long unsigned int p4d_page_vaddr(p4d_t p4d)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int p4d_page_vaddr(p4d_t p4d)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long unsigned int p4d_page_vaddr(p4d_t p4d)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int p4d_page_vaddr(p4d_t p4d)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
long unsigned int p4d_page_vaddr(p4d_t p4d)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
