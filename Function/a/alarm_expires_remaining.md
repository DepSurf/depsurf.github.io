# Function: <code>alarm_expires_remaining</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
ktime_t alarm_expires_remaining(const struct alarm * alarm)
```

```json
{
  "name": "alarm_expires_remaining",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579871328,
      "name": "alarm_expires_remaining",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:202",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_get"
      ],
      "caller_func": [
        "fs/timerfd.c:timerfd_get_remaining",
        "drivers/power/charger-manager.c:cm_suspend_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579871328,
      "name": "alarm_expires_remaining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
ktime_t alarm_expires_remaining(const struct alarm * alarm)
```

```json
{
  "name": "alarm_expires_remaining",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579901950,
      "name": "alarm_expires_remaining",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:201",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_get"
      ],
      "caller_func": [
        "fs/timerfd.c:timerfd_get_remaining",
        "drivers/power/charger-manager.c:cm_suspend_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579900624,
      "name": "alarm_expires_remaining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
ktime_t alarm_expires_remaining(const struct alarm * alarm)
```

```json
{
  "name": "alarm_expires_remaining",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579912222,
      "name": "alarm_expires_remaining",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:207",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_get"
      ],
      "caller_func": [
        "fs/timerfd.c:timerfd_get_remaining",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579909680,
      "name": "alarm_expires_remaining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
ktime_t alarm_expires_remaining(const struct alarm * alarm)
```

```json
{
  "name": "alarm_expires_remaining",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579918144,
      "name": "alarm_expires_remaining",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:214",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:timerfd_get_remaining",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579918144,
      "name": "alarm_expires_remaining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
ktime_t alarm_expires_remaining(const struct alarm * alarm)
```

```json
{
  "name": "alarm_expires_remaining",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579963328,
      "name": "alarm_expires_remaining",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:228",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:timerfd_get_remaining",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579963328,
      "name": "alarm_expires_remaining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
ktime_t alarm_expires_remaining(const struct alarm * alarm)
```

```json
{
  "name": "alarm_expires_remaining",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580010944,
      "name": "alarm_expires_remaining",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:228",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:timerfd_get_remaining",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580010944,
      "name": "alarm_expires_remaining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
ktime_t alarm_expires_remaining(const struct alarm * alarm)
```

```json
{
  "name": "alarm_expires_remaining",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580057968,
      "name": "alarm_expires_remaining",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:225",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:timerfd_get_remaining",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580057968,
      "name": "alarm_expires_remaining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
ktime_t alarm_expires_remaining(const struct alarm * alarm)
```

```json
{
  "name": "alarm_expires_remaining",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580101552,
      "name": "alarm_expires_remaining",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:225",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:timerfd_get_remaining",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580101552,
      "name": "alarm_expires_remaining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
ktime_t alarm_expires_remaining(const struct alarm * alarm)
```

```json
{
  "name": "alarm_expires_remaining",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580150528,
      "name": "alarm_expires_remaining",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:234",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:timerfd_get_remaining",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580150528,
      "name": "alarm_expires_remaining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
ktime_t alarm_expires_remaining(const struct alarm * alarm)
```

```json
{
  "name": "alarm_expires_remaining",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580212528,
      "name": "alarm_expires_remaining",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:225",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_show",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580212528,
      "name": "alarm_expires_remaining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
ktime_t alarm_expires_remaining(const struct alarm * alarm)
```

```json
{
  "name": "alarm_expires_remaining",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580196800,
      "name": "alarm_expires_remaining",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:225",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_show",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580196800,
      "name": "alarm_expires_remaining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
ktime_t alarm_expires_remaining(const struct alarm * alarm)
```

```json
{
  "name": "alarm_expires_remaining",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580202112,
      "name": "alarm_expires_remaining",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:225",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_show",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580202112,
      "name": "alarm_expires_remaining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
ktime_t alarm_expires_remaining(const struct alarm * alarm)
```

```json
{
  "name": "alarm_expires_remaining",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580348752,
      "name": "alarm_expires_remaining",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:225",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_show",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580348752,
      "name": "alarm_expires_remaining",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
ktime_t alarm_expires_remaining(const struct alarm * alarm)
```

```json
{
  "name": "alarm_expires_remaining",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580562656,
      "name": "alarm_expires_remaining",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:225",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_show",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580562656,
      "name": "alarm_expires_remaining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
ktime_t alarm_expires_remaining(const struct alarm * alarm)
```

```json
{
  "name": "alarm_expires_remaining",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580822320,
      "name": "alarm_expires_remaining",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:225",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_show",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580822320,
      "name": "alarm_expires_remaining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
ktime_t alarm_expires_remaining(const struct alarm * alarm)
```

```json
{
  "name": "alarm_expires_remaining",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580905824,
      "name": "alarm_expires_remaining",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:224",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_show",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580905824,
      "name": "alarm_expires_remaining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
ktime_t alarm_expires_remaining(const struct alarm * alarm)
```

```json
{
  "name": "alarm_expires_remaining",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580996352,
      "name": "alarm_expires_remaining",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:224",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_show",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580996352,
      "name": "alarm_expires_remaining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
ktime_t alarm_expires_remaining(const struct alarm * alarm)
```

```json
{
  "name": "alarm_expires_remaining",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491370520,
      "name": "alarm_expires_remaining",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:234",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:timerfd_get_remaining",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491370520,
      "name": "alarm_expires_remaining",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
ktime_t alarm_expires_remaining(const struct alarm * alarm)
```

```json
{
  "name": "alarm_expires_remaining",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225369788,
      "name": "alarm_expires_remaining",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:234",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:timerfd_get_remaining",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225369788,
      "name": "alarm_expires_remaining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
ktime_t alarm_expires_remaining(const struct alarm * alarm)
```

```json
{
  "name": "alarm_expires_remaining",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284308016,
      "name": "alarm_expires_remaining",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:234",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:timerfd_get_remaining",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284308016,
      "name": "alarm_expires_remaining",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
ktime_t alarm_expires_remaining(const struct alarm * alarm)
```

```json
{
  "name": "alarm_expires_remaining",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271860756,
      "name": "alarm_expires_remaining",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:234",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:timerfd_get_remaining",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271860756,
      "name": "alarm_expires_remaining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
ktime_t alarm_expires_remaining(const struct alarm * alarm)
```

```json
{
  "name": "alarm_expires_remaining",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580119728,
      "name": "alarm_expires_remaining",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:234",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:timerfd_get_remaining"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580119728,
      "name": "alarm_expires_remaining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
ktime_t alarm_expires_remaining(const struct alarm * alarm)
```

```json
{
  "name": "alarm_expires_remaining",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580065024,
      "name": "alarm_expires_remaining",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:234",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:timerfd_get_remaining"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580065024,
      "name": "alarm_expires_remaining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
ktime_t alarm_expires_remaining(const struct alarm * alarm)
```

```json
{
  "name": "alarm_expires_remaining",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580110800,
      "name": "alarm_expires_remaining",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:234",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:timerfd_get_remaining",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580110800,
      "name": "alarm_expires_remaining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
ktime_t alarm_expires_remaining(const struct alarm * alarm)
```

```json
{
  "name": "alarm_expires_remaining",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580162544,
      "name": "alarm_expires_remaining",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:234",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:timerfd_get_remaining",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580162544,
      "name": "alarm_expires_remaining",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
