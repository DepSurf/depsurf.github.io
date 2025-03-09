# Function: <code>split_huge_page_to_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int split_huge_page_to_list(struct page * page, struct list_head * list)
```

```json
{
  "name": "split_huge_page_to_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580905616,
      "name": "split_huge_page_to_list",
      "external": true,
      "loc": "mm/huge_memory.c:1957",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_state.c:add_to_swap",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/migrate.c:migrate_pages",
        "mm/huge_memory.c:__split_huge_page_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580905616,
      "name": "split_huge_page_to_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1943
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int split_huge_page_to_list(struct page * page, struct list_head * list)
```

```json
{
  "name": "split_huge_page_to_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581038656,
      "name": "split_huge_page_to_list",
      "external": true,
      "loc": "mm/huge_memory.c:1978",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/gup.c:follow_page_mask",
        "mm/gup.c:follow_page_pte",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/swap_state.c:add_to_swap",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/migrate.c:migrate_pages",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581038656,
      "name": "split_huge_page_to_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1787
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
int split_huge_page_to_list(struct page * page, struct list_head * list)
```

```json
{
  "name": "split_huge_page_to_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581113840,
      "name": "split_huge_page_to_list",
      "external": true,
      "loc": "mm/huge_memory.c:2109",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/gup.c:follow_page_mask",
        "mm/gup.c:follow_page_pte",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/swap_state.c:add_to_swap",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_pages",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581113840,
      "name": "split_huge_page_to_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1775
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
int split_huge_page_to_list(struct page * page, struct list_head * list)
```

```json
{
  "name": "split_huge_page_to_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581162000,
      "name": "split_huge_page_to_list",
      "external": true,
      "loc": "mm/huge_memory.c:2448",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/gup.c:follow_page_pte",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_pages",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581162000,
      "name": "split_huge_page_to_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1832
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
int split_huge_page_to_list(struct page * page, struct list_head * list)
```

```json
{
  "name": "split_huge_page_to_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581288288,
      "name": "split_huge_page_to_list",
      "external": true,
      "loc": "mm/huge_memory.c:2600",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_page_pte",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_pages",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581288288,
      "name": "split_huge_page_to_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2070
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
int split_huge_page_to_list(struct page * page, struct list_head * list)
```

```json
{
  "name": "split_huge_page_to_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581435328,
      "name": "split_huge_page_to_list",
      "external": true,
      "loc": "mm/huge_memory.c:2592",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/gup.c:follow_page_pte",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_pages",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581435328,
      "name": "split_huge_page_to_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2056
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
int split_huge_page_to_list(struct page * page, struct list_head * list)
```

```json
{
  "name": "split_huge_page_to_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581518880,
      "name": "split_huge_page_to_list",
      "external": true,
      "loc": "mm/huge_memory.c:2611",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/gup.c:follow_page_pte",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_pages",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581518880,
      "name": "split_huge_page_to_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2137
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
int split_huge_page_to_list(struct page * page, struct list_head * list)
```

```json
{
  "name": "split_huge_page_to_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581628720,
      "name": "split_huge_page_to_list",
      "external": true,
      "loc": "mm/huge_memory.c:2672",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/gup.c:follow_page_pte",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_pages",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581628720,
      "name": "split_huge_page_to_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1245
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
int split_huge_page_to_list(struct page * page, struct list_head * list)
```

```json
{
  "name": "split_huge_page_to_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581699536,
      "name": "split_huge_page_to_list",
      "external": true,
      "loc": "mm/huge_memory.c:2695",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/gup.c:follow_page_pte",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_pages",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581699536,
      "name": "split_huge_page_to_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1316
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
int split_huge_page_to_list(struct page * page, struct list_head * list)
```

```json
{
  "name": "split_huge_page_to_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581915520,
      "name": "split_huge_page_to_list",
      "external": true,
      "loc": "mm/huge_memory.c:2605",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/gup.c:follow_page_pte",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_pages",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581915520,
      "name": "split_huge_page_to_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1239
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
int split_huge_page_to_list(struct page * page, struct list_head * list)
```

```json
{
  "name": "split_huge_page_to_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581962320,
      "name": "split_huge_page_to_list",
      "external": true,
      "loc": "mm/huge_memory.c:2662",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/gup.c:follow_page_pte",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581962320,
      "name": "split_huge_page_to_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1142
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
int split_huge_page_to_list(struct page * page, struct list_head * list)
```

```json
{
  "name": "split_huge_page_to_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581988432,
      "name": "split_huge_page_to_list",
      "external": true,
      "loc": "mm/huge_memory.c:2673",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581988432,
      "name": "split_huge_page_to_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1102
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
int split_huge_page_to_list(struct page * page, struct list_head * list)
```

```json
{
  "name": "split_huge_page_to_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582290528,
      "name": "split_huge_page_to_list",
      "external": true,
      "loc": "mm/huge_memory.c:2612",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582290528,
      "name": "split_huge_page_to_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1157
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
int split_huge_page_to_list(struct page * page, struct list_head * list)
```

```json
{
  "name": "split_huge_page_to_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582774608,
      "name": "split_huge_page_to_list",
      "external": true,
      "loc": "mm/huge_memory.c:2567",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_inode_partial_folio",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582774608,
      "name": "split_huge_page_to_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2280
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int split_huge_page_to_list(struct page * page, struct list_head * list)
```

```json
{
  "name": "split_huge_page_to_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583308464,
      "name": "split_huge_page_to_list",
      "external": true,
      "loc": "mm/huge_memory.c:2652",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_inode_partial_folio",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583308464,
      "name": "split_huge_page_to_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1633
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int split_huge_page_to_list(struct page * page, struct list_head * list)
```

```json
{
  "name": "split_huge_page_to_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583528064,
      "name": "split_huge_page_to_list",
      "external": true,
      "loc": "mm/huge_memory.c:2645",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_inode_partial_folio",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_pages_batch",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memory-failure.c:try_to_split_thp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583528064,
      "name": "split_huge_page_to_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1454
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int split_huge_page_to_list(struct page * page, struct list_head * list)
```

```json
{
  "name": "split_huge_page_to_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583722480,
      "name": "split_huge_page_to_list",
      "external": true,
      "loc": "mm/huge_memory.c:2978",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:truncate_inode_partial_folio",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_pages_batch",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memory-failure.c:try_to_split_thp_page",
        "mm/userfaultfd.c:move_pages_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583722480,
      "name": "split_huge_page_to_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1464
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int split_huge_page_to_list(struct page * page, struct list_head * list)
```

```json
{
  "name": "split_huge_page_to_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493143232,
      "name": "split_huge_page_to_list",
      "external": true,
      "loc": "mm/huge_memory.c:2695",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_page_pte",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:memory_failure",
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493143232,
      "name": "split_huge_page_to_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1436
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "split_huge_page_to_list",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "split_huge_page_to_list",
      "external": false,
      "loc": "include/linux/huge_mm.h:324",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "split_huge_page_to_list",
      "external": false,
      "loc": "include/linux/huge_mm.h:324",
      "file": "mm/migrate.c",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int split_huge_page_to_list(struct page * page, struct list_head * list)
```

```json
{
  "name": "split_huge_page_to_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286630896,
      "name": "split_huge_page_to_list",
      "external": true,
      "loc": "mm/huge_memory.c:2695",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286630896,
      "name": "split_huge_page_to_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1972
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
  "name": "split_huge_page_to_list",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "split_huge_page_to_list",
      "external": false,
      "loc": "include/linux/huge_mm.h:324",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "split_huge_page_to_list",
      "external": false,
      "loc": "include/linux/huge_mm.h:324",
      "file": "mm/migrate.c",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int split_huge_page_to_list(struct page * page, struct list_head * list)
```

```json
{
  "name": "split_huge_page_to_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581668272,
      "name": "split_huge_page_to_list",
      "external": true,
      "loc": "mm/huge_memory.c:2695",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/gup.c:follow_page_pte",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_pages",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581668272,
      "name": "split_huge_page_to_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1316
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
int split_huge_page_to_list(struct page * page, struct list_head * list)
```

```json
{
  "name": "split_huge_page_to_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581607808,
      "name": "split_huge_page_to_list",
      "external": true,
      "loc": "mm/huge_memory.c:2695",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_page_pte",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_pages",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581607808,
      "name": "split_huge_page_to_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1316
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
int split_huge_page_to_list(struct page * page, struct list_head * list)
```

```json
{
  "name": "split_huge_page_to_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581659584,
      "name": "split_huge_page_to_list",
      "external": true,
      "loc": "mm/huge_memory.c:2695",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/gup.c:follow_page_pte",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_pages",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581659584,
      "name": "split_huge_page_to_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1316
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
int split_huge_page_to_list(struct page * page, struct list_head * list)
```

```json
{
  "name": "split_huge_page_to_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581725968,
      "name": "split_huge_page_to_list",
      "external": true,
      "loc": "mm/huge_memory.c:2695",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/gup.c:follow_page_pte",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_pages",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581725968,
      "name": "split_huge_page_to_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1312
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int split_huge_page_to_list(struct page * page, struct list_head * list)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int split_huge_page_to_list(struct page * page, struct list_head * list)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
