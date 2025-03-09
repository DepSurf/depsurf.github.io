# Function: <code>rcu_tasks_invoke_cbs</code>

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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void rcu_tasks_invoke_cbs(struct rcu_tasks * rtp, struct rcu_tasks_percpu * rtpcp)
```

```json
{
  "name": "rcu_tasks_invoke_cbs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580364496,
      "name": "rcu_tasks_invoke_cbs",
      "external": false,
      "loc": "kernel/rcu/tasks.h:449",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/update.c:rcu_tasks_invoke_cbs_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580364496,
      "name": "rcu_tasks_invoke_cbs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 547
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
void rcu_tasks_invoke_cbs(struct rcu_tasks * rtp, struct rcu_tasks_percpu * rtpcp)
```

```json
{
  "name": "rcu_tasks_invoke_cbs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580587264,
      "name": "rcu_tasks_invoke_cbs",
      "external": false,
      "loc": "kernel/rcu/tasks.h:454",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_one_gp",
        "kernel/rcu/update.c:rcu_tasks_invoke_cbs_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580587264,
      "name": "rcu_tasks_invoke_cbs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 547
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
void rcu_tasks_invoke_cbs(struct rcu_tasks * rtp, struct rcu_tasks_percpu * rtpcp)
```

```json
{
  "name": "rcu_tasks_invoke_cbs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580660352,
      "name": "rcu_tasks_invoke_cbs",
      "external": false,
      "loc": "kernel/rcu/tasks.h:463",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_one_gp",
        "kernel/rcu/update.c:rcu_tasks_invoke_cbs_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580660352,
      "name": "rcu_tasks_invoke_cbs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 614
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
void rcu_tasks_invoke_cbs(struct rcu_tasks * rtp, struct rcu_tasks_percpu * rtpcp)
```

```json
{
  "name": "rcu_tasks_invoke_cbs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580726016,
      "name": "rcu_tasks_invoke_cbs",
      "external": false,
      "loc": "kernel/rcu/tasks.h:510",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_one_gp",
        "kernel/rcu/update.c:rcu_tasks_invoke_cbs_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580726016,
      "name": "rcu_tasks_invoke_cbs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 666
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void rcu_tasks_invoke_cbs(struct rcu_tasks * rtp, struct rcu_tasks_percpu * rtpcp)
```
</details>
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
