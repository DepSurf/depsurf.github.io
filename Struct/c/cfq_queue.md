# Struct: <code>cfq_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct cfq_queue {
    int ref;
    unsigned int flags;
    struct cfq_data * cfqd;
    struct rb_node rb_node;
    long unsigned int rb_key;
    struct rb_node p_node;
    struct rb_root * p_root;
    struct rb_root sort_list;
    struct request * next_rq;
    int[2] queued;
    int[2] allocated;
    struct list_head fifo;
    long unsigned int dispatch_start;
    unsigned int allocated_slice;
    unsigned int slice_dispatch;
    long unsigned int slice_start;
    long unsigned int slice_end;
    long int slice_resid;
    int prio_pending;
    int dispatched;
    short unsigned int ioprio;
    short unsigned int org_ioprio;
    short unsigned int ioprio_class;
    pid_t pid;
    u32 seek_history;
    sector_t last_request_pos;
    struct cfq_rb_root * service_tree;
    struct cfq_queue * new_cfqq;
    struct cfq_group * cfqg;
    long unsigned int nr_sectors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct cfq_queue {
    int ref;
    unsigned int flags;
    struct cfq_data * cfqd;
    struct rb_node rb_node;
    u64 rb_key;
    struct rb_node p_node;
    struct rb_root * p_root;
    struct rb_root sort_list;
    struct request * next_rq;
    int[2] queued;
    int[2] allocated;
    struct list_head fifo;
    u64 dispatch_start;
    u64 allocated_slice;
    u64 slice_dispatch;
    u64 slice_start;
    u64 slice_end;
    s64 slice_resid;
    int prio_pending;
    int dispatched;
    short unsigned int ioprio;
    short unsigned int org_ioprio;
    short unsigned int ioprio_class;
    short unsigned int org_ioprio_class;
    pid_t pid;
    u32 seek_history;
    sector_t last_request_pos;
    struct cfq_rb_root * service_tree;
    struct cfq_queue * new_cfqq;
    struct cfq_group * cfqg;
    long unsigned int nr_sectors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct cfq_queue {
    int ref;
    unsigned int flags;
    struct cfq_data * cfqd;
    struct rb_node rb_node;
    u64 rb_key;
    struct rb_node p_node;
    struct rb_root * p_root;
    struct rb_root sort_list;
    struct request * next_rq;
    int[2] queued;
    int[2] allocated;
    struct list_head fifo;
    u64 dispatch_start;
    u64 allocated_slice;
    u64 slice_dispatch;
    u64 slice_start;
    u64 slice_end;
    s64 slice_resid;
    int prio_pending;
    int dispatched;
    short unsigned int ioprio;
    short unsigned int org_ioprio;
    short unsigned int ioprio_class;
    short unsigned int org_ioprio_class;
    pid_t pid;
    u32 seek_history;
    sector_t last_request_pos;
    struct cfq_rb_root * service_tree;
    struct cfq_queue * new_cfqq;
    struct cfq_group * cfqg;
    long unsigned int nr_sectors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct cfq_queue {
    int ref;
    unsigned int flags;
    struct cfq_data * cfqd;
    struct rb_node rb_node;
    u64 rb_key;
    struct rb_node p_node;
    struct rb_root * p_root;
    struct rb_root sort_list;
    struct request * next_rq;
    int[2] queued;
    int[2] allocated;
    struct list_head fifo;
    u64 dispatch_start;
    u64 allocated_slice;
    u64 slice_dispatch;
    u64 slice_start;
    u64 slice_end;
    s64 slice_resid;
    int prio_pending;
    int dispatched;
    short unsigned int ioprio;
    short unsigned int org_ioprio;
    short unsigned int ioprio_class;
    short unsigned int org_ioprio_class;
    pid_t pid;
    u32 seek_history;
    sector_t last_request_pos;
    struct cfq_rb_root * service_tree;
    struct cfq_queue * new_cfqq;
    struct cfq_group * cfqg;
    long unsigned int nr_sectors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct cfq_queue {
    int ref;
    unsigned int flags;
    struct cfq_data * cfqd;
    struct rb_node rb_node;
    u64 rb_key;
    struct rb_node p_node;
    struct rb_root * p_root;
    struct rb_root sort_list;
    struct request * next_rq;
    int[2] queued;
    int[2] allocated;
    struct list_head fifo;
    u64 dispatch_start;
    u64 allocated_slice;
    u64 slice_dispatch;
    u64 slice_start;
    u64 slice_end;
    s64 slice_resid;
    int prio_pending;
    int dispatched;
    short unsigned int ioprio;
    short unsigned int org_ioprio;
    short unsigned int ioprio_class;
    short unsigned int org_ioprio_class;
    pid_t pid;
    u32 seek_history;
    sector_t last_request_pos;
    struct cfq_rb_root * service_tree;
    struct cfq_queue * new_cfqq;
    struct cfq_group * cfqg;
    long unsigned int nr_sectors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct cfq_queue {
    int ref;
    unsigned int flags;
    struct cfq_data * cfqd;
    struct rb_node rb_node;
    u64 rb_key;
    struct rb_node p_node;
    struct rb_root * p_root;
    struct rb_root sort_list;
    struct request * next_rq;
    int[2] queued;
    int[2] allocated;
    struct list_head fifo;
    u64 dispatch_start;
    u64 allocated_slice;
    u64 slice_dispatch;
    u64 slice_start;
    u64 slice_end;
    s64 slice_resid;
    int prio_pending;
    int dispatched;
    short unsigned int ioprio;
    short unsigned int org_ioprio;
    short unsigned int ioprio_class;
    short unsigned int org_ioprio_class;
    pid_t pid;
    u32 seek_history;
    sector_t last_request_pos;
    struct cfq_rb_root * service_tree;
    struct cfq_queue * new_cfqq;
    struct cfq_group * cfqg;
    long unsigned int nr_sectors;
}
```
</details>
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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>short unsigned int org_ioprio_class</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int rb_key</code> ➡️ <code>u64 rb_key</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int dispatch_start</code> ➡️ <code>u64 dispatch_start</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int allocated_slice</code> ➡️ <code>u64 allocated_slice</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int slice_dispatch</code> ➡️ <code>u64 slice_dispatch</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int slice_start</code> ➡️ <code>u64 slice_start</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int slice_end</code> ➡️ <code>u64 slice_end</code>
</li>
<li>
<b>Field type changed. </b>
<code>long int slice_resid</code> ➡️ <code>s64 slice_resid</code>
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
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
struct cfq_queue {
    int ref;
    unsigned int flags;
    struct cfq_data * cfqd;
    struct rb_node rb_node;
    u64 rb_key;
    struct rb_node p_node;
    struct rb_root * p_root;
    struct rb_root sort_list;
    struct request * next_rq;
    int[2] queued;
    int[2] allocated;
    struct list_head fifo;
    u64 dispatch_start;
    u64 allocated_slice;
    u64 slice_dispatch;
    u64 slice_start;
    u64 slice_end;
    s64 slice_resid;
    int prio_pending;
    int dispatched;
    short unsigned int ioprio;
    short unsigned int org_ioprio;
    short unsigned int ioprio_class;
    short unsigned int org_ioprio_class;
    pid_t pid;
    u32 seek_history;
    sector_t last_request_pos;
    struct cfq_rb_root * service_tree;
    struct cfq_queue * new_cfqq;
    struct cfq_group * cfqg;
    long unsigned int nr_sectors;
}
```
</details>
</li>
</ul>
