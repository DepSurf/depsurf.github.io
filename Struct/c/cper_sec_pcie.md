# Struct: <code>cper_sec_pcie</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_pcie {
    __u64 validation_bits;
    __u32 port_type;
    struct (anon) version;
    __u16 command;
    __u16 status;
    __u32 reserved;
    struct (anon) device_id;
    struct (anon) serial_number;
    struct (anon) bridge;
    __u8[60] capability;
    __u8[96] aer_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_pcie {
    __u64 validation_bits;
    __u32 port_type;
    struct (anon) version;
    __u16 command;
    __u16 status;
    __u32 reserved;
    struct (anon) device_id;
    struct (anon) serial_number;
    struct (anon) bridge;
    __u8[60] capability;
    __u8[96] aer_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_pcie {
    __u64 validation_bits;
    __u32 port_type;
    struct (anon) version;
    __u16 command;
    __u16 status;
    __u32 reserved;
    struct (anon) device_id;
    struct (anon) serial_number;
    struct (anon) bridge;
    __u8[60] capability;
    __u8[96] aer_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_pcie {
    __u64 validation_bits;
    __u32 port_type;
    struct (anon) version;
    __u16 command;
    __u16 status;
    __u32 reserved;
    struct (anon) device_id;
    struct (anon) serial_number;
    struct (anon) bridge;
    __u8[60] capability;
    __u8[96] aer_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_pcie {
    __u64 validation_bits;
    __u32 port_type;
    struct (anon) version;
    __u16 command;
    __u16 status;
    __u32 reserved;
    struct (anon) device_id;
    struct (anon) serial_number;
    struct (anon) bridge;
    __u8[60] capability;
    __u8[96] aer_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_pcie {
    __u64 validation_bits;
    __u32 port_type;
    struct (anon) version;
    __u16 command;
    __u16 status;
    __u32 reserved;
    struct (anon) device_id;
    struct (anon) serial_number;
    struct (anon) bridge;
    __u8[60] capability;
    __u8[96] aer_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_pcie {
    __u64 validation_bits;
    __u32 port_type;
    struct (anon) version;
    __u16 command;
    __u16 status;
    __u32 reserved;
    struct (anon) device_id;
    struct (anon) serial_number;
    struct (anon) bridge;
    __u8[60] capability;
    __u8[96] aer_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_pcie {
    u64 validation_bits;
    u32 port_type;
    struct (anon) version;
    u16 command;
    u16 status;
    u32 reserved;
    struct (anon) device_id;
    struct (anon) serial_number;
    struct (anon) bridge;
    u8[60] capability;
    u8[96] aer_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_pcie {
    u64 validation_bits;
    u32 port_type;
    struct (anon) version;
    u16 command;
    u16 status;
    u32 reserved;
    struct (anon) device_id;
    struct (anon) serial_number;
    struct (anon) bridge;
    u8[60] capability;
    u8[96] aer_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_pcie {
    u64 validation_bits;
    u32 port_type;
    struct (anon) version;
    u16 command;
    u16 status;
    u32 reserved;
    struct (anon) device_id;
    struct (anon) serial_number;
    struct (anon) bridge;
    u8[60] capability;
    u8[96] aer_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_pcie {
    u64 validation_bits;
    u32 port_type;
    struct (anon) version;
    u16 command;
    u16 status;
    u32 reserved;
    struct (anon) device_id;
    struct (anon) serial_number;
    struct (anon) bridge;
    u8[60] capability;
    u8[96] aer_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_pcie {
    u64 validation_bits;
    u32 port_type;
    struct (anon) version;
    u16 command;
    u16 status;
    u32 reserved;
    struct (anon) device_id;
    struct (anon) serial_number;
    struct (anon) bridge;
    u8[60] capability;
    u8[96] aer_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_pcie {
    u64 validation_bits;
    u32 port_type;
    struct (anon) version;
    u16 command;
    u16 status;
    u32 reserved;
    struct (anon) device_id;
    struct (anon) serial_number;
    struct (anon) bridge;
    u8[60] capability;
    u8[96] aer_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_pcie {
    u64 validation_bits;
    u32 port_type;
    struct (anon) version;
    u16 command;
    u16 status;
    u32 reserved;
    struct (anon) device_id;
    struct (anon) serial_number;
    struct (anon) bridge;
    u8[60] capability;
    u8[96] aer_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_pcie {
    u64 validation_bits;
    u32 port_type;
    struct (anon) version;
    u16 command;
    u16 status;
    u32 reserved;
    struct (anon) device_id;
    struct (anon) serial_number;
    struct (anon) bridge;
    u8[60] capability;
    u8[96] aer_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_pcie {
    u64 validation_bits;
    u32 port_type;
    struct (anon) version;
    u16 command;
    u16 status;
    u32 reserved;
    struct (anon) device_id;
    struct (anon) serial_number;
    struct (anon) bridge;
    u8[60] capability;
    u8[96] aer_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_pcie {
    u64 validation_bits;
    u32 port_type;
    struct (anon) version;
    u16 command;
    u16 status;
    u32 reserved;
    struct (anon) device_id;
    struct (anon) serial_number;
    struct (anon) bridge;
    u8[60] capability;
    u8[96] aer_info;
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
struct cper_sec_pcie {
    u64 validation_bits;
    u32 port_type;
    struct (anon) version;
    u16 command;
    u16 status;
    u32 reserved;
    struct (anon) device_id;
    struct (anon) serial_number;
    struct (anon) bridge;
    u8[60] capability;
    u8[96] aer_info;
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct cper_sec_pcie {
    u64 validation_bits;
    u32 port_type;
    struct (anon) version;
    u16 command;
    u16 status;
    u32 reserved;
    struct (anon) device_id;
    struct (anon) serial_number;
    struct (anon) bridge;
    u8[60] capability;
    u8[96] aer_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct cper_sec_pcie {
    u64 validation_bits;
    u32 port_type;
    struct (anon) version;
    u16 command;
    u16 status;
    u32 reserved;
    struct (anon) device_id;
    struct (anon) serial_number;
    struct (anon) bridge;
    u8[60] capability;
    u8[96] aer_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct cper_sec_pcie {
    u64 validation_bits;
    u32 port_type;
    struct (anon) version;
    u16 command;
    u16 status;
    u32 reserved;
    struct (anon) device_id;
    struct (anon) serial_number;
    struct (anon) bridge;
    u8[60] capability;
    u8[96] aer_info;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
<code>__u64 validation_bits</code> ➡️ <code>u64 validation_bits</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 port_type</code> ➡️ <code>u32 port_type</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u16 command</code> ➡️ <code>u16 command</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u16 status</code> ➡️ <code>u16 status</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 reserved</code> ➡️ <code>u32 reserved</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u8[60] capability</code> ➡️ <code>u8[60] capability</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u8[96] aer_info</code> ➡️ <code>u8[96] aer_info</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct cper_sec_pcie {
    u64 validation_bits;
    u32 port_type;
    struct (anon) version;
    u16 command;
    u16 status;
    u32 reserved;
    struct (anon) device_id;
    struct (anon) serial_number;
    struct (anon) bridge;
    u8[60] capability;
    u8[96] aer_info;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct cper_sec_pcie {
    u64 validation_bits;
    u32 port_type;
    struct (anon) version;
    u16 command;
    u16 status;
    u32 reserved;
    struct (anon) device_id;
    struct (anon) serial_number;
    struct (anon) bridge;
    u8[60] capability;
    u8[96] aer_info;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct cper_sec_pcie {
    u64 validation_bits;
    u32 port_type;
    struct (anon) version;
    u16 command;
    u16 status;
    u32 reserved;
    struct (anon) device_id;
    struct (anon) serial_number;
    struct (anon) bridge;
    u8[60] capability;
    u8[96] aer_info;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
struct cper_sec_pcie {
    u64 validation_bits;
    u32 port_type;
    struct (anon) version;
    u16 command;
    u16 status;
    u32 reserved;
    struct (anon) device_id;
    struct (anon) serial_number;
    struct (anon) bridge;
    u8[60] capability;
    u8[96] aer_info;
}
```
</details>
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
