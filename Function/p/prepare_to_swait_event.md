# Function: <code>prepare_to_swait_event</code>

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
long int prepare_to_swait_event(struct swait_queue_head * q, struct swait_queue * wait, int state)
```

```json
{
  "name": "prepare_to_swait_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579661792,
      "name": "prepare_to_swait_event",
      "external": true,
      "loc": "kernel/sched/swait.c:93",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579661792,
      "name": "prepare_to_swait_event",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
long int prepare_to_swait_event(struct swait_queue_head * q, struct swait_queue * wait, int state)
```

```json
{
  "name": "prepare_to_swait_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579686064,
      "name": "prepare_to_swait_event",
      "external": true,
      "loc": "kernel/sched/swait.c:93",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "drivers/base/firmware_class.c:__fw_state_wait_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579686064,
      "name": "prepare_to_swait_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
long int prepare_to_swait_event(struct swait_queue_head * q, struct swait_queue * wait, int state)
```

```json
{
  "name": "prepare_to_swait_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579672112,
      "name": "prepare_to_swait_event",
      "external": true,
      "loc": "kernel/sched/swait.c:93",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579672112,
      "name": "prepare_to_swait_event",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
long int prepare_to_swait_event(struct swait_queue_head * q, struct swait_queue * wait, int state)
```

```json
{
  "name": "prepare_to_swait_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579702864,
      "name": "prepare_to_swait_event",
      "external": true,
      "loc": "kernel/sched/swait.c:88",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579702864,
      "name": "prepare_to_swait_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
long int prepare_to_swait_event(struct swait_queue_head * q, struct swait_queue * wait, int state)
```

```json
{
  "name": "prepare_to_swait_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579736992,
      "name": "prepare_to_swait_event",
      "external": true,
      "loc": "kernel/sched/swait.c:90",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579736992,
      "name": "prepare_to_swait_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
long int prepare_to_swait_event(struct swait_queue_head * q, struct swait_queue * wait, int state)
```

```json
{
  "name": "prepare_to_swait_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579776672,
      "name": "prepare_to_swait_event",
      "external": true,
      "loc": "kernel/sched/swait.c:90",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579776672,
      "name": "prepare_to_swait_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
long int prepare_to_swait_event(struct swait_queue_head * q, struct swait_queue * wait, int state)
```

```json
{
  "name": "prepare_to_swait_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579804448,
      "name": "prepare_to_swait_event",
      "external": true,
      "loc": "kernel/sched/swait.c:90",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 18446744071579804448,
      "name": "prepare_to_swait_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
long int prepare_to_swait_event(struct swait_queue_head * q, struct swait_queue * wait, int state)
```

```json
{
  "name": "prepare_to_swait_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579852016,
      "name": "prepare_to_swait_event",
      "external": true,
      "loc": "kernel/sched/swait.c:90",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 18446744071579852016,
      "name": "prepare_to_swait_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
long int prepare_to_swait_event(struct swait_queue_head * q, struct swait_queue * wait, int state)
```

```json
{
  "name": "prepare_to_swait_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579890896,
      "name": "prepare_to_swait_event",
      "external": true,
      "loc": "kernel/sched/swait.c:103",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:s2idle_enter",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_fqs_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579890896,
      "name": "prepare_to_swait_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
long int prepare_to_swait_event(struct swait_queue_head * q, struct swait_queue * wait, int state)
```

```json
{
  "name": "prepare_to_swait_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579885616,
      "name": "prepare_to_swait_event",
      "external": true,
      "loc": "kernel/sched/swait.c:103",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:s2idle_enter",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_fqs_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579885616,
      "name": "prepare_to_swait_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
long int prepare_to_swait_event(struct swait_queue_head * q, struct swait_queue * wait, int state)
```

```json
{
  "name": "prepare_to_swait_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579894800,
      "name": "prepare_to_swait_event",
      "external": true,
      "loc": "kernel/sched/swait.c:103",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_fqs_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579894800,
      "name": "prepare_to_swait_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
long int prepare_to_swait_event(struct swait_queue_head * q, struct swait_queue * wait, int state)
```

```json
{
  "name": "prepare_to_swait_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580009616,
      "name": "prepare_to_swait_event",
      "external": true,
      "loc": "kernel/sched/swait.c:103",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_fqs_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580009616,
      "name": "prepare_to_swait_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
long int prepare_to_swait_event(struct swait_queue_head * q, struct swait_queue * wait, int state)
```

```json
{
  "name": "prepare_to_swait_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580165680,
      "name": "prepare_to_swait_event",
      "external": true,
      "loc": "kernel/sched/swait.c:102",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_fqs_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580165680,
      "name": "prepare_to_swait_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
long int prepare_to_swait_event(struct swait_queue_head * q, struct swait_queue * wait, int state)
```

```json
{
  "name": "prepare_to_swait_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580352096,
      "name": "prepare_to_swait_event",
      "external": true,
      "loc": "kernel/sched/swait.c:102",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_fqs_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580352096,
      "name": "prepare_to_swait_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
long int prepare_to_swait_event(struct swait_queue_head * q, struct swait_queue * wait, int state)
```

```json
{
  "name": "prepare_to_swait_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580416800,
      "name": "prepare_to_swait_event",
      "external": true,
      "loc": "kernel/sched/swait.c:102",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_fqs_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580416800,
      "name": "prepare_to_swait_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
long int prepare_to_swait_event(struct swait_queue_head * q, struct swait_queue * wait, int state)
```

```json
{
  "name": "prepare_to_swait_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580471440,
      "name": "prepare_to_swait_event",
      "external": true,
      "loc": "kernel/sched/swait.c:102",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/rcu/tree.c:rcu_nocb_rdp_offload",
        "kernel/rcu/tree.c:rcu_nocb_rdp_deoffload",
        "kernel/rcu/tree.c:nocb_cb_wait",
        "kernel/rcu/tree.c:nocb_gp_wait",
        "kernel/rcu/tree.c:nocb_gp_wait",
        "kernel/rcu/tree.c:nocb_gp_wait",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_fqs_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580471440,
      "name": "prepare_to_swait_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
long int prepare_to_swait_event(struct swait_queue_head * q, struct swait_queue * wait, int state)
```

```json
{
  "name": "prepare_to_swait_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491045672,
      "name": "prepare_to_swait_event",
      "external": true,
      "loc": "kernel/sched/swait.c:90",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 18446603336491045672,
      "name": "prepare_to_swait_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
long int prepare_to_swait_event(struct swait_queue_head * q, struct swait_queue * wait, int state)
```

```json
{
  "name": "prepare_to_swait_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225053264,
      "name": "prepare_to_swait_event",
      "external": true,
      "loc": "kernel/sched/swait.c:90",
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
      "addr": 3225053264,
      "name": "prepare_to_swait_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
long int prepare_to_swait_event(struct swait_queue_head * q, struct swait_queue * wait, int state)
```

```json
{
  "name": "prepare_to_swait_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283923136,
      "name": "prepare_to_swait_event",
      "external": true,
      "loc": "kernel/sched/swait.c:90",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/rcu/tree.c:synchronize_sched_expedited_wait",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283923136,
      "name": "prepare_to_swait_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
long int prepare_to_swait_event(struct swait_queue_head * q, struct swait_queue * wait, int state)
```

```json
{
  "name": "prepare_to_swait_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271643634,
      "name": "prepare_to_swait_event",
      "external": true,
      "loc": "kernel/sched/swait.c:90",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_sched_expedited_wait",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271643634,
      "name": "prepare_to_swait_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
long int prepare_to_swait_event(struct swait_queue_head * q, struct swait_queue * wait, int state)
```

```json
{
  "name": "prepare_to_swait_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579824368,
      "name": "prepare_to_swait_event",
      "external": true,
      "loc": "kernel/sched/swait.c:90",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_sched_expedited_wait",
        "kernel/rcu/tree.c:synchronize_sched_expedited_wait",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579824368,
      "name": "prepare_to_swait_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
long int prepare_to_swait_event(struct swait_queue_head * q, struct swait_queue * wait, int state)
```

```json
{
  "name": "prepare_to_swait_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579758960,
      "name": "prepare_to_swait_event",
      "external": true,
      "loc": "kernel/sched/swait.c:90",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/rcu/tree.c:rcu_nocb_cb_kthread",
        "kernel/rcu/tree.c:nocb_gp_wait",
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
      "addr": 18446744071579758960,
      "name": "prepare_to_swait_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
long int prepare_to_swait_event(struct swait_queue_head * q, struct swait_queue * wait, int state)
```

```json
{
  "name": "prepare_to_swait_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579812384,
      "name": "prepare_to_swait_event",
      "external": true,
      "loc": "kernel/sched/swait.c:90",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 18446744071579812384,
      "name": "prepare_to_swait_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
long int prepare_to_swait_event(struct swait_queue_head * q, struct swait_queue * wait, int state)
```

```json
{
  "name": "prepare_to_swait_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579857744,
      "name": "prepare_to_swait_event",
      "external": true,
      "loc": "kernel/sched/swait.c:90",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 18446744071579857744,
      "name": "prepare_to_swait_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
long int prepare_to_swait_event(struct swait_queue_head * q, struct swait_queue * wait, int state)
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
