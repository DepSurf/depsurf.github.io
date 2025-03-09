# Struct: <code>kvm_hv</code>

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
struct kvm_hv {
    struct mutex hv_lock;
    u64 hv_guest_os_id;
    u64 hv_hypercall;
    u64 hv_tsc_page;
    u64[5] hv_crash_param;
    u64 hv_crash_ctl;
    struct ms_hyperv_tsc_page tsc_ref;
    struct idr conn_to_evt;
    u64 hv_reenlightenment_control;
    u64 hv_tsc_emulation_control;
    u64 hv_tsc_emulation_status;
    atomic_t num_mismatched_vp_indexes;
    struct hv_partition_assist_pg * hv_pa_pg;
    struct kvm_hv_syndbg hv_syndbg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct kvm_hv {
    struct mutex hv_lock;
    u64 hv_guest_os_id;
    u64 hv_hypercall;
    u64 hv_tsc_page;
    enum hv_tsc_page_status hv_tsc_page_status;
    u64[5] hv_crash_param;
    u64 hv_crash_ctl;
    struct ms_hyperv_tsc_page tsc_ref;
    struct idr conn_to_evt;
    u64 hv_reenlightenment_control;
    u64 hv_tsc_emulation_control;
    u64 hv_tsc_emulation_status;
    atomic_t num_mismatched_vp_indexes;
    struct hv_partition_assist_pg * hv_pa_pg;
    struct kvm_hv_syndbg hv_syndbg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct kvm_hv {
    struct mutex hv_lock;
    u64 hv_guest_os_id;
    u64 hv_hypercall;
    u64 hv_tsc_page;
    enum hv_tsc_page_status hv_tsc_page_status;
    u64[5] hv_crash_param;
    u64 hv_crash_ctl;
    struct ms_hyperv_tsc_page tsc_ref;
    struct idr conn_to_evt;
    u64 hv_reenlightenment_control;
    u64 hv_tsc_emulation_control;
    u64 hv_tsc_emulation_status;
    atomic_t num_mismatched_vp_indexes;
    unsigned int synic_auto_eoi_used;
    struct hv_partition_assist_pg * hv_pa_pg;
    struct kvm_hv_syndbg hv_syndbg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct kvm_hv {
    struct mutex hv_lock;
    u64 hv_guest_os_id;
    u64 hv_hypercall;
    u64 hv_tsc_page;
    enum hv_tsc_page_status hv_tsc_page_status;
    u64[5] hv_crash_param;
    u64 hv_crash_ctl;
    struct ms_hyperv_tsc_page tsc_ref;
    struct idr conn_to_evt;
    u64 hv_reenlightenment_control;
    u64 hv_tsc_emulation_control;
    u64 hv_tsc_emulation_status;
    atomic_t num_mismatched_vp_indexes;
    unsigned int synic_auto_eoi_used;
    struct hv_partition_assist_pg * hv_pa_pg;
    struct kvm_hv_syndbg hv_syndbg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct kvm_hv {
    struct mutex hv_lock;
    u64 hv_guest_os_id;
    u64 hv_hypercall;
    u64 hv_tsc_page;
    enum hv_tsc_page_status hv_tsc_page_status;
    u64[5] hv_crash_param;
    u64 hv_crash_ctl;
    struct ms_hyperv_tsc_page tsc_ref;
    struct idr conn_to_evt;
    u64 hv_reenlightenment_control;
    u64 hv_tsc_emulation_control;
    u64 hv_tsc_emulation_status;
    atomic_t num_mismatched_vp_indexes;
    unsigned int synic_auto_eoi_used;
    struct hv_partition_assist_pg * hv_pa_pg;
    struct kvm_hv_syndbg hv_syndbg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct kvm_hv {
    struct mutex hv_lock;
    u64 hv_guest_os_id;
    u64 hv_hypercall;
    u64 hv_tsc_page;
    enum hv_tsc_page_status hv_tsc_page_status;
    u64[5] hv_crash_param;
    u64 hv_crash_ctl;
    struct ms_hyperv_tsc_page tsc_ref;
    struct idr conn_to_evt;
    u64 hv_reenlightenment_control;
    u64 hv_tsc_emulation_control;
    u64 hv_tsc_emulation_status;
    u64 hv_invtsc_control;
    atomic_t num_mismatched_vp_indexes;
    unsigned int synic_auto_eoi_used;
    struct hv_partition_assist_pg * hv_pa_pg;
    struct kvm_hv_syndbg hv_syndbg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct kvm_hv {
    struct mutex hv_lock;
    u64 hv_guest_os_id;
    u64 hv_hypercall;
    u64 hv_tsc_page;
    enum hv_tsc_page_status hv_tsc_page_status;
    u64[5] hv_crash_param;
    u64 hv_crash_ctl;
    struct ms_hyperv_tsc_page tsc_ref;
    struct idr conn_to_evt;
    u64 hv_reenlightenment_control;
    u64 hv_tsc_emulation_control;
    u64 hv_tsc_emulation_status;
    u64 hv_invtsc_control;
    atomic_t num_mismatched_vp_indexes;
    unsigned int synic_auto_eoi_used;
    struct kvm_hv_syndbg hv_syndbg;
    bool xsaves_xsavec_checked;
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
struct kvm_hv {
    struct mutex hv_lock;
    u64 hv_guest_os_id;
    u64 hv_hypercall;
    u64 hv_tsc_page;
    u64[5] hv_crash_param;
    u64 hv_crash_ctl;
    struct ms_hyperv_tsc_page tsc_ref;
    struct idr conn_to_evt;
    u64 hv_reenlightenment_control;
    u64 hv_tsc_emulation_control;
    u64 hv_tsc_emulation_status;
    atomic_t num_mismatched_vp_indexes;
    struct hv_partition_assist_pg * hv_pa_pg;
    struct kvm_hv_syndbg hv_syndbg;
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
<code>enum hv_tsc_page_status hv_tsc_page_status</code>
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
<code>unsigned int synic_auto_eoi_used</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 hv_invtsc_control</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool xsaves_xsavec_checked</code>
</li>
<li>
<b>Field removed. </b>
<code>struct hv_partition_assist_pg * hv_pa_pg</code>
</li>
</ul>
</details>
</li>
</ul>
