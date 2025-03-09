# Function: <code>add_timer_on</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void add_timer_on(struct timer_list * timer, int cpu)
```

```json
{
  "name": "add_timer_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579814208,
      "name": "add_timer_on",
      "external": true,
      "loc": "kernel/time/timer.c:978",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:__restart_timer",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_start_timer",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:clocksource_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579814208,
      "name": "add_timer_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
void add_timer_on(struct timer_list * timer, int cpu)
```

```json
{
  "name": "add_timer_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579844032,
      "name": "add_timer_on",
      "external": true,
      "loc": "kernel/time/timer.c:1118",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_start_timer",
        "arch/x86/kernel/cpu/mcheck/mce.c:__restart_timer",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579844032,
      "name": "add_timer_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 441
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
void add_timer_on(struct timer_list * timer, int cpu)
```

```json
{
  "name": "add_timer_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579873136,
      "name": "add_timer_on",
      "external": true,
      "loc": "kernel/time/timer.c:1128",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579873136,
      "name": "add_timer_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 426
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
void add_timer_on(struct timer_list * timer, int cpu)
```

```json
{
  "name": "add_timer_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579882224,
      "name": "add_timer_on",
      "external": true,
      "loc": "kernel/time/timer.c:1103",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579882224,
      "name": "add_timer_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
void add_timer_on(struct timer_list * timer, int cpu)
```

```json
{
  "name": "add_timer_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579927568,
      "name": "add_timer_on",
      "external": true,
      "loc": "kernel/time/timer.c:1141",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579927568,
      "name": "add_timer_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
void add_timer_on(struct timer_list * timer, int cpu)
```

```json
{
  "name": "add_timer_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579973952,
      "name": "add_timer_on",
      "external": true,
      "loc": "kernel/time/timer.c:1149",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579973952,
      "name": "add_timer_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
void add_timer_on(struct timer_list * timer, int cpu)
```

```json
{
  "name": "add_timer_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580019024,
      "name": "add_timer_on",
      "external": true,
      "loc": "kernel/time/timer.c:1148",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580019024,
      "name": "add_timer_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
void add_timer_on(struct timer_list * timer, int cpu)
```

```json
{
  "name": "add_timer_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580063984,
      "name": "add_timer_on",
      "external": true,
      "loc": "kernel/time/timer.c:1143",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580063984,
      "name": "add_timer_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void add_timer_on(struct timer_list * timer, int cpu)
```

```json
{
  "name": "add_timer_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580113040,
      "name": "add_timer_on",
      "external": true,
      "loc": "kernel/time/timer.c:1147",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_enable",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580113040,
      "name": "add_timer_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void add_timer_on(struct timer_list * timer, int cpu)
```

```json
{
  "name": "add_timer_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580178288,
      "name": "add_timer_on",
      "external": true,
      "loc": "kernel/time/timer.c:1159",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_enable",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580178288,
      "name": "add_timer_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
void add_timer_on(struct timer_list * timer, int cpu)
```

```json
{
  "name": "add_timer_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580162112,
      "name": "add_timer_on",
      "external": true,
      "loc": "kernel/time/timer.c:1153",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580162112,
      "name": "add_timer_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
void add_timer_on(struct timer_list * timer, int cpu)
```

```json
{
  "name": "add_timer_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580167312,
      "name": "add_timer_on",
      "external": true,
      "loc": "kernel/time/timer.c:1155",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580167312,
      "name": "add_timer_on",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void add_timer_on(struct timer_list * timer, int cpu)
```

```json
{
  "name": "add_timer_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580312016,
      "name": "add_timer_on",
      "external": true,
      "loc": "kernel/time/timer.c:1155",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580312016,
      "name": "add_timer_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
void add_timer_on(struct timer_list * timer, int cpu)
```

```json
{
  "name": "add_timer_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580521104,
      "name": "add_timer_on",
      "external": true,
      "loc": "kernel/time/timer.c:1208",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580521104,
      "name": "add_timer_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
void add_timer_on(struct timer_list * timer, int cpu)
```

```json
{
  "name": "add_timer_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580776800,
      "name": "add_timer_on",
      "external": true,
      "loc": "kernel/time/timer.c:1257",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog",
        "drivers/char/random.c:try_to_generate_entropy",
        "drivers/char/random.c:add_interrupt_randomness"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580776800,
      "name": "add_timer_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
void add_timer_on(struct timer_list * timer, int cpu)
```

```json
{
  "name": "add_timer_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580859568,
      "name": "add_timer_on",
      "external": true,
      "loc": "kernel/time/timer.c:1257",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog",
        "drivers/char/random.c:try_to_generate_entropy",
        "drivers/char/random.c:add_interrupt_randomness"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580859568,
      "name": "add_timer_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 405
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
void add_timer_on(struct timer_list * timer, int cpu)
```

```json
{
  "name": "add_timer_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580949712,
      "name": "add_timer_on",
      "external": true,
      "loc": "kernel/time/timer.c:1257",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn",
        "arch/x86/kernel/apic/vector.c:__vector_schedule_cleanup",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog",
        "drivers/char/random.c:try_to_generate_entropy",
        "drivers/char/random.c:add_interrupt_randomness"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580949712,
      "name": "add_timer_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
void add_timer_on(struct timer_list * timer, int cpu)
```

```json
{
  "name": "add_timer_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491328504,
      "name": "add_timer_on",
      "external": true,
      "loc": "kernel/time/timer.c:1147",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__queue_delayed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491328504,
      "name": "add_timer_on",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void add_timer_on(struct timer_list * timer, int cpu)
```

```json
{
  "name": "add_timer_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225321072,
      "name": "add_timer_on",
      "external": true,
      "loc": "kernel/time/timer.c:1147",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__queue_delayed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225321072,
      "name": "add_timer_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
void add_timer_on(struct timer_list * timer, int cpu)
```

```json
{
  "name": "add_timer_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284256624,
      "name": "add_timer_on",
      "external": true,
      "loc": "kernel/time/timer.c:1147",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__queue_delayed_work",
        "drivers/cpufreq/powernv-cpufreq.c:gpstate_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284256624,
      "name": "add_timer_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
void add_timer_on(struct timer_list * timer, int cpu)
```

```json
{
  "name": "add_timer_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271830304,
      "name": "add_timer_on",
      "external": true,
      "loc": "kernel/time/timer.c:1147",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__queue_delayed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271830304,
      "name": "add_timer_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
void add_timer_on(struct timer_list * timer, int cpu)
```

```json
{
  "name": "add_timer_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580082240,
      "name": "add_timer_on",
      "external": true,
      "loc": "kernel/time/timer.c:1147",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580082240,
      "name": "add_timer_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void add_timer_on(struct timer_list * timer, int cpu)
```

```json
{
  "name": "add_timer_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580027584,
      "name": "add_timer_on",
      "external": true,
      "loc": "kernel/time/timer.c:1147",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580027584,
      "name": "add_timer_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void add_timer_on(struct timer_list * timer, int cpu)
```

```json
{
  "name": "add_timer_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580073312,
      "name": "add_timer_on",
      "external": true,
      "loc": "kernel/time/timer.c:1147",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580073312,
      "name": "add_timer_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void add_timer_on(struct timer_list * timer, int cpu)
```

```json
{
  "name": "add_timer_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580124752,
      "name": "add_timer_on",
      "external": true,
      "loc": "kernel/time/timer.c:1147",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_enable",
        "kernel/workqueue.c:__queue_delayed_work",
        "kernel/time/clocksource.c:clocksource_select_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580124752,
      "name": "add_timer_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
