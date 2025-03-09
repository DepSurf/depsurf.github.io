# Struct: <code>io_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct io_context {
    atomic_long_t refcount;
    atomic_t active_ref;
    atomic_t nr_tasks;
    spinlock_t lock;
    short unsigned int ioprio;
    int nr_batch_requests;
    long unsigned int last_waited;
    struct radix_tree_root icq_tree;
    struct io_cq * icq_hint;
    struct hlist_head icq_list;
    struct work_struct release_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct io_context {
    atomic_long_t refcount;
    atomic_t active_ref;
    atomic_t nr_tasks;
    spinlock_t lock;
    short unsigned int ioprio;
    int nr_batch_requests;
    long unsigned int last_waited;
    struct radix_tree_root icq_tree;
    struct io_cq * icq_hint;
    struct hlist_head icq_list;
    struct work_struct release_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct io_context {
    atomic_long_t refcount;
    atomic_t active_ref;
    atomic_t nr_tasks;
    spinlock_t lock;
    short unsigned int ioprio;
    int nr_batch_requests;
    long unsigned int last_waited;
    struct radix_tree_root icq_tree;
    struct io_cq * icq_hint;
    struct hlist_head icq_list;
    struct work_struct release_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct io_context {
    atomic_long_t refcount;
    atomic_t active_ref;
    atomic_t nr_tasks;
    spinlock_t lock;
    short unsigned int ioprio;
    int nr_batch_requests;
    long unsigned int last_waited;
    struct radix_tree_root icq_tree;
    struct io_cq * icq_hint;
    struct hlist_head icq_list;
    struct work_struct release_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct io_context {
    atomic_long_t refcount;
    atomic_t active_ref;
    atomic_t nr_tasks;
    spinlock_t lock;
    short unsigned int ioprio;
    int nr_batch_requests;
    long unsigned int last_waited;
    struct radix_tree_root icq_tree;
    struct io_cq * icq_hint;
    struct hlist_head icq_list;
    struct work_struct release_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct io_context {
    atomic_long_t refcount;
    atomic_t active_ref;
    atomic_t nr_tasks;
    spinlock_t lock;
    short unsigned int ioprio;
    int nr_batch_requests;
    long unsigned int last_waited;
    struct radix_tree_root icq_tree;
    struct io_cq * icq_hint;
    struct hlist_head icq_list;
    struct work_struct release_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct io_context {
    atomic_long_t refcount;
    atomic_t active_ref;
    atomic_t nr_tasks;
    spinlock_t lock;
    short unsigned int ioprio;
    int nr_batch_requests;
    long unsigned int last_waited;
    struct xarray icq_tree;
    struct io_cq * icq_hint;
    struct hlist_head icq_list;
    struct work_struct release_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct io_context {
    atomic_long_t refcount;
    atomic_t active_ref;
    atomic_t nr_tasks;
    spinlock_t lock;
    short unsigned int ioprio;
    int nr_batch_requests;
    long unsigned int last_waited;
    struct xarray icq_tree;
    struct io_cq * icq_hint;
    struct hlist_head icq_list;
    struct work_struct release_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct io_context {
    atomic_long_t refcount;
    atomic_t active_ref;
    atomic_t nr_tasks;
    spinlock_t lock;
    short unsigned int ioprio;
    int nr_batch_requests;
    long unsigned int last_waited;
    struct xarray icq_tree;
    struct io_cq * icq_hint;
    struct hlist_head icq_list;
    struct work_struct release_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct io_context {
    atomic_long_t refcount;
    atomic_t active_ref;
    atomic_t nr_tasks;
    spinlock_t lock;
    short unsigned int ioprio;
    int nr_batch_requests;
    long unsigned int last_waited;
    struct xarray icq_tree;
    struct io_cq * icq_hint;
    struct hlist_head icq_list;
    struct work_struct release_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct io_context {
    atomic_long_t refcount;
    atomic_t active_ref;
    atomic_t nr_tasks;
    spinlock_t lock;
    short unsigned int ioprio;
    struct xarray icq_tree;
    struct io_cq * icq_hint;
    struct hlist_head icq_list;
    struct work_struct release_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct io_context {
    atomic_long_t refcount;
    atomic_t active_ref;
    atomic_t nr_tasks;
    spinlock_t lock;
    short unsigned int ioprio;
    struct xarray icq_tree;
    struct io_cq * icq_hint;
    struct hlist_head icq_list;
    struct work_struct release_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct io_context {
    atomic_long_t refcount;
    atomic_t active_ref;
    atomic_t nr_tasks;
    spinlock_t lock;
    short unsigned int ioprio;
    struct xarray icq_tree;
    struct io_cq * icq_hint;
    struct hlist_head icq_list;
    struct work_struct release_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct io_context {
    atomic_long_t refcount;
    atomic_t active_ref;
    short unsigned int ioprio;
    spinlock_t lock;
    struct xarray icq_tree;
    struct io_cq * icq_hint;
    struct hlist_head icq_list;
    struct work_struct release_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct io_context {
    atomic_long_t refcount;
    atomic_t active_ref;
    short unsigned int ioprio;
    spinlock_t lock;
    struct xarray icq_tree;
    struct io_cq * icq_hint;
    struct hlist_head icq_list;
    struct work_struct release_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct io_context {
    atomic_long_t refcount;
    atomic_t active_ref;
    short unsigned int ioprio;
    spinlock_t lock;
    struct xarray icq_tree;
    struct io_cq * icq_hint;
    struct hlist_head icq_list;
    struct work_struct release_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct io_context {
    atomic_long_t refcount;
    atomic_t active_ref;
    short unsigned int ioprio;
    spinlock_t lock;
    struct xarray icq_tree;
    struct io_cq * icq_hint;
    struct hlist_head icq_list;
    struct work_struct release_work;
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
struct io_context {
    atomic_long_t refcount;
    atomic_t active_ref;
    atomic_t nr_tasks;
    spinlock_t lock;
    short unsigned int ioprio;
    int nr_batch_requests;
    long unsigned int last_waited;
    struct xarray icq_tree;
    struct io_cq * icq_hint;
    struct hlist_head icq_list;
    struct work_struct release_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct io_context {
    atomic_long_t refcount;
    atomic_t active_ref;
    atomic_t nr_tasks;
    spinlock_t lock;
    short unsigned int ioprio;
    int nr_batch_requests;
    long unsigned int last_waited;
    struct xarray icq_tree;
    struct io_cq * icq_hint;
    struct hlist_head icq_list;
    struct work_struct release_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct io_context {
    atomic_long_t refcount;
    atomic_t active_ref;
    atomic_t nr_tasks;
    spinlock_t lock;
    short unsigned int ioprio;
    int nr_batch_requests;
    long unsigned int last_waited;
    struct xarray icq_tree;
    struct io_cq * icq_hint;
    struct hlist_head icq_list;
    struct work_struct release_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct io_context {
    atomic_long_t refcount;
    atomic_t active_ref;
    atomic_t nr_tasks;
    spinlock_t lock;
    short unsigned int ioprio;
    int nr_batch_requests;
    long unsigned int last_waited;
    struct xarray icq_tree;
    struct io_cq * icq_hint;
    struct hlist_head icq_list;
    struct work_struct release_work;
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
struct io_context {
    atomic_long_t refcount;
    atomic_t active_ref;
    atomic_t nr_tasks;
    spinlock_t lock;
    short unsigned int ioprio;
    int nr_batch_requests;
    long unsigned int last_waited;
    struct xarray icq_tree;
    struct io_cq * icq_hint;
    struct hlist_head icq_list;
    struct work_struct release_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct io_context {
    atomic_long_t refcount;
    atomic_t active_ref;
    atomic_t nr_tasks;
    spinlock_t lock;
    short unsigned int ioprio;
    int nr_batch_requests;
    long unsigned int last_waited;
    struct xarray icq_tree;
    struct io_cq * icq_hint;
    struct hlist_head icq_list;
    struct work_struct release_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct io_context {
    atomic_long_t refcount;
    atomic_t active_ref;
    atomic_t nr_tasks;
    spinlock_t lock;
    short unsigned int ioprio;
    int nr_batch_requests;
    long unsigned int last_waited;
    struct xarray icq_tree;
    struct io_cq * icq_hint;
    struct hlist_head icq_list;
    struct work_struct release_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct io_context {
    atomic_long_t refcount;
    atomic_t active_ref;
    atomic_t nr_tasks;
    spinlock_t lock;
    short unsigned int ioprio;
    int nr_batch_requests;
    long unsigned int last_waited;
    struct xarray icq_tree;
    struct io_cq * icq_hint;
    struct hlist_head icq_list;
    struct work_struct release_work;
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct radix_tree_root icq_tree</code> ➡️ <code>struct xarray icq_tree</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int nr_batch_requests</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int last_waited</code>
</li>
</ul>
</details>
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
<b>Field removed. </b>
<code>atomic_t nr_tasks</code>
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
