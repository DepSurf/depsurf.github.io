# Function: <code>__migrate_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct rq * __migrate_task(struct rq * rq, struct task_struct * p, int dest_cpu)
```

```json
{
  "name": "__migrate_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579547456,
      "name": "__migrate_task",
      "external": false,
      "loc": "kernel/sched/core.c:1104",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:migration_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579547456,
      "name": "__migrate_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
struct rq * __migrate_task(struct rq * rq, struct task_struct * p, int dest_cpu)
```

```json
{
  "name": "__migrate_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579558816,
      "name": "__migrate_task",
      "external": false,
      "loc": "kernel/sched/core.c:1022",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:migration_cpu_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579558816,
      "name": "__migrate_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
struct rq * __migrate_task(struct rq * rq, struct task_struct * p, int dest_cpu)
```

```json
{
  "name": "__migrate_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579583744,
      "name": "__migrate_task",
      "external": false,
      "loc": "kernel/sched/core.c:1029",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:migration_cpu_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579583744,
      "name": "__migrate_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct rq * __migrate_task(struct rq * rq, struct rq_flags * rf, struct task_struct * p, int dest_cpu)
```

```json
{
  "name": "__migrate_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579567360,
      "name": "__migrate_task",
      "external": false,
      "loc": "kernel/sched/core.c:951",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:migration_cpu_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579567360,
      "name": "__migrate_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct rq * __migrate_task(struct rq * rq, struct rq_flags * rf, struct task_struct * p, int dest_cpu)
```

```json
{
  "name": "__migrate_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579597104,
      "name": "__migrate_task",
      "external": false,
      "loc": "kernel/sched/core.c:961",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:migration_cpu_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579597104,
      "name": "__migrate_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct rq * __migrate_task(struct rq * rq, struct rq_flags * rf, struct task_struct * p, int dest_cpu)
```

```json
{
  "name": "__migrate_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579628704,
      "name": "__migrate_task",
      "external": false,
      "loc": "kernel/sched/core.c:966",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:migration_cpu_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579628704,
      "name": "__migrate_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct rq * __migrate_task(struct rq * rq, struct rq_flags * rf, struct task_struct * p, int dest_cpu)
```

```json
{
  "name": "__migrate_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579666336,
      "name": "__migrate_task",
      "external": false,
      "loc": "kernel/sched/core.c:961",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:migration_cpu_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579666336,
      "name": "__migrate_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__migrate_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579711607,
      "name": "__migrate_task",
      "external": false,
      "loc": "kernel/sched/core.c:1404",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop"
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
  "name": "__migrate_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579754085,
      "name": "__migrate_task",
      "external": false,
      "loc": "kernel/sched/core.c:1524",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop"
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
  "name": "__migrate_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579775177,
      "name": "__migrate_task",
      "external": false,
      "loc": "kernel/sched/core.c:1589",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:migrate_tasks",
        "kernel/sched/core.c:migrate_tasks",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop"
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
  "name": "__migrate_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579765012,
      "name": "__migrate_task",
      "external": false,
      "loc": "kernel/sched/core.c:1886",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop"
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
  "name": "__migrate_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579772724,
      "name": "__migrate_task",
      "external": false,
      "loc": "kernel/sched/core.c:1894",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop"
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
  "name": "__migrate_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579864389,
      "name": "__migrate_task",
      "external": false,
      "loc": "kernel/sched/core.c:2272",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop"
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
  "name": "__migrate_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579980080,
      "name": "__migrate_task",
      "external": false,
      "loc": "kernel/sched/core.c:2371",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop"
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
  "name": "__migrate_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580140752,
      "name": "__migrate_task",
      "external": false,
      "loc": "kernel/sched/core.c:2367",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop"
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
  "name": "__migrate_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580221738,
      "name": "__migrate_task",
      "external": false,
      "loc": "kernel/sched/core.c:2542",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop"
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
  "name": "__migrate_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580270586,
      "name": "__migrate_task",
      "external": false,
      "loc": "kernel/sched/core.c:2568",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop"
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
  "name": "__migrate_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490932184,
      "name": "__migrate_task",
      "external": false,
      "loc": "kernel/sched/core.c:1524",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop"
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
  "name": "__migrate_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224950796,
      "name": "__migrate_task",
      "external": false,
      "loc": "kernel/sched/core.c:1524",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop"
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
  "name": "__migrate_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283787452,
      "name": "__migrate_task",
      "external": false,
      "loc": "kernel/sched/core.c:1524",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop"
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
  "name": "__migrate_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271557674,
      "name": "__migrate_task",
      "external": false,
      "loc": "kernel/sched/core.c:1524",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:migration_cpu_stop"
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
  "name": "__migrate_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579730005,
      "name": "__migrate_task",
      "external": false,
      "loc": "kernel/sched/core.c:1524",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop"
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
  "name": "__migrate_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579658788,
      "name": "__migrate_task",
      "external": false,
      "loc": "kernel/sched/core.c:1524",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop"
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
  "name": "__migrate_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579715653,
      "name": "__migrate_task",
      "external": false,
      "loc": "kernel/sched/core.c:1524",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop"
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
  "name": "__migrate_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579761741,
      "name": "__migrate_task",
      "external": false,
      "loc": "kernel/sched/core.c:1524",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop"
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
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct rq_flags * rf</code>
</li>
<li>
<b>Param reordered. </b>
<code>rq, p, dest_cpu</code> ➡️ <code>rq, rf, p, dest_cpu</code>
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
struct rq * __migrate_task(struct rq * rq, struct rq_flags * rf, struct task_struct * p, int dest_cpu)
```
</details>
</li>
</ul>
