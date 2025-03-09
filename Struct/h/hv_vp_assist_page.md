# Struct: <code>hv_vp_assist_page</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct hv_vp_assist_page {
    __u32 apic_assist;
    __u32 reserved;
    __u64[2] vtl_control;
    __u64[2] nested_enlightenments_control;
    __u32 enlighten_vmentry;
    __u64 current_nested_vmcs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct hv_vp_assist_page {
    __u32 apic_assist;
    __u32 reserved;
    __u64[2] vtl_control;
    __u64[2] nested_enlightenments_control;
    __u32 enlighten_vmentry;
    __u32 padding;
    __u64 current_nested_vmcs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct hv_vp_assist_page {
    __u32 apic_assist;
    __u32 reserved;
    __u64[2] vtl_control;
    __u64[2] nested_enlightenments_control;
    __u32 enlighten_vmentry;
    __u32 padding;
    __u64 current_nested_vmcs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct hv_vp_assist_page {
    __u32 apic_assist;
    __u32 reserved1;
    __u64[3] vtl_control;
    struct hv_nested_enlightenments_control nested_control;
    __u8 enlighten_vmentry;
    __u8[7] reserved2;
    __u64 current_nested_vmcs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct hv_vp_assist_page {
    __u32 apic_assist;
    __u32 reserved1;
    __u64[3] vtl_control;
    struct hv_nested_enlightenments_control nested_control;
    __u8 enlighten_vmentry;
    __u8[7] reserved2;
    __u64 current_nested_vmcs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct hv_vp_assist_page {
    __u32 apic_assist;
    __u32 reserved1;
    __u64[3] vtl_control;
    struct hv_nested_enlightenments_control nested_control;
    __u8 enlighten_vmentry;
    __u8[7] reserved2;
    __u64 current_nested_vmcs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct hv_vp_assist_page {
    __u32 apic_assist;
    __u32 reserved1;
    __u64[3] vtl_control;
    struct hv_nested_enlightenments_control nested_control;
    __u8 enlighten_vmentry;
    __u8[7] reserved2;
    __u64 current_nested_vmcs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct hv_vp_assist_page {
    __u32 apic_assist;
    __u32 reserved1;
    __u64[3] vtl_control;
    struct hv_nested_enlightenments_control nested_control;
    __u8 enlighten_vmentry;
    __u8[7] reserved2;
    __u64 current_nested_vmcs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct hv_vp_assist_page {
    __u32 apic_assist;
    __u32 reserved1;
    __u64[3] vtl_control;
    struct hv_nested_enlightenments_control nested_control;
    __u8 enlighten_vmentry;
    __u8[7] reserved2;
    __u64 current_nested_vmcs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct hv_vp_assist_page {
    __u32 apic_assist;
    __u32 reserved1;
    __u32 vtl_entry_reason;
    __u32 vtl_reserved;
    __u64 vtl_ret_x64rax;
    __u64 vtl_ret_x64rcx;
    struct hv_nested_enlightenments_control nested_control;
    __u8 enlighten_vmentry;
    __u8[7] reserved2;
    __u64 current_nested_vmcs;
    __u8 synthetic_time_unhalted_timer_expired;
    __u8[7] reserved3;
    __u8[40] virtualization_fault_information;
    __u8[8] reserved4;
    __u8[256] intercept_message;
    __u8[256] vtl_ret_actions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct hv_vp_assist_page {
    __u32 apic_assist;
    __u32 reserved1;
    __u32 vtl_entry_reason;
    __u32 vtl_reserved;
    __u64 vtl_ret_x64rax;
    __u64 vtl_ret_x64rcx;
    struct hv_nested_enlightenments_control nested_control;
    __u8 enlighten_vmentry;
    __u8[7] reserved2;
    __u64 current_nested_vmcs;
    __u8 synthetic_time_unhalted_timer_expired;
    __u8[7] reserved3;
    __u8[40] virtualization_fault_information;
    __u8[8] reserved4;
    __u8[256] intercept_message;
    __u8[256] vtl_ret_actions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct hv_vp_assist_page {
    __u32 apic_assist;
    __u32 reserved1;
    __u32 vtl_entry_reason;
    __u32 vtl_reserved;
    __u64 vtl_ret_x64rax;
    __u64 vtl_ret_x64rcx;
    struct hv_nested_enlightenments_control nested_control;
    __u8 enlighten_vmentry;
    __u8[7] reserved2;
    __u64 current_nested_vmcs;
    __u8 synthetic_time_unhalted_timer_expired;
    __u8[7] reserved3;
    __u8[40] virtualization_fault_information;
    __u8[8] reserved4;
    __u8[256] intercept_message;
    __u8[256] vtl_ret_actions;
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct hv_vp_assist_page {
    __u32 apic_assist;
    __u32 reserved1;
    __u64[3] vtl_control;
    struct hv_nested_enlightenments_control nested_control;
    __u8 enlighten_vmentry;
    __u8[7] reserved2;
    __u64 current_nested_vmcs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct hv_vp_assist_page {
    __u32 apic_assist;
    __u32 reserved1;
    __u64[3] vtl_control;
    struct hv_nested_enlightenments_control nested_control;
    __u8 enlighten_vmentry;
    __u8[7] reserved2;
    __u64 current_nested_vmcs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct hv_vp_assist_page {
    __u32 apic_assist;
    __u32 reserved1;
    __u64[3] vtl_control;
    struct hv_nested_enlightenments_control nested_control;
    __u8 enlighten_vmentry;
    __u8[7] reserved2;
    __u64 current_nested_vmcs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct hv_vp_assist_page {
    __u32 apic_assist;
    __u32 reserved1;
    __u64[3] vtl_control;
    struct hv_nested_enlightenments_control nested_control;
    __u8 enlighten_vmentry;
    __u8[7] reserved2;
    __u64 current_nested_vmcs;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct hv_vp_assist_page {
    __u32 apic_assist;
    __u32 reserved;
    __u64[2] vtl_control;
    __u64[2] nested_enlightenments_control;
    __u32 enlighten_vmentry;
    __u64 current_nested_vmcs;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u32 padding</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u32 reserved1</code>
</li>
<li>
<b>Field added. </b>
<code>struct hv_nested_enlightenments_control nested_control</code>
</li>
<li>
<b>Field added. </b>
<code>__u8[7] reserved2</code>
</li>
<li>
<b>Field removed. </b>
<code>__u32 reserved</code>
</li>
<li>
<b>Field removed. </b>
<code>__u64[2] nested_enlightenments_control</code>
</li>
<li>
<b>Field removed. </b>
<code>__u32 padding</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u64[2] vtl_control</code> ➡️ <code>__u64[3] vtl_control</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 enlighten_vmentry</code> ➡️ <code>__u8 enlighten_vmentry</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u32 vtl_entry_reason</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 vtl_reserved</code>
</li>
<li>
<b>Field added. </b>
<code>__u64 vtl_ret_x64rax</code>
</li>
<li>
<b>Field added. </b>
<code>__u64 vtl_ret_x64rcx</code>
</li>
<li>
<b>Field added. </b>
<code>__u8 synthetic_time_unhalted_timer_expired</code>
</li>
<li>
<b>Field added. </b>
<code>__u8[7] reserved3</code>
</li>
<li>
<b>Field added. </b>
<code>__u8[40] virtualization_fault_information</code>
</li>
<li>
<b>Field added. </b>
<code>__u8[8] reserved4</code>
</li>
<li>
<b>Field added. </b>
<code>__u8[256] intercept_message</code>
</li>
<li>
<b>Field added. </b>
<code>__u8[256] vtl_ret_actions</code>
</li>
<li>
<b>Field removed. </b>
<code>__u64[3] vtl_control</code>
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct hv_vp_assist_page {
    __u32 apic_assist;
    __u32 reserved1;
    __u64[3] vtl_control;
    struct hv_nested_enlightenments_control nested_control;
    __u8 enlighten_vmentry;
    __u8[7] reserved2;
    __u64 current_nested_vmcs;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct hv_vp_assist_page {
    __u32 apic_assist;
    __u32 reserved1;
    __u64[3] vtl_control;
    struct hv_nested_enlightenments_control nested_control;
    __u8 enlighten_vmentry;
    __u8[7] reserved2;
    __u64 current_nested_vmcs;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct hv_vp_assist_page {
    __u32 apic_assist;
    __u32 reserved1;
    __u64[3] vtl_control;
    struct hv_nested_enlightenments_control nested_control;
    __u8 enlighten_vmentry;
    __u8[7] reserved2;
    __u64 current_nested_vmcs;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct hv_vp_assist_page {
    __u32 apic_assist;
    __u32 reserved1;
    __u64[3] vtl_control;
    struct hv_nested_enlightenments_control nested_control;
    __u8 enlighten_vmentry;
    __u8[7] reserved2;
    __u64 current_nested_vmcs;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
