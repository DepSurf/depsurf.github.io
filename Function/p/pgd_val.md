# Function: <code>pgd_val</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578969413,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:446",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:__xen_pgd_walk",
        "arch/x86/xen/mmu.c:__xen_pgd_walk",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_pagetable_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579004976,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:446",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595008806,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:446",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579220537,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:446",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579274385,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:446",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:sync_global_pgds",
        "arch/x86/mm/init_64.c:sync_global_pgds",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:set_pte_vaddr",
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579279951,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:446",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595064763,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:446",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579289693,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:446",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pgd_range",
        "arch/x86/mm/pageattr.c:unmap_pgd_range",
        "arch/x86/mm/pageattr.c:lookup_address_in_pgd",
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:446",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579310215,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:446",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580657626,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:446",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_mask",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580663395,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:446",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pgd_range",
        "mm/memory.c:free_pgd_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:__get_locked_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580714317,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:446",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580717964,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:446",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580723281,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:446",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580730796,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:446",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580745279,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:446",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580746589,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:446",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580762580,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:446",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580800332,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:446",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hugetlb.c:huge_pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587361721,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:446",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580905229,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:446",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:page_check_address_pmd",
        "mm/huge_memory.c:split_huge_page_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580972867,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:446",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581314830,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:446",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582953727,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:446",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595141764,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:419",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:__xen_pgd_walk",
        "arch/x86/xen/mmu.c:__xen_pgd_walk",
        "arch/x86/xen/mmu.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579009264,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:419",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595173334,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:419",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579220772,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:419",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579277714,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:419",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:set_pte_vaddr",
        "arch/x86/mm/init_64.c:sync_global_pgds",
        "arch/x86/mm/init_64.c:sync_global_pgds",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579279012,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:419",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595230446,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:419",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579298844,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:419",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address",
        "arch/x86/mm/pageattr.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:419",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579311000,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:419",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579320410,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:419",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587851872,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:419",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579346224,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:419",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580768173,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:419",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580789593,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:419",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pgd_range",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580829439,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:419",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580833654,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:419",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580841771,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:419",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_check_address_transhuge",
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580849676,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:419",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580864413,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:419",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580865805,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:419",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580884974,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:419",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580924316,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:419",
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
      "addr": 18446744071587863174,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:419",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581034283,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:419",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581126675,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:419",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581481689,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:419",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583241332,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:419",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586580474,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:419",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595384434,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:__xen_pgd_walk",
        "arch/x86/xen/mmu.c:__xen_pgd_walk",
        "arch/x86/xen/mmu.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579011136,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595415714,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579232926,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579293036,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:set_pte_vaddr",
        "arch/x86/mm/init_64.c:sync_global_pgds",
        "arch/x86/mm/init_64.c:sync_global_pgds",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579294276,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595473503,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579314316,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address",
        "arch/x86/mm/pageattr.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579326216,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579335634,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588066633,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579362080,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580833709,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580854043,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pgd_range",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580895007,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580899765,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580905133,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580906381,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580907773,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580912315,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_check_address_transhuge",
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580920156,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580953054,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580992668,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
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
      "addr": 18446744071588077880,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581109483,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581201715,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581562571,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583356644,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586765146,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596305747,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578998718,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596334828,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579230528,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579290413,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init",
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
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596395066,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579311690,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579329514,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588293444,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596408580,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580879122,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
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
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
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
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580944255,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
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
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580951507,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580953229,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad",
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580957329,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580964624,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580998291,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581040156,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
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
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581157852,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581249166,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581618180,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586888442,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588205465,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602594781,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602623639,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579001076,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602652150,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579246098,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579310359,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds",
        "arch/x86/mm/init_64.c:sync_global_pgds",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579312518,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602713748,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579334274,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579354838,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588858488,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579370073,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:p4d_page_vaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602733192,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580963940,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
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
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
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
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581044544,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
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
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581052914,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581054973,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad",
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581058975,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581071072,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581109389,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581150165,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
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
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581245258,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581287367,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581380864,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581762596,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587377310,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588754618,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602763124,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602792304,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579004345,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602822029,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579258558,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321482,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579324884,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602886384,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579345110,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579366285,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589237633,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579382691,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579395177,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
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
      "addr": 18446744071581100287,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
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
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
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
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581182229,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
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
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581191756,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581193685,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad",
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581197683,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581208156,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581245347,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581293612,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
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
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581396680,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581434423,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581501929,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581530878,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581930850,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587681163,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589132643,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:404",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604557217,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604586169,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579005849,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604617173,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579282222,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579345786,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579348948,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604683394,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579371702,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579381315,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pgd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579393879,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589481671,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579410260,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579423481,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
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
      "addr": 18446744071581178293,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
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
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
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
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581264664,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
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
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581274879,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581276965,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad",
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581281027,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581289324,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581328867,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581376636,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
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
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581480312,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581517943,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581587177,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581616670,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582015266,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587820388,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589367247,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604651551,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604681574,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579013245,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604713348,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579296487,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579361466,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579363673,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604782882,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579386806,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579396735,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pgd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579409820,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589941403,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579426051,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579439527,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
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
      "addr": 18446744071581248485,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
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
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
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
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581339245,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
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
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581349343,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581351413,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad",
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581355651,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581363996,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581448262,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581487538,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
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
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581627738,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581698611,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581728733,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582151861,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588123492,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589824163,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:411",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604663823,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604694016,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579015549,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604725650,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579302039,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579365706,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579367913,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604808649,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579390198,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579400047,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pgd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579413004,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590168955,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579429219,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579442919,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
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
      "addr": 18446744071581307093,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
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
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
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
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581398534,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
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
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581409449,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581410917,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad",
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581415187,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423644,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581512486,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581551954,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
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
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581659130,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581698554,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581772051,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581802285,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582229141,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588328292,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590050387,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
pgdval_t pgd_val(pgd_t pgd)
```

```json
{
  "name": "pgd_val",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578870966,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ]
    },
    {
      "addr": 18446744071609045397,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_p2m_free",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys"
      ]
    },
    {
      "addr": 18446744071579027172,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609059134,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579138493,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579331857,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579392582,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:set_pte_vaddr",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init"
      ]
    },
    {
      "addr": 18446744071579397039,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609147308,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579408565,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579413248,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:sync_current_stack_to_mm",
        "arch/x86/mm/tlb.c:sync_current_stack_to_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579422066,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591186903,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579454342,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579466330,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
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
      "addr": 18446744071579491087,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "arch/x86/platform/uv/bios_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/bios_uv.c:pgd_page_vaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581512351,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581521142,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581593075,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581596360,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581605181,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581608987,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581610869,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581616320,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581626881,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_p4d_range",
        "mm/vmalloc.c:vunmap_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581719640,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581762399,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
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
      "addr": 18446744071591198035,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581868115,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:p4d_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581914501,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581992741,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582022877,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582042933,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pgd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582458557,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585045879,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591150519,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
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
      "addr": 18446744071578870966,
      "name": "pgd_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071578998944,
      "name": "pgd_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579393603,
      "name": "pgd_val",
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
pgdval_t pgd_val(pgd_t pgd)
```

```json
{
  "name": "pgd_val",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591238335,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ]
    },
    {
      "addr": 18446744071612108753,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_p2m_free",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys"
      ]
    },
    {
      "addr": 18446744071579031188,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612122494,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591251011,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579333441,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579396873,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:set_pte_vaddr",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init"
      ]
    },
    {
      "addr": 18446744071579403407,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
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
      "addr": 18446744071612217650,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579409029,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579421476,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591682218,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579451206,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579462686,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
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
      "addr": 18446744071581190772,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581552479,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581588498,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__apply_to_page_range",
        "mm/memory.c:__apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581639091,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581642584,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581652328,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581656379,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581658261,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581663312,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581672577,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_p4d_range",
        "mm/vmalloc.c:vunmap_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581696710,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ioremap.c:ioremap_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581767544,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581810479,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
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
      "addr": 18446744071591692926,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581913027,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:p4d_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581961381,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582042309,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582071309,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582091893,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pgd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582515469,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591236503,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:387",
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
      "addr": 18446744071591238335,
      "name": "pgd_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579000768,
      "name": "pgd_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591266293,
      "name": "pgd_val",
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
pgdval_t pgd_val(pgd_t pgd)
```

```json
{
  "name": "pgd_val",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591181152,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ]
    },
    {
      "addr": 18446744071591185763,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys"
      ]
    },
    {
      "addr": 18446744071579034172,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591190538,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591194619,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579335555,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579400180,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init"
      ]
    },
    {
      "addr": 18446744071579402505,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591212686,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579412309,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579420915,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591215834,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579453459,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071614377667,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581198099,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581559363,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581583171,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581657043,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581664003,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581672067,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581675731,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581680069,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581681283,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581697540,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_small_pages_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581795305,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581819763,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591635424,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581936883,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581964819,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582066835,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582096227,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582116965,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pgd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582542451,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591178627,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:p4d_offset"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591181152,
      "name": "pgd_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591185763,
      "name": "pgd_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591208604,
      "name": "pgd_val",
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
pgdval_t pgd_val(pgd_t pgd)
```

```json
{
  "name": "pgd_val",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592037297,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ]
    },
    {
      "addr": 18446744071592047935,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys"
      ]
    },
    {
      "addr": 18446744071579053020,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592054747,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592060384,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579390851,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579462492,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init"
      ]
    },
    {
      "addr": 18446744071579464850,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592086982,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579475157,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579484499,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592092443,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579518819,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071615309926,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581438451,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581823635,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581848492,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581925235,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581932339,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581941363,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581944915,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581949349,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581950563,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581969789,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_small_pages_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582079284,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582105987,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582170739,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582241251,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582267603,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582376707,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582411011,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582433349,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pgd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582858499,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592034691,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:409",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:p4d_offset"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592037297,
      "name": "pgd_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071592047935,
      "name": "pgd_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071592082242,
      "name": "pgd_val",
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
pgdval_t pgd_val(pgd_t pgd)
```

```json
{
  "name": "pgd_val",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593803327,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ]
    },
    {
      "addr": 18446744071579046496,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys"
      ]
    },
    {
      "addr": 18446744071579079902,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593821589,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593826862,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579457203,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579538971,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init"
      ]
    },
    {
      "addr": 18446744071579541401,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593853798,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579552997,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579564163,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593859540,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579602931,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071617090870,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581778083,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593969000,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582215715,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582240979,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582332035,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582340835,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582350627,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582354163,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582358741,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582360211,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582392947,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_small_pages_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582518986,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582549875,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582628947,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582736931,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582745939,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582877875,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582923907,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582950005,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pgd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583421107,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593800083,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:p4d_offset"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593803327,
      "name": "pgd_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579046496,
      "name": "pgd_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579532400,
      "name": "pgd_val",
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
  "name": "pgd_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627491436,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627536778,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579113342,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627560546,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579269924,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579546244,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579642401,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:preallocate_vmalloc_pages",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579646007,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579651972,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579672148,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579715748,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579715876,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071627749310,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582202532,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582617956,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582722463,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582731433,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582832484,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582842420,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582852308,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582856084,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582860997,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582862644,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582899220,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_small_pages_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583037206,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583066596,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583119556,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_remap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583153156,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583267362,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:p4d_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583425604,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583479428,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583507253,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pgd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584009108,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595745764,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:415",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:p4d_offset"
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
  "name": "pgd_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619235564,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619282762,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579113662,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619309874,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579276244,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579561540,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579656449,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:preallocate_vmalloc_pages",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579660423,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579666196,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579686052,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579729332,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579729460,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071619508825,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582402580,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582826868,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582938253,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582947284,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583047876,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583058164,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583068260,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583071668,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583076501,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583079284,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583114356,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_small_pages_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583246219,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583277108,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583329812,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_remap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583363588,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583487714,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:p4d_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583645988,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583696004,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583722133,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pgd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584233524,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596270052,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:p4d_offset"
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
  "name": "pgd_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621525644,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621575194,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579139470,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579232580,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579306052,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579589060,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579690321,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:preallocate_vmalloc_pages",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579694423,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579700196,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579720580,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579764276,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579764404,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071621805657,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582570308,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583001316,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583092644,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583123444,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583229684,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583239876,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583250196,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583253652,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583258757,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583261604,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583296724,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_small_pages_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583480747,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583514132,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583600068,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583681090,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:p4d_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583840564,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583890212,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583922837,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pgd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584448084,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597154788,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:410",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:p4d_offset"
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "pgd_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282719212,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:56",
      "file": "arch/powerpc/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/pgtable.c:__find_linux_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282724632,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:56",
      "file": "arch/powerpc/mm/pgtable_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/pgtable_64.c:pgd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282734852,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:56",
      "file": "arch/powerpc/mm/book3s64/hash_pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/hash_pgtable.c:hash__map_kernel_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297809576,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:56",
      "file": "arch/powerpc/mm/book3s64/radix_pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/radix_pgtable.c:remove_pagetable",
        "arch/powerpc/mm/book3s64/radix_pgtable.c:__map_kernel_page",
        "arch/powerpc/mm/book3s64/radix_pgtable.c:__map_kernel_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282817148,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:56",
      "file": "arch/powerpc/mm/book3s64/subpage_prot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/subpage_prot.c:hpte_flush_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282842640,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:56",
      "file": "arch/powerpc/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/hugetlbpage.c:hugetlb_free_pgd_range",
        "arch/powerpc/mm/hugetlbpage.c:hugetlb_free_pgd_range",
        "arch/powerpc/mm/hugetlbpage.c:hugetlb_free_pgd_range",
        "arch/powerpc/mm/hugetlbpage.c:hugetlb_free_pgd_range",
        "arch/powerpc/mm/hugetlbpage.c:huge_pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283266448,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:56",
      "file": "arch/powerpc/xmon/xmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/xmon/xmon.c:show_pte",
        "arch/powerpc/xmon/xmon.c:show_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286061156,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:56",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:follow_page_mask",
        "mm/gup.c:follow_page_mask",
        "mm/gup.c:follow_page_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286075124,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:56",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pgd_range",
        "mm/memory.c:free_pgd_range",
        "mm/memory.c:free_pgd_range",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286169252,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:56",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286176752,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:56",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286183732,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:56",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286187616,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:56",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286191224,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:56",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286195992,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:56",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286209104,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:56",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_page_range_noflush",
        "mm/vmalloc.c:vunmap_page_range",
        "mm/vmalloc.c:vunmap_page_range",
        "mm/vmalloc.c:vunmap_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286345336,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:56",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297817964,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:56",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286564600,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:56",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286629168,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:56",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286745592,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:56",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286793100,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:56",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287412944,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:56",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297670976,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:56",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604590095,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604620297,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579015901,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604651953,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579297847,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579361610,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579363817,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604722591,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579386102,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579395951,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pgd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579408844,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589771243,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579425059,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579438759,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
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
      "addr": 18446744071581275941,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
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
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
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
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581367382,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
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
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581378297,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581379765,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad",
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581384035,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581392492,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581481222,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581520690,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
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
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581627866,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581667290,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581740787,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581771021,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582197877,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587935076,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589652643,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604667919,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604698112,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579015485,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604729716,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579299047,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579361530,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579363737,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604800158,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579386022,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579395871,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pgd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579408764,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590214651,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579424979,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579438679,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
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
      "addr": 18446744071581267141,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
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
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
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
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581358582,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
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
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581369497,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581370965,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad",
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581375235,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581383692,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581472534,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581512002,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
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
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581619178,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581658602,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581732099,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581762333,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582188357,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588266852,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590096019,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604667924,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604698118,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579019053,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_set_p4d",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604729762,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579307879,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579369962,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579372169,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604812777,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579394534,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579404383,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pgd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579417628,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590265019,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579434163,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579447879,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
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
      "addr": 18446744071581330997,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
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
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
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
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581422488,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
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
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581433369,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581434853,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad",
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581439091,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581447708,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581537361,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581577058,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
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
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581682458,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581724986,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581800387,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581831213,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582264476,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588402020,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590146275,
      "name": "pgd_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:399",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
pgdval_t pgd_val(pgd_t pgd)
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
pgdval_t pgd_val(pgd_t pgd)
```
</details>
</li>
</ul>
