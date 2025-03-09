# Function: <code>rcu_irq_exit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void rcu_irq_exit()
```

```json
{
  "name": "rcu_irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579794336,
      "name": "rcu_irq_exit",
      "external": true,
      "loc": "kernel/rcu/tree.c:754",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/kernel/process.c:default_idle",
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/softirq.c:irq_exit",
        "kernel/softirq.c:irq_exit",
        "kernel/sched/idle.c:cpu_startup_entry",
        "kernel/sched/idle.c:cpu_startup_entry",
        "kernel/time/tick-broadcast-hrtimer.c:bc_set_next",
        "kernel/time/tick-broadcast-hrtimer.c:bc_set_next",
        "kernel/trace/trace_stack.c:check_stack",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_freeze",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_freeze",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579794336,
      "name": "rcu_irq_exit",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rcu_irq_exit()
```

```json
{
  "name": "rcu_irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579819515,
      "name": "rcu_irq_exit",
      "external": true,
      "loc": "kernel/rcu/tree.c:789",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_irq_exit_irqson"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/softirq.c:irq_exit",
        "kernel/softirq.c:irq_exit",
        "kernel/rcu/tree.c:rcu_irq_exit_irqson",
        "kernel/trace/trace_stack.c:check_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579808592,
      "name": "rcu_irq_exit.part.66",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071579819440,
      "name": "rcu_irq_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rcu_irq_exit()
```

```json
{
  "name": "rcu_irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579848411,
      "name": "rcu_irq_exit",
      "external": true,
      "loc": "kernel/rcu/tree.c:790",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_irq_exit_irqson"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/softirq.c:irq_exit",
        "kernel/softirq.c:irq_exit",
        "kernel/rcu/tree.c:rcu_irq_exit_irqson",
        "kernel/trace/trace_stack.c:check_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579840480,
      "name": "rcu_irq_exit.part.68",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071579848336,
      "name": "rcu_irq_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void rcu_irq_exit()
```

```json
{
  "name": "rcu_irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579851982,
      "name": "rcu_irq_exit",
      "external": true,
      "loc": "kernel/rcu/tree.c:885",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_irq_exit_irqson"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/softirq.c:irq_exit",
        "kernel/softirq.c:irq_exit",
        "kernel/trace/trace_stack.c:check_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851904,
      "name": "rcu_irq_exit",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void rcu_irq_exit()
```

```json
{
  "name": "rcu_irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579892432,
      "name": "rcu_irq_exit",
      "external": true,
      "loc": "kernel/rcu/tree.c:888",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/softirq.c:irq_exit",
        "kernel/softirq.c:irq_exit",
        "kernel/rcu/tree.c:rcu_irq_exit_irqson"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579892432,
      "name": "rcu_irq_exit",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_irq_exit()
```

```json
{
  "name": "rcu_irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579926219,
      "name": "rcu_irq_exit",
      "external": true,
      "loc": "kernel/rcu/tree.c:842",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_irq_exit_irqson"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/softirq.c:irq_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579926160,
      "name": "rcu_irq_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void rcu_irq_exit()
```

```json
{
  "name": "rcu_irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579972432,
      "name": "rcu_irq_exit",
      "external": true,
      "loc": "kernel/rcu/tree.c:733",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/softirq.c:irq_exit",
        "kernel/rcu/tree.c:rcu_irq_exit_irqson"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579972432,
      "name": "rcu_irq_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void rcu_irq_exit()
```

```json
{
  "name": "rcu_irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580012448,
      "name": "rcu_irq_exit",
      "external": true,
      "loc": "kernel/rcu/tree.c:694",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/softirq.c:irq_exit",
        "kernel/softirq.c:irq_exit",
        "kernel/rcu/tree.c:rcu_irq_exit_irqson"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580012448,
      "name": "rcu_irq_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void rcu_irq_exit()
```

```json
{
  "name": "rcu_irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580062864,
      "name": "rcu_irq_exit",
      "external": true,
      "loc": "kernel/rcu/tree.c:702",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/softirq.c:irq_exit",
        "kernel/softirq.c:irq_exit",
        "kernel/rcu/tree.c:rcu_irq_exit_irqson"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580062864,
      "name": "rcu_irq_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void rcu_irq_exit()
```

```json
{
  "name": "rcu_irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591164416,
      "name": "rcu_irq_exit",
      "external": true,
      "loc": "kernel/rcu/tree.c:759",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:idtentry_exit_cond_rcu",
        "kernel/softirq.c:irq_exit",
        "kernel/rcu/tree.c:rcu_irq_exit_irqson"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591164416,
      "name": "rcu_irq_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void rcu_irq_exit()
```

```json
{
  "name": "rcu_irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591659488,
      "name": "rcu_irq_exit",
      "external": true,
      "loc": "kernel/rcu/tree.c:825",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:irq_exit",
        "kernel/rcu/tree.c:rcu_irq_exit_irqson",
        "kernel/entry/common.c:irqentry_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591659488,
      "name": "rcu_irq_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void rcu_irq_exit()
```

```json
{
  "name": "rcu_irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591603168,
      "name": "rcu_irq_exit",
      "external": true,
      "loc": "kernel/rcu/tree.c:830",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:irq_exit",
        "kernel/rcu/tree.c:rcu_irq_exit_irqson",
        "kernel/entry/common.c:irqentry_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591603168,
      "name": "rcu_irq_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void rcu_irq_exit()
```

```json
{
  "name": "rcu_irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592776064,
      "name": "rcu_irq_exit",
      "external": true,
      "loc": "kernel/rcu/tree.c:805",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:irq_exit",
        "kernel/rcu/tree.c:rcu_irq_exit_irqson",
        "kernel/entry/common.c:irqentry_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592776064,
      "name": "rcu_irq_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void rcu_irq_exit()
```

```json
{
  "name": "rcu_irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594673648,
      "name": "rcu_irq_exit",
      "external": true,
      "loc": "kernel/rcu/tree.c:812",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:irq_exit",
        "kernel/rcu/tree.c:rcu_irq_exit_irqson",
        "kernel/entry/common.c:irqentry_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594673648,
      "name": "rcu_irq_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void rcu_irq_exit()
```

```json
{
  "name": "rcu_irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491272712,
      "name": "rcu_irq_exit",
      "external": true,
      "loc": "kernel/rcu/tree.c:702",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:irq_exit",
        "kernel/softirq.c:irq_exit",
        "kernel/rcu/tree.c:rcu_irq_exit_irqson"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491272712,
      "name": "rcu_irq_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void rcu_irq_exit()
```

```json
{
  "name": "rcu_irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225281928,
      "name": "rcu_irq_exit",
      "external": true,
      "loc": "kernel/rcu/tree.c:702",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:irq_exit",
        "kernel/softirq.c:irq_exit",
        "kernel/rcu/tree.c:rcu_irq_exit_irqson"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225281928,
      "name": "rcu_irq_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void rcu_irq_exit()
```

```json
{
  "name": "rcu_irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284178480,
      "name": "rcu_irq_exit",
      "external": true,
      "loc": "kernel/rcu/tree.c:702",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:irq_exit",
        "kernel/softirq.c:irq_exit",
        "kernel/rcu/tree.c:rcu_irq_exit_irqson"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284178480,
      "name": "rcu_irq_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void rcu_irq_exit()
```

```json
{
  "name": "rcu_irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271794094,
      "name": "rcu_irq_exit",
      "external": true,
      "loc": "kernel/rcu/tree.c:702",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:irq_exit",
        "kernel/softirq.c:irq_exit",
        "kernel/rcu/tree.c:rcu_irq_exit_irqson"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271794094,
      "name": "rcu_irq_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void rcu_irq_exit()
```

```json
{
  "name": "rcu_irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580031600,
      "name": "rcu_irq_exit",
      "external": true,
      "loc": "kernel/rcu/tree.c:702",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/softirq.c:irq_exit",
        "kernel/softirq.c:irq_exit",
        "kernel/rcu/tree.c:rcu_irq_exit_irqson"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580031600,
      "name": "rcu_irq_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void rcu_irq_exit()
```

```json
{
  "name": "rcu_irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579975904,
      "name": "rcu_irq_exit",
      "external": true,
      "loc": "kernel/rcu/tree.c:702",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/softirq.c:irq_exit",
        "kernel/softirq.c:irq_exit",
        "kernel/softirq.c:irq_exit",
        "kernel/rcu/tree.c:rcu_irq_exit_irqson"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579975904,
      "name": "rcu_irq_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void rcu_irq_exit()
```

```json
{
  "name": "rcu_irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580023136,
      "name": "rcu_irq_exit",
      "external": true,
      "loc": "kernel/rcu/tree.c:702",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/softirq.c:irq_exit",
        "kernel/softirq.c:irq_exit",
        "kernel/rcu/tree.c:rcu_irq_exit_irqson"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580023136,
      "name": "rcu_irq_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void rcu_irq_exit()
```

```json
{
  "name": "rcu_irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580072656,
      "name": "rcu_irq_exit",
      "external": true,
      "loc": "kernel/rcu/tree.c:702",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/softirq.c:irq_exit",
        "kernel/softirq.c:irq_exit",
        "kernel/rcu/tree.c:rcu_irq_exit_irqson"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580072656,
      "name": "rcu_irq_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void rcu_irq_exit()
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
