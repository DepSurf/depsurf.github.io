# Function: <code>kernfs_path_from_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int kernfs_path_from_node(struct kernfs_node * to, struct kernfs_node * from, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_path_from_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581505008,
      "name": "kernfs_path_from_node",
      "external": true,
      "loc": "fs/kernfs/dir.c:227",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_show_options",
        "kernel/cgroup.c:cgroup_show_options",
        "fs/kernfs/dir.c:kernfs_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581505008,
      "name": "kernfs_path_from_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int kernfs_path_from_node(struct kernfs_node * to, struct kernfs_node * from, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_path_from_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581690544,
      "name": "kernfs_path_from_node",
      "external": true,
      "loc": "fs/kernfs/dir.c:226",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_show_path",
        "fs/kernfs/dir.c:kernfs_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581690544,
      "name": "kernfs_path_from_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int kernfs_path_from_node(struct kernfs_node * to, struct kernfs_node * from, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_path_from_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581778496,
      "name": "kernfs_path_from_node",
      "external": true,
      "loc": "fs/kernfs/dir.c:198",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_show_path",
        "kernel/cgroup.c:perf_trace_cgroup_migrate",
        "kernel/cgroup.c:perf_trace_cgroup_migrate",
        "kernel/cgroup.c:perf_trace_cgroup",
        "kernel/cgroup.c:perf_trace_cgroup",
        "kernel/cgroup.c:trace_event_raw_event_cgroup_migrate",
        "kernel/cgroup.c:trace_event_raw_event_cgroup_migrate",
        "kernel/cgroup.c:trace_event_raw_event_cgroup",
        "kernel/cgroup.c:trace_event_raw_event_cgroup",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_extend_slice",
        "block/blk-throttle.c:throtl_start_new_slice",
        "block/blk-throttle.c:throtl_start_new_slice_with_credit",
        "block/blk-throttle.c:throtl_schedule_pending_timer",
        "block/cfq-iosched.c:cfq_set_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:cfq_preempt_queue",
        "block/cfq-iosched.c:cfq_get_queue",
        "block/cfq-iosched.c:check_blkcg_changed",
        "block/cfq-iosched.c:check_blkcg_changed",
        "block/cfq-iosched.c:cfq_put_queue",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_request",
        "block/cfq-iosched.c:cfq_dispatch_insert",
        "block/cfq-iosched.c:cfq_arm_slice_timer",
        "block/cfq-iosched.c:cfq_arm_slice_timer",
        "block/cfq-iosched.c:cfq_should_idle",
        "block/cfq-iosched.c:__cfq_slice_expired",
        "block/cfq-iosched.c:__cfq_slice_expired",
        "block/cfq-iosched.c:__cfq_set_active_queue",
        "block/cfq-iosched.c:cfq_deactivate_request",
        "block/cfq-iosched.c:cfq_activate_request",
        "block/cfq-iosched.c:cfq_del_cfqq_rr",
        "block/cfq-iosched.c:cfq_add_cfqq_rr",
        "block/cfq-iosched.c:cfq_group_served",
        "block/cfq-iosched.c:cfq_group_served",
        "block/cfq-iosched.c:cfq_group_notify_queue_del",
        "block/cfq-iosched.c:cfq_set_prio_slice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581778496,
      "name": "kernfs_path_from_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int kernfs_path_from_node(struct kernfs_node * to, struct kernfs_node * from, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_path_from_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581833568,
      "name": "kernfs_path_from_node",
      "external": true,
      "loc": "fs/kernfs/dir.c:208",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_path_ns_locked",
        "kernel/cgroup/cgroup.c:cgroup_show_path",
        "kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate",
        "kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate",
        "kernel/cgroup/cgroup.c:perf_trace_cgroup",
        "kernel/cgroup/cgroup.c:perf_trace_cgroup",
        "kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_migrate",
        "kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_migrate",
        "kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup",
        "kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_tg_is_idle",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_extend_slice",
        "block/blk-throttle.c:throtl_start_new_slice",
        "block/blk-throttle.c:throtl_start_new_slice_with_credit",
        "block/blk-throttle.c:throtl_schedule_pending_timer",
        "block/cfq-iosched.c:cfq_set_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:cfq_preempt_queue",
        "block/cfq-iosched.c:cfq_get_queue",
        "block/cfq-iosched.c:check_blkcg_changed",
        "block/cfq-iosched.c:check_blkcg_changed",
        "block/cfq-iosched.c:cfq_put_queue",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_request",
        "block/cfq-iosched.c:cfq_dispatch_insert",
        "block/cfq-iosched.c:cfq_arm_slice_timer",
        "block/cfq-iosched.c:cfq_arm_slice_timer",
        "block/cfq-iosched.c:cfq_should_idle",
        "block/cfq-iosched.c:__cfq_slice_expired",
        "block/cfq-iosched.c:__cfq_slice_expired",
        "block/cfq-iosched.c:__cfq_set_active_queue",
        "block/cfq-iosched.c:cfq_deactivate_request",
        "block/cfq-iosched.c:cfq_activate_request",
        "block/cfq-iosched.c:cfq_del_cfqq_rr",
        "block/cfq-iosched.c:cfq_add_cfqq_rr",
        "block/cfq-iosched.c:cfq_group_served",
        "block/cfq-iosched.c:cfq_group_served",
        "block/cfq-iosched.c:cfq_group_notify_queue_del",
        "block/cfq-iosched.c:cfq_set_prio_slice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581833568,
      "name": "kernfs_path_from_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int kernfs_path_from_node(struct kernfs_node * to, struct kernfs_node * from, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_path_from_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581983024,
      "name": "kernfs_path_from_node",
      "external": true,
      "loc": "fs/kernfs/dir.c:209",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_path_ns_locked",
        "kernel/cgroup/cgroup.c:cgroup_show_path",
        "kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate",
        "kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate",
        "kernel/cgroup/cgroup.c:perf_trace_cgroup",
        "kernel/cgroup/cgroup.c:perf_trace_cgroup",
        "kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_migrate",
        "kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_migrate",
        "kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup",
        "kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup",
        "fs/sysfs/dir.c:sysfs_warn_dup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581983024,
      "name": "kernfs_path_from_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int kernfs_path_from_node(struct kernfs_node * to, struct kernfs_node * from, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_path_from_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582170480,
      "name": "kernfs_path_from_node",
      "external": true,
      "loc": "fs/kernfs/dir.c:209",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_path_ns_locked",
        "kernel/cgroup/cgroup.c:cgroup_show_path",
        "kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate",
        "kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate",
        "kernel/cgroup/cgroup.c:perf_trace_cgroup",
        "kernel/cgroup/cgroup.c:perf_trace_cgroup",
        "kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_migrate",
        "kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_migrate",
        "kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup",
        "kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup",
        "fs/sysfs/dir.c:sysfs_warn_dup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582170480,
      "name": "kernfs_path_from_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int kernfs_path_from_node(struct kernfs_node * to, struct kernfs_node * from, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_path_from_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582265552,
      "name": "kernfs_path_from_node",
      "external": true,
      "loc": "fs/kernfs/dir.c:209",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_path_ns_locked",
        "kernel/cgroup/cgroup.c:cgroup_show_path",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "fs/sysfs/dir.c:sysfs_warn_dup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582265552,
      "name": "kernfs_path_from_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int kernfs_path_from_node(struct kernfs_node * to, struct kernfs_node * from, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_path_from_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582429984,
      "name": "kernfs_path_from_node",
      "external": true,
      "loc": "fs/kernfs/dir.c:208",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_trace_cfs_rq_path",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_path_ns_locked",
        "kernel/cgroup/cgroup.c:cgroup_show_path",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "fs/sysfs/dir.c:sysfs_warn_dup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582429984,
      "name": "kernfs_path_from_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int kernfs_path_from_node(struct kernfs_node * to, struct kernfs_node * from, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_path_from_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582528768,
      "name": "kernfs_path_from_node",
      "external": true,
      "loc": "fs/kernfs/dir.c:210",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_trace_cfs_rq_path",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_path_ns_locked",
        "kernel/cgroup/cgroup.c:cgroup_show_path",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582528768,
      "name": "kernfs_path_from_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int kernfs_path_from_node(struct kernfs_node * to, struct kernfs_node * from, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_path_from_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582834240,
      "name": "kernfs_path_from_node",
      "external": true,
      "loc": "fs/kernfs/dir.c:210",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_trace_cfs_rq_path",
        "kernel/sched/debug.c:print_cfs_rq",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns",
        "kernel/cgroup/cgroup.c:cgroup_show_path",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/events/core.c:perf_event_cgroup",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582834240,
      "name": "kernfs_path_from_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int kernfs_path_from_node(struct kernfs_node * to, struct kernfs_node * from, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_path_from_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582906992,
      "name": "kernfs_path_from_node",
      "external": true,
      "loc": "fs/kernfs/dir.c:210",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_trace_cfs_rq_path",
        "kernel/sched/debug.c:print_cfs_rq",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns",
        "kernel/cgroup/cgroup.c:cgroup_show_path",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/events/core.c:perf_event_cgroup",
        "mm/mmap_lock.c:get_mm_memcg_path",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:ioc_forgive_debts",
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:iocg_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582906992,
      "name": "kernfs_path_from_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int kernfs_path_from_node(struct kernfs_node * to, struct kernfs_node * from, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_path_from_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582934784,
      "name": "kernfs_path_from_node",
      "external": true,
      "loc": "fs/kernfs/dir.c:210",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_trace_cfs_rq_path",
        "kernel/sched/debug.c:print_cfs_rq",
        "kernel/sched/debug.c:print_cfs_rq",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns",
        "kernel/cgroup/cgroup.c:cgroup_show_path",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/events/core.c:perf_event_cgroup",
        "mm/mmap_lock.c:get_mm_memcg_path",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:ioc_forgive_debts",
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:iocg_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582934784,
      "name": "kernfs_path_from_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int kernfs_path_from_node(struct kernfs_node * to, struct kernfs_node * from, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_path_from_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583269632,
      "name": "kernfs_path_from_node",
      "external": true,
      "loc": "fs/kernfs/dir.c:210",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_trace_cfs_rq_path",
        "kernel/sched/debug.c:print_cfs_rq",
        "kernel/sched/debug.c:print_cfs_rq",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns",
        "kernel/cgroup/cgroup.c:cgroup_show_path",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/events/core.c:perf_event_cgroup",
        "mm/mmap_lock.c:get_mm_memcg_path",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:ioc_forgive_debts",
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:iocg_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583269632,
      "name": "kernfs_path_from_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int kernfs_path_from_node(struct kernfs_node * to, struct kernfs_node * from, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_path_from_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583777415,
      "name": "kernfs_path_from_node",
      "external": true,
      "loc": "fs/kernfs/dir.c:217",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:pr_cont_kernfs_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns",
        "kernel/cgroup/cgroup.c:cgroup_show_path",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/events/core.c:perf_event_cgroup",
        "mm/mmap_lock.c:get_mm_memcg_path",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:ioc_forgive_debts",
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:iocg_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583772944,
      "name": "kernfs_path_from_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int kernfs_path_from_node(struct kernfs_node * to, struct kernfs_node * from, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_path_from_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584395431,
      "name": "kernfs_path_from_node",
      "external": true,
      "loc": "fs/kernfs/dir.c:224",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:pr_cont_kernfs_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_path_ns",
        "kernel/cgroup/cgroup.c:cgroup_show_path",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/events/core.c:perf_event_cgroup",
        "mm/vmscan.c:lru_gen_seq_show",
        "mm/mmap_lock.c:get_mm_memcg_path",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:ioc_forgive_debts",
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:iocg_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584390496,
      "name": "kernfs_path_from_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int kernfs_path_from_node(struct kernfs_node * to, struct kernfs_node * from, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_path_from_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584623863,
      "name": "kernfs_path_from_node",
      "external": true,
      "loc": "fs/kernfs/dir.c:221",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:pr_cont_kernfs_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_path_ns",
        "kernel/cgroup/cgroup.c:cgroup_show_path",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/events/core.c:perf_event_cgroup",
        "mm/vmscan.c:lru_gen_seq_show",
        "mm/mmap_lock.c:get_mm_memcg_path",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:ioc_forgive_debts",
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:iocg_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584618880,
      "name": "kernfs_path_from_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int kernfs_path_from_node(struct kernfs_node * to, struct kernfs_node * from, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_path_from_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584856359,
      "name": "kernfs_path_from_node",
      "external": true,
      "loc": "fs/kernfs/dir.c:223",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:pr_cont_kernfs_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_path_ns_locked",
        "kernel/cgroup/cgroup.c:cgroup_show_path",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/events/core.c:perf_event_cgroup",
        "mm/vmscan.c:lru_gen_seq_show",
        "mm/mmap_lock.c:get_mm_memcg_path",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:ioc_forgive_debts",
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:iocg_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584851040,
      "name": "kernfs_path_from_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int kernfs_path_from_node(struct kernfs_node * to, struct kernfs_node * from, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_path_from_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494164080,
      "name": "kernfs_path_from_node",
      "external": true,
      "loc": "fs/kernfs/dir.c:210",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_trace_cfs_rq_path",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_path_ns_locked",
        "kernel/cgroup/cgroup.c:cgroup_show_path",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494164080,
      "name": "kernfs_path_from_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int kernfs_path_from_node(struct kernfs_node * to, struct kernfs_node * from, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_path_from_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227601424,
      "name": "kernfs_path_from_node",
      "external": true,
      "loc": "fs/kernfs/dir.c:210",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_trace_cfs_rq_path",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_path_ns_locked",
        "kernel/cgroup/cgroup.c:cgroup_show_path",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227601424,
      "name": "kernfs_path_from_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int kernfs_path_from_node(struct kernfs_node * to, struct kernfs_node * from, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_path_from_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287841808,
      "name": "kernfs_path_from_node",
      "external": true,
      "loc": "fs/kernfs/dir.c:210",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_trace_cfs_rq_path",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_path_ns_locked",
        "kernel/cgroup/cgroup.c:cgroup_show_path",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287841808,
      "name": "kernfs_path_from_node",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int kernfs_path_from_node(struct kernfs_node * to, struct kernfs_node * from, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_path_from_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273630694,
      "name": "kernfs_path_from_node",
      "external": true,
      "loc": "fs/kernfs/dir.c:210",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_trace_cfs_rq_path",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_path_ns_locked",
        "kernel/cgroup/cgroup.c:cgroup_show_path",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273630694,
      "name": "kernfs_path_from_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int kernfs_path_from_node(struct kernfs_node * to, struct kernfs_node * from, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_path_from_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582497504,
      "name": "kernfs_path_from_node",
      "external": true,
      "loc": "fs/kernfs/dir.c:210",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_trace_cfs_rq_path",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_path_ns_locked",
        "kernel/cgroup/cgroup.c:cgroup_show_path",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582497504,
      "name": "kernfs_path_from_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int kernfs_path_from_node(struct kernfs_node * to, struct kernfs_node * from, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_path_from_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582434736,
      "name": "kernfs_path_from_node",
      "external": true,
      "loc": "fs/kernfs/dir.c:210",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_trace_cfs_rq_path",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_path_ns_locked",
        "kernel/cgroup/cgroup.c:cgroup_show_path",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582434736,
      "name": "kernfs_path_from_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int kernfs_path_from_node(struct kernfs_node * to, struct kernfs_node * from, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_path_from_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582487984,
      "name": "kernfs_path_from_node",
      "external": true,
      "loc": "fs/kernfs/dir.c:210",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_trace_cfs_rq_path",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_path_ns_locked",
        "kernel/cgroup/cgroup.c:cgroup_show_path",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582487984,
      "name": "kernfs_path_from_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int kernfs_path_from_node(struct kernfs_node * to, struct kernfs_node * from, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_path_from_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582568544,
      "name": "kernfs_path_from_node",
      "external": true,
      "loc": "fs/kernfs/dir.c:210",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_trace_cfs_rq_path",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_path_ns_locked",
        "kernel/cgroup/cgroup.c:cgroup_show_path",
        "kernel/cgroup/cgroup.c:cgroup_update_populated",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582568544,
      "name": "kernfs_path_from_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
