# Function: <code>__mod_node_page_state</code>

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
void __mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "__mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580702416,
      "name": "__mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:260",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__delete_from_page_cache",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:add_page_to_unevictable_list",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:isolate_lru_page",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580702416,
      "name": "__mod_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void __mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "__mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580768256,
      "name": "__mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:260",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__delete_from_page_cache",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:add_page_to_unevictable_list",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:isolate_lru_page",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580768256,
      "name": "__mod_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void __mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "__mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580804432,
      "name": "__mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:260",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__delete_from_page_cache",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:add_page_to_unevictable_list",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:isolate_lru_page",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:__add_to_swap_cache",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580804432,
      "name": "__mod_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void __mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "__mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580893184,
      "name": "__mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:335",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:add_page_to_unevictable_list",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:isolate_lru_page",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:__add_to_swap_cache",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580893184,
      "name": "__mod_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void __mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "__mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581028336,
      "name": "__mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:335",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:isolate_lru_page",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:__add_to_swap_cache",
        "mm/slub.c:__free_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581028336,
      "name": "__mod_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void __mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "__mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581105872,
      "name": "__mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:335",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:isolate_lru_page",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/slub.c:__free_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581105872,
      "name": "__mod_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void __mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "__mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581171520,
      "name": "__mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:336",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "mm/memcontrol.c:__mod_lruvec_slab_state",
        "mm/memcontrol.c:__mod_lruvec_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581171520,
      "name": "__mod_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void __mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "__mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581229520,
      "name": "__mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:336",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:__mod_lruvec_slab_state",
        "mm/memcontrol.c:__mod_lruvec_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581229520,
      "name": "__mod_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void __mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "__mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581422384,
      "name": "__mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:336",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_delete_from_page_cache",
        "mm/shmem.c:shmem_delete_from_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_anon_compound_rmap",
        "mm/rmap.c:page_remove_anon_compound_rmap",
        "mm/rmap.c:page_remove_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:__mod_lruvec_slab_state",
        "mm/memcontrol.c:__mod_lruvec_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581422384,
      "name": "__mod_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void __mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "__mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581465552,
      "name": "__mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:336",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/memcontrol.c:__mod_lruvec_kmem_state",
        "mm/memcontrol.c:__mod_lruvec_page_state",
        "mm/memcontrol.c:__mod_lruvec_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581465552,
      "name": "__mod_node_page_state",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void __mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "__mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581486352,
      "name": "__mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:336",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/memcontrol.c:__mod_lruvec_kmem_state",
        "mm/memcontrol.c:__mod_lruvec_page_state",
        "mm/memcontrol.c:__mod_lruvec_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581486352,
      "name": "__mod_node_page_state",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void __mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "__mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581741920,
      "name": "__mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:347",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/memcontrol.c:__mod_lruvec_kmem_state",
        "mm/memcontrol.c:__mod_lruvec_page_state",
        "mm/memcontrol.c:__mod_lruvec_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581741920,
      "name": "__mod_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void __mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "__mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582123632,
      "name": "__mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:376",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:folio_account_dirtied",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/memcontrol.c:__mod_lruvec_kmem_state",
        "mm/memcontrol.c:__mod_lruvec_page_state",
        "mm/memcontrol.c:__mod_lruvec_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582123632,
      "name": "__mod_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
void __mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "__mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582598256,
      "name": "__mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:373",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:folio_account_dirtied",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/memcontrol.c:__mod_lruvec_kmem_state",
        "mm/memcontrol.c:__mod_lruvec_page_state",
        "mm/memcontrol.c:__mod_lruvec_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582598256,
      "name": "__mod_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
void __mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "__mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582805888,
      "name": "__mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:374",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:folio_account_dirtied",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/memcontrol.c:__mod_lruvec_kmem_state",
        "mm/memcontrol.c:__mod_lruvec_page_state",
        "mm/memcontrol.c:__mod_lruvec_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582805888,
      "name": "__mod_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
void __mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "__mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582980448,
      "name": "__mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:373",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:folio_account_dirtied",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/memcontrol.c:__mod_lruvec_kmem_state",
        "mm/memcontrol.c:__lruvec_stat_mod_folio",
        "mm/memcontrol.c:__mod_lruvec_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582980448,
      "name": "__mod_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
void __mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "__mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492628096,
      "name": "__mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:336",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:__mod_lruvec_slab_state",
        "mm/memcontrol.c:__mod_lruvec_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492628096,
      "name": "__mod_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void __mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "__mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226474800,
      "name": "__mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:336",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/vmstat.c:mod_node_page_state",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/memcontrol.c:__mod_lruvec_slab_state",
        "mm/memcontrol.c:__mod_lruvec_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226474800,
      "name": "__mod_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void __mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "__mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285937840,
      "name": "__mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:336",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/vmstat.c:mod_node_page_state",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:__mod_lruvec_slab_state",
        "mm/memcontrol.c:__mod_lruvec_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285937840,
      "name": "__mod_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void __mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "__mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272644938,
      "name": "__mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:336",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/vmstat.c:mod_node_page_state",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/memcontrol.c:__mod_lruvec_slab_state",
        "mm/memcontrol.c:__mod_lruvec_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272644938,
      "name": "__mod_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void __mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "__mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581198368,
      "name": "__mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:336",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:__mod_lruvec_slab_state",
        "mm/memcontrol.c:__mod_lruvec_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581198368,
      "name": "__mod_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void __mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "__mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581145120,
      "name": "__mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:336",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:__mod_lruvec_slab_state",
        "mm/memcontrol.c:__mod_lruvec_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581145120,
      "name": "__mod_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void __mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "__mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581189568,
      "name": "__mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:336",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:__mod_lruvec_slab_state",
        "mm/memcontrol.c:__mod_lruvec_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581189568,
      "name": "__mod_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void __mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
```

```json
{
  "name": "__mod_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581252896,
      "name": "__mod_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:336",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:__mod_lruvec_slab_state",
        "mm/memcontrol.c:__mod_lruvec_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581252896,
      "name": "__mod_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void __mod_node_page_state(struct pglist_data * pgdat, enum node_stat_item item, long int delta)
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
