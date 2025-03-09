# Function: <code>memcg_page_state</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcg_page_state",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580745447,
      "name": "memcg_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:491",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:inactive_list_is_low"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581205630,
      "name": "memcg_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:491",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_print_oom_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581187168,
      "name": "memcg_page_state.isra.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcg_page_state",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580832653,
      "name": "memcg_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:492",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:inactive_list_is_low"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581335985,
      "name": "memcg_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:492",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_print_oom_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581316480,
      "name": "memcg_page_state.isra.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcg_page_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580966901,
      "name": "memcg_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:525",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:inactive_list_is_low"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581483584,
      "name": "memcg_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:525",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:mem_cgroup_print_oom_info"
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
  "name": "memcg_page_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581043141,
      "name": "memcg_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:565",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:inactive_list_is_low"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581575437,
      "name": "memcg_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:565",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:accumulate_memcg_tree",
        "mm/memcontrol.c:mem_cgroup_print_oom_meminfo"
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
  "name": "memcg_page_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581662581,
      "name": "memcg_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:558",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format"
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
  "name": "memcg_page_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581734885,
      "name": "memcg_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:594",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcg_page_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581954063,
      "name": "memcg_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:571",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_read_u64",
        "mm/memcontrol.c:mem_cgroup_read_u64",
        "mm/memcontrol.c:mem_cgroup_read_u64",
        "mm/memcontrol.c:mem_cgroup_read_u64",
        "mm/memcontrol.c:mem_cgroup_read_u64",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcg_page_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582000239,
      "name": "memcg_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:889",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_read_u64",
        "mm/memcontrol.c:mem_cgroup_read_u64",
        "mm/memcontrol.c:mem_cgroup_read_u64",
        "mm/memcontrol.c:mem_cgroup_read_u64",
        "mm/memcontrol.c:mem_cgroup_read_u64",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format"
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
  "name": "memcg_page_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582055837,
      "name": "memcg_page_state",
      "external": false,
      "loc": "mm/memcontrol.c:650",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_read_u64",
        "mm/memcontrol.c:mem_cgroup_read_u64",
        "mm/memcontrol.c:mem_cgroup_read_u64",
        "mm/memcontrol.c:mem_cgroup_read_u64",
        "mm/memcontrol.c:mem_cgroup_read_u64",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format"
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
  "name": "memcg_page_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582363737,
      "name": "memcg_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:967",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_read_u64",
        "mm/memcontrol.c:mem_cgroup_read_u64",
        "mm/memcontrol.c:mem_cgroup_read_u64",
        "mm/memcontrol.c:mem_cgroup_read_u64",
        "mm/memcontrol.c:mem_cgroup_read_u64",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582713704,
      "name": "memcg_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:967",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id"
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
  "name": "memcg_page_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582816485,
      "name": "memcg_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:979",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:zswap_current_read",
        "mm/memcontrol.c:obj_cgroup_may_zswap",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_read_u64",
        "mm/memcontrol.c:mem_cgroup_read_u64",
        "mm/memcontrol.c:mem_cgroup_read_u64",
        "mm/memcontrol.c:mem_cgroup_read_u64",
        "mm/memcontrol.c:mem_cgroup_read_u64",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583257946,
      "name": "memcg_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:979",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int memcg_page_state(struct mem_cgroup * memcg, int idx)
```

```json
{
  "name": "memcg_page_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583362805,
      "name": "memcg_page_state",
      "external": true,
      "loc": "mm/memcontrol.c:725",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:zswap_current_read",
        "mm/memcontrol.c:obj_cgroup_may_zswap",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show"
      ],
      "caller_func": [
        "fs/fs-writeback.c:cgroup_writeback_by_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583383936,
      "name": "memcg_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int memcg_page_state(struct mem_cgroup * memcg, int idx)
```

```json
{
  "name": "memcg_page_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583582501,
      "name": "memcg_page_state",
      "external": true,
      "loc": "mm/memcontrol.c:750",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:zswap_current_read",
        "mm/memcontrol.c:obj_cgroup_may_zswap",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:memcg_numa_stat_show"
      ],
      "caller_func": [
        "fs/fs-writeback.c:cgroup_writeback_by_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583604528,
      "name": "memcg_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int memcg_page_state(struct mem_cgroup * memcg, int idx)
```

```json
{
  "name": "memcg_page_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583780724,
      "name": "memcg_page_state",
      "external": true,
      "loc": "mm/memcontrol.c:785",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:zswap_current_read",
        "mm/memcontrol.c:obj_cgroup_may_zswap",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:memcg_numa_stat_show"
      ],
      "caller_func": [
        "mm/zswap.c:zswap_shrinker_count",
        "mm/zswap.c:zswap_shrinker_count",
        "fs/fs-writeback.c:cgroup_writeback_by_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583798992,
      "name": "memcg_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "memcg_page_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493181448,
      "name": "memcg_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:594",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:mem_cgroup_read_u64",
        "mm/memcontrol.c:mem_cgroup_read_u64",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format"
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
  "name": "memcg_page_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226816952,
      "name": "memcg_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:594",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:mem_cgroup_read_u64",
        "mm/memcontrol.c:mem_cgroup_read_u64",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "memcg_page_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286685836,
      "name": "memcg_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:594",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "memcg_page_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272966364,
      "name": "memcg_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:594",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:mem_cgroup_read_u64",
        "mm/memcontrol.c:mem_cgroup_read_u64",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format"
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
  "name": "memcg_page_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581703621,
      "name": "memcg_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:594",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcg_page_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581642837,
      "name": "memcg_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:594",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcg_page_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581694933,
      "name": "memcg_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:594",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format"
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
  "name": "memcg_page_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581762757,
      "name": "memcg_page_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:594",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:memory_stat_format"
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
long unsigned int memcg_page_state(struct mem_cgroup * memcg, int idx)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
