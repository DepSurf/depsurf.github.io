# Function: <code>pud_val</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578969709,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:__xen_pgd_walk",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:xen_pagetable_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579004832,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579059900,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595008864,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579220738,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579274324,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579280031,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595064818,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579288992,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pgd_range",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:lookup_address_in_pgd",
        "arch/x86/mm/pageattr.c:lookup_address_in_pgd",
        "arch/x86/mm/pageattr.c:slow_virt_to_phys",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:lookup_pmd_address",
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579308889,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579309619,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_huge_pud",
        "arch/x86/mm/gup.c:gup_pud_range",
        "arch/x86/mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579315113,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/hugetlbpage.c:pud_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580657784,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_mask",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580663449,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
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
      "addr": 18446744071580714537,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580718087,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580723379,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580730873,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580745473,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580746669,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580762815,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580800816,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:huge_pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587361519,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580905339,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:page_check_address_pmd",
        "mm/huge_memory.c:split_huge_page_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580972936,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581314929,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582953894,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:579",
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
  "name": "pud_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595141876,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:552",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:__xen_pgd_walk",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579009120,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:552",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579056263,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:552",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595173436,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:552",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579220971,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:552",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579277769,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:552",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579279085,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:552",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
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
      "addr": 18446744071595230521,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:552",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579294800,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:552",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:slow_virt_to_phys",
        "arch/x86/mm/pageattr.c:lookup_pmd_address",
        "arch/x86/mm/pageattr.c:lookup_pmd_address",
        "arch/x86/mm/pageattr.c:lookup_address_in_pgd",
        "arch/x86/mm/pageattr.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579308617,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:552",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579311149,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:552",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_pud_range",
        "arch/x86/mm/gup.c:gup_pud_range",
        "arch/x86/mm/gup.c:gup_huge_pud",
        "arch/x86/mm/gup.c:gup_huge_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579317305,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:552",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/hugetlbpage.c:pud_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579320495,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:552",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580768245,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:552",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580789672,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:552",
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
      "addr": 18446744071580829719,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:552",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580833775,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:552",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580841861,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:552",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_check_address_transhuge",
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580849748,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:552",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580864602,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:552",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580865885,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:552",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580885203,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:552",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580924437,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:552",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587862947,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:552",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581034397,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:552",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581126752,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:552",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581481783,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:552",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583241496,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:552",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586580528,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:552",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume",
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume",
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
  "name": "pud_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595384546,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:543",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:__xen_pgd_walk",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579010992,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:543",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579055284,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:543",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595415816,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:543",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579233125,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:543",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579293091,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:543",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579294349,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:543",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
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
      "addr": 18446744071595473578,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:543",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579310300,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:543",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:slow_virt_to_phys",
        "arch/x86/mm/pageattr.c:lookup_pmd_address",
        "arch/x86/mm/pageattr.c:lookup_pmd_address",
        "arch/x86/mm/pageattr.c:lookup_address_in_pgd",
        "arch/x86/mm/pageattr.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579323849,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:543",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_clear_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579326365,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:543",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_pud_range",
        "arch/x86/mm/gup.c:gup_pud_range",
        "arch/x86/mm/gup.c:gup_huge_pud",
        "arch/x86/mm/gup.c:gup_huge_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579332585,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:543",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/hugetlbpage.c:pud_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579335719,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:543",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580833781,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:543",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580854122,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:543",
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
      "addr": 18446744071580895287,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:543",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580899886,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:543",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580905239,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:543",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580906570,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:543",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580907853,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:543",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580912405,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:543",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_check_address_transhuge",
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580920228,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:543",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580953286,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:543",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580992789,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:543",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588077653,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:543",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581109597,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:543",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581201792,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:543",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581562665,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:543",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583356808,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:543",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586765200,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:543",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume",
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume",
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
  "name": "pud_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596305871,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579003971,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579047543,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596334930,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579230724,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579290596,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579293629,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
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
      "addr": 18446744071596395116,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579306270,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:slow_virt_to_phys",
        "arch/x86/mm/pageattr.c:lookup_pmd_address",
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321209,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_clear_huge",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579326473,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/hugetlbpage.c:pud_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329770,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
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
      "addr": 18446744071580879268,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages_fast",
        "mm/gup.c:__get_user_pages_fast",
        "mm/gup.c:__get_user_pages_fast",
        "mm/gup.c:__get_user_pages_fast",
        "mm/gup.c:__get_user_pages_fast",
        "mm/gup.c:__get_user_pages_fast",
        "mm/gup.c:__get_user_pages_fast",
        "mm/gup.c:__get_user_pages_fast",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580883674,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pgd_range",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580940173,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580944387,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580950031,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580952181,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580953309,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580957420,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580964748,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580998522,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581040277,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588304106,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581157965,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:__pud_trans_huge_lock",
        "mm/huge_memory.c:__pud_trans_huge_lock",
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581249236,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581618274,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586888496,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume",
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume",
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588205625,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
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
  "name": "pud_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602594881,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602623771,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:pud_large"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579005491,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579056334,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602652258,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579246299,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579310145,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579312607,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602713811,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579328775,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:lookup_pmd_address",
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579344621,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579351625,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/hugetlbpage.c:pud_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579354896,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602722021,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd",
        "arch/x86/mm/pti.c:pud_page_vaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602724521,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580964106,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_pmd_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580977221,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pgd_range",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581040079,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581044678,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581051233,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581053695,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581055053,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581059065,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581071198,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581109643,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581150336,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588869416,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581245352,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581287482,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:__pud_trans_huge_lock",
        "mm/huge_memory.c:__pud_trans_huge_lock",
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581380947,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581762699,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587377369,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume",
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume",
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588754791,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
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
  "name": "pud_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602763219,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602792390,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:pud_large"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579008259,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579061316,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602822115,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579258756,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321589,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579324982,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602886460,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579339758,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:lookup_pmd_address",
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579355962,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579363381,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/hugetlbpage.c:pud_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579366603,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579382735,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602895975,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581100437,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581112457,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pgd_range",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581178731,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581182357,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581189742,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581192317,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581193765,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581197782,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581208289,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581245579,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581293766,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589248463,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581396764,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581434527,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:__pud_trans_huge_lock",
        "mm/huge_memory.c:__pud_trans_huge_lock",
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581502127,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill",
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581530948,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581931535,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587681223,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume",
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume",
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589132812,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:526",
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
  "name": "pud_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604557312,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:519",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604586255,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:519",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:pud_large"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579009763,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:519",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579065892,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:519",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604617259,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:519",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579282420,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:519",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579345893,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:519",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:pud_same",
        "arch/x86/mm/init_64.c:pud_same"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579349046,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:519",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604683470,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:519",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579366738,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:519",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:lookup_pmd_address",
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579383165,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:519",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579390901,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:519",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/hugetlbpage.c:pud_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579394237,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:519",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579410304,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:519",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604693284,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:519",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581178485,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:519",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581191577,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:519",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pgd_range",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581258890,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:519",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581264793,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:519",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581272715,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:519",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581275456,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:519",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range",
        "mm/pagewalk.c:walk_pgd_range",
        "mm/pagewalk.c:walk_pgd_range",
        "mm/pagewalk.c:walk_pgd_range",
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581277045,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:519",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581281126,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:519",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581289457,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:519",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581329099,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:519",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581376790,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:519",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589490749,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:519",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581480396,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:519",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581518047,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:519",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:__pud_trans_huge_lock",
        "mm/huge_memory.c:__pud_trans_huge_lock",
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581587378,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:519",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill",
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581616740,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:519",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582015951,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:519",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587820448,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:519",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code",
        "arch/x86/power/hibernate.c:relocate_restore_code",
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589367521,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:519",
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
  "name": "pud_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604651646,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:520",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604681648,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:520",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:pud_large"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579017060,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:520",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579074436,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:520",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604713433,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:520",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579296685,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:520",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579361576,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:520",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:pud_same",
        "arch/x86/mm/init_64.c:pud_same"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579363753,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:520",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604782989,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:520",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579381750,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:520",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:__split_large_page",
        "arch/x86/mm/pageattr.c:lookup_pmd_address",
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579398637,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:520",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579406261,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:520",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/hugetlbpage.c:pud_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579408989,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:520",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level",
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579426095,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:520",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604793301,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:520",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581248687,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:520",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581264393,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:520",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581334665,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:520",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581339374,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:520",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581347179,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:520",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581349795,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:520",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range",
        "mm/pagewalk.c:walk_pgd_range",
        "mm/pagewalk.c:walk_pgd_range",
        "mm/pagewalk.c:walk_pgd_range",
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581351493,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:520",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581355750,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:520",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581364129,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:520",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581448474,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:520",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581487689,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:520",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589951709,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:520",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581627842,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:520",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:__pud_trans_huge_lock",
        "mm/huge_memory.c:__pud_trans_huge_lock",
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581698690,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:520",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift",
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581728803,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:520",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581749048,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:520",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582152490,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:520",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588123552,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:520",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code",
        "arch/x86/power/hibernate.c:relocate_restore_code",
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589824491,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:520",
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
  "name": "pud_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604663918,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604694090,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:pud_large"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579019364,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076436,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604725735,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579302237,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579365816,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:pud_same",
        "arch/x86/mm/init_64.c:pud_same"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579367993,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604808756,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579386054,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:__split_large_page",
        "arch/x86/mm/pageattr.c:lookup_pmd_address",
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579401949,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579409445,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/hugetlbpage.c:pud_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579412173,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level",
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579429263,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604819022,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581307295,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581323178,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581394249,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581398663,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581406491,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581409965,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range",
        "mm/pagewalk.c:walk_pgd_range",
        "mm/pagewalk.c:walk_pgd_range",
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581410997,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581415286,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423777,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581512698,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581552105,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590179243,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581659214,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581698658,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:__pud_trans_huge_lock",
        "mm/huge_memory.c:__pud_trans_huge_lock",
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581772130,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift",
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581802355,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581821160,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582229770,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588328352,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code",
        "arch/x86/power/hibernate.c:relocate_restore_code",
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590050715,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
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
pudval_t pud_val(pud_t pud)
```

```json
{
  "name": "pud_val",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578870979,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:522",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ]
    },
    {
      "addr": 18446744071609044938,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:522",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud",
        "arch/x86/xen/mmu_pv.c:xen_pud_walk"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud"
      ]
    },
    {
      "addr": 18446744071579027060,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:522",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579086878,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:522",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579138645,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:522",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579332199,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:522",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579392816,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:522",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:fill_pmd"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 18446744071579397166,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:522",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609147376,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:522",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579411325,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:522",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579419487,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:522",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579440389,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:522",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/hugetlbpage.c:pud_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579454687,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:522",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609157215,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:522",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581509998,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:522",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:get_gate_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581521361,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:522",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_p4d_range",
        "mm/memory.c:apply_to_p4d_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581592150,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:522",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581596570,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:522",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581605328,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:522",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581607439,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:522",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581611093,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:522",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581616457,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:522",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581627055,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:522",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581720021,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:522",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581762545,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:522",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591197544,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:522",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581880550,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:522",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581914644,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:522",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:__pud_trans_huge_lock",
        "mm/huge_memory.c:__pud_trans_huge_lock",
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581992863,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:522",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift",
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582023009,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:522",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582038535,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:522",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582042700,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:522",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_clean_pud_entry",
        "mm/mapping_dirty_helpers.c:wp_clean_pud_entry",
        "mm/mapping_dirty_helpers.c:wp_clean_pud_entry",
        "mm/mapping_dirty_helpers.c:wp_clean_pud_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582043378,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:522",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pud_entry",
        "mm/ptdump.c:ptdump_pud_entry",
        "mm/ptdump.c:ptdump_pud_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582458702,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:522",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585045131,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:522",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591150603,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:522",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code",
        "arch/x86/power/hibernate.c:relocate_restore_code",
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578870979,
      "name": "pud_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071578998976,
      "name": "pud_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579393694,
      "name": "pud_val",
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
pudval_t pud_val(pud_t pud)
```

```json
{
  "name": "pud_val",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591238348,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ]
    },
    {
      "addr": 18446744071612108294,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud",
        "arch/x86/xen/mmu_pv.c:xen_pud_walk"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud"
      ]
    },
    {
      "addr": 18446744071579031076,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579088942,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591251163,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579333783,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397111,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 18446744071579403534,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612217718,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579411949,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579421873,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579438645,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/hugetlbpage.c:pud_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579451551,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612227709,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581190900,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size",
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581550126,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:get_gate_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581596290,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_invalidate_pte",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__apply_to_page_range",
        "mm/memory.c:__apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581638166,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581645360,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581652477,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581654863,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581658453,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581663449,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581672751,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581697377,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ioremap.c:ioremap_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581767929,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581810625,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591692435,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581926569,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581961524,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:__pud_trans_huge_lock",
        "mm/huge_memory.c:__pud_trans_huge_lock",
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582042431,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift",
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582071441,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582087415,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582091660,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_clean_pud_entry",
        "mm/mapping_dirty_helpers.c:wp_clean_pud_entry",
        "mm/mapping_dirty_helpers.c:wp_clean_pud_entry",
        "mm/mapping_dirty_helpers.c:wp_clean_pud_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582092338,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pud_entry",
        "mm/ptdump.c:ptdump_pud_entry",
        "mm/ptdump.c:ptdump_pud_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582515614,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591236587,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code",
        "arch/x86/power/hibernate.c:relocate_restore_code",
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591238348,
      "name": "pud_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579000800,
      "name": "pud_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591266384,
      "name": "pud_val",
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
pudval_t pud_val(pud_t pud)
```

```json
{
  "name": "pud_val",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591181165,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ]
    },
    {
      "addr": 18446744071614247778,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud",
        "arch/x86/xen/mmu_pv.c:xen_pud_walk"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud"
      ]
    },
    {
      "addr": 18446744071579034060,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579095501,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591194916,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579336479,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579400361,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 18446744071579406733,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614358896,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579415101,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579424931,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579441157,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/hugetlbpage.c:pud_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579454016,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614368486,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581220361,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size",
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581575092,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:get_gate_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581611065,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_pud_range",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:copy_p4d_range"
      ],
      "caller_func": [
        "mm/memory.c:follow_invalidate_pte",
        "mm/memory.c:follow_invalidate_pte",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_pmd_range",
        "mm/memory.c:apply_to_pmd_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_pmd_range",
        "mm/memory.c:copy_pmd_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ]
    },
    {
      "addr": 18446744071581659797,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581666859,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581673455,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581676351,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581680261,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581685453,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581699066,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581795687,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581839014,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
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
      "addr": 18446744071591635177,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581951936,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581987455,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:__pud_trans_huge_lock",
        "mm/huge_memory.c:__pud_trans_huge_lock",
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582068911,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift",
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582096444,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582112492,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582116732,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_clean_pud_entry",
        "mm/mapping_dirty_helpers.c:wp_clean_pud_entry",
        "mm/mapping_dirty_helpers.c:wp_clean_pud_entry",
        "mm/mapping_dirty_helpers.c:wp_clean_pud_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582117410,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pud_entry",
        "mm/ptdump.c:ptdump_pud_entry",
        "mm/ptdump.c:ptdump_pud_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582545183,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591179253,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code",
        "arch/x86/power/hibernate.c:relocate_restore_code",
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591181165,
      "name": "pud_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591185828,
      "name": "pud_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591208695,
      "name": "pud_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071581581936,
      "name": "pud_val",
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
pudval_t pud_val(pud_t pud)
```

```json
{
  "name": "pud_val",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592037310,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ]
    },
    {
      "addr": 18446744071615167900,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud",
        "arch/x86/xen/mmu_pv.c:xen_pud_walk"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud"
      ]
    },
    {
      "addr": 18446744071579052908,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579118859,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592060708,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579391779,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579462674,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 18446744071579469288,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615289414,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579477981,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579488558,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579505541,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/hugetlbpage.c:pud_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579519410,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615300036,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581460347,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size",
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581839718,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:get_gate_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581879772,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:copy_p4d_range"
      ],
      "caller_func": [
        "mm/memory.c:follow_invalidate_pte",
        "mm/memory.c:follow_invalidate_pte",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_pud_range",
        "mm/memory.c:apply_to_pmd_range",
        "mm/memory.c:apply_to_pmd_range",
        "mm/memory.c:walk_to_pmd",
        "mm/memory.c:copy_pmd_range",
        "mm/memory.c:copy_pmd_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ]
    },
    {
      "addr": 18446744071581928120,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581934854,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
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
      "addr": 18446744071581942794,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581945538,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581949541,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581954904,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581970863,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vunmap_range_noflush",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582079653,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582129874,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
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
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
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
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582289530,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:__pud_trans_huge_lock",
        "mm/huge_memory.c:__pud_trans_huge_lock",
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582382981,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift",
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582411235,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582428812,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582433116,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_clean_pud_entry",
        "mm/mapping_dirty_helpers.c:wp_clean_pud_entry",
        "mm/mapping_dirty_helpers.c:wp_clean_pud_entry",
        "mm/mapping_dirty_helpers.c:wp_clean_pud_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582433794,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pud_entry",
        "mm/ptdump.c:ptdump_pud_entry",
        "mm/ptdump.c:ptdump_pud_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582861290,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592035333,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code",
        "arch/x86/power/hibernate.c:relocate_restore_code",
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592037310,
      "name": "pud_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071592048000,
      "name": "pud_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071592082333,
      "name": "pud_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071581846896,
      "name": "pud_val",
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
pudval_t pud_val(pud_t pud)
```

```json
{
  "name": "pud_val",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593803345,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ]
    },
    {
      "addr": 18446744071616933925,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud",
        "arch/x86/xen/mmu_pv.c:xen_pud_walk"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud"
      ]
    },
    {
      "addr": 18446744071579079758,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579151429,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593827216,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579458286,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579539280,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 18446744071579546179,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617068788,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579556525,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579568570,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579587749,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/hugetlbpage.c:pud_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579603533,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579605032,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581807595,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size",
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617165787,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582231847,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:get_gate_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582277648,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_pud_range",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:copy_p4d_range"
      ],
      "caller_func": [
        "mm/memory.c:follow_pte",
        "mm/memory.c:follow_pte",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_pmd_range",
        "mm/memory.c:apply_to_pmd_range",
        "mm/memory.c:walk_to_pmd",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ]
    },
    {
      "addr": 18446744071582337747,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582344069,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
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
      "addr": 18446744071582352379,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582354902,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582358997,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582370166,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582394035,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vunmap_p4d_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582519458,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582576897,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
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
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582743772,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582773999,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:__pud_trans_huge_lock",
        "mm/huge_memory.c:__pud_trans_huge_lock",
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582885825,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift",
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582924146,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582943545,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582949769,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_clean_pud_entry",
        "mm/mapping_dirty_helpers.c:wp_clean_pud_entry",
        "mm/mapping_dirty_helpers.c:wp_clean_pud_entry",
        "mm/mapping_dirty_helpers.c:wp_clean_pud_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582950598,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pud_entry",
        "mm/ptdump.c:ptdump_pud_entry",
        "mm/ptdump.c:ptdump_pud_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583431833,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593800753,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code",
        "arch/x86/power/hibernate.c:relocate_restore_code",
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593803345,
      "name": "pud_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579046560,
      "name": "pud_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579532672,
      "name": "pud_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071582239232,
      "name": "pud_val",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
pudval_t pud_val(pud_t pud)
```

```json
{
  "name": "pud_val",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627491599,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627536879,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_pud_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579113166,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579200038,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579270880,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579547444,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579642715,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
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
      "addr": 18446744071579645413,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627717455,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579663545,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579676808,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579698269,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/hugetlbpage.c:pud_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579716543,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579718843,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582234210,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size",
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582514898,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:walk_pud_range",
        "mm/vmscan.c:walk_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627852008,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582722652,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_p4d_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582770144,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_pud_range",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:copy_p4d_range"
      ],
      "caller_func": [
        "mm/memory.c:follow_pte",
        "mm/memory.c:follow_pte",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_pmd_range",
        "mm/memory.c:apply_to_pmd_range",
        "mm/memory.c:walk_to_pmd",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ]
    },
    {
      "addr": 18446744071582838834,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582845353,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
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
      "addr": 18446744071582853679,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582856885,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582861285,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582871639,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582900297,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vunmap_p4d_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583037582,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583095800,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
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
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
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
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
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
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583304401,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:__pud_trans_huge_lock",
        "mm/huge_memory.c:__pud_trans_huge_lock",
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583435230,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583479702,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583500424,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583507014,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_clean_pud_entry",
        "mm/mapping_dirty_helpers.c:wp_clean_pud_entry",
        "mm/mapping_dirty_helpers.c:wp_clean_pud_entry",
        "mm/mapping_dirty_helpers.c:wp_clean_pud_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583507926,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pud_entry",
        "mm/ptdump.c:ptdump_pud_entry",
        "mm/ptdump.c:ptdump_pud_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584019843,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595746514,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:477",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code",
        "arch/x86/power/hibernate.c:relocate_restore_code",
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582730096,
      "name": "pud_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
pudval_t pud_val(pud_t pud)
```

```json
{
  "name": "pud_val",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619235727,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619282863,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_pud_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579113486,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579204085,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579277200,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579562740,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579656763,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
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
      "addr": 18446744071579659829,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619474927,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579677689,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579690680,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579712125,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/hugetlbpage.c:pud_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579730127,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579732429,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582437440,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size",
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582716862,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:walk_pud_range",
        "mm/vmscan.c:walk_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619628904,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582938526,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_p4d_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582992274,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_pud_range",
        "mm/memory.c:remap_p4d_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": [
        "mm/memory.c:follow_pte",
        "mm/memory.c:follow_pte",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_pmd_range",
        "mm/memory.c:apply_to_pmd_range",
        "mm/memory.c:walk_to_pmd",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pud_range"
      ]
    },
    {
      "addr": 18446744071583053574,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583060937,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
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
      "addr": 18446744071583070063,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583072521,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583076789,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583088474,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583115433,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vunmap_p4d_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583245702,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583305643,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
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
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
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
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
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
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583523722,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:__pud_trans_huge_lock",
        "mm/huge_memory.c:__pud_trans_huge_lock",
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583650225,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583696281,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583716844,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583721929,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_clean_pud_entry",
        "mm/mapping_dirty_helpers.c:wp_clean_pud_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583722806,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pud_entry",
        "mm/ptdump.c:ptdump_pud_entry",
        "mm/ptdump.c:ptdump_pud_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584238922,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596270802,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code",
        "arch/x86/power/hibernate.c:relocate_restore_code",
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582946288,
      "name": "pud_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
pudval_t pud_val(pud_t pud)
```

```json
{
  "name": "pud_val",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621525807,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621575295,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_pud_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579139294,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579233429,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579307216,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579590276,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579690635,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579693813,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621771407,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579711817,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579725208,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:populate_pmd",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:unmap_pmd_range",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579746829,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/hugetlbpage.c:pud_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579765071,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579767373,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582605952,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size",
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582886206,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:walk_pud_range",
        "mm/vmscan.c:walk_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621932921,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583113784,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:get_gate_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583174293,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_pud_range",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": [
        "mm/memory.c:follow_pte",
        "mm/memory.c:follow_pte",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_pmd_range",
        "mm/memory.c:apply_to_pmd_range",
        "mm/memory.c:walk_to_pmd",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pud_range"
      ]
    },
    {
      "addr": 18446744071583235206,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583242460,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583251965,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583254569,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583259045,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583270906,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583298329,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vunmap_p4d_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583480230,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583543515,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
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
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
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
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583718454,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:__pud_trans_huge_lock",
        "mm/huge_memory.c:__pud_trans_huge_lock",
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583845149,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583890489,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583917484,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583922377,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_clean_pud_entry",
        "mm/mapping_dirty_helpers.c:wp_clean_pud_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583923510,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pud_entry",
        "mm/ptdump.c:ptdump_pud_entry",
        "mm/ptdump.c:ptdump_pud_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584451035,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071597155538,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:471",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code",
        "arch/x86/power/hibernate.c:relocate_restore_code",
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583121616,
      "name": "pud_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
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
  "name": "pud_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282719344,
      "name": "pud_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:40",
      "file": "arch/powerpc/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/pgtable.c:__find_linux_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282724744,
      "name": "pud_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:40",
      "file": "arch/powerpc/mm/pgtable_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/pgtable_64.c:pud_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282734952,
      "name": "pud_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:40",
      "file": "arch/powerpc/mm/book3s64/hash_pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/hash_pgtable.c:hash__map_kernel_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282776364,
      "name": "pud_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:40",
      "file": "arch/powerpc/mm/book3s64/radix_pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/radix_pgtable.c:pud_free_pmd_page",
        "arch/powerpc/mm/book3s64/radix_pgtable.c:remove_pagetable",
        "arch/powerpc/mm/book3s64/radix_pgtable.c:__map_kernel_page",
        "arch/powerpc/mm/book3s64/radix_pgtable.c:__map_kernel_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282817240,
      "name": "pud_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:40",
      "file": "arch/powerpc/mm/book3s64/subpage_prot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/subpage_prot.c:hpte_flush_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282842816,
      "name": "pud_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:40",
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
      "addr": 13835058055283266644,
      "name": "pud_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:40",
      "file": "arch/powerpc/xmon/xmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/xmon/xmon.c:show_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286057064,
      "name": "pud_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:40",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:follow_page_mask",
        "mm/gup.c:follow_page_mask",
        "mm/gup.c:follow_pmd_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286075260,
      "name": "pud_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:40",
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
      "addr": 13835058055286169528,
      "name": "pud_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:40",
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
      "addr": 13835058055286176876,
      "name": "pud_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:40",
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
      "addr": 13835058055286183824,
      "name": "pud_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:40",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286187892,
      "name": "pud_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:40",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286191320,
      "name": "pud_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:40",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286196084,
      "name": "pud_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:40",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286209192,
      "name": "pud_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:40",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_page_range_noflush",
        "mm/vmalloc.c:vunmap_page_range",
        "mm/vmalloc.c:vunmap_page_range",
        "mm/vmalloc.c:vunmap_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286345560,
      "name": "pud_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:40",
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
      "addr": 13835058055297817760,
      "name": "pud_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:40",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286564700,
      "name": "pud_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:40",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286629280,
      "name": "pud_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:40",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286745684,
      "name": "pud_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:40",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286793200,
      "name": "pud_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:40",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287413036,
      "name": "pud_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:40",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297671380,
      "name": "pud_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:40",
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
  "name": "pud_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604590190,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604620371,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:pud_large"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579019716,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076788,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604652038,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579298045,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579361720,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:pud_same",
        "arch/x86/mm/init_64.c:pud_same"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579363897,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604722698,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579381958,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:__split_large_page",
        "arch/x86/mm/pageattr.c:lookup_pmd_address",
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397853,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579405285,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/hugetlbpage.c:pud_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579408013,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level",
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579425103,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604732902,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581276143,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581292026,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581363097,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581367511,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581375339,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581378813,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range",
        "mm/pagewalk.c:walk_pgd_range",
        "mm/pagewalk.c:walk_pgd_range",
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581379845,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581384134,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581392625,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581481434,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581520841,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589781531,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581627950,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581667394,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:__pud_trans_huge_lock",
        "mm/huge_memory.c:__pud_trans_huge_lock",
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581740866,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift",
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581771091,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581789896,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582198506,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587935136,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code",
        "arch/x86/power/hibernate.c:relocate_restore_code",
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589652971,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
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
  "name": "pud_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604668014,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604698186,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:pud_large"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579019300,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076372,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604729801,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579299245,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579361640,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:pud_same",
        "arch/x86/mm/init_64.c:pud_same"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579363817,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604800265,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579381878,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:__split_large_page",
        "arch/x86/mm/pageattr.c:lookup_pmd_address",
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397773,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579405205,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/hugetlbpage.c:pud_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579407933,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level",
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579425023,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604810469,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581267343,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581283226,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581354297,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581358711,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581366539,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581370013,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range",
        "mm/pagewalk.c:walk_pgd_range",
        "mm/pagewalk.c:walk_pgd_range",
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581371045,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581375334,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581383825,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581472746,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581512153,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590224939,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581619262,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581658706,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:__pud_trans_huge_lock",
        "mm/huge_memory.c:__pud_trans_huge_lock",
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581732178,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift",
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581762403,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581781208,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582188986,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588266912,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code",
        "arch/x86/power/hibernate.c:relocate_restore_code",
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590096347,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
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
  "name": "pud_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604668019,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604698192,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:pud_large"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579022868,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579080468,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604729847,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579308077,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579370072,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:pud_same",
        "arch/x86/mm/init_64.c:pud_same"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579372249,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604812884,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579391037,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:__split_large_page",
        "arch/x86/mm/pageattr.c:lookup_pmd_address",
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579406269,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pud_clear_huge",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags",
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579414069,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/hugetlbpage.c:pud_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579416797,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level",
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579434207,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604823179,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581331199,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581347242,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581418242,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581422617,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581430433,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581433892,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range",
        "mm/pagewalk.c:walk_pgd_range",
        "mm/pagewalk.c:walk_pgd_range",
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581434933,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pud_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581439190,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581447841,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581537573,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581577209,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590275297,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581682542,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581725090,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:__pud_trans_huge_lock",
        "mm/huge_memory.c:__pud_trans_huge_lock",
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581800466,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift",
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581831283,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581850216,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582265096,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588402080,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code",
        "arch/x86/power/hibernate.c:relocate_restore_code",
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590146603,
      "name": "pud_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:508",
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
pudval_t pud_val(pud_t pud)
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
