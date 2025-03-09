# Struct: <code>iocb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct iocb {
    __u64 aio_data;
    __u32 aio_key;
    __u32 aio_reserved1;
    __u16 aio_lio_opcode;
    __s16 aio_reqprio;
    __u32 aio_fildes;
    __u64 aio_buf;
    __u64 aio_nbytes;
    __s64 aio_offset;
    __u64 aio_reserved2;
    __u32 aio_flags;
    __u32 aio_resfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct iocb {
    __u64 aio_data;
    __u32 aio_key;
    __u32 aio_reserved1;
    __u16 aio_lio_opcode;
    __s16 aio_reqprio;
    __u32 aio_fildes;
    __u64 aio_buf;
    __u64 aio_nbytes;
    __s64 aio_offset;
    __u64 aio_reserved2;
    __u32 aio_flags;
    __u32 aio_resfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct iocb {
    __u64 aio_data;
    __u32 aio_key;
    __u32 aio_reserved1;
    __u16 aio_lio_opcode;
    __s16 aio_reqprio;
    __u32 aio_fildes;
    __u64 aio_buf;
    __u64 aio_nbytes;
    __s64 aio_offset;
    __u64 aio_reserved2;
    __u32 aio_flags;
    __u32 aio_resfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct iocb {
    __u64 aio_data;
    __u32 aio_key;
    __u32 aio_rw_flags;
    __u16 aio_lio_opcode;
    __s16 aio_reqprio;
    __u32 aio_fildes;
    __u64 aio_buf;
    __u64 aio_nbytes;
    __s64 aio_offset;
    __u64 aio_reserved2;
    __u32 aio_flags;
    __u32 aio_resfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct iocb {
    __u64 aio_data;
    __u32 aio_key;
    __kernel_rwf_t aio_rw_flags;
    __u16 aio_lio_opcode;
    __s16 aio_reqprio;
    __u32 aio_fildes;
    __u64 aio_buf;
    __u64 aio_nbytes;
    __s64 aio_offset;
    __u64 aio_reserved2;
    __u32 aio_flags;
    __u32 aio_resfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct iocb {
    __u64 aio_data;
    __u32 aio_key;
    __kernel_rwf_t aio_rw_flags;
    __u16 aio_lio_opcode;
    __s16 aio_reqprio;
    __u32 aio_fildes;
    __u64 aio_buf;
    __u64 aio_nbytes;
    __s64 aio_offset;
    __u64 aio_reserved2;
    __u32 aio_flags;
    __u32 aio_resfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct iocb {
    __u64 aio_data;
    __u32 aio_key;
    __kernel_rwf_t aio_rw_flags;
    __u16 aio_lio_opcode;
    __s16 aio_reqprio;
    __u32 aio_fildes;
    __u64 aio_buf;
    __u64 aio_nbytes;
    __s64 aio_offset;
    __u64 aio_reserved2;
    __u32 aio_flags;
    __u32 aio_resfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct iocb {
    __u64 aio_data;
    __u32 aio_key;
    __kernel_rwf_t aio_rw_flags;
    __u16 aio_lio_opcode;
    __s16 aio_reqprio;
    __u32 aio_fildes;
    __u64 aio_buf;
    __u64 aio_nbytes;
    __s64 aio_offset;
    __u64 aio_reserved2;
    __u32 aio_flags;
    __u32 aio_resfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct iocb {
    __u64 aio_data;
    __u32 aio_key;
    __kernel_rwf_t aio_rw_flags;
    __u16 aio_lio_opcode;
    __s16 aio_reqprio;
    __u32 aio_fildes;
    __u64 aio_buf;
    __u64 aio_nbytes;
    __s64 aio_offset;
    __u64 aio_reserved2;
    __u32 aio_flags;
    __u32 aio_resfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct iocb {
    __u64 aio_data;
    __u32 aio_key;
    __kernel_rwf_t aio_rw_flags;
    __u16 aio_lio_opcode;
    __s16 aio_reqprio;
    __u32 aio_fildes;
    __u64 aio_buf;
    __u64 aio_nbytes;
    __s64 aio_offset;
    __u64 aio_reserved2;
    __u32 aio_flags;
    __u32 aio_resfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct iocb {
    __u64 aio_data;
    __u32 aio_key;
    __kernel_rwf_t aio_rw_flags;
    __u16 aio_lio_opcode;
    __s16 aio_reqprio;
    __u32 aio_fildes;
    __u64 aio_buf;
    __u64 aio_nbytes;
    __s64 aio_offset;
    __u64 aio_reserved2;
    __u32 aio_flags;
    __u32 aio_resfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct iocb {
    __u64 aio_data;
    __u32 aio_key;
    __kernel_rwf_t aio_rw_flags;
    __u16 aio_lio_opcode;
    __s16 aio_reqprio;
    __u32 aio_fildes;
    __u64 aio_buf;
    __u64 aio_nbytes;
    __s64 aio_offset;
    __u64 aio_reserved2;
    __u32 aio_flags;
    __u32 aio_resfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct iocb {
    __u64 aio_data;
    __u32 aio_key;
    __kernel_rwf_t aio_rw_flags;
    __u16 aio_lio_opcode;
    __s16 aio_reqprio;
    __u32 aio_fildes;
    __u64 aio_buf;
    __u64 aio_nbytes;
    __s64 aio_offset;
    __u64 aio_reserved2;
    __u32 aio_flags;
    __u32 aio_resfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct iocb {
    __u64 aio_data;
    __u32 aio_key;
    __kernel_rwf_t aio_rw_flags;
    __u16 aio_lio_opcode;
    __s16 aio_reqprio;
    __u32 aio_fildes;
    __u64 aio_buf;
    __u64 aio_nbytes;
    __s64 aio_offset;
    __u64 aio_reserved2;
    __u32 aio_flags;
    __u32 aio_resfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct iocb {
    __u64 aio_data;
    __u32 aio_key;
    __kernel_rwf_t aio_rw_flags;
    __u16 aio_lio_opcode;
    __s16 aio_reqprio;
    __u32 aio_fildes;
    __u64 aio_buf;
    __u64 aio_nbytes;
    __s64 aio_offset;
    __u64 aio_reserved2;
    __u32 aio_flags;
    __u32 aio_resfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct iocb {
    __u64 aio_data;
    __u32 aio_key;
    __kernel_rwf_t aio_rw_flags;
    __u16 aio_lio_opcode;
    __s16 aio_reqprio;
    __u32 aio_fildes;
    __u64 aio_buf;
    __u64 aio_nbytes;
    __s64 aio_offset;
    __u64 aio_reserved2;
    __u32 aio_flags;
    __u32 aio_resfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct iocb {
    __u64 aio_data;
    __u32 aio_key;
    __kernel_rwf_t aio_rw_flags;
    __u16 aio_lio_opcode;
    __s16 aio_reqprio;
    __u32 aio_fildes;
    __u64 aio_buf;
    __u64 aio_nbytes;
    __s64 aio_offset;
    __u64 aio_reserved2;
    __u32 aio_flags;
    __u32 aio_resfd;
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
struct iocb {
    __u64 aio_data;
    __u32 aio_key;
    __kernel_rwf_t aio_rw_flags;
    __u16 aio_lio_opcode;
    __s16 aio_reqprio;
    __u32 aio_fildes;
    __u64 aio_buf;
    __u64 aio_nbytes;
    __s64 aio_offset;
    __u64 aio_reserved2;
    __u32 aio_flags;
    __u32 aio_resfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct iocb {
    __u64 aio_data;
    __u32 aio_key;
    __kernel_rwf_t aio_rw_flags;
    __u16 aio_lio_opcode;
    __s16 aio_reqprio;
    __u32 aio_fildes;
    __u64 aio_buf;
    __u64 aio_nbytes;
    __s64 aio_offset;
    __u64 aio_reserved2;
    __u32 aio_flags;
    __u32 aio_resfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct iocb {
    __u64 aio_data;
    __u32 aio_key;
    __kernel_rwf_t aio_rw_flags;
    __u16 aio_lio_opcode;
    __s16 aio_reqprio;
    __u32 aio_fildes;
    __u64 aio_buf;
    __u64 aio_nbytes;
    __s64 aio_offset;
    __u64 aio_reserved2;
    __u32 aio_flags;
    __u32 aio_resfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct iocb {
    __u64 aio_data;
    __u32 aio_key;
    __kernel_rwf_t aio_rw_flags;
    __u16 aio_lio_opcode;
    __s16 aio_reqprio;
    __u32 aio_fildes;
    __u64 aio_buf;
    __u64 aio_nbytes;
    __s64 aio_offset;
    __u64 aio_reserved2;
    __u32 aio_flags;
    __u32 aio_resfd;
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
struct iocb {
    __u64 aio_data;
    __u32 aio_key;
    __kernel_rwf_t aio_rw_flags;
    __u16 aio_lio_opcode;
    __s16 aio_reqprio;
    __u32 aio_fildes;
    __u64 aio_buf;
    __u64 aio_nbytes;
    __s64 aio_offset;
    __u64 aio_reserved2;
    __u32 aio_flags;
    __u32 aio_resfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct iocb {
    __u64 aio_data;
    __u32 aio_key;
    __kernel_rwf_t aio_rw_flags;
    __u16 aio_lio_opcode;
    __s16 aio_reqprio;
    __u32 aio_fildes;
    __u64 aio_buf;
    __u64 aio_nbytes;
    __s64 aio_offset;
    __u64 aio_reserved2;
    __u32 aio_flags;
    __u32 aio_resfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct iocb {
    __u64 aio_data;
    __u32 aio_key;
    __kernel_rwf_t aio_rw_flags;
    __u16 aio_lio_opcode;
    __s16 aio_reqprio;
    __u32 aio_fildes;
    __u64 aio_buf;
    __u64 aio_nbytes;
    __s64 aio_offset;
    __u64 aio_reserved2;
    __u32 aio_flags;
    __u32 aio_resfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct iocb {
    __u64 aio_data;
    __u32 aio_key;
    __kernel_rwf_t aio_rw_flags;
    __u16 aio_lio_opcode;
    __s16 aio_reqprio;
    __u32 aio_fildes;
    __u64 aio_buf;
    __u64 aio_nbytes;
    __s64 aio_offset;
    __u64 aio_reserved2;
    __u32 aio_flags;
    __u32 aio_resfd;
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u32 aio_rw_flags</code>
</li>
<li>
<b>Field removed. </b>
<code>__u32 aio_reserved1</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>__u32 aio_rw_flags</code> ➡️ <code>__kernel_rwf_t aio_rw_flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
