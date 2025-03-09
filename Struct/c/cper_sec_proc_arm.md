# Struct: <code>cper_sec_proc_arm</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_proc_arm {
    __u32 validation_bits;
    __u16 err_info_num;
    __u16 context_info_num;
    __u32 section_length;
    __u8 affinity_level;
    __u8[3] reserved;
    __u64 mpidr;
    __u64 midr;
    __u32 running_state;
    __u32 psci_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_proc_arm {
    __u32 validation_bits;
    __u16 err_info_num;
    __u16 context_info_num;
    __u32 section_length;
    __u8 affinity_level;
    __u8[3] reserved;
    __u64 mpidr;
    __u64 midr;
    __u32 running_state;
    __u32 psci_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_proc_arm {
    __u32 validation_bits;
    __u16 err_info_num;
    __u16 context_info_num;
    __u32 section_length;
    __u8 affinity_level;
    __u8[3] reserved;
    __u64 mpidr;
    __u64 midr;
    __u32 running_state;
    __u32 psci_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_proc_arm {
    __u32 validation_bits;
    __u16 err_info_num;
    __u16 context_info_num;
    __u32 section_length;
    __u8 affinity_level;
    __u8[3] reserved;
    __u64 mpidr;
    __u64 midr;
    __u32 running_state;
    __u32 psci_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_proc_arm {
    u32 validation_bits;
    u16 err_info_num;
    u16 context_info_num;
    u32 section_length;
    u8 affinity_level;
    u8[3] reserved;
    u64 mpidr;
    u64 midr;
    u32 running_state;
    u32 psci_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_proc_arm {
    u32 validation_bits;
    u16 err_info_num;
    u16 context_info_num;
    u32 section_length;
    u8 affinity_level;
    u8[3] reserved;
    u64 mpidr;
    u64 midr;
    u32 running_state;
    u32 psci_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_proc_arm {
    u32 validation_bits;
    u16 err_info_num;
    u16 context_info_num;
    u32 section_length;
    u8 affinity_level;
    u8[3] reserved;
    u64 mpidr;
    u64 midr;
    u32 running_state;
    u32 psci_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_proc_arm {
    u32 validation_bits;
    u16 err_info_num;
    u16 context_info_num;
    u32 section_length;
    u8 affinity_level;
    u8[3] reserved;
    u64 mpidr;
    u64 midr;
    u32 running_state;
    u32 psci_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_proc_arm {
    u32 validation_bits;
    u16 err_info_num;
    u16 context_info_num;
    u32 section_length;
    u8 affinity_level;
    u8[3] reserved;
    u64 mpidr;
    u64 midr;
    u32 running_state;
    u32 psci_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_proc_arm {
    u32 validation_bits;
    u16 err_info_num;
    u16 context_info_num;
    u32 section_length;
    u8 affinity_level;
    u8[3] reserved;
    u64 mpidr;
    u64 midr;
    u32 running_state;
    u32 psci_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_proc_arm {
    u32 validation_bits;
    u16 err_info_num;
    u16 context_info_num;
    u32 section_length;
    u8 affinity_level;
    u8[3] reserved;
    u64 mpidr;
    u64 midr;
    u32 running_state;
    u32 psci_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_proc_arm {
    u32 validation_bits;
    u16 err_info_num;
    u16 context_info_num;
    u32 section_length;
    u8 affinity_level;
    u8[3] reserved;
    u64 mpidr;
    u64 midr;
    u32 running_state;
    u32 psci_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_proc_arm {
    u32 validation_bits;
    u16 err_info_num;
    u16 context_info_num;
    u32 section_length;
    u8 affinity_level;
    u8[3] reserved;
    u64 mpidr;
    u64 midr;
    u32 running_state;
    u32 psci_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_proc_arm {
    u32 validation_bits;
    u16 err_info_num;
    u16 context_info_num;
    u32 section_length;
    u8 affinity_level;
    u8[3] reserved;
    u64 mpidr;
    u64 midr;
    u32 running_state;
    u32 psci_state;
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
struct cper_sec_proc_arm {
    u32 validation_bits;
    u16 err_info_num;
    u16 context_info_num;
    u32 section_length;
    u8 affinity_level;
    u8[3] reserved;
    u64 mpidr;
    u64 midr;
    u32 running_state;
    u32 psci_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct cper_sec_proc_arm {
    u32 validation_bits;
    u16 err_info_num;
    u16 context_info_num;
    u32 section_length;
    u8 affinity_level;
    u8[3] reserved;
    u64 mpidr;
    u64 midr;
    u32 running_state;
    u32 psci_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct cper_sec_proc_arm {
    u32 validation_bits;
    u16 err_info_num;
    u16 context_info_num;
    u32 section_length;
    u8 affinity_level;
    u8[3] reserved;
    u64 mpidr;
    u64 midr;
    u32 running_state;
    u32 psci_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct cper_sec_proc_arm {
    u32 validation_bits;
    u16 err_info_num;
    u16 context_info_num;
    u32 section_length;
    u8 affinity_level;
    u8[3] reserved;
    u64 mpidr;
    u64 midr;
    u32 running_state;
    u32 psci_state;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct cper_sec_proc_arm {
    u32 validation_bits;
    u16 err_info_num;
    u16 context_info_num;
    u32 section_length;
    u8 affinity_level;
    u8[3] reserved;
    u64 mpidr;
    u64 midr;
    u32 running_state;
    u32 psci_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct cper_sec_proc_arm {
    u32 validation_bits;
    u16 err_info_num;
    u16 context_info_num;
    u32 section_length;
    u8 affinity_level;
    u8[3] reserved;
    u64 mpidr;
    u64 midr;
    u32 running_state;
    u32 psci_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct cper_sec_proc_arm {
    u32 validation_bits;
    u16 err_info_num;
    u16 context_info_num;
    u32 section_length;
    u8 affinity_level;
    u8[3] reserved;
    u64 mpidr;
    u64 midr;
    u32 running_state;
    u32 psci_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct cper_sec_proc_arm {
    u32 validation_bits;
    u16 err_info_num;
    u16 context_info_num;
    u32 section_length;
    u8 affinity_level;
    u8[3] reserved;
    u64 mpidr;
    u64 midr;
    u32 running_state;
    u32 psci_state;
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct cper_sec_proc_arm {
    __u32 validation_bits;
    __u16 err_info_num;
    __u16 context_info_num;
    __u32 section_length;
    __u8 affinity_level;
    __u8[3] reserved;
    __u64 mpidr;
    __u64 midr;
    __u32 running_state;
    __u32 psci_state;
}
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>__u32 validation_bits</code> ➡️ <code>u32 validation_bits</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u16 err_info_num</code> ➡️ <code>u16 err_info_num</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u16 context_info_num</code> ➡️ <code>u16 context_info_num</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 section_length</code> ➡️ <code>u32 section_length</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u8 affinity_level</code> ➡️ <code>u8 affinity_level</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u8[3] reserved</code> ➡️ <code>u8[3] reserved</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u64 mpidr</code> ➡️ <code>u64 mpidr</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u64 midr</code> ➡️ <code>u64 midr</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 running_state</code> ➡️ <code>u32 running_state</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 psci_state</code> ➡️ <code>u32 psci_state</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
