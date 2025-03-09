# Function: <code>idle_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int idle_cpu(int cpu)
```

```json
{
  "name": "idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579543141,
      "name": "idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:3567",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:scheduler_tick"
      ],
      "caller_func": [
        "kernel/softirq.c:irq_exit",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/fair.c:run_rebalance_domains",
        "kernel/sched/fair.c:trigger_load_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579556064,
      "name": "idle_cpu",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int idle_cpu(int cpu)
```

```json
{
  "name": "idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579565384,
      "name": "idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:3820",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target"
      ],
      "caller_func": [
        "kernel/softirq.c:irq_exit",
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:run_rebalance_domains",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:select_task_rq_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579566736,
      "name": "idle_cpu",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int idle_cpu(int cpu)
```

```json
{
  "name": "idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579590280,
      "name": "idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:3857",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target"
      ],
      "caller_func": [
        "kernel/softirq.c:irq_exit",
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:run_rebalance_domains",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:__update_idle_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579591712,
      "name": "idle_cpu",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int idle_cpu(int cpu)
```

```json
{
  "name": "idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579574577,
      "name": "idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:3863",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target"
      ],
      "caller_func": [
        "kernel/softirq.c:irq_exit",
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:run_rebalance_domains",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:__update_idle_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579575968,
      "name": "idle_cpu",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int idle_cpu(int cpu)
```

```json
{
  "name": "idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579604215,
      "name": "idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:3907",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target"
      ],
      "caller_func": [
        "kernel/softirq.c:irq_exit",
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:run_rebalance_domains",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:find_busiest_group",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:__update_idle_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579605664,
      "name": "idle_cpu",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int idle_cpu(int cpu)
```

```json
{
  "name": "idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579636933,
      "name": "idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:4017",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:available_idle_cpu",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target"
      ],
      "caller_func": [
        "kernel/softirq.c:irq_exit",
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:find_busiest_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579636848,
      "name": "idle_cpu",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int idle_cpu(int cpu)
```

```json
{
  "name": "idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579674613,
      "name": "idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:4002",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:available_idle_cpu",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target"
      ],
      "caller_func": [
        "kernel/softirq.c:irq_exit",
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579674528,
      "name": "idle_cpu",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int idle_cpu(int cpu)
```

```json
{
  "name": "idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579706533,
      "name": "idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:4421",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:available_idle_cpu",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target"
      ],
      "caller_func": [
        "kernel/softirq.c:irq_exit",
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579706448,
      "name": "idle_cpu",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int idle_cpu(int cpu)
```

```json
{
  "name": "idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579748629,
      "name": "idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:4623",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:available_idle_cpu",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat",
        "kernel/softirq.c:irq_exit",
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579748544,
      "name": "idle_cpu",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int idle_cpu(int cpu)
```

```json
{
  "name": "idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579784341,
      "name": "idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:4856",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:available_idle_cpu",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:nohz_csd_func",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat",
        "kernel/softirq.c:irq_exit",
        "kernel/softirq.c:irq_exit_rcu",
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/fair.c:task_numa_compare",
        "kernel/sched/fair.c:task_numa_compare",
        "kernel/sched/fair.c:task_numa_compare",
        "kernel/sched/fair.c:task_numa_assign",
        "kernel/sched/fair.c:update_numa_stats",
        "kernel/sched/fair.c:update_numa_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579784256,
      "name": "idle_cpu",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int idle_cpu(int cpu)
```

```json
{
  "name": "idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579774789,
      "name": "idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:5629",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:available_idle_cpu",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:nohz_csd_func",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target"
      ],
      "caller_func": [
        "kernel/softirq.c:irq_exit",
        "kernel/softirq.c:irq_exit_rcu",
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/fair.c:task_numa_compare",
        "kernel/sched/fair.c:task_numa_compare",
        "kernel/sched/fair.c:task_numa_compare",
        "kernel/sched/fair.c:task_numa_assign",
        "kernel/sched/fair.c:update_numa_stats",
        "kernel/sched/fair.c:update_numa_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579774704,
      "name": "idle_cpu",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int idle_cpu(int cpu)
```

```json
{
  "name": "idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579782677,
      "name": "idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:5844",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:available_idle_cpu",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:nohz_csd_func",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target"
      ],
      "caller_func": [
        "kernel/softirq.c:irq_exit",
        "kernel/softirq.c:irq_exit_rcu",
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/fair.c:task_numa_compare",
        "kernel/sched/fair.c:task_numa_compare",
        "kernel/sched/fair.c:task_numa_compare",
        "kernel/sched/fair.c:task_numa_assign",
        "kernel/sched/fair.c:update_numa_stats",
        "kernel/sched/fair.c:update_numa_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579782592,
      "name": "idle_cpu",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int idle_cpu(int cpu)
```

```json
{
  "name": "idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579876629,
      "name": "idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:7007",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:available_idle_cpu",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:nohz_csd_func",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target"
      ],
      "caller_func": [
        "kernel/softirq.c:irq_exit",
        "kernel/softirq.c:irq_exit_rcu",
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/fair.c:task_numa_compare",
        "kernel/sched/fair.c:task_numa_compare",
        "kernel/sched/fair.c:task_numa_compare",
        "kernel/sched/fair.c:task_numa_assign",
        "kernel/sched/fair.c:update_numa_stats",
        "kernel/sched/fair.c:update_numa_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579876512,
      "name": "idle_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int idle_cpu(int cpu)
```

```json
{
  "name": "idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579992501,
      "name": "idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:7099",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:available_idle_cpu",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:nohz_csd_func",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi",
        "kernel/softirq.c:__irq_exit_rcu",
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/fair.c:task_numa_compare",
        "kernel/sched/fair.c:task_numa_compare",
        "kernel/sched/fair.c:task_numa_compare",
        "kernel/sched/fair.c:task_numa_assign",
        "kernel/sched/fair.c:update_numa_stats",
        "kernel/sched/fair.c:update_numa_stats",
        "kernel/rcu/tree.c:print_cpu_stall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579992368,
      "name": "idle_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int idle_cpu(int cpu)
```

```json
{
  "name": "idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580153893,
      "name": "idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:7240",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:available_idle_cpu",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:nohz_csd_func",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi",
        "kernel/softirq.c:__irq_exit_rcu",
        "kernel/sched/fair.c:nohz_balancer_kick",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/fair.c:task_numa_compare",
        "kernel/sched/fair.c:task_numa_compare",
        "kernel/sched/fair.c:task_numa_compare",
        "kernel/sched/fair.c:task_numa_assign",
        "kernel/sched/fair.c:update_numa_stats",
        "kernel/sched/fair.c:update_numa_stats",
        "kernel/rcu/tree.c:print_cpu_stall_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580153744,
      "name": "idle_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int idle_cpu(int cpu)
```

```json
{
  "name": "idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580204405,
      "name": "idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:7341",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:available_idle_cpu",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:nohz_csd_func",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi",
        "kernel/softirq.c:__irq_exit_rcu",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/fair.c:sched_use_asym_prio",
        "kernel/sched/fair.c:task_numa_compare",
        "kernel/sched/fair.c:task_numa_compare",
        "kernel/sched/fair.c:task_numa_compare",
        "kernel/sched/fair.c:task_numa_assign",
        "kernel/sched/fair.c:update_numa_stats",
        "kernel/sched/fair.c:update_numa_stats",
        "kernel/rcu/tree.c:print_cpu_stall_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580204256,
      "name": "idle_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int idle_cpu(int cpu)
```

```json
{
  "name": "idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580253286,
      "name": "idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:7391",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_core_idle_cpu",
        "kernel/sched/core.c:available_idle_cpu",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:nohz_csd_func",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/fair.c:should_we_balance",
        "kernel/sched/fair.c:should_we_balance",
        "kernel/sched/fair.c:update_sg_lb_stats",
        "kernel/sched/fair.c:sched_use_asym_prio",
        "kernel/sched/fair.c:task_numa_compare",
        "kernel/sched/fair.c:task_numa_compare",
        "kernel/sched/fair.c:task_numa_compare",
        "kernel/sched/fair.c:task_numa_assign",
        "kernel/sched/fair.c:update_numa_stats",
        "kernel/sched/fair.c:update_numa_stats",
        "kernel/rcu/tree.c:print_cpu_stall_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580252816,
      "name": "idle_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int idle_cpu(int cpu)
```

```json
{
  "name": "idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490927240,
      "name": "idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:4623",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:available_idle_cpu",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target"
      ],
      "caller_func": [
        "kernel/softirq.c:irq_exit",
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490927096,
      "name": "idle_cpu",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int idle_cpu(int cpu)
```

```json
{
  "name": "idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224945060,
      "name": "idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:4623",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:available_idle_cpu",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target"
      ],
      "caller_func": [
        "kernel/softirq.c:irq_exit",
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224944944,
      "name": "idle_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int idle_cpu(int cpu)
```

```json
{
  "name": "idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283780240,
      "name": "idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:4623",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:available_idle_cpu",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target"
      ],
      "caller_func": [
        "kernel/softirq.c:irq_exit",
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283780112,
      "name": "idle_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int idle_cpu(int cpu)
```

```json
{
  "name": "idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271562768,
      "name": "idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:4623",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:available_idle_cpu",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target"
      ],
      "caller_func": [
        "kernel/softirq.c:irq_exit",
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271562648,
      "name": "idle_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int idle_cpu(int cpu)
```

```json
{
  "name": "idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579724581,
      "name": "idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:4623",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:available_idle_cpu",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target"
      ],
      "caller_func": [
        "kernel/softirq.c:irq_exit",
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579724496,
      "name": "idle_cpu",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int idle_cpu(int cpu)
```

```json
{
  "name": "idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579653141,
      "name": "idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:4623",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:available_idle_cpu",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target"
      ],
      "caller_func": [
        "kernel/softirq.c:irq_exit",
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579653056,
      "name": "idle_cpu",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int idle_cpu(int cpu)
```

```json
{
  "name": "idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579711333,
      "name": "idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:4623",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:available_idle_cpu",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target"
      ],
      "caller_func": [
        "kernel/softirq.c:irq_exit",
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579711248,
      "name": "idle_cpu",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int idle_cpu(int cpu)
```

```json
{
  "name": "idle_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579756261,
      "name": "idle_cpu",
      "external": true,
      "loc": "kernel/sched/core.c:4623",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:available_idle_cpu",
        "kernel/sched/core.c:scheduler_tick",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:get_nohz_timer_target",
        "kernel/sched/core.c:get_nohz_timer_target"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat",
        "kernel/softirq.c:irq_exit",
        "kernel/sched/fair.c:_nohz_idle_balance",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_sd_lb_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579756176,
      "name": "idle_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
