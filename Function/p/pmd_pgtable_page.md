# Function: <code>pmd_pgtable_page</code>

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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_pgtable_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582512263,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2564",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582712796,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2564",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582756690,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2564",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:pmd_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582843670,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2564",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582855309,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2564",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582862117,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2564",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgtable_trans_huge_withdraw",
        "mm/pgtable-generic.c:pgtable_trans_huge_deposit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583096278,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2564",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unshare_pmds",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_follow_page_mask",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
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
      "addr": 18446744071583136759,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2564",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583252101,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2564",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:migration_entry_wait_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583271306,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2564",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583304792,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2564",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
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
      "addr": 18446744071583338402,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2564",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583498855,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2564",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584061403,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2564",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_pmd_load_hole"
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
  "name": "pmd_pgtable_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582714295,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2889",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582927276,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2889",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582972504,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2889",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:pmd_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583060102,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2889",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583071312,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2889",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583077621,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2889",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgtable_trans_huge_withdraw",
        "mm/pgtable-generic.c:pgtable_trans_huge_deposit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583306165,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2889",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unshare_pmds",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_follow_page_mask",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
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
      "addr": 18446744071583347132,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2889",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_folios_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583471573,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2889",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:migration_entry_wait_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583494377,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2889",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583524092,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2889",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
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
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583557435,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2889",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583713847,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2889",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584287838,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2889",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_pmd_load_hole"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct page * pmd_pgtable_page(pmd_t * pmd)
```

```json
{
  "name": "pmd_pgtable_page",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582883527,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2985",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583101450,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2985",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583150250,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2985",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:pmd_install"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583241574,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2985",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583253285,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2985",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583259877,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2985",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgtable_trans_huge_withdraw",
        "mm/pgtable-generic.c:pgtable_trans_huge_deposit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583544038,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2985",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unshare_pmds",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_follow_page_mask",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
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
      "addr": 18446744071583583174,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2985",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_folios_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583663877,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2985",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:migration_entry_wait_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583685610,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2985",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583718796,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2985",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:move_pages_huge_pmd",
        "mm/huge_memory.c:move_pages_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
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
      "addr": 18446744071583747071,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2985",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:retract_page_tables",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": [
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ]
    },
    {
      "addr": 18446744071583914591,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2985",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584504638,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2985",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_pmd_load_hole"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584732578,
      "name": "pmd_pgtable_page",
      "external": false,
      "loc": "include/linux/mm.h:2985",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_scan_hugetlb_entry"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583731120,
      "name": "pmd_pgtable_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
struct page * pmd_pgtable_page(pmd_t * pmd)
```
</details>
</li>
</ul>
