# Function: <code>cpu_load_update</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void cpu_load_update(struct rq * this_rq, long unsigned int this_load, long unsigned int pending_updates)
```

```json
{
  "name": "cpu_load_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579593920,
      "name": "cpu_load_update",
      "external": false,
      "loc": "kernel/sched/fair.c:4711",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:run_rebalance_domains",
        "kernel/sched/fair.c:cpu_load_update_active",
        "kernel/sched/fair.c:cpu_load_update_active",
        "kernel/sched/fair.c:cpu_load_update_nohz_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579593920,
      "name": "cpu_load_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
void cpu_load_update(struct rq * this_rq, long unsigned int this_load, long unsigned int pending_updates)
```

```json
{
  "name": "cpu_load_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579616656,
      "name": "cpu_load_update",
      "external": false,
      "loc": "kernel/sched/fair.c:4941",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:run_rebalance_domains",
        "kernel/sched/fair.c:cpu_load_update_active",
        "kernel/sched/fair.c:cpu_load_update_active",
        "kernel/sched/fair.c:cpu_load_update_nohz_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579616656,
      "name": "cpu_load_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void cpu_load_update(struct rq * this_rq, long unsigned int this_load, long unsigned int pending_updates)
```

```json
{
  "name": "cpu_load_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579595232,
      "name": "cpu_load_update",
      "external": false,
      "loc": "kernel/sched/fair.c:5084",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:run_rebalance_domains",
        "kernel/sched/fair.c:cpu_load_update_active",
        "kernel/sched/fair.c:cpu_load_update_active",
        "kernel/sched/fair.c:cpu_load_update_nohz_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579595232,
      "name": "cpu_load_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void cpu_load_update(struct rq * this_rq, long unsigned int this_load, long unsigned int pending_updates)
```

```json
{
  "name": "cpu_load_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579624240,
      "name": "cpu_load_update",
      "external": false,
      "loc": "kernel/sched/fair.c:5423",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:run_rebalance_domains",
        "kernel/sched/fair.c:cpu_load_update_active",
        "kernel/sched/fair.c:cpu_load_update_active",
        "kernel/sched/fair.c:cpu_load_update_nohz_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579624240,
      "name": "cpu_load_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
void cpu_load_update(struct rq * this_rq, long unsigned int this_load, long unsigned int pending_updates)
```

```json
{
  "name": "cpu_load_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579653136,
      "name": "cpu_load_update",
      "external": false,
      "loc": "kernel/sched/fair.c:5619",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:cpu_load_update_active",
        "kernel/sched/fair.c:cpu_load_update_active",
        "kernel/sched/fair.c:cpu_load_update_nohz_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579653136,
      "name": "cpu_load_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
void cpu_load_update(struct rq * this_rq, long unsigned int this_load, long unsigned int pending_updates)
```

```json
{
  "name": "cpu_load_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579691424,
      "name": "cpu_load_update",
      "external": false,
      "loc": "kernel/sched/fair.c:5361",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:cpu_load_update_active",
        "kernel/sched/fair.c:cpu_load_update_active",
        "kernel/sched/fair.c:cpu_load_update_nohz_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579691424,
      "name": "cpu_load_update",
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void cpu_load_update(struct rq * this_rq, long unsigned int this_load, long unsigned int pending_updates)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
void cpu_load_update(struct rq * this_rq, long unsigned int this_load, long unsigned int pending_updates)
```
</details>
</li>
</ul>
