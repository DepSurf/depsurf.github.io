# Struct: <code>kvmppc_mmu</code>

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
struct kvmppc_mmu {
    void (*)(struct kvm_vcpu *, u64, u64) slbmte;
    u64 (*)(struct kvm_vcpu *, u64) slbmfee;
    u64 (*)(struct kvm_vcpu *, u64) slbmfev;
    int (*)(struct kvm_vcpu *, gva_t, ulong *) slbfee;
    void (*)(struct kvm_vcpu *, u64) slbie;
    void (*)(struct kvm_vcpu *) slbia;
    void (*)(struct kvm_vcpu *, u32, ulong) mtsrin;
    u32 (*)(struct kvm_vcpu *, u32) mfsrin;
    int (*)(struct kvm_vcpu *, gva_t, struct kvmppc_pte *, bool, bool) xlate;
    void (*)(struct kvm_vcpu *) reset_msr;
    void (*)(struct kvm_vcpu *, ulong, bool) tlbie;
    int (*)(struct kvm_vcpu *, ulong, u64 *) esid_to_vsid;
    u64 (*)(struct kvm_vcpu *, gva_t, bool) ea_to_vp;
    bool (*)(struct kvm_vcpu *) is_dcbz32;
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
struct kvmppc_mmu {
    void (*)(struct kvm_vcpu *, u64, u64) slbmte;
    u64 (*)(struct kvm_vcpu *, u64) slbmfee;
    u64 (*)(struct kvm_vcpu *, u64) slbmfev;
    int (*)(struct kvm_vcpu *, gva_t, ulong *) slbfee;
    void (*)(struct kvm_vcpu *, u64) slbie;
    void (*)(struct kvm_vcpu *) slbia;
    void (*)(struct kvm_vcpu *, u32, ulong) mtsrin;
    u32 (*)(struct kvm_vcpu *, u32) mfsrin;
    int (*)(struct kvm_vcpu *, gva_t, struct kvmppc_pte *, bool, bool) xlate;
    void (*)(struct kvm_vcpu *) reset_msr;
    void (*)(struct kvm_vcpu *, ulong, bool) tlbie;
    int (*)(struct kvm_vcpu *, ulong, u64 *) esid_to_vsid;
    u64 (*)(struct kvm_vcpu *, gva_t, bool) ea_to_vp;
    bool (*)(struct kvm_vcpu *) is_dcbz32;
}
```
</details>
</li>
</ul>
