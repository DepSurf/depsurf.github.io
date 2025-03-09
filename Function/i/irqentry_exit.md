# Function: <code>irqentry_exit</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void irqentry_exit(struct pt_regs * regs, irqentry_state_t state)
```

```json
{
  "name": "irqentry_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591660096,
      "name": "irqentry_exit",
      "external": true,
      "loc": "kernel/entry/common.c:396",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:xen_pv_evtchn_do_upcall",
        "arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback",
        "arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment",
        "arch/x86/kernel/traps.c:exc_device_not_available",
        "arch/x86/kernel/traps.c:exc_spurious_interrupt_bug",
        "arch/x86/kernel/traps.c:exc_simd_coprocessor_error",
        "arch/x86/kernel/traps.c:exc_coprocessor_error",
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:exc_bounds",
        "arch/x86/kernel/traps.c:exc_alignment_check",
        "arch/x86/kernel/traps.c:exc_stack_segment",
        "arch/x86/kernel/traps.c:exc_segment_not_present",
        "arch/x86/kernel/traps.c:exc_invalid_tss",
        "arch/x86/kernel/traps.c:exc_coproc_segment_overrun",
        "arch/x86/kernel/traps.c:exc_invalid_op",
        "arch/x86/kernel/traps.c:exc_overflow",
        "arch/x86/kernel/traps.c:exc_divide_error",
        "arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi",
        "arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi",
        "arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi",
        "arch/x86/kernel/irq.c:sysvec_x86_platform_ipi",
        "arch/x86/kernel/irq.c:common_interrupt",
        "arch/x86/kernel/irq_work.c:sysvec_irq_work",
        "arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error",
        "arch/x86/kernel/cpu/mce/threshold.c:sysvec_threshold",
        "arch/x86/kernel/cpu/mce/therm_throt.c:sysvec_thermal",
        "arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_stimer0",
        "arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_callback",
        "arch/x86/kernel/cpu/acrn.c:sysvec_acrn_hv_callback",
        "arch/x86/kernel/smp.c:sysvec_call_function_single",
        "arch/x86/kernel/smp.c:sysvec_call_function",
        "arch/x86/kernel/smp.c:sysvec_reschedule_ipi",
        "arch/x86/kernel/smp.c:sysvec_reboot",
        "arch/x86/kernel/apic/apic.c:sysvec_error_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt",
        "arch/x86/kernel/apic/apic.c:spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup",
        "arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt",
        "arch/x86/kernel/kvm.c:__kvm_handle_async_pf",
        "arch/x86/mm/fault.c:exc_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591660096,
      "name": "irqentry_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void irqentry_exit(struct pt_regs * regs, irqentry_state_t state)
```

```json
{
  "name": "irqentry_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591603776,
      "name": "irqentry_exit",
      "external": true,
      "loc": "kernel/entry/common.c:400",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:xen_pv_evtchn_do_upcall",
        "arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback",
        "arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment",
        "arch/x86/kernel/traps.c:exc_device_not_available",
        "arch/x86/kernel/traps.c:exc_spurious_interrupt_bug",
        "arch/x86/kernel/traps.c:exc_simd_coprocessor_error",
        "arch/x86/kernel/traps.c:exc_coprocessor_error",
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:exc_bounds",
        "arch/x86/kernel/traps.c:exc_alignment_check",
        "arch/x86/kernel/traps.c:exc_stack_segment",
        "arch/x86/kernel/traps.c:exc_segment_not_present",
        "arch/x86/kernel/traps.c:exc_invalid_tss",
        "arch/x86/kernel/traps.c:exc_coproc_segment_overrun",
        "arch/x86/kernel/traps.c:exc_invalid_op",
        "arch/x86/kernel/traps.c:exc_overflow",
        "arch/x86/kernel/traps.c:exc_divide_error",
        "arch/x86/kernel/irq.c:sysvec_thermal",
        "arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi",
        "arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi",
        "arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi",
        "arch/x86/kernel/irq.c:sysvec_x86_platform_ipi",
        "arch/x86/kernel/irq.c:common_interrupt",
        "arch/x86/kernel/irq_work.c:sysvec_irq_work",
        "arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error",
        "arch/x86/kernel/cpu/mce/threshold.c:sysvec_threshold",
        "arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_stimer0",
        "arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_callback",
        "arch/x86/kernel/cpu/acrn.c:sysvec_acrn_hv_callback",
        "arch/x86/kernel/smp.c:sysvec_call_function_single",
        "arch/x86/kernel/smp.c:sysvec_call_function",
        "arch/x86/kernel/smp.c:sysvec_reschedule_ipi",
        "arch/x86/kernel/smp.c:sysvec_reboot",
        "arch/x86/kernel/apic/apic.c:sysvec_error_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt",
        "arch/x86/kernel/apic/apic.c:spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup",
        "arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt",
        "arch/x86/kernel/kvm.c:__kvm_handle_async_pf",
        "arch/x86/mm/fault.c:exc_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591603776,
      "name": "irqentry_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void irqentry_exit(struct pt_regs * regs, irqentry_state_t state)
```

```json
{
  "name": "irqentry_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592776656,
      "name": "irqentry_exit",
      "external": true,
      "loc": "kernel/entry/common.c:398",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:xen_pv_evtchn_do_upcall",
        "arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback",
        "arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment",
        "arch/x86/kernel/traps.c:exc_device_not_available",
        "arch/x86/kernel/traps.c:exc_spurious_interrupt_bug",
        "arch/x86/kernel/traps.c:exc_simd_coprocessor_error",
        "arch/x86/kernel/traps.c:exc_coprocessor_error",
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:exc_bounds",
        "arch/x86/kernel/traps.c:exc_alignment_check",
        "arch/x86/kernel/traps.c:exc_stack_segment",
        "arch/x86/kernel/traps.c:exc_segment_not_present",
        "arch/x86/kernel/traps.c:exc_invalid_tss",
        "arch/x86/kernel/traps.c:exc_coproc_segment_overrun",
        "arch/x86/kernel/traps.c:exc_invalid_op",
        "arch/x86/kernel/traps.c:exc_overflow",
        "arch/x86/kernel/traps.c:exc_divide_error",
        "arch/x86/kernel/irq.c:sysvec_thermal",
        "arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi",
        "arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi",
        "arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi",
        "arch/x86/kernel/irq.c:sysvec_x86_platform_ipi",
        "arch/x86/kernel/irq.c:common_interrupt",
        "arch/x86/kernel/irq_work.c:sysvec_irq_work",
        "arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error",
        "arch/x86/kernel/cpu/mce/threshold.c:sysvec_threshold",
        "arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_stimer0",
        "arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_callback",
        "arch/x86/kernel/cpu/acrn.c:sysvec_acrn_hv_callback",
        "arch/x86/kernel/smp.c:sysvec_call_function_single",
        "arch/x86/kernel/smp.c:sysvec_call_function",
        "arch/x86/kernel/smp.c:sysvec_reschedule_ipi",
        "arch/x86/kernel/smp.c:sysvec_reboot",
        "arch/x86/kernel/apic/apic.c:sysvec_error_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt",
        "arch/x86/kernel/apic/apic.c:spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup",
        "arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt",
        "arch/x86/kernel/kvm.c:__kvm_handle_async_pf",
        "arch/x86/mm/fault.c:exc_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592776656,
      "name": "irqentry_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void irqentry_exit(struct pt_regs * regs, irqentry_state_t state)
```

```json
{
  "name": "irqentry_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594674272,
      "name": "irqentry_exit",
      "external": true,
      "loc": "kernel/entry/common.c:402",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:xen_pv_evtchn_do_upcall",
        "arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback",
        "arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback",
        "arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment",
        "arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment",
        "arch/x86/kernel/traps.c:exc_virtualization_exception",
        "arch/x86/kernel/traps.c:exc_device_not_available",
        "arch/x86/kernel/traps.c:exc_spurious_interrupt_bug",
        "arch/x86/kernel/traps.c:exc_simd_coprocessor_error",
        "arch/x86/kernel/traps.c:exc_coprocessor_error",
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:exc_bounds",
        "arch/x86/kernel/traps.c:exc_alignment_check",
        "arch/x86/kernel/traps.c:exc_stack_segment",
        "arch/x86/kernel/traps.c:exc_segment_not_present",
        "arch/x86/kernel/traps.c:exc_invalid_tss",
        "arch/x86/kernel/traps.c:exc_coproc_segment_overrun",
        "arch/x86/kernel/traps.c:exc_invalid_op",
        "arch/x86/kernel/traps.c:exc_overflow",
        "arch/x86/kernel/traps.c:exc_divide_error",
        "arch/x86/kernel/irq.c:sysvec_thermal",
        "arch/x86/kernel/irq.c:sysvec_thermal",
        "arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi",
        "arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi",
        "arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi",
        "arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi",
        "arch/x86/kernel/irq.c:sysvec_x86_platform_ipi",
        "arch/x86/kernel/irq.c:sysvec_x86_platform_ipi",
        "arch/x86/kernel/irq.c:common_interrupt",
        "arch/x86/kernel/irq_work.c:sysvec_irq_work",
        "arch/x86/kernel/irq_work.c:sysvec_irq_work",
        "arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error",
        "arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error",
        "arch/x86/kernel/cpu/mce/threshold.c:sysvec_threshold",
        "arch/x86/kernel/cpu/mce/threshold.c:sysvec_threshold",
        "arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_stimer0",
        "arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_stimer0",
        "arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_callback",
        "arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_callback",
        "arch/x86/kernel/cpu/acrn.c:sysvec_acrn_hv_callback",
        "arch/x86/kernel/cpu/acrn.c:sysvec_acrn_hv_callback",
        "arch/x86/kernel/smp.c:sysvec_call_function_single",
        "arch/x86/kernel/smp.c:sysvec_call_function_single",
        "arch/x86/kernel/smp.c:sysvec_call_function",
        "arch/x86/kernel/smp.c:sysvec_call_function",
        "arch/x86/kernel/smp.c:sysvec_reschedule_ipi",
        "arch/x86/kernel/smp.c:sysvec_reboot",
        "arch/x86/kernel/apic/apic.c:sysvec_error_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_error_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt",
        "arch/x86/kernel/apic/apic.c:spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup",
        "arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup",
        "arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt",
        "arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt",
        "arch/x86/kernel/kvm.c:__kvm_handle_async_pf",
        "arch/x86/mm/fault.c:exc_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594674272,
      "name": "irqentry_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void irqentry_exit(struct pt_regs * regs, irqentry_state_t state)
```

```json
{
  "name": "irqentry_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596408496,
      "name": "irqentry_exit",
      "external": true,
      "loc": "kernel/entry/common.c:406",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:xen_pv_evtchn_do_upcall",
        "arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback",
        "arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback",
        "arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment",
        "arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment",
        "arch/x86/kernel/traps.c:exc_virtualization_exception",
        "arch/x86/kernel/traps.c:exc_device_not_available",
        "arch/x86/kernel/traps.c:exc_spurious_interrupt_bug",
        "arch/x86/kernel/traps.c:exc_simd_coprocessor_error",
        "arch/x86/kernel/traps.c:exc_coprocessor_error",
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:exc_bounds",
        "arch/x86/kernel/traps.c:exc_alignment_check",
        "arch/x86/kernel/traps.c:exc_stack_segment",
        "arch/x86/kernel/traps.c:exc_segment_not_present",
        "arch/x86/kernel/traps.c:exc_invalid_tss",
        "arch/x86/kernel/traps.c:exc_coproc_segment_overrun",
        "arch/x86/kernel/traps.c:exc_invalid_op",
        "arch/x86/kernel/traps.c:exc_overflow",
        "arch/x86/kernel/traps.c:exc_divide_error",
        "arch/x86/kernel/irq.c:sysvec_thermal",
        "arch/x86/kernel/irq.c:sysvec_thermal",
        "arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi",
        "arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi",
        "arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi",
        "arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi",
        "arch/x86/kernel/irq.c:sysvec_x86_platform_ipi",
        "arch/x86/kernel/irq.c:sysvec_x86_platform_ipi",
        "arch/x86/kernel/irq.c:common_interrupt",
        "arch/x86/kernel/irq_work.c:sysvec_irq_work",
        "arch/x86/kernel/irq_work.c:sysvec_irq_work",
        "arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error",
        "arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error",
        "arch/x86/kernel/cpu/mce/threshold.c:sysvec_threshold",
        "arch/x86/kernel/cpu/mce/threshold.c:sysvec_threshold",
        "arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_stimer0",
        "arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_stimer0",
        "arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_callback",
        "arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_callback",
        "arch/x86/kernel/cpu/acrn.c:sysvec_acrn_hv_callback",
        "arch/x86/kernel/cpu/acrn.c:sysvec_acrn_hv_callback",
        "arch/x86/kernel/smp.c:sysvec_call_function_single",
        "arch/x86/kernel/smp.c:sysvec_call_function_single",
        "arch/x86/kernel/smp.c:sysvec_call_function",
        "arch/x86/kernel/smp.c:sysvec_call_function",
        "arch/x86/kernel/smp.c:sysvec_reschedule_ipi",
        "arch/x86/kernel/smp.c:sysvec_reboot",
        "arch/x86/kernel/apic/apic.c:sysvec_error_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_error_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt",
        "arch/x86/kernel/apic/apic.c:spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup",
        "arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup",
        "arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt",
        "arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt",
        "arch/x86/kernel/kvm.c:__kvm_handle_async_pf",
        "arch/x86/mm/fault.c:exc_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596408496,
      "name": "irqentry_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void irqentry_exit(struct pt_regs * regs, irqentry_state_t state)
```

```json
{
  "name": "irqentry_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596940528,
      "name": "irqentry_exit",
      "external": true,
      "loc": "kernel/entry/common.c:407",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:xen_pv_evtchn_do_upcall",
        "arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback",
        "arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback",
        "arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment",
        "arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment",
        "arch/x86/kernel/traps.c:exc_virtualization_exception",
        "arch/x86/kernel/traps.c:exc_device_not_available",
        "arch/x86/kernel/traps.c:exc_spurious_interrupt_bug",
        "arch/x86/kernel/traps.c:exc_simd_coprocessor_error",
        "arch/x86/kernel/traps.c:exc_coprocessor_error",
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:exc_bounds",
        "arch/x86/kernel/traps.c:exc_alignment_check",
        "arch/x86/kernel/traps.c:exc_stack_segment",
        "arch/x86/kernel/traps.c:exc_segment_not_present",
        "arch/x86/kernel/traps.c:exc_invalid_tss",
        "arch/x86/kernel/traps.c:exc_coproc_segment_overrun",
        "arch/x86/kernel/traps.c:exc_invalid_op",
        "arch/x86/kernel/traps.c:exc_overflow",
        "arch/x86/kernel/traps.c:exc_divide_error",
        "arch/x86/kernel/irq.c:sysvec_thermal",
        "arch/x86/kernel/irq.c:sysvec_thermal",
        "arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi",
        "arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi",
        "arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi",
        "arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi",
        "arch/x86/kernel/irq.c:sysvec_x86_platform_ipi",
        "arch/x86/kernel/irq.c:sysvec_x86_platform_ipi",
        "arch/x86/kernel/irq.c:common_interrupt",
        "arch/x86/kernel/irq_work.c:sysvec_irq_work",
        "arch/x86/kernel/irq_work.c:sysvec_irq_work",
        "arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error",
        "arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error",
        "arch/x86/kernel/cpu/mce/threshold.c:sysvec_threshold",
        "arch/x86/kernel/cpu/mce/threshold.c:sysvec_threshold",
        "arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_stimer0",
        "arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_stimer0",
        "arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_callback",
        "arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_callback",
        "arch/x86/kernel/cpu/acrn.c:sysvec_acrn_hv_callback",
        "arch/x86/kernel/cpu/acrn.c:sysvec_acrn_hv_callback",
        "arch/x86/kernel/smp.c:sysvec_call_function_single",
        "arch/x86/kernel/smp.c:sysvec_call_function_single",
        "arch/x86/kernel/smp.c:sysvec_call_function",
        "arch/x86/kernel/smp.c:sysvec_call_function",
        "arch/x86/kernel/smp.c:sysvec_reschedule_ipi",
        "arch/x86/kernel/smp.c:sysvec_reboot",
        "arch/x86/kernel/apic/apic.c:sysvec_error_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_error_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt",
        "arch/x86/kernel/apic/apic.c:spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup",
        "arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup",
        "arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt",
        "arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt",
        "arch/x86/kernel/kvm.c:__kvm_handle_async_pf",
        "arch/x86/mm/fault.c:exc_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596940528,
      "name": "irqentry_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void irqentry_exit(struct pt_regs * regs, irqentry_state_t state)
```

```json
{
  "name": "irqentry_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597867120,
      "name": "irqentry_exit",
      "external": true,
      "loc": "kernel/entry/common.c:322",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:xen_pv_evtchn_do_upcall",
        "arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback",
        "arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback",
        "arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment",
        "arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment",
        "arch/x86/kernel/traps.c:exc_virtualization_exception",
        "arch/x86/kernel/traps.c:exc_device_not_available",
        "arch/x86/kernel/traps.c:exc_spurious_interrupt_bug",
        "arch/x86/kernel/traps.c:exc_simd_coprocessor_error",
        "arch/x86/kernel/traps.c:exc_coprocessor_error",
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:exc_bounds",
        "arch/x86/kernel/traps.c:exc_alignment_check",
        "arch/x86/kernel/traps.c:exc_stack_segment",
        "arch/x86/kernel/traps.c:exc_segment_not_present",
        "arch/x86/kernel/traps.c:exc_invalid_tss",
        "arch/x86/kernel/traps.c:exc_coproc_segment_overrun",
        "arch/x86/kernel/traps.c:exc_invalid_op",
        "arch/x86/kernel/traps.c:exc_overflow",
        "arch/x86/kernel/traps.c:exc_divide_error",
        "arch/x86/kernel/irq.c:sysvec_thermal",
        "arch/x86/kernel/irq.c:sysvec_thermal",
        "arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi",
        "arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi",
        "arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi",
        "arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi",
        "arch/x86/kernel/irq.c:sysvec_x86_platform_ipi",
        "arch/x86/kernel/irq.c:sysvec_x86_platform_ipi",
        "arch/x86/kernel/irq.c:common_interrupt",
        "arch/x86/kernel/irq_work.c:sysvec_irq_work",
        "arch/x86/kernel/irq_work.c:sysvec_irq_work",
        "arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error",
        "arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error",
        "arch/x86/kernel/cpu/mce/threshold.c:sysvec_threshold",
        "arch/x86/kernel/cpu/mce/threshold.c:sysvec_threshold",
        "arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_stimer0",
        "arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_stimer0",
        "arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_callback",
        "arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_callback",
        "arch/x86/kernel/cpu/acrn.c:sysvec_acrn_hv_callback",
        "arch/x86/kernel/cpu/acrn.c:sysvec_acrn_hv_callback",
        "arch/x86/kernel/smp.c:sysvec_call_function_single",
        "arch/x86/kernel/smp.c:sysvec_call_function_single",
        "arch/x86/kernel/smp.c:sysvec_call_function",
        "arch/x86/kernel/smp.c:sysvec_call_function",
        "arch/x86/kernel/smp.c:sysvec_reschedule_ipi",
        "arch/x86/kernel/smp.c:sysvec_reboot",
        "arch/x86/kernel/apic/apic.c:sysvec_error_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_error_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt",
        "arch/x86/kernel/apic/apic.c:spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt",
        "arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt",
        "arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt",
        "arch/x86/kernel/kvm.c:__kvm_handle_async_pf",
        "arch/x86/kernel/cet.c:exc_control_protection",
        "arch/x86/mm/fault.c:exc_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597867120,
      "name": "irqentry_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void irqentry_exit(struct pt_regs * regs, irqentry_state_t state)
```
</details>
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
