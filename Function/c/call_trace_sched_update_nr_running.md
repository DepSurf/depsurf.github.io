# Function: <code>call_trace_sched_update_nr_running</code>

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
void call_trace_sched_update_nr_running(struct rq * rq, int count)
```

```json
{
  "name": "call_trace_sched_update_nr_running",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579781936,
      "name": "call_trace_sched_update_nr_running",
      "external": true,
      "loc": "kernel/sched/core.c:9177",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/fair.c:throttle_cfs_rq",
        "kernel/sched/rt.c:enqueue_top_rt_rq",
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:__enqueue_dl_entity",
        "kernel/sched/stop_task.c:dequeue_task_stop",
        "kernel/sched/stop_task.c:enqueue_task_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579781936,
      "name": "call_trace_sched_update_nr_running",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void call_trace_sched_update_nr_running(struct rq * rq, int count)
```

```json
{
  "name": "call_trace_sched_update_nr_running",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579790064,
      "name": "call_trace_sched_update_nr_running",
      "external": true,
      "loc": "kernel/sched/core.c:9553",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/fair.c:throttle_cfs_rq",
        "kernel/sched/rt.c:enqueue_top_rt_rq",
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:__enqueue_dl_entity",
        "kernel/sched/stop_task.c:dequeue_task_stop",
        "kernel/sched/stop_task.c:enqueue_task_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579790064,
      "name": "call_trace_sched_update_nr_running",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void call_trace_sched_update_nr_running(struct rq * rq, int count)
```

```json
{
  "name": "call_trace_sched_update_nr_running",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579885728,
      "name": "call_trace_sched_update_nr_running",
      "external": true,
      "loc": "kernel/sched/core.c:10872",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/fair.c:throttle_cfs_rq",
        "kernel/sched/rt.c:enqueue_top_rt_rq",
        "kernel/sched/rt.c:dequeue_top_rt_rq",
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:__enqueue_dl_entity",
        "kernel/sched/stop_task.c:dequeue_task_stop",
        "kernel/sched/stop_task.c:enqueue_task_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579885728,
      "name": "call_trace_sched_update_nr_running",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void call_trace_sched_update_nr_running(struct rq * rq, int count)
```

```json
{
  "name": "call_trace_sched_update_nr_running",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580003120,
      "name": "call_trace_sched_update_nr_running",
      "external": true,
      "loc": "kernel/sched/core.c:11205",
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
        "kernel/sched/build_policy.c:enqueue_top_rt_rq",
        "kernel/sched/build_policy.c:dequeue_top_rt_rq",
        "kernel/sched/build_utility.c:dequeue_task_stop",
        "kernel/sched/build_utility.c:enqueue_task_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580003120,
      "name": "call_trace_sched_update_nr_running",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void call_trace_sched_update_nr_running(struct rq * rq, int count)
```

```json
{
  "name": "call_trace_sched_update_nr_running",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580165504,
      "name": "call_trace_sched_update_nr_running",
      "external": true,
      "loc": "kernel/sched/core.c:11365",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/fair.c:throttle_cfs_rq",
        "kernel/sched/build_policy.c:__dequeue_task_dl",
        "kernel/sched/build_policy.c:enqueue_dl_entity",
        "kernel/sched/build_policy.c:enqueue_top_rt_rq",
        "kernel/sched/build_policy.c:dequeue_top_rt_rq",
        "kernel/sched/build_utility.c:dequeue_task_stop",
        "kernel/sched/build_utility.c:enqueue_task_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580165504,
      "name": "call_trace_sched_update_nr_running",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void call_trace_sched_update_nr_running(struct rq * rq, int count)
```

```json
{
  "name": "call_trace_sched_update_nr_running",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580213904,
      "name": "call_trace_sched_update_nr_running",
      "external": true,
      "loc": "kernel/sched/core.c:11525",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/fair.c:throttle_cfs_rq",
        "kernel/sched/build_policy.c:__dequeue_task_dl",
        "kernel/sched/build_policy.c:enqueue_dl_entity",
        "kernel/sched/build_policy.c:enqueue_top_rt_rq",
        "kernel/sched/build_policy.c:dequeue_top_rt_rq",
        "kernel/sched/build_utility.c:dequeue_task_stop",
        "kernel/sched/build_utility.c:enqueue_task_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580213904,
      "name": "call_trace_sched_update_nr_running",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void call_trace_sched_update_nr_running(struct rq * rq, int count)
```

```json
{
  "name": "call_trace_sched_update_nr_running",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580262608,
      "name": "call_trace_sched_update_nr_running",
      "external": true,
      "loc": "kernel/sched/core.c:11527",
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
      "addr": 18446744071580262608,
      "name": "call_trace_sched_update_nr_running",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void call_trace_sched_update_nr_running(struct rq * rq, int count)
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
