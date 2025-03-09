# Struct: <code>dma_buf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dma_buf {
    size_t size;
    struct file * file;
    struct list_head attachments;
    const struct dma_buf_ops * ops;
    struct mutex lock;
    unsigned int vmapping_counter;
    void * vmap_ptr;
    const char * exp_name;
    struct module * owner;
    struct list_head list_node;
    void * priv;
    struct reservation_object * resv;
    wait_queue_head_t poll;
    struct dma_buf_poll_cb_t cb_excl;
    struct dma_buf_poll_cb_t cb_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct dma_buf {
    size_t size;
    struct file * file;
    struct list_head attachments;
    const struct dma_buf_ops * ops;
    struct mutex lock;
    unsigned int vmapping_counter;
    void * vmap_ptr;
    const char * exp_name;
    struct module * owner;
    struct list_head list_node;
    void * priv;
    struct reservation_object * resv;
    wait_queue_head_t poll;
    struct dma_buf_poll_cb_t cb_excl;
    struct dma_buf_poll_cb_t cb_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct dma_buf {
    size_t size;
    struct file * file;
    struct list_head attachments;
    const struct dma_buf_ops * ops;
    struct mutex lock;
    unsigned int vmapping_counter;
    void * vmap_ptr;
    const char * exp_name;
    struct module * owner;
    struct list_head list_node;
    void * priv;
    struct reservation_object * resv;
    wait_queue_head_t poll;
    struct dma_buf_poll_cb_t cb_excl;
    struct dma_buf_poll_cb_t cb_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dma_buf {
    size_t size;
    struct file * file;
    struct list_head attachments;
    const struct dma_buf_ops * ops;
    struct mutex lock;
    unsigned int vmapping_counter;
    void * vmap_ptr;
    const char * exp_name;
    struct module * owner;
    struct list_head list_node;
    void * priv;
    struct reservation_object * resv;
    wait_queue_head_t poll;
    struct dma_buf_poll_cb_t cb_excl;
    struct dma_buf_poll_cb_t cb_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dma_buf {
    size_t size;
    struct file * file;
    struct list_head attachments;
    const struct dma_buf_ops * ops;
    struct mutex lock;
    unsigned int vmapping_counter;
    void * vmap_ptr;
    const char * exp_name;
    struct module * owner;
    struct list_head list_node;
    void * priv;
    struct reservation_object * resv;
    wait_queue_head_t poll;
    struct dma_buf_poll_cb_t cb_excl;
    struct dma_buf_poll_cb_t cb_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dma_buf {
    size_t size;
    struct file * file;
    struct list_head attachments;
    const struct dma_buf_ops * ops;
    struct mutex lock;
    unsigned int vmapping_counter;
    void * vmap_ptr;
    const char * exp_name;
    struct module * owner;
    struct list_head list_node;
    void * priv;
    struct reservation_object * resv;
    wait_queue_head_t poll;
    struct dma_buf_poll_cb_t cb_excl;
    struct dma_buf_poll_cb_t cb_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dma_buf {
    size_t size;
    struct file * file;
    struct list_head attachments;
    const struct dma_buf_ops * ops;
    struct mutex lock;
    unsigned int vmapping_counter;
    void * vmap_ptr;
    const char * exp_name;
    struct module * owner;
    struct list_head list_node;
    void * priv;
    struct reservation_object * resv;
    wait_queue_head_t poll;
    struct dma_buf_poll_cb_t cb_excl;
    struct dma_buf_poll_cb_t cb_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dma_buf {
    size_t size;
    struct file * file;
    struct list_head attachments;
    const struct dma_buf_ops * ops;
    struct mutex lock;
    unsigned int vmapping_counter;
    void * vmap_ptr;
    const char * exp_name;
    const char * name;
    struct module * owner;
    struct list_head list_node;
    void * priv;
    struct reservation_object * resv;
    wait_queue_head_t poll;
    struct dma_buf_poll_cb_t cb_excl;
    struct dma_buf_poll_cb_t cb_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct dma_buf {
    size_t size;
    struct file * file;
    struct list_head attachments;
    const struct dma_buf_ops * ops;
    struct mutex lock;
    unsigned int vmapping_counter;
    void * vmap_ptr;
    const char * exp_name;
    const char * name;
    struct module * owner;
    struct list_head list_node;
    void * priv;
    struct dma_resv * resv;
    wait_queue_head_t poll;
    struct dma_buf_poll_cb_t cb_excl;
    struct dma_buf_poll_cb_t cb_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct dma_buf {
    size_t size;
    struct file * file;
    struct list_head attachments;
    const struct dma_buf_ops * ops;
    struct mutex lock;
    unsigned int vmapping_counter;
    void * vmap_ptr;
    const char * exp_name;
    const char * name;
    spinlock_t name_lock;
    struct module * owner;
    struct list_head list_node;
    void * priv;
    struct dma_resv * resv;
    wait_queue_head_t poll;
    struct dma_buf_poll_cb_t cb_excl;
    struct dma_buf_poll_cb_t cb_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct dma_buf {
    size_t size;
    struct file * file;
    struct list_head attachments;
    const struct dma_buf_ops * ops;
    struct mutex lock;
    unsigned int vmapping_counter;
    struct dma_buf_map vmap_ptr;
    const char * exp_name;
    const char * name;
    spinlock_t name_lock;
    struct module * owner;
    struct list_head list_node;
    void * priv;
    struct dma_resv * resv;
    wait_queue_head_t poll;
    struct dma_buf_poll_cb_t cb_excl;
    struct dma_buf_poll_cb_t cb_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct dma_buf {
    size_t size;
    struct file * file;
    struct list_head attachments;
    const struct dma_buf_ops * ops;
    struct mutex lock;
    unsigned int vmapping_counter;
    struct dma_buf_map vmap_ptr;
    const char * exp_name;
    const char * name;
    spinlock_t name_lock;
    struct module * owner;
    struct list_head list_node;
    void * priv;
    struct dma_resv * resv;
    wait_queue_head_t poll;
    struct dma_buf_poll_cb_t cb_excl;
    struct dma_buf_poll_cb_t cb_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct dma_buf {
    size_t size;
    struct file * file;
    struct list_head attachments;
    const struct dma_buf_ops * ops;
    struct mutex lock;
    unsigned int vmapping_counter;
    struct dma_buf_map vmap_ptr;
    const char * exp_name;
    const char * name;
    spinlock_t name_lock;
    struct module * owner;
    struct list_head list_node;
    void * priv;
    struct dma_resv * resv;
    wait_queue_head_t poll;
    struct dma_buf_poll_cb_t cb_in;
    struct dma_buf_poll_cb_t cb_out;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct dma_buf {
    size_t size;
    struct file * file;
    struct list_head attachments;
    const struct dma_buf_ops * ops;
    struct mutex lock;
    unsigned int vmapping_counter;
    struct iosys_map vmap_ptr;
    const char * exp_name;
    const char * name;
    spinlock_t name_lock;
    struct module * owner;
    struct list_head list_node;
    void * priv;
    struct dma_resv * resv;
    wait_queue_head_t poll;
    struct dma_buf_poll_cb_t cb_in;
    struct dma_buf_poll_cb_t cb_out;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dma_buf {
    size_t size;
    struct file * file;
    struct list_head attachments;
    const struct dma_buf_ops * ops;
    unsigned int vmapping_counter;
    struct iosys_map vmap_ptr;
    const char * exp_name;
    const char * name;
    spinlock_t name_lock;
    struct module * owner;
    struct list_head list_node;
    void * priv;
    struct dma_resv * resv;
    wait_queue_head_t poll;
    struct dma_buf_poll_cb_t cb_in;
    struct dma_buf_poll_cb_t cb_out;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct dma_buf {
    size_t size;
    struct file * file;
    struct list_head attachments;
    const struct dma_buf_ops * ops;
    unsigned int vmapping_counter;
    struct iosys_map vmap_ptr;
    const char * exp_name;
    const char * name;
    spinlock_t name_lock;
    struct module * owner;
    struct list_head list_node;
    void * priv;
    struct dma_resv * resv;
    wait_queue_head_t poll;
    struct dma_buf_poll_cb_t cb_in;
    struct dma_buf_poll_cb_t cb_out;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dma_buf {
    size_t size;
    struct file * file;
    struct list_head attachments;
    const struct dma_buf_ops * ops;
    unsigned int vmapping_counter;
    struct iosys_map vmap_ptr;
    const char * exp_name;
    const char * name;
    spinlock_t name_lock;
    struct module * owner;
    struct list_head list_node;
    void * priv;
    struct dma_resv * resv;
    wait_queue_head_t poll;
    struct dma_buf_poll_cb_t cb_in;
    struct dma_buf_poll_cb_t cb_out;
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
struct dma_buf {
    size_t size;
    struct file * file;
    struct list_head attachments;
    const struct dma_buf_ops * ops;
    struct mutex lock;
    unsigned int vmapping_counter;
    void * vmap_ptr;
    const char * exp_name;
    const char * name;
    struct module * owner;
    struct list_head list_node;
    void * priv;
    struct dma_resv * resv;
    wait_queue_head_t poll;
    struct dma_buf_poll_cb_t cb_excl;
    struct dma_buf_poll_cb_t cb_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dma_buf {
    size_t size;
    struct file * file;
    struct list_head attachments;
    const struct dma_buf_ops * ops;
    struct mutex lock;
    unsigned int vmapping_counter;
    void * vmap_ptr;
    const char * exp_name;
    const char * name;
    struct module * owner;
    struct list_head list_node;
    void * priv;
    struct dma_resv * resv;
    wait_queue_head_t poll;
    struct dma_buf_poll_cb_t cb_excl;
    struct dma_buf_poll_cb_t cb_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct dma_buf {
    size_t size;
    struct file * file;
    struct list_head attachments;
    const struct dma_buf_ops * ops;
    struct mutex lock;
    unsigned int vmapping_counter;
    void * vmap_ptr;
    const char * exp_name;
    const char * name;
    struct module * owner;
    struct list_head list_node;
    void * priv;
    struct dma_resv * resv;
    wait_queue_head_t poll;
    struct dma_buf_poll_cb_t cb_excl;
    struct dma_buf_poll_cb_t cb_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct dma_buf {
    size_t size;
    struct file * file;
    struct list_head attachments;
    const struct dma_buf_ops * ops;
    struct mutex lock;
    unsigned int vmapping_counter;
    void * vmap_ptr;
    const char * exp_name;
    const char * name;
    struct module * owner;
    struct list_head list_node;
    void * priv;
    struct dma_resv * resv;
    wait_queue_head_t poll;
    struct dma_buf_poll_cb_t cb_excl;
    struct dma_buf_poll_cb_t cb_shared;
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
struct dma_buf {
    size_t size;
    struct file * file;
    struct list_head attachments;
    const struct dma_buf_ops * ops;
    struct mutex lock;
    unsigned int vmapping_counter;
    void * vmap_ptr;
    const char * exp_name;
    const char * name;
    struct module * owner;
    struct list_head list_node;
    void * priv;
    struct dma_resv * resv;
    wait_queue_head_t poll;
    struct dma_buf_poll_cb_t cb_excl;
    struct dma_buf_poll_cb_t cb_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct dma_buf {
    size_t size;
    struct file * file;
    struct list_head attachments;
    const struct dma_buf_ops * ops;
    struct mutex lock;
    unsigned int vmapping_counter;
    void * vmap_ptr;
    const char * exp_name;
    const char * name;
    struct module * owner;
    struct list_head list_node;
    void * priv;
    struct dma_resv * resv;
    wait_queue_head_t poll;
    struct dma_buf_poll_cb_t cb_excl;
    struct dma_buf_poll_cb_t cb_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct dma_buf {
    size_t size;
    struct file * file;
    struct list_head attachments;
    const struct dma_buf_ops * ops;
    struct mutex lock;
    unsigned int vmapping_counter;
    void * vmap_ptr;
    const char * exp_name;
    const char * name;
    struct module * owner;
    struct list_head list_node;
    void * priv;
    struct dma_resv * resv;
    wait_queue_head_t poll;
    struct dma_buf_poll_cb_t cb_excl;
    struct dma_buf_poll_cb_t cb_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dma_buf {
    size_t size;
    struct file * file;
    struct list_head attachments;
    const struct dma_buf_ops * ops;
    struct mutex lock;
    unsigned int vmapping_counter;
    void * vmap_ptr;
    const char * exp_name;
    const char * name;
    struct module * owner;
    struct list_head list_node;
    void * priv;
    struct dma_resv * resv;
    wait_queue_head_t poll;
    struct dma_buf_poll_cb_t cb_excl;
    struct dma_buf_poll_cb_t cb_shared;
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
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const char * name</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct reservation_object * resv</code> ➡️ <code>struct dma_resv * resv</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>spinlock_t name_lock</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>void * vmap_ptr</code> ➡️ <code>struct dma_buf_map vmap_ptr</code>
</li>
</ul>
</details>
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
<code>struct dma_buf_poll_cb_t cb_in</code>
</li>
<li>
<b>Field added. </b>
<code>struct dma_buf_poll_cb_t cb_out</code>
</li>
<li>
<b>Field removed. </b>
<code>struct dma_buf_poll_cb_t cb_excl</code>
</li>
<li>
<b>Field removed. </b>
<code>struct dma_buf_poll_cb_t cb_shared</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct dma_buf_map vmap_ptr</code> ➡️ <code>struct iosys_map vmap_ptr</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct mutex lock</code>
</li>
</ul>
</details>
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
