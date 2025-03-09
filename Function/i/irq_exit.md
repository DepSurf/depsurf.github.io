# Function: <code>irq_exit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void irq_exit()
```

```json
{
  "name": "irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579393024,
      "name": "irq_exit",
      "external": true,
      "loc": "kernel/softirq.c:380",
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
        "arch/x86/kernel/smp.c:smp_trace_reschedule_interrupt",
        "arch/x86/kernel/smp.c:smp_trace_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_trace_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_single_interrupt",
        "arch/x86/kernel/smp.c:smp_trace_call_function_single_interrupt",
        "arch/x86/kernel/smp.c:smp_trace_call_function_single_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_trace_spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_trace_spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_error_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_trace_error_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_trace_error_interrupt",
        "arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt",
        "kernel/sched/core.c:scheduler_ipi",
        "drivers/xen/events/events_base.c:xen_evtchn_do_upcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579393024,
      "name": "irq_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void irq_exit()
```

```json
{
  "name": "irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579404880,
      "name": "irq_exit",
      "external": true,
      "loc": "kernel/softirq.c:380",
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
        "arch/x86/kernel/smp.c:smp_trace_call_function_single_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_single_interrupt",
        "arch/x86/kernel/smp.c:smp_trace_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_trace_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_trace_reschedule_interrupt",
        "arch/x86/kernel/smp.c:smp_trace_reschedule_interrupt",
        "arch/x86/kernel/smp.c:smp_reboot_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_trace_error_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_trace_error_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_error_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_trace_spurious_interrupt",
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
      "addr": 18446744071579404880,
      "name": "irq_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void irq_exit()
```

```json
{
  "name": "irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579425168,
      "name": "irq_exit",
      "external": true,
      "loc": "kernel/softirq.c:394",
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
        "arch/x86/kernel/smp.c:smp_trace_call_function_single_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_single_interrupt",
        "arch/x86/kernel/smp.c:smp_trace_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_trace_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_trace_reschedule_interrupt",
        "arch/x86/kernel/smp.c:smp_trace_reschedule_interrupt",
        "arch/x86/kernel/smp.c:smp_reboot_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_trace_error_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_trace_error_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_error_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_trace_spurious_interrupt",
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
      "addr": 18446744071579425168,
      "name": "irq_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void irq_exit()
```

```json
{
  "name": "irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579412928,
      "name": "irq_exit",
      "external": true,
      "loc": "kernel/softirq.c:394",
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
        "arch/x86/kernel/smp.c:smp_trace_call_function_single_interrupt",
        "arch/x86/kernel/smp.c:smp_trace_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_trace_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_trace_reschedule_interrupt",
        "arch/x86/kernel/smp.c:smp_trace_reschedule_interrupt",
        "arch/x86/kernel/smp.c:smp_reboot_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_trace_error_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_trace_error_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_error_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_trace_spurious_interrupt",
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
      "addr": 18446744071579412928,
      "name": "irq_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void irq_exit()
```

```json
{
  "name": "irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579440784,
      "name": "irq_exit",
      "external": true,
      "loc": "kernel/softirq.c:395",
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
        "arch/x86/kernel/irq_work.c:smp_irq_work_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt",
        "arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler",
        "arch/x86/kernel/smp.c:smp_call_function_single_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_single_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_reschedule_interrupt",
        "arch/x86/kernel/smp.c:smp_reboot_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_error_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_error_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_spurious_interrupt",
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
      "addr": 18446744071579440784,
      "name": "irq_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void irq_exit()
```

```json
{
  "name": "irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579455840,
      "name": "irq_exit",
      "external": true,
      "loc": "kernel/softirq.c:402",
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
        "arch/x86/kernel/irq_work.c:smp_irq_work_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt",
        "arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler",
        "arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler",
        "arch/x86/kernel/smp.c:smp_call_function_single_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_single_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_reschedule_interrupt",
        "arch/x86/kernel/smp.c:smp_reboot_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_error_interrupt",
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
      "addr": 18446744071579455840,
      "name": "irq_exit",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void irq_exit()
```

```json
{
  "name": "irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579489488,
      "name": "irq_exit",
      "external": true,
      "loc": "kernel/softirq.c:403",
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
        "arch/x86/kernel/irq_work.c:smp_irq_work_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt",
        "arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler",
        "arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler",
        "arch/x86/kernel/smp.c:smp_call_function_single_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_single_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_reschedule_interrupt",
        "arch/x86/kernel/smp.c:smp_reboot_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_error_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_error_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_spurious_interrupt",
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
      "addr": 18446744071579489488,
      "name": "irq_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
void irq_exit()
```

```json
{
  "name": "irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579507376,
      "name": "irq_exit",
      "external": true,
      "loc": "kernel/softirq.c:403",
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
        "arch/x86/kernel/irq_work.c:smp_irq_work_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt",
        "arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler",
        "arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler",
        "arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler",
        "arch/x86/kernel/smp.c:smp_call_function_single_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_single_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_reschedule_interrupt",
        "arch/x86/kernel/smp.c:smp_reboot_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_error_interrupt",
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
      "addr": 18446744071579507376,
      "name": "irq_exit",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void irq_exit()
```

```json
{
  "name": "irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579533424,
      "name": "irq_exit",
      "external": true,
      "loc": "kernel/softirq.c:403",
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
        "arch/x86/kernel/irq_work.c:smp_irq_work_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt",
        "arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler",
        "arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler",
        "arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler",
        "arch/x86/kernel/smp.c:smp_call_function_single_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_single_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_reschedule_interrupt",
        "arch/x86/kernel/smp.c:smp_reboot_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_error_interrupt",
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
      "addr": 18446744071579533424,
      "name": "irq_exit",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void irq_exit()
```

```json
{
  "name": "irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579564368,
      "name": "irq_exit",
      "external": true,
      "loc": "kernel/softirq.c:439",
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
      "addr": 18446744071579564368,
      "name": "irq_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void irq_exit()
```

```json
{
  "name": "irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579545824,
      "name": "irq_exit",
      "external": true,
      "loc": "kernel/softirq.c:442",
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
      "addr": 18446744071579545824,
      "name": "irq_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void irq_exit()
```

```json
{
  "name": "irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579550416,
      "name": "irq_exit",
      "external": true,
      "loc": "kernel/softirq.c:659",
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
      "addr": 18446744071579550416,
      "name": "irq_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void irq_exit()
```

```json
{
  "name": "irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579621680,
      "name": "irq_exit",
      "external": true,
      "loc": "kernel/softirq.c:658",
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
      "addr": 18446744071579621680,
      "name": "irq_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void irq_exit()
```

```json
{
  "name": "irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579716048,
      "name": "irq_exit",
      "external": true,
      "loc": "kernel/softirq.c:672",
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
      "addr": 18446744071579716048,
      "name": "irq_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void irq_exit()
```

```json
{
  "name": "irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579842896,
      "name": "irq_exit",
      "external": true,
      "loc": "kernel/softirq.c:672",
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
      "addr": 18446744071579842896,
      "name": "irq_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void irq_exit()
```

```json
{
  "name": "irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579892896,
      "name": "irq_exit",
      "external": true,
      "loc": "kernel/softirq.c:654",
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
      "addr": 18446744071579892896,
      "name": "irq_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void irq_exit()
```

```json
{
  "name": "irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579931584,
      "name": "irq_exit",
      "external": true,
      "loc": "kernel/softirq.c:654",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579931584,
      "name": "irq_exit",
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
void irq_exit()
```

```json
{
  "name": "irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490676576,
      "name": "irq_exit",
      "external": true,
      "loc": "kernel/softirq.c:403",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 18446603336490676576,
      "name": "irq_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void irq_exit()
```

```json
{
  "name": "irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224747620,
      "name": "irq_exit",
      "external": true,
      "loc": "kernel/softirq.c:403",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 3224747620,
      "name": "irq_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void irq_exit()
```

```json
{
  "name": "irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283500144,
      "name": "irq_exit",
      "external": true,
      "loc": "kernel/softirq.c:403",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/irq.c:__do_irq",
        "arch/powerpc/kernel/irq.c:__do_irq",
        "arch/powerpc/kernel/time.c:timer_interrupt",
        "arch/powerpc/kernel/traps.c:handle_hmi_exception",
        "arch/powerpc/kernel/dbell.c:doorbell_exception",
        "arch/powerpc/kernel/dbell.c:doorbell_exception",
        "arch/powerpc/platforms/powernv/opal-irqchip.c:opal_handle_events",
        "arch/powerpc/perf/core-book3s.c:perf_event_interrupt",
        "kernel/sched/core.c:scheduler_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283500144,
      "name": "irq_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
void irq_exit()
```

```json
{
  "name": "irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271413376,
      "name": "irq_exit",
      "external": true,
      "loc": "kernel/softirq.c:403",
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
      "addr": 18446743936271413376,
      "name": "irq_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
void irq_exit()
```

```json
{
  "name": "irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579507088,
      "name": "irq_exit",
      "external": true,
      "loc": "kernel/softirq.c:403",
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
        "arch/x86/kernel/irq_work.c:smp_irq_work_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt",
        "arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler",
        "arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler",
        "arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler",
        "arch/x86/kernel/smp.c:smp_call_function_single_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_single_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_reschedule_interrupt",
        "arch/x86/kernel/smp.c:smp_reboot_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_error_interrupt",
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
      "addr": 18446744071579507088,
      "name": "irq_exit",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void irq_exit()
```

```json
{
  "name": "irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579435856,
      "name": "irq_exit",
      "external": true,
      "loc": "kernel/softirq.c:403",
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
        "arch/x86/kernel/irq_work.c:smp_irq_work_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt",
        "arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler",
        "arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler",
        "arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler",
        "arch/x86/kernel/smp.c:smp_call_function_single_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_single_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_reschedule_interrupt",
        "arch/x86/kernel/smp.c:smp_reboot_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_error_interrupt",
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
      "addr": 18446744071579435856,
      "name": "irq_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void irq_exit()
```

```json
{
  "name": "irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579507008,
      "name": "irq_exit",
      "external": true,
      "loc": "kernel/softirq.c:403",
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
        "arch/x86/kernel/irq_work.c:smp_irq_work_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt",
        "arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler",
        "arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler",
        "arch/x86/kernel/smp.c:smp_call_function_single_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_single_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_call_function_interrupt",
        "arch/x86/kernel/smp.c:smp_reschedule_interrupt",
        "arch/x86/kernel/smp.c:smp_reboot_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_error_interrupt",
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
      "name": "irq_exit",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void irq_exit()
```

```json
{
  "name": "irq_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579539760,
      "name": "irq_exit",
      "external": true,
      "loc": "kernel/softirq.c:403",
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
      "addr": 18446744071579539760,
      "name": "irq_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
