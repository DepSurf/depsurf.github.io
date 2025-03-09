# Function: <code>__pm_wakeup_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __pm_wakeup_event(struct wakeup_source * ws, unsigned int msec)
```

```json
{
  "name": "__pm_wakeup_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584465568,
      "name": "__pm_wakeup_event",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:755",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_lock",
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "drivers/base/power/wakeup.c:pm_wakeup_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584465568,
      "name": "__pm_wakeup_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void __pm_wakeup_event(struct wakeup_source * ws, unsigned int msec)
```

```json
{
  "name": "__pm_wakeup_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584801952,
      "name": "__pm_wakeup_event",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:753",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_lock",
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "drivers/base/power/wakeup.c:pm_wakeup_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584801952,
      "name": "__pm_wakeup_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void __pm_wakeup_event(struct wakeup_source * ws, unsigned int msec)
```

```json
{
  "name": "__pm_wakeup_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584993952,
      "name": "__pm_wakeup_event",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:753",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/wakelock.c:pm_wake_lock",
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "drivers/base/power/wakeup.c:pm_wakeup_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584993952,
      "name": "__pm_wakeup_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579766270,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:206",
      "file": "kernel/power/wakelock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/wakelock.c:pm_wake_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579921113,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:206",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_suspend"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579799758,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:206",
      "file": "kernel/power/wakelock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/wakelock.c:pm_wake_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579966341,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:206",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_suspend"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579833320,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:213",
      "file": "kernel/power/wakelock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/wakelock.c:pm_wake_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580014105,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:213",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_suspend"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579880056,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:213",
      "file": "kernel/power/wakelock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/wakelock.c:pm_wake_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580061129,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:213",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_suspend"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579914641,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "kernel/power/wakelock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/wakelock.c:pm_wake_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580104729,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:191",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_suspend"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579964721,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:186",
      "file": "kernel/power/wakelock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/wakelock.c:pm_wake_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580153705,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:186",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_suspend"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pm_wakeup_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580009985,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:195",
      "file": "kernel/power/wakelock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/wakelock.c:pm_wake_lock"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579987809,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:205",
      "file": "kernel/power/wakelock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/wakelock.c:pm_wake_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588976661,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:205",
      "file": "drivers/mmc/core/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579989640,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:205",
      "file": "kernel/power/wakelock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/wakelock.c:pm_wake_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588864453,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:205",
      "file": "drivers/mmc/core/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580121576,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:205",
      "file": "kernel/power/wakelock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/wakelock.c:pm_wake_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589566549,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:205",
      "file": "drivers/mmc/core/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580262554,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:205",
      "file": "kernel/power/wakelock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/wakelock.c:pm_wake_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591061267,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:205",
      "file": "drivers/mmc/core/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580468074,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:197",
      "file": "kernel/power/wakelock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/wakelock.c:pm_wake_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592774755,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:197",
      "file": "drivers/mmc/core/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580539530,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:197",
      "file": "kernel/power/wakelock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/wakelock.c:pm_wake_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593207875,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:197",
      "file": "drivers/mmc/core/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580601338,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:207",
      "file": "kernel/power/wakelock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/wakelock.c:pm_wake_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593962451,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:207",
      "file": "drivers/mmc/core/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491145660,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:186",
      "file": "kernel/power/wakelock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/wakelock.c:pm_wake_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491377596,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:186",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_suspend"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225174872,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:186",
      "file": "kernel/power/wakelock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/wakelock.c:pm_wake_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 3225373644,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:186",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_suspend"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284040004,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:186",
      "file": "kernel/power/wakelock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/wakelock.c:pm_wake_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284313376,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:186",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_suspend"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__pm_wakeup_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:186",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579933457,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:186",
      "file": "kernel/power/wakelock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/wakelock.c:pm_wake_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580122905,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:186",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_suspend"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579871729,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:186",
      "file": "kernel/power/wakelock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/wakelock.c:pm_wake_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580068201,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:186",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_suspend"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579924993,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:186",
      "file": "kernel/power/wakelock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/wakelock.c:pm_wake_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580113977,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:186",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_suspend"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pm_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579970993,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:186",
      "file": "kernel/power/wakelock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/wakelock.c:pm_wake_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580165762,
      "name": "__pm_wakeup_event",
      "external": false,
      "loc": "include/linux/pm_wakeup.h:186",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "kernel/time/alarmtimer.c:alarmtimer_suspend"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void __pm_wakeup_event(struct wakeup_source * ws, unsigned int msec)
```
</details>
</li>
</ul>
