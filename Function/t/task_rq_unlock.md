# Function: <code>task_rq_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void task_rq_unlock(struct rq * rq, struct task_struct * p, long unsigned int * flags)
```

```json
{
  "name": "task_rq_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579519232,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1501",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:SyS_sched_rr_get_interval",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_move_task"
      ],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler"
      ]
    },
    {
      "addr": 18446744071579641967,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1501",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_task_timer"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579519232,
      "name": "task_rq_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void task_rq_unlock(struct rq * rq, struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "task_rq_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579550008,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1484",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:SyS_sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler"
      ]
    },
    {
      "addr": 18446744071579656736,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1484",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_task_timer"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579533344,
      "name": "task_rq_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void task_rq_unlock(struct rq * rq, struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "task_rq_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579574808,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1523",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:SyS_sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler"
      ]
    },
    {
      "addr": 18446744071579681253,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1523",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_task_timer"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579557888,
      "name": "task_rq_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void task_rq_unlock(struct rq * rq, struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "task_rq_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579558672,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1700",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:SyS_sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler"
      ]
    },
    {
      "addr": 18446744071579658547,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1700",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1700",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579544224,
      "name": "task_rq_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void task_rq_unlock(struct rq * rq, struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "task_rq_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579588048,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1739",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler"
      ]
    },
    {
      "addr": 18446744071579689339,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1739",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579907899,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1739",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_switch_task"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579572128,
      "name": "task_rq_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void task_rq_unlock(struct rq * rq, struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "task_rq_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579619968,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1783",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ]
    },
    {
      "addr": 18446744071579729907,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1783",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579941759,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1783",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_switch_task"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579613168,
      "name": "task_rq_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void task_rq_unlock(struct rq * rq, struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "task_rq_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579660544,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1120",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ]
    },
    {
      "addr": 18446744071579760531,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1120",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579826657,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1120",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:cgroup_move_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579988847,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1120",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_switch_task"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579652144,
      "name": "task_rq_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_rq_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579682144,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1178",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579788148,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1178",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579856545,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1178",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:cgroup_move_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580030725,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1178",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "task_rq_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579726144,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1186",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:uclamp_update_active_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579846155,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1186",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579905073,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1186",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:cgroup_move_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580081445,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1186",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "task_rq_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579769504,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1234",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:uclamp_update_active_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579885051,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1234",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579950097,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1234",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:cgroup_move_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580140424,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1234",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "task_rq_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579758144,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1292",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_post_fork",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/sched/core.c:uclamp_sync_util_min_rt_default"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579878347,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1292",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579938661,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1292",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:cgroup_move_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580117656,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1292",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582626822,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1292",
      "file": "fs/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io-wq.c:io_wq_worker_affinity"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void task_rq_unlock(struct rq * rq, struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "task_rq_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579765296,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1305",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_post_fork",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/core.c:uclamp_update_active_tasks"
      ],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler"
      ]
    },
    {
      "addr": 18446744071579887533,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1305",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579945858,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1305",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:cgroup_move_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580121137,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1305",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579752512,
      "name": "task_rq_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_rq_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579851584,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1592",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_post_fork",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/core.c:uclamp_update_active_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580000474,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1592",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580072927,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1592",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:cgroup_move_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580074394,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1592",
      "file": "kernel/sched/core_sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core_sched.c:sched_core_update_cookie"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580263816,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1592",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "task_rq_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579960880,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1573",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_post_fork",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/core.c:uclamp_update_active_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580130850,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1573",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:dl_add_task_root_domain",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:dl_task_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580205990,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1573",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:cgroup_move_task",
        "kernel/sched/build_utility.c:__sched_core_set"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_rq_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580164549,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1619",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_post_fork",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/core.c:uclamp_update_active_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580305036,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1619",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:dl_add_task_root_domain",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:dl_task_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580397322,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1619",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:cgroup_move_task",
        "kernel/sched/build_utility.c:__sched_core_set"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_rq_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580212902,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1646",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_post_fork",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/core.c:uclamp_update_active_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580372524,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1646",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:dl_add_task_root_domain",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:dl_task_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580465770,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1646",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:cgroup_move_task",
        "kernel/sched/build_utility.c:__sched_core_set"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_rq_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580261584,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1665",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_post_fork",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/core.c:uclamp_update_active_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580430636,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1665",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:dl_add_task_root_domain",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:dl_task_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580525514,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1665",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:cgroup_move_task",
        "kernel/sched/build_utility.c:__sched_core_set"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "task_rq_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490908700,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1186",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:uclamp_update_active_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491035300,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1186",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491104844,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1186",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:cgroup_move_task"
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
  "name": "task_rq_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224914788,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1186",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_util_update_eff",
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 3224957440,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1186",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:thread_group_cputime"
      ],
      "caller_func": []
    },
    {
      "addr": 3225044832,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1186",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 3225110712,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1186",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:cgroup_move_task"
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
  "name": "task_rq_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283742848,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1186",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:uclamp_update_active_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283913952,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1186",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283996816,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1186",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:cgroup_move_task"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284206624,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1186",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "task_rq_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271547968,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1186",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:__se_sys_sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271637184,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1186",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271687568,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1186",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:cgroup_move_task"
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
  "name": "task_rq_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579698320,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1186",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:uclamp_update_active_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579818507,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1186",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579877185,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1186",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:cgroup_move_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580050181,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1186",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "task_rq_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579630544,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1186",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:uclamp_update_active_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579753115,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1186",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579812177,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1186",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:cgroup_move_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579995493,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1186",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "task_rq_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579695056,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1186",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579806523,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1186",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579865345,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1186",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:cgroup_move_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580041717,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1186",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "task_rq_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579728240,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1186",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:uclamp_update_active_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579851499,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1186",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579910721,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1186",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:cgroup_move_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580092469,
      "name": "task_rq_unlock",
      "external": false,
      "loc": "kernel/sched/sched.h:1186",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct rq_flags * rf</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int * flags</code>
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void task_rq_unlock(struct rq * rq, struct task_struct * p, struct rq_flags * rf)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void task_rq_unlock(struct rq * rq, struct task_struct * p, struct rq_flags * rf)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void task_rq_unlock(struct rq * rq, struct task_struct * p, struct rq_flags * rf)
```
</details>
</li>
</ul>
