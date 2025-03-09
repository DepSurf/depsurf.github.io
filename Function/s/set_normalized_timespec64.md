# Function: <code>set_normalized_timespec64</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_normalized_timespec64(struct timespec * ts, time64_t sec, s64 nsec)
```

```json
{
  "name": "set_normalized_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579918829,
      "name": "set_normalized_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:505",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:timespec64_add_safe"
      ],
      "caller_func": [
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock",
        "kernel/time/timekeeping.c:get_monotonic_coarse64",
        "kernel/time/timekeeping.c:update_wall_time",
        "kernel/time/timekeeping.c:update_wall_time",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:do_settimeofday64",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "fs/select.c:compat_poll_select_copy_remaining",
        "fs/select.c:poll_select_copy_remaining",
        "fs/select.c:select_estimate_accuracy",
        "drivers/rtc/systohc.c:rtc_set_ntp_time",
        "drivers/rtc/systohc.c:rtc_set_ntp_time",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579915344,
      "name": "set_normalized_timespec64",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_normalized_timespec64(struct timespec64 * ts, time64_t sec, s64 nsec)
```

```json
{
  "name": "set_normalized_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579965229,
      "name": "set_normalized_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:517",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:timespec64_add_safe"
      ],
      "caller_func": [
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock",
        "kernel/time/timekeeping.c:ktime_get_coarse_ts64",
        "kernel/time/timekeeping.c:update_wall_time",
        "kernel/time/timekeeping.c:update_wall_time",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "fs/select.c:compat_poll_select_copy_remaining",
        "fs/select.c:poll_select_copy_remaining",
        "fs/select.c:select_estimate_accuracy",
        "drivers/rtc/systohc.c:rtc_set_ntp_time",
        "drivers/rtc/systohc.c:rtc_set_ntp_time",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579959984,
      "name": "set_normalized_timespec64",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_normalized_timespec64(struct timespec64 * ts, time64_t sec, s64 nsec)
```

```json
{
  "name": "set_normalized_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580012093,
      "name": "set_normalized_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:455",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:timespec64_add_safe"
      ],
      "caller_func": [
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock",
        "kernel/time/timekeeping.c:ktime_get_coarse_ts64",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "fs/select.c:poll_select_copy_remaining",
        "fs/select.c:select_estimate_accuracy",
        "drivers/rtc/systohc.c:rtc_set_ntp_time",
        "drivers/rtc/systohc.c:rtc_set_ntp_time",
        "net/socket.c:do_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580006560,
      "name": "set_normalized_timespec64",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_normalized_timespec64(struct timespec64 * ts, time64_t sec, s64 nsec)
```

```json
{
  "name": "set_normalized_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580056289,
      "name": "set_normalized_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:523",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:timespec64_add_safe"
      ],
      "caller_func": [
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock",
        "kernel/time/timekeeping.c:ktime_get_coarse_ts64",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "fs/select.c:poll_select_finish",
        "fs/select.c:select_estimate_accuracy",
        "drivers/rtc/systohc.c:rtc_set_ntp_time",
        "drivers/rtc/systohc.c:rtc_set_ntp_time",
        "net/socket.c:do_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580050128,
      "name": "set_normalized_timespec64",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_normalized_timespec64(struct timespec64 * ts, time64_t sec, s64 nsec)
```

```json
{
  "name": "set_normalized_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580105345,
      "name": "set_normalized_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:523",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:timespec64_add_safe"
      ],
      "caller_func": [
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock",
        "kernel/time/timekeeping.c:ktime_get_coarse_ts64",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "fs/select.c:poll_select_finish",
        "fs/select.c:select_estimate_accuracy",
        "drivers/rtc/systohc.c:rtc_set_ntp_time",
        "drivers/rtc/systohc.c:rtc_set_ntp_time",
        "net/socket.c:do_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580099184,
      "name": "set_normalized_timespec64",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_normalized_timespec64(struct timespec64 * ts, time64_t sec, s64 nsec)
```

```json
{
  "name": "set_normalized_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580167441,
      "name": "set_normalized_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:478",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:timespec64_add_safe"
      ],
      "caller_func": [
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock",
        "kernel/time/timekeeping.c:ktime_get_coarse_ts64",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "kernel/time/ntp.c:sync_cmos_clock",
        "kernel/time/alarmtimer.c:get_boottime_timespec",
        "kernel/time/posix-timers.c:posix_get_boottime_timespec",
        "kernel/time/posix-timers.c:posix_get_monotonic_coarse",
        "kernel/time/posix-timers.c:posix_get_monotonic_raw",
        "kernel/time/posix-timers.c:posix_get_monotonic_timespec",
        "kernel/time/namespace.c:proc_timens_set_offset",
        "fs/select.c:poll_select_finish",
        "fs/select.c:select_estimate_accuracy",
        "fs/proc/uptime.c:uptime_proc_show",
        "drivers/rtc/systohc.c:rtc_set_ntp_time",
        "drivers/rtc/systohc.c:rtc_set_ntp_time",
        "net/socket.c:do_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580161760,
      "name": "set_normalized_timespec64",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_normalized_timespec64(struct timespec64 * ts, time64_t sec, s64 nsec)
```

```json
{
  "name": "set_normalized_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580151585,
      "name": "set_normalized_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:478",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:timespec64_add_safe"
      ],
      "caller_func": [
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock",
        "kernel/time/timekeeping.c:ktime_get_coarse_ts64",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/time/alarmtimer.c:get_boottime_timespec",
        "kernel/time/posix-timers.c:posix_get_boottime_timespec",
        "kernel/time/posix-timers.c:posix_get_monotonic_coarse",
        "kernel/time/posix-timers.c:posix_get_monotonic_raw",
        "kernel/time/posix-timers.c:posix_get_monotonic_timespec",
        "kernel/time/namespace.c:proc_timens_set_offset",
        "fs/select.c:poll_select_finish",
        "fs/select.c:select_estimate_accuracy",
        "fs/proc/stat.c:show_stat",
        "fs/proc/uptime.c:uptime_proc_show",
        "net/socket.c:do_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580145904,
      "name": "set_normalized_timespec64",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_normalized_timespec64(struct timespec64 * ts, time64_t sec, s64 nsec)
```

```json
{
  "name": "set_normalized_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580156241,
      "name": "set_normalized_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:478",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:timespec64_add_safe"
      ],
      "caller_func": [
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock",
        "kernel/time/timekeeping.c:ktime_get_coarse_ts64",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/time/alarmtimer.c:get_boottime_timespec",
        "kernel/time/posix-timers.c:posix_get_boottime_timespec",
        "kernel/time/posix-timers.c:posix_get_monotonic_coarse",
        "kernel/time/posix-timers.c:posix_get_monotonic_raw",
        "kernel/time/posix-timers.c:posix_get_monotonic_timespec",
        "kernel/time/namespace.c:proc_timens_set_offset",
        "fs/select.c:poll_select_finish",
        "fs/select.c:select_estimate_accuracy",
        "fs/proc/stat.c:show_stat",
        "fs/proc/uptime.c:uptime_proc_show",
        "net/socket.c:do_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580150592,
      "name": "set_normalized_timespec64",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_normalized_timespec64(struct timespec64 * ts, time64_t sec, s64 nsec)
```

```json
{
  "name": "set_normalized_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580300769,
      "name": "set_normalized_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:478",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:timespec64_add_safe"
      ],
      "caller_func": [
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock",
        "kernel/time/timekeeping.c:ktime_get_coarse_ts64",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/time/alarmtimer.c:get_boottime_timespec",
        "kernel/time/posix-timers.c:posix_get_boottime_timespec",
        "kernel/time/posix-timers.c:posix_get_monotonic_coarse",
        "kernel/time/posix-timers.c:posix_get_monotonic_raw",
        "kernel/time/posix-timers.c:posix_get_monotonic_timespec",
        "kernel/time/namespace.c:proc_timens_set_offset",
        "fs/select.c:poll_select_finish",
        "fs/select.c:select_estimate_accuracy",
        "fs/proc/stat.c:show_stat",
        "fs/proc/uptime.c:uptime_proc_show",
        "net/socket.c:do_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580295120,
      "name": "set_normalized_timespec64",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_normalized_timespec64(struct timespec64 * ts, time64_t sec, s64 nsec)
```

```json
{
  "name": "set_normalized_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580509761,
      "name": "set_normalized_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:478",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:timespec64_add_safe"
      ],
      "caller_func": [
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock",
        "kernel/time/timekeeping.c:ktime_get_coarse_ts64",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:do_settimeofday64",
        "kernel/time/timekeeping.c:do_settimeofday64",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/time/alarmtimer.c:get_boottime_timespec",
        "kernel/time/posix-timers.c:posix_get_boottime_timespec",
        "kernel/time/posix-timers.c:posix_get_monotonic_coarse",
        "kernel/time/posix-timers.c:posix_get_monotonic_raw",
        "kernel/time/posix-timers.c:posix_get_monotonic_timespec",
        "kernel/time/namespace.c:proc_timens_set_offset",
        "fs/select.c:poll_select_finish",
        "fs/select.c:select_estimate_accuracy",
        "fs/proc/stat.c:show_stat",
        "fs/proc/uptime.c:uptime_proc_show",
        "drivers/rtc/class.c:rtc_resume",
        "drivers/rtc/class.c:rtc_resume",
        "drivers/rtc/class.c:rtc_resume",
        "drivers/rtc/class.c:rtc_suspend",
        "drivers/rtc/class.c:rtc_suspend",
        "drivers/rtc/class.c:rtc_suspend",
        "net/socket.c:do_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580503808,
      "name": "set_normalized_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void set_normalized_timespec64(struct timespec64 * ts, time64_t sec, s64 nsec)
```

```json
{
  "name": "set_normalized_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580763761,
      "name": "set_normalized_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:478",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:timespec64_add_safe"
      ],
      "caller_func": [
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock",
        "kernel/time/timekeeping.c:ktime_get_coarse_ts64",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:do_settimeofday64",
        "kernel/time/timekeeping.c:do_settimeofday64",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/time/alarmtimer.c:get_boottime_timespec",
        "kernel/time/posix-timers.c:posix_get_boottime_timespec",
        "kernel/time/posix-timers.c:posix_get_monotonic_coarse",
        "kernel/time/posix-timers.c:posix_get_monotonic_raw",
        "kernel/time/posix-timers.c:posix_get_monotonic_timespec",
        "kernel/time/namespace.c:proc_timens_set_offset",
        "fs/select.c:poll_select_finish",
        "fs/select.c:select_estimate_accuracy",
        "fs/proc/stat.c:show_stat",
        "fs/proc/uptime.c:uptime_proc_show",
        "drivers/rtc/class.c:rtc_resume",
        "drivers/rtc/class.c:rtc_resume",
        "drivers/rtc/class.c:rtc_resume",
        "drivers/rtc/class.c:rtc_suspend",
        "drivers/rtc/class.c:rtc_suspend",
        "drivers/rtc/class.c:rtc_suspend",
        "net/socket.c:do_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580757072,
      "name": "set_normalized_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void set_normalized_timespec64(struct timespec64 * ts, time64_t sec, s64 nsec)
```

```json
{
  "name": "set_normalized_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580846433,
      "name": "set_normalized_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:478",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:timespec64_add_safe"
      ],
      "caller_func": [
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock",
        "kernel/time/timekeeping.c:ktime_get_coarse_ts64",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:do_settimeofday64",
        "kernel/time/timekeeping.c:do_settimeofday64",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/time/alarmtimer.c:get_boottime_timespec",
        "kernel/time/posix-timers.c:posix_get_boottime_timespec",
        "kernel/time/posix-timers.c:posix_get_monotonic_coarse",
        "kernel/time/posix-timers.c:posix_get_monotonic_raw",
        "kernel/time/posix-timers.c:posix_get_monotonic_timespec",
        "kernel/time/namespace.c:proc_timens_set_offset",
        "fs/select.c:poll_select_finish",
        "fs/select.c:select_estimate_accuracy",
        "fs/proc/stat.c:show_stat",
        "fs/proc/uptime.c:uptime_proc_show",
        "drivers/rtc/class.c:rtc_resume",
        "drivers/rtc/class.c:rtc_resume",
        "drivers/rtc/class.c:rtc_resume",
        "drivers/rtc/class.c:rtc_suspend",
        "drivers/rtc/class.c:rtc_suspend",
        "drivers/rtc/class.c:rtc_suspend",
        "net/socket.c:do_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580839744,
      "name": "set_normalized_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void set_normalized_timespec64(struct timespec64 * ts, time64_t sec, s64 nsec)
```

```json
{
  "name": "set_normalized_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580935825,
      "name": "set_normalized_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:495",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:timespec64_add_safe"
      ],
      "caller_func": [
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock",
        "kernel/time/timekeeping.c:ktime_get_coarse_ts64",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:do_settimeofday64",
        "kernel/time/timekeeping.c:do_settimeofday64",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/time/alarmtimer.c:get_boottime_timespec",
        "kernel/time/posix-timers.c:posix_get_boottime_timespec",
        "kernel/time/posix-timers.c:posix_get_monotonic_coarse",
        "kernel/time/posix-timers.c:posix_get_monotonic_raw",
        "kernel/time/posix-timers.c:posix_get_monotonic_timespec",
        "kernel/time/namespace.c:proc_timens_set_offset",
        "fs/select.c:poll_select_finish",
        "fs/select.c:select_estimate_accuracy",
        "fs/proc/stat.c:show_stat",
        "fs/proc/uptime.c:uptime_proc_show",
        "drivers/rtc/class.c:rtc_resume",
        "drivers/rtc/class.c:rtc_resume",
        "drivers/rtc/class.c:rtc_resume",
        "drivers/rtc/class.c:rtc_suspend",
        "drivers/rtc/class.c:rtc_suspend",
        "drivers/rtc/class.c:rtc_suspend",
        "net/socket.c:do_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580929168,
      "name": "set_normalized_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void set_normalized_timespec64(struct timespec64 * ts, time64_t sec, s64 nsec)
```

```json
{
  "name": "set_normalized_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491319660,
      "name": "set_normalized_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:523",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:timespec64_add_safe"
      ],
      "caller_func": [
        "arch/arm/xen/enlighten.c:xen_pm_init",
        "arch/arm/xen/enlighten.c:xen_pvclock_gtod_notify",
        "kernel/time/timekeeping.c:ktime_get_coarse_ts64",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "fs/select.c:poll_select_finish",
        "fs/select.c:select_estimate_accuracy",
        "drivers/rtc/systohc.c:rtc_set_ntp_time",
        "drivers/rtc/systohc.c:rtc_set_ntp_time",
        "net/socket.c:do_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491310176,
      "name": "set_normalized_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void set_normalized_timespec64(struct timespec64 * ts, time64_t sec, s64 nsec)
```

```json
{
  "name": "set_normalized_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225312696,
      "name": "set_normalized_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:523",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:timespec64_add_safe"
      ],
      "caller_func": [
        "kernel/time/timekeeping.c:ktime_get_coarse_ts64",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "fs/select.c:poll_select_finish",
        "fs/select.c:select_estimate_accuracy",
        "drivers/rtc/systohc.c:rtc_set_ntp_time",
        "drivers/rtc/systohc.c:rtc_set_ntp_time",
        "net/socket.c:do_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225306768,
      "name": "set_normalized_timespec64",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void set_normalized_timespec64(struct timespec64 * ts, time64_t sec, s64 nsec)
```

```json
{
  "name": "set_normalized_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284243456,
      "name": "set_normalized_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:523",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:timespec64_add_safe"
      ],
      "caller_func": [
        "kernel/time/timekeeping.c:ktime_get_coarse_ts64",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "fs/select.c:poll_select_finish",
        "fs/select.c:select_estimate_accuracy",
        "drivers/rtc/systohc.c:rtc_set_ntp_time",
        "drivers/rtc/systohc.c:rtc_set_ntp_time",
        "net/socket.c:do_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284236080,
      "name": "set_normalized_timespec64",
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
void set_normalized_timespec64(struct timespec64 * ts, time64_t sec, s64 nsec)
```

```json
{
  "name": "set_normalized_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271821986,
      "name": "set_normalized_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:523",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:timespec64_add_safe"
      ],
      "caller_func": [
        "kernel/time/timekeeping.c:ktime_get_coarse_ts64",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "fs/select.c:poll_select_finish",
        "fs/select.c:select_estimate_accuracy",
        "drivers/rtc/systohc.c:rtc_set_ntp_time",
        "drivers/rtc/systohc.c:rtc_set_ntp_time",
        "net/socket.c:do_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271819148,
      "name": "set_normalized_timespec64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void set_normalized_timespec64(struct timespec64 * ts, time64_t sec, s64 nsec)
```

```json
{
  "name": "set_normalized_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580074545,
      "name": "set_normalized_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:523",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:timespec64_add_safe"
      ],
      "caller_func": [
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock",
        "kernel/time/timekeeping.c:ktime_get_coarse_ts64",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "fs/select.c:poll_select_finish",
        "fs/select.c:select_estimate_accuracy",
        "drivers/rtc/systohc.c:rtc_set_ntp_time",
        "drivers/rtc/systohc.c:rtc_set_ntp_time",
        "net/socket.c:do_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580068384,
      "name": "set_normalized_timespec64",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void set_normalized_timespec64(struct timespec64 * ts, time64_t sec, s64 nsec)
```

```json
{
  "name": "set_normalized_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580019361,
      "name": "set_normalized_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:523",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:timespec64_add_safe"
      ],
      "caller_func": [
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock",
        "kernel/time/timekeeping.c:ktime_get_coarse_ts64",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "fs/select.c:poll_select_finish",
        "fs/select.c:select_estimate_accuracy",
        "drivers/rtc/systohc.c:rtc_set_ntp_time",
        "drivers/rtc/systohc.c:rtc_set_ntp_time",
        "net/socket.c:do_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580013200,
      "name": "set_normalized_timespec64",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void set_normalized_timespec64(struct timespec64 * ts, time64_t sec, s64 nsec)
```

```json
{
  "name": "set_normalized_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580065617,
      "name": "set_normalized_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:523",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:timespec64_add_safe"
      ],
      "caller_func": [
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock",
        "kernel/time/timekeeping.c:ktime_get_coarse_ts64",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "fs/select.c:poll_select_finish",
        "fs/select.c:select_estimate_accuracy",
        "drivers/rtc/systohc.c:rtc_set_ntp_time",
        "drivers/rtc/systohc.c:rtc_set_ntp_time",
        "net/socket.c:do_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580059456,
      "name": "set_normalized_timespec64",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void set_normalized_timespec64(struct timespec64 * ts, time64_t sec, s64 nsec)
```

```json
{
  "name": "set_normalized_timespec64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580116385,
      "name": "set_normalized_timespec64",
      "external": true,
      "loc": "kernel/time/time.c:523",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:timespec64_add_safe"
      ],
      "caller_func": [
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock",
        "kernel/time/timekeeping.c:ktime_get_coarse_ts64",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "fs/select.c:poll_select_finish",
        "fs/select.c:select_estimate_accuracy",
        "drivers/rtc/systohc.c:rtc_set_ntp_time",
        "drivers/rtc/systohc.c:rtc_set_ntp_time",
        "net/socket.c:do_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580110272,
      "name": "set_normalized_timespec64",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void set_normalized_timespec64(struct timespec * ts, time64_t sec, s64 nsec)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timespec * ts</code> ➡️ <code>struct timespec64 * ts</code>
</li>
</ul>
</details>
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
