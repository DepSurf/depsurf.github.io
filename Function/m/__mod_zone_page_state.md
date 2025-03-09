# Function: <code>__mod_zone_page_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "__mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580600208,
      "name": "__mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:221",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:setup_per_zone_wmarks",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/swap.c:__page_cache_release",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:release_pages",
        "mm/swap.c:add_page_to_unevictable_list",
        "mm/swap.c:lru_cache_add_active_or_unevictable",
        "mm/swap.c:lru_add_page_tail",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/memcontrol.c:lock_page_lru",
        "mm/memcontrol.c:unlock_page_lru",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580600208,
      "name": "__mod_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void __mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "__mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580702320,
      "name": "__mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:240",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_cache_add_active_or_unevictable",
        "mm/swap.c:add_page_to_unevictable_list",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:isolate_lru_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580702320,
      "name": "__mod_zone_page_state",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void __mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "__mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580768160,
      "name": "__mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:240",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_cache_add_active_or_unevictable",
        "mm/swap.c:add_page_to_unevictable_list",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:isolate_lru_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580768160,
      "name": "__mod_zone_page_state",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void __mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "__mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580804336,
      "name": "__mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:240",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_cache_add_active_or_unevictable",
        "mm/swap.c:add_page_to_unevictable_list",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:isolate_lru_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580804336,
      "name": "__mod_zone_page_state",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void __mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "__mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580893088,
      "name": "__mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:315",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_cache_add_active_or_unevictable",
        "mm/swap.c:add_page_to_unevictable_list",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:isolate_lru_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580893088,
      "name": "__mod_zone_page_state",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void __mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "__mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581028240,
      "name": "__mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:315",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_cache_add_active_or_unevictable",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:isolate_lru_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581028240,
      "name": "__mod_zone_page_state",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void __mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "__mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581105776,
      "name": "__mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:315",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_cache_add_active_or_unevictable",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:isolate_lru_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581105776,
      "name": "__mod_zone_page_state",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void __mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "__mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581171424,
      "name": "__mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:316",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_cache_add_active_or_unevictable",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581171424,
      "name": "__mod_zone_page_state",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void __mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "__mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581229424,
      "name": "__mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:316",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_cache_add_active_or_unevictable",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581229424,
      "name": "__mod_zone_page_state",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void __mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "__mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581422288,
      "name": "__mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:316",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_cache_add_active_or_unevictable",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__free_one_page",
        "mm/page_alloc.c:__free_one_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:set_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581422288,
      "name": "__mod_zone_page_state",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void __mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "__mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581465440,
      "name": "__mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:316",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_cache_add_inactive_or_unevictable",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__free_one_page",
        "mm/page_alloc.c:__free_one_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:set_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581465440,
      "name": "__mod_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void __mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "__mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581486240,
      "name": "__mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:316",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_cache_add_inactive_or_unevictable",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "mm/page_alloc.c:take_page_off_buddy",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__free_one_page",
        "mm/page_alloc.c:__free_one_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581486240,
      "name": "__mod_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void __mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "__mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581742752,
      "name": "__mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:314",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_cache_add_inactive_or_unevictable",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "mm/page_alloc.c:take_page_off_buddy",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:rmqueue_bulk",
        "mm/page_alloc.c:__free_one_page",
        "mm/page_alloc.c:__free_one_page",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581742752,
      "name": "__mod_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void __mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "__mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582124656,
      "name": "__mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:343",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:folio_account_dirtied",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:__folio_activate",
        "mm/swap.c:__folio_activate",
        "mm/swap.c:pagevec_move_tail_fn",
        "mm/swap.c:pagevec_move_tail_fn",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:folio_isolate_lru",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__mlock_new_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/page_alloc.c:take_page_off_buddy",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:rmqueue_bulk",
        "mm/page_alloc.c:split_free_page",
        "mm/page_alloc.c:__free_one_page",
        "mm/page_alloc.c:__free_one_page",
        "mm/page_alloc.c:__free_one_page",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582124656,
      "name": "__mod_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void __mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "__mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582599472,
      "name": "__mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:342",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:folio_account_dirtied",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_add_fn",
        "mm/swap.c:__page_cache_release",
        "mm/swap.c:lru_gen_add_folio",
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:drain_evictable",
        "mm/vmscan.c:drain_evictable",
        "mm/vmscan.c:drain_evictable",
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:reset_batch_size",
        "mm/vmscan.c:folio_inc_gen",
        "mm/vmscan.c:folio_inc_gen",
        "mm/vmscan.c:move_folios_to_lru",
        "mm/vmscan.c:folio_isolate_lru",
        "mm/vmscan.c:isolate_lru_folios",
        "mm/vmscan.c:lru_gen_add_folio",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__mlock_new_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/page_alloc.c:take_page_off_buddy",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:rmqueue_bulk",
        "mm/page_alloc.c:split_free_page",
        "mm/page_alloc.c:__free_one_page",
        "mm/page_alloc.c:__free_one_page",
        "mm/page_alloc.c:__free_one_page",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582599472,
      "name": "__mod_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void __mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "__mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582807088,
      "name": "__mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:343",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:folio_account_dirtied",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_add_fn",
        "mm/swap.c:__page_cache_release",
        "mm/swap.c:lru_gen_add_folio",
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:drain_evictable",
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:reset_batch_size",
        "mm/vmscan.c:folio_inc_gen",
        "mm/vmscan.c:folio_inc_gen",
        "mm/vmscan.c:move_folios_to_lru",
        "mm/vmscan.c:folio_isolate_lru",
        "mm/vmscan.c:isolate_lru_folios",
        "mm/vmscan.c:lru_gen_add_folio",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mlock.c:__munlock_folio",
        "mm/mlock.c:__munlock_folio",
        "mm/mlock.c:__munlock_folio",
        "mm/mlock.c:__mlock_new_folio",
        "mm/mlock.c:__mlock_folio",
        "mm/mlock.c:__mlock_folio",
        "mm/mlock.c:__mlock_folio",
        "mm/mlock.c:__mlock_folio",
        "mm/page_alloc.c:try_to_accept_memory",
        "mm/page_alloc.c:try_to_accept_memory",
        "mm/page_alloc.c:take_page_off_buddy",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:rmqueue_bulk",
        "mm/page_alloc.c:__free_pages_core",
        "mm/page_alloc.c:__free_pages_core",
        "mm/page_alloc.c:split_free_page",
        "mm/page_alloc.c:__free_one_page",
        "mm/page_alloc.c:__free_one_page",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582807088,
      "name": "__mod_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void __mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "__mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582981104,
      "name": "__mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:342",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:folio_account_dirtied",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_add_fn",
        "mm/swap.c:__page_cache_release",
        "mm/swap.c:lru_gen_add_folio",
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:drain_evictable",
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:reset_batch_size",
        "mm/vmscan.c:folio_inc_gen",
        "mm/vmscan.c:folio_inc_gen",
        "mm/vmscan.c:move_folios_to_lru",
        "mm/vmscan.c:folio_isolate_lru",
        "mm/vmscan.c:isolate_lru_folios",
        "mm/vmscan.c:lru_gen_add_folio",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mlock.c:__munlock_folio",
        "mm/mlock.c:__munlock_folio",
        "mm/mlock.c:__munlock_folio",
        "mm/mlock.c:__mlock_new_folio",
        "mm/mlock.c:__mlock_folio",
        "mm/mlock.c:__mlock_folio",
        "mm/mlock.c:__mlock_folio",
        "mm/mlock.c:__mlock_folio",
        "mm/page_alloc.c:try_to_accept_memory",
        "mm/page_alloc.c:try_to_accept_memory",
        "mm/page_alloc.c:take_page_off_buddy",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:rmqueue_bulk",
        "mm/page_alloc.c:__free_pages_core",
        "mm/page_alloc.c:__free_pages_core",
        "mm/page_alloc.c:split_free_page",
        "mm/page_alloc.c:__free_one_page",
        "mm/page_alloc.c:__free_one_page",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582981104,
      "name": "__mod_zone_page_state",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void __mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "__mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492627872,
      "name": "__mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:316",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_cache_add_active_or_unevictable",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__free_one_page",
        "mm/page_alloc.c:__free_one_page",
        "mm/page_alloc.c:__free_one_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492627872,
      "name": "__mod_zone_page_state",
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
void __mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "__mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226474576,
      "name": "__mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:316",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_cache_add_active_or_unevictable",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226474576,
      "name": "__mod_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void __mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "__mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285937584,
      "name": "__mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:316",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_cache_add_active_or_unevictable",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285937584,
      "name": "__mod_zone_page_state",
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
void __mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "__mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272644696,
      "name": "__mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:316",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_cache_add_active_or_unevictable",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/vmstat.c:mod_zone_page_state",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272644696,
      "name": "__mod_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void __mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "__mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581198272,
      "name": "__mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:316",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_cache_add_active_or_unevictable",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581198272,
      "name": "__mod_zone_page_state",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void __mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "__mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581145024,
      "name": "__mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:316",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_cache_add_active_or_unevictable",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581145024,
      "name": "__mod_zone_page_state",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void __mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "__mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581189472,
      "name": "__mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:316",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_cache_add_active_or_unevictable",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581189472,
      "name": "__mod_zone_page_state",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void __mod_zone_page_state(struct zone * zone, enum zone_stat_item item, long int delta)
```

```json
{
  "name": "__mod_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581252800,
      "name": "__mod_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:316",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_cache_add_active_or_unevictable",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_page",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/page_isolation.c:unset_migratetype_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581252800,
      "name": "__mod_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
