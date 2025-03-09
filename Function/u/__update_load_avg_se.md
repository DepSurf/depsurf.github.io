# Function: <code>__update_load_avg_se</code>

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
  "name": "__update_load_avg_se",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579590944,
      "name": "__update_load_avg_se",
      "external": false,
      "loc": "kernel/sched/fair.c:3000",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579590944,
      "name": "__update_load_avg_se.isra.37",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__update_load_avg_se",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579620032,
      "name": "__update_load_avg_se",
      "external": false,
      "loc": "kernel/sched/fair.c:3294",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579620032,
      "name": "__update_load_avg_se.isra.38",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 457
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__update_load_avg_se",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579651840,
      "name": "__update_load_avg_se",
      "external": false,
      "loc": "kernel/sched/fair.c:3344",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:enqueue_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579651840,
      "name": "__update_load_avg_se.isra.45",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
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
int __update_load_avg_se(u64 now, int cpu, struct cfs_rq * cfs_rq, struct sched_entity * se)
```

```json
{
  "name": "__update_load_avg_se",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579791616,
      "name": "__update_load_avg_se",
      "external": true,
      "loc": "kernel/sched/pelt.c:280",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:dequeue_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579791616,
      "name": "__update_load_avg_se",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 610
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
int __update_load_avg_se(u64 now, struct cfs_rq * cfs_rq, struct sched_entity * se)
```

```json
{
  "name": "__update_load_avg_se",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579819552,
      "name": "__update_load_avg_se",
      "external": true,
      "loc": "kernel/sched/pelt.c:277",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579819552,
      "name": "__update_load_avg_se",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 757
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
int __update_load_avg_se(u64 now, struct cfs_rq * cfs_rq, struct sched_entity * se)
```

```json
{
  "name": "__update_load_avg_se",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579867648,
      "name": "__update_load_avg_se",
      "external": true,
      "loc": "kernel/sched/pelt.c:277",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579867648,
      "name": "__update_load_avg_se",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 757
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
int __update_load_avg_se(u64 now, struct cfs_rq * cfs_rq, struct sched_entity * se)
```

```json
{
  "name": "__update_load_avg_se",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579908704,
      "name": "__update_load_avg_se",
      "external": true,
      "loc": "kernel/sched/pelt.c:314",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579908704,
      "name": "__update_load_avg_se",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 994
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
int __update_load_avg_se(u64 now, struct cfs_rq * cfs_rq, struct sched_entity * se)
```

```json
{
  "name": "__update_load_avg_se",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579902304,
      "name": "__update_load_avg_se",
      "external": true,
      "loc": "kernel/sched/pelt.c:310",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579902304,
      "name": "__update_load_avg_se",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 933
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
int __update_load_avg_se(u64 now, struct cfs_rq * cfs_rq, struct sched_entity * se)
```

```json
{
  "name": "__update_load_avg_se",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579911376,
      "name": "__update_load_avg_se",
      "external": true,
      "loc": "kernel/sched/pelt.c:310",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579911376,
      "name": "__update_load_avg_se",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 955
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
int __update_load_avg_se(u64 now, struct cfs_rq * cfs_rq, struct sched_entity * se)
```

```json
{
  "name": "__update_load_avg_se",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580030704,
      "name": "__update_load_avg_se",
      "external": true,
      "loc": "kernel/sched/pelt.c:310",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580030704,
      "name": "__update_load_avg_se",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1657
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
int __update_load_avg_se(u64 now, struct cfs_rq * cfs_rq, struct sched_entity * se)
```

```json
{
  "name": "__update_load_avg_se",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580117888,
      "name": "__update_load_avg_se",
      "external": true,
      "loc": "kernel/sched/pelt.c:306",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580117888,
      "name": "__update_load_avg_se",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1633
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
int __update_load_avg_se(u64 now, struct cfs_rq * cfs_rq, struct sched_entity * se)
```

```json
{
  "name": "__update_load_avg_se",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580291584,
      "name": "__update_load_avg_se",
      "external": true,
      "loc": "kernel/sched/pelt.c:306",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580291584,
      "name": "__update_load_avg_se",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1633
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
int __update_load_avg_se(u64 now, struct cfs_rq * cfs_rq, struct sched_entity * se)
```

```json
{
  "name": "__update_load_avg_se",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580358992,
      "name": "__update_load_avg_se",
      "external": true,
      "loc": "kernel/sched/pelt.c:306",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580358992,
      "name": "__update_load_avg_se",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1578
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
int __update_load_avg_se(u64 now, struct cfs_rq * cfs_rq, struct sched_entity * se)
```

```json
{
  "name": "__update_load_avg_se",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580414560,
      "name": "__update_load_avg_se",
      "external": true,
      "loc": "kernel/sched/pelt.c:306",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580414560,
      "name": "__update_load_avg_se",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1578
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
int __update_load_avg_se(u64 now, struct cfs_rq * cfs_rq, struct sched_entity * se)
```

```json
{
  "name": "__update_load_avg_se",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491066360,
      "name": "__update_load_avg_se",
      "external": true,
      "loc": "kernel/sched/pelt.c:277",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491066360,
      "name": "__update_load_avg_se",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 744
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
int __update_load_avg_se(u64 now, struct cfs_rq * cfs_rq, struct sched_entity * se)
```

```json
{
  "name": "__update_load_avg_se",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225068672,
      "name": "__update_load_avg_se",
      "external": true,
      "loc": "kernel/sched/pelt.c:277",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225068672,
      "name": "__update_load_avg_se",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1300
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
int __update_load_avg_se(u64 now, struct cfs_rq * cfs_rq, struct sched_entity * se)
```

```json
{
  "name": "__update_load_avg_se",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283945888,
      "name": "__update_load_avg_se",
      "external": true,
      "loc": "kernel/sched/pelt.c:277",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283945888,
      "name": "__update_load_avg_se",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int __update_load_avg_se(u64 now, struct cfs_rq * cfs_rq, struct sched_entity * se)
```

```json
{
  "name": "__update_load_avg_se",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271657122,
      "name": "__update_load_avg_se",
      "external": true,
      "loc": "kernel/sched/pelt.c:277",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271657122,
      "name": "__update_load_avg_se",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 660
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
int __update_load_avg_se(u64 now, struct cfs_rq * cfs_rq, struct sched_entity * se)
```

```json
{
  "name": "__update_load_avg_se",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579840000,
      "name": "__update_load_avg_se",
      "external": true,
      "loc": "kernel/sched/pelt.c:277",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579840000,
      "name": "__update_load_avg_se",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 757
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
int __update_load_avg_se(u64 now, struct cfs_rq * cfs_rq, struct sched_entity * se)
```

```json
{
  "name": "__update_load_avg_se",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579774736,
      "name": "__update_load_avg_se",
      "external": true,
      "loc": "kernel/sched/pelt.c:277",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579774736,
      "name": "__update_load_avg_se",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 757
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
int __update_load_avg_se(u64 now, struct cfs_rq * cfs_rq, struct sched_entity * se)
```

```json
{
  "name": "__update_load_avg_se",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579828016,
      "name": "__update_load_avg_se",
      "external": true,
      "loc": "kernel/sched/pelt.c:277",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579828016,
      "name": "__update_load_avg_se",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 757
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
int __update_load_avg_se(u64 now, struct cfs_rq * cfs_rq, struct sched_entity * se)
```

```json
{
  "name": "__update_load_avg_se",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579873184,
      "name": "__update_load_avg_se",
      "external": true,
      "loc": "kernel/sched/pelt.c:277",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579873184,
      "name": "__update_load_avg_se",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 772
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
int __update_load_avg_se(u64 now, int cpu, struct cfs_rq * cfs_rq, struct sched_entity * se)
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
<code>now, cpu, cfs_rq, se</code> ➡️ <code>now, cfs_rq, se</code>
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
