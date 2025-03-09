# Function: <code>sched_clock_idle_wakeup_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void sched_clock_idle_wakeup_event(u64 delta_ns)
```

```json
{
  "name": "sched_clock_idle_wakeup_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579571472,
      "name": "sched_clock_idle_wakeup_event",
      "external": true,
      "loc": "kernel/sched/clock.c:351",
      "file": "kernel/sched/clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:set_cyc2ns_scale",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_irq_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579571472,
      "name": "sched_clock_idle_wakeup_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void sched_clock_idle_wakeup_event(u64 delta_ns)
```

```json
{
  "name": "sched_clock_idle_wakeup_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579582352,
      "name": "sched_clock_idle_wakeup_event",
      "external": true,
      "loc": "kernel/sched/clock.c:357",
      "file": "kernel/sched/clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:set_cyc2ns_scale",
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579582352,
      "name": "sched_clock_idle_wakeup_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void sched_clock_idle_wakeup_event(u64 delta_ns)
```

```json
{
  "name": "sched_clock_idle_wakeup_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579608528,
      "name": "sched_clock_idle_wakeup_event",
      "external": true,
      "loc": "kernel/sched/clock.c:357",
      "file": "kernel/sched/clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:set_cyc2ns_scale",
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579608528,
      "name": "sched_clock_idle_wakeup_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void sched_clock_idle_wakeup_event()
```

```json
{
  "name": "sched_clock_idle_wakeup_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579586032,
      "name": "sched_clock_idle_wakeup_event",
      "external": true,
      "loc": "kernel/sched/clock.c:431",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:set_cyc2ns_scale",
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579586032,
      "name": "sched_clock_idle_wakeup_event",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sched_clock_idle_wakeup_event()
```

```json
{
  "name": "sched_clock_idle_wakeup_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579615456,
      "name": "sched_clock_idle_wakeup_event",
      "external": true,
      "loc": "kernel/sched/clock.c:431",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:set_cyc2ns_scale",
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579615456,
      "name": "sched_clock_idle_wakeup_event",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sched_clock_idle_wakeup_event()
```

```json
{
  "name": "sched_clock_idle_wakeup_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579645808,
      "name": "sched_clock_idle_wakeup_event",
      "external": true,
      "loc": "kernel/sched/clock.c:419",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:set_cyc2ns_scale",
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579645808,
      "name": "sched_clock_idle_wakeup_event",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sched_clock_idle_wakeup_event()
```

```json
{
  "name": "sched_clock_idle_wakeup_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579683408,
      "name": "sched_clock_idle_wakeup_event",
      "external": true,
      "loc": "kernel/sched/clock.c:434",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:set_cyc2ns_scale",
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579683408,
      "name": "sched_clock_idle_wakeup_event",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sched_clock_idle_wakeup_event()
```

```json
{
  "name": "sched_clock_idle_wakeup_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579717184,
      "name": "sched_clock_idle_wakeup_event",
      "external": true,
      "loc": "kernel/sched/clock.c:435",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:set_cyc2ns_scale",
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579717184,
      "name": "sched_clock_idle_wakeup_event",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sched_clock_idle_wakeup_event()
```

```json
{
  "name": "sched_clock_idle_wakeup_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579759616,
      "name": "sched_clock_idle_wakeup_event",
      "external": true,
      "loc": "kernel/sched/clock.c:435",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:set_cyc2ns_scale",
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579759616,
      "name": "sched_clock_idle_wakeup_event",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void sched_clock_idle_wakeup_event()
```

```json
{
  "name": "sched_clock_idle_wakeup_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579793152,
      "name": "sched_clock_idle_wakeup_event",
      "external": true,
      "loc": "kernel/sched/clock.c:435",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:time_cpufreq_notifier",
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579793152,
      "name": "sched_clock_idle_wakeup_event.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071579793200,
      "name": "sched_clock_idle_wakeup_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void sched_clock_idle_wakeup_event()
```

```json
{
  "name": "sched_clock_idle_wakeup_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579784000,
      "name": "sched_clock_idle_wakeup_event",
      "external": true,
      "loc": "kernel/sched/clock.c:435",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:time_cpufreq_notifier",
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579784000,
      "name": "sched_clock_idle_wakeup_event.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071579784048,
      "name": "sched_clock_idle_wakeup_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void sched_clock_idle_wakeup_event()
```

```json
{
  "name": "sched_clock_idle_wakeup_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579792112,
      "name": "sched_clock_idle_wakeup_event",
      "external": true,
      "loc": "kernel/sched/clock.c:435",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:time_cpufreq_notifier",
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579792112,
      "name": "sched_clock_idle_wakeup_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void sched_clock_idle_wakeup_event()
```

```json
{
  "name": "sched_clock_idle_wakeup_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579887888,
      "name": "sched_clock_idle_wakeup_event",
      "external": true,
      "loc": "kernel/sched/clock.c:435",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:time_cpufreq_notifier",
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579887888,
      "name": "sched_clock_idle_wakeup_event",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void sched_clock_idle_wakeup_event()
```

```json
{
  "name": "sched_clock_idle_wakeup_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580177312,
      "name": "sched_clock_idle_wakeup_event",
      "external": true,
      "loc": "kernel/sched/clock.c:433",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:set_cyc2ns_scale",
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580177312,
      "name": "sched_clock_idle_wakeup_event.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071580177360,
      "name": "sched_clock_idle_wakeup_event",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void sched_clock_idle_wakeup_event()
```

```json
{
  "name": "sched_clock_idle_wakeup_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580361872,
      "name": "sched_clock_idle_wakeup_event",
      "external": true,
      "loc": "kernel/sched/clock.c:433",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:set_cyc2ns_scale",
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580361872,
      "name": "sched_clock_idle_wakeup_event.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071580361952,
      "name": "sched_clock_idle_wakeup_event",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void sched_clock_idle_wakeup_event()
```

```json
{
  "name": "sched_clock_idle_wakeup_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580431600,
      "name": "sched_clock_idle_wakeup_event",
      "external": true,
      "loc": "kernel/sched/clock.c:458",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:set_cyc2ns_scale",
        "kernel/time/tick-sched.c:tick_nohz_stop_idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580431600,
      "name": "sched_clock_idle_wakeup_event.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071580431680,
      "name": "sched_clock_idle_wakeup_event",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void sched_clock_idle_wakeup_event()
```

```json
{
  "name": "sched_clock_idle_wakeup_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580490800,
      "name": "sched_clock_idle_wakeup_event",
      "external": true,
      "loc": "kernel/sched/clock.c:458",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:set_cyc2ns_scale",
        "kernel/time/tick-sched.c:tick_nohz_stop_idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580490800,
      "name": "sched_clock_idle_wakeup_event.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071580490880,
      "name": "sched_clock_idle_wakeup_event",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "sched_clock_idle_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_clock_idle_wakeup_event",
      "external": false,
      "loc": "include/linux/sched/clock.h:39",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "sched_clock_idle_wakeup_event",
      "external": false,
      "loc": "include/linux/sched/clock.h:39",
      "file": "drivers/cpuidle/cpuidle.c",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "sched_clock_idle_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_clock_idle_wakeup_event",
      "external": false,
      "loc": "include/linux/sched/clock.h:39",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "sched_clock_idle_wakeup_event",
      "external": false,
      "loc": "include/linux/sched/clock.h:39",
      "file": "drivers/cpuidle/cpuidle.c",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "sched_clock_idle_wakeup_event",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_clock_idle_wakeup_event",
      "external": false,
      "loc": "include/linux/sched/clock.h:39",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "sched_clock_idle_wakeup_event",
      "external": false,
      "loc": "include/linux/sched/clock.h:39",
      "file": "drivers/cpuidle/cpuidle.c",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "sched_clock_idle_wakeup_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_clock_idle_wakeup_event",
      "external": false,
      "loc": "include/linux/sched/clock.h:39",
      "file": "kernel/time/tick-sched.c",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void sched_clock_idle_wakeup_event()
```

```json
{
  "name": "sched_clock_idle_wakeup_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579735536,
      "name": "sched_clock_idle_wakeup_event",
      "external": true,
      "loc": "kernel/sched/clock.c:435",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:set_cyc2ns_scale",
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579735536,
      "name": "sched_clock_idle_wakeup_event",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void sched_clock_idle_wakeup_event()
```

```json
{
  "name": "sched_clock_idle_wakeup_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579664352,
      "name": "sched_clock_idle_wakeup_event",
      "external": true,
      "loc": "kernel/sched/clock.c:435",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:set_cyc2ns_scale",
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579664352,
      "name": "sched_clock_idle_wakeup_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void sched_clock_idle_wakeup_event()
```

```json
{
  "name": "sched_clock_idle_wakeup_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579719984,
      "name": "sched_clock_idle_wakeup_event",
      "external": true,
      "loc": "kernel/sched/clock.c:435",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:set_cyc2ns_scale",
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579719984,
      "name": "sched_clock_idle_wakeup_event",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void sched_clock_idle_wakeup_event()
```

```json
{
  "name": "sched_clock_idle_wakeup_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579767328,
      "name": "sched_clock_idle_wakeup_event",
      "external": true,
      "loc": "kernel/sched/clock.c:435",
      "file": "kernel/sched/clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:set_cyc2ns_scale",
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579767328,
      "name": "sched_clock_idle_wakeup_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u64 delta_ns</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void sched_clock_idle_wakeup_event()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void sched_clock_idle_wakeup_event()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void sched_clock_idle_wakeup_event()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void sched_clock_idle_wakeup_event()
```
</details>
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
