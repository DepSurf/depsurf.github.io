# Function: <code>cpumask_any_distribute</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int cpumask_any_distribute(const struct cpumask * srcp)
```

```json
{
  "name": "cpumask_any_distribute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585190464,
      "name": "cpumask_any_distribute",
      "external": true,
      "loc": "lib/cpumask.c:265",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/deadline.c:find_later_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585190464,
      "name": "cpumask_any_distribute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int cpumask_any_distribute(const struct cpumask * srcp)
```

```json
{
  "name": "cpumask_any_distribute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585072864,
      "name": "cpumask_any_distribute",
      "external": true,
      "loc": "lib/cpumask.c:265",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/deadline.c:find_later_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585072864,
      "name": "cpumask_any_distribute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int cpumask_any_distribute(const struct cpumask * srcp)
```

```json
{
  "name": "cpumask_any_distribute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585519552,
      "name": "cpumask_any_distribute",
      "external": true,
      "loc": "lib/cpumask.c:265",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/deadline.c:find_later_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585519552,
      "name": "cpumask_any_distribute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int cpumask_any_distribute(const struct cpumask * srcp)
```

```json
{
  "name": "cpumask_any_distribute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586672064,
      "name": "cpumask_any_distribute",
      "external": true,
      "loc": "lib/cpumask.c:265",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:find_later_rq",
        "kernel/sched/build_policy.c:find_lowest_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586672064,
      "name": "cpumask_any_distribute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
unsigned int cpumask_any_distribute(const struct cpumask * srcp)
```

```json
{
  "name": "cpumask_any_distribute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595751488,
      "name": "cpumask_any_distribute",
      "external": true,
      "loc": "lib/cpumask.c:178",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:find_later_rq",
        "kernel/sched/build_policy.c:find_lowest_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595751488,
      "name": "cpumask_any_distribute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
unsigned int cpumask_any_distribute(const struct cpumask * srcp)
```

```json
{
  "name": "cpumask_any_distribute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596275792,
      "name": "cpumask_any_distribute",
      "external": true,
      "loc": "lib/cpumask.c:187",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:find_later_rq",
        "kernel/sched/build_policy.c:find_lowest_rq",
        "kernel/bpf/cpumask.c:bpf_cpumask_any_distribute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596275792,
      "name": "cpumask_any_distribute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
unsigned int cpumask_any_distribute(const struct cpumask * srcp)
```

```json
{
  "name": "cpumask_any_distribute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597160624,
      "name": "cpumask_any_distribute",
      "external": true,
      "loc": "lib/cpumask.c:192",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:kick_pool",
        "kernel/sched/build_policy.c:find_later_rq",
        "kernel/sched/build_policy.c:find_lowest_rq",
        "kernel/bpf/cpumask.c:bpf_cpumask_any_distribute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597160624,
      "name": "cpumask_any_distribute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int cpumask_any_distribute(const struct cpumask * srcp)
```
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>unsigned int</code>
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
