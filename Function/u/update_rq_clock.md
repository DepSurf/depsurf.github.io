# Function: <code>update_rq_clock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void update_rq_clock(struct rq * rq)
```

```json
{
  "name": "update_rq_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579526592,
      "name": "update_rq_clock",
      "external": true,
      "loc": "kernel/sched/core.c:98",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:hrtick",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:activate_task",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:migration_call",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task"
      ],
      "caller_func": [
        "kernel/sched/core.c:hrtick",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:activate_task",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:migration_call",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/fair.c:run_rebalance_domains",
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/deadline.c:yield_task_dl",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579526592,
      "name": "update_rq_clock.part.79",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071579541968,
      "name": "update_rq_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void update_rq_clock(struct rq * rq)
```

```json
{
  "name": "update_rq_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579579017,
      "name": "update_rq_clock",
      "external": true,
      "loc": "kernel/sched/core.c:99",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:activate_task",
        "kernel/sched/core.c:hrtick"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:activate_task",
        "kernel/sched/core.c:hrtick",
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:run_rebalance_domains",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:cpu_load_update_nohz_stop",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/deadline.c:yield_task_dl",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579542912,
      "name": "update_rq_clock.part.82",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071579549616,
      "name": "update_rq_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void update_rq_clock(struct rq * rq)
```

```json
{
  "name": "update_rq_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579605099,
      "name": "update_rq_clock",
      "external": true,
      "loc": "kernel/sched/core.c:99",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:activate_task",
        "kernel/sched/core.c:hrtick"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:do_set_cpus_allowed",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:activate_task",
        "kernel/sched/core.c:hrtick",
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:run_rebalance_domains",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:cpu_load_update_nohz_stop",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/deadline.c:yield_task_dl",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579567728,
      "name": "update_rq_clock.part.80",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071579574416,
      "name": "update_rq_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void update_rq_clock(struct rq * rq)
```

```json
{
  "name": "update_rq_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579558368,
      "name": "update_rq_clock",
      "external": true,
      "loc": "kernel/sched/core.c:212",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:activate_task",
        "kernel/sched/core.c:hrtick",
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:online_fair_sched_group",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:run_rebalance_domains",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:cpu_load_update_nohz_stop",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/deadline.c:yield_task_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579558368,
      "name": "update_rq_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void update_rq_clock(struct rq * rq)
```

```json
{
  "name": "update_rq_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579587728,
      "name": "update_rq_clock",
      "external": true,
      "loc": "kernel/sched/core.c:214",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:activate_task",
        "kernel/sched/core.c:hrtick",
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:online_fair_sched_group",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:run_rebalance_domains",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:cpu_load_update_nohz_stop",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/deadline.c:yield_task_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579587728,
      "name": "update_rq_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void update_rq_clock(struct rq * rq)
```

```json
{
  "name": "update_rq_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579619312,
      "name": "update_rq_clock",
      "external": true,
      "loc": "kernel/sched/core.c:192",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:activate_task",
        "kernel/sched/core.c:hrtick",
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:online_fair_sched_group",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:cpu_load_update_nohz_stop",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/sched/deadline.c:yield_task_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579619312,
      "name": "update_rq_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void update_rq_clock(struct rq * rq)
```

```json
{
  "name": "update_rq_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579656720,
      "name": "update_rq_clock",
      "external": true,
      "loc": "kernel/sched/core.c:185",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:activate_task",
        "kernel/sched/core.c:hrtick",
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:online_fair_sched_group",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:cpu_load_update_nohz_stop",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/sched/deadline.c:yield_task_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579656720,
      "name": "update_rq_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void update_rq_clock(struct rq * rq)
```

```json
{
  "name": "update_rq_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579680288,
      "name": "update_rq_clock",
      "external": true,
      "loc": "kernel/sched/core.c:199",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:activate_task",
        "kernel/sched/core.c:hrtick",
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:online_fair_sched_group",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/sched/deadline.c:yield_task_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579680288,
      "name": "update_rq_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
void update_rq_clock(struct rq * rq)
```

```json
{
  "name": "update_rq_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579720064,
      "name": "update_rq_clock",
      "external": true,
      "loc": "kernel/sched/core.c:199",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:activate_task",
        "kernel/sched/core.c:hrtick",
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:online_fair_sched_group",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/sched/deadline.c:yield_task_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579720064,
      "name": "update_rq_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
void update_rq_clock(struct rq * rq)
```

```json
{
  "name": "update_rq_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579762512,
      "name": "update_rq_clock",
      "external": true,
      "loc": "kernel/sched/core.c:202",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:migrate_tasks",
        "kernel/sched/core.c:migrate_tasks",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:hrtick",
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:online_fair_sched_group",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/rt.c:do_sched_rt_period_timer",
        "kernel/sched/deadline.c:yield_task_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579762512,
      "name": "update_rq_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void update_rq_clock(struct rq * rq)
```

```json
{
  "name": "update_rq_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579751344,
      "name": "update_rq_clock",
      "external": true,
      "loc": "kernel/sched/core.c:301",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:hrtick",
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:online_fair_sched_group",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/rt.c:do_sched_rt_period_timer",
        "kernel/sched/deadline.c:yield_task_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579751344,
      "name": "update_rq_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void update_rq_clock(struct rq * rq)
```

```json
{
  "name": "update_rq_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579758112,
      "name": "update_rq_clock",
      "external": true,
      "loc": "kernel/sched/core.c:311",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:hrtick",
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:online_fair_sched_group",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/rt.c:do_sched_rt_period_timer",
        "kernel/sched/deadline.c:yield_task_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579758112,
      "name": "update_rq_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void update_rq_clock(struct rq * rq)
```

```json
{
  "name": "update_rq_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "update_rq_clock",
      "external": true,
      "loc": "kernel/sched/core.c:664",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:hrtick",
        "kernel/sched/fair.c:online_fair_sched_group",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/rt.c:do_sched_rt_period_timer",
        "kernel/sched/deadline.c:yield_task_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592107238,
      "name": "update_rq_clock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579843904,
      "name": "update_rq_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
void update_rq_clock(struct rq * rq)
```

```json
{
  "name": "update_rq_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "update_rq_clock",
      "external": true,
      "loc": "kernel/sched/core.c:734",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:hrtick",
        "kernel/sched/fair.c:__sched_group_set_shares",
        "kernel/sched/fair.c:online_fair_sched_group",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/build_policy.c:migrate_task_rq_dl",
        "kernel/sched/build_policy.c:yield_task_dl",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:dl_task_timer",
        "kernel/sched/build_policy.c:dl_task_timer",
        "kernel/sched/build_policy.c:do_sched_rt_period_timer",
        "kernel/sched/build_utility.c:__sched_core_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593874955,
      "name": "update_rq_clock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579959776,
      "name": "update_rq_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
void update_rq_clock(struct rq * rq)
```

```json
{
  "name": "update_rq_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "update_rq_clock",
      "external": true,
      "loc": "kernel/sched/core.c:728",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:hrtick",
        "kernel/sched/fair.c:__sched_group_set_shares",
        "kernel/sched/fair.c:online_fair_sched_group",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/build_policy.c:migrate_task_rq_dl",
        "kernel/sched/build_policy.c:yield_task_dl",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:dl_task_timer",
        "kernel/sched/build_policy.c:dl_task_timer",
        "kernel/sched/build_policy.c:do_sched_rt_period_timer",
        "kernel/sched/build_utility.c:__sched_core_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595977300,
      "name": "update_rq_clock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071580119280,
      "name": "update_rq_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 551
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
void update_rq_clock(struct rq * rq)
```

```json
{
  "name": "update_rq_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "update_rq_clock",
      "external": true,
      "loc": "kernel/sched/core.c:750",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:hrtick",
        "kernel/sched/fair.c:__sched_group_set_shares",
        "kernel/sched/fair.c:online_fair_sched_group",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:__cfsb_csd_unthrottle",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/build_policy.c:migrate_task_rq_dl",
        "kernel/sched/build_policy.c:yield_task_dl",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:dl_task_timer",
        "kernel/sched/build_policy.c:dl_task_timer",
        "kernel/sched/build_policy.c:do_sched_rt_period_timer",
        "kernel/sched/build_utility.c:__sched_core_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596495140,
      "name": "update_rq_clock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071580180832,
      "name": "update_rq_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 569
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void update_rq_clock(struct rq * rq)
```

```json
{
  "name": "update_rq_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "update_rq_clock",
      "external": true,
      "loc": "kernel/sched/core.c:751",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:sched_tick_remote",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:hrtick",
        "kernel/sched/fair.c:__sched_group_set_shares",
        "kernel/sched/fair.c:online_fair_sched_group",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:__cfsb_csd_unthrottle",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/build_policy.c:migrate_task_rq_dl",
        "kernel/sched/build_policy.c:yield_task_dl",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:dl_task_timer",
        "kernel/sched/build_policy.c:dl_task_timer",
        "kernel/sched/build_policy.c:dl_task_timer",
        "kernel/sched/build_policy.c:do_sched_rt_period_timer",
        "kernel/sched/build_utility.c:__sched_core_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597391943,
      "name": "update_rq_clock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071580227376,
      "name": "update_rq_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 569
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
void update_rq_clock(struct rq * rq)
```

```json
{
  "name": "update_rq_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490902568,
      "name": "update_rq_clock",
      "external": true,
      "loc": "kernel/sched/core.c:199",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:dequeue_task",
        "kernel/sched/core.c:enqueue_task",
        "kernel/sched/core.c:hrtick",
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:online_fair_sched_group",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/sched/deadline.c:yield_task_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490902568,
      "name": "update_rq_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void update_rq_clock(struct rq * rq)
```

```json
{
  "name": "update_rq_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224916616,
      "name": "update_rq_clock",
      "external": true,
      "loc": "kernel/sched/core.c:199",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:activate_task",
        "kernel/sched/core.c:hrtick",
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:online_fair_sched_group",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/sched/deadline.c:yield_task_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224916616,
      "name": "update_rq_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
void update_rq_clock(struct rq * rq)
```

```json
{
  "name": "update_rq_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283742224,
      "name": "update_rq_clock",
      "external": true,
      "loc": "kernel/sched/core.c:199",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:activate_task",
        "kernel/sched/core.c:hrtick",
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:online_fair_sched_group",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/sched/deadline.c:yield_task_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283742224,
      "name": "update_rq_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
void update_rq_clock(struct rq * rq)
```

```json
{
  "name": "update_rq_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271545224,
      "name": "update_rq_clock",
      "external": true,
      "loc": "kernel/sched/core.c:199",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:activate_task",
        "kernel/sched/core.c:hrtick",
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:online_fair_sched_group",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/sched/deadline.c:yield_task_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271545224,
      "name": "update_rq_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void update_rq_clock(struct rq * rq)
```

```json
{
  "name": "update_rq_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579696256,
      "name": "update_rq_clock",
      "external": true,
      "loc": "kernel/sched/core.c:199",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:activate_task",
        "kernel/sched/core.c:hrtick",
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:online_fair_sched_group",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/sched/deadline.c:yield_task_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579696256,
      "name": "update_rq_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
void update_rq_clock(struct rq * rq)
```

```json
{
  "name": "update_rq_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579624768,
      "name": "update_rq_clock",
      "external": true,
      "loc": "kernel/sched/core.c:199",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:sched_tick_remote",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:activate_task",
        "kernel/sched/core.c:hrtick",
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:online_fair_sched_group",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/sched/deadline.c:yield_task_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579624768,
      "name": "update_rq_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
void update_rq_clock(struct rq * rq)
```

```json
{
  "name": "update_rq_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579691024,
      "name": "update_rq_clock",
      "external": true,
      "loc": "kernel/sched/core.c:199",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:activate_task",
        "kernel/sched/core.c:hrtick",
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:online_fair_sched_group",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/sched/deadline.c:yield_task_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579691024,
      "name": "update_rq_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
void update_rq_clock(struct rq * rq)
```

```json
{
  "name": "update_rq_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579727856,
      "name": "update_rq_clock",
      "external": true,
      "loc": "kernel/sched/core.c:199",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:activate_task",
        "kernel/sched/core.c:hrtick",
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:online_fair_sched_group",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:yield_task_fair",
        "kernel/sched/fair.c:unthrottle_cfs_rq",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/sched/deadline.c:yield_task_dl",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579727856,
      "name": "update_rq_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
