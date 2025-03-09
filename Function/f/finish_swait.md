# Function: <code>finish_swait</code>

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
void finish_swait(struct swait_queue_head * q, struct swait_queue * wait)
```

```json
{
  "name": "finish_swait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579661552,
      "name": "finish_swait",
      "external": true,
      "loc": "kernel/sched/swait.c:111",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579661552,
      "name": "finish_swait",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void finish_swait(struct swait_queue_head * q, struct swait_queue * wait)
```

```json
{
  "name": "finish_swait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579685824,
      "name": "finish_swait",
      "external": true,
      "loc": "kernel/sched/swait.c:111",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "drivers/base/firmware_class.c:__fw_state_wait_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579685824,
      "name": "finish_swait",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void finish_swait(struct swait_queue_head * q, struct swait_queue * wait)
```

```json
{
  "name": "finish_swait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579672000,
      "name": "finish_swait",
      "external": true,
      "loc": "kernel/sched/swait.c:111",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579672000,
      "name": "finish_swait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void finish_swait(struct swait_queue_head * q, struct swait_queue * wait)
```

```json
{
  "name": "finish_swait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579702752,
      "name": "finish_swait",
      "external": true,
      "loc": "kernel/sched/swait.c:106",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579702752,
      "name": "finish_swait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void finish_swait(struct swait_queue_head * q, struct swait_queue * wait)
```

```json
{
  "name": "finish_swait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579737072,
      "name": "finish_swait",
      "external": true,
      "loc": "kernel/sched/swait.c:108",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579737072,
      "name": "finish_swait",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void finish_swait(struct swait_queue_head * q, struct swait_queue * wait)
```

```json
{
  "name": "finish_swait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579776896,
      "name": "finish_swait",
      "external": true,
      "loc": "kernel/sched/swait.c:120",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579776896,
      "name": "finish_swait",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void finish_swait(struct swait_queue_head * q, struct swait_queue * wait)
```

```json
{
  "name": "finish_swait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579804336,
      "name": "finish_swait",
      "external": true,
      "loc": "kernel/sched/swait.c:120",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/rcu/tree.c:synchronize_sched_expedited_wait",
        "kernel/rcu/tree.c:synchronize_sched_expedited_wait",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579804336,
      "name": "finish_swait",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void finish_swait(struct swait_queue_head * q, struct swait_queue * wait)
```

```json
{
  "name": "finish_swait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579851904,
      "name": "finish_swait",
      "external": true,
      "loc": "kernel/sched/swait.c:120",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/rcu/tree.c:synchronize_sched_expedited_wait",
        "kernel/rcu/tree.c:synchronize_sched_expedited_wait",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851904,
      "name": "finish_swait",
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
void finish_swait(struct swait_queue_head * q, struct swait_queue * wait)
```

```json
{
  "name": "finish_swait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579890784,
      "name": "finish_swait",
      "external": true,
      "loc": "kernel/sched/swait.c:133",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule",
        "kernel/power/suspend.c:s2idle_enter",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_fqs_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579890784,
      "name": "finish_swait",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void finish_swait(struct swait_queue_head * q, struct swait_queue * wait)
```

```json
{
  "name": "finish_swait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579885408,
      "name": "finish_swait",
      "external": true,
      "loc": "kernel/sched/swait.c:133",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule",
        "kernel/power/suspend.c:s2idle_enter",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_fqs_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579885408,
      "name": "finish_swait",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void finish_swait(struct swait_queue_head * q, struct swait_queue * wait)
```

```json
{
  "name": "finish_swait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579894592,
      "name": "finish_swait",
      "external": true,
      "loc": "kernel/sched/swait.c:133",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_fqs_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579894592,
      "name": "finish_swait",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void finish_swait(struct swait_queue_head * q, struct swait_queue * wait)
```

```json
{
  "name": "finish_swait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580009408,
      "name": "finish_swait",
      "external": true,
      "loc": "kernel/sched/swait.c:133",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_fqs_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580009408,
      "name": "finish_swait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void finish_swait(struct swait_queue_head * q, struct swait_queue * wait)
```

```json
{
  "name": "finish_swait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580137392,
      "name": "finish_swait",
      "external": true,
      "loc": "kernel/sched/swait.c:132",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_fqs_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580137392,
      "name": "finish_swait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void finish_swait(struct swait_queue_head * q, struct swait_queue * wait)
```

```json
{
  "name": "finish_swait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580312000,
      "name": "finish_swait",
      "external": true,
      "loc": "kernel/sched/swait.c:132",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_fqs_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580312000,
      "name": "finish_swait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void finish_swait(struct swait_queue_head * q, struct swait_queue * wait)
```

```json
{
  "name": "finish_swait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580378672,
      "name": "finish_swait",
      "external": true,
      "loc": "kernel/sched/swait.c:132",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_fqs_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580378672,
      "name": "finish_swait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void finish_swait(struct swait_queue_head * q, struct swait_queue * wait)
```

```json
{
  "name": "finish_swait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580436656,
      "name": "finish_swait",
      "external": true,
      "loc": "kernel/sched/swait.c:132",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/rcu/tree.c:rcu_nocb_rdp_offload",
        "kernel/rcu/tree.c:rcu_nocb_rdp_deoffload",
        "kernel/rcu/tree.c:nocb_cb_wait",
        "kernel/rcu/tree.c:nocb_gp_wait",
        "kernel/rcu/tree.c:nocb_gp_wait",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_fqs_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580436656,
      "name": "finish_swait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void finish_swait(struct swait_queue_head * q, struct swait_queue * wait)
```

```json
{
  "name": "finish_swait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491046880,
      "name": "finish_swait",
      "external": true,
      "loc": "kernel/sched/swait.c:120",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/kvm_main.c:kvm_vcpu_block",
        "virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/rcu/tree.c:synchronize_sched_expedited_wait",
        "kernel/rcu/tree.c:synchronize_sched_expedited_wait",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491046880,
      "name": "finish_swait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void finish_swait(struct swait_queue_head * q, struct swait_queue * wait)
```

```json
{
  "name": "finish_swait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225052860,
      "name": "finish_swait",
      "external": true,
      "loc": "kernel/sched/swait.c:120",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/rcu/tree.c:synchronize_sched_expedited_wait",
        "kernel/rcu/tree.c:synchronize_sched_expedited_wait",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225052860,
      "name": "finish_swait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void finish_swait(struct swait_queue_head * q, struct swait_queue * wait)
```

```json
{
  "name": "finish_swait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283922960,
      "name": "finish_swait",
      "external": true,
      "loc": "kernel/sched/swait.c:120",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/rcu/tree.c:synchronize_sched_expedited_wait",
        "kernel/rcu/tree.c:synchronize_sched_expedited_wait",
        "kernel/rcu/tree.c:synchronize_sched_expedited_wait",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283922960,
      "name": "finish_swait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void finish_swait(struct swait_queue_head * q, struct swait_queue * wait)
```

```json
{
  "name": "finish_swait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271643532,
      "name": "finish_swait",
      "external": true,
      "loc": "kernel/sched/swait.c:120",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_sched_expedited_wait",
        "kernel/rcu/tree.c:synchronize_sched_expedited_wait",
        "kernel/rcu/tree.c:synchronize_sched_expedited_wait",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271643532,
      "name": "finish_swait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void finish_swait(struct swait_queue_head * q, struct swait_queue * wait)
```

```json
{
  "name": "finish_swait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579824256,
      "name": "finish_swait",
      "external": true,
      "loc": "kernel/sched/swait.c:120",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/rcu/tree.c:synchronize_sched_expedited_wait",
        "kernel/rcu/tree.c:synchronize_sched_expedited_wait",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579824256,
      "name": "finish_swait",
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
void finish_swait(struct swait_queue_head * q, struct swait_queue * wait)
```

```json
{
  "name": "finish_swait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579758848,
      "name": "finish_swait",
      "external": true,
      "loc": "kernel/sched/swait.c:120",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/rcu/tree.c:rcu_nocb_cb_kthread",
        "kernel/rcu/tree.c:nocb_gp_wait",
        "kernel/rcu/tree.c:synchronize_sched_expedited_wait",
        "kernel/rcu/tree.c:synchronize_sched_expedited_wait",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579758848,
      "name": "finish_swait",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void finish_swait(struct swait_queue_head * q, struct swait_queue * wait)
```

```json
{
  "name": "finish_swait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579812272,
      "name": "finish_swait",
      "external": true,
      "loc": "kernel/sched/swait.c:120",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/rcu/tree.c:synchronize_sched_expedited_wait",
        "kernel/rcu/tree.c:synchronize_sched_expedited_wait",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579812272,
      "name": "finish_swait",
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
void finish_swait(struct swait_queue_head * q, struct swait_queue * wait)
```

```json
{
  "name": "finish_swait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579857408,
      "name": "finish_swait",
      "external": true,
      "loc": "kernel/sched/swait.c:120",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_async_pf_task_wait",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/rcu/tree.c:synchronize_sched_expedited_wait",
        "kernel/rcu/tree.c:synchronize_sched_expedited_wait",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579857408,
      "name": "finish_swait",
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
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void finish_swait(struct swait_queue_head * q, struct swait_queue * wait)
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
