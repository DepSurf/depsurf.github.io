# Function: <code>pick_task_rt</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * pick_task_rt(struct rq * rq)
```

```json
{
  "name": "pick_task_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579973285,
      "name": "pick_task_rt",
      "external": false,
      "loc": "kernel/sched/rt.c:1644",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:pick_next_task_rt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579967760,
      "name": "pick_task_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * pick_task_rt(struct rq * rq)
```

```json
{
  "name": "pick_task_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580124133,
      "name": "pick_task_rt",
      "external": false,
      "loc": "kernel/sched/rt.c:1803",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:pick_next_task_rt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580085760,
      "name": "pick_task_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
struct task_struct * pick_task_rt(struct rq * rq)
```

```json
{
  "name": "pick_task_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pick_task_rt",
      "external": false,
      "loc": "kernel/sched/rt.c:1802",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:pick_next_task_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580257136,
      "name": "pick_task_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446744071595979434,
      "name": "pick_task_rt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
struct task_struct * pick_task_rt(struct rq * rq)
```

```json
{
  "name": "pick_task_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pick_task_rt",
      "external": false,
      "loc": "kernel/sched/rt.c:1802",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:pick_next_task_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580323408,
      "name": "pick_task_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    },
    {
      "addr": 18446744071596497618,
      "name": "pick_task_rt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
struct task_struct * pick_task_rt(struct rq * rq)
```

```json
{
  "name": "pick_task_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pick_task_rt",
      "external": false,
      "loc": "kernel/sched/rt.c:1747",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:pick_next_task_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580377504,
      "name": "pick_task_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    },
    {
      "addr": 18446744071597394763,
      "name": "pick_task_rt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
struct task_struct * pick_task_rt(struct rq * rq)
```
</details>
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
