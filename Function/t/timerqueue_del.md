# Function: <code>timerqueue_del</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool timerqueue_del(struct timerqueue_head * head, struct timerqueue_node * node)
```

```json
{
  "name": "timerqueue_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582982848,
      "name": "timerqueue_del",
      "external": true,
      "loc": "lib/timerqueue.c:75",
      "file": "lib/timerqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/alarmtimer.c:alarmtimer_enqueue",
        "kernel/time/alarmtimer.c:alarmtimer_fired",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582982848,
      "name": "timerqueue_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
bool timerqueue_del(struct timerqueue_head * head, struct timerqueue_node * node)
```

```json
{
  "name": "timerqueue_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583272032,
      "name": "timerqueue_del",
      "external": true,
      "loc": "lib/timerqueue.c:75",
      "file": "lib/timerqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/alarmtimer.c:alarmtimer_fired",
        "kernel/time/alarmtimer.c:alarmtimer_enqueue",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583272032,
      "name": "timerqueue_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
bool timerqueue_del(struct timerqueue_head * head, struct timerqueue_node * node)
```

```json
{
  "name": "timerqueue_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583390800,
      "name": "timerqueue_del",
      "external": true,
      "loc": "lib/timerqueue.c:75",
      "file": "lib/timerqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/alarmtimer.c:alarmtimer_fired",
        "kernel/time/alarmtimer.c:alarmtimer_enqueue",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583390800,
      "name": "timerqueue_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
bool timerqueue_del(struct timerqueue_head * head, struct timerqueue_node * node)
```

```json
{
  "name": "timerqueue_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588246784,
      "name": "timerqueue_del",
      "external": true,
      "loc": "lib/timerqueue.c:75",
      "file": "lib/timerqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/alarmtimer.c:alarmtimer_fired",
        "kernel/time/alarmtimer.c:alarmtimer_enqueue",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588246784,
      "name": "timerqueue_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
bool timerqueue_del(struct timerqueue_head * head, struct timerqueue_node * node)
```

```json
{
  "name": "timerqueue_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588798208,
      "name": "timerqueue_del",
      "external": true,
      "loc": "lib/timerqueue.c:77",
      "file": "lib/timerqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/alarmtimer.c:alarmtimer_fired",
        "kernel/time/alarmtimer.c:alarmtimer_enqueue",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588798208,
      "name": "timerqueue_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
bool timerqueue_del(struct timerqueue_head * head, struct timerqueue_node * node)
```

```json
{
  "name": "timerqueue_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589176304,
      "name": "timerqueue_del",
      "external": true,
      "loc": "lib/timerqueue.c:77",
      "file": "lib/timerqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/alarmtimer.c:alarmtimer_fired",
        "kernel/time/alarmtimer.c:alarmtimer_enqueue",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589176304,
      "name": "timerqueue_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
bool timerqueue_del(struct timerqueue_head * head, struct timerqueue_node * node)
```

```json
{
  "name": "timerqueue_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589406224,
      "name": "timerqueue_del",
      "external": true,
      "loc": "lib/timerqueue.c:77",
      "file": "lib/timerqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/alarmtimer.c:alarmtimer_fired",
        "kernel/time/alarmtimer.c:alarmtimer_enqueue",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589406224,
      "name": "timerqueue_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
bool timerqueue_del(struct timerqueue_head * head, struct timerqueue_node * node)
```

```json
{
  "name": "timerqueue_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589862144,
      "name": "timerqueue_del",
      "external": true,
      "loc": "lib/timerqueue.c:64",
      "file": "lib/timerqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/alarmtimer.c:alarmtimer_fired",
        "kernel/time/alarmtimer.c:alarmtimer_enqueue",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589862144,
      "name": "timerqueue_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
bool timerqueue_del(struct timerqueue_head * head, struct timerqueue_node * node)
```

```json
{
  "name": "timerqueue_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590087952,
      "name": "timerqueue_del",
      "external": true,
      "loc": "lib/timerqueue.c:63",
      "file": "lib/timerqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/alarmtimer.c:alarmtimer_fired",
        "kernel/time/alarmtimer.c:alarmtimer_enqueue",
        "kernel/time/posix-cpu-timers.c:collect_posix_cputimers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:cleanup_timers",
        "kernel/time/posix-cpu-timers.c:cleanup_timers",
        "kernel/time/posix-cpu-timers.c:cleanup_timers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590087952,
      "name": "timerqueue_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
bool timerqueue_del(struct timerqueue_head * head, struct timerqueue_node * node)
```

```json
{
  "name": "timerqueue_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585085872,
      "name": "timerqueue_del",
      "external": true,
      "loc": "lib/timerqueue.c:63",
      "file": "lib/timerqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:__run_hrtimer",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/alarmtimer.c:alarm_restart",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/alarmtimer.c:alarmtimer_fired",
        "kernel/time/alarmtimer.c:alarmtimer_fired",
        "kernel/time/posix-cpu-timers.c:collect_posix_cputimers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "drivers/rtc/interface.c:rtc_timer_cancel",
        "drivers/rtc/interface.c:rtc_timer_start",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585085872,
      "name": "timerqueue_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
bool timerqueue_del(struct timerqueue_head * head, struct timerqueue_node * node)
```

```json
{
  "name": "timerqueue_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585234992,
      "name": "timerqueue_del",
      "external": true,
      "loc": "lib/timerqueue.c:63",
      "file": "lib/timerqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:__run_hrtimer",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/alarmtimer.c:alarm_restart",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/alarmtimer.c:alarmtimer_fired",
        "kernel/time/alarmtimer.c:alarmtimer_fired",
        "kernel/time/posix-cpu-timers.c:collect_posix_cputimers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585234992,
      "name": "timerqueue_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
bool timerqueue_del(struct timerqueue_head * head, struct timerqueue_node * node)
```

```json
{
  "name": "timerqueue_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585117808,
      "name": "timerqueue_del",
      "external": true,
      "loc": "lib/timerqueue.c:53",
      "file": "lib/timerqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/alarmtimer.c:alarm_restart",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/alarmtimer.c:alarmtimer_fired",
        "kernel/time/alarmtimer.c:alarmtimer_fired",
        "kernel/time/posix-cpu-timers.c:collect_posix_cputimers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "drivers/rtc/interface.c:rtc_timer_cancel",
        "drivers/rtc/interface.c:rtc_timer_start",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585117808,
      "name": "timerqueue_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
bool timerqueue_del(struct timerqueue_head * head, struct timerqueue_node * node)
```

```json
{
  "name": "timerqueue_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585566528,
      "name": "timerqueue_del",
      "external": true,
      "loc": "lib/timerqueue.c:53",
      "file": "lib/timerqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/alarmtimer.c:alarm_restart",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/alarmtimer.c:alarmtimer_fired",
        "kernel/time/alarmtimer.c:alarmtimer_fired",
        "kernel/time/posix-cpu-timers.c:collect_posix_cputimers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "drivers/rtc/interface.c:rtc_timer_cancel",
        "drivers/rtc/interface.c:rtc_timer_start",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585566528,
      "name": "timerqueue_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
bool timerqueue_del(struct timerqueue_head * head, struct timerqueue_node * node)
```

```json
{
  "name": "timerqueue_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586720144,
      "name": "timerqueue_del",
      "external": true,
      "loc": "lib/timerqueue.c:53",
      "file": "lib/timerqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/alarmtimer.c:alarm_restart",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/alarmtimer.c:alarmtimer_fired",
        "kernel/time/alarmtimer.c:alarmtimer_fired",
        "kernel/time/posix-cpu-timers.c:collect_posix_cputimers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "drivers/rtc/class.c:rtc_device_release",
        "drivers/rtc/interface.c:rtc_timer_cancel",
        "drivers/rtc/interface.c:rtc_timer_start",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586720144,
      "name": "timerqueue_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
bool timerqueue_del(struct timerqueue_head * head, struct timerqueue_node * node)
```

```json
{
  "name": "timerqueue_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595882720,
      "name": "timerqueue_del",
      "external": true,
      "loc": "lib/timerqueue.c:53",
      "file": "lib/timerqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/alarmtimer.c:alarm_restart",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/alarmtimer.c:alarmtimer_fired",
        "kernel/time/alarmtimer.c:alarmtimer_fired",
        "kernel/time/posix-cpu-timers.c:collect_posix_cputimers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "drivers/rtc/class.c:rtc_device_release",
        "drivers/rtc/interface.c:rtc_timer_cancel",
        "drivers/rtc/interface.c:rtc_timer_start",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595882720,
      "name": "timerqueue_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
bool timerqueue_del(struct timerqueue_head * head, struct timerqueue_node * node)
```

```json
{
  "name": "timerqueue_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596400128,
      "name": "timerqueue_del",
      "external": true,
      "loc": "lib/timerqueue.c:53",
      "file": "lib/timerqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/alarmtimer.c:alarm_restart",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/alarmtimer.c:alarmtimer_fired",
        "kernel/time/alarmtimer.c:alarmtimer_fired",
        "kernel/time/posix-cpu-timers.c:collect_posix_cputimers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "drivers/rtc/class.c:rtc_device_release",
        "drivers/rtc/interface.c:rtc_timer_cancel",
        "drivers/rtc/interface.c:rtc_timer_start",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_update_irq_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596400128,
      "name": "timerqueue_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
bool timerqueue_del(struct timerqueue_head * head, struct timerqueue_node * node)
```

```json
{
  "name": "timerqueue_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597295232,
      "name": "timerqueue_del",
      "external": true,
      "loc": "lib/timerqueue.c:53",
      "file": "lib/timerqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/alarmtimer.c:alarm_restart",
        "kernel/time/alarmtimer.c:alarm_start",
        "kernel/time/alarmtimer.c:alarmtimer_fired",
        "kernel/time/alarmtimer.c:alarmtimer_fired",
        "kernel/time/posix-cpu-timers.c:collect_posix_cputimers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit_group",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "drivers/rtc/class.c:rtc_device_release",
        "drivers/rtc/interface.c:rtc_timer_cancel",
        "drivers/rtc/interface.c:rtc_timer_start",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_update_irq_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597295232,
      "name": "timerqueue_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
bool timerqueue_del(struct timerqueue_head * head, struct timerqueue_node * node)
```

```json
{
  "name": "timerqueue_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503866104,
      "name": "timerqueue_del",
      "external": true,
      "loc": "lib/timerqueue.c:63",
      "file": "lib/timerqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/alarmtimer.c:alarmtimer_fired",
        "kernel/time/alarmtimer.c:alarmtimer_enqueue",
        "kernel/time/posix-cpu-timers.c:collect_posix_cputimers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:cleanup_timers",
        "kernel/time/posix-cpu-timers.c:cleanup_timers",
        "kernel/time/posix-cpu-timers.c:cleanup_timers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503866104,
      "name": "timerqueue_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
bool timerqueue_del(struct timerqueue_head * head, struct timerqueue_node * node)
```

```json
{
  "name": "timerqueue_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236493976,
      "name": "timerqueue_del",
      "external": true,
      "loc": "lib/timerqueue.c:63",
      "file": "lib/timerqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/alarmtimer.c:alarmtimer_fired",
        "kernel/time/alarmtimer.c:alarmtimer_enqueue",
        "kernel/time/posix-cpu-timers.c:collect_posix_cputimers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:cleanup_timers",
        "kernel/time/posix-cpu-timers.c:cleanup_timers",
        "kernel/time/posix-cpu-timers.c:cleanup_timers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236493976,
      "name": "timerqueue_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
bool timerqueue_del(struct timerqueue_head * head, struct timerqueue_node * node)
```

```json
{
  "name": "timerqueue_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297725856,
      "name": "timerqueue_del",
      "external": true,
      "loc": "lib/timerqueue.c:63",
      "file": "lib/timerqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/alarmtimer.c:alarmtimer_fired",
        "kernel/time/alarmtimer.c:alarmtimer_enqueue",
        "kernel/time/posix-cpu-timers.c:collect_posix_cputimers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:cleanup_timers",
        "kernel/time/posix-cpu-timers.c:cleanup_timers",
        "kernel/time/posix-cpu-timers.c:cleanup_timers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297725856,
      "name": "timerqueue_del",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
bool timerqueue_del(struct timerqueue_head * head, struct timerqueue_node * node)
```

```json
{
  "name": "timerqueue_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279762072,
      "name": "timerqueue_del",
      "external": true,
      "loc": "lib/timerqueue.c:63",
      "file": "lib/timerqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/alarmtimer.c:alarmtimer_fired",
        "kernel/time/alarmtimer.c:alarmtimer_enqueue",
        "kernel/time/posix-cpu-timers.c:collect_posix_cputimers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:cleanup_timers",
        "kernel/time/posix-cpu-timers.c:cleanup_timers",
        "kernel/time/posix-cpu-timers.c:cleanup_timers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279762072,
      "name": "timerqueue_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
bool timerqueue_del(struct timerqueue_head * head, struct timerqueue_node * node)
```

```json
{
  "name": "timerqueue_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589690208,
      "name": "timerqueue_del",
      "external": true,
      "loc": "lib/timerqueue.c:63",
      "file": "lib/timerqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/alarmtimer.c:alarmtimer_fired",
        "kernel/time/alarmtimer.c:alarmtimer_enqueue",
        "kernel/time/posix-cpu-timers.c:collect_posix_cputimers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:cleanup_timers",
        "kernel/time/posix-cpu-timers.c:cleanup_timers",
        "kernel/time/posix-cpu-timers.c:cleanup_timers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589690208,
      "name": "timerqueue_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
bool timerqueue_del(struct timerqueue_head * head, struct timerqueue_node * node)
```

```json
{
  "name": "timerqueue_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589416000,
      "name": "timerqueue_del",
      "external": true,
      "loc": "lib/timerqueue.c:63",
      "file": "lib/timerqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/alarmtimer.c:alarmtimer_fired",
        "kernel/time/alarmtimer.c:alarmtimer_enqueue",
        "kernel/time/posix-cpu-timers.c:collect_posix_cputimers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:cleanup_timers",
        "kernel/time/posix-cpu-timers.c:cleanup_timers",
        "kernel/time/posix-cpu-timers.c:cleanup_timers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589416000,
      "name": "timerqueue_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
bool timerqueue_del(struct timerqueue_head * head, struct timerqueue_node * node)
```

```json
{
  "name": "timerqueue_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590133584,
      "name": "timerqueue_del",
      "external": true,
      "loc": "lib/timerqueue.c:63",
      "file": "lib/timerqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/alarmtimer.c:alarmtimer_fired",
        "kernel/time/alarmtimer.c:alarmtimer_enqueue",
        "kernel/time/posix-cpu-timers.c:collect_posix_cputimers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:cleanup_timers",
        "kernel/time/posix-cpu-timers.c:cleanup_timers",
        "kernel/time/posix-cpu-timers.c:cleanup_timers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590133584,
      "name": "timerqueue_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
bool timerqueue_del(struct timerqueue_head * head, struct timerqueue_node * node)
```

```json
{
  "name": "timerqueue_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590183968,
      "name": "timerqueue_del",
      "external": true,
      "loc": "lib/timerqueue.c:63",
      "file": "lib/timerqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/alarmtimer.c:alarm_try_to_cancel",
        "kernel/time/alarmtimer.c:alarmtimer_fired",
        "kernel/time/alarmtimer.c:alarmtimer_enqueue",
        "kernel/time/posix-cpu-timers.c:collect_posix_cputimers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:cleanup_timers",
        "kernel/time/posix-cpu-timers.c:cleanup_timers",
        "kernel/time/posix-cpu-timers.c:cleanup_timers",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590183968,
      "name": "timerqueue_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
