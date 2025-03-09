# Function: <code>rt_mutex_setprio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void rt_mutex_setprio(struct task_struct * p, int prio)
```

```json
{
  "name": "rt_mutex_setprio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579554752,
      "name": "rt_mutex_setprio",
      "external": true,
      "loc": "kernel/sched/core.c:3365",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:__rt_mutex_adjust_prio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579554752,
      "name": "rt_mutex_setprio",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void rt_mutex_setprio(struct task_struct * p, int prio)
```

```json
{
  "name": "rt_mutex_setprio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579565472,
      "name": "rt_mutex_setprio",
      "external": true,
      "loc": "kernel/sched/core.c:3613",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:__rt_mutex_adjust_prio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579565472,
      "name": "rt_mutex_setprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 916
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
void rt_mutex_setprio(struct task_struct * p, int prio)
```

```json
{
  "name": "rt_mutex_setprio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579590432,
      "name": "rt_mutex_setprio",
      "external": true,
      "loc": "kernel/sched/core.c:3644",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:__rt_mutex_adjust_prio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579590432,
      "name": "rt_mutex_setprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 942
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
void rt_mutex_setprio(struct task_struct * p, struct task_struct * pi_task)
```

```json
{
  "name": "rt_mutex_setprio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579574720,
      "name": "rt_mutex_setprio",
      "external": true,
      "loc": "kernel/sched/core.c:3617",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579574720,
      "name": "rt_mutex_setprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 903
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
void rt_mutex_setprio(struct task_struct * p, struct task_struct * pi_task)
```

```json
{
  "name": "rt_mutex_setprio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579604384,
      "name": "rt_mutex_setprio",
      "external": true,
      "loc": "kernel/sched/core.c:3661",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579604384,
      "name": "rt_mutex_setprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 931
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
void rt_mutex_setprio(struct task_struct * p, struct task_struct * pi_task)
```

```json
{
  "name": "rt_mutex_setprio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579635808,
      "name": "rt_mutex_setprio",
      "external": true,
      "loc": "kernel/sched/core.c:3771",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579635808,
      "name": "rt_mutex_setprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 931
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
void rt_mutex_setprio(struct task_struct * p, struct task_struct * pi_task)
```

```json
{
  "name": "rt_mutex_setprio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579673536,
      "name": "rt_mutex_setprio",
      "external": true,
      "loc": "kernel/sched/core.c:3755",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579673536,
      "name": "rt_mutex_setprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 945
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void rt_mutex_setprio(struct task_struct * p, struct task_struct * pi_task)
```

```json
{
  "name": "rt_mutex_setprio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rt_mutex_setprio",
      "external": true,
      "loc": "kernel/sched/core.c:4174",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579715010,
      "name": "rt_mutex_setprio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071579705440,
      "name": "rt_mutex_setprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 964
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
void rt_mutex_setprio(struct task_struct * p, struct task_struct * pi_task)
```

```json
{
  "name": "rt_mutex_setprio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579746368,
      "name": "rt_mutex_setprio",
      "external": true,
      "loc": "kernel/sched/core.c:4376",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579746368,
      "name": "rt_mutex_setprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2139
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
void rt_mutex_setprio(struct task_struct * p, struct task_struct * pi_task)
```

```json
{
  "name": "rt_mutex_setprio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579783136,
      "name": "rt_mutex_setprio",
      "external": true,
      "loc": "kernel/sched/core.c:4609",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579783136,
      "name": "rt_mutex_setprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1083
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
void rt_mutex_setprio(struct task_struct * p, struct task_struct * pi_task)
```

```json
{
  "name": "rt_mutex_setprio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579773648,
      "name": "rt_mutex_setprio",
      "external": true,
      "loc": "kernel/sched/core.c:5379",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579773648,
      "name": "rt_mutex_setprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1021
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
void rt_mutex_setprio(struct task_struct * p, struct task_struct * pi_task)
```

```json
{
  "name": "rt_mutex_setprio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579781536,
      "name": "rt_mutex_setprio",
      "external": true,
      "loc": "kernel/sched/core.c:5593",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579781536,
      "name": "rt_mutex_setprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1016
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
void rt_mutex_setprio(struct task_struct * p, struct task_struct * pi_task)
```

```json
{
  "name": "rt_mutex_setprio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579875456,
      "name": "rt_mutex_setprio",
      "external": true,
      "loc": "kernel/sched/core.c:6756",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579875456,
      "name": "rt_mutex_setprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1012
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
void rt_mutex_setprio(struct task_struct * p, struct task_struct * pi_task)
```

```json
{
  "name": "rt_mutex_setprio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579991232,
      "name": "rt_mutex_setprio",
      "external": true,
      "loc": "kernel/sched/core.c:6836",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579991232,
      "name": "rt_mutex_setprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1099
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
void rt_mutex_setprio(struct task_struct * p, struct task_struct * pi_task)
```

```json
{
  "name": "rt_mutex_setprio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580152560,
      "name": "rt_mutex_setprio",
      "external": true,
      "loc": "kernel/sched/core.c:6977",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580152560,
      "name": "rt_mutex_setprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1110
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
void rt_mutex_setprio(struct task_struct * p, struct task_struct * pi_task)
```

```json
{
  "name": "rt_mutex_setprio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580203040,
      "name": "rt_mutex_setprio",
      "external": true,
      "loc": "kernel/sched/core.c:7078",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580203040,
      "name": "rt_mutex_setprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1144
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
void rt_mutex_setprio(struct task_struct * p, struct task_struct * pi_task)
```

```json
{
  "name": "rt_mutex_setprio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580251600,
      "name": "rt_mutex_setprio",
      "external": true,
      "loc": "kernel/sched/core.c:7129",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580251600,
      "name": "rt_mutex_setprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1144
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
void rt_mutex_setprio(struct task_struct * p, struct task_struct * pi_task)
```

```json
{
  "name": "rt_mutex_setprio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490926160,
      "name": "rt_mutex_setprio",
      "external": true,
      "loc": "kernel/sched/core.c:4376",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490926160,
      "name": "rt_mutex_setprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 884
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
void rt_mutex_setprio(struct task_struct * p, struct task_struct * pi_task)
```

```json
{
  "name": "rt_mutex_setprio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224942532,
      "name": "rt_mutex_setprio",
      "external": true,
      "loc": "kernel/sched/core.c:4376",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224942532,
      "name": "rt_mutex_setprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2160
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
void rt_mutex_setprio(struct task_struct * p, struct task_struct * pi_task)
```

```json
{
  "name": "rt_mutex_setprio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283777616,
      "name": "rt_mutex_setprio",
      "external": true,
      "loc": "kernel/sched/core.c:4376",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283777616,
      "name": "rt_mutex_setprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2452
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
void rt_mutex_setprio(struct task_struct * p, struct task_struct * pi_task)
```

```json
{
  "name": "rt_mutex_setprio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271561826,
      "name": "rt_mutex_setprio",
      "external": true,
      "loc": "kernel/sched/core.c:4376",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271561826,
      "name": "rt_mutex_setprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 782
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
void rt_mutex_setprio(struct task_struct * p, struct task_struct * pi_task)
```

```json
{
  "name": "rt_mutex_setprio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579722928,
      "name": "rt_mutex_setprio",
      "external": true,
      "loc": "kernel/sched/core.c:4376",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579722928,
      "name": "rt_mutex_setprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1533
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
void rt_mutex_setprio(struct task_struct * p, struct task_struct * pi_task)
```

```json
{
  "name": "rt_mutex_setprio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579650880,
      "name": "rt_mutex_setprio",
      "external": true,
      "loc": "kernel/sched/core.c:4376",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579650880,
      "name": "rt_mutex_setprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2139
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
void rt_mutex_setprio(struct task_struct * p, struct task_struct * pi_task)
```

```json
{
  "name": "rt_mutex_setprio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579710176,
      "name": "rt_mutex_setprio",
      "external": true,
      "loc": "kernel/sched/core.c:4376",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579710176,
      "name": "rt_mutex_setprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1029
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
void rt_mutex_setprio(struct task_struct * p, struct task_struct * pi_task)
```

```json
{
  "name": "rt_mutex_setprio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579753936,
      "name": "rt_mutex_setprio",
      "external": true,
      "loc": "kernel/sched/core.c:4376",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579753936,
      "name": "rt_mutex_setprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2205
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct * pi_task</code>
</li>
<li>
<b>Param removed. </b>
<code>int prio</code>
</li>
</ul>
</details>
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
