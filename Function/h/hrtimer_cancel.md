# Function: <code>hrtimer_cancel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hrtimer_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579824240,
      "name": "hrtimer_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1069",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "arch/x86/events/intel/cqm.c:__mbm_stop_timer",
        "arch/x86/events/intel/rapl.c:rapl_pmu_event_stop",
        "arch/x86/events/intel/rapl.c:rapl_cpu_notifier",
        "arch/x86/events/intel/uncore.c:uncore_change_context",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "kernel/exit.c:do_exit",
        "kernel/sched/core.c:hotplug_hrtick",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/time/tick-sched.c:tick_nohz_restart",
        "kernel/time/tick-sched.c:__tick_nohz_idle_enter",
        "kernel/time/tick-sched.c:tick_cancel_sched_timer",
        "kernel/futex.c:futex_wait",
        "kernel/watchdog.c:watchdog_disable",
        "fs/timerfd.c:timerfd_release",
        "fs/aio.c:read_events",
        "drivers/usb/host/ehci-hcd.c:ehci_shutdown",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "net/core/dev.c:napi_disable",
        "net/sched/sch_api.c:qdisc_watchdog_cancel",
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579824240,
      "name": "hrtimer_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int hrtimer_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587881772,
      "name": "hrtimer_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1059",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "arch/x86/events/intel/cqm.c:__mbm_stop_timer",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "kernel/exit.c:do_exit",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/time/tick-sched.c:tick_cancel_sched_timer",
        "kernel/time/tick-sched.c:__tick_nohz_idle_enter",
        "kernel/time/tick-sched.c:tick_nohz_restart",
        "kernel/futex.c:futex_wait",
        "kernel/watchdog.c:watchdog_disable",
        "fs/timerfd.c:timerfd_release",
        "fs/aio.c:read_events",
        "block/cfq-iosched.c:cfq_exit_queue",
        "block/cfq-iosched.c:cfq_exit_queue",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_shutdown",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "net/core/dev.c:napi_disable",
        "net/sched/sch_api.c:qdisc_watchdog_cancel",
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579853088,
      "name": "hrtimer_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int hrtimer_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588098509,
      "name": "hrtimer_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1059",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "arch/x86/events/intel/cqm.c:__mbm_stop_timer",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "kernel/exit.c:do_exit",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/time/tick-sched.c:tick_cancel_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_restart",
        "kernel/futex.c:futex_wait",
        "kernel/watchdog.c:watchdog_disable",
        "fs/timerfd.c:timerfd_release",
        "fs/aio.c:read_events",
        "block/blk-mq.c:blk_mq_poll_hybrid_sleep",
        "block/cfq-iosched.c:cfq_exit_queue",
        "block/cfq-iosched.c:cfq_exit_queue",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_shutdown",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "net/core/dev.c:napi_disable",
        "net/sched/sch_api.c:qdisc_watchdog_cancel",
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579881920,
      "name": "hrtimer_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int hrtimer_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588324176,
      "name": "hrtimer_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1029",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "kernel/exit.c:do_exit",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/time/tick-sched.c:tick_cancel_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:__tick_nohz_idle_enter",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/watchdog.c:watchdog_disable",
        "fs/timerfd.c:timerfd_release",
        "fs/aio.c:read_events",
        "block/cfq-iosched.c:cfq_exit_queue",
        "block/cfq-iosched.c:cfq_exit_queue",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_shutdown",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "net/core/dev.c:napi_disable",
        "net/sched/sch_api.c:qdisc_watchdog_cancel",
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579891008,
      "name": "hrtimer_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int hrtimer_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588890268,
      "name": "hrtimer_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1029",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "kernel/exit.c:do_exit",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/time/tick-sched.c:tick_cancel_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:__tick_nohz_idle_enter",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/watchdog.c:watchdog_disable",
        "fs/timerfd.c:timerfd_release",
        "fs/aio.c:read_events",
        "block/cfq-iosched.c:cfq_exit_queue",
        "block/cfq-iosched.c:cfq_exit_queue",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_shutdown",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "net/core/dev.c:napi_disable",
        "net/sched/sch_api.c:qdisc_watchdog_cancel",
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579935552,
      "name": "hrtimer_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int hrtimer_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579984416,
      "name": "hrtimer_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1167",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "kernel/exit.c:do_exit",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/time/tick-sched.c:tick_cancel_sched_timer",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/watchdog.c:watchdog_disable",
        "fs/timerfd.c:timerfd_release",
        "fs/aio.c:read_events",
        "block/cfq-iosched.c:cfq_exit_queue",
        "block/cfq-iosched.c:cfq_exit_queue",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_shutdown",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "net/core/dev.c:napi_disable",
        "net/sched/sch_api.c:qdisc_watchdog_cancel",
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579984416,
      "name": "hrtimer_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int hrtimer_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580029440,
      "name": "hrtimer_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1158",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "kernel/exit.c:do_exit",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/time/tick-sched.c:tick_cancel_sched_timer",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/watchdog.c:watchdog_disable",
        "kernel/events/core.c:cpu_clock_event_stop",
        "fs/timerfd.c:timerfd_release",
        "fs/aio.c:read_events",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_shutdown",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/powercap/idle_inject.c:idle_inject_stop",
        "net/core/dev.c:napi_disable",
        "net/sched/sch_api.c:qdisc_watchdog_cancel",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580029440,
      "name": "hrtimer_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int hrtimer_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580072480,
      "name": "hrtimer_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1158",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "kernel/exit.c:do_exit",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/time/tick-sched.c:tick_cancel_sched_timer",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/watchdog.c:watchdog_disable",
        "fs/timerfd.c:timerfd_release",
        "fs/aio.c:read_events",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_shutdown",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/powercap/idle_inject.c:idle_inject_stop",
        "net/core/dev.c:napi_disable",
        "net/sched/sch_api.c:qdisc_watchdog_cancel",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580072480,
      "name": "hrtimer_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int hrtimer_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580121792,
      "name": "hrtimer_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1273",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "kernel/exit.c:do_exit",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/sched/rt.c:free_rt_sched_group",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/time/tick-sched.c:tick_cancel_sched_timer",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/watchdog.c:watchdog_disable",
        "fs/timerfd.c:timerfd_release",
        "fs/aio.c:read_events",
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:ioc_pd_free",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_shutdown",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/powercap/idle_inject.c:idle_inject_stop",
        "net/core/dev.c:napi_disable",
        "net/sched/sch_api.c:qdisc_watchdog_cancel",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580121792,
      "name": "hrtimer_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int hrtimer_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580184448,
      "name": "hrtimer_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1273",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_change_context",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "kernel/exit.c:do_exit",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/time/tick-sched.c:tick_cancel_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick",
        "kernel/time/tick-sched.c:tick_nohz_restart",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/watchdog.c:watchdog_disable",
        "kernel/events/core.c:task_clock_event_del",
        "kernel/events/core.c:cpu_clock_event_del",
        "fs/timerfd.c:timerfd_release",
        "fs/aio.c:read_events",
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:ioc_pd_free",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_config",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_config",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_shutdown",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/powercap/idle_inject.c:idle_inject_stop",
        "net/core/dev.c:napi_disable",
        "net/sched/sch_api.c:qdisc_watchdog_cancel",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580184448,
      "name": "hrtimer_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int hrtimer_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580169248,
      "name": "hrtimer_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1290",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_change_context",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "kernel/exit.c:do_exit",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/time/tick-sched.c:tick_cancel_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick",
        "kernel/time/tick-sched.c:tick_nohz_restart",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/watchdog.c:watchdog_disable",
        "kernel/events/core.c:task_clock_event_del",
        "kernel/events/core.c:cpu_clock_event_del",
        "fs/timerfd.c:timerfd_release",
        "fs/aio.c:read_events",
        "block/blk-mq.c:blk_mq_poll_hybrid",
        "block/blk-iocost.c:ioc_pd_free",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_config",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_config",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_shutdown",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/powercap/idle_inject.c:idle_inject_stop",
        "net/core/dev.c:napi_disable",
        "net/sched/sch_api.c:qdisc_watchdog_cancel",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580169248,
      "name": "hrtimer_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int hrtimer_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591656727,
      "name": "hrtimer_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1290",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_change_context",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "kernel/exit.c:do_exit",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/time/tick-sched.c:tick_cancel_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick",
        "kernel/time/tick-sched.c:tick_nohz_restart",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/watchdog.c:watchdog_disable",
        "kernel/events/core.c:task_clock_event_del",
        "kernel/events/core.c:cpu_clock_event_del",
        "fs/timerfd.c:timerfd_release",
        "fs/aio.c:read_events",
        "block/blk-mq.c:blk_mq_poll_hybrid",
        "block/blk-iocost.c:ioc_pd_free",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_config",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_config",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_shutdown",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/powercap/idle_inject.c:idle_inject_stop",
        "net/core/dev.c:napi_disable",
        "net/sched/sch_api.c:qdisc_watchdog_cancel",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580173584,
      "name": "hrtimer_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int hrtimer_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592830423,
      "name": "hrtimer_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1438",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_change_context",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "kernel/exit.c:do_exit",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:unregister_fair_sched_group",
        "kernel/sched/fair.c:unregister_fair_sched_group",
        "kernel/time/tick-sched.c:tick_cancel_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick",
        "kernel/time/tick-sched.c:tick_nohz_restart",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/watchdog.c:lockup_detector_offline_cpu",
        "kernel/watchdog.c:softlockup_stop_fn",
        "kernel/bpf/helpers.c:bpf_timer_cancel_and_free",
        "kernel/bpf/helpers.c:bpf_timer_cancel",
        "kernel/events/core.c:task_clock_event_del",
        "kernel/events/core.c:cpu_clock_event_del",
        "fs/timerfd.c:timerfd_release",
        "fs/aio.c:read_events",
        "block/blk-mq.c:blk_mq_poll_hybrid",
        "block/blk-iocost.c:ioc_pd_free",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_config",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_config",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_shutdown",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_suspend",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/powercap/idle_inject.c:idle_inject_stop",
        "net/core/dev.c:napi_disable",
        "net/sched/sch_api.c:qdisc_watchdog_cancel",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580317552,
      "name": "hrtimer_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int hrtimer_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580527600,
      "name": "hrtimer_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1438",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_change_context",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "kernel/exit.c:do_exit",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:unregister_fair_sched_group",
        "kernel/sched/fair.c:unregister_fair_sched_group",
        "kernel/time/tick-sched.c:tick_cancel_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick",
        "kernel/time/tick-sched.c:tick_nohz_restart",
        "kernel/futex/syscalls.c:__do_sys_futex_waitv",
        "kernel/futex/pi.c:futex_lock_pi",
        "kernel/futex/pi.c:futex_lock_pi",
        "kernel/futex/pi.c:futex_lock_pi",
        "kernel/futex/requeue.c:futex_wait_requeue_pi",
        "kernel/futex/waitwake.c:futex_wait",
        "kernel/watchdog.c:lockup_detector_offline_cpu",
        "kernel/watchdog.c:softlockup_stop_fn",
        "kernel/bpf/helpers.c:bpf_timer_cancel_and_free",
        "kernel/bpf/helpers.c:bpf_timer_cancel",
        "kernel/events/core.c:task_clock_event_del",
        "kernel/events/core.c:cpu_clock_event_del",
        "fs/timerfd.c:timerfd_release",
        "fs/aio.c:read_events",
        "block/blk-mq.c:blk_mq_poll_hybrid",
        "block/blk-iocost.c:ioc_pd_free",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_config",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_config",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_shutdown",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_suspend",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_stop",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/powercap/idle_inject.c:idle_inject_stop",
        "net/core/dev.c:napi_disable",
        "net/sched/sch_api.c:qdisc_watchdog_cancel",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580527600,
      "name": "hrtimer_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int hrtimer_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580784512,
      "name": "hrtimer_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1438",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_change_context",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "kernel/exit.c:do_exit",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:unregister_fair_sched_group",
        "kernel/sched/fair.c:unregister_fair_sched_group",
        "kernel/time/tick-sched.c:tick_cancel_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick",
        "kernel/time/tick-sched.c:tick_nohz_restart",
        "kernel/futex/syscalls.c:__do_sys_futex_waitv",
        "kernel/futex/pi.c:futex_lock_pi",
        "kernel/futex/pi.c:futex_lock_pi",
        "kernel/futex/pi.c:futex_lock_pi",
        "kernel/futex/requeue.c:futex_wait_requeue_pi",
        "kernel/futex/waitwake.c:futex_wait",
        "kernel/watchdog.c:lockup_detector_offline_cpu",
        "kernel/watchdog.c:softlockup_stop_fn",
        "kernel/bpf/helpers.c:bpf_timer_cancel_and_free",
        "kernel/bpf/helpers.c:bpf_timer_cancel",
        "kernel/events/core.c:task_clock_event_del",
        "kernel/events/core.c:cpu_clock_event_del",
        "fs/timerfd.c:timerfd_release",
        "fs/aio.c:read_events",
        "block/blk-mq.c:blk_mq_poll_hybrid",
        "block/blk-iocost.c:ioc_pd_free",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_config",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_config",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_shutdown",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_suspend",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_update_worker",
        "drivers/powercap/idle_inject.c:idle_inject_stop",
        "net/core/dev.c:napi_disable",
        "net/sched/sch_api.c:qdisc_watchdog_cancel",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580784512,
      "name": "hrtimer_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int hrtimer_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597032172,
      "name": "hrtimer_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1441",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_change_context",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "kernel/exit.c:do_exit",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:destroy_cfs_bandwidth",
        "kernel/sched/fair.c:destroy_cfs_bandwidth",
        "kernel/time/tick-sched.c:tick_cancel_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick",
        "kernel/time/tick-sched.c:tick_nohz_restart",
        "kernel/futex/syscalls.c:__do_sys_futex_waitv",
        "kernel/futex/pi.c:futex_lock_pi",
        "kernel/futex/pi.c:futex_lock_pi",
        "kernel/futex/pi.c:futex_lock_pi",
        "kernel/futex/requeue.c:futex_wait_requeue_pi",
        "kernel/futex/waitwake.c:futex_wait",
        "kernel/watchdog.c:lockup_detector_offline_cpu",
        "kernel/watchdog.c:softlockup_stop_fn",
        "kernel/trace/trace_osnoise.c:timerlat_fd_release",
        "kernel/trace/trace_osnoise.c:timerlat_main",
        "kernel/bpf/helpers.c:bpf_timer_cancel_and_free",
        "kernel/bpf/helpers.c:bpf_timer_cancel",
        "kernel/events/core.c:task_clock_event_del",
        "kernel/events/core.c:cpu_clock_event_del",
        "fs/timerfd.c:timerfd_release",
        "fs/aio.c:read_events",
        "block/blk-iocost.c:ioc_pd_free",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_config",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_config",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_shutdown",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_suspend",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_update_worker",
        "drivers/powercap/idle_inject.c:idle_inject_stop",
        "net/core/dev.c:napi_disable",
        "net/sched/sch_api.c:qdisc_watchdog_cancel",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580869536,
      "name": "hrtimer_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int hrtimer_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597961564,
      "name": "hrtimer_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1442",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_change_context",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "kernel/exit.c:do_exit",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:destroy_cfs_bandwidth",
        "kernel/sched/fair.c:destroy_cfs_bandwidth",
        "kernel/time/tick-sched.c:tick_cancel_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_restart_sched_tick",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick",
        "kernel/futex/syscalls.c:__ia32_sys_futex_wait",
        "kernel/futex/syscalls.c:__x64_sys_futex_wait",
        "kernel/futex/syscalls.c:__do_sys_futex_waitv",
        "kernel/futex/pi.c:futex_lock_pi",
        "kernel/futex/pi.c:futex_lock_pi",
        "kernel/futex/pi.c:futex_lock_pi",
        "kernel/futex/requeue.c:futex_wait_requeue_pi",
        "kernel/futex/waitwake.c:futex_wait",
        "kernel/watchdog.c:lockup_detector_offline_cpu",
        "kernel/watchdog.c:softlockup_stop_fn",
        "kernel/trace/trace_osnoise.c:timerlat_fd_release",
        "kernel/trace/trace_osnoise.c:timerlat_main",
        "kernel/bpf/helpers.c:bpf_timer_cancel_and_free",
        "kernel/bpf/helpers.c:bpf_timer_cancel",
        "kernel/events/core.c:task_clock_event_del",
        "kernel/events/core.c:cpu_clock_event_del",
        "fs/timerfd.c:timerfd_release",
        "fs/aio.c:read_events",
        "block/blk-iocost.c:ioc_pd_free",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_config",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_config",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_shutdown",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_suspend",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_update_worker",
        "drivers/powercap/idle_inject.c:idle_inject_stop",
        "net/core/dev.c:napi_disable",
        "net/sched/sch_api.c:qdisc_watchdog_cancel",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580960032,
      "name": "hrtimer_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int hrtimer_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491342864,
      "name": "hrtimer_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1273",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "virt/kvm/arm/arch_timer.c:kvm_timer_vcpu_terminate",
        "virt/kvm/arm/arch_timer.c:kvm_timer_vcpu_reset",
        "virt/kvm/arm/arch_timer.c:kvm_timer_vcpu_put",
        "virt/kvm/arm/arch_timer.c:kvm_timer_vcpu_load",
        "virt/kvm/arm/arch_timer.c:kvm_timer_vcpu_load",
        "kernel/exit.c:do_exit",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/sched/rt.c:free_rt_sched_group",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/time/sched_clock.c:sched_clock_suspend",
        "kernel/time/tick-sched.c:tick_cancel_sched_timer",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/watchdog.c:watchdog_disable",
        "kernel/events/core.c:task_clock_event_stop",
        "fs/timerfd.c:timerfd_release",
        "fs/aio.c:read_events",
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:ioc_pd_free",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_shutdown",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/media/cec/cec-pin.c:cec_pin_adap_enable",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_remove",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_remove",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/powercap/idle_inject.c:idle_inject_stop",
        "drivers/perf/arm-ccn.c:arm_ccn_pmu_event_del",
        "net/core/dev.c:napi_disable",
        "net/sched/sch_api.c:qdisc_watchdog_cancel",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491342864,
      "name": "hrtimer_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int hrtimer_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_cancel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225332864,
      "name": "hrtimer_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1273",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_event_del",
        "arch/arm/mach-imx/mmdc.c:imx_mmdc_probe",
        "arch/arm/mach-imx/mmdc.c:mmdc_pmu_event_del",
        "kernel/exit.c:do_exit",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/sched/rt.c:free_rt_sched_group",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/sched_clock.c:sched_clock_suspend",
        "kernel/time/tick-sched.c:tick_cancel_sched_timer",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/watchdog.c:watchdog_disable",
        "fs/timerfd.c:timerfd_release",
        "fs/aio.c:do_io_getevents",
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:ioc_pd_free",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_shutdown",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_remove",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_remove",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/powercap/idle_inject.c:idle_inject_stop",
        "drivers/perf/arm-ccn.c:arm_ccn_pmu_event_del",
        "sound/soc/fsl/imx-pcm-fiq.c:snd_imx_close",
        "net/core/dev.c:napi_disable",
        "net/sched/sch_api.c:qdisc_watchdog_cancel",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225332864,
      "name": "hrtimer_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int hrtimer_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_cancel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284270448,
      "name": "hrtimer_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1273",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/watchdog.c:stop_watchdog",
        "kernel/exit.c:do_exit",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/sched/rt.c:free_rt_sched_group",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/tick-sched.c:tick_cancel_sched_timer",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/watchdog.c:watchdog_disable",
        "kernel/watchdog.c:watchdog_disable",
        "fs/timerfd.c:timerfd_release",
        "fs/aio.c:read_events",
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:ioc_pd_free",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_shutdown",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_remove",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_remove",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/powercap/idle_inject.c:idle_inject_stop",
        "net/core/dev.c:napi_disable",
        "net/sched/sch_api.c:qdisc_watchdog_cancel",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284270448,
      "name": "hrtimer_cancel",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int hrtimer_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279808972,
      "name": "hrtimer_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1273",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "kernel/exit.c:do_exit",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/sched/rt.c:free_rt_sched_group",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/time/sched_clock.c:sched_clock_suspend",
        "kernel/time/tick-sched.c:tick_cancel_sched_timer",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/watchdog.c:watchdog_disable",
        "kernel/events/core.c:cpu_clock_event_stop",
        "fs/timerfd.c:timerfd_release",
        "fs/aio.c:read_events",
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:ioc_pd_free",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_shutdown",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_remove",
        "drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_remove",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "net/core/dev.c:napi_disable",
        "net/sched/sch_api.c:qdisc_watchdog_cancel",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271836998,
      "name": "hrtimer_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int hrtimer_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580090992,
      "name": "hrtimer_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1273",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "kernel/exit.c:do_exit",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/time/tick-sched.c:tick_cancel_sched_timer",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/watchdog.c:watchdog_disable",
        "fs/timerfd.c:timerfd_release",
        "fs/aio.c:read_events",
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:ioc_pd_free",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_shutdown",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "net/core/dev.c:napi_disable",
        "net/sched/sch_api.c:qdisc_watchdog_cancel",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580090992,
      "name": "hrtimer_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int hrtimer_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580036320,
      "name": "hrtimer_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1273",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "kernel/exit.c:do_exit",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/sched/rt.c:free_rt_sched_group",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/time/tick-sched.c:tick_cancel_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_restart_sched_tick",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/watchdog.c:watchdog_disable",
        "fs/timerfd.c:timerfd_release",
        "fs/aio.c:read_events",
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:ioc_pd_free",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "net/core/dev.c:napi_disable",
        "net/sched/sch_api.c:qdisc_watchdog_cancel",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580036320,
      "name": "hrtimer_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int hrtimer_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580082064,
      "name": "hrtimer_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1273",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "kernel/exit.c:do_exit",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/sched/rt.c:free_rt_sched_group",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/time/tick-sched.c:tick_cancel_sched_timer",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/watchdog.c:watchdog_disable",
        "fs/timerfd.c:timerfd_release",
        "fs/aio.c:read_events",
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:ioc_pd_free",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_shutdown",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/powercap/idle_inject.c:idle_inject_stop",
        "net/core/dev.c:napi_disable",
        "net/sched/sch_api.c:qdisc_watchdog_cancel",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580082064,
      "name": "hrtimer_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int hrtimer_cancel(struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_cancel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580133648,
      "name": "hrtimer_cancel",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1273",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_stop",
        "kernel/exit.c:do_exit",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/sched/fair.c:free_fair_sched_group",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/time/tick-sched.c:tick_cancel_sched_timer",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/watchdog.c:watchdog_disable",
        "fs/timerfd.c:timerfd_release",
        "fs/aio.c:read_events",
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:ioc_pd_free",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/host/ehci-hcd.c:ehci_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_shutdown",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_suspend",
        "drivers/media/cec/cec-pin.c:cec_pin_adap_enable",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/powercap/idle_inject.c:idle_inject_stop",
        "net/core/dev.c:napi_disable",
        "net/sched/sch_api.c:qdisc_watchdog_cancel",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580133648,
      "name": "hrtimer_cancel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
