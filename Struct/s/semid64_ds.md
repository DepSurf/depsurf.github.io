# Struct: <code>semid64_ds</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct semid64_ds {
    struct ipc64_perm sem_perm;
    __kernel_time_t sem_otime;
    __kernel_ulong_t __unused1;
    __kernel_time_t sem_ctime;
    __kernel_ulong_t __unused2;
    __kernel_ulong_t sem_nsems;
    __kernel_ulong_t __unused3;
    __kernel_ulong_t __unused4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct semid64_ds {
    struct ipc64_perm sem_perm;
    __kernel_time_t sem_otime;
    __kernel_ulong_t __unused1;
    __kernel_time_t sem_ctime;
    __kernel_ulong_t __unused2;
    __kernel_ulong_t sem_nsems;
    __kernel_ulong_t __unused3;
    __kernel_ulong_t __unused4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct semid64_ds {
    struct ipc64_perm sem_perm;
    __kernel_time_t sem_otime;
    __kernel_ulong_t __unused1;
    __kernel_time_t sem_ctime;
    __kernel_ulong_t __unused2;
    __kernel_ulong_t sem_nsems;
    __kernel_ulong_t __unused3;
    __kernel_ulong_t __unused4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct semid64_ds {
    struct ipc64_perm sem_perm;
    __kernel_time_t sem_otime;
    __kernel_ulong_t __unused1;
    __kernel_time_t sem_ctime;
    __kernel_ulong_t __unused2;
    __kernel_ulong_t sem_nsems;
    __kernel_ulong_t __unused3;
    __kernel_ulong_t __unused4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct semid64_ds {
    struct ipc64_perm sem_perm;
    __kernel_time_t sem_otime;
    __kernel_ulong_t __unused1;
    __kernel_time_t sem_ctime;
    __kernel_ulong_t __unused2;
    __kernel_ulong_t sem_nsems;
    __kernel_ulong_t __unused3;
    __kernel_ulong_t __unused4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct semid64_ds {
    struct ipc64_perm sem_perm;
    __kernel_time_t sem_otime;
    __kernel_ulong_t __unused1;
    __kernel_time_t sem_ctime;
    __kernel_ulong_t __unused2;
    __kernel_ulong_t sem_nsems;
    __kernel_ulong_t __unused3;
    __kernel_ulong_t __unused4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct semid64_ds {
    struct ipc64_perm sem_perm;
    __kernel_time_t sem_otime;
    __kernel_ulong_t __unused1;
    __kernel_time_t sem_ctime;
    __kernel_ulong_t __unused2;
    __kernel_ulong_t sem_nsems;
    __kernel_ulong_t __unused3;
    __kernel_ulong_t __unused4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct semid64_ds {
    struct ipc64_perm sem_perm;
    __kernel_time_t sem_otime;
    __kernel_ulong_t __unused1;
    __kernel_time_t sem_ctime;
    __kernel_ulong_t __unused2;
    __kernel_ulong_t sem_nsems;
    __kernel_ulong_t __unused3;
    __kernel_ulong_t __unused4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct semid64_ds {
    struct ipc64_perm sem_perm;
    __kernel_time_t sem_otime;
    __kernel_ulong_t __unused1;
    __kernel_time_t sem_ctime;
    __kernel_ulong_t __unused2;
    __kernel_ulong_t sem_nsems;
    __kernel_ulong_t __unused3;
    __kernel_ulong_t __unused4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct semid64_ds {
    struct ipc64_perm sem_perm;
    __kernel_long_t sem_otime;
    __kernel_ulong_t __unused1;
    __kernel_long_t sem_ctime;
    __kernel_ulong_t __unused2;
    __kernel_ulong_t sem_nsems;
    __kernel_ulong_t __unused3;
    __kernel_ulong_t __unused4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct semid64_ds {
    struct ipc64_perm sem_perm;
    __kernel_long_t sem_otime;
    __kernel_ulong_t __unused1;
    __kernel_long_t sem_ctime;
    __kernel_ulong_t __unused2;
    __kernel_ulong_t sem_nsems;
    __kernel_ulong_t __unused3;
    __kernel_ulong_t __unused4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct semid64_ds {
    struct ipc64_perm sem_perm;
    __kernel_long_t sem_otime;
    __kernel_ulong_t __unused1;
    __kernel_long_t sem_ctime;
    __kernel_ulong_t __unused2;
    __kernel_ulong_t sem_nsems;
    __kernel_ulong_t __unused3;
    __kernel_ulong_t __unused4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct semid64_ds {
    struct ipc64_perm sem_perm;
    __kernel_long_t sem_otime;
    __kernel_ulong_t __unused1;
    __kernel_long_t sem_ctime;
    __kernel_ulong_t __unused2;
    __kernel_ulong_t sem_nsems;
    __kernel_ulong_t __unused3;
    __kernel_ulong_t __unused4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct semid64_ds {
    struct ipc64_perm sem_perm;
    __kernel_long_t sem_otime;
    __kernel_ulong_t __unused1;
    __kernel_long_t sem_ctime;
    __kernel_ulong_t __unused2;
    __kernel_ulong_t sem_nsems;
    __kernel_ulong_t __unused3;
    __kernel_ulong_t __unused4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct semid64_ds {
    struct ipc64_perm sem_perm;
    __kernel_long_t sem_otime;
    __kernel_ulong_t __unused1;
    __kernel_long_t sem_ctime;
    __kernel_ulong_t __unused2;
    __kernel_ulong_t sem_nsems;
    __kernel_ulong_t __unused3;
    __kernel_ulong_t __unused4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct semid64_ds {
    struct ipc64_perm sem_perm;
    __kernel_long_t sem_otime;
    __kernel_ulong_t __unused1;
    __kernel_long_t sem_ctime;
    __kernel_ulong_t __unused2;
    __kernel_ulong_t sem_nsems;
    __kernel_ulong_t __unused3;
    __kernel_ulong_t __unused4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct semid64_ds {
    struct ipc64_perm sem_perm;
    __kernel_long_t sem_otime;
    __kernel_ulong_t __unused1;
    __kernel_long_t sem_ctime;
    __kernel_ulong_t __unused2;
    __kernel_ulong_t sem_nsems;
    __kernel_ulong_t __unused3;
    __kernel_ulong_t __unused4;
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
struct semid64_ds {
    struct ipc64_perm sem_perm;
    __kernel_time_t sem_otime;
    __kernel_time_t sem_ctime;
    long unsigned int sem_nsems;
    long unsigned int __unused3;
    long unsigned int __unused4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct semid64_ds {
    struct ipc64_perm sem_perm;
    long unsigned int sem_otime;
    long unsigned int sem_otime_high;
    long unsigned int sem_ctime;
    long unsigned int sem_ctime_high;
    long unsigned int sem_nsems;
    long unsigned int __unused3;
    long unsigned int __unused4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct semid64_ds {
    struct ipc64_perm sem_perm;
    __kernel_time_t sem_otime;
    __kernel_time_t sem_ctime;
    long unsigned int sem_nsems;
    long unsigned int __unused3;
    long unsigned int __unused4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct semid64_ds {
    struct ipc64_perm sem_perm;
    __kernel_time_t sem_otime;
    __kernel_time_t sem_ctime;
    long unsigned int sem_nsems;
    long unsigned int __unused3;
    long unsigned int __unused4;
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
struct semid64_ds {
    struct ipc64_perm sem_perm;
    __kernel_time_t sem_otime;
    __kernel_ulong_t __unused1;
    __kernel_time_t sem_ctime;
    __kernel_ulong_t __unused2;
    __kernel_ulong_t sem_nsems;
    __kernel_ulong_t __unused3;
    __kernel_ulong_t __unused4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct semid64_ds {
    struct ipc64_perm sem_perm;
    __kernel_time_t sem_otime;
    __kernel_ulong_t __unused1;
    __kernel_time_t sem_ctime;
    __kernel_ulong_t __unused2;
    __kernel_ulong_t sem_nsems;
    __kernel_ulong_t __unused3;
    __kernel_ulong_t __unused4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct semid64_ds {
    struct ipc64_perm sem_perm;
    __kernel_time_t sem_otime;
    __kernel_ulong_t __unused1;
    __kernel_time_t sem_ctime;
    __kernel_ulong_t __unused2;
    __kernel_ulong_t sem_nsems;
    __kernel_ulong_t __unused3;
    __kernel_ulong_t __unused4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct semid64_ds {
    struct ipc64_perm sem_perm;
    __kernel_time_t sem_otime;
    __kernel_ulong_t __unused1;
    __kernel_time_t sem_ctime;
    __kernel_ulong_t __unused2;
    __kernel_ulong_t sem_nsems;
    __kernel_ulong_t __unused3;
    __kernel_ulong_t __unused4;
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>__kernel_time_t sem_otime</code> ➡️ <code>__kernel_long_t sem_otime</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_time_t sem_ctime</code> ➡️ <code>__kernel_long_t sem_ctime</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>__kernel_ulong_t __unused1</code>
</li>
<li>
<b>Field removed. </b>
<code>__kernel_ulong_t __unused2</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t sem_nsems</code> ➡️ <code>long unsigned int sem_nsems</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t __unused3</code> ➡️ <code>long unsigned int __unused3</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t __unused4</code> ➡️ <code>long unsigned int __unused4</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int sem_otime_high</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int sem_ctime_high</code>
</li>
<li>
<b>Field removed. </b>
<code>__kernel_ulong_t __unused1</code>
</li>
<li>
<b>Field removed. </b>
<code>__kernel_ulong_t __unused2</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_time_t sem_otime</code> ➡️ <code>long unsigned int sem_otime</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_time_t sem_ctime</code> ➡️ <code>long unsigned int sem_ctime</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t sem_nsems</code> ➡️ <code>long unsigned int sem_nsems</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t __unused3</code> ➡️ <code>long unsigned int __unused3</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t __unused4</code> ➡️ <code>long unsigned int __unused4</code>
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
<code>__kernel_ulong_t __unused1</code>
</li>
<li>
<b>Field removed. </b>
<code>__kernel_ulong_t __unused2</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t sem_nsems</code> ➡️ <code>long unsigned int sem_nsems</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t __unused3</code> ➡️ <code>long unsigned int __unused3</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t __unused4</code> ➡️ <code>long unsigned int __unused4</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>__kernel_ulong_t __unused1</code>
</li>
<li>
<b>Field removed. </b>
<code>__kernel_ulong_t __unused2</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t sem_nsems</code> ➡️ <code>long unsigned int sem_nsems</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t __unused3</code> ➡️ <code>long unsigned int __unused3</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t __unused4</code> ➡️ <code>long unsigned int __unused4</code>
</li>
</ul>
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
