# Function: <code>mem_cgroup_page_lruvec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct lruvec * mem_cgroup_page_lruvec(struct page * page, struct zone * zone)
```

```json
{
  "name": "mem_cgroup_page_lruvec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580937200,
      "name": "mem_cgroup_page_lruvec",
      "external": true,
      "loc": "mm/memcontrol.c:1083",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__page_cache_release",
        "mm/swap.c:release_pages",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap.c:add_page_to_unevictable_list",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/memcontrol.c:lock_page_lru",
        "mm/memcontrol.c:unlock_page_lru"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580937200,
      "name": "mem_cgroup_page_lruvec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
struct lruvec * mem_cgroup_page_lruvec(struct page * page, struct pglist_data * pgdat)
```

```json
{
  "name": "mem_cgroup_page_lruvec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581091826,
      "name": "mem_cgroup_page_lruvec",
      "external": true,
      "loc": "mm/memcontrol.c:932",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ],
      "caller_func": [
        "mm/swap.c:release_pages",
        "mm/swap.c:add_page_to_unevictable_list",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:isolate_lru_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581084544,
      "name": "mem_cgroup_page_lruvec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
struct lruvec * mem_cgroup_page_lruvec(struct page * page, struct pglist_data * pgdat)
```

```json
{
  "name": "mem_cgroup_page_lruvec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581167067,
      "name": "mem_cgroup_page_lruvec",
      "external": true,
      "loc": "mm/memcontrol.c:971",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ],
      "caller_func": [
        "mm/swap.c:release_pages",
        "mm/swap.c:add_page_to_unevictable_list",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:isolate_lru_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581159264,
      "name": "mem_cgroup_page_lruvec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
struct lruvec * mem_cgroup_page_lruvec(struct page * page, struct pglist_data * pgdat)
```

```json
{
  "name": "mem_cgroup_page_lruvec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581214857,
      "name": "mem_cgroup_page_lruvec",
      "external": true,
      "loc": "mm/memcontrol.c:941",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/swap.c:release_pages",
        "mm/swap.c:add_page_to_unevictable_list",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:isolate_lru_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581207008,
      "name": "mem_cgroup_page_lruvec",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct lruvec * mem_cgroup_page_lruvec(struct page * page, struct pglist_data * pgdat)
```

```json
{
  "name": "mem_cgroup_page_lruvec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581345481,
      "name": "mem_cgroup_page_lruvec",
      "external": true,
      "loc": "mm/memcontrol.c:955",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/swap.c:release_pages",
        "mm/swap.c:add_page_to_unevictable_list",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:isolate_lru_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581337376,
      "name": "mem_cgroup_page_lruvec",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct lruvec * mem_cgroup_page_lruvec(struct page * page, struct pglist_data * pgdat)
```

```json
{
  "name": "mem_cgroup_page_lruvec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581493385,
      "name": "mem_cgroup_page_lruvec",
      "external": true,
      "loc": "mm/memcontrol.c:926",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/swap.c:release_pages",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:isolate_lru_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581485296,
      "name": "mem_cgroup_page_lruvec",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct lruvec * mem_cgroup_page_lruvec(struct page * page, struct pglist_data * pgdat)
```

```json
{
  "name": "mem_cgroup_page_lruvec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581571072,
      "name": "mem_cgroup_page_lruvec",
      "external": true,
      "loc": "mm/memcontrol.c:1100",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/swap.c:release_pages",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:isolate_lru_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581571072,
      "name": "mem_cgroup_page_lruvec",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct lruvec * mem_cgroup_page_lruvec(struct page * page, struct pglist_data * pgdat)
```

```json
{
  "name": "mem_cgroup_page_lruvec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581682528,
      "name": "mem_cgroup_page_lruvec",
      "external": true,
      "loc": "mm/memcontrol.c:1236",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/swap.c:release_pages",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/huge_memory.c:__split_huge_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581682528,
      "name": "mem_cgroup_page_lruvec",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct lruvec * mem_cgroup_page_lruvec(struct page * page, struct pglist_data * pgdat)
```

```json
{
  "name": "mem_cgroup_page_lruvec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581754928,
      "name": "mem_cgroup_page_lruvec",
      "external": true,
      "loc": "mm/memcontrol.c:1247",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/swap.c:release_pages",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/huge_memory.c:__split_huge_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581754928,
      "name": "mem_cgroup_page_lruvec",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct lruvec * mem_cgroup_page_lruvec(struct page * page, struct pglist_data * pgdat)
```

```json
{
  "name": "mem_cgroup_page_lruvec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581974688,
      "name": "mem_cgroup_page_lruvec",
      "external": true,
      "loc": "mm/memcontrol.c:1207",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_note_cost_page",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:isolate_lru_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/workingset.c:workingset_activation",
        "mm/huge_memory.c:__split_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581974688,
      "name": "mem_cgroup_page_lruvec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
  "name": "mem_cgroup_page_lruvec",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581362284,
      "name": "mem_cgroup_page_lruvec",
      "external": false,
      "loc": "include/linux/memcontrol.h:663",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:test_clear_page_writeback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581377442,
      "name": "mem_cgroup_page_lruvec",
      "external": false,
      "loc": "include/linux/memcontrol.h:663",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_note_cost_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581518813,
      "name": "mem_cgroup_page_lruvec",
      "external": false,
      "loc": "include/linux/memcontrol.h:663",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581536617,
      "name": "mem_cgroup_page_lruvec",
      "external": false,
      "loc": "include/linux/memcontrol.h:663",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_activation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582024254,
      "name": "mem_cgroup_page_lruvec",
      "external": false,
      "loc": "include/linux/memcontrol.h:663",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:lock_page_lruvec_irqsave",
        "mm/memcontrol.c:lock_page_lruvec_irq",
        "mm/memcontrol.c:lock_page_lruvec"
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
  "name": "mem_cgroup_page_lruvec",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581398193,
      "name": "mem_cgroup_page_lruvec",
      "external": false,
      "loc": "include/linux/memcontrol.h:750",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_note_cost_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581538873,
      "name": "mem_cgroup_page_lruvec",
      "external": false,
      "loc": "include/linux/memcontrol.h:750",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581558649,
      "name": "mem_cgroup_page_lruvec",
      "external": false,
      "loc": "include/linux/memcontrol.h:750",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_activation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582050770,
      "name": "mem_cgroup_page_lruvec",
      "external": false,
      "loc": "include/linux/memcontrol.h:750",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:lock_page_lruvec_irqsave",
        "mm/memcontrol.c:lock_page_lruvec_irq",
        "mm/memcontrol.c:lock_page_lruvec"
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
  "name": "mem_cgroup_page_lruvec",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581648385,
      "name": "mem_cgroup_page_lruvec",
      "external": false,
      "loc": "include/linux/memcontrol.h:762",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_note_cost_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581799172,
      "name": "mem_cgroup_page_lruvec",
      "external": false,
      "loc": "include/linux/memcontrol.h:762",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581822682,
      "name": "mem_cgroup_page_lruvec",
      "external": false,
      "loc": "include/linux/memcontrol.h:762",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_activation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582357478,
      "name": "mem_cgroup_page_lruvec",
      "external": false,
      "loc": "include/linux/memcontrol.h:762",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:lock_page_lruvec_irqsave",
        "mm/memcontrol.c:lock_page_lruvec_irq",
        "mm/memcontrol.c:lock_page_lruvec"
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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
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
struct lruvec * mem_cgroup_page_lruvec(struct page * page, struct pglist_data * pgdat)
```

```json
{
  "name": "mem_cgroup_page_lruvec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493208456,
      "name": "mem_cgroup_page_lruvec",
      "external": true,
      "loc": "mm/memcontrol.c:1247",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/swap.c:release_pages",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/huge_memory.c:__split_huge_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493208456,
      "name": "mem_cgroup_page_lruvec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct lruvec * mem_cgroup_page_lruvec(struct page * page, struct pglist_data * pgdat)
```

```json
{
  "name": "mem_cgroup_page_lruvec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226848836,
      "name": "mem_cgroup_page_lruvec",
      "external": true,
      "loc": "mm/memcontrol.c:1247",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/swap.c:release_pages",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/compaction.c:isolate_migratepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226839148,
      "name": "mem_cgroup_page_lruvec",
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
struct lruvec * mem_cgroup_page_lruvec(struct page * page, struct pglist_data * pgdat)
```

```json
{
  "name": "mem_cgroup_page_lruvec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286716912,
      "name": "mem_cgroup_page_lruvec",
      "external": true,
      "loc": "mm/memcontrol.c:1247",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/swap.c:release_pages",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/huge_memory.c:__split_huge_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286716912,
      "name": "mem_cgroup_page_lruvec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct lruvec * mem_cgroup_page_lruvec(struct page * page, struct pglist_data * pgdat)
```

```json
{
  "name": "mem_cgroup_page_lruvec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272993822,
      "name": "mem_cgroup_page_lruvec",
      "external": true,
      "loc": "mm/memcontrol.c:1247",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/swap.c:release_pages",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/compaction.c:isolate_migratepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272985714,
      "name": "mem_cgroup_page_lruvec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
struct lruvec * mem_cgroup_page_lruvec(struct page * page, struct pglist_data * pgdat)
```

```json
{
  "name": "mem_cgroup_page_lruvec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581723664,
      "name": "mem_cgroup_page_lruvec",
      "external": true,
      "loc": "mm/memcontrol.c:1247",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/swap.c:release_pages",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/huge_memory.c:__split_huge_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581723664,
      "name": "mem_cgroup_page_lruvec",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct lruvec * mem_cgroup_page_lruvec(struct page * page, struct pglist_data * pgdat)
```

```json
{
  "name": "mem_cgroup_page_lruvec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581662464,
      "name": "mem_cgroup_page_lruvec",
      "external": true,
      "loc": "mm/memcontrol.c:1247",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/swap.c:release_pages",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/huge_memory.c:__split_huge_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581662464,
      "name": "mem_cgroup_page_lruvec",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct lruvec * mem_cgroup_page_lruvec(struct page * page, struct pglist_data * pgdat)
```

```json
{
  "name": "mem_cgroup_page_lruvec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581714976,
      "name": "mem_cgroup_page_lruvec",
      "external": true,
      "loc": "mm/memcontrol.c:1247",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/swap.c:release_pages",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/huge_memory.c:__split_huge_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581714976,
      "name": "mem_cgroup_page_lruvec",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct lruvec * mem_cgroup_page_lruvec(struct page * page, struct pglist_data * pgdat)
```

```json
{
  "name": "mem_cgroup_page_lruvec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581782528,
      "name": "mem_cgroup_page_lruvec",
      "external": true,
      "loc": "mm/memcontrol.c:1247",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/swap.c:release_pages",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/huge_memory.c:__split_huge_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581782528,
      "name": "mem_cgroup_page_lruvec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pglist_data * pgdat</code>
</li>
<li>
<b>Param removed. </b>
<code>struct zone * zone</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
struct lruvec * mem_cgroup_page_lruvec(struct page * page, struct pglist_data * pgdat)
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
