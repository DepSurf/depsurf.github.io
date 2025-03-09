# Function: <code>resched_curr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void resched_curr(struct rq * rq)
```

```json
{
  "name": "resched_curr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579542224,
      "name": "resched_curr",
      "external": true,
      "loc": "kernel/sched/core.c:574",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/core.c:check_preempt_curr",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/idle_task.c:check_preempt_curr_idle",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/rt.c:check_preempt_curr_rt",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/sched/rt.c:task_tick_rt",
        "kernel/sched/rt.c:rq_offline_rt",
        "kernel/sched/deadline.c:check_preempt_curr_dl",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:pull_dl_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579542224,
      "name": "resched_curr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void resched_curr(struct rq * rq)
```

```json
{
  "name": "resched_curr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579553584,
      "name": "resched_curr",
      "external": true,
      "loc": "kernel/sched/core.c:481",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:check_preempt_curr",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/idle_task.c:check_preempt_curr_idle",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/rt.c:task_tick_rt",
        "kernel/sched/rt.c:rq_offline_rt",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:check_preempt_curr_rt",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:check_preempt_curr_dl",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579553584,
      "name": "resched_curr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void resched_curr(struct rq * rq)
```

```json
{
  "name": "resched_curr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579578304,
      "name": "resched_curr",
      "external": true,
      "loc": "kernel/sched/core.c:481",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:check_preempt_curr",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/idle_task.c:check_preempt_curr_idle",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/rt.c:task_tick_rt",
        "kernel/sched/rt.c:rq_offline_rt",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:check_preempt_curr_rt",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:check_preempt_curr_dl",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579578304,
      "name": "resched_curr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void resched_curr(struct rq * rq)
```

```json
{
  "name": "resched_curr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579561696,
      "name": "resched_curr",
      "external": true,
      "loc": "kernel/sched/core.c:479",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:check_preempt_curr",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/idle_task.c:check_preempt_curr_idle",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:hrtick_start_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/rt.c:task_tick_rt",
        "kernel/sched/rt.c:rq_offline_rt",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:check_preempt_curr_rt",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:check_preempt_curr_dl",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579561696,
      "name": "resched_curr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void resched_curr(struct rq * rq)
```

```json
{
  "name": "resched_curr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579590960,
      "name": "resched_curr",
      "external": true,
      "loc": "kernel/sched/core.c:481",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:check_preempt_curr",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/idle_task.c:check_preempt_curr_idle",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:hrtick_start_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/rt.c:task_tick_rt",
        "kernel/sched/rt.c:rq_offline_rt",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:check_preempt_curr_rt",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:check_preempt_curr_dl",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579590960,
      "name": "resched_curr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void resched_curr(struct rq * rq)
```

```json
{
  "name": "resched_curr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579623312,
      "name": "resched_curr",
      "external": true,
      "loc": "kernel/sched/core.c:459",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:check_preempt_curr",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/idle.c:check_preempt_curr_idle",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:hrtick_start_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/rt.c:task_tick_rt",
        "kernel/sched/rt.c:rq_offline_rt",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:check_preempt_curr_rt",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:check_preempt_curr_dl",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579623312,
      "name": "resched_curr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
void resched_curr(struct rq * rq)
```

```json
{
  "name": "resched_curr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579660864,
      "name": "resched_curr",
      "external": true,
      "loc": "kernel/sched/core.c:465",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:check_preempt_curr",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/idle.c:check_preempt_curr_idle",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:hrtick_start_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/rt.c:task_tick_rt",
        "kernel/sched/rt.c:rq_offline_rt",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:check_preempt_curr_rt",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:check_preempt_curr_dl",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579660864,
      "name": "resched_curr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
void resched_curr(struct rq * rq)
```

```json
{
  "name": "resched_curr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579686816,
      "name": "resched_curr",
      "external": true,
      "loc": "kernel/sched/core.c:507",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:check_preempt_curr",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/idle.c:check_preempt_curr_idle",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:hrtick_start_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/rt.c:task_tick_rt",
        "kernel/sched/rt.c:rq_offline_rt",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:check_preempt_curr_rt",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:check_preempt_curr_dl",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579686816,
      "name": "resched_curr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void resched_curr(struct rq * rq)
```

```json
{
  "name": "resched_curr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579726544,
      "name": "resched_curr",
      "external": true,
      "loc": "kernel/sched/core.c:507",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:check_preempt_curr",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/idle.c:check_preempt_curr_idle",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:hrtick_start_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/rt.c:task_tick_rt",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:check_preempt_curr_rt",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/rt.c:sched_rt_rq_enqueue",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:check_preempt_curr_dl",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579726544,
      "name": "resched_curr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void resched_curr(struct rq * rq)
```

```json
{
  "name": "resched_curr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579770176,
      "name": "resched_curr",
      "external": true,
      "loc": "kernel/sched/core.c:510",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:check_preempt_curr",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/idle.c:check_preempt_curr_idle",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:hrtick_start_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/rt.c:task_tick_rt",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:check_preempt_curr_rt",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/rt.c:do_sched_rt_period_timer",
        "kernel/sched/rt.c:__disable_runtime",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:check_preempt_curr_dl",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579770176,
      "name": "resched_curr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void resched_curr(struct rq * rq)
```

```json
{
  "name": "resched_curr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579758880,
      "name": "resched_curr",
      "external": true,
      "loc": "kernel/sched/core.c:599",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:check_preempt_curr",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/idle.c:check_preempt_curr_idle",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:hrtick_start_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/rt.c:task_tick_rt",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:check_preempt_curr_rt",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/rt.c:do_sched_rt_period_timer",
        "kernel/sched/rt.c:__disable_runtime",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:check_preempt_curr_dl",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579758880,
      "name": "resched_curr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void resched_curr(struct rq * rq)
```

```json
{
  "name": "resched_curr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579766192,
      "name": "resched_curr",
      "external": true,
      "loc": "kernel/sched/core.c:609",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:check_preempt_curr",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/idle.c:check_preempt_curr_idle",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:hrtick_start_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/rt.c:task_tick_rt",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:check_preempt_curr_rt",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/rt.c:do_sched_rt_period_timer",
        "kernel/sched/rt.c:__disable_runtime",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:check_preempt_curr_dl",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579766192,
      "name": "resched_curr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void resched_curr(struct rq * rq)
```

```json
{
  "name": "resched_curr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579852016,
      "name": "resched_curr",
      "external": true,
      "loc": "kernel/sched/core.c:961",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:check_preempt_curr",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/idle.c:check_preempt_curr_idle",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:hrtick_start_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/rt.c:task_tick_rt",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:check_preempt_curr_rt",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/rt.c:do_sched_rt_period_timer",
        "kernel/sched/rt.c:__disable_runtime",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:check_preempt_curr_dl",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/core_sched.c:sched_core_update_cookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579852016,
      "name": "resched_curr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void resched_curr(struct rq * rq)
```

```json
{
  "name": "resched_curr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579962960,
      "name": "resched_curr",
      "external": true,
      "loc": "kernel/sched/core.c:1031",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:check_preempt_curr",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:hrtick_start_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/build_policy.c:pull_dl_task",
        "kernel/sched/build_policy.c:push_dl_task",
        "kernel/sched/build_policy.c:push_dl_task",
        "kernel/sched/build_policy.c:check_preempt_curr_dl",
        "kernel/sched/build_policy.c:update_curr_dl",
        "kernel/sched/build_policy.c:dl_task_timer",
        "kernel/sched/build_policy.c:task_tick_rt",
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:push_rt_task",
        "kernel/sched/build_policy.c:push_rt_task",
        "kernel/sched/build_policy.c:check_preempt_curr_rt",
        "kernel/sched/build_policy.c:update_curr_rt",
        "kernel/sched/build_policy.c:do_sched_rt_period_timer",
        "kernel/sched/build_policy.c:__disable_runtime",
        "kernel/sched/build_policy.c:check_preempt_curr_idle",
        "kernel/sched/build_utility.c:__sched_core_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579962960,
      "name": "resched_curr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void resched_curr(struct rq * rq)
```

```json
{
  "name": "resched_curr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580122624,
      "name": "resched_curr",
      "external": true,
      "loc": "kernel/sched/core.c:1019",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:check_preempt_curr",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:hrtick_start_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/build_policy.c:pull_dl_task",
        "kernel/sched/build_policy.c:push_dl_task",
        "kernel/sched/build_policy.c:push_dl_task",
        "kernel/sched/build_policy.c:check_preempt_curr_dl",
        "kernel/sched/build_policy.c:update_curr_dl",
        "kernel/sched/build_policy.c:dl_task_timer",
        "kernel/sched/build_policy.c:task_tick_rt",
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:push_rt_task",
        "kernel/sched/build_policy.c:push_rt_task",
        "kernel/sched/build_policy.c:check_preempt_curr_rt",
        "kernel/sched/build_policy.c:update_curr_rt",
        "kernel/sched/build_policy.c:do_sched_rt_period_timer",
        "kernel/sched/build_policy.c:__disable_runtime",
        "kernel/sched/build_policy.c:check_preempt_curr_idle",
        "kernel/sched/build_utility.c:__sched_core_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580122624,
      "name": "resched_curr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
void resched_curr(struct rq * rq)
```

```json
{
  "name": "resched_curr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580184352,
      "name": "resched_curr",
      "external": true,
      "loc": "kernel/sched/core.c:1041",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:check_preempt_curr",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:hrtick_start_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/build_policy.c:pull_dl_task",
        "kernel/sched/build_policy.c:push_dl_task",
        "kernel/sched/build_policy.c:push_dl_task",
        "kernel/sched/build_policy.c:check_preempt_curr_dl",
        "kernel/sched/build_policy.c:update_curr_dl",
        "kernel/sched/build_policy.c:dl_task_timer",
        "kernel/sched/build_policy.c:task_tick_rt",
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:push_rt_task",
        "kernel/sched/build_policy.c:push_rt_task",
        "kernel/sched/build_policy.c:check_preempt_curr_rt",
        "kernel/sched/build_policy.c:update_curr_rt",
        "kernel/sched/build_policy.c:do_sched_rt_period_timer",
        "kernel/sched/build_policy.c:__disable_runtime",
        "kernel/sched/build_policy.c:check_preempt_curr_idle",
        "kernel/sched/build_utility.c:__sched_core_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580184352,
      "name": "resched_curr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
void resched_curr(struct rq * rq)
```

```json
{
  "name": "resched_curr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580231504,
      "name": "resched_curr",
      "external": true,
      "loc": "kernel/sched/core.c:1041",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:wakeup_preempt",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:check_preempt_wakeup_fair",
        "kernel/sched/fair.c:hrtick_start_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/fair.c:update_curr",
        "kernel/sched/build_policy.c:pull_dl_task",
        "kernel/sched/build_policy.c:push_dl_task",
        "kernel/sched/build_policy.c:push_dl_task",
        "kernel/sched/build_policy.c:wakeup_preempt_dl",
        "kernel/sched/build_policy.c:update_curr_dl_se",
        "kernel/sched/build_policy.c:dl_task_timer",
        "kernel/sched/build_policy.c:dl_task_timer",
        "kernel/sched/build_policy.c:task_tick_rt",
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:push_rt_task",
        "kernel/sched/build_policy.c:push_rt_task",
        "kernel/sched/build_policy.c:wakeup_preempt_rt",
        "kernel/sched/build_policy.c:update_curr_rt",
        "kernel/sched/build_policy.c:do_sched_rt_period_timer",
        "kernel/sched/build_policy.c:__disable_runtime",
        "kernel/sched/build_policy.c:wakeup_preempt_idle",
        "kernel/sched/build_utility.c:__sched_core_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580231504,
      "name": "resched_curr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
void resched_curr(struct rq * rq)
```

```json
{
  "name": "resched_curr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490909248,
      "name": "resched_curr",
      "external": true,
      "loc": "kernel/sched/core.c:507",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:check_preempt_curr",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/idle.c:check_preempt_curr_idle",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:hrtick_start_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/rt.c:task_tick_rt",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:check_preempt_curr_rt",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/rt.c:sched_rt_rq_enqueue",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:check_preempt_curr_dl",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490909248,
      "name": "resched_curr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void resched_curr(struct rq * rq)
```

```json
{
  "name": "resched_curr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224922232,
      "name": "resched_curr",
      "external": true,
      "loc": "kernel/sched/core.c:507",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:check_preempt_curr",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/idle.c:check_preempt_curr_idle",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:hrtick_start_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/rt.c:task_tick_rt",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:check_preempt_curr_rt",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/rt.c:sched_rt_rq_enqueue",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:check_preempt_curr_dl",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224922232,
      "name": "resched_curr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void resched_curr(struct rq * rq)
```

```json
{
  "name": "resched_curr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283749680,
      "name": "resched_curr",
      "external": true,
      "loc": "kernel/sched/core.c:507",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:check_preempt_curr",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/idle.c:check_preempt_curr_idle",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:hrtick_start_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/rt.c:task_tick_rt",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:check_preempt_curr_rt",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/rt.c:sched_rt_rq_enqueue",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:check_preempt_curr_dl",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283749680,
      "name": "resched_curr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
void resched_curr(struct rq * rq)
```

```json
{
  "name": "resched_curr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271548448,
      "name": "resched_curr",
      "external": true,
      "loc": "kernel/sched/core.c:507",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:check_preempt_curr",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/idle.c:check_preempt_curr_idle",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:hrtick_start_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/rt.c:task_tick_rt",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:check_preempt_curr_rt",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/rt.c:sched_rt_rq_enqueue",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:check_preempt_curr_dl",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271548448,
      "name": "resched_curr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void resched_curr(struct rq * rq)
```

```json
{
  "name": "resched_curr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579703200,
      "name": "resched_curr",
      "external": true,
      "loc": "kernel/sched/core.c:507",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:check_preempt_curr",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/idle.c:check_preempt_curr_idle",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:hrtick_start_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/rt.c:task_tick_rt",
        "kernel/sched/rt.c:rq_offline_rt",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:check_preempt_curr_rt",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:check_preempt_curr_dl",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579703200,
      "name": "resched_curr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void resched_curr(struct rq * rq)
```

```json
{
  "name": "resched_curr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579630944,
      "name": "resched_curr",
      "external": true,
      "loc": "kernel/sched/core.c:507",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:check_preempt_curr",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/idle.c:check_preempt_curr_idle",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:hrtick_start_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/rt.c:task_tick_rt",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:check_preempt_curr_rt",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/rt.c:sched_rt_rq_enqueue",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:check_preempt_curr_dl",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579630944,
      "name": "resched_curr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void resched_curr(struct rq * rq)
```

```json
{
  "name": "resched_curr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579695456,
      "name": "resched_curr",
      "external": true,
      "loc": "kernel/sched/core.c:507",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:check_preempt_curr",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/idle.c:check_preempt_curr_idle",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:hrtick_start_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/rt.c:task_tick_rt",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:check_preempt_curr_rt",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/rt.c:sched_rt_rq_enqueue",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:check_preempt_curr_dl",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579695456,
      "name": "resched_curr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void resched_curr(struct rq * rq)
```

```json
{
  "name": "resched_curr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579733632,
      "name": "resched_curr",
      "external": true,
      "loc": "kernel/sched/core.c:507",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:check_preempt_curr",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/idle.c:check_preempt_curr_idle",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:hrtick_start_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/rt.c:task_tick_rt",
        "kernel/sched/rt.c:rq_offline_rt",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:check_preempt_curr_rt",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:check_preempt_curr_dl",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579733632,
      "name": "resched_curr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
