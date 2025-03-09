# Struct: <code>msg_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct msg_queue {
    struct kern_ipc_perm q_perm;
    time_t q_stime;
    time_t q_rtime;
    time_t q_ctime;
    long unsigned int q_cbytes;
    long unsigned int q_qnum;
    long unsigned int q_qbytes;
    pid_t q_lspid;
    pid_t q_lrpid;
    struct list_head q_messages;
    struct list_head q_receivers;
    struct list_head q_senders;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct msg_queue {
    struct kern_ipc_perm q_perm;
    time_t q_stime;
    time_t q_rtime;
    time_t q_ctime;
    long unsigned int q_cbytes;
    long unsigned int q_qnum;
    long unsigned int q_qbytes;
    pid_t q_lspid;
    pid_t q_lrpid;
    struct list_head q_messages;
    struct list_head q_receivers;
    struct list_head q_senders;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct msg_queue {
    struct kern_ipc_perm q_perm;
    time_t q_stime;
    time_t q_rtime;
    time_t q_ctime;
    long unsigned int q_cbytes;
    long unsigned int q_qnum;
    long unsigned int q_qbytes;
    pid_t q_lspid;
    pid_t q_lrpid;
    struct list_head q_messages;
    struct list_head q_receivers;
    struct list_head q_senders;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct msg_queue {
    struct kern_ipc_perm q_perm;
    time_t q_stime;
    time_t q_rtime;
    time_t q_ctime;
    long unsigned int q_cbytes;
    long unsigned int q_qnum;
    long unsigned int q_qbytes;
    pid_t q_lspid;
    pid_t q_lrpid;
    struct list_head q_messages;
    struct list_head q_receivers;
    struct list_head q_senders;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct msg_queue {
    struct kern_ipc_perm q_perm;
    time64_t q_stime;
    time64_t q_rtime;
    time64_t q_ctime;
    long unsigned int q_cbytes;
    long unsigned int q_qnum;
    long unsigned int q_qbytes;
    pid_t q_lspid;
    pid_t q_lrpid;
    struct list_head q_messages;
    struct list_head q_receivers;
    struct list_head q_senders;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct msg_queue {
    struct kern_ipc_perm q_perm;
    time64_t q_stime;
    time64_t q_rtime;
    time64_t q_ctime;
    long unsigned int q_cbytes;
    long unsigned int q_qnum;
    long unsigned int q_qbytes;
    struct pid * q_lspid;
    struct pid * q_lrpid;
    struct list_head q_messages;
    struct list_head q_receivers;
    struct list_head q_senders;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct msg_queue {
    struct kern_ipc_perm q_perm;
    time64_t q_stime;
    time64_t q_rtime;
    time64_t q_ctime;
    long unsigned int q_cbytes;
    long unsigned int q_qnum;
    long unsigned int q_qbytes;
    struct pid * q_lspid;
    struct pid * q_lrpid;
    struct list_head q_messages;
    struct list_head q_receivers;
    struct list_head q_senders;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct msg_queue {
    struct kern_ipc_perm q_perm;
    time64_t q_stime;
    time64_t q_rtime;
    time64_t q_ctime;
    long unsigned int q_cbytes;
    long unsigned int q_qnum;
    long unsigned int q_qbytes;
    struct pid * q_lspid;
    struct pid * q_lrpid;
    struct list_head q_messages;
    struct list_head q_receivers;
    struct list_head q_senders;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct msg_queue {
    struct kern_ipc_perm q_perm;
    time64_t q_stime;
    time64_t q_rtime;
    time64_t q_ctime;
    long unsigned int q_cbytes;
    long unsigned int q_qnum;
    long unsigned int q_qbytes;
    struct pid * q_lspid;
    struct pid * q_lrpid;
    struct list_head q_messages;
    struct list_head q_receivers;
    struct list_head q_senders;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct msg_queue {
    struct kern_ipc_perm q_perm;
    time64_t q_stime;
    time64_t q_rtime;
    time64_t q_ctime;
    long unsigned int q_cbytes;
    long unsigned int q_qnum;
    long unsigned int q_qbytes;
    struct pid * q_lspid;
    struct pid * q_lrpid;
    struct list_head q_messages;
    struct list_head q_receivers;
    struct list_head q_senders;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct msg_queue {
    struct kern_ipc_perm q_perm;
    time64_t q_stime;
    time64_t q_rtime;
    time64_t q_ctime;
    long unsigned int q_cbytes;
    long unsigned int q_qnum;
    long unsigned int q_qbytes;
    struct pid * q_lspid;
    struct pid * q_lrpid;
    struct list_head q_messages;
    struct list_head q_receivers;
    struct list_head q_senders;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct msg_queue {
    struct kern_ipc_perm q_perm;
    time64_t q_stime;
    time64_t q_rtime;
    time64_t q_ctime;
    long unsigned int q_cbytes;
    long unsigned int q_qnum;
    long unsigned int q_qbytes;
    struct pid * q_lspid;
    struct pid * q_lrpid;
    struct list_head q_messages;
    struct list_head q_receivers;
    struct list_head q_senders;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct msg_queue {
    struct kern_ipc_perm q_perm;
    time64_t q_stime;
    time64_t q_rtime;
    time64_t q_ctime;
    long unsigned int q_cbytes;
    long unsigned int q_qnum;
    long unsigned int q_qbytes;
    struct pid * q_lspid;
    struct pid * q_lrpid;
    struct list_head q_messages;
    struct list_head q_receivers;
    struct list_head q_senders;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct msg_queue {
    struct kern_ipc_perm q_perm;
    time64_t q_stime;
    time64_t q_rtime;
    time64_t q_ctime;
    long unsigned int q_cbytes;
    long unsigned int q_qnum;
    long unsigned int q_qbytes;
    struct pid * q_lspid;
    struct pid * q_lrpid;
    struct list_head q_messages;
    struct list_head q_receivers;
    struct list_head q_senders;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct msg_queue {
    struct kern_ipc_perm q_perm;
    time64_t q_stime;
    time64_t q_rtime;
    time64_t q_ctime;
    long unsigned int q_cbytes;
    long unsigned int q_qnum;
    long unsigned int q_qbytes;
    struct pid * q_lspid;
    struct pid * q_lrpid;
    struct list_head q_messages;
    struct list_head q_receivers;
    struct list_head q_senders;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct msg_queue {
    struct kern_ipc_perm q_perm;
    time64_t q_stime;
    time64_t q_rtime;
    time64_t q_ctime;
    long unsigned int q_cbytes;
    long unsigned int q_qnum;
    long unsigned int q_qbytes;
    struct pid * q_lspid;
    struct pid * q_lrpid;
    struct list_head q_messages;
    struct list_head q_receivers;
    struct list_head q_senders;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct msg_queue {
    struct kern_ipc_perm q_perm;
    time64_t q_stime;
    time64_t q_rtime;
    time64_t q_ctime;
    long unsigned int q_cbytes;
    long unsigned int q_qnum;
    long unsigned int q_qbytes;
    struct pid * q_lspid;
    struct pid * q_lrpid;
    struct list_head q_messages;
    struct list_head q_receivers;
    struct list_head q_senders;
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
struct msg_queue {
    struct kern_ipc_perm q_perm;
    time64_t q_stime;
    time64_t q_rtime;
    time64_t q_ctime;
    long unsigned int q_cbytes;
    long unsigned int q_qnum;
    long unsigned int q_qbytes;
    struct pid * q_lspid;
    struct pid * q_lrpid;
    struct list_head q_messages;
    struct list_head q_receivers;
    struct list_head q_senders;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct msg_queue {
    struct kern_ipc_perm q_perm;
    time64_t q_stime;
    time64_t q_rtime;
    time64_t q_ctime;
    long unsigned int q_cbytes;
    long unsigned int q_qnum;
    long unsigned int q_qbytes;
    struct pid * q_lspid;
    struct pid * q_lrpid;
    struct list_head q_messages;
    struct list_head q_receivers;
    struct list_head q_senders;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct msg_queue {
    struct kern_ipc_perm q_perm;
    time64_t q_stime;
    time64_t q_rtime;
    time64_t q_ctime;
    long unsigned int q_cbytes;
    long unsigned int q_qnum;
    long unsigned int q_qbytes;
    struct pid * q_lspid;
    struct pid * q_lrpid;
    struct list_head q_messages;
    struct list_head q_receivers;
    struct list_head q_senders;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct msg_queue {
    struct kern_ipc_perm q_perm;
    time64_t q_stime;
    time64_t q_rtime;
    time64_t q_ctime;
    long unsigned int q_cbytes;
    long unsigned int q_qnum;
    long unsigned int q_qbytes;
    struct pid * q_lspid;
    struct pid * q_lrpid;
    struct list_head q_messages;
    struct list_head q_receivers;
    struct list_head q_senders;
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
struct msg_queue {
    struct kern_ipc_perm q_perm;
    time64_t q_stime;
    time64_t q_rtime;
    time64_t q_ctime;
    long unsigned int q_cbytes;
    long unsigned int q_qnum;
    long unsigned int q_qbytes;
    struct pid * q_lspid;
    struct pid * q_lrpid;
    struct list_head q_messages;
    struct list_head q_receivers;
    struct list_head q_senders;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct msg_queue {
    struct kern_ipc_perm q_perm;
    time64_t q_stime;
    time64_t q_rtime;
    time64_t q_ctime;
    long unsigned int q_cbytes;
    long unsigned int q_qnum;
    long unsigned int q_qbytes;
    struct pid * q_lspid;
    struct pid * q_lrpid;
    struct list_head q_messages;
    struct list_head q_receivers;
    struct list_head q_senders;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct msg_queue {
    struct kern_ipc_perm q_perm;
    time64_t q_stime;
    time64_t q_rtime;
    time64_t q_ctime;
    long unsigned int q_cbytes;
    long unsigned int q_qnum;
    long unsigned int q_qbytes;
    struct pid * q_lspid;
    struct pid * q_lrpid;
    struct list_head q_messages;
    struct list_head q_receivers;
    struct list_head q_senders;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct msg_queue {
    struct kern_ipc_perm q_perm;
    time64_t q_stime;
    time64_t q_rtime;
    time64_t q_ctime;
    long unsigned int q_cbytes;
    long unsigned int q_qnum;
    long unsigned int q_qbytes;
    struct pid * q_lspid;
    struct pid * q_lrpid;
    struct list_head q_messages;
    struct list_head q_receivers;
    struct list_head q_senders;
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>time_t q_stime</code> ➡️ <code>time64_t q_stime</code>
</li>
<li>
<b>Field type changed. </b>
<code>time_t q_rtime</code> ➡️ <code>time64_t q_rtime</code>
</li>
<li>
<b>Field type changed. </b>
<code>time_t q_ctime</code> ➡️ <code>time64_t q_ctime</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>pid_t q_lspid</code> ➡️ <code>struct pid * q_lspid</code>
</li>
<li>
<b>Field type changed. </b>
<code>pid_t q_lrpid</code> ➡️ <code>struct pid * q_lrpid</code>
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
