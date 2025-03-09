# Function: <code>printk_deferred</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int printk_deferred(const char * fmt, void (anon))
```

```json
{
  "name": "printk_deferred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580466568,
      "name": "printk_deferred",
      "external": true,
      "loc": "kernel/printk/printk.c:2751",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:replenish_dl_entity",
        "kernel/time/clockevents.c:clockevents_program_min_delta",
        "kernel/time/clockevents.c:clockevents_program_min_delta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580466568,
      "name": "printk_deferred",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int printk_deferred(const char * fmt, void (anon))
```

```json
{
  "name": "printk_deferred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580543701,
      "name": "printk_deferred",
      "external": true,
      "loc": "kernel/printk/printk.c:2893",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:replenish_dl_entity",
        "kernel/printk/nmi.c:printk_nmi_flush_line",
        "kernel/time/clockevents.c:clockevents_program_min_delta",
        "kernel/time/clockevents.c:clockevents_program_min_delta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580543701,
      "name": "printk_deferred",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int printk_deferred(const char * fmt, void (anon))
```

```json
{
  "name": "printk_deferred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580607800,
      "name": "printk_deferred",
      "external": true,
      "loc": "kernel/printk/printk.c:2725",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack_64.c:get_stack_info",
        "arch/x86/kernel/unwind_frame.c:unwind_next_frame",
        "arch/x86/kernel/unwind_frame.c:unwind_next_frame",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:replenish_dl_entity",
        "kernel/printk/nmi.c:printk_nmi_flush_line",
        "kernel/time/clockevents.c:clockevents_program_min_delta",
        "kernel/time/clockevents.c:clockevents_program_min_delta",
        "kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580607800,
      "name": "printk_deferred",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int printk_deferred(const char * fmt, void (anon))
```

```json
{
  "name": "printk_deferred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579781909,
      "name": "printk_deferred",
      "external": true,
      "loc": "kernel/printk/printk.c:2737",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack_64.c:get_stack_info",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:replenish_dl_entity",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/time/clockevents.c:clockevents_program_min_delta",
        "kernel/time/clockevents.c:clockevents_program_min_delta",
        "kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579781909,
      "name": "printk_deferred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int printk_deferred(const char * fmt, void (anon))
```

```json
{
  "name": "printk_deferred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579815348,
      "name": "printk_deferred",
      "external": true,
      "loc": "kernel/printk/printk.c:2731",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack_64.c:get_stack_info",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:replenish_dl_entity",
        "kernel/power/main.c:__pm_pr_dbg",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/time/clockevents.c:clockevents_program_min_delta",
        "kernel/time/clockevents.c:clockevents_program_min_delta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579815348,
      "name": "printk_deferred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int printk_deferred(const char * fmt, void (anon))
```

```json
{
  "name": "printk_deferred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579848870,
      "name": "printk_deferred",
      "external": true,
      "loc": "kernel/printk/printk.c:2908",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack_64.c:get_stack_info",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:replenish_dl_entity",
        "kernel/power/main.c:__pm_pr_dbg",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579848870,
      "name": "printk_deferred",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int printk_deferred(const char * fmt, void (anon))
```

```json
{
  "name": "printk_deferred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579895905,
      "name": "printk_deferred",
      "external": true,
      "loc": "kernel/printk/printk.c:2920",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack_64.c:get_stack_info",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:replenish_dl_entity",
        "kernel/sched/psi.c:psi_task_change",
        "kernel/sched/psi.c:psi_task_change",
        "kernel/power/main.c:__pm_pr_dbg",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579895905,
      "name": "printk_deferred",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int printk_deferred(const char * fmt, void (anon))
```

```json
{
  "name": "printk_deferred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579930690,
      "name": "printk_deferred",
      "external": true,
      "loc": "kernel/printk/printk.c:2985",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack_64.c:get_stack_info",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:replenish_dl_entity",
        "kernel/sched/psi.c:psi_task_change",
        "kernel/sched/psi.c:psi_task_change",
        "kernel/power/main.c:__pm_pr_dbg",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/time/clockevents.c:clockevents_program_min_delta",
        "kernel/time/clockevents.c:clockevents_program_min_delta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579930690,
      "name": "printk_deferred",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int printk_deferred(const char * fmt, void (anon))
```

```json
{
  "name": "printk_deferred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579980836,
      "name": "printk_deferred",
      "external": true,
      "loc": "kernel/printk/printk.c:2995",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack_64.c:get_stack_info",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:replenish_dl_entity",
        "kernel/sched/psi.c:psi_task_change",
        "kernel/sched/psi.c:psi_task_change",
        "kernel/power/main.c:__pm_pr_dbg",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/time/clockevents.c:clockevents_program_min_delta",
        "kernel/time/clockevents.c:clockevents_program_min_delta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579980836,
      "name": "printk_deferred",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int printk_deferred(const char * fmt, void (anon))
```

```json
{
  "name": "printk_deferred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580028384,
      "name": "printk_deferred",
      "external": true,
      "loc": "kernel/printk/printk.c:3063",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack_64.c:get_stack_info",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:replenish_dl_entity",
        "kernel/sched/psi.c:psi_flags_change",
        "kernel/sched/psi.c:psi_group_change",
        "kernel/power/main.c:__pm_pr_dbg",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:printk_safe_flush_line",
        "kernel/time/clockevents.c:clockevents_program_min_delta",
        "kernel/time/clockevents.c:clockevents_program_min_delta",
        "drivers/char/random.c:get_random_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580028384,
      "name": "printk_deferred",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int printk_deferred(const char * fmt, void (anon))
```

```json
{
  "name": "printk_deferred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591302124,
      "name": "printk_deferred",
      "external": true,
      "loc": "kernel/printk/printk.c:3142",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack_64.c:get_stack_info",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:replenish_dl_entity",
        "kernel/sched/psi.c:psi_flags_change",
        "kernel/sched/psi.c:psi_group_change",
        "kernel/power/main.c:__pm_pr_dbg",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:printk_safe_flush_line",
        "kernel/time/clockevents.c:clockevents_program_min_delta",
        "kernel/time/clockevents.c:clockevents_program_min_delta",
        "drivers/char/random.c:get_random_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591302124,
      "name": "printk_deferred",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int printk_deferred(const char * fmt, void (anon))
```

```json
{
  "name": "printk_deferred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591244912,
      "name": "printk_deferred",
      "external": true,
      "loc": "kernel/printk/printk.c:3206",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack_64.c:get_stack_info",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:replenish_dl_entity",
        "kernel/sched/psi.c:psi_flags_change",
        "kernel/sched/psi.c:psi_group_change",
        "kernel/power/main.c:__pm_pr_dbg",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:printk_safe_flush_line",
        "kernel/time/clockevents.c:clockevents_program_min_delta",
        "kernel/time/clockevents.c:clockevents_program_min_delta",
        "drivers/char/random.c:get_random_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591244912,
      "name": "printk_deferred",
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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int printk_deferred(const char * fmt, void (anon))
```

```json
{
  "name": "printk_deferred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491165864,
      "name": "printk_deferred",
      "external": true,
      "loc": "kernel/printk/printk.c:2995",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:replenish_dl_entity",
        "kernel/sched/psi.c:psi_task_change",
        "kernel/sched/psi.c:psi_task_change",
        "kernel/power/main.c:__pm_pr_dbg",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491165864,
      "name": "printk_deferred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int printk_deferred(const char * fmt, void (anon))
```

```json
{
  "name": "printk_deferred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225192236,
      "name": "printk_deferred",
      "external": true,
      "loc": "kernel/printk/printk.c:2995",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:replenish_dl_entity",
        "kernel/sched/psi.c:psi_task_change",
        "kernel/sched/psi.c:psi_task_change",
        "kernel/power/main.c:__pm_pr_dbg",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225192236,
      "name": "printk_deferred",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int printk_deferred(const char * fmt, void (anon))
```

```json
{
  "name": "printk_deferred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284064456,
      "name": "printk_deferred",
      "external": true,
      "loc": "kernel/printk/printk.c:2995",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:replenish_dl_entity",
        "kernel/sched/psi.c:psi_task_change",
        "kernel/sched/psi.c:psi_task_change",
        "kernel/power/main.c:__pm_pr_dbg",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284064456,
      "name": "printk_deferred",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int printk_deferred(const char * fmt, void (anon))
```

```json
{
  "name": "printk_deferred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271719208,
      "name": "printk_deferred",
      "external": true,
      "loc": "kernel/printk/printk.c:2995",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:replenish_dl_entity",
        "kernel/sched/psi.c:psi_task_change",
        "kernel/sched/psi.c:psi_task_change",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/time/timekeeping.c:timekeeping_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271719208,
      "name": "printk_deferred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int printk_deferred(const char * fmt, void (anon))
```

```json
{
  "name": "printk_deferred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579949572,
      "name": "printk_deferred",
      "external": true,
      "loc": "kernel/printk/printk.c:2995",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack_64.c:get_stack_info",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:replenish_dl_entity",
        "kernel/sched/psi.c:psi_task_change",
        "kernel/sched/psi.c:psi_task_change",
        "kernel/power/main.c:__pm_pr_dbg",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/time/clockevents.c:clockevents_program_min_delta",
        "kernel/time/clockevents.c:clockevents_program_min_delta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579949572,
      "name": "printk_deferred",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int printk_deferred(const char * fmt, void (anon))
```

```json
{
  "name": "printk_deferred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579887460,
      "name": "printk_deferred",
      "external": true,
      "loc": "kernel/printk/printk.c:2995",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack_64.c:get_stack_info",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:replenish_dl_entity",
        "kernel/sched/psi.c:psi_task_change",
        "kernel/sched/psi.c:psi_task_change",
        "kernel/power/main.c:__pm_pr_dbg",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/time/clockevents.c:clockevents_program_min_delta",
        "kernel/time/clockevents.c:clockevents_program_min_delta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579887460,
      "name": "printk_deferred",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int printk_deferred(const char * fmt, void (anon))
```

```json
{
  "name": "printk_deferred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579941108,
      "name": "printk_deferred",
      "external": true,
      "loc": "kernel/printk/printk.c:2995",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack_64.c:get_stack_info",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:replenish_dl_entity",
        "kernel/sched/psi.c:psi_task_change",
        "kernel/sched/psi.c:psi_task_change",
        "kernel/power/main.c:__pm_pr_dbg",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/time/clockevents.c:clockevents_program_min_delta",
        "kernel/time/clockevents.c:clockevents_program_min_delta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579941108,
      "name": "printk_deferred",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int printk_deferred(const char * fmt, void (anon))
```

```json
{
  "name": "printk_deferred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579987466,
      "name": "printk_deferred",
      "external": true,
      "loc": "kernel/printk/printk.c:2995",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack_64.c:get_stack_info",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:replenish_dl_entity",
        "kernel/sched/psi.c:psi_task_change",
        "kernel/sched/psi.c:psi_task_change",
        "kernel/power/main.c:__pm_pr_dbg",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/time/clockevents.c:clockevents_program_min_delta",
        "kernel/time/clockevents.c:clockevents_program_min_delta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579987466,
      "name": "printk_deferred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
int printk_deferred(const char * fmt, void (anon))
```
</details>
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
