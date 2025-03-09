# Function: <code>enqueue_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "enqueue_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579540213,
      "name": "enqueue_task",
      "external": false,
      "loc": "kernel/sched/core.c:830",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:activate_task",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_move_task"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "enqueue_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579579017,
      "name": "enqueue_task",
      "external": false,
      "loc": "kernel/sched/core.c:748",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:activate_task"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "enqueue_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579605148,
      "name": "enqueue_task",
      "external": false,
      "loc": "kernel/sched/core.c:755",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:activate_task"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "enqueue_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579583692,
      "name": "enqueue_task",
      "external": false,
      "loc": "kernel/sched/core.c:754",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:activate_task"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "enqueue_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579613080,
      "name": "enqueue_task",
      "external": false,
      "loc": "kernel/sched/core.c:764",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:activate_task"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void enqueue_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "enqueue_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579642914,
      "name": "enqueue_task",
      "external": false,
      "loc": "kernel/sched/core.c:742",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:activate_task"
      ],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579619440,
      "name": "enqueue_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void enqueue_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "enqueue_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579662805,
      "name": "enqueue_task",
      "external": false,
      "loc": "kernel/sched/core.c:733",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:activate_task"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:do_set_cpus_allowed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579656848,
      "name": "enqueue_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void enqueue_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "enqueue_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579713638,
      "name": "enqueue_task",
      "external": false,
      "loc": "kernel/sched/core.c:1170",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:activate_task"
      ],
      "caller_func": [
        "kernel/sched/core.c:rt_mutex_setprio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579680496,
      "name": "enqueue_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void enqueue_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "enqueue_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579755940,
      "name": "enqueue_task",
      "external": false,
      "loc": "kernel/sched/core.c:1290",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:activate_task"
      ],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579720272,
      "name": "enqueue_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 900
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void enqueue_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "enqueue_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579789947,
      "name": "enqueue_task",
      "external": false,
      "loc": "kernel/sched/core.c:1372",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:do_set_cpus_allowed"
      ],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:move_queued_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579762784,
      "name": "enqueue_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void enqueue_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "enqueue_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579781502,
      "name": "enqueue_task",
      "external": false,
      "loc": "kernel/sched/core.c:1583",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__do_set_cpus_allowed"
      ],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:ttwu_do_activate",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:move_queued_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579751616,
      "name": "enqueue_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void enqueue_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "enqueue_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579789630,
      "name": "enqueue_task",
      "external": false,
      "loc": "kernel/sched/core.c:1593",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__do_set_cpus_allowed"
      ],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:ttwu_do_activate",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:move_queued_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579758384,
      "name": "enqueue_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void enqueue_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "enqueue_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579885202,
      "name": "enqueue_task",
      "external": false,
      "loc": "kernel/sched/core.c:1965",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__do_set_cpus_allowed"
      ],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:ttwu_do_activate",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:move_queued_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579844256,
      "name": "enqueue_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 398
    },
    {
      "addr": 18446744071592107280,
      "name": "enqueue_task.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void enqueue_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "enqueue_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580002572,
      "name": "enqueue_task",
      "external": false,
      "loc": "kernel/sched/core.c:2061",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:__do_set_cpus_allowed"
      ],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:ttwu_do_activate",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:move_queued_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579960160,
      "name": "enqueue_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
    },
    {
      "addr": 18446744071593874997,
      "name": "enqueue_task.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void enqueue_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "enqueue_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580165028,
      "name": "enqueue_task",
      "external": false,
      "loc": "kernel/sched/core.c:2049",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:__do_set_cpus_allowed"
      ],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:ttwu_do_activate",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:move_queued_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580119856,
      "name": "enqueue_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 407
    },
    {
      "addr": 18446744071595977384,
      "name": "enqueue_task.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void enqueue_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "enqueue_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580213279,
      "name": "enqueue_task",
      "external": false,
      "loc": "kernel/sched/core.c:2071",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:__do_set_cpus_allowed"
      ],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:ttwu_do_activate",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:move_queued_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580181424,
      "name": "enqueue_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
    },
    {
      "addr": 18446744071596495224,
      "name": "enqueue_task.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void enqueue_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "enqueue_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580261981,
      "name": "enqueue_task",
      "external": false,
      "loc": "kernel/sched/core.c:2107",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:__do_set_cpus_allowed"
      ],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:ttwu_do_activate",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:move_queued_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580227968,
      "name": "enqueue_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
    },
    {
      "addr": 18446744071597392027,
      "name": "enqueue_task.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void enqueue_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "enqueue_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490902832,
      "name": "enqueue_task",
      "external": false,
      "loc": "kernel/sched/core.c:1290",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:activate_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490902832,
      "name": "enqueue_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 740
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "enqueue_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224952780,
      "name": "enqueue_task",
      "external": false,
      "loc": "kernel/sched/core.c:1290",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:activate_task"
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
  "name": "enqueue_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283790288,
      "name": "enqueue_task",
      "external": false,
      "loc": "kernel/sched/core.c:1290",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:activate_task"
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
  "name": "enqueue_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271568278,
      "name": "enqueue_task",
      "external": false,
      "loc": "kernel/sched/core.c:1290",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:activate_task"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void enqueue_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "enqueue_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579731860,
      "name": "enqueue_task",
      "external": false,
      "loc": "kernel/sched/core.c:1290",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:activate_task"
      ],
      "caller_func": [
        "kernel/sched/core.c:rt_mutex_setprio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579696464,
      "name": "enqueue_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 902
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "enqueue_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579660708,
      "name": "enqueue_task",
      "external": false,
      "loc": "kernel/sched/core.c:1290",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:activate_task"
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
  "name": "enqueue_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579717280,
      "name": "enqueue_task",
      "external": false,
      "loc": "kernel/sched/core.c:1290",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:activate_task"
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
  "name": "enqueue_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579763570,
      "name": "enqueue_task",
      "external": false,
      "loc": "kernel/sched/core.c:1290",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:activate_task"
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void enqueue_task(struct rq * rq, struct task_struct * p, int flags)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void enqueue_task(struct rq * rq, struct task_struct * p, int flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void enqueue_task(struct rq * rq, struct task_struct * p, int flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void enqueue_task(struct rq * rq, struct task_struct * p, int flags)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void enqueue_task(struct rq * rq, struct task_struct * p, int flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
void enqueue_task(struct rq * rq, struct task_struct * p, int flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ➖</summary>

```c
void enqueue_task(struct rq * rq, struct task_struct * p, int flags)
```
</details>
</li>
</ul>
