# Struct: <code>kvm_vcpu_hv</code>

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
struct kvm_vcpu_hv {
    u32 vp_index;
    u64 hv_vapic;
    s64 runtime_offset;
    struct kvm_vcpu_hv_synic synic;
    struct kvm_hyperv_exit exit;
    struct kvm_vcpu_hv_stimer[4] stimer;
    long unsigned int[1] stimer_pending_bitmap;
    cpumask_t tlb_flush;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct kvm_vcpu_hv {
    struct kvm_vcpu * vcpu;
    u32 vp_index;
    u64 hv_vapic;
    s64 runtime_offset;
    struct kvm_vcpu_hv_synic synic;
    struct kvm_hyperv_exit exit;
    struct kvm_vcpu_hv_stimer[4] stimer;
    long unsigned int[1] stimer_pending_bitmap;
    cpumask_t tlb_flush;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct kvm_vcpu_hv {
    struct kvm_vcpu * vcpu;
    u32 vp_index;
    u64 hv_vapic;
    s64 runtime_offset;
    struct kvm_vcpu_hv_synic synic;
    struct kvm_hyperv_exit exit;
    struct kvm_vcpu_hv_stimer[4] stimer;
    long unsigned int[1] stimer_pending_bitmap;
    cpumask_t tlb_flush;
    bool enforce_cpuid;
    struct (anon) cpuid_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct kvm_vcpu_hv {
    struct kvm_vcpu * vcpu;
    u32 vp_index;
    u64 hv_vapic;
    s64 runtime_offset;
    struct kvm_vcpu_hv_synic synic;
    struct kvm_hyperv_exit exit;
    struct kvm_vcpu_hv_stimer[4] stimer;
    long unsigned int[1] stimer_pending_bitmap;
    bool enforce_cpuid;
    struct (anon) cpuid_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct kvm_vcpu_hv {
    struct kvm_vcpu * vcpu;
    u32 vp_index;
    u64 hv_vapic;
    s64 runtime_offset;
    struct kvm_vcpu_hv_synic synic;
    struct kvm_hyperv_exit exit;
    struct kvm_vcpu_hv_stimer[4] stimer;
    long unsigned int[1] stimer_pending_bitmap;
    bool enforce_cpuid;
    struct (anon) cpuid_cache;
    struct kvm_vcpu_hv_tlb_flush_fifo[2] tlb_flush_fifo;
    u64[64] sparse_banks;
    struct hv_vp_assist_page vp_assist_page;
    struct (anon) nested;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct kvm_vcpu_hv {
    struct kvm_vcpu * vcpu;
    u32 vp_index;
    u64 hv_vapic;
    s64 runtime_offset;
    struct kvm_vcpu_hv_synic synic;
    struct kvm_hyperv_exit exit;
    struct kvm_vcpu_hv_stimer[4] stimer;
    long unsigned int[1] stimer_pending_bitmap;
    bool enforce_cpuid;
    struct (anon) cpuid_cache;
    struct kvm_vcpu_hv_tlb_flush_fifo[2] tlb_flush_fifo;
    u64[64] sparse_banks;
    struct hv_vp_assist_page vp_assist_page;
    struct (anon) nested;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct kvm_vcpu_hv {
    struct kvm_vcpu * vcpu;
    u32 vp_index;
    u64 hv_vapic;
    s64 runtime_offset;
    struct kvm_vcpu_hv_synic synic;
    struct kvm_hyperv_exit exit;
    struct kvm_vcpu_hv_stimer[4] stimer;
    long unsigned int[1] stimer_pending_bitmap;
    bool enforce_cpuid;
    struct (anon) cpuid_cache;
    struct kvm_vcpu_hv_tlb_flush_fifo[2] tlb_flush_fifo;
    u64[64] sparse_banks;
    struct hv_vp_assist_page vp_assist_page;
    struct (anon) nested;
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
struct kvm_vcpu_hv {
    u32 vp_index;
    u64 hv_vapic;
    s64 runtime_offset;
    struct kvm_vcpu_hv_synic synic;
    struct kvm_hyperv_exit exit;
    struct kvm_vcpu_hv_stimer[4] stimer;
    long unsigned int[1] stimer_pending_bitmap;
    cpumask_t tlb_flush;
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
<code>struct kvm_vcpu * vcpu</code>
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
<code>bool enforce_cpuid</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) cpuid_cache</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>cpumask_t tlb_flush</code>
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
<code>struct kvm_vcpu_hv_tlb_flush_fifo[2] tlb_flush_fifo</code>
</li>
<li>
<b>Field added. </b>
<code>u64[64] sparse_banks</code>
</li>
<li>
<b>Field added. </b>
<code>struct hv_vp_assist_page vp_assist_page</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) nested</code>
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
