# Function: <code>hrtimer_start_range_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void hrtimer_start_range_ns(struct hrtimer * timer, ktime_t tim, long unsigned int delta_ns, const enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_start_range_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579825184,
      "name": "hrtimer_start_range_ns",
      "external": true,
      "loc": "kernel/time/hrtimer.c:981",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/cqm.c:__mbm_start_timer",
        "arch/x86/events/intel/rapl.c:__rapl_pmu_event_start",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_start",
        "kernel/softirq.c:__tasklet_hrtimer_trampoline",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/core.c:__hrtick_start",
        "kernel/sched/core.c:hrtick_start",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/sched/deadline.c:start_dl_timer",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/posix-timers.c:common_timer_set",
        "kernel/time/posix-timers.c:do_schedule_next_timer",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/alarmtimer.c:alarm_restart",
        "kernel/time/tick-broadcast-hrtimer.c:bc_set_next",
        "kernel/time/tick-sched.c:tick_nohz_restart",
        "kernel/time/tick-sched.c:__tick_nohz_idle_enter",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "fs/timerfd.c:timerfd_read",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/aio.c:read_events",
        "drivers/usb/host/ehci-hcd.c:ehci_enable_event",
        "drivers/rtc/interface.c:rtc_update_hrtimer",
        "drivers/mailbox/mailbox.c:msg_submit",
        "net/core/dev.c:napi_complete_done",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:xfrm_state_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579825184,
      "name": "hrtimer_start_range_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 983
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
void hrtimer_start_range_ns(struct hrtimer * timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_start_range_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579854000,
      "name": "hrtimer_start_range_ns",
      "external": true,
      "loc": "kernel/time/hrtimer.c:971",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/cqm.c:__mbm_start_timer",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_start",
        "kernel/softirq.c:__tasklet_hrtimer_trampoline",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/core.c:hrtick_start",
        "kernel/sched/core.c:__hrtick_start",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/sched/deadline.c:start_dl_timer",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/posix-timers.c:common_timer_set",
        "kernel/time/posix-timers.c:do_schedule_next_timer",
        "kernel/time/alarmtimer.c:alarm_restart",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/tick-broadcast-hrtimer.c:bc_set_next",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:__tick_nohz_idle_enter",
        "kernel/time/tick-sched.c:tick_nohz_restart",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_read",
        "fs/aio.c:read_events",
        "block/cfq-iosched.c:cfq_arm_slice_timer",
        "drivers/usb/host/ehci-hcd.c:ehci_enable_event",
        "drivers/rtc/interface.c:rtc_update_hrtimer",
        "drivers/mailbox/mailbox.c:msg_submit",
        "net/core/dev.c:napi_complete_done",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579854000,
      "name": "hrtimer_start_range_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 971
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
void hrtimer_start_range_ns(struct hrtimer * timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_start_range_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579882704,
      "name": "hrtimer_start_range_ns",
      "external": true,
      "loc": "kernel/time/hrtimer.c:971",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/cqm.c:__mbm_start_timer",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_start",
        "kernel/softirq.c:__tasklet_hrtimer_trampoline",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/core.c:hrtick_start",
        "kernel/sched/core.c:__hrtick_start",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/sched/deadline.c:start_dl_timer",
        "kernel/sched/idle.c:play_idle",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_restart",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/posix-timers.c:common_timer_set",
        "kernel/time/posix-timers.c:do_schedule_next_timer",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_restart",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_read",
        "fs/aio.c:read_events",
        "block/blk-mq.c:blk_mq_poll_hybrid_sleep",
        "block/cfq-iosched.c:cfq_arm_slice_timer",
        "drivers/rtc/interface.c:rtc_update_hrtimer",
        "drivers/mailbox/mailbox.c:msg_submit",
        "net/core/dev.c:napi_complete_done",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579882704,
      "name": "hrtimer_start_range_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 972
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
void hrtimer_start_range_ns(struct hrtimer * timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_start_range_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579891712,
      "name": "hrtimer_start_range_ns",
      "external": true,
      "loc": "kernel/time/hrtimer.c:943",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_start",
        "kernel/softirq.c:__tasklet_hrtimer_trampoline",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/core.c:hrtick_start",
        "kernel/sched/core.c:__hrtick_start",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/sched/deadline.c:start_dl_timer",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/idle.c:play_idle",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_restart",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:__tick_nohz_idle_enter",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_read",
        "fs/aio.c:read_events",
        "block/cfq-iosched.c:cfq_arm_slice_timer",
        "drivers/rtc/interface.c:rtc_update_hrtimer",
        "drivers/mailbox/mailbox.c:msg_submit",
        "net/core/dev.c:napi_complete_done",
        "net/ipv4/tcp_output.c:tcp_transmit_skb",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579891712,
      "name": "hrtimer_start_range_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 810
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
void hrtimer_start_range_ns(struct hrtimer * timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_start_range_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579936272,
      "name": "hrtimer_start_range_ns",
      "external": true,
      "loc": "kernel/time/hrtimer.c:943",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_start",
        "kernel/softirq.c:__tasklet_hrtimer_trampoline",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/core.c:hrtick_start",
        "kernel/sched/core.c:__hrtick_start",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/sched/deadline.c:start_dl_timer",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/sched/idle.c:play_idle",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_restart",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:__tick_nohz_idle_enter",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_read",
        "fs/aio.c:read_events",
        "block/cfq-iosched.c:cfq_completed_request",
        "drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms",
        "drivers/rtc/interface.c:rtc_update_hrtimer",
        "drivers/mailbox/mailbox.c:msg_submit",
        "net/core/dev.c:napi_complete_done",
        "net/ipv4/tcp_output.c:tcp_transmit_skb",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579936272,
      "name": "hrtimer_start_range_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 818
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
void hrtimer_start_range_ns(struct hrtimer * timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_start_range_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579982512,
      "name": "hrtimer_start_range_ns",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1101",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_start",
        "kernel/softirq.c:__tasklet_hrtimer_trampoline",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/core.c:hrtick_start",
        "kernel/sched/core.c:__hrtick_start",
        "kernel/sched/idle.c:play_idle",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/sched/deadline.c:start_dl_timer",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_restart",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:timerfd_read",
        "fs/aio.c:read_events",
        "block/cfq-iosched.c:cfq_completed_request",
        "drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms",
        "drivers/rtc/interface.c:rtc_update_hrtimer",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/mailbox/mailbox.c:msg_submit",
        "net/core/dev.c:napi_complete_done",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579982512,
      "name": "hrtimer_start_range_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 689
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
void hrtimer_start_range_ns(struct hrtimer * timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_start_range_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580030400,
      "name": "hrtimer_start_range_ns",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1092",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_start",
        "kernel/softirq.c:__tasklet_hrtimer_trampoline",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/core.c:hrtick_start",
        "kernel/sched/core.c:__hrtick_start",
        "kernel/sched/idle.c:play_idle",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/sched/deadline.c:start_dl_timer",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_restart",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:timerfd_read",
        "fs/aio.c:read_events",
        "drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/rtc/interface.c:rtc_update_hrtimer",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/mailbox/mailbox.c:msg_submit",
        "drivers/powercap/idle_inject.c:idle_inject_start",
        "net/core/dev.c:napi_complete_done",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_state_find",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580030400,
      "name": "hrtimer_start_range_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 689
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
void hrtimer_start_range_ns(struct hrtimer * timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_start_range_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580073600,
      "name": "hrtimer_start_range_ns",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1091",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_start",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/core.c:hrtick_start",
        "kernel/sched/core.c:__hrtick_start",
        "kernel/sched/idle.c:play_idle",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/sched/deadline.c:start_dl_timer",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_restart",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:timerfd_read",
        "fs/aio.c:read_events",
        "drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/rtc/interface.c:rtc_update_hrtimer",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/mailbox/mailbox.c:msg_submit",
        "drivers/powercap/idle_inject.c:idle_inject_start",
        "net/core/dev.c:napi_complete_done",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_state_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580073600,
      "name": "hrtimer_start_range_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 771
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
void hrtimer_start_range_ns(struct hrtimer * timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_start_range_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580122752,
      "name": "hrtimer_start_range_ns",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1115",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_start",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/core.c:hrtick_start",
        "kernel/sched/core.c:__hrtick_start",
        "kernel/sched/idle.c:play_idle",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/rt.c:__enqueue_rt_entity",
        "kernel/sched/deadline.c:start_dl_timer",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_restart",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-broadcast-hrtimer.c:bc_set_next",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:timerfd_read",
        "fs/aio.c:read_events",
        "fs/io_uring.c:__io_submit_sqe",
        "block/blk-iocost.c:iocg_kick_delay",
        "block/blk-iocost.c:iocg_kick_waitq",
        "drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/rtc/interface.c:rtc_update_hrtimer",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/mailbox/mailbox.c:msg_submit",
        "drivers/powercap/idle_inject.c:idle_inject_start",
        "net/core/dev.c:napi_complete_done",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_state_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580122752,
      "name": "hrtimer_start_range_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 770
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
void hrtimer_start_range_ns(struct hrtimer * timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_start_range_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580183760,
      "name": "hrtimer_start_range_ns",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1115",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_start",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/core.c:hrtick_start",
        "kernel/sched/core.c:__hrtick_start",
        "kernel/sched/idle.c:play_idle_precise",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/rt.c:__enqueue_rt_entity",
        "kernel/sched/deadline.c:start_dl_timer",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_restart",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-broadcast-hrtimer.c:bc_set_next",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick",
        "kernel/time/tick-sched.c:tick_nohz_restart",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_start",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_read",
        "fs/aio.c:read_events",
        "fs/io_uring.c:io_queue_linked_timeout",
        "fs/io_uring.c:io_issue_sqe",
        "block/blk-iocost.c:iocg_kick_delay",
        "block/blk-iocost.c:iocg_kick_waitq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx",
        "drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add",
        "drivers/usb/host/ehci-hcd.c:sitd_complete",
        "drivers/usb/host/ehci-hcd.c:itd_complete",
        "drivers/usb/host/ehci-hcd.c:scan_async",
        "drivers/usb/host/ehci-hcd.c:unlink_empty_async",
        "drivers/usb/host/ehci-hcd.c:end_unlink_async",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks",
        "drivers/rtc/interface.c:rtc_irq_set_freq",
        "drivers/rtc/interface.c:rtc_irq_set_state",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/mailbox/mailbox.c:msg_submit",
        "drivers/powercap/idle_inject.c:idle_inject_start",
        "net/core/dev.c:napi_complete_done",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/xfrm/xfrm_state.c:xfrm_state_check_expire",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_state_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580183760,
      "name": "hrtimer_start_range_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void hrtimer_start_range_ns(struct hrtimer * timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_start_range_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580167648,
      "name": "hrtimer_start_range_ns",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1132",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_start",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/core.c:hrtick_start",
        "kernel/sched/core.c:__hrtick_start",
        "kernel/sched/idle.c:play_idle_precise",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/rt.c:__enqueue_rt_entity",
        "kernel/sched/deadline.c:start_dl_timer",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/time/alarmtimer.c:alarm_restart",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-broadcast-hrtimer.c:bc_set_next",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick",
        "kernel/time/tick-sched.c:tick_nohz_restart",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_start",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_read",
        "fs/aio.c:read_events",
        "fs/io_uring.c:io_queue_linked_timeout",
        "fs/io_uring.c:io_timeout",
        "fs/io_uring.c:io_timeout_remove",
        "block/blk-iocost.c:iocg_kick_waitq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx",
        "drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add",
        "drivers/usb/host/ehci-hcd.c:sitd_complete",
        "drivers/usb/host/ehci-hcd.c:itd_complete",
        "drivers/usb/host/ehci-hcd.c:scan_async",
        "drivers/usb/host/ehci-hcd.c:unlink_empty_async",
        "drivers/usb/host/ehci-hcd.c:end_unlink_async",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks",
        "drivers/rtc/interface.c:rtc_irq_set_freq",
        "drivers/rtc/interface.c:rtc_irq_set_state",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/mailbox/mailbox.c:msg_submit",
        "drivers/powercap/idle_inject.c:idle_inject_start",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_complete_done",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/xfrm/xfrm_state.c:xfrm_state_check_expire",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_state_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580167648,
      "name": "hrtimer_start_range_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void hrtimer_start_range_ns(struct hrtimer * timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_start_range_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580173072,
      "name": "hrtimer_start_range_ns",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1132",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_start",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/core.c:hrtick_start",
        "kernel/sched/core.c:__hrtick_start",
        "kernel/sched/idle.c:play_idle_precise",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/rt.c:__enqueue_rt_entity",
        "kernel/sched/deadline.c:start_dl_timer",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/time/alarmtimer.c:alarm_restart",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-broadcast-hrtimer.c:bc_set_next",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick",
        "kernel/time/tick-sched.c:tick_nohz_restart",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_start",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_read",
        "fs/aio.c:read_events",
        "fs/io_uring.c:io_queue_linked_timeout",
        "fs/io_uring.c:io_issue_sqe",
        "block/blk-iocost.c:iocg_kick_waitq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx",
        "drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add",
        "drivers/usb/host/ehci-hcd.c:sitd_complete",
        "drivers/usb/host/ehci-hcd.c:itd_complete",
        "drivers/usb/host/ehci-hcd.c:unlink_empty_async",
        "drivers/usb/host/ehci-hcd.c:end_unlink_async",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks",
        "drivers/rtc/interface.c:rtc_irq_set_freq",
        "drivers/rtc/interface.c:rtc_irq_set_state",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/mailbox/mailbox.c:msg_submit",
        "drivers/powercap/idle_inject.c:idle_inject_start",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_complete_done",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/xfrm/xfrm_state.c:xfrm_state_check_expire",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_state_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580173072,
      "name": "hrtimer_start_range_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void hrtimer_start_range_ns(struct hrtimer * timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_start_range_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580318656,
      "name": "hrtimer_start_range_ns",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1280",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_start",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/core.c:hrtick_start",
        "kernel/sched/core.c:__hrtick_start",
        "kernel/sched/idle.c:play_idle_precise",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:start_dl_timer",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/time/alarmtimer.c:alarm_restart",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-broadcast-hrtimer.c:bc_set_next",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick",
        "kernel/time/tick-sched.c:tick_nohz_restart",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/bpf/helpers.c:bpf_timer_start",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_start",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_read",
        "fs/aio.c:read_events",
        "fs/io_uring.c:io_queue_linked_timeout",
        "fs/io_uring.c:io_issue_sqe",
        "block/blk-iocost.c:iocg_kick_waitq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx",
        "drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add",
        "drivers/usb/host/ehci-hcd.c:sitd_complete",
        "drivers/usb/host/ehci-hcd.c:itd_complete",
        "drivers/usb/host/ehci-hcd.c:unlink_empty_async",
        "drivers/usb/host/ehci-hcd.c:end_unlink_async",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks",
        "drivers/rtc/interface.c:rtc_irq_set_freq",
        "drivers/rtc/interface.c:rtc_irq_set_state",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/mailbox/mailbox.c:msg_submit",
        "drivers/powercap/idle_inject.c:idle_inject_start",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_complete_done",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/xfrm/xfrm_state.c:xfrm_state_check_expire",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_state_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580318656,
      "name": "hrtimer_start_range_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void hrtimer_start_range_ns(struct hrtimer * timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_start_range_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580530032,
      "name": "hrtimer_start_range_ns",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1280",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_start",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/core.c:hrtick_start",
        "kernel/sched/core.c:__hrtick_start",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/build_policy.c:start_dl_timer",
        "kernel/sched/build_policy.c:task_non_contending",
        "kernel/sched/build_policy.c:enqueue_task_rt",
        "kernel/sched/build_policy.c:update_curr_rt",
        "kernel/sched/build_policy.c:play_idle_precise",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/time/alarmtimer.c:alarm_restart",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-broadcast-hrtimer.c:bc_set_next",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick",
        "kernel/time/tick-sched.c:tick_nohz_restart",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/bpf/helpers.c:bpf_timer_start",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_start",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_read",
        "block/blk-iocost.c:iocg_kick_waitq",
        "io_uring/io_uring.c:io_queue_linked_timeout",
        "io_uring/io_uring.c:io_timeout",
        "io_uring/io_uring.c:io_timeout_remove",
        "io_uring/io_uring.c:io_timeout_remove",
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx",
        "drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add",
        "drivers/usb/host/ehci-hcd.c:sitd_complete",
        "drivers/usb/host/ehci-hcd.c:itd_complete",
        "drivers/usb/host/ehci-hcd.c:unlink_empty_async",
        "drivers/usb/host/ehci-hcd.c:end_unlink_async",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks",
        "drivers/rtc/interface.c:rtc_irq_set_freq",
        "drivers/rtc/interface.c:rtc_irq_set_state",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_stop",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/mailbox/mailbox.c:msg_submit",
        "drivers/powercap/idle_inject.c:idle_inject_start",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_complete_done",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/xfrm/xfrm_state.c:xfrm_state_check_expire",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_state_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580530032,
      "name": "hrtimer_start_range_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
void hrtimer_start_range_ns(struct hrtimer * timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_start_range_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580786160,
      "name": "hrtimer_start_range_ns",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1280",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_start",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/core.c:hrtick_start",
        "kernel/sched/core.c:__hrtick_start",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/build_policy.c:start_dl_timer",
        "kernel/sched/build_policy.c:task_non_contending",
        "kernel/sched/build_policy.c:enqueue_task_rt",
        "kernel/sched/build_policy.c:update_curr_rt",
        "kernel/sched/build_policy.c:play_idle_precise",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/time/alarmtimer.c:alarm_restart",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-broadcast-hrtimer.c:bc_set_next",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick",
        "kernel/time/tick-sched.c:tick_nohz_restart",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/bpf/helpers.c:bpf_timer_start",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_start",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_read",
        "block/blk-iocost.c:iocg_kick_waitq",
        "io_uring/timeout.c:io_queue_linked_timeout",
        "io_uring/timeout.c:io_timeout",
        "io_uring/timeout.c:io_timeout_remove",
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx",
        "drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add",
        "drivers/usb/host/ehci-hcd.c:sitd_complete",
        "drivers/usb/host/ehci-hcd.c:itd_complete",
        "drivers/usb/host/ehci-hcd.c:unlink_empty_async",
        "drivers/usb/host/ehci-hcd.c:end_unlink_async",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death",
        "drivers/rtc/interface.c:rtc_irq_set_freq",
        "drivers/rtc/interface.c:rtc_irq_set_state",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/watchdog/watchdog_dev.c:watchdog_update_worker",
        "drivers/mailbox/mailbox.c:msg_submit",
        "drivers/powercap/idle_inject.c:idle_inject_start",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_complete_done",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/xfrm/xfrm_state.c:xfrm_state_check_expire",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_state_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580786160,
      "name": "hrtimer_start_range_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
void hrtimer_start_range_ns(struct hrtimer * timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_start_range_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580868432,
      "name": "hrtimer_start_range_ns",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1283",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_start",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/core.c:hrtick_start",
        "kernel/sched/core.c:__hrtick_start",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/build_policy.c:start_dl_timer",
        "kernel/sched/build_policy.c:task_non_contending",
        "kernel/sched/build_policy.c:enqueue_task_rt",
        "kernel/sched/build_policy.c:update_curr_rt",
        "kernel/sched/build_policy.c:play_idle_precise",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/time/alarmtimer.c:alarm_restart",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-broadcast-hrtimer.c:bc_set_next",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick",
        "kernel/time/tick-sched.c:tick_nohz_restart",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/bpf/helpers.c:bpf_timer_start",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_read",
        "block/blk-iocost.c:iocg_kick_waitq",
        "io_uring/timeout.c:io_queue_linked_timeout",
        "io_uring/timeout.c:io_timeout",
        "io_uring/timeout.c:io_timeout_remove",
        "io_uring/timeout.c:io_timeout_complete",
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx",
        "drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add",
        "drivers/usb/host/ehci-hcd.c:sitd_complete",
        "drivers/usb/host/ehci-hcd.c:itd_complete",
        "drivers/usb/host/ehci-hcd.c:unlink_empty_async",
        "drivers/usb/host/ehci-hcd.c:end_unlink_async",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death",
        "drivers/rtc/interface.c:rtc_irq_set_freq",
        "drivers/rtc/interface.c:rtc_irq_set_state",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/watchdog/watchdog_dev.c:watchdog_update_worker",
        "drivers/mailbox/mailbox.c:msg_submit",
        "drivers/powercap/idle_inject.c:idle_inject_start",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_complete_done",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/xfrm/xfrm_state.c:xfrm_state_check_expire",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_state_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580868432,
      "name": "hrtimer_start_range_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
void hrtimer_start_range_ns(struct hrtimer * timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_start_range_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580959408,
      "name": "hrtimer_start_range_ns",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1284",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_start",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/core.c:hrtick_start",
        "kernel/sched/core.c:__hrtick_start",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/build_policy.c:start_dl_timer",
        "kernel/sched/build_policy.c:task_non_contending",
        "kernel/sched/build_policy.c:enqueue_task_rt",
        "kernel/sched/build_policy.c:update_curr_rt",
        "kernel/sched/build_policy.c:play_idle_precise",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/time/alarmtimer.c:alarm_restart",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-broadcast-hrtimer.c:bc_set_next",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_restart_sched_tick",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/bpf/helpers.c:bpf_timer_start",
        "kernel/events/core.c:task_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_read",
        "block/blk-iocost.c:iocg_kick_waitq",
        "io_uring/timeout.c:io_queue_linked_timeout",
        "io_uring/timeout.c:io_timeout",
        "io_uring/timeout.c:io_timeout_remove",
        "io_uring/timeout.c:io_timeout_complete",
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx",
        "drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add",
        "drivers/usb/host/ehci-hcd.c:sitd_complete",
        "drivers/usb/host/ehci-hcd.c:itd_complete",
        "drivers/usb/host/ehci-hcd.c:unlink_empty_async",
        "drivers/usb/host/ehci-hcd.c:end_unlink_async",
        "drivers/usb/host/ehci-hcd.c:end_free_itds",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks",
        "drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death",
        "drivers/rtc/interface.c:rtc_irq_set_freq",
        "drivers/rtc/interface.c:rtc_irq_set_state",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/watchdog/watchdog_dev.c:watchdog_update_worker",
        "drivers/mailbox/mailbox.c:msg_submit",
        "drivers/powercap/idle_inject.c:idle_inject_start",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_complete_done",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/xfrm/xfrm_state.c:xfrm_state_check_expire",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_state_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580959408,
      "name": "hrtimer_start_range_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
void hrtimer_start_range_ns(struct hrtimer * timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_start_range_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491341480,
      "name": "hrtimer_start_range_ns",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1115",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/arm/arch_timer.c:kvm_timer_vcpu_put",
        "virt/kvm/arm/arch_timer.c:kvm_timer_vcpu_load",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/core.c:hrtick_start",
        "kernel/sched/core.c:__hrtick_start",
        "kernel/sched/idle.c:play_idle",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/rt.c:__enqueue_rt_entity",
        "kernel/sched/deadline.c:start_dl_timer",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_restart",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-broadcast-hrtimer.c:bc_set_next",
        "kernel/time/sched_clock.c:sched_clock_resume",
        "kernel/time/sched_clock.c:generic_sched_clock_init",
        "kernel/time/sched_clock.c:sched_clock_register",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:timerfd_read",
        "fs/aio.c:read_events",
        "fs/io_uring.c:__io_submit_sqe",
        "block/blk-iocost.c:iocg_kick_delay",
        "block/blk-iocost.c:iocg_kick_waitq",
        "drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/rtc/interface.c:rtc_update_hrtimer",
        "drivers/media/cec/cec-pin.c:cec_pin_adap_enable",
        "drivers/media/cec/cec-pin.c:cec_pin_thread_func",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_timer_trigger",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/mailbox/mailbox.c:msg_submit",
        "drivers/powercap/idle_inject.c:idle_inject_start",
        "net/core/dev.c:napi_complete_done",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_state_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491341480,
      "name": "hrtimer_start_range_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 960
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
void hrtimer_start_range_ns(struct hrtimer * timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_start_range_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225334420,
      "name": "hrtimer_start_range_ns",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1115",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_event_add",
        "arch/arm/mach-imx/mmdc.c:mmdc_pmu_event_start",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/core.c:__hrtick_restart",
        "kernel/sched/idle.c:play_idle",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/rt.c:__enqueue_rt_entity",
        "kernel/sched/deadline.c:start_dl_timer",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_restart",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-broadcast-hrtimer.c:bc_set_next",
        "kernel/time/sched_clock.c:sched_clock_resume",
        "kernel/time/sched_clock.c:generic_sched_clock_init",
        "kernel/time/sched_clock.c:sched_clock_register",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:timerfd_read",
        "fs/aio.c:do_io_getevents",
        "fs/io_uring.c:__io_submit_sqe",
        "block/blk-iocost.c:iocg_kick_delay",
        "block/blk-iocost.c:iocg_kick_waitq",
        "drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/rtc/interface.c:rtc_update_hrtimer",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_timer_trigger",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/mailbox/mailbox.c:msg_submit",
        "drivers/powercap/idle_inject.c:idle_inject_start",
        "sound/soc/fsl/imx-pcm-fiq.c:snd_imx_pcm_trigger",
        "net/core/dev.c:napi_complete_done",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/xfrm/xfrm_state.c:xfrm_state_check_expire",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_state_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225334420,
      "name": "hrtimer_start_range_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1136
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
void hrtimer_start_range_ns(struct hrtimer * timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_start_range_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284272080,
      "name": "hrtimer_start_range_ns",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1115",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/watchdog.c:start_watchdog",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/core.c:hrtick_start",
        "kernel/sched/core.c:__hrtick_start",
        "kernel/sched/idle.c:play_idle",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/rt.c:__enqueue_rt_entity",
        "kernel/sched/deadline.c:start_dl_timer",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_restart",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-broadcast-hrtimer.c:bc_set_next",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:timerfd_read",
        "fs/aio.c:read_events",
        "fs/io_uring.c:__io_submit_sqe",
        "block/blk-iocost.c:iocg_kick_delay",
        "block/blk-iocost.c:iocg_kick_waitq",
        "drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms",
        "drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/rtc/interface.c:rtc_update_hrtimer",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_timer_trigger",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/mailbox/mailbox.c:msg_submit",
        "drivers/powercap/idle_inject.c:idle_inject_start",
        "net/core/dev.c:napi_complete_done",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_state_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284272080,
      "name": "hrtimer_start_range_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1088
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
void hrtimer_start_range_ns(struct hrtimer * timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_start_range_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271838220,
      "name": "hrtimer_start_range_ns",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1115",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/core.c:hrtick_start",
        "kernel/sched/core.c:__hrtick_start",
        "kernel/sched/idle.c:play_idle",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/rt.c:__enqueue_rt_entity",
        "kernel/sched/deadline.c:start_dl_timer",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_restart",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/sched_clock.c:sched_clock_resume",
        "kernel/time/sched_clock.c:generic_sched_clock_init",
        "kernel/time/sched_clock.c:sched_clock_register",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "fs/timerfd.c:__se_sys_timerfd_gettime",
        "fs/timerfd.c:__se_sys_timerfd_settime",
        "fs/timerfd.c:timerfd_read",
        "fs/aio.c:read_events",
        "fs/io_uring.c:__io_submit_sqe",
        "block/blk-iocost.c:iocg_kick_delay",
        "block/blk-iocost.c:iocg_kick_waitq",
        "drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/rtc/interface.c:rtc_update_hrtimer",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_timer_trigger",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/mailbox/mailbox.c:msg_submit",
        "net/core/dev.c:napi_complete_done",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_state_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271838220,
      "name": "hrtimer_start_range_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 820
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
void hrtimer_start_range_ns(struct hrtimer * timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_start_range_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580091952,
      "name": "hrtimer_start_range_ns",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1115",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_start",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/core.c:hrtick_start",
        "kernel/sched/core.c:__hrtick_start",
        "kernel/sched/idle.c:play_idle",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/sched/deadline.c:start_dl_timer",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_restart",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-broadcast-hrtimer.c:bc_set_next",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:timerfd_read",
        "fs/aio.c:read_events",
        "fs/io_uring.c:__io_submit_sqe",
        "block/blk-iocost.c:iocg_kick_delay",
        "block/blk-iocost.c:iocg_kick_waitq",
        "drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/rtc/interface.c:rtc_update_hrtimer",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/mailbox/mailbox.c:msg_submit",
        "net/core/dev.c:napi_complete_done",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_state_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580091952,
      "name": "hrtimer_start_range_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 770
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
void hrtimer_start_range_ns(struct hrtimer * timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_start_range_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580037280,
      "name": "hrtimer_start_range_ns",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1115",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_start",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/core.c:hrtick_start",
        "kernel/sched/core.c:__hrtick_start",
        "kernel/sched/idle.c:play_idle",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/rt.c:__enqueue_rt_entity",
        "kernel/sched/deadline.c:start_dl_timer",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_restart",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-broadcast-hrtimer.c:bc_set_next",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_restart_sched_tick",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:timerfd_read",
        "fs/aio.c:read_events",
        "fs/io_uring.c:__io_submit_sqe",
        "block/blk-iocost.c:iocg_kick_delay",
        "block/blk-iocost.c:iocg_kick_waitq",
        "drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/rtc/interface.c:rtc_update_hrtimer",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/mailbox/mailbox.c:msg_submit",
        "net/core/dev.c:napi_complete_done",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_state_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580037280,
      "name": "hrtimer_start_range_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 770
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
void hrtimer_start_range_ns(struct hrtimer * timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_start_range_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580083024,
      "name": "hrtimer_start_range_ns",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1115",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_start",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/core.c:hrtick_start",
        "kernel/sched/core.c:__hrtick_start",
        "kernel/sched/idle.c:play_idle",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/rt.c:__enqueue_rt_entity",
        "kernel/sched/deadline.c:start_dl_timer",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_restart",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-broadcast-hrtimer.c:bc_set_next",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:timerfd_read",
        "fs/aio.c:read_events",
        "fs/io_uring.c:__io_submit_sqe",
        "block/blk-iocost.c:iocg_kick_delay",
        "block/blk-iocost.c:iocg_kick_waitq",
        "drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/rtc/interface.c:rtc_update_hrtimer",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/mailbox/mailbox.c:msg_submit",
        "drivers/powercap/idle_inject.c:idle_inject_start",
        "net/core/dev.c:napi_complete_done",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_state_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580083024,
      "name": "hrtimer_start_range_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 770
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
void hrtimer_start_range_ns(struct hrtimer * timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_start_range_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580134704,
      "name": "hrtimer_start_range_ns",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1115",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_start",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/core.c:hrtick_start",
        "kernel/sched/core.c:__hrtick_start",
        "kernel/sched/idle.c:play_idle",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/sched/deadline.c:start_dl_timer",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_restart",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/tick-broadcast-hrtimer.c:bc_set_next",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:timerfd_read",
        "fs/aio.c:read_events",
        "fs/io_uring.c:__io_submit_sqe",
        "block/blk-iocost.c:iocg_kick_delay",
        "block/blk-iocost.c:iocg_kick_waitq",
        "drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/rtc/interface.c:rtc_update_hrtimer",
        "drivers/media/cec/cec-pin.c:cec_pin_adap_enable",
        "drivers/media/cec/cec-pin.c:cec_pin_thread_func",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/mailbox/mailbox.c:msg_submit",
        "drivers/powercap/idle_inject.c:idle_inject_start",
        "net/core/dev.c:napi_complete_done",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/xfrm/xfrm_state.c:xfrm_state_update",
        "net/xfrm/xfrm_state.c:__find_acq_core",
        "net/xfrm/xfrm_state.c:__xfrm_state_insert",
        "net/xfrm/xfrm_state.c:xfrm_state_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580134704,
      "name": "hrtimer_start_range_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 802
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
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int delta_ns</code> ➡️ <code>u64 delta_ns</code>
</li>
</ul>
</details>
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
