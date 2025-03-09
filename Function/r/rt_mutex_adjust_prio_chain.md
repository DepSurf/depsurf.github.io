# Function: <code>rt_mutex_adjust_prio_chain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int rt_mutex_adjust_prio_chain(struct task_struct * task, enum rtmutex_chainwalk chwalk, struct rt_mutex * orig_lock, struct rt_mutex * next_lock, struct rt_mutex_waiter * orig_waiter, struct task_struct * top_task)
```

```json
{
  "name": "rt_mutex_adjust_prio_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579676512,
      "name": "rt_mutex_adjust_prio_chain",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:424",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579676512,
      "name": "rt_mutex_adjust_prio_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1072
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
int rt_mutex_adjust_prio_chain(struct task_struct * task, enum rtmutex_chainwalk chwalk, struct rt_mutex * orig_lock, struct rt_mutex * next_lock, struct rt_mutex_waiter * orig_waiter, struct task_struct * top_task)
```

```json
{
  "name": "rt_mutex_adjust_prio_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579695696,
      "name": "rt_mutex_adjust_prio_chain",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:426",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579695696,
      "name": "rt_mutex_adjust_prio_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 969
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
int rt_mutex_adjust_prio_chain(struct task_struct * task, enum rtmutex_chainwalk chwalk, struct rt_mutex * orig_lock, struct rt_mutex * next_lock, struct rt_mutex_waiter * orig_waiter, struct task_struct * top_task)
```

```json
{
  "name": "rt_mutex_adjust_prio_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579722800,
      "name": "rt_mutex_adjust_prio_chain",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:490",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579722800,
      "name": "rt_mutex_adjust_prio_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 988
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
int rt_mutex_adjust_prio_chain(struct task_struct * task, enum rtmutex_chainwalk chwalk, struct rt_mutex * orig_lock, struct rt_mutex * next_lock, struct rt_mutex_waiter * orig_waiter, struct task_struct * top_task)
```

```json
{
  "name": "rt_mutex_adjust_prio_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579718656,
      "name": "rt_mutex_adjust_prio_chain",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:460",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579718656,
      "name": "rt_mutex_adjust_prio_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1135
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
int rt_mutex_adjust_prio_chain(struct task_struct * task, enum rtmutex_chainwalk chwalk, struct rt_mutex * orig_lock, struct rt_mutex * next_lock, struct rt_mutex_waiter * orig_waiter, struct task_struct * top_task)
```

```json
{
  "name": "rt_mutex_adjust_prio_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579751136,
      "name": "rt_mutex_adjust_prio_chain",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:448",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579751136,
      "name": "rt_mutex_adjust_prio_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1253
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int rt_mutex_adjust_prio_chain(struct task_struct * task, enum rtmutex_chainwalk chwalk, struct rt_mutex * orig_lock, struct rt_mutex * next_lock, struct rt_mutex_waiter * orig_waiter, struct task_struct * top_task)
```

```json
{
  "name": "rt_mutex_adjust_prio_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rt_mutex_adjust_prio_chain",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:448",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579785632,
      "name": "rt_mutex_adjust_prio_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1172
    },
    {
      "addr": 18446744071579788577,
      "name": "rt_mutex_adjust_prio_chain.cold.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int rt_mutex_adjust_prio_chain(struct task_struct * task, enum rtmutex_chainwalk chwalk, struct rt_mutex * orig_lock, struct rt_mutex * next_lock, struct rt_mutex_waiter * orig_waiter, struct task_struct * top_task)
```

```json
{
  "name": "rt_mutex_adjust_prio_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rt_mutex_adjust_prio_chain",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:448",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579832096,
      "name": "rt_mutex_adjust_prio_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1181
    },
    {
      "addr": 18446744071579835041,
      "name": "rt_mutex_adjust_prio_chain.cold.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
int rt_mutex_adjust_prio_chain(struct task_struct * task, enum rtmutex_chainwalk chwalk, struct rt_mutex * orig_lock, struct rt_mutex * next_lock, struct rt_mutex_waiter * orig_waiter, struct task_struct * top_task)
```

```json
{
  "name": "rt_mutex_adjust_prio_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rt_mutex_adjust_prio_chain",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:449",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579866816,
      "name": "rt_mutex_adjust_prio_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1343
    },
    {
      "addr": 18446744071579870134,
      "name": "rt_mutex_adjust_prio_chain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int rt_mutex_adjust_prio_chain(struct task_struct * task, enum rtmutex_chainwalk chwalk, struct rt_mutex * orig_lock, struct rt_mutex * next_lock, struct rt_mutex_waiter * orig_waiter, struct task_struct * top_task)
```

```json
{
  "name": "rt_mutex_adjust_prio_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rt_mutex_adjust_prio_chain",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:449",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579915440,
      "name": "rt_mutex_adjust_prio_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1343
    },
    {
      "addr": 18446744071579918739,
      "name": "rt_mutex_adjust_prio_chain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int rt_mutex_adjust_prio_chain(struct task_struct * task, enum rtmutex_chainwalk chwalk, struct rt_mutex * orig_lock, struct rt_mutex * next_lock, struct rt_mutex_waiter * orig_waiter, struct task_struct * top_task)
```

```json
{
  "name": "rt_mutex_adjust_prio_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rt_mutex_adjust_prio_chain",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:447",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579959904,
      "name": "rt_mutex_adjust_prio_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1638
    },
    {
      "addr": 18446744071579963707,
      "name": "rt_mutex_adjust_prio_chain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int rt_mutex_adjust_prio_chain(struct task_struct * task, enum rtmutex_chainwalk chwalk, struct rt_mutex * orig_lock, struct rt_mutex * next_lock, struct rt_mutex_waiter * orig_waiter, struct task_struct * top_task)
```

```json
{
  "name": "rt_mutex_adjust_prio_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rt_mutex_adjust_prio_chain",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:447",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579948048,
      "name": "rt_mutex_adjust_prio_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1638
    },
    {
      "addr": 18446744071591291073,
      "name": "rt_mutex_adjust_prio_chain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
int rt_mutex_adjust_prio_chain(struct task_struct * task, enum rtmutex_chainwalk chwalk, struct rt_mutex * orig_lock, struct rt_mutex * next_lock, struct rt_mutex_waiter * orig_waiter, struct task_struct * top_task)
```

```json
{
  "name": "rt_mutex_adjust_prio_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591649792,
      "name": "rt_mutex_adjust_prio_chain",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:424",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591649792,
      "name": "rt_mutex_adjust_prio_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2117
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
int rt_mutex_adjust_prio_chain(struct task_struct * task, enum rtmutex_chainwalk chwalk, struct rt_mutex_base * orig_lock, struct rt_mutex_base * next_lock, struct rt_mutex_waiter * orig_waiter, struct task_struct * top_task)
```

```json
{
  "name": "rt_mutex_adjust_prio_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592823520,
      "name": "rt_mutex_adjust_prio_chain",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:567",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex_api.c:remove_waiter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592823520,
      "name": "rt_mutex_adjust_prio_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2169
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
int rt_mutex_adjust_prio_chain(struct task_struct * task, enum rtmutex_chainwalk chwalk, struct rt_mutex_base * orig_lock, struct rt_mutex_base * next_lock, struct rt_mutex_waiter * orig_waiter, struct task_struct * top_task)
```

```json
{
  "name": "rt_mutex_adjust_prio_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594731152,
      "name": "rt_mutex_adjust_prio_chain",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:576",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex_api.c:remove_waiter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594731152,
      "name": "rt_mutex_adjust_prio_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2348
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
int rt_mutex_adjust_prio_chain(struct task_struct * task, enum rtmutex_chainwalk chwalk, struct rt_mutex_base * orig_lock, struct rt_mutex_base * next_lock, struct rt_mutex_waiter * orig_waiter, struct task_struct * top_task)
```

```json
{
  "name": "rt_mutex_adjust_prio_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596482880,
      "name": "rt_mutex_adjust_prio_chain",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:613",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex_api.c:remove_waiter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596482880,
      "name": "rt_mutex_adjust_prio_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2338
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
int rt_mutex_adjust_prio_chain(struct task_struct * task, enum rtmutex_chainwalk chwalk, struct rt_mutex_base * orig_lock, struct rt_mutex_base * next_lock, struct rt_mutex_waiter * orig_waiter, struct task_struct * top_task)
```

```json
{
  "name": "rt_mutex_adjust_prio_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597024512,
      "name": "rt_mutex_adjust_prio_chain",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:655",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex_api.c:remove_waiter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597024512,
      "name": "rt_mutex_adjust_prio_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2268
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
int rt_mutex_adjust_prio_chain(struct task_struct * task, enum rtmutex_chainwalk chwalk, struct rt_mutex_base * orig_lock, struct rt_mutex_base * next_lock, struct rt_mutex_waiter * orig_waiter, struct task_struct * top_task)
```

```json
{
  "name": "rt_mutex_adjust_prio_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597953856,
      "name": "rt_mutex_adjust_prio_chain",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:674",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex_api.c:remove_waiter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597953856,
      "name": "rt_mutex_adjust_prio_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2268
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
int rt_mutex_adjust_prio_chain(struct task_struct * task, enum rtmutex_chainwalk chwalk, struct rt_mutex * orig_lock, struct rt_mutex * next_lock, struct rt_mutex_waiter * orig_waiter, struct task_struct * top_task)
```

```json
{
  "name": "rt_mutex_adjust_prio_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491119064,
      "name": "rt_mutex_adjust_prio_chain",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:449",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491119064,
      "name": "rt_mutex_adjust_prio_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2024
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
int rt_mutex_adjust_prio_chain(struct task_struct * task, enum rtmutex_chainwalk chwalk, struct rt_mutex * orig_lock, struct rt_mutex * next_lock, struct rt_mutex_waiter * orig_waiter, struct task_struct * top_task)
```

```json
{
  "name": "rt_mutex_adjust_prio_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225120188,
      "name": "rt_mutex_adjust_prio_chain",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:449",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225120188,
      "name": "rt_mutex_adjust_prio_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1720
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
int rt_mutex_adjust_prio_chain(struct task_struct * task, enum rtmutex_chainwalk chwalk, struct rt_mutex * orig_lock, struct rt_mutex * next_lock, struct rt_mutex_waiter * orig_waiter, struct task_struct * top_task)
```

```json
{
  "name": "rt_mutex_adjust_prio_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284009792,
      "name": "rt_mutex_adjust_prio_chain",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:449",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284009792,
      "name": "rt_mutex_adjust_prio_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2328
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
int rt_mutex_adjust_prio_chain(struct task_struct * task, enum rtmutex_chainwalk chwalk, struct rt_mutex * orig_lock, struct rt_mutex * next_lock, struct rt_mutex_waiter * orig_waiter, struct task_struct * top_task)
```

```json
{
  "name": "rt_mutex_adjust_prio_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271693678,
      "name": "rt_mutex_adjust_prio_chain",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:449",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271693678,
      "name": "rt_mutex_adjust_prio_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1614
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int rt_mutex_adjust_prio_chain(struct task_struct * task, enum rtmutex_chainwalk chwalk, struct rt_mutex * orig_lock, struct rt_mutex * next_lock, struct rt_mutex_waiter * orig_waiter, struct task_struct * top_task)
```

```json
{
  "name": "rt_mutex_adjust_prio_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rt_mutex_adjust_prio_chain",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:449",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579887552,
      "name": "rt_mutex_adjust_prio_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1343
    },
    {
      "addr": 18446744071579890851,
      "name": "rt_mutex_adjust_prio_chain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int rt_mutex_adjust_prio_chain(struct task_struct * task, enum rtmutex_chainwalk chwalk, struct rt_mutex * orig_lock, struct rt_mutex * next_lock, struct rt_mutex_waiter * orig_waiter, struct task_struct * top_task)
```

```json
{
  "name": "rt_mutex_adjust_prio_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rt_mutex_adjust_prio_chain",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:449",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579822528,
      "name": "rt_mutex_adjust_prio_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1313
    },
    {
      "addr": 18446744071579825805,
      "name": "rt_mutex_adjust_prio_chain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int rt_mutex_adjust_prio_chain(struct task_struct * task, enum rtmutex_chainwalk chwalk, struct rt_mutex * orig_lock, struct rt_mutex * next_lock, struct rt_mutex_waiter * orig_waiter, struct task_struct * top_task)
```

```json
{
  "name": "rt_mutex_adjust_prio_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rt_mutex_adjust_prio_chain",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:449",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579875712,
      "name": "rt_mutex_adjust_prio_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1343
    },
    {
      "addr": 18446744071579879011,
      "name": "rt_mutex_adjust_prio_chain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int rt_mutex_adjust_prio_chain(struct task_struct * task, enum rtmutex_chainwalk chwalk, struct rt_mutex * orig_lock, struct rt_mutex * next_lock, struct rt_mutex_waiter * orig_waiter, struct task_struct * top_task)
```

```json
{
  "name": "rt_mutex_adjust_prio_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rt_mutex_adjust_prio_chain",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:449",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_adjust_pi",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579921216,
      "name": "rt_mutex_adjust_prio_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1437
    },
    {
      "addr": 18446744071579924618,
      "name": "rt_mutex_adjust_prio_chain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct rt_mutex * orig_lock</code> ➡️ <code>struct rt_mutex_base * orig_lock</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct rt_mutex * next_lock</code> ➡️ <code>struct rt_mutex_base * next_lock</code>
</li>
</ul>
</details>
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
