# Function: <code>css_task_iter_next</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct task_struct * css_task_iter_next(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579994640,
      "name": "css_task_iter_next",
      "external": true,
      "loc": "kernel/cgroup.c:4106",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:pidlist_array_load",
        "kernel/cgroup.c:cgroup_transfer_tasks",
        "kernel/cgroup.c:cgroupstats_build",
        "kernel/cgroup.c:cgroupstats_build",
        "kernel/cgroup_freezer.c:freezer_apply_state",
        "kernel/cgroup_freezer.c:freezer_apply_state",
        "kernel/cgroup_freezer.c:freezer_read",
        "kernel/cpuset.c:update_tasks_cpumask",
        "kernel/cpuset.c:update_tasks_nodemask",
        "kernel/cpuset.c:update_flag",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "net/core/netclassid_cgroup.c:update_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579994640,
      "name": "css_task_iter_next",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct task_struct * css_task_iter_next(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580026176,
      "name": "css_task_iter_next",
      "external": true,
      "loc": "kernel/cgroup.c:4295",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_pidlist_start",
        "kernel/cgroup.c:cgroupstats_build",
        "kernel/cgroup.c:cgroupstats_build",
        "kernel/cgroup.c:cgroup_transfer_tasks",
        "kernel/cgroup_freezer.c:freezer_apply_state",
        "kernel/cgroup_freezer.c:freezer_apply_state",
        "kernel/cgroup_freezer.c:freezer_read",
        "kernel/cpuset.c:update_flag",
        "kernel/cpuset.c:update_tasks_nodemask",
        "kernel/cpuset.c:update_tasks_cpumask",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "net/core/netclassid_cgroup.c:update_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580026176,
      "name": "css_task_iter_next",
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
struct task_struct * css_task_iter_next(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580060208,
      "name": "css_task_iter_next",
      "external": true,
      "loc": "kernel/cgroup.c:4306",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_pidlist_start",
        "kernel/cgroup.c:cgroupstats_build",
        "kernel/cgroup.c:cgroupstats_build",
        "kernel/cgroup.c:cgroup_transfer_tasks",
        "kernel/cgroup_freezer.c:freezer_apply_state",
        "kernel/cgroup_freezer.c:freezer_apply_state",
        "kernel/cgroup_freezer.c:freezer_read",
        "kernel/cpuset.c:update_flag",
        "kernel/cpuset.c:update_tasks_nodemask",
        "kernel/cpuset.c:update_tasks_cpumask",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580060208,
      "name": "css_task_iter_next",
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
struct task_struct * css_task_iter_next(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580057488,
      "name": "css_task_iter_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:3793",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_procs_start",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:freezer_apply_state",
        "kernel/cgroup/freezer.c:freezer_apply_state",
        "kernel/cgroup/freezer.c:freezer_read",
        "kernel/cgroup/cpuset.c:update_flag",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580057488,
      "name": "css_task_iter_next",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct task_struct * css_task_iter_next(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580107968,
      "name": "css_task_iter_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4208",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:unfreeze_cgroup",
        "kernel/cgroup/freezer.c:freeze_cgroup",
        "kernel/cgroup/freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580107968,
      "name": "css_task_iter_next",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct task_struct * css_task_iter_next(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580167136,
      "name": "css_task_iter_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4245",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:unfreeze_cgroup",
        "kernel/cgroup/freezer.c:freeze_cgroup",
        "kernel/cgroup/freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580167136,
      "name": "css_task_iter_next",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct task_struct * css_task_iter_next(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580215056,
      "name": "css_task_iter_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4314",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:unfreeze_cgroup",
        "kernel/cgroup/freezer.c:freeze_cgroup",
        "kernel/cgroup/freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580215056,
      "name": "css_task_iter_next",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct task_struct * css_task_iter_next(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580262992,
      "name": "css_task_iter_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4600",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580262992,
      "name": "css_task_iter_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
struct task_struct * css_task_iter_next(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580311280,
      "name": "css_task_iter_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4611",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/cgroup/cpuset.c:update_tasks_root_domain",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580311280,
      "name": "css_task_iter_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
struct task_struct * css_task_iter_next(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580381200,
      "name": "css_task_iter_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4545",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/cgroup/cgroup.c:__cgroup_procs_start",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/cgroup/cpuset.c:update_tasks_root_domain",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580381200,
      "name": "css_task_iter_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
struct task_struct * css_task_iter_next(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580368112,
      "name": "css_task_iter_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4546",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/cgroup/cgroup.c:__cgroup_procs_start",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/cgroup/cpuset.c:update_tasks_root_domain",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580368112,
      "name": "css_task_iter_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
struct task_struct * css_task_iter_next(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580371136,
      "name": "css_task_iter_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4559",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/cgroup/cgroup.c:__cgroup_procs_start",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/cgroup/cpuset.c:update_tasks_root_domain",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580371136,
      "name": "css_task_iter_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
struct task_struct * css_task_iter_next(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580531088,
      "name": "css_task_iter_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4734",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/cgroup/cgroup.c:__cgroup_procs_start",
        "kernel/cgroup/cgroup.c:__cgroup_kill",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/cgroup/cpuset.c:update_tasks_root_domain",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580531088,
      "name": "css_task_iter_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
struct task_struct * css_task_iter_next(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580728288,
      "name": "css_task_iter_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4745",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/cgroup/cgroup.c:__cgroup_procs_start",
        "kernel/cgroup/cgroup.c:__cgroup_kill",
        "kernel/cgroup/cgroup.c:__cgroup_kill",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/cgroup/cpuset.c:update_tasks_root_domain",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580728288,
      "name": "css_task_iter_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
struct task_struct * css_task_iter_next(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581003920,
      "name": "css_task_iter_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4942",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/cgroup/cgroup.c:__cgroup_procs_start",
        "kernel/cgroup/cgroup.c:__cgroup_kill",
        "kernel/cgroup/cgroup.c:__cgroup_kill",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/cgroup/cpuset.c:update_tasks_root_domain",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581003920,
      "name": "css_task_iter_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
struct task_struct * css_task_iter_next(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581092512,
      "name": "css_task_iter_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4919",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/cgroup/cgroup.c:__cgroup_procs_start",
        "kernel/cgroup/cgroup.c:__cgroup_kill",
        "kernel/cgroup/cgroup.c:__cgroup_kill",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/cgroup/cpuset.c:dl_update_tasks_root_domain",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581092512,
      "name": "css_task_iter_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
struct task_struct * css_task_iter_next(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581190032,
      "name": "css_task_iter_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4951",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/cgroup/cgroup.c:__cgroup_procs_start",
        "kernel/cgroup/cgroup.c:__cgroup_kill",
        "kernel/cgroup/cgroup.c:__cgroup_kill",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/cgroup/cpuset.c:dl_update_tasks_root_domain",
        "kernel/bpf/task_iter.c:bpf_iter_css_task_next",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581190032,
      "name": "css_task_iter_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
struct task_struct * css_task_iter_next(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491563648,
      "name": "css_task_iter_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4611",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/cgroup/cpuset.c:update_tasks_root_domain",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491563648,
      "name": "css_task_iter_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
struct task_struct * css_task_iter_next(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225528200,
      "name": "css_task_iter_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4611",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_util_update_eff",
        "kernel/cgroup/cgroup.c:__cgroup_procs_start",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/legacy_freezer.c:freezer_apply_state",
        "kernel/cgroup/legacy_freezer.c:freezer_apply_state",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/cpuset.c:update_flag",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225528200,
      "name": "css_task_iter_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct task_struct * css_task_iter_next(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284541488,
      "name": "css_task_iter_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4611",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/cgroup/cpuset.c:update_tasks_root_domain",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284541488,
      "name": "css_task_iter_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
struct task_struct * css_task_iter_next(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271977292,
      "name": "css_task_iter_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4611",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/cgroup/cpuset.c:update_tasks_root_domain",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271977292,
      "name": "css_task_iter_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
struct task_struct * css_task_iter_next(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580280080,
      "name": "css_task_iter_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4611",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/cgroup/cpuset.c:update_tasks_root_domain",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580280080,
      "name": "css_task_iter_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
struct task_struct * css_task_iter_next(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580227536,
      "name": "css_task_iter_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4611",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/cgroup/cpuset.c:update_tasks_root_domain",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580227536,
      "name": "css_task_iter_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct task_struct * css_task_iter_next(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580271328,
      "name": "css_task_iter_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4611",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/cgroup/cpuset.c:update_tasks_root_domain",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580271328,
      "name": "css_task_iter_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
struct task_struct * css_task_iter_next(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580324880,
      "name": "css_task_iter_next",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4611",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/cgroup/cpuset.c:update_tasks_root_domain",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580324880,
      "name": "css_task_iter_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
