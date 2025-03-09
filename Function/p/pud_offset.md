# Function: <code>pud_offset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
pud_t * pud_offset(pgd_t * pgd, long unsigned int address)
```

```json
{
  "name": "pud_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578969432,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:649",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:__xen_pgd_walk",
        "arch/x86/xen/mmu.c:xen_pagetable_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595008806,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:649",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579220537,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:649",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579274384,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:649",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:populate_extra_pmd"
      ]
    },
    {
      "addr": 18446744071579279951,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:649",
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
      "addr": 18446744071595064763,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:649",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579289693,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:649",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pgd_range",
        "arch/x86/mm/pageattr.c:lookup_address_in_pgd",
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579310215,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:649",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580657626,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:649",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:649",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:649",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580717964,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:649",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:649",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580730796,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:649",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580745279,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:649",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580762580,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:649",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580800332,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:649",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:649",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580905229,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:649",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:649",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581314830,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:649",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582953727,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:649",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579274384,
      "name": "pud_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
pud_t * pud_offset(pgd_t * pgd, long unsigned int address)
```

```json
{
  "name": "pud_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595141764,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595173275,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579220772,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579277601,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:populate_extra_pmd"
      ]
    },
    {
      "addr": 18446744071579279012,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
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
      "addr": 18446744071595230446,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579298844,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address",
        "arch/x86/mm/pageattr.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579311000,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579346224,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580768173,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580833654,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580864413,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580884777,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580924316,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581034283,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581126675,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581481689,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583241332,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586580467,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
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
      "addr": 18446744071579273600,
      "name": "pud_offset",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
pud_t * pud_offset(pgd_t * pgd, long unsigned int address)
```

```json
{
  "name": "pud_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595384434,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595415655,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579232926,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579292929,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:populate_extra_pmd"
      ]
    },
    {
      "addr": 18446744071579294276,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
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
      "addr": 18446744071595473503,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579314316,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address",
        "arch/x86/mm/pageattr.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579326216,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579362080,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580833709,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580899765,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580906381,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580912315,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580952857,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580992668,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581109483,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581201715,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581562571,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583356644,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586765139,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:686",
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
      "addr": 18446744071579289040,
      "name": "pud_offset",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
pud_t * pud_offset(p4d_t * p4d, long unsigned int address)
```

```json
{
  "name": "pud_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596305747,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:831",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:831",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579230528,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:831",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579290534,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:831",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ]
    },
    {
      "addr": 18446744071579293556,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:831",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:831",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579311690,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:831",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579360735,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:831",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog"
      ]
    },
    {
      "addr": 18446744071580879122,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:831",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:831",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:831",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580944255,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:831",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:831",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580951507,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:831",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580957329,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:831",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580964624,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:831",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580998291,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:831",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581040156,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:831",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:831",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581157852,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:831",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581249166,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:831",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581618180,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:831",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586888432,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:831",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588205465,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:831",
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
      "addr": 18446744071579285984,
      "name": "pud_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579360735,
      "name": "pud_offset",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602594826,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602623639,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579246098,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579310079,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579312518,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579334274,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602722626,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602732977,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580963940,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581044544,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581052914,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581058975,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581071072,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581109389,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581150165,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581245258,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581287367,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581380864,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581762596,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587377283,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588754501,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
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
  "name": "pud_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602763177,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602792304,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579258558,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321527,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579324884,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579345110,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579382691,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602897258,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579395177,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581100287,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581182229,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581191756,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581197683,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581208156,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581245347,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581293612,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581396680,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581434423,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581501929,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581530878,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581930850,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587681133,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589132643,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:880",
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
  "name": "pud_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604557270,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:905",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604586169,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:905",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:905",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579282222,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:905",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579345831,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:905",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579348948,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:905",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:905",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579371702,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:905",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579381315,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:905",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pgd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579410260,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:905",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604694642,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:905",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579423481,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:905",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581178293,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:905",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:905",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:905",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581264664,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:905",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:905",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581274879,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:905",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581281027,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:905",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581289324,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:905",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581328867,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:905",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581376636,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:905",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:905",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581480312,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:905",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581517943,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:905",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581587177,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:905",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581616670,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:905",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582015266,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:905",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587820358,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:905",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589367247,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:905",
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
  "name": "pud_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604651604,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604681574,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579296487,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579361511,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579363673,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579386806,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579396735,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pgd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589941403,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579426051,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604794666,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579439527,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581248485,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581339245,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581349343,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581355651,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581363996,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581448262,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581487538,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581627738,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581698611,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581728733,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582151861,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588123462,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589824163,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
  "name": "pud_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604663876,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604694016,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579302039,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579365751,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579367913,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579390198,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579400047,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pgd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590168955,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579429219,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604820389,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579442919,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581307093,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581398534,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581409449,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581415187,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423644,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581512486,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581551954,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581659130,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581698554,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581772051,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581802285,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582229141,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588328262,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590050387,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071609015095,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609045070,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579138542,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579331993,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579392753,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_p4d_table",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:ident_p4d_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397078,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579408599,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579420290,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579454643,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609158789,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579466554,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
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
      "addr": 18446744071609172932,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "arch/x86/platform/uv/bios_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_prolog",
        "arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_prolog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581504199,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:get_gate_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581521233,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581596451,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581605224,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581608300,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581616363,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581626927,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581762442,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581880468,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581914540,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581992780,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582022937,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582458596,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585044823,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591150556,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071612077099,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612108426,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591251060,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579333577,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397046,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:preallocate_vmalloc_pages",
        "arch/x86/mm/init_64.c:remove_p4d_table",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:ident_p4d_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579403446,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579409063,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579421752,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579451507,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612229387,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579462910,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
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
      "addr": 18446744071581190811,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581544359,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:get_gate_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581596162,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581642671,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581652371,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581655724,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581663355,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581672623,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ioremap.c:ioremap_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581767744,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581810522,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581926487,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581961420,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582042348,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582071369,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582515508,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591236540,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614215606,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614248111,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579336279,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579400296,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:preallocate_vmalloc_pages",
        "arch/x86/mm/init_64.c:remove_p4d_table",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:ident_p4d_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579406650,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579413134,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pgd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579424810,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579453972,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614370143,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579465111,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
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
      "addr": 18446744071581220272,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581574913,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581664237,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581673315,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581677215,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581685359,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581699007,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581838911,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581951855,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581987358,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582068828,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582096374,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582545085,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591179199,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:97",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615134433,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:116",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615168233,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:116",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592060619,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:116",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579391590,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:116",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579462608,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:116",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:preallocate_vmalloc_pages",
        "arch/x86/mm/init_64.c:remove_p4d_table",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:ident_p4d_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579469203,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:116",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615289376,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:116",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579475995,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:116",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pgd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579488435,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:116",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:116",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579519364,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:116",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615302120,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:116",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579530577,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:116",
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
      "addr": 18446744071581460259,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:116",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581839554,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:116",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:116",
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
        "mm/memory.c:free_pud_range",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581929176,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:116",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581932591,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:116",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581942671,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:116",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581946412,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:116",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581954817,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:116",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581970801,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:116",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:116",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582129781,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:116",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:116",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:116",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582289443,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:116",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582382896,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:116",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582411171,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:116",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582861203,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:116",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592035286,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:116",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071616897753,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616934279,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593827125,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579458100,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579539085,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:preallocate_vmalloc_pages",
        "arch/x86/mm/init_64.c:remove_p4d_table",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:ident_p4d_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579546095,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617068751,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579553989,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pgd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579568444,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579603488,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617082385,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579617487,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
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
      "addr": 18446744071581807508,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617165681,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582231664,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582352257,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582355698,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582370076,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582393974,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582576801,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
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
      "addr": 18446744071594711429,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:__populate_section_memmap",
        "mm/sparse-vmemmap.c:vmemmap_pud_populate",
        "mm/sparse-vmemmap.c:vmemmap_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582743705,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582773909,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582885741,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582924083,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583431743,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593800707,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627491566,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627539609,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579270813,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579547257,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579642515,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:preallocate_vmalloc_pages",
        "arch/x86/mm/init_64.c:remove_p4d_table",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:ident_p4d_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579645330,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627717418,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579676684,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579716498,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627737310,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579729537,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582514633,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:walk_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627851901,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582722570,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582853555,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582857686,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582871548,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582900236,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583095703,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583435151,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583479635,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584019752,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595746467,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:117",
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
  "name": "pud_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619235694,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:125",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619285785,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:125",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579277133,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:125",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579562553,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:125",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579656563,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:125",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:preallocate_vmalloc_pages",
        "arch/x86/mm/init_64.c:remove_p4d_table",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:ident_p4d_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579659746,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:125",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619474890,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:125",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579690556,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:125",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:125",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579730082,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:125",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619496608,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:125",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579776018,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:125",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:125",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582716637,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:125",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:walk_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619628797,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:125",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582938353,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:125",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:125",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:125",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:125",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583069939,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:125",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583073190,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:125",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583088383,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:125",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583115372,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:125",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:125",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583305546,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:125",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:125",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:125",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:125",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583650146,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:125",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583696214,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:125",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584238831,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:125",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596270755,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:125",
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
  "name": "pud_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621525774,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:129",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621578281,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:129",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579307149,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:129",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579590089,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:129",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579690435,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:129",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:preallocate_vmalloc_pages",
        "arch/x86/mm/init_64.c:remove_p4d_table",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:ident_p4d_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579693730,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:129",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621771370,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:129",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579725084,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:129",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:129",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579765026,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:129",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621793440,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:129",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579810914,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:129",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:129",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582885981,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:129",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:walk_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621932814,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:129",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583113590,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:129",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:129",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:129",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:129",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583251841,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:129",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583255238,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:129",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583270815,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:129",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583298268,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:129",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:129",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583543418,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:129",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:129",
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
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:129",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583845066,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:129",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583890422,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:129",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584450944,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:129",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071597155491,
      "name": "pud_offset",
      "external": false,
      "loc": "include/linux/pgtable.h:129",
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "pud_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pud_offset",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d-hack.h:41",
      "file": "arch/arm/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_offset",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d-hack.h:41",
      "file": "arch/arm/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_offset",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d-hack.h:41",
      "file": "arch/arm/mm/dma-mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_offset",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d-hack.h:41",
      "file": "arch/arm/mm/idmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_offset",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d-hack.h:41",
      "file": "arch/arm/mm/pgd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_offset",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d-hack.h:41",
      "file": "arch/arm/mm/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_offset",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d-hack.h:41",
      "file": "arch/arm/mm/dump.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_offset",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d-hack.h:41",
      "file": "arch/arm/mm/highmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_offset",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d-hack.h:41",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_offset",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d-hack.h:41",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_offset",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d-hack.h:41",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_offset",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d-hack.h:41",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_offset",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d-hack.h:41",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_offset",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d-hack.h:41",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_offset",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d-hack.h:41",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_offset",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d-hack.h:41",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_offset",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d-hack.h:41",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_offset",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d-hack.h:41",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_offset",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d-hack.h:41",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_offset",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d-hack.h:41",
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "pud_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pud_offset",
      "external": false,
      "loc": "include/asm-generic/pgtable-nopud.h:45",
      "file": "arch/riscv/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_offset",
      "external": false,
      "loc": "include/asm-generic/pgtable-nopud.h:45",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_offset",
      "external": false,
      "loc": "include/asm-generic/pgtable-nopud.h:45",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_offset",
      "external": false,
      "loc": "include/asm-generic/pgtable-nopud.h:45",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_offset",
      "external": false,
      "loc": "include/asm-generic/pgtable-nopud.h:45",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_offset",
      "external": false,
      "loc": "include/asm-generic/pgtable-nopud.h:45",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_offset",
      "external": false,
      "loc": "include/asm-generic/pgtable-nopud.h:45",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_offset",
      "external": false,
      "loc": "include/asm-generic/pgtable-nopud.h:45",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_offset",
      "external": false,
      "loc": "include/asm-generic/pgtable-nopud.h:45",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_offset",
      "external": false,
      "loc": "include/asm-generic/pgtable-nopud.h:45",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_offset",
      "external": false,
      "loc": "include/asm-generic/pgtable-nopud.h:45",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_offset",
      "external": false,
      "loc": "include/asm-generic/pgtable-nopud.h:45",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_offset",
      "external": false,
      "loc": "include/asm-generic/pgtable-nopud.h:45",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_offset",
      "external": false,
      "loc": "include/asm-generic/pgtable-nopud.h:45",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_offset",
      "external": false,
      "loc": "include/asm-generic/pgtable-nopud.h:45",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604590148,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604620297,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579297847,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579361655,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579363817,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579386102,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579395951,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pgd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589771243,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579425059,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604734269,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579438759,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581275941,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581367382,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581378297,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581384035,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581392492,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581481222,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581520690,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581627866,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581667290,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581740787,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581771021,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582197877,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587935046,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589652643,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604581818,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604619659,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579233950,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579292631,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579295132,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
      "addr": 18446744071604690495,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579307040,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589494064,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579354112,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604701890,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579367827,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581222421,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581310904,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581320687,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581326878,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581335193,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423554,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581462821,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581569066,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581606902,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581679612,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581709642,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582135375,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587648339,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589378446,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604667972,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604698112,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579299047,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579361575,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579363737,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579386022,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579395871,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pgd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590214651,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579424979,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604811836,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579438679,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581267141,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581358582,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581369497,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581375235,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581383692,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581472534,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581512002,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581619178,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581658602,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581732099,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581762333,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582188357,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588266822,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590096019,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
  "name": "pud_offset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604667977,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604698118,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579307879,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579370007,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579372169,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579394534,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579404383,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pgd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590265019,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579434163,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604824546,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579447879,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581330997,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581422488,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581433369,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581439091,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581447708,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581537361,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581577058,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581682458,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581724986,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581800387,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581831213,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582264476,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588401990,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590146275,
      "name": "pud_offset",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:922",
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>p4d_t * p4d</code>
</li>
<li>
<b>Param removed. </b>
<code>pgd_t * pgd</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
pud_t * pud_offset(p4d_t * p4d, long unsigned int address)
```
</details>
</li>
</ul>
