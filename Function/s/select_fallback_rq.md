# Function: <code>select_fallback_rq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int select_fallback_rq(int cpu, struct task_struct * p)
```

```json
{
  "name": "select_fallback_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579545888,
      "name": "select_fallback_rq",
      "external": false,
      "loc": "kernel/sched/core.c:1547",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:migration_call",
        "kernel/sched/core.c:wake_up_new_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579545888,
      "name": "select_fallback_rq",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int select_fallback_rq(int cpu, struct task_struct * p)
```

```json
{
  "name": "select_fallback_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579557232,
      "name": "select_fallback_rq",
      "external": false,
      "loc": "kernel/sched/core.c:1513",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579557232,
      "name": "select_fallback_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
int select_fallback_rq(int cpu, struct task_struct * p)
```

```json
{
  "name": "select_fallback_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579582176,
      "name": "select_fallback_rq",
      "external": false,
      "loc": "kernel/sched/core.c:1524",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579582176,
      "name": "select_fallback_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
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
int select_fallback_rq(int cpu, struct task_struct * p)
```

```json
{
  "name": "select_fallback_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579565696,
      "name": "select_fallback_rq",
      "external": false,
      "loc": "kernel/sched/core.c:1456",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579565696,
      "name": "select_fallback_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
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
int select_fallback_rq(int cpu, struct task_struct * p)
```

```json
{
  "name": "select_fallback_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579595408,
      "name": "select_fallback_rq",
      "external": false,
      "loc": "kernel/sched/core.c:1475",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579595408,
      "name": "select_fallback_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
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
int select_fallback_rq(int cpu, struct task_struct * p)
```

```json
{
  "name": "select_fallback_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "select_fallback_rq",
      "external": false,
      "loc": "kernel/sched/core.c:1473",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579627072,
      "name": "select_fallback_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
    },
    {
      "addr": 18446744071579643649,
      "name": "select_fallback_rq.cold.84",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int select_fallback_rq(int cpu, struct task_struct * p)
```

```json
{
  "name": "select_fallback_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "select_fallback_rq",
      "external": false,
      "loc": "kernel/sched/core.c:1471",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579664592,
      "name": "select_fallback_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
    },
    {
      "addr": 18446744071579681203,
      "name": "select_fallback_rq.cold.84",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int select_fallback_rq(int cpu, struct task_struct * p)
```

```json
{
  "name": "select_fallback_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "select_fallback_rq",
      "external": false,
      "loc": "kernel/sched/core.c:1911",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579694912,
      "name": "select_fallback_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
    },
    {
      "addr": 18446744071579714931,
      "name": "select_fallback_rq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
int select_fallback_rq(int cpu, struct task_struct * p)
```

```json
{
  "name": "select_fallback_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "select_fallback_rq",
      "external": false,
      "loc": "kernel/sched/core.c:2031",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579735520,
      "name": "select_fallback_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
    },
    {
      "addr": 18446744071579757435,
      "name": "select_fallback_rq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
int select_fallback_rq(int cpu, struct task_struct * p)
```

```json
{
  "name": "select_fallback_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "select_fallback_rq",
      "external": false,
      "loc": "kernel/sched/core.c:2101",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:migrate_tasks",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579772976,
      "name": "select_fallback_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    },
    {
      "addr": 18446744071579790845,
      "name": "select_fallback_rq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
int select_fallback_rq(int cpu, struct task_struct * p)
```

```json
{
  "name": "select_fallback_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "select_fallback_rq",
      "external": false,
      "loc": "kernel/sched/core.c:2727",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579747840,
      "name": "select_fallback_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
    },
    {
      "addr": 18446744071591282227,
      "name": "select_fallback_rq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int select_fallback_rq(int cpu, struct task_struct * p)
```

```json
{
  "name": "select_fallback_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "select_fallback_rq",
      "external": false,
      "loc": "kernel/sched/core.c:2748",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579753248,
      "name": "select_fallback_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
    },
    {
      "addr": 18446744071591225269,
      "name": "select_fallback_rq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int select_fallback_rq(int cpu, struct task_struct * p)
```

```json
{
  "name": "select_fallback_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "select_fallback_rq",
      "external": false,
      "loc": "kernel/sched/core.c:3316",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579837120,
      "name": "select_fallback_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
    },
    {
      "addr": 18446744071592107076,
      "name": "select_fallback_rq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int select_fallback_rq(int cpu, struct task_struct * p)
```

```json
{
  "name": "select_fallback_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "select_fallback_rq",
      "external": false,
      "loc": "kernel/sched/core.c:3415",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579951328,
      "name": "select_fallback_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 562
    },
    {
      "addr": 18446744071593874780,
      "name": "select_fallback_rq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
int select_fallback_rq(int cpu, struct task_struct * p)
```

```json
{
  "name": "select_fallback_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580110352,
      "name": "select_fallback_rq",
      "external": false,
      "loc": "kernel/sched/core.c:3471",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580110352,
      "name": "select_fallback_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 656
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
int select_fallback_rq(int cpu, struct task_struct * p)
```

```json
{
  "name": "select_fallback_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580172304,
      "name": "select_fallback_rq",
      "external": false,
      "loc": "kernel/sched/core.c:3540",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580172304,
      "name": "select_fallback_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 657
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
int select_fallback_rq(int cpu, struct task_struct * p)
```

```json
{
  "name": "select_fallback_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580218672,
      "name": "select_fallback_rq",
      "external": false,
      "loc": "kernel/sched/core.c:3559",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580218672,
      "name": "select_fallback_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 657
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
int select_fallback_rq(int cpu, struct task_struct * p)
```

```json
{
  "name": "select_fallback_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490914856,
      "name": "select_fallback_rq",
      "external": false,
      "loc": "kernel/sched/core.c:2031",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490914856,
      "name": "select_fallback_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int select_fallback_rq(int cpu, struct task_struct * p)
```

```json
{
  "name": "select_fallback_rq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224931356,
      "name": "select_fallback_rq",
      "external": false,
      "loc": "kernel/sched/core.c:2031",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224931356,
      "name": "select_fallback_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
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
int select_fallback_rq(int cpu, struct task_struct * p)
```

```json
{
  "name": "select_fallback_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283761392,
      "name": "select_fallback_rq",
      "external": false,
      "loc": "kernel/sched/core.c:2031",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283761392,
      "name": "select_fallback_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 592
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "select_fallback_rq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271560082,
      "name": "select_fallback_rq",
      "external": false,
      "loc": "kernel/sched/core.c:2031",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int select_fallback_rq(int cpu, struct task_struct * p)
```

```json
{
  "name": "select_fallback_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "select_fallback_rq",
      "external": false,
      "loc": "kernel/sched/core.c:2031",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579712176,
      "name": "select_fallback_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
    },
    {
      "addr": 18446744071579733355,
      "name": "select_fallback_rq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
int select_fallback_rq(int cpu, struct task_struct * p)
```

```json
{
  "name": "select_fallback_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "select_fallback_rq",
      "external": false,
      "loc": "kernel/sched/core.c:2031",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579640032,
      "name": "select_fallback_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
    },
    {
      "addr": 18446744071579662198,
      "name": "select_fallback_rq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
int select_fallback_rq(int cpu, struct task_struct * p)
```

```json
{
  "name": "select_fallback_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "select_fallback_rq",
      "external": false,
      "loc": "kernel/sched/core.c:2031",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579700496,
      "name": "select_fallback_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
    },
    {
      "addr": 18446744071579717803,
      "name": "select_fallback_rq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
int select_fallback_rq(int cpu, struct task_struct * p)
```

```json
{
  "name": "select_fallback_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "select_fallback_rq",
      "external": false,
      "loc": "kernel/sched/core.c:2031",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579742800,
      "name": "select_fallback_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
    },
    {
      "addr": 18446744071579765082,
      "name": "select_fallback_rq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int select_fallback_rq(int cpu, struct task_struct * p)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
