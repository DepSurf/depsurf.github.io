# Function: <code>decay_load</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "decay_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579577298,
      "name": "decay_load",
      "external": false,
      "loc": "kernel/sched/fair.c:2485",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:attach_entity_load_avg",
        "kernel/sched/fair.c:attach_entity_load_avg",
        "kernel/sched/fair.c:detach_task_cfs_rq",
        "kernel/sched/fair.c:detach_task_cfs_rq",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:remove_entity_load_avg",
        "kernel/sched/fair.c:remove_entity_load_avg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "decay_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579606431,
      "name": "decay_load",
      "external": false,
      "loc": "kernel/sched/fair.c:2619",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:attach_task_cfs_rq",
        "kernel/sched/fair.c:attach_task_cfs_rq",
        "kernel/sched/fair.c:attach_task_cfs_rq",
        "kernel/sched/fair.c:detach_task_cfs_rq",
        "kernel/sched/fair.c:detach_task_cfs_rq",
        "kernel/sched/fair.c:detach_task_cfs_rq",
        "kernel/sched/fair.c:detach_task_cfs_rq",
        "kernel/sched/fair.c:detach_task_cfs_rq",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:remove_entity_load_avg",
        "kernel/sched/fair.c:remove_entity_load_avg",
        "kernel/sched/fair.c:attach_entity_load_avg",
        "kernel/sched/fair.c:attach_entity_load_avg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "decay_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579646960,
      "name": "decay_load",
      "external": false,
      "loc": "kernel/sched/fair.c:2751",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:sync_entity_load_avg",
        "kernel/sched/fair.c:sync_entity_load_avg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 decay_load(u64 val, u64 n)
```

```json
{
  "name": "decay_load",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579589583,
      "name": "decay_load",
      "external": false,
      "loc": "kernel/sched/fair.c:2798",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:__accumulate_pelt_segments",
        "kernel/sched/fair.c:__accumulate_pelt_segments"
      ],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579589440,
      "name": "decay_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 decay_load(u64 val, u64 n)
```

```json
{
  "name": "decay_load",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579618991,
      "name": "decay_load",
      "external": false,
      "loc": "kernel/sched/fair.c:3045",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:__accumulate_pelt_segments",
        "kernel/sched/fair.c:__accumulate_pelt_segments"
      ],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579618848,
      "name": "decay_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 decay_load(u64 val, u64 n)
