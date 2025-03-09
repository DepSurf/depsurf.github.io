# Function: <code>set_pte_at</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578967812,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:493",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578991899,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:493",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_map_shared",
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595008987,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:493",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579256532,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:493",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579358681,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:493",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595065331,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:493",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580448924,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:493",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580657464,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:493",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580665574,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:493",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:do_set_pte",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580715428,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:493",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580718763,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:493",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580724515,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:493",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580737745,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:493",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580763614,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:493",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580801742,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:493",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587361462,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:493",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580833138,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:493",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580880256,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:493",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580898714,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:493",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:__split_huge_page_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580973868,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:493",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mfill_zeropage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581437720,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:493",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582954151,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:493",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583920437,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:493",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578964724,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:466",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578988654,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:466",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_shared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595173617,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:466",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579255588,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:466",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579365566,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:466",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595231051,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:466",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580524212,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:466",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580765621,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:466",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580793245,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:466",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580830831,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:466",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580834410,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:466",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580845707,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:466",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580855415,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:466",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580872519,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:466",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580886123,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:466",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580927290,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:466",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587862886,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:466",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580958790,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:466",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581007850,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:466",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581033293,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:466",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581050124,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:466",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581128926,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:466",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581620640,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:466",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583241774,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:466",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584251642,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:466",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
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
  "name": "set_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578966548,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578990526,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_shared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595415997,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579269108,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579383668,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595474108,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580587550,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580831220,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580857651,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580896406,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580900525,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580915637,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580925668,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580940457,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580954210,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580995626,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588077592,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581033068,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581081874,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581108477,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581133070,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581203993,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581580034,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581709032,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583357086,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584433255,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
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
  "name": "set_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578956958,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_shared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578975476,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596335111,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579265732,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579291358,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596395657,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580617501,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580798959,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580873666,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580901181,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580941284,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580945051,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580960159,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580969744,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580984630,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580999404,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581044524,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588304045,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581079470,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581130651,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581147002,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581173178,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581252862,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581641080,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_writeback_mapping_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581755675,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584518054,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588205908,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:465",
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
  "name": "set_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578960135,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_status",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_shared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578978644,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579049459,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602652514,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579282500,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579311101,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602714725,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580698237,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580872543,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580968221,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580998195,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581041303,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581045983,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581062521,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581072226,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581087629,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581110622,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581155010,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588869359,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581190849,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581251409,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581281533,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581309604,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581384868,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581786701,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_writeback_mapping_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581912638,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584928086,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588755081,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
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
  "name": "set_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578962711,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_status",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_shared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578981376,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579054240,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602822326,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579293952,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579322621,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602887412,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579369123,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580830703,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581006421,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581099999,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581132238,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581176903,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581183403,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581201789,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581207772,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581230488,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581246579,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581298473,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589248413,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581336455,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581394034,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581430060,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581451299,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581534969,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581960199,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_writeback_mapping_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582094394,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585159351,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589133107,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:451",
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
  "name": "set_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578960807,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_status",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_shared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578979440,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579060302,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604617468,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579318944,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579346960,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604684422,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579396579,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580897906,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581083689,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581182759,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581213738,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581260571,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581265826,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581285507,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581291915,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581313467,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581330135,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581382047,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589490699,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581420242,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581479680,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581501819,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581534918,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581621037,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582041344,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582190164,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585270167,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589368104,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
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
  "name": "set_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578967824,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_status",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_shared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578986416,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579068150,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579080813,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604713652,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579334144,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579362687,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604783958,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579411963,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580995424,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581146670,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581253212,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581283538,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581334084,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581340420,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581359786,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581366493,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581424393,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581440003,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581493339,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589951656,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581530108,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581588782,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581611452,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581638151,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581733396,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582202431,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582353531,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585480819,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589824937,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:455",
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
  "name": "set_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578970256,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_status",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_shared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578988784,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579070246,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579082814,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604725954,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579338352,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579366927,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604809713,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579415147,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581049425,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581204206,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581311820,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581342258,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581393492,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581399719,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581419479,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581426237,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581485785,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581504227,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581557834,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590179190,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581595008,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581657695,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581682364,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581709175,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581806948,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582283269,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582452427,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585621523,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590051161,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
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
void set_pte_at(struct mm_struct * mm, long unsigned int addr, pte_t * ptep, pte_t pte)
```

```json
{
  "name": "set_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578979856,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_status",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_shared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578999136,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579077412,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:unmap_ldt_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579094188,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579138927,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579368048,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579394125,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071609148375,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579444641,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_page_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581232074,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581395210,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581501506,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581539478,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pte_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_one_pte"
      ],
      "caller_func": [
        "mm/memory.c:copy_one_pte"
      ]
    },
    {
      "addr": 18446744071581591489,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581597929,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581621081,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581628917,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581691080,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581711586,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581768173,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591197494,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581809614,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:write_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581876664,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581900899,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581926876,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:__collapse_huge_page_copy",
        "mm/khugepaged.c:__collapse_huge_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582023510,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage_pte",
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582571020,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582748216,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585044642,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586345175,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:457",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581513936,
      "name": "set_pte_at",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578982018,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_status",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_shared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579000960,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579079368,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579095394,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591251429,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579261104,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579367056,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581274669,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581438727,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581541660,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581582694,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pte_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581637502,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581644109,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581667273,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581674189,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581696321,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ioremap.c:ioremap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581740576,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581759378,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581816421,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591692390,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581857230,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:write_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581925869,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581946432,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582072804,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582643340,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582809925,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_soft_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586461221,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
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
  "name": "set_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578991106,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_status",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_shared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579008960,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579086329,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579101599,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591195188,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579262848,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579371408,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581291303,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581459187,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581564876,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581604401,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581659145,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581665616,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581689237,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581695414,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581768857,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581786378,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581844416,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591635140,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581892362,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:write_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581948103,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581972360,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582097827,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582671350,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582838645,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_soft_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586344977,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1035",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
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
  "name": "set_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579008162,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1006",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_status",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_shared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579109411,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1006",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579125519,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1006",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592060973,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1006",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579304096,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1006",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579432624,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1006",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581535593,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1006",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581829644,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1006",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581870593,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1006",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:restore_exclusive_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581927426,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1006",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581934304,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1006",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581961174,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1006",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581967592,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1006",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582051513,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1006",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582070154,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1006",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582135697,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1006",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592809180,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1006",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate",
        "mm/sparse-vmemmap.c:vmemmap_restore_pte",
        "mm/sparse-vmemmap.c:vmemmap_remap_pte",
        "mm/sparse-vmemmap.c:vmemmap_remap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582187035,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1006",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:write_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582252693,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1006",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582274813,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1006",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582412432,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1006",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582997606,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1006",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583171669,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1006",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_soft_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586865297,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1006",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
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
  "name": "set_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579025697,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1004",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_status",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_shared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579140562,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1004",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:map_ldt_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579159817,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1004",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593827481,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1004",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579359700,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1004",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579501616,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1004",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581884520,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1004",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582222893,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1004",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582266147,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1004",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:restore_exclusive_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582334790,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1004",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582343301,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1004",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582380472,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1004",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582390386,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1004",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582477720,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1004",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582509254,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1004",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582584950,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1004",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594710389,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1004",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate",
        "mm/sparse-vmemmap.c:vmemmap_restore_pte",
        "mm/sparse-vmemmap.c:vmemmap_remap_pte",
        "mm/sparse-vmemmap.c:__split_vmemmap_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582646759,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1004",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:write_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582718644,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1004",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582741550,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1004",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582758155,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1004",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582925677,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1004",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583672389,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1004",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_soft_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588151370,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1004",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
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
  "name": "set_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579054172,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1022",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_status",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_shared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579184924,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1022",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:map_ldt_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579210003,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1022",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579271054,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1022",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579430740,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1022",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579598800,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1022",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582317774,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1022",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582712489,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1022",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582757634,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1022",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:restore_exclusive_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582836019,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1022",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582844616,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1022",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582883952,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1022",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582896656,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1022",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582991388,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1022",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583028298,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1022",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583114706,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1022",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583122292,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1022",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_restore_pte",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_pte",
        "mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596455171,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1022",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583166670,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1022",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:write_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583245659,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1022",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583273993,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1022",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583291671,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1022",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583481373,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1022",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584279909,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1022",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_soft_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589545195,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1022",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
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
  "name": "set_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579054076,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1023",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_status",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_shared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579188991,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1023",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:map_ldt_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579215553,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1023",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579277334,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1023",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579442756,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1023",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579611520,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1023",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582518887,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1023",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582926875,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1023",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582973406,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1023",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_p4d_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:restore_exclusive_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583050826,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1023",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583058850,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1023",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583098803,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1023",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583108266,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1023",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pfn_apply",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583201569,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1023",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583237932,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1023",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583325093,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1023",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583332557,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1023",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_restore_pte",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_pte",
        "mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596996501,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1023",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583382867,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1023",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:write_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583465309,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1023",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583496152,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1023",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583510657,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1023",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583697245,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1023",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_pte_zeropage",
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584510069,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1023",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_soft_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589846794,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1023",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
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
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "set_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490358380,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:271",
      "file": "arch/arm64/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/hugetlbpage.c:huge_ptep_set_wrprotect",
        "arch/arm64/mm/hugetlbpage.c:huge_ptep_set_access_flags",
        "arch/arm64/mm/hugetlbpage.c:set_huge_pte_at",
        "arch/arm64/mm/hugetlbpage.c:set_huge_pte_at"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492406316,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:271",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492593716,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:271",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492719552,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:271",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492753096,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:271",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492798680,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:271",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492802468,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:271",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492818616,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:271",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492827500,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:271",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492903520,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:271",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492933428,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:271",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503922172,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:271",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493034944,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:271",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493117336,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:271",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493129524,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:271",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493164380,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:271",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493272256,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:271",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493856708,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:271",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498279040,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:271",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503826384,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm64/include/asm/pgtable.h:271",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "set_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224501156,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm/include/asm/pgtable.h:255",
      "file": "arch/arm/mm/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mm/mmu.c:__set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 3226290832,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm/include/asm/pgtable.h:255",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226448324,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm/include/asm/pgtable.h:255",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 3226551484,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm/include/asm/pgtable.h:255",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226559252,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm/include/asm/pgtable.h:255",
      "file": "mm/highmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226579904,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm/include/asm/pgtable.h:255",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_page",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 3226612772,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm/include/asm/pgtable.h:255",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 3226615744,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm/include/asm/pgtable.h:255",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 3226621268,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm/include/asm/pgtable.h:255",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:ptep_clear_flush_young",
        "mm/pgtable-generic.c:ptep_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 3226625920,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm/include/asm/pgtable.h:255",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 3226633504,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm/include/asm/pgtable.h:255",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226695784,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm/include/asm/pgtable.h:255",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 3226720624,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm/include/asm/pgtable.h:255",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 3226750952,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm/include/asm/pgtable.h:255",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:write_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226801976,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm/include/asm/pgtable.h:255",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 3226878172,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm/include/asm/pgtable.h:255",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 3226879124,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm/include/asm/pgtable.h:255",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_clear_pte_refs_one"
      ],
      "caller_func": []
    },
    {
      "addr": 3227518116,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm/include/asm/pgtable.h:255",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 3236447068,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/arm/include/asm/pgtable.h:255",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void set_pte_at(struct mm_struct * mm, long unsigned int addr, pte_t * ptep, pte_t pte)
```

```json
{
  "name": "set_pte_at",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282720096,
      "name": "set_pte_at",
      "external": true,
      "loc": "arch/powerpc/mm/pgtable.c:179",
      "file": "arch/powerpc/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/mm/book3s64/hash_pgtable.c:hash__map_kernel_page",
        "arch/powerpc/mm/book3s64/pgtable.c:ptep_modify_prot_commit",
        "arch/powerpc/mm/book3s64/pgtable.c:set_pmd_at",
        "arch/powerpc/mm/book3s64/pgtable.c:set_pmd_at",
        "arch/powerpc/mm/book3s64/radix_pgtable.c:pmd_set_huge",
        "arch/powerpc/mm/book3s64/radix_pgtable.c:pud_set_huge",
        "arch/powerpc/mm/book3s64/radix_pgtable.c:radix__ptep_modify_prot_commit",
        "arch/powerpc/mm/book3s64/radix_pgtable.c:__map_kernel_page",
        "arch/powerpc/mm/book3s64/radix_pgtable.c:__map_kernel_page",
        "arch/powerpc/mm/book3s64/hash_hugetlbpage.c:huge_ptep_modify_prot_commit",
        "arch/powerpc/mm/book3s64/radix_hugetlbpage.c:radix__huge_ptep_modify_prot_commit",
        "kernel/events/uprobes.c:__replace_page",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/mprotect.c:change_protection_range",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/vmalloc.c:vmap_page_range_noflush",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/swapfile.c:unuse_pte_range",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/sparse-vmemmap.c:vmemmap_pte_populate",
        "mm/ksm.c:replace_page",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/dax.c:dax_entry_mkclean",
        "lib/ioremap.c:ioremap_pud_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282720096,
      "name": "set_pte_at",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "set_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270613914,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:333",
      "file": "arch/riscv/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/mm/init.c:paging_init",
        "arch/riscv/mm/init.c:paging_init",
        "arch/riscv/mm/init.c:get_pmd_virt",
        "arch/riscv/mm/init.c:get_pte_virt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272622560,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:333",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272714008,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:333",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272734584,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:333",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272765484,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:333",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272768070,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:333",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272777114,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:333",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272783542,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:333",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272828190,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:333",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272852092,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:333",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272895712,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:333",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270897116,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:333",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272910768,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:333",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272949726,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:333",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273024384,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:333",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273427896,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:333",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279720354,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:333",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578970272,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_status",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_shared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578989136,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579070598,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579083166,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604652257,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579334256,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579362831,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604723655,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579410987,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581018273,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581173054,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581280668,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581311106,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581362340,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581368567,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581388327,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581395085,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581454633,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581472963,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581526570,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589781478,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581563744,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581626431,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581651100,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581677911,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581775684,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582252005,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582421163,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585383171,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589653417,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
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
  "name": "set_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578970192,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_status",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_shared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578988720,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579070182,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579082750,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604730020,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579334176,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579362751,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604801222,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579410907,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581009473,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581164254,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581271868,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581302306,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581353540,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581359767,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581379527,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581386285,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581445833,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581464275,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581517882,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590224886,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581555056,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581617743,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581642412,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581669223,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581766996,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582242485,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582411643,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585571923,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590096793,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
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
  "name": "set_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578970784,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_status",
        "arch/x86/xen/grant-table.c:arch_gnttab_map_shared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578989856,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579074278,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579086846,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604730066,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579342528,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579371183,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604813841,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579419771,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581070724,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581230521,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581335738,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581366290,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581417474,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423673,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581443376,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581450605,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581510293,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581528998,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581582872,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590275244,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581620107,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581686187,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581708796,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581735633,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581835828,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582320072,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582491089,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585679891,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590147049,
      "name": "set_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:443",
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
void set_pte_at(struct mm_struct * mm, long unsigned int addr, pte_t * ptep, pte_t pte)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void set_pte_at(struct mm_struct * mm, long unsigned int addr, pte_t * ptep, pte_t pte)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void set_pte_at(struct mm_struct * mm, long unsigned int addr, pte_t * ptep, pte_t pte)
```
</details>
</li>
</ul>
