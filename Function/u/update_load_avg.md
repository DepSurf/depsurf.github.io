# Function: <code>update_load_avg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void update_load_avg(struct sched_entity * se, int update_tg)
```

```json
{
  "name": "update_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579592575,
      "name": "update_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:2732",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:task_tick_fair"
      ],
      "caller_func": [
        "kernel/sched/fair.c:set_next_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579605344,
      "name": "update_load_avg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1984
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579625529,
      "name": "update_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:2974",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void update_load_avg(struct sched_entity * se, int flags)
```

```json
{
  "name": "update_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579646763,
      "name": "update_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:3270",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair"
      ],
      "caller_func": [
        "kernel/sched/fair.c:detach_task_cfs_rq",
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579618784,
      "name": "update_load_avg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1292
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void update_load_avg(struct sched_entity * se, int flags)
```

```json
{
  "name": "update_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579640752,
      "name": "update_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:3378",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair"
      ],
      "caller_func": [
        "kernel/sched/fair.c:detach_task_cfs_rq",
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579599616,
      "name": "update_load_avg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1413
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
void update_load_avg(struct cfs_rq * cfs_rq, struct sched_entity * se, int flags)
```

```json
{
  "name": "update_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579671135,
      "name": "update_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:3775",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair"
      ],
      "caller_func": [
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579629872,
      "name": "update_load_avg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1748
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
void update_load_avg(struct cfs_rq * cfs_rq, struct sched_entity * se, int flags)
```

```json
{
  "name": "update_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579704323,
      "name": "update_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:3826",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:enqueue_task_fair"
      ],
      "caller_func": [
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579671872,
      "name": "update_load_avg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1374
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void update_load_avg(struct cfs_rq * cfs_rq, struct sched_entity * se, int flags)
```

```json
{
  "name": "update_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579743568,
      "name": "update_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:3500",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:dequeue_task_fair"
      ],
      "caller_func": [
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579699680,
      "name": "update_load_avg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1416
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void update_load_avg(struct cfs_rq * cfs_rq, struct sched_entity * se, int flags)
```

```json
{
  "name": "update_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579743712,
      "name": "update_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:3592",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579743712,
      "name": "update_load_avg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1558
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void update_load_avg(struct cfs_rq * cfs_rq, struct sched_entity * se, int flags)
```

```json
{
  "name": "update_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579786400,
      "name": "update_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:3589",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579786400,
      "name": "update_load_avg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1532
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void update_load_avg(struct cfs_rq * cfs_rq, struct sched_entity * se, int flags)
```

```json
{
  "name": "update_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579815056,
      "name": "update_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:3776",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:__update_blocked_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/fair.c:throttle_cfs_rq",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579815056,
      "name": "update_load_avg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1576
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void update_load_avg(struct cfs_rq * cfs_rq, struct sched_entity * se, int flags)
```

```json
{
  "name": "update_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579806352,
      "name": "update_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:3793",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:__update_blocked_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/fair.c:throttle_cfs_rq",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579806352,
      "name": "update_load_avg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1540
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void update_load_avg(struct cfs_rq * cfs_rq, struct sched_entity * se, int flags)
```

```json
{
  "name": "update_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579814208,
      "name": "update_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:3841",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:propagate_entity_cfs_rq",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:__update_blocked_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/fair.c:throttle_cfs_rq",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579814208,
      "name": "update_load_avg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1463
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void update_load_avg(struct cfs_rq * cfs_rq, struct sched_entity * se, int flags)
```

```json
{
  "name": "update_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579916939,
      "name": "update_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:3853",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:propagate_entity_cfs_rq",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:__update_blocked_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/fair.c:throttle_cfs_rq",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579915664,
      "name": "update_load_avg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1557
    },
    {
      "addr": 18446744071592108827,
      "name": "update_load_avg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void update_load_avg(struct cfs_rq * cfs_rq, struct sched_entity * se, int flags)
```

```json
{
  "name": "update_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580025600,
      "name": "update_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:3902",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:__sched_group_set_shares",
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:propagate_entity_cfs_rq",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:__update_blocked_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/fair.c:throttle_cfs_rq",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580024512,
      "name": "update_load_avg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1956
    },
    {
      "addr": 18446744071593876422,
      "name": "update_load_avg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void update_load_avg(struct cfs_rq * cfs_rq, struct sched_entity * se, int flags)
```

```json
{
  "name": "update_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580193956,
      "name": "update_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:4185",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:__sched_group_set_shares",
        "kernel/sched/fair.c:detach_task_cfs_rq",
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:__update_blocked_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/fair.c:throttle_cfs_rq",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580192336,
      "name": "update_load_avg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2050
    },
    {
      "addr": 18446744071595978326,
      "name": "update_load_avg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void update_load_avg(struct cfs_rq * cfs_rq, struct sched_entity * se, int flags)
```

```json
{
  "name": "update_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580259156,
      "name": "update_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:4242",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:__sched_group_set_shares",
        "kernel/sched/fair.c:detach_task_cfs_rq",
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:__update_blocked_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/fair.c:throttle_cfs_rq",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580257536,
      "name": "update_load_avg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2050
    },
    {
      "addr": 18446744071596496289,
      "name": "update_load_avg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void update_load_avg(struct cfs_rq * cfs_rq, struct sched_entity * se, int flags)
```

```json
{
  "name": "update_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580309795,
      "name": "update_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:4729",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:__sched_group_set_shares",
        "kernel/sched/fair.c:switched_from_fair",
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:__update_blocked_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/fair.c:throttle_cfs_rq",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580308128,
      "name": "update_load_avg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2114
    },
    {
      "addr": 18446744071597393177,
      "name": "update_load_avg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void update_load_avg(struct cfs_rq * cfs_rq, struct sched_entity * se, int flags)
```

```json
{
  "name": "update_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490964064,
      "name": "update_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:3589",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490964064,
      "name": "update_load_avg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1368
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void update_load_avg(struct cfs_rq * cfs_rq, struct sched_entity * se, int flags)
```

```json
{
  "name": "update_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224973048,
      "name": "update_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:3589",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:propagate_entity_cfs_rq",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224973048,
      "name": "update_load_avg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1900
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void update_load_avg(struct cfs_rq * cfs_rq, struct sched_entity * se, int flags)
```

```json
{
  "name": "update_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283828832,
      "name": "update_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:3589",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283828832,
      "name": "update_load_avg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1836
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void update_load_avg(struct cfs_rq * cfs_rq, struct sched_entity * se, int flags)
```

```json
{
  "name": "update_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271581880,
      "name": "update_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:3589",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271581880,
      "name": "update_load_avg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1142
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void update_load_avg(struct cfs_rq * cfs_rq, struct sched_entity * se, int flags)
```

```json
{
  "name": "update_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579762256,
      "name": "update_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:3589",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579762256,
      "name": "update_load_avg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1532
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void update_load_avg(struct cfs_rq * cfs_rq, struct sched_entity * se, int flags)
```

```json
{
  "name": "update_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579692624,
      "name": "update_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:3589",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579692624,
      "name": "update_load_avg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1532
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void update_load_avg(struct cfs_rq * cfs_rq, struct sched_entity * se, int flags)
```

```json
{
  "name": "update_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579746768,
      "name": "update_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:3589",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579746768,
      "name": "update_load_avg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1532
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void update_load_avg(struct cfs_rq * cfs_rq, struct sched_entity * se, int flags)
```

```json
{
  "name": "update_load_avg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579795184,
      "name": "update_load_avg",
      "external": false,
      "loc": "kernel/sched/fair.c:3589",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579795184,
      "name": "update_load_avg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1597
    }
  ]
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
void update_load_avg(struct sched_entity * se, int update_tg)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void update_load_avg(struct sched_entity * se, int flags)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct cfs_rq * cfs_rq</code>
</li>
<li>
<b>Param reordered. </b>
<code>se, flags</code> ➡️ <code>cfs_rq, se, flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
