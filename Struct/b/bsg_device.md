# Struct: <code>bsg_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct bsg_device {
    struct request_queue * queue;
    spinlock_t lock;
    struct list_head busy_list;
    struct list_head done_list;
    struct hlist_node dev_list;
    atomic_t ref_count;
    int queued_cmds;
    int done_cmds;
    wait_queue_head_t wq_done;
    wait_queue_head_t wq_free;
    char[20] name;
    int max_queue;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct bsg_device {
    struct request_queue * queue;
    spinlock_t lock;
    struct list_head busy_list;
    struct list_head done_list;
    struct hlist_node dev_list;
    atomic_t ref_count;
    int queued_cmds;
    int done_cmds;
    wait_queue_head_t wq_done;
    wait_queue_head_t wq_free;
    char[20] name;
    int max_queue;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct bsg_device {
    struct request_queue * queue;
    spinlock_t lock;
    struct list_head busy_list;
    struct list_head done_list;
    struct hlist_node dev_list;
    atomic_t ref_count;
    int queued_cmds;
    int done_cmds;
    wait_queue_head_t wq_done;
    wait_queue_head_t wq_free;
    char[20] name;
    int max_queue;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct bsg_device {
    struct request_queue * queue;
    spinlock_t lock;
    struct list_head busy_list;
    struct list_head done_list;
    struct hlist_node dev_list;
    atomic_t ref_count;
    int queued_cmds;
    int done_cmds;
    wait_queue_head_t wq_done;
    wait_queue_head_t wq_free;
    char[20] name;
    int max_queue;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct bsg_device {
    struct request_queue * queue;
    spinlock_t lock;
    struct list_head busy_list;
    struct list_head done_list;
    struct hlist_node dev_list;
    atomic_t ref_count;
    int queued_cmds;
    int done_cmds;
    wait_queue_head_t wq_done;
    wait_queue_head_t wq_free;
    char[20] name;
    int max_queue;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct bsg_device {
    struct request_queue * queue;
    spinlock_t lock;
    struct list_head busy_list;
    struct list_head done_list;
    struct hlist_node dev_list;
    atomic_t ref_count;
    int queued_cmds;
    int done_cmds;
    wait_queue_head_t wq_done;
    wait_queue_head_t wq_free;
    char[20] name;
    int max_queue;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct bsg_device {
    struct request_queue * queue;
    spinlock_t lock;
    struct hlist_node dev_list;
    refcount_t ref_count;
    char[20] name;
    int max_queue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct bsg_device {
    struct request_queue * queue;
    spinlock_t lock;
    struct hlist_node dev_list;
    refcount_t ref_count;
    char[20] name;
    int max_queue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct bsg_device {
    struct request_queue * queue;
    spinlock_t lock;
    struct hlist_node dev_list;
    refcount_t ref_count;
    char[20] name;
    int max_queue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct bsg_device {
    struct request_queue * queue;
    spinlock_t lock;
    struct hlist_node dev_list;
    refcount_t ref_count;
    char[20] name;
    int max_queue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct bsg_device {
    struct request_queue * queue;
    spinlock_t lock;
    struct hlist_node dev_list;
    refcount_t ref_count;
    char[20] name;
    int max_queue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct bsg_device {
    struct request_queue * queue;
    spinlock_t lock;
    struct hlist_node dev_list;
    refcount_t ref_count;
    char[20] name;
    int max_queue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct bsg_device {
    struct request_queue * queue;
    struct device device;
    struct cdev cdev;
    int max_queue;
    unsigned int timeout;
    unsigned int reserved_size;
    bsg_sg_io_fn * sg_io_fn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct bsg_device {
    struct request_queue * queue;
    struct device device;
    struct cdev cdev;
    int max_queue;
    unsigned int timeout;
    unsigned int reserved_size;
    bsg_sg_io_fn * sg_io_fn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct bsg_device {
    struct request_queue * queue;
    struct device device;
    struct cdev cdev;
    int max_queue;
    unsigned int timeout;
    unsigned int reserved_size;
    bsg_sg_io_fn * sg_io_fn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct bsg_device {
    struct request_queue * queue;
    struct device device;
    struct cdev cdev;
    int max_queue;
    unsigned int timeout;
    unsigned int reserved_size;
    bsg_sg_io_fn * sg_io_fn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct bsg_device {
    struct request_queue * queue;
    struct device device;
    struct cdev cdev;
    int max_queue;
    unsigned int timeout;
    unsigned int reserved_size;
    bsg_sg_io_fn * sg_io_fn;
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
struct bsg_device {
    struct request_queue * queue;
    spinlock_t lock;
    struct hlist_node dev_list;
    refcount_t ref_count;
    char[20] name;
    int max_queue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct bsg_device {
    struct request_queue * queue;
    spinlock_t lock;
    struct hlist_node dev_list;
    refcount_t ref_count;
    char[20] name;
    int max_queue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct bsg_device {
    struct request_queue * queue;
    spinlock_t lock;
    struct hlist_node dev_list;
    refcount_t ref_count;
    char[20] name;
    int max_queue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct bsg_device {
    struct request_queue * queue;
    spinlock_t lock;
    struct hlist_node dev_list;
    refcount_t ref_count;
    char[20] name;
    int max_queue;
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
struct bsg_device {
    struct request_queue * queue;
    spinlock_t lock;
    struct hlist_node dev_list;
    refcount_t ref_count;
    char[20] name;
    int max_queue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct bsg_device {
    struct request_queue * queue;
    spinlock_t lock;
    struct hlist_node dev_list;
    refcount_t ref_count;
    char[20] name;
    int max_queue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct bsg_device {
    struct request_queue * queue;
    spinlock_t lock;
    struct hlist_node dev_list;
    refcount_t ref_count;
    char[20] name;
    int max_queue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct bsg_device {
    struct request_queue * queue;
    spinlock_t lock;
    struct hlist_node dev_list;
    refcount_t ref_count;
    char[20] name;
    int max_queue;
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct list_head busy_list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head done_list</code>
</li>
<li>
<b>Field removed. </b>
<code>int queued_cmds</code>
</li>
<li>
<b>Field removed. </b>
<code>int done_cmds</code>
</li>
<li>
<b>Field removed. </b>
<code>wait_queue_head_t wq_done</code>
</li>
<li>
<b>Field removed. </b>
<code>wait_queue_head_t wq_free</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int flags</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_t ref_count</code> ➡️ <code>refcount_t ref_count</code>
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
<code>struct device device</code>
</li>
<li>
<b>Field added. </b>
<code>struct cdev cdev</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int timeout</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int reserved_size</code>
</li>
<li>
<b>Field added. </b>
<code>bsg_sg_io_fn * sg_io_fn</code>
</li>
<li>
<b>Field removed. </b>
<code>spinlock_t lock</code>
</li>
<li>
<b>Field removed. </b>
<code>struct hlist_node dev_list</code>
</li>
<li>
<b>Field removed. </b>
<code>refcount_t ref_count</code>
</li>
<li>
<b>Field removed. </b>
<code>char[20] name</code>
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
