# Function: <code>hrtimer_try_to_cancel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hrtimer_try_to_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_try_to_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579823936,
      "name": "hrtimer_try_to_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1034",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/posix-timers.c:common_timer_del",
        "kernel/time/posix-timers.c:common_timer_set",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/tick-broadcast-hrtimer.c:bc_shutdown",
        "kernel/time/tick-broadcast-hrtimer.c:bc_set_next",
        "fs/timerfd.c:do_timerfd_settime",
        "drivers/rtc/interface.c:rtc_update_hrtimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579823936,
      "name": "hrtimer_try_to_cancel",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hrtimer_try_to_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_try_to_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579852800,
      "name": "hrtimer_try_to_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1024",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/posix-timers.c:common_timer_del",
        "kernel/time/posix-timers.c:common_timer_set",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/tick-broadcast-hrtimer.c:bc_set_next",
        "kernel/time/tick-broadcast-hrtimer.c:bc_shutdown",
        "fs/timerfd.c:do_timerfd_settime",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:__cfq_slice_expired",
        "block/cfq-iosched.c:__cfq_set_active_queue",
        "drivers/rtc/interface.c:rtc_update_hrtimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579852800,
      "name": "hrtimer_try_to_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hrtimer_try_to_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_try_to_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579881632,
      "name": "hrtimer_try_to_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1024",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/posix-timers.c:common_timer_del",
        "kernel/time/posix-timers.c:common_timer_set",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-broadcast-hrtimer.c:bc_shutdown",
        "fs/timerfd.c:do_timerfd_settime",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:__cfq_slice_expired",
        "block/cfq-iosched.c:__cfq_set_active_queue",
        "drivers/rtc/interface.c:rtc_update_hrtimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579881632,
      "name": "hrtimer_try_to_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
int hrtimer_try_to_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_try_to_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579890736,
      "name": "hrtimer_try_to_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:994",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/posix-timers.c:common_hrtimer_try_to_cancel",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-broadcast-hrtimer.c:bc_shutdown",
        "fs/timerfd.c:do_timerfd_settime",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:__cfq_slice_expired",
        "block/cfq-iosched.c:__cfq_set_active_queue",
        "drivers/rtc/interface.c:rtc_update_hrtimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579890736,
      "name": "hrtimer_try_to_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
int hrtimer_try_to_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_try_to_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579935280,
      "name": "hrtimer_try_to_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:994",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/posix-timers.c:common_hrtimer_try_to_cancel",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-broadcast-hrtimer.c:bc_shutdown",
        "fs/timerfd.c:do_timerfd_settime",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:__cfq_slice_expired",
        "block/cfq-iosched.c:__cfq_set_active_queue",
        "drivers/rtc/interface.c:rtc_update_hrtimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579935280,
      "name": "hrtimer_try_to_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
