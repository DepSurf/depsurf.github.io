# Function: <code>request_percpu_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int request_percpu_irq(unsigned int irq, irq_handler_t handler, const char * devname, void * dev_id)
```

```json
{
  "name": "request_percpu_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579750208,
      "name": "request_percpu_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1886",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579750208,
      "name": "request_percpu_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int request_percpu_irq(unsigned int irq, irq_handler_t handler, const char * devname, void * dev_id)
```

```json
{
  "name": "request_percpu_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579772560,
      "name": "request_percpu_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1971",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579772560,
      "name": "request_percpu_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
int request_percpu_irq(unsigned int irq, irq_handler_t handler, const char * devname, void * dev_id)
```

```json
{
  "name": "request_percpu_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579799472,
      "name": "request_percpu_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:1971",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579799472,
      "name": "request_percpu_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "request_percpu_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588969362,
      "name": "request_percpu_irq",
      "external": false,
      "loc": "include/linux/interrupt.h:181",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "request_percpu_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589679432,
      "name": "request_percpu_irq",
      "external": false,
      "loc": "include/linux/interrupt.h:185",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_stimer_alloc"
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
  "name": "request_percpu_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591184504,
      "name": "request_percpu_irq",
      "external": false,
      "loc": "include/linux/interrupt.h:185",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_stimer_alloc"
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
  "name": "request_percpu_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592911048,
      "name": "request_percpu_irq",
      "external": false,
      "loc": "include/linux/interrupt.h:185",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_stimer_alloc"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "request_percpu_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593350280,
      "name": "request_percpu_irq",
      "external": false,
      "loc": "include/linux/interrupt.h:185",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_stimer_alloc"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "request_percpu_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594104280,
      "name": "request_percpu_irq",
      "external": false,
      "loc": "include/linux/interrupt.h:185",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_stimer_alloc"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "request_percpu_irq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490542132,
      "name": "request_percpu_irq",
      "external": false,
      "loc": "include/linux/interrupt.h:164",
      "file": "virt/kvm/arm/vgic/vgic-init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/vgic/vgic-init.c:kvm_vgic_hyp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490605020,
      "name": "request_percpu_irq",
      "external": false,
      "loc": "include/linux/interrupt.h:164",
      "file": "virt/kvm/arm/arch_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/arch_timer.c:kvm_timer_hyp_init",
        "virt/kvm/arm/arch_timer.c:kvm_timer_hyp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510843160,
      "name": "request_percpu_irq",
      "external": false,
      "loc": "include/linux/interrupt.h:164",
      "file": "arch/arm/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/xen/enlighten.c:xen_guest_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511290988,
      "name": "request_percpu_irq",
      "external": false,
      "loc": "include/linux/interrupt.h:164",
      "file": "drivers/clocksource/timer-of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-of.c:timer_of_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511294780,
      "name": "request_percpu_irq",
      "external": false,
      "loc": "include/linux/interrupt.h:164",
      "file": "drivers/clocksource/arm_arch_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/arm_arch_timer.c:arch_timer_register",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_register",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_register",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501777724,
      "name": "request_percpu_irq",
      "external": false,
      "loc": "include/linux/interrupt.h:164",
      "file": "drivers/perf/arm_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm_pmu.c:armpmu_request_irq"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "request_percpu_irq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243269592,
      "name": "request_percpu_irq",
      "external": false,
      "loc": "include/linux/interrupt.h:164",
      "file": "arch/arm/kernel/smp_twd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/smp_twd.c:twd_local_timer_of_register"
      ],
      "caller_func": []
    },
    {
      "addr": 3243942988,
      "name": "request_percpu_irq",
      "external": false,
      "loc": "include/linux/interrupt.h:164",
      "file": "drivers/clocksource/timer-of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-of.c:timer_of_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3243947280,
      "name": "request_percpu_irq",
      "external": false,
      "loc": "include/linux/interrupt.h:164",
      "file": "drivers/clocksource/timer-armada-370-xp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_timer_common_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3243950356,
      "name": "request_percpu_irq",
      "external": false,
      "loc": "include/linux/interrupt.h:164",
      "file": "drivers/clocksource/exynos_mct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/exynos_mct.c:mct_init_dt"
      ],
      "caller_func": []
    },
    {
      "addr": 3243951500,
      "name": "request_percpu_irq",
      "external": false,
      "loc": "include/linux/interrupt.h:164",
      "file": "drivers/clocksource/timer-qcom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-qcom.c:msm_dt_timer_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3243954628,
      "name": "request_percpu_irq",
      "external": false,
      "loc": "include/linux/interrupt.h:164",
      "file": "drivers/clocksource/arm_arch_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/arm_arch_timer.c:arch_timer_of_init",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_of_init",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_of_init",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_of_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3243956644,
      "name": "request_percpu_irq",
      "external": false,
      "loc": "include/linux/interrupt.h:164",
      "file": "drivers/clocksource/arm_global_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/arm_global_timer.c:global_timer_of_register"
      ],
      "caller_func": []
    },
    {
      "addr": 3234327260,
      "name": "request_percpu_irq",
      "external": false,
      "loc": "include/linux/interrupt.h:164",
      "file": "drivers/perf/arm_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm_pmu.c:armpmu_request_irq"
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "request_percpu_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270836458,
      "name": "request_percpu_irq",
      "external": false,
      "loc": "include/linux/interrupt.h:164",
      "file": "drivers/clocksource/timer-of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-of.c:timer_of_init"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int request_percpu_irq(unsigned int irq, irq_handler_t handler, const char * devname, void * dev_id)
```
</details>
</li>
</ul>
