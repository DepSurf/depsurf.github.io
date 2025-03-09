# Struct: <code>kvm_vcpu_stat</code>

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
struct kvm_vcpu_stat {
    u64 pf_fixed;
    u64 pf_guest;
    u64 tlb_flush;
    u64 invlpg;
    u64 exits;
    u64 io_exits;
    u64 mmio_exits;
    u64 signal_exits;
    u64 irq_window_exits;
    u64 nmi_window_exits;
    u64 l1d_flush;
    u64 halt_exits;
    u64 halt_successful_poll;
    u64 halt_attempted_poll;
    u64 halt_poll_invalid;
    u64 halt_wakeup;
    u64 request_irq_exits;
    u64 irq_exits;
    u64 host_state_reload;
    u64 fpu_reload;
    u64 insn_emulation;
    u64 insn_emulation_fail;
    u64 hypercalls;
    u64 irq_injections;
    u64 nmi_injections;
    u64 req_event;
    u64 halt_poll_success_ns;
    u64 halt_poll_fail_ns;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct kvm_vcpu_stat {
    u64 pf_fixed;
    u64 pf_guest;
    u64 tlb_flush;
    u64 invlpg;
    u64 exits;
    u64 io_exits;
    u64 mmio_exits;
    u64 signal_exits;
    u64 irq_window_exits;
    u64 nmi_window_exits;
    u64 l1d_flush;
    u64 halt_exits;
    u64 halt_successful_poll;
    u64 halt_attempted_poll;
    u64 halt_poll_invalid;
    u64 halt_wakeup;
    u64 request_irq_exits;
    u64 irq_exits;
    u64 host_state_reload;
    u64 fpu_reload;
    u64 insn_emulation;
    u64 insn_emulation_fail;
    u64 hypercalls;
    u64 irq_injections;
    u64 nmi_injections;
    u64 req_event;
    u64 halt_poll_success_ns;
    u64 halt_poll_fail_ns;
    u64 nested_run;
    u64 directed_yield_attempted;
    u64 directed_yield_successful;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct kvm_vcpu_stat {
    struct kvm_vcpu_stat_generic generic;
    u64 pf_fixed;
    u64 pf_guest;
    u64 tlb_flush;
    u64 invlpg;
    u64 exits;
    u64 io_exits;
    u64 mmio_exits;
    u64 signal_exits;
    u64 irq_window_exits;
    u64 nmi_window_exits;
    u64 l1d_flush;
    u64 halt_exits;
    u64 request_irq_exits;
    u64 irq_exits;
    u64 host_state_reload;
    u64 fpu_reload;
    u64 insn_emulation;
    u64 insn_emulation_fail;
    u64 hypercalls;
    u64 irq_injections;
    u64 nmi_injections;
    u64 req_event;
    u64 nested_run;
    u64 directed_yield_attempted;
    u64 directed_yield_successful;
    u64 guest_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct kvm_vcpu_stat {
    struct kvm_vcpu_stat_generic generic;
    u64 pf_taken;
    u64 pf_fixed;
    u64 pf_emulate;
    u64 pf_spurious;
    u64 pf_fast;
    u64 pf_mmio_spte_created;
    u64 pf_guest;
    u64 tlb_flush;
    u64 invlpg;
    u64 exits;
    u64 io_exits;
    u64 mmio_exits;
    u64 signal_exits;
    u64 irq_window_exits;
    u64 nmi_window_exits;
    u64 l1d_flush;
    u64 halt_exits;
    u64 request_irq_exits;
    u64 irq_exits;
    u64 host_state_reload;
    u64 fpu_reload;
    u64 insn_emulation;
    u64 insn_emulation_fail;
    u64 hypercalls;
    u64 irq_injections;
    u64 nmi_injections;
    u64 req_event;
    u64 nested_run;
    u64 directed_yield_attempted;
    u64 directed_yield_successful;
    u64 preemption_reported;
    u64 preemption_other;
    u64 guest_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct kvm_vcpu_stat {
    struct kvm_vcpu_stat_generic generic;
    u64 pf_taken;
    u64 pf_fixed;
    u64 pf_emulate;
    u64 pf_spurious;
    u64 pf_fast;
    u64 pf_mmio_spte_created;
    u64 pf_guest;
    u64 tlb_flush;
    u64 invlpg;
    u64 exits;
    u64 io_exits;
    u64 mmio_exits;
    u64 signal_exits;
    u64 irq_window_exits;
    u64 nmi_window_exits;
    u64 l1d_flush;
    u64 halt_exits;
    u64 request_irq_exits;
    u64 irq_exits;
    u64 host_state_reload;
    u64 fpu_reload;
    u64 insn_emulation;
    u64 insn_emulation_fail;
    u64 hypercalls;
    u64 irq_injections;
    u64 nmi_injections;
    u64 req_event;
    u64 nested_run;
    u64 directed_yield_attempted;
    u64 directed_yield_successful;
    u64 preemption_reported;
    u64 preemption_other;
    u64 guest_mode;
    u64 notify_window_exits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct kvm_vcpu_stat {
    struct kvm_vcpu_stat_generic generic;
    u64 pf_taken;
    u64 pf_fixed;
    u64 pf_emulate;
    u64 pf_spurious;
    u64 pf_fast;
    u64 pf_mmio_spte_created;
    u64 pf_guest;
    u64 tlb_flush;
    u64 invlpg;
    u64 exits;
    u64 io_exits;
    u64 mmio_exits;
    u64 signal_exits;
    u64 irq_window_exits;
    u64 nmi_window_exits;
    u64 l1d_flush;
    u64 halt_exits;
    u64 request_irq_exits;
    u64 irq_exits;
    u64 host_state_reload;
    u64 fpu_reload;
    u64 insn_emulation;
    u64 insn_emulation_fail;
    u64 hypercalls;
    u64 irq_injections;
    u64 nmi_injections;
    u64 req_event;
    u64 nested_run;
    u64 directed_yield_attempted;
    u64 directed_yield_successful;
    u64 preemption_reported;
    u64 preemption_other;
    u64 guest_mode;
    u64 notify_window_exits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct kvm_vcpu_stat {
    struct kvm_vcpu_stat_generic generic;
    u64 pf_taken;
    u64 pf_fixed;
    u64 pf_emulate;
    u64 pf_spurious;
    u64 pf_fast;
    u64 pf_mmio_spte_created;
    u64 pf_guest;
    u64 tlb_flush;
    u64 invlpg;
    u64 exits;
    u64 io_exits;
    u64 mmio_exits;
    u64 signal_exits;
    u64 irq_window_exits;
    u64 nmi_window_exits;
    u64 l1d_flush;
    u64 halt_exits;
    u64 request_irq_exits;
    u64 irq_exits;
    u64 host_state_reload;
    u64 fpu_reload;
    u64 insn_emulation;
    u64 insn_emulation_fail;
    u64 hypercalls;
    u64 irq_injections;
    u64 nmi_injections;
    u64 req_event;
    u64 nested_run;
    u64 directed_yield_attempted;
    u64 directed_yield_successful;
    u64 preemption_reported;
    u64 preemption_other;
    u64 guest_mode;
    u64 notify_window_exits;
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
struct kvm_vcpu_stat {
    u64 halt_successful_poll;
    u64 halt_attempted_poll;
    u64 halt_poll_invalid;
    u64 halt_wakeup;
    u64 hvc_exit_stat;
    u64 wfe_exit_stat;
    u64 wfi_exit_stat;
    u64 mmio_exit_user;
    u64 mmio_exit_kernel;
    u64 exits;
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct kvm_vcpu_stat {
    u64 sum_exits;
    u64 mmio_exits;
    u64 signal_exits;
    u64 light_exits;
    u64 itlb_real_miss_exits;
    u64 itlb_virt_miss_exits;
    u64 dtlb_real_miss_exits;
    u64 dtlb_virt_miss_exits;
    u64 syscall_exits;
    u64 isi_exits;
    u64 dsi_exits;
    u64 emulated_inst_exits;
    u64 dec_exits;
    u64 ext_intr_exits;
    u64 halt_poll_success_ns;
    u64 halt_poll_fail_ns;
    u64 halt_wait_ns;
    u64 halt_successful_poll;
    u64 halt_attempted_poll;
    u64 halt_successful_wait;
    u64 halt_poll_invalid;
    u64 halt_wakeup;
    u64 dbell_exits;
    u64 gdbell_exits;
    u64 ld;
    u64 st;
    u64 pf_storage;
    u64 pf_instruc;
    u64 sp_storage;
    u64 sp_instruc;
    u64 queue_intr;
    u64 ld_slow;
    u64 st_slow;
    u64 pthru_all;
    u64 pthru_host;
    u64 pthru_bad_aff;
}
```
</details>
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
struct kvm_vcpu_stat {
    u64 pf_fixed;
    u64 pf_guest;
    u64 tlb_flush;
    u64 invlpg;
    u64 exits;
    u64 io_exits;
    u64 mmio_exits;
    u64 signal_exits;
    u64 irq_window_exits;
    u64 nmi_window_exits;
    u64 l1d_flush;
    u64 halt_exits;
    u64 halt_successful_poll;
    u64 halt_attempted_poll;
    u64 halt_poll_invalid;
    u64 halt_wakeup;
    u64 request_irq_exits;
    u64 irq_exits;
    u64 host_state_reload;
    u64 fpu_reload;
    u64 insn_emulation;
    u64 insn_emulation_fail;
    u64 hypercalls;
    u64 irq_injections;
    u64 nmi_injections;
    u64 req_event;
    u64 halt_poll_success_ns;
    u64 halt_poll_fail_ns;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 nested_run</code>
</li>
<li>
<b>Field added. </b>
<code>u64 directed_yield_attempted</code>
</li>
<li>
<b>Field added. </b>
<code>u64 directed_yield_successful</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct kvm_vcpu_stat_generic generic</code>
</li>
<li>
<b>Field added. </b>
<code>u64 guest_mode</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 halt_successful_poll</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 halt_attempted_poll</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 halt_poll_invalid</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 halt_wakeup</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 halt_poll_success_ns</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 halt_poll_fail_ns</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 pf_taken</code>
</li>
<li>
<b>Field added. </b>
<code>u64 pf_emulate</code>
</li>
<li>
<b>Field added. </b>
<code>u64 pf_spurious</code>
</li>
<li>
<b>Field added. </b>
<code>u64 pf_fast</code>
</li>
<li>
<b>Field added. </b>
<code>u64 pf_mmio_spte_created</code>
</li>
<li>
<b>Field added. </b>
<code>u64 preemption_reported</code>
</li>
<li>
<b>Field added. </b>
<code>u64 preemption_other</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 notify_window_exits</code>
</li>
</ul>
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct kvm_vcpu_stat {
    u64 halt_successful_poll;
    u64 halt_attempted_poll;
    u64 halt_poll_invalid;
    u64 halt_wakeup;
    u64 hvc_exit_stat;
    u64 wfe_exit_stat;
    u64 wfi_exit_stat;
    u64 mmio_exit_user;
    u64 mmio_exit_kernel;
    u64 exits;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct kvm_vcpu_stat {
    u64 sum_exits;
    u64 mmio_exits;
    u64 signal_exits;
    u64 light_exits;
    u64 itlb_real_miss_exits;
    u64 itlb_virt_miss_exits;
    u64 dtlb_real_miss_exits;
    u64 dtlb_virt_miss_exits;
    u64 syscall_exits;
    u64 isi_exits;
    u64 dsi_exits;
    u64 emulated_inst_exits;
    u64 dec_exits;
    u64 ext_intr_exits;
    u64 halt_poll_success_ns;
    u64 halt_poll_fail_ns;
    u64 halt_wait_ns;
    u64 halt_successful_poll;
    u64 halt_attempted_poll;
    u64 halt_successful_wait;
    u64 halt_poll_invalid;
    u64 halt_wakeup;
    u64 dbell_exits;
    u64 gdbell_exits;
    u64 ld;
    u64 st;
    u64 pf_storage;
    u64 pf_instruc;
    u64 sp_storage;
    u64 sp_instruc;
    u64 queue_intr;
    u64 ld_slow;
    u64 st_slow;
    u64 pthru_all;
    u64 pthru_host;
    u64 pthru_bad_aff;
}
```
</details>
</li>
</ul>
