# Function: <code>irq_enter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void irq_enter()
```

```json
{
  "name": "irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579392928,
      "name": "irq_enter",
      "external": true,
      "loc": "kernel/softirq.c:325",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_irq_work_interrupt",
        "arch/x86/kernel/irq.c:do_IRQ",
        "arch/x86/kernel/irq.c:smp_x86_platform_ipi",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi",
        "arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi",
        "arch/x86/kernel/irq_work.c:smp_irq_work_interrupt",
        "arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_trace_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt",
        "arch/x86/kernel/cpu/mcheck/threshold.c:smp_trace_threshold_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_trace_thermal_interrupt",
        "arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler",
        "arch/x86/kernel/smp.c:smp_reboot_interrupt",
        "arch/x86/kernel/smp.c:smp_trace_reschedule_interrupt",
        "arch/x86/kernel/smp.c:smp_trace_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_single_interrupt",
        "arch/x86/kernel/smp.c:smp_trace_call_function_single_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_trace_spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_error_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_trace_error_interrupt",
        "arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt",
        "kernel/sched/core.c:scheduler_ipi",
        "drivers/xen/events/events_base.c:xen_evtchn_do_upcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579392928,
      "name": "irq_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void irq_enter()
```

```json
{
  "name": "irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579404784,
      "name": "irq_enter",
      "external": true,
      "loc": "kernel/softirq.c:325",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_irq_work_interrupt",
        "arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi",
        "arch/x86/kernel/irq.c:smp_x86_platform_ipi",
        "arch/x86/kernel/irq.c:do_IRQ",
        "arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt",
        "arch/x86/kernel/irq_work.c:smp_irq_work_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_trace_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/threshold.c:smp_trace_threshold_interrupt",
        "arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_trace_thermal_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt",
        "arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler",
        "arch/x86/kernel/smp.c:smp_trace_call_function_single_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_single_interrupt",
        "arch/x86/kernel/smp.c:smp_trace_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_trace_reschedule_interrupt",
        "arch/x86/kernel/smp.c:smp_reboot_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_trace_error_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_error_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_trace_spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt",
        "arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt",
        "kernel/sched/core.c:scheduler_ipi",
        "drivers/xen/events/events_base.c:xen_evtchn_do_upcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579404784,
      "name": "irq_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void irq_enter()
```

```json
{
  "name": "irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579425088,
      "name": "irq_enter",
      "external": true,
      "loc": "kernel/softirq.c:336",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_irq_work_interrupt",
        "arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi",
        "arch/x86/kernel/irq.c:smp_x86_platform_ipi",
        "arch/x86/kernel/irq.c:do_IRQ",
        "arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt",
        "arch/x86/kernel/irq_work.c:smp_irq_work_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_trace_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/threshold.c:smp_trace_threshold_interrupt",
        "arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_trace_thermal_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt",
        "arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler",
        "arch/x86/kernel/smp.c:smp_trace_call_function_single_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_single_interrupt",
        "arch/x86/kernel/smp.c:smp_trace_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_trace_reschedule_interrupt",
        "arch/x86/kernel/smp.c:smp_reboot_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_trace_error_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_error_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_trace_spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt",
        "arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt",
        "kernel/sched/core.c:scheduler_ipi",
        "drivers/xen/events/events_base.c:xen_evtchn_do_upcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579425088,
      "name": "irq_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void irq_enter()
```

```json
{
  "name": "irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579412848,
      "name": "irq_enter",
      "external": true,
      "loc": "kernel/softirq.c:336",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_irq_work_interrupt",
        "arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi",
        "arch/x86/kernel/irq.c:smp_x86_platform_ipi",
        "arch/x86/kernel/irq.c:do_IRQ",
        "arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt",
        "arch/x86/kernel/irq_work.c:smp_irq_work_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_trace_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/threshold.c:smp_trace_threshold_interrupt",
        "arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_trace_thermal_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt",
        "arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler",
        "arch/x86/kernel/smp.c:smp_trace_call_function_single_interrupt",
        "arch/x86/kernel/smp.c:smp_trace_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_trace_reschedule_interrupt",
        "arch/x86/kernel/smp.c:smp_reboot_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_trace_error_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_error_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_trace_spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt",
        "arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt",
        "kernel/sched/core.c:scheduler_ipi",
        "drivers/xen/events/events_base.c:xen_evtchn_do_upcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579412848,
      "name": "irq_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void irq_enter()
```

```json
{
  "name": "irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579440704,
      "name": "irq_enter",
      "external": true,
      "loc": "kernel/softirq.c:337",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_irq_work_interrupt",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi",
        "arch/x86/kernel/irq.c:smp_x86_platform_ipi",
        "arch/x86/kernel/irq.c:do_IRQ",
        "arch/x86/kernel/irq_work.c:smp_irq_work_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt",
        "arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler",
        "arch/x86/kernel/smp.c:smp_call_function_single_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_reschedule_interrupt",
        "arch/x86/kernel/smp.c:smp_reboot_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_error_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt",
        "arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt",
        "kernel/sched/core.c:scheduler_ipi",
        "drivers/xen/events/events_base.c:xen_evtchn_do_upcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579440704,
      "name": "irq_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void irq_enter()
```

```json
{
  "name": "irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579455760,
      "name": "irq_enter",
      "external": true,
      "loc": "kernel/softirq.c:344",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_irq_work_interrupt",
        "arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi",
        "arch/x86/kernel/irq.c:smp_x86_platform_ipi",
        "arch/x86/kernel/irq.c:do_IRQ",
        "arch/x86/kernel/irq_work.c:smp_irq_work_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt",
        "arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler",
        "arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler",
        "arch/x86/kernel/smp.c:smp_call_function_single_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_reschedule_interrupt",
        "arch/x86/kernel/smp.c:smp_reboot_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_error_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt",
        "arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt",
        "kernel/sched/core.c:scheduler_ipi",
        "drivers/xen/events/events_base.c:xen_evtchn_do_upcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579455760,
      "name": "irq_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void irq_enter()
```

```json
{
  "name": "irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579489408,
      "name": "irq_enter",
      "external": true,
      "loc": "kernel/softirq.c:345",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_irq_work_interrupt",
        "arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi",
        "arch/x86/kernel/irq.c:smp_x86_platform_ipi",
        "arch/x86/kernel/irq.c:do_IRQ",
        "arch/x86/kernel/irq_work.c:smp_irq_work_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt",
        "arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler",
        "arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler",
        "arch/x86/kernel/smp.c:smp_call_function_single_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_reschedule_interrupt",
        "arch/x86/kernel/smp.c:smp_reboot_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_error_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt",
        "arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt",
        "kernel/sched/core.c:scheduler_ipi",
        "drivers/xen/events/events_base.c:xen_evtchn_do_upcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579489408,
      "name": "irq_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void irq_enter()
```

```json
{
  "name": "irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579507296,
      "name": "irq_enter",
      "external": true,
      "loc": "kernel/softirq.c:345",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_call_function_single_interrupt",
        "arch/x86/xen/smp.c:xen_call_function_interrupt",
        "arch/x86/xen/smp_pv.c:xen_irq_work_interrupt",
        "arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi",
        "arch/x86/kernel/irq.c:smp_x86_platform_ipi",
        "arch/x86/kernel/irq.c:do_IRQ",
        "arch/x86/kernel/irq_work.c:smp_irq_work_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt",
        "arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler",
        "arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler",
        "arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler",
        "arch/x86/kernel/smp.c:smp_call_function_single_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_reschedule_interrupt",
        "arch/x86/kernel/smp.c:smp_reboot_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_error_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt",
        "arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt",
        "kernel/sched/core.c:scheduler_ipi",
        "drivers/xen/events/events_base.c:xen_evtchn_do_upcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579507296,
      "name": "irq_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void irq_enter()
```

```json
{
  "name": "irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579533344,
      "name": "irq_enter",
      "external": true,
      "loc": "kernel/softirq.c:345",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_call_function_single_interrupt",
        "arch/x86/xen/smp.c:xen_call_function_interrupt",
        "arch/x86/xen/smp_pv.c:xen_irq_work_interrupt",
        "arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi",
        "arch/x86/kernel/irq.c:smp_x86_platform_ipi",
        "arch/x86/kernel/irq.c:do_IRQ",
        "arch/x86/kernel/irq_work.c:smp_irq_work_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt",
        "arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler",
        "arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler",
        "arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler",
        "arch/x86/kernel/smp.c:smp_call_function_single_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_reschedule_interrupt",
        "arch/x86/kernel/smp.c:smp_reboot_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_error_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt",
        "arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt",
        "kernel/sched/core.c:scheduler_ipi",
        "drivers/xen/events/events_base.c:xen_evtchn_do_upcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579533344,
      "name": "irq_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void irq_enter()
```

```json
{
  "name": "irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579564080,
      "name": "irq_enter",
      "external": true,
      "loc": "kernel/softirq.c:362",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_irq_work_interrupt",
        "drivers/xen/events/events_base.c:xen_evtchn_do_upcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579564080,
      "name": "irq_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void irq_enter()
```

```json
{
  "name": "irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579545536,
      "name": "irq_enter",
      "external": true,
      "loc": "kernel/softirq.c:391",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_irq_work_interrupt",
        "drivers/xen/events/events_base.c:xen_evtchn_do_upcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579545536,
      "name": "irq_enter",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void irq_enter()
```

```json
{
  "name": "irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579550128,
      "name": "irq_enter",
      "external": true,
      "loc": "kernel/softirq.c:608",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_irq_work_interrupt",
        "drivers/xen/events/events_base.c:xen_evtchn_do_upcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579550128,
      "name": "irq_enter",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void irq_enter()
```

```json
{
  "name": "irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579621424,
      "name": "irq_enter",
      "external": true,
      "loc": "kernel/softirq.c:607",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_irq_work_interrupt",
        "drivers/xen/events/events_base.c:xen_evtchn_do_upcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579621424,
      "name": "irq_enter",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void irq_enter()
```

```json
{
  "name": "irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579715936,
      "name": "irq_enter",
      "external": true,
      "loc": "kernel/softirq.c:621",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_evtchn_do_upcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579715936,
      "name": "irq_enter",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void irq_enter()
```

```json
{
  "name": "irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579842752,
      "name": "irq_enter",
      "external": true,
      "loc": "kernel/softirq.c:621",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_evtchn_do_upcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579842752,
      "name": "irq_enter",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void irq_enter()
```

```json
{
  "name": "irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579892752,
      "name": "irq_enter",
      "external": true,
      "loc": "kernel/softirq.c:603",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_evtchn_do_upcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579892752,
      "name": "irq_enter",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void irq_enter()
```

```json
{
  "name": "irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579931488,
      "name": "irq_enter",
      "external": true,
      "loc": "kernel/softirq.c:603",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579931488,
      "name": "irq_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void irq_enter()
```

```json
{
  "name": "irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490676464,
      "name": "irq_enter",
      "external": true,
      "loc": "kernel/softirq.c:345",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/smp.c:handle_IPI",
        "arch/arm64/kernel/smp.c:handle_IPI",
        "arch/arm64/kernel/smp.c:handle_IPI",
        "arch/arm64/kernel/smp.c:handle_IPI",
        "arch/arm64/kernel/smp.c:handle_IPI",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/irq/irqdesc.c:__handle_domain_irq",
        "drivers/xen/events/events_base.c:xen_evtchn_do_upcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490676464,
      "name": "irq_enter",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void irq_enter()
```

```json
{
  "name": "irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224747492,
      "name": "irq_enter",
      "external": true,
      "loc": "kernel/softirq.c:345",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/smp.c:handle_IPI",
        "arch/arm/kernel/smp.c:handle_IPI",
        "arch/arm/kernel/smp.c:handle_IPI",
        "arch/arm/kernel/smp.c:handle_IPI",
        "arch/arm/kernel/smp.c:handle_IPI",
        "arch/arm/kernel/smp.c:handle_IPI",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/irq/irqdesc.c:__handle_domain_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224747492,
      "name": "irq_enter",
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
void irq_enter()
```

```json
{
  "name": "irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283499984,
      "name": "irq_enter",
      "external": true,
      "loc": "kernel/softirq.c:345",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/irq.c:__do_irq",
        "arch/powerpc/kernel/time.c:timer_interrupt",
        "arch/powerpc/kernel/traps.c:handle_hmi_exception",
        "arch/powerpc/kernel/dbell.c:doorbell_exception",
        "arch/powerpc/platforms/powernv/opal-irqchip.c:opal_handle_events",
        "arch/powerpc/perf/core-book3s.c:perf_event_interrupt",
        "kernel/sched/core.c:scheduler_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283499984,
      "name": "irq_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void irq_enter()
```

```json
{
  "name": "irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271413256,
      "name": "irq_enter",
      "external": true,
      "loc": "kernel/softirq.c:345",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/kernel/irq.c:do_IRQ",
        "kernel/sched/core.c:scheduler_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271413256,
      "name": "irq_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void irq_enter()
```

```json
{
  "name": "irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579507008,
      "name": "irq_enter",
      "external": true,
      "loc": "kernel/softirq.c:345",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_call_function_single_interrupt",
        "arch/x86/xen/smp.c:xen_call_function_interrupt",
        "arch/x86/xen/smp_pv.c:xen_irq_work_interrupt",
        "arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi",
        "arch/x86/kernel/irq.c:smp_x86_platform_ipi",
        "arch/x86/kernel/irq.c:do_IRQ",
        "arch/x86/kernel/irq_work.c:smp_irq_work_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt",
        "arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler",
        "arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler",
        "arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler",
        "arch/x86/kernel/smp.c:smp_call_function_single_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_reschedule_interrupt",
        "arch/x86/kernel/smp.c:smp_reboot_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_error_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt",
        "arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt",
        "kernel/sched/core.c:scheduler_ipi",
        "drivers/xen/events/events_base.c:xen_evtchn_do_upcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579507008,
      "name": "irq_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void irq_enter()
```

```json
{
  "name": "irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579435776,
      "name": "irq_enter",
      "external": true,
      "loc": "kernel/softirq.c:345",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi",
        "arch/x86/kernel/irq.c:smp_x86_platform_ipi",
        "arch/x86/kernel/irq.c:do_IRQ",
        "arch/x86/kernel/irq_work.c:smp_irq_work_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt",
        "arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler",
        "arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler",
        "arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler",
        "arch/x86/kernel/smp.c:smp_call_function_single_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_reschedule_interrupt",
        "arch/x86/kernel/smp.c:smp_reboot_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_error_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt",
        "arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt",
        "kernel/sched/core.c:scheduler_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579435776,
      "name": "irq_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void irq_enter()
```

```json
{
  "name": "irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579506928,
      "name": "irq_enter",
      "external": true,
      "loc": "kernel/softirq.c:345",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_call_function_single_interrupt",
        "arch/x86/xen/smp.c:xen_call_function_interrupt",
        "arch/x86/xen/smp_pv.c:xen_irq_work_interrupt",
        "arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi",
        "arch/x86/kernel/irq.c:smp_x86_platform_ipi",
        "arch/x86/kernel/irq.c:do_IRQ",
        "arch/x86/kernel/irq_work.c:smp_irq_work_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt",
        "arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler",
        "arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler",
        "arch/x86/kernel/smp.c:smp_call_function_single_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_reschedule_interrupt",
        "arch/x86/kernel/smp.c:smp_reboot_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_error_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt",
        "arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt",
        "kernel/sched/core.c:scheduler_ipi",
        "drivers/xen/events/events_base.c:xen_evtchn_do_upcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579506928,
      "name": "irq_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void irq_enter()
```

```json
{
  "name": "irq_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579539680,
      "name": "irq_enter",
      "external": true,
      "loc": "kernel/softirq.c:345",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_call_function_single_interrupt",
        "arch/x86/xen/smp.c:xen_call_function_interrupt",
        "arch/x86/xen/smp_pv.c:xen_irq_work_interrupt",
        "arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi",
        "arch/x86/kernel/irq.c:smp_x86_platform_ipi",
        "arch/x86/kernel/irq.c:do_IRQ",
        "arch/x86/kernel/irq_work.c:smp_irq_work_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt",
        "arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler",
        "arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler",
        "arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler",
        "arch/x86/kernel/smp.c:smp_call_function_single_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_reschedule_interrupt",
        "arch/x86/kernel/smp.c:smp_reboot_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_error_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt",
        "arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt",
        "kernel/sched/core.c:scheduler_ipi",
        "drivers/xen/events/events_base.c:xen_evtchn_do_upcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579539680,
      "name": "irq_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
