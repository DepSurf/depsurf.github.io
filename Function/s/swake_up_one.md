# Function: <code>swake_up_one</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void swake_up_one(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579777088,
      "name": "swake_up_one",
      "external": true,
      "loc": "kernel/sched/swait.c:35",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:s2idle_wake",
        "kernel/rcu/tree.c:rcu_report_exp_cpu_mult",
        "kernel/rcu/tree.c:rcu_gp_kthread_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579777088,
      "name": "swake_up_one",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void swake_up_one(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579804768,
      "name": "swake_up_one",
      "external": true,
      "loc": "kernel/sched/swait.c:35",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:s2idle_wake",
        "kernel/rcu/tree.c:rcu_report_exp_cpu_mult"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579804768,
      "name": "swake_up_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void swake_up_one(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579852336,
      "name": "swake_up_one",
      "external": true,
      "loc": "kernel/sched/swait.c:35",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:s2idle_wake",
        "kernel/rcu/tree.c:rcu_report_exp_cpu_mult"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579852336,
      "name": "swake_up_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void swake_up_one(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579891136,
      "name": "swake_up_one",
      "external": true,
      "loc": "kernel/sched/swait.c:48",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wake",
        "arch/x86/kernel/kvm.c:apf_task_wake_all",
        "kernel/power/suspend.c:s2idle_wake",
        "kernel/rcu/tree.c:__rcu_report_exp_rnp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579891136,
      "name": "swake_up_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void swake_up_one(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579885520,
      "name": "swake_up_one",
      "external": true,
      "loc": "kernel/sched/swait.c:48",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wake",
        "arch/x86/kernel/kvm.c:apf_task_wake_all",
        "kernel/power/suspend.c:s2idle_wake",
        "kernel/rcu/tree.c:__rcu_report_exp_rnp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579885520,
      "name": "swake_up_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void swake_up_one(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579894704,
      "name": "swake_up_one",
      "external": true,
      "loc": "kernel/sched/swait.c:48",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wake",
        "arch/x86/kernel/kvm.c:apf_task_wake_all",
        "kernel/power/suspend.c:s2idle_wake",
        "kernel/rcu/tree.c:rcu_report_exp_cpu_mult"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579894704,
      "name": "swake_up_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void swake_up_one(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580009520,
      "name": "swake_up_one",
      "external": true,
      "loc": "kernel/sched/swait.c:48",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wake",
        "arch/x86/kernel/kvm.c:apf_task_wake_all",
        "kernel/power/suspend.c:s2idle_wake",
        "kernel/rcu/tree.c:rcu_report_exp_cpu_mult"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580009520,
      "name": "swake_up_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void swake_up_one(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580163744,
      "name": "swake_up_one",
      "external": true,
      "loc": "kernel/sched/swait.c:47",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wake",
        "arch/x86/kernel/kvm.c:apf_task_wake_all",
        "arch/x86/kernel/kvm.c:apf_task_wake_all",
        "arch/x86/kernel/kvm.c:apf_task_wake_all",
        "kernel/power/suspend.c:s2idle_wake",
        "kernel/rcu/tree.c:__rcu_report_exp_rnp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580163744,
      "name": "swake_up_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void swake_up_one(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580340000,
      "name": "swake_up_one",
      "external": true,
      "loc": "kernel/sched/swait.c:47",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wake",
        "arch/x86/kernel/kvm.c:apf_task_wake_all",
        "arch/x86/kernel/kvm.c:apf_task_wake_all",
        "arch/x86/kernel/kvm.c:apf_task_wake_all",
        "kernel/power/suspend.c:s2idle_wake",
        "kernel/rcu/tree.c:__rcu_report_exp_rnp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580340000,
      "name": "swake_up_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void swake_up_one(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580407872,
      "name": "swake_up_one",
      "external": true,
      "loc": "kernel/sched/swait.c:47",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wake",
        "arch/x86/kernel/kvm.c:apf_task_wake_all",
        "arch/x86/kernel/kvm.c:apf_task_wake_all",
        "arch/x86/kernel/kvm.c:apf_task_wake_all",
        "kernel/power/suspend.c:s2idle_wake",
        "kernel/rcu/tree.c:__rcu_report_exp_rnp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580407872,
      "name": "swake_up_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void swake_up_one(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580465808,
      "name": "swake_up_one",
      "external": true,
      "loc": "kernel/sched/swait.c:47",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wake",
        "arch/x86/kernel/kvm.c:apf_task_wake_all",
        "arch/x86/kernel/kvm.c:apf_task_wake_all",
        "arch/x86/kernel/kvm.c:apf_task_wake_all",
        "kernel/power/suspend.c:s2idle_wake",
        "kernel/rcu/tree.c:rdp_offload_toggle",
        "kernel/rcu/tree.c:nocb_cb_wait",
        "kernel/rcu/tree.c:nocb_gp_wait",
        "kernel/rcu/tree.c:nocb_gp_wait",
        "kernel/rcu/tree.c:swake_up_one_online_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580465808,
      "name": "swake_up_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void swake_up_one(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491046424,
      "name": "swake_up_one",
      "external": true,
      "loc": "kernel/sched/swait.c:35",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/kvm_main.c:kvm_vcpu_kick",
        "virt/kvm/kvm_main.c:kvm_make_vcpus_request_mask",
        "virt/kvm/arm/arm.c:kvm_arm_resume_guest",
        "kernel/power/suspend.c:s2idle_wake",
        "kernel/rcu/tree.c:rcu_report_exp_cpu_mult"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491046424,
      "name": "swake_up_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void swake_up_one(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225053660,
      "name": "swake_up_one",
      "external": true,
      "loc": "kernel/sched/swait.c:35",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:s2idle_wake",
        "kernel/rcu/tree.c:rcu_report_exp_cpu_mult"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225053660,
      "name": "swake_up_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void swake_up_one(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283923600,
      "name": "swake_up_one",
      "external": true,
      "loc": "kernel/sched/swait.c:35",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:s2idle_wake",
        "kernel/rcu/tree.c:rcu_report_exp_cpu_mult"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283923600,
      "name": "swake_up_one",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void swake_up_one(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271643912,
      "name": "swake_up_one",
      "external": true,
      "loc": "kernel/sched/swait.c:35",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_report_exp_cpu_mult"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271643912,
      "name": "swake_up_one",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void swake_up_one(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579824688,
      "name": "swake_up_one",
      "external": true,
      "loc": "kernel/sched/swait.c:35",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_report_exp_cpu_mult"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579824688,
      "name": "swake_up_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void swake_up_one(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579759280,
      "name": "swake_up_one",
      "external": true,
      "loc": "kernel/sched/swait.c:35",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:s2idle_wake",
        "kernel/rcu/tree.c:nocb_gp_wait",
        "kernel/rcu/tree.c:rcu_report_exp_cpu_mult"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579759280,
      "name": "swake_up_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void swake_up_one(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579812704,
      "name": "swake_up_one",
      "external": true,
      "loc": "kernel/sched/swait.c:35",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:s2idle_wake",
        "kernel/rcu/tree.c:rcu_report_exp_cpu_mult"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579812704,
      "name": "swake_up_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void swake_up_one(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579858064,
      "name": "swake_up_one",
      "external": true,
      "loc": "kernel/sched/swait.c:35",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:s2idle_wake",
        "kernel/rcu/tree.c:__rcu_report_exp_rnp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579858064,
      "name": "swake_up_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void swake_up_one(struct swait_queue_head * q)
```
</details>
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
