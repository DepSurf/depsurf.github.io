# Function: <code>raw_spin_rq_unlock</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void raw_spin_rq_unlock(struct rq * rq)
```

```json
{
  "name": "raw_spin_rq_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579838192,
      "name": "raw_spin_rq_unlock",
      "external": true,
      "loc": "kernel/sched/core.c:516",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:tg_set_cfs_bandwidth",
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:balance_push_set",
        "kernel/sched/core.c:balance_push_set",
        "kernel/sched/core.c:balance_push",
        "kernel/sched/core.c:balance_push",
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:init_idle",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:do_sched_yield",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:sched_core_balance",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_post_fork",
        "kernel/sched/core.c:try_invoke_on_locked_down_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:migrate_swap_stop",
        "kernel/sched/core.c:migrate_swap_stop",
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/core.c:__hrtick_start",
        "kernel/sched/core.c:hrtick",
        "kernel/sched/core.c:task_rq_lock",
        "kernel/sched/core.c:__task_rq_lock",
        "kernel/sched/idle.c:dequeue_task_idle",
        "kernel/sched/fair.c:sched_group_set_idle",
        "kernel/sched/fair.c:unregister_fair_sched_group",
        "kernel/sched/fair.c:online_fair_sched_group",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:distribute_cfs_runtime",
        "kernel/sched/fair.c:distribute_cfs_runtime",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:rto_push_irq_work_func",
        "kernel/sched/rt.c:find_lock_lowest_rq",
        "kernel/sched/rt.c:find_lock_lowest_rq",
        "kernel/sched/rt.c:find_lock_lowest_rq",
        "kernel/sched/rt.c:do_sched_rt_period_timer",
        "kernel/sched/deadline.c:dl_add_task_root_domain",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:inactive_task_timer",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/topology.c:rq_attach_root",
        "kernel/sched/debug.c:print_cfs_rq",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:psi_memstall_leave",
        "kernel/sched/psi.c:psi_memstall_enter",
        "kernel/sched/core_sched.c:sched_core_update_cookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579838192,
      "name": "raw_spin_rq_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void raw_spin_rq_unlock(struct rq * rq)
```

```json
{
  "name": "raw_spin_rq_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579952624,
      "name": "raw_spin_rq_unlock",
      "external": true,
      "loc": "kernel/sched/core.c:586",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:tg_set_cfs_bandwidth",
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:balance_push_set",
        "kernel/sched/core.c:balance_push",
        "kernel/sched/core.c:balance_push",
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:init_idle",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:do_sched_yield",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:sched_core_balance",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_post_fork",
        "kernel/sched/core.c:task_call_func",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:migrate_swap_stop",
        "kernel/sched/core.c:migrate_swap_stop",
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/core.c:__hrtick_start",
        "kernel/sched/core.c:hrtick",
        "kernel/sched/core.c:task_rq_lock",
        "kernel/sched/core.c:__task_rq_lock",
        "kernel/sched/fair.c:sched_group_set_idle",
        "kernel/sched/fair.c:__sched_group_set_shares",
        "kernel/sched/fair.c:unregister_fair_sched_group",
        "kernel/sched/fair.c:online_fair_sched_group",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:distribute_cfs_runtime",
        "kernel/sched/fair.c:distribute_cfs_runtime",
        "kernel/sched/build_policy.c:dl_add_task_root_domain",
        "kernel/sched/build_policy.c:pull_dl_task",
        "kernel/sched/build_policy.c:pull_dl_task",
        "kernel/sched/build_policy.c:pull_dl_task",
        "kernel/sched/build_policy.c:push_dl_task",
        "kernel/sched/build_policy.c:find_lock_later_rq",
        "kernel/sched/build_policy.c:find_lock_later_rq",
        "kernel/sched/build_policy.c:find_lock_later_rq",
        "kernel/sched/build_policy.c:migrate_task_rq_dl",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:dl_task_timer",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:rto_push_irq_work_func",
        "kernel/sched/build_policy.c:push_rt_task",
        "kernel/sched/build_policy.c:push_rt_task",
        "kernel/sched/build_policy.c:find_lock_lowest_rq",
        "kernel/sched/build_policy.c:find_lock_lowest_rq",
        "kernel/sched/build_policy.c:find_lock_lowest_rq",
        "kernel/sched/build_policy.c:do_sched_rt_period_timer",
        "kernel/sched/build_policy.c:dequeue_task_idle",
        "kernel/sched/build_utility.c:cgroup_move_task",
        "kernel/sched/build_utility.c:psi_memstall_leave",
        "kernel/sched/build_utility.c:psi_memstall_enter",
        "kernel/sched/build_utility.c:__sched_core_set",
        "kernel/sched/build_utility.c:rq_attach_root",
        "kernel/sched/build_utility.c:print_cfs_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579952624,
      "name": "raw_spin_rq_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void raw_spin_rq_unlock(struct rq * rq)
```

```json
{
  "name": "raw_spin_rq_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580111728,
      "name": "raw_spin_rq_unlock",
      "external": true,
      "loc": "kernel/sched/core.c:579",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:tg_set_cfs_bandwidth",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:balance_push_set",
        "kernel/sched/core.c:balance_push",
        "kernel/sched/core.c:balance_push",
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:init_idle",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:do_sched_yield",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:sched_core_balance",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_post_fork",
        "kernel/sched/core.c:task_call_func",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:migrate_swap_stop",
        "kernel/sched/core.c:migrate_swap_stop",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/core.c:__hrtick_start",
        "kernel/sched/core.c:hrtick",
        "kernel/sched/core.c:task_rq_lock",
        "kernel/sched/core.c:__task_rq_lock",
        "kernel/sched/fair.c:sched_group_set_idle",
        "kernel/sched/fair.c:__sched_group_set_shares",
        "kernel/sched/fair.c:unregister_fair_sched_group",
        "kernel/sched/fair.c:online_fair_sched_group",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:distribute_cfs_runtime",
        "kernel/sched/fair.c:distribute_cfs_runtime",
        "kernel/sched/build_policy.c:dl_add_task_root_domain",
        "kernel/sched/build_policy.c:pull_dl_task",
        "kernel/sched/build_policy.c:pull_dl_task",
        "kernel/sched/build_policy.c:pull_dl_task",
        "kernel/sched/build_policy.c:push_dl_task",
        "kernel/sched/build_policy.c:find_lock_later_rq",
        "kernel/sched/build_policy.c:find_lock_later_rq",
        "kernel/sched/build_policy.c:find_lock_later_rq",
        "kernel/sched/build_policy.c:migrate_task_rq_dl",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:dl_task_timer",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:rto_push_irq_work_func",
        "kernel/sched/build_policy.c:push_rt_task",
        "kernel/sched/build_policy.c:push_rt_task",
        "kernel/sched/build_policy.c:find_lock_lowest_rq",
        "kernel/sched/build_policy.c:find_lock_lowest_rq",
        "kernel/sched/build_policy.c:find_lock_lowest_rq",
        "kernel/sched/build_policy.c:do_sched_rt_period_timer",
        "kernel/sched/build_policy.c:dequeue_task_idle",
        "kernel/sched/build_utility.c:psi_cgroup_restart",
        "kernel/sched/build_utility.c:cgroup_move_task",
        "kernel/sched/build_utility.c:psi_memstall_enter",
        "kernel/sched/build_utility.c:__sched_core_set",
        "kernel/sched/build_utility.c:rq_attach_root",
        "kernel/sched/build_utility.c:print_cfs_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580111728,
      "name": "raw_spin_rq_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void raw_spin_rq_unlock(struct rq * rq)
```

```json
{
  "name": "raw_spin_rq_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580230786,
      "name": "raw_spin_rq_unlock",
      "external": true,
      "loc": "kernel/sched/core.c:600",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_mm_cid_after_execve",
        "kernel/sched/core.c:sched_mm_cid_before_execve",
        "kernel/sched/core.c:tg_set_cfs_bandwidth",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:balance_push_set",
        "kernel/sched/core.c:balance_push",
        "kernel/sched/core.c:balance_push",
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:init_idle",
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:do_sched_yield",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:sched_core_balance",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_post_fork",
        "kernel/sched/core.c:task_call_func",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:migrate_swap_stop",
        "kernel/sched/core.c:migrate_swap_stop",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/core.c:__hrtick_start",
        "kernel/sched/core.c:hrtick",
        "kernel/sched/core.c:task_rq_lock",
        "kernel/sched/core.c:__task_rq_lock"
      ],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_idle",
        "kernel/sched/fair.c:__sched_group_set_shares",
        "kernel/sched/fair.c:unregister_fair_sched_group",
        "kernel/sched/fair.c:online_fair_sched_group",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:distribute_cfs_runtime",
        "kernel/sched/fair.c:distribute_cfs_runtime",
        "kernel/sched/fair.c:__cfsb_csd_unthrottle",
        "kernel/sched/build_policy.c:dl_add_task_root_domain",
        "kernel/sched/build_policy.c:pull_dl_task",
        "kernel/sched/build_policy.c:pull_dl_task",
        "kernel/sched/build_policy.c:pull_dl_task",
        "kernel/sched/build_policy.c:push_dl_task",
        "kernel/sched/build_policy.c:find_lock_later_rq",
        "kernel/sched/build_policy.c:find_lock_later_rq",
        "kernel/sched/build_policy.c:find_lock_later_rq",
        "kernel/sched/build_policy.c:migrate_task_rq_dl",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:dl_task_timer",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:rto_push_irq_work_func",
        "kernel/sched/build_policy.c:push_rt_task",
        "kernel/sched/build_policy.c:push_rt_task",
        "kernel/sched/build_policy.c:find_lock_lowest_rq",
        "kernel/sched/build_policy.c:find_lock_lowest_rq",
        "kernel/sched/build_policy.c:find_lock_lowest_rq",
        "kernel/sched/build_policy.c:do_sched_rt_period_timer",
        "kernel/sched/build_policy.c:dequeue_task_idle",
        "kernel/sched/build_utility.c:psi_cgroup_restart",
        "kernel/sched/build_utility.c:cgroup_move_task",
        "kernel/sched/build_utility.c:psi_memstall_enter",
        "kernel/sched/build_utility.c:__sched_core_set",
        "kernel/sched/build_utility.c:rq_attach_root",
        "kernel/sched/build_utility.c:print_cfs_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580176304,
      "name": "raw_spin_rq_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void raw_spin_rq_unlock(struct rq * rq)
```

```json
{
  "name": "raw_spin_rq_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580279623,
      "name": "raw_spin_rq_unlock",
      "external": true,
      "loc": "kernel/sched/core.c:601",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_mm_cid_after_execve",
        "kernel/sched/core.c:sched_mm_cid_before_execve",
        "kernel/sched/core.c:tg_set_cfs_bandwidth",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:balance_push_set",
        "kernel/sched/core.c:balance_push",
        "kernel/sched/core.c:balance_push",
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:sched_setnuma",
        "kernel/sched/core.c:init_idle",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/core.c:do_sched_yield",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:set_user_nice",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:sched_core_balance",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:try_steal_cookie",
        "kernel/sched/core.c:sched_tick_remote",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:task_sched_runtime",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_post_fork",
        "kernel/sched/core.c:task_call_func",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:migrate_swap_stop",
        "kernel/sched/core.c:migrate_swap_stop",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:push_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:migration_cpu_stop",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:wait_task_inactive",
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/core.c:uclamp_update_active_tasks",
        "kernel/sched/core.c:resched_cpu",
        "kernel/sched/core.c:__hrtick_start",
        "kernel/sched/core.c:hrtick",
        "kernel/sched/core.c:task_rq_lock",
        "kernel/sched/core.c:__task_rq_lock"
      ],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_idle",
        "kernel/sched/fair.c:__sched_group_set_shares",
        "kernel/sched/fair.c:unregister_fair_sched_group",
        "kernel/sched/fair.c:online_fair_sched_group",
        "kernel/sched/fair.c:task_fork_fair",
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:active_load_balance_cpu_stop",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:distribute_cfs_runtime",
        "kernel/sched/fair.c:distribute_cfs_runtime",
        "kernel/sched/fair.c:__cfsb_csd_unthrottle",
        "kernel/sched/build_policy.c:dl_add_task_root_domain",
        "kernel/sched/build_policy.c:pull_dl_task",
        "kernel/sched/build_policy.c:pull_dl_task",
        "kernel/sched/build_policy.c:pull_dl_task",
        "kernel/sched/build_policy.c:push_dl_task",
        "kernel/sched/build_policy.c:find_lock_later_rq",
        "kernel/sched/build_policy.c:find_lock_later_rq",
        "kernel/sched/build_policy.c:find_lock_later_rq",
        "kernel/sched/build_policy.c:migrate_task_rq_dl",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:inactive_task_timer",
        "kernel/sched/build_policy.c:dl_task_timer",
        "kernel/sched/build_policy.c:dl_task_timer",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:rto_push_irq_work_func",
        "kernel/sched/build_policy.c:push_rt_task",
        "kernel/sched/build_policy.c:push_rt_task",
        "kernel/sched/build_policy.c:find_lock_lowest_rq",
        "kernel/sched/build_policy.c:find_lock_lowest_rq",
        "kernel/sched/build_policy.c:find_lock_lowest_rq",
        "kernel/sched/build_policy.c:do_sched_rt_period_timer",
        "kernel/sched/build_policy.c:dequeue_task_idle",
        "kernel/sched/build_utility.c:psi_cgroup_restart",
        "kernel/sched/build_utility.c:cgroup_move_task",
        "kernel/sched/build_utility.c:psi_memstall_enter",
        "kernel/sched/build_utility.c:__sched_core_set",
        "kernel/sched/build_utility.c:rq_attach_root",
        "kernel/sched/build_utility.c:print_cfs_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580222672,
      "name": "raw_spin_rq_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void raw_spin_rq_unlock(struct rq * rq)
```
</details>
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
