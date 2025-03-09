# Struct: <code>bio_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct bio_set {
    struct kmem_cache * bio_slab;
    unsigned int front_pad;
    mempool_t * bio_pool;
    mempool_t * bvec_pool;
    mempool_t * bio_integrity_pool;
    mempool_t * bvec_integrity_pool;
    spinlock_t rescue_lock;
    struct bio_list rescue_list;
    struct work_struct rescue_work;
    struct workqueue_struct * rescue_workqueue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct bio_set {
    struct kmem_cache * bio_slab;
    unsigned int front_pad;
    mempool_t * bio_pool;
    mempool_t * bvec_pool;
    mempool_t * bio_integrity_pool;
    mempool_t * bvec_integrity_pool;
    spinlock_t rescue_lock;
    struct bio_list rescue_list;
    struct work_struct rescue_work;
    struct workqueue_struct * rescue_workqueue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct bio_set {
    struct kmem_cache * bio_slab;
    unsigned int front_pad;
    mempool_t * bio_pool;
    mempool_t * bvec_pool;
    mempool_t * bio_integrity_pool;
    mempool_t * bvec_integrity_pool;
    spinlock_t rescue_lock;
    struct bio_list rescue_list;
    struct work_struct rescue_work;
    struct workqueue_struct * rescue_workqueue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct bio_set {
    struct kmem_cache * bio_slab;
    unsigned int front_pad;
    mempool_t * bio_pool;
    mempool_t * bvec_pool;
    mempool_t * bio_integrity_pool;
    mempool_t * bvec_integrity_pool;
    spinlock_t rescue_lock;
    struct bio_list rescue_list;
    struct work_struct rescue_work;
    struct workqueue_struct * rescue_workqueue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct bio_set {
    struct kmem_cache * bio_slab;
    unsigned int front_pad;
    mempool_t * bio_pool;
    mempool_t * bvec_pool;
    mempool_t * bio_integrity_pool;
    mempool_t * bvec_integrity_pool;
    spinlock_t rescue_lock;
    struct bio_list rescue_list;
    struct work_struct rescue_work;
    struct workqueue_struct * rescue_workqueue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct bio_set {
    struct kmem_cache * bio_slab;
    unsigned int front_pad;
    mempool_t bio_pool;
    mempool_t bvec_pool;
    mempool_t bio_integrity_pool;
    mempool_t bvec_integrity_pool;
    spinlock_t rescue_lock;
    struct bio_list rescue_list;
    struct work_struct rescue_work;
    struct workqueue_struct * rescue_workqueue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct bio_set {
    struct kmem_cache * bio_slab;
    unsigned int front_pad;
    mempool_t bio_pool;
    mempool_t bvec_pool;
    mempool_t bio_integrity_pool;
    mempool_t bvec_integrity_pool;
    spinlock_t rescue_lock;
    struct bio_list rescue_list;
    struct work_struct rescue_work;
    struct workqueue_struct * rescue_workqueue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct bio_set {
    struct kmem_cache * bio_slab;
    unsigned int front_pad;
    mempool_t bio_pool;
    mempool_t bvec_pool;
    mempool_t bio_integrity_pool;
    mempool_t bvec_integrity_pool;
    spinlock_t rescue_lock;
    struct bio_list rescue_list;
    struct work_struct rescue_work;
    struct workqueue_struct * rescue_workqueue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct bio_set {
    struct kmem_cache * bio_slab;
    unsigned int front_pad;
    mempool_t bio_pool;
    mempool_t bvec_pool;
    mempool_t bio_integrity_pool;
    mempool_t bvec_integrity_pool;
    spinlock_t rescue_lock;
    struct bio_list rescue_list;
    struct work_struct rescue_work;
    struct workqueue_struct * rescue_workqueue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct bio_set {
    struct kmem_cache * bio_slab;
    unsigned int front_pad;
    mempool_t bio_pool;
    mempool_t bvec_pool;
    mempool_t bio_integrity_pool;
    mempool_t bvec_integrity_pool;
    spinlock_t rescue_lock;
    struct bio_list rescue_list;
    struct work_struct rescue_work;
    struct workqueue_struct * rescue_workqueue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct bio_set {
    struct kmem_cache * bio_slab;
    unsigned int front_pad;
    mempool_t bio_pool;
    mempool_t bvec_pool;
    mempool_t bio_integrity_pool;
    mempool_t bvec_integrity_pool;
    spinlock_t rescue_lock;
    struct bio_list rescue_list;
    struct work_struct rescue_work;
    struct workqueue_struct * rescue_workqueue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct bio_set {
    struct kmem_cache * bio_slab;
    unsigned int front_pad;
    mempool_t bio_pool;
    mempool_t bvec_pool;
    mempool_t bio_integrity_pool;
    mempool_t bvec_integrity_pool;
    unsigned int back_pad;
    spinlock_t rescue_lock;
    struct bio_list rescue_list;
    struct work_struct rescue_work;
    struct workqueue_struct * rescue_workqueue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct bio_set {
    struct kmem_cache * bio_slab;
    unsigned int front_pad;
    struct bio_alloc_cache * cache;
    mempool_t bio_pool;
    mempool_t bvec_pool;
    mempool_t bio_integrity_pool;
    mempool_t bvec_integrity_pool;
    unsigned int back_pad;
    spinlock_t rescue_lock;
    struct bio_list rescue_list;
    struct work_struct rescue_work;
    struct workqueue_struct * rescue_workqueue;
    struct hlist_node cpuhp_dead;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct bio_set {
    struct kmem_cache * bio_slab;
    unsigned int front_pad;
    struct bio_alloc_cache * cache;
    mempool_t bio_pool;
    mempool_t bvec_pool;
    mempool_t bio_integrity_pool;
    mempool_t bvec_integrity_pool;
    unsigned int back_pad;
    spinlock_t rescue_lock;
    struct bio_list rescue_list;
    struct work_struct rescue_work;
    struct workqueue_struct * rescue_workqueue;
    struct hlist_node cpuhp_dead;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct bio_set {
    struct kmem_cache * bio_slab;
    unsigned int front_pad;
    struct bio_alloc_cache * cache;
    mempool_t bio_pool;
    mempool_t bvec_pool;
    mempool_t bio_integrity_pool;
    mempool_t bvec_integrity_pool;
    unsigned int back_pad;
    spinlock_t rescue_lock;
    struct bio_list rescue_list;
    struct work_struct rescue_work;
    struct workqueue_struct * rescue_workqueue;
    struct hlist_node cpuhp_dead;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct bio_set {
    struct kmem_cache * bio_slab;
    unsigned int front_pad;
    struct bio_alloc_cache * cache;
    mempool_t bio_pool;
    mempool_t bvec_pool;
    mempool_t bio_integrity_pool;
    mempool_t bvec_integrity_pool;
    unsigned int back_pad;
    spinlock_t rescue_lock;
    struct bio_list rescue_list;
    struct work_struct rescue_work;
    struct workqueue_struct * rescue_workqueue;
    struct hlist_node cpuhp_dead;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct bio_set {
    struct kmem_cache * bio_slab;
    unsigned int front_pad;
    struct bio_alloc_cache * cache;
    mempool_t bio_pool;
    mempool_t bvec_pool;
    mempool_t bio_integrity_pool;
    mempool_t bvec_integrity_pool;
    unsigned int back_pad;
    spinlock_t rescue_lock;
    struct bio_list rescue_list;
    struct work_struct rescue_work;
    struct workqueue_struct * rescue_workqueue;
    struct hlist_node cpuhp_dead;
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
struct bio_set {
    struct kmem_cache * bio_slab;
    unsigned int front_pad;
    mempool_t bio_pool;
    mempool_t bvec_pool;
    mempool_t bio_integrity_pool;
    mempool_t bvec_integrity_pool;
    spinlock_t rescue_lock;
    struct bio_list rescue_list;
    struct work_struct rescue_work;
    struct workqueue_struct * rescue_workqueue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct bio_set {
    struct kmem_cache * bio_slab;
    unsigned int front_pad;
    mempool_t bio_pool;
    mempool_t bvec_pool;
    mempool_t bio_integrity_pool;
    mempool_t bvec_integrity_pool;
    spinlock_t rescue_lock;
    struct bio_list rescue_list;
    struct work_struct rescue_work;
    struct workqueue_struct * rescue_workqueue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct bio_set {
    struct kmem_cache * bio_slab;
    unsigned int front_pad;
    mempool_t bio_pool;
    mempool_t bvec_pool;
    mempool_t bio_integrity_pool;
    mempool_t bvec_integrity_pool;
    spinlock_t rescue_lock;
    struct bio_list rescue_list;
    struct work_struct rescue_work;
    struct workqueue_struct * rescue_workqueue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct bio_set {
    struct kmem_cache * bio_slab;
    unsigned int front_pad;
    mempool_t bio_pool;
    mempool_t bvec_pool;
    mempool_t bio_integrity_pool;
    mempool_t bvec_integrity_pool;
    spinlock_t rescue_lock;
    struct bio_list rescue_list;
    struct work_struct rescue_work;
    struct workqueue_struct * rescue_workqueue;
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
struct bio_set {
    struct kmem_cache * bio_slab;
    unsigned int front_pad;
    mempool_t bio_pool;
    mempool_t bvec_pool;
    mempool_t bio_integrity_pool;
    mempool_t bvec_integrity_pool;
    spinlock_t rescue_lock;
    struct bio_list rescue_list;
    struct work_struct rescue_work;
    struct workqueue_struct * rescue_workqueue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct bio_set {
    struct kmem_cache * bio_slab;
    unsigned int front_pad;
    mempool_t bio_pool;
    mempool_t bvec_pool;
    mempool_t bio_integrity_pool;
    mempool_t bvec_integrity_pool;
    spinlock_t rescue_lock;
    struct bio_list rescue_list;
    struct work_struct rescue_work;
    struct workqueue_struct * rescue_workqueue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct bio_set {
    struct kmem_cache * bio_slab;
    unsigned int front_pad;
    mempool_t bio_pool;
    mempool_t bvec_pool;
    mempool_t bio_integrity_pool;
    mempool_t bvec_integrity_pool;
    spinlock_t rescue_lock;
    struct bio_list rescue_list;
    struct work_struct rescue_work;
    struct workqueue_struct * rescue_workqueue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct bio_set {
    struct kmem_cache * bio_slab;
    unsigned int front_pad;
    mempool_t bio_pool;
    mempool_t bvec_pool;
    mempool_t bio_integrity_pool;
    mempool_t bvec_integrity_pool;
    spinlock_t rescue_lock;
    struct bio_list rescue_list;
    struct work_struct rescue_work;
    struct workqueue_struct * rescue_workqueue;
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
<code>mempool_t * bio_pool</code> ➡️ <code>mempool_t bio_pool</code>
</li>
<li>
<b>Field type changed. </b>
<code>mempool_t * bvec_pool</code> ➡️ <code>mempool_t bvec_pool</code>
</li>
<li>
<b>Field type changed. </b>
<code>mempool_t * bio_integrity_pool</code> ➡️ <code>mempool_t bio_integrity_pool</code>
</li>
<li>
<b>Field type changed. </b>
<code>mempool_t * bvec_integrity_pool</code> ➡️ <code>mempool_t bvec_integrity_pool</code>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int back_pad</code>
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
<code>struct bio_alloc_cache * cache</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_node cpuhp_dead</code>
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
