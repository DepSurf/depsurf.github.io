# Struct: <code>dm_kcopyd_client</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dm_kcopyd_client {
    struct page_list * pages;
    unsigned int nr_reserved_pages;
    unsigned int nr_free_pages;
    struct dm_io_client * io_client;
    wait_queue_head_t destroyq;
    atomic_t nr_jobs;
    mempool_t * job_pool;
    struct workqueue_struct * kcopyd_wq;
    struct work_struct kcopyd_work;
    struct dm_kcopyd_throttle * throttle;
    spinlock_t job_lock;
    struct list_head complete_jobs;
    struct list_head io_jobs;
    struct list_head pages_jobs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct dm_kcopyd_client {
    struct page_list * pages;
    unsigned int nr_reserved_pages;
    unsigned int nr_free_pages;
    struct dm_io_client * io_client;
    wait_queue_head_t destroyq;
    atomic_t nr_jobs;
    mempool_t * job_pool;
    struct workqueue_struct * kcopyd_wq;
    struct work_struct kcopyd_work;
    struct dm_kcopyd_throttle * throttle;
    spinlock_t job_lock;
    struct list_head complete_jobs;
    struct list_head io_jobs;
    struct list_head pages_jobs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct dm_kcopyd_client {
    struct page_list * pages;
    unsigned int nr_reserved_pages;
    unsigned int nr_free_pages;
    struct dm_io_client * io_client;
    wait_queue_head_t destroyq;
    atomic_t nr_jobs;
    mempool_t * job_pool;
    struct workqueue_struct * kcopyd_wq;
    struct work_struct kcopyd_work;
    struct dm_kcopyd_throttle * throttle;
    spinlock_t job_lock;
    struct list_head complete_jobs;
    struct list_head io_jobs;
    struct list_head pages_jobs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dm_kcopyd_client {
    struct page_list * pages;
    unsigned int nr_reserved_pages;
    unsigned int nr_free_pages;
    struct dm_io_client * io_client;
    wait_queue_head_t destroyq;
    atomic_t nr_jobs;
    mempool_t * job_pool;
    struct workqueue_struct * kcopyd_wq;
    struct work_struct kcopyd_work;
    struct dm_kcopyd_throttle * throttle;
    spinlock_t job_lock;
    struct list_head complete_jobs;
    struct list_head io_jobs;
    struct list_head pages_jobs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dm_kcopyd_client {
    struct page_list * pages;
    unsigned int nr_reserved_pages;
    unsigned int nr_free_pages;
    struct dm_io_client * io_client;
    wait_queue_head_t destroyq;
    atomic_t nr_jobs;
    mempool_t * job_pool;
    struct workqueue_struct * kcopyd_wq;
    struct work_struct kcopyd_work;
    struct dm_kcopyd_throttle * throttle;
    spinlock_t job_lock;
    struct list_head complete_jobs;
    struct list_head io_jobs;
    struct list_head pages_jobs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dm_kcopyd_client {
    struct page_list * pages;
    unsigned int nr_reserved_pages;
    unsigned int nr_free_pages;
    struct dm_io_client * io_client;
    wait_queue_head_t destroyq;
    mempool_t job_pool;
    struct workqueue_struct * kcopyd_wq;
    struct work_struct kcopyd_work;
    struct dm_kcopyd_throttle * throttle;
    atomic_t nr_jobs;
    spinlock_t job_lock;
    struct list_head complete_jobs;
    struct list_head io_jobs;
    struct list_head pages_jobs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dm_kcopyd_client {
    struct page_list * pages;
    unsigned int nr_reserved_pages;
    unsigned int nr_free_pages;
    struct dm_io_client * io_client;
    wait_queue_head_t destroyq;
    mempool_t job_pool;
    struct workqueue_struct * kcopyd_wq;
    struct work_struct kcopyd_work;
    struct dm_kcopyd_throttle * throttle;
    atomic_t nr_jobs;
    spinlock_t job_lock;
    struct list_head callback_jobs;
    struct list_head complete_jobs;
    struct list_head io_jobs;
    struct list_head pages_jobs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dm_kcopyd_client {
    struct page_list * pages;
    unsigned int nr_reserved_pages;
    unsigned int nr_free_pages;
    unsigned int sub_job_size;
    struct dm_io_client * io_client;
    wait_queue_head_t destroyq;
    mempool_t job_pool;
    struct workqueue_struct * kcopyd_wq;
    struct work_struct kcopyd_work;
    struct dm_kcopyd_throttle * throttle;
    atomic_t nr_jobs;
    spinlock_t job_lock;
    struct list_head callback_jobs;
    struct list_head complete_jobs;
    struct list_head io_jobs;
    struct list_head pages_jobs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct dm_kcopyd_client {
    struct page_list * pages;
    unsigned int nr_reserved_pages;
    unsigned int nr_free_pages;
    unsigned int sub_job_size;
    struct dm_io_client * io_client;
    wait_queue_head_t destroyq;
    mempool_t job_pool;
    struct workqueue_struct * kcopyd_wq;
    struct work_struct kcopyd_work;
    struct dm_kcopyd_throttle * throttle;
    atomic_t nr_jobs;
    spinlock_t job_lock;
    struct list_head callback_jobs;
    struct list_head complete_jobs;
    struct list_head io_jobs;
    struct list_head pages_jobs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct dm_kcopyd_client {
    struct page_list * pages;
    unsigned int nr_reserved_pages;
    unsigned int nr_free_pages;
    unsigned int sub_job_size;
    struct dm_io_client * io_client;
    wait_queue_head_t destroyq;
    mempool_t job_pool;
    struct workqueue_struct * kcopyd_wq;
    struct work_struct kcopyd_work;
    struct dm_kcopyd_throttle * throttle;
    atomic_t nr_jobs;
    spinlock_t job_lock;
    struct list_head callback_jobs;
    struct list_head complete_jobs;
    struct list_head io_jobs;
    struct list_head pages_jobs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct dm_kcopyd_client {
    struct page_list * pages;
    unsigned int nr_reserved_pages;
    unsigned int nr_free_pages;
    unsigned int sub_job_size;
    struct dm_io_client * io_client;
    wait_queue_head_t destroyq;
    mempool_t job_pool;
    struct workqueue_struct * kcopyd_wq;
    struct work_struct kcopyd_work;
    struct dm_kcopyd_throttle * throttle;
    atomic_t nr_jobs;
    spinlock_t job_lock;
    struct list_head callback_jobs;
    struct list_head complete_jobs;
    struct list_head io_jobs;
    struct list_head pages_jobs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct dm_kcopyd_client {
    struct page_list * pages;
    unsigned int nr_reserved_pages;
    unsigned int nr_free_pages;
    unsigned int sub_job_size;
    struct dm_io_client * io_client;
    wait_queue_head_t destroyq;
    mempool_t job_pool;
    struct workqueue_struct * kcopyd_wq;
    struct work_struct kcopyd_work;
    struct dm_kcopyd_throttle * throttle;
    atomic_t nr_jobs;
    spinlock_t job_lock;
    struct list_head callback_jobs;
    struct list_head complete_jobs;
    struct list_head io_jobs;
    struct list_head pages_jobs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct dm_kcopyd_client {
    struct page_list * pages;
    unsigned int nr_reserved_pages;
    unsigned int nr_free_pages;
    unsigned int sub_job_size;
    struct dm_io_client * io_client;
    wait_queue_head_t destroyq;
    mempool_t job_pool;
    struct workqueue_struct * kcopyd_wq;
    struct work_struct kcopyd_work;
    struct dm_kcopyd_throttle * throttle;
    atomic_t nr_jobs;
    spinlock_t job_lock;
    struct list_head callback_jobs;
    struct list_head complete_jobs;
    struct list_head io_jobs;
    struct list_head pages_jobs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct dm_kcopyd_client {
    struct page_list * pages;
    unsigned int nr_reserved_pages;
    unsigned int nr_free_pages;
    unsigned int sub_job_size;
    struct dm_io_client * io_client;
    wait_queue_head_t destroyq;
    mempool_t job_pool;
    struct workqueue_struct * kcopyd_wq;
    struct work_struct kcopyd_work;
    struct dm_kcopyd_throttle * throttle;
    atomic_t nr_jobs;
    spinlock_t job_lock;
    struct list_head callback_jobs;
    struct list_head complete_jobs;
    struct list_head io_jobs;
    struct list_head pages_jobs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dm_kcopyd_client {
    struct page_list * pages;
    unsigned int nr_reserved_pages;
    unsigned int nr_free_pages;
    unsigned int sub_job_size;
    struct dm_io_client * io_client;
    wait_queue_head_t destroyq;
    mempool_t job_pool;
    struct workqueue_struct * kcopyd_wq;
    struct work_struct kcopyd_work;
    struct dm_kcopyd_throttle * throttle;
    atomic_t nr_jobs;
    spinlock_t job_lock;
    struct list_head callback_jobs;
    struct list_head complete_jobs;
    struct list_head io_jobs;
    struct list_head pages_jobs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct dm_kcopyd_client {
    struct page_list * pages;
    unsigned int nr_reserved_pages;
    unsigned int nr_free_pages;
    unsigned int sub_job_size;
    struct dm_io_client * io_client;
    wait_queue_head_t destroyq;
    mempool_t job_pool;
    struct workqueue_struct * kcopyd_wq;
    struct work_struct kcopyd_work;
    struct dm_kcopyd_throttle * throttle;
    atomic_t nr_jobs;
    spinlock_t job_lock;
    struct list_head callback_jobs;
    struct list_head complete_jobs;
    struct list_head io_jobs;
    struct list_head pages_jobs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dm_kcopyd_client {
    struct page_list * pages;
    unsigned int nr_reserved_pages;
    unsigned int nr_free_pages;
    unsigned int sub_job_size;
    struct dm_io_client * io_client;
    wait_queue_head_t destroyq;
    mempool_t job_pool;
    struct workqueue_struct * kcopyd_wq;
    struct work_struct kcopyd_work;
    struct dm_kcopyd_throttle * throttle;
    atomic_t nr_jobs;
    spinlock_t job_lock;
    struct list_head callback_jobs;
    struct list_head complete_jobs;
    struct list_head io_jobs;
    struct list_head pages_jobs;
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
struct dm_kcopyd_client {
    struct page_list * pages;
    unsigned int nr_reserved_pages;
    unsigned int nr_free_pages;
    unsigned int sub_job_size;
    struct dm_io_client * io_client;
    wait_queue_head_t destroyq;
    mempool_t job_pool;
    struct workqueue_struct * kcopyd_wq;
    struct work_struct kcopyd_work;
    struct dm_kcopyd_throttle * throttle;
    atomic_t nr_jobs;
    spinlock_t job_lock;
    struct list_head callback_jobs;
    struct list_head complete_jobs;
    struct list_head io_jobs;
    struct list_head pages_jobs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dm_kcopyd_client {
    struct page_list * pages;
    unsigned int nr_reserved_pages;
    unsigned int nr_free_pages;
    unsigned int sub_job_size;
    struct dm_io_client * io_client;
    wait_queue_head_t destroyq;
    mempool_t job_pool;
    struct workqueue_struct * kcopyd_wq;
    struct work_struct kcopyd_work;
    struct dm_kcopyd_throttle * throttle;
    atomic_t nr_jobs;
    spinlock_t job_lock;
    struct list_head callback_jobs;
    struct list_head complete_jobs;
    struct list_head io_jobs;
    struct list_head pages_jobs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct dm_kcopyd_client {
    struct page_list * pages;
    unsigned int nr_reserved_pages;
    unsigned int nr_free_pages;
    unsigned int sub_job_size;
    struct dm_io_client * io_client;
    wait_queue_head_t destroyq;
    mempool_t job_pool;
    struct workqueue_struct * kcopyd_wq;
    struct work_struct kcopyd_work;
    struct dm_kcopyd_throttle * throttle;
    atomic_t nr_jobs;
    spinlock_t job_lock;
    struct list_head callback_jobs;
    struct list_head complete_jobs;
    struct list_head io_jobs;
    struct list_head pages_jobs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct dm_kcopyd_client {
    struct page_list * pages;
    unsigned int nr_reserved_pages;
    unsigned int nr_free_pages;
    unsigned int sub_job_size;
    struct dm_io_client * io_client;
    wait_queue_head_t destroyq;
    mempool_t job_pool;
    struct workqueue_struct * kcopyd_wq;
    struct work_struct kcopyd_work;
    struct dm_kcopyd_throttle * throttle;
    atomic_t nr_jobs;
    spinlock_t job_lock;
    struct list_head callback_jobs;
    struct list_head complete_jobs;
    struct list_head io_jobs;
    struct list_head pages_jobs;
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
struct dm_kcopyd_client {
    struct page_list * pages;
    unsigned int nr_reserved_pages;
    unsigned int nr_free_pages;
    unsigned int sub_job_size;
    struct dm_io_client * io_client;
    wait_queue_head_t destroyq;
    mempool_t job_pool;
    struct workqueue_struct * kcopyd_wq;
    struct work_struct kcopyd_work;
    struct dm_kcopyd_throttle * throttle;
    atomic_t nr_jobs;
    spinlock_t job_lock;
    struct list_head callback_jobs;
    struct list_head complete_jobs;
    struct list_head io_jobs;
    struct list_head pages_jobs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct dm_kcopyd_client {
    struct page_list * pages;
    unsigned int nr_reserved_pages;
    unsigned int nr_free_pages;
    unsigned int sub_job_size;
    struct dm_io_client * io_client;
    wait_queue_head_t destroyq;
    mempool_t job_pool;
    struct workqueue_struct * kcopyd_wq;
    struct work_struct kcopyd_work;
    struct dm_kcopyd_throttle * throttle;
    atomic_t nr_jobs;
    spinlock_t job_lock;
    struct list_head callback_jobs;
    struct list_head complete_jobs;
    struct list_head io_jobs;
    struct list_head pages_jobs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct dm_kcopyd_client {
    struct page_list * pages;
    unsigned int nr_reserved_pages;
    unsigned int nr_free_pages;
    unsigned int sub_job_size;
    struct dm_io_client * io_client;
    wait_queue_head_t destroyq;
    mempool_t job_pool;
    struct workqueue_struct * kcopyd_wq;
    struct work_struct kcopyd_work;
    struct dm_kcopyd_throttle * throttle;
    atomic_t nr_jobs;
    spinlock_t job_lock;
    struct list_head callback_jobs;
    struct list_head complete_jobs;
    struct list_head io_jobs;
    struct list_head pages_jobs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dm_kcopyd_client {
    struct page_list * pages;
    unsigned int nr_reserved_pages;
    unsigned int nr_free_pages;
    unsigned int sub_job_size;
    struct dm_io_client * io_client;
    wait_queue_head_t destroyq;
    mempool_t job_pool;
    struct workqueue_struct * kcopyd_wq;
    struct work_struct kcopyd_work;
    struct dm_kcopyd_throttle * throttle;
    atomic_t nr_jobs;
    spinlock_t job_lock;
    struct list_head callback_jobs;
    struct list_head complete_jobs;
    struct list_head io_jobs;
    struct list_head pages_jobs;
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
<code>mempool_t * job_pool</code> ➡️ <code>mempool_t job_pool</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct list_head callback_jobs</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int sub_job_size</code>
</li>
</ul>
</details>
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
