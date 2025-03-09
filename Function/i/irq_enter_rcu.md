# Function: <code>irq_enter_rcu</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void irq_enter_rcu()
```

```json
{
  "name": "irq_enter_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579564094,
      "name": "irq_enter_rcu",
      "external": true,
      "loc": "kernel/softirq.c:345",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:irq_enter"
      ],
      "caller_func": [
        "arch/x86/entry/common.c:xen_pv_evtchn_do_upcall",
        "arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback",
        "arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment",
        "arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi",
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
        "arch/x86/kernel/smp.c:sysvec_reboot",
        "arch/x86/kernel/apic/apic.c:sysvec_error_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt",
        "arch/x86/kernel/apic/apic.c:spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup",
        "arch/x86/platform/uv/tlb_uv.c:sysvec_uv_bau_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579564000,
      "name": "irq_enter_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void irq_enter_rcu()
```

```json
{
  "name": "irq_enter_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579545550,
      "name": "irq_enter_rcu",
      "external": true,
      "loc": "kernel/softirq.c:378",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:irq_enter"
      ],
      "caller_func": [
        "arch/x86/entry/common.c:xen_pv_evtchn_do_upcall",
        "arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback",
        "arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment",
        "arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi",
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
        "arch/x86/kernel/smp.c:sysvec_reboot",
        "arch/x86/kernel/apic/apic.c:sysvec_error_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt",
        "arch/x86/kernel/apic/apic.c:spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup",
        "arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579545472,
      "name": "irq_enter_rcu",
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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void irq_enter_rcu()
```

```json
{
  "name": "irq_enter_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579550142,
      "name": "irq_enter_rcu",
      "external": true,
      "loc": "kernel/softirq.c:595",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:irq_enter"
      ],
      "caller_func": [
        "arch/x86/entry/common.c:xen_pv_evtchn_do_upcall",
        "arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback",
        "arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment",
        "arch/x86/kernel/irq.c:sysvec_thermal",
        "arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi",
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
        "arch/x86/kernel/smp.c:sysvec_reboot",
        "arch/x86/kernel/apic/apic.c:sysvec_error_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt",
        "arch/x86/kernel/apic/apic.c:spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup",
        "arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579550064,
      "name": "irq_enter_rcu",
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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void irq_enter_rcu()
```

```json
{
  "name": "irq_enter_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579621438,
      "name": "irq_enter_rcu",
      "external": true,
      "loc": "kernel/softirq.c:594",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:irq_enter"
      ],
      "caller_func": [
        "arch/x86/entry/common.c:xen_pv_evtchn_do_upcall",
        "arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback",
        "arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment",
        "arch/x86/kernel/irq.c:sysvec_thermal",
        "arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi",
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
        "arch/x86/kernel/smp.c:sysvec_reboot",
        "arch/x86/kernel/apic/apic.c:sysvec_error_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt",
        "arch/x86/kernel/apic/apic.c:spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup",
        "arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579621360,
      "name": "irq_enter_rcu",
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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void irq_enter_rcu()
```

```json
{
  "name": "irq_enter_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579715950,
      "name": "irq_enter_rcu",
      "external": true,
      "loc": "kernel/softirq.c:607",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:irq_enter",
        "kernel/softirq.c:irq_enter"
      ],
      "caller_func": [
        "arch/x86/entry/common.c:xen_pv_evtchn_do_upcall",
        "arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback",
        "arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment",
        "arch/x86/kernel/irq.c:sysvec_thermal",
        "arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi",
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
        "arch/x86/kernel/smp.c:sysvec_reboot",
        "arch/x86/kernel/apic/apic.c:sysvec_error_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt",
        "arch/x86/kernel/apic/apic.c:spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup",
        "arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579715856,
      "name": "irq_enter_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void irq_enter_rcu()
```

```json
{
  "name": "irq_enter_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579842766,
      "name": "irq_enter_rcu",
      "external": true,
      "loc": "kernel/softirq.c:607",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:irq_enter",
        "kernel/softirq.c:irq_enter"
      ],
      "caller_func": [
        "arch/x86/entry/common.c:xen_pv_evtchn_do_upcall",
        "arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback",
        "arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment",
        "arch/x86/kernel/irq.c:sysvec_thermal",
        "arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi",
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
        "arch/x86/kernel/smp.c:sysvec_reboot",
        "arch/x86/kernel/apic/apic.c:sysvec_error_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt",
        "arch/x86/kernel/apic/apic.c:spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup",
        "arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579842656,
      "name": "irq_enter_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void irq_enter_rcu()
```

```json
{
  "name": "irq_enter_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579892766,
      "name": "irq_enter_rcu",
      "external": true,
      "loc": "kernel/softirq.c:589",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:irq_enter",
        "kernel/softirq.c:irq_enter"
      ],
      "caller_func": [
        "arch/x86/entry/common.c:xen_pv_evtchn_do_upcall",
        "arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback",
        "arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment",
        "arch/x86/kernel/irq.c:sysvec_thermal",
        "arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi",
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
        "arch/x86/kernel/smp.c:sysvec_reboot",
        "arch/x86/kernel/apic/apic.c:sysvec_error_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt",
        "arch/x86/kernel/apic/apic.c:spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt",
        "arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup",
        "arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579892656,
      "name": "irq_enter_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void irq_enter_rcu()
```

```json
{
  "name": "irq_enter_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_enter_rcu",
      "external": true,
      "loc": "kernel/softirq.c:589",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:xen_pv_evtchn_do_upcall",
        "arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback",
        "arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment",
        "arch/x86/kernel/irq.c:sysvec_thermal",
        "arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi",
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
        "arch/x86/kernel/smp.c:sysvec_reboot",
        "arch/x86/kernel/apic/apic.c:sysvec_error_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt",
        "arch/x86/kernel/apic/apic.c:spurious_interrupt",
        "arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt",
        "arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt",
        "kernel/softirq.c:irq_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597388279,
      "name": "irq_enter_rcu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071579931328,
      "name": "irq_enter_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void irq_enter_rcu()
```
</details>
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
