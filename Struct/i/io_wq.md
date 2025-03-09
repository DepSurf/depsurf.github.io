# Struct: <code>io_wq</code>

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
struct io_wq {
    struct io_wqe * * wqes;
    long unsigned int state;
    free_work_fn * free_work;
    io_wq_work_fn * do_work;
    struct task_struct * manager;
    struct user_struct * user;
    refcount_t refs;
    struct completion done;
    refcount_t use_refs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct io_wq {
    struct io_wqe * * wqes;
    long unsigned int state;
    free_work_fn * free_work;
    io_wq_work_fn * do_work;
    struct task_struct * manager;
    struct user_struct * user;
    refcount_t refs;
    struct completion done;
    struct hlist_node cpuhp_node;
    refcount_t use_refs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct io_wq {
    struct io_wqe * * wqes;
    long unsigned int state;
    free_work_fn * free_work;
    io_wq_work_fn * do_work;
    struct io_wq_hash * hash;
    refcount_t refs;
    atomic_t worker_refs;
    struct completion worker_done;
    struct hlist_node cpuhp_node;
    struct task_struct * task;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct io_wq {
    long unsigned int state;
    free_work_fn * free_work;
    io_wq_work_fn * do_work;
    struct io_wq_hash * hash;
    atomic_t worker_refs;
    struct completion worker_done;
    struct hlist_node cpuhp_node;
    struct task_struct * task;
    struct io_wqe *[0] wqes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct io_wq {
    long unsigned int state;
    free_work_fn * free_work;
    io_wq_work_fn * do_work;
    struct io_wq_hash * hash;
    atomic_t worker_refs;
    struct completion worker_done;
    struct hlist_node cpuhp_node;
    struct task_struct * task;
    struct io_wqe *[0] wqes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct io_wq {
    long unsigned int state;
    free_work_fn * free_work;
    io_wq_work_fn * do_work;
    struct io_wq_hash * hash;
    atomic_t worker_refs;
    struct completion worker_done;
    struct hlist_node cpuhp_node;
    struct task_struct * task;
    struct io_wqe *[0] wqes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct io_wq {
    long unsigned int state;
    free_work_fn * free_work;
    io_wq_work_fn * do_work;
    struct io_wq_hash * hash;
    atomic_t worker_refs;
    struct completion worker_done;
    struct hlist_node cpuhp_node;
    struct task_struct * task;
    struct io_wq_acct[2] acct;
    raw_spinlock_t lock;
    struct hlist_nulls_head free_list;
    struct list_head all_list;
    struct wait_queue_entry wait;
    struct io_wq_work *[64] hash_tail;
    cpumask_var_t cpu_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct io_wq {
    long unsigned int state;
    free_work_fn * free_work;
    io_wq_work_fn * do_work;
    struct io_wq_hash * hash;
    atomic_t worker_refs;
    struct completion worker_done;
    struct hlist_node cpuhp_node;
    struct task_struct * task;
    struct io_wq_acct[2] acct;
    raw_spinlock_t lock;
    struct hlist_nulls_head free_list;
    struct list_head all_list;
    struct wait_queue_entry wait;
    struct io_wq_work *[64] hash_tail;
    cpumask_var_t cpu_mask;
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct io_wq {
    struct io_wqe * * wqes;
    long unsigned int state;
    free_work_fn * free_work;
    io_wq_work_fn * do_work;
    struct task_struct * manager;
    struct user_struct * user;
    refcount_t refs;
    struct completion done;
    refcount_t use_refs;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct hlist_node cpuhp_node</code>
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
<code>struct io_wq_hash * hash</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t worker_refs</code>
</li>
<li>
<b>Field added. </b>
<code>struct completion worker_done</code>
</li>
<li>
<b>Field added. </b>
<code>struct task_struct * task</code>
</li>
<li>
<b>Field removed. </b>
<code>struct task_struct * manager</code>
</li>
<li>
<b>Field removed. </b>
<code>struct user_struct * user</code>
</li>
<li>
<b>Field removed. </b>
<code>struct completion done</code>
</li>
<li>
<b>Field removed. </b>
<code>refcount_t use_refs</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>refcount_t refs</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct io_wqe * * wqes</code> ➡️ <code>struct io_wqe *[0] wqes</code>
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
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct io_wq_acct[2] acct</code>
</li>
<li>
<b>Field added. </b>
<code>raw_spinlock_t lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_nulls_head free_list</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head all_list</code>
</li>
<li>
<b>Field added. </b>
<code>struct wait_queue_entry wait</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_wq_work *[64] hash_tail</code>
</li>
<li>
<b>Field added. </b>
<code>cpumask_var_t cpu_mask</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_wqe *[0] wqes</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
