# Function: <code>deactivate_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void deactivate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "deactivate_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579544640,
      "name": "deactivate_task",
      "external": true,
      "loc": "kernel/sched/core.c:854",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579544640,
      "name": "deactivate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void deactivate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "deactivate_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579555968,
      "name": "deactivate_task",
      "external": true,
      "loc": "kernel/sched/core.c:772",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579555968,
      "name": "deactivate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void deactivate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "deactivate_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579580800,
      "name": "deactivate_task",
      "external": true,
      "loc": "kernel/sched/core.c:779",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579580800,
      "name": "deactivate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void deactivate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "deactivate_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579564368,
      "name": "deactivate_task",
      "external": true,
      "loc": "kernel/sched/core.c:784",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579564368,
      "name": "deactivate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
void deactivate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "deactivate_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579594016,
      "name": "deactivate_task",
      "external": true,
      "loc": "kernel/sched/core.c:794",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579594016,
      "name": "deactivate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
void deactivate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "deactivate_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579625584,
      "name": "deactivate_task",
      "external": true,
      "loc": "kernel/sched/core.c:772",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579625584,
      "name": "deactivate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
void deactivate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "deactivate_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579663072,
      "name": "deactivate_task",
      "external": true,
      "loc": "kernel/sched/core.c:767",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579663072,
      "name": "deactivate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void deactivate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "deactivate_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579691872,
      "name": "deactivate_task",
      "external": true,
      "loc": "kernel/sched/core.c:1208",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579691872,
      "name": "deactivate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 826
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
void deactivate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "deactivate_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579732256,
      "name": "deactivate_task",
      "external": true,
      "loc": "kernel/sched/core.c:1328",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579732256,
      "name": "deactivate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 826
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
void deactivate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "deactivate_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591200088,
      "name": "deactivate_task",
      "external": true,
      "loc": "kernel/sched/core.c:1407",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": [
        "kernel/sched/fair.c:detach_tasks",
        "kernel/sched/fair.c:detach_one_task",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579771888,
      "name": "deactivate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void deactivate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "deactivate_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591695009,
      "name": "deactivate_task",
      "external": true,
      "loc": "kernel/sched/core.c:1618",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:move_queued_task"
      ],
      "caller_func": [
        "kernel/sched/fair.c:detach_tasks",
        "kernel/sched/fair.c:detach_one_task",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579760592,
      "name": "deactivate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void deactivate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "deactivate_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591637511,
      "name": "deactivate_task",
      "external": true,
      "loc": "kernel/sched/core.c:1628",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:move_queued_task"
      ],
      "caller_func": [
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:detach_tasks",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579768256,
      "name": "deactivate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void deactivate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "deactivate_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592811515,
      "name": "deactivate_task",
      "external": true,
      "loc": "kernel/sched/core.c:2006",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:move_queued_task"
      ],
      "caller_func": [
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:detach_tasks",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579858640,
      "name": "deactivate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void deactivate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "deactivate_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594713404,
      "name": "deactivate_task",
      "external": true,
      "loc": "kernel/sched/core.c:2102",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:move_queued_task"
      ],
      "caller_func": [
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:detach_tasks",
        "kernel/sched/build_policy.c:pull_dl_task",
        "kernel/sched/build_policy.c:push_dl_task",
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:push_rt_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579973824,
      "name": "deactivate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void deactivate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "deactivate_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596460606,
      "name": "deactivate_task",
      "external": true,
      "loc": "kernel/sched/core.c:2090",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:move_queued_task"
      ],
      "caller_func": [
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:detach_tasks",
        "kernel/sched/build_policy.c:pull_dl_task",
        "kernel/sched/build_policy.c:push_dl_task",
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:push_rt_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580133984,
      "name": "deactivate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void deactivate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "deactivate_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597002000,
      "name": "deactivate_task",
      "external": true,
      "loc": "kernel/sched/core.c:2117",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:move_queued_task"
      ],
      "caller_func": [
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:detach_tasks",
        "kernel/sched/build_policy.c:pull_dl_task",
        "kernel/sched/build_policy.c:push_dl_task",
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:push_rt_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580196288,
      "name": "deactivate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void deactivate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "deactivate_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597931324,
      "name": "deactivate_task",
      "external": true,
      "loc": "kernel/sched/core.c:2154",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:move_queued_task"
      ],
      "caller_func": [
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:detach_tasks",
        "kernel/sched/build_policy.c:pull_dl_task",
        "kernel/sched/build_policy.c:push_dl_task",
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:push_rt_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580244160,
      "name": "deactivate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void deactivate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "deactivate_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490913312,
      "name": "deactivate_task",
      "external": true,
      "loc": "kernel/sched/core.c:1328",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490913312,
      "name": "deactivate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void deactivate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "deactivate_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224927828,
      "name": "deactivate_task",
      "external": true,
      "loc": "kernel/sched/core.c:1328",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224927828,
      "name": "deactivate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 928
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
void deactivate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "deactivate_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283756992,
      "name": "deactivate_task",
      "external": true,
      "loc": "kernel/sched/core.c:1328",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283756992,
      "name": "deactivate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1040
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
void deactivate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "deactivate_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271551124,
      "name": "deactivate_task",
      "external": true,
      "loc": "kernel/sched/core.c:1328",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271551124,
      "name": "deactivate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
void deactivate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "deactivate_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579708912,
      "name": "deactivate_task",
      "external": true,
      "loc": "kernel/sched/core.c:1328",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579708912,
      "name": "deactivate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 826
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
void deactivate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "deactivate_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579636768,
      "name": "deactivate_task",
      "external": true,
      "loc": "kernel/sched/core.c:1328",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579636768,
      "name": "deactivate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 826
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
void deactivate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "deactivate_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579698896,
      "name": "deactivate_task",
      "external": true,
      "loc": "kernel/sched/core.c:1328",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579698896,
      "name": "deactivate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
void deactivate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "deactivate_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579739456,
      "name": "deactivate_task",
      "external": true,
      "loc": "kernel/sched/core.c:1328",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579739456,
      "name": "deactivate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 826
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
