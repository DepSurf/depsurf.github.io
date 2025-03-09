# Function: <code>ktime_get_boottime</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_boottime()
```

```json
{
  "name": "ktime_get_boottime",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579364148,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:188",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579446215,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:188",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:do_sysinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579822864,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:188",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579830966,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:188",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_boottime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579872480,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:188",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580391441,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:188",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_boot_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581479949,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:188",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585583513,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:188",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:__evdev_queue_syn_dropped"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585666740,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:188",
      "file": "drivers/power/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/charger-manager.c:cm_suspend_prepare"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579822864,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071579872480,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_boottime()
```

```json
{
  "name": "ktime_get_boottime",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579371529,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:204",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579458903,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:204",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:do_sysinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579706268,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:204",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579851504,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:204",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579859670,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:204",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_boottime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579901904,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:204",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580459185,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:204",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_boot_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581664360,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:204",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585977545,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:204",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:__evdev_queue_syn_dropped"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586063524,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:204",
      "file": "drivers/power/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/charger-manager.c:cm_suspend_prepare"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851504,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071579901904,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_boottime()
```

```json
{
  "name": "ktime_get_boottime",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579390169,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:204",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579479335,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:204",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:do_sysinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579733836,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:204",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579880112,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:204",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579912176,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:204",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579915382,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:204",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_boottime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580521633,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:204",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_boot_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581752925,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:204",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586165865,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:204",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:__evdev_queue_syn_dropped"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586261267,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:204",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579880112,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071579912176,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_boottime()
```

```json
{
  "name": "ktime_get_boottime",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579377670,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579466537,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:do_sysinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579729740,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579889424,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579921328,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579924742,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_boottime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580554225,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_boot_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581806694,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586254572,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:__evdev_queue_syn_dropped"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586360502,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:193",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579889424,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071579921328,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_boottime()
```

```json
{
  "name": "ktime_get_boottime",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579404406,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:73",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579494425,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:73",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:do_sysinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579762748,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:73",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579933936,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:73",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579966560,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:73",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579970166,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:73",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_boottime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580547576,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:73",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580634993,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:73",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_boot_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581956188,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:73",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586718060,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:73",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:__evdev_queue_syn_dropped"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586825302,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:73",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579933936,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071579966560,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_boottime()
```

```json
{
  "name": "ktime_get_boottime",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579420139,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:78",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579517063,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:78",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:do_sysinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579797237,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:78",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579981840,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:78",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580014160,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:78",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580017877,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:78",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_boottime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580638851,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:78",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580761552,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:78",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_boot_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582141402,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:78",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586983561,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:78",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:__evdev_queue_syn_dropped"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587122347,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:78",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579981840,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071580014160,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_boottime()
```

```json
{
  "name": "ktime_get_boottime",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579454054,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579553367,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:do_sysinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579843845,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580028640,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580061184,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580065061,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_boottime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580695234,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580828368,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_boot_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582236026,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587144681,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:__evdev_queue_syn_dropped"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587300284,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580028640,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071580061184,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_boottime()
```

```json
{
  "name": "ktime_get_boottime",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579472411,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579575974,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:do_sysinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579877861,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580071520,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580104784,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580108709,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_boottime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580766800,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580923328,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_boottime_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582400439,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587409641,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:__evdev_queue_syn_dropped"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587569482,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587641384,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:submit_flushes"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580071520,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071580104784,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_boottime()
```

```json
{
  "name": "ktime_get_boottime",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579498515,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579602294,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:do_sysinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579928069,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580121056,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580153760,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580157877,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_boottime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580817781,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580977520,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_boottime_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582499399,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587772727,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587845495,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:submit_flushes"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580121056,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071580153760,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_boottime()
```

```json
{
  "name": "ktime_get_boottime",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579527460,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579635434,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579972101,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580181008,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580213910,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:get_boottime_timespec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580219045,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_boottime_ktime",
        "kernel/time/posix-timers.c:posix_get_boottime_timespec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580263500,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/namespace.c:proc_timens_set_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580943106,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581144048,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_boottime_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582800651,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588620121,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_setup_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588699031,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:submit_flushes"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580181008,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071580213856,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_boottime()
```

```json
{
  "name": "ktime_get_boottime",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579509761,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:92",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579615306,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:92",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579959893,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:92",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580165936,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:92",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580198182,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:92",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:get_boottime_timespec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580203301,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:92",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_boottime_ktime",
        "kernel/time/posix-timers.c:posix_get_boottime_timespec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580247205,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:92",
      "file": "kernel/time/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/namespace.c:proc_timens_set_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580940120,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:92",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581184096,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:92",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_boottime_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582874283,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:92",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591581476,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:92",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_setup_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588726375,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:92",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:submit_flushes"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580165936,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071580198128,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_boottime()
```

```json
{
  "name": "ktime_get_boottime",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579513022,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579621578,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579962517,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580170496,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580203494,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:get_boottime_timespec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580208597,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_boottime_ktime",
        "kernel/time/posix-timers.c:posix_get_boottime_timespec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580252325,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/namespace.c:proc_timens_set_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580942595,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581202464,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_boottime_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582902625,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591524011,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_setup_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588615719,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:submit_flushes"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580170496,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071580203440,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_boottime()
```

```json
{
  "name": "ktime_get_boottime",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579584591,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579698077,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580092277,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580314864,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580350198,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:get_boottime_timespec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580356117,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_boottime_ktime",
        "kernel/time/posix-timers.c:posix_get_boottime_timespec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580403482,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/namespace.c:proc_timens_set_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581146662,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581442112,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_boottime_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583236791,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592634096,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_setup_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589292903,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:submit_flushes"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580314864,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071580350144,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_boottime()
```

```json
{
  "name": "ktime_get_boottime",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579675969,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579800285,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580229493,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580525744,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580564486,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:get_boottime_timespec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580570789,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_boottime_ktime",
        "kernel/time/posix-timers.c:posix_get_boottime_timespec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580622856,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/namespace.c:proc_timens_set_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581421846,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581783344,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_boottime_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583735644,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588497436,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:random_pm_notification"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594517498,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_setup_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590729447,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:submit_flushes"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580525744,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071580564416,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_boottime()
```

```json
{
  "name": "ktime_get_boottime",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579796182,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579935149,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580421526,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580781568,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580824662,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:get_boottime_timespec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580831365,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_boottime_ktime",
        "kernel/time/posix-timers.c:posix_get_boottime_timespec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580888632,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/namespace.c:proc_timens_set_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581771235,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582209104,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_boottime_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584348930,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589565128,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:_regulator_do_disable",
        "drivers/regulator/core.c:_regulator_do_enable",
        "drivers/regulator/core.c:set_machine_constraints"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589937596,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:random_pm_notification"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592318447,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_setup_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592404903,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:submit_flushes"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580781568,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071580824576,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_boottime()
```

```json
{
  "name": "ktime_get_boottime",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579844405,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579985021,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580490886,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580864560,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580908166,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:get_boottime_timespec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580914917,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_boottime_ktime",
        "kernel/time/posix-timers.c:posix_get_boottime_timespec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580972549,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/namespace.c:proc_timens_set_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581933469,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582409120,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_boottime_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584579202,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589867176,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:_regulator_do_disable",
        "drivers/regulator/core.c:_regulator_do_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590246876,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:random_pm_notification"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592745055,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_setup_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592834343,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:submit_flushes"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580864560,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071580908080,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_boottime()
```

```json
{
  "name": "ktime_get_boottime",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579882231,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:94",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580024429,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:94",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580550774,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:94",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580955232,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:94",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580998694,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:94",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:get_boottime_timespec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581005525,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:94",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_boottime_ktime",
        "kernel/time/posix-timers.c:posix_get_boottime_timespec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581067285,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:94",
      "file": "kernel/time/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/namespace.c:proc_timens_set_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582060051,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:94",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582577344,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:94",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_boottime_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584810465,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:94",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590205016,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:94",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:_regulator_do_disable",
        "drivers/regulator/core.c:_regulator_do_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590587900,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:94",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:random_pm_notification"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593493007,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:94",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_setup_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593607527,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:94",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:submit_flushes"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580955232,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071580998608,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_boottime()
```

```json
{
  "name": "ktime_get_boottime",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490630832,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490763480,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:do_sysinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491137508,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491338488,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491371784,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491379584,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_boottime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492140992,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492326248,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_boottime_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494123512,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500966764,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501079516,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:submit_flushes"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491338488,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336491371784,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_boottime()
```

```json
{
  "name": "ktime_get_boottime",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224709280,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 3224824416,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__se_sys_sysinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 3225134564,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 3225331944,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225373844,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225379344,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_boottime"
      ],
      "caller_func": []
    },
    {
      "addr": 3226037204,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 3226218300,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_boottime_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 3227573104,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 3233480296,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 3233560240,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:submit_flushes"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225331944,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 3225373844,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_boottime()
```

```json
{
  "name": "ktime_get_boottime",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283450400,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283593572,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:do_sysinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284029940,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284268832,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284313472,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284320208,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_boottime"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285347312,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285572548,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_boottime_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287795968,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294430856,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294575268,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:submit_flushes"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284268832,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 13835058055284313472,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_boottime()
```

```json
{
  "name": "ktime_get_boottime",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271386296,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271458684,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__do_sys_sysinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271702728,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271836194,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271863928,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271867596,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_boottime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272303652,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272451112,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_boottime_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273605968,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277725132,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277807742,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:submit_flushes"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271836194,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446743936271863928,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_boottime()
```

```json
{
  "name": "ktime_get_boottime",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579472179,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579578598,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:do_sysinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579899717,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580090256,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580122960,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580127077,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_boottime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580786581,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580946320,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_boottime_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582468135,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587476471,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:submit_flushes"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580090256,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071580122960,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_boottime()
```

```json
{
  "name": "ktime_get_boottime",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579401091,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579507222,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:do_sysinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579835141,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580035584,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580068256,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580072373,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_boottime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580732757,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580892384,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_boottime_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582405367,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587244647,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:submit_flushes"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580035584,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071580068256,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_boottime()
```

```json
{
  "name": "ktime_get_boottime",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579472099,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579575878,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:do_sysinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579888341,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580081328,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580114032,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580118149,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_boottime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580777829,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580937568,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_boottime_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582458615,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587728871,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587801639,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:submit_flushes"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580081328,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071580114032,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_boottime()
```

```json
{
  "name": "ktime_get_boottime",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579503900,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579610182,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:do_sysinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579934101,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580132864,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580165824,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580170005,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_boottime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580836101,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580999152,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_boottime_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582538967,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587841927,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587893351,
      "name": "ktime_get_boottime",
      "external": false,
      "loc": "include/linux/timekeeping.h:93",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_flush_request",
        "drivers/md/md.c:submit_flushes"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580132864,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071580165824,
      "name": "ktime_get_boottime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
