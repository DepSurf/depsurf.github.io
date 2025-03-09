# Function: <code>hrtimer_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579825056,
      "name": "hrtimer_init",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1155",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart",
        "kernel/time/hrtimer.c:hrtimer_nanosleep"
      ],
      "caller_func": [
        "arch/x86/events/intel/cqm.c:intel_mbm_init",
        "arch/x86/events/intel/rapl.c:rapl_cpu_prepare",
        "arch/x86/events/intel/uncore.c:uncore_alloc_box",
        "kernel/fork.c:copy_process",
        "kernel/softirq.c:tasklet_hrtimer_init",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/fair.c:init_cfs_bandwidth",
        "kernel/sched/fair.c:init_cfs_bandwidth",
        "kernel/sched/rt.c:init_rt_bandwidth",
        "kernel/sched/deadline.c:init_dl_task_timer",
        "kernel/time/posix-timers.c:common_timer_create",
        "kernel/time/posix-timers.c:common_timer_set",
        "kernel/time/alarmtimer.c:alarm_timer_create",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/futex.c:futex_wait",
        "kernel/futex.c:futex_lock_pi",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:perf_pmu_register",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:SyS_timerfd_create",
        "fs/aio.c:read_events",
        "fs/aio.c:read_events",
        "fs/aio.c:read_events",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/rtc/class.c:rtc_device_register",
        "drivers/mailbox/mailbox.c:mbox_controller_register",
        "net/core/dev.c:netif_napi_add",
        "net/sched/sch_api.c:qdisc_watchdog_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579825056,
      "name": "hrtimer_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579855971,
      "name": "hrtimer_init",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1145",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart"
      ],
      "caller_func": [
        "arch/x86/events/intel/cqm.c:intel_mbm_init",
        "arch/x86/events/intel/uncore.c:uncore_alloc_box",
        "kernel/softirq.c:tasklet_hrtimer_init",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/fair.c:init_cfs_bandwidth",
        "kernel/sched/fair.c:init_cfs_bandwidth",
        "kernel/sched/rt.c:init_rt_bandwidth",
        "kernel/sched/deadline.c:init_dl_task_timer",
        "kernel/time/posix-timers.c:common_timer_set",
        "kernel/time/posix-timers.c:common_timer_create",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/time/alarmtimer.c:alarm_timer_create",
        "kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:perf_pmu_register",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:SyS_timerfd_create",
        "fs/aio.c:read_events",
        "fs/aio.c:read_events",
        "fs/aio.c:read_events",
        "block/cfq-iosched.c:cfq_init_queue",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/rtc/class.c:rtc_device_register",
        "drivers/mailbox/mailbox.c:mbox_controller_register",
        "net/core/dev.c:netif_napi_add",
        "net/sched/sch_api.c:qdisc_watchdog_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579853872,
      "name": "hrtimer_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579884826,
      "name": "hrtimer_init",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1145",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart"
      ],
      "caller_func": [
        "arch/x86/events/intel/cqm.c:intel_mbm_init",
        "arch/x86/events/intel/uncore.c:uncore_alloc_box",
        "kernel/softirq.c:tasklet_hrtimer_init",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/fair.c:init_cfs_bandwidth",
        "kernel/sched/fair.c:init_cfs_bandwidth",
        "kernel/sched/rt.c:init_rt_bandwidth",
        "kernel/sched/deadline.c:init_dl_task_timer",
        "kernel/sched/idle.c:play_idle",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/time/alarmtimer.c:alarm_timer_create",
        "kernel/time/posix-timers.c:common_timer_set",
        "kernel/time/posix-timers.c:common_timer_create",
        "kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:perf_pmu_register",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:SyS_timerfd_create",
        "fs/aio.c:read_events",
        "fs/aio.c:read_events",
        "fs/aio.c:read_events",
        "block/blk-mq.c:blk_mq_poll_hybrid_sleep",
        "block/cfq-iosched.c:cfq_init_queue",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/rtc/class.c:rtc_device_register",
        "drivers/mailbox/mailbox.c:mbox_controller_register",
        "net/core/dev.c:netif_napi_add",
        "net/sched/sch_api.c:qdisc_watchdog_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579882576,
      "name": "hrtimer_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579893718,
      "name": "hrtimer_init",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1121",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_alloc_box",
        "kernel/softirq.c:tasklet_hrtimer_init",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/fair.c:init_cfs_bandwidth",
        "kernel/sched/fair.c:init_cfs_bandwidth",
        "kernel/sched/rt.c:init_rt_bandwidth",
        "kernel/sched/deadline.c:init_dl_inactive_task_timer",
        "kernel/sched/deadline.c:init_dl_task_timer",
        "kernel/sched/idle.c:play_idle",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/time/alarmtimer.c:alarm_timer_create",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_timer_create",
        "kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:perf_pmu_register",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:SyS_timerfd_create",
        "fs/aio.c:read_events",
        "fs/aio.c:read_events",
        "block/cfq-iosched.c:cfq_init_queue",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/rtc/class.c:rtc_allocate_device",
        "drivers/mailbox/mailbox.c:mbox_controller_register",
        "net/core/dev.c:netif_napi_add",
        "net/sched/sch_api.c:qdisc_watchdog_init",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579891584,
      "name": "hrtimer_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579938246,
      "name": "hrtimer_init",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1126",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_alloc_box",
        "kernel/softirq.c:tasklet_hrtimer_init",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/fair.c:init_cfs_bandwidth",
        "kernel/sched/fair.c:init_cfs_bandwidth",
        "kernel/sched/rt.c:init_rt_bandwidth",
        "kernel/sched/deadline.c:init_dl_inactive_task_timer",
        "kernel/sched/deadline.c:init_dl_task_timer",
        "kernel/sched/idle.c:play_idle",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/time/alarmtimer.c:alarm_timer_create",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_timer_create",
        "kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:perf_pmu_register",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:SyS_timerfd_create",
        "fs/aio.c:read_events",
        "block/cfq-iosched.c:cfq_init_queue",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/rtc/class.c:rtc_allocate_device",
        "drivers/mailbox/mailbox.c:mbox_controller_register",
        "net/core/dev.c:netif_napi_add",
        "net/sched/sch_api.c:qdisc_watchdog_init",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579936144,
      "name": "hrtimer_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589269029,
      "name": "hrtimer_init",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1305",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_alloc_box",
        "kernel/softirq.c:tasklet_hrtimer_init",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/idle.c:play_idle",
        "kernel/sched/fair.c:init_cfs_bandwidth",
        "kernel/sched/fair.c:init_cfs_bandwidth",
        "kernel/sched/rt.c:init_rt_bandwidth",
        "kernel/sched/deadline.c:init_dl_inactive_task_timer",
        "kernel/sched/deadline.c:init_dl_task_timer",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/time/alarmtimer.c:alarm_timer_create",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_timer_create",
        "kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:perf_pmu_register",
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create",
        "fs/aio.c:read_events",
        "block/cfq-iosched.c:cfq_init_queue",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/rtc/class.c:rtc_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/mailbox/mailbox.c:mbox_controller_register",
        "net/core/dev.c:netif_napi_add",
        "net/sched/sch_api.c:qdisc_watchdog_init",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579983216,
      "name": "hrtimer_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589511589,
      "name": "hrtimer_init",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1296",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_alloc_box",
        "kernel/softirq.c:tasklet_hrtimer_init",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/idle.c:play_idle",
        "kernel/sched/fair.c:init_cfs_bandwidth",
        "kernel/sched/fair.c:init_cfs_bandwidth",
        "kernel/sched/rt.c:init_rt_bandwidth",
        "kernel/sched/deadline.c:init_dl_inactive_task_timer",
        "kernel/sched/deadline.c:init_dl_task_timer",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/time/alarmtimer.c:alarm_timer_create",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_timer_create",
        "kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:perf_pmu_register",
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create",
        "fs/aio.c:read_events",
        "drivers/base/power/runtime.c:pm_runtime_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/mailbox/mailbox.c:mbox_controller_register",
        "drivers/powercap/idle_inject.c:idle_inject_register",
        "net/core/dev.c:netif_napi_add",
        "net/sched/sch_api.c:qdisc_watchdog_init",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580030272,
      "name": "hrtimer_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589970757,
      "name": "hrtimer_init",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1296",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_alloc_box",
        "kernel/fork.c:copy_process",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/idle.c:play_idle",
        "kernel/sched/fair.c:init_cfs_bandwidth",
        "kernel/sched/fair.c:init_cfs_bandwidth",
        "kernel/sched/rt.c:init_rt_bandwidth",
        "kernel/sched/deadline.c:init_dl_inactive_task_timer",
        "kernel/sched/deadline.c:init_dl_task_timer",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/time/alarmtimer.c:alarm_timer_create",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_timer_create",
        "kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:perf_pmu_register",
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create",
        "fs/aio.c:read_events",
        "drivers/base/power/runtime.c:pm_runtime_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/mailbox/mailbox.c:mbox_controller_register",
        "drivers/powercap/idle_inject.c:idle_inject_register",
        "net/core/dev.c:netif_napi_add",
        "net/sched/sch_api.c:qdisc_watchdog_init",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580073472,
      "name": "hrtimer_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580122624,
      "name": "hrtimer_init",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1424",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_alloc_box",
        "kernel/fork.c:copy_process",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/idle.c:play_idle",
        "kernel/sched/fair.c:init_cfs_bandwidth",
        "kernel/sched/fair.c:init_cfs_bandwidth",
        "kernel/sched/rt.c:alloc_rt_sched_group",
        "kernel/sched/deadline.c:init_dl_inactive_task_timer",
        "kernel/sched/deadline.c:init_dl_task_timer",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/time/alarmtimer.c:alarm_timer_create",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_timer_create",
        "kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:perf_pmu_register",
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create",
        "fs/io_uring.c:__io_submit_sqe",
        "block/blk-iocost.c:ioc_pd_init",
        "block/blk-iocost.c:ioc_pd_init",
        "drivers/base/power/runtime.c:pm_runtime_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/mailbox/mailbox.c:mbox_controller_register",
        "drivers/powercap/idle_inject.c:idle_inject_register",
        "net/core/dev.c:netif_napi_add",
        "net/sched/sch_api.c:qdisc_watchdog_init",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580122624,
      "name": "hrtimer_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580181488,
      "name": "hrtimer_init",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1424",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_signal",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/idle.c:play_idle_precise",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/rt.c:init_rt_bandwidth",
        "kernel/sched/deadline.c:init_dl_inactive_task_timer",
        "kernel/sched/deadline.c:init_dl_task_timer",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/time/alarmtimer.c:alarm_timer_create",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_timer_create",
        "kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_switch_to_nohz",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:task_clock_event_init",
        "kernel/events/core.c:cpu_clock_event_init",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:__do_sys_timerfd_create",
        "fs/io_uring.c:io_timeout_prep",
        "block/blk-iocost.c:ioc_pd_init",
        "block/blk-iocost.c:ioc_pd_init",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_config",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_config",
        "drivers/base/power/runtime.c:pm_runtime_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/host/ehci-hcd.c:ehci_init",
        "drivers/rtc/class.c:rtc_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/mailbox/mailbox.c:mbox_controller_register",
        "drivers/powercap/idle_inject.c:idle_inject_register",
        "net/core/dev.c:netif_napi_add",
        "net/sched/sch_api.c:qdisc_watchdog_init",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580181488,
      "name": "hrtimer_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580166592,
      "name": "hrtimer_init",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1441",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_signal",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/idle.c:play_idle_precise",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/rt.c:init_rt_bandwidth",
        "kernel/sched/deadline.c:init_dl_inactive_task_timer",
        "kernel/sched/deadline.c:init_dl_task_timer",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/time/ntp.c:ntp_init",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/time/alarmtimer.c:alarm_timer_create",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_timer_create",
        "kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_switch_to_nohz",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:task_clock_event_init",
        "kernel/events/core.c:cpu_clock_event_init",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:__do_sys_timerfd_create",
        "fs/io_uring.c:io_timeout_prep",
        "fs/io_uring.c:io_timeout_remove",
        "block/blk-iocost.c:ioc_pd_init",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_config",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_config",
        "drivers/base/power/runtime.c:pm_runtime_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/host/ehci-hcd.c:ehci_init",
        "drivers/rtc/class.c:rtc_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/mailbox/mailbox.c:mbox_controller_register",
        "drivers/powercap/idle_inject.c:idle_inject_register",
        "net/core/dev.c:netif_napi_add",
        "net/sched/sch_api.c:qdisc_watchdog_init",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580166592,
      "name": "hrtimer_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580171072,
      "name": "hrtimer_init",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1441",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_signal",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/idle.c:play_idle_precise",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/rt.c:init_rt_bandwidth",
        "kernel/sched/deadline.c:init_dl_inactive_task_timer",
        "kernel/sched/deadline.c:init_dl_task_timer",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/time/ntp.c:ntp_init",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/time/alarmtimer.c:alarm_timer_create",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_timer_create",
        "kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:task_clock_event_init",
        "kernel/events/core.c:cpu_clock_event_init",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:__do_sys_timerfd_create",
        "fs/io_uring.c:io_timeout_prep",
        "block/blk-iocost.c:ioc_pd_init",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_config",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_config",
        "drivers/base/power/runtime.c:pm_runtime_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/host/ehci-hcd.c:ehci_init",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/mailbox/mailbox.c:mbox_controller_register",
        "drivers/powercap/idle_inject.c:idle_inject_register",
        "net/core/dev.c:netif_napi_add",
        "net/sched/sch_api.c:qdisc_watchdog_init",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580171072,
      "name": "hrtimer_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580315840,
      "name": "hrtimer_init",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1589",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_signal",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/idle.c:play_idle_precise",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/rt.c:init_rt_bandwidth",
        "kernel/sched/deadline.c:init_dl_inactive_task_timer",
        "kernel/sched/deadline.c:init_dl_task_timer",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/time/ntp.c:ntp_init",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/time/alarmtimer.c:alarm_timer_create",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_timer_create",
        "kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/bpf/helpers.c:bpf_timer_init",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:task_clock_event_init",
        "kernel/events/core.c:cpu_clock_event_init",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:__do_sys_timerfd_create",
        "fs/io_uring.c:io_timeout_prep",
        "block/blk-iocost.c:ioc_pd_init",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_config",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_config",
        "drivers/base/power/runtime.c:pm_runtime_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/host/ehci-hcd.c:ehci_init",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/mailbox/mailbox.c:mbox_controller_register",
        "drivers/powercap/idle_inject.c:idle_inject_register",
        "net/core/dev.c:netif_napi_add",
        "net/sched/sch_api.c:qdisc_watchdog_init",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580315840,
      "name": "hrtimer_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580528768,
      "name": "hrtimer_init",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1589",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_signal",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/build_policy.c:init_dl_inactive_task_timer",
        "kernel/sched/build_policy.c:init_dl_task_timer",
        "kernel/sched/build_policy.c:init_rt_bandwidth",
        "kernel/sched/build_policy.c:play_idle_precise",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/time/ntp.c:ntp_init",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/time/alarmtimer.c:alarm_timer_create",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_timer_create",
        "kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/bpf/helpers.c:bpf_timer_init",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:task_clock_event_init",
        "kernel/events/core.c:cpu_clock_event_init",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:__do_sys_timerfd_create",
        "block/blk-iocost.c:ioc_pd_init",
        "io_uring/io_uring.c:__io_timeout_prep",
        "io_uring/io_uring.c:io_timeout_remove",
        "io_uring/io_uring.c:io_timeout_remove",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_config",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_config",
        "drivers/base/power/runtime.c:pm_runtime_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/host/ehci-hcd.c:ehci_init",
        "drivers/rtc/class.c:rtc_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/mailbox/mailbox.c:mbox_controller_register",
        "drivers/powercap/idle_inject.c:idle_inject_register",
        "net/core/dev.c:netif_napi_add_weight",
        "net/sched/sch_api.c:qdisc_watchdog_init",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580528768,
      "name": "hrtimer_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580784832,
      "name": "hrtimer_init",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1589",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_signal",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/fair.c:alloc_fair_sched_group",
        "kernel/sched/build_policy.c:init_dl_inactive_task_timer",
        "kernel/sched/build_policy.c:init_dl_task_timer",
        "kernel/sched/build_policy.c:init_rt_bandwidth",
        "kernel/sched/build_policy.c:play_idle_precise",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/time/ntp.c:ntp_init",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/time/alarmtimer.c:alarm_timer_create",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_timer_create",
        "kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/bpf/helpers.c:bpf_timer_init",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:task_clock_event_init",
        "kernel/events/core.c:cpu_clock_event_init",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:__do_sys_timerfd_create",
        "block/blk-iocost.c:ioc_pd_init",
        "io_uring/timeout.c:__io_timeout_prep",
        "io_uring/timeout.c:io_timeout_remove",
        "io_uring/timeout.c:io_timeout_remove",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_config",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_config",
        "drivers/base/power/runtime.c:pm_runtime_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/host/ehci-hcd.c:ehci_init",
        "drivers/rtc/class.c:rtc_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/mailbox/mailbox.c:mbox_controller_register",
        "drivers/powercap/idle_inject.c:idle_inject_register",
        "net/core/dev.c:netif_napi_add_weight",
        "net/sched/sch_api.c:qdisc_watchdog_init",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580784832,
      "name": "hrtimer_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580868720,
      "name": "hrtimer_init",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1592",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_signal",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/fair.c:init_cfs_bandwidth",
        "kernel/sched/fair.c:init_cfs_bandwidth",
        "kernel/sched/build_policy.c:init_dl_inactive_task_timer",
        "kernel/sched/build_policy.c:init_dl_task_timer",
        "kernel/sched/build_policy.c:init_rt_bandwidth",
        "kernel/sched/build_policy.c:play_idle_precise",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/time/ntp.c:ntp_init",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/time/alarmtimer.c:alarm_timer_create",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_timer_create",
        "kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/trace/trace_osnoise.c:timerlat_fd_read",
        "kernel/trace/trace_osnoise.c:timerlat_main",
        "kernel/bpf/helpers.c:bpf_timer_init",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:task_clock_event_init",
        "kernel/events/core.c:cpu_clock_event_init",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:__do_sys_timerfd_create",
        "block/blk-iocost.c:ioc_pd_init",
        "io_uring/timeout.c:__io_timeout_prep",
        "io_uring/timeout.c:io_timeout_remove",
        "io_uring/timeout.c:io_timeout_remove",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_config",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_config",
        "drivers/base/power/runtime.c:pm_runtime_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/host/ehci-hcd.c:ehci_init",
        "drivers/rtc/class.c:rtc_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/mailbox/mailbox.c:mbox_controller_register",
        "drivers/powercap/idle_inject.c:idle_inject_register_full",
        "net/core/dev.c:netif_napi_add_weight",
        "net/sched/sch_api.c:qdisc_watchdog_init",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580868720,
      "name": "hrtimer_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580956432,
      "name": "hrtimer_init",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1593",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_signal",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/fair.c:init_cfs_bandwidth",
        "kernel/sched/fair.c:init_cfs_bandwidth",
        "kernel/sched/build_policy.c:init_dl_entity",
        "kernel/sched/build_policy.c:init_dl_entity",
        "kernel/sched/build_policy.c:init_rt_bandwidth",
        "kernel/sched/build_policy.c:play_idle_precise",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/time/ntp.c:ntp_init",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/time/alarmtimer.c:alarm_timer_create",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_timer_create",
        "kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/trace/trace_osnoise.c:timerlat_fd_open",
        "kernel/trace/trace_osnoise.c:timerlat_main",
        "kernel/bpf/helpers.c:bpf_timer_init",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:task_clock_event_init",
        "kernel/events/core.c:cpu_clock_event_init",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:__do_sys_timerfd_create",
        "block/blk-iocost.c:ioc_pd_init",
        "io_uring/timeout.c:__io_timeout_prep",
        "io_uring/timeout.c:io_timeout_remove",
        "io_uring/timeout.c:io_timeout_remove",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_config",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_config",
        "drivers/base/power/runtime.c:pm_runtime_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/host/ehci-hcd.c:ehci_init",
        "drivers/rtc/class.c:rtc_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/mailbox/mailbox.c:mbox_controller_register",
        "drivers/powercap/idle_inject.c:idle_inject_register_full",
        "net/core/dev.c:netif_napi_add_weight",
        "net/sched/sch_api.c:qdisc_watchdog_init",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580956432,
      "name": "hrtimer_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491339304,
      "name": "hrtimer_init",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1424",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/arm/arch_timer.c:kvm_timer_vcpu_init",
        "virt/kvm/arm/arch_timer.c:kvm_timer_vcpu_init",
        "virt/kvm/arm/arch_timer.c:kvm_timer_vcpu_init",
        "kernel/fork.c:copy_process",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/idle.c:play_idle",
        "kernel/sched/fair.c:init_cfs_bandwidth",
        "kernel/sched/fair.c:init_cfs_bandwidth",
        "kernel/sched/rt.c:alloc_rt_sched_group",
        "kernel/sched/deadline.c:init_dl_inactive_task_timer",
        "kernel/sched/deadline.c:init_dl_task_timer",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/time/alarmtimer.c:alarm_timer_create",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_timer_create",
        "kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast",
        "kernel/time/sched_clock.c:generic_sched_clock_init",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:perf_pmu_register",
        "fs/timerfd.c:__arm64_sys_timerfd_create",
        "fs/io_uring.c:__io_submit_sqe",
        "block/blk-iocost.c:ioc_pd_init",
        "block/blk-iocost.c:ioc_pd_init",
        "drivers/base/power/runtime.c:pm_runtime_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/media/cec/cec-pin.c:cec_pin_allocate_adapter",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/mailbox/mailbox.c:mbox_controller_register",
        "drivers/powercap/idle_inject.c:idle_inject_register",
        "drivers/perf/arm-ccn.c:arm_ccn_probe",
        "net/core/dev.c:netif_napi_add",
        "net/sched/sch_api.c:qdisc_watchdog_init",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491339304,
      "name": "hrtimer_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225334236,
      "name": "hrtimer_init",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1424",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_init",
        "arch/arm/mach-imx/mmdc.c:imx_mmdc_probe",
        "kernel/fork.c:copy_process",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/idle.c:play_idle",
        "kernel/sched/fair.c:init_cfs_bandwidth",
        "kernel/sched/fair.c:init_cfs_bandwidth",
        "kernel/sched/rt.c:alloc_rt_sched_group",
        "kernel/sched/deadline.c:init_dl_inactive_task_timer",
        "kernel/sched/deadline.c:init_dl_task_timer",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/time/alarmtimer.c:alarm_timer_create",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_timer_create",
        "kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast",
        "kernel/time/sched_clock.c:generic_sched_clock_init",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:perf_pmu_register",
        "fs/timerfd.c:__se_sys_timerfd_create",
        "fs/io_uring.c:__io_submit_sqe",
        "block/blk-iocost.c:ioc_pd_init",
        "block/blk-iocost.c:ioc_pd_init",
        "drivers/base/power/runtime.c:pm_runtime_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/mailbox/mailbox.c:mbox_controller_register",
        "drivers/powercap/idle_inject.c:idle_inject_register",
        "drivers/perf/arm-ccn.c:arm_ccn_probe",
        "sound/soc/fsl/imx-pcm-fiq.c:snd_imx_open",
        "net/core/dev.c:netif_napi_add",
        "net/sched/sch_api.c:qdisc_watchdog_init",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225334236,
      "name": "hrtimer_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284271808,
      "name": "hrtimer_init",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1424",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/watchdog.c:start_watchdog",
        "kernel/fork.c:copy_process",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/idle.c:play_idle",
        "kernel/sched/fair.c:init_cfs_bandwidth",
        "kernel/sched/fair.c:init_cfs_bandwidth",
        "kernel/sched/rt.c:alloc_rt_sched_group",
        "kernel/sched/deadline.c:init_dl_inactive_task_timer",
        "kernel/sched/deadline.c:init_dl_task_timer",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/time/alarmtimer.c:alarm_timer_create",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_timer_create",
        "kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:perf_pmu_register",
        "fs/timerfd.c:__se_sys_timerfd_create",
        "fs/io_uring.c:__io_submit_sqe",
        "block/blk-iocost.c:ioc_pd_init",
        "block/blk-iocost.c:ioc_pd_init",
        "drivers/base/power/runtime.c:pm_runtime_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/mailbox/mailbox.c:mbox_controller_register",
        "drivers/powercap/idle_inject.c:idle_inject_register",
        "net/core/dev.c:netif_napi_add",
        "net/sched/sch_api.c:qdisc_watchdog_init",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284271808,
      "name": "hrtimer_init",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271838068,
      "name": "hrtimer_init",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1424",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/idle.c:play_idle",
        "kernel/sched/fair.c:init_cfs_bandwidth",
        "kernel/sched/fair.c:init_cfs_bandwidth",
        "kernel/sched/rt.c:alloc_rt_sched_group",
        "kernel/sched/deadline.c:init_dl_inactive_task_timer",
        "kernel/sched/deadline.c:init_dl_task_timer",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/time/alarmtimer.c:alarm_timer_create",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_timer_create",
        "kernel/time/sched_clock.c:generic_sched_clock_init",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:perf_pmu_register",
        "fs/timerfd.c:__se_sys_timerfd_settime",
        "fs/timerfd.c:__se_sys_timerfd_create",
        "fs/io_uring.c:__io_submit_sqe",
        "block/blk-iocost.c:ioc_pd_init",
        "block/blk-iocost.c:ioc_pd_init",
        "drivers/base/power/runtime.c:pm_runtime_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/mailbox/mailbox.c:mbox_controller_register",
        "net/core/dev.c:netif_napi_add",
        "net/sched/sch_api.c:qdisc_watchdog_init",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271838068,
      "name": "hrtimer_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580091824,
      "name": "hrtimer_init",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1424",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_alloc_box",
        "kernel/fork.c:copy_process",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/idle.c:play_idle",
        "kernel/sched/fair.c:init_cfs_bandwidth",
        "kernel/sched/fair.c:init_cfs_bandwidth",
        "kernel/sched/rt.c:init_rt_bandwidth",
        "kernel/sched/deadline.c:init_dl_inactive_task_timer",
        "kernel/sched/deadline.c:init_dl_task_timer",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/time/alarmtimer.c:alarm_timer_create",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_timer_create",
        "kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:perf_pmu_register",
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create",
        "fs/io_uring.c:__io_submit_sqe",
        "block/blk-iocost.c:ioc_pd_init",
        "block/blk-iocost.c:ioc_pd_init",
        "drivers/base/power/runtime.c:pm_runtime_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/mailbox/mailbox.c:mbox_controller_register",
        "net/core/dev.c:netif_napi_add",
        "net/sched/sch_api.c:qdisc_watchdog_init",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580091824,
      "name": "hrtimer_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580037152,
      "name": "hrtimer_init",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1424",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_alloc_box",
        "kernel/fork.c:copy_process",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/idle.c:play_idle",
        "kernel/sched/fair.c:init_cfs_bandwidth",
        "kernel/sched/fair.c:init_cfs_bandwidth",
        "kernel/sched/rt.c:alloc_rt_sched_group",
        "kernel/sched/deadline.c:init_dl_inactive_task_timer",
        "kernel/sched/deadline.c:init_dl_task_timer",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/time/alarmtimer.c:alarm_timer_create",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_timer_create",
        "kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:perf_pmu_register",
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create",
        "fs/io_uring.c:__io_submit_sqe",
        "block/blk-iocost.c:ioc_pd_init",
        "block/blk-iocost.c:ioc_pd_init",
        "drivers/base/power/runtime.c:pm_runtime_init",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/mailbox/mailbox.c:mbox_controller_register",
        "net/core/dev.c:netif_napi_add",
        "net/sched/sch_api.c:qdisc_watchdog_init",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580037152,
      "name": "hrtimer_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580082896,
      "name": "hrtimer_init",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1424",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_alloc_box",
        "kernel/fork.c:copy_process",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/idle.c:play_idle",
        "kernel/sched/fair.c:init_cfs_bandwidth",
        "kernel/sched/fair.c:init_cfs_bandwidth",
        "kernel/sched/rt.c:alloc_rt_sched_group",
        "kernel/sched/deadline.c:init_dl_inactive_task_timer",
        "kernel/sched/deadline.c:init_dl_task_timer",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/time/alarmtimer.c:alarm_timer_create",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_timer_create",
        "kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:perf_pmu_register",
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create",
        "fs/io_uring.c:__io_submit_sqe",
        "block/blk-iocost.c:ioc_pd_init",
        "block/blk-iocost.c:ioc_pd_init",
        "drivers/base/power/runtime.c:pm_runtime_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/mailbox/mailbox.c:mbox_controller_register",
        "drivers/powercap/idle_inject.c:idle_inject_register",
        "net/core/dev.c:netif_napi_add",
        "net/sched/sch_api.c:qdisc_watchdog_init",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580082896,
      "name": "hrtimer_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void hrtimer_init(struct hrtimer * timer, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580134560,
      "name": "hrtimer_init",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1424",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_alloc_box",
        "kernel/fork.c:copy_process",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/idle.c:play_idle",
        "kernel/sched/fair.c:init_cfs_bandwidth",
        "kernel/sched/fair.c:init_cfs_bandwidth",
        "kernel/sched/rt.c:init_rt_bandwidth",
        "kernel/sched/deadline.c:init_dl_inactive_task_timer",
        "kernel/sched/deadline.c:init_dl_task_timer",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/time/alarmtimer.c:alarm_timer_create",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/time/posix-timers.c:common_timer_create",
        "kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/core.c:perf_pmu_register",
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create",
        "fs/io_uring.c:__io_submit_sqe",
        "block/blk-iocost.c:ioc_pd_init",
        "block/blk-iocost.c:ioc_pd_init",
        "drivers/base/power/runtime.c:pm_runtime_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/rtc/class.c:devm_rtc_allocate_device",
        "drivers/media/cec/cec-pin.c:cec_pin_allocate_adapter",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_register",
        "drivers/mailbox/mailbox.c:mbox_controller_register",
        "drivers/powercap/idle_inject.c:idle_inject_register",
        "net/core/dev.c:netif_napi_add",
        "net/sched/sch_api.c:qdisc_watchdog_init",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers",
        "net/ipv4/tcp_timer.c:tcp_init_xmit_timers",
        "net/xfrm/xfrm_state.c:xfrm_state_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580134560,
      "name": "hrtimer_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
