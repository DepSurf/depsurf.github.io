# Struct: <code>kvmppc_xive_vcpu</code>

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
struct kvmppc_xive_vcpu {
    struct kvmppc_xive * xive;
    struct kvm_vcpu * vcpu;
    bool valid;
    u32 server_num;
    u32 vp_id;
    u32 vp_chip_id;
    u32 vp_cam;
    u32 vp_ipi;
    struct xive_irq_data vp_ipi_data;
    uint8_t cppr;
    uint8_t hw_cppr;
    uint8_t mfrr;
    uint8_t pending;
    struct xive_q[8] queues;
    u32[8] esc_virq;
    char *[8] esc_virq_names;
    u32 delayed_irq;
    u64 stat_rm_h_xirr;
    u64 stat_rm_h_ipoll;
    u64 stat_rm_h_cppr;
    u64 stat_rm_h_eoi;
    u64 stat_rm_h_ipi;
    u64 stat_vm_h_xirr;
    u64 stat_vm_h_ipoll;
    u64 stat_vm_h_cppr;
    u64 stat_vm_h_eoi;
    u64 stat_vm_h_ipi;
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
struct kvmppc_xive_vcpu {
    struct kvmppc_xive * xive;
    struct kvm_vcpu * vcpu;
    bool valid;
    u32 server_num;
    u32 vp_id;
    u32 vp_chip_id;
    u32 vp_cam;
    u32 vp_ipi;
    struct xive_irq_data vp_ipi_data;
    uint8_t cppr;
    uint8_t hw_cppr;
    uint8_t mfrr;
    uint8_t pending;
    struct xive_q[8] queues;
    u32[8] esc_virq;
    char *[8] esc_virq_names;
    u32 delayed_irq;
    u64 stat_rm_h_xirr;
    u64 stat_rm_h_ipoll;
    u64 stat_rm_h_cppr;
    u64 stat_rm_h_eoi;
    u64 stat_rm_h_ipi;
    u64 stat_vm_h_xirr;
    u64 stat_vm_h_ipoll;
    u64 stat_vm_h_cppr;
    u64 stat_vm_h_eoi;
    u64 stat_vm_h_ipi;
}
```
</details>
</li>
</ul>
