# Function: <code>rcu_irq_exit_irqson</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void rcu_irq_exit_irqson()
```

```json
{
  "name": "rcu_irq_exit_irqson",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579819488,
      "name": "rcu_irq_exit_irqson",
      "external": true,
      "loc": "kernel/rcu/tree.c:810",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/kernel/process.c:default_idle",
        "kernel/sched/idle.c:cpu_startup_entry",
        "kernel/sched/idle.c:cpu_startup_entry",
        "kernel/time/tick-broadcast-hrtimer.c:bc_set_next",
        "kernel/time/tick-broadcast-hrtimer.c:bc_set_next",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_freeze",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_freeze",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579819488,
      "name": "rcu_irq_exit_irqson",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void rcu_irq_exit_irqson()
```

```json
{
  "name": "rcu_irq_exit_irqson",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579848384,
      "name": "rcu_irq_exit_irqson",
      "external": true,
      "loc": "kernel/rcu/tree.c:811",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/kernel/process.c:default_idle",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/printk/printk.c:console_unlock",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_freeze",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_freeze"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579848384,
      "name": "rcu_irq_exit_irqson",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void rcu_irq_exit_irqson()
```

```json
{
  "name": "rcu_irq_exit_irqson",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579851952,
      "name": "rcu_irq_exit_irqson",
      "external": true,
      "loc": "kernel/rcu/tree.c:904",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/printk/printk.c:console_unlock",
        "kernel/trace/trace.c:__trace_stack",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_freeze",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_freeze"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851952,
      "name": "rcu_irq_exit_irqson",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void rcu_irq_exit_irqson()
```

```json
{
  "name": "rcu_irq_exit_irqson",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579892496,
      "name": "rcu_irq_exit_irqson",
      "external": true,
      "loc": "kernel/rcu/tree.c:915",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/printk/printk.c:console_unlock",
        "kernel/trace/trace.c:__trace_stack",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579892496,
      "name": "rcu_irq_exit_irqson",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void rcu_irq_exit_irqson()
```

```json
{
  "name": "rcu_irq_exit_irqson",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579926192,
      "name": "rcu_irq_exit_irqson",
      "external": true,
      "loc": "kernel/rcu/tree.c:860",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/printk/printk.c:console_unlock",
        "kernel/trace/trace.c:__trace_stack",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579926192,
      "name": "rcu_irq_exit_irqson",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void rcu_irq_exit_irqson()
```

```json
{
  "name": "rcu_irq_exit_irqson",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579972576,
      "name": "rcu_irq_exit_irqson",
      "external": true,
      "loc": "kernel/rcu/tree.c:745",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/printk/printk.c:console_unlock",
        "kernel/trace/trace.c:__trace_stack",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/base/power/runtime.c:__pm_runtime_suspend",
        "drivers/base/power/runtime.c:pm_schedule_suspend",
        "drivers/base/power/runtime.c:pm_suspend_timer_fn",
        "drivers/base/power/runtime.c:pm_runtime_work",
        "drivers/base/power/runtime.c:pm_runtime_work",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579972576,
      "name": "rcu_irq_exit_irqson",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void rcu_irq_exit_irqson()
```

```json
{
  "name": "rcu_irq_exit_irqson",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580012576,
      "name": "rcu_irq_exit_irqson",
      "external": true,
      "loc": "kernel/rcu/tree.c:706",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/printk/printk.c:console_unlock",
        "kernel/trace/trace.c:__trace_stack",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580012576,
      "name": "rcu_irq_exit_irqson",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void rcu_irq_exit_irqson()
```

```json
{
  "name": "rcu_irq_exit_irqson",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580063008,
      "name": "rcu_irq_exit_irqson",
      "external": true,
      "loc": "kernel/rcu/tree.c:714",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/printk/printk.c:console_unlock",
        "kernel/time/tick-broadcast-hrtimer.c:bc_set_next",
        "kernel/trace/trace.c:__trace_stack",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580063008,
      "name": "rcu_irq_exit_irqson",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void rcu_irq_exit_irqson()
```

```json
{
  "name": "rcu_irq_exit_irqson",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580122480,
      "name": "rcu_irq_exit_irqson",
      "external": true,
      "loc": "kernel/rcu/tree.c:811",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "kernel/time/tick-broadcast-hrtimer.c:bc_set_next",
        "kernel/trace/trace.c:__trace_stack",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/base/power/runtime.c:update_autosuspend",
        "drivers/base/power/runtime.c:pm_runtime_allow",
        "drivers/base/power/runtime.c:pm_runtime_get_if_active",
        "drivers/base/power/runtime.c:__pm_runtime_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:enter_s2idle_proper",
        "drivers/cpuidle/cpuidle.c:enter_s2idle_proper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580122480,
      "name": "rcu_irq_exit_irqson",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void rcu_irq_exit_irqson()
```

```json
{
  "name": "rcu_irq_exit_irqson",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580104192,
      "name": "rcu_irq_exit_irqson",
      "external": true,
      "loc": "kernel/rcu/tree.c:877",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-broadcast-hrtimer.c:bc_set_next",
        "kernel/trace/trace.c:__trace_stack",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/base/power/runtime.c:update_autosuspend",
        "drivers/base/power/runtime.c:pm_runtime_allow",
        "drivers/base/power/runtime.c:pm_runtime_get_if_active",
        "drivers/base/power/runtime.c:__pm_runtime_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580104192,
      "name": "rcu_irq_exit_irqson",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void rcu_irq_exit_irqson()
```

```json
{
  "name": "rcu_irq_exit_irqson",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580107040,
      "name": "rcu_irq_exit_irqson",
      "external": true,
      "loc": "kernel/rcu/tree.c:882",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-broadcast-hrtimer.c:bc_set_next",
        "kernel/trace/trace.c:__trace_stack",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/base/power/runtime.c:update_autosuspend",
        "drivers/base/power/runtime.c:pm_runtime_allow",
        "drivers/base/power/runtime.c:pm_runtime_get_if_active",
        "drivers/base/power/runtime.c:__pm_runtime_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580107040,
      "name": "rcu_irq_exit_irqson",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void rcu_irq_exit_irqson()
```

```json
{
  "name": "rcu_irq_exit_irqson",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580247728,
      "name": "rcu_irq_exit_irqson",
      "external": true,
      "loc": "kernel/rcu/tree.c:835",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-broadcast-hrtimer.c:bc_set_next",
        "kernel/trace/trace.c:__trace_stack",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/base/power/runtime.c:update_autosuspend",
        "drivers/base/power/runtime.c:pm_runtime_allow",
        "drivers/base/power/runtime.c:pm_runtime_get_if_active",
        "drivers/base/power/runtime.c:__pm_runtime_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580247728,
      "name": "rcu_irq_exit_irqson",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void rcu_irq_exit_irqson()
```

```json
{
  "name": "rcu_irq_exit_irqson",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580415664,
      "name": "rcu_irq_exit_irqson",
      "external": true,
      "loc": "kernel/rcu/tree.c:842",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:printk_sprint",
        "kernel/time/tick-broadcast-hrtimer.c:bc_set_next",
        "kernel/trace/trace.c:__trace_stack",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/base/power/runtime.c:update_autosuspend",
        "drivers/base/power/runtime.c:pm_runtime_allow",
        "drivers/base/power/runtime.c:pm_runtime_get_if_active",
        "drivers/base/power/runtime.c:__pm_runtime_suspend",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580415664,
      "name": "rcu_irq_exit_irqson",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
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
void rcu_irq_exit_irqson()
```

```json
{
  "name": "rcu_irq_exit_irqson",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491272872,
      "name": "rcu_irq_exit_irqson",
      "external": true,
      "loc": "kernel/rcu/tree.c:714",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/process.c:arch_cpu_idle",
        "arch/arm64/kernel/process.c:arch_cpu_idle",
        "arch/arm64/kernel/smp.c:handle_IPI",
        "arch/arm64/kernel/smp.c:handle_IPI",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/printk/printk.c:console_unlock",
        "kernel/time/tick-broadcast-hrtimer.c:bc_set_next",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/cpu_pm.c:cpu_pm_notify",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491272872,
      "name": "rcu_irq_exit_irqson",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void rcu_irq_exit_irqson()
```

```json
{
  "name": "rcu_irq_exit_irqson",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225282204,
      "name": "rcu_irq_exit_irqson",
      "external": true,
      "loc": "kernel/rcu/tree.c:714",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/smp.c:smp_send_stop",
        "arch/arm/kernel/smp.c:smp_send_reschedule",
        "arch/arm/kernel/smp.c:handle_IPI",
        "arch/arm/kernel/smp.c:handle_IPI",
        "arch/arm/kernel/smp.c:tick_broadcast",
        "arch/arm/kernel/smp.c:arch_irq_work_raise",
        "arch/arm/kernel/smp.c:arch_send_call_function_single_ipi",
        "arch/arm/kernel/smp.c:arch_send_wakeup_ipi_mask",
        "arch/arm/kernel/smp.c:arch_send_call_function_ipi_mask",
        "arch/arm/mach-omap2/powerdomain.c:pwrdm_set_next_pwrst",
        "arch/arm/mach-omap2/powerdomain.c:_pwrdm_state_switch",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/printk/printk.c:console_unlock",
        "kernel/time/tick-broadcast-hrtimer.c:bc_set_next",
        "kernel/trace/trace.c:__trace_stack",
        "kernel/cpu_pm.c:cpu_pm_notify",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/perf/arm_pmu.c:cpu_pm_pmu_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225282204,
      "name": "rcu_irq_exit_irqson",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void rcu_irq_exit_irqson()
```

```json
{
  "name": "rcu_irq_exit_irqson",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284178672,
      "name": "rcu_irq_exit_irqson",
      "external": true,
      "loc": "kernel/rcu/tree.c:714",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/printk/printk.c:console_unlock",
        "kernel/time/tick-broadcast-hrtimer.c:bc_set_next",
        "kernel/trace/trace.c:__trace_stack",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284178672,
      "name": "rcu_irq_exit_irqson",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void rcu_irq_exit_irqson()
```

```json
{
  "name": "rcu_irq_exit_irqson",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271794262,
      "name": "rcu_irq_exit_irqson",
      "external": true,
      "loc": "kernel/rcu/tree.c:714",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/printk/printk.c:console_unlock",
        "kernel/trace/trace.c:__trace_stack",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271794262,
      "name": "rcu_irq_exit_irqson",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void rcu_irq_exit_irqson()
```

```json
{
  "name": "rcu_irq_exit_irqson",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580031744,
      "name": "rcu_irq_exit_irqson",
      "external": true,
      "loc": "kernel/rcu/tree.c:714",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/printk/printk.c:console_unlock",
        "kernel/time/tick-broadcast-hrtimer.c:bc_set_next",
        "kernel/trace/trace.c:__trace_stack",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580031744,
      "name": "rcu_irq_exit_irqson",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void rcu_irq_exit_irqson()
```

```json
{
  "name": "rcu_irq_exit_irqson",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579976064,
      "name": "rcu_irq_exit_irqson",
      "external": true,
      "loc": "kernel/rcu/tree.c:714",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/printk/printk.c:console_unlock",
        "kernel/time/tick-broadcast-hrtimer.c:bc_set_next",
        "kernel/trace/trace.c:__trace_stack",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579976064,
      "name": "rcu_irq_exit_irqson",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void rcu_irq_exit_irqson()
```

```json
{
  "name": "rcu_irq_exit_irqson",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580023280,
      "name": "rcu_irq_exit_irqson",
      "external": true,
      "loc": "kernel/rcu/tree.c:714",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/printk/printk.c:console_unlock",
        "kernel/time/tick-broadcast-hrtimer.c:bc_set_next",
        "kernel/trace/trace.c:__trace_stack",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580023280,
      "name": "rcu_irq_exit_irqson",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void rcu_irq_exit_irqson()
```

```json
{
  "name": "rcu_irq_exit_irqson",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580072800,
      "name": "rcu_irq_exit_irqson",
      "external": true,
      "loc": "kernel/rcu/tree.c:714",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/sched/idle.c:cpu_idle_poll",
        "kernel/time/tick-broadcast-hrtimer.c:bc_set_next",
        "kernel/trace/trace.c:__trace_stack",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_enable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/clk/clk.c:clk_core_disable",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/base/power/runtime.c:rpm_idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580072800,
      "name": "rcu_irq_exit_irqson",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void rcu_irq_exit_irqson()
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void rcu_irq_exit_irqson()
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
