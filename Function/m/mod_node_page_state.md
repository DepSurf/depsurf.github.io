# Function: <code>mod_node_page_state</code>

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
void mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580706560,
      "name": "mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:499",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580706560,
      "name": "mod_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580772496,
      "name": "mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:499",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580772496,
      "name": "mod_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580808944,
      "name": "mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:499",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/slub.c:__free_slab",
        "mm/slub.c:new_slab",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580808944,
      "name": "mod_node_page_state",
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
void mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580898128,
      "name": "mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:574",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/mempolicy.c:migrate_page_add",
        "mm/slub.c:__free_slab",
        "mm/slub.c:new_slab",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:SYSC_move_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:putback_movable_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580898128,
      "name": "mod_node_page_state",
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
void mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581034032,
      "name": "mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:574",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/mempolicy.c:migrate_page_add",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:kernel_move_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:putback_movable_pages",
        "fs/dcache.c:__d_alloc",
        "fs/dcache.c:__d_free_external_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581034032,
      "name": "mod_node_page_state",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581111600,
      "name": "mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:574",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/mempolicy.c:migrate_page_add",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:kernel_move_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:putback_movable_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581111600,
      "name": "mod_node_page_state",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581176304,
      "name": "mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:575",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/gup.c:__gup_longterm_locked",
        "mm/mempolicy.c:migrate_page_add",
        "mm/slub.c:__free_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:putback_movable_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581176304,
      "name": "mod_node_page_state",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581234432,
      "name": "mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:575",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/slab_common.c:kmalloc_order",
        "mm/gup.c:__gup_longterm_locked",
        "mm/mempolicy.c:migrate_page_add",
        "mm/slub.c:kfree",
        "mm/slub.c:kmalloc_large_node",
        "mm/slub.c:__free_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:putback_movable_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581234432,
      "name": "mod_node_page_state",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581422752,
      "name": "mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:575",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/slab_common.c:kmalloc_order",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/gup.c:put_compound_head",
        "mm/gup.c:unpin_user_page",
        "mm/gup.c:__unpin_devmap_managed_user_page",
        "mm/mempolicy.c:migrate_page_add",
        "mm/slub.c:kfree",
        "mm/slub.c:kmalloc_large_node",
        "mm/slub.c:__free_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:putback_movable_pages",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:release_pte_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581422752,
      "name": "mod_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581466512,
      "name": "mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:589",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/gup.c:put_compound_head",
        "mm/mempolicy.c:migrate_page_add",
        "mm/slub.c:__free_slab",
        "mm/slub.c:allocate_slab",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:putback_movable_pages",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:release_pte_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581466512,
      "name": "mod_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581486880,
      "name": "mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:601",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/gup.c:put_compound_head",
        "mm/mempolicy.c:migrate_page_add",
        "mm/slub.c:__free_slab",
        "mm/slub.c:allocate_slab",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:putback_movable_pages",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:release_pte_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581486880,
      "name": "mod_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581742400,
      "name": "mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:647",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/gup.c:put_compound_head",
        "mm/mempolicy.c:migrate_page_add",
        "mm/slub.c:__free_slab",
        "mm/slub.c:allocate_slab",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:putback_movable_pages",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:release_pte_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581742400,
      "name": "mod_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582124192,
      "name": "mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:676",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__folio_end_writeback",
        "mm/page-writeback.c:folio_account_redirty",
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:pageout",
        "mm/vmscan.c:__acct_reclaim_writeback",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/gup.c:try_grab_page",
        "mm/gup.c:gup_put_folio",
        "mm/gup.c:try_grab_folio",
        "mm/mempolicy.c:migrate_page_add",
        "mm/slub.c:__free_slab",
        "mm/slub.c:allocate_slab",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:numamigrate_isolate_page",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:putback_movable_pages",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:release_pte_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582124192,
      "name": "mod_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
void mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582598736,
      "name": "mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:663",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:should_numa_migrate_memory",
        "mm/page-writeback.c:__folio_end_writeback",
        "mm/page-writeback.c:folio_account_redirty",
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:pageout",
        "mm/vmscan.c:__acct_reclaim_writeback",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/gup.c:collect_longterm_unpinnable_pages",
        "mm/gup.c:try_grab_page",
        "mm/gup.c:gup_put_folio",
        "mm/gup.c:try_grab_folio",
        "mm/mempolicy.c:migrate_page_add",
        "mm/slub.c:__free_slab",
        "mm/slub.c:allocate_slab",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:numamigrate_isolate_page",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:putback_movable_pages",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:release_pte_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582598736,
      "name": "mod_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
void mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582806368,
      "name": "mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:664",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:should_numa_migrate_memory",
        "mm/page-writeback.c:__folio_end_writeback",
        "mm/page-writeback.c:folio_account_redirty",
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:pageout",
        "mm/vmscan.c:__acct_reclaim_writeback",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/gup.c:collect_longterm_unpinnable_pages",
        "mm/gup.c:try_grab_page",
        "mm/gup.c:gup_put_folio",
        "mm/gup.c:try_grab_folio",
        "mm/mempolicy.c:migrate_folio_add",
        "mm/slub.c:__free_slab",
        "mm/slub.c:allocate_slab",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:numamigrate_isolate_page",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:migrate_folio_done",
        "mm/migrate.c:putback_movable_pages",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:release_pte_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582806368,
      "name": "mod_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
void mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582982096,
      "name": "mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:665",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:should_numa_migrate_memory",
        "mm/page-writeback.c:__folio_end_writeback",
        "mm/page-writeback.c:folio_redirty_for_writepage",
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:demote_folio_list",
        "mm/vmscan.c:pageout",
        "mm/vmscan.c:__acct_reclaim_writeback",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/gup.c:collect_longterm_unpinnable_pages",
        "mm/gup.c:try_grab_page",
        "mm/gup.c:gup_put_folio",
        "mm/gup.c:try_grab_folio",
        "mm/slub.c:__free_slab",
        "mm/slub.c:allocate_slab",
        "mm/mempolicy.c:migrate_folio_add",
        "mm/migrate.c:migrate_misplaced_folio",
        "mm/migrate.c:migrate_misplaced_folio",
        "mm/migrate.c:migrate_misplaced_folio",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate.c:migrate_folio_done",
        "mm/migrate.c:putback_movable_pages",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:release_pte_folio",
        "mm/memory-failure.c:soft_offline_in_use_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582982096,
      "name": "mod_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
void mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492625856,
      "name": "mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:575",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/slab_common.c:kmalloc_order",
        "mm/gup.c:__gup_longterm_locked",
        "mm/mempolicy.c:migrate_page_add",
        "mm/slub.c:kfree",
        "mm/slub.c:kmalloc_large_node",
        "mm/slub.c:__free_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:putback_movable_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492625856,
      "name": "mod_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
void mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226474980,
      "name": "mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:645",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/slab_common.c:kmalloc_order",
        "mm/gup.c:__gup_longterm_locked",
        "mm/slub.c:kfree",
        "mm/slub.c:__free_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:putback_movable_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226474980,
      "name": "mod_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285938016,
      "name": "mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:645",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/slab_common.c:kmalloc_order",
        "mm/gup.c:__gup_longterm_locked",
        "mm/mempolicy.c:migrate_page_add",
        "mm/slub.c:kfree",
        "mm/slub.c:kmalloc_large_node",
        "mm/slub.c:__free_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:putback_movable_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285938016,
      "name": "mod_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272645116,
      "name": "mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:645",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/slab_common.c:kmalloc_order",
        "mm/gup.c:__gup_longterm_locked",
        "mm/slub.c:kfree",
        "mm/slub.c:__free_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:putback_movable_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272645116,
      "name": "mod_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581203280,
      "name": "mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:575",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/slab_common.c:kmalloc_order",
        "mm/gup.c:__gup_longterm_locked",
        "mm/mempolicy.c:migrate_page_add",
        "mm/slub.c:kfree",
        "mm/slub.c:kmalloc_large_node",
        "mm/slub.c:__free_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:putback_movable_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581203280,
      "name": "mod_node_page_state",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581150032,
      "name": "mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:575",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/slab_common.c:kmalloc_order",
        "mm/gup.c:__gup_longterm_locked",
        "mm/mempolicy.c:migrate_page_add",
        "mm/slub.c:kfree",
        "mm/slub.c:kmalloc_large_node",
        "mm/slub.c:__free_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:putback_movable_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581150032,
      "name": "mod_node_page_state",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581194480,
      "name": "mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:575",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/slab_common.c:kmalloc_order",
        "mm/gup.c:__gup_longterm_locked",
        "mm/mempolicy.c:migrate_page_add",
        "mm/slub.c:kfree",
        "mm/slub.c:kmalloc_large_node",
        "mm/slub.c:__free_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:putback_movable_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581194480,
      "name": "mod_node_page_state",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581257760,
      "name": "mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:575",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/slab_common.c:kmalloc_order",
        "mm/gup.c:__gup_longterm_locked",
        "mm/mempolicy.c:migrate_page_add",
        "mm/slub.c:kfree",
        "mm/slub.c:kmalloc_large_node",
        "mm/slub.c:__free_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:do_pages_move",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:putback_movable_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581257760,
      "name": "mod_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
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
