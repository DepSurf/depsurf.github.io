# Function: <code>kernfs_path</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
char * kernfs_path(struct kernfs_node * kn, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581505104,
      "name": "kernfs_path",
      "external": true,
      "loc": "fs/kernfs/dir.c:251",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_balance_dirty_pages",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/sysfs/dir.c:sysfs_warn_dup",
        "block/blk-throttle.c:throtl_schedule_pending_timer",
        "block/blk-throttle.c:throtl_extend_slice",
        "block/blk-throttle.c:throtl_start_new_slice",
        "block/blk-throttle.c:throtl_start_new_slice_with_credit",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/cfq-iosched.c:cfq_set_prio_slice",
        "block/cfq-iosched.c:cfq_activate_request",
        "block/cfq-iosched.c:cfq_deactivate_request",
        "block/cfq-iosched.c:cfq_check_fifo",
        "block/cfq-iosched.c:cfq_add_cfqq_rr",
        "block/cfq-iosched.c:cfq_dispatch_insert",
        "block/cfq-iosched.c:__cfq_set_active_queue",
        "block/cfq-iosched.c:cfq_group_notify_queue_del",
        "block/cfq-iosched.c:cfq_del_cfqq_rr",
        "block/cfq-iosched.c:cfq_group_served",
        "block/cfq-iosched.c:cfq_group_served",
        "block/cfq-iosched.c:cfq_should_idle",
        "block/cfq-iosched.c:cfq_get_queue",
        "block/cfq-iosched.c:__cfq_slice_expired",
        "block/cfq-iosched.c:__cfq_slice_expired",
        "block/cfq-iosched.c:cfq_preempt_queue",
        "block/cfq-iosched.c:cfq_put_queue",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:check_blkcg_changed",
        "block/cfq-iosched.c:check_blkcg_changed",
        "block/cfq-iosched.c:cfq_set_request",
        "block/cfq-iosched.c:cfq_arm_slice_timer",
        "block/cfq-iosched.c:cfq_arm_slice_timer",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_completed_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581505104,
      "name": "kernfs_path",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
char * kernfs_path(struct kernfs_node * kn, char * buf, size_t buflen)
```

```json
{
  "name": "kernfs_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581690640,
      "name": "kernfs_path",
      "external": true,
      "loc": "fs/kernfs/dir.c:250",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "block/cfq-iosched.c:cfq_check_fifo",
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
      "addr": 18446744071581690640,
      "name": "kernfs_path",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kernfs_path",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579698485,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:446",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580036416,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:446",
      "file": "kernel/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:perf_trace_cgroup_migrate",
        "kernel/cgroup.c:perf_trace_cgroup_migrate",
        "kernel/cgroup.c:perf_trace_cgroup",
        "kernel/cgroup.c:perf_trace_cgroup",
        "kernel/cgroup.c:trace_event_raw_event_cgroup_migrate",
        "kernel/cgroup.c:trace_event_raw_event_cgroup_migrate",
        "kernel/cgroup.c:trace_event_raw_event_cgroup",
        "kernel/cgroup.c:trace_event_raw_event_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581792834,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:446",
      "file": "fs/sysfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/sysfs/dir.c:sysfs_warn_dup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583288677,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:446",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_extend_slice",
        "block/blk-throttle.c:throtl_start_new_slice",
        "block/blk-throttle.c:throtl_start_new_slice_with_credit",
        "block/blk-throttle.c:throtl_schedule_pending_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583320991,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:446",
      "file": "block/cfq-iosched.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kernfs_path",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579694501,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:456",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580036961,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:456",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate",
        "kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate",
        "kernel/cgroup/cgroup.c:perf_trace_cgroup",
        "kernel/cgroup/cgroup.c:perf_trace_cgroup",
        "kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_migrate",
        "kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_migrate",
        "kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup",
        "kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581847874,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:456",
      "file": "fs/sysfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/sysfs/dir.c:sysfs_warn_dup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583350839,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:456",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_tg_is_idle",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_extend_slice",
        "block/blk-throttle.c:throtl_start_new_slice",
        "block/blk-throttle.c:throtl_start_new_slice_with_credit",
        "block/blk-throttle.c:throtl_schedule_pending_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583381991,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:456",
      "file": "block/cfq-iosched.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kernfs_path",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579725557,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:480",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580108779,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:480",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate",
        "kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate",
        "kernel/cgroup/cgroup.c:perf_trace_cgroup",
        "kernel/cgroup/cgroup.c:perf_trace_cgroup",
        "kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_migrate",
        "kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_migrate",
        "kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup",
        "kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581997682,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:480",
      "file": "fs/sysfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/sysfs/dir.c:sysfs_warn_dup"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kernfs_path",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579756994,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:485",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580167947,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:485",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate",
        "kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate",
        "kernel/cgroup/cgroup.c:perf_trace_cgroup",
        "kernel/cgroup/cgroup.c:perf_trace_cgroup",
        "kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_migrate",
        "kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_migrate",
        "kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup",
        "kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582185670,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:485",
      "file": "fs/sysfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/sysfs/dir.c:sysfs_warn_dup"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kernfs_path",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579799874,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:486",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580215867,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:486",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580225098,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:486",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582280806,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:486",
      "file": "fs/sysfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/sysfs/dir.c:sysfs_warn_dup"
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
  "name": "kernfs_path",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579723015,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:514",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:sched_trace_cfs_rq_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579827986,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:514",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580263836,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:514",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_update_populated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580271865,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:514",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580280111,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:514",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582445479,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:514",
      "file": "fs/sysfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/sysfs/dir.c:sysfs_warn_dup"
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
  "name": "kernfs_path",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579765639,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:sched_trace_cfs_rq_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579876690,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580312140,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_update_populated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580320921,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580328271,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582544679,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "fs/sysfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/sysfs/dir.c:sysfs_warn_dup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584168733,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn"
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
  "name": "kernfs_path",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579799737,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:540",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:sched_trace_cfs_rq_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579923333,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:540",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:print_cfs_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580382172,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:540",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_update_populated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580393241,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:540",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580400799,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:540",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581153722,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:540",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582851063,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:540",
      "file": "fs/sysfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/sysfs/dir.c:sysfs_warn_dup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584566454,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:540",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_activate"
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
  "name": "kernfs_path",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579790953,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:540",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:sched_trace_cfs_rq_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579917205,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:540",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:print_cfs_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580369084,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:540",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_update_populated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580380288,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:540",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580388079,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:540",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581194122,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:540",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581556572,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:540",
      "file": "mm/mmap_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap_lock.c:get_mm_memcg_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582924103,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:540",
      "file": "fs/sysfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/sysfs/dir.c:sysfs_warn_dup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584679003,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:540",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:ioc_forgive_debts",
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:iocg_activate"
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
  "name": "kernfs_path",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579799321,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:540",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:sched_trace_cfs_rq_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579926452,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:540",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:print_cfs_rq",
        "kernel/sched/debug.c:print_cfs_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580372108,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:540",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_update_populated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580382921,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:540",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580391007,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:540",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581213178,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:540",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581579385,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:540",
      "file": "mm/mmap_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap_lock.c:get_mm_memcg_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582951751,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:540",
      "file": "fs/sysfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/sysfs/dir.c:sysfs_warn_dup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584707083,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:540",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:ioc_forgive_debts",
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:iocg_activate"
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
  "name": "kernfs_path",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579895353,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:545",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:sched_trace_cfs_rq_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580049647,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:545",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:print_cfs_rq",
        "kernel/sched/debug.c:print_cfs_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580532652,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:545",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_update_populated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580544568,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:545",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580553084,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:545",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581453066,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:545",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581844329,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:545",
      "file": "mm/mmap_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap_lock.c:get_mm_memcg_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583286983,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:545",
      "file": "fs/sysfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/sysfs/dir.c:sysfs_warn_dup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585130532,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:545",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:ioc_forgive_debts",
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:iocg_activate"
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
  "name": "kernfs_path",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580156680,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:529",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580729963,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:529",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_update_populated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580743121,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:529",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580751801,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:529",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581799221,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:529",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582237401,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:529",
      "file": "mm/mmap_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap_lock.c:get_mm_memcg_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583792454,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:529",
      "file": "fs/sysfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/sysfs/dir.c:sysfs_warn_dup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585865604,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:529",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:ioc_forgive_debts",
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:iocg_activate"
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
  "name": "kernfs_path",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580330568,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:589",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581005739,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:589",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_update_populated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581021185,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:589",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581029273,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:589",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582223141,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:589",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582511455,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:589",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:lru_gen_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582727705,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:589",
      "file": "mm/mmap_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap_lock.c:get_mm_memcg_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584412194,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:589",
      "file": "fs/sysfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/sysfs/dir.c:sysfs_warn_dup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586646977,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:589",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:ioc_forgive_debts",
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:iocg_activate"
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
  "name": "kernfs_path",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580397912,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:593",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581094331,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:593",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_update_populated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581109521,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:593",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581117641,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:593",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582424021,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:593",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582713609,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:593",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:lru_gen_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582943081,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:593",
      "file": "mm/mmap_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap_lock.c:get_mm_memcg_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584640754,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:593",
      "file": "fs/sysfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/sysfs/dir.c:sysfs_warn_dup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586908042,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:593",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:ioc_forgive_debts",
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:iocg_activate"
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
  "name": "kernfs_path",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580453640,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:594",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581191851,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:594",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_update_populated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581207393,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:594",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581215881,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:594",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen",
        "kernel/cgroup/freezer.c:cgroup_propagate_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582591716,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:594",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582882846,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:594",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:lru_gen_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583118329,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:594",
      "file": "mm/mmap_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap_lock.c:get_mm_memcg_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584873089,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:594",
      "file": "fs/sysfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/sysfs/dir.c:sysfs_warn_dup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587186074,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:594",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:ioc_forgive_debts",
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:iocg_activate"
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
  "name": "kernfs_path",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490944892,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:sched_trace_cfs_rq_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491075036,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491564876,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_update_populated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491579228,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491588396,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494182660,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "fs/sysfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/sysfs/dir.c:sysfs_warn_dup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496021416,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn"
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
  "name": "kernfs_path",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224965280,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:sched_trace_cfs_rq_path"
      ],
      "caller_func": []
    },
    {
      "addr": 3225077436,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225529196,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_update_populated"
      ],
      "caller_func": []
    },
    {
      "addr": 3225540876,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 3225549032,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 3227619576,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "fs/sysfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/sysfs/dir.c:sysfs_warn_dup"
      ],
      "caller_func": []
    },
    {
      "addr": 3229364924,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_activate"
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
  "name": "kernfs_path",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283805180,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:sched_trace_cfs_rq_path"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283959880,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284542960,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_update_populated"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284556524,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284570424,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287870564,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "fs/sysfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/sysfs/dir.c:sysfs_warn_dup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290255184,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn"
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
  "name": "kernfs_path",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271576976,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:sched_trace_cfs_rq_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271665954,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271978378,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_update_populated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271987928,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271995894,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273647232,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "fs/sysfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/sysfs/dir.c:sysfs_warn_dup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275113306,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn"
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
  "name": "kernfs_path",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579741495,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:sched_trace_cfs_rq_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579848834,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580280940,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_update_populated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580289721,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580297071,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582513415,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "fs/sysfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/sysfs/dir.c:sysfs_warn_dup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584137469,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn"
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
  "name": "kernfs_path",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579671879,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:sched_trace_cfs_rq_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579783746,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580228380,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_update_populated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580237097,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580244415,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582450583,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "fs/sysfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/sysfs/dir.c:sysfs_warn_dup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584073013,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn"
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
  "name": "kernfs_path",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579726007,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:sched_trace_cfs_rq_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579837058,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580272188,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_update_populated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580280969,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580288319,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582503895,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "fs/sysfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/sysfs/dir.c:sysfs_warn_dup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584121229,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn"
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
  "name": "kernfs_path",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579773543,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:sched_trace_cfs_rq_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579882098,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580325724,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_update_populated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580335289,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580342431,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582584503,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "fs/sysfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/sysfs/dir.c:sysfs_warn_dup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584216259,
      "name": "kernfs_path",
      "external": false,
      "loc": "include/linux/kernfs.h:515",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
char * kernfs_path(struct kernfs_node * kn, char * buf, size_t buflen)
```
</details>
</li>
</ul>
