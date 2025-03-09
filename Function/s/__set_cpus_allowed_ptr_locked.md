# Function: <code>__set_cpus_allowed_ptr_locked</code>

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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int __set_cpus_allowed_ptr_locked(struct task_struct * p, const struct cpumask * new_mask, u32 flags, struct rq * rq, struct rq_flags * rf)
```

```json
{
  "name": "__set_cpus_allowed_ptr_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579861904,
      "name": "__set_cpus_allowed_ptr_locked",
      "external": false,
      "loc": "kernel/sched/core.c:2747",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/core.c:migrate_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579861904,
      "name": "__set_cpus_allowed_ptr_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 446
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
int __set_cpus_allowed_ptr_locked(struct task_struct * p, const struct cpumask * new_mask, u32 flags, struct rq * rq, struct rq_flags * rf)
```

```json
{
  "name": "__set_cpus_allowed_ptr_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579977312,
      "name": "__set_cpus_allowed_ptr_locked",
      "external": false,
      "loc": "kernel/sched/core.c:2846",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/core.c:migrate_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579977312,
      "name": "__set_cpus_allowed_ptr_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 443
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
int __set_cpus_allowed_ptr_locked(struct task_struct * p, struct affinity_context * ctx, struct rq * rq, struct rq_flags * rf)
```

```json
{
  "name": "__set_cpus_allowed_ptr_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580137904,
      "name": "__set_cpus_allowed_ptr_locked",
      "external": false,
      "loc": "kernel/sched/core.c:2910",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580137904,
      "name": "__set_cpus_allowed_ptr_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
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
int __set_cpus_allowed_ptr_locked(struct task_struct * p, struct affinity_context * ctx, struct rq * rq, struct rq_flags * rf)
```

```json
{
  "name": "__set_cpus_allowed_ptr_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580217024,
      "name": "__set_cpus_allowed_ptr_locked",
      "external": false,
      "loc": "kernel/sched/core.c:3086",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580217024,
      "name": "__set_cpus_allowed_ptr_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 470
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
int __set_cpus_allowed_ptr_locked(struct task_struct * p, struct affinity_context * ctx, struct rq * rq, struct rq_flags * rf)
```

```json
{
  "name": "__set_cpus_allowed_ptr_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580265824,
      "name": "__set_cpus_allowed_ptr_locked",
      "external": false,
      "loc": "kernel/sched/core.c:3116",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580265824,
      "name": "__set_cpus_allowed_ptr_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 470
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
int __set_cpus_allowed_ptr_locked(struct task_struct * p, const struct cpumask * new_mask, u32 flags, struct rq * rq, struct rq_flags * rf)
```
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct affinity_context * ctx</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct cpumask * new_mask</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>p, new_mask, flags, rq, rf</code> ➡️ <code>p, ctx, rq, rf</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
