# Function: <code>mem_cgroup_flush_stats</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mem_cgroup_flush_stats()
```

```json
{
  "name": "mem_cgroup_flush_stats",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582333164,
      "name": "mem_cgroup_flush_stats",
      "external": true,
      "loc": "mm/memcontrol.c:679",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_read_u64",
        "mm/memcontrol.c:mem_cgroup_read_u64",
        "mm/memcontrol.c:memory_stat_format"
      ],
      "caller_func": [
        "mm/vmscan.c:shrink_node",
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582344096,
      "name": "mem_cgroup_flush_stats",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mem_cgroup_flush_stats()
```

```json
{
  "name": "mem_cgroup_flush_stats",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582824742,
      "name": "mem_cgroup_flush_stats",
      "external": true,
      "loc": "mm/memcontrol.c:647",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_read_u64",
        "mm/memcontrol.c:mem_cgroup_read_u64",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:mem_cgroup_flush_stats_delayed"
      ],
      "caller_func": [
        "mm/vmscan.c:shrink_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582838640,
      "name": "mem_cgroup_flush_stats",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mem_cgroup_flush_stats()
```

```json
{
  "name": "mem_cgroup_flush_stats",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583368758,
      "name": "mem_cgroup_flush_stats",
      "external": true,
      "loc": "mm/memcontrol.c:640",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_flush_stats_delayed"
      ],
      "caller_func": [
        "mm/vmscan.c:prepare_scan_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583383760,
      "name": "mem_cgroup_flush_stats",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void mem_cgroup_flush_stats()
```

```json
{
  "name": "mem_cgroup_flush_stats",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583588502,
      "name": "mem_cgroup_flush_stats",
      "external": true,
      "loc": "mm/memcontrol.c:661",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_flush_stats_ratelimited"
      ],
      "caller_func": [
        "mm/vmscan.c:prepare_scan_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583604352,
      "name": "mem_cgroup_flush_stats",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mem_cgroup_flush_stats(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_flush_stats",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583780709,
      "name": "mem_cgroup_flush_stats",
      "external": true,
      "loc": "mm/memcontrol.c:756",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:zswap_current_read",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_flush_stats_ratelimited"
      ],
      "caller_func": [
        "mm/vmscan.c:prepare_scan_control",
        "mm/zswap.c:zswap_shrinker_count",
        "mm/memcontrol.c:zswap_current_read",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_flush_stats_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583777088,
      "name": "mem_cgroup_flush_stats.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    },
    {
      "addr": 18446744071583798864,
      "name": "mem_cgroup_flush_stats",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void mem_cgroup_flush_stats()
```
</details>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mem_cgroup * memcg</code>
</li>
</ul>
</details>
</li>
</ul>
