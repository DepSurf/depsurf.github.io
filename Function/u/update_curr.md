# Function: <code>update_curr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void update_curr(struct cfs_rq * cfs_rq)
```

```json
{
  "name": "update_curr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579585088,
      "name": "update_curr",
      "external": false,
      "loc": "kernel/sched/fair.c:701",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_curr_fair",
        "kernel/sched/fair.c:update_cfs_shares",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:pick_next_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579585088,
      "name": "update_curr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void update_curr(struct cfs_rq * cfs_rq)
```

```json
{
  "name": "update_curr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579596192,
      "name": "update_curr",
      "external": false,
      "loc": "kernel/sched/fair.c:783",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:update_cfs_shares",
        "kernel/sched/fair.c:update_curr_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579596192,
      "name": "update_curr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
void update_curr(struct cfs_rq * cfs_rq)
```

```json
{
  "name": "update_curr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579629744,
      "name": "update_curr",
      "external": false,
      "loc": "kernel/sched/fair.c:842",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:update_cfs_shares",
        "kernel/sched/fair.c:update_curr_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579629744,
      "name": "update_curr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
void update_curr(struct cfs_rq * cfs_rq)
```

```json
{
  "name": "update_curr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579611744,
      "name": "update_curr",
      "external": false,
      "loc": "kernel/sched/fair.c:839",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:update_cfs_shares",
        "kernel/sched/fair.c:update_curr_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579611744,
      "name": "update_curr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
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
void update_curr(struct cfs_rq * cfs_rq)
```

```json
{
  "name": "update_curr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579643392,
      "name": "update_curr",
      "external": false,
      "loc": "kernel/sched/fair.c:819",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:update_curr_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579643392,
      "name": "update_curr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 461
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
void update_curr(struct cfs_rq * cfs_rq)
```

```json
{
  "name": "update_curr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579669200,
      "name": "update_curr",
      "external": false,
      "loc": "kernel/sched/fair.c:806",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:update_curr_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579669200,
      "name": "update_curr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
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
void update_curr(struct cfs_rq * cfs_rq)
```

```json
{
  "name": "update_curr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579711168,
      "name": "update_curr",
      "external": false,
      "loc": "kernel/sched/fair.c:802",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:update_curr_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579711168,
      "name": "update_curr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void update_curr(struct cfs_rq * cfs_rq)
```

```json
{
  "name": "update_curr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579741104,
      "name": "update_curr",
      "external": false,
      "loc": "kernel/sched/fair.c:834",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:update_curr_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579741104,
      "name": "update_curr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void update_curr(struct cfs_rq * cfs_rq)
```

```json
{
  "name": "update_curr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579781840,
      "name": "update_curr",
      "external": false,
      "loc": "kernel/sched/fair.c:833",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:update_curr_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579781840,
      "name": "update_curr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void update_curr(struct cfs_rq * cfs_rq)
```

```json
{
  "name": "update_curr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579820256,
      "name": "update_curr",
      "external": false,
      "loc": "kernel/sched/fair.c:844",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:update_curr_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579820256,
      "name": "update_curr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void update_curr(struct cfs_rq * cfs_rq)
```

```json
{
  "name": "update_curr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579811584,
      "name": "update_curr",
      "external": false,
      "loc": "kernel/sched/fair.c:842",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:update_curr_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579811584,
      "name": "update_curr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
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
void update_curr(struct cfs_rq * cfs_rq)
```

```json
{
  "name": "update_curr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579822240,
      "name": "update_curr",
      "external": false,
      "loc": "kernel/sched/fair.c:839",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:update_curr_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579822240,
      "name": "update_curr",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void update_curr(struct cfs_rq * cfs_rq)
```

```json
{
  "name": "update_curr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "update_curr",
      "external": false,
      "loc": "kernel/sched/fair.c:825",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_task_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:update_curr_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579922160,
      "name": "update_curr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 449
    },
    {
      "addr": 18446744071592109101,
      "name": "update_curr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void update_curr(struct cfs_rq * cfs_rq)
```

```json
{
  "name": "update_curr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "update_curr",
      "external": false,
      "loc": "kernel/sched/fair.c:888",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_task_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:update_curr_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580041296,
      "name": "update_curr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 518
    },
    {
      "addr": 18446744071593876741,
      "name": "update_curr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void update_curr(struct cfs_rq * cfs_rq)
```

```json
{
  "name": "update_curr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "update_curr",
      "external": false,
      "loc": "kernel/sched/fair.c:897",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_task_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:update_curr_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580205040,
      "name": "update_curr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 515
    },
    {
      "addr": 18446744071595978619,
      "name": "update_curr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void update_curr(struct cfs_rq * cfs_rq)
```

```json
{
  "name": "update_curr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "update_curr",
      "external": false,
      "loc": "kernel/sched/fair.c:897",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_task_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:update_curr_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580263040,
      "name": "update_curr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 515
    },
    {
      "addr": 18446744071596496538,
      "name": "update_curr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void update_curr(struct cfs_rq * cfs_rq)
```

```json
{
  "name": "update_curr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580305936,
      "name": "update_curr",
      "external": false,
      "loc": "kernel/sched/fair.c:1156",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_task_fair",
        "kernel/sched/fair.c:check_preempt_wakeup_fair",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:update_curr_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580305936,
      "name": "update_curr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 522
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void update_curr(struct cfs_rq * cfs_rq)
```

```json
{
  "name": "update_curr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490960904,
      "name": "update_curr",
      "external": false,
      "loc": "kernel/sched/fair.c:833",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:update_curr_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490960904,
      "name": "update_curr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
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
void update_curr(struct cfs_rq * cfs_rq)
```

```json
{
  "name": "update_curr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224969464,
      "name": "update_curr",
      "external": false,
      "loc": "kernel/sched/fair.c:833",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:update_curr_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224969464,
      "name": "update_curr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 700
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
void update_curr(struct cfs_rq * cfs_rq)
```

```json
{
  "name": "update_curr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283825152,
      "name": "update_curr",
      "external": false,
      "loc": "kernel/sched/fair.c:833",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:update_curr_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283825152,
      "name": "update_curr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
void update_curr(struct cfs_rq * cfs_rq)
```

```json
{
  "name": "update_curr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271586332,
      "name": "update_curr",
      "external": false,
      "loc": "kernel/sched/fair.c:833",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:update_curr_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271586332,
      "name": "update_curr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void update_curr(struct cfs_rq * cfs_rq)
```

```json
{
  "name": "update_curr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579757696,
      "name": "update_curr",
      "external": false,
      "loc": "kernel/sched/fair.c:833",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:update_curr_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579757696,
      "name": "update_curr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void update_curr(struct cfs_rq * cfs_rq)
```

```json
{
  "name": "update_curr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579688080,
      "name": "update_curr",
      "external": false,
      "loc": "kernel/sched/fair.c:833",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:update_curr_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579688080,
      "name": "update_curr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
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
void update_curr(struct cfs_rq * cfs_rq)
```

```json
{
  "name": "update_curr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579742208,
      "name": "update_curr",
      "external": false,
      "loc": "kernel/sched/fair.c:833",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:update_curr_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579742208,
      "name": "update_curr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void update_curr(struct cfs_rq * cfs_rq)
```

```json
{
  "name": "update_curr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579790528,
      "name": "update_curr",
      "external": false,
      "loc": "kernel/sched/fair.c:833",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:update_curr_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579790528,
      "name": "update_curr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 515
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
