# Function: <code>alarm_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void alarm_init(struct alarm * alarm, enum alarmtimer_type type, enum alarmtimer_restart (*)(struct alarm *, ktime_t) function)
```

```json
{
  "name": "alarm_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579871536,
      "name": "alarm_init",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:302",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_create",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart"
      ],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:SyS_timerfd_create",
        "drivers/power/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579871536,
      "name": "alarm_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void alarm_init(struct alarm * alarm, enum alarmtimer_type type, enum alarmtimer_restart (*)(struct alarm *, ktime_t) function)
```

```json
{
  "name": "alarm_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579903979,
      "name": "alarm_init",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:317",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/time/alarmtimer.c:alarm_timer_create"
      ],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:SyS_timerfd_create",
        "drivers/power/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579900832,
      "name": "alarm_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void alarm_init(struct alarm * alarm, enum alarmtimer_type type, enum alarmtimer_restart (*)(struct alarm *, ktime_t) function)
```

```json
{
  "name": "alarm_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579914507,
      "name": "alarm_init",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:346",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/time/alarmtimer.c:alarm_timer_create"
      ],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:SyS_timerfd_create",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579910800,
      "name": "alarm_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void alarm_init(struct alarm * alarm, enum alarmtimer_type type, enum alarmtimer_restart (*)(struct alarm *, ktime_t) function)
```

```json
{
  "name": "alarm_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579922754,
      "name": "alarm_init",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:321",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/time/alarmtimer.c:alarm_timer_create"
      ],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:SyS_timerfd_create",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579919248,
      "name": "alarm_init",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void alarm_init(struct alarm * alarm, enum alarmtimer_type type, enum alarmtimer_restart (*)(struct alarm *, ktime_t) function)
```

```json
{
  "name": "alarm_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579968114,
      "name": "alarm_init",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:335",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/time/alarmtimer.c:alarm_timer_create"
      ],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:SyS_timerfd_create",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579964432,
      "name": "alarm_init",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void alarm_init(struct alarm * alarm, enum alarmtimer_type type, enum alarmtimer_restart (*)(struct alarm *, ktime_t) function)
```

```json
{
  "name": "alarm_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580013047,
      "name": "alarm_init",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:346",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_create"
      ],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580012032,
      "name": "alarm_init",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void alarm_init(struct alarm * alarm, enum alarmtimer_type type, enum alarmtimer_restart (*)(struct alarm *, ktime_t) function)
```

```json
{
  "name": "alarm_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580060071,
      "name": "alarm_init",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:343",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_create"
      ],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580059056,
      "name": "alarm_init",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void alarm_init(struct alarm * alarm, enum alarmtimer_type type, enum alarmtimer_restart (*)(struct alarm *, ktime_t) function)
```

```json
{
  "name": "alarm_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580103671,
      "name": "alarm_init",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:342",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_create"
      ],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580102640,
      "name": "alarm_init",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void alarm_init(struct alarm * alarm, enum alarmtimer_type type, enum alarmtimer_restart (*)(struct alarm *, ktime_t) function)
```

```json
{
  "name": "alarm_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580152647,
      "name": "alarm_init",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:351",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_create"
      ],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580151632,
      "name": "alarm_init",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void alarm_init(struct alarm * alarm, enum alarmtimer_type type, enum alarmtimer_restart (*)(struct alarm *, ktime_t) function)
```

```json
{
  "name": "alarm_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580217264,
      "name": "alarm_init",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:342",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/time/alarmtimer.c:alarm_timer_create"
      ],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:__do_sys_timerfd_create",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580213600,
      "name": "alarm_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void alarm_init(struct alarm * alarm, enum alarmtimer_type type, enum alarmtimer_restart (*)(struct alarm *, ktime_t) function)
```

```json
{
  "name": "alarm_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580201680,
      "name": "alarm_init",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:342",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/time/alarmtimer.c:alarm_timer_create"
      ],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:__do_sys_timerfd_create",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580197872,
      "name": "alarm_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void alarm_init(struct alarm * alarm, enum alarmtimer_type type, enum alarmtimer_restart (*)(struct alarm *, ktime_t) function)
```

```json
{
  "name": "alarm_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580206992,
      "name": "alarm_init",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:342",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/time/alarmtimer.c:alarm_timer_create"
      ],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:__do_sys_timerfd_create",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580203184,
      "name": "alarm_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void alarm_init(struct alarm * alarm, enum alarmtimer_type type, enum alarmtimer_restart (*)(struct alarm *, ktime_t) function)
