# Function: <code>rcu_irq_enter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void rcu_irq_enter()
```

```json
{
  "name": "rcu_irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579794480,
      "name": "rcu_irq_enter",
      "external": true,
      "loc": "kernel/rcu/tree.c:882",
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
        "kernel/softirq.c:irq_enter",
        "kernel/sched/idle.c:cpu_startup_entry",
        "kernel/sched/idle.c:cpu_startup_entry",
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
      "addr": 18446744071579794480,
      "name": "rcu_irq_enter",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rcu_irq_enter()
```

```json
{
  "name": "rcu_irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579819643,
      "name": "rcu_irq_enter",
      "external": true,
      "loc": "kernel/rcu/tree.c:927",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_irq_enter_irqson"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/softirq.c:irq_enter",
        "kernel/rcu/tree.c:rcu_irq_enter_irqson",
        "kernel/trace/trace_stack.c:check_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579808688,
      "name": "rcu_irq_enter.part.67",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071579819568,
      "name": "rcu_irq_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void rcu_irq_enter()
```

```json
{
  "name": "rcu_irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579848539,
      "name": "rcu_irq_enter",
      "external": true,
      "loc": "kernel/rcu/tree.c:928",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_irq_enter_irqson"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/softirq.c:irq_enter",
        "kernel/rcu/tree.c:rcu_irq_enter_irqson",
        "kernel/trace/trace_stack.c:check_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579840576,
      "name": "rcu_irq_enter.part.69",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071579848464,
      "name": "rcu_irq_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void rcu_irq_enter()
```

```json
{
  "name": "rcu_irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579852123,
      "name": "rcu_irq_enter",
      "external": true,
      "loc": "kernel/rcu/tree.c:1016",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_irq_enter_irqson"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/softirq.c:irq_enter",
        "kernel/trace/trace_stack.c:check_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579852048,
      "name": "rcu_irq_enter",
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
void rcu_irq_enter()
```

```json
{
  "name": "rcu_irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579892672,
      "name": "rcu_irq_enter",
      "external": true,
      "loc": "kernel/rcu/tree.c:1037",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/softirq.c:irq_enter",
        "kernel/rcu/tree.c:rcu_irq_enter_irqson"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579892672,
      "name": "rcu_irq_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void rcu_irq_enter()
```

```json
{
  "name": "rcu_irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579926523,
      "name": "rcu_irq_enter",
      "external": true,
      "loc": "kernel/rcu/tree.c:995",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_irq_enter_irqson"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/softirq.c:irq_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579926464,
      "name": "rcu_irq_enter",
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
void rcu_irq_enter()
```

```json
{
  "name": "rcu_irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579972768,
      "name": "rcu_irq_enter",
      "external": true,
      "loc": "kernel/rcu/tree.c:898",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/softirq.c:irq_enter",
        "kernel/rcu/tree.c:rcu_irq_enter_irqson"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579972768,
      "name": "rcu_irq_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void rcu_irq_enter()
```

```json
{
  "name": "rcu_irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580012768,
      "name": "rcu_irq_enter",
      "external": true,
      "loc": "kernel/rcu/tree.c:860",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/softirq.c:irq_enter",
        "kernel/rcu/tree.c:rcu_irq_enter_irqson"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580012768,
      "name": "rcu_irq_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void rcu_irq_enter()
```

```json
{
  "name": "rcu_irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580063200,
      "name": "rcu_irq_enter",
      "external": true,
      "loc": "kernel/rcu/tree.c:868",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/softirq.c:irq_enter",
        "kernel/rcu/tree.c:rcu_irq_enter_irqson"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580063200,
      "name": "rcu_irq_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void rcu_irq_enter()
```

```json
{
  "name": "rcu_irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591164544,
      "name": "rcu_irq_enter",
      "external": true,
      "loc": "kernel/rcu/tree.c:1042",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:idtentry_enter_cond_rcu",
        "kernel/softirq.c:irq_enter",
        "kernel/rcu/tree.c:rcu_irq_enter_irqson"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591164544,
      "name": "rcu_irq_enter",
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
void rcu_irq_enter()
```

```json
{
  "name": "rcu_irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591659616,
      "name": "rcu_irq_enter",
      "external": true,
      "loc": "kernel/rcu/tree.c:1111",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:irq_enter",
        "kernel/rcu/tree.c:rcu_irq_enter_irqson",
        "kernel/entry/common.c:irqentry_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591659616,
      "name": "rcu_irq_enter",
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
void rcu_irq_enter()
```

```json
{
  "name": "rcu_irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591603296,
      "name": "rcu_irq_enter",
      "external": true,
      "loc": "kernel/rcu/tree.c:1115",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:irq_enter",
        "kernel/rcu/tree.c:rcu_irq_enter_irqson",
        "kernel/entry/common.c:irqentry_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591603296,
      "name": "rcu_irq_enter",
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
void rcu_irq_enter()
```

```json
{
  "name": "rcu_irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592776192,
      "name": "rcu_irq_enter",
      "external": true,
      "loc": "kernel/rcu/tree.c:1068",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:irq_enter",
        "kernel/rcu/tree.c:rcu_irq_enter_irqson",
        "kernel/entry/common.c:irqentry_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592776192,
      "name": "rcu_irq_enter",
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
void rcu_irq_enter()
```

```json
{
  "name": "rcu_irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594673792,
      "name": "rcu_irq_enter",
      "external": true,
      "loc": "kernel/rcu/tree.c:1068",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:irq_enter",
        "kernel/rcu/tree.c:rcu_irq_enter_irqson",
        "kernel/entry/common.c:irqentry_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594673792,
      "name": "rcu_irq_enter",
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
void rcu_irq_enter()
```

```json
{
  "name": "rcu_irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491273088,
      "name": "rcu_irq_enter",
      "external": true,
      "loc": "kernel/rcu/tree.c:868",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:irq_enter",
        "kernel/rcu/tree.c:rcu_irq_enter_irqson"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491273088,
      "name": "rcu_irq_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void rcu_irq_enter()
```

```json
{
  "name": "rcu_irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225282408,
      "name": "rcu_irq_enter",
      "external": true,
      "loc": "kernel/rcu/tree.c:868",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:irq_enter",
        "kernel/rcu/tree.c:rcu_irq_enter_irqson"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225282408,
      "name": "rcu_irq_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void rcu_irq_enter()
```

```json
{
  "name": "rcu_irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284178976,
      "name": "rcu_irq_enter",
      "external": true,
      "loc": "kernel/rcu/tree.c:868",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:irq_enter",
        "kernel/rcu/tree.c:rcu_irq_enter_irqson"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284178976,
      "name": "rcu_irq_enter",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void rcu_irq_enter()
```

```json
{
  "name": "rcu_irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271794452,
      "name": "rcu_irq_enter",
      "external": true,
      "loc": "kernel/rcu/tree.c:868",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:irq_enter",
        "kernel/rcu/tree.c:rcu_irq_enter_irqson"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271794452,
      "name": "rcu_irq_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void rcu_irq_enter()
```

```json
{
  "name": "rcu_irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580031936,
      "name": "rcu_irq_enter",
      "external": true,
      "loc": "kernel/rcu/tree.c:868",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/softirq.c:irq_enter",
        "kernel/rcu/tree.c:rcu_irq_enter_irqson"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580031936,
      "name": "rcu_irq_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void rcu_irq_enter()
```

```json
{
  "name": "rcu_irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579976144,
      "name": "rcu_irq_enter",
      "external": true,
      "loc": "kernel/rcu/tree.c:868",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/softirq.c:irq_enter",
        "kernel/rcu/tree.c:rcu_irq_enter_irqson"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579976144,
      "name": "rcu_irq_enter",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void rcu_irq_enter()
```

```json
{
  "name": "rcu_irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580023472,
      "name": "rcu_irq_enter",
      "external": true,
      "loc": "kernel/rcu/tree.c:868",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/softirq.c:irq_enter",
        "kernel/rcu/tree.c:rcu_irq_enter_irqson"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580023472,
      "name": "rcu_irq_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void rcu_irq_enter()
```

```json
{
  "name": "rcu_irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580072992,
      "name": "rcu_irq_enter",
      "external": true,
      "loc": "kernel/rcu/tree.c:868",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/softirq.c:irq_enter",
        "kernel/rcu/tree.c:rcu_irq_enter_irqson"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580072992,
      "name": "rcu_irq_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void rcu_irq_enter()
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
