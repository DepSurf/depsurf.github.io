# Struct: <code>iova_domain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct iova_domain {
    spinlock_t iova_rbtree_lock;
    struct rb_root rbroot;
    struct rb_node * cached32_node;
    long unsigned int granule;
    long unsigned int start_pfn;
    long unsigned int dma_32bit_pfn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct iova_domain {
    spinlock_t iova_rbtree_lock;
    struct rb_root rbroot;
    struct rb_node * cached32_node;
    long unsigned int granule;
    long unsigned int start_pfn;
    long unsigned int dma_32bit_pfn;
    struct iova_rcache[6] rcaches;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct iova_domain {
    spinlock_t iova_rbtree_lock;
    struct rb_root rbroot;
    struct rb_node * cached32_node;
    long unsigned int granule;
    long unsigned int start_pfn;
    long unsigned int dma_32bit_pfn;
    struct iova_rcache[6] rcaches;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct iova_domain {
    spinlock_t iova_rbtree_lock;
    struct rb_root rbroot;
    struct rb_node * cached32_node;
    long unsigned int granule;
    long unsigned int start_pfn;
    long unsigned int dma_32bit_pfn;
    struct iova_rcache[6] rcaches;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct iova_domain {
    spinlock_t iova_rbtree_lock;
    struct rb_root rbroot;
    struct rb_node * cached_node;
    struct rb_node * cached32_node;
    long unsigned int granule;
    long unsigned int start_pfn;
    long unsigned int dma_32bit_pfn;
    struct iova anchor;
    struct iova_rcache[6] rcaches;
    iova_flush_cb flush_cb;
    iova_entry_dtor entry_dtor;
    struct iova_fq * fq;
    atomic64_t fq_flush_start_cnt;
    atomic64_t fq_flush_finish_cnt;
    struct timer_list fq_timer;
    atomic_t fq_timer_on;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct iova_domain {
    spinlock_t iova_rbtree_lock;
    struct rb_root rbroot;
    struct rb_node * cached_node;
    struct rb_node * cached32_node;
    long unsigned int granule;
    long unsigned int start_pfn;
    long unsigned int dma_32bit_pfn;
    struct iova anchor;
    struct iova_rcache[6] rcaches;
    iova_flush_cb flush_cb;
    iova_entry_dtor entry_dtor;
    struct iova_fq * fq;
    atomic64_t fq_flush_start_cnt;
    atomic64_t fq_flush_finish_cnt;
    struct timer_list fq_timer;
    atomic_t fq_timer_on;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct iova_domain {
    spinlock_t iova_rbtree_lock;
    struct rb_root rbroot;
    struct rb_node * cached_node;
    struct rb_node * cached32_node;
    long unsigned int granule;
    long unsigned int start_pfn;
    long unsigned int dma_32bit_pfn;
    long unsigned int max32_alloc_size;
    struct iova anchor;
    struct iova_rcache[6] rcaches;
    iova_flush_cb flush_cb;
    iova_entry_dtor entry_dtor;
    struct iova_fq * fq;
    atomic64_t fq_flush_start_cnt;
    atomic64_t fq_flush_finish_cnt;
    struct timer_list fq_timer;
    atomic_t fq_timer_on;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct iova_domain {
    spinlock_t iova_rbtree_lock;
    struct rb_root rbroot;
    struct rb_node * cached_node;
    struct rb_node * cached32_node;
    long unsigned int granule;
    long unsigned int start_pfn;
    long unsigned int dma_32bit_pfn;
    long unsigned int max32_alloc_size;
    struct iova_fq * fq;
    atomic64_t fq_flush_start_cnt;
    atomic64_t fq_flush_finish_cnt;
    struct iova anchor;
    struct iova_rcache[6] rcaches;
    iova_flush_cb flush_cb;
    iova_entry_dtor entry_dtor;
    struct timer_list fq_timer;
    atomic_t fq_timer_on;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct iova_domain {
    spinlock_t iova_rbtree_lock;
    struct rb_root rbroot;
    struct rb_node * cached_node;
    struct rb_node * cached32_node;
    long unsigned int granule;
    long unsigned int start_pfn;
    long unsigned int dma_32bit_pfn;
    long unsigned int max32_alloc_size;
    struct iova_fq * fq;
    atomic64_t fq_flush_start_cnt;
    atomic64_t fq_flush_finish_cnt;
    struct iova anchor;
    struct iova_rcache[6] rcaches;
    iova_flush_cb flush_cb;
    iova_entry_dtor entry_dtor;
    struct timer_list fq_timer;
    atomic_t fq_timer_on;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct iova_domain {
    spinlock_t iova_rbtree_lock;
    struct rb_root rbroot;
    struct rb_node * cached_node;
    struct rb_node * cached32_node;
    long unsigned int granule;
    long unsigned int start_pfn;
    long unsigned int dma_32bit_pfn;
    long unsigned int max32_alloc_size;
    struct iova_fq * fq;
    atomic64_t fq_flush_start_cnt;
    atomic64_t fq_flush_finish_cnt;
    struct iova anchor;
    struct iova_rcache[6] rcaches;
    iova_flush_cb flush_cb;
    iova_entry_dtor entry_dtor;
    struct timer_list fq_timer;
    atomic_t fq_timer_on;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct iova_domain {
    spinlock_t iova_rbtree_lock;
    struct rb_root rbroot;
    struct rb_node * cached_node;
    struct rb_node * cached32_node;
    long unsigned int granule;
    long unsigned int start_pfn;
    long unsigned int dma_32bit_pfn;
    long unsigned int max32_alloc_size;
    struct iova_fq * fq;
    atomic64_t fq_flush_start_cnt;
    atomic64_t fq_flush_finish_cnt;
    struct iova anchor;
    struct iova_rcache[6] rcaches;
    iova_flush_cb flush_cb;
    iova_entry_dtor entry_dtor;
    struct timer_list fq_timer;
    atomic_t fq_timer_on;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct iova_domain {
    spinlock_t iova_rbtree_lock;
    struct rb_root rbroot;
    struct rb_node * cached_node;
    struct rb_node * cached32_node;
    long unsigned int granule;
    long unsigned int start_pfn;
    long unsigned int dma_32bit_pfn;
    long unsigned int max32_alloc_size;
    struct iova_fq * fq;
    atomic64_t fq_flush_start_cnt;
    atomic64_t fq_flush_finish_cnt;
    struct iova anchor;
    struct iova_rcache[6] rcaches;
    iova_flush_cb flush_cb;
    iova_entry_dtor entry_dtor;
    struct timer_list fq_timer;
    atomic_t fq_timer_on;
    struct hlist_node cpuhp_dead;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct iova_domain {
    spinlock_t iova_rbtree_lock;
    struct rb_root rbroot;
    struct rb_node * cached_node;
    struct rb_node * cached32_node;
    long unsigned int granule;
    long unsigned int start_pfn;
    long unsigned int dma_32bit_pfn;
    long unsigned int max32_alloc_size;
    struct iova_fq * fq;
    atomic64_t fq_flush_start_cnt;
    atomic64_t fq_flush_finish_cnt;
    struct iova anchor;
    struct iova_rcache[6] rcaches;
    iova_flush_cb flush_cb;
    iova_entry_dtor entry_dtor;
    struct timer_list fq_timer;
    atomic_t fq_timer_on;
    struct hlist_node cpuhp_dead;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct iova_domain {
    spinlock_t iova_rbtree_lock;
    struct rb_root rbroot;
    struct rb_node * cached_node;
    struct rb_node * cached32_node;
    long unsigned int granule;
    long unsigned int start_pfn;
    long unsigned int dma_32bit_pfn;
    long unsigned int max32_alloc_size;
    struct iova anchor;
    struct iova_rcache * rcaches;
    struct hlist_node cpuhp_dead;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct iova_domain {
    spinlock_t iova_rbtree_lock;
    struct rb_root rbroot;
    struct rb_node * cached_node;
    struct rb_node * cached32_node;
    long unsigned int granule;
    long unsigned int start_pfn;
    long unsigned int dma_32bit_pfn;
    long unsigned int max32_alloc_size;
    struct iova anchor;
    struct iova_rcache * rcaches;
    struct hlist_node cpuhp_dead;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct iova_domain {
    spinlock_t iova_rbtree_lock;
    struct rb_root rbroot;
    struct rb_node * cached_node;
    struct rb_node * cached32_node;
    long unsigned int granule;
    long unsigned int start_pfn;
    long unsigned int dma_32bit_pfn;
    long unsigned int max32_alloc_size;
    struct iova anchor;
    struct iova_rcache * rcaches;
    struct hlist_node cpuhp_dead;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct iova_domain {
    spinlock_t iova_rbtree_lock;
    struct rb_root rbroot;
    struct rb_node * cached_node;
    struct rb_node * cached32_node;
    long unsigned int granule;
    long unsigned int start_pfn;
    long unsigned int dma_32bit_pfn;
    long unsigned int max32_alloc_size;
    struct iova anchor;
    struct iova_rcache * rcaches;
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
struct iova_domain {
    spinlock_t iova_rbtree_lock;
    struct rb_root rbroot;
    struct rb_node * cached_node;
    struct rb_node * cached32_node;
    long unsigned int granule;
    long unsigned int start_pfn;
    long unsigned int dma_32bit_pfn;
    long unsigned int max32_alloc_size;
    struct iova_fq * fq;
    atomic64_t fq_flush_start_cnt;
    atomic64_t fq_flush_finish_cnt;
    struct iova anchor;
    struct iova_rcache[6] rcaches;
    iova_flush_cb flush_cb;
    iova_entry_dtor entry_dtor;
    struct timer_list fq_timer;
    atomic_t fq_timer_on;
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct iova_domain {
    spinlock_t iova_rbtree_lock;
    struct rb_root rbroot;
    struct rb_node * cached_node;
    struct rb_node * cached32_node;
    long unsigned int granule;
    long unsigned int start_pfn;
    long unsigned int dma_32bit_pfn;
    long unsigned int max32_alloc_size;
    struct iova_fq * fq;
    atomic64_t fq_flush_start_cnt;
    atomic64_t fq_flush_finish_cnt;
    struct iova anchor;
    struct iova_rcache[6] rcaches;
    iova_flush_cb flush_cb;
    iova_entry_dtor entry_dtor;
    struct timer_list fq_timer;
    atomic_t fq_timer_on;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct iova_domain {
    spinlock_t iova_rbtree_lock;
    struct rb_root rbroot;
    struct rb_node * cached_node;
    struct rb_node * cached32_node;
    long unsigned int granule;
    long unsigned int start_pfn;
    long unsigned int dma_32bit_pfn;
    long unsigned int max32_alloc_size;
    struct iova_fq * fq;
    atomic64_t fq_flush_start_cnt;
    atomic64_t fq_flush_finish_cnt;
    struct iova anchor;
    struct iova_rcache[6] rcaches;
    iova_flush_cb flush_cb;
    iova_entry_dtor entry_dtor;
    struct timer_list fq_timer;
    atomic_t fq_timer_on;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct iova_domain {
    spinlock_t iova_rbtree_lock;
    struct rb_root rbroot;
    struct rb_node * cached_node;
    struct rb_node * cached32_node;
    long unsigned int granule;
    long unsigned int start_pfn;
    long unsigned int dma_32bit_pfn;
    long unsigned int max32_alloc_size;
    struct iova_fq * fq;
    atomic64_t fq_flush_start_cnt;
    atomic64_t fq_flush_finish_cnt;
    struct iova anchor;
    struct iova_rcache[6] rcaches;
    iova_flush_cb flush_cb;
    iova_entry_dtor entry_dtor;
    struct timer_list fq_timer;
    atomic_t fq_timer_on;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct iova_domain {
    spinlock_t iova_rbtree_lock;
    struct rb_root rbroot;
    struct rb_node * cached_node;
    struct rb_node * cached32_node;
    long unsigned int granule;
    long unsigned int start_pfn;
    long unsigned int dma_32bit_pfn;
    long unsigned int max32_alloc_size;
    struct iova_fq * fq;
    atomic64_t fq_flush_start_cnt;
    atomic64_t fq_flush_finish_cnt;
    struct iova anchor;
    struct iova_rcache[6] rcaches;
    iova_flush_cb flush_cb;
    iova_entry_dtor entry_dtor;
    struct timer_list fq_timer;
    atomic_t fq_timer_on;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct iova_rcache[6] rcaches</code>
</li>
</ul>
</details>
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
<code>struct rb_node * cached_node</code>
</li>
<li>
<b>Field added. </b>
<code>struct iova anchor</code>
</li>
<li>
<b>Field added. </b>
<code>iova_flush_cb flush_cb</code>
</li>
<li>
<b>Field added. </b>
<code>iova_entry_dtor entry_dtor</code>
</li>
<li>
<b>Field added. </b>
<code>struct iova_fq * fq</code>
</li>
<li>
<b>Field added. </b>
<code>atomic64_t fq_flush_start_cnt</code>
</li>
<li>
<b>Field added. </b>
<code>atomic64_t fq_flush_finish_cnt</code>
</li>
<li>
<b>Field added. </b>
<code>struct timer_list fq_timer</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t fq_timer_on</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int max32_alloc_size</code>
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
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct hlist_node cpuhp_dead</code>
</li>
</ul>
</details>
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
<code>struct iova_fq * fq</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic64_t fq_flush_start_cnt</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic64_t fq_flush_finish_cnt</code>
</li>
<li>
<b>Field removed. </b>
<code>iova_flush_cb flush_cb</code>
</li>
<li>
<b>Field removed. </b>
<code>iova_entry_dtor entry_dtor</code>
</li>
<li>
<b>Field removed. </b>
<code>struct timer_list fq_timer</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t fq_timer_on</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct iova_rcache[6] rcaches</code> ➡️ <code>struct iova_rcache * rcaches</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct iova_domain {
    spinlock_t iova_rbtree_lock;
    struct rb_root rbroot;
    struct rb_node * cached_node;
    struct rb_node * cached32_node;
    long unsigned int granule;
    long unsigned int start_pfn;
    long unsigned int dma_32bit_pfn;
    long unsigned int max32_alloc_size;
    struct iova_fq * fq;
    atomic64_t fq_flush_start_cnt;
    atomic64_t fq_flush_finish_cnt;
    struct iova anchor;
    struct iova_rcache[6] rcaches;
    iova_flush_cb flush_cb;
    iova_entry_dtor entry_dtor;
    struct timer_list fq_timer;
    atomic_t fq_timer_on;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct iova_domain {
    spinlock_t iova_rbtree_lock;
    struct rb_root rbroot;
    struct rb_node * cached_node;
    struct rb_node * cached32_node;
    long unsigned int granule;
    long unsigned int start_pfn;
    long unsigned int dma_32bit_pfn;
    long unsigned int max32_alloc_size;
    struct iova_fq * fq;
    atomic64_t fq_flush_start_cnt;
    atomic64_t fq_flush_finish_cnt;
    struct iova anchor;
    struct iova_rcache[6] rcaches;
    iova_flush_cb flush_cb;
    iova_entry_dtor entry_dtor;
    struct timer_list fq_timer;
    atomic_t fq_timer_on;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct iova_domain {
    spinlock_t iova_rbtree_lock;
    struct rb_root rbroot;
    struct rb_node * cached_node;
    struct rb_node * cached32_node;
    long unsigned int granule;
    long unsigned int start_pfn;
    long unsigned int dma_32bit_pfn;
    long unsigned int max32_alloc_size;
    struct iova_fq * fq;
    atomic64_t fq_flush_start_cnt;
    atomic64_t fq_flush_finish_cnt;
    struct iova anchor;
    struct iova_rcache[6] rcaches;
    iova_flush_cb flush_cb;
    iova_entry_dtor entry_dtor;
    struct timer_list fq_timer;
    atomic_t fq_timer_on;
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
