# Function: <code>sched_group_set_rt_runtime</code>

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
int sched_group_set_rt_runtime(struct task_group * tg, long int rt_runtime_us)
```

```json
{
  "name": "sched_group_set_rt_runtime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579829152,
      "name": "sched_group_set_rt_runtime",
      "external": true,
      "loc": "kernel/sched/rt.c:2541",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_rt_runtime_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579829152,
      "name": "sched_group_set_rt_runtime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int sched_group_set_rt_runtime(struct task_group * tg, long int rt_runtime_us)
```

```json
{
  "name": "sched_group_set_rt_runtime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491014624,
      "name": "sched_group_set_rt_runtime",
      "external": true,
      "loc": "kernel/sched/rt.c:2541",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_rt_runtime_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491014624,
      "name": "sched_group_set_rt_runtime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int sched_group_set_rt_runtime(struct task_group * tg, long int rt_runtime_us)
```

```json
{
  "name": "sched_group_set_rt_runtime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225021504,
      "name": "sched_group_set_rt_runtime",
      "external": true,
      "loc": "kernel/sched/rt.c:2541",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_rt_runtime_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225021504,
      "name": "sched_group_set_rt_runtime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int sched_group_set_rt_runtime(struct task_group * tg, long int rt_runtime_us)
```

```json
{
  "name": "sched_group_set_rt_runtime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283888992,
      "name": "sched_group_set_rt_runtime",
      "external": true,
      "loc": "kernel/sched/rt.c:2541",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_rt_runtime_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283888992,
      "name": "sched_group_set_rt_runtime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int sched_group_set_rt_runtime(struct task_group * tg, long int rt_runtime_us)
```

```json
{
  "name": "sched_group_set_rt_runtime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271621172,
      "name": "sched_group_set_rt_runtime",
      "external": true,
      "loc": "kernel/sched/rt.c:2541",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_rt_runtime_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271621172,
      "name": "sched_group_set_rt_runtime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int sched_group_set_rt_runtime(struct task_group * tg, long int rt_runtime_us)
```

```json
{
  "name": "sched_group_set_rt_runtime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579735904,
      "name": "sched_group_set_rt_runtime",
      "external": true,
      "loc": "kernel/sched/rt.c:2541",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_rt_runtime_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579735904,
      "name": "sched_group_set_rt_runtime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int sched_group_set_rt_runtime(struct task_group * tg, long int rt_runtime_us)
```

```json
{
  "name": "sched_group_set_rt_runtime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579789520,
      "name": "sched_group_set_rt_runtime",
      "external": true,
      "loc": "kernel/sched/rt.c:2541",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_rt_runtime_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579789520,
      "name": "sched_group_set_rt_runtime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int sched_group_set_rt_runtime(struct task_group * tg, long int rt_runtime_us)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int sched_group_set_rt_runtime(struct task_group * tg, long int rt_runtime_us)
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
int sched_group_set_rt_runtime(struct task_group * tg, long int rt_runtime_us)
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
int sched_group_set_rt_runtime(struct task_group * tg, long int rt_runtime_us)
```
</details>
</li>
</ul>
