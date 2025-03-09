# Function: <code>mem_cgroup_update_lru_size</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void mem_cgroup_update_lru_size(struct lruvec * lruvec, enum lru_list lru, int nr_pages)
```

```json
{
  "name": "mem_cgroup_update_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580937296,
      "name": "mem_cgroup_update_lru_size",
      "external": true,
      "loc": "mm/memcontrol.c:1124",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__page_cache_release",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:release_pages",
        "mm/swap.c:add_page_to_unevictable_list",
        "mm/swap.c:lru_add_page_tail",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memcontrol.c:lock_page_lru",
        "mm/memcontrol.c:unlock_page_lru"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580937296,
      "name": "mem_cgroup_update_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mem_cgroup_update_lru_size(struct lruvec * lruvec, enum lru_list lru, int nr_pages)
```

```json
{
  "name": "mem_cgroup_update_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581084624,
      "name": "mem_cgroup_update_lru_size",
      "external": true,
      "loc": "mm/memcontrol.c:974",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
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
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581084624,
      "name": "mem_cgroup_update_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mem_cgroup_update_lru_size(struct lruvec * lruvec, enum lru_list lru, int zid, int nr_pages)
```

```json
{
  "name": "mem_cgroup_update_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581159344,
      "name": "mem_cgroup_update_lru_size",
      "external": true,
      "loc": "mm/memcontrol.c:1014",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
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
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581159344,
      "name": "mem_cgroup_update_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mem_cgroup_update_lru_size(struct lruvec * lruvec, enum lru_list lru, int zid, int nr_pages)
```

```json
{
  "name": "mem_cgroup_update_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581207088,
      "name": "mem_cgroup_update_lru_size",
      "external": true,
      "loc": "mm/memcontrol.c:984",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
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
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581207088,
      "name": "mem_cgroup_update_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mem_cgroup_update_lru_size(struct lruvec * lruvec, enum lru_list lru, int zid, int nr_pages)
```

```json
{
  "name": "mem_cgroup_update_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581337456,
      "name": "mem_cgroup_update_lru_size",
      "external": true,
      "loc": "mm/memcontrol.c:998",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
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
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581337456,
      "name": "mem_cgroup_update_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mem_cgroup_update_lru_size(struct lruvec * lruvec, enum lru_list lru, int zid, int nr_pages)
```

```json
{
  "name": "mem_cgroup_update_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581485376,
      "name": "mem_cgroup_update_lru_size",
      "external": true,
      "loc": "mm/memcontrol.c:969",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:isolate_lru_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581485376,
      "name": "mem_cgroup_update_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mem_cgroup_update_lru_size(struct lruvec * lruvec, enum lru_list lru, int zid, int nr_pages)
```

```json
{
  "name": "mem_cgroup_update_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581571152,
      "name": "mem_cgroup_update_lru_size",
      "external": true,
      "loc": "mm/memcontrol.c:1143",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:isolate_lru_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581571152,
      "name": "mem_cgroup_update_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void mem_cgroup_update_lru_size(struct lruvec * lruvec, enum lru_list lru, int zid, int nr_pages)
```

```json
{
  "name": "mem_cgroup_update_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581682608,
      "name": "mem_cgroup_update_lru_size",
      "external": true,
      "loc": "mm/memcontrol.c:1279",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581682608,
      "name": "mem_cgroup_update_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void mem_cgroup_update_lru_size(struct lruvec * lruvec, enum lru_list lru, int zid, int nr_pages)
```

```json
{
  "name": "mem_cgroup_update_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581755008,
      "name": "mem_cgroup_update_lru_size",
      "external": true,
      "loc": "mm/memcontrol.c:1290",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581755008,
      "name": "mem_cgroup_update_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void mem_cgroup_update_lru_size(struct lruvec * lruvec, enum lru_list lru, int zid, int nr_pages)
```

```json
{
  "name": "mem_cgroup_update_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581974768,
      "name": "mem_cgroup_update_lru_size",
      "external": true,
      "loc": "mm/memcontrol.c:1250",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581974768,
      "name": "mem_cgroup_update_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void mem_cgroup_update_lru_size(struct lruvec * lruvec, enum lru_list lru, int zid, int nr_pages)
```

```json
{
  "name": "mem_cgroup_update_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582024368,
      "name": "mem_cgroup_update_lru_size",
      "external": true,
      "loc": "mm/memcontrol.c:1406",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mlock.c:__munlock_pagevec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582024368,
      "name": "mem_cgroup_update_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void mem_cgroup_update_lru_size(struct lruvec * lruvec, enum lru_list lru, int zid, int nr_pages)
```

```json
{
  "name": "mem_cgroup_update_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582050880,
      "name": "mem_cgroup_update_lru_size",
      "external": true,
      "loc": "mm/memcontrol.c:1228",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mlock.c:__munlock_pagevec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582050880,
      "name": "mem_cgroup_update_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void mem_cgroup_update_lru_size(struct lruvec * lruvec, enum lru_list lru, int zid, int nr_pages)
```

```json
{
  "name": "mem_cgroup_update_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_update_lru_size",
      "external": true,
      "loc": "mm/memcontrol.c:1280",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mlock.c:__munlock_pagevec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592225043,
      "name": "mem_cgroup_update_lru_size.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071582357600,
      "name": "mem_cgroup_update_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void mem_cgroup_update_lru_size(struct lruvec * lruvec, enum lru_list lru, int zid, int nr_pages)
```

```json
{
  "name": "mem_cgroup_update_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_update_lru_size",
      "external": true,
      "loc": "mm/memcontrol.c:1283",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "mm/mlock.c:__mlock_new_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594004119,
      "name": "mem_cgroup_update_lru_size.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071582849088,
      "name": "mem_cgroup_update_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void mem_cgroup_update_lru_size(struct lruvec * lruvec, enum lru_list lru, int zid, int nr_pages)
```

```json
{
  "name": "mem_cgroup_update_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_update_lru_size",
      "external": true,
      "loc": "mm/memcontrol.c:1363",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_add_fn",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:drain_evictable",
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:move_folios_to_lru",
        "mm/vmscan.c:folio_isolate_lru",
        "mm/vmscan.c:isolate_lru_folios",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__mlock_new_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page",
        "mm/mlock.c:__mlock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596048804,
      "name": "mem_cgroup_update_lru_size.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071583395040,
      "name": "mem_cgroup_update_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void mem_cgroup_update_lru_size(struct lruvec * lruvec, enum lru_list lru, int zid, int nr_pages)
```

```json
{
  "name": "mem_cgroup_update_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_update_lru_size",
      "external": true,
      "loc": "mm/memcontrol.c:1387",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_add_fn",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:drain_evictable",
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:move_folios_to_lru",
        "mm/vmscan.c:folio_isolate_lru",
        "mm/vmscan.c:isolate_lru_folios",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mlock.c:__munlock_folio",
        "mm/mlock.c:__munlock_folio",
        "mm/mlock.c:__mlock_new_folio",
        "mm/mlock.c:__mlock_folio",
        "mm/mlock.c:__mlock_folio",
        "mm/mlock.c:__mlock_folio",
        "mm/mlock.c:__mlock_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596571278,
      "name": "mem_cgroup_update_lru_size.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071583614272,
      "name": "mem_cgroup_update_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void mem_cgroup_update_lru_size(struct lruvec * lruvec, enum lru_list lru, int zid, int nr_pages)
```

```json
{
  "name": "mem_cgroup_update_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_update_lru_size",
      "external": true,
      "loc": "mm/memcontrol.c:1438",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_add_fn",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:drain_evictable",
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:move_folios_to_lru",
        "mm/vmscan.c:folio_isolate_lru",
        "mm/vmscan.c:isolate_lru_folios",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mlock.c:__munlock_folio",
        "mm/mlock.c:__munlock_folio",
        "mm/mlock.c:__mlock_new_folio",
        "mm/mlock.c:__mlock_folio",
        "mm/mlock.c:__mlock_folio",
        "mm/mlock.c:__mlock_folio",
        "mm/mlock.c:__mlock_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597475767,
      "name": "mem_cgroup_update_lru_size.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071583809168,
      "name": "mem_cgroup_update_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
void mem_cgroup_update_lru_size(struct lruvec * lruvec, enum lru_list lru, int zid, int nr_pages)
```

```json
{
  "name": "mem_cgroup_update_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493208584,
      "name": "mem_cgroup_update_lru_size",
      "external": true,
      "loc": "mm/memcontrol.c:1290",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493208584,
      "name": "mem_cgroup_update_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void mem_cgroup_update_lru_size(struct lruvec * lruvec, enum lru_list lru, int zid, int nr_pages)
```

```json
{
  "name": "mem_cgroup_update_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226839236,
      "name": "mem_cgroup_update_lru_size",
      "external": true,
      "loc": "mm/memcontrol.c:1290",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:release_pages",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226839236,
      "name": "mem_cgroup_update_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void mem_cgroup_update_lru_size(struct lruvec * lruvec, enum lru_list lru, int zid, int nr_pages)
```

```json
{
  "name": "mem_cgroup_update_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286717040,
      "name": "mem_cgroup_update_lru_size",
      "external": true,
      "loc": "mm/memcontrol.c:1290",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286717040,
      "name": "mem_cgroup_update_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
void mem_cgroup_update_lru_size(struct lruvec * lruvec, enum lru_list lru, int zid, int nr_pages)
```

```json
{
  "name": "mem_cgroup_update_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272985816,
      "name": "mem_cgroup_update_lru_size",
      "external": true,
      "loc": "mm/memcontrol.c:1290",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:release_pages",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272985816,
      "name": "mem_cgroup_update_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void mem_cgroup_update_lru_size(struct lruvec * lruvec, enum lru_list lru, int zid, int nr_pages)
```

```json
{
  "name": "mem_cgroup_update_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581723744,
      "name": "mem_cgroup_update_lru_size",
      "external": true,
      "loc": "mm/memcontrol.c:1290",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581723744,
      "name": "mem_cgroup_update_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void mem_cgroup_update_lru_size(struct lruvec * lruvec, enum lru_list lru, int zid, int nr_pages)
```

```json
{
  "name": "mem_cgroup_update_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581662544,
      "name": "mem_cgroup_update_lru_size",
      "external": true,
      "loc": "mm/memcontrol.c:1290",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581662544,
      "name": "mem_cgroup_update_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void mem_cgroup_update_lru_size(struct lruvec * lruvec, enum lru_list lru, int zid, int nr_pages)
```

```json
{
  "name": "mem_cgroup_update_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581715056,
      "name": "mem_cgroup_update_lru_size",
      "external": true,
      "loc": "mm/memcontrol.c:1290",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581715056,
      "name": "mem_cgroup_update_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void mem_cgroup_update_lru_size(struct lruvec * lruvec, enum lru_list lru, int zid, int nr_pages)
```

```json
{
  "name": "mem_cgroup_update_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581782608,
      "name": "mem_cgroup_update_lru_size",
      "external": true,
      "loc": "mm/memcontrol.c:1290",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:release_pages",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581782608,
      "name": "mem_cgroup_update_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int zid</code>
</li>
<li>
<b>Param reordered. </b>
<code>lruvec, lru, nr_pages</code> ➡️ <code>lruvec, lru, zid, nr_pages</code>
</li>
</ul>
</details>
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
