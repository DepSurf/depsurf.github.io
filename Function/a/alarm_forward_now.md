# Function: <code>alarm_forward_now</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
u64 alarm_forward_now(struct alarm * alarm, ktime_t interval)
```

```json
{
  "name": "alarm_forward_now",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579872016,
      "name": "alarm_forward_now",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:433",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:timerfd_read",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872016,
      "name": "alarm_forward_now",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
u64 alarm_forward_now(struct alarm * alarm, ktime_t interval)
```

```json
{
  "name": "alarm_forward_now",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579901312,
      "name": "alarm_forward_now",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:448",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579901312,
      "name": "alarm_forward_now",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
u64 alarm_forward_now(struct alarm * alarm, ktime_t interval)
```

```json
{
  "name": "alarm_forward_now",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579911472,
      "name": "alarm_forward_now",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:481",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579911472,
      "name": "alarm_forward_now",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
u64 alarm_forward_now(struct alarm * alarm, ktime_t interval)
```

```json
{
  "name": "alarm_forward_now",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579920046,
      "name": "alarm_forward_now",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:456",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_handle_timer"
      ],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579919968,
      "name": "alarm_forward_now",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 alarm_forward_now(struct alarm * alarm, ktime_t interval)
```

```json
{
  "name": "alarm_forward_now",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579965262,
      "name": "alarm_forward_now",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:470",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_handle_timer"
      ],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579965184,
      "name": "alarm_forward_now",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
u64 alarm_forward_now(struct alarm * alarm, ktime_t interval)
```

```json
{
  "name": "alarm_forward_now",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580012879,
      "name": "alarm_forward_now",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:477",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_handle_timer"
      ],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:timerfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580012784,
      "name": "alarm_forward_now",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
u64 alarm_forward_now(struct alarm * alarm, ktime_t interval)
```

```json
{
  "name": "alarm_forward_now",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580059791,
      "name": "alarm_forward_now",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:474",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_handle_timer"
      ],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:timerfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580059696,
      "name": "alarm_forward_now",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
u64 alarm_forward_now(struct alarm * alarm, ktime_t interval)
```

```json
{
  "name": "alarm_forward_now",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580103503,
      "name": "alarm_forward_now",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:473",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_handle_timer"
      ],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:timerfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580103408,
      "name": "alarm_forward_now",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 alarm_forward_now(struct alarm * alarm, ktime_t interval)
```

```json
{
  "name": "alarm_forward_now",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580152367,
      "name": "alarm_forward_now",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:482",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_handle_timer"
      ],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:timerfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580152272,
      "name": "alarm_forward_now",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 alarm_forward_now(struct alarm * alarm, ktime_t interval)
```

```json
{
  "name": "alarm_forward_now",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580215791,
      "name": "alarm_forward_now",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:473",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_handle_timer"
      ],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580218544,
      "name": "alarm_forward_now",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
u64 alarm_forward_now(struct alarm * alarm, ktime_t interval)
```

```json
{
  "name": "alarm_forward_now",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580200031,
      "name": "alarm_forward_now",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:473",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_handle_timer"
      ],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580202800,
      "name": "alarm_forward_now",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
u64 alarm_forward_now(struct alarm * alarm, ktime_t interval)
```

```json
{
  "name": "alarm_forward_now",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580205343,
      "name": "alarm_forward_now",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:473",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_handle_timer"
      ],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580208096,
      "name": "alarm_forward_now",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
u64 alarm_forward_now(struct alarm * alarm, ktime_t interval)
```

```json
{
  "name": "alarm_forward_now",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580352162,
      "name": "alarm_forward_now",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:473",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_rearm"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarm_handle_timer",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580353792,
      "name": "alarm_forward_now",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
u64 alarm_forward_now(struct alarm * alarm, ktime_t interval)
```

```json
{
  "name": "alarm_forward_now",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580566450,
      "name": "alarm_forward_now",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:473",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_rearm"
      ],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarm_handle_timer",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580568192,
      "name": "alarm_forward_now",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
u64 alarm_forward_now(struct alarm * alarm, ktime_t interval)
```

```json
{
  "name": "alarm_forward_now",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580826802,
      "name": "alarm_forward_now",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:499",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_rearm"
      ],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580828688,
      "name": "alarm_forward_now",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
u64 alarm_forward_now(struct alarm * alarm, ktime_t interval)
```

```json
{
  "name": "alarm_forward_now",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580910370,
      "name": "alarm_forward_now",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:498",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_rearm"
      ],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580912240,
      "name": "alarm_forward_now",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
u64 alarm_forward_now(struct alarm * alarm, ktime_t interval)
```

```json
{
  "name": "alarm_forward_now",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581000898,
      "name": "alarm_forward_now",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:509",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_rearm"
      ],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:timerfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581002768,
      "name": "alarm_forward_now",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
u64 alarm_forward_now(struct alarm * alarm, ktime_t interval)
```

```json
{
  "name": "alarm_forward_now",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491373792,
      "name": "alarm_forward_now",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:482",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_handle_timer"
      ],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:timerfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491371584,
      "name": "alarm_forward_now",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
u64 alarm_forward_now(struct alarm * alarm, ktime_t interval)
```

```json
{
  "name": "alarm_forward_now",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225372280,
      "name": "alarm_forward_now",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:482",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_handle_timer",
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:timerfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225372280,
      "name": "alarm_forward_now",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
u64 alarm_forward_now(struct alarm * alarm, ktime_t interval)
```

```json
{
  "name": "alarm_forward_now",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284311240,
      "name": "alarm_forward_now",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:482",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_handle_timer"
      ],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:timerfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284311056,
      "name": "alarm_forward_now",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
u64 alarm_forward_now(struct alarm * alarm, ktime_t interval)
```

```json
{
  "name": "alarm_forward_now",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271862526,
      "name": "alarm_forward_now",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:482",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_handle_timer"
      ],
      "caller_func": [
        "fs/timerfd.c:__se_sys_timerfd_gettime",
        "fs/timerfd.c:__se_sys_timerfd_settime",
        "fs/timerfd.c:timerfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271862422,
      "name": "alarm_forward_now",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
u64 alarm_forward_now(struct alarm * alarm, ktime_t interval)
```

```json
{
  "name": "alarm_forward_now",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580121567,
      "name": "alarm_forward_now",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:482",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_handle_timer"
      ],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:timerfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580121472,
      "name": "alarm_forward_now",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
u64 alarm_forward_now(struct alarm * alarm, ktime_t interval)
```

```json
{
  "name": "alarm_forward_now",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580066863,
      "name": "alarm_forward_now",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:482",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_handle_timer"
      ],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:timerfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580066768,
      "name": "alarm_forward_now",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
u64 alarm_forward_now(struct alarm * alarm, ktime_t interval)
```

```json
{
  "name": "alarm_forward_now",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580112639,
      "name": "alarm_forward_now",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:482",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_handle_timer"
      ],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:timerfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580112544,
      "name": "alarm_forward_now",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
u64 alarm_forward_now(struct alarm * alarm, ktime_t interval)
```

```json
{
  "name": "alarm_forward_now",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580164399,
      "name": "alarm_forward_now",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:482",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_rearm",
        "kernel/time/alarmtimer.c:alarm_handle_timer"
      ],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_gettime",
        "fs/timerfd.c:timerfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580164304,
      "name": "alarm_forward_now",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
