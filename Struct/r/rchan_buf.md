# Struct: <code>rchan_buf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct rchan_buf {
    void * start;
    void * data;
    size_t offset;
    size_t subbufs_produced;
    size_t subbufs_consumed;
    struct rchan * chan;
    wait_queue_head_t read_wait;
    struct timer_list timer;
    struct dentry * dentry;
    struct kref kref;
    struct page * * page_array;
    unsigned int page_count;
    unsigned int finalized;
    size_t * padding;
    size_t prev_padding;
    size_t bytes_consumed;
    size_t early_bytes;
    unsigned int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct rchan_buf {
    void * start;
    void * data;
    size_t offset;
    size_t subbufs_produced;
    size_t subbufs_consumed;
    struct rchan * chan;
    wait_queue_head_t read_wait;
    struct timer_list timer;
    struct dentry * dentry;
    struct kref kref;
    struct page * * page_array;
    unsigned int page_count;
    unsigned int finalized;
    size_t * padding;
    size_t prev_padding;
    size_t bytes_consumed;
    size_t early_bytes;
    unsigned int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct rchan_buf {
    void * start;
    void * data;
    size_t offset;
    size_t subbufs_produced;
    size_t subbufs_consumed;
    struct rchan * chan;
    wait_queue_head_t read_wait;
    struct irq_work wakeup_work;
    struct dentry * dentry;
    struct kref kref;
    struct page * * page_array;
    unsigned int page_count;
    unsigned int finalized;
    size_t * padding;
    size_t prev_padding;
    size_t bytes_consumed;
    size_t early_bytes;
    unsigned int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct rchan_buf {
    void * start;
    void * data;
    size_t offset;
    size_t subbufs_produced;
    size_t subbufs_consumed;
    struct rchan * chan;
    wait_queue_head_t read_wait;
    struct irq_work wakeup_work;
    struct dentry * dentry;
    struct kref kref;
    struct page * * page_array;
    unsigned int page_count;
    unsigned int finalized;
    size_t * padding;
    size_t prev_padding;
    size_t bytes_consumed;
    size_t early_bytes;
    unsigned int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct rchan_buf {
    void * start;
    void * data;
    size_t offset;
    size_t subbufs_produced;
    size_t subbufs_consumed;
    struct rchan * chan;
    wait_queue_head_t read_wait;
    struct irq_work wakeup_work;
    struct dentry * dentry;
    struct kref kref;
    struct page * * page_array;
    unsigned int page_count;
    unsigned int finalized;
    size_t * padding;
    size_t prev_padding;
    size_t bytes_consumed;
    size_t early_bytes;
    unsigned int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct rchan_buf {
    void * start;
    void * data;
    size_t offset;
    size_t subbufs_produced;
    size_t subbufs_consumed;
    struct rchan * chan;
    wait_queue_head_t read_wait;
    struct irq_work wakeup_work;
    struct dentry * dentry;
    struct kref kref;
    struct page * * page_array;
    unsigned int page_count;
    unsigned int finalized;
    size_t * padding;
    size_t prev_padding;
    size_t bytes_consumed;
    size_t early_bytes;
    unsigned int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct rchan_buf {
    void * start;
    void * data;
    size_t offset;
    size_t subbufs_produced;
    size_t subbufs_consumed;
    struct rchan * chan;
    wait_queue_head_t read_wait;
    struct irq_work wakeup_work;
    struct dentry * dentry;
    struct kref kref;
    struct page * * page_array;
    unsigned int page_count;
    unsigned int finalized;
    size_t * padding;
    size_t prev_padding;
    size_t bytes_consumed;
    size_t early_bytes;
    unsigned int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct rchan_buf {
    void * start;
    void * data;
    size_t offset;
    size_t subbufs_produced;
    size_t subbufs_consumed;
    struct rchan * chan;
    wait_queue_head_t read_wait;
    struct irq_work wakeup_work;
    struct dentry * dentry;
    struct kref kref;
    struct page * * page_array;
    unsigned int page_count;
    unsigned int finalized;
    size_t * padding;
    size_t prev_padding;
    size_t bytes_consumed;
    size_t early_bytes;
    unsigned int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct rchan_buf {
    void * start;
    void * data;
    size_t offset;
    size_t subbufs_produced;
    size_t subbufs_consumed;
    struct rchan * chan;
    wait_queue_head_t read_wait;
    struct irq_work wakeup_work;
    struct dentry * dentry;
    struct kref kref;
    struct page * * page_array;
    unsigned int page_count;
    unsigned int finalized;
    size_t * padding;
    size_t prev_padding;
    size_t bytes_consumed;
    size_t early_bytes;
    unsigned int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct rchan_buf {
    void * start;
    void * data;
    size_t offset;
    size_t subbufs_produced;
    size_t subbufs_consumed;
    struct rchan * chan;
    wait_queue_head_t read_wait;
    struct irq_work wakeup_work;
    struct dentry * dentry;
    struct kref kref;
    struct page * * page_array;
    unsigned int page_count;
    unsigned int finalized;
    size_t * padding;
    size_t prev_padding;
    size_t bytes_consumed;
    size_t early_bytes;
    unsigned int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct rchan_buf {
    void * start;
    void * data;
    size_t offset;
    size_t subbufs_produced;
    size_t subbufs_consumed;
    struct rchan * chan;
    wait_queue_head_t read_wait;
    struct irq_work wakeup_work;
    struct dentry * dentry;
    struct kref kref;
    struct page * * page_array;
    unsigned int page_count;
    unsigned int finalized;
    size_t * padding;
    size_t prev_padding;
    size_t bytes_consumed;
    size_t early_bytes;
    unsigned int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct rchan_buf {
    void * start;
    void * data;
    size_t offset;
    size_t subbufs_produced;
    size_t subbufs_consumed;
    struct rchan * chan;
    wait_queue_head_t read_wait;
    struct irq_work wakeup_work;
    struct dentry * dentry;
    struct kref kref;
    struct page * * page_array;
    unsigned int page_count;
    unsigned int finalized;
    size_t * padding;
    size_t prev_padding;
    size_t bytes_consumed;
    size_t early_bytes;
    unsigned int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct rchan_buf {
    void * start;
    void * data;
    size_t offset;
    size_t subbufs_produced;
    size_t subbufs_consumed;
    struct rchan * chan;
    wait_queue_head_t read_wait;
    struct irq_work wakeup_work;
    struct dentry * dentry;
    struct kref kref;
    struct page * * page_array;
    unsigned int page_count;
    unsigned int finalized;
    size_t * padding;
    size_t prev_padding;
    size_t bytes_consumed;
    size_t early_bytes;
    unsigned int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct rchan_buf {
    void * start;
    void * data;
    size_t offset;
    size_t subbufs_produced;
    size_t subbufs_consumed;
    struct rchan * chan;
    wait_queue_head_t read_wait;
    struct irq_work wakeup_work;
    struct dentry * dentry;
    struct kref kref;
    struct page * * page_array;
    unsigned int page_count;
    unsigned int finalized;
    size_t * padding;
    size_t prev_padding;
    size_t bytes_consumed;
    size_t early_bytes;
    unsigned int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct rchan_buf {
    void * start;
    void * data;
    size_t offset;
    size_t subbufs_produced;
    size_t subbufs_consumed;
    struct rchan * chan;
    wait_queue_head_t read_wait;
    struct irq_work wakeup_work;
    struct dentry * dentry;
    struct kref kref;
    struct page * * page_array;
    unsigned int page_count;
    unsigned int finalized;
    size_t * padding;
    size_t prev_padding;
    size_t bytes_consumed;
    size_t early_bytes;
    unsigned int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct rchan_buf {
    void * start;
    void * data;
    size_t offset;
    size_t subbufs_produced;
    size_t subbufs_consumed;
    struct rchan * chan;
    wait_queue_head_t read_wait;
    struct irq_work wakeup_work;
    struct dentry * dentry;
    struct kref kref;
    struct page * * page_array;
    unsigned int page_count;
    unsigned int finalized;
    size_t * padding;
    size_t prev_padding;
    size_t bytes_consumed;
    size_t early_bytes;
    unsigned int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct rchan_buf {
    void * start;
    void * data;
    size_t offset;
    size_t subbufs_produced;
    size_t subbufs_consumed;
    struct rchan * chan;
    wait_queue_head_t read_wait;
    struct irq_work wakeup_work;
    struct dentry * dentry;
    struct kref kref;
    struct page * * page_array;
    unsigned int page_count;
    unsigned int finalized;
    size_t * padding;
    size_t prev_padding;
    size_t bytes_consumed;
    size_t early_bytes;
    unsigned int cpu;
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
struct rchan_buf {
    void * start;
    void * data;
    size_t offset;
    size_t subbufs_produced;
    size_t subbufs_consumed;
    struct rchan * chan;
    wait_queue_head_t read_wait;
    struct irq_work wakeup_work;
    struct dentry * dentry;
    struct kref kref;
    struct page * * page_array;
    unsigned int page_count;
    unsigned int finalized;
    size_t * padding;
    size_t prev_padding;
    size_t bytes_consumed;
    size_t early_bytes;
    unsigned int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct rchan_buf {
    void * start;
    void * data;
    size_t offset;
    size_t subbufs_produced;
    size_t subbufs_consumed;
    struct rchan * chan;
    wait_queue_head_t read_wait;
    struct irq_work wakeup_work;
    struct dentry * dentry;
    struct kref kref;
    struct page * * page_array;
    unsigned int page_count;
    unsigned int finalized;
    size_t * padding;
    size_t prev_padding;
    size_t bytes_consumed;
    size_t early_bytes;
    unsigned int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct rchan_buf {
    void * start;
    void * data;
    size_t offset;
    size_t subbufs_produced;
    size_t subbufs_consumed;
    struct rchan * chan;
    wait_queue_head_t read_wait;
    struct irq_work wakeup_work;
    struct dentry * dentry;
    struct kref kref;
    struct page * * page_array;
    unsigned int page_count;
    unsigned int finalized;
    size_t * padding;
    size_t prev_padding;
    size_t bytes_consumed;
    size_t early_bytes;
    unsigned int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct rchan_buf {
    void * start;
    void * data;
    size_t offset;
    size_t subbufs_produced;
    size_t subbufs_consumed;
    struct rchan * chan;
    wait_queue_head_t read_wait;
    struct irq_work wakeup_work;
    struct dentry * dentry;
    struct kref kref;
    struct page * * page_array;
    unsigned int page_count;
    unsigned int finalized;
    size_t * padding;
    size_t prev_padding;
    size_t bytes_consumed;
    size_t early_bytes;
    unsigned int cpu;
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
struct rchan_buf {
    void * start;
    void * data;
    size_t offset;
    size_t subbufs_produced;
    size_t subbufs_consumed;
    struct rchan * chan;
    wait_queue_head_t read_wait;
    struct irq_work wakeup_work;
    struct dentry * dentry;
    struct kref kref;
    struct page * * page_array;
    unsigned int page_count;
    unsigned int finalized;
    size_t * padding;
    size_t prev_padding;
    size_t bytes_consumed;
    size_t early_bytes;
    unsigned int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct rchan_buf {
    void * start;
    void * data;
    size_t offset;
    size_t subbufs_produced;
    size_t subbufs_consumed;
    struct rchan * chan;
    wait_queue_head_t read_wait;
    struct irq_work wakeup_work;
    struct dentry * dentry;
    struct kref kref;
    struct page * * page_array;
    unsigned int page_count;
    unsigned int finalized;
    size_t * padding;
    size_t prev_padding;
    size_t bytes_consumed;
    size_t early_bytes;
    unsigned int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct rchan_buf {
    void * start;
    void * data;
    size_t offset;
    size_t subbufs_produced;
    size_t subbufs_consumed;
    struct rchan * chan;
    wait_queue_head_t read_wait;
    struct irq_work wakeup_work;
    struct dentry * dentry;
    struct kref kref;
    struct page * * page_array;
    unsigned int page_count;
    unsigned int finalized;
    size_t * padding;
    size_t prev_padding;
    size_t bytes_consumed;
    size_t early_bytes;
    unsigned int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct rchan_buf {
    void * start;
    void * data;
    size_t offset;
    size_t subbufs_produced;
    size_t subbufs_consumed;
    struct rchan * chan;
    wait_queue_head_t read_wait;
    struct irq_work wakeup_work;
    struct dentry * dentry;
    struct kref kref;
    struct page * * page_array;
    unsigned int page_count;
    unsigned int finalized;
    size_t * padding;
    size_t prev_padding;
    size_t bytes_consumed;
    size_t early_bytes;
    unsigned int cpu;
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
<code>struct irq_work wakeup_work</code>
</li>
<li>
<b>Field removed. </b>
<code>struct timer_list timer</code>
</li>
</ul>
</details>
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
