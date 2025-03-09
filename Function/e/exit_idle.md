# Function: <code>exit_idle</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void exit_idle()
```

```json
{
  "name": "exit_idle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579079952,
      "name": "exit_idle",
      "external": true,
      "loc": "arch/x86/kernel/process.c:265",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:do_IRQ",
        "arch/x86/kernel/irq.c:smp_x86_platform_ipi",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi",
        "arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_trace_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt",
        "arch/x86/kernel/cpu/mcheck/threshold.c:smp_trace_threshold_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_trace_thermal_interrupt",
        "arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler",
        "arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_trace_spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_error_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_trace_error_interrupt",
        "arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt",
        "drivers/xen/events/events_base.c:xen_evtchn_do_upcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579079952,
      "name": "exit_idle",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void exit_idle()
```

```json
{
  "name": "exit_idle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579075840,
      "name": "exit_idle",
      "external": true,
      "loc": "arch/x86/kernel/process.c:268",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi",
        "arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi",
        "arch/x86/kernel/irq.c:smp_x86_platform_ipi",
        "arch/x86/kernel/irq.c:do_IRQ",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_trace_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/threshold.c:smp_trace_threshold_interrupt",
        "arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_trace_thermal_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt",
        "arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler",
        "arch/x86/kernel/apic/apic.c:smp_trace_error_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_error_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_trace_spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt",
        "arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt",
        "arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt",
        "drivers/xen/events/events_base.c:xen_evtchn_do_upcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579075840,
      "name": "exit_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
void exit_idle()
```
</details>
</li>
</ul>
