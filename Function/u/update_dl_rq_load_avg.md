# Function: <code>update_dl_rq_load_avg</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int update_dl_rq_load_avg(u64 now, struct rq * rq, int running)
```

```json
{
  "name": "update_dl_rq_load_avg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579793344,
      "name": "update_dl_rq_load_avg",
      "external": true,
      "loc": "kernel/sched/pelt.c:341",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/deadline.c:pick_next_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579793344,
      "name": "update_dl_rq_load_avg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 535
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
int update_dl_rq_load_avg(u64 now, struct rq * rq, int running)
```

```json
{
  "name": "update_dl_rq_load_avg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579821728,
      "name": "update_dl_rq_load_avg",
      "external": true,
      "loc": "kernel/sched/pelt.c:341",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/deadline.c:pick_next_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579821728,
      "name": "update_dl_rq_load_avg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 693
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
int update_dl_rq_load_avg(u64 now, struct rq * rq, int running)
```

```json
{
  "name": "update_dl_rq_load_avg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579869824,
      "name": "update_dl_rq_load_avg",
      "external": true,
      "loc": "kernel/sched/pelt.c:341",
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
      "addr": 18446744071579869824,
      "name": "update_dl_rq_load_avg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 693
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
int update_dl_rq_load_avg(u64 now, struct rq * rq, int running)
```

```json
{
  "name": "update_dl_rq_load_avg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579911520,
      "name": "update_dl_rq_load_avg",
      "external": true,
      "loc": "kernel/sched/pelt.c:380",
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
      "addr": 18446744071579911520,
      "name": "update_dl_rq_load_avg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 876
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
int update_dl_rq_load_avg(u64 now, struct rq * rq, int running)
```

```json
{
  "name": "update_dl_rq_load_avg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579905008,
      "name": "update_dl_rq_load_avg",
      "external": true,
      "loc": "kernel/sched/pelt.c:376",
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
      "addr": 18446744071579905008,
      "name": "update_dl_rq_load_avg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 852
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
int update_dl_rq_load_avg(u64 now, struct rq * rq, int running)
```

```json
{
  "name": "update_dl_rq_load_avg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579914048,
      "name": "update_dl_rq_load_avg",
      "external": true,
      "loc": "kernel/sched/pelt.c:376",
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
      "addr": 18446744071579914048,
      "name": "update_dl_rq_load_avg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 833
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
int update_dl_rq_load_avg(u64 now, struct rq * rq, int running)
```

```json
{
  "name": "update_dl_rq_load_avg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580035376,
      "name": "update_dl_rq_load_avg",
      "external": true,
      "loc": "kernel/sched/pelt.c:376",
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
      "addr": 18446744071580035376,
      "name": "update_dl_rq_load_avg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1478
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
int update_dl_rq_load_avg(u64 now, struct rq * rq, int running)
```

```json
{
  "name": "update_dl_rq_load_avg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580124736,
      "name": "update_dl_rq_load_avg",
      "external": true,
      "loc": "kernel/sched/pelt.c:372",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_blocked_averages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580124736,
      "name": "update_dl_rq_load_avg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1494
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
int update_dl_rq_load_avg(u64 now, struct rq * rq, int running)
```

```json
{
  "name": "update_dl_rq_load_avg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580298448,
      "name": "update_dl_rq_load_avg",
      "external": true,
      "loc": "kernel/sched/pelt.c:372",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_blocked_averages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580298448,
      "name": "update_dl_rq_load_avg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1494
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
int update_dl_rq_load_avg(u64 now, struct rq * rq, int running)
```

```json
{
  "name": "update_dl_rq_load_avg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580365904,
      "name": "update_dl_rq_load_avg",
      "external": true,
      "loc": "kernel/sched/pelt.c:372",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_blocked_averages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580365904,
      "name": "update_dl_rq_load_avg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1573
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
int update_dl_rq_load_avg(u64 now, struct rq * rq, int running)
```

```json
{
  "name": "update_dl_rq_load_avg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580421504,
      "name": "update_dl_rq_load_avg",
      "external": true,
      "loc": "kernel/sched/pelt.c:372",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_blocked_averages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580421504,
      "name": "update_dl_rq_load_avg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1573
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
int update_dl_rq_load_avg(u64 now, struct rq * rq, int running)
```

```json
{
  "name": "update_dl_rq_load_avg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491068512,
      "name": "update_dl_rq_load_avg",
      "external": true,
      "loc": "kernel/sched/pelt.c:341",
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
      "addr": 18446603336491068512,
      "name": "update_dl_rq_load_avg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 696
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
int update_dl_rq_load_avg(u64 now, struct rq * rq, int running)
```

```json
{
  "name": "update_dl_rq_load_avg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225072428,
      "name": "update_dl_rq_load_avg",
      "external": true,
      "loc": "kernel/sched/pelt.c:341",
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
      "addr": 3225072428,
      "name": "update_dl_rq_load_avg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1220
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
int update_dl_rq_load_avg(u64 now, struct rq * rq, int running)
```

```json
{
  "name": "update_dl_rq_load_avg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283949184,
      "name": "update_dl_rq_load_avg",
      "external": true,
      "loc": "kernel/sched/pelt.c:341",
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
      "addr": 13835058055283949184,
      "name": "update_dl_rq_load_avg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1044
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
int update_dl_rq_load_avg(u64 now, struct rq * rq, int running)
```

```json
{
  "name": "update_dl_rq_load_avg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271659034,
      "name": "update_dl_rq_load_avg",
      "external": true,
      "loc": "kernel/sched/pelt.c:341",
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
      "addr": 18446743936271659034,
      "name": "update_dl_rq_load_avg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 646
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
int update_dl_rq_load_avg(u64 now, struct rq * rq, int running)
```

```json
{
  "name": "update_dl_rq_load_avg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579842176,
      "name": "update_dl_rq_load_avg",
      "external": true,
      "loc": "kernel/sched/pelt.c:341",
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
      "addr": 18446744071579842176,
      "name": "update_dl_rq_load_avg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 693
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
int update_dl_rq_load_avg(u64 now, struct rq * rq, int running)
```

```json
{
  "name": "update_dl_rq_load_avg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579776912,
      "name": "update_dl_rq_load_avg",
      "external": true,
      "loc": "kernel/sched/pelt.c:341",
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
      "addr": 18446744071579776912,
      "name": "update_dl_rq_load_avg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 693
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
int update_dl_rq_load_avg(u64 now, struct rq * rq, int running)
```

```json
{
  "name": "update_dl_rq_load_avg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579830192,
      "name": "update_dl_rq_load_avg",
      "external": true,
      "loc": "kernel/sched/pelt.c:341",
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
      "addr": 18446744071579830192,
      "name": "update_dl_rq_load_avg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 693
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
int update_dl_rq_load_avg(u64 now, struct rq * rq, int running)
```

```json
{
  "name": "update_dl_rq_load_avg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579875408,
      "name": "update_dl_rq_load_avg",
      "external": true,
      "loc": "kernel/sched/pelt.c:341",
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
      "addr": 18446744071579875408,
      "name": "update_dl_rq_load_avg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 708
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
int update_dl_rq_load_avg(u64 now, struct rq * rq, int running)
```
</details>
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
