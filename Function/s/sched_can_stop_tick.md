# Function: <code>sched_can_stop_tick</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
bool sched_can_stop_tick(struct rq * rq)
```

```json
{
  "name": "sched_can_stop_tick",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580243184,
      "name": "sched_can_stop_tick",
      "external": true,
      "loc": "kernel/sched/core.c:1230",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/fair.c:throttle_cfs_rq",
        "kernel/sched/build_policy.c:enqueue_dl_entity",
        "kernel/sched/build_policy.c:__dequeue_dl_entity",
        "kernel/sched/build_policy.c:dequeue_rt_stack",
        "kernel/sched/build_policy.c:enqueue_top_rt_rq",
        "kernel/sched/build_policy.c:update_curr_rt",
        "kernel/sched/build_utility.c:dequeue_task_stop",
        "kernel/sched/build_utility.c:enqueue_task_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580243184,
      "name": "sched_can_stop_tick",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
bool sched_can_stop_tick(struct rq * rq)
```

```json
{
  "name": "sched_can_stop_tick",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579633952,
      "name": "sched_can_stop_tick",
      "external": true,
      "loc": "kernel/sched/core.c:662",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/fair.c:throttle_cfs_rq",
        "kernel/sched/deadline.c:enqueue_dl_entity",
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/stop_task.c:dequeue_task_stop",
        "kernel/sched/stop_task.c:enqueue_task_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579633952,
      "name": "sched_can_stop_tick",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
bool sched_can_stop_tick(struct rq * rq)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➕</summary>

```c
bool sched_can_stop_tick(struct rq * rq)
```
</details>
</li>
</ul>
