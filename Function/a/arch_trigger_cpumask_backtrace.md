# Function: <code>arch_trigger_cpumask_backtrace</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self)
```

```json
{
  "name": "arch_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579208912,
      "name": "arch_trigger_cpumask_backtrace",
      "external": true,
      "loc": "arch/x86/kernel/apic/hw_nmi.c:35",
      "file": "arch/x86/kernel/apic/hw_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/hung_task.c:watchdog",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/tty/sysrq.c:sysrq_handle_showallcpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579208912,
      "name": "arch_trigger_cpumask_backtrace",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self)
```

```json
{
  "name": "arch_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579206432,
      "name": "arch_trigger_cpumask_backtrace",
      "external": true,
      "loc": "arch/x86/kernel/apic/hw_nmi.c:35",
      "file": "arch/x86/kernel/apic/hw_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_dump_cpu_stacks",
        "kernel/hung_task.c:watchdog",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/tty/sysrq.c:sysrq_handle_showallcpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579206432,
      "name": "arch_trigger_cpumask_backtrace",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self)
```

```json
{
  "name": "arch_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579224096,
      "name": "arch_trigger_cpumask_backtrace",
      "external": true,
      "loc": "arch/x86/kernel/apic/hw_nmi.c:36",
      "file": "arch/x86/kernel/apic/hw_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_dump_cpu_stacks",
        "kernel/hung_task.c:watchdog",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/tty/sysrq.c:sysrq_handle_showallcpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579224096,
      "name": "arch_trigger_cpumask_backtrace",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self)
```

```json
{
  "name": "arch_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579236496,
      "name": "arch_trigger_cpumask_backtrace",
      "external": true,
      "loc": "arch/x86/kernel/apic/hw_nmi.c:36",
      "file": "arch/x86/kernel/apic/hw_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_dump_cpu_stacks",
        "kernel/hung_task.c:watchdog",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/tty/sysrq.c:sysrq_handle_showallcpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579236496,
      "name": "arch_trigger_cpumask_backtrace",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self)
```

```json
{
  "name": "arch_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579260160,
      "name": "arch_trigger_cpumask_backtrace",
      "external": true,
      "loc": "arch/x86/kernel/apic/hw_nmi.c:36",
      "file": "arch/x86/kernel/apic/hw_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_dump_cpu_stacks",
        "kernel/hung_task.c:watchdog",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/tty/sysrq.c:sysrq_handle_showallcpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579260160,
      "name": "arch_trigger_cpumask_backtrace",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self)
```

```json
{
  "name": "arch_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579274272,
      "name": "arch_trigger_cpumask_backtrace",
      "external": true,
      "loc": "arch/x86/kernel/apic/hw_nmi.c:36",
      "file": "arch/x86/kernel/apic/hw_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_dump_cpu_stacks",
        "kernel/hung_task.c:watchdog",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/tty/sysrq.c:sysrq_handle_showallcpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579274272,
      "name": "arch_trigger_cpumask_backtrace",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self)
```

```json
{
  "name": "arch_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579276704,
      "name": "arch_trigger_cpumask_backtrace",
      "external": true,
      "loc": "arch/x86/kernel/apic/hw_nmi.c:36",
      "file": "arch/x86/kernel/apic/hw_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_dump_cpu_stacks",
        "kernel/hung_task.c:watchdog",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/tty/sysrq.c:sysrq_handle_showallcpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579276704,
      "name": "arch_trigger_cpumask_backtrace",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self)
```

```json
{
  "name": "arch_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579305344,
      "name": "arch_trigger_cpumask_backtrace",
      "external": true,
      "loc": "arch/x86/kernel/apic/hw_nmi.c:36",
      "file": "arch/x86/kernel/apic/hw_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:oops_enter",
        "kernel/rcu/tree.c:rcu_dump_cpu_stacks",
        "kernel/hung_task.c:check_hung_uninterruptible_tasks",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/tty/sysrq.c:sysrq_handle_showallcpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579305344,
      "name": "arch_trigger_cpumask_backtrace",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self)
```

```json
{
  "name": "arch_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579310656,
      "name": "arch_trigger_cpumask_backtrace",
      "external": true,
      "loc": "arch/x86/kernel/apic/hw_nmi.c:37",
      "file": "arch/x86/kernel/apic/hw_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:oops_enter",
        "kernel/rcu/tree.c:rcu_dump_cpu_stacks",
        "kernel/hung_task.c:check_hung_uninterruptible_tasks",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/tty/sysrq.c:sysrq_handle_showallcpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579310656,
      "name": "arch_trigger_cpumask_backtrace",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self)
```

```json
{
  "name": "arch_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579313472,
      "name": "arch_trigger_cpumask_backtrace",
      "external": true,
      "loc": "arch/x86/kernel/apic/hw_nmi.c:37",
      "file": "arch/x86/kernel/apic/hw_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:oops_enter",
        "kernel/rcu/tree.c:trigger_single_cpu_backtrace",
        "kernel/hung_task.c:check_hung_uninterruptible_tasks",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/tty/sysrq.c:sysrq_handle_showallcpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579313472,
      "name": "arch_trigger_cpumask_backtrace",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self)
```

```json
{
  "name": "arch_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579362336,
      "name": "arch_trigger_cpumask_backtrace",
      "external": true,
      "loc": "arch/x86/kernel/apic/hw_nmi.c:37",
      "file": "arch/x86/kernel/apic/hw_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:oops_enter",
        "kernel/rcu/tree.c:trigger_single_cpu_backtrace",
        "kernel/hung_task.c:check_hung_uninterruptible_tasks",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/tty/sysrq.c:sysrq_handle_showallcpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579362336,
      "name": "arch_trigger_cpumask_backtrace",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self)
