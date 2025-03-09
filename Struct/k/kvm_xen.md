# Struct: <code>kvm_xen</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct kvm_xen {
    bool long_mode;
    bool shinfo_set;
    u8 upcall_vector;
    struct gfn_to_hva_cache shinfo_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct kvm_xen {
    bool long_mode;
    u8 upcall_vector;
    gfn_t shinfo_gfn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct kvm_xen {
    u32 xen_version;
    bool long_mode;
    u8 upcall_vector;
    struct gfn_to_pfn_cache shinfo_cache;
    struct idr evtchn_ports;
    long unsigned int[16] poll_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct kvm_xen {
    struct mutex xen_lock;
    u32 xen_version;
    bool long_mode;
    bool runstate_update_flag;
    u8 upcall_vector;
    struct gfn_to_pfn_cache shinfo_cache;
    struct idr evtchn_ports;
    long unsigned int[16] poll_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct kvm_xen {
    struct mutex xen_lock;
    u32 xen_version;
    bool long_mode;
    bool runstate_update_flag;
    u8 upcall_vector;
    struct gfn_to_pfn_cache shinfo_cache;
    struct idr evtchn_ports;
    long unsigned int[16] poll_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct kvm_xen {
    struct mutex xen_lock;
    u32 xen_version;
    bool long_mode;
    bool runstate_update_flag;
    u8 upcall_vector;
    struct gfn_to_pfn_cache shinfo_cache;
    struct idr evtchn_ports;
    long unsigned int[64] poll_mask;
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct kvm_xen {
    bool long_mode;
    bool shinfo_set;
    u8 upcall_vector;
    struct gfn_to_hva_cache shinfo_cache;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>gfn_t shinfo_gfn</code>
</li>
<li>
<b>Field removed. </b>
<code>bool shinfo_set</code>
</li>
<li>
<b>Field removed. </b>
<code>struct gfn_to_hva_cache shinfo_cache</code>
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
<code>u32 xen_version</code>
</li>
<li>
<b>Field added. </b>
<code>struct gfn_to_pfn_cache shinfo_cache</code>
</li>
<li>
<b>Field added. </b>
<code>struct idr evtchn_ports</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int[16] poll_mask</code>
</li>
<li>
<b>Field removed. </b>
<code>gfn_t shinfo_gfn</code>
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
<code>struct mutex xen_lock</code>
</li>
<li>
<b>Field added. </b>
<code>bool runstate_update_flag</code>
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
<b>Field type changed. </b>
<code>long unsigned int[16] poll_mask</code> ➡️ <code>long unsigned int[64] poll_mask</code>
</li>
</ul>
</details>
</li>
</ul>
