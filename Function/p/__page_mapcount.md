# Function: <code>__page_mapcount</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int __page_mapcount(struct page * page)
```

```json
{
  "name": "__page_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580698928,
      "name": "__page_mapcount",
      "external": true,
      "loc": "mm/util.c:410",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__delete_from_page_cache",
        "mm/shmem.c:shmem_add_seals",
        "mm/shmem.c:shmem_add_seals",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:unmap_page_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_isolated_page",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:page_mapcount_is_zero",
        "mm/rmap.c:try_to_unmap_one",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:SyS_move_pages",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/khugepaged.c:khugepaged",
        "mm/memory-failure.c:memory_failure",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/page.c:kpagecount_read",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580698928,
      "name": "__page_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int __page_mapcount(struct page * page)
```

```json
{
  "name": "__page_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580764736,
      "name": "__page_mapcount",
      "external": true,
      "loc": "mm/util.c:413",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__delete_from_page_cache",
        "mm/shmem.c:shmem_add_seals",
        "mm/shmem.c:shmem_add_seals",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:unmap_page_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_isolated_page",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:page_mapcount_is_zero",
        "mm/rmap.c:try_to_unmap_one",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:SYSC_move_pages",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/khugepaged.c:khugepaged",
        "mm/memory-failure.c:memory_failure",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/page.c:kpagecount_read",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580764736,
      "name": "__page_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int __page_mapcount(struct page * page)
```

```json
{
  "name": "__page_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580801120,
      "name": "__page_mapcount",
      "external": true,
      "loc": "mm/util.c:497",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__delete_from_page_cache",
        "mm/shmem.c:shmem_add_seals",
        "mm/shmem.c:shmem_add_seals",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/memory.c:__handle_mm_fault",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_isolated_page",
        "mm/rmap.c:try_to_unmap",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:SYSC_move_pages",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/khugepaged.c:khugepaged",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/page.c:kpagecount_read",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580801120,
      "name": "__page_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __page_mapcount(struct page * page)
```

```json
{
  "name": "__page_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580889824,
      "name": "__page_mapcount",
      "external": true,
      "loc": "mm/util.c:497",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/shmem.c:shmem_add_seals",
        "mm/shmem.c:shmem_add_seals",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/memory.c:handle_pte_fault",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_isolated_page",
        "mm/rmap.c:try_to_unmap",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/mempolicy.c:migrate_page_add",
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:SYSC_move_pages",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/khugepaged.c:khugepaged",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/page.c:kpagecount_read",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580889824,
      "name": "__page_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int __page_mapcount(struct page * page)
```

```json
{
  "name": "__page_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581025568,
      "name": "__page_mapcount",
      "external": true,
      "loc": "mm/util.c:533",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/memory.c:handle_pte_fault",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_isolated_page",
        "mm/mprotect.c:change_pte_range",
        "mm/rmap.c:try_to_unmap",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/mempolicy.c:migrate_page_add",
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:kernel_move_pages",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/memfd.c:memfd_fcntl",
        "mm/memfd.c:memfd_fcntl",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/page.c:kpagecount_read",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581025568,
      "name": "__page_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int __page_mapcount(struct page * page)
```

```json
{
  "name": "__page_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581103088,
      "name": "__page_mapcount",
      "external": true,
      "loc": "mm/util.c:536",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/memory.c:__handle_mm_fault",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_isolated_page",
        "mm/mprotect.c:change_protection_range",
        "mm/rmap.c:try_to_unmap",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/mempolicy.c:migrate_page_add",
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:kernel_move_pages",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/khugepaged.c:khugepaged",
        "mm/memfd.c:memfd_fcntl",
        "mm/memfd.c:memfd_fcntl",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/page.c:kpagecount_read",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581103088,
      "name": "__page_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int __page_mapcount(struct page * page)
```

```json
{
  "name": "__page_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581167840,
      "name": "__page_mapcount",
      "external": true,
      "loc": "mm/util.c:579",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/memory.c:do_numa_page",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_isolated_page",
        "mm/mprotect.c:change_pte_range",
        "mm/rmap.c:try_to_unmap",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/mempolicy.c:migrate_page_add",
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/ksm.c:stable_tree_search",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:do_pages_move",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/khugepaged.c:khugepaged",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/page.c:kpagecount_read",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581167840,
      "name": "__page_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int __page_mapcount(struct page * page)
```

```json
{
  "name": "__page_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581225808,
      "name": "__page_mapcount",
      "external": true,
      "loc": "mm/util.c:684",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/memory.c:do_numa_page",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_isolated_page",
        "mm/mprotect.c:change_pte_range",
        "mm/rmap.c:try_to_unmap",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/mempolicy.c:migrate_page_add",
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/ksm.c:stable_tree_search",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:do_pages_move",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/page.c:kpagecount_read",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581225808,
      "name": "__page_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __page_mapcount(struct page * page)
```

```json
{
  "name": "__page_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581413024,
      "name": "__page_mapcount",
      "external": true,
      "loc": "mm/util.c:712",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:zap_pte_range",
        "mm/mlock.c:__putback_lru_fast_prepare",
        "mm/mlock.c:__munlock_isolated_page",
        "mm/mprotect.c:change_pte_range",
        "mm/rmap.c:try_to_unmap",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/mempolicy.c:migrate_page_add",
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:write_protect_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:add_page_for_migration",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/khugepaged.c:khugepaged_scan_file",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/page.c:kpagecount_read",
        "fs/fuse/dev.c:fuse_try_move_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581413024,
      "name": "__page_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int __page_mapcount(struct page * page)
```

```json
{
  "name": "__page_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581455744,
      "name": "__page_mapcount",
      "external": true,
      "loc": "mm/util.c:725",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:zap_pte_range",
        "mm/mlock.c:__putback_lru_fast_prepare",
        "mm/mlock.c:__munlock_isolated_page",
        "mm/mprotect.c:change_pte_range",
        "mm/rmap.c:try_to_unmap",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/mempolicy.c:migrate_page_add",
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:write_protect_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:add_page_for_migration",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/khugepaged.c:khugepaged_scan_file",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/page.c:kpagecount_read",
        "fs/fuse/dev.c:fuse_try_move_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581455744,
      "name": "__page_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int __page_mapcount(struct page * page)
```

```json
{
  "name": "__page_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581476624,
      "name": "__page_mapcount",
      "external": true,
      "loc": "mm/util.c:715",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:zap_pte_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_isolated_page",
        "mm/mprotect.c:change_pte_range",
        "mm/rmap.c:try_to_unmap",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/mempolicy.c:migrate_page_add",
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:write_protect_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:add_page_for_migration",
        "mm/khugepaged.c:khugepaged_scan_file",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/page.c:kpagecount_read",
        "fs/fuse/dev.c:fuse_try_move_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581476624,
      "name": "__page_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int __page_mapcount(struct page * page)
```

```json
{
  "name": "__page_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581730864,
      "name": "__page_mapcount",
      "external": true,
      "loc": "mm/util.c:736",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:zap_pte_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_isolated_page",
        "mm/rmap.c:make_device_exclusive_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/mempolicy.c:migrate_page_add",
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:write_protect_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:add_page_for_migration",
        "mm/khugepaged.c:khugepaged_scan_file",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/page.c:kpagecount_read",
        "fs/fuse/dev.c:fuse_try_move_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581730864,
      "name": "__page_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int __page_mapcount(struct page * page)
```

```json
{
  "name": "__page_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582111664,
      "name": "__page_mapcount",
      "external": true,
      "loc": "mm/util.c:815",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:zap_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/mempolicy.c:migrate_page_add",
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:write_protect_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate_device.c:migrate_vma_unmap",
        "mm/khugepaged.c:khugepaged_scan_file",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/page.c:kpagecount_read",
        "fs/fuse/dev.c:fuse_try_move_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582111664,
      "name": "__page_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int __page_mapcount(struct page * page)
```

```json
{
  "name": "__page_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492614272,
      "name": "__page_mapcount",
      "external": true,
      "loc": "mm/util.c:684",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:unmap_page_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_isolated_page",
        "mm/mprotect.c:change_protection_range",
        "mm/rmap.c:try_to_unmap",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/mempolicy.c:migrate_page_add",
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/ksm.c:stable_tree_search",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:do_pages_move",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/khugepaged.c:khugepaged",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/page.c:kpagecount_read",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492614272,
      "name": "__page_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int __page_mapcount(struct page * page)
```

```json
{
  "name": "__page_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226465196,
      "name": "__page_mapcount",
      "external": true,
      "loc": "mm/util.c:684",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/memory.c:unmap_page_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_isolated_page",
        "mm/mprotect.c:change_protection_range",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:page_mapcount_is_zero",
        "mm/rmap.c:page_referenced",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/swapfile.c:reuse_swap_page",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:write_protect_page",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_pte_entry",
        "fs/proc/page.c:kpagecount_read",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226465196,
      "name": "__page_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int __page_mapcount(struct page * page)
```

```json
{
  "name": "__page_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285931952,
      "name": "__page_mapcount",
      "external": true,
      "loc": "mm/util.c:684",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:zap_pte_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_isolated_page",
        "mm/mprotect.c:change_protection_range",
        "mm/rmap.c:try_to_unmap",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/mempolicy.c:migrate_page_add",
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/ksm.c:stable_tree_search",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:do_pages_move",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/page.c:kpagecount_read",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285931952,
      "name": "__page_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int __page_mapcount(struct page * page)
```

```json
{
  "name": "__page_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272640918,
      "name": "__page_mapcount",
      "external": true,
      "loc": "mm/util.c:684",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/memory.c:unmap_page_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_isolated_page",
        "mm/mprotect.c:change_protection_range",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:page_mapcount_is_zero",
        "mm/rmap.c:page_referenced",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/swapfile.c:reuse_swap_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/ksm.c:ksm_do_scan",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_range",
        "fs/proc/page.c:kpagecount_read",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272640918,
      "name": "__page_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int __page_mapcount(struct page * page)
```

```json
{
  "name": "__page_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581194656,
      "name": "__page_mapcount",
      "external": true,
      "loc": "mm/util.c:684",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/memory.c:do_numa_page",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_isolated_page",
        "mm/mprotect.c:change_pte_range",
        "mm/rmap.c:try_to_unmap",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/mempolicy.c:migrate_page_add",
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/ksm.c:stable_tree_search",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:do_pages_move",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/page.c:kpagecount_read",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581194656,
      "name": "__page_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int __page_mapcount(struct page * page)
```

```json
{
  "name": "__page_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581141408,
      "name": "__page_mapcount",
      "external": true,
      "loc": "mm/util.c:684",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:zap_pte_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_isolated_page",
        "mm/mprotect.c:change_protection_range",
        "mm/rmap.c:try_to_unmap",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/mempolicy.c:migrate_page_add",
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/ksm.c:stable_tree_search",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:do_pages_move",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/page.c:kpagecount_read",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581141408,
      "name": "__page_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int __page_mapcount(struct page * page)
```

```json
{
  "name": "__page_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581185856,
      "name": "__page_mapcount",
      "external": true,
      "loc": "mm/util.c:684",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/memory.c:do_numa_page",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_isolated_page",
        "mm/mprotect.c:change_pte_range",
        "mm/rmap.c:try_to_unmap",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/mempolicy.c:migrate_page_add",
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/ksm.c:stable_tree_search",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:do_pages_move",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/page.c:kpagecount_read",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581185856,
      "name": "__page_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int __page_mapcount(struct page * page)
```

```json
{
  "name": "__page_mapcount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581249104,
      "name": "__page_mapcount",
      "external": true,
      "loc": "mm/util.c:684",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/memory.c:do_numa_page",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_isolated_page",
        "mm/mprotect.c:change_pte_range",
        "mm/rmap.c:try_to_unmap",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/mempolicy.c:migrate_page_add",
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/ksm.c:stable_tree_search",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:do_pages_move",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/khugepaged.c:khugepaged",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/proc/task_mmu.c:gather_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_account",
        "fs/proc/page.c:kpagecount_read",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581249104,
      "name": "__page_mapcount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int __page_mapcount(struct page * page)
```
</details>
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
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int __page_mapcount(struct page * page)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
