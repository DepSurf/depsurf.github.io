# Function: <code>rcu_sched_clock_irq</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void rcu_sched_clock_irq(int user)
```

```json
{
  "name": "rcu_sched_clock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_sched_clock_irq",
      "external": true,
      "loc": "kernel/rcu/tree.c:2169",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:update_process_times"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580018211,
      "name": "rcu_sched_clock_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 957
    },
    {
      "addr": 18446744071580013024,
      "name": "rcu_sched_clock_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 886
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
void rcu_sched_clock_irq(int user)
```

```json
{
  "name": "rcu_sched_clock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_sched_clock_irq",
      "external": true,
      "loc": "kernel/rcu/tree.c:2231",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:update_process_times"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580068733,
      "name": "rcu_sched_clock_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 961
    },
    {
      "addr": 18446744071580063456,
      "name": "rcu_sched_clock_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1036
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
void rcu_sched_clock_irq(int user)
```

```json
{
  "name": "rcu_sched_clock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580122736,
      "name": "rcu_sched_clock_irq",
      "external": true,
      "loc": "kernel/rcu/tree.c:2490",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:update_process_times"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580122736,
      "name": "rcu_sched_clock_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
void rcu_sched_clock_irq(int user)
```

```json
{
  "name": "rcu_sched_clock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580104416,
      "name": "rcu_sched_clock_irq",
      "external": true,
      "loc": "kernel/rcu/tree.c:2617",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:update_process_times"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580104416,
      "name": "rcu_sched_clock_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void rcu_sched_clock_irq(int user)
```

```json
{
  "name": "rcu_sched_clock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580107296,
      "name": "rcu_sched_clock_irq",
      "external": true,
      "loc": "kernel/rcu/tree.c:2634",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:update_process_times"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580107296,
      "name": "rcu_sched_clock_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 417
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
void rcu_sched_clock_irq(int user)
```

```json
{
  "name": "rcu_sched_clock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_sched_clock_irq",
      "external": true,
      "loc": "kernel/rcu/tree.c:2585",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:update_process_times"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592146393,
      "name": "rcu_sched_clock_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071580248048,
      "name": "rcu_sched_clock_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 569
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
void rcu_sched_clock_irq(int user)
```

```json
{
  "name": "rcu_sched_clock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_sched_clock_irq",
      "external": true,
      "loc": "kernel/rcu/tree.c:2653",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:update_process_times"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593919101,
      "name": "rcu_sched_clock_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071580416080,
      "name": "rcu_sched_clock_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 705
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void rcu_sched_clock_irq(int user)
```

```json
{
  "name": "rcu_sched_clock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_sched_clock_irq",
      "external": true,
      "loc": "kernel/rcu/tree.c:2321",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:update_process_times"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595991837,
      "name": "rcu_sched_clock_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071580654320,
      "name": "rcu_sched_clock_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void rcu_sched_clock_irq(int user)
```

```json
{
  "name": "rcu_sched_clock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_sched_clock_irq",
      "external": true,
      "loc": "kernel/rcu/tree.c:2214",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:update_process_times"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596510000,
      "name": "rcu_sched_clock_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071580730176,
      "name": "rcu_sched_clock_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void rcu_sched_clock_irq(int user)
```

```json
{
  "name": "rcu_sched_clock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_sched_clock_irq",
      "external": true,
      "loc": "kernel/rcu/tree.c:2269",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:update_process_times"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597408853,
      "name": "rcu_sched_clock_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580815040,
      "name": "rcu_sched_clock_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 952
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
void rcu_sched_clock_irq(int user)
```

```json
{
  "name": "rcu_sched_clock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491273432,
      "name": "rcu_sched_clock_irq",
      "external": true,
      "loc": "kernel/rcu/tree.c:2231",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:update_process_times"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491273432,
      "name": "rcu_sched_clock_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2208
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
void rcu_sched_clock_irq(int user)
```

```json
{
  "name": "rcu_sched_clock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225282744,
      "name": "rcu_sched_clock_irq",
      "external": true,
      "loc": "kernel/rcu/tree.c:2231",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:update_process_times"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225282744,
      "name": "rcu_sched_clock_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2576
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
void rcu_sched_clock_irq(int user)
```

```json
{
  "name": "rcu_sched_clock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284179344,
      "name": "rcu_sched_clock_irq",
      "external": true,
      "loc": "kernel/rcu/tree.c:2231",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:update_process_times"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284179344,
      "name": "rcu_sched_clock_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2632
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
void rcu_sched_clock_irq(int user)
```

```json
{
  "name": "rcu_sched_clock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271794804,
      "name": "rcu_sched_clock_irq",
      "external": true,
      "loc": "kernel/rcu/tree.c:2231",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:update_process_times"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271794804,
      "name": "rcu_sched_clock_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1858
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
void rcu_sched_clock_irq(int user)
```

```json
{
  "name": "rcu_sched_clock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_sched_clock_irq",
      "external": true,
      "loc": "kernel/rcu/tree.c:2231",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:update_process_times"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580037469,
      "name": "rcu_sched_clock_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 961
    },
    {
      "addr": 18446744071580032192,
      "name": "rcu_sched_clock_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1036
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
void rcu_sched_clock_irq(int user)
```

```json
{
  "name": "rcu_sched_clock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_sched_clock_irq",
      "external": true,
      "loc": "kernel/rcu/tree.c:2231",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:update_process_times"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579982901,
      "name": "rcu_sched_clock_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 964
    },
    {
      "addr": 18446744071579976432,
      "name": "rcu_sched_clock_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1156
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
void rcu_sched_clock_irq(int user)
```

```json
{
  "name": "rcu_sched_clock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_sched_clock_irq",
      "external": true,
      "loc": "kernel/rcu/tree.c:2231",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:update_process_times"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580029005,
      "name": "rcu_sched_clock_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 961
    },
    {
      "addr": 18446744071580023728,
      "name": "rcu_sched_clock_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1036
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
void rcu_sched_clock_irq(int user)
```

```json
{
  "name": "rcu_sched_clock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_sched_clock_irq",
      "external": true,
      "loc": "kernel/rcu/tree.c:2231",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:update_process_times"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580079403,
      "name": "rcu_sched_clock_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1264
    },
    {
      "addr": 18446744071580073248,
      "name": "rcu_sched_clock_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1407
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
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void rcu_sched_clock_irq(int user)
```
</details>
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
