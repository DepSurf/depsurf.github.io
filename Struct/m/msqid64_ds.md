# Struct: <code>msqid64_ds</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct msqid64_ds {
    struct ipc64_perm msg_perm;
    __kernel_time_t msg_stime;
    __kernel_time_t msg_rtime;
    __kernel_time_t msg_ctime;
    __kernel_ulong_t msg_cbytes;
    __kernel_ulong_t msg_qnum;
    __kernel_ulong_t msg_qbytes;
    __kernel_pid_t msg_lspid;
    __kernel_pid_t msg_lrpid;
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
struct msqid64_ds {
    struct ipc64_perm msg_perm;
    __kernel_time_t msg_stime;
    __kernel_time_t msg_rtime;
    __kernel_time_t msg_ctime;
    __kernel_ulong_t msg_cbytes;
    __kernel_ulong_t msg_qnum;
    __kernel_ulong_t msg_qbytes;
    __kernel_pid_t msg_lspid;
    __kernel_pid_t msg_lrpid;
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
struct msqid64_ds {
    struct ipc64_perm msg_perm;
    __kernel_time_t msg_stime;
    __kernel_time_t msg_rtime;
    __kernel_time_t msg_ctime;
    __kernel_ulong_t msg_cbytes;
    __kernel_ulong_t msg_qnum;
    __kernel_ulong_t msg_qbytes;
    __kernel_pid_t msg_lspid;
    __kernel_pid_t msg_lrpid;
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
struct msqid64_ds {
    struct ipc64_perm msg_perm;
    __kernel_time_t msg_stime;
    __kernel_time_t msg_rtime;
    __kernel_time_t msg_ctime;
    __kernel_ulong_t msg_cbytes;
    __kernel_ulong_t msg_qnum;
    __kernel_ulong_t msg_qbytes;
    __kernel_pid_t msg_lspid;
    __kernel_pid_t msg_lrpid;
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
struct msqid64_ds {
    struct ipc64_perm msg_perm;
    __kernel_time_t msg_stime;
    __kernel_time_t msg_rtime;
    __kernel_time_t msg_ctime;
    __kernel_ulong_t msg_cbytes;
    __kernel_ulong_t msg_qnum;
    __kernel_ulong_t msg_qbytes;
    __kernel_pid_t msg_lspid;
    __kernel_pid_t msg_lrpid;
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
struct msqid64_ds {
    struct ipc64_perm msg_perm;
    __kernel_time_t msg_stime;
    __kernel_time_t msg_rtime;
    __kernel_time_t msg_ctime;
    long unsigned int msg_cbytes;
    long unsigned int msg_qnum;
    long unsigned int msg_qbytes;
    __kernel_pid_t msg_lspid;
    __kernel_pid_t msg_lrpid;
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
struct msqid64_ds {
    struct ipc64_perm msg_perm;
    __kernel_time_t msg_stime;
    __kernel_time_t msg_rtime;
    __kernel_time_t msg_ctime;
    long unsigned int msg_cbytes;
    long unsigned int msg_qnum;
    long unsigned int msg_qbytes;
    __kernel_pid_t msg_lspid;
    __kernel_pid_t msg_lrpid;
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
struct msqid64_ds {
    struct ipc64_perm msg_perm;
    __kernel_time_t msg_stime;
    __kernel_time_t msg_rtime;
    __kernel_time_t msg_ctime;
    long unsigned int msg_cbytes;
    long unsigned int msg_qnum;
    long unsigned int msg_qbytes;
    __kernel_pid_t msg_lspid;
    __kernel_pid_t msg_lrpid;
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
struct msqid64_ds {
    struct ipc64_perm msg_perm;
    __kernel_time_t msg_stime;
    __kernel_time_t msg_rtime;
    __kernel_time_t msg_ctime;
    long unsigned int msg_cbytes;
    long unsigned int msg_qnum;
    long unsigned int msg_qbytes;
    __kernel_pid_t msg_lspid;
    __kernel_pid_t msg_lrpid;
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
struct msqid64_ds {
    struct ipc64_perm msg_perm;
    long int msg_stime;
    long int msg_rtime;
    long int msg_ctime;
    long unsigned int msg_cbytes;
    long unsigned int msg_qnum;
    long unsigned int msg_qbytes;
    __kernel_pid_t msg_lspid;
    __kernel_pid_t msg_lrpid;
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
struct msqid64_ds {
    struct ipc64_perm msg_perm;
    long int msg_stime;
    long int msg_rtime;
    long int msg_ctime;
    long unsigned int msg_cbytes;
    long unsigned int msg_qnum;
    long unsigned int msg_qbytes;
    __kernel_pid_t msg_lspid;
    __kernel_pid_t msg_lrpid;
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
struct msqid64_ds {
    struct ipc64_perm msg_perm;
    long int msg_stime;
    long int msg_rtime;
    long int msg_ctime;
    long unsigned int msg_cbytes;
    long unsigned int msg_qnum;
    long unsigned int msg_qbytes;
    __kernel_pid_t msg_lspid;
    __kernel_pid_t msg_lrpid;
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
struct msqid64_ds {
    struct ipc64_perm msg_perm;
    long int msg_stime;
    long int msg_rtime;
    long int msg_ctime;
    long unsigned int msg_cbytes;
    long unsigned int msg_qnum;
    long unsigned int msg_qbytes;
    __kernel_pid_t msg_lspid;
    __kernel_pid_t msg_lrpid;
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
struct msqid64_ds {
    struct ipc64_perm msg_perm;
    long int msg_stime;
    long int msg_rtime;
    long int msg_ctime;
    long unsigned int msg_cbytes;
    long unsigned int msg_qnum;
    long unsigned int msg_qbytes;
    __kernel_pid_t msg_lspid;
    __kernel_pid_t msg_lrpid;
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
struct msqid64_ds {
    struct ipc64_perm msg_perm;
    long int msg_stime;
    long int msg_rtime;
    long int msg_ctime;
    long unsigned int msg_cbytes;
    long unsigned int msg_qnum;
    long unsigned int msg_qbytes;
    __kernel_pid_t msg_lspid;
    __kernel_pid_t msg_lrpid;
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
struct msqid64_ds {
    struct ipc64_perm msg_perm;
    long int msg_stime;
    long int msg_rtime;
    long int msg_ctime;
    long unsigned int msg_cbytes;
    long unsigned int msg_qnum;
    long unsigned int msg_qbytes;
    __kernel_pid_t msg_lspid;
    __kernel_pid_t msg_lrpid;
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
struct msqid64_ds {
    struct ipc64_perm msg_perm;
    long int msg_stime;
    long int msg_rtime;
    long int msg_ctime;
    long unsigned int msg_cbytes;
    long unsigned int msg_qnum;
    long unsigned int msg_qbytes;
    __kernel_pid_t msg_lspid;
    __kernel_pid_t msg_lrpid;
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
struct msqid64_ds {
    struct ipc64_perm msg_perm;
    __kernel_time_t msg_stime;
    __kernel_time_t msg_rtime;
    __kernel_time_t msg_ctime;
    long unsigned int msg_cbytes;
    long unsigned int msg_qnum;
    long unsigned int msg_qbytes;
    __kernel_pid_t msg_lspid;
    __kernel_pid_t msg_lrpid;
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
struct msqid64_ds {
    struct ipc64_perm msg_perm;
    long unsigned int msg_stime;
    long unsigned int msg_stime_high;
    long unsigned int msg_rtime;
    long unsigned int msg_rtime_high;
    long unsigned int msg_ctime;
    long unsigned int msg_ctime_high;
    long unsigned int msg_cbytes;
    long unsigned int msg_qnum;
    long unsigned int msg_qbytes;
    __kernel_pid_t msg_lspid;
    __kernel_pid_t msg_lrpid;
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
struct msqid64_ds {
    struct ipc64_perm msg_perm;
    __kernel_time_t msg_stime;
    __kernel_time_t msg_rtime;
    __kernel_time_t msg_ctime;
    long unsigned int msg_cbytes;
    long unsigned int msg_qnum;
    long unsigned int msg_qbytes;
    __kernel_pid_t msg_lspid;
    __kernel_pid_t msg_lrpid;
    long unsigned int __unused4;
    long unsigned int __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct msqid64_ds {
    struct ipc64_perm msg_perm;
    __kernel_time_t msg_stime;
    __kernel_time_t msg_rtime;
    __kernel_time_t msg_ctime;
    long unsigned int msg_cbytes;
    long unsigned int msg_qnum;
    long unsigned int msg_qbytes;
    __kernel_pid_t msg_lspid;
    __kernel_pid_t msg_lrpid;
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
struct msqid64_ds {
    struct ipc64_perm msg_perm;
    __kernel_time_t msg_stime;
    __kernel_time_t msg_rtime;
    __kernel_time_t msg_ctime;
    long unsigned int msg_cbytes;
    long unsigned int msg_qnum;
    long unsigned int msg_qbytes;
    __kernel_pid_t msg_lspid;
    __kernel_pid_t msg_lrpid;
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
struct msqid64_ds {
    struct ipc64_perm msg_perm;
    __kernel_time_t msg_stime;
    __kernel_time_t msg_rtime;
    __kernel_time_t msg_ctime;
    long unsigned int msg_cbytes;
    long unsigned int msg_qnum;
    long unsigned int msg_qbytes;
    __kernel_pid_t msg_lspid;
    __kernel_pid_t msg_lrpid;
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
struct msqid64_ds {
    struct ipc64_perm msg_perm;
    __kernel_time_t msg_stime;
    __kernel_time_t msg_rtime;
    __kernel_time_t msg_ctime;
    long unsigned int msg_cbytes;
    long unsigned int msg_qnum;
    long unsigned int msg_qbytes;
    __kernel_pid_t msg_lspid;
    __kernel_pid_t msg_lrpid;
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
struct msqid64_ds {
    struct ipc64_perm msg_perm;
    __kernel_time_t msg_stime;
    __kernel_time_t msg_rtime;
    __kernel_time_t msg_ctime;
    long unsigned int msg_cbytes;
    long unsigned int msg_qnum;
    long unsigned int msg_qbytes;
    __kernel_pid_t msg_lspid;
    __kernel_pid_t msg_lrpid;
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
<code>__kernel_ulong_t msg_cbytes</code> ➡️ <code>long unsigned int msg_cbytes</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t msg_qnum</code> ➡️ <code>long unsigned int msg_qnum</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_ulong_t msg_qbytes</code> ➡️ <code>long unsigned int msg_qbytes</code>
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
<code>__kernel_time_t msg_stime</code> ➡️ <code>long int msg_stime</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_time_t msg_rtime</code> ➡️ <code>long int msg_rtime</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_time_t msg_ctime</code> ➡️ <code>long int msg_ctime</code>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int msg_stime_high</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int msg_rtime_high</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int msg_ctime_high</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_time_t msg_stime</code> ➡️ <code>long unsigned int msg_stime</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_time_t msg_rtime</code> ➡️ <code>long unsigned int msg_rtime</code>
</li>
<li>
<b>Field type changed. </b>
<code>__kernel_time_t msg_ctime</code> ➡️ <code>long unsigned int msg_ctime</code>
</li>
</ul>
</details>
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
