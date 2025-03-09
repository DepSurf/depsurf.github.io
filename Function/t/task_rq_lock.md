# Function: <code>task_rq_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_rq_lock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579539099,
      "name": "task_rq_lock",
      "external": false,
      "loc": "kernel/sched/sched.h:1455",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:SyS_sched_rr_get_interval",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_move_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579641843,
      "name": "task_rq_lock",
      "external": false,
      "loc": "kernel/sched/sched.h:1455",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_task_timer"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct rq * task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579549776,
      "name": "task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:201",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:SyS_sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579549776,
      "name": "task_rq_lock",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct rq * task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579574576,
      "name": "task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:201",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:SyS_sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579574576,
      "name": "task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct rq * task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579558160,
      "name": "task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:116",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:SyS_sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579558160,
      "name": "task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
struct rq * task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579587232,
      "name": "task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:118",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/livepatch/transition.c:klp_try_switch_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579587232,
      "name": "task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
struct rq * task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579618464,
      "name": "task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:96",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/livepatch/transition.c:klp_try_switch_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579618464,
      "name": "task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
struct rq * task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579655872,
      "name": "task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:90",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/livepatch/transition.c:klp_try_switch_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579655872,
      "name": "task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
struct rq * task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579679440,
      "name": "task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:102",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/psi.c:cgroup_move_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579679440,
      "name": "task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
struct rq * task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579717024,
      "name": "task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:102",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/psi.c:cgroup_move_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579717024,
      "name": "task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
struct rq * task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579760400,
      "name": "task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:105",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/psi.c:cgroup_move_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579760400,
      "name": "task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
struct rq * task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579748800,
      "name": "task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:204",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:sched_post_fork",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/sched/core.c:uclamp_sync_util_min_rt_default",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/psi.c:cgroup_move_task",
        "fs/io-wq.c:io_wq_worker_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579748800,
      "name": "task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
struct rq * task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579755920,
      "name": "task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:214",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:sched_post_fork",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/psi.c:cgroup_move_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579755920,
      "name": "task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
struct rq * task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:567",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:sched_post_fork",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/core.c:migrate_enable",
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/core_sched.c:sched_core_update_cookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592107218,
      "name": "task_rq_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071579841472,
      "name": "task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
struct rq * task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:637",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:sched_post_fork",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/core.c:migrate_enable",
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:dl_task_timer",
        "kernel/sched/build_utility.c:cgroup_move_task",
        "kernel/sched/build_utility.c:__sched_core_set",
        "kernel/sched/build_utility.c:__sched_core_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593874934,
      "name": "task_rq_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579956176,
      "name": "task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
struct rq * task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:630",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:sched_post_fork",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:dl_task_timer",
        "kernel/sched/build_utility.c:cgroup_move_task",
        "kernel/sched/build_utility.c:__sched_core_set",
        "kernel/sched/build_utility.c:__sched_core_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595977279,
      "name": "task_rq_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580115488,
      "name": "task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
struct rq * task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:651",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:sched_post_fork",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:dl_task_timer",
        "kernel/sched/build_utility.c:cgroup_move_task",
        "kernel/sched/build_utility.c:__sched_core_set",
        "kernel/sched/build_utility.c:__sched_core_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596495119,
      "name": "task_rq_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580176944,
      "name": "task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 369
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
struct rq * task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:652",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:sched_post_fork",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:dl_task_timer",
        "kernel/sched/build_utility.c:cgroup_move_task",
        "kernel/sched/build_utility.c:__sched_core_set",
        "kernel/sched/build_utility.c:__sched_core_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597391922,
      "name": "task_rq_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580223312,
      "name": "task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 369
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
struct rq * task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490899696,
      "name": "task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:102",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/psi.c:cgroup_move_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490899696,
      "name": "task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
struct rq * task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224914060,
      "name": "task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:102",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_util_update_eff",
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/cputime.c:thread_group_cputime",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/psi.c:cgroup_move_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224914060,
      "name": "task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
struct rq * task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283738288,
      "name": "task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:102",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/psi.c:cgroup_move_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283738288,
      "name": "task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
struct rq * task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271544962,
      "name": "task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:102",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:__se_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/psi.c:cgroup_move_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271544962,
      "name": "task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
struct rq * task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579693200,
      "name": "task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:102",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/psi.c:cgroup_move_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579693200,
      "name": "task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
struct rq * task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579621728,
      "name": "task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:102",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/psi.c:cgroup_move_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579621728,
      "name": "task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
struct rq * task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579690176,
      "name": "task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:102",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/psi.c:cgroup_move_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579690176,
      "name": "task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
struct rq * task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579724832,
      "name": "task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:102",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/psi.c:cgroup_move_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579724832,
      "name": "task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct rq * task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```
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
