# Function: <code>hrtimer_forward</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
u64 hrtimer_forward(struct hrtimer * timer, ktime_t now, ktime_t interval)
```

```json
{
  "name": "hrtimer_forward",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579822944,
      "name": "hrtimer_forward",
      "external": true,
      "loc": "kernel/time/hrtimer.c:833",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/cqm.c:mbm_hrtimer_handle",
        "arch/x86/events/intel/rapl.c:rapl_hrtimer_handle",
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:posix_timer_fn",
        "kernel/time/posix-timers.c:do_schedule_next_timer",
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:tick_nohz_restart",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "kernel/events/core.c:perf_swevent_hrtimer",
        "fs/timerfd.c:timerfd_read",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "drivers/rtc/interface.c:rtc_pie_update_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579822944,
      "name": "hrtimer_forward",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
u64 hrtimer_forward(struct hrtimer * timer, ktime_t now, ktime_t interval)
```

```json
{
  "name": "hrtimer_forward",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579851680,
      "name": "hrtimer_forward",
      "external": true,
      "loc": "kernel/time/hrtimer.c:823",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/cqm.c:mbm_hrtimer_handle",
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:posix_timer_fn",
        "kernel/time/posix-timers.c:do_schedule_next_timer",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:tick_nohz_restart",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/events/core.c:perf_swevent_hrtimer",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_read",
        "drivers/rtc/interface.c:rtc_pie_update_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851680,
      "name": "hrtimer_forward",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
u64 hrtimer_forward(struct hrtimer * timer, ktime_t now, ktime_t interval)
```

```json
{
  "name": "hrtimer_forward",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579880528,
      "name": "hrtimer_forward",
      "external": true,
      "loc": "kernel/time/hrtimer.c:823",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/cqm.c:mbm_hrtimer_handle",
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/posix-timers.c:posix_timer_fn",
        "kernel/time/posix-timers.c:do_schedule_next_timer",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:tick_nohz_restart",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/events/core.c:perf_swevent_hrtimer",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_read",
        "drivers/rtc/interface.c:rtc_pie_update_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579880528,
      "name": "hrtimer_forward",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
u64 hrtimer_forward(struct hrtimer * timer, ktime_t now, ktime_t interval)
```

```json
{
  "name": "hrtimer_forward",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579889456,
      "name": "hrtimer_forward",
      "external": true,
      "loc": "kernel/time/hrtimer.c:796",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/time/posix-timers.c:common_hrtimer_forward",
        "kernel/time/posix-timers.c:posix_timer_fn",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/events/core.c:perf_swevent_hrtimer",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_read",
        "drivers/rtc/interface.c:rtc_pie_update_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579889456,
      "name": "hrtimer_forward",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
u64 hrtimer_forward(struct hrtimer * timer, ktime_t now, ktime_t interval)
```

```json
{
  "name": "hrtimer_forward",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579933968,
      "name": "hrtimer_forward",
      "external": true,
      "loc": "kernel/time/hrtimer.c:796",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/time/posix-timers.c:common_hrtimer_forward",
        "kernel/time/posix-timers.c:posix_timer_fn",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/events/core.c:perf_swevent_hrtimer",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_read",
        "drivers/rtc/interface.c:rtc_pie_update_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579933968,
      "name": "hrtimer_forward",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
u64 hrtimer_forward(struct hrtimer * timer, ktime_t now, ktime_t interval)
```

```json
{
  "name": "hrtimer_forward",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579980512,
      "name": "hrtimer_forward",
      "external": true,
      "loc": "kernel/time/hrtimer.c:907",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/time/posix-timers.c:common_hrtimer_forward",
        "kernel/time/posix-timers.c:posix_timer_fn",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/events/core.c:perf_swevent_hrtimer",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:timerfd_read",
        "drivers/rtc/interface.c:rtc_pie_update_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579980512,
      "name": "hrtimer_forward",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
u64 hrtimer_forward(struct hrtimer * timer, ktime_t now, ktime_t interval)
```

```json
{
  "name": "hrtimer_forward",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580027168,
      "name": "hrtimer_forward",
      "external": true,
      "loc": "kernel/time/hrtimer.c:898",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/time/posix-timers.c:common_hrtimer_forward",
        "kernel/time/posix-timers.c:posix_timer_fn",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/events/core.c:perf_swevent_hrtimer",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:timerfd_read",
        "drivers/rtc/interface.c:rtc_pie_update_irq",
        "drivers/powercap/idle_inject.c:idle_inject_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580027168,
      "name": "hrtimer_forward",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
u64 hrtimer_forward(struct hrtimer * timer, ktime_t now, ktime_t interval)
```

```json
{
  "name": "hrtimer_forward",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hrtimer_forward",
      "external": true,
      "loc": "kernel/time/hrtimer.c:897",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/time/posix-timers.c:common_hrtimer_forward",
        "kernel/time/posix-timers.c:posix_timer_fn",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/events/core.c:perf_swevent_hrtimer",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:timerfd_read",
        "drivers/rtc/interface.c:rtc_pie_update_irq",
        "drivers/powercap/idle_inject.c:idle_inject_timer_fn",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580077431,
      "name": "hrtimer_forward.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071580071600,
      "name": "hrtimer_forward",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
u64 hrtimer_forward(struct hrtimer * timer, ktime_t now, ktime_t interval)
```

```json
{
  "name": "hrtimer_forward",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580119472,
      "name": "hrtimer_forward",
      "external": true,
      "loc": "kernel/time/hrtimer.c:918",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/rt.c:__enqueue_rt_entity",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/time/posix-timers.c:common_hrtimer_forward",
        "kernel/time/posix-timers.c:posix_timer_fn",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/events/core.c:perf_swevent_hrtimer",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:timerfd_read",
        "drivers/rtc/interface.c:rtc_pie_update_irq",
        "drivers/powercap/idle_inject.c:idle_inject_timer_fn",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580119472,
      "name": "hrtimer_forward",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
u64 hrtimer_forward(struct hrtimer * timer, ktime_t now, ktime_t interval)
```

```json
{
  "name": "hrtimer_forward",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580180224,
      "name": "hrtimer_forward",
      "external": true,
      "loc": "kernel/time/hrtimer.c:918",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/rt.c:__enqueue_rt_entity",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/time/posix-timers.c:common_hrtimer_forward",
        "kernel/time/posix-timers.c:posix_timer_fn",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_switch_to_nohz",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:tick_nohz_restart",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/events/core.c:perf_swevent_hrtimer",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_read",
        "drivers/rtc/interface.c:rtc_pie_update_irq",
        "drivers/mailbox/mailbox.c:txdone_hrtimer",
        "drivers/powercap/idle_inject.c:idle_inject_timer_fn",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580180224,
      "name": "hrtimer_forward",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
u64 hrtimer_forward(struct hrtimer * timer, ktime_t now, ktime_t interval)
```

```json
{
  "name": "hrtimer_forward",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580165152,
      "name": "hrtimer_forward",
      "external": true,
      "loc": "kernel/time/hrtimer.c:935",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/rt.c:__enqueue_rt_entity",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/time/posix-timers.c:common_hrtimer_forward",
        "kernel/time/posix-timers.c:posix_timer_fn",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_switch_to_nohz",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:tick_nohz_restart",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/events/core.c:perf_swevent_hrtimer",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_read",
        "drivers/rtc/interface.c:rtc_pie_update_irq",
        "drivers/mailbox/mailbox.c:txdone_hrtimer",
        "drivers/powercap/idle_inject.c:idle_inject_timer_fn",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580165152,
      "name": "hrtimer_forward",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
u64 hrtimer_forward(struct hrtimer * timer, ktime_t now, ktime_t interval)
```

```json
{
  "name": "hrtimer_forward",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580169728,
      "name": "hrtimer_forward",
      "external": true,
      "loc": "kernel/time/hrtimer.c:935",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/rt.c:__enqueue_rt_entity",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/time/posix-timers.c:common_hrtimer_forward",
        "kernel/time/posix-timers.c:posix_timer_fn",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:tick_nohz_restart",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/events/core.c:perf_swevent_hrtimer",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_read",
        "drivers/rtc/interface.c:rtc_pie_update_irq",
        "drivers/mailbox/mailbox.c:txdone_hrtimer",
        "drivers/powercap/idle_inject.c:idle_inject_timer_fn",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580169728,
      "name": "hrtimer_forward",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
u64 hrtimer_forward(struct hrtimer * timer, ktime_t now, ktime_t interval)
```

```json
{
  "name": "hrtimer_forward",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580314592,
      "name": "hrtimer_forward",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1037",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/time/posix-timers.c:common_hrtimer_forward",
        "kernel/time/posix-timers.c:posix_timer_fn",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:tick_nohz_restart",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/events/core.c:perf_swevent_hrtimer",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_read",
        "drivers/rtc/interface.c:rtc_pie_update_irq",
        "drivers/mailbox/mailbox.c:txdone_hrtimer",
        "drivers/powercap/idle_inject.c:idle_inject_timer_fn",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580314592,
      "name": "hrtimer_forward",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
u64 hrtimer_forward(struct hrtimer * timer, ktime_t now, ktime_t interval)
```

```json
{
  "name": "hrtimer_forward",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580525392,
      "name": "hrtimer_forward",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1037",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/build_policy.c:enqueue_task_rt",
        "kernel/sched/build_policy.c:update_curr_rt",
        "kernel/sched/build_policy.c:sched_rt_period_timer",
        "kernel/time/posix-timers.c:common_hrtimer_forward",
        "kernel/time/posix-timers.c:posix_timer_fn",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:tick_nohz_restart",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/events/core.c:perf_swevent_hrtimer",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_read",
        "drivers/rtc/interface.c:rtc_pie_update_irq",
        "drivers/mailbox/mailbox.c:txdone_hrtimer",
        "drivers/powercap/idle_inject.c:idle_inject_timer_fn",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580525392,
      "name": "hrtimer_forward",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
u64 hrtimer_forward(struct hrtimer * timer, ktime_t now, ktime_t interval)
```

```json
{
  "name": "hrtimer_forward",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580781168,
      "name": "hrtimer_forward",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1037",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/build_policy.c:enqueue_task_rt",
        "kernel/sched/build_policy.c:update_curr_rt",
        "kernel/sched/build_policy.c:sched_rt_period_timer",
        "kernel/time/posix-timers.c:common_hrtimer_forward",
        "kernel/time/posix-timers.c:posix_timer_fn",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:tick_nohz_restart",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/events/core.c:perf_swevent_hrtimer",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_read",
        "drivers/rtc/interface.c:rtc_pie_update_irq",
        "drivers/mailbox/mailbox.c:txdone_hrtimer",
        "drivers/powercap/idle_inject.c:idle_inject_timer_fn",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580781168,
      "name": "hrtimer_forward",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
u64 hrtimer_forward(struct hrtimer * timer, ktime_t now, ktime_t interval)
```

```json
{
  "name": "hrtimer_forward",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580864160,
      "name": "hrtimer_forward",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1040",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/build_policy.c:enqueue_task_rt",
        "kernel/sched/build_policy.c:update_curr_rt",
        "kernel/sched/build_policy.c:sched_rt_period_timer",
        "kernel/time/posix-timers.c:common_hrtimer_forward",
        "kernel/time/posix-timers.c:posix_timer_fn",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:tick_nohz_restart",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/events/core.c:perf_swevent_hrtimer",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_read",
        "drivers/rtc/interface.c:rtc_pie_update_irq",
        "drivers/mailbox/mailbox.c:txdone_hrtimer",
        "drivers/powercap/idle_inject.c:idle_inject_timer_fn",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580864160,
      "name": "hrtimer_forward",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
u64 hrtimer_forward(struct hrtimer * timer, ktime_t now, ktime_t interval)
```

```json
{
  "name": "hrtimer_forward",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580954624,
      "name": "hrtimer_forward",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1040",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/build_policy.c:enqueue_task_rt",
        "kernel/sched/build_policy.c:update_curr_rt",
        "kernel/sched/build_policy.c:sched_rt_period_timer",
        "kernel/time/posix-timers.c:common_hrtimer_forward",
        "kernel/time/posix-timers.c:posix_timer_fn",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_highres_handler",
        "kernel/time/tick-sched.c:tick_nohz_lowres_handler",
        "kernel/time/tick-sched.c:tick_nohz_restart_sched_tick",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/events/core.c:perf_swevent_hrtimer",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_read",
        "drivers/rtc/interface.c:rtc_pie_update_irq",
        "drivers/mailbox/mailbox.c:txdone_hrtimer",
        "drivers/powercap/idle_inject.c:idle_inject_timer_fn",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580954624,
      "name": "hrtimer_forward",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
u64 hrtimer_forward(struct hrtimer * timer, ktime_t now, ktime_t interval)
```

```json
{
  "name": "hrtimer_forward",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491337352,
      "name": "hrtimer_forward",
      "external": true,
      "loc": "kernel/time/hrtimer.c:918",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/arm/arch_timer.c:kvm_hrtimer_expire",
        "virt/kvm/arm/arch_timer.c:kvm_bg_timer_expire",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/rt.c:__enqueue_rt_entity",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/time/posix-timers.c:common_hrtimer_forward",
        "kernel/time/posix-timers.c:posix_timer_fn",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/sched_clock.c:sched_clock_poll",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/events/core.c:perf_swevent_hrtimer",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:timerfd_read",
        "drivers/rtc/interface.c:rtc_pie_update_irq",
        "drivers/media/cec/cec-pin.c:cec_pin_timer",
        "drivers/media/cec/cec-pin.c:cec_pin_timer",
        "drivers/media/cec/cec-pin.c:cec_pin_timer",
        "drivers/media/cec/cec-pin.c:cec_pin_timer",
        "drivers/media/cec/cec-pin.c:cec_pin_timer",
        "drivers/powercap/idle_inject.c:idle_inject_timer_fn",
        "drivers/perf/arm-ccn.c:arm_ccn_pmu_timer_handler",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491337352,
      "name": "hrtimer_forward",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
u64 hrtimer_forward(struct hrtimer * timer, ktime_t now, ktime_t interval)
```

```json
{
  "name": "hrtimer_forward",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225335876,
      "name": "hrtimer_forward",
      "external": true,
      "loc": "kernel/time/hrtimer.c:918",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_poll",
        "arch/arm/mach-imx/mmdc.c:mmdc_pmu_timer_handler",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/rt.c:__enqueue_rt_entity",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/time/posix-timers.c:common_hrtimer_forward",
        "kernel/time/posix-timers.c:posix_timer_fn",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/sched_clock.c:sched_clock_poll",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/events/core.c:perf_swevent_hrtimer",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:timerfd_read",
        "drivers/rtc/interface.c:rtc_pie_update_irq",
        "drivers/powercap/idle_inject.c:idle_inject_timer_fn",
        "drivers/perf/arm-ccn.c:arm_ccn_pmu_timer_handler",
        "sound/soc/fsl/imx-pcm-fiq.c:snd_hrtimer_callback",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225335876,
      "name": "hrtimer_forward",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
u64 hrtimer_forward(struct hrtimer * timer, ktime_t now, ktime_t interval)
```

```json
{
  "name": "hrtimer_forward",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284269008,
      "name": "hrtimer_forward",
      "external": true,
      "loc": "kernel/time/hrtimer.c:918",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/watchdog.c:watchdog_timer_fn",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/rt.c:__enqueue_rt_entity",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/time/posix-timers.c:common_hrtimer_forward",
        "kernel/time/posix-timers.c:posix_timer_fn",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/events/core.c:perf_swevent_hrtimer",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:timerfd_read",
        "drivers/rtc/interface.c:rtc_pie_update_irq",
        "drivers/powercap/idle_inject.c:idle_inject_timer_fn",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284269008,
      "name": "hrtimer_forward",
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
u64 hrtimer_forward(struct hrtimer * timer, ktime_t now, ktime_t interval)
```

```json
{
  "name": "hrtimer_forward",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271834936,
      "name": "hrtimer_forward",
      "external": true,
      "loc": "kernel/time/hrtimer.c:918",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/rt.c:__enqueue_rt_entity",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/time/posix-timers.c:common_hrtimer_forward",
        "kernel/time/posix-timers.c:posix_timer_fn",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/sched_clock.c:sched_clock_poll",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/events/core.c:perf_swevent_hrtimer",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "fs/timerfd.c:__se_sys_timerfd_gettime",
        "fs/timerfd.c:__se_sys_timerfd_settime",
        "fs/timerfd.c:timerfd_read",
        "drivers/rtc/interface.c:rtc_pie_update_irq",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271834936,
      "name": "hrtimer_forward",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
u64 hrtimer_forward(struct hrtimer * timer, ktime_t now, ktime_t interval)
```

```json
{
  "name": "hrtimer_forward",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580088672,
      "name": "hrtimer_forward",
      "external": true,
      "loc": "kernel/time/hrtimer.c:918",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/time/posix-timers.c:common_hrtimer_forward",
        "kernel/time/posix-timers.c:posix_timer_fn",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/events/core.c:perf_swevent_hrtimer",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:timerfd_read",
        "drivers/rtc/interface.c:rtc_pie_update_irq",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580088672,
      "name": "hrtimer_forward",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
u64 hrtimer_forward(struct hrtimer * timer, ktime_t now, ktime_t interval)
```

```json
{
  "name": "hrtimer_forward",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580034000,
      "name": "hrtimer_forward",
      "external": true,
      "loc": "kernel/time/hrtimer.c:918",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/rt.c:__enqueue_rt_entity",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/time/posix-timers.c:common_hrtimer_forward",
        "kernel/time/posix-timers.c:posix_timer_fn",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:tick_nohz_restart_sched_tick",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/events/core.c:perf_swevent_hrtimer",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:timerfd_read",
        "drivers/rtc/interface.c:rtc_pie_update_irq",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580034000,
      "name": "hrtimer_forward",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
u64 hrtimer_forward(struct hrtimer * timer, ktime_t now, ktime_t interval)
```

```json
{
  "name": "hrtimer_forward",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580079744,
      "name": "hrtimer_forward",
      "external": true,
      "loc": "kernel/time/hrtimer.c:918",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/rt.c:__enqueue_rt_entity",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/time/posix-timers.c:common_hrtimer_forward",
        "kernel/time/posix-timers.c:posix_timer_fn",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/events/core.c:perf_swevent_hrtimer",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:timerfd_read",
        "drivers/rtc/interface.c:rtc_pie_update_irq",
        "drivers/powercap/idle_inject.c:idle_inject_timer_fn",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580079744,
      "name": "hrtimer_forward",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
u64 hrtimer_forward(struct hrtimer * timer, ktime_t now, ktime_t interval)
```

```json
{
  "name": "hrtimer_forward",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580131248,
      "name": "hrtimer_forward",
      "external": true,
      "loc": "kernel/time/hrtimer.c:918",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer",
        "kernel/signal.c:dequeue_signal",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/sched/rt.c:sched_rt_period_timer",
        "kernel/time/posix-timers.c:common_hrtimer_forward",
        "kernel/time/posix-timers.c:posix_timer_fn",
        "kernel/time/posix-timers.c:common_hrtimer_rearm",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_setup_sched_timer",
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/events/core.c:perf_swevent_hrtimer",
        "kernel/events/core.c:perf_mux_hrtimer_restart",
        "kernel/events/core.c:perf_mux_hrtimer_handler",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:timerfd_read",
        "drivers/rtc/interface.c:rtc_pie_update_irq",
        "drivers/media/cec/cec-pin.c:cec_pin_timer",
        "drivers/media/cec/cec-pin.c:cec_pin_timer",
        "drivers/media/cec/cec-pin.c:cec_pin_timer",
        "drivers/powercap/idle_inject.c:idle_inject_timer_fn",
        "net/xfrm/xfrm_state.c:xfrm_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580131248,
      "name": "hrtimer_forward",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
