# Struct: <code>kvm_run</code>

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
struct kvm_run {
    __u8 request_interrupt_window;
    __u8 immediate_exit;
    __u8[6] padding1;
    __u32 exit_reason;
    __u8 ready_for_interrupt_injection;
    __u8 if_flag;
    __u16 flags;
    __u64 cr8;
    __u64 apic_base;
    struct (anon) hw;
    struct (anon) fail_entry;
    struct (anon) ex;
    struct (anon) io;
    struct (anon) debug;
    struct (anon) mmio;
    struct (anon) hypercall;
    struct (anon) tpr_access;
    struct (anon) s390_sieic;
    __u64 s390_reset_flags;
    struct (anon) s390_ucontrol;
    struct (anon) dcr;
    struct (anon) internal;
    struct (anon) osi;
    struct (anon) papr_hcall;
    struct (anon) s390_tsch;
    struct (anon) epr;
    struct (anon) system_event;
    struct (anon) s390_stsi;
    struct (anon) eoi;
    struct kvm_hyperv_exit hyperv;
    struct (anon) arm_nisv;
    struct (anon) msr;
    char[256] padding;
    __u64 kvm_valid_regs;
    __u64 kvm_dirty_regs;
    union (anon) s;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct kvm_run {
    __u8 request_interrupt_window;
    __u8 immediate_exit;
    __u8[6] padding1;
    __u32 exit_reason;
    __u8 ready_for_interrupt_injection;
    __u8 if_flag;
    __u16 flags;
    __u64 cr8;
    __u64 apic_base;
    struct (anon) hw;
    struct (anon) fail_entry;
    struct (anon) ex;
    struct (anon) io;
    struct (anon) debug;
    struct (anon) mmio;
    struct (anon) hypercall;
    struct (anon) tpr_access;
    struct (anon) s390_sieic;
    __u64 s390_reset_flags;
    struct (anon) s390_ucontrol;
    struct (anon) dcr;
    struct (anon) internal;
    struct (anon) osi;
    struct (anon) papr_hcall;
    struct (anon) s390_tsch;
    struct (anon) epr;
    struct (anon) system_event;
    struct (anon) s390_stsi;
    struct (anon) eoi;
    struct kvm_hyperv_exit hyperv;
    struct (anon) arm_nisv;
    struct (anon) msr;
    struct kvm_xen_exit xen;
    char[256] padding;
    __u64 kvm_valid_regs;
    __u64 kvm_dirty_regs;
    union (anon) s;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct kvm_run {
    __u8 request_interrupt_window;
    __u8 immediate_exit;
    __u8[6] padding1;
    __u32 exit_reason;
    __u8 ready_for_interrupt_injection;
    __u8 if_flag;
    __u16 flags;
    __u64 cr8;
    __u64 apic_base;
    struct (anon) hw;
    struct (anon) fail_entry;
    struct (anon) ex;
    struct (anon) io;
    struct (anon) debug;
    struct (anon) mmio;
    struct (anon) hypercall;
    struct (anon) tpr_access;
    struct (anon) s390_sieic;
    __u64 s390_reset_flags;
    struct (anon) s390_ucontrol;
    struct (anon) dcr;
    struct (anon) internal;
    struct (anon) emulation_failure;
    struct (anon) osi;
    struct (anon) papr_hcall;
    struct (anon) s390_tsch;
    struct (anon) epr;
    struct (anon) system_event;
    struct (anon) s390_stsi;
    struct (anon) eoi;
    struct kvm_hyperv_exit hyperv;
    struct (anon) arm_nisv;
    struct (anon) msr;
    struct kvm_xen_exit xen;
    char[256] padding;
    __u64 kvm_valid_regs;
    __u64 kvm_dirty_regs;
    union (anon) s;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct kvm_run {
    __u8 request_interrupt_window;
    __u8 immediate_exit;
    __u8[6] padding1;
    __u32 exit_reason;
    __u8 ready_for_interrupt_injection;
    __u8 if_flag;
    __u16 flags;
    __u64 cr8;
    __u64 apic_base;
    struct (anon) hw;
    struct (anon) fail_entry;
    struct (anon) ex;
    struct (anon) io;
    struct (anon) debug;
    struct (anon) mmio;
    struct (anon) hypercall;
    struct (anon) tpr_access;
    struct (anon) s390_sieic;
    __u64 s390_reset_flags;
    struct (anon) s390_ucontrol;
    struct (anon) dcr;
    struct (anon) internal;
    struct (anon) emulation_failure;
    struct (anon) osi;
    struct (anon) papr_hcall;
    struct (anon) s390_tsch;
    struct (anon) epr;
    struct (anon) system_event;
    struct (anon) s390_stsi;
    struct (anon) eoi;
    struct kvm_hyperv_exit hyperv;
    struct (anon) arm_nisv;
    struct (anon) msr;
    struct kvm_xen_exit xen;
    struct (anon) riscv_sbi;
    char[256] padding;
    __u64 kvm_valid_regs;
    __u64 kvm_dirty_regs;
    union (anon) s;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct kvm_run {
    __u8 request_interrupt_window;
    __u8 immediate_exit;
    __u8[6] padding1;
    __u32 exit_reason;
    __u8 ready_for_interrupt_injection;
    __u8 if_flag;
    __u16 flags;
    __u64 cr8;
    __u64 apic_base;
    struct (anon) hw;
    struct (anon) fail_entry;
    struct (anon) ex;
    struct (anon) io;
    struct (anon) debug;
    struct (anon) mmio;
    struct (anon) hypercall;
    struct (anon) tpr_access;
    struct (anon) s390_sieic;
    __u64 s390_reset_flags;
    struct (anon) s390_ucontrol;
    struct (anon) dcr;
    struct (anon) internal;
    struct (anon) emulation_failure;
    struct (anon) osi;
    struct (anon) papr_hcall;
    struct (anon) s390_tsch;
    struct (anon) epr;
    struct (anon) system_event;
    struct (anon) s390_stsi;
    struct (anon) eoi;
    struct kvm_hyperv_exit hyperv;
    struct (anon) arm_nisv;
    struct (anon) msr;
    struct kvm_xen_exit xen;
    struct (anon) riscv_sbi;
    struct (anon) riscv_csr;
    struct (anon) notify;
    char[256] padding;
    __u64 kvm_valid_regs;
    __u64 kvm_dirty_regs;
    union (anon) s;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct kvm_run {
    __u8 request_interrupt_window;
    __u8 immediate_exit;
    __u8[6] padding1;
    __u32 exit_reason;
    __u8 ready_for_interrupt_injection;
    __u8 if_flag;
    __u16 flags;
    __u64 cr8;
    __u64 apic_base;
    struct (anon) hw;
    struct (anon) fail_entry;
    struct (anon) ex;
    struct (anon) io;
    struct (anon) debug;
    struct (anon) mmio;
    struct (anon) hypercall;
    struct (anon) tpr_access;
    struct (anon) s390_sieic;
    __u64 s390_reset_flags;
    struct (anon) s390_ucontrol;
    struct (anon) dcr;
    struct (anon) internal;
    struct (anon) emulation_failure;
    struct (anon) osi;
    struct (anon) papr_hcall;
    struct (anon) s390_tsch;
    struct (anon) epr;
    struct (anon) system_event;
    struct (anon) s390_stsi;
    struct (anon) eoi;
    struct kvm_hyperv_exit hyperv;
    struct (anon) arm_nisv;
    struct (anon) msr;
    struct kvm_xen_exit xen;
    struct (anon) riscv_sbi;
    struct (anon) riscv_csr;
    struct (anon) notify;
    char[256] padding;
    __u64 kvm_valid_regs;
    __u64 kvm_dirty_regs;
    union (anon) s;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct kvm_run {
    __u8 request_interrupt_window;
    __u8 immediate_exit;
    __u8[6] padding1;
    __u32 exit_reason;
    __u8 ready_for_interrupt_injection;
    __u8 if_flag;
    __u16 flags;
    __u64 cr8;
    __u64 apic_base;
    struct (anon) hw;
    struct (anon) fail_entry;
    struct (anon) ex;
    struct (anon) io;
    struct (anon) debug;
    struct (anon) mmio;
    struct (anon) iocsr_io;
    struct (anon) hypercall;
    struct (anon) tpr_access;
    struct (anon) s390_sieic;
    __u64 s390_reset_flags;
    struct (anon) s390_ucontrol;
    struct (anon) dcr;
    struct (anon) internal;
    struct (anon) emulation_failure;
    struct (anon) osi;
    struct (anon) papr_hcall;
    struct (anon) s390_tsch;
    struct (anon) epr;
    struct (anon) system_event;
    struct (anon) s390_stsi;
    struct (anon) eoi;
    struct kvm_hyperv_exit hyperv;
    struct (anon) arm_nisv;
    struct (anon) msr;
    struct kvm_xen_exit xen;
    struct (anon) riscv_sbi;
    struct (anon) riscv_csr;
    struct (anon) notify;
    struct (anon) memory_fault;
    char[256] padding;
    __u64 kvm_valid_regs;
    __u64 kvm_dirty_regs;
    union (anon) s;
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
struct kvm_run {
    __u8 request_interrupt_window;
    __u8 immediate_exit;
    __u8[6] padding1;
    __u32 exit_reason;
    __u8 ready_for_interrupt_injection;
    __u8 if_flag;
    __u16 flags;
    __u64 cr8;
    __u64 apic_base;
    struct (anon) hw;
    struct (anon) fail_entry;
    struct (anon) ex;
    struct (anon) io;
    struct (anon) debug;
    struct (anon) mmio;
    struct (anon) hypercall;
    struct (anon) tpr_access;
    struct (anon) s390_sieic;
    __u64 s390_reset_flags;
    struct (anon) s390_ucontrol;
    struct (anon) dcr;
    struct (anon) internal;
    struct (anon) osi;
    struct (anon) papr_hcall;
    struct (anon) s390_tsch;
    struct (anon) epr;
    struct (anon) system_event;
    struct (anon) s390_stsi;
    struct (anon) eoi;
    struct kvm_hyperv_exit hyperv;
    char[256] padding;
    __u64 kvm_valid_regs;
    __u64 kvm_dirty_regs;
    union (anon) s;
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
struct kvm_run {
    __u8 request_interrupt_window;
    __u8 immediate_exit;
    __u8[6] padding1;
    __u32 exit_reason;
    __u8 ready_for_interrupt_injection;
    __u8 if_flag;
    __u16 flags;
    __u64 cr8;
    __u64 apic_base;
    struct (anon) hw;
    struct (anon) fail_entry;
    struct (anon) ex;
    struct (anon) io;
    struct (anon) debug;
    struct (anon) mmio;
    struct (anon) hypercall;
    struct (anon) tpr_access;
    struct (anon) s390_sieic;
    __u64 s390_reset_flags;
    struct (anon) s390_ucontrol;
    struct (anon) dcr;
    struct (anon) internal;
    struct (anon) osi;
    struct (anon) papr_hcall;
    struct (anon) s390_tsch;
    struct (anon) epr;
    struct (anon) system_event;
    struct (anon) s390_stsi;
    struct (anon) eoi;
    struct kvm_hyperv_exit hyperv;
    char[256] padding;
    __u64 kvm_valid_regs;
    __u64 kvm_dirty_regs;
    union (anon) s;
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
struct kvm_run {
    __u8 request_interrupt_window;
    __u8 immediate_exit;
    __u8[6] padding1;
    __u32 exit_reason;
    __u8 ready_for_interrupt_injection;
    __u8 if_flag;
    __u16 flags;
    __u64 cr8;
    __u64 apic_base;
    struct (anon) hw;
    struct (anon) fail_entry;
    struct (anon) ex;
    struct (anon) io;
    struct (anon) debug;
    struct (anon) mmio;
    struct (anon) hypercall;
    struct (anon) tpr_access;
    struct (anon) s390_sieic;
    __u64 s390_reset_flags;
    struct (anon) s390_ucontrol;
    struct (anon) dcr;
    struct (anon) internal;
    struct (anon) osi;
    struct (anon) papr_hcall;
    struct (anon) s390_tsch;
    struct (anon) epr;
    struct (anon) system_event;
    struct (anon) s390_stsi;
    struct (anon) eoi;
    struct kvm_hyperv_exit hyperv;
    struct (anon) arm_nisv;
    struct (anon) msr;
    char[256] padding;
    __u64 kvm_valid_regs;
    __u64 kvm_dirty_regs;
    union (anon) s;
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
<code>struct kvm_xen_exit xen</code>
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
<code>struct (anon) emulation_failure</code>
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
<code>struct (anon) riscv_sbi</code>
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
<code>struct (anon) riscv_csr</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) notify</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct (anon) iocsr_io</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) memory_fault</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct kvm_run {
    __u8 request_interrupt_window;
    __u8 immediate_exit;
    __u8[6] padding1;
    __u32 exit_reason;
    __u8 ready_for_interrupt_injection;
    __u8 if_flag;
    __u16 flags;
    __u64 cr8;
    __u64 apic_base;
    struct (anon) hw;
    struct (anon) fail_entry;
    struct (anon) ex;
    struct (anon) io;
    struct (anon) debug;
    struct (anon) mmio;
    struct (anon) hypercall;
    struct (anon) tpr_access;
    struct (anon) s390_sieic;
    __u64 s390_reset_flags;
    struct (anon) s390_ucontrol;
    struct (anon) dcr;
    struct (anon) internal;
    struct (anon) osi;
    struct (anon) papr_hcall;
    struct (anon) s390_tsch;
    struct (anon) epr;
    struct (anon) system_event;
    struct (anon) s390_stsi;
    struct (anon) eoi;
    struct kvm_hyperv_exit hyperv;
    char[256] padding;
    __u64 kvm_valid_regs;
    __u64 kvm_dirty_regs;
    union (anon) s;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct kvm_run {
    __u8 request_interrupt_window;
    __u8 immediate_exit;
    __u8[6] padding1;
    __u32 exit_reason;
    __u8 ready_for_interrupt_injection;
    __u8 if_flag;
    __u16 flags;
    __u64 cr8;
    __u64 apic_base;
    struct (anon) hw;
    struct (anon) fail_entry;
    struct (anon) ex;
    struct (anon) io;
    struct (anon) debug;
    struct (anon) mmio;
    struct (anon) hypercall;
    struct (anon) tpr_access;
    struct (anon) s390_sieic;
    __u64 s390_reset_flags;
    struct (anon) s390_ucontrol;
    struct (anon) dcr;
    struct (anon) internal;
    struct (anon) osi;
    struct (anon) papr_hcall;
    struct (anon) s390_tsch;
    struct (anon) epr;
    struct (anon) system_event;
    struct (anon) s390_stsi;
    struct (anon) eoi;
    struct kvm_hyperv_exit hyperv;
    char[256] padding;
    __u64 kvm_valid_regs;
    __u64 kvm_dirty_regs;
    union (anon) s;
}
```
</details>
</li>
</ul>