```

```json
{
  "name": "alarm_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580354256,
      "name": "alarm_init",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:342",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/time/alarmtimer.c:alarm_timer_create"
      ],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:__do_sys_timerfd_create",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580349872,
      "name": "alarm_init",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void alarm_init(struct alarm * alarm, enum alarmtimer_type type, enum alarmtimer_restart (*)(struct alarm *, ktime_t) function)
```

```json
{
  "name": "alarm_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580568717,
      "name": "alarm_init",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:342",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/time/alarmtimer.c:alarm_timer_create"
      ],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:__do_sys_timerfd_create",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580564096,
      "name": "alarm_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void alarm_init(struct alarm * alarm, enum alarmtimer_type type, enum alarmtimer_restart (*)(struct alarm *, ktime_t) function)
```

```json
{
  "name": "alarm_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580829069,
      "name": "alarm_init",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:342",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/time/alarmtimer.c:alarm_timer_create"
      ],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:__do_sys_timerfd_create",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580823952,
      "name": "alarm_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void alarm_init(struct alarm * alarm, enum alarmtimer_type type, enum alarmtimer_restart (*)(struct alarm *, ktime_t) function)
```

```json
{
  "name": "alarm_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580912621,
      "name": "alarm_init",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:341",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/time/alarmtimer.c:alarm_timer_create"
      ],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:__do_sys_timerfd_create",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580907456,
      "name": "alarm_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void alarm_init(struct alarm * alarm, enum alarmtimer_type type, enum alarmtimer_restart (*)(struct alarm *, ktime_t) function)
```

```json
{
  "name": "alarm_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581003149,
      "name": "alarm_init",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:352",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/time/alarmtimer.c:alarm_timer_create"
      ],
      "caller_func": [
        "fs/timerfd.c:do_timerfd_settime",
        "fs/timerfd.c:__do_sys_timerfd_create",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580997984,
      "name": "alarm_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void alarm_init(struct alarm * alarm, enum alarmtimer_type type, enum alarmtimer_restart (*)(struct alarm *, ktime_t) function)
```

```json
{
  "name": "alarm_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491372768,
      "name": "alarm_init",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:351",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_create"
      ],
      "caller_func": [
        "fs/timerfd.c:__arm64_sys_timerfd_create",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491371232,
      "name": "alarm_init",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void alarm_init(struct alarm * alarm, enum alarmtimer_type type, enum alarmtimer_restart (*)(struct alarm *, ktime_t) function)
```

```json
{
  "name": "alarm_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225372588,
      "name": "alarm_init",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:351",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_create"
      ],
      "caller_func": [
        "fs/timerfd.c:__se_sys_timerfd_create",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225371128,
      "name": "alarm_init",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void alarm_init(struct alarm * alarm, enum alarmtimer_type type, enum alarmtimer_restart (*)(struct alarm *, ktime_t) function)
```

```json
{
  "name": "alarm_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284311668,
      "name": "alarm_init",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:351",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_create"
      ],
      "caller_func": [
        "fs/timerfd.c:__se_sys_timerfd_create",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284309840,
      "name": "alarm_init",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void alarm_init(struct alarm * alarm, enum alarmtimer_type type, enum alarmtimer_restart (*)(struct alarm *, ktime_t) function)
```

```json
{
  "name": "alarm_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271862860,
      "name": "alarm_init",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:351",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_create"
      ],
      "caller_func": [
        "fs/timerfd.c:__se_sys_timerfd_settime",
        "fs/timerfd.c:__se_sys_timerfd_create",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271861692,
      "name": "alarm_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void alarm_init(struct alarm * alarm, enum alarmtimer_type type, enum alarmtimer_restart (*)(struct alarm *, ktime_t) function)
```

```json
{
  "name": "alarm_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580121847,
      "name": "alarm_init",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:351",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_create"
      ],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580120832,
      "name": "alarm_init",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void alarm_init(struct alarm * alarm, enum alarmtimer_type type, enum alarmtimer_restart (*)(struct alarm *, ktime_t) function)
```

```json
{
  "name": "alarm_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580067143,
      "name": "alarm_init",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:351",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_create"
      ],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580066128,
      "name": "alarm_init",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void alarm_init(struct alarm * alarm, enum alarmtimer_type type, enum alarmtimer_restart (*)(struct alarm *, ktime_t) function)
```

```json
{
  "name": "alarm_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580112919,
      "name": "alarm_init",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:351",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_create"
      ],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580111904,
      "name": "alarm_init",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void alarm_init(struct alarm * alarm, enum alarmtimer_type type, enum alarmtimer_restart (*)(struct alarm *, ktime_t) function)
```

```json
{
  "name": "alarm_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580164679,
      "name": "alarm_init",
      "external": true,
      "loc": "kernel/time/alarmtimer.c:351",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarm_timer_create"
      ],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create",
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580163648,
      "name": "alarm_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
