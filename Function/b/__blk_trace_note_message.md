# Function: <code>__blk_trace_note_message</code>

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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void __blk_trace_note_message(struct blk_trace * bt, struct cgroup_subsys_state * css, const char * fmt, void (anon))
```

```json
{
  "name": "__blk_trace_note_message",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blk_trace_note_message",
      "external": true,
      "loc": "kernel/trace/blktrace.c:148",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_msg_write",
        "block/blk-throttle.c:__blk_throtl_bio",
        "block/blk-throttle.c:__blk_throtl_bio",
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
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:throtl_trim_slice",
        "block/blk-throttle.c:throtl_trim_slice",
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
      "addr": 18446744071593947463,
      "name": "__blk_trace_note_message.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071581168928,
      "name": "__blk_trace_note_message",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void __blk_trace_note_message(struct blk_trace * bt, struct cgroup_subsys_state * css, const char * fmt, void (anon))
```

```json
{
  "name": "__blk_trace_note_message",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blk_trace_note_message",
      "external": true,
      "loc": "kernel/trace/blktrace.c:148",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_msg_write",
        "block/elevator.c:elevator_disable",
        "block/elevator.c:elevator_switch",
        "block/blk-throttle.c:__blk_throtl_bio",
        "block/blk-throttle.c:__blk_throtl_bio",
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
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_update_carryover",
        "block/blk-throttle.c:tg_update_carryover",
        "block/blk-throttle.c:throtl_trim_slice",
        "block/blk-throttle.c:throtl_trim_slice",
        "block/blk-throttle.c:throtl_start_new_slice",
        "block/blk-throttle.c:throtl_start_new_slice",
        "block/blk-throttle.c:throtl_start_new_slice_with_credit",
        "block/blk-throttle.c:throtl_start_new_slice_with_credit",
        "block/blk-throttle.c:throtl_schedule_pending_timer",
        "block/blk-throttle.c:throtl_schedule_pending_timer",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_unplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596007186,
      "name": "__blk_trace_note_message.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581483776,
      "name": "__blk_trace_note_message",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
void __blk_trace_note_message(struct blk_trace * bt, struct cgroup_subsys_state * css, const char * fmt, void (anon))
```

```json
{
  "name": "__blk_trace_note_message",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blk_trace_note_message",
      "external": true,
      "loc": "kernel/trace/blktrace.c:148",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_msg_write",
        "block/elevator.c:elevator_disable",
        "block/elevator.c:elevator_switch",
        "block/blk-throttle.c:__blk_throtl_bio",
        "block/blk-throttle.c:__blk_throtl_bio",
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
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_update_carryover",
        "block/blk-throttle.c:tg_update_carryover",
        "block/blk-throttle.c:throtl_trim_slice",
        "block/blk-throttle.c:throtl_trim_slice",
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
      "addr": 18446744071596526001,
      "name": "__blk_trace_note_message.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581601712,
      "name": "__blk_trace_note_message",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
void __blk_trace_note_message(struct blk_trace * bt, struct cgroup_subsys_state * css, const char * fmt, void (anon))
```

```json
{
  "name": "__blk_trace_note_message",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__blk_trace_note_message",
      "external": true,
      "loc": "kernel/trace/blktrace.c:148",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_msg_write",
        "block/elevator.c:elevator_disable",
        "block/elevator.c:elevator_switch",
        "block/blk-throttle.c:__blk_throtl_bio",
        "block/blk-throttle.c:__blk_throtl_bio",
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
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_update_carryover",
        "block/blk-throttle.c:tg_update_carryover",
        "block/blk-throttle.c:throtl_trim_slice",
        "block/blk-throttle.c:throtl_trim_slice",
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
      "addr": 18446744071597426611,
      "name": "__blk_trace_note_message.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581714144,
      "name": "__blk_trace_note_message",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void __blk_trace_note_message(struct blk_trace * bt, struct cgroup_subsys_state * css, const char * fmt, void (anon))
```
</details>
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
