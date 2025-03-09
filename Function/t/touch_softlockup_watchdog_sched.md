# Function: <code>touch_softlockup_watchdog_sched</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void touch_softlockup_watchdog_sched()
```

```json
{
  "name": "touch_softlockup_watchdog_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580167345,
      "name": "touch_softlockup_watchdog_sched",
      "external": true,
      "loc": "kernel/watchdog.c:237",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:touch_nmi_watchdog"
      ],
      "caller_func": [
        "kernel/sched/clock.c:sched_clock_idle_wakeup_event",
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580169664,
      "name": "touch_softlockup_watchdog_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void touch_softlockup_watchdog_sched()
```

```json
{
  "name": "touch_softlockup_watchdog_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580207766,
      "name": "touch_softlockup_watchdog_sched",
      "external": true,
      "loc": "kernel/watchdog.c:177",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:touch_softlockup_watchdog"
      ],
      "caller_func": [
        "kernel/sched/clock.c:sched_clock_idle_wakeup_event",
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580209104,
      "name": "touch_softlockup_watchdog_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void touch_softlockup_watchdog_sched()
```

```json
{
  "name": "touch_softlockup_watchdog_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580215830,
      "name": "touch_softlockup_watchdog_sched",
      "external": true,
      "loc": "kernel/watchdog.c:260",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:touch_softlockup_watchdog"
      ],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_sched_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580217664,
      "name": "touch_softlockup_watchdog_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void touch_softlockup_watchdog_sched()
```

```json
{
  "name": "touch_softlockup_watchdog_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580267174,
      "name": "touch_softlockup_watchdog_sched",
      "external": true,
      "loc": "kernel/watchdog.c:269",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:touch_softlockup_watchdog"
      ],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_sched_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580268896,
      "name": "touch_softlockup_watchdog_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void touch_softlockup_watchdog_sched()
```

```json
{
  "name": "touch_softlockup_watchdog_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580327600,
      "name": "touch_softlockup_watchdog_sched",
      "external": true,
      "loc": "kernel/watchdog.c:269",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:touch_softlockup_watchdog"
      ],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_sched_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580329136,
      "name": "touch_softlockup_watchdog_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void touch_softlockup_watchdog_sched()
```

```json
{
  "name": "touch_softlockup_watchdog_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580380592,
      "name": "touch_softlockup_watchdog_sched",
      "external": true,
      "loc": "kernel/watchdog.c:264",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:touch_softlockup_watchdog"
      ],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_sched_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580382400,
      "name": "touch_softlockup_watchdog_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void touch_softlockup_watchdog_sched()
```

```json
{
  "name": "touch_softlockup_watchdog_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580433424,
      "name": "touch_softlockup_watchdog_sched",
      "external": true,
      "loc": "kernel/watchdog.c:271",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:touch_softlockup_watchdog"
      ],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_sched_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580435104,
      "name": "touch_softlockup_watchdog_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void touch_softlockup_watchdog_sched()
```

```json
{
  "name": "touch_softlockup_watchdog_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580482176,
      "name": "touch_softlockup_watchdog_sched",
      "external": true,
      "loc": "kernel/watchdog.c:273",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:touch_softlockup_watchdog"
      ],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_sched_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580483872,
      "name": "touch_softlockup_watchdog_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void touch_softlockup_watchdog_sched()
```

```json
{
  "name": "touch_softlockup_watchdog_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580567104,
      "name": "touch_softlockup_watchdog_sched",
      "external": true,
      "loc": "kernel/watchdog.c:252",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:touch_softlockup_watchdog"
      ],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_update_jiffies",
        "kernel/time/tick-sched.c:tick_sched_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580568736,
      "name": "touch_softlockup_watchdog_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void touch_softlockup_watchdog_sched()
```

```json
{
  "name": "touch_softlockup_watchdog_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580554976,
      "name": "touch_softlockup_watchdog_sched",
      "external": true,
      "loc": "kernel/watchdog.c:252",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:touch_softlockup_watchdog"
      ],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_update_jiffies",
        "kernel/time/tick-sched.c:tick_sched_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580556608,
      "name": "touch_softlockup_watchdog_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void touch_softlockup_watchdog_sched()
```

```json
{
  "name": "touch_softlockup_watchdog_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580558144,
      "name": "touch_softlockup_watchdog_sched",
      "external": true,
      "loc": "kernel/watchdog.c:264",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:touch_softlockup_watchdog"
      ],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_sched_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580559920,
      "name": "touch_softlockup_watchdog_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void touch_softlockup_watchdog_sched()
```

```json
{
  "name": "touch_softlockup_watchdog_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580728096,
      "name": "touch_softlockup_watchdog_sched",
      "external": true,
      "loc": "kernel/watchdog.c:264",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:touch_softlockup_watchdog"
      ],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_sched_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580729856,
      "name": "touch_softlockup_watchdog_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void touch_softlockup_watchdog_sched()
```

```json
{
  "name": "touch_softlockup_watchdog_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580940448,
      "name": "touch_softlockup_watchdog_sched",
      "external": true,
      "loc": "kernel/watchdog.c:264",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:touch_softlockup_watchdog"
      ],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_update_jiffies",
        "kernel/time/tick-sched.c:tick_sched_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580942832,
      "name": "touch_softlockup_watchdog_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void touch_softlockup_watchdog_sched()
```

```json
{
  "name": "touch_softlockup_watchdog_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581233872,
      "name": "touch_softlockup_watchdog_sched",
      "external": true,
      "loc": "kernel/watchdog.c:264",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:touch_softlockup_watchdog"
      ],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_update_jiffies",
        "kernel/time/tick-sched.c:tick_sched_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581236560,
      "name": "touch_softlockup_watchdog_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void touch_softlockup_watchdog_sched()
```

```json
{
  "name": "touch_softlockup_watchdog_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581328256,
      "name": "touch_softlockup_watchdog_sched",
      "external": true,
      "loc": "kernel/watchdog.c:364",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:touch_softlockup_watchdog"
      ],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_update_jiffies",
        "kernel/time/tick-sched.c:tick_sched_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581331824,
      "name": "touch_softlockup_watchdog_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void touch_softlockup_watchdog_sched()
```

```json
{
  "name": "touch_softlockup_watchdog_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581434560,
      "name": "touch_softlockup_watchdog_sched",
      "external": true,
      "loc": "kernel/watchdog.c:391",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:touch_softlockup_watchdog"
      ],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_restart_sched_tick",
        "kernel/time/tick-sched.c:tick_nohz_update_jiffies",
        "kernel/time/tick-sched.c:tick_sched_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581438336,
      "name": "touch_softlockup_watchdog_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void touch_softlockup_watchdog_sched()
```

```json
{
  "name": "touch_softlockup_watchdog_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491758000,
      "name": "touch_softlockup_watchdog_sched",
      "external": true,
      "loc": "kernel/watchdog.c:273",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:touch_softlockup_watchdog"
      ],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491760120,
      "name": "touch_softlockup_watchdog_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void touch_softlockup_watchdog_sched()
```

```json
{
  "name": "touch_softlockup_watchdog_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225708420,
      "name": "touch_softlockup_watchdog_sched",
      "external": true,
      "loc": "kernel/watchdog.c:273",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_sched_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225708420,
      "name": "touch_softlockup_watchdog_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void touch_softlockup_watchdog_sched()
```

```json
{
  "name": "touch_softlockup_watchdog_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284799320,
      "name": "touch_softlockup_watchdog_sched",
      "external": true,
      "loc": "kernel/watchdog.c:273",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:touch_softlockup_watchdog"
      ],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284802208,
      "name": "touch_softlockup_watchdog_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void touch_softlockup_watchdog_sched()
```

```json
{
  "name": "touch_softlockup_watchdog_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272081184,
      "name": "touch_softlockup_watchdog_sched",
      "external": true,
      "loc": "kernel/watchdog.c:273",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272081184,
      "name": "touch_softlockup_watchdog_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void touch_softlockup_watchdog_sched()
```

```json
{
  "name": "touch_softlockup_watchdog_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580450976,
      "name": "touch_softlockup_watchdog_sched",
      "external": true,
      "loc": "kernel/watchdog.c:273",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:touch_softlockup_watchdog"
      ],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_sched_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580452672,
      "name": "touch_softlockup_watchdog_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void touch_softlockup_watchdog_sched()
```

```json
{
  "name": "touch_softlockup_watchdog_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580398048,
      "name": "touch_softlockup_watchdog_sched",
      "external": true,
      "loc": "kernel/watchdog.c:273",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:touch_softlockup_watchdog"
      ],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_nohz_restart_sched_tick",
        "kernel/time/tick-sched.c:tick_sched_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580399744,
      "name": "touch_softlockup_watchdog_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void touch_softlockup_watchdog_sched()
```

```json
{
  "name": "touch_softlockup_watchdog_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580442224,
      "name": "touch_softlockup_watchdog_sched",
      "external": true,
      "loc": "kernel/watchdog.c:273",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:touch_softlockup_watchdog"
      ],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_sched_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580443920,
      "name": "touch_softlockup_watchdog_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void touch_softlockup_watchdog_sched()
```

```json
{
  "name": "touch_softlockup_watchdog_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580497856,
      "name": "touch_softlockup_watchdog_sched",
      "external": true,
      "loc": "kernel/watchdog.c:273",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:touch_softlockup_watchdog"
      ],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_sched_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580499552,
      "name": "touch_softlockup_watchdog_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void touch_softlockup_watchdog_sched()
```
</details>
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
