# Function: <code>mem_cgroup_iter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct mem_cgroup * mem_cgroup_iter(struct mem_cgroup * root, struct mem_cgroup * prev, struct mem_cgroup_reclaim_cookie * reclaim)
```

```json
{
  "name": "mem_cgroup_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580928000,
      "name": "mem_cgroup_iter",
      "external": true,
      "loc": "mm/memcontrol.c:871",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:drop_slab_node",
        "mm/vmscan.c:shrink_zone",
        "mm/vmscan.c:shrink_zone",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:tree_stat",
        "mm/memcontrol.c:tree_stat",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:mem_cgroup_count_children",
        "mm/memcontrol.c:mem_cgroup_count_children",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "mm/memcontrol.c:mem_cgroup_print_oom_info",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580928000,
      "name": "mem_cgroup_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 898
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
struct mem_cgroup * mem_cgroup_iter(struct mem_cgroup * root, struct mem_cgroup * prev, struct mem_cgroup_reclaim_cookie * reclaim)
```

```json
{
  "name": "mem_cgroup_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581074512,
      "name": "mem_cgroup_iter",
      "external": true,
      "loc": "mm/memcontrol.c:764",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:drop_slab_node",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "mm/memcontrol.c:mem_cgroup_count_children",
        "mm/memcontrol.c:mem_cgroup_count_children",
        "mm/memcontrol.c:mem_cgroup_print_oom_info",
        "mm/memcontrol.c:mem_cgroup_print_oom_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581074512,
      "name": "mem_cgroup_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 717
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
struct mem_cgroup * mem_cgroup_iter(struct mem_cgroup * root, struct mem_cgroup * prev, struct mem_cgroup_reclaim_cookie * reclaim)
```

```json
{
  "name": "mem_cgroup_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581150128,
      "name": "mem_cgroup_iter",
      "external": true,
      "loc": "mm/memcontrol.c:766",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:drop_slab_node",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_count_children",
        "mm/memcontrol.c:mem_cgroup_count_children",
        "mm/memcontrol.c:mem_cgroup_print_oom_info",
        "mm/memcontrol.c:mem_cgroup_print_oom_info",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581150128,
      "name": "mem_cgroup_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 757
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
struct mem_cgroup * mem_cgroup_iter(struct mem_cgroup * root, struct mem_cgroup * prev, struct mem_cgroup_reclaim_cookie * reclaim)
```

```json
{
  "name": "mem_cgroup_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581197264,
      "name": "mem_cgroup_iter",
      "external": true,
      "loc": "mm/memcontrol.c:736",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:drop_slab_node",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_count_children",
        "mm/memcontrol.c:mem_cgroup_count_children",
        "mm/memcontrol.c:mem_cgroup_print_oom_info",
        "mm/memcontrol.c:mem_cgroup_print_oom_info",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581197264,
      "name": "mem_cgroup_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 739
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
struct mem_cgroup * mem_cgroup_iter(struct mem_cgroup * root, struct mem_cgroup * prev, struct mem_cgroup_reclaim_cookie * reclaim)
```

```json
{
  "name": "mem_cgroup_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581327216,
      "name": "mem_cgroup_iter",
      "external": true,
      "loc": "mm/memcontrol.c:750",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:drop_slab_node",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_count_children",
        "mm/memcontrol.c:mem_cgroup_count_children",
        "mm/memcontrol.c:mem_cgroup_print_oom_info",
        "mm/memcontrol.c:mem_cgroup_print_oom_info",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581327216,
      "name": "mem_cgroup_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 750
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
struct mem_cgroup * mem_cgroup_iter(struct mem_cgroup * root, struct mem_cgroup * prev, struct mem_cgroup_reclaim_cookie * reclaim)
```

```json
{
  "name": "mem_cgroup_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581475328,
      "name": "mem_cgroup_iter",
      "external": true,
      "loc": "mm/memcontrol.c:721",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:drop_slab_node",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memory_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_print_oom_info",
        "mm/memcontrol.c:mem_cgroup_print_oom_info",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581475328,
      "name": "mem_cgroup_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 754
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
struct mem_cgroup * mem_cgroup_iter(struct mem_cgroup * root, struct mem_cgroup * prev, struct mem_cgroup_reclaim_cookie * reclaim)
```

```json
{
  "name": "mem_cgroup_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581557728,
      "name": "mem_cgroup_iter",
      "external": true,
      "loc": "mm/memcontrol.c:910",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:drop_slab_node",
        "mm/vmscan.c:drop_slab_node",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:accumulate_memcg_tree",
        "mm/memcontrol.c:accumulate_memcg_tree",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_print_oom_meminfo",
        "mm/memcontrol.c:mem_cgroup_print_oom_meminfo",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:memcg_expand_shrinker_maps",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581557728,
      "name": "mem_cgroup_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 704
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
struct mem_cgroup * mem_cgroup_iter(struct mem_cgroup * root, struct mem_cgroup * prev, struct mem_cgroup_reclaim_cookie * reclaim)
```

```json
{
  "name": "mem_cgroup_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581675296,
      "name": "mem_cgroup_iter",
      "external": true,
      "loc": "mm/memcontrol.c:1027",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:drop_slab_node",
        "mm/vmscan.c:drop_slab_node",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:memcg_expand_shrinker_maps",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581675296,
      "name": "mem_cgroup_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 713
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
struct mem_cgroup * mem_cgroup_iter(struct mem_cgroup * root, struct mem_cgroup * prev, struct mem_cgroup_reclaim_cookie * reclaim)
```

```json
{
  "name": "mem_cgroup_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581747696,
      "name": "mem_cgroup_iter",
      "external": true,
      "loc": "mm/memcontrol.c:1038",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:drop_slab_node",
        "mm/vmscan.c:drop_slab_node",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:memcg_expand_shrinker_maps",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581747696,
      "name": "mem_cgroup_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 707
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
struct mem_cgroup * mem_cgroup_iter(struct mem_cgroup * root, struct mem_cgroup * prev, struct mem_cgroup_reclaim_cookie * reclaim)
```

```json
{
  "name": "mem_cgroup_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581968112,
      "name": "mem_cgroup_iter",
      "external": true,
      "loc": "mm/memcontrol.c:1003",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:age_active_anon",
        "mm/vmscan.c:age_active_anon",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:drop_slab_node",
        "mm/vmscan.c:drop_slab_node",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581968112,
      "name": "mem_cgroup_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 665
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
struct mem_cgroup * mem_cgroup_iter(struct mem_cgroup * root, struct mem_cgroup * prev, struct mem_cgroup_reclaim_cookie * reclaim)
```

```json
{
  "name": "mem_cgroup_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582017168,
      "name": "mem_cgroup_iter",
      "external": true,
      "loc": "mm/memcontrol.c:1135",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:age_active_anon",
        "mm/vmscan.c:age_active_anon",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:drop_slab_node",
        "mm/vmscan.c:drop_slab_node",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582017168,
      "name": "mem_cgroup_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 679
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
struct mem_cgroup * mem_cgroup_iter(struct mem_cgroup * root, struct mem_cgroup * prev, struct mem_cgroup_reclaim_cookie * reclaim)
```

```json
{
  "name": "mem_cgroup_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582043824,
      "name": "mem_cgroup_iter",
      "external": true,
      "loc": "mm/memcontrol.c:962",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:drop_slab_node",
        "mm/vmscan.c:drop_slab_node",
        "mm/vmscan.c:prealloc_shrinker",
        "mm/vmscan.c:prealloc_shrinker",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582043824,
      "name": "mem_cgroup_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 687
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
struct mem_cgroup * mem_cgroup_iter(struct mem_cgroup * root, struct mem_cgroup * prev, struct mem_cgroup_reclaim_cookie * reclaim)
```

```json
{
  "name": "mem_cgroup_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582350688,
      "name": "mem_cgroup_iter",
      "external": true,
      "loc": "mm/memcontrol.c:1017",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:drop_slab_node",
        "mm/vmscan.c:drop_slab_node",
        "mm/vmscan.c:prealloc_shrinker",
        "mm/vmscan.c:prealloc_shrinker",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582350688,
      "name": "mem_cgroup_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 687
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
struct mem_cgroup * mem_cgroup_iter(struct mem_cgroup * root, struct mem_cgroup * prev, struct mem_cgroup_reclaim_cookie * reclaim)
```

```json
{
  "name": "mem_cgroup_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582846560,
      "name": "mem_cgroup_iter",
      "external": true,
      "loc": "mm/memcontrol.c:999",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:drop_slab",
        "mm/vmscan.c:drop_slab",
        "mm/vmscan.c:prealloc_shrinker",
        "mm/vmscan.c:prealloc_shrinker",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582846560,
      "name": "mem_cgroup_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 750
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
struct mem_cgroup * mem_cgroup_iter(struct mem_cgroup * root, struct mem_cgroup * prev, struct mem_cgroup_reclaim_cookie * reclaim)
```

```json
{
  "name": "mem_cgroup_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583392336,
      "name": "mem_cgroup_iter",
      "external": true,
      "loc": "mm/memcontrol.c:1079",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:lru_gen_seq_next",
        "mm/vmscan.c:lru_gen_seq_start",
        "mm/vmscan.c:lru_gen_seq_start",
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:lru_gen_age_node",
        "mm/vmscan.c:lru_gen_age_node",
        "mm/vmscan.c:drop_slab",
        "mm/vmscan.c:drop_slab",
        "mm/vmscan.c:__prealloc_shrinker",
        "mm/vmscan.c:__prealloc_shrinker",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583392336,
      "name": "mem_cgroup_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 750
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
struct mem_cgroup * mem_cgroup_iter(struct mem_cgroup * root, struct mem_cgroup * prev, struct mem_cgroup_reclaim_cookie * reclaim)
```

```json
{
  "name": "mem_cgroup_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583611696,
      "name": "mem_cgroup_iter",
      "external": true,
      "loc": "mm/memcontrol.c:1104",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:lru_gen_seq_next",
        "mm/vmscan.c:lru_gen_seq_start",
        "mm/vmscan.c:lru_gen_seq_start",
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:lru_gen_age_node",
        "mm/vmscan.c:lru_gen_age_node",
        "mm/vmscan.c:drop_slab",
        "mm/vmscan.c:drop_slab",
        "mm/vmscan.c:__prealloc_shrinker",
        "mm/vmscan.c:__prealloc_shrinker",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583611696,
      "name": "mem_cgroup_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 669
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
struct mem_cgroup * mem_cgroup_iter(struct mem_cgroup * root, struct mem_cgroup * prev, struct mem_cgroup_reclaim_cookie * reclaim)
```

```json
{
  "name": "mem_cgroup_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583806592,
      "name": "mem_cgroup_iter",
      "external": true,
      "loc": "mm/memcontrol.c:1155",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:lru_gen_seq_next",
        "mm/vmscan.c:lru_gen_seq_start",
        "mm/vmscan.c:lru_gen_seq_start",
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:lru_gen_change_state",
        "mm/vmscan.c:lru_gen_age_node",
        "mm/vmscan.c:lru_gen_age_node",
        "mm/vmscan.c:drop_slab",
        "mm/vmscan.c:drop_slab",
        "mm/shrinker.c:shrinker_alloc",
        "mm/shrinker.c:shrinker_alloc",
        "mm/zswap.c:shrink_worker",
        "mm/zswap.c:zswap_memcg_offline_cleanup",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583806592,
      "name": "mem_cgroup_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 669
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
struct mem_cgroup * mem_cgroup_iter(struct mem_cgroup * root, struct mem_cgroup * prev, struct mem_cgroup_reclaim_cookie * reclaim)
```

```json
{
  "name": "mem_cgroup_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493200968,
      "name": "mem_cgroup_iter",
      "external": true,
      "loc": "mm/memcontrol.c:1038",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:drop_slab_node",
        "mm/vmscan.c:drop_slab_node",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:memcg_expand_shrinker_maps",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493200968,
      "name": "mem_cgroup_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 612
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
struct mem_cgroup * mem_cgroup_iter(struct mem_cgroup * root, struct mem_cgroup * prev, struct mem_cgroup_reclaim_cookie * reclaim)
```

```json
{
  "name": "mem_cgroup_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226832268,
      "name": "mem_cgroup_iter",
      "external": true,
      "loc": "mm/memcontrol.c:1038",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:drop_slab_node",
        "mm/vmscan.c:drop_slab_node",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:memcg_expand_shrinker_maps",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226832268,
      "name": "mem_cgroup_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 992
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
struct mem_cgroup * mem_cgroup_iter(struct mem_cgroup * root, struct mem_cgroup * prev, struct mem_cgroup_reclaim_cookie * reclaim)
```

```json
{
  "name": "mem_cgroup_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286705328,
      "name": "mem_cgroup_iter",
      "external": true,
      "loc": "mm/memcontrol.c:1038",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:drop_slab_node",
        "mm/vmscan.c:drop_slab_node",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:memcg_expand_shrinker_maps",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286705328,
      "name": "mem_cgroup_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1352
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
struct mem_cgroup * mem_cgroup_iter(struct mem_cgroup * root, struct mem_cgroup * prev, struct mem_cgroup_reclaim_cookie * reclaim)
```

```json
{
  "name": "mem_cgroup_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272979900,
      "name": "mem_cgroup_iter",
      "external": true,
      "loc": "mm/memcontrol.c:1038",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:drop_slab_node",
        "mm/vmscan.c:drop_slab_node",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:memcg_expand_shrinker_maps",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272979900,
      "name": "mem_cgroup_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 708
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
struct mem_cgroup * mem_cgroup_iter(struct mem_cgroup * root, struct mem_cgroup * prev, struct mem_cgroup_reclaim_cookie * reclaim)
```

```json
{
  "name": "mem_cgroup_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581716432,
      "name": "mem_cgroup_iter",
      "external": true,
      "loc": "mm/memcontrol.c:1038",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:drop_slab_node",
        "mm/vmscan.c:drop_slab_node",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:memcg_expand_shrinker_maps",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581716432,
      "name": "mem_cgroup_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 707
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
struct mem_cgroup * mem_cgroup_iter(struct mem_cgroup * root, struct mem_cgroup * prev, struct mem_cgroup_reclaim_cookie * reclaim)
```

```json
{
  "name": "mem_cgroup_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581655312,
      "name": "mem_cgroup_iter",
      "external": true,
      "loc": "mm/memcontrol.c:1038",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:drop_slab_node",
        "mm/vmscan.c:drop_slab_node",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:memcg_expand_shrinker_maps",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581655312,
      "name": "mem_cgroup_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 707
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
struct mem_cgroup * mem_cgroup_iter(struct mem_cgroup * root, struct mem_cgroup * prev, struct mem_cgroup_reclaim_cookie * reclaim)
```

```json
{
  "name": "mem_cgroup_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581707744,
      "name": "mem_cgroup_iter",
      "external": true,
      "loc": "mm/memcontrol.c:1038",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:drop_slab_node",
        "mm/vmscan.c:drop_slab_node",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:memcg_expand_shrinker_maps",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581707744,
      "name": "mem_cgroup_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 707
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
struct mem_cgroup * mem_cgroup_iter(struct mem_cgroup * root, struct mem_cgroup * prev, struct mem_cgroup_reclaim_cookie * reclaim)
```

```json
{
  "name": "mem_cgroup_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581775152,
      "name": "mem_cgroup_iter",
      "external": true,
      "loc": "mm/memcontrol.c:1038",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:drop_slab_node",
        "mm/vmscan.c:drop_slab_node",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:mem_cgroup_oom_notify",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_unmark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_mark_under_oom",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_unlock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:memcg_expand_shrinker_maps",
        "mm/memcontrol.c:memcg_expand_shrinker_maps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581775152,
      "name": "mem_cgroup_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 815
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
