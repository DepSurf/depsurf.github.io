# Function: <code>__mem_cgroup_flush_stats</code>

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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void __mem_cgroup_flush_stats()
```

```json
{
  "name": "__mem_cgroup_flush_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582332944,
      "name": "__mem_cgroup_flush_stats",
      "external": false,
      "loc": "mm/memcontrol.c:667",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "mm/memcontrol.c:flush_memcg_stats_dwork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582332944,
      "name": "__mem_cgroup_flush_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void __mem_cgroup_flush_stats()
```

```json
{
  "name": "__mem_cgroup_flush_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582816256,
      "name": "__mem_cgroup_flush_stats",
      "external": false,
      "loc": "mm/memcontrol.c:634",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_read_u64",
        "mm/memcontrol.c:mem_cgroup_read_u64",
        "mm/memcontrol.c:memory_stat_format",
        "mm/memcontrol.c:flush_memcg_stats_dwork",
        "mm/memcontrol.c:mem_cgroup_flush_stats_delayed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582816256,
      "name": "__mem_cgroup_flush_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void __mem_cgroup_flush_stats()
```

```json
{
  "name": "__mem_cgroup_flush_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583362528,
      "name": "__mem_cgroup_flush_stats",
      "external": false,
      "loc": "mm/memcontrol.c:627",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:__mem_cgroup_threshold",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:flush_memcg_stats_dwork",
        "mm/memcontrol.c:mem_cgroup_flush_stats_delayed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583362528,
      "name": "__mem_cgroup_flush_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    }
  ]
}
```
</details>
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
void __mem_cgroup_flush_stats()
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void __mem_cgroup_flush_stats()
```
</details>
</li>
</ul>
