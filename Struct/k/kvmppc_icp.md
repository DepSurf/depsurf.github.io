# Struct: <code>kvmppc_icp</code>

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
struct kvmppc_icp {
    struct kvm_vcpu * vcpu;
    long unsigned int server_num;
    union kvmppc_icp_state state;
    long unsigned int[16] resend_map;
    u32 rm_action;
    struct kvm_vcpu * rm_kick_target;
    struct kvmppc_icp * rm_resend_icp;
    u32 rm_reject;
    u32 rm_eoied_irq;
    long unsigned int n_rm_kick_vcpu;
    long unsigned int n_rm_check_resend;
    long unsigned int n_rm_notify_eoi;
    long unsigned int n_check_resend;
    long unsigned int n_reject;
    union kvmppc_icp_state rm_dbgstate;
    struct kvm_vcpu * rm_dbgtgt;
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
struct kvmppc_icp {
    struct kvm_vcpu * vcpu;
    long unsigned int server_num;
    union kvmppc_icp_state state;
    long unsigned int[16] resend_map;
    u32 rm_action;
    struct kvm_vcpu * rm_kick_target;
    struct kvmppc_icp * rm_resend_icp;
    u32 rm_reject;
    u32 rm_eoied_irq;
    long unsigned int n_rm_kick_vcpu;
    long unsigned int n_rm_check_resend;
    long unsigned int n_rm_notify_eoi;
    long unsigned int n_check_resend;
    long unsigned int n_reject;
    union kvmppc_icp_state rm_dbgstate;
    struct kvm_vcpu * rm_dbgtgt;
}
```
</details>
</li>
</ul>
