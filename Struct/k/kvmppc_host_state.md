# Struct: <code>kvmppc_host_state</code>

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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct kvmppc_host_state {
    ulong host_r1;
    ulong host_r2;
    ulong host_msr;
    ulong vmhandler;
    ulong scratch0;
    ulong scratch1;
    ulong scratch2;
    u8 in_guest;
    u8 restore_hid5;
    u8 napping;
    u8 hwthread_req;
    u8 hwthread_state;
    u8 host_ipi;
    u8 ptid;
    u8 tid;
    u8 fake_suspend;
    struct kvm_vcpu * kvm_vcpu;
    struct kvmppc_vcore * kvm_vcore;
    void * xics_phys;
    void * xive_tima_phys;
    void * xive_tima_virt;
    u32 saved_xirr;
    u64 dabr;
    u64[7] host_mmcr;
    u32[8] host_pmc;
    u64 host_purr;
    u64 host_spurr;
    u64 host_dscr;
    u64 dec_expires;
    struct kvm_split_mode * kvm_split_mode;
    u64 cfar;
    u64 ppr;
    u64 host_fscr;
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct kvmppc_host_state {
    ulong host_r1;
    ulong host_r2;
    ulong host_msr;
    ulong vmhandler;
    ulong scratch0;
    ulong scratch1;
    ulong scratch2;
    u8 in_guest;
    u8 restore_hid5;
    u8 napping;
    u8 hwthread_req;
    u8 hwthread_state;
    u8 host_ipi;
    u8 ptid;
    u8 tid;
    u8 fake_suspend;
    struct kvm_vcpu * kvm_vcpu;
    struct kvmppc_vcore * kvm_vcore;
    void * xics_phys;
    void * xive_tima_phys;
    void * xive_tima_virt;
    u32 saved_xirr;
    u64 dabr;
    u64[7] host_mmcr;
    u32[8] host_pmc;
    u64 host_purr;
    u64 host_spurr;
    u64 host_dscr;
    u64 dec_expires;
    struct kvm_split_mode * kvm_split_mode;
    u64 cfar;
    u64 ppr;
    u64 host_fscr;
}
```
</details>
</li>
</ul>
