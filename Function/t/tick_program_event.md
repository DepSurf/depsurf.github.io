# Function: <code>tick_program_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int tick_program_event(ktime_t expires, int force)
```

```json
{
  "name": "tick_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579885248,
      "name": "tick_program_event",
      "external": true,
      "loc": "kernel/time/tick-oneshot.c:27",
      "file": "kernel/time/tick-oneshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/hrtimer.c:retrigger_next_event",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:tick_nohz_restart",
        "kernel/time/tick-sched.c:__tick_nohz_idle_enter",
        "kernel/time/tick-sched.c:tick_check_oneshot_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579885248,
      "name": "tick_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int tick_program_event(ktime_t expires, int force)
```

```json
{
  "name": "tick_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579914832,
      "name": "tick_program_event",
      "external": true,
      "loc": "kernel/time/tick-oneshot.c:27",
      "file": "kernel/time/tick-oneshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/hrtimer.c:retrigger_next_event",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:__tick_nohz_idle_enter",
        "kernel/time/tick-sched.c:tick_nohz_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579914832,
      "name": "tick_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int tick_program_event(ktime_t expires, int force)
```

```json
{
  "name": "tick_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579945376,
      "name": "tick_program_event",
      "external": true,
      "loc": "kernel/time/tick-oneshot.c:27",
      "file": "kernel/time/tick-oneshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:tick_nohz_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579945376,
      "name": "tick_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int tick_program_event(ktime_t expires, int force)
```

```json
{
  "name": "tick_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579953280,
      "name": "tick_program_event",
      "external": true,
      "loc": "kernel/time/tick-oneshot.c:27",
      "file": "kernel/time/tick-oneshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:__tick_nohz_idle_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579953280,
      "name": "tick_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int tick_program_event(ktime_t expires, int force)
```

```json
{
  "name": "tick_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579998992,
      "name": "tick_program_event",
      "external": true,
      "loc": "kernel/time/tick-oneshot.c:27",
      "file": "kernel/time/tick-oneshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:__tick_nohz_idle_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579998992,
      "name": "tick_program_event",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int tick_program_event(ktime_t expires, int force)
```

```json
{
  "name": "tick_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580051152,
      "name": "tick_program_event",
      "external": true,
      "loc": "kernel/time/tick-oneshot.c:27",
      "file": "kernel/time/tick-oneshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_reprogram",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580051152,
      "name": "tick_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int tick_program_event(ktime_t expires, int force)
```

```json
{
  "name": "tick_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580097968,
      "name": "tick_program_event",
      "external": true,
      "loc": "kernel/time/tick-oneshot.c:23",
      "file": "kernel/time/tick-oneshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_reprogram",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580097968,
      "name": "tick_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int tick_program_event(ktime_t expires, int force)
```

```json
{
  "name": "tick_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580141792,
      "name": "tick_program_event",
      "external": true,
      "loc": "kernel/time/tick-oneshot.c:23",
      "file": "kernel/time/tick-oneshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_reprogram",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580141792,
      "name": "tick_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int tick_program_event(ktime_t expires, int force)
```

```json
{
  "name": "tick_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580189824,
      "name": "tick_program_event",
      "external": true,
      "loc": "kernel/time/tick-oneshot.c:23",
      "file": "kernel/time/tick-oneshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_reprogram",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580189824,
      "name": "tick_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int tick_program_event(ktime_t expires, int force)
```

```json
{
  "name": "tick_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580254912,
      "name": "tick_program_event",
      "external": true,
      "loc": "kernel/time/tick-oneshot.c:23",
      "file": "kernel/time/tick-oneshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_reprogram",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-sched.c:tick_nohz_switch_to_nohz",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick",
        "kernel/time/tick-sched.c:tick_nohz_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580254912,
      "name": "tick_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int tick_program_event(ktime_t expires, int force)
```

```json
{
  "name": "tick_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580238688,
      "name": "tick_program_event",
      "external": true,
      "loc": "kernel/time/tick-oneshot.c:23",
      "file": "kernel/time/tick-oneshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_reprogram",
        "kernel/time/hrtimer.c:retrigger_next_event",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-sched.c:tick_nohz_switch_to_nohz",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick",
        "kernel/time/tick-sched.c:tick_nohz_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580238688,
      "name": "tick_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int tick_program_event(ktime_t expires, int force)
```

```json
{
  "name": "tick_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580243920,
      "name": "tick_program_event",
      "external": true,
      "loc": "kernel/time/tick-oneshot.c:23",
      "file": "kernel/time/tick-oneshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_reprogram",
        "kernel/time/hrtimer.c:retrigger_next_event",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick",
        "kernel/time/tick-sched.c:tick_nohz_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580243920,
      "name": "tick_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int tick_program_event(ktime_t expires, int force)
```

```json
{
  "name": "tick_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580394560,
      "name": "tick_program_event",
      "external": true,
      "loc": "kernel/time/tick-oneshot.c:23",
      "file": "kernel/time/tick-oneshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/hrtimer.c:hrtimer_reprogram",
        "kernel/time/hrtimer.c:retrigger_next_event",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick",
        "kernel/time/tick-sched.c:tick_nohz_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580394560,
      "name": "tick_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int tick_program_event(ktime_t expires, int force)
```

```json
{
  "name": "tick_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580612864,
      "name": "tick_program_event",
      "external": true,
      "loc": "kernel/time/tick-oneshot.c:23",
      "file": "kernel/time/tick-oneshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/hrtimer.c:hrtimer_reprogram",
        "kernel/time/hrtimer.c:retrigger_next_event",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick",
        "kernel/time/tick-sched.c:tick_nohz_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580612864,
      "name": "tick_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int tick_program_event(ktime_t expires, int force)
```

```json
{
  "name": "tick_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580877408,
      "name": "tick_program_event",
      "external": true,
      "loc": "kernel/time/tick-oneshot.c:23",
      "file": "kernel/time/tick-oneshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/hrtimer.c:hrtimer_reprogram",
        "kernel/time/hrtimer.c:retrigger_next_event",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick",
        "kernel/time/tick-sched.c:tick_nohz_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580877408,
      "name": "tick_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int tick_program_event(ktime_t expires, int force)
```

```json
{
  "name": "tick_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580961216,
      "name": "tick_program_event",
      "external": true,
      "loc": "kernel/time/tick-oneshot.c:23",
      "file": "kernel/time/tick-oneshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/hrtimer.c:hrtimer_reprogram",
        "kernel/time/hrtimer.c:retrigger_next_event",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick",
        "kernel/time/tick-sched.c:tick_nohz_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580961216,
      "name": "tick_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int tick_program_event(ktime_t expires, int force)
```

```json
{
  "name": "tick_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581052800,
      "name": "tick_program_event",
      "external": true,
      "loc": "kernel/time/tick-oneshot.c:23",
      "file": "kernel/time/tick-oneshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/hrtimer.c:hrtimer_reprogram",
        "kernel/time/hrtimer.c:retrigger_next_event",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_nohz_lowres_handler",
        "kernel/time/tick-sched.c:tick_nohz_restart_sched_tick",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581052800,
      "name": "tick_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int tick_program_event(ktime_t expires, int force)
```

```json
{
  "name": "tick_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491419136,
      "name": "tick_program_event",
      "external": true,
      "loc": "kernel/time/tick-oneshot.c:23",
      "file": "kernel/time/tick-oneshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_reprogram",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491419136,
      "name": "tick_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int tick_program_event(ktime_t expires, int force)
```

```json
{
  "name": "tick_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225412148,
      "name": "tick_program_event",
      "external": true,
      "loc": "kernel/time/tick-oneshot.c:23",
      "file": "kernel/time/tick-oneshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_reprogram",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225412148,
      "name": "tick_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int tick_program_event(ktime_t expires, int force)
```

```json
{
  "name": "tick_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284365360,
      "name": "tick_program_event",
      "external": true,
      "loc": "kernel/time/tick-oneshot.c:23",
      "file": "kernel/time/tick-oneshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_reprogram",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284365360,
      "name": "tick_program_event",
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
int tick_program_event(ktime_t expires, int force)
```

```json
{
  "name": "tick_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271886762,
      "name": "tick_program_event",
      "external": true,
      "loc": "kernel/time/tick-oneshot.c:23",
      "file": "kernel/time/tick-oneshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271886762,
      "name": "tick_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int tick_program_event(ktime_t expires, int force)
```

```json
{
  "name": "tick_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580158624,
      "name": "tick_program_event",
      "external": true,
      "loc": "kernel/time/tick-oneshot.c:23",
      "file": "kernel/time/tick-oneshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_reprogram",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580158624,
      "name": "tick_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int tick_program_event(ktime_t expires, int force)
```

```json
{
  "name": "tick_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580104736,
      "name": "tick_program_event",
      "external": true,
      "loc": "kernel/time/tick-oneshot.c:23",
      "file": "kernel/time/tick-oneshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_reprogram",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:tick_nohz_restart_sched_tick",
        "kernel/time/tick-sched.c:tick_nohz_stop_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580104736,
      "name": "tick_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int tick_program_event(ktime_t expires, int force)
```

```json
{
  "name": "tick_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580150096,
      "name": "tick_program_event",
      "external": true,
      "loc": "kernel/time/tick-oneshot.c:23",
      "file": "kernel/time/tick-oneshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_reprogram",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580150096,
      "name": "tick_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int tick_program_event(ktime_t expires, int force)
```

```json
{
  "name": "tick_program_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580202080,
      "name": "tick_program_event",
      "external": true,
      "loc": "kernel/time/tick-oneshot.c:23",
      "file": "kernel/time/tick-oneshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_reprogram",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-sched.c:tick_check_oneshot_change",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_idle_stop_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580202080,
      "name": "tick_program_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
