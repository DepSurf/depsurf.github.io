# Function: <code>__update_load_avg_cfs_rq</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__update_load_avg_cfs_rq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579641450,
      "name": "__update_load_avg_cfs_rq",
      "external": false,
      "loc": "kernel/sched/fair.c:3008",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__update_load_avg_cfs_rq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579671135,
      "name": "__update_load_avg_cfs_rq",
      "external": false,
      "loc": "kernel/sched/fair.c:3310",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__update_load_avg_cfs_rq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579652368,
      "name": "__update_load_avg_cfs_rq",
      "external": false,
      "loc": "kernel/sched/fair.c:3361",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579652368,
      "name": "__update_load_avg_cfs_rq.isra.46",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int __update_load_avg_cfs_rq(u64 now, int cpu, struct cfs_rq * cfs_rq)
```

```json
{
  "name": "__update_load_avg_cfs_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579792240,
      "name": "__update_load_avg_cfs_rq",
      "external": true,
      "loc": "kernel/sched/pelt.c:293",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:dequeue_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579792240,
      "name": "__update_load_avg_cfs_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 555
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
int __update_load_avg_cfs_rq(u64 now, struct cfs_rq * cfs_rq)
```

```json
{
  "name": "__update_load_avg_cfs_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579820320,
      "name": "__update_load_avg_cfs_rq",
      "external": true,
      "loc": "kernel/sched/pelt.c:291",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_blocked_averages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579820320,
      "name": "__update_load_avg_cfs_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 702
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
int __update_load_avg_cfs_rq(u64 now, struct cfs_rq * cfs_rq)
```

```json
{
  "name": "__update_load_avg_cfs_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579868416,
      "name": "__update_load_avg_cfs_rq",
      "external": true,
      "loc": "kernel/sched/pelt.c:291",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_blocked_averages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579868416,
      "name": "__update_load_avg_cfs_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 702
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
int __update_load_avg_cfs_rq(u64 now, struct cfs_rq * cfs_rq)
```

```json
{
  "name": "__update_load_avg_cfs_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579909712,
      "name": "__update_load_avg_cfs_rq",
      "external": true,
      "loc": "kernel/sched/pelt.c:328",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:__update_blocked_fair",
        "kernel/sched/fair.c:__update_blocked_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579909712,
      "name": "__update_load_avg_cfs_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 918
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
int __update_load_avg_cfs_rq(u64 now, struct cfs_rq * cfs_rq)
```

```json
{
  "name": "__update_load_avg_cfs_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579903248,
      "name": "__update_load_avg_cfs_rq",
      "external": true,
      "loc": "kernel/sched/pelt.c:324",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:__update_blocked_fair",
        "kernel/sched/fair.c:__update_blocked_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579903248,
      "name": "__update_load_avg_cfs_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 885
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
int __update_load_avg_cfs_rq(u64 now, struct cfs_rq * cfs_rq)
```

```json
{
  "name": "__update_load_avg_cfs_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579912336,
      "name": "__update_load_avg_cfs_rq",
      "external": true,
      "loc": "kernel/sched/pelt.c:324",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:__update_blocked_fair",
        "kernel/sched/fair.c:__update_blocked_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579912336,
      "name": "__update_load_avg_cfs_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 857
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
int __update_load_avg_cfs_rq(u64 now, struct cfs_rq * cfs_rq)
```

```json
{
  "name": "__update_load_avg_cfs_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580032368,
      "name": "__update_load_avg_cfs_rq",
      "external": true,
      "loc": "kernel/sched/pelt.c:324",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:__update_blocked_fair",
        "kernel/sched/fair.c:__update_blocked_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580032368,
      "name": "__update_load_avg_cfs_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1518
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
int __update_load_avg_cfs_rq(u64 now, struct cfs_rq * cfs_rq)
```

```json
{
  "name": "__update_load_avg_cfs_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580119536,
      "name": "__update_load_avg_cfs_rq",
      "external": true,
      "loc": "kernel/sched/pelt.c:320",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:__update_blocked_fair",
        "kernel/sched/fair.c:__update_blocked_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580119536,
      "name": "__update_load_avg_cfs_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1502
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
int __update_load_avg_cfs_rq(u64 now, struct cfs_rq * cfs_rq)
```

```json
{
  "name": "__update_load_avg_cfs_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580293248,
      "name": "__update_load_avg_cfs_rq",
      "external": true,
      "loc": "kernel/sched/pelt.c:320",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:__update_blocked_fair",
        "kernel/sched/fair.c:__update_blocked_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580293248,
      "name": "__update_load_avg_cfs_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1504
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
int __update_load_avg_cfs_rq(u64 now, struct cfs_rq * cfs_rq)
```

```json
{
  "name": "__update_load_avg_cfs_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580360592,
      "name": "__update_load_avg_cfs_rq",
      "external": true,
      "loc": "kernel/sched/pelt.c:320",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:__update_blocked_fair",
        "kernel/sched/fair.c:__update_blocked_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580360592,
      "name": "__update_load_avg_cfs_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1530
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
int __update_load_avg_cfs_rq(u64 now, struct cfs_rq * cfs_rq)
```

```json
{
  "name": "__update_load_avg_cfs_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580416160,
      "name": "__update_load_avg_cfs_rq",
      "external": true,
      "loc": "kernel/sched/pelt.c:320",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:__update_blocked_fair",
        "kernel/sched/fair.c:__update_blocked_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580416160,
      "name": "__update_load_avg_cfs_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1530
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
int __update_load_avg_cfs_rq(u64 now, struct cfs_rq * cfs_rq)
```

```json
{
  "name": "__update_load_avg_cfs_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491067104,
      "name": "__update_load_avg_cfs_rq",
      "external": true,
      "loc": "kernel/sched/pelt.c:291",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_blocked_averages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491067104,
      "name": "__update_load_avg_cfs_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 712
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
int __update_load_avg_cfs_rq(u64 now, struct cfs_rq * cfs_rq)
```

```json
{
  "name": "__update_load_avg_cfs_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225069972,
      "name": "__update_load_avg_cfs_rq",
      "external": true,
      "loc": "kernel/sched/pelt.c:291",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_blocked_averages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225069972,
      "name": "__update_load_avg_cfs_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1236
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
int __update_load_avg_cfs_rq(u64 now, struct cfs_rq * cfs_rq)
```

```json
{
  "name": "__update_load_avg_cfs_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283947056,
      "name": "__update_load_avg_cfs_rq",
      "external": true,
      "loc": "kernel/sched/pelt.c:291",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_blocked_averages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283947056,
      "name": "__update_load_avg_cfs_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1060
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
int __update_load_avg_cfs_rq(u64 now, struct cfs_rq * cfs_rq)
```

```json
{
  "name": "__update_load_avg_cfs_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271657782,
      "name": "__update_load_avg_cfs_rq",
      "external": true,
      "loc": "kernel/sched/pelt.c:291",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_blocked_averages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271657782,
      "name": "__update_load_avg_cfs_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 606
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
int __update_load_avg_cfs_rq(u64 now, struct cfs_rq * cfs_rq)
```

```json
{
  "name": "__update_load_avg_cfs_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579840768,
      "name": "__update_load_avg_cfs_rq",
      "external": true,
      "loc": "kernel/sched/pelt.c:291",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_blocked_averages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579840768,
      "name": "__update_load_avg_cfs_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 702
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
int __update_load_avg_cfs_rq(u64 now, struct cfs_rq * cfs_rq)
```

```json
{
  "name": "__update_load_avg_cfs_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579775504,
      "name": "__update_load_avg_cfs_rq",
      "external": true,
      "loc": "kernel/sched/pelt.c:291",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_blocked_averages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579775504,
      "name": "__update_load_avg_cfs_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 702
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
int __update_load_avg_cfs_rq(u64 now, struct cfs_rq * cfs_rq)
```

```json
{
  "name": "__update_load_avg_cfs_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579828784,
      "name": "__update_load_avg_cfs_rq",
      "external": true,
      "loc": "kernel/sched/pelt.c:291",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_blocked_averages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579828784,
      "name": "__update_load_avg_cfs_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 702
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
int __update_load_avg_cfs_rq(u64 now, struct cfs_rq * cfs_rq)
```

```json
{
  "name": "__update_load_avg_cfs_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579873968,
      "name": "__update_load_avg_cfs_rq",
      "external": true,
      "loc": "kernel/sched/pelt.c:291",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_blocked_averages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579873968,
      "name": "__update_load_avg_cfs_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 717
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int __update_load_avg_cfs_rq(u64 now, int cpu, struct cfs_rq * cfs_rq)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int cpu</code>
</li>
<li>
<b>Param reordered. </b>
<code>now, cpu, cfs_rq</code> ➡️ <code>now, cfs_rq</code>
</li>
</ul>
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
