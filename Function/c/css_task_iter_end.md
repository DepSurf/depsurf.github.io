# Function: <code>css_task_iter_end</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void css_task_iter_end(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579994768,
      "name": "css_task_iter_end",
      "external": true,
      "loc": "kernel/cgroup.c:4133",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:pidlist_array_load",
        "kernel/cgroup.c:cgroup_transfer_tasks",
        "kernel/cgroup.c:cgroup_transfer_tasks",
        "kernel/cgroup.c:cgroupstats_build",
        "kernel/cgroup_freezer.c:freezer_apply_state",
        "kernel/cgroup_freezer.c:freezer_apply_state",
        "kernel/cgroup_freezer.c:freezer_read",
        "kernel/cgroup_freezer.c:freezer_read",
        "kernel/cpuset.c:update_tasks_cpumask",
        "kernel/cpuset.c:update_tasks_nodemask",
        "kernel/cpuset.c:update_flag",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "net/core/netclassid_cgroup.c:update_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579994768,
      "name": "css_task_iter_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void css_task_iter_end(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580026304,
      "name": "css_task_iter_end",
      "external": true,
      "loc": "kernel/cgroup.c:4322",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_pidlist_start",
        "kernel/cgroup.c:cgroupstats_build",
        "kernel/cgroup.c:cgroup_transfer_tasks",
        "kernel/cgroup.c:cgroup_transfer_tasks",
        "kernel/cgroup_freezer.c:freezer_apply_state",
        "kernel/cgroup_freezer.c:freezer_apply_state",
        "kernel/cgroup_freezer.c:freezer_read",
        "kernel/cgroup_freezer.c:freezer_read",
        "kernel/cpuset.c:update_flag",
        "kernel/cpuset.c:update_tasks_nodemask",
        "kernel/cpuset.c:update_tasks_cpumask",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "net/core/netclassid_cgroup.c:update_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580026304,
      "name": "css_task_iter_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void css_task_iter_end(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580060336,
      "name": "css_task_iter_end",
      "external": true,
      "loc": "kernel/cgroup.c:4333",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_pidlist_start",
        "kernel/cgroup.c:cgroupstats_build",
        "kernel/cgroup.c:cgroup_transfer_tasks",
        "kernel/cgroup.c:cgroup_transfer_tasks",
        "kernel/cgroup_freezer.c:freezer_apply_state",
        "kernel/cgroup_freezer.c:freezer_apply_state",
        "kernel/cgroup_freezer.c:freezer_read",
        "kernel/cgroup_freezer.c:freezer_read",
        "kernel/cpuset.c:update_flag",
        "kernel/cpuset.c:update_tasks_nodemask",
        "kernel/cpuset.c:update_tasks_cpumask",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580060336,
      "name": "css_task_iter_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void css_task_iter_end(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580057664,
      "name": "css_task_iter_end",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:3820",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_procs_start",
        "kernel/cgroup/cgroup.c:cgroup_procs_release",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:freezer_apply_state",
        "kernel/cgroup/freezer.c:freezer_apply_state",
        "kernel/cgroup/freezer.c:freezer_read",
        "kernel/cgroup/cpuset.c:update_flag",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580057664,
      "name": "css_task_iter_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void css_task_iter_end(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580108128,
      "name": "css_task_iter_end",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4235",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_procs_release",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:unfreeze_cgroup",
        "kernel/cgroup/freezer.c:freeze_cgroup",
        "kernel/cgroup/freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580108128,
      "name": "css_task_iter_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void css_task_iter_end(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580167296,
      "name": "css_task_iter_end",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4272",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_procs_release",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:unfreeze_cgroup",
        "kernel/cgroup/freezer.c:freeze_cgroup",
        "kernel/cgroup/freezer.c:update_if_frozen",
        "kernel/cgroup/freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580167296,
      "name": "css_task_iter_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void css_task_iter_end(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580215216,
      "name": "css_task_iter_end",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4341",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_procs_release",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:unfreeze_cgroup",
        "kernel/cgroup/freezer.c:freeze_cgroup",
        "kernel/cgroup/freezer.c:update_if_frozen",
        "kernel/cgroup/freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580215216,
      "name": "css_task_iter_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void css_task_iter_end(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580263184,
      "name": "css_task_iter_end",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4631",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_procs_release",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580263184,
      "name": "css_task_iter_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
