# Struct: <code>cper_sec_proc_generic</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_proc_generic {
    __u64 validation_bits;
    __u8 proc_type;
    __u8 proc_isa;
    __u8 proc_error_type;
    __u8 operation;
    __u8 flags;
    __u8 level;
    __u16 reserved;
    __u64 cpu_version;
    char[128] cpu_brand;
    __u64 proc_id;
    __u64 target_addr;
    __u64 requestor_id;
    __u64 responder_id;
    __u64 ip;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_proc_generic {
    __u64 validation_bits;
    __u8 proc_type;
    __u8 proc_isa;
    __u8 proc_error_type;
    __u8 operation;
    __u8 flags;
    __u8 level;
    __u16 reserved;
    __u64 cpu_version;
    char[128] cpu_brand;
    __u64 proc_id;
    __u64 target_addr;
    __u64 requestor_id;
    __u64 responder_id;
    __u64 ip;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_proc_generic {
    __u64 validation_bits;
    __u8 proc_type;
    __u8 proc_isa;
    __u8 proc_error_type;
    __u8 operation;
    __u8 flags;
    __u8 level;
    __u16 reserved;
    __u64 cpu_version;
    char[128] cpu_brand;
    __u64 proc_id;
    __u64 target_addr;
    __u64 requestor_id;
    __u64 responder_id;
    __u64 ip;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_proc_generic {
    __u64 validation_bits;
    __u8 proc_type;
    __u8 proc_isa;
    __u8 proc_error_type;
    __u8 operation;
    __u8 flags;
    __u8 level;
    __u16 reserved;
    __u64 cpu_version;
    char[128] cpu_brand;
    __u64 proc_id;
    __u64 target_addr;
    __u64 requestor_id;
    __u64 responder_id;
    __u64 ip;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_proc_generic {
    __u64 validation_bits;
    __u8 proc_type;
    __u8 proc_isa;
    __u8 proc_error_type;
    __u8 operation;
    __u8 flags;
    __u8 level;
    __u16 reserved;
    __u64 cpu_version;
    char[128] cpu_brand;
    __u64 proc_id;
    __u64 target_addr;
    __u64 requestor_id;
    __u64 responder_id;
    __u64 ip;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_proc_generic {
    __u64 validation_bits;
    __u8 proc_type;
    __u8 proc_isa;
    __u8 proc_error_type;
    __u8 operation;
    __u8 flags;
    __u8 level;
    __u16 reserved;
    __u64 cpu_version;
    char[128] cpu_brand;
    __u64 proc_id;
    __u64 target_addr;
    __u64 requestor_id;
    __u64 responder_id;
    __u64 ip;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_proc_generic {
    __u64 validation_bits;
    __u8 proc_type;
    __u8 proc_isa;
    __u8 proc_error_type;
    __u8 operation;
    __u8 flags;
    __u8 level;
    __u16 reserved;
    __u64 cpu_version;
    char[128] cpu_brand;
    __u64 proc_id;
    __u64 target_addr;
    __u64 requestor_id;
    __u64 responder_id;
    __u64 ip;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_proc_generic {
    u64 validation_bits;
    u8 proc_type;
    u8 proc_isa;
    u8 proc_error_type;
    u8 operation;
    u8 flags;
    u8 level;
    u16 reserved;
    u64 cpu_version;
    char[128] cpu_brand;
    u64 proc_id;
    u64 target_addr;
    u64 requestor_id;
    u64 responder_id;
    u64 ip;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_proc_generic {
    u64 validation_bits;
    u8 proc_type;
    u8 proc_isa;
    u8 proc_error_type;
    u8 operation;
    u8 flags;
    u8 level;
    u16 reserved;
    u64 cpu_version;
    char[128] cpu_brand;
    u64 proc_id;
    u64 target_addr;
    u64 requestor_id;
    u64 responder_id;
    u64 ip;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_proc_generic {
    u64 validation_bits;
    u8 proc_type;
    u8 proc_isa;
    u8 proc_error_type;
    u8 operation;
    u8 flags;
    u8 level;
    u16 reserved;
    u64 cpu_version;
    char[128] cpu_brand;
    u64 proc_id;
    u64 target_addr;
    u64 requestor_id;
    u64 responder_id;
    u64 ip;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_proc_generic {
    u64 validation_bits;
    u8 proc_type;
    u8 proc_isa;
    u8 proc_error_type;
    u8 operation;
    u8 flags;
    u8 level;
    u16 reserved;
    u64 cpu_version;
    char[128] cpu_brand;
    u64 proc_id;
    u64 target_addr;
    u64 requestor_id;
    u64 responder_id;
    u64 ip;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_proc_generic {
    u64 validation_bits;
    u8 proc_type;
    u8 proc_isa;
    u8 proc_error_type;
    u8 operation;
    u8 flags;
    u8 level;
    u16 reserved;
    u64 cpu_version;
    char[128] cpu_brand;
    u64 proc_id;
    u64 target_addr;
    u64 requestor_id;
    u64 responder_id;
    u64 ip;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_proc_generic {
    u64 validation_bits;
    u8 proc_type;
    u8 proc_isa;
    u8 proc_error_type;
    u8 operation;
    u8 flags;
    u8 level;
    u16 reserved;
    u64 cpu_version;
    char[128] cpu_brand;
    u64 proc_id;
    u64 target_addr;
    u64 requestor_id;
    u64 responder_id;
    u64 ip;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_proc_generic {
    u64 validation_bits;
    u8 proc_type;
    u8 proc_isa;
    u8 proc_error_type;
    u8 operation;
    u8 flags;
    u8 level;
    u16 reserved;
    u64 cpu_version;
    char[128] cpu_brand;
    u64 proc_id;
    u64 target_addr;
    u64 requestor_id;
    u64 responder_id;
    u64 ip;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_proc_generic {
    u64 validation_bits;
    u8 proc_type;
    u8 proc_isa;
    u8 proc_error_type;
    u8 operation;
    u8 flags;
    u8 level;
    u16 reserved;
    u64 cpu_version;
    char[128] cpu_brand;
    u64 proc_id;
    u64 target_addr;
    u64 requestor_id;
    u64 responder_id;
    u64 ip;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_proc_generic {
    u64 validation_bits;
    u8 proc_type;
    u8 proc_isa;
    u8 proc_error_type;
    u8 operation;
    u8 flags;
    u8 level;
    u16 reserved;
    u64 cpu_version;
    char[128] cpu_brand;
    u64 proc_id;
    u64 target_addr;
    u64 requestor_id;
    u64 responder_id;
    u64 ip;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct cper_sec_proc_generic {
    u64 validation_bits;
    u8 proc_type;
    u8 proc_isa;
    u8 proc_error_type;
    u8 operation;
    u8 flags;
    u8 level;
    u16 reserved;
    u64 cpu_version;
    char[128] cpu_brand;
    u64 proc_id;
    u64 target_addr;
    u64 requestor_id;
    u64 responder_id;
    u64 ip;
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
struct cper_sec_proc_generic {
    u64 validation_bits;
    u8 proc_type;
    u8 proc_isa;
    u8 proc_error_type;
    u8 operation;
    u8 flags;
    u8 level;
    u16 reserved;
    u64 cpu_version;
    char[128] cpu_brand;
    u64 proc_id;
    u64 target_addr;
    u64 requestor_id;
    u64 responder_id;
    u64 ip;
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
struct cper_sec_proc_generic {
    u64 validation_bits;
    u8 proc_type;
    u8 proc_isa;
    u8 proc_error_type;
    u8 operation;
    u8 flags;
    u8 level;
    u16 reserved;
    u64 cpu_version;
    char[128] cpu_brand;
    u64 proc_id;
    u64 target_addr;
    u64 requestor_id;
    u64 responder_id;
    u64 ip;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct cper_sec_proc_generic {
    u64 validation_bits;
    u8 proc_type;
    u8 proc_isa;
    u8 proc_error_type;
    u8 operation;
    u8 flags;
    u8 level;
    u16 reserved;
    u64 cpu_version;
    char[128] cpu_brand;
    u64 proc_id;
    u64 target_addr;
    u64 requestor_id;
    u64 responder_id;
    u64 ip;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct cper_sec_proc_generic {
    u64 validation_bits;
    u8 proc_type;
    u8 proc_isa;
    u8 proc_error_type;
    u8 operation;
    u8 flags;
    u8 level;
    u16 reserved;
    u64 cpu_version;
    char[128] cpu_brand;
    u64 proc_id;
    u64 target_addr;
    u64 requestor_id;
    u64 responder_id;
    u64 ip;
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
<code>__u8 proc_type</code> ➡️ <code>u8 proc_type</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u8 proc_isa</code> ➡️ <code>u8 proc_isa</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u8 proc_error_type</code> ➡️ <code>u8 proc_error_type</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u8 operation</code> ➡️ <code>u8 operation</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u8 flags</code> ➡️ <code>u8 flags</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u8 level</code> ➡️ <code>u8 level</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u16 reserved</code> ➡️ <code>u16 reserved</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u64 cpu_version</code> ➡️ <code>u64 cpu_version</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u64 proc_id</code> ➡️ <code>u64 proc_id</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u64 target_addr</code> ➡️ <code>u64 target_addr</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u64 requestor_id</code> ➡️ <code>u64 requestor_id</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u64 responder_id</code> ➡️ <code>u64 responder_id</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u64 ip</code> ➡️ <code>u64 ip</code>
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
struct cper_sec_proc_generic {
    u64 validation_bits;
    u8 proc_type;
    u8 proc_isa;
    u8 proc_error_type;
    u8 operation;
    u8 flags;
    u8 level;
    u16 reserved;
    u64 cpu_version;
    char[128] cpu_brand;
    u64 proc_id;
    u64 target_addr;
    u64 requestor_id;
    u64 responder_id;
    u64 ip;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct cper_sec_proc_generic {
    u64 validation_bits;
    u8 proc_type;
    u8 proc_isa;
    u8 proc_error_type;
    u8 operation;
    u8 flags;
    u8 level;
    u16 reserved;
    u64 cpu_version;
    char[128] cpu_brand;
    u64 proc_id;
    u64 target_addr;
    u64 requestor_id;
    u64 responder_id;
    u64 ip;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct cper_sec_proc_generic {
    u64 validation_bits;
    u8 proc_type;
    u8 proc_isa;
    u8 proc_error_type;
    u8 operation;
    u8 flags;
    u8 level;
    u16 reserved;
    u64 cpu_version;
    char[128] cpu_brand;
    u64 proc_id;
    u64 target_addr;
    u64 requestor_id;
    u64 responder_id;
    u64 ip;
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
struct cper_sec_proc_generic {
    u64 validation_bits;
    u8 proc_type;
    u8 proc_isa;
    u8 proc_error_type;
    u8 operation;
    u8 flags;
    u8 level;
    u16 reserved;
    u64 cpu_version;
    char[128] cpu_brand;
    u64 proc_id;
    u64 target_addr;
    u64 requestor_id;
    u64 responder_id;
    u64 ip;
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
