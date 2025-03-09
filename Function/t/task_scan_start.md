# Function: <code>task_scan_start</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
unsigned int task_scan_start(struct task_struct * p)
```

```json
{
  "name": "task_scan_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579624592,
      "name": "task_scan_start",
      "external": false,
      "loc": "kernel/sched/fair.c:1113",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_tick_numa",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/sched/fair.c:task_numa_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579624592,
      "name": "task_scan_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
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
unsigned int task_scan_start(struct task_struct * p)
```

```json
{
  "name": "task_scan_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579657696,
      "name": "task_scan_start",
      "external": false,
      "loc": "kernel/sched/fair.c:1100",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_tick_numa",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/sched/fair.c:task_numa_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579657696,
      "name": "task_scan_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
unsigned int task_scan_start(struct task_struct * p)
```

```json
{
  "name": "task_scan_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579691872,
      "name": "task_scan_start",
      "external": false,
      "loc": "kernel/sched/fair.c:1096",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:migrate_task_rq_fair",
        "kernel/sched/fair.c:task_tick_numa",
        "kernel/sched/fair.c:task_numa_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579691872,
      "name": "task_scan_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
unsigned int task_scan_start(struct task_struct * p)
```

```json
{
  "name": "task_scan_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579726896,
      "name": "task_scan_start",
      "external": false,
      "loc": "kernel/sched/fair.c:1143",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:migrate_task_rq_fair",
        "kernel/sched/fair.c:task_numa_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579726896,
      "name": "task_scan_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
unsigned int task_scan_start(struct task_struct * p)
```

```json
{
  "name": "task_scan_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579769408,
      "name": "task_scan_start",
      "external": false,
      "loc": "kernel/sched/fair.c:1142",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:migrate_task_rq_fair",
        "kernel/sched/fair.c:task_numa_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579769408,
      "name": "task_scan_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
unsigned int task_scan_start(struct task_struct * p)
```

```json
{
  "name": "task_scan_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579801024,
      "name": "task_scan_start",
      "external": false,
      "loc": "kernel/sched/fair.c:1153",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:migrate_task_rq_fair",
        "kernel/sched/fair.c:task_numa_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579801024,
      "name": "task_scan_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
unsigned int task_scan_start(struct task_struct * p)
```

```json
{
  "name": "task_scan_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579792352,
      "name": "task_scan_start",
      "external": false,
      "loc": "kernel/sched/fair.c:1160",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:migrate_task_rq_fair",
        "kernel/sched/fair.c:task_numa_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579792352,
      "name": "task_scan_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 383
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
unsigned int task_scan_start(struct task_struct * p)
```

```json
{
  "name": "task_scan_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579800272,
      "name": "task_scan_start",
      "external": false,
      "loc": "kernel/sched/fair.c:1157",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:migrate_task_rq_fair",
        "kernel/sched/fair.c:task_numa_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579800272,
      "name": "task_scan_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
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
unsigned int task_scan_start(struct task_struct * p)
```

```json
{
  "name": "task_scan_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579896672,
      "name": "task_scan_start",
      "external": false,
      "loc": "kernel/sched/fair.c:1146",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:migrate_task_rq_fair",
        "kernel/sched/fair.c:task_numa_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579896672,
      "name": "task_scan_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
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
unsigned int task_scan_start(struct task_struct * p)
```

```json
{
  "name": "task_scan_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580008608,
      "name": "task_scan_start",
      "external": false,
      "loc": "kernel/sched/fair.c:1148",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:migrate_task_rq_fair",
        "kernel/sched/fair.c:task_numa_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580008608,
      "name": "task_scan_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 398
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
unsigned int task_scan_start(struct task_struct * p)
```

```json
{
  "name": "task_scan_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580170624,
      "name": "task_scan_start",
      "external": false,
      "loc": "kernel/sched/fair.c:1187",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:migrate_task_rq_fair",
        "kernel/sched/fair.c:task_numa_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580170624,
      "name": "task_scan_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
unsigned int task_scan_start(struct task_struct * p)
```

```json
{
  "name": "task_scan_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580236112,
      "name": "task_scan_start",
      "external": false,
      "loc": "kernel/sched/fair.c:1204",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:migrate_task_rq_fair",
        "kernel/sched/fair.c:task_numa_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580236112,
      "name": "task_scan_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
unsigned int task_scan_start(struct task_struct * p)
```

```json
{
  "name": "task_scan_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580285632,
      "name": "task_scan_start",
      "external": false,
      "loc": "kernel/sched/fair.c:1445",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:migrate_task_rq_fair",
        "kernel/sched/fair.c:task_numa_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580285632,
      "name": "task_scan_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
unsigned int task_scan_start(struct task_struct * p)
```

```json
{
  "name": "task_scan_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490950504,
      "name": "task_scan_start",
      "external": false,
      "loc": "kernel/sched/fair.c:1142",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:migrate_task_rq_fair",
        "kernel/sched/fair.c:task_numa_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490950504,
      "name": "task_scan_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
unsigned int task_scan_start(struct task_struct * p)
```

```json
{
  "name": "task_scan_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283811824,
      "name": "task_scan_start",
      "external": false,
      "loc": "kernel/sched/fair.c:1142",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:migrate_task_rq_fair",
        "kernel/sched/fair.c:task_numa_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283811824,
      "name": "task_scan_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
    }
  ]
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
unsigned int task_scan_start(struct task_struct * p)
```

```json
{
  "name": "task_scan_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579745264,
      "name": "task_scan_start",
      "external": false,
      "loc": "kernel/sched/fair.c:1142",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:migrate_task_rq_fair",
        "kernel/sched/fair.c:task_numa_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579745264,
      "name": "task_scan_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
unsigned int task_scan_start(struct task_struct * p)
```

```json
{
  "name": "task_scan_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579675648,
      "name": "task_scan_start",
      "external": false,
      "loc": "kernel/sched/fair.c:1142",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:migrate_task_rq_fair",
        "kernel/sched/fair.c:task_numa_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579675648,
      "name": "task_scan_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
unsigned int task_scan_start(struct task_struct * p)
```

```json
{
  "name": "task_scan_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579729776,
      "name": "task_scan_start",
      "external": false,
      "loc": "kernel/sched/fair.c:1142",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:migrate_task_rq_fair",
        "kernel/sched/fair.c:task_numa_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579729776,
      "name": "task_scan_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
unsigned int task_scan_start(struct task_struct * p)
```

```json
{
  "name": "task_scan_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579777552,
      "name": "task_scan_start",
      "external": false,
      "loc": "kernel/sched/fair.c:1142",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:migrate_task_rq_fair",
        "kernel/sched/fair.c:task_numa_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579777552,
      "name": "task_scan_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
unsigned int task_scan_start(struct task_struct * p)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
unsigned int task_scan_start(struct task_struct * p)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
unsigned int task_scan_start(struct task_struct * p)
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
