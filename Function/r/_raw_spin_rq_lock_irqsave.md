# Function: <code>_raw_spin_rq_lock_irqsave</code>

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
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_raw_spin_rq_lock_irqsave",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579883463,
      "name": "_raw_spin_rq_lock_irqsave",
      "external": false,
      "loc": "kernel/sched/sched.h:1333",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:balance_push_set",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:resched_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579964910,
      "name": "_raw_spin_rq_lock_irqsave",
      "external": false,
      "loc": "kernel/sched/sched.h:1333",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:sched_group_set_idle",
        "kernel/sched/fair.c:unregister_fair_sched_group",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:distribute_cfs_runtime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580021445,
      "name": "_raw_spin_rq_lock_irqsave",
      "external": false,
      "loc": "kernel/sched/sched.h:1333",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580048486,
      "name": "_raw_spin_rq_lock_irqsave",
      "external": false,
      "loc": "kernel/sched/sched.h:1333",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:print_cfs_rq"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate ❓</summary>

```c
long unsigned int _raw_spin_rq_lock_irqsave(struct rq * rq)
```

```json
{
  "name": "_raw_spin_rq_lock_irqsave",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579952400,
      "name": "_raw_spin_rq_lock_irqsave",
      "external": false,
      "loc": "kernel/sched/sched.h:1319",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:balance_push_set",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:resched_cpu"
      ]
    },
    {
      "addr": 18446744071580005504,
      "name": "_raw_spin_rq_lock_irqsave",
      "external": false,
      "loc": "kernel/sched/sched.h:1319",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_idle",
        "kernel/sched/fair.c:__sched_group_set_shares",
        "kernel/sched/fair.c:unregister_fair_sched_group",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:distribute_cfs_runtime"
      ]
    },
    {
      "addr": 18446744071580144976,
      "name": "_raw_spin_rq_lock_irqsave",
      "external": false,
      "loc": "kernel/sched/sched.h:1319",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:rq_attach_root",
        "kernel/sched/build_utility.c:print_cfs_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579952400,
      "name": "_raw_spin_rq_lock_irqsave",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071580005504,
      "name": "_raw_spin_rq_lock_irqsave",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071580144976,
      "name": "_raw_spin_rq_lock_irqsave",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate ❓</summary>

```c
long unsigned int _raw_spin_rq_lock_irqsave(struct rq * rq)
```

```json
{
  "name": "_raw_spin_rq_lock_irqsave",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580111456,
      "name": "_raw_spin_rq_lock_irqsave",
      "external": false,
      "loc": "kernel/sched/sched.h:1373",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:balance_push_set",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:resched_cpu"
      ]
    },
    {
      "addr": 18446744071580168032,
      "name": "_raw_spin_rq_lock_irqsave",
      "external": false,
      "loc": "kernel/sched/sched.h:1373",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_idle",
        "kernel/sched/fair.c:__sched_group_set_shares",
        "kernel/sched/fair.c:unregister_fair_sched_group",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:distribute_cfs_runtime"
      ]
    },
    {
      "addr": 18446744071580319664,
      "name": "_raw_spin_rq_lock_irqsave",
      "external": false,
      "loc": "kernel/sched/sched.h:1373",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:rq_attach_root",
        "kernel/sched/build_utility.c:print_cfs_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580111456,
      "name": "_raw_spin_rq_lock_irqsave",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071580168032,
      "name": "_raw_spin_rq_lock_irqsave",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071580319664,
      "name": "_raw_spin_rq_lock_irqsave",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate ❓</summary>

```c
long unsigned int _raw_spin_rq_lock_irqsave(struct rq * rq)
```

```json
{
  "name": "_raw_spin_rq_lock_irqsave",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580173424,
      "name": "_raw_spin_rq_lock_irqsave",
      "external": false,
      "loc": "kernel/sched/sched.h:1381",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_mm_cid_after_execve",
        "kernel/sched/core.c:sched_mm_cid_before_execve",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:balance_push_set",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:resched_cpu"
      ]
    },
    {
      "addr": 18446744071580233504,
      "name": "_raw_spin_rq_lock_irqsave",
      "external": false,
      "loc": "kernel/sched/sched.h:1381",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_idle",
        "kernel/sched/fair.c:__sched_group_set_shares",
        "kernel/sched/fair.c:unregister_fair_sched_group",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:distribute_cfs_runtime",
        "kernel/sched/fair.c:distribute_cfs_runtime"
      ]
    },
    {
      "addr": 18446744071580386928,
      "name": "_raw_spin_rq_lock_irqsave",
      "external": false,
      "loc": "kernel/sched/sched.h:1381",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:rq_attach_root",
        "kernel/sched/build_utility.c:print_cfs_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580173424,
      "name": "_raw_spin_rq_lock_irqsave",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071580233504,
      "name": "_raw_spin_rq_lock_irqsave",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071580386928,
      "name": "_raw_spin_rq_lock_irqsave",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate ❓</summary>

```c
long unsigned int _raw_spin_rq_lock_irqsave(struct rq * rq)
```

```json
{
  "name": "_raw_spin_rq_lock_irqsave",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580219792,
      "name": "_raw_spin_rq_lock_irqsave",
      "external": false,
      "loc": "kernel/sched/sched.h:1400",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_mm_cid_after_execve",
        "kernel/sched/core.c:sched_mm_cid_before_execve",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:balance_push_set",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:resched_cpu"
      ]
    },
    {
      "addr": 18446744071580281344,
      "name": "_raw_spin_rq_lock_irqsave",
      "external": false,
      "loc": "kernel/sched/sched.h:1400",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_idle",
        "kernel/sched/fair.c:__sched_group_set_shares",
        "kernel/sched/fair.c:unregister_fair_sched_group",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:distribute_cfs_runtime",
        "kernel/sched/fair.c:distribute_cfs_runtime"
      ]
    },
    {
      "addr": 18446744071580443536,
      "name": "_raw_spin_rq_lock_irqsave",
      "external": false,
      "loc": "kernel/sched/sched.h:1400",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:rq_attach_root",
        "kernel/sched/build_utility.c:print_cfs_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580219792,
      "name": "_raw_spin_rq_lock_irqsave",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071580281344,
      "name": "_raw_spin_rq_lock_irqsave",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071580443536,
      "name": "_raw_spin_rq_lock_irqsave",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
long unsigned int _raw_spin_rq_lock_irqsave(struct rq * rq)
```
</details>
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
