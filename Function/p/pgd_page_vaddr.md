# Function: <code>pgd_page_vaddr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578969432,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:632",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:632",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579220537,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:632",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579274385,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:632",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:sync_global_pgds",
        "arch/x86/mm/init_64.c:sync_global_pgds",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:set_pte_vaddr",
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579279951,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:632",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595064763,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:632",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579289693,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:632",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:632",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579310215,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:632",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580657626,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:632",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:632",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:632",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580717964,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:632",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:632",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580730796,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:632",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580745279,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:632",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580762580,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:632",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580800332,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:632",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:632",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580905229,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:632",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:632",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581314830,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:632",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582953727,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:632",
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
  "name": "pgd_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595141764,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579220772,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579277601,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pagetable",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579298844,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579311000,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579320410,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587851872,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579346224,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580768173,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580833654,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580864413,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580884777,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580924316,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581034283,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581126675,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581481689,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583241332,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586580474,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
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
  "name": "pgd_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595384434,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579232926,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579292929,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pagetable",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579314316,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579326216,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579335634,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588066633,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579362080,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580833709,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580899765,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580906381,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580912315,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580952857,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580992668,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pud_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581109483,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581201715,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581562571,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583356644,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586765146,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:669",
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
long unsigned int pgd_page_vaddr(pgd_t pgd)
```

```json
{
  "name": "pgd_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609015016,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:945",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609045397,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:945",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_p2m_free",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609059134,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:945",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579138493,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:945",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579331857,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:945",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579392658,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:945",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "caller_func": []
    },
    {
      "addr": 18446744071579397039,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:945",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:945",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579408565,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:945",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579413248,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:945",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:945",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:945",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579454342,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:945",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609158688,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:945",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579466330,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:945",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:945",
      "file": "arch/x86/platform/uv/bios_uv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_epilog"
      ]
    },
    {
      "addr": 18446744071581512351,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:945",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:945",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:945",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581596360,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:945",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581605181,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:945",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581608987,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:945",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581616320,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:945",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581626881,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:945",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:945",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581762399,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:945",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:945",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581868115,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:945",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:p4d_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581914501,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:945",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581992741,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:945",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582022877,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:945",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582458557,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:945",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585045879,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:945",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591150519,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:945",
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
      "addr": 18446744071579491087,
      "name": "pgd_page_vaddr",
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
long unsigned int pgd_page_vaddr(pgd_t pgd)
```

```json
{
  "name": "pgd_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612077020,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612108753,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_p2m_free",
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612122494,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591251011,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579333441,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579396950,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:set_pte_vaddr",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5"
      ]
    },
    {
      "addr": 18446744071579403407,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612217650,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579409029,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579421476,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579451206,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612229286,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579462686,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581552479,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581642584,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581652328,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581656379,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581663312,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581672577,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ioremap.c:ioremap_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581767544,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581810479,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
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
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581913027,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:p4d_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581961381,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582042309,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582071309,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582515469,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591236503,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
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
      "addr": 18446744071591267485,
      "name": "pgd_page_vaddr",
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
long unsigned int pgd_page_vaddr(pgd_t pgd)
```

```json
{
  "name": "pgd_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614215527,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579010485,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591190538,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591194619,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579335555,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591210135,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5"
      ]
    },
    {
      "addr": 18446744071579402339,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591212686,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579412309,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579420915,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591215834,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579453459,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071614370046,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614377667,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581198099,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581559363,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581583171,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581657043,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581664003,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581672067,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581675731,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581681283,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581697540,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_small_pages_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581795305,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581819763,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591635424,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581936883,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581964819,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582066835,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582096227,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582542451,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591178627,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:944",
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
      "addr": 18446744071591210135,
      "name": "pgd_page_vaddr",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int pgd_page_vaddr(pgd_t pgd)
```

```json
{
  "name": "pgd_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615134354,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:915",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579028677,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:915",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592054747,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:915",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592060384,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:915",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579390851,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:915",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592083839,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:915",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5"
      ]
    },
    {
      "addr": 18446744071579464675,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:915",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592086982,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:915",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579475157,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:915",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579484499,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:915",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592092443,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:915",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579518819,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:915",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071615302025,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:915",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615309926,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:915",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581438451,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:915",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581823635,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:915",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581848492,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:915",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581925235,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:915",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581932339,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:915",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581941363,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:915",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581944915,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:915",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581950563,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:915",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581969789,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:915",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_small_pages_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582079284,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:915",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582105987,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:915",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582170739,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:915",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582241251,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:915",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582267603,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:915",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582376707,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:915",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582411011,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:915",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582858499,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:915",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592034691,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:915",
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
      "addr": 18446744071592083839,
      "name": "pgd_page_vaddr",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int pgd_page_vaddr(pgd_t pgd)
```

```json
{
  "name": "pgd_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071616897674,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:913",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579048965,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:913",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593821589,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:913",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593826862,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:913",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579457203,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:913",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579533504,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:913",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5"
      ]
    },
    {
      "addr": 18446744071579541203,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:913",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593853798,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:913",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579552997,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:913",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579564163,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:913",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593859540,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:913",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579602931,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:913",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071617082294,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:913",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617090870,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:913",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581778083,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:913",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593969000,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:913",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582215715,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:913",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582240979,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:913",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582332035,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:913",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582340835,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:913",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582350627,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:913",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582354163,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:913",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582360211,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:913",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582392947,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:913",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_small_pages_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582518986,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:913",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582549875,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:913",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582628947,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:913",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582736931,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:913",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582745939,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:913",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582877875,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:913",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582923907,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:913",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583421107,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:913",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593800083,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:913",
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
      "addr": 18446744071579533504,
      "name": "pgd_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
  "name": "pgd_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627491499,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:931",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579079864,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:931",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071627560546,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:931",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579269924,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:931",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579546244,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:931",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627714957,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:931",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:preallocate_vmalloc_pages",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579645108,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:931",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579651972,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:931",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:931",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579672148,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:931",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579715748,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:931",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579715876,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:931",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071627737254,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:931",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627749310,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:931",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582202532,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:931",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582617956,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:931",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582722463,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:931",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582731433,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:931",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582832484,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:931",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582842420,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:931",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582852308,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:931",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582856084,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:931",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582862644,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:931",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582899220,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:931",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_small_pages_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583037206,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:931",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583066596,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:931",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583119556,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:931",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_remap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583153156,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:931",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583267362,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:931",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:p4d_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583425604,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:931",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583479428,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:931",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584009108,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:931",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595745764,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:931",
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
  "name": "pgd_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619235627,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579079672,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071619309874,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579276244,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579561540,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619472429,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:preallocate_vmalloc_pages",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579659524,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579666196,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579686052,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579729332,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579729460,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071619496466,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619508825,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582402580,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582826868,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582938253,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582947284,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583047876,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583058164,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583068260,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583071668,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583079284,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583114356,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_small_pages_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583246219,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583277108,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583329812,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_remap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583363588,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583487714,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:p4d_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583645988,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583696004,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584233524,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596270052,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
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
  "name": "pgd_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621525707,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1154",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579105448,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1154",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579232580,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1154",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579306052,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1154",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579589060,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1154",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621768909,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1154",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:preallocate_vmalloc_pages",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579693508,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1154",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579700196,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1154",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1154",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579720580,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1154",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579764276,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1154",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579764404,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1154",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071621793298,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1154",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621805657,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1154",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582570308,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1154",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583001316,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1154",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583092644,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1154",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583123444,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1154",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583229684,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1154",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583239876,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1154",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583250196,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1154",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583253652,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1154",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583261604,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1154",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583296724,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1154",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_small_pages_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583480747,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1154",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583514132,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1154",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583600068,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1154",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583681090,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1154",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:p4d_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583840564,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1154",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583890212,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1154",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584448084,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1154",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:p4d_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597154788,
      "name": "pgd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1154",
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
long unsigned int pgd_page_vaddr(pgd_t pgd)
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
long unsigned int pgd_page_vaddr(pgd_t pgd)
```
</details>
</li>
</ul>
