# Struct: <code>kioctx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct kioctx {
    struct percpu_ref users;
    atomic_t dead;
    struct percpu_ref reqs;
    long unsigned int user_id;
    struct kioctx_cpu * cpu;
    unsigned int req_batch;
    unsigned int max_reqs;
    unsigned int nr_events;
    long unsigned int mmap_base;
    long unsigned int mmap_size;
    struct page * * ring_pages;
    long int nr_pages;
    struct work_struct free_work;
    struct ctx_rq_wait * rq_wait;
    atomic_t reqs_available;
    spinlock_t ctx_lock;
    struct list_head active_reqs;
    struct mutex ring_lock;
    wait_queue_head_t wait;
    unsigned int tail;
    unsigned int completed_events;
    spinlock_t completion_lock;
    struct page *[8] internal_pages;
    struct file * aio_ring_file;
    unsigned int id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct kioctx {
    struct percpu_ref users;
    atomic_t dead;
    struct percpu_ref reqs;
    long unsigned int user_id;
    struct kioctx_cpu * cpu;
    unsigned int req_batch;
    unsigned int max_reqs;
    unsigned int nr_events;
    long unsigned int mmap_base;
    long unsigned int mmap_size;
    struct page * * ring_pages;
    long int nr_pages;
    struct work_struct free_work;
    struct ctx_rq_wait * rq_wait;
    atomic_t reqs_available;
    spinlock_t ctx_lock;
    struct list_head active_reqs;
    struct mutex ring_lock;
    wait_queue_head_t wait;
    unsigned int tail;
    unsigned int completed_events;
    spinlock_t completion_lock;
    struct page *[8] internal_pages;
    struct file * aio_ring_file;
    unsigned int id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct kioctx {
    struct percpu_ref users;
    atomic_t dead;
    struct percpu_ref reqs;
    long unsigned int user_id;
    struct kioctx_cpu * cpu;
    unsigned int req_batch;
    unsigned int max_reqs;
    unsigned int nr_events;
    long unsigned int mmap_base;
    long unsigned int mmap_size;
    struct page * * ring_pages;
    long int nr_pages;
    struct work_struct free_work;
    struct ctx_rq_wait * rq_wait;
    atomic_t reqs_available;
    spinlock_t ctx_lock;
    struct list_head active_reqs;
    struct mutex ring_lock;
    wait_queue_head_t wait;
    unsigned int tail;
    unsigned int completed_events;
    spinlock_t completion_lock;
    struct page *[8] internal_pages;
    struct file * aio_ring_file;
    unsigned int id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct kioctx {
    struct percpu_ref users;
    atomic_t dead;
    struct percpu_ref reqs;
    long unsigned int user_id;
    struct kioctx_cpu * cpu;
    unsigned int req_batch;
    unsigned int max_reqs;
    unsigned int nr_events;
    long unsigned int mmap_base;
    long unsigned int mmap_size;
    struct page * * ring_pages;
    long int nr_pages;
    struct work_struct free_work;
    struct ctx_rq_wait * rq_wait;
    atomic_t reqs_available;
    spinlock_t ctx_lock;
    struct list_head active_reqs;
    struct mutex ring_lock;
    wait_queue_head_t wait;
    unsigned int tail;
    unsigned int completed_events;
    spinlock_t completion_lock;
    struct page *[8] internal_pages;
    struct file * aio_ring_file;
    unsigned int id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct kioctx {
    struct percpu_ref users;
    atomic_t dead;
    struct percpu_ref reqs;
    long unsigned int user_id;
    struct kioctx_cpu * cpu;
    unsigned int req_batch;
    unsigned int max_reqs;
    unsigned int nr_events;
    long unsigned int mmap_base;
    long unsigned int mmap_size;
    struct page * * ring_pages;
    long int nr_pages;
    struct callback_head free_rcu;
    struct work_struct free_work;
    struct ctx_rq_wait * rq_wait;
    atomic_t reqs_available;
    spinlock_t ctx_lock;
    struct list_head active_reqs;
    struct mutex ring_lock;
    wait_queue_head_t wait;
    unsigned int tail;
    unsigned int completed_events;
    spinlock_t completion_lock;
    struct page *[8] internal_pages;
    struct file * aio_ring_file;
    unsigned int id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct kioctx {
    struct percpu_ref users;
    atomic_t dead;
    struct percpu_ref reqs;
    long unsigned int user_id;
    struct kioctx_cpu * cpu;
    unsigned int req_batch;
    unsigned int max_reqs;
    unsigned int nr_events;
    long unsigned int mmap_base;
    long unsigned int mmap_size;
    struct page * * ring_pages;
    long int nr_pages;
    struct rcu_work free_rwork;
    struct ctx_rq_wait * rq_wait;
    atomic_t reqs_available;
    spinlock_t ctx_lock;
    struct list_head active_reqs;
    struct mutex ring_lock;
    wait_queue_head_t wait;
    unsigned int tail;
    unsigned int completed_events;
    spinlock_t completion_lock;
    struct page *[8] internal_pages;
    struct file * aio_ring_file;
    unsigned int id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct kioctx {
    struct percpu_ref users;
    atomic_t dead;
    struct percpu_ref reqs;
    long unsigned int user_id;
    struct kioctx_cpu * cpu;
    unsigned int req_batch;
    unsigned int max_reqs;
    unsigned int nr_events;
    long unsigned int mmap_base;
    long unsigned int mmap_size;
    struct page * * ring_pages;
    long int nr_pages;
    struct rcu_work free_rwork;
    struct ctx_rq_wait * rq_wait;
    atomic_t reqs_available;
    spinlock_t ctx_lock;
    struct list_head active_reqs;
    struct mutex ring_lock;
    wait_queue_head_t wait;
    unsigned int tail;
    unsigned int completed_events;
    spinlock_t completion_lock;
    struct page *[8] internal_pages;
    struct file * aio_ring_file;
    unsigned int id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct kioctx {
    struct percpu_ref users;
    atomic_t dead;
    struct percpu_ref reqs;
    long unsigned int user_id;
    struct kioctx_cpu * cpu;
    unsigned int req_batch;
    unsigned int max_reqs;
    unsigned int nr_events;
    long unsigned int mmap_base;
    long unsigned int mmap_size;
    struct page * * ring_pages;
    long int nr_pages;
    struct rcu_work free_rwork;
    struct ctx_rq_wait * rq_wait;
    atomic_t reqs_available;
    spinlock_t ctx_lock;
    struct list_head active_reqs;
    struct mutex ring_lock;
    wait_queue_head_t wait;
    unsigned int tail;
    unsigned int completed_events;
    spinlock_t completion_lock;
    struct page *[8] internal_pages;
    struct file * aio_ring_file;
    unsigned int id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct kioctx {
    struct percpu_ref users;
    atomic_t dead;
    struct percpu_ref reqs;
    long unsigned int user_id;
    struct kioctx_cpu * cpu;
    unsigned int req_batch;
    unsigned int max_reqs;
    unsigned int nr_events;
    long unsigned int mmap_base;
    long unsigned int mmap_size;
    struct page * * ring_pages;
    long int nr_pages;
    struct rcu_work free_rwork;
    struct ctx_rq_wait * rq_wait;
    atomic_t reqs_available;
    spinlock_t ctx_lock;
    struct list_head active_reqs;
    struct mutex ring_lock;
    wait_queue_head_t wait;
    unsigned int tail;
    unsigned int completed_events;
    spinlock_t completion_lock;
    struct page *[8] internal_pages;
    struct file * aio_ring_file;
    unsigned int id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct kioctx {
    struct percpu_ref users;
    atomic_t dead;
    struct percpu_ref reqs;
    long unsigned int user_id;
    struct kioctx_cpu * cpu;
    unsigned int req_batch;
    unsigned int max_reqs;
    unsigned int nr_events;
    long unsigned int mmap_base;
    long unsigned int mmap_size;
    struct page * * ring_pages;
    long int nr_pages;
    struct rcu_work free_rwork;
    struct ctx_rq_wait * rq_wait;
    atomic_t reqs_available;
    spinlock_t ctx_lock;
    struct list_head active_reqs;
    struct mutex ring_lock;
    wait_queue_head_t wait;
    unsigned int tail;
    unsigned int completed_events;
    spinlock_t completion_lock;
    struct page *[8] internal_pages;
    struct file * aio_ring_file;
    unsigned int id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct kioctx {
    struct percpu_ref users;
    atomic_t dead;
    struct percpu_ref reqs;
    long unsigned int user_id;
    struct kioctx_cpu * cpu;
    unsigned int req_batch;
    unsigned int max_reqs;
    unsigned int nr_events;
    long unsigned int mmap_base;
    long unsigned int mmap_size;
    struct page * * ring_pages;
    long int nr_pages;
    struct rcu_work free_rwork;
    struct ctx_rq_wait * rq_wait;
    atomic_t reqs_available;
    spinlock_t ctx_lock;
    struct list_head active_reqs;
    struct mutex ring_lock;
    wait_queue_head_t wait;
    unsigned int tail;
    unsigned int completed_events;
    spinlock_t completion_lock;
    struct page *[8] internal_pages;
    struct file * aio_ring_file;
    unsigned int id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct kioctx {
    struct percpu_ref users;
    atomic_t dead;
    struct percpu_ref reqs;
    long unsigned int user_id;
    struct kioctx_cpu * cpu;
    unsigned int req_batch;
    unsigned int max_reqs;
    unsigned int nr_events;
    long unsigned int mmap_base;
    long unsigned int mmap_size;
    struct page * * ring_pages;
    long int nr_pages;
    struct rcu_work free_rwork;
    struct ctx_rq_wait * rq_wait;
    atomic_t reqs_available;
    spinlock_t ctx_lock;
    struct list_head active_reqs;
    struct mutex ring_lock;
    wait_queue_head_t wait;
    unsigned int tail;
    unsigned int completed_events;
    spinlock_t completion_lock;
    struct page *[8] internal_pages;
    struct file * aio_ring_file;
    unsigned int id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct kioctx {
    struct percpu_ref users;
    atomic_t dead;
    struct percpu_ref reqs;
    long unsigned int user_id;
    struct kioctx_cpu * cpu;
    unsigned int req_batch;
    unsigned int max_reqs;
    unsigned int nr_events;
    long unsigned int mmap_base;
    long unsigned int mmap_size;
    struct page * * ring_pages;
    long int nr_pages;
    struct rcu_work free_rwork;
    struct ctx_rq_wait * rq_wait;
    atomic_t reqs_available;
    spinlock_t ctx_lock;
    struct list_head active_reqs;
    struct mutex ring_lock;
    wait_queue_head_t wait;
    unsigned int tail;
    unsigned int completed_events;
    spinlock_t completion_lock;
    struct page *[8] internal_pages;
    struct file * aio_ring_file;
    unsigned int id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct kioctx {
    struct percpu_ref users;
    atomic_t dead;
    struct percpu_ref reqs;
    long unsigned int user_id;
    struct kioctx_cpu * cpu;
    unsigned int req_batch;
    unsigned int max_reqs;
    unsigned int nr_events;
    long unsigned int mmap_base;
    long unsigned int mmap_size;
    struct page * * ring_pages;
    long int nr_pages;
    struct rcu_work free_rwork;
    struct ctx_rq_wait * rq_wait;
    atomic_t reqs_available;
    spinlock_t ctx_lock;
    struct list_head active_reqs;
    struct mutex ring_lock;
    wait_queue_head_t wait;
    unsigned int tail;
    unsigned int completed_events;
    spinlock_t completion_lock;
    struct page *[8] internal_pages;
    struct file * aio_ring_file;
    unsigned int id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct kioctx {
    struct percpu_ref users;
    atomic_t dead;
    struct percpu_ref reqs;
    long unsigned int user_id;
    struct kioctx_cpu * cpu;
    unsigned int req_batch;
    unsigned int max_reqs;
    unsigned int nr_events;
    long unsigned int mmap_base;
    long unsigned int mmap_size;
    struct page * * ring_pages;
    long int nr_pages;
    struct rcu_work free_rwork;
    struct ctx_rq_wait * rq_wait;
    atomic_t reqs_available;
    spinlock_t ctx_lock;
    struct list_head active_reqs;
    struct mutex ring_lock;
    wait_queue_head_t wait;
    unsigned int tail;
    unsigned int completed_events;
    spinlock_t completion_lock;
    struct page *[8] internal_pages;
    struct file * aio_ring_file;
    unsigned int id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct kioctx {
    struct percpu_ref users;
    atomic_t dead;
    struct percpu_ref reqs;
    long unsigned int user_id;
    struct kioctx_cpu * cpu;
    unsigned int req_batch;
    unsigned int max_reqs;
    unsigned int nr_events;
    long unsigned int mmap_base;
    long unsigned int mmap_size;
    struct page * * ring_pages;
    long int nr_pages;
    struct rcu_work free_rwork;
    struct ctx_rq_wait * rq_wait;
    atomic_t reqs_available;
    spinlock_t ctx_lock;
    struct list_head active_reqs;
    struct mutex ring_lock;
    wait_queue_head_t wait;
    unsigned int tail;
    unsigned int completed_events;
    spinlock_t completion_lock;
    struct page *[8] internal_pages;
    struct file * aio_ring_file;
    unsigned int id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct kioctx {
    struct percpu_ref users;
    atomic_t dead;
    struct percpu_ref reqs;
    long unsigned int user_id;
    struct kioctx_cpu * cpu;
    unsigned int req_batch;
    unsigned int max_reqs;
    unsigned int nr_events;
    long unsigned int mmap_base;
    long unsigned int mmap_size;
    struct page * * ring_pages;
    long int nr_pages;
    struct rcu_work free_rwork;
    struct ctx_rq_wait * rq_wait;
    atomic_t reqs_available;
    spinlock_t ctx_lock;
    struct list_head active_reqs;
    struct mutex ring_lock;
    wait_queue_head_t wait;
    unsigned int tail;
    unsigned int completed_events;
    spinlock_t completion_lock;
    struct page *[8] internal_pages;
    struct file * aio_ring_file;
    unsigned int id;
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
struct kioctx {
    struct percpu_ref users;
    atomic_t dead;
    struct percpu_ref reqs;
    long unsigned int user_id;
    struct kioctx_cpu * cpu;
    unsigned int req_batch;
    unsigned int max_reqs;
    unsigned int nr_events;
    long unsigned int mmap_base;
    long unsigned int mmap_size;
    struct page * * ring_pages;
    long int nr_pages;
    struct rcu_work free_rwork;
    struct ctx_rq_wait * rq_wait;
    atomic_t reqs_available;
    spinlock_t ctx_lock;
    struct list_head active_reqs;
    struct mutex ring_lock;
    wait_queue_head_t wait;
    unsigned int tail;
    unsigned int completed_events;
    spinlock_t completion_lock;
    struct page *[8] internal_pages;
    struct file * aio_ring_file;
    unsigned int id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct kioctx {
    struct percpu_ref users;
    atomic_t dead;
    struct percpu_ref reqs;
    long unsigned int user_id;
    struct kioctx_cpu * cpu;
    unsigned int req_batch;
    unsigned int max_reqs;
    unsigned int nr_events;
    long unsigned int mmap_base;
    long unsigned int mmap_size;
    struct page * * ring_pages;
    long int nr_pages;
    struct rcu_work free_rwork;
    struct ctx_rq_wait * rq_wait;
    atomic_t reqs_available;
    spinlock_t ctx_lock;
    struct list_head active_reqs;
    struct mutex ring_lock;
    wait_queue_head_t wait;
    unsigned int tail;
    unsigned int completed_events;
    spinlock_t completion_lock;
    struct page *[8] internal_pages;
    struct file * aio_ring_file;
    unsigned int id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct kioctx {
    struct percpu_ref users;
    atomic_t dead;
    struct percpu_ref reqs;
    long unsigned int user_id;
    struct kioctx_cpu * cpu;
    unsigned int req_batch;
    unsigned int max_reqs;
    unsigned int nr_events;
    long unsigned int mmap_base;
    long unsigned int mmap_size;
    struct page * * ring_pages;
    long int nr_pages;
    struct rcu_work free_rwork;
    struct ctx_rq_wait * rq_wait;
    atomic_t reqs_available;
    spinlock_t ctx_lock;
    struct list_head active_reqs;
    struct mutex ring_lock;
    wait_queue_head_t wait;
    unsigned int tail;
    unsigned int completed_events;
    spinlock_t completion_lock;
    struct page *[8] internal_pages;
    struct file * aio_ring_file;
    unsigned int id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct kioctx {
    struct percpu_ref users;
    atomic_t dead;
    struct percpu_ref reqs;
    long unsigned int user_id;
    struct kioctx_cpu * cpu;
    unsigned int req_batch;
    unsigned int max_reqs;
    unsigned int nr_events;
    long unsigned int mmap_base;
    long unsigned int mmap_size;
    struct page * * ring_pages;
    long int nr_pages;
    struct rcu_work free_rwork;
    struct ctx_rq_wait * rq_wait;
    atomic_t reqs_available;
    spinlock_t ctx_lock;
    struct list_head active_reqs;
    struct mutex ring_lock;
    wait_queue_head_t wait;
    unsigned int tail;
    unsigned int completed_events;
    spinlock_t completion_lock;
    struct page *[8] internal_pages;
    struct file * aio_ring_file;
    unsigned int id;
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
struct kioctx {
    struct percpu_ref users;
    atomic_t dead;
    struct percpu_ref reqs;
    long unsigned int user_id;
    struct kioctx_cpu * cpu;
    unsigned int req_batch;
    unsigned int max_reqs;
    unsigned int nr_events;
    long unsigned int mmap_base;
    long unsigned int mmap_size;
    struct page * * ring_pages;
    long int nr_pages;
    struct rcu_work free_rwork;
    struct ctx_rq_wait * rq_wait;
    atomic_t reqs_available;
    spinlock_t ctx_lock;
    struct list_head active_reqs;
    struct mutex ring_lock;
    wait_queue_head_t wait;
    unsigned int tail;
    unsigned int completed_events;
    spinlock_t completion_lock;
    struct page *[8] internal_pages;
    struct file * aio_ring_file;
    unsigned int id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct kioctx {
    struct percpu_ref users;
    atomic_t dead;
    struct percpu_ref reqs;
    long unsigned int user_id;
    struct kioctx_cpu * cpu;
    unsigned int req_batch;
    unsigned int max_reqs;
    unsigned int nr_events;
    long unsigned int mmap_base;
    long unsigned int mmap_size;
    struct page * * ring_pages;
    long int nr_pages;
    struct rcu_work free_rwork;
    struct ctx_rq_wait * rq_wait;
    atomic_t reqs_available;
    spinlock_t ctx_lock;
    struct list_head active_reqs;
    struct mutex ring_lock;
    wait_queue_head_t wait;
    unsigned int tail;
    unsigned int completed_events;
    spinlock_t completion_lock;
    struct page *[8] internal_pages;
    struct file * aio_ring_file;
    unsigned int id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct kioctx {
    struct percpu_ref users;
    atomic_t dead;
    struct percpu_ref reqs;
    long unsigned int user_id;
    struct kioctx_cpu * cpu;
    unsigned int req_batch;
    unsigned int max_reqs;
    unsigned int nr_events;
    long unsigned int mmap_base;
    long unsigned int mmap_size;
    struct page * * ring_pages;
    long int nr_pages;
    struct rcu_work free_rwork;
    struct ctx_rq_wait * rq_wait;
    atomic_t reqs_available;
    spinlock_t ctx_lock;
    struct list_head active_reqs;
    struct mutex ring_lock;
    wait_queue_head_t wait;
    unsigned int tail;
    unsigned int completed_events;
    spinlock_t completion_lock;
    struct page *[8] internal_pages;
    struct file * aio_ring_file;
    unsigned int id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct kioctx {
    struct percpu_ref users;
    atomic_t dead;
    struct percpu_ref reqs;
    long unsigned int user_id;
    struct kioctx_cpu * cpu;
    unsigned int req_batch;
    unsigned int max_reqs;
    unsigned int nr_events;
    long unsigned int mmap_base;
    long unsigned int mmap_size;
    struct page * * ring_pages;
    long int nr_pages;
    struct rcu_work free_rwork;
    struct ctx_rq_wait * rq_wait;
    atomic_t reqs_available;
    spinlock_t ctx_lock;
    struct list_head active_reqs;
    struct mutex ring_lock;
    wait_queue_head_t wait;
    unsigned int tail;
    unsigned int completed_events;
    spinlock_t completion_lock;
    struct page *[8] internal_pages;
    struct file * aio_ring_file;
    unsigned int id;
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
<b>Field added. </b>
<code>struct callback_head free_rcu</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct rcu_work free_rwork</code>
</li>
<li>
<b>Field removed. </b>
<code>struct callback_head free_rcu</code>
</li>
<li>
<b>Field removed. </b>
<code>struct work_struct free_work</code>
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