void css_task_iter_end(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580311488,
      "name": "css_task_iter_end",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4642",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/cgroup/cgroup.c:cgroup_procs_release",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/cgroup/cpuset.c:update_tasks_root_domain",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580311488,
      "name": "css_task_iter_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
void css_task_iter_end(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580381488,
      "name": "css_task_iter_end",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4576",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/cgroup/cgroup.c:__cgroup_procs_start",
        "kernel/cgroup/cgroup.c:cgroup_procs_release",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/cgroup/cpuset.c:update_tasks_root_domain",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580381488,
      "name": "css_task_iter_end",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void css_task_iter_end(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580368400,
      "name": "css_task_iter_end",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4577",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/cgroup/cgroup.c:__cgroup_procs_start",
        "kernel/cgroup/cgroup.c:cgroup_procs_release",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/cgroup/cpuset.c:update_tasks_root_domain",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580368400,
      "name": "css_task_iter_end",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void css_task_iter_end(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580371424,
      "name": "css_task_iter_end",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4590",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/cgroup/cgroup.c:__cgroup_procs_start",
        "kernel/cgroup/cgroup.c:cgroup_procs_release",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/cgroup/cpuset.c:update_tasks_root_domain",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580371424,
      "name": "css_task_iter_end",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void css_task_iter_end(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580531376,
      "name": "css_task_iter_end",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4765",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/cgroup/cgroup.c:__cgroup_procs_start",
        "kernel/cgroup/cgroup.c:cgroup_procs_release",
        "kernel/cgroup/cgroup.c:__cgroup_kill",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/cgroup/cpuset.c:update_tasks_root_domain",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580531376,
      "name": "css_task_iter_end",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void css_task_iter_end(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580728576,
      "name": "css_task_iter_end",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4776",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/cgroup/cgroup.c:__cgroup_procs_start",
        "kernel/cgroup/cgroup.c:cgroup_procs_release",
        "kernel/cgroup/cgroup.c:__cgroup_kill",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/cgroup/cpuset.c:update_tasks_root_domain",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580728576,
      "name": "css_task_iter_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void css_task_iter_end(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581004240,
      "name": "css_task_iter_end",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4973",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/cgroup/cgroup.c:__cgroup_procs_start",
        "kernel/cgroup/cgroup.c:cgroup_procs_release",
        "kernel/cgroup/cgroup.c:__cgroup_kill",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
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
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581004240,
      "name": "css_task_iter_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void css_task_iter_end(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581092832,
      "name": "css_task_iter_end",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4950",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/cgroup/cgroup.c:__cgroup_procs_start",
        "kernel/cgroup/cgroup.c:cgroup_procs_release",
        "kernel/cgroup/cgroup.c:__cgroup_kill",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/cgroup/cpuset.c:dl_update_tasks_root_domain",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581092832,
      "name": "css_task_iter_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void css_task_iter_end(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581190352,
      "name": "css_task_iter_end",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4984",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/cgroup/cgroup.c:__cgroup_procs_start",
        "kernel/cgroup/cgroup.c:cgroup_procs_release",
        "kernel/cgroup/cgroup.c:__cgroup_kill",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/cgroup/cpuset.c:dl_update_tasks_root_domain",
        "kernel/bpf/task_iter.c:bpf_iter_css_task_destroy",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581190352,
      "name": "css_task_iter_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
void css_task_iter_end(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491563976,
      "name": "css_task_iter_end",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4642",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/cgroup/cgroup.c:cgroup_procs_release",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/cgroup/cpuset.c:update_tasks_root_domain",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491563976,
      "name": "css_task_iter_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
void css_task_iter_end(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225528460,
      "name": "css_task_iter_end",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4642",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_util_update_eff",
        "kernel/cgroup/cgroup.c:__cgroup_procs_start",
        "kernel/cgroup/cgroup.c:cgroup_procs_release",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/legacy_freezer.c:freezer_apply_state",
        "kernel/cgroup/legacy_freezer.c:freezer_apply_state",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/cpuset.c:update_flag",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225528460,
      "name": "css_task_iter_end",
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
void css_task_iter_end(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284541840,
      "name": "css_task_iter_end",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4642",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/cgroup/cgroup.c:cgroup_procs_release",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/cgroup/cpuset.c:update_tasks_root_domain",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284541840,
      "name": "css_task_iter_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
void css_task_iter_end(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271977568,
      "name": "css_task_iter_end",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4642",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_procs_release",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/cgroup/cpuset.c:update_tasks_root_domain",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271977568,
      "name": "css_task_iter_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
void css_task_iter_end(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580280288,
      "name": "css_task_iter_end",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4642",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/cgroup/cgroup.c:cgroup_procs_release",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/cgroup/cpuset.c:update_tasks_root_domain",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580280288,
      "name": "css_task_iter_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
void css_task_iter_end(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580227728,
      "name": "css_task_iter_end",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4642",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/cgroup/cgroup.c:cgroup_procs_release",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/cgroup/cpuset.c:update_tasks_root_domain",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580227728,
      "name": "css_task_iter_end",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void css_task_iter_end(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580271536,
      "name": "css_task_iter_end",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4642",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_procs_release",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/cgroup/cpuset.c:update_tasks_root_domain",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580271536,
      "name": "css_task_iter_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
void css_task_iter_end(struct css_task_iter * it)
```

```json
{
  "name": "css_task_iter_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580325072,
      "name": "css_task_iter_end",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:4642",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/cgroup/cgroup.c:cgroup_procs_release",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/cgroup/cpuset.c:update_tasks_flags",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask",
        "kernel/cgroup/cpuset.c:update_tasks_cpumask",
        "kernel/cgroup/cpuset.c:update_tasks_root_domain",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580325072,
      "name": "css_task_iter_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
