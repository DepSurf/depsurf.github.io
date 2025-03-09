# Function: <code>smp_send_reschedule</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_reschedule",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579253722,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:126",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579519396,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:126",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:kick_process",
        "kernel/sched/core.c:resched_curr",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wake_up_if_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579625275,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:126",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:trigger_load_balance"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_reschedule",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579252721,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:115",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579560284,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:115",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:kick_process",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579639580,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:115",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:trigger_load_balance"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_reschedule",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579266209,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:113",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579585080,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:113",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:kick_process",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579664170,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:113",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:trigger_load_balance"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_reschedule",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579262822,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:113",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579568966,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:113",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:kick_process",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579638739,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:113",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:trigger_load_balance"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_reschedule",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579278950,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:114",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579598738,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:114",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:kick_process",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579669301,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:114",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:trigger_load_balance"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_reschedule",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579290342,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:114",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579630325,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:114",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:kick_process",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579651142,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:114",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:kick_ilb"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_reschedule",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579315190,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:114",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579668066,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:114",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:kick_process",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579688982,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:114",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:kick_ilb"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_reschedule",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579329734,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:115",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579699634,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:115",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:kick_process",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579722793,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:115",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:kick_ilb"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_reschedule",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579333846,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:115",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579740513,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:115",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:kick_process",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579765545,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:115",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:kick_ilb"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_reschedule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579779039,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:115",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:kick_process",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_reschedule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579769366,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:105",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:kick_process",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_reschedule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579777062,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:105",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:kick_process",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_reschedule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579870197,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:105",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:kick_process",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_reschedule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579928316,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:112",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:kick_process",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_reschedule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580079772,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:101",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:kick_process",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr"
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
void smp_send_reschedule(int cpu)
```

```json
{
  "name": "smp_send_reschedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490274376,
      "name": "smp_send_reschedule",
      "external": true,
      "loc": "arch/arm64/kernel/smp.c:946",
      "file": "arch/arm64/kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/kvm_main.c:kvm_vcpu_kick",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:kick_process",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr",
        "kernel/sched/core.c:resched_curr",
        "kernel/sched/fair.c:kick_ilb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490274376,
      "name": "smp_send_reschedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
void smp_send_reschedule(int cpu)
```

```json
{
  "name": "smp_send_reschedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224450908,
      "name": "smp_send_reschedule",
      "external": true,
      "loc": "arch/arm/kernel/smp.c:703",
      "file": "arch/arm/kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:kick_process",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr",
        "kernel/sched/fair.c:kick_ilb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224450908,
      "name": "smp_send_reschedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
void smp_send_reschedule(int cpu)
```

```json
{
  "name": "smp_send_reschedule",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055282511236,
      "name": "smp_send_reschedule",
      "external": true,
      "loc": "arch/powerpc/kernel/smp.c:330",
      "file": "arch/powerpc/kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/smp.c:smp_generic_kick_cpu"
      ],
      "caller_func": [
        "arch/powerpc/platforms/powernv/subcore.c:cpu_update_split_mode",
        "arch/powerpc/platforms/powernv/subcore.c:cpu_do_split",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:kick_process",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr",
        "kernel/sched/fair.c:kick_ilb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282510032,
      "name": "smp_send_reschedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void smp_send_reschedule(int cpu)
```

```json
{
  "name": "smp_send_reschedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271350628,
      "name": "smp_send_reschedule",
      "external": true,
      "loc": "arch/riscv/kernel/smp.c:207",
      "file": "arch/riscv/kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:kick_process",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr",
        "kernel/sched/fair.c:kick_ilb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271350628,
      "name": "smp_send_reschedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_reschedule",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579329750,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:115",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579717137,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:115",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:kick_process",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579741401,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:115",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:kick_ilb"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_reschedule",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579264150,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:115",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579645026,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:115",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:kick_process",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579671785,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:115",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:kick_ilb"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_reschedule",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579329670,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:115",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579704402,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:115",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:kick_process",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579725913,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:115",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:kick_ilb"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smp_send_reschedule",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579337942,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:115",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579747877,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:115",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wake_up_if_idle",
        "kernel/sched/core.c:kick_process",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579773449,
      "name": "smp_send_reschedule",
      "external": false,
      "loc": "arch/x86/include/asm/smp.h:115",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:kick_ilb"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void smp_send_reschedule(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void smp_send_reschedule(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void smp_send_reschedule(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void smp_send_reschedule(int cpu)
```
</details>
</li>
</ul>
