# Struct: <code>svc_pool</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct svc_pool {
    unsigned int sp_id;
    spinlock_t sp_lock;
    struct list_head sp_sockets;
    unsigned int sp_nrthreads;
    struct list_head sp_all_threads;
    struct svc_pool_stats sp_stats;
    long unsigned int sp_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct svc_pool {
    unsigned int sp_id;
    spinlock_t sp_lock;
    struct list_head sp_sockets;
    unsigned int sp_nrthreads;
    struct list_head sp_all_threads;
    struct svc_pool_stats sp_stats;
    long unsigned int sp_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct svc_pool {
    unsigned int sp_id;
    spinlock_t sp_lock;
    struct list_head sp_sockets;
    unsigned int sp_nrthreads;
    struct list_head sp_all_threads;
    struct svc_pool_stats sp_stats;
    long unsigned int sp_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct svc_pool {
    unsigned int sp_id;
    spinlock_t sp_lock;
    struct list_head sp_sockets;
    unsigned int sp_nrthreads;
    struct list_head sp_all_threads;
    struct percpu_counter sp_sockets_queued;
    struct percpu_counter sp_threads_woken;
    struct percpu_counter sp_threads_timedout;
    long unsigned int sp_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct svc_pool {
    unsigned int sp_id;
    struct lwq sp_xprts;
    atomic_t sp_nrthreads;
    struct list_head sp_all_threads;
    struct llist_head sp_idle_threads;
    struct percpu_counter sp_messages_arrived;
    struct percpu_counter sp_sockets_queued;
    struct percpu_counter sp_threads_woken;
    long unsigned int sp_flags;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
struct svc_pool {
    unsigned int sp_id;
    spinlock_t sp_lock;
    struct list_head sp_sockets;
    unsigned int sp_nrthreads;
    struct list_head sp_all_threads;
    struct svc_pool_stats sp_stats;
    long unsigned int sp_flags;
}
```
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct percpu_counter sp_sockets_queued</code>
</li>
<li>
<b>Field added. </b>
<code>struct percpu_counter sp_threads_woken</code>
</li>
<li>
<b>Field added. </b>
<code>struct percpu_counter sp_threads_timedout</code>
</li>
<li>
<b>Field removed. </b>
<code>struct svc_pool_stats sp_stats</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct lwq sp_xprts</code>
</li>
<li>
<b>Field added. </b>
<code>struct llist_head sp_idle_threads</code>
</li>
<li>
<b>Field added. </b>
<code>struct percpu_counter sp_messages_arrived</code>
</li>
<li>
<b>Field removed. </b>
<code>spinlock_t sp_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head sp_sockets</code>
</li>
<li>
<b>Field removed. </b>
<code>struct percpu_counter sp_threads_timedout</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int sp_nrthreads</code> ➡️ <code>atomic_t sp_nrthreads</code>
</li>
</ul>
</details>
</li>
</ul>
