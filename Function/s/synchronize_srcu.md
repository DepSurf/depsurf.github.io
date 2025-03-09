# Function: <code>synchronize_srcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void synchronize_srcu(struct srcu_struct * sp)
```

```json
{
  "name": "synchronize_srcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579779296,
      "name": "synchronize_srcu",
      "external": true,
      "loc": "kernel/rcu/srcu.c:490",
      "file": "kernel/rcu/srcu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcu.c:srcu_barrier",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/group.c:fsnotify_destroy_group",
        "fs/notify/mark.c:fsnotify_mark_destroy",
        "fs/quota/dquot.c:dquot_disable",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "net/core/netpoll.c:__netpoll_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579779296,
      "name": "synchronize_srcu",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void synchronize_srcu(struct srcu_struct * sp)
```

```json
{
  "name": "synchronize_srcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579804640,
      "name": "synchronize_srcu",
      "external": true,
      "loc": "kernel/rcu/srcu.c:490",
      "file": "kernel/rcu/srcu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/srcu.c:srcu_barrier",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/mark.c:fsnotify_mark_destroy_list",
        "fs/quota/dquot.c:dquot_disable",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "net/core/netpoll.c:__netpoll_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579804640,
      "name": "synchronize_srcu",
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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void synchronize_srcu(struct srcu_struct * sp)
```

```json
{
  "name": "synchronize_srcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579833024,
      "name": "synchronize_srcu",
      "external": true,
      "loc": "kernel/rcu/srcu.c:490",
      "file": "kernel/rcu/srcu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/srcu.c:srcu_barrier",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/mark.c:fsnotify_mark_destroy_list",
        "fs/quota/dquot.c:dquot_disable",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "net/core/netpoll.c:__netpoll_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579833024,
      "name": "synchronize_srcu",
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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void synchronize_srcu(struct srcu_struct * sp)
```

```json
{
  "name": "synchronize_srcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579836992,
      "name": "synchronize_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:970",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/mark.c:fsnotify_mark_destroy_workfn",
        "fs/notify/mark.c:fsnotify_connector_destroy_workfn",
        "fs/quota/dquot.c:dquot_disable",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "net/core/netpoll.c:__netpoll_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579836992,
      "name": "synchronize_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void synchronize_srcu(struct srcu_struct * sp)
```

```json
{
  "name": "synchronize_srcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579877296,
      "name": "synchronize_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:971",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/mark.c:fsnotify_mark_destroy_workfn",
        "fs/notify/mark.c:fsnotify_connector_destroy_workfn",
        "fs/quota/dquot.c:dquot_disable",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "net/core/netpoll.c:__netpoll_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579877296,
      "name": "synchronize_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
void synchronize_srcu(struct srcu_struct * sp)
```

```json
{
  "name": "synchronize_srcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579911296,
      "name": "synchronize_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:1001",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/mark.c:fsnotify_mark_destroy_workfn",
        "fs/notify/mark.c:fsnotify_connector_destroy_workfn",
        "fs/quota/dquot.c:dquot_disable",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "net/core/netpoll.c:__netpoll_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579911296,
      "name": "synchronize_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void synchronize_srcu(struct srcu_struct * ssp)
```

```json
{
  "name": "synchronize_srcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579958992,
      "name": "synchronize_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:1019",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:trigger_data_free",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/mark.c:fsnotify_mark_destroy_workfn",
        "fs/notify/mark.c:fsnotify_connector_destroy_workfn",
        "fs/quota/dquot.c:dquot_disable",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "net/core/netpoll.c:__netpoll_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579958992,
      "name": "synchronize_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void synchronize_srcu(struct srcu_struct * ssp)
```

```json
{
  "name": "synchronize_srcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579995536,
      "name": "synchronize_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:994",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:trigger_data_free",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/mark.c:fsnotify_mark_destroy_workfn",
        "fs/notify/mark.c:fsnotify_connector_destroy_workfn",
        "fs/quota/dquot.c:dquot_disable",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "net/core/netpoll.c:__netpoll_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579995536,
      "name": "synchronize_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void synchronize_srcu(struct srcu_struct * ssp)
```

```json
{
  "name": "synchronize_srcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580045664,
      "name": "synchronize_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:995",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:trigger_data_free",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/mmu_notifier.c:mmu_notifier_synchronize",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/mark.c:fsnotify_mark_destroy_workfn",
        "fs/notify/mark.c:fsnotify_connector_destroy_workfn",
        "fs/quota/dquot.c:dquot_disable",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "net/core/netpoll.c:__netpoll_cleanup",
        "net/core/drop_monitor.c:net_dm_trace_off_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580045664,
      "name": "synchronize_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void synchronize_srcu(struct srcu_struct * ssp)
```

```json
{
  "name": "synchronize_srcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580101552,
      "name": "synchronize_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:1008",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_postscan",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_free",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_free",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/mmu_notifier.c:mmu_notifier_synchronize",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:mn_hlist_release",
        "fs/notify/mark.c:fsnotify_mark_destroy_workfn",
        "fs/notify/mark.c:fsnotify_connector_destroy_workfn",
        "fs/quota/dquot.c:dquot_disable",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:__bind",
        "net/core/netpoll.c:__netpoll_cleanup",
        "net/core/drop_monitor.c:net_dm_trace_off_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580101552,
      "name": "synchronize_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void synchronize_srcu(struct srcu_struct * ssp)
```

```json
{
  "name": "synchronize_srcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580083088,
      "name": "synchronize_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:997",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_release",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_release",
        "kernel/tracepoint.c:tracepoint_remove_func",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_free",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_free",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/mmu_notifier.c:mmu_notifier_synchronize",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:mn_hlist_release",
        "fs/notify/mark.c:fsnotify_mark_destroy_workfn",
        "fs/notify/mark.c:fsnotify_connector_destroy_workfn",
        "fs/quota/dquot.c:dquot_disable",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:__bind",
        "net/core/netpoll.c:__netpoll_cleanup",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580083088,
      "name": "synchronize_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void synchronize_srcu(struct srcu_struct * ssp)
```

```json
{
  "name": "synchronize_srcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580084496,
      "name": "synchronize_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:1011",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_release",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_release",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_add_func",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_free",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_free",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/mmu_notifier.c:mmu_notifier_synchronize",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/mark.c:fsnotify_mark_destroy_workfn",
        "fs/notify/mark.c:fsnotify_connector_destroy_workfn",
        "fs/quota/dquot.c:dquot_disable",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "drivers/base/core.c:device_link_release_fn",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:__bind",
        "net/core/netpoll.c:__netpoll_cleanup",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580084496,
      "name": "synchronize_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void synchronize_srcu(struct srcu_struct * ssp)
```

```json
{
  "name": "synchronize_srcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580220912,
      "name": "synchronize_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:1006",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_release",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_release",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_free",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_free",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/mmu_notifier.c:mmu_notifier_synchronize",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/mark.c:fsnotify_mark_destroy_workfn",
        "fs/notify/mark.c:fsnotify_connector_destroy_workfn",
        "fs/quota/dquot.c:dquot_disable",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "drivers/base/core.c:device_link_release_fn",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:__bind",
        "net/core/netpoll.c:__netpoll_cleanup",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580220912,
      "name": "synchronize_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void synchronize_srcu(struct srcu_struct * ssp)
```

```json
{
  "name": "synchronize_srcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580382016,
      "name": "synchronize_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:1291",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_release",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_release",
        "kernel/rcu/update.c:rcu_tasks_postscan",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_free",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_free",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/mmu_notifier.c:mmu_notifier_synchronize",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/mark.c:fsnotify_mark_destroy_workfn",
        "fs/notify/mark.c:fsnotify_connector_destroy_workfn",
        "fs/quota/dquot.c:dquot_disable",
        "fs/proc/vmcore.c:unregister_vmcore_cb",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "drivers/base/core.c:device_link_release_fn",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/md/dm.c:dm_internal_suspend_fast",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:__bind",
        "net/core/netpoll.c:__netpoll_cleanup",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580382016,
      "name": "synchronize_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void synchronize_srcu(struct srcu_struct * ssp)
```

```json
{
  "name": "synchronize_srcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580608256,
      "name": "synchronize_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:1360",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_release",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_release",
        "kernel/printk/printk.c:console_force_preferred_locked",
        "kernel/printk/printk.c:unregister_console_locked",
        "kernel/printk/printk.c:console_stop",
        "kernel/rcu/update.c:rcu_tasks_postscan",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_free",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_free",
        "kernel/trace/rv/rv.c:monitoring_on_write_data",
        "kernel/trace/rv/rv.c:enabled_monitors_open",
        "kernel/trace/rv/rv_reactors.c:reacting_on_write_data",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/mmu_notifier.c:mmu_notifier_synchronize",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/mark.c:fsnotify_mark_destroy_workfn",
        "fs/notify/mark.c:fsnotify_connector_destroy_workfn",
        "fs/quota/dquot.c:dquot_disable",
        "fs/proc/vmcore.c:unregister_vmcore_cb",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_timeout_work",
        "block/blk-mq.c:blk_mq_quiesce_tagset",
        "drivers/base/core.c:device_link_release_fn",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/dax/super.c:kill_dax",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/md/dm.c:dm_internal_suspend_fast",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:__bind",
        "net/core/netpoll.c:__netpoll_cleanup",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580608256,
      "name": "synchronize_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
void synchronize_srcu(struct srcu_struct * ssp)
```

```json
{
  "name": "synchronize_srcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580681952,
      "name": "synchronize_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:1436",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_release",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_release",
        "kernel/notifier.c:srcu_notifier_chain_unregister",
        "kernel/printk/printk.c:console_force_preferred_locked",
        "kernel/printk/printk.c:unregister_console_locked",
        "kernel/printk/printk.c:console_stop",
        "kernel/rcu/update.c:rcu_tasks_postscan",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_free",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_free",
        "kernel/trace/rv/rv.c:monitoring_on_write_data",
        "kernel/trace/rv/rv.c:enabled_monitors_open",
        "kernel/trace/rv/rv_reactors.c:reacting_on_write_data",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/mmu_notifier.c:mmu_notifier_synchronize",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/mark.c:fsnotify_mark_destroy_workfn",
        "fs/notify/mark.c:fsnotify_connector_destroy_workfn",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:quota_release_workfn",
        "fs/proc/vmcore.c:unregister_vmcore_cb",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_timeout_work",
        "block/blk-mq.c:blk_mq_quiesce_tagset",
        "drivers/base/core.c:device_link_release_fn",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/dax/super.c:kill_dax",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/md/dm.c:dm_internal_suspend_fast",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:__bind",
        "net/core/netpoll.c:__netpoll_cleanup",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580681952,
      "name": "synchronize_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
void synchronize_srcu(struct srcu_struct * ssp)
```

```json
{
  "name": "synchronize_srcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580748736,
      "name": "synchronize_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:1456",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_release",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_release",
        "kernel/notifier.c:srcu_notifier_chain_unregister",
        "kernel/printk/printk.c:console_force_preferred_locked",
        "kernel/printk/printk.c:unregister_console_locked",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:resume_console",
        "kernel/printk/printk.c:suspend_console",
        "kernel/rcu/update.c:rcu_tasks_postscan",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_free",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_free",
        "kernel/trace/rv/rv.c:monitoring_on_write_data",
        "kernel/trace/rv/rv.c:enabled_monitors_open",
        "kernel/trace/rv/rv_reactors.c:reacting_on_write_data",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/mmu_notifier.c:mmu_notifier_synchronize",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/mark.c:fsnotify_mark_destroy_workfn",
        "fs/notify/mark.c:fsnotify_connector_destroy_workfn",
        "fs/quota/dquot.c:quota_release_workfn",
        "fs/proc/vmcore.c:unregister_vmcore_cb",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_timeout_work",
        "block/blk-mq.c:blk_mq_quiesce_tagset",
        "drivers/base/core.c:device_link_release_fn",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/dax/super.c:kill_dax",
        "drivers/gpu/drm/drm_drv.c:drm_dev_unplug",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/md/dm.c:dm_internal_suspend_fast",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:__bind",
        "net/core/netpoll.c:__netpoll_cleanup",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580748736,
      "name": "synchronize_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
void synchronize_srcu(struct srcu_struct * ssp)
```

```json
{
  "name": "synchronize_srcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491251608,
      "name": "synchronize_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:995",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/eventfd.c:kvm_unregister_irq_ack_notifier",
        "virt/kvm/eventfd.c:kvm_irqfd_assign",
        "virt/kvm/eventfd.c:irqfd_shutdown",
        "virt/kvm/eventfd.c:irqfd_resampler_shutdown",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:trigger_data_free",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/mmu_notifier.c:mmu_notifier_synchronize",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/mark.c:fsnotify_mark_destroy_workfn",
        "fs/notify/mark.c:fsnotify_connector_destroy_workfn",
        "fs/quota/dquot.c:dquot_disable",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "net/core/netpoll.c:__netpoll_cleanup",
        "net/core/drop_monitor.c:net_dm_trace_off_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491251608,
      "name": "synchronize_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
void synchronize_srcu(struct srcu_struct * ssp)
```

```json
{
  "name": "synchronize_srcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225261356,
      "name": "synchronize_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:995",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_event_perf.c:perf_trace_event_unreg",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:trigger_data_free",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/mmu_notifier.c:mmu_notifier_synchronize",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/mark.c:fsnotify_mark_destroy_workfn",
        "fs/notify/mark.c:fsnotify_connector_destroy_workfn",
        "fs/quota/dquot.c:dquot_disable",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "net/core/netpoll.c:__netpoll_cleanup",
        "net/core/drop_monitor.c:net_dm_trace_off_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225261356,
      "name": "synchronize_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void synchronize_srcu(struct srcu_struct * ssp)
```

```json
{
  "name": "synchronize_srcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284150864,
      "name": "synchronize_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:995",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_event_perf.c:perf_trace_event_unreg",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:trigger_data_free",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/mmu_notifier.c:mmu_notifier_synchronize",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/mark.c:fsnotify_mark_destroy_workfn",
        "fs/notify/mark.c:fsnotify_connector_destroy_workfn",
        "fs/quota/dquot.c:dquot_disable",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "net/core/netpoll.c:__netpoll_cleanup",
        "net/core/drop_monitor.c:net_dm_trace_off_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284150864,
      "name": "synchronize_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
void synchronize_srcu(struct srcu_struct * ssp)
```

```json
{
  "name": "synchronize_srcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271776320,
      "name": "synchronize_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:995",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_event_perf.c:perf_trace_event_unreg",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:trigger_data_free",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/mmu_notifier.c:mmu_notifier_synchronize",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/mark.c:fsnotify_mark_destroy_workfn",
        "fs/notify/mark.c:fsnotify_connector_destroy_workfn",
        "fs/quota/dquot.c:dquot_disable",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "net/core/netpoll.c:__netpoll_cleanup",
        "net/core/drop_monitor.c:net_dm_trace_off_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271776320,
      "name": "synchronize_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void synchronize_srcu(struct srcu_struct * ssp)
```

```json
{
  "name": "synchronize_srcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580014400,
      "name": "synchronize_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:995",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:trigger_data_free",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/mmu_notifier.c:mmu_notifier_synchronize",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/mark.c:fsnotify_mark_destroy_workfn",
        "fs/notify/mark.c:fsnotify_connector_destroy_workfn",
        "fs/quota/dquot.c:dquot_disable",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/nvme/host/multipath.c:nvme_mpath_set_live",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "net/core/netpoll.c:__netpoll_cleanup",
        "net/core/drop_monitor.c:net_dm_trace_off_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580014400,
      "name": "synchronize_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void synchronize_srcu(struct srcu_struct * ssp)
```

```json
{
  "name": "synchronize_srcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579953136,
      "name": "synchronize_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:995",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:trigger_data_free",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/mmu_notifier.c:mmu_notifier_synchronize",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/mark.c:fsnotify_mark_destroy_workfn",
        "fs/notify/mark.c:fsnotify_connector_destroy_workfn",
        "fs/quota/dquot.c:dquot_disable",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/nvme/host/multipath.c:nvme_mpath_set_live",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "net/core/netpoll.c:__netpoll_cleanup",
        "net/core/drop_monitor.c:net_dm_trace_off_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579953136,
      "name": "synchronize_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void synchronize_srcu(struct srcu_struct * ssp)
```

```json
{
  "name": "synchronize_srcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580005936,
      "name": "synchronize_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:995",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:trigger_data_free",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/mmu_notifier.c:mmu_notifier_synchronize",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/mark.c:fsnotify_mark_destroy_workfn",
        "fs/notify/mark.c:fsnotify_connector_destroy_workfn",
        "fs/quota/dquot.c:dquot_disable",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "net/core/netpoll.c:__netpoll_cleanup",
        "net/core/drop_monitor.c:net_dm_trace_off_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580005936,
      "name": "synchronize_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void synchronize_srcu(struct srcu_struct * ssp)
```

```json
{
  "name": "synchronize_srcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580055024,
      "name": "synchronize_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:995",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:trigger_data_free",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/events/core.c:perf_pmu_unregister",
        "mm/mmu_notifier.c:mmu_notifier_synchronize",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_release",
        "fs/notify/mark.c:fsnotify_mark_destroy_workfn",
        "fs/notify/mark.c:fsnotify_connector_destroy_workfn",
        "fs/quota/dquot.c:dquot_disable",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "net/core/netpoll.c:__netpoll_cleanup",
        "net/core/drop_monitor.c:net_dm_trace_off_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580055024,
      "name": "synchronize_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct srcu_struct * ssp</code>
</li>
<li>
<b>Param removed. </b>
<code>struct srcu_struct * sp</code>
</li>
</ul>
</details>
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
