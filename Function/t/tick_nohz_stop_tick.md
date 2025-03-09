# Function: <code>tick_nohz_stop_tick</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tick_nohz_stop_tick",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580053987,
      "name": "tick_nohz_stop_tick",
      "external": false,
      "loc": "kernel/time/tick-sched.c:732",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
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
  "name": "tick_nohz_stop_tick",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580100788,
      "name": "tick_nohz_stop_tick",
      "external": false,
      "loc": "kernel/time/tick-sched.c:729",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
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
  "name": "tick_nohz_stop_tick",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580144707,
      "name": "tick_nohz_stop_tick",
      "external": false,
      "loc": "kernel/time/tick-sched.c:739",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
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
  "name": "tick_nohz_stop_tick",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580192739,
      "name": "tick_nohz_stop_tick",
      "external": false,
      "loc": "kernel/time/tick-sched.c:745",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void tick_nohz_stop_tick(struct tick_sched * ts, int cpu)
```

```json
{
  "name": "tick_nohz_stop_tick",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580255984,
      "name": "tick_nohz_stop_tick",
      "external": false,
      "loc": "kernel/time/tick-sched.c:770",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580255984,
      "name": "tick_nohz_stop_tick",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 435
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
void tick_nohz_stop_tick(struct tick_sched * ts, int cpu)
```

```json
{
  "name": "tick_nohz_stop_tick",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580239632,
      "name": "tick_nohz_stop_tick",
      "external": false,
      "loc": "kernel/time/tick-sched.c:818",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580239632,
      "name": "tick_nohz_stop_tick",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
void tick_nohz_stop_tick(struct tick_sched * ts, int cpu)
```

```json
{
  "name": "tick_nohz_stop_tick",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580244880,
      "name": "tick_nohz_stop_tick",
      "external": false,
      "loc": "kernel/time/tick-sched.c:819",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580244880,
      "name": "tick_nohz_stop_tick",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
void tick_nohz_stop_tick(struct tick_sched * ts, int cpu)
```

```json
{
  "name": "tick_nohz_stop_tick",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tick_nohz_stop_tick",
      "external": false,
      "loc": "kernel/time/tick-sched.c:854",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580395520,
      "name": "tick_nohz_stop_tick",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
    },
    {
      "addr": 18446744071592157512,
      "name": "tick_nohz_stop_tick.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void tick_nohz_stop_tick(struct tick_sched * ts, int cpu)
```

```json
{
  "name": "tick_nohz_stop_tick",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tick_nohz_stop_tick",
      "external": false,
      "loc": "kernel/time/tick-sched.c:868",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580614736,
      "name": "tick_nohz_stop_tick",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 523
    },
    {
      "addr": 18446744071593932445,
      "name": "tick_nohz_stop_tick.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
void tick_nohz_stop_tick(struct tick_sched * ts, int cpu)
```

```json
{
  "name": "tick_nohz_stop_tick",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tick_nohz_stop_tick",
      "external": false,
      "loc": "kernel/time/tick-sched.c:868",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580879600,
      "name": "tick_nohz_stop_tick",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 523
    },
    {
      "addr": 18446744071595998594,
      "name": "tick_nohz_stop_tick.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
void tick_nohz_stop_tick(struct tick_sched * ts, int cpu)
```

```json
{
  "name": "tick_nohz_stop_tick",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tick_nohz_stop_tick",
      "external": false,
      "loc": "kernel/time/tick-sched.c:884",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580964112,
      "name": "tick_nohz_stop_tick",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 527
    },
    {
      "addr": 18446744071596516754,
      "name": "tick_nohz_stop_tick.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
void tick_nohz_stop_tick(struct tick_sched * ts, int cpu)
```

```json
{
  "name": "tick_nohz_stop_tick",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tick_nohz_stop_tick",
      "external": false,
      "loc": "kernel/time/tick-sched.c:889",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581056880,
      "name": "tick_nohz_stop_tick",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 527
    },
    {
      "addr": 18446744071597416402,
      "name": "tick_nohz_stop_tick.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
  "name": "tick_nohz_stop_tick",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491422880,
      "name": "tick_nohz_stop_tick",
      "external": false,
      "loc": "kernel/time/tick-sched.c:745",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
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
  "name": "tick_nohz_stop_tick",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225416464,
      "name": "tick_nohz_stop_tick",
      "external": false,
      "loc": "kernel/time/tick-sched.c:745",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
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
  "name": "tick_nohz_stop_tick",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284370312,
      "name": "tick_nohz_stop_tick",
      "external": false,
      "loc": "kernel/time/tick-sched.c:745",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
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
  "name": "tick_nohz_stop_tick",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271890078,
      "name": "tick_nohz_stop_tick",
      "external": false,
      "loc": "kernel/time/tick-sched.c:745",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
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
  "name": "tick_nohz_stop_tick",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580161539,
      "name": "tick_nohz_stop_tick",
      "external": false,
      "loc": "kernel/time/tick-sched.c:745",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void tick_nohz_stop_tick(struct tick_sched * ts, int cpu)
```

```json
{
  "name": "tick_nohz_stop_tick",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580107600,
      "name": "tick_nohz_stop_tick",
      "external": false,
      "loc": "kernel/time/tick-sched.c:745",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_irq_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580107600,
      "name": "tick_nohz_stop_tick",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 435
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tick_nohz_stop_tick",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580153011,
      "name": "tick_nohz_stop_tick",
      "external": false,
      "loc": "kernel/time/tick-sched.c:745",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
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
  "name": "tick_nohz_stop_tick",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580204995,
      "name": "tick_nohz_stop_tick",
      "external": false,
      "loc": "kernel/time/tick-sched.c:745",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
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
void tick_nohz_stop_tick(struct tick_sched * ts, int cpu)
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➕</summary>

```c
void tick_nohz_stop_tick(struct tick_sched * ts, int cpu)
```
</details>
</li>
</ul>
