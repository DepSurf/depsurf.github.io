# Function: <code>schedule_on_each_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int schedule_on_each_cpu(work_func_t func)
```

```json
{
  "name": "schedule_on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579481104,
      "name": "schedule_on_each_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:2938",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clocksource/numachip.c:numachip_timer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579481104,
      "name": "schedule_on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int schedule_on_each_cpu(work_func_t func)
```

```json
{
  "name": "schedule_on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579494912,
      "name": "schedule_on_each_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:3038",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_refresh",
        "drivers/clocksource/numachip.c:numachip_timer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579494912,
      "name": "schedule_on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
int schedule_on_each_cpu(work_func_t func)
```

```json
{
  "name": "schedule_on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579514704,
      "name": "schedule_on_each_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:3064",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_refresh",
        "drivers/clocksource/numachip.c:numachip_timer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579514704,
      "name": "schedule_on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int schedule_on_each_cpu(work_func_t func)
```

```json
{
  "name": "schedule_on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579503120,
      "name": "schedule_on_each_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:3063",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "mm/vmstat.c:vmstat_refresh",
        "drivers/clocksource/numachip.c:numachip_timer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579503120,
      "name": "schedule_on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
int schedule_on_each_cpu(work_func_t func)
```

```json
{
  "name": "schedule_on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579529888,
      "name": "schedule_on_each_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:3077",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "mm/vmstat.c:vmstat_refresh",
        "drivers/clocksource/numachip.c:numachip_timer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579529888,
      "name": "schedule_on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int schedule_on_each_cpu(work_func_t func)
```

```json
{
  "name": "schedule_on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579557440,
      "name": "schedule_on_each_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:3151",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "mm/vmstat.c:vmstat_refresh",
        "drivers/clocksource/numachip.c:numachip_timer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579557440,
      "name": "schedule_on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int schedule_on_each_cpu(work_func_t func)
```

```json
{
  "name": "schedule_on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579594576,
      "name": "schedule_on_each_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:3174",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "mm/vmstat.c:vmstat_refresh",
        "drivers/clocksource/numachip.c:numachip_timer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579594576,
      "name": "schedule_on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int schedule_on_each_cpu(work_func_t func)
```

```json
{
  "name": "schedule_on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579621840,
      "name": "schedule_on_each_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:3274",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "mm/vmstat.c:vmstat_refresh",
        "drivers/clocksource/numachip.c:numachip_timer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579621840,
      "name": "schedule_on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
int schedule_on_each_cpu(work_func_t func)
```

```json
{
  "name": "schedule_on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579644000,
      "name": "schedule_on_each_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:3283",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "mm/vmstat.c:vmstat_refresh",
        "drivers/clocksource/numachip.c:numachip_timer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579644000,
      "name": "schedule_on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
int schedule_on_each_cpu(work_func_t func)
```

```json
{
  "name": "schedule_on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579675344,
      "name": "schedule_on_each_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:3280",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock",
        "kernel/rcu/update.c:rcu_tasks_rude_wait_gp",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "mm/vmstat.c:vmstat_refresh",
        "drivers/clocksource/numachip.c:numachip_timer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579675344,
      "name": "schedule_on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
int schedule_on_each_cpu(work_func_t func)
```

```json
{
  "name": "schedule_on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579655168,
      "name": "schedule_on_each_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:3286",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock",
        "kernel/rcu/update.c:rcu_tasks_rude_wait_gp",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "mm/util.c:overcommit_policy_handler",
        "mm/vmstat.c:vmstat_refresh",
        "drivers/clocksource/numachip.c:numachip_timer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579655168,
      "name": "schedule_on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
int schedule_on_each_cpu(work_func_t func)
```

```json
{
  "name": "schedule_on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579661616,
      "name": "schedule_on_each_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:3287",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock",
        "kernel/rcu/update.c:rcu_tasks_rude_wait_gp",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "mm/util.c:overcommit_policy_handler",
        "mm/vmstat.c:vmstat_refresh",
        "drivers/clocksource/numachip.c:numachip_timer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579661616,
      "name": "schedule_on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
int schedule_on_each_cpu(work_func_t func)
```

```json
{
  "name": "schedule_on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579738704,
      "name": "schedule_on_each_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:3326",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock",
        "kernel/rcu/update.c:rcu_tasks_rude_wait_gp",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "mm/util.c:overcommit_policy_handler",
        "mm/vmstat.c:vmstat_refresh",
        "drivers/clocksource/numachip.c:numachip_timer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579738704,
      "name": "schedule_on_each_cpu",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int schedule_on_each_cpu(work_func_t func)
```

```json
{
  "name": "schedule_on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579842912,
      "name": "schedule_on_each_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:3309",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "mm/util.c:overcommit_policy_handler",
        "mm/vmstat.c:vmstat_refresh",
        "drivers/clocksource/numachip.c:numachip_timer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579842912,
      "name": "schedule_on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
int schedule_on_each_cpu(work_func_t func)
```

```json
{
  "name": "schedule_on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579982576,
      "name": "schedule_on_each_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:3316",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock",
        "kernel/rcu/update.c:rcu_tasks_rude_wait_gp",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "mm/util.c:overcommit_policy_handler",
        "mm/vmstat.c:vmstat_refresh",
        "drivers/clocksource/numachip.c:numachip_timer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579982576,
      "name": "schedule_on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
int schedule_on_each_cpu(work_func_t func)
```

```json
{
  "name": "schedule_on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580035152,
      "name": "schedule_on_each_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:3632",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_init",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock",
        "kernel/rcu/update.c:rcu_tasks_rude_wait_gp",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "mm/util.c:overcommit_policy_handler",
        "mm/vmstat.c:vmstat_refresh",
        "drivers/clocksource/numachip.c:numachip_timer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580035152,
      "name": "schedule_on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
int schedule_on_each_cpu(work_func_t func)
```

```json
{
  "name": "schedule_on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580076064,
      "name": "schedule_on_each_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:3653",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock",
        "kernel/rcu/update.c:rcu_tasks_rude_wait_gp",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "mm/util.c:overcommit_policy_handler",
        "mm/vmstat.c:vmstat_refresh",
        "drivers/clocksource/numachip.c:numachip_timer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580076064,
      "name": "schedule_on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
int schedule_on_each_cpu(work_func_t func)
```

```json
{
  "name": "schedule_on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490814960,
      "name": "schedule_on_each_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:3283",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "mm/vmstat.c:vmstat_refresh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490814960,
      "name": "schedule_on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int schedule_on_each_cpu(work_func_t func)
```

```json
{
  "name": "schedule_on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224849748,
      "name": "schedule_on_each_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:3283",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "mm/vmstat.c:vmstat_refresh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224849748,
      "name": "schedule_on_each_cpu",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int schedule_on_each_cpu(work_func_t func)
```

```json
{
  "name": "schedule_on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283647056,
      "name": "schedule_on_each_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:3283",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "mm/vmstat.c:vmstat_refresh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283647056,
      "name": "schedule_on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
int schedule_on_each_cpu(work_func_t func)
```

```json
{
  "name": "schedule_on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271490394,
      "name": "schedule_on_each_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:3283",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "mm/vmstat.c:vmstat_refresh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271490394,
      "name": "schedule_on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
int schedule_on_each_cpu(work_func_t func)
```

```json
{
  "name": "schedule_on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579620304,
      "name": "schedule_on_each_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:3283",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "mm/vmstat.c:vmstat_refresh",
        "drivers/clocksource/numachip.c:numachip_timer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579620304,
      "name": "schedule_on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
int schedule_on_each_cpu(work_func_t func)
```

```json
{
  "name": "schedule_on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579548672,
      "name": "schedule_on_each_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:3283",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "mm/vmstat.c:vmstat_refresh",
        "drivers/clocksource/numachip.c:numachip_timer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579548672,
      "name": "schedule_on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
int schedule_on_each_cpu(work_func_t func)
```

```json
{
  "name": "schedule_on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579617584,
      "name": "schedule_on_each_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:3283",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "mm/vmstat.c:vmstat_refresh",
        "drivers/clocksource/numachip.c:numachip_timer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579617584,
      "name": "schedule_on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
int schedule_on_each_cpu(work_func_t func)
```

```json
{
  "name": "schedule_on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579651248,
      "name": "schedule_on_each_cpu",
      "external": true,
      "loc": "kernel/workqueue.c:3283",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "mm/vmstat.c:vmstat_refresh",
        "drivers/clocksource/numachip.c:numachip_timer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579651248,
      "name": "schedule_on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
