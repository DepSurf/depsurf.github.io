# Function: <code>tg_set_rt_bandwidth</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int tg_set_rt_bandwidth(struct task_group * tg, u64 rt_period, u64 rt_runtime)
```

```json
{
  "name": "tg_set_rt_bandwidth",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579819936,
      "name": "tg_set_rt_bandwidth",
      "external": false,
      "loc": "kernel/sched/rt.c:2500",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:sched_group_set_rt_period",
        "kernel/sched/rt.c:sched_group_set_rt_runtime",
        "kernel/sched/rt.c:sched_group_set_rt_runtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579819936,
      "name": "tg_set_rt_bandwidth",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int tg_set_rt_bandwidth(struct task_group * tg, u64 rt_period, u64 rt_runtime)
```

```json
{
  "name": "tg_set_rt_bandwidth",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491003824,
      "name": "tg_set_rt_bandwidth",
      "external": false,
      "loc": "kernel/sched/rt.c:2500",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:sched_group_set_rt_period",
        "kernel/sched/rt.c:sched_group_set_rt_runtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491003824,
      "name": "tg_set_rt_bandwidth",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
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
int tg_set_rt_bandwidth(struct task_group * tg, u64 rt_period, u64 rt_runtime)
```

```json
{
  "name": "tg_set_rt_bandwidth",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225012136,
      "name": "tg_set_rt_bandwidth",
      "external": false,
      "loc": "kernel/sched/rt.c:2500",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:sched_group_set_rt_period",
        "kernel/sched/rt.c:sched_group_set_rt_runtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225012136,
      "name": "tg_set_rt_bandwidth",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
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
int tg_set_rt_bandwidth(struct task_group * tg, u64 rt_period, u64 rt_runtime)
```

```json
{
  "name": "tg_set_rt_bandwidth",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283872400,
      "name": "tg_set_rt_bandwidth",
      "external": false,
      "loc": "kernel/sched/rt.c:2500",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:sched_group_set_rt_period",
        "kernel/sched/rt.c:sched_group_set_rt_runtime",
        "kernel/sched/rt.c:sched_group_set_rt_runtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283872400,
      "name": "tg_set_rt_bandwidth",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 648
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
int tg_set_rt_bandwidth(struct task_group * tg, u64 rt_period, u64 rt_runtime)
```

```json
{
  "name": "tg_set_rt_bandwidth",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271612184,
      "name": "tg_set_rt_bandwidth",
      "external": false,
      "loc": "kernel/sched/rt.c:2500",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:sched_group_set_rt_period",
        "kernel/sched/rt.c:sched_group_set_rt_runtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271612184,
      "name": "tg_set_rt_bandwidth",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int tg_set_rt_bandwidth(struct task_group * tg, u64 rt_period, u64 rt_runtime)
```

```json
{
  "name": "tg_set_rt_bandwidth",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579726576,
      "name": "tg_set_rt_bandwidth",
      "external": false,
      "loc": "kernel/sched/rt.c:2500",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:sched_group_set_rt_period",
        "kernel/sched/rt.c:sched_group_set_rt_runtime",
        "kernel/sched/rt.c:sched_group_set_rt_runtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579726576,
      "name": "tg_set_rt_bandwidth",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
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
int tg_set_rt_bandwidth(struct task_group * tg, u64 rt_period, u64 rt_runtime)
```

```json
{
  "name": "tg_set_rt_bandwidth",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579780304,
      "name": "tg_set_rt_bandwidth",
      "external": false,
      "loc": "kernel/sched/rt.c:2500",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:sched_group_set_rt_period",
        "kernel/sched/rt.c:sched_group_set_rt_runtime",
        "kernel/sched/rt.c:sched_group_set_rt_runtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579780304,
      "name": "tg_set_rt_bandwidth",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int tg_set_rt_bandwidth(struct task_group * tg, u64 rt_period, u64 rt_runtime)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int tg_set_rt_bandwidth(struct task_group * tg, u64 rt_period, u64 rt_runtime)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
int tg_set_rt_bandwidth(struct task_group * tg, u64 rt_period, u64 rt_runtime)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ➖</summary>

```c
int tg_set_rt_bandwidth(struct task_group * tg, u64 rt_period, u64 rt_runtime)
```
</details>
</li>
</ul>
