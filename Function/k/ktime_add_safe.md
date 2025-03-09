# Function: <code>ktime_add_safe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs)
```

```json
{
  "name": "ktime_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579822400,
      "name": "ktime_add_safe",
      "external": true,
      "loc": "kernel/time/hrtimer.c:308",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_forward",
        "kernel/time/hrtimer.c:hrtimer_forward",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_nanosleep"
      ],
      "caller_func": [
        "kernel/time/posix-timers.c:common_timer_set",
        "kernel/time/posix-timers.c:common_timer_set",
        "kernel/futex.c:futex_wait",
        "kernel/futex.c:SyS_futex",
        "kernel/futex_compat.c:compat_SyS_futex",
        "drivers/md/dm.c:dm_request_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579822400,
      "name": "ktime_add_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs)
```

```json
{
  "name": "ktime_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579856032,
      "name": "ktime_add_safe",
      "external": true,
      "loc": "kernel/time/hrtimer.c:308",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_forward",
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": [
        "kernel/time/posix-timers.c:common_timer_set",
        "kernel/time/posix-timers.c:common_timer_set",
        "kernel/futex.c:SyS_futex",
        "kernel/futex.c:futex_wait",
        "kernel/futex_compat.c:compat_SyS_futex",
        "drivers/md/dm-rq.c:dm_old_request_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851280,
      "name": "ktime_add_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs)
```

```json
{
  "name": "ktime_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579884897,
      "name": "ktime_add_safe",
      "external": true,
      "loc": "kernel/time/hrtimer.c:308",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_forward",
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": [
        "kernel/time/posix-timers.c:common_timer_set",
        "kernel/time/posix-timers.c:common_timer_set",
        "kernel/futex.c:SyS_futex",
        "kernel/futex.c:futex_wait",
        "kernel/futex_compat.c:compat_SyS_futex",
        "drivers/md/dm-rq.c:dm_old_request_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579880016,
      "name": "ktime_add_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs)
```

```json
{
  "name": "ktime_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579893780,
      "name": "ktime_add_safe",
      "external": true,
      "loc": "kernel/time/hrtimer.c:309",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_forward",
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_forward",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/futex.c:SyS_futex",
        "kernel/futex.c:futex_wait",
        "kernel/futex_compat.c:compat_SyS_futex",
        "drivers/md/dm-rq.c:dm_old_request_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579889312,
      "name": "ktime_add_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs)
```

```json
{
  "name": "ktime_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579938308,
      "name": "ktime_add_safe",
      "external": true,
      "loc": "kernel/time/hrtimer.c:309",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_forward",
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_forward",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/futex.c:SyS_futex",
        "kernel/futex.c:futex_wait",
        "kernel/futex_compat.c:compat_SyS_futex",
        "drivers/md/dm-rq.c:dm_old_request_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579933824,
      "name": "ktime_add_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs)
```

```json
{
  "name": "ktime_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589269068,
      "name": "ktime_add_safe",
      "external": true,
      "loc": "kernel/time/hrtimer.c:323",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_forward",
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_forward",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/futex.c:__ia32_sys_futex",
        "kernel/futex.c:__x64_sys_futex",
        "kernel/futex.c:futex_wait",
        "kernel/futex_compat.c:__x32_compat_sys_futex",
        "kernel/futex_compat.c:__ia32_compat_sys_futex",
        "drivers/md/dm-rq.c:dm_old_request_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579980448,
      "name": "ktime_add_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs)
```

```json
{
  "name": "ktime_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589511628,
      "name": "ktime_add_safe",
      "external": true,
      "loc": "kernel/time/hrtimer.c:314",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_forward",
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_forward",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/futex.c:__x32_compat_sys_futex",
        "kernel/futex.c:__ia32_compat_sys_futex",
        "kernel/futex.c:__ia32_sys_futex",
        "kernel/futex.c:__x64_sys_futex",
        "kernel/futex.c:futex_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580027104,
      "name": "ktime_add_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs)
```

```json
{
  "name": "ktime_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589970814,
      "name": "ktime_add_safe",
      "external": true,
      "loc": "kernel/time/hrtimer.c:313",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_forward",
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_forward",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/futex.c:__ia32_sys_futex_time32",
        "kernel/futex.c:__x64_sys_futex_time32",
        "kernel/futex.c:__ia32_sys_futex",
        "kernel/futex.c:__x64_sys_futex",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580070368,
      "name": "ktime_add_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs)
```

```json
{
  "name": "ktime_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590198343,
      "name": "ktime_add_safe",
      "external": true,
      "loc": "kernel/time/hrtimer.c:323",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_forward",
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_forward",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/futex.c:__ia32_sys_futex_time32",
        "kernel/futex.c:__x64_sys_futex_time32",
        "kernel/futex.c:__ia32_sys_futex",
        "kernel/futex.c:__x64_sys_futex",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580119408,
      "name": "ktime_add_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs)
```

```json
{
  "name": "ktime_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591214159,
      "name": "ktime_add_safe",
      "external": true,
      "loc": "kernel/time/hrtimer.c:323",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_forward",
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_timer_forward",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/futex.c:__ia32_sys_futex_time32",
        "kernel/futex.c:__x64_sys_futex_time32",
        "kernel/futex.c:__ia32_sys_futex",
        "kernel/futex.c:__x64_sys_futex",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580180160,
      "name": "ktime_add_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs)
```

```json
{
  "name": "ktime_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591709295,
      "name": "ktime_add_safe",
      "external": true,
      "loc": "kernel/time/hrtimer.c:327",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_forward",
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_timer_forward",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/futex.c:__ia32_sys_futex_time32",
        "kernel/futex.c:__x64_sys_futex_time32",
        "kernel/futex.c:__ia32_sys_futex",
        "kernel/futex.c:__x64_sys_futex",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580165088,
      "name": "ktime_add_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs)
```

```json
{
  "name": "ktime_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591656668,
      "name": "ktime_add_safe",
      "external": true,
      "loc": "kernel/time/hrtimer.c:327",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_forward",
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_timer_forward",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/futex.c:__ia32_sys_futex_time32",
        "kernel/futex.c:__x64_sys_futex_time32",
        "kernel/futex.c:__ia32_sys_futex",
        "kernel/futex.c:__x64_sys_futex",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580169680,
      "name": "ktime_add_safe",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs)
```

```json
{
  "name": "ktime_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592830364,
      "name": "ktime_add_safe",
      "external": true,
      "loc": "kernel/time/hrtimer.c:327",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_forward",
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_timer_forward",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/futex.c:__ia32_sys_futex_time32",
        "kernel/futex.c:__x64_sys_futex_time32",
        "kernel/futex.c:__ia32_sys_futex",
        "kernel/futex.c:__x64_sys_futex",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580314544,
      "name": "ktime_add_safe",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs)
```

```json
{
  "name": "ktime_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594738696,
      "name": "ktime_add_safe",
      "external": true,
      "loc": "kernel/time/hrtimer.c:327",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_forward",
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_timer_forward",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/futex/core.c:futex_setup_timer",
        "kernel/futex/syscalls.c:__ia32_sys_futex_time32",
        "kernel/futex/syscalls.c:__x64_sys_futex_time32",
        "kernel/futex/syscalls.c:__ia32_sys_futex",
        "kernel/futex/syscalls.c:__x64_sys_futex",
        "fs/aio.c:read_events",
        "ipc/sem.c:__do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580525328,
      "name": "ktime_add_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs)
```

```json
{
  "name": "ktime_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596490840,
      "name": "ktime_add_safe",
      "external": true,
      "loc": "kernel/time/hrtimer.c:327",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_forward",
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_timer_forward",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/futex/core.c:futex_setup_timer",
        "kernel/futex/syscalls.c:__ia32_sys_futex_time32",
        "kernel/futex/syscalls.c:__x64_sys_futex_time32",
        "kernel/futex/syscalls.c:__ia32_sys_futex",
        "kernel/futex/syscalls.c:__x64_sys_futex",
        "fs/aio.c:read_events",
        "ipc/sem.c:__do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580781088,
      "name": "ktime_add_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs)
```

```json
{
  "name": "ktime_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597032110,
      "name": "ktime_add_safe",
      "external": true,
      "loc": "kernel/time/hrtimer.c:329",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_forward",
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_timer_forward",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/futex/core.c:futex_setup_timer",
        "kernel/futex/syscalls.c:__ia32_sys_futex_time32",
        "kernel/futex/syscalls.c:__x64_sys_futex_time32",
        "kernel/futex/syscalls.c:__ia32_sys_futex",
        "kernel/futex/syscalls.c:__x64_sys_futex",
        "fs/aio.c:read_events",
        "ipc/sem.c:__do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580864080,
      "name": "ktime_add_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs)
```

```json
{
  "name": "ktime_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597961502,
      "name": "ktime_add_safe",
      "external": true,
      "loc": "kernel/time/hrtimer.c:329",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_forward",
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_timer_forward",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/futex/core.c:futex_setup_timer",
        "kernel/futex/syscalls.c:__ia32_sys_futex_time32",
        "kernel/futex/syscalls.c:__x64_sys_futex_time32",
        "kernel/futex/syscalls.c:__ia32_sys_futex",
        "kernel/futex/syscalls.c:__x64_sys_futex",
        "fs/aio.c:read_events",
        "ipc/sem.c:__do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580954544,
      "name": "ktime_add_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs)
```

```json
{
  "name": "ktime_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503945224,
      "name": "ktime_add_safe",
      "external": true,
      "loc": "kernel/time/hrtimer.c:323",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_forward",
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_forward",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/futex.c:__arm64_sys_futex_time32",
        "kernel/futex.c:__arm64_sys_futex",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491337280,
      "name": "ktime_add_safe",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs)
```

```json
{
  "name": "ktime_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236554212,
      "name": "ktime_add_safe",
      "external": true,
      "loc": "kernel/time/hrtimer.c:323",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_forward",
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_forward",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/futex.c:__se_sys_futex_time32",
        "kernel/futex.c:__se_sys_futex",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225330000,
      "name": "ktime_add_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs)
```

```json
{
  "name": "ktime_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297798184,
      "name": "ktime_add_safe",
      "external": true,
      "loc": "kernel/time/hrtimer.c:323",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_forward",
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_forward",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/futex.c:__se_sys_futex_time32",
        "kernel/futex.c:__se_sys_futex",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284266224,
      "name": "ktime_add_safe",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs)
```

```json
{
  "name": "ktime_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279808916,
      "name": "ktime_add_safe",
      "external": true,
      "loc": "kernel/time/hrtimer.c:323",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_forward",
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_forward",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/futex.c:__se_sys_futex",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271834738,
      "name": "ktime_add_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs)
```

```json
{
  "name": "ktime_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589800631,
      "name": "ktime_add_safe",
      "external": true,
      "loc": "kernel/time/hrtimer.c:323",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_forward",
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_forward",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/futex.c:__ia32_sys_futex_time32",
        "kernel/futex.c:__x64_sys_futex_time32",
        "kernel/futex.c:__ia32_sys_futex",
        "kernel/futex.c:__x64_sys_futex",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580088608,
      "name": "ktime_add_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs)
```

```json
{
  "name": "ktime_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589523079,
      "name": "ktime_add_safe",
      "external": true,
      "loc": "kernel/time/hrtimer.c:323",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_forward",
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_forward",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/futex.c:__ia32_sys_futex_time32",
        "kernel/futex.c:__x64_sys_futex_time32",
        "kernel/futex.c:__ia32_sys_futex",
        "kernel/futex.c:__x64_sys_futex",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580033936,
      "name": "ktime_add_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs)
```

```json
{
  "name": "ktime_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590244039,
      "name": "ktime_add_safe",
      "external": true,
      "loc": "kernel/time/hrtimer.c:323",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_forward",
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_forward",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/futex.c:__ia32_sys_futex_time32",
        "kernel/futex.c:__x64_sys_futex_time32",
        "kernel/futex.c:__ia32_sys_futex",
        "kernel/futex.c:__x64_sys_futex",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580079680,
      "name": "ktime_add_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs)
```

```json
{
  "name": "ktime_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590294359,
      "name": "ktime_add_safe",
      "external": true,
      "loc": "kernel/time/hrtimer.c:323",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_forward",
        "kernel/time/hrtimer.c:hrtimer_forward"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_forward",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "kernel/time/posix-timers.c:common_hrtimer_arm",
        "kernel/futex.c:__ia32_sys_futex_time32",
        "kernel/futex.c:__x64_sys_futex_time32",
        "kernel/futex.c:__ia32_sys_futex",
        "kernel/futex.c:__x64_sys_futex",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580131184,
      "name": "ktime_add_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
