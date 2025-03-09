# Struct: <code>ipc64_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ipc64_perm {
    __kernel_key_t key;
    __kernel_uid32_t uid;
    __kernel_gid32_t gid;
    __kernel_uid32_t cuid;
    __kernel_gid32_t cgid;
    __kernel_mode_t mode;
    unsigned char[0] __pad1;
    short unsigned int seq;
    short unsigned int __pad2;
    __kernel_ulong_t __unused1;
    __kernel_ulong_t __unused2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct ipc64_perm {
    __kernel_key_t key;
    __kernel_uid32_t uid;
    __kernel_gid32_t gid;
    __kernel_uid32_t cuid;
    __kernel_gid32_t cgid;
    __kernel_mode_t mode;
    unsigned char[0] __pad1;
    short unsigned int seq;
    short unsigned int __pad2;
    __kernel_ulong_t __unused1;
    __kernel_ulong_t __unused2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct ipc64_perm {
    __kernel_key_t key;
    __kernel_uid32_t uid;
    __kernel_gid32_t gid;
    __kernel_uid32_t cuid;
    __kernel_gid32_t cgid;
    __kernel_mode_t mode;
    unsigned char[0] __pad1;
    short unsigned int seq;
    short unsigned int __pad2;
    __kernel_ulong_t __unused1;
    __kernel_ulong_t __unused2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct ipc64_perm {
    __kernel_key_t key;
    __kernel_uid32_t uid;
    __kernel_gid32_t gid;
    __kernel_uid32_t cuid;
    __kernel_gid32_t cgid;
    __kernel_mode_t mode;
    unsigned char[0] __pad1;
    short unsigned int seq;
    short unsigned int __pad2;
    __kernel_ulong_t __unused1;
    __kernel_ulong_t __unused2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ipc64_perm {
    __kernel_key_t key;
    __kernel_uid32_t uid;
    __kernel_gid32_t gid;
    __kernel_uid32_t cuid;
    __kernel_gid32_t cgid;
    __kernel_mode_t mode;
    unsigned char[0] __pad1;
    short unsigned int seq;
    short unsigned int __pad2;
    __kernel_ulong_t __unused1;
    __kernel_ulong_t __unused2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ipc64_perm {
    __kernel_key_t key;
    __kernel_uid32_t uid;
    __kernel_gid32_t gid;
    __kernel_uid32_t cuid;
    __kernel_gid32_t cgid;
    __kernel_mode_t mode;
    unsigned char[0] __pad1;
    short unsigned int seq;
    short unsigned int __pad2;
    __kernel_ulong_t __unused1;
    __kernel_ulong_t __unused2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ipc64_perm {
    __kernel_key_t key;
    __kernel_uid32_t uid;
    __kernel_gid32_t gid;
    __kernel_uid32_t cuid;
    __kernel_gid32_t cgid;
    __kernel_mode_t mode;
    unsigned char[0] __pad1;
    short unsigned int seq;
    short unsigned int __pad2;
    __kernel_ulong_t __unused1;
    __kernel_ulong_t __unused2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ipc64_perm {
    __kernel_key_t key;
    __kernel_uid32_t uid;
    __kernel_gid32_t gid;
    __kernel_uid32_t cuid;
    __kernel_gid32_t cgid;
    __kernel_mode_t mode;
    unsigned char[0] __pad1;
    short unsigned int seq;
    short unsigned int __pad2;
    __kernel_ulong_t __unused1;
    __kernel_ulong_t __unused2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ipc64_perm {
    __kernel_key_t key;
    __kernel_uid32_t uid;
    __kernel_gid32_t gid;
    __kernel_uid32_t cuid;
    __kernel_gid32_t cgid;
    __kernel_mode_t mode;
    unsigned char[0] __pad1;
    short unsigned int seq;
    short unsigned int __pad2;
    __kernel_ulong_t __unused1;
    __kernel_ulong_t __unused2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ipc64_perm {
    __kernel_key_t key;
    __kernel_uid32_t uid;
    __kernel_gid32_t gid;
    __kernel_uid32_t cuid;
    __kernel_gid32_t cgid;
    __kernel_mode_t mode;
    unsigned char[0] __pad1;
    short unsigned int seq;
    short unsigned int __pad2;
    __kernel_ulong_t __unused1;
    __kernel_ulong_t __unused2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ipc64_perm {
    __kernel_key_t key;
    __kernel_uid32_t uid;
    __kernel_gid32_t gid;
    __kernel_uid32_t cuid;
    __kernel_gid32_t cgid;
    __kernel_mode_t mode;
    unsigned char[0] __pad1;
    short unsigned int seq;
    short unsigned int __pad2;
    __kernel_ulong_t __unused1;
    __kernel_ulong_t __unused2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ipc64_perm {
    __kernel_key_t key;
    __kernel_uid32_t uid;
    __kernel_gid32_t gid;
    __kernel_uid32_t cuid;
    __kernel_gid32_t cgid;
    __kernel_mode_t mode;
    unsigned char[0] __pad1;
    short unsigned int seq;
    short unsigned int __pad2;
    __kernel_ulong_t __unused1;
    __kernel_ulong_t __unused2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ipc64_perm {
    __kernel_key_t key;
    __kernel_uid32_t uid;
    __kernel_gid32_t gid;
    __kernel_uid32_t cuid;
    __kernel_gid32_t cgid;
    __kernel_mode_t mode;
    unsigned char[0] __pad1;
    short unsigned int seq;
    short unsigned int __pad2;
    __kernel_ulong_t __unused1;
    __kernel_ulong_t __unused2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ipc64_perm {
    __kernel_key_t key;
    __kernel_uid32_t uid;
    __kernel_gid32_t gid;
    __kernel_uid32_t cuid;
    __kernel_gid32_t cgid;
    __kernel_mode_t mode;
    unsigned char[0] __pad1;
    short unsigned int seq;
    short unsigned int __pad2;
    __kernel_ulong_t __unused1;
    __kernel_ulong_t __unused2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ipc64_perm {
    __kernel_key_t key;
    __kernel_uid32_t uid;
    __kernel_gid32_t gid;
    __kernel_uid32_t cuid;
    __kernel_gid32_t cgid;
    __kernel_mode_t mode;
    unsigned char[0] __pad1;
    short unsigned int seq;
    short unsigned int __pad2;
    __kernel_ulong_t __unused1;
    __kernel_ulong_t __unused2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ipc64_perm {
    __kernel_key_t key;
    __kernel_uid32_t uid;
    __kernel_gid32_t gid;
    __kernel_uid32_t cuid;
    __kernel_gid32_t cgid;
    __kernel_mode_t mode;
    unsigned char[0] __pad1;
    short unsigned int seq;
    short unsigned int __pad2;
    __kernel_ulong_t __unused1;
    __kernel_ulong_t __unused2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ipc64_perm {
    __kernel_key_t key;
    __kernel_uid32_t uid;
    __kernel_gid32_t gid;
    __kernel_uid32_t cuid;
    __kernel_gid32_t cgid;
    __kernel_mode_t mode;
    unsigned char[0] __pad1;
    short unsigned int seq;
    short unsigned int __pad2;
    __kernel_ulong_t __unused1;
    __kernel_ulong_t __unused2;
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
struct ipc64_perm {
    __kernel_key_t key;
    __kernel_uid32_t uid;
    __kernel_gid32_t gid;
    __kernel_uid32_t cuid;
    __kernel_gid32_t cgid;
    __kernel_mode_t mode;
    unsigned char[0] __pad1;
    short unsigned int seq;
    short unsigned int __pad2;
    __kernel_ulong_t __unused1;
    __kernel_ulong_t __unused2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ipc64_perm {
    __kernel_key_t key;
    __kernel_uid32_t uid;
    __kernel_gid32_t gid;
    __kernel_uid32_t cuid;
    __kernel_gid32_t cgid;
    __kernel_mode_t mode;
    unsigned char[2] __pad1;
    short unsigned int seq;
    short unsigned int __pad2;
    __kernel_ulong_t __unused1;
    __kernel_ulong_t __unused2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ipc64_perm {
    __kernel_key_t key;
    __kernel_uid_t uid;
    __kernel_gid_t gid;
    __kernel_uid_t cuid;
    __kernel_gid_t cgid;
    __kernel_mode_t mode;
    unsigned int seq;
    unsigned int __pad1;
    long long unsigned int __unused1;
    long long unsigned int __unused2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ipc64_perm {
    __kernel_key_t key;
    __kernel_uid32_t uid;
    __kernel_gid32_t gid;
    __kernel_uid32_t cuid;
    __kernel_gid32_t cgid;
    __kernel_mode_t mode;
    unsigned char[0] __pad1;
    short unsigned int seq;
    short unsigned int __pad2;
    __kernel_ulong_t __unused1;
    __kernel_ulong_t __unused2;
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
struct ipc64_perm {
    __kernel_key_t key;
    __kernel_uid32_t uid;
    __kernel_gid32_t gid;
    __kernel_uid32_t cuid;
    __kernel_gid32_t cgid;
    __kernel_mode_t mode;
    unsigned char[0] __pad1;
    short unsigned int seq;
    short unsigned int __pad2;
    __kernel_ulong_t __unused1;
    __kernel_ulong_t __unused2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ipc64_perm {
    __kernel_key_t key;
    __kernel_uid32_t uid;
    __kernel_gid32_t gid;
    __kernel_uid32_t cuid;
    __kernel_gid32_t cgid;
    __kernel_mode_t mode;
    unsigned char[0] __pad1;
    short unsigned int seq;
    short unsigned int __pad2;
    __kernel_ulong_t __unused1;
    __kernel_ulong_t __unused2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ipc64_perm {
    __kernel_key_t key;
    __kernel_uid32_t uid;
    __kernel_gid32_t gid;
    __kernel_uid32_t cuid;
    __kernel_gid32_t cgid;
    __kernel_mode_t mode;
    unsigned char[0] __pad1;
    short unsigned int seq;
    short unsigned int __pad2;
    __kernel_ulong_t __unused1;
    __kernel_ulong_t __unused2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ipc64_perm {
    __kernel_key_t key;
    __kernel_uid32_t uid;
    __kernel_gid32_t gid;
    __kernel_uid32_t cuid;
    __kernel_gid32_t cgid;
    __kernel_mode_t mode;
    unsigned char[0] __pad1;
    short unsigned int seq;
    short unsigned int __pad2;
    __kernel_ulong_t __unused1;
    __kernel_ulong_t __unused2;
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>unsigned char[0] __pad1</code> ➡️ <code>unsigned char[2] __pad1</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>short unsigned int __pad2</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_uid32_t uid</code> ➡️ <code>__kernel_uid_t uid</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_gid32_t gid</code> ➡️ <code>__kernel_gid_t gid</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_uid32_t cuid</code> ➡️ <code>__kernel_uid_t cuid</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_gid32_t cgid</code> ➡️ <code>__kernel_gid_t cgid</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned char[0] __pad1</code> ➡️ <code>unsigned int __pad1</code>
</li>
<li>
<b>Field type changed. </b>
<code>short unsigned int seq</code> ➡️ <code>unsigned int seq</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t __unused1</code> ➡️ <code>long long unsigned int __unused1</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t __unused2</code> ➡️ <code>long long unsigned int __unused2</code>
</li>
</ul>
</details>
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
