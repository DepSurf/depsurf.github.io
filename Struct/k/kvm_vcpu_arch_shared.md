# Struct: <code>kvm_vcpu_arch_shared</code>

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
struct kvm_vcpu_arch_shared {
    __u64 scratch1;
    __u64 scratch2;
    __u64 scratch3;
    __u64 critical;
    __u64 sprg0;
    __u64 sprg1;
    __u64 sprg2;
    __u64 sprg3;
    __u64 srr0;
    __u64 srr1;
    __u64 dar;
    __u64 msr;
    __u32 dsisr;
    __u32 int_pending;
    __u32[16] sr;
    __u32 mas0;
    __u32 mas1;
    __u64 mas7_3;
    __u64 mas2;
    __u32 mas4;
    __u32 mas6;
    __u32 esr;
    __u32 pir;
    __u64 sprg4;
    __u64 sprg5;
    __u64 sprg6;
    __u64 sprg7;
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
struct kvm_vcpu_arch_shared {
    __u64 scratch1;
    __u64 scratch2;
    __u64 scratch3;
    __u64 critical;
    __u64 sprg0;
    __u64 sprg1;
    __u64 sprg2;
    __u64 sprg3;
    __u64 srr0;
    __u64 srr1;
    __u64 dar;
    __u64 msr;
    __u32 dsisr;
    __u32 int_pending;
    __u32[16] sr;
    __u32 mas0;
    __u32 mas1;
    __u64 mas7_3;
    __u64 mas2;
    __u32 mas4;
    __u32 mas6;
    __u32 esr;
    __u32 pir;
    __u64 sprg4;
    __u64 sprg5;
    __u64 sprg6;
    __u64 sprg7;
}
```
</details>
</li>
</ul>
