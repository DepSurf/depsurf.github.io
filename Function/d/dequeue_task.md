# Function: <code>dequeue_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dequeue_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579540616,
      "name": "dequeue_task",
      "external": false,
      "loc": "kernel/sched/core.c:838",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:deactivate_task",
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
  "name": "dequeue_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579579048,
      "name": "dequeue_task",
      "external": false,
      "loc": "kernel/sched/core.c:756",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:deactivate_task"
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
  "name": "dequeue_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579605099,
      "name": "dequeue_task",
      "external": false,
      "loc": "kernel/sched/core.c:763",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:deactivate_task"
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
  "name": "dequeue_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579583637,
      "name": "dequeue_task",
      "external": false,
      "loc": "kernel/sched/core.c:765",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:deactivate_task"
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
  "name": "dequeue_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579613013,
      "name": "dequeue_task",
      "external": false,
      "loc": "kernel/sched/core.c:775",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:deactivate_task"
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
void dequeue_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "dequeue_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579642872,
      "name": "dequeue_task",
      "external": false,
      "loc": "kernel/sched/core.c:753",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:deactivate_task"
      ],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579619600,
      "name": "dequeue_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
void dequeue_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "dequeue_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579680504,
      "name": "dequeue_task",
      "external": false,
      "loc": "kernel/sched/core.c:746",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:deactivate_task"
      ],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579657120,
      "name": "dequeue_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
void dequeue_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "dequeue_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579713440,
      "name": "dequeue_task",
      "external": false,
      "loc": "kernel/sched/core.c:1184",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:deactivate_task"
      ],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579681200,
      "name": "dequeue_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 755
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
void dequeue_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "dequeue_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579755742,
      "name": "dequeue_task",
      "external": false,
      "loc": "kernel/sched/core.c:1304",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:deactivate_task"
      ],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579721184,
      "name": "dequeue_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 755
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
void dequeue_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "dequeue_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579789896,
      "name": "dequeue_task",
      "external": false,
      "loc": "kernel/sched/core.c:1386",
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
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:move_queued_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579763120,
      "name": "dequeue_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
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
void dequeue_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "dequeue_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579781448,
      "name": "dequeue_task",
      "external": false,
      "loc": "kernel/sched/core.c:1597",
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
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:move_queued_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579752000,
      "name": "dequeue_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
void dequeue_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "dequeue_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579789576,
      "name": "dequeue_task",
      "external": false,
      "loc": "kernel/sched/core.c:1607",
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
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:move_queued_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579758768,
      "name": "dequeue_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
void dequeue_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "dequeue_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579885146,
      "name": "dequeue_task",
      "external": false,
      "loc": "kernel/sched/core.c:1982",
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
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:move_queued_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579844656,
      "name": "dequeue_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 399
    },
    {
      "addr": 18446744071592107300,
      "name": "dequeue_task.cold",
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
void dequeue_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "dequeue_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580002516,
      "name": "dequeue_task",
      "external": false,
      "loc": "kernel/sched/core.c:2078",
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
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:move_queued_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579963376,
      "name": "dequeue_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
    },
    {
      "addr": 18446744071593875039,
      "name": "dequeue_task.cold",
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
void dequeue_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "dequeue_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580164700,
      "name": "dequeue_task",
      "external": false,
      "loc": "kernel/sched/core.c:2066",
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
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:move_queued_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580123072,
      "name": "dequeue_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
    },
    {
      "addr": 18446744071595977426,
      "name": "dequeue_task.cold",
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
void dequeue_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "dequeue_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580213077,
      "name": "dequeue_task",
      "external": false,
      "loc": "kernel/sched/core.c:2088",
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
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:move_queued_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580184880,
      "name": "dequeue_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
    },
    {
      "addr": 18446744071596495266,
      "name": "dequeue_task.cold",
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
void dequeue_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "dequeue_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580261774,
      "name": "dequeue_task",
      "external": false,
      "loc": "kernel/sched/core.c:2124",
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
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:move_queued_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580232032,
      "name": "dequeue_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
    },
    {
      "addr": 18446744071597392111,
      "name": "dequeue_task.cold",
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
void dequeue_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "dequeue_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490903576,
      "name": "dequeue_task",
      "external": false,
      "loc": "kernel/sched/core.c:1304",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:deactivate_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490903576,
      "name": "dequeue_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 684
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
  "name": "dequeue_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224952556,
      "name": "dequeue_task",
      "external": false,
      "loc": "kernel/sched/core.c:1304",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:deactivate_task"
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
  "name": "dequeue_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283789996,
      "name": "dequeue_task",
      "external": false,
      "loc": "kernel/sched/core.c:1304",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:deactivate_task"
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
  "name": "dequeue_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271568250,
      "name": "dequeue_task",
      "external": false,
      "loc": "kernel/sched/core.c:1304",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:deactivate_task"
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
void dequeue_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "dequeue_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579731662,
      "name": "dequeue_task",
      "external": false,
      "loc": "kernel/sched/core.c:1304",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:deactivate_task"
      ],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579697376,
      "name": "dequeue_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 755
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
  "name": "dequeue_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579660510,
      "name": "dequeue_task",
      "external": false,
      "loc": "kernel/sched/core.c:1304",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:deactivate_task"
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
  "name": "dequeue_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579717238,
      "name": "dequeue_task",
      "external": false,
      "loc": "kernel/sched/core.c:1304",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:deactivate_task"
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
  "name": "dequeue_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579763372,
      "name": "dequeue_task",
      "external": false,
      "loc": "kernel/sched/core.c:1304",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:deactivate_task"
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
void dequeue_task(struct rq * rq, struct task_struct * p, int flags)
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
void dequeue_task(struct rq * rq, struct task_struct * p, int flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void dequeue_task(struct rq * rq, struct task_struct * p, int flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void dequeue_task(struct rq * rq, struct task_struct * p, int flags)
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
void dequeue_task(struct rq * rq, struct task_struct * p, int flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
void dequeue_task(struct rq * rq, struct task_struct * p, int flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ➖</summary>

```c
void dequeue_task(struct rq * rq, struct task_struct * p, int flags)
```
</details>
</li>
</ul>