```

```json
{
  "name": "decay_load",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579650453,
      "name": "decay_load",
      "external": false,
      "loc": "kernel/sched/fair.c:3071",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:__accumulate_pelt_segments",
        "kernel/sched/fair.c:__accumulate_pelt_segments"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579650368,
      "name": "decay_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "decay_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579793652,
      "name": "decay_load",
      "external": false,
      "loc": "kernel/sched/pelt.c:36",
      "file": "kernel/sched/pelt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__accumulate_pelt_segments",
        "kernel/sched/pelt.c:__accumulate_pelt_segments"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "decay_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579822066,
      "name": "decay_load",
      "external": false,
      "loc": "kernel/sched/pelt.c:37",
      "file": "kernel/sched/pelt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__accumulate_pelt_segments",
        "kernel/sched/pelt.c:__accumulate_pelt_segments"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "decay_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579870162,
      "name": "decay_load",
      "external": false,
      "loc": "kernel/sched/pelt.c:37",
      "file": "kernel/sched/pelt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__accumulate_pelt_segments",
        "kernel/sched/pelt.c:__accumulate_pelt_segments"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "decay_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579911864,
      "name": "decay_load",
      "external": false,
      "loc": "kernel/sched/pelt.c:37",
      "file": "kernel/sched/pelt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "decay_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579905345,
      "name": "decay_load",
      "external": false,
      "loc": "kernel/sched/pelt.c:35",
      "file": "kernel/sched/pelt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "decay_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579914374,
      "name": "decay_load",
      "external": false,
      "loc": "kernel/sched/pelt.c:35",
      "file": "kernel/sched/pelt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "decay_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580035757,
      "name": "decay_load",
      "external": false,
      "loc": "kernel/sched/pelt.c:35",
      "file": "kernel/sched/pelt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "decay_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580124876,
      "name": "decay_load",
      "external": false,
      "loc": "kernel/sched/pelt.c:31",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:update_dl_rq_load_avg",
        "kernel/sched/build_policy.c:update_dl_rq_load_avg",
        "kernel/sched/build_policy.c:update_dl_rq_load_avg",
        "kernel/sched/build_policy.c:update_dl_rq_load_avg",
        "kernel/sched/build_policy.c:update_dl_rq_load_avg",
        "kernel/sched/build_policy.c:update_rt_rq_load_avg",
        "kernel/sched/build_policy.c:update_rt_rq_load_avg",
        "kernel/sched/build_policy.c:update_rt_rq_load_avg",
        "kernel/sched/build_policy.c:update_rt_rq_load_avg",
        "kernel/sched/build_policy.c:update_rt_rq_load_avg",
        "kernel/sched/build_policy.c:__update_load_avg_cfs_rq",
        "kernel/sched/build_policy.c:__update_load_avg_cfs_rq",
        "kernel/sched/build_policy.c:__update_load_avg_cfs_rq",
        "kernel/sched/build_policy.c:__update_load_avg_cfs_rq",
        "kernel/sched/build_policy.c:__update_load_avg_cfs_rq",
        "kernel/sched/build_policy.c:__update_load_avg_se",
        "kernel/sched/build_policy.c:__update_load_avg_se",
        "kernel/sched/build_policy.c:__update_load_avg_se",
        "kernel/sched/build_policy.c:__update_load_avg_se",
        "kernel/sched/build_policy.c:__update_load_avg_se",
        "kernel/sched/build_policy.c:__update_load_avg_blocked_se",
        "kernel/sched/build_policy.c:__update_load_avg_blocked_se",
        "kernel/sched/build_policy.c:__update_load_avg_blocked_se"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "decay_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580298588,
      "name": "decay_load",
      "external": false,
      "loc": "kernel/sched/pelt.c:31",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:update_dl_rq_load_avg",
        "kernel/sched/build_policy.c:update_dl_rq_load_avg",
        "kernel/sched/build_policy.c:update_dl_rq_load_avg",
        "kernel/sched/build_policy.c:update_dl_rq_load_avg",
        "kernel/sched/build_policy.c:update_dl_rq_load_avg",
        "kernel/sched/build_policy.c:update_rt_rq_load_avg",
        "kernel/sched/build_policy.c:update_rt_rq_load_avg",
        "kernel/sched/build_policy.c:update_rt_rq_load_avg",
        "kernel/sched/build_policy.c:update_rt_rq_load_avg",
        "kernel/sched/build_policy.c:update_rt_rq_load_avg",
        "kernel/sched/build_policy.c:__update_load_avg_cfs_rq",
        "kernel/sched/build_policy.c:__update_load_avg_cfs_rq",
        "kernel/sched/build_policy.c:__update_load_avg_cfs_rq",
        "kernel/sched/build_policy.c:__update_load_avg_cfs_rq",
        "kernel/sched/build_policy.c:__update_load_avg_cfs_rq",
        "kernel/sched/build_policy.c:__update_load_avg_se",
        "kernel/sched/build_policy.c:__update_load_avg_se",
        "kernel/sched/build_policy.c:__update_load_avg_se",
        "kernel/sched/build_policy.c:__update_load_avg_se",
        "kernel/sched/build_policy.c:__update_load_avg_se",
        "kernel/sched/build_policy.c:__update_load_avg_blocked_se",
        "kernel/sched/build_policy.c:__update_load_avg_blocked_se",
        "kernel/sched/build_policy.c:__update_load_avg_blocked_se"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "decay_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580366291,
      "name": "decay_load",
      "external": false,
      "loc": "kernel/sched/pelt.c:31",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:update_dl_rq_load_avg",
        "kernel/sched/build_policy.c:update_dl_rq_load_avg",
        "kernel/sched/build_policy.c:update_dl_rq_load_avg",
        "kernel/sched/build_policy.c:update_dl_rq_load_avg",
        "kernel/sched/build_policy.c:update_dl_rq_load_avg",
        "kernel/sched/build_policy.c:update_rt_rq_load_avg",
        "kernel/sched/build_policy.c:update_rt_rq_load_avg",
        "kernel/sched/build_policy.c:update_rt_rq_load_avg",
        "kernel/sched/build_policy.c:update_rt_rq_load_avg",
        "kernel/sched/build_policy.c:update_rt_rq_load_avg",
        "kernel/sched/build_policy.c:__update_load_avg_cfs_rq",
        "kernel/sched/build_policy.c:__update_load_avg_cfs_rq",
        "kernel/sched/build_policy.c:__update_load_avg_cfs_rq",
        "kernel/sched/build_policy.c:__update_load_avg_cfs_rq",
        "kernel/sched/build_policy.c:__update_load_avg_cfs_rq",
        "kernel/sched/build_policy.c:__update_load_avg_se",
        "kernel/sched/build_policy.c:__update_load_avg_se",
        "kernel/sched/build_policy.c:__update_load_avg_se",
        "kernel/sched/build_policy.c:__update_load_avg_se",
        "kernel/sched/build_policy.c:__update_load_avg_se",
        "kernel/sched/build_policy.c:__update_load_avg_blocked_se",
        "kernel/sched/build_policy.c:__update_load_avg_blocked_se",
        "kernel/sched/build_policy.c:__update_load_avg_blocked_se"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "decay_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580421891,
      "name": "decay_load",
      "external": false,
      "loc": "kernel/sched/pelt.c:31",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:update_dl_rq_load_avg",
        "kernel/sched/build_policy.c:update_dl_rq_load_avg",
        "kernel/sched/build_policy.c:update_dl_rq_load_avg",
        "kernel/sched/build_policy.c:update_dl_rq_load_avg",
        "kernel/sched/build_policy.c:update_dl_rq_load_avg",
        "kernel/sched/build_policy.c:update_rt_rq_load_avg",
        "kernel/sched/build_policy.c:update_rt_rq_load_avg",
        "kernel/sched/build_policy.c:update_rt_rq_load_avg",
        "kernel/sched/build_policy.c:update_rt_rq_load_avg",
        "kernel/sched/build_policy.c:update_rt_rq_load_avg",
        "kernel/sched/build_policy.c:__update_load_avg_cfs_rq",
        "kernel/sched/build_policy.c:__update_load_avg_cfs_rq",
        "kernel/sched/build_policy.c:__update_load_avg_cfs_rq",
        "kernel/sched/build_policy.c:__update_load_avg_cfs_rq",
        "kernel/sched/build_policy.c:__update_load_avg_cfs_rq",
        "kernel/sched/build_policy.c:__update_load_avg_se",
        "kernel/sched/build_policy.c:__update_load_avg_se",
        "kernel/sched/build_policy.c:__update_load_avg_se",
        "kernel/sched/build_policy.c:__update_load_avg_se",
        "kernel/sched/build_policy.c:__update_load_avg_se",
        "kernel/sched/build_policy.c:__update_load_avg_blocked_se",
        "kernel/sched/build_policy.c:__update_load_avg_blocked_se",
        "kernel/sched/build_policy.c:__update_load_avg_blocked_se"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "decay_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491068860,
      "name": "decay_load",
      "external": false,
      "loc": "kernel/sched/pelt.c:37",
      "file": "kernel/sched/pelt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__accumulate_pelt_segments",
        "kernel/sched/pelt.c:__accumulate_pelt_segments"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "decay_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225072896,
      "name": "decay_load",
      "external": false,
      "loc": "kernel/sched/pelt.c:37",
      "file": "kernel/sched/pelt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__accumulate_pelt_segments",
        "kernel/sched/pelt.c:__accumulate_pelt_segments"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "decay_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283949636,
      "name": "decay_load",
      "external": false,
      "loc": "kernel/sched/pelt.c:37",
      "file": "kernel/sched/pelt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__accumulate_pelt_segments",
        "kernel/sched/pelt.c:__accumulate_pelt_segments"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "decay_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271659434,
      "name": "decay_load",
      "external": false,
      "loc": "kernel/sched/pelt.c:37",
      "file": "kernel/sched/pelt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__accumulate_pelt_segments",
        "kernel/sched/pelt.c:__accumulate_pelt_segments"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "decay_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579842514,
      "name": "decay_load",
      "external": false,
      "loc": "kernel/sched/pelt.c:37",
      "file": "kernel/sched/pelt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__accumulate_pelt_segments",
        "kernel/sched/pelt.c:__accumulate_pelt_segments"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "decay_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579777250,
      "name": "decay_load",
      "external": false,
      "loc": "kernel/sched/pelt.c:37",
      "file": "kernel/sched/pelt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__accumulate_pelt_segments",
        "kernel/sched/pelt.c:__accumulate_pelt_segments"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "decay_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579830530,
      "name": "decay_load",
      "external": false,
      "loc": "kernel/sched/pelt.c:37",
      "file": "kernel/sched/pelt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__accumulate_pelt_segments",
        "kernel/sched/pelt.c:__accumulate_pelt_segments"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "decay_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579875746,
      "name": "decay_load",
      "external": false,
      "loc": "kernel/sched/pelt.c:37",
      "file": "kernel/sched/pelt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__accumulate_pelt_segments",
        "kernel/sched/pelt.c:__accumulate_pelt_segments"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
u64 decay_load(u64 val, u64 n)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
u64 decay_load(u64 val, u64 n)
```
</details>
</li>
</ul>
