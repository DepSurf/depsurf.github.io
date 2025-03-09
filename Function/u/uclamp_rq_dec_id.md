# Function: <code>uclamp_rq_dec_id</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uclamp_rq_dec_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579713466,
      "name": "uclamp_rq_dec_id",
      "external": false,
      "loc": "kernel/sched/core.c:944",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uclamp_rq_dec_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579755768,
      "name": "uclamp_rq_dec_id",
      "external": false,
      "loc": "kernel/sched/core.c:982",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/sched/core.c:uclamp_update_active_tasks"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void uclamp_rq_dec_id(struct rq * rq, struct task_struct * p, enum uclamp_id clamp_id)
```

```json
{
  "name": "uclamp_rq_dec_id",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579749184,
      "name": "uclamp_rq_dec_id",
      "external": false,
      "loc": "kernel/sched/core.c:1002",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:uclamp_update_active_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579749184,
      "name": "uclamp_rq_dec_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
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
void uclamp_rq_dec_id(struct rq * rq, struct task_struct * p, enum uclamp_id clamp_id)
```

```json
{
  "name": "uclamp_rq_dec_id",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579734960,
      "name": "uclamp_rq_dec_id",
      "external": false,
      "loc": "kernel/sched/core.c:1161",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__do_set_cpus_allowed",
        "kernel/sched/core.c:__do_set_cpus_allowed",
        "kernel/sched/core.c:uclamp_update_active_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579734960,
      "name": "uclamp_rq_dec_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
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
void uclamp_rq_dec_id(struct rq * rq, struct task_struct * p, enum uclamp_id clamp_id)
```

```json
{
  "name": "uclamp_rq_dec_id",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579741504,
      "name": "uclamp_rq_dec_id",
      "external": false,
      "loc": "kernel/sched/core.c:1174",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__do_set_cpus_allowed",
        "kernel/sched/core.c:__do_set_cpus_allowed",
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/sched/core.c:uclamp_update_active_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579741504,
      "name": "uclamp_rq_dec_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
void uclamp_rq_dec_id(struct rq * rq, struct task_struct * p, enum uclamp_id clamp_id)
```

```json
{
  "name": "uclamp_rq_dec_id",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579822782,
      "name": "uclamp_rq_dec_id",
      "external": false,
      "loc": "kernel/sched/core.c:1528",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__do_set_cpus_allowed",
        "kernel/sched/core.c:__do_set_cpus_allowed",
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/sched/core.c:uclamp_update_active_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579822528,
      "name": "uclamp_rq_dec_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 519
    },
    {
      "addr": 18446744071592106783,
      "name": "uclamp_rq_dec_id.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void uclamp_rq_dec_id(struct rq * rq, struct task_struct * p, enum uclamp_id clamp_id)
```

```json
{
  "name": "uclamp_rq_dec_id",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579940912,
      "name": "uclamp_rq_dec_id",
      "external": false,
      "loc": "kernel/sched/core.c:1571",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:__do_set_cpus_allowed",
        "kernel/sched/core.c:__do_set_cpus_allowed",
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/sched/core.c:uclamp_update_active_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579940640,
      "name": "uclamp_rq_dec_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
    },
    {
      "addr": 18446744071593874515,
      "name": "uclamp_rq_dec_id.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void uclamp_rq_dec_id(struct rq * rq, struct task_struct * p, enum uclamp_id clamp_id)
```

```json
{
  "name": "uclamp_rq_dec_id",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580097430,
      "name": "uclamp_rq_dec_id",
      "external": false,
      "loc": "kernel/sched/core.c:1559",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:__do_set_cpus_allowed",
        "kernel/sched/core.c:__do_set_cpus_allowed",
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/sched/core.c:uclamp_update_active_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580097136,
      "name": "uclamp_rq_dec_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 617
    },
    {
      "addr": 18446744071595976951,
      "name": "uclamp_rq_dec_id.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void uclamp_rq_dec_id(struct rq * rq, struct task_struct * p, enum uclamp_id clamp_id)
```

```json
{
  "name": "uclamp_rq_dec_id",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580155376,
      "name": "uclamp_rq_dec_id",
      "external": false,
      "loc": "kernel/sched/core.c:1581",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:__do_set_cpus_allowed",
        "kernel/sched/core.c:__do_set_cpus_allowed",
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/sched/core.c:uclamp_update_active_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580155072,
      "name": "uclamp_rq_dec_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 647
    },
    {
      "addr": 18446744071596494778,
      "name": "uclamp_rq_dec_id.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void uclamp_rq_dec_id(struct rq * rq, struct task_struct * p, enum uclamp_id clamp_id)
```

```json
{
  "name": "uclamp_rq_dec_id",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580200272,
      "name": "uclamp_rq_dec_id",
      "external": false,
      "loc": "kernel/sched/core.c:1622",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:__do_set_cpus_allowed",
        "kernel/sched/core.c:__do_set_cpus_allowed",
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/sched/core.c:uclamp_update_active_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580199968,
      "name": "uclamp_rq_dec_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 647
    },
    {
      "addr": 18446744071597391507,
      "name": "uclamp_rq_dec_id.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "uclamp_rq_dec_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490903676,
      "name": "uclamp_rq_dec_id",
      "external": false,
      "loc": "kernel/sched/core.c:982",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:dequeue_task",
        "kernel/sched/core.c:dequeue_task",
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/sched/core.c:uclamp_update_active_tasks"
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
  "name": "uclamp_rq_dec_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224914848,
      "name": "uclamp_rq_dec_id",
      "external": false,
      "loc": "kernel/sched/core.c:982",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_util_update_eff",
        "kernel/sched/core.c:cpu_util_update_eff",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:deactivate_task",
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
  "name": "uclamp_rq_dec_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283790096,
      "name": "uclamp_rq_dec_id",
      "external": false,
      "loc": "kernel/sched/core.c:982",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/sched/core.c:uclamp_update_active_tasks"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uclamp_rq_dec_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579731688,
      "name": "uclamp_rq_dec_id",
      "external": false,
      "loc": "kernel/sched/core.c:982",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/sched/core.c:uclamp_update_active_tasks"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uclamp_rq_dec_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579660536,
      "name": "uclamp_rq_dec_id",
      "external": false,
      "loc": "kernel/sched/core.c:982",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/sched/core.c:uclamp_update_active_tasks"
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
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uclamp_rq_dec_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579763398,
      "name": "uclamp_rq_dec_id",
      "external": false,
      "loc": "kernel/sched/core.c:982",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/sched/core.c:uclamp_update_active_tasks"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void uclamp_rq_dec_id(struct rq * rq, struct task_struct * p, enum uclamp_id clamp_id)
```
</details>
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
