# Function: <code>pud_page_vaddr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int pud_page_vaddr(pud_t pud)
```

```json
{
  "name": "pud_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578969709,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:591",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:__xen_pgd_walk",
        "arch/x86/xen/mmu.c:xen_pagetable_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579059900,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:591",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595008864,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:591",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579220738,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:591",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579274320,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:591",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:vmemmap_populate"
      ]
    },
    {
      "addr": 18446744071579280068,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:591",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595064818,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:591",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579288992,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:591",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:lookup_address_in_pgd",
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579310242,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:591",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580657784,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:591",
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
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:591",
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
      "addr": 18446744071580714377,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:591",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580718087,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:591",
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
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:591",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580730873,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:591",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580745316,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:591",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580762642,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:591",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580800816,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:591",
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
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:591",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580905339,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:591",
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
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:591",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581314929,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:591",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582953764,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:591",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579274320,
      "name": "pud_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int pud_page_vaddr(pud_t pud)
```

```json
{
  "name": "pud_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595141948,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579056263,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595173436,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579220971,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579277895,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
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
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pmd"
      ]
    },
    {
      "addr": 18446744071579279150,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
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
      "addr": 18446744071595230521,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579289834,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:lookup_pmd_address",
        "arch/x86/mm/pageattr.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579311043,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579320559,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580768245,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
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
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
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
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580833775,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
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
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
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
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580864602,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580885203,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580924437,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
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
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581034397,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581126752,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581481783,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583241496,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586580575,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579273536,
      "name": "pud_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int pud_page_vaddr(pud_t pud)
```

```json
{
  "name": "pud_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595384618,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579055284,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595415816,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579233125,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579293211,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
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
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pmd"
      ]
    },
    {
      "addr": 18446744071579294414,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
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
      "addr": 18446744071595473578,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579305258,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:lookup_pmd_address",
        "arch/x86/mm/pageattr.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579326259,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579335783,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580833781,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
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
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
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
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580899886,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
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
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580906570,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580912405,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
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
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580953286,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580992789,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
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
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581109597,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581201792,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581562665,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583356808,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586765247,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579288976,
      "name": "pud_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int pud_page_vaddr(pud_t pud)
```

```json
{
  "name": "pud_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596305764,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:767",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579047543,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:767",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596334930,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:767",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579230724,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:767",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579290717,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:767",
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
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pmd"
      ]
    },
    {
      "addr": 18446744071579293692,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:767",
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
      "addr": 18446744071596395116,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:767",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579302871,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:767",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329876,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:767",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580879142,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:767",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages_fast",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580883674,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:767",
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
      "addr": 18446744071580940173,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:767",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580944387,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:767",
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
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:767",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580951541,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:767",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580957420,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:767",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580964748,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:767",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580998522,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:767",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581040277,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:767",
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
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:767",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581157965,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:767",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581249236,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:767",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581618274,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:767",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586888620,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:767",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588205625,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:767",
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
      "addr": 18446744071579285920,
      "name": "pud_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int pud_page_vaddr(pud_t pud)
```

```json
{
  "name": "pud_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602594921,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:776",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602623663,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:776",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579056334,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:776",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602652258,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:776",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579246299,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:776",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579310272,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:776",
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
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pmd"
      ]
    },
    {
      "addr": 18446744071579312657,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:776",
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
      "addr": 18446744071602713811,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:776",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579324521,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:776",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579344621,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:776",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579355169,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:776",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579369999,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:776",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ]
    },
    {
      "addr": 18446744071580964106,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:776",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_pmd_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580977221,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:776",
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
      "addr": 18446744071581040079,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:776",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581044678,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:776",
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
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:776",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581053695,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:776",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581059065,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:776",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581071198,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:776",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581109643,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:776",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581150336,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:776",
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
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:776",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581245352,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:776",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581287482,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:776",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581380947,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:776",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581762699,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:776",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587377499,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:776",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588754791,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:776",
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
      "addr": 18446744071579304608,
      "name": "pud_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071579369999,
      "name": "pud_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
long unsigned int pud_page_vaddr(pud_t pud)
```

```json
{
  "name": "pud_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602763259,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602792429,
      "name": "pud_page_vaddr",
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
      "addr": 18446744071579061316,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602822115,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579258756,
      "name": "pud_page_vaddr",
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
      "addr": 18446744071579321735,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
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
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pmd"
      ]
    },
    {
      "addr": 18446744071579325032,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
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
      "addr": 18446744071602886460,
      "name": "pud_page_vaddr",
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
      "addr": 18446744071579335373,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579355962,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579366603,
      "name": "pud_page_vaddr",
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
      "addr": 18446744071579382873,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602897713,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581100437,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581112457,
      "name": "pud_page_vaddr",
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
      "addr": 18446744071581178731,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581182357,
      "name": "pud_page_vaddr",
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
      "addr": 18446744071581189742,
      "name": "pud_page_vaddr",
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
      "addr": 18446744071581192317,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581197782,
      "name": "pud_page_vaddr",
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
      "addr": 18446744071581208289,
      "name": "pud_page_vaddr",
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
      "addr": 18446744071581245579,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581293766,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
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
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581396764,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581434527,
      "name": "pud_page_vaddr",
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
      "addr": 18446744071581502162,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:818",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581530948,
      "name": "pud_page_vaddr",
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
      "addr": 18446744071581931535,
      "name": "pud_page_vaddr",
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
      "addr": 18446744071587681342,
      "name": "pud_page_vaddr",
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
      "addr": 18446744071589132812,
      "name": "pud_page_vaddr",
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
  "symbols": [
    {
      "addr": 18446744071579316800,
      "name": "pud_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071581109744,
      "name": "pud_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
long unsigned int pud_page_vaddr(pud_t pud)
```

```json
{
  "name": "pud_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604557352,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:843",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604586294,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:843",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579065892,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:843",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604617259,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:843",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579282420,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:843",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579346039,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:843",
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
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pmd"
      ]
    },
    {
      "addr": 18446744071579349096,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:843",
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
      "addr": 18446744071604683470,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:843",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579361917,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:843",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579383165,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:843",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579394237,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:843",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579410443,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:843",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604695097,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:843",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581178485,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:843",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581191577,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:843",
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
      "addr": 18446744071581258890,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:843",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581264793,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:843",
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
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:843",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581275456,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:843",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581281126,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:843",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581289457,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:843",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581329099,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:843",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581376790,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:843",
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
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:843",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581480396,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:843",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581518047,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:843",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581587413,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:843",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581616740,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:843",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582015951,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:843",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587820563,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:843",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589367521,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:843",
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
      "addr": 18446744071579341536,
      "name": "pud_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
long unsigned int pud_page_vaddr(pud_t pud)
```

```json
{
  "name": "pud_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604651686,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604681687,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579074436,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604713433,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579296685,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579361722,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
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
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pmd"
      ]
    },
    {
      "addr": 18446744071579363793,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
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
      "addr": 18446744071604782989,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579376519,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579398637,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579409158,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579426233,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604795122,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581248687,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581264393,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
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
      "addr": 18446744071581334665,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581339374,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
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
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581349898,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581355750,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581364129,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581448474,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581487689,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
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
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581627842,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581698727,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581728803,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581748719,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582152490,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588123667,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589824491,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
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
      "addr": 18446744071579356912,
      "name": "pud_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
long unsigned int pud_page_vaddr(pud_t pud)
```

```json
{
  "name": "pud_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604663958,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604694129,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076436,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604725735,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579302237,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579365962,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
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
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pmd"
      ]
    },
    {
      "addr": 18446744071579368033,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
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
      "addr": 18446744071604808756,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579380807,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579401949,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579412342,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579429401,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604820862,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581307295,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581323178,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
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
      "addr": 18446744071581394249,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581398663,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
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
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581408531,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581415286,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423777,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581512698,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581552105,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
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
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581659214,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581698658,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581772167,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581802355,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581820831,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582229770,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588328467,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590050715,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
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
      "addr": 18446744071579361152,
      "name": "pud_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
long unsigned int pud_page_vaddr(pud_t pud)
```

```json
{
  "name": "pud_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609015170,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:869",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609044938,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:869",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud",
        "arch/x86/xen/mmu_pv.c:xen_pud_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579086878,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:869",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579138645,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:869",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579332199,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:869",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579393207,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:869",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:fill_pmd"
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
      "addr": 18446744071579397192,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:869",
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
      "addr": 18446744071609147376,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:869",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579411325,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:869",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579419487,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:869",
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
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579454825,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:869",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579456209,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:869",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581504271,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:869",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:get_gate_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581521361,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:869",
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
      "addr": 18446744071581592150,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:869",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581596570,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:869",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581605328,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:869",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581607439,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:869",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581616457,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:869",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581627055,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:869",
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
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:869",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581762545,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:869",
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
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:869",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581880550,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:869",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581914644,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:869",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581992895,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:869",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582023009,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:869",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582458702,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:869",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585045131,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:869",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591150640,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:869",
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
      "addr": 18446744071579387312,
      "name": "pud_page_vaddr",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int pud_page_vaddr(pud_t pud)
```

```json
{
  "name": "pud_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612077174,
      "name": "pud_page_vaddr",
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
      "addr": 18446744071612108294,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud",
        "arch/x86/xen/mmu_pv.c:xen_pud_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579088942,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591251163,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579333783,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397461,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
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
      "addr": 18446744071579403560,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612217718,
      "name": "pud_page_vaddr",
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
      "addr": 18446744071579411949,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579420159,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
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
      "addr": 18446744071579451689,
      "name": "pud_page_vaddr",
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
      "addr": 18446744071591273280,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581190946,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581544431,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:get_gate_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581596290,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
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
      "addr": 18446744071581638166,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581645360,
      "name": "pud_page_vaddr",
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
      "addr": 18446744071581652477,
      "name": "pud_page_vaddr",
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
      "addr": 18446744071581654863,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581663449,
      "name": "pud_page_vaddr",
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
      "addr": 18446744071581672751,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
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
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ioremap.c:ioremap_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581767929,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581810625,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
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
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581926569,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581961524,
      "name": "pud_page_vaddr",
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
      "addr": 18446744071582042463,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582071441,
      "name": "pud_page_vaddr",
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
      "addr": 18446744071582515614,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591236624,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
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
      "addr": 18446744071579392656,
      "name": "pud_page_vaddr",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int pud_page_vaddr(pud_t pud)
```

```json
{
  "name": "pud_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614215681,
      "name": "pud_page_vaddr",
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
      "addr": 18446744071614247778,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud",
        "arch/x86/xen/mmu_pv.c:xen_pud_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579095501,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591194916,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579336479,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579400711,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
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
      "addr": 18446744071579406759,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614358896,
      "name": "pud_page_vaddr",
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
      "addr": 18446744071579415101,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579422753,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
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
      "addr": 18446744071579454155,
      "name": "pud_page_vaddr",
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
      "addr": 18446744071591216232,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581220407,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581575092,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:get_gate_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581618931,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_invalidate_pte",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:apply_to_pmd_range",
        "mm/memory.c:apply_to_pmd_range",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_pmd_range",
        "mm/memory.c:copy_pmd_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581659797,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581666859,
      "name": "pud_page_vaddr",
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
      "addr": 18446744071581673455,
      "name": "pud_page_vaddr",
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
      "addr": 18446744071581676351,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581685453,
      "name": "pud_page_vaddr",
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
      "addr": 18446744071581699171,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581795687,
      "name": "pud_page_vaddr",
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
      "addr": 18446744071581839014,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
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
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581951936,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581987455,
      "name": "pud_page_vaddr",
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
      "addr": 18446744071582068943,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582096444,
      "name": "pud_page_vaddr",
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
      "addr": 18446744071582545183,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591179290,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:868",
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
      "addr": 18446744071579396256,
      "name": "pud_page_vaddr",
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
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "pud_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271359486,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable-64.h:56",
      "file": "arch/riscv/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/mm/fault.c:do_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272714264,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable-64.h:56",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272721430,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable-64.h:56",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
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
      "addr": 18446743936272765156,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable-64.h:56",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272767684,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable-64.h:56",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272770800,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable-64.h:56",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272771560,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable-64.h:56",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272775008,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable-64.h:56",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272781824,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable-64.h:56",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272853252,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable-64.h:56",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272890864,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable-64.h:56",
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
      "addr": 18446743936270897150,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable-64.h:56",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273021522,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable-64.h:56",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273385334,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable-64.h:56",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279720192,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable-64.h:56",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int pud_page_vaddr(pud_t pud)
```

```json
{
  "name": "pud_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604590230,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604620410,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076788,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604652038,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579298045,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579361866,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
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
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pmd"
      ]
    },
    {
      "addr": 18446744071579363937,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
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
      "addr": 18446744071604722698,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579376711,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397853,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579408182,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579425241,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604734742,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581276143,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581292026,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
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
      "addr": 18446744071581363097,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581367511,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
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
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581377379,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581384134,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581392625,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581481434,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581520841,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
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
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581627950,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581667394,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581740903,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581771091,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581789567,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582198506,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587935251,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589652971,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
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
      "addr": 18446744071579357056,
      "name": "pud_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
  "name": "pud_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604581866,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579009631,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604619731,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579234016,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579292809,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:fill_pmd",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579295235,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
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
      "addr": 18446744071604690585,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579306178,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:lookup_pmd_address",
        "arch/x86/mm/pageattr.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579327270,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579337887,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579354224,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604702363,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581222622,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_pmd_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581236497,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
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
      "addr": 18446744071581305428,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581311001,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581318706,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581321252,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581326920,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581335310,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423737,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581462928,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
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
      "addr": 18446744071589504306,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581569163,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581606970,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581679690,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581709720,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581727265,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582135431,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587648448,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589378773,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
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
long unsigned int pud_page_vaddr(pud_t pud)
```

```json
{
  "name": "pud_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604668054,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604698225,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076372,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604729801,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579299245,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579361786,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
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
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pmd"
      ]
    },
    {
      "addr": 18446744071579363857,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
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
      "addr": 18446744071604800265,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579376631,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397773,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579408102,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579425161,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604812309,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581267343,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581283226,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
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
      "addr": 18446744071581354297,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581358711,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
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
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581368579,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581375334,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581383825,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581472746,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581512153,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
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
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581619262,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581658706,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581732215,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581762403,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581780879,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582188986,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588267027,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590096347,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
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
      "addr": 18446744071579356976,
      "name": "pud_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
long unsigned int pud_page_vaddr(pud_t pud)
```

```json
{
  "name": "pud_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604668059,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604698231,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579080468,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604729847,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579308077,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579370218,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
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
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pmd"
      ]
    },
    {
      "addr": 18446744071579372289,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
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
      "addr": 18446744071604812884,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579385111,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579406269,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_free_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579416966,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579434345,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604825019,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581331199,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581347242,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
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
      "addr": 18446744071581418242,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581422617,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
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
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581432451,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581439190,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581447841,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581537573,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581577209,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
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
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581682542,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581725090,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581800503,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581831283,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581849887,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582265096,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588402195,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590146603,
      "name": "pud_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:860",
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
      "addr": 18446744071579365408,
      "name": "pud_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
long unsigned int pud_page_vaddr(pud_t pud)
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
long unsigned int pud_page_vaddr(pud_t pud)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int pud_page_vaddr(pud_t pud)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long unsigned int pud_page_vaddr(pud_t pud)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int pud_page_vaddr(pud_t pud)
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
long unsigned int pud_page_vaddr(pud_t pud)
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