```

```json
{
  "name": "arch_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579425504,
      "name": "arch_trigger_cpumask_backtrace",
      "external": true,
      "loc": "arch/x86/kernel/apic/hw_nmi.c:37",
      "file": "arch/x86/kernel/apic/hw_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:oops_enter",
        "kernel/rcu/tree.c:trigger_single_cpu_backtrace",
        "kernel/hung_task.c:check_hung_uninterruptible_tasks",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/tty/sysrq.c:sysrq_handle_showallcpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579425504,
      "name": "arch_trigger_cpumask_backtrace",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self)
```

```json
{
  "name": "arch_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579509424,
      "name": "arch_trigger_cpumask_backtrace",
      "external": true,
      "loc": "arch/x86/kernel/apic/hw_nmi.c:37",
      "file": "arch/x86/kernel/apic/hw_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:oops_enter",
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/sched/core.c:dump_cpu_task",
        "kernel/hung_task.c:check_hung_uninterruptible_tasks",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/tty/sysrq.c:sysrq_handle_showallcpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579509424,
      "name": "arch_trigger_cpumask_backtrace",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t * mask, int exclude_cpu)
```

```json
{
  "name": "arch_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579521680,
      "name": "arch_trigger_cpumask_backtrace",
      "external": true,
      "loc": "arch/x86/kernel/apic/hw_nmi.c:37",
      "file": "arch/x86/kernel/apic/hw_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:oops_enter",
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/sched/core.c:dump_cpu_task",
        "kernel/hung_task.c:check_hung_uninterruptible_tasks",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog.c:watchdog_hardlockup_check",
        "kernel/watchdog.c:watchdog_hardlockup_check",
        "drivers/tty/sysrq.c:sysrq_handle_showallcpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579521680,
      "name": "arch_trigger_cpumask_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void arch_trigger_cpumask_backtrace(const cpumask_t * mask, int exclude_cpu)
```

```json
{
  "name": "arch_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579550480,
      "name": "arch_trigger_cpumask_backtrace",
      "external": true,
      "loc": "arch/x86/kernel/apic/hw_nmi.c:39",
      "file": "arch/x86/kernel/apic/hw_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:oops_enter",
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/sched/core.c:dump_cpu_task",
        "kernel/hung_task.c:check_hung_uninterruptible_tasks",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog.c:watchdog_hardlockup_check",
        "kernel/watchdog.c:watchdog_hardlockup_check",
        "drivers/tty/sysrq.c:sysrq_handle_showallcpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579550480,
      "name": "arch_trigger_cpumask_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self)
```

```json
{
  "name": "arch_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224451928,
      "name": "arch_trigger_cpumask_backtrace",
      "external": true,
      "loc": "arch/arm/kernel/smp.c:813",
      "file": "arch/arm/kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_dump_cpu_stacks",
        "kernel/hung_task.c:watchdog",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/tty/sysrq.c:sysrq_handle_showallcpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224451928,
      "name": "arch_trigger_cpumask_backtrace",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self)
```

```json
{
  "name": "arch_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282596304,
      "name": "arch_trigger_cpumask_backtrace",
      "external": true,
      "loc": "arch/powerpc/kernel/stacktrace.c:267",
      "file": "arch/powerpc/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/watchdog.c:watchdog_timer_fn",
        "arch/powerpc/kernel/watchdog.c:soft_nmi_interrupt",
        "kernel/rcu/tree.c:rcu_dump_cpu_stacks",
        "kernel/hung_task.c:watchdog",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/tty/sysrq.c:sysrq_handle_showallcpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282596304,
      "name": "arch_trigger_cpumask_backtrace",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self)
```

```json
{
  "name": "arch_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579275408,
      "name": "arch_trigger_cpumask_backtrace",
      "external": true,
      "loc": "arch/x86/kernel/apic/hw_nmi.c:36",
      "file": "arch/x86/kernel/apic/hw_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_dump_cpu_stacks",
        "kernel/hung_task.c:watchdog",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/tty/sysrq.c:sysrq_handle_showallcpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579275408,
      "name": "arch_trigger_cpumask_backtrace",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self)
```

```json
{
  "name": "arch_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579210752,
      "name": "arch_trigger_cpumask_backtrace",
      "external": true,
      "loc": "arch/x86/kernel/apic/hw_nmi.c:36",
      "file": "arch/x86/kernel/apic/hw_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_dump_cpu_stacks",
        "kernel/hung_task.c:watchdog",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/tty/sysrq.c:sysrq_handle_showallcpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579210752,
      "name": "arch_trigger_cpumask_backtrace",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self)
```

```json
{
  "name": "arch_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579276608,
      "name": "arch_trigger_cpumask_backtrace",
      "external": true,
      "loc": "arch/x86/kernel/apic/hw_nmi.c:36",
      "file": "arch/x86/kernel/apic/hw_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_dump_cpu_stacks",
        "kernel/hung_task.c:watchdog",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/tty/sysrq.c:sysrq_handle_showallcpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579276608,
      "name": "arch_trigger_cpumask_backtrace",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self)
```

```json
{
  "name": "arch_trigger_cpumask_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579282496,
      "name": "arch_trigger_cpumask_backtrace",
      "external": true,
      "loc": "arch/x86/kernel/apic/hw_nmi.c:36",
      "file": "arch/x86/kernel/apic/hw_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_dump_cpu_stacks",
        "kernel/hung_task.c:watchdog",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/tty/sysrq.c:sysrq_handle_showallcpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579282496,
      "name": "arch_trigger_cpumask_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self)
```
</details>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int exclude_cpu</code>
</li>
<li>
<b>Param removed. </b>
<code>bool exclude_self</code>
</li>
</ul>
</details>
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
void arch_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t * mask, bool exclude_self)
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