int hrtimer_try_to_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_try_to_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579984144,
      "name": "hrtimer_try_to_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1132",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:dl_change_utilization",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/posix-timers.c:common_hrtimer_try_to_cancel",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-broadcast-hrtimer.c:bc_shutdown",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:__cfq_slice_expired",
        "block/cfq-iosched.c:__cfq_set_active_queue",
        "drivers/rtc/interface.c:rtc_update_hrtimer",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579984144,
      "name": "hrtimer_try_to_cancel",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hrtimer_try_to_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_try_to_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580029168,
      "name": "hrtimer_try_to_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1123",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:dl_change_utilization",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/posix-timers.c:common_hrtimer_try_to_cancel",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-broadcast-hrtimer.c:bc_shutdown",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/rtc/interface.c:rtc_update_hrtimer",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580029168,
      "name": "hrtimer_try_to_cancel",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hrtimer_try_to_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_try_to_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580072208,
      "name": "hrtimer_try_to_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1123",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:task_contending",
        "kernel/sched/deadline.c:dl_change_utilization",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_cancel",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/posix-timers.c:common_hrtimer_try_to_cancel",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-broadcast-hrtimer.c:bc_shutdown",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/rtc/interface.c:rtc_update_hrtimer",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580072208,
      "name": "hrtimer_try_to_cancel",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hrtimer_try_to_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_try_to_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580121520,
      "name": "hrtimer_try_to_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1151",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:task_contending",
        "kernel/sched/deadline.c:dl_change_utilization",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/posix-timers.c:common_hrtimer_try_to_cancel",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-broadcast-hrtimer.c:bc_shutdown",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_commit_cqring",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/rtc/interface.c:rtc_update_hrtimer",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580121520,
      "name": "hrtimer_try_to_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int hrtimer_try_to_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_try_to_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591214218,
      "name": "hrtimer_try_to_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1151",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "kernel/sched/deadline.c:dl_change_utilization",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/posix-timers.c:common_hrtimer_try_to_cancel",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-broadcast-hrtimer.c:bc_shutdown",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:__io_timeout_cancel",
        "fs/io_uring.c:__io_fail_links",
        "fs/io_uring.c:io_req_link_next",
        "fs/io_uring.c:io_commit_cqring",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/rtc/interface.c:rtc_irq_set_freq",
        "drivers/rtc/interface.c:rtc_irq_set_state",
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580184160,
      "name": "hrtimer_try_to_cancel.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071580184400,
      "name": "hrtimer_try_to_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int hrtimer_try_to_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_try_to_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591709354,
      "name": "hrtimer_try_to_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1168",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl",
        "kernel/sched/deadline.c:dl_change_utilization",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/posix-timers.c:common_hrtimer_try_to_cancel",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-broadcast-hrtimer.c:bc_shutdown",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/io_uring.c:io_timeout_extract",
        "fs/io_uring.c:io_kill_linked_timeout",
        "fs/io_uring.c:io_flush_timeouts",
        "fs/io_uring.c:io_kill_timeouts",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/rtc/interface.c:rtc_irq_set_freq",
        "drivers/rtc/interface.c:rtc_irq_set_state",
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580168976,
      "name": "hrtimer_try_to_cancel.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    },
    {
      "addr": 18446744071580169200,
      "name": "hrtimer_try_to_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int hrtimer_try_to_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_try_to_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591656727,
      "name": "hrtimer_try_to_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1168",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl",
        "kernel/sched/deadline.c:dl_change_utilization",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/posix-timers.c:common_hrtimer_try_to_cancel",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-broadcast-hrtimer.c:bc_shutdown",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/io_uring.c:io_kill_timeouts",
        "fs/io_uring.c:io_timeout_extract",
        "fs/io_uring.c:io_disarm_next",
        "fs/io_uring.c:io_commit_cqring",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/rtc/interface.c:rtc_irq_set_freq",
        "drivers/rtc/interface.c:rtc_irq_set_state",
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580173312,
      "name": "hrtimer_try_to_cancel.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    },
    {
      "addr": 18446744071580173536,
      "name": "hrtimer_try_to_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int hrtimer_try_to_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_try_to_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592830423,
      "name": "hrtimer_try_to_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1316",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:enqueue_task_dl",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/posix-timers.c:common_hrtimer_try_to_cancel",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-broadcast-hrtimer.c:bc_shutdown",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/io_uring.c:io_kill_timeouts",
        "fs/io_uring.c:io_timeout_extract",
        "fs/io_uring.c:io_disarm_next",
        "fs/io_uring.c:__io_commit_cqring_flush",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/rtc/interface.c:rtc_irq_set_freq",
        "drivers/rtc/interface.c:rtc_irq_set_state",
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580317296,
      "name": "hrtimer_try_to_cancel.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
    },
    {
      "addr": 18446744071580317504,
      "name": "hrtimer_try_to_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int hrtimer_try_to_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_try_to_cancel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580527312,
      "name": "hrtimer_try_to_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1316",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:migrate_task_rq_dl",
        "kernel/sched/build_policy.c:enqueue_task_dl",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/posix-timers.c:common_hrtimer_try_to_cancel",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-broadcast-hrtimer.c:bc_shutdown",
        "fs/timerfd.c:do_timerfd_settime",
        "io_uring/io_uring.c:io_timeout_remove",
        "io_uring/io_uring.c:io_timeout_extract",
        "io_uring/io_uring.c:io_disarm_next",
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/rtc/interface.c:rtc_irq_set_freq",
        "drivers/rtc/interface.c:rtc_irq_set_state",
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580527312,
      "name": "hrtimer_try_to_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int hrtimer_try_to_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_try_to_cancel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580784208,
      "name": "hrtimer_try_to_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1316",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:migrate_task_rq_dl",
        "kernel/sched/build_policy.c:enqueue_task_dl",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/posix-timers.c:common_hrtimer_try_to_cancel",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-broadcast-hrtimer.c:bc_shutdown",
        "fs/timerfd.c:do_timerfd_settime",
        "io_uring/timeout.c:io_kill_timeouts",
        "io_uring/timeout.c:io_timeout_remove",
        "io_uring/timeout.c:io_timeout_extract",
        "io_uring/timeout.c:io_disarm_next",
        "io_uring/timeout.c:io_flush_timeouts",
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/rtc/interface.c:rtc_irq_set_freq",
        "drivers/rtc/interface.c:rtc_irq_set_state",
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580784208,
      "name": "hrtimer_try_to_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int hrtimer_try_to_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_try_to_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597032172,
      "name": "hrtimer_try_to_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1319",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:migrate_task_rq_dl",
        "kernel/sched/build_policy.c:enqueue_task_dl",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/posix-timers.c:common_hrtimer_try_to_cancel",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-broadcast-hrtimer.c:bc_shutdown",
        "fs/timerfd.c:do_timerfd_settime",
        "io_uring/timeout.c:io_kill_timeouts",
        "io_uring/timeout.c:io_timeout_remove",
        "io_uring/timeout.c:io_timeout_extract",
        "io_uring/timeout.c:io_disarm_next",
        "io_uring/timeout.c:io_flush_timeouts",
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/rtc/interface.c:rtc_irq_set_freq",
        "drivers/rtc/interface.c:rtc_irq_set_state",
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580869200,
      "name": "hrtimer_try_to_cancel.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
    },
    {
      "addr": 18446744071580869472,
      "name": "hrtimer_try_to_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
int hrtimer_try_to_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_try_to_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597961564,
      "name": "hrtimer_try_to_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1320",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:migrate_task_rq_dl",
        "kernel/sched/build_policy.c:enqueue_task_dl",
        "kernel/sched/build_policy.c:task_contending",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/posix-timers.c:common_hrtimer_try_to_cancel",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-broadcast-hrtimer.c:bc_shutdown",
        "fs/timerfd.c:do_timerfd_settime",
        "io_uring/timeout.c:io_kill_timeouts",
        "io_uring/timeout.c:io_timeout_remove",
        "io_uring/timeout.c:io_timeout_extract",
        "io_uring/timeout.c:io_disarm_next",
        "io_uring/timeout.c:io_flush_timeouts",
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/rtc/interface.c:rtc_irq_set_freq",
        "drivers/rtc/interface.c:rtc_irq_set_state",
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580959696,
      "name": "hrtimer_try_to_cancel.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
    },
    {
      "addr": 18446744071580959968,
      "name": "hrtimer_try_to_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
int hrtimer_try_to_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_try_to_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491342504,
      "name": "hrtimer_try_to_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1151",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:task_contending",
        "kernel/sched/deadline.c:dl_change_utilization",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/posix-timers.c:common_hrtimer_try_to_cancel",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-broadcast-hrtimer.c:bc_shutdown",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_commit_cqring",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/rtc/interface.c:rtc_update_hrtimer",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491342504,
      "name": "hrtimer_try_to_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
int hrtimer_try_to_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_try_to_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225332516,
      "name": "hrtimer_try_to_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1151",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:dl_change_utilization",
        "kernel/time/hrtimer.c:hrtimer_cancel",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/posix-timers.c:common_hrtimer_try_to_cancel",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-broadcast-hrtimer.c:bc_shutdown",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_commit_cqring",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/rtc/interface.c:rtc_update_hrtimer",
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225332516,
      "name": "hrtimer_try_to_cancel",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int hrtimer_try_to_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_try_to_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284270048,
      "name": "hrtimer_try_to_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1151",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:task_contending",
        "kernel/sched/deadline.c:dl_change_utilization",
        "kernel/time/hrtimer.c:hrtimer_cancel",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/posix-timers.c:common_hrtimer_try_to_cancel",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-broadcast-hrtimer.c:bc_shutdown",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_commit_cqring",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/rtc/interface.c:rtc_update_hrtimer",
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284270048,
      "name": "hrtimer_try_to_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
int hrtimer_try_to_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_try_to_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271836730,
      "name": "hrtimer_try_to_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1151",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:dl_change_utilization",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/posix-timers.c:common_hrtimer_try_to_cancel",
        "kernel/time/itimer.c:do_setitimer",
        "fs/timerfd.c:__se_sys_timerfd_settime",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_commit_cqring",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/rtc/interface.c:rtc_update_hrtimer",
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271836730,
      "name": "hrtimer_try_to_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
int hrtimer_try_to_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_try_to_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580090720,
      "name": "hrtimer_try_to_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1151",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:task_contending",
        "kernel/sched/deadline.c:dl_change_utilization",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/posix-timers.c:common_hrtimer_try_to_cancel",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-broadcast-hrtimer.c:bc_shutdown",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_commit_cqring",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/rtc/interface.c:rtc_update_hrtimer",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580090720,
      "name": "hrtimer_try_to_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
int hrtimer_try_to_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_try_to_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580036048,
      "name": "hrtimer_try_to_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1151",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:task_contending",
        "kernel/sched/deadline.c:dl_change_utilization",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/posix-timers.c:common_hrtimer_try_to_cancel",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-broadcast-hrtimer.c:bc_shutdown",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_commit_cqring",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/rtc/interface.c:rtc_update_hrtimer",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580036048,
      "name": "hrtimer_try_to_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
int hrtimer_try_to_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_try_to_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580081792,
      "name": "hrtimer_try_to_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1151",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:task_contending",
        "kernel/sched/deadline.c:dl_change_utilization",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/posix-timers.c:common_hrtimer_try_to_cancel",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-broadcast-hrtimer.c:bc_shutdown",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_commit_cqring",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/rtc/interface.c:rtc_update_hrtimer",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580081792,
      "name": "hrtimer_try_to_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
int hrtimer_try_to_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_try_to_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580133360,
      "name": "hrtimer_try_to_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1151",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:task_contending",
        "kernel/sched/deadline.c:dl_change_utilization",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/posix-timers.c:common_hrtimer_try_to_cancel",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-broadcast-hrtimer.c:bc_shutdown",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_commit_cqring",
        "drivers/base/power/runtime.c:__pm_runtime_barrier",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/rtc/interface.c:rtc_update_hrtimer",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580133360,
      "name": "hrtimer_try_to_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
