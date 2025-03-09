# Function: <code>activate_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void activate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "activate_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579544512,
      "name": "activate_task",
      "external": true,
      "loc": "kernel/sched/core.c:846",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579544512,
      "name": "activate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void activate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "activate_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579555840,
      "name": "activate_task",
      "external": true,
      "loc": "kernel/sched/core.c:764",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:ttwu_do_activate",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579555840,
      "name": "activate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void activate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "activate_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579580672,
      "name": "activate_task",
      "external": true,
      "loc": "kernel/sched/core.c:771",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:ttwu_do_activate",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579580672,
      "name": "activate_task",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void activate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "activate_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579564176,
      "name": "activate_task",
      "external": true,
      "loc": "kernel/sched/core.c:776",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:ttwu_do_activate",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579564176,
      "name": "activate_task",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void activate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "activate_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579593824,
      "name": "activate_task",
      "external": true,
      "loc": "kernel/sched/core.c:786",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:ttwu_do_activate",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579593824,
      "name": "activate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void activate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "activate_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579625392,
      "name": "activate_task",
      "external": true,
      "loc": "kernel/sched/core.c:764",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:ttwu_do_activate",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579625392,
      "name": "activate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void activate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "activate_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579662768,
      "name": "activate_task",
      "external": true,
      "loc": "kernel/sched/core.c:759",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:ttwu_do_activate",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579662768,
      "name": "activate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
void activate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "activate_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579691120,
      "name": "activate_task",
      "external": true,
      "loc": "kernel/sched/core.c:1198",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:ttwu_do_activate",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579691120,
      "name": "activate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 745
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
void activate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "activate_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579731296,
      "name": "activate_task",
      "external": true,
      "loc": "kernel/sched/core.c:1318",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:ttwu_do_activate",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579731296,
      "name": "activate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 960
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
void activate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "activate_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579781462,
      "name": "activate_task",
      "external": true,
      "loc": "kernel/sched/core.c:1400",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending"
      ],
      "caller_func": [
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579771856,
      "name": "activate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void activate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "activate_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579772053,
      "name": "activate_task",
      "external": true,
      "loc": "kernel/sched/core.c:1611",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:ttwu_do_activate",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:move_queued_task"
      ],
      "caller_func": [
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579760560,
      "name": "activate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void activate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "activate_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579779658,
      "name": "activate_task",
      "external": true,
      "loc": "kernel/sched/core.c:1621",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:ttwu_do_activate",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:move_queued_task"
      ],
      "caller_func": [
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579768224,
      "name": "activate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void activate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "activate_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579866319,
      "name": "activate_task",
      "external": true,
      "loc": "kernel/sched/core.c:1999",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:ttwu_do_activate",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:move_queued_task"
      ],
      "caller_func": [
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579858608,
      "name": "activate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void activate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "activate_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579982225,
      "name": "activate_task",
      "external": true,
      "loc": "kernel/sched/core.c:2095",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:ttwu_do_activate",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:move_queued_task"
      ],
      "caller_func": [
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/build_policy.c:pull_dl_task",
        "kernel/sched/build_policy.c:push_dl_task",
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:push_rt_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579973776,
      "name": "activate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void activate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "activate_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580142958,
      "name": "activate_task",
      "external": true,
      "loc": "kernel/sched/core.c:2083",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:ttwu_do_activate",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:move_queued_task"
      ],
      "caller_func": [
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/build_policy.c:pull_dl_task",
        "kernel/sched/build_policy.c:push_dl_task",
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:push_rt_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580133920,
      "name": "activate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void activate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "activate_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580227663,
      "name": "activate_task",
      "external": true,
      "loc": "kernel/sched/core.c:2105",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:ttwu_do_activate",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:move_queued_task"
      ],
      "caller_func": [
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/build_policy.c:pull_dl_task",
        "kernel/sched/build_policy.c:push_dl_task",
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:push_rt_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580214832,
      "name": "activate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void activate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "activate_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580276448,
      "name": "activate_task",
      "external": true,
      "loc": "kernel/sched/core.c:2141",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:ttwu_do_activate",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:move_queued_task"
      ],
      "caller_func": [
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/build_policy.c:pull_dl_task",
        "kernel/sched/build_policy.c:push_dl_task",
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:push_rt_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580263568,
      "name": "activate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void activate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "activate_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490913200,
      "name": "activate_task",
      "external": true,
      "loc": "kernel/sched/core.c:1318",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:ttwu_do_activate",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490913200,
      "name": "activate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void activate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "activate_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224926972,
      "name": "activate_task",
      "external": true,
      "loc": "kernel/sched/core.c:1318",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:ttwu_do_activate",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224926972,
      "name": "activate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 856
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
void activate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "activate_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283755936,
      "name": "activate_task",
      "external": true,
      "loc": "kernel/sched/core.c:1318",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:ttwu_do_activate",
        "kernel/sched/fair.c:attach_task",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283755936,
      "name": "activate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1056
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
void activate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "activate_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271550818,
      "name": "activate_task",
      "external": true,
      "loc": "kernel/sched/core.c:1318",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:ttwu_do_activate",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271550818,
      "name": "activate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
void activate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "activate_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579707936,
      "name": "activate_task",
      "external": true,
      "loc": "kernel/sched/core.c:1318",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:ttwu_do_activate",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579707936,
      "name": "activate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 962
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
void activate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "activate_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579635808,
      "name": "activate_task",
      "external": true,
      "loc": "kernel/sched/core.c:1318",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:ttwu_do_activate",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579635808,
      "name": "activate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 960
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
void activate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "activate_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579698544,
      "name": "activate_task",
      "external": true,
      "loc": "kernel/sched/core.c:1318",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:ttwu_do_activate",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579698544,
      "name": "activate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
void activate_task(struct rq * rq, struct task_struct * p, int flags)
```

```json
{
  "name": "activate_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579738480,
      "name": "activate_task",
      "external": true,
      "loc": "kernel/sched/core.c:1318",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:ttwu_do_activate",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579738480,
      "name": "activate_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 962
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
