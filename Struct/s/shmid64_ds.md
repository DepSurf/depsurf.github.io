# Struct: <code>shmid64_ds</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct shmid64_ds {
    struct ipc64_perm shm_perm;
    size_t shm_segsz;
    __kernel_time_t shm_atime;
    __kernel_time_t shm_dtime;
    __kernel_time_t shm_ctime;
    __kernel_pid_t shm_cpid;
    __kernel_pid_t shm_lpid;
    __kernel_ulong_t shm_nattch;
    __kernel_ulong_t __unused4;
    __kernel_ulong_t __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct shmid64_ds {
    struct ipc64_perm shm_perm;
    size_t shm_segsz;
    __kernel_time_t shm_atime;
    __kernel_time_t shm_dtime;
    __kernel_time_t shm_ctime;
    __kernel_pid_t shm_cpid;
    __kernel_pid_t shm_lpid;
    __kernel_ulong_t shm_nattch;
    __kernel_ulong_t __unused4;
    __kernel_ulong_t __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct shmid64_ds {
    struct ipc64_perm shm_perm;
    size_t shm_segsz;
    __kernel_time_t shm_atime;
    __kernel_time_t shm_dtime;
    __kernel_time_t shm_ctime;
    __kernel_pid_t shm_cpid;
    __kernel_pid_t shm_lpid;
    __kernel_ulong_t shm_nattch;
    __kernel_ulong_t __unused4;
    __kernel_ulong_t __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct shmid64_ds {
    struct ipc64_perm shm_perm;
    size_t shm_segsz;
    __kernel_time_t shm_atime;
    __kernel_time_t shm_dtime;
    __kernel_time_t shm_ctime;
    __kernel_pid_t shm_cpid;
    __kernel_pid_t shm_lpid;
    __kernel_ulong_t shm_nattch;
    __kernel_ulong_t __unused4;
    __kernel_ulong_t __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct shmid64_ds {
    struct ipc64_perm shm_perm;
    size_t shm_segsz;
    __kernel_time_t shm_atime;
    __kernel_time_t shm_dtime;
    __kernel_time_t shm_ctime;
    __kernel_pid_t shm_cpid;
    __kernel_pid_t shm_lpid;
    __kernel_ulong_t shm_nattch;
    __kernel_ulong_t __unused4;
    __kernel_ulong_t __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct shmid64_ds {
    struct ipc64_perm shm_perm;
    size_t shm_segsz;
    __kernel_time_t shm_atime;
    __kernel_time_t shm_dtime;
    __kernel_time_t shm_ctime;
    __kernel_pid_t shm_cpid;
    __kernel_pid_t shm_lpid;
    long unsigned int shm_nattch;
    long unsigned int __unused4;
    long unsigned int __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct shmid64_ds {
    struct ipc64_perm shm_perm;
    size_t shm_segsz;
    __kernel_time_t shm_atime;
    __kernel_time_t shm_dtime;
    __kernel_time_t shm_ctime;
    __kernel_pid_t shm_cpid;
    __kernel_pid_t shm_lpid;
    long unsigned int shm_nattch;
    long unsigned int __unused4;
    long unsigned int __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct shmid64_ds {
    struct ipc64_perm shm_perm;
    size_t shm_segsz;
    __kernel_time_t shm_atime;
    __kernel_time_t shm_dtime;
    __kernel_time_t shm_ctime;
    __kernel_pid_t shm_cpid;
    __kernel_pid_t shm_lpid;
    long unsigned int shm_nattch;
    long unsigned int __unused4;
    long unsigned int __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct shmid64_ds {
    struct ipc64_perm shm_perm;
    size_t shm_segsz;
    __kernel_time_t shm_atime;
    __kernel_time_t shm_dtime;
    __kernel_time_t shm_ctime;
    __kernel_pid_t shm_cpid;
    __kernel_pid_t shm_lpid;
    long unsigned int shm_nattch;
    long unsigned int __unused4;
    long unsigned int __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct shmid64_ds {
    struct ipc64_perm shm_perm;
    size_t shm_segsz;
    long int shm_atime;
    long int shm_dtime;
    long int shm_ctime;
    __kernel_pid_t shm_cpid;
    __kernel_pid_t shm_lpid;
    long unsigned int shm_nattch;
    long unsigned int __unused4;
    long unsigned int __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct shmid64_ds {
    struct ipc64_perm shm_perm;
    size_t shm_segsz;
    long int shm_atime;
    long int shm_dtime;
    long int shm_ctime;
    __kernel_pid_t shm_cpid;
    __kernel_pid_t shm_lpid;
    long unsigned int shm_nattch;
    long unsigned int __unused4;
    long unsigned int __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct shmid64_ds {
    struct ipc64_perm shm_perm;
    size_t shm_segsz;
    long int shm_atime;
    long int shm_dtime;
    long int shm_ctime;
    __kernel_pid_t shm_cpid;
    __kernel_pid_t shm_lpid;
    long unsigned int shm_nattch;
    long unsigned int __unused4;
    long unsigned int __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct shmid64_ds {
    struct ipc64_perm shm_perm;
    size_t shm_segsz;
    long int shm_atime;
    long int shm_dtime;
    long int shm_ctime;
    __kernel_pid_t shm_cpid;
    __kernel_pid_t shm_lpid;
    long unsigned int shm_nattch;
    long unsigned int __unused4;
    long unsigned int __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct shmid64_ds {
    struct ipc64_perm shm_perm;
    __kernel_size_t shm_segsz;
    long int shm_atime;
    long int shm_dtime;
    long int shm_ctime;
    __kernel_pid_t shm_cpid;
    __kernel_pid_t shm_lpid;
    long unsigned int shm_nattch;
    long unsigned int __unused4;
    long unsigned int __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct shmid64_ds {
    struct ipc64_perm shm_perm;
    __kernel_size_t shm_segsz;
    long int shm_atime;
    long int shm_dtime;
    long int shm_ctime;
    __kernel_pid_t shm_cpid;
    __kernel_pid_t shm_lpid;
    long unsigned int shm_nattch;
    long unsigned int __unused4;
    long unsigned int __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct shmid64_ds {
    struct ipc64_perm shm_perm;
    __kernel_size_t shm_segsz;
    long int shm_atime;
    long int shm_dtime;
    long int shm_ctime;
    __kernel_pid_t shm_cpid;
    __kernel_pid_t shm_lpid;
    long unsigned int shm_nattch;
    long unsigned int __unused4;
    long unsigned int __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct shmid64_ds {
    struct ipc64_perm shm_perm;
    __kernel_size_t shm_segsz;
    long int shm_atime;
    long int shm_dtime;
    long int shm_ctime;
    __kernel_pid_t shm_cpid;
    __kernel_pid_t shm_lpid;
    long unsigned int shm_nattch;
    long unsigned int __unused4;
    long unsigned int __unused5;
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
struct shmid64_ds {
    struct ipc64_perm shm_perm;
    size_t shm_segsz;
    __kernel_time_t shm_atime;
    __kernel_time_t shm_dtime;
    __kernel_time_t shm_ctime;
    __kernel_pid_t shm_cpid;
    __kernel_pid_t shm_lpid;
    long unsigned int shm_nattch;
    long unsigned int __unused4;
    long unsigned int __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct shmid64_ds {
    struct ipc64_perm shm_perm;
    size_t shm_segsz;
    long unsigned int shm_atime;
    long unsigned int shm_atime_high;
    long unsigned int shm_dtime;
    long unsigned int shm_dtime_high;
    long unsigned int shm_ctime;
    long unsigned int shm_ctime_high;
    __kernel_pid_t shm_cpid;
    __kernel_pid_t shm_lpid;
    long unsigned int shm_nattch;
    long unsigned int __unused4;
    long unsigned int __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct shmid64_ds {
    struct ipc64_perm shm_perm;
    __kernel_time_t shm_atime;
    __kernel_time_t shm_dtime;
    __kernel_time_t shm_ctime;
    size_t shm_segsz;
    __kernel_pid_t shm_cpid;
    __kernel_pid_t shm_lpid;
    long unsigned int shm_nattch;
    long unsigned int __unused5;
    long unsigned int __unused6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct shmid64_ds {
    struct ipc64_perm shm_perm;
    size_t shm_segsz;
    __kernel_time_t shm_atime;
    __kernel_time_t shm_dtime;
    __kernel_time_t shm_ctime;
    __kernel_pid_t shm_cpid;
    __kernel_pid_t shm_lpid;
    long unsigned int shm_nattch;
    long unsigned int __unused4;
    long unsigned int __unused5;
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
struct shmid64_ds {
    struct ipc64_perm shm_perm;
    size_t shm_segsz;
    __kernel_time_t shm_atime;
    __kernel_time_t shm_dtime;
    __kernel_time_t shm_ctime;
    __kernel_pid_t shm_cpid;
    __kernel_pid_t shm_lpid;
    long unsigned int shm_nattch;
    long unsigned int __unused4;
    long unsigned int __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct shmid64_ds {
    struct ipc64_perm shm_perm;
    size_t shm_segsz;
    __kernel_time_t shm_atime;
    __kernel_time_t shm_dtime;
    __kernel_time_t shm_ctime;
    __kernel_pid_t shm_cpid;
    __kernel_pid_t shm_lpid;
    long unsigned int shm_nattch;
    long unsigned int __unused4;
    long unsigned int __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct shmid64_ds {
    struct ipc64_perm shm_perm;
    size_t shm_segsz;
    __kernel_time_t shm_atime;
    __kernel_time_t shm_dtime;
    __kernel_time_t shm_ctime;
    __kernel_pid_t shm_cpid;
    __kernel_pid_t shm_lpid;
    long unsigned int shm_nattch;
    long unsigned int __unused4;
    long unsigned int __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct shmid64_ds {
    struct ipc64_perm shm_perm;
    size_t shm_segsz;
    __kernel_time_t shm_atime;
    __kernel_time_t shm_dtime;
    __kernel_time_t shm_ctime;
    __kernel_pid_t shm_cpid;
    __kernel_pid_t shm_lpid;
    long unsigned int shm_nattch;
    long unsigned int __unused4;
    long unsigned int __unused5;
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t shm_nattch</code> ➡️ <code>long unsigned int shm_nattch</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t __unused4</code> ➡️ <code>long unsigned int __unused4</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t __unused5</code> ➡️ <code>long unsigned int __unused5</code>
</li>
</ul>
</details>
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
<code>__kernel_time_t shm_atime</code> ➡️ <code>long int shm_atime</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_time_t shm_dtime</code> ➡️ <code>long int shm_dtime</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_time_t shm_ctime</code> ➡️ <code>long int shm_ctime</code>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>size_t shm_segsz</code> ➡️ <code>__kernel_size_t shm_segsz</code>
</li>
</ul>
</details>
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
<b>Field added. </b>
<code>long unsigned int shm_atime_high</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int shm_dtime_high</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int shm_ctime_high</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_time_t shm_atime</code> ➡️ <code>long unsigned int shm_atime</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_time_t shm_dtime</code> ➡️ <code>long unsigned int shm_dtime</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_time_t shm_ctime</code> ➡️ <code>long unsigned int shm_ctime</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int __unused6</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int __unused4</code>
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
