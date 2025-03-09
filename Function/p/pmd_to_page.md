# Function: <code>pmd_to_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_to_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580658087,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1643",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580668511,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1643",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580714796,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1643",
      "file": "mm/mprotect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580723847,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1643",
      "file": "mm/rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/rmap.c:__page_check_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580746918,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1643",
      "file": "mm/pgtable-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgtable_trans_huge_deposit",
        "mm/pgtable-generic.c:pgtable_trans_huge_deposit",
        "mm/pgtable-generic.c:pgtable_trans_huge_withdraw",
        "mm/pgtable-generic.c:pgtable_trans_huge_withdraw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580801326,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1643",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580810947,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1643",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580880412,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1643",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:migration_entry_wait_huge",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580897469,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1643",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:page_check_address_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__split_huge_page_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
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
  "name": "pmd_to_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581133842,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1759",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580787318,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1759",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580830157,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1759",
      "file": "mm/mprotect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580842583,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1759",
      "file": "mm/rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_check_address_transhuge",
        "mm/rmap.c:page_check_address_transhuge",
        "mm/rmap.c:__page_check_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580866342,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1759",
      "file": "mm/pgtable-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgtable_trans_huge_withdraw",
        "mm/pgtable-generic.c:pgtable_trans_huge_deposit",
        "mm/pgtable-generic.c:pgtable_trans_huge_deposit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580933714,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1759",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580937342,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1759",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581020402,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1759",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migration_entry_wait_huge",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581031903,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1759",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581054086,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1759",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page"
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
  "name": "pmd_to_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581208941,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1733",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580851622,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1733",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580895679,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1733",
      "file": "mm/mprotect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580905290,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1733",
      "file": "mm/page_vma_mapped.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580908294,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1733",
      "file": "mm/pgtable-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgtable_trans_huge_withdraw",
        "mm/pgtable-generic.c:pgtable_trans_huge_deposit",
        "mm/pgtable-generic.c:pgtable_trans_huge_deposit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580913117,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1733",
      "file": "mm/rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_check_address_transhuge",
        "mm/rmap.c:page_check_address_transhuge",
        "mm/rmap.c:__page_check_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581002047,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1733",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581009082,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1733",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581095010,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1733",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migration_entry_wait_huge",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581107198,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1733",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581131741,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1733",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_shmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581584784,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1733",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pmd_fault"
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
  "name": "pmd_to_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580874452,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1786",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580884064,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1786",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580950082,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1786",
      "file": "mm/page_vma_mapped.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580953862,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1786",
      "file": "mm/pgtable-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgtable_trans_huge_withdraw",
        "mm/pgtable-generic.c:pgtable_trans_huge_deposit",
        "mm/pgtable-generic.c:pgtable_trans_huge_deposit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581049664,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1786",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581051370,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1786",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581141822,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1786",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migration_entry_wait_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581157398,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1786",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581176283,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1786",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581644713,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1786",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_fault"
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
  "name": "pmd_to_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580968726,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1888",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_pmd_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580977346,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1888",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581050687,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1888",
      "file": "mm/page_vma_mapped.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581055589,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1888",
      "file": "mm/pgtable-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgtable_trans_huge_withdraw",
        "mm/pgtable-generic.c:pgtable_trans_huge_deposit",
        "mm/pgtable-generic.c:pgtable_trans_huge_deposit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581160572,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1888",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581162599,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1888",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581249860,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1888",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:migration_entry_wait_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581280041,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1888",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581306001,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1888",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_shmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581790013,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1888",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_fault"
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
  "name": "pmd_to_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581097664,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1977",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581112571,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1977",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581190220,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1977",
      "file": "mm/page_vma_mapped.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581194261,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1977",
      "file": "mm/pgtable-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgtable_trans_huge_withdraw",
        "mm/pgtable-generic.c:pgtable_trans_huge_deposit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581303711,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1977",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581312729,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1977",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581392258,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1977",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:migration_entry_wait_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581428547,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1977",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581448985,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1977",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581964006,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:1977",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_to_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581177392,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2047",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581191722,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2047",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581266921,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2047",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581273176,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2047",
      "file": "mm/page_vma_mapped.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581277637,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2047",
      "file": "mm/pgtable-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgtable_trans_huge_withdraw",
        "mm/pgtable-generic.c:pgtable_trans_huge_deposit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581387375,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2047",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581394267,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2047",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581477874,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2047",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:migration_entry_wait_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581514374,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2047",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581531739,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2047",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582048664,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2047",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_to_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581253680,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2042",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581264532,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2042",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581341500,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2042",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581347640,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2042",
      "file": "mm/page_vma_mapped.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581352101,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2042",
      "file": "mm/pgtable-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgtable_trans_huge_withdraw",
        "mm/pgtable-generic.c:pgtable_trans_huge_deposit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581499034,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2042",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581506445,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2042",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581602364,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2042",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:migration_entry_wait_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581623998,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2042",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581642821,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2042",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581744698,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2042",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582205581,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2042",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_to_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581312281,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581323326,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581400826,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581406952,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/page_vma_mapped.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581411605,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/pgtable-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgtable_trans_huge_withdraw",
        "mm/pgtable-generic.c:pgtable_trans_huge_deposit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581563546,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581570813,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581656722,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:migration_entry_wait_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581694871,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581714910,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581817730,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582286429,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_to_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581501998,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2285",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581521509,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2285",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:pte_alloc_one_map",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581597146,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2285",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_normal_pmd",
        "mm/mremap.c:move_normal_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581604789,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2285",
      "file": "mm/page_vma_mapped.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581611733,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2285",
      "file": "mm/pgtable-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgtable_trans_huge_withdraw",
        "mm/pgtable-generic.c:pgtable_trans_huge_deposit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581774128,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2285",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581788729,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2285",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581875442,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2285",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:migration_entry_wait_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581912424,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2285",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581929856,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2285",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:retract_page_tables",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582037978,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2285",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582575837,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2285",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_to_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581542158,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2285",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581596439,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2285",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_invalidate_pte",
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:pte_alloc_one_map",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581643332,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2285",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581652657,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2285",
      "file": "mm/page_vma_mapped.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581659061,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2285",
      "file": "mm/pgtable-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgtable_trans_huge_withdraw",
        "mm/pgtable-generic.c:pgtable_trans_huge_deposit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581822272,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2285",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581836153,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2285",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581923925,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2285",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:migration_entry_wait_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581958073,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2285",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581976722,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2285",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:retract_page_tables",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582086854,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2285",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582647244,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2285",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct page * pmd_to_page(pmd_t * pmd)
