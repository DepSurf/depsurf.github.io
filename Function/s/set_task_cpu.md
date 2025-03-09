# Function: <code>set_task_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void set_task_cpu(struct task_struct * p, unsigned int new_cpu)
```

```json
{
  "name": "set_task_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579546288,
      "name": "set_task_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:1267",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/core.c:wake_up_new_task",
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
      "addr": 18446744071579546288,
      "name": "set_task_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
void set_task_cpu(struct task_struct * p, unsigned int new_cpu)
```

```json
{
  "name": "set_task_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579557616,
      "name": "set_task_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:1203",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:move_queued_task",
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
      "addr": 18446744071579557616,
      "name": "set_task_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
void set_task_cpu(struct task_struct * p, unsigned int new_cpu)
```

```json
{
  "name": "set_task_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579582560,
      "name": "set_task_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:1214",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579582560,
      "name": "set_task_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
void set_task_cpu(struct task_struct * p, unsigned int new_cpu)
```

```json
{
  "name": "set_task_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579566064,
      "name": "set_task_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:1138",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579566064,
      "name": "set_task_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
void set_task_cpu(struct task_struct * p, unsigned int new_cpu)
```

```json
{
  "name": "set_task_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579595760,
      "name": "set_task_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:1153",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579595760,
      "name": "set_task_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
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
void set_task_cpu(struct task_struct * p, unsigned int new_cpu)
```

```json
{
  "name": "set_task_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579627408,
      "name": "set_task_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:1150",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579627408,
      "name": "set_task_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
void set_task_cpu(struct task_struct * p, unsigned int new_cpu)
```

```json
{
  "name": "set_task_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579664928,
      "name": "set_task_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:1145",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579664928,
      "name": "set_task_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
void set_task_cpu(struct task_struct * p, unsigned int new_cpu)
```

```json
{
  "name": "set_task_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579695232,
      "name": "set_task_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:1587",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579695232,
      "name": "set_task_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
void set_task_cpu(struct task_struct * p, unsigned int new_cpu)
```

```json
{
  "name": "set_task_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579735840,
      "name": "set_task_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:1707",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:dl_task_offline_migration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579735840,
      "name": "set_task_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 419
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
void set_task_cpu(struct task_struct * p, unsigned int new_cpu)
```

```json
{
  "name": "set_task_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579773312,
      "name": "set_task_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:1777",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/fair.c:detach_tasks",
        "kernel/sched/fair.c:detach_one_task",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:dl_task_offline_migration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579773312,
      "name": "set_task_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
void set_task_cpu(struct task_struct * p, unsigned int new_cpu)
```

```json
{
  "name": "set_task_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579761440,
      "name": "set_task_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:2401",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/fair.c:detach_tasks",
        "kernel/sched/fair.c:detach_one_task",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:dl_task_offline_migration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579761440,
      "name": "set_task_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
void set_task_cpu(struct task_struct * p, unsigned int new_cpu)
```

```json
{
  "name": "set_task_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579769088,
      "name": "set_task_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:2422",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:detach_tasks",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:dl_task_offline_migration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579769088,
      "name": "set_task_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
void set_task_cpu(struct task_struct * p, unsigned int new_cpu)
```

```json
{
  "name": "set_task_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579859760,
      "name": "set_task_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:2989",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:detach_tasks",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:dl_task_offline_migration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579859760,
      "name": "set_task_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 399
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
void set_task_cpu(struct task_struct * p, unsigned int new_cpu)
```

```json
{
  "name": "set_task_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579975104,
      "name": "set_task_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:3088",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:detach_tasks",
        "kernel/sched/build_policy.c:pull_dl_task",
        "kernel/sched/build_policy.c:push_dl_task",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:push_rt_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579975104,
      "name": "set_task_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
void set_task_cpu(struct task_struct * p, unsigned int new_cpu)
```

```json
{
  "name": "set_task_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580135616,
      "name": "set_task_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:3144",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:detach_tasks",
        "kernel/sched/build_policy.c:pull_dl_task",
        "kernel/sched/build_policy.c:push_dl_task",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:push_rt_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580135616,
      "name": "set_task_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 466
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
void set_task_cpu(struct task_struct * p, unsigned int new_cpu)
```

```json
{
  "name": "set_task_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580197904,
      "name": "set_task_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:3320",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:detach_tasks",
        "kernel/sched/build_policy.c:pull_dl_task",
        "kernel/sched/build_policy.c:push_dl_task",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:push_rt_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580197904,
      "name": "set_task_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
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
void set_task_cpu(struct task_struct * p, unsigned int new_cpu)
```

```json
{
  "name": "set_task_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580245888,
      "name": "set_task_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:3350",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:detach_tasks",
        "kernel/sched/build_policy.c:pull_dl_task",
        "kernel/sched/build_policy.c:push_dl_task",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:push_rt_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580245888,
      "name": "set_task_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
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
void set_task_cpu(struct task_struct * p, unsigned int new_cpu)
```

```json
{
  "name": "set_task_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490915352,
      "name": "set_task_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:1707",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:dl_task_offline_migration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490915352,
      "name": "set_task_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
void set_task_cpu(struct task_struct * p, unsigned int new_cpu)
```

```json
{
  "name": "set_task_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224931796,
      "name": "set_task_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:1707",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:dl_task_offline_migration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224931796,
      "name": "set_task_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
void set_task_cpu(struct task_struct * p, unsigned int new_cpu)
```

```json
{
  "name": "set_task_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283761984,
      "name": "set_task_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:1707",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:dl_task_offline_migration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283761984,
      "name": "set_task_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 652
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
void set_task_cpu(struct task_struct * p, unsigned int new_cpu)
```

```json
{
  "name": "set_task_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271552810,
      "name": "set_task_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:1707",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:dl_task_offline_migration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271552810,
      "name": "set_task_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
void set_task_cpu(struct task_struct * p, unsigned int new_cpu)
```

```json
{
  "name": "set_task_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579712496,
      "name": "set_task_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:1707",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:dl_task_offline_migration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579712496,
      "name": "set_task_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
void set_task_cpu(struct task_struct * p, unsigned int new_cpu)
```

```json
{
  "name": "set_task_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579640352,
      "name": "set_task_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:1707",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:dl_task_offline_migration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579640352,
      "name": "set_task_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 419
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
void set_task_cpu(struct task_struct * p, unsigned int new_cpu)
```

```json
{
  "name": "set_task_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579700816,
      "name": "set_task_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:1707",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:dl_task_offline_migration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579700816,
      "name": "set_task_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 419
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
void set_task_cpu(struct task_struct * p, unsigned int new_cpu)
```

```json
{
  "name": "set_task_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579743120,
      "name": "set_task_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:1707",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:dl_task_offline_migration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579743120,
      "name": "set_task_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
