# Struct: <code>io_wqe</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct io_wqe {
    spinlock_t lock;
    struct io_wq_work_list work_list;
    long unsigned int hash_map;
    unsigned int flags;
    int node;
    struct io_wqe_acct[2] acct;
    struct hlist_nulls_head free_list;
    struct list_head all_list;
    struct io_wq * wq;
    struct io_wq_work *[64] hash_tail;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct io_wqe {
    raw_spinlock_t lock;
    struct io_wq_work_list work_list;
    long unsigned int hash_map;
    unsigned int flags;
    int node;
    struct io_wqe_acct[2] acct;
    struct hlist_nulls_head free_list;
    struct list_head all_list;
    struct io_wq * wq;
    struct io_wq_work *[64] hash_tail;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct io_wqe {
    raw_spinlock_t lock;
    struct io_wq_work_list work_list;
    unsigned int flags;
    int node;
    struct io_wqe_acct[2] acct;
    struct hlist_nulls_head free_list;
    struct list_head all_list;
    struct wait_queue_entry wait;
    struct io_wq * wq;
    struct io_wq_work *[64] hash_tail;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct io_wqe {
    raw_spinlock_t lock;
    struct io_wqe_acct[2] acct;
    int node;
    struct hlist_nulls_head free_list;
    struct list_head all_list;
    struct wait_queue_entry wait;
    struct io_wq * wq;
    struct io_wq_work *[64] hash_tail;
    cpumask_var_t cpu_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct io_wqe {
    raw_spinlock_t lock;
    struct io_wqe_acct[2] acct;
    int node;
    struct hlist_nulls_head free_list;
    struct list_head all_list;
    struct wait_queue_entry wait;
    struct io_wq * wq;
    struct io_wq_work *[64] hash_tail;
    cpumask_var_t cpu_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct io_wqe {
    raw_spinlock_t lock;
    struct io_wqe_acct[2] acct;
    int node;
    struct hlist_nulls_head free_list;
    struct list_head all_list;
    struct wait_queue_entry wait;
    struct io_wq * wq;
    struct io_wq_work *[64] hash_tail;
    cpumask_var_t cpu_mask;
}
```
</details>
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct io_wqe {
    spinlock_t lock;
    struct io_wq_work_list work_list;
    long unsigned int hash_map;
    unsigned int flags;
    int node;
    struct io_wqe_acct[2] acct;
    struct hlist_nulls_head free_list;
    struct list_head all_list;
    struct io_wq * wq;
    struct io_wq_work *[64] hash_tail;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>spinlock_t lock</code> ➡️ <code>raw_spinlock_t lock</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct wait_queue_entry wait</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int hash_map</code>
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
<code>cpumask_var_t cpu_mask</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_wq_work_list work_list</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int flags</code>
</li>
</ul>
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
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
struct io_wqe {
    raw_spinlock_t lock;
    struct io_wqe_acct[2] acct;
    int node;
    struct hlist_nulls_head free_list;
    struct list_head all_list;
    struct wait_queue_entry wait;
    struct io_wq * wq;
    struct io_wq_work *[64] hash_tail;
    cpumask_var_t cpu_mask;
}
```
</details>
</li>
</ul>
