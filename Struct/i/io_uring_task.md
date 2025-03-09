# Struct: <code>io_uring_task</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct io_uring_task {
    struct xarray xa;
    struct wait_queue_head wait;
    struct file * last;
    struct percpu_counter inflight;
    struct io_identity __identity;
    struct io_identity * identity;
    atomic_t in_idle;
    bool sqpoll;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct io_uring_task {
    struct xarray xa;
    struct wait_queue_head wait;
    const struct io_ring_ctx * last;
    struct io_wq * io_wq;
    struct percpu_counter inflight;
    atomic_t inflight_tracked;
    atomic_t in_idle;
    spinlock_t task_lock;
    struct io_wq_work_list task_list;
    long unsigned int task_state;
    struct callback_head task_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct io_uring_task {
    int cached_refs;
    struct xarray xa;
    struct wait_queue_head wait;
    const struct io_ring_ctx * last;
    struct io_wq * io_wq;
    struct percpu_counter inflight;
    atomic_t inflight_tracked;
    atomic_t in_idle;
    spinlock_t task_lock;
    struct io_wq_work_list task_list;
    struct callback_head task_work;
    bool task_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct io_uring_task {
    int cached_refs;
    struct xarray xa;
    struct wait_queue_head wait;
    const struct io_ring_ctx * last;
    struct io_wq * io_wq;
    struct percpu_counter inflight;
    atomic_t inflight_tracked;
    atomic_t in_idle;
    spinlock_t task_lock;
    struct io_wq_work_list task_list;
    struct io_wq_work_list prio_task_list;
    struct callback_head task_work;
    struct file * * registered_rings;
    bool task_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct io_uring_task {
    int cached_refs;
    const struct io_ring_ctx * last;
    struct io_wq * io_wq;
    struct file *[16] registered_rings;
    struct xarray xa;
    struct wait_queue_head wait;
    atomic_t in_idle;
    atomic_t inflight_tracked;
    struct percpu_counter inflight;
    struct llist_head task_list;
    struct callback_head task_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct io_uring_task {
    int cached_refs;
    const struct io_ring_ctx * last;
    struct io_wq * io_wq;
    struct file *[16] registered_rings;
    struct xarray xa;
    struct wait_queue_head wait;
    atomic_t in_cancel;
    atomic_t inflight_tracked;
    struct percpu_counter inflight;
    struct llist_head task_list;
    struct callback_head task_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct io_uring_task {
    int cached_refs;
    const struct io_ring_ctx * last;
    struct io_wq * io_wq;
    struct file *[16] registered_rings;
    struct xarray xa;
    struct wait_queue_head wait;
    atomic_t in_cancel;
    atomic_t inflight_tracked;
    struct percpu_counter inflight;
    struct llist_head task_list;
    struct callback_head task_work;
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
struct io_uring_task {
    struct xarray xa;
    struct wait_queue_head wait;
    struct file * last;
    struct percpu_counter inflight;
    struct io_identity __identity;
    struct io_identity * identity;
    atomic_t in_idle;
    bool sqpoll;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct io_wq * io_wq</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t inflight_tracked</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t task_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_wq_work_list task_list</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int task_state</code>
</li>
<li>
<b>Field added. </b>
<code>struct callback_head task_work</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_identity __identity</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_identity * identity</code>
</li>
<li>
<b>Field removed. </b>
<code>bool sqpoll</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct file * last</code> ➡️ <code>const struct io_ring_ctx * last</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int cached_refs</code>
</li>
<li>
<b>Field added. </b>
<code>bool task_running</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int task_state</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct io_wq_work_list prio_task_list</code>
</li>
<li>
<b>Field added. </b>
<code>struct file * * registered_rings</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>spinlock_t task_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_wq_work_list prio_task_list</code>
</li>
<li>
<b>Field removed. </b>
<code>bool task_running</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct io_wq_work_list task_list</code> ➡️ <code>struct llist_head task_list</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct file * * registered_rings</code> ➡️ <code>struct file *[16] registered_rings</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>atomic_t in_cancel</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t in_idle</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
