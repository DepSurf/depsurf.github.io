# Function: <code>hrtimer_active</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool hrtimer_active(const struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579822608,
      "name": "hrtimer_active",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1170",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:hotplug_hrtick",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/rt.c:sched_rt_bandwidth_account",
        "kernel/time/itimer.c:itimer_get_remtime",
        "kernel/time/posix-timers.c:common_timer_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579822608,
      "name": "hrtimer_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
bool hrtimer_active(const struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579851536,
      "name": "hrtimer_active",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1160",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/rt.c:sched_rt_bandwidth_account",
        "kernel/time/itimer.c:itimer_get_remtime",
        "kernel/time/posix-timers.c:common_timer_get",
        "block/cfq-iosched.c:cfq_dispatch_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851536,
      "name": "hrtimer_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
bool hrtimer_active(const struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579880144,
      "name": "hrtimer_active",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1160",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/rt.c:sched_rt_bandwidth_account",
        "kernel/time/posix-timers.c:common_timer_get",
        "kernel/time/itimer.c:itimer_get_remtime",
        "block/cfq-iosched.c:cfq_dispatch_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579880144,
      "name": "hrtimer_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
bool hrtimer_active(const struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579889696,
      "name": "hrtimer_active",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1136",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/rt.c:sched_rt_bandwidth_account",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/time/itimer.c:itimer_get_remtime",
        "kernel/time/tick-sched.c:__tick_nohz_idle_enter",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579889696,
      "name": "hrtimer_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
bool hrtimer_active(const struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579934208,
      "name": "hrtimer_active",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1141",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/rt.c:sched_rt_bandwidth_account",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/time/itimer.c:itimer_get_remtime",
        "kernel/time/tick-sched.c:__tick_nohz_idle_enter",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579934208,
      "name": "hrtimer_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
bool hrtimer_active(const struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579980752,
      "name": "hrtimer_active",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1320",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/rt.c:sched_rt_bandwidth_account",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/time/itimer.c:itimer_get_remtime",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick",
        "block/cfq-iosched.c:cfq_dispatch_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579980752,
      "name": "hrtimer_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
bool hrtimer_active(const struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580027408,
      "name": "hrtimer_active",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1311",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/rt.c:sched_rt_bandwidth_account",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/time/itimer.c:itimer_get_remtime",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580027408,
      "name": "hrtimer_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
bool hrtimer_active(const struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580070464,
      "name": "hrtimer_active",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1311",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/rt.c:sched_rt_bandwidth_account",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/time/itimer.c:itimer_get_remtime",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580070464,
      "name": "hrtimer_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
bool hrtimer_active(const struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580119840,
      "name": "hrtimer_active",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1439",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/rt.c:sched_rt_bandwidth_account",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/time/itimer.c:itimer_get_remtime",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580119840,
      "name": "hrtimer_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
bool hrtimer_active(const struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580180400,
      "name": "hrtimer_active",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1439",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/rt.c:sched_rt_bandwidth_account",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580180400,
      "name": "hrtimer_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
bool hrtimer_active(const struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580165328,
      "name": "hrtimer_active",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1456",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/rt.c:sched_rt_bandwidth_account",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick",
        "drivers/mailbox/mailbox.c:msg_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580165328,
      "name": "hrtimer_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
bool hrtimer_active(const struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580169904,
      "name": "hrtimer_active",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1456",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/rt.c:sched_rt_bandwidth_account",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick",
        "drivers/mailbox/mailbox.c:msg_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580169904,
      "name": "hrtimer_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
bool hrtimer_active(const struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580314768,
      "name": "hrtimer_active",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1604",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/rt.c:sched_rt_bandwidth_account",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick",
        "drivers/mailbox/mailbox.c:msg_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580314768,
      "name": "hrtimer_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
bool hrtimer_active(const struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580525616,
      "name": "hrtimer_active",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1604",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:update_curr_dl",
        "kernel/sched/build_policy.c:task_non_contending",
        "kernel/time/hrtimer.c:hrtimer_try_to_cancel",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580525616,
      "name": "hrtimer_active",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
bool hrtimer_active(const struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580781408,
      "name": "hrtimer_active",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1604",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:update_curr_dl",
        "kernel/sched/build_policy.c:task_non_contending",
        "kernel/time/hrtimer.c:hrtimer_try_to_cancel",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580781408,
      "name": "hrtimer_active",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
bool hrtimer_active(const struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580864400,
      "name": "hrtimer_active",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1607",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:update_curr_dl",
        "kernel/sched/build_policy.c:task_non_contending",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580864400,
      "name": "hrtimer_active",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
bool hrtimer_active(const struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580954864,
      "name": "hrtimer_active",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1608",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/build_policy.c:sched_dl_overflow",
        "kernel/sched/build_policy.c:update_curr_dl_se",
        "kernel/sched/build_policy.c:task_non_contending",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580954864,
      "name": "hrtimer_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
bool hrtimer_active(const struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491337592,
      "name": "hrtimer_active",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1439",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/rt.c:sched_rt_bandwidth_account",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/time/itimer.c:itimer_get_remtime",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491337592,
      "name": "hrtimer_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
bool hrtimer_active(const struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225330384,
      "name": "hrtimer_active",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1439",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/rt.c:sched_rt_bandwidth_account",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/time/itimer.c:itimer_get_remtime",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225330384,
      "name": "hrtimer_active",
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
bool hrtimer_active(const struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284266624,
      "name": "hrtimer_active",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1439",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/rt.c:sched_rt_bandwidth_account",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/time/itimer.c:itimer_get_remtime",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284266624,
      "name": "hrtimer_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
bool hrtimer_active(const struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271835298,
      "name": "hrtimer_active",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1439",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/rt.c:sched_rt_bandwidth_account",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/time/itimer.c:itimer_get_remtime",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271835298,
      "name": "hrtimer_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
bool hrtimer_active(const struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580089040,
      "name": "hrtimer_active",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1439",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/rt.c:sched_rt_bandwidth_account",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/time/itimer.c:itimer_get_remtime",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580089040,
      "name": "hrtimer_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
bool hrtimer_active(const struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580034368,
      "name": "hrtimer_active",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1439",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/rt.c:sched_rt_bandwidth_account",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/time/itimer.c:itimer_get_remtime",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580034368,
      "name": "hrtimer_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
bool hrtimer_active(const struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580080112,
      "name": "hrtimer_active",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1439",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/rt.c:sched_rt_bandwidth_account",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/time/itimer.c:itimer_get_remtime",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580080112,
      "name": "hrtimer_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
bool hrtimer_active(const struct hrtimer * timer)
```

```json
{
  "name": "hrtimer_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580131616,
      "name": "hrtimer_active",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1439",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/rt.c:sched_rt_bandwidth_account",
        "kernel/sched/deadline.c:sched_dl_overflow",
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/time/itimer.c:itimer_get_remtime",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580131616,
      "name": "hrtimer_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