```

```json
{
  "name": "pmd_to_page",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581334079,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2293",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581565392,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2293",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581619072,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2293",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_invalidate_pte",
        "mm/memory.c:finish_fault",
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581664836,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2293",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581674687,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2293",
      "file": "mm/page_vma_mapped.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581680869,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2293",
      "file": "mm/pgtable-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgtable_trans_huge_withdraw",
        "mm/pgtable-generic.c:pgtable_trans_huge_deposit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581854048,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2293",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unshare_all_pmds",
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581866967,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2293",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581946837,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2293",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:migration_entry_wait_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581984105,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2293",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582004735,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2293",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:retract_page_tables",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582110659,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2293",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582673579,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2293",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581582336,
      "name": "pmd_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
struct page * pmd_to_page(pmd_t * pmd)
```

```json
{
  "name": "pmd_to_page",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581582255,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2322",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581830158,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2322",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581886677,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2322",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_invalidate_pte",
        "mm/memory.c:finish_fault",
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581933446,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2322",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581943938,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2322",
      "file": "mm/page_vma_mapped.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581950149,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2322",
      "file": "mm/pgtable-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgtable_trans_huge_withdraw",
        "mm/pgtable-generic.c:pgtable_trans_huge_deposit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582145861,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2322",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unshare_all_pmds",
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582158001,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2322",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582251477,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2322",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:migration_entry_wait_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582286089,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2322",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582307177,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2322",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:retract_page_tables",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582426973,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2322",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582999867,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2322",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581847424,
      "name": "pmd_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
struct page * pmd_to_page(pmd_t * pmd)
```

```json
{
  "name": "pmd_to_page",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582223311,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2400",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582265264,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2400",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:pmd_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582342373,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2400",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582353794,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2400",
      "file": "mm/page_vma_mapped.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582359733,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2400",
      "file": "mm/pgtable-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgtable_trans_huge_withdraw",
        "mm/pgtable-generic.c:pgtable_trans_huge_deposit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582599856,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2400",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unshare_all_pmds",
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582613257,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2400",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582731477,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2400",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:migration_entry_wait_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582740029,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2400",
      "file": "mm/migrate_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582770168,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2400",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582792459,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2400",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_and_free_pmd",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582942044,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2400",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583468605,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2400",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582239664,
      "name": "pmd_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_to_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492720072,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_pmd_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492729628,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492807076,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/page_vma_mapped.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492811200,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/pgtable-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgtable_trans_huge_withdraw",
        "mm/pgtable-generic.c:pgtable_trans_huge_deposit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492998044,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493007768,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493117112,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migration_entry_wait_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493139076,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493161524,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493282172,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "pmd_to_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282735852,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "arch/powerpc/mm/book3s64/hash_pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/hash_pgtable.c:hash__pgtable_trans_huge_withdraw",
        "arch/powerpc/mm/book3s64/hash_pgtable.c:hash__pgtable_trans_huge_deposit"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282775024,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "arch/powerpc/mm/book3s64/radix_pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/radix_pgtable.c:radix__pgtable_trans_huge_withdraw",
        "arch/powerpc/mm/book3s64/radix_pgtable.c:radix__pgtable_trans_huge_withdraw",
        "arch/powerpc/mm/book3s64/radix_pgtable.c:radix__pgtable_trans_huge_deposit",
        "arch/powerpc/mm/book3s64/radix_pgtable.c:radix__pgtable_trans_huge_deposit",
        "arch/powerpc/mm/book3s64/radix_pgtable.c:radix__pgtable_trans_huge_deposit"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282841756,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "arch/powerpc/mm/hugetlbpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/hugetlbpage.c:huge_pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286062304,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_pmd_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286075516,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286184304,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/page_vma_mapped.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286424728,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286428128,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286572892,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:migration_entry_wait_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286623544,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286657716,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286816064,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287489812,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
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
  "name": "pmd_to_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581281129,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581292174,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581369674,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581375800,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/page_vma_mapped.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581380453,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/pgtable-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgtable_trans_huge_withdraw",
        "mm/pgtable-generic.c:pgtable_trans_huge_deposit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581532282,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581539549,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581625458,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:migration_entry_wait_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581663607,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581683646,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581786466,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582255165,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_to_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581227315,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_pmd_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581236622,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581312890,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581319082,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/page_vma_mapped.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581323157,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/pgtable-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgtable_trans_huge_withdraw",
        "mm/pgtable-generic.c:pgtable_trans_huge_deposit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581474107,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581481254,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581566744,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:migration_entry_wait_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581603383,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581622252,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581724693,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582199668,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_to_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581272329,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581283374,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581360874,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581367000,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/page_vma_mapped.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581371653,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/pgtable-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgtable_trans_huge_withdraw",
        "mm/pgtable-generic.c:pgtable_trans_huge_deposit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581523594,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581530861,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581616770,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:migration_entry_wait_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581654919,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581674958,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581777778,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582245645,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_to_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581336207,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581347381,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581424763,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581430894,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/page_vma_mapped.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581435541,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/pgtable-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgtable_trans_huge_withdraw",
        "mm/pgtable-generic.c:pgtable_trans_huge_deposit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581588536,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581590331,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581685213,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:migration_entry_wait_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581721310,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581741579,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581846758,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582328425,
      "name": "pmd_to_page",
      "external": false,
      "loc": "include/linux/mm.h:2014",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct page * pmd_to_page(pmd_t * pmd)
```
</details>
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
struct page * pmd_to_page(pmd_t * pmd)
```
</details>
</li>
</ul>
