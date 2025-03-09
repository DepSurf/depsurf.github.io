# Function: <code>cgroup_file_notify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void cgroup_file_notify(struct cgroup_file * cfile)
```

```json
{
  "name": "cgroup_file_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579984320,
      "name": "cgroup_file_notify",
      "external": true,
      "loc": "kernel/cgroup.c:3720",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_update_populated",
        "mm/vmscan.c:shrink_zone",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579984320,
      "name": "cgroup_file_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void cgroup_file_notify(struct cgroup_file * cfile)
```

```json
{
  "name": "cgroup_file_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580011472,
      "name": "cgroup_file_notify",
      "external": true,
      "loc": "kernel/cgroup.c:3907",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_update_populated",
        "kernel/cgroup_pids.c:pids_can_fork",
        "mm/vmscan.c:shrink_node",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580011472,
      "name": "cgroup_file_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void cgroup_file_notify(struct cgroup_file * cfile)
```

```json
{
  "name": "cgroup_file_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580045056,
      "name": "cgroup_file_notify",
      "external": true,
      "loc": "kernel/cgroup.c:3918",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_update_populated",
        "kernel/cgroup_pids.c:pids_can_fork",
        "mm/vmscan.c:shrink_node",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580045056,
      "name": "cgroup_file_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void cgroup_file_notify(struct cgroup_file * cfile)
```

```json
{
  "name": "cgroup_file_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580044528,
      "name": "cgroup_file_notify",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:3425",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/pids.c:pids_can_fork",
        "mm/oom_kill.c:oom_kill_process",
        "mm/vmscan.c:shrink_node",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580044528,
      "name": "cgroup_file_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void cgroup_file_notify(struct cgroup_file * cfile)
```

```json
{
  "name": "cgroup_file_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580094288,
      "name": "cgroup_file_notify",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:3794",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/pids.c:pids_can_fork",
        "mm/oom_kill.c:oom_kill_process",
        "mm/vmscan.c:shrink_node",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580094288,
      "name": "cgroup_file_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void cgroup_file_notify(struct cgroup_file * cfile)
```

```json
{
  "name": "cgroup_file_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580153376,
      "name": "cgroup_file_notify",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:3822",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify_timer",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/pids.c:pids_can_fork",
        "mm/oom_kill.c:oom_kill_process",
        "mm/vmscan.c:shrink_node",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580153376,
      "name": "cgroup_file_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void cgroup_file_notify(struct cgroup_file * cfile)
```

```json
{
  "name": "cgroup_file_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580201024,
      "name": "cgroup_file_notify",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:3886",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify_timer",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/pids.c:pids_can_fork",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/vmscan.c:shrink_node",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580201024,
      "name": "cgroup_file_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void cgroup_file_notify(struct cgroup_file * cfile)
```

```json
{
  "name": "cgroup_file_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580248112,
      "name": "cgroup_file_notify",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4142",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify_timer",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/pids.c:pids_can_fork",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580248112,
      "name": "cgroup_file_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void cgroup_file_notify(struct cgroup_file * cfile)
```

```json
{
  "name": "cgroup_file_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580296336,
      "name": "cgroup_file_notify",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4144",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify_timer",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/pids.c:pids_can_fork",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580296336,
      "name": "cgroup_file_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void cgroup_file_notify(struct cgroup_file * cfile)
```

```json
{
  "name": "cgroup_file_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580367456,
      "name": "cgroup_file_notify",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4085",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify_timer",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/cgroup/pids.c:pids_can_fork",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580367456,
      "name": "cgroup_file_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void cgroup_file_notify(struct cgroup_file * cfile)
```

```json
{
  "name": "cgroup_file_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580354400,
      "name": "cgroup_file_notify",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4086",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify_timer",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/cgroup/pids.c:pids_can_fork",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580354400,
      "name": "cgroup_file_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void cgroup_file_notify(struct cgroup_file * cfile)
```

```json
{
  "name": "cgroup_file_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580357520,
      "name": "cgroup_file_notify",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4099",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify_timer",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/cgroup/pids.c:pids_can_fork",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580357520,
      "name": "cgroup_file_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void cgroup_file_notify(struct cgroup_file * cfile)
```

```json
{
  "name": "cgroup_file_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580515504,
      "name": "cgroup_file_notify",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4274",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify_timer",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/cgroup/pids.c:pids_can_fork",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580515504,
      "name": "cgroup_file_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void cgroup_file_notify(struct cgroup_file * cfile)
```

```json
{
  "name": "cgroup_file_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580712256,
      "name": "cgroup_file_notify",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4285",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify_timer",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/cgroup/pids.c:pids_can_fork",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/misc.c:misc_cg_try_charge",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580712256,
      "name": "cgroup_file_notify",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void cgroup_file_notify(struct cgroup_file * cfile)
```

```json
{
  "name": "cgroup_file_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580986608,
      "name": "cgroup_file_notify",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4462",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify_timer",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/cgroup/pids.c:pids_can_fork",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/misc.c:misc_cg_try_charge",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580986608,
      "name": "cgroup_file_notify",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void cgroup_file_notify(struct cgroup_file * cfile)
```

```json
{
  "name": "cgroup_file_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581074128,
      "name": "cgroup_file_notify",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4439",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify_timer",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/cgroup/pids.c:pids_can_fork",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_parent_subparts_cpumask",
        "kernel/cgroup/misc.c:misc_cg_try_charge",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_one",
        "mm/vmscan.c:shrink_one",
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581074128,
      "name": "cgroup_file_notify",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void cgroup_file_notify(struct cgroup_file * cfile)
```

```json
{
  "name": "cgroup_file_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581171744,
      "name": "cgroup_file_notify",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4469",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify_timer",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/cgroup/pids.c:pids_can_fork",
        "kernel/cgroup/cpuset.c:update_prstate",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:compute_partition_effective_cpumask",
        "kernel/cgroup/cpuset.c:update_parent_effective_cpumask",
        "kernel/cgroup/misc.c:misc_cg_try_charge",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_one",
        "mm/vmscan.c:shrink_one",
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:reclaim_high",
        "mm/memcontrol.c:reclaim_high",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581171744,
      "name": "cgroup_file_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void cgroup_file_notify(struct cgroup_file * cfile)
```

```json
{
  "name": "cgroup_file_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491547024,
      "name": "cgroup_file_notify",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4144",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify_timer",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/pids.c:pids_can_fork",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491547024,
      "name": "cgroup_file_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void cgroup_file_notify(struct cgroup_file * cfile)
```

```json
{
  "name": "cgroup_file_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225511428,
      "name": "cgroup_file_notify",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4144",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify_timer",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/pids.c:pids_can_fork",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225511428,
      "name": "cgroup_file_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void cgroup_file_notify(struct cgroup_file * cfile)
```

```json
{
  "name": "cgroup_file_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284518000,
      "name": "cgroup_file_notify",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4144",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify_timer",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/pids.c:pids_can_fork",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284518000,
      "name": "cgroup_file_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void cgroup_file_notify(struct cgroup_file * cfile)
```

```json
{
  "name": "cgroup_file_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271962176,
      "name": "cgroup_file_notify",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4144",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify_timer",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/pids.c:pids_can_fork",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271962176,
      "name": "cgroup_file_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void cgroup_file_notify(struct cgroup_file * cfile)
```

```json
{
  "name": "cgroup_file_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580265136,
      "name": "cgroup_file_notify",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4144",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify_timer",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/pids.c:pids_can_fork",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580265136,
      "name": "cgroup_file_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void cgroup_file_notify(struct cgroup_file * cfile)
```

```json
{
  "name": "cgroup_file_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580212640,
      "name": "cgroup_file_notify",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4144",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify_timer",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/pids.c:pids_can_fork",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580212640,
      "name": "cgroup_file_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void cgroup_file_notify(struct cgroup_file * cfile)
```

```json
{
  "name": "cgroup_file_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580256384,
      "name": "cgroup_file_notify",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4144",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify_timer",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/pids.c:pids_can_fork",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580256384,
      "name": "cgroup_file_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void cgroup_file_notify(struct cgroup_file * cfile)
```

```json
{
  "name": "cgroup_file_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580309728,
      "name": "cgroup_file_notify",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4144",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify_timer",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/pids.c:pids_can_fork",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580309728,
      "name": "cgroup_file_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
