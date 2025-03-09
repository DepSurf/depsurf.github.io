# Struct: <code>compat_msqid64_ds</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct compat_msqid64_ds {
    struct compat_ipc64_perm msg_perm;
    compat_time_t msg_stime;
    compat_ulong_t __unused1;
    compat_time_t msg_rtime;
    compat_ulong_t __unused2;
    compat_time_t msg_ctime;
    compat_ulong_t __unused3;
    compat_ulong_t msg_cbytes;
    compat_ulong_t msg_qnum;
    compat_ulong_t msg_qbytes;
    compat_pid_t msg_lspid;
    compat_pid_t msg_lrpid;
    compat_ulong_t __unused4;
    compat_ulong_t __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct compat_msqid64_ds {
    struct compat_ipc64_perm msg_perm;
    compat_time_t msg_stime;
    compat_ulong_t __unused1;
    compat_time_t msg_rtime;
    compat_ulong_t __unused2;
    compat_time_t msg_ctime;
    compat_ulong_t __unused3;
    compat_ulong_t msg_cbytes;
    compat_ulong_t msg_qnum;
    compat_ulong_t msg_qbytes;
    compat_pid_t msg_lspid;
    compat_pid_t msg_lrpid;
    compat_ulong_t __unused4;
    compat_ulong_t __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct compat_msqid64_ds {
    struct compat_ipc64_perm msg_perm;
    compat_time_t msg_stime;
    compat_ulong_t __unused1;
    compat_time_t msg_rtime;
    compat_ulong_t __unused2;
    compat_time_t msg_ctime;
    compat_ulong_t __unused3;
    compat_ulong_t msg_cbytes;
    compat_ulong_t msg_qnum;
    compat_ulong_t msg_qbytes;
    compat_pid_t msg_lspid;
    compat_pid_t msg_lrpid;
    compat_ulong_t __unused4;
    compat_ulong_t __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct compat_msqid64_ds {
    struct compat_ipc64_perm msg_perm;
    compat_time_t msg_stime;
    compat_ulong_t __unused1;
    compat_time_t msg_rtime;
    compat_ulong_t __unused2;
    compat_time_t msg_ctime;
    compat_ulong_t __unused3;
    compat_ulong_t msg_cbytes;
    compat_ulong_t msg_qnum;
    compat_ulong_t msg_qbytes;
    compat_pid_t msg_lspid;
    compat_pid_t msg_lrpid;
    compat_ulong_t __unused4;
    compat_ulong_t __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct compat_msqid64_ds {
    struct compat_ipc64_perm msg_perm;
    compat_time_t msg_stime;
    compat_ulong_t __unused1;
    compat_time_t msg_rtime;
    compat_ulong_t __unused2;
    compat_time_t msg_ctime;
    compat_ulong_t __unused3;
    compat_ulong_t msg_cbytes;
    compat_ulong_t msg_qnum;
    compat_ulong_t msg_qbytes;
    compat_pid_t msg_lspid;
    compat_pid_t msg_lrpid;
    compat_ulong_t __unused4;
    compat_ulong_t __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct compat_msqid64_ds {
    struct compat_ipc64_perm msg_perm;
    compat_ulong_t msg_stime;
    compat_ulong_t msg_stime_high;
    compat_ulong_t msg_rtime;
    compat_ulong_t msg_rtime_high;
    compat_ulong_t msg_ctime;
    compat_ulong_t msg_ctime_high;
    compat_ulong_t msg_cbytes;
    compat_ulong_t msg_qnum;
    compat_ulong_t msg_qbytes;
    compat_pid_t msg_lspid;
    compat_pid_t msg_lrpid;
    compat_ulong_t __unused4;
    compat_ulong_t __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct compat_msqid64_ds {
    struct compat_ipc64_perm msg_perm;
    compat_ulong_t msg_stime;
    compat_ulong_t msg_stime_high;
    compat_ulong_t msg_rtime;
    compat_ulong_t msg_rtime_high;
    compat_ulong_t msg_ctime;
    compat_ulong_t msg_ctime_high;
    compat_ulong_t msg_cbytes;
    compat_ulong_t msg_qnum;
    compat_ulong_t msg_qbytes;
    compat_pid_t msg_lspid;
    compat_pid_t msg_lrpid;
    compat_ulong_t __unused4;
    compat_ulong_t __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct compat_msqid64_ds {
    struct compat_ipc64_perm msg_perm;
    compat_ulong_t msg_stime;
    compat_ulong_t msg_stime_high;
    compat_ulong_t msg_rtime;
    compat_ulong_t msg_rtime_high;
    compat_ulong_t msg_ctime;
    compat_ulong_t msg_ctime_high;
    compat_ulong_t msg_cbytes;
    compat_ulong_t msg_qnum;
    compat_ulong_t msg_qbytes;
    compat_pid_t msg_lspid;
    compat_pid_t msg_lrpid;
    compat_ulong_t __unused4;
    compat_ulong_t __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct compat_msqid64_ds {
    struct compat_ipc64_perm msg_perm;
    compat_ulong_t msg_stime;
    compat_ulong_t msg_stime_high;
    compat_ulong_t msg_rtime;
    compat_ulong_t msg_rtime_high;
    compat_ulong_t msg_ctime;
    compat_ulong_t msg_ctime_high;
    compat_ulong_t msg_cbytes;
    compat_ulong_t msg_qnum;
    compat_ulong_t msg_qbytes;
    compat_pid_t msg_lspid;
    compat_pid_t msg_lrpid;
    compat_ulong_t __unused4;
    compat_ulong_t __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct compat_msqid64_ds {
    struct compat_ipc64_perm msg_perm;
    compat_ulong_t msg_stime;
    compat_ulong_t msg_stime_high;
    compat_ulong_t msg_rtime;
    compat_ulong_t msg_rtime_high;
    compat_ulong_t msg_ctime;
    compat_ulong_t msg_ctime_high;
    compat_ulong_t msg_cbytes;
    compat_ulong_t msg_qnum;
    compat_ulong_t msg_qbytes;
    compat_pid_t msg_lspid;
    compat_pid_t msg_lrpid;
    compat_ulong_t __unused4;
    compat_ulong_t __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct compat_msqid64_ds {
    struct compat_ipc64_perm msg_perm;
    compat_ulong_t msg_stime;
    compat_ulong_t msg_stime_high;
    compat_ulong_t msg_rtime;
    compat_ulong_t msg_rtime_high;
    compat_ulong_t msg_ctime;
    compat_ulong_t msg_ctime_high;
    compat_ulong_t msg_cbytes;
    compat_ulong_t msg_qnum;
    compat_ulong_t msg_qbytes;
    compat_pid_t msg_lspid;
    compat_pid_t msg_lrpid;
    compat_ulong_t __unused4;
    compat_ulong_t __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct compat_msqid64_ds {
    struct compat_ipc64_perm msg_perm;
    compat_ulong_t msg_stime;
    compat_ulong_t msg_stime_high;
    compat_ulong_t msg_rtime;
    compat_ulong_t msg_rtime_high;
    compat_ulong_t msg_ctime;
    compat_ulong_t msg_ctime_high;
    compat_ulong_t msg_cbytes;
    compat_ulong_t msg_qnum;
    compat_ulong_t msg_qbytes;
    compat_pid_t msg_lspid;
    compat_pid_t msg_lrpid;
    compat_ulong_t __unused4;
    compat_ulong_t __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct compat_msqid64_ds {
    struct compat_ipc64_perm msg_perm;
    compat_ulong_t msg_stime;
    compat_ulong_t msg_stime_high;
    compat_ulong_t msg_rtime;
    compat_ulong_t msg_rtime_high;
    compat_ulong_t msg_ctime;
    compat_ulong_t msg_ctime_high;
    compat_ulong_t msg_cbytes;
    compat_ulong_t msg_qnum;
    compat_ulong_t msg_qbytes;
    compat_pid_t msg_lspid;
    compat_pid_t msg_lrpid;
    compat_ulong_t __unused4;
    compat_ulong_t __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct compat_msqid64_ds {
    struct compat_ipc64_perm msg_perm;
    compat_ulong_t msg_stime;
    compat_ulong_t msg_stime_high;
    compat_ulong_t msg_rtime;
    compat_ulong_t msg_rtime_high;
    compat_ulong_t msg_ctime;
    compat_ulong_t msg_ctime_high;
    compat_ulong_t msg_cbytes;
    compat_ulong_t msg_qnum;
    compat_ulong_t msg_qbytes;
    compat_pid_t msg_lspid;
    compat_pid_t msg_lrpid;
    compat_ulong_t __unused4;
    compat_ulong_t __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct compat_msqid64_ds {
    struct compat_ipc64_perm msg_perm;
    compat_ulong_t msg_stime;
    compat_ulong_t msg_stime_high;
    compat_ulong_t msg_rtime;
    compat_ulong_t msg_rtime_high;
    compat_ulong_t msg_ctime;
    compat_ulong_t msg_ctime_high;
    compat_ulong_t msg_cbytes;
    compat_ulong_t msg_qnum;
    compat_ulong_t msg_qbytes;
    compat_pid_t msg_lspid;
    compat_pid_t msg_lrpid;
    compat_ulong_t __unused4;
    compat_ulong_t __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct compat_msqid64_ds {
    struct compat_ipc64_perm msg_perm;
    compat_ulong_t msg_stime;
    compat_ulong_t msg_stime_high;
    compat_ulong_t msg_rtime;
    compat_ulong_t msg_rtime_high;
    compat_ulong_t msg_ctime;
    compat_ulong_t msg_ctime_high;
    compat_ulong_t msg_cbytes;
    compat_ulong_t msg_qnum;
    compat_ulong_t msg_qbytes;
    compat_pid_t msg_lspid;
    compat_pid_t msg_lrpid;
    compat_ulong_t __unused4;
    compat_ulong_t __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct compat_msqid64_ds {
    struct compat_ipc64_perm msg_perm;
    compat_ulong_t msg_stime;
    compat_ulong_t msg_stime_high;
    compat_ulong_t msg_rtime;
    compat_ulong_t msg_rtime_high;
    compat_ulong_t msg_ctime;
    compat_ulong_t msg_ctime_high;
    compat_ulong_t msg_cbytes;
    compat_ulong_t msg_qnum;
    compat_ulong_t msg_qbytes;
    compat_pid_t msg_lspid;
    compat_pid_t msg_lrpid;
    compat_ulong_t __unused4;
    compat_ulong_t __unused5;
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
struct compat_msqid64_ds {
    struct compat_ipc64_perm msg_perm;
    compat_ulong_t msg_stime;
    compat_ulong_t msg_stime_high;
    compat_ulong_t msg_rtime;
    compat_ulong_t msg_rtime_high;
    compat_ulong_t msg_ctime;
    compat_ulong_t msg_ctime_high;
    compat_ulong_t msg_cbytes;
    compat_ulong_t msg_qnum;
    compat_ulong_t msg_qbytes;
    compat_pid_t msg_lspid;
    compat_pid_t msg_lrpid;
    compat_ulong_t __unused4;
    compat_ulong_t __unused5;
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct compat_msqid64_ds {
    struct compat_ipc64_perm msg_perm;
    unsigned int msg_stime_high;
    unsigned int msg_stime;
    unsigned int msg_rtime_high;
    unsigned int msg_rtime;
    unsigned int msg_ctime_high;
    unsigned int msg_ctime;
    compat_ulong_t msg_cbytes;
    compat_ulong_t msg_qnum;
    compat_ulong_t msg_qbytes;
    compat_pid_t msg_lspid;
    compat_pid_t msg_lrpid;
    compat_ulong_t __unused4;
    compat_ulong_t __unused5;
}
```
</details>
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
struct compat_msqid64_ds {
    struct compat_ipc64_perm msg_perm;
    compat_ulong_t msg_stime;
    compat_ulong_t msg_stime_high;
    compat_ulong_t msg_rtime;
    compat_ulong_t msg_rtime_high;
    compat_ulong_t msg_ctime;
    compat_ulong_t msg_ctime_high;
    compat_ulong_t msg_cbytes;
    compat_ulong_t msg_qnum;
    compat_ulong_t msg_qbytes;
    compat_pid_t msg_lspid;
    compat_pid_t msg_lrpid;
    compat_ulong_t __unused4;
    compat_ulong_t __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct compat_msqid64_ds {
    struct compat_ipc64_perm msg_perm;
    compat_ulong_t msg_stime;
    compat_ulong_t msg_stime_high;
    compat_ulong_t msg_rtime;
    compat_ulong_t msg_rtime_high;
    compat_ulong_t msg_ctime;
    compat_ulong_t msg_ctime_high;
    compat_ulong_t msg_cbytes;
    compat_ulong_t msg_qnum;
    compat_ulong_t msg_qbytes;
    compat_pid_t msg_lspid;
    compat_pid_t msg_lrpid;
    compat_ulong_t __unused4;
    compat_ulong_t __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct compat_msqid64_ds {
    struct compat_ipc64_perm msg_perm;
    compat_ulong_t msg_stime;
    compat_ulong_t msg_stime_high;
    compat_ulong_t msg_rtime;
    compat_ulong_t msg_rtime_high;
    compat_ulong_t msg_ctime;
    compat_ulong_t msg_ctime_high;
    compat_ulong_t msg_cbytes;
    compat_ulong_t msg_qnum;
    compat_ulong_t msg_qbytes;
    compat_pid_t msg_lspid;
    compat_pid_t msg_lrpid;
    compat_ulong_t __unused4;
    compat_ulong_t __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct compat_msqid64_ds {
    struct compat_ipc64_perm msg_perm;
    compat_ulong_t msg_stime;
    compat_ulong_t msg_stime_high;
    compat_ulong_t msg_rtime;
    compat_ulong_t msg_rtime_high;
    compat_ulong_t msg_ctime;
    compat_ulong_t msg_ctime_high;
    compat_ulong_t msg_cbytes;
    compat_ulong_t msg_qnum;
    compat_ulong_t msg_qbytes;
    compat_pid_t msg_lspid;
    compat_pid_t msg_lrpid;
    compat_ulong_t __unused4;
    compat_ulong_t __unused5;
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
<b>Field added. </b>
<code>compat_ulong_t msg_stime_high</code>
</li>
<li>
<b>Field added. </b>
<code>compat_ulong_t msg_rtime_high</code>
</li>
<li>
<b>Field added. </b>
<code>compat_ulong_t msg_ctime_high</code>
</li>
<li>
<b>Field removed. </b>
<code>compat_ulong_t __unused1</code>
</li>
<li>
<b>Field removed. </b>
<code>compat_ulong_t __unused2</code>
</li>
<li>
<b>Field removed. </b>
<code>compat_ulong_t __unused3</code>
</li>
<li>
<b>Field type changed. </b>
<code>compat_time_t msg_stime</code> ➡️ <code>compat_ulong_t msg_stime</code>
</li>
<li>
<b>Field type changed. </b>
<code>compat_time_t msg_rtime</code> ➡️ <code>compat_ulong_t msg_rtime</code>
</li>
<li>
<b>Field type changed. </b>
<code>compat_time_t msg_ctime</code> ➡️ <code>compat_ulong_t msg_ctime</code>
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
struct compat_msqid64_ds {
    struct compat_ipc64_perm msg_perm;
    compat_ulong_t msg_stime;
    compat_ulong_t msg_stime_high;
    compat_ulong_t msg_rtime;
    compat_ulong_t msg_rtime_high;
    compat_ulong_t msg_ctime;
    compat_ulong_t msg_ctime_high;
    compat_ulong_t msg_cbytes;
    compat_ulong_t msg_qnum;
    compat_ulong_t msg_qbytes;
    compat_pid_t msg_lspid;
    compat_pid_t msg_lrpid;
    compat_ulong_t __unused4;
    compat_ulong_t __unused5;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>compat_ulong_t msg_stime</code> ➡️ <code>unsigned int msg_stime</code>
</li>
<li>
<b>Field type changed. </b>
<code>compat_ulong_t msg_stime_high</code> ➡️ <code>unsigned int msg_stime_high</code>
</li>
<li>
<b>Field type changed. </b>
<code>compat_ulong_t msg_rtime</code> ➡️ <code>unsigned int msg_rtime</code>
</li>
<li>
<b>Field type changed. </b>
<code>compat_ulong_t msg_rtime_high</code> ➡️ <code>unsigned int msg_rtime_high</code>
</li>
<li>
<b>Field type changed. </b>
<code>compat_ulong_t msg_ctime</code> ➡️ <code>unsigned int msg_ctime</code>
</li>
<li>
<b>Field type changed. </b>
<code>compat_ulong_t msg_ctime_high</code> ➡️ <code>unsigned int msg_ctime_high</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct compat_msqid64_ds {
    struct compat_ipc64_perm msg_perm;
    compat_ulong_t msg_stime;
    compat_ulong_t msg_stime_high;
    compat_ulong_t msg_rtime;
    compat_ulong_t msg_rtime_high;
    compat_ulong_t msg_ctime;
    compat_ulong_t msg_ctime_high;
    compat_ulong_t msg_cbytes;
    compat_ulong_t msg_qnum;
    compat_ulong_t msg_qbytes;
    compat_pid_t msg_lspid;
    compat_pid_t msg_lrpid;
    compat_ulong_t __unused4;
    compat_ulong_t __unused5;
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
