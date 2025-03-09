# Function: <code>rt_mutex_get_top_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct task_struct * rt_mutex_get_top_task(struct task_struct * task)
```

```json
{
  "name": "rt_mutex_get_top_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579678512,
      "name": "rt_mutex_get_top_task",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:272",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/deadline.c:enqueue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579678512,
      "name": "rt_mutex_get_top_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
struct task_struct * rt_mutex_get_top_task(struct task_struct * task)
```

```json
{
  "name": "rt_mutex_get_top_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579697552,
      "name": "rt_mutex_get_top_task",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:274",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/deadline.c:enqueue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579697552,
      "name": "rt_mutex_get_top_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
struct task_struct * rt_mutex_get_top_task(struct task_struct * task)
```

```json
{
  "name": "rt_mutex_get_top_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579724672,
      "name": "rt_mutex_get_top_task",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:338",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/deadline.c:enqueue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579724672,
      "name": "rt_mutex_get_top_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt_mutex_get_top_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579559169,
      "name": "rt_mutex_get_top_task",
      "external": false,
      "loc": "include/linux/sched/rt.h:24",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579661853,
      "name": "rt_mutex_get_top_task",
      "external": false,
      "loc": "include/linux/sched/rt.h:24",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:enqueue_task_dl"
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
  "name": "rt_mutex_get_top_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579588553,
      "name": "rt_mutex_get_top_task",
      "external": false,
      "loc": "include/linux/sched/rt.h:36",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579691997,
      "name": "rt_mutex_get_top_task",
      "external": false,
      "loc": "include/linux/sched/rt.h:36",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:enqueue_task_dl"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt_mutex_get_top_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579620498,
      "name": "rt_mutex_get_top_task",
      "external": false,
      "loc": "include/linux/sched/rt.h:36",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579723029,
      "name": "rt_mutex_get_top_task",
      "external": false,
      "loc": "include/linux/sched/rt.h:36",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:enqueue_task_dl"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt_mutex_get_top_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579657810,
      "name": "rt_mutex_get_top_task",
      "external": false,
      "loc": "include/linux/sched/rt.h:36",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579765333,
      "name": "rt_mutex_get_top_task",
      "external": false,
      "loc": "include/linux/sched/rt.h:36",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:enqueue_task_dl"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt_mutex_get_top_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579682797,
      "name": "rt_mutex_get_top_task",
      "external": false,
      "loc": "include/linux/sched/rt.h:36",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579794069,
      "name": "rt_mutex_get_top_task",
      "external": false,
      "loc": "include/linux/sched/rt.h:36",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:enqueue_task_dl"
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
  "name": "rt_mutex_get_top_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579722472,
      "name": "rt_mutex_get_top_task",
      "external": false,
      "loc": "include/linux/sched/rt.h:36",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579840725,
      "name": "rt_mutex_get_top_task",
      "external": false,
      "loc": "include/linux/sched/rt.h:36",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:enqueue_task_dl"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt_mutex_get_top_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579765099,
      "name": "rt_mutex_get_top_task",
      "external": false,
      "loc": "include/linux/sched/rt.h:36",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579879301,
      "name": "rt_mutex_get_top_task",
      "external": false,
      "loc": "include/linux/sched/rt.h:36",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:enqueue_task_dl"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt_mutex_get_top_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579754003,
      "name": "rt_mutex_get_top_task",
      "external": false,
      "loc": "include/linux/sched/rt.h:36",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt_mutex_get_top_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579760692,
      "name": "rt_mutex_get_top_task",
      "external": false,
      "loc": "include/linux/sched/rt.h:36",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt_mutex_get_top_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579846980,
      "name": "rt_mutex_get_top_task",
      "external": false,
      "loc": "include/linux/sched/rt.h:36",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt_mutex_get_top_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579964732,
      "name": "rt_mutex_get_top_task",
      "external": false,
      "loc": "include/linux/sched/rt.h:36",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler"
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
  "name": "rt_mutex_get_top_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580124412,
      "name": "rt_mutex_get_top_task",
      "external": false,
      "loc": "include/linux/sched/rt.h:36",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler"
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
  "name": "rt_mutex_get_top_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580186120,
      "name": "rt_mutex_get_top_task",
      "external": false,
      "loc": "include/linux/sched/rt.h:36",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler"
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
  "name": "rt_mutex_get_top_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580233272,
      "name": "rt_mutex_get_top_task",
      "external": false,
      "loc": "include/linux/sched/rt.h:40",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler"
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
  "name": "rt_mutex_get_top_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490904716,
      "name": "rt_mutex_get_top_task",
      "external": false,
      "loc": "include/linux/sched/rt.h:36",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491029360,
      "name": "rt_mutex_get_top_task",
      "external": false,
      "loc": "include/linux/sched/rt.h:36",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:enqueue_task_dl"
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
  "name": "rt_mutex_get_top_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224917628,
      "name": "rt_mutex_get_top_task",
      "external": false,
      "loc": "include/linux/sched/rt.h:36",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": []
    },
    {
      "addr": 3225037596,
      "name": "rt_mutex_get_top_task",
      "external": false,
      "loc": "include/linux/sched/rt.h:36",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:enqueue_task_dl"
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
  "name": "rt_mutex_get_top_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283743580,
      "name": "rt_mutex_get_top_task",
      "external": false,
      "loc": "include/linux/sched/rt.h:36",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283905496,
      "name": "rt_mutex_get_top_task",
      "external": false,
      "loc": "include/linux/sched/rt.h:36",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:enqueue_task_dl"
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
  "name": "rt_mutex_get_top_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271545730,
      "name": "rt_mutex_get_top_task",
      "external": false,
      "loc": "include/linux/sched/rt.h:36",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271633870,
      "name": "rt_mutex_get_top_task",
      "external": false,
      "loc": "include/linux/sched/rt.h:36",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:enqueue_task_dl"
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
  "name": "rt_mutex_get_top_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579698914,
      "name": "rt_mutex_get_top_task",
      "external": false,
      "loc": "include/linux/sched/rt.h:36",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579813077,
      "name": "rt_mutex_get_top_task",
      "external": false,
      "loc": "include/linux/sched/rt.h:36",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:enqueue_task_dl"
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
  "name": "rt_mutex_get_top_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579625500,
      "name": "rt_mutex_get_top_task",
      "external": false,
      "loc": "include/linux/sched/rt.h:36",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579747701,
      "name": "rt_mutex_get_top_task",
      "external": false,
      "loc": "include/linux/sched/rt.h:36",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:enqueue_task_dl"
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
  "name": "rt_mutex_get_top_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579691686,
      "name": "rt_mutex_get_top_task",
      "external": false,
      "loc": "include/linux/sched/rt.h:36",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579801093,
      "name": "rt_mutex_get_top_task",
      "external": false,
      "loc": "include/linux/sched/rt.h:36",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:enqueue_task_dl"
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
  "name": "rt_mutex_get_top_task",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579728834,
      "name": "rt_mutex_get_top_task",
      "external": false,
      "loc": "include/linux/sched/rt.h:36",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579846069,
      "name": "rt_mutex_get_top_task",
      "external": false,
      "loc": "include/linux/sched/rt.h:36",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:enqueue_task_dl"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
struct task_struct * rt_mutex_get_top_task(struct task_struct * task)
```
</details>
</li>
</ul>
