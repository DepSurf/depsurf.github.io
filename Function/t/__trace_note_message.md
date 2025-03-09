# Function: <code>__trace_note_message</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __trace_note_message(struct blk_trace * bt, const char * fmt, void (anon))
```

```json
{
  "name": "__trace_note_message",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580273984,
      "name": "__trace_note_message",
      "external": true,
      "loc": "kernel/trace/blktrace.c:143",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_msg_write",
        "block/elevator.c:__elevator_change",
        "block/blk-throttle.c:throtl_schedule_pending_timer",
        "block/blk-throttle.c:throtl_schedule_pending_timer",
        "block/blk-throttle.c:throtl_extend_slice",
        "block/blk-throttle.c:throtl_extend_slice",
        "block/blk-throttle.c:throtl_start_new_slice",
        "block/blk-throttle.c:throtl_start_new_slice",
        "block/blk-throttle.c:throtl_start_new_slice_with_credit",
        "block/blk-throttle.c:throtl_start_new_slice_with_credit",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:blk_throtl_bio",
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
        "block/cfq-iosched.c:cfq_idle_slice_timer",
        "block/cfq-iosched.c:cfq_idle_slice_timer",
        "block/cfq-iosched.c:cfq_put_queue",
        "block/cfq-iosched.c:cfq_put_queue",
        "block/cfq-iosched.c:cfq_exit_cfqq",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:check_blkcg_changed",
        "block/cfq-iosched.c:check_blkcg_changed",
        "block/cfq-iosched.c:cfq_set_request",
        "block/cfq-iosched.c:cfq_arm_slice_timer",
        "block/cfq-iosched.c:cfq_arm_slice_timer",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_completed_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580273984,
      "name": "__trace_note_message",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __trace_note_message(struct blk_trace * bt, const char * fmt, void (anon))
```

```json
{
  "name": "__trace_note_message",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580317440,
      "name": "__trace_note_message",
      "external": true,
      "loc": "kernel/trace/blktrace.c:144",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_msg_write",
        "block/elevator.c:__elevator_change",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_extend_slice",
        "block/blk-throttle.c:throtl_extend_slice",
        "block/blk-throttle.c:throtl_start_new_slice",
        "block/blk-throttle.c:throtl_start_new_slice",
        "block/blk-throttle.c:throtl_start_new_slice_with_credit",
        "block/blk-throttle.c:throtl_start_new_slice_with_credit",
        "block/blk-throttle.c:throtl_schedule_pending_timer",
        "block/blk-throttle.c:throtl_schedule_pending_timer",
        "block/cfq-iosched.c:cfq_idle_slice_timer",
        "block/cfq-iosched.c:cfq_idle_slice_timer",
        "block/cfq-iosched.c:cfq_set_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:cfq_preempt_queue",
        "block/cfq-iosched.c:cfq_get_queue",
        "block/cfq-iosched.c:check_blkcg_changed",
        "block/cfq-iosched.c:check_blkcg_changed",
        "block/cfq-iosched.c:cfq_exit_cfqq",
        "block/cfq-iosched.c:cfq_put_queue",
        "block/cfq-iosched.c:cfq_put_queue",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests",
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
      "addr": 18446744071580317440,
      "name": "__trace_note_message",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void __trace_note_message(struct blk_trace * bt, const char * fmt, void (anon))
```

```json
{
  "name": "__trace_note_message",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580363600,
      "name": "__trace_note_message",
      "external": true,
      "loc": "kernel/trace/blktrace.c:144",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_msg_write",
        "block/elevator.c:__elevator_change",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_extend_slice",
        "block/blk-throttle.c:throtl_extend_slice",
        "block/blk-throttle.c:throtl_start_new_slice",
        "block/blk-throttle.c:throtl_start_new_slice",
        "block/blk-throttle.c:throtl_start_new_slice_with_credit",
        "block/blk-throttle.c:throtl_start_new_slice_with_credit",
        "block/blk-throttle.c:throtl_schedule_pending_timer",
        "block/blk-throttle.c:throtl_schedule_pending_timer",
        "block/cfq-iosched.c:cfq_idle_slice_timer",
        "block/cfq-iosched.c:cfq_idle_slice_timer",
        "block/cfq-iosched.c:cfq_set_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:cfq_preempt_queue",
        "block/cfq-iosched.c:cfq_get_queue",
        "block/cfq-iosched.c:check_blkcg_changed",
        "block/cfq-iosched.c:check_blkcg_changed",
        "block/cfq-iosched.c:cfq_exit_cfqq",
        "block/cfq-iosched.c:cfq_put_queue",
        "block/cfq-iosched.c:cfq_put_queue",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests",
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
        "block/cfq-iosched.c:cfq_set_prio_slice",
        "drivers/md/bitmap.c:bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580363600,
      "name": "__trace_note_message",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void __trace_note_message(struct blk_trace * bt, const char * fmt, void (anon))
```

```json
{
  "name": "__trace_note_message",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580376672,
      "name": "__trace_note_message",
      "external": true,
      "loc": "kernel/trace/blktrace.c:146",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_msg_write",
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_switch",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_tg_is_idle",
        "block/blk-throttle.c:throtl_tg_is_idle",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_extend_slice",
        "block/blk-throttle.c:throtl_extend_slice",
        "block/blk-throttle.c:throtl_start_new_slice",
        "block/blk-throttle.c:throtl_start_new_slice",
        "block/blk-throttle.c:throtl_start_new_slice_with_credit",
        "block/blk-throttle.c:throtl_start_new_slice_with_credit",
        "block/blk-throttle.c:throtl_schedule_pending_timer",
        "block/blk-throttle.c:throtl_schedule_pending_timer",
        "block/cfq-iosched.c:cfq_idle_slice_timer",
        "block/cfq-iosched.c:cfq_idle_slice_timer",
        "block/cfq-iosched.c:cfq_set_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:cfq_preempt_queue",
        "block/cfq-iosched.c:cfq_get_queue",
        "block/cfq-iosched.c:check_blkcg_changed",
        "block/cfq-iosched.c:check_blkcg_changed",
        "block/cfq-iosched.c:cfq_exit_cfqq",
        "block/cfq-iosched.c:cfq_put_queue",
        "block/cfq-iosched.c:cfq_put_queue",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests",
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
        "block/cfq-iosched.c:cfq_set_prio_slice",
        "drivers/md/bitmap.c:bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580376672,
      "name": "__trace_note_message",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void __trace_note_message(struct blk_trace * bt, struct blkcg * blkcg, const char * fmt, void (anon))
```

```json
{
  "name": "__trace_note_message",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580431824,
      "name": "__trace_note_message",
      "external": true,
      "loc": "kernel/trace/blktrace.c:158",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_msg_write",
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_switch",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_tg_is_idle",
        "block/blk-throttle.c:throtl_tg_is_idle",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/cfq-iosched.c:cfq_idle_slice_timer",
        "block/cfq-iosched.c:cfq_idle_slice_timer",
        "block/cfq-iosched.c:cfq_set_request",
        "block/cfq-iosched.c:cfq_set_request",
        "block/cfq-iosched.c:cfq_set_request",
        "block/cfq-iosched.c:cfq_set_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:cfq_get_queue",
        "block/cfq-iosched.c:cfq_exit_cfqq",
        "block/cfq-iosched.c:cfq_put_queue",
        "block/cfq-iosched.c:cfq_put_queue",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_insert",
        "block/cfq-iosched.c:cfq_should_idle",
        "block/cfq-iosched.c:__cfq_slice_expired",
        "block/cfq-iosched.c:__cfq_slice_expired",
        "block/cfq-iosched.c:__cfq_slice_expired",
        "block/cfq-iosched.c:__cfq_slice_expired",
        "block/cfq-iosched.c:__cfq_set_active_queue",
        "block/cfq-iosched.c:cfq_deactivate_request",
        "block/cfq-iosched.c:cfq_activate_request",
        "block/cfq-iosched.c:cfq_add_rq_rb",
        "block/cfq-iosched.c:cfq_del_cfqq_rr",
        "block/cfq-iosched.c:cfq_del_cfqq_rr",
        "drivers/md/md-bitmap.c:bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580431824,
      "name": "__trace_note_message",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
void __trace_note_message(struct blk_trace * bt, struct blkcg * blkcg, const char * fmt, void (anon))
```

```json
{
  "name": "__trace_note_message",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580493152,
      "name": "__trace_note_message",
      "external": true,
      "loc": "kernel/trace/blktrace.c:158",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_msg_write",
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_switch",
        "block/elevator.c:elevator_switch",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_tg_is_idle",
        "block/blk-throttle.c:throtl_tg_is_idle",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/cfq-iosched.c:cfq_idle_slice_timer",
        "block/cfq-iosched.c:cfq_idle_slice_timer",
        "block/cfq-iosched.c:cfq_set_request",
        "block/cfq-iosched.c:cfq_set_request",
        "block/cfq-iosched.c:cfq_set_request",
        "block/cfq-iosched.c:cfq_set_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:cfq_get_queue",
        "block/cfq-iosched.c:cfq_exit_cfqq",
        "block/cfq-iosched.c:cfq_put_queue",
        "block/cfq-iosched.c:cfq_put_queue",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_insert",
        "block/cfq-iosched.c:cfq_should_idle",
        "block/cfq-iosched.c:__cfq_slice_expired",
        "block/cfq-iosched.c:__cfq_slice_expired",
        "block/cfq-iosched.c:__cfq_slice_expired",
        "block/cfq-iosched.c:__cfq_slice_expired",
        "block/cfq-iosched.c:__cfq_set_active_queue",
        "block/cfq-iosched.c:cfq_deactivate_request",
        "block/cfq-iosched.c:cfq_activate_request",
        "block/cfq-iosched.c:cfq_add_rq_rb",
        "block/cfq-iosched.c:cfq_del_cfqq_rr",
        "block/cfq-iosched.c:cfq_del_cfqq_rr",
        "drivers/md/md-bitmap.c:bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580493152,
      "name": "__trace_note_message",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
void __trace_note_message(struct blk_trace * bt, struct blkcg * blkcg, const char * fmt, void (anon))
```

```json
{
  "name": "__trace_note_message",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580549072,
      "name": "__trace_note_message",
      "external": true,
      "loc": "kernel/trace/blktrace.c:146",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_msg_write",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_tg_is_idle",
        "block/blk-throttle.c:throtl_tg_is_idle",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580549072,
      "name": "__trace_note_message",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
void __trace_note_message(struct blk_trace * bt, struct blkcg * blkcg, const char * fmt, void (anon))
```

```json
{
  "name": "__trace_note_message",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580605728,
      "name": "__trace_note_message",
      "external": true,
      "loc": "kernel/trace/blktrace.c:146",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_msg_write",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_tg_is_idle",
        "block/blk-throttle.c:throtl_tg_is_idle",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580605728,
      "name": "__trace_note_message",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
void __trace_note_message(struct blk_trace * bt, struct blkcg * blkcg, const char * fmt, void (anon))
```

```json
{
  "name": "__trace_note_message",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580652992,
      "name": "__trace_note_message",
      "external": true,
      "loc": "kernel/trace/blktrace.c:146",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_msg_write",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_tg_is_idle",
        "block/blk-throttle.c:throtl_tg_is_idle",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580652992,
      "name": "__trace_note_message",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
void __trace_note_message(struct blk_trace * bt, struct blkcg * blkcg, const char * fmt, void (anon))
```

```json
{
  "name": "__trace_note_message",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580752288,
      "name": "__trace_note_message",
      "external": true,
      "loc": "kernel/trace/blktrace.c:148",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_msg_write",
        "block/elevator.c:elevator_switch_mq",
        "block/elevator.c:elevator_switch_mq",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_tg_is_idle",
        "block/blk-throttle.c:throtl_tg_is_idle",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_trim_slice",
        "block/blk-throttle.c:throtl_trim_slice",
        "block/blk-throttle.c:throtl_extend_slice",
        "block/blk-throttle.c:throtl_extend_slice",
        "block/blk-throttle.c:throtl_start_new_slice",
        "block/blk-throttle.c:throtl_start_new_slice",
        "block/blk-throttle.c:throtl_start_new_slice_with_credit",
        "block/blk-throttle.c:throtl_start_new_slice_with_credit",
        "block/blk-throttle.c:throtl_schedule_pending_timer",
        "block/blk-throttle.c:throtl_schedule_pending_timer",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580752288,
      "name": "__trace_note_message",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
void __trace_note_message(struct blk_trace * bt, struct blkcg * blkcg, const char * fmt, void (anon))
```

```json
{
  "name": "__trace_note_message",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580742080,
      "name": "__trace_note_message",
      "external": true,
      "loc": "kernel/trace/blktrace.c:148",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_msg_write",
        "block/elevator.c:elevator_switch_mq",
        "block/elevator.c:elevator_switch_mq",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:throtl_downgrade_state",
        "block/blk-throttle.c:throtl_downgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_tg_is_idle",
        "block/blk-throttle.c:throtl_tg_is_idle",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_trim_slice",
        "block/blk-throttle.c:throtl_trim_slice",
        "block/blk-throttle.c:throtl_extend_slice",
        "block/blk-throttle.c:throtl_extend_slice",
        "block/blk-throttle.c:throtl_start_new_slice",
        "block/blk-throttle.c:throtl_start_new_slice",
        "block/blk-throttle.c:throtl_start_new_slice_with_credit",
        "block/blk-throttle.c:throtl_start_new_slice_with_credit",
        "block/blk-throttle.c:throtl_schedule_pending_timer",
        "block/blk-throttle.c:throtl_schedule_pending_timer",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580742080,
      "name": "__trace_note_message",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
void __trace_note_message(struct blk_trace * bt, struct blkcg * blkcg, const char * fmt, void (anon))
```

```json
{
  "name": "__trace_note_message",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580744704,
      "name": "__trace_note_message",
      "external": true,
      "loc": "kernel/trace/blktrace.c:148",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_msg_write",
        "block/elevator.c:elevator_switch_mq",
        "block/elevator.c:elevator_switch_mq",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_tg_is_idle",
        "block/blk-throttle.c:throtl_tg_is_idle",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_trim_slice",
        "block/blk-throttle.c:throtl_trim_slice",
        "block/blk-throttle.c:throtl_extend_slice",
        "block/blk-throttle.c:throtl_extend_slice",
        "block/blk-throttle.c:throtl_start_new_slice",
        "block/blk-throttle.c:throtl_start_new_slice",
        "block/blk-throttle.c:throtl_start_new_slice_with_credit",
        "block/blk-throttle.c:throtl_start_new_slice_with_credit",
        "block/blk-throttle.c:throtl_schedule_pending_timer",
        "block/blk-throttle.c:throtl_schedule_pending_timer",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580744704,
      "name": "__trace_note_message",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
void __trace_note_message(struct blk_trace * bt, struct blkcg * blkcg, const char * fmt, void (anon))
```

```json
{
  "name": "__trace_note_message",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__trace_note_message",
      "external": true,
      "loc": "kernel/trace/blktrace.c:148",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_msg_write",
        "block/elevator.c:elevator_switch_mq",
        "block/elevator.c:elevator_switch_mq",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:throtl_downgrade_check",
        "block/blk-throttle.c:throtl_downgrade_check",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_tg_is_idle",
        "block/blk-throttle.c:throtl_tg_is_idle",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_trim_slice",
        "block/blk-throttle.c:throtl_trim_slice",
        "block/blk-throttle.c:throtl_extend_slice",
        "block/blk-throttle.c:throtl_extend_slice",
        "block/blk-throttle.c:throtl_start_new_slice",
        "block/blk-throttle.c:throtl_start_new_slice",
        "block/blk-throttle.c:throtl_start_new_slice_with_credit",
        "block/blk-throttle.c:throtl_start_new_slice_with_credit",
        "block/blk-throttle.c:throtl_schedule_pending_timer",
        "block/blk-throttle.c:throtl_schedule_pending_timer",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592173818,
      "name": "__trace_note_message.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071580927216,
      "name": "__trace_note_message",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void __trace_note_message(struct blk_trace * bt, struct blkcg * blkcg, const char * fmt, void (anon))
```

```json
{
  "name": "__trace_note_message",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491951480,
      "name": "__trace_note_message",
      "external": true,
      "loc": "kernel/trace/blktrace.c:146",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_msg_write",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_tg_is_idle",
        "block/blk-throttle.c:throtl_tg_is_idle",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491951480,
      "name": "__trace_note_message",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
void __trace_note_message(struct blk_trace * bt, struct blkcg * blkcg, const char * fmt, void (anon))
```

```json
{
  "name": "__trace_note_message",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225888768,
      "name": "__trace_note_message",
      "external": true,
      "loc": "kernel/trace/blktrace.c:146",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_msg_write",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:throtl_downgrade_check",
        "block/blk-throttle.c:throtl_downgrade_check",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_tg_is_idle",
        "block/blk-throttle.c:throtl_tg_is_idle",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225888768,
      "name": "__trace_note_message",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void __trace_note_message(struct blk_trace * bt, struct blkcg * blkcg, const char * fmt, void (anon))
```

```json
{
  "name": "__trace_note_message",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285058048,
      "name": "__trace_note_message",
      "external": true,
      "loc": "kernel/trace/blktrace.c:146",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_msg_write",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_tg_is_idle",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285058048,
      "name": "__trace_note_message",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
void __trace_note_message(struct blk_trace * bt, struct blkcg * blkcg, const char * fmt, void (anon))
```

```json
{
  "name": "__trace_note_message",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272227738,
      "name": "__trace_note_message",
      "external": true,
      "loc": "kernel/trace/blktrace.c:146",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_msg_write",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_tg_is_idle",
        "block/blk-throttle.c:throtl_tg_is_idle",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272227738,
      "name": "__trace_note_message",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
void __trace_note_message(struct blk_trace * bt, struct blkcg * blkcg, const char * fmt, void (anon))
```

```json
{
  "name": "__trace_note_message",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580621792,
      "name": "__trace_note_message",
      "external": true,
      "loc": "kernel/trace/blktrace.c:146",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_msg_write",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_tg_is_idle",
        "block/blk-throttle.c:throtl_tg_is_idle",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580621792,
      "name": "__trace_note_message",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
void __trace_note_message(struct blk_trace * bt, struct blkcg * blkcg, const char * fmt, void (anon))
```

```json
{
  "name": "__trace_note_message",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580564624,
      "name": "__trace_note_message",
      "external": true,
      "loc": "kernel/trace/blktrace.c:146",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_msg_write",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_tg_is_idle",
        "block/blk-throttle.c:throtl_tg_is_idle",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580564624,
      "name": "__trace_note_message",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
void __trace_note_message(struct blk_trace * bt, struct blkcg * blkcg, const char * fmt, void (anon))
```

```json
{
  "name": "__trace_note_message",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580613040,
      "name": "__trace_note_message",
      "external": true,
      "loc": "kernel/trace/blktrace.c:146",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_msg_write",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_tg_is_idle",
        "block/blk-throttle.c:throtl_tg_is_idle",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580613040,
      "name": "__trace_note_message",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
void __trace_note_message(struct blk_trace * bt, struct blkcg * blkcg, const char * fmt, void (anon))
```

```json
{
  "name": "__trace_note_message",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580670496,
      "name": "__trace_note_message",
      "external": true,
      "loc": "kernel/trace/blktrace.c:146",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_msg_write",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_tg_is_idle",
        "block/blk-throttle.c:throtl_tg_is_idle",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580670496,
      "name": "__trace_note_message",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct blkcg * blkcg</code>
</li>
<li>
<b>Param reordered. </b>
<code>bt, fmt, (anon)</code> ➡️ <code>bt, blkcg, fmt, (anon)</code>
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void __trace_note_message(struct blk_trace * bt, struct blkcg * blkcg, const char * fmt, void (anon))
```
</details>
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
