# Function: <code>alarm_start</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void alarm_start(struct alarm * alarm, ktime_t start)
```

```json
{
  "name": "alarm_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579871696,
      "name": "alarm_start",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:320",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "kernel/time/alarmtimer.c:alarm_timer_set",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "fs/timerfd.c:do_timerfd_settime",
        "drivers/power/charger-manager.c:cm_suspend_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579871696,
      "name": "alarm_start",
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
void alarm_start(struct alarm * alarm, ktime_t start)
```

```json
{
  "name": "alarm_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579900992,
      "name": "alarm_start",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:335",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_set",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "fs/timerfd.c:do_timerfd_settime",
        "drivers/power/charger-manager.c:cm_suspend_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579900992,
      "name": "alarm_start",
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
void alarm_start(struct alarm * alarm, ktime_t start)
```

```json
{
  "name": "alarm_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579910960,
      "name": "alarm_start",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:364",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_set",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "fs/timerfd.c:do_timerfd_settime",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579910960,
      "name": "alarm_start",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void alarm_start(struct alarm * alarm, ktime_t start)
```

```json
{
  "name": "alarm_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579919392,
      "name": "alarm_start",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:339",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "fs/timerfd.c:do_timerfd_settime",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579919392,
      "name": "alarm_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
void alarm_start(struct alarm * alarm, ktime_t start)
```

```json
{
  "name": "alarm_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579964576,
      "name": "alarm_start",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:353",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "fs/timerfd.c:do_timerfd_settime",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579964576,
      "name": "alarm_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void alarm_start(struct alarm * alarm, ktime_t start)
```

```json
{
  "name": "alarm_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580012176,
      "name": "alarm_start",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:360",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580012176,
      "name": "alarm_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void alarm_start(struct alarm * alarm, ktime_t start)
```

```json
{
  "name": "alarm_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580059200,
      "name": "alarm_start",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:357",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580059200,
      "name": "alarm_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void alarm_start(struct alarm * alarm, ktime_t start)
```

```json
{
  "name": "alarm_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580102784,
      "name": "alarm_start",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:356",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580102784,
      "name": "alarm_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void alarm_start(struct alarm * alarm, ktime_t start)
```

```json
{
  "name": "alarm_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580151776,
      "name": "alarm_start",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:365",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580151776,
      "name": "alarm_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void alarm_start(struct alarm * alarm, ktime_t start)
```

```json
{
  "name": "alarm_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580215408,
      "name": "alarm_start",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:356",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "fs/timerfd.c:do_timerfd_settime",
        "drivers/power/supply/charger-manager.c:cm_setup_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580215408,
      "name": "alarm_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void alarm_start(struct alarm * alarm, ktime_t start)
```

```json
{
  "name": "alarm_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580199648,
      "name": "alarm_start",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:356",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "fs/timerfd.c:do_timerfd_settime",
        "drivers/power/supply/charger-manager.c:cm_setup_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580199648,
      "name": "alarm_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
void alarm_start(struct alarm * alarm, ktime_t start)
```

```json
{
  "name": "alarm_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580204960,
      "name": "alarm_start",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:356",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "fs/timerfd.c:do_timerfd_settime",
        "drivers/power/supply/charger-manager.c:cm_setup_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580204960,
      "name": "alarm_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
void alarm_start(struct alarm * alarm, ktime_t start)
```

```json
{
  "name": "alarm_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580351744,
      "name": "alarm_start",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:356",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "fs/timerfd.c:do_timerfd_settime",
        "drivers/power/supply/charger-manager.c:cm_setup_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580351744,
      "name": "alarm_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void alarm_start(struct alarm * alarm, ktime_t start)
```

```json
{
  "name": "alarm_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580566000,
      "name": "alarm_start",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:356",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "fs/timerfd.c:do_timerfd_settime",
        "drivers/power/supply/charger-manager.c:cm_setup_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580566000,
      "name": "alarm_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
void alarm_start(struct alarm * alarm, ktime_t start)
```

```json
{
  "name": "alarm_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580826320,
      "name": "alarm_start",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:356",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "fs/timerfd.c:do_timerfd_settime",
        "drivers/power/supply/charger-manager.c:cm_setup_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580826320,
      "name": "alarm_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
void alarm_start(struct alarm * alarm, ktime_t start)
```

```json
{
  "name": "alarm_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580909888,
      "name": "alarm_start",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:355",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "fs/timerfd.c:do_timerfd_settime",
        "drivers/power/supply/charger-manager.c:cm_setup_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580909888,
      "name": "alarm_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
void alarm_start(struct alarm * alarm, ktime_t start)
```

```json
{
  "name": "alarm_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581000416,
      "name": "alarm_start",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:366",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "fs/timerfd.c:do_timerfd_settime",
        "drivers/power/supply/charger-manager.c:cm_setup_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581000416,
      "name": "alarm_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
void alarm_start(struct alarm * alarm, ktime_t start)
```

```json
{
  "name": "alarm_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491373280,
      "name": "alarm_start",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:365",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491373280,
      "name": "alarm_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
void alarm_start(struct alarm * alarm, ktime_t start)
```

```json
{
  "name": "alarm_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225371308,
      "name": "alarm_start",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:365",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225371308,
      "name": "alarm_start",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void alarm_start(struct alarm * alarm, ktime_t start)
```

```json
{
  "name": "alarm_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284310176,
      "name": "alarm_start",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:365",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284310176,
      "name": "alarm_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
void alarm_start(struct alarm * alarm, ktime_t start)
```

```json
{
  "name": "alarm_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271861880,
      "name": "alarm_start",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:365",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "fs/timerfd.c:__se_sys_timerfd_settime",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271861880,
      "name": "alarm_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void alarm_start(struct alarm * alarm, ktime_t start)
```

```json
{
  "name": "alarm_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580120976,
      "name": "alarm_start",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:365",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_start_relative"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580120976,
      "name": "alarm_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void alarm_start(struct alarm * alarm, ktime_t start)
```

```json
{
  "name": "alarm_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580066272,
      "name": "alarm_start",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:365",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_start_relative"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580066272,
      "name": "alarm_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void alarm_start(struct alarm * alarm, ktime_t start)
```

```json
{
  "name": "alarm_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580112048,
      "name": "alarm_start",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:365",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580112048,
      "name": "alarm_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void alarm_start(struct alarm * alarm, ktime_t start)
```

```json
{
  "name": "alarm_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580163792,
      "name": "alarm_start",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:365",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_arm",
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_start_relative",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580163792,
      "name": "alarm_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
