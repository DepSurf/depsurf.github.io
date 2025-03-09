# Struct: <code>blk_mq_ctx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_ctx {
    spinlock_t lock;
    struct list_head rq_list;
    unsigned int cpu;
    unsigned int index_hw;
    unsigned int last_tag;
    long unsigned int[2] rq_dispatched;
    long unsigned int rq_merged;
    long unsigned int[2] rq_completed;
    struct request_queue * queue;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_ctx {
    spinlock_t lock;
    struct list_head rq_list;
    unsigned int cpu;
    unsigned int index_hw;
    unsigned int last_tag;
    long unsigned int[2] rq_dispatched;
    long unsigned int rq_merged;
    long unsigned int[2] rq_completed;
    struct request_queue * queue;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_ctx {
    spinlock_t lock;
    struct list_head rq_list;
    unsigned int cpu;
    unsigned int index_hw;
    long unsigned int[2] rq_dispatched;
    long unsigned int rq_merged;
    long unsigned int[2] rq_completed;
    struct blk_rq_stat[2] stat;
    struct request_queue * queue;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_ctx {
    spinlock_t lock;
    struct list_head rq_list;
    unsigned int cpu;
    unsigned int index_hw;
    long unsigned int[2] rq_dispatched;
    long unsigned int rq_merged;
    long unsigned int[2] rq_completed;
    struct request_queue * queue;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_ctx {
    spinlock_t lock;
    struct list_head rq_list;
    unsigned int cpu;
    unsigned int index_hw;
    long unsigned int[2] rq_dispatched;
    long unsigned int rq_merged;
    long unsigned int[2] rq_completed;
    struct request_queue * queue;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_ctx {
    spinlock_t lock;
    struct list_head rq_list;
    unsigned int cpu;
    unsigned int index_hw;
    long unsigned int[2] rq_dispatched;
    long unsigned int rq_merged;
    long unsigned int[2] rq_completed;
    struct request_queue * queue;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_ctx {
    spinlock_t lock;
    struct list_head[3] rq_lists;
    unsigned int cpu;
    short unsigned int[3] index_hw;
    long unsigned int[2] rq_dispatched;
    long unsigned int rq_merged;
    long unsigned int[2] rq_completed;
    struct request_queue * queue;
    struct blk_mq_ctxs * ctxs;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_ctx {
    spinlock_t lock;
    struct list_head[3] rq_lists;
    unsigned int cpu;
    short unsigned int[3] index_hw;
    struct blk_mq_hw_ctx *[3] hctxs;
    long unsigned int[2] rq_dispatched;
    long unsigned int rq_merged;
    long unsigned int[2] rq_completed;
    struct request_queue * queue;
    struct blk_mq_ctxs * ctxs;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_ctx {
    spinlock_t lock;
    struct list_head[3] rq_lists;
    unsigned int cpu;
    short unsigned int[3] index_hw;
    struct blk_mq_hw_ctx *[3] hctxs;
    long unsigned int[2] rq_dispatched;
    long unsigned int rq_merged;
    long unsigned int[2] rq_completed;
    struct request_queue * queue;
    struct blk_mq_ctxs * ctxs;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_ctx {
    spinlock_t lock;
    struct list_head[3] rq_lists;
    unsigned int cpu;
    short unsigned int[3] index_hw;
    struct blk_mq_hw_ctx *[3] hctxs;
    long unsigned int[2] rq_dispatched;
    long unsigned int rq_merged;
    long unsigned int[2] rq_completed;
    struct request_queue * queue;
    struct blk_mq_ctxs * ctxs;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_ctx {
    spinlock_t lock;
    struct list_head[3] rq_lists;
    unsigned int cpu;
    short unsigned int[3] index_hw;
    struct blk_mq_hw_ctx *[3] hctxs;
    long unsigned int[2] rq_dispatched;
    long unsigned int rq_merged;
    long unsigned int[2] rq_completed;
    struct request_queue * queue;
    struct blk_mq_ctxs * ctxs;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_ctx {
    spinlock_t lock;
    struct list_head[3] rq_lists;
    unsigned int cpu;
    short unsigned int[3] index_hw;
    struct blk_mq_hw_ctx *[3] hctxs;
    long unsigned int[2] rq_dispatched;
    long unsigned int rq_merged;
    long unsigned int[2] rq_completed;
    struct request_queue * queue;
    struct blk_mq_ctxs * ctxs;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_ctx {
    spinlock_t lock;
    struct list_head[3] rq_lists;
    unsigned int cpu;
    short unsigned int[3] index_hw;
    struct blk_mq_hw_ctx *[3] hctxs;
    long unsigned int[2] rq_dispatched;
    long unsigned int rq_merged;
    long unsigned int[2] rq_completed;
    struct request_queue * queue;
    struct blk_mq_ctxs * ctxs;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_ctx {
    spinlock_t lock;
    struct list_head[3] rq_lists;
    unsigned int cpu;
    short unsigned int[3] index_hw;
    struct blk_mq_hw_ctx *[3] hctxs;
    struct request_queue * queue;
    struct blk_mq_ctxs * ctxs;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_ctx {
    spinlock_t lock;
    struct list_head[3] rq_lists;
    unsigned int cpu;
    short unsigned int[3] index_hw;
    struct blk_mq_hw_ctx *[3] hctxs;
    struct request_queue * queue;
    struct blk_mq_ctxs * ctxs;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_ctx {
    spinlock_t lock;
    struct list_head[3] rq_lists;
    unsigned int cpu;
    short unsigned int[3] index_hw;
    struct blk_mq_hw_ctx *[3] hctxs;
    struct request_queue * queue;
    struct blk_mq_ctxs * ctxs;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_ctx {
    spinlock_t lock;
    struct list_head[3] rq_lists;
    unsigned int cpu;
    short unsigned int[3] index_hw;
    struct blk_mq_hw_ctx *[3] hctxs;
    struct request_queue * queue;
    struct blk_mq_ctxs * ctxs;
    struct kobject kobj;
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
struct blk_mq_ctx {
    spinlock_t lock;
    struct list_head[3] rq_lists;
    unsigned int cpu;
    short unsigned int[3] index_hw;
    struct blk_mq_hw_ctx *[3] hctxs;
    long unsigned int[2] rq_dispatched;
    long unsigned int rq_merged;
    long unsigned int[2] rq_completed;
    struct request_queue * queue;
    struct blk_mq_ctxs * ctxs;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct blk_mq_ctx {
    spinlock_t lock;
    struct list_head[3] rq_lists;
    unsigned int cpu;
    short unsigned int[3] index_hw;
    struct blk_mq_hw_ctx *[3] hctxs;
    long unsigned int[2] rq_dispatched;
    long unsigned int rq_merged;
    long unsigned int[2] rq_completed;
    struct request_queue * queue;
    struct blk_mq_ctxs * ctxs;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct blk_mq_ctx {
    spinlock_t lock;
    struct list_head[3] rq_lists;
    unsigned int cpu;
    short unsigned int[3] index_hw;
    struct blk_mq_hw_ctx *[3] hctxs;
    long unsigned int[2] rq_dispatched;
    long unsigned int rq_merged;
    long unsigned int[2] rq_completed;
    struct request_queue * queue;
    struct blk_mq_ctxs * ctxs;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct blk_mq_ctx {
    spinlock_t lock;
    struct list_head[3] rq_lists;
    unsigned int cpu;
    short unsigned int[3] index_hw;
    struct blk_mq_hw_ctx *[3] hctxs;
    long unsigned int[2] rq_dispatched;
    long unsigned int rq_merged;
    long unsigned int[2] rq_completed;
    struct request_queue * queue;
    struct blk_mq_ctxs * ctxs;
    struct kobject kobj;
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
struct blk_mq_ctx {
    spinlock_t lock;
    struct list_head[3] rq_lists;
    unsigned int cpu;
    short unsigned int[3] index_hw;
    struct blk_mq_hw_ctx *[3] hctxs;
    long unsigned int[2] rq_dispatched;
    long unsigned int rq_merged;
    long unsigned int[2] rq_completed;
    struct request_queue * queue;
    struct blk_mq_ctxs * ctxs;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct blk_mq_ctx {
    spinlock_t lock;
    struct list_head[3] rq_lists;
    unsigned int cpu;
    short unsigned int[3] index_hw;
    struct blk_mq_hw_ctx *[3] hctxs;
    long unsigned int[2] rq_dispatched;
    long unsigned int rq_merged;
    long unsigned int[2] rq_completed;
    struct request_queue * queue;
    struct blk_mq_ctxs * ctxs;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct blk_mq_ctx {
    spinlock_t lock;
    struct list_head[3] rq_lists;
    unsigned int cpu;
    short unsigned int[3] index_hw;
    struct blk_mq_hw_ctx *[3] hctxs;
    long unsigned int[2] rq_dispatched;
    long unsigned int rq_merged;
    long unsigned int[2] rq_completed;
    struct request_queue * queue;
    struct blk_mq_ctxs * ctxs;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct blk_mq_ctx {
    spinlock_t lock;
    struct list_head[3] rq_lists;
    unsigned int cpu;
    short unsigned int[3] index_hw;
    struct blk_mq_hw_ctx *[3] hctxs;
    long unsigned int[2] rq_dispatched;
    long unsigned int rq_merged;
    long unsigned int[2] rq_completed;
    struct request_queue * queue;
    struct blk_mq_ctxs * ctxs;
    struct kobject kobj;
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct blk_rq_stat[2] stat</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int last_tag</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct blk_rq_stat[2] stat</code>
</li>
</ul>
</details>
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
<code>struct list_head[3] rq_lists</code>
</li>
<li>
<b>Field added. </b>
<code>struct blk_mq_ctxs * ctxs</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head rq_list</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int index_hw</code> ➡️ <code>short unsigned int[3] index_hw</code>
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
<code>struct blk_mq_hw_ctx *[3] hctxs</code>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>long unsigned int[2] rq_dispatched</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int rq_merged</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int[2] rq_completed</code>
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
