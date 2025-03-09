# Struct: <code>deadline_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct deadline_data {
    struct rb_root[2] sort_list;
    struct list_head[2] fifo_list;
    struct request *[2] next_rq;
    unsigned int batching;
    sector_t last_sector;
    unsigned int starved;
    int[2] fifo_expire;
    int fifo_batch;
    int writes_starved;
    int front_merges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct deadline_data {
    struct rb_root[2] sort_list;
    struct list_head[2] fifo_list;
    struct request *[2] next_rq;
    unsigned int batching;
    unsigned int starved;
    int[2] fifo_expire;
    int fifo_batch;
    int writes_starved;
    int front_merges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct deadline_data {
    struct rb_root[2] sort_list;
    struct list_head[2] fifo_list;
    struct request *[2] next_rq;
    unsigned int batching;
    unsigned int starved;
    int[2] fifo_expire;
    int fifo_batch;
    int writes_starved;
    int front_merges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct deadline_data {
    struct rb_root[2] sort_list;
    struct list_head[2] fifo_list;
    struct request *[2] next_rq;
    unsigned int batching;
    unsigned int starved;
    int[2] fifo_expire;
    int fifo_batch;
    int writes_starved;
    int front_merges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct deadline_data {
    struct rb_root[2] sort_list;
    struct list_head[2] fifo_list;
    struct request *[2] next_rq;
    unsigned int batching;
    unsigned int starved;
    int[2] fifo_expire;
    int fifo_batch;
    int writes_starved;
    int front_merges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct deadline_data {
    struct rb_root[2] sort_list;
    struct list_head[2] fifo_list;
    struct request *[2] next_rq;
    unsigned int batching;
    unsigned int starved;
    int[2] fifo_expire;
    int fifo_batch;
    int writes_starved;
    int front_merges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct deadline_data {
    struct rb_root[2] sort_list;
    struct list_head[2] fifo_list;
    struct request *[2] next_rq;
    unsigned int batching;
    unsigned int starved;
    int[2] fifo_expire;
    int fifo_batch;
    int writes_starved;
    int front_merges;
    spinlock_t lock;
    spinlock_t zone_lock;
    struct list_head dispatch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct deadline_data {
    struct rb_root[2] sort_list;
    struct list_head[2] fifo_list;
    struct request *[2] next_rq;
    unsigned int batching;
    unsigned int starved;
    int[2] fifo_expire;
    int fifo_batch;
    int writes_starved;
    int front_merges;
    spinlock_t lock;
    spinlock_t zone_lock;
    struct list_head dispatch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct deadline_data {
    struct rb_root[2] sort_list;
    struct list_head[2] fifo_list;
    struct request *[2] next_rq;
    unsigned int batching;
    unsigned int starved;
    int[2] fifo_expire;
    int fifo_batch;
    int writes_starved;
    int front_merges;
    spinlock_t lock;
    spinlock_t zone_lock;
    struct list_head dispatch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct deadline_data {
    struct rb_root[2] sort_list;
    struct list_head[2] fifo_list;
    struct request *[2] next_rq;
    unsigned int batching;
    unsigned int starved;
    int[2] fifo_expire;
    int fifo_batch;
    int writes_starved;
    int front_merges;
    spinlock_t lock;
    spinlock_t zone_lock;
    struct list_head dispatch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct deadline_data {
    struct rb_root[2] sort_list;
    struct list_head[2] fifo_list;
    struct request *[2] next_rq;
    unsigned int batching;
    unsigned int starved;
    int[2] fifo_expire;
    int fifo_batch;
    int writes_starved;
    int front_merges;
    spinlock_t lock;
    spinlock_t zone_lock;
    struct list_head dispatch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct deadline_data {
    struct rb_root[2] sort_list;
    struct list_head[2] fifo_list;
    struct request *[2] next_rq;
    unsigned int batching;
    unsigned int starved;
    int[2] fifo_expire;
    int fifo_batch;
    int writes_starved;
    int front_merges;
    spinlock_t lock;
    spinlock_t zone_lock;
    struct list_head dispatch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct deadline_data {
    struct dd_per_prio[3] per_prio;
    enum dd_data_dir last_dir;
    unsigned int batching;
    unsigned int starved;
    struct io_stats * stats;
    int[2] fifo_expire;
    int fifo_batch;
    int writes_starved;
    int front_merges;
    u32 async_depth;
    spinlock_t lock;
    spinlock_t zone_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct deadline_data {
    struct dd_per_prio[3] per_prio;
    enum dd_data_dir last_dir;
    unsigned int batching;
    unsigned int starved;
    int[2] fifo_expire;
    int fifo_batch;
    int writes_starved;
    int front_merges;
    u32 async_depth;
    int prio_aging_expire;
    spinlock_t lock;
    spinlock_t zone_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct deadline_data {
    struct dd_per_prio[3] per_prio;
    enum dd_data_dir last_dir;
    unsigned int batching;
    unsigned int starved;
    int[2] fifo_expire;
    int fifo_batch;
    int writes_starved;
    int front_merges;
    u32 async_depth;
    int prio_aging_expire;
    spinlock_t lock;
    spinlock_t zone_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct deadline_data {
    struct dd_per_prio[3] per_prio;
    enum dd_data_dir last_dir;
    unsigned int batching;
    unsigned int starved;
    int[2] fifo_expire;
    int fifo_batch;
    int writes_starved;
    int front_merges;
    u32 async_depth;
    int prio_aging_expire;
    spinlock_t lock;
    spinlock_t zone_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct deadline_data {
    struct dd_per_prio[3] per_prio;
    enum dd_data_dir last_dir;
    unsigned int batching;
    unsigned int starved;
    int[2] fifo_expire;
    int fifo_batch;
    int writes_starved;
    int front_merges;
    u32 async_depth;
    int prio_aging_expire;
    spinlock_t lock;
    spinlock_t zone_lock;
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
struct deadline_data {
    struct rb_root[2] sort_list;
    struct list_head[2] fifo_list;
    struct request *[2] next_rq;
    unsigned int batching;
    unsigned int starved;
    int[2] fifo_expire;
    int fifo_batch;
    int writes_starved;
    int front_merges;
    spinlock_t lock;
    spinlock_t zone_lock;
    struct list_head dispatch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct deadline_data {
    struct rb_root[2] sort_list;
    struct list_head[2] fifo_list;
    struct request *[2] next_rq;
    unsigned int batching;
    unsigned int starved;
    int[2] fifo_expire;
    int fifo_batch;
    int writes_starved;
    int front_merges;
    spinlock_t lock;
    spinlock_t zone_lock;
    struct list_head dispatch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct deadline_data {
    struct rb_root[2] sort_list;
    struct list_head[2] fifo_list;
    struct request *[2] next_rq;
    unsigned int batching;
    unsigned int starved;
    int[2] fifo_expire;
    int fifo_batch;
    int writes_starved;
    int front_merges;
    spinlock_t lock;
    spinlock_t zone_lock;
    struct list_head dispatch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct deadline_data {
    struct rb_root[2] sort_list;
    struct list_head[2] fifo_list;
    struct request *[2] next_rq;
    unsigned int batching;
    unsigned int starved;
    int[2] fifo_expire;
    int fifo_batch;
    int writes_starved;
    int front_merges;
    spinlock_t lock;
    spinlock_t zone_lock;
    struct list_head dispatch;
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
struct deadline_data {
    struct rb_root[2] sort_list;
    struct list_head[2] fifo_list;
    struct request *[2] next_rq;
    unsigned int batching;
    unsigned int starved;
    int[2] fifo_expire;
    int fifo_batch;
    int writes_starved;
    int front_merges;
    spinlock_t lock;
    spinlock_t zone_lock;
    struct list_head dispatch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct deadline_data {
    struct rb_root[2] sort_list;
    struct list_head[2] fifo_list;
    struct request *[2] next_rq;
    unsigned int batching;
    unsigned int starved;
    int[2] fifo_expire;
    int fifo_batch;
    int writes_starved;
    int front_merges;
    spinlock_t lock;
    spinlock_t zone_lock;
    struct list_head dispatch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct deadline_data {
    struct rb_root[2] sort_list;
    struct list_head[2] fifo_list;
    struct request *[2] next_rq;
    unsigned int batching;
    unsigned int starved;
    int[2] fifo_expire;
    int fifo_batch;
    int writes_starved;
    int front_merges;
    spinlock_t lock;
    spinlock_t zone_lock;
    struct list_head dispatch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct deadline_data {
    struct rb_root[2] sort_list;
    struct list_head[2] fifo_list;
    struct request *[2] next_rq;
    unsigned int batching;
    unsigned int starved;
    int[2] fifo_expire;
    int fifo_batch;
    int writes_starved;
    int front_merges;
    spinlock_t lock;
    spinlock_t zone_lock;
    struct list_head dispatch;
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
<b>Field removed. </b>
<code>sector_t last_sector</code>
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
<b>Field added. </b>
<code>spinlock_t lock</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t zone_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head dispatch</code>
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
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct dd_per_prio[3] per_prio</code>
</li>
<li>
<b>Field added. </b>
<code>enum dd_data_dir last_dir</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_stats * stats</code>
</li>
<li>
<b>Field added. </b>
<code>u32 async_depth</code>
</li>
<li>
<b>Field removed. </b>
<code>struct rb_root[2] sort_list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head[2] fifo_list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct request *[2] next_rq</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head dispatch</code>
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
<code>int prio_aging_expire</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_stats * stats</code>
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
