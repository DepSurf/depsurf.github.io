# Struct: <code>blk_mq_hw_ctx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_hw_ctx {
    spinlock_t lock;
    struct list_head dispatch;
    long unsigned int state;
    struct delayed_work run_work;
    struct delayed_work delay_work;
    cpumask_var_t cpumask;
    int next_cpu;
    int next_cpu_batch;
    long unsigned int flags;
    struct request_queue * queue;
    struct blk_flush_queue * fq;
    void * driver_data;
    struct blk_mq_ctxmap ctx_map;
    unsigned int nr_ctx;
    struct blk_mq_ctx * * ctxs;
    atomic_t wait_index;
    struct blk_mq_tags * tags;
    long unsigned int queued;
    long unsigned int run;
    long unsigned int[10] dispatched;
    unsigned int numa_node;
    unsigned int queue_num;
    atomic_t nr_active;
    struct blk_mq_cpu_notifier cpu_notifier;
    struct kobject kobj;
    long unsigned int poll_invoked;
    long unsigned int poll_success;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_hw_ctx {
    spinlock_t lock;
    struct list_head dispatch;
    long unsigned int state;
    struct delayed_work run_work;
    struct delayed_work delay_work;
    cpumask_var_t cpumask;
    int next_cpu;
    int next_cpu_batch;
    long unsigned int flags;
    struct request_queue * queue;
    struct blk_flush_queue * fq;
    void * driver_data;
    struct blk_mq_ctxmap ctx_map;
    unsigned int nr_ctx;
    struct blk_mq_ctx * * ctxs;
    atomic_t wait_index;
    struct blk_mq_tags * tags;
    long unsigned int queued;
    long unsigned int run;
    long unsigned int[10] dispatched;
    unsigned int numa_node;
    unsigned int queue_num;
    atomic_t nr_active;
    struct blk_mq_cpu_notifier cpu_notifier;
    struct kobject kobj;
    long unsigned int poll_invoked;
    long unsigned int poll_success;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_hw_ctx {
    spinlock_t lock;
    struct list_head dispatch;
    long unsigned int state;
    struct work_struct run_work;
    cpumask_var_t cpumask;
    int next_cpu;
    int next_cpu_batch;
    long unsigned int flags;
    struct request_queue * queue;
    struct blk_flush_queue * fq;
    void * driver_data;
    struct sbitmap ctx_map;
    struct blk_mq_ctx * * ctxs;
    unsigned int nr_ctx;
    atomic_t wait_index;
    struct blk_mq_tags * tags;
    struct srcu_struct queue_rq_srcu;
    long unsigned int queued;
    long unsigned int run;
    long unsigned int[7] dispatched;
    unsigned int numa_node;
    unsigned int queue_num;
    atomic_t nr_active;
    struct delayed_work delay_work;
    struct hlist_node cpuhp_dead;
    struct kobject kobj;
    long unsigned int poll_considered;
    long unsigned int poll_invoked;
    long unsigned int poll_success;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_hw_ctx {
    spinlock_t lock;
    struct list_head dispatch;
    long unsigned int state;
    struct delayed_work run_work;
    cpumask_var_t cpumask;
    int next_cpu;
    int next_cpu_batch;
    long unsigned int flags;
    void * sched_data;
    struct request_queue * queue;
    struct blk_flush_queue * fq;
    void * driver_data;
    struct sbitmap ctx_map;
    struct blk_mq_ctx * * ctxs;
    unsigned int nr_ctx;
    wait_queue_entry_t dispatch_wait;
    atomic_t wait_index;
    struct blk_mq_tags * tags;
    struct blk_mq_tags * sched_tags;
    long unsigned int queued;
    long unsigned int run;
    long unsigned int[7] dispatched;
    unsigned int numa_node;
    unsigned int queue_num;
    atomic_t nr_active;
    struct hlist_node cpuhp_dead;
    struct kobject kobj;
    long unsigned int poll_considered;
    long unsigned int poll_invoked;
    long unsigned int poll_success;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct srcu_struct[0] queue_rq_srcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_hw_ctx {
    spinlock_t lock;
    struct list_head dispatch;
    long unsigned int state;
    struct delayed_work run_work;
    cpumask_var_t cpumask;
    int next_cpu;
    int next_cpu_batch;
    long unsigned int flags;
    void * sched_data;
    struct request_queue * queue;
    struct blk_flush_queue * fq;
    void * driver_data;
    struct sbitmap ctx_map;
    struct blk_mq_ctx * dispatch_from;
    struct blk_mq_ctx * * ctxs;
    unsigned int nr_ctx;
    wait_queue_entry_t dispatch_wait;
    atomic_t wait_index;
    struct blk_mq_tags * tags;
    struct blk_mq_tags * sched_tags;
    long unsigned int queued;
    long unsigned int run;
    long unsigned int[7] dispatched;
    unsigned int numa_node;
    unsigned int queue_num;
    atomic_t nr_active;
    struct hlist_node cpuhp_dead;
    struct kobject kobj;
    long unsigned int poll_considered;
    long unsigned int poll_invoked;
    long unsigned int poll_success;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct srcu_struct[0] queue_rq_srcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_hw_ctx {
    spinlock_t lock;
    struct list_head dispatch;
    long unsigned int state;
    struct delayed_work run_work;
    cpumask_var_t cpumask;
    int next_cpu;
    int next_cpu_batch;
    long unsigned int flags;
    void * sched_data;
    struct request_queue * queue;
    struct blk_flush_queue * fq;
    void * driver_data;
    struct sbitmap ctx_map;
    struct blk_mq_ctx * dispatch_from;
    struct blk_mq_ctx * * ctxs;
    unsigned int nr_ctx;
    wait_queue_entry_t dispatch_wait;
    atomic_t wait_index;
    struct blk_mq_tags * tags;
    struct blk_mq_tags * sched_tags;
    long unsigned int queued;
    long unsigned int run;
    long unsigned int[7] dispatched;
    unsigned int numa_node;
    unsigned int queue_num;
    atomic_t nr_active;
    unsigned int nr_expired;
    struct hlist_node cpuhp_dead;
    struct kobject kobj;
    long unsigned int poll_considered;
    long unsigned int poll_invoked;
    long unsigned int poll_success;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct srcu_struct[0] srcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_hw_ctx {
    spinlock_t lock;
    struct list_head dispatch;
    long unsigned int state;
    struct delayed_work run_work;
    cpumask_var_t cpumask;
    int next_cpu;
    int next_cpu_batch;
    long unsigned int flags;
    void * sched_data;
    struct request_queue * queue;
    struct blk_flush_queue * fq;
    void * driver_data;
    struct sbitmap ctx_map;
    struct blk_mq_ctx * dispatch_from;
    unsigned int dispatch_busy;
    short unsigned int type;
    short unsigned int nr_ctx;
    struct blk_mq_ctx * * ctxs;
    spinlock_t dispatch_wait_lock;
    wait_queue_entry_t dispatch_wait;
    atomic_t wait_index;
    struct blk_mq_tags * tags;
    struct blk_mq_tags * sched_tags;
    long unsigned int queued;
    long unsigned int run;
    long unsigned int[7] dispatched;
    unsigned int numa_node;
    unsigned int queue_num;
    atomic_t nr_active;
    unsigned int nr_expired;
    struct hlist_node cpuhp_dead;
    struct kobject kobj;
    long unsigned int poll_considered;
    long unsigned int poll_invoked;
    long unsigned int poll_success;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct srcu_struct[0] srcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_hw_ctx {
    spinlock_t lock;
    struct list_head dispatch;
    long unsigned int state;
    struct delayed_work run_work;
    cpumask_var_t cpumask;
    int next_cpu;
    int next_cpu_batch;
    long unsigned int flags;
    void * sched_data;
    struct request_queue * queue;
    struct blk_flush_queue * fq;
    void * driver_data;
    struct sbitmap ctx_map;
    struct blk_mq_ctx * dispatch_from;
    unsigned int dispatch_busy;
    short unsigned int type;
    short unsigned int nr_ctx;
    struct blk_mq_ctx * * ctxs;
    spinlock_t dispatch_wait_lock;
    wait_queue_entry_t dispatch_wait;
    atomic_t wait_index;
    struct blk_mq_tags * tags;
    struct blk_mq_tags * sched_tags;
    long unsigned int queued;
    long unsigned int run;
    long unsigned int[7] dispatched;
    unsigned int numa_node;
    unsigned int queue_num;
    atomic_t nr_active;
    struct hlist_node cpuhp_dead;
    struct kobject kobj;
    long unsigned int poll_considered;
    long unsigned int poll_invoked;
    long unsigned int poll_success;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct list_head hctx_list;
    struct srcu_struct[0] srcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_hw_ctx {
    spinlock_t lock;
    struct list_head dispatch;
    long unsigned int state;
    struct delayed_work run_work;
    cpumask_var_t cpumask;
    int next_cpu;
    int next_cpu_batch;
    long unsigned int flags;
    void * sched_data;
    struct request_queue * queue;
    struct blk_flush_queue * fq;
    void * driver_data;
    struct sbitmap ctx_map;
    struct blk_mq_ctx * dispatch_from;
    unsigned int dispatch_busy;
    short unsigned int type;
    short unsigned int nr_ctx;
    struct blk_mq_ctx * * ctxs;
    spinlock_t dispatch_wait_lock;
    wait_queue_entry_t dispatch_wait;
    atomic_t wait_index;
    struct blk_mq_tags * tags;
    struct blk_mq_tags * sched_tags;
    long unsigned int queued;
    long unsigned int run;
    long unsigned int[7] dispatched;
    unsigned int numa_node;
    unsigned int queue_num;
    atomic_t nr_active;
    struct hlist_node cpuhp_dead;
    struct kobject kobj;
    long unsigned int poll_considered;
    long unsigned int poll_invoked;
    long unsigned int poll_success;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct list_head hctx_list;
    struct srcu_struct[0] srcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_hw_ctx {
    spinlock_t lock;
    struct list_head dispatch;
    long unsigned int state;
    struct delayed_work run_work;
    cpumask_var_t cpumask;
    int next_cpu;
    int next_cpu_batch;
    long unsigned int flags;
    void * sched_data;
    struct request_queue * queue;
    struct blk_flush_queue * fq;
    void * driver_data;
    struct sbitmap ctx_map;
    struct blk_mq_ctx * dispatch_from;
    unsigned int dispatch_busy;
    short unsigned int type;
    short unsigned int nr_ctx;
    struct blk_mq_ctx * * ctxs;
    spinlock_t dispatch_wait_lock;
    wait_queue_entry_t dispatch_wait;
    atomic_t wait_index;
    struct blk_mq_tags * tags;
    struct blk_mq_tags * sched_tags;
    long unsigned int queued;
    long unsigned int run;
    long unsigned int[7] dispatched;
    unsigned int numa_node;
    unsigned int queue_num;
    atomic_t nr_active;
    struct hlist_node cpuhp_online;
    struct hlist_node cpuhp_dead;
    struct kobject kobj;
    long unsigned int poll_considered;
    long unsigned int poll_invoked;
    long unsigned int poll_success;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct list_head hctx_list;
    struct srcu_struct[0] srcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_hw_ctx {
    spinlock_t lock;
    struct list_head dispatch;
    long unsigned int state;
    struct delayed_work run_work;
    cpumask_var_t cpumask;
    int next_cpu;
    int next_cpu_batch;
    long unsigned int flags;
    void * sched_data;
    struct request_queue * queue;
    struct blk_flush_queue * fq;
    void * driver_data;
    struct sbitmap ctx_map;
    struct blk_mq_ctx * dispatch_from;
    unsigned int dispatch_busy;
    short unsigned int type;
    short unsigned int nr_ctx;
    struct blk_mq_ctx * * ctxs;
    spinlock_t dispatch_wait_lock;
    wait_queue_entry_t dispatch_wait;
    atomic_t wait_index;
    struct blk_mq_tags * tags;
    struct blk_mq_tags * sched_tags;
    long unsigned int queued;
    long unsigned int run;
    long unsigned int[7] dispatched;
    unsigned int numa_node;
    unsigned int queue_num;
    atomic_t nr_active;
    atomic_t elevator_queued;
    struct hlist_node cpuhp_online;
    struct hlist_node cpuhp_dead;
    struct kobject kobj;
    long unsigned int poll_considered;
    long unsigned int poll_invoked;
    long unsigned int poll_success;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct list_head hctx_list;
    struct srcu_struct[0] srcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_hw_ctx {
    spinlock_t lock;
    struct list_head dispatch;
    long unsigned int state;
    struct delayed_work run_work;
    cpumask_var_t cpumask;
    int next_cpu;
    int next_cpu_batch;
    long unsigned int flags;
    void * sched_data;
    struct request_queue * queue;
    struct blk_flush_queue * fq;
    void * driver_data;
    struct sbitmap ctx_map;
    struct blk_mq_ctx * dispatch_from;
    unsigned int dispatch_busy;
    short unsigned int type;
    short unsigned int nr_ctx;
    struct blk_mq_ctx * * ctxs;
    spinlock_t dispatch_wait_lock;
    wait_queue_entry_t dispatch_wait;
    atomic_t wait_index;
    struct blk_mq_tags * tags;
    struct blk_mq_tags * sched_tags;
    long unsigned int queued;
    long unsigned int run;
    long unsigned int[7] dispatched;
    unsigned int numa_node;
    unsigned int queue_num;
    atomic_t nr_active;
    struct hlist_node cpuhp_online;
    struct hlist_node cpuhp_dead;
    struct kobject kobj;
    long unsigned int poll_considered;
    long unsigned int poll_invoked;
    long unsigned int poll_success;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct list_head hctx_list;
    struct srcu_struct[0] srcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_hw_ctx {
    spinlock_t lock;
    struct list_head dispatch;
    long unsigned int state;
    struct delayed_work run_work;
    cpumask_var_t cpumask;
    int next_cpu;
    int next_cpu_batch;
    long unsigned int flags;
    void * sched_data;
    struct request_queue * queue;
    struct blk_flush_queue * fq;
    void * driver_data;
    struct sbitmap ctx_map;
    struct blk_mq_ctx * dispatch_from;
    unsigned int dispatch_busy;
    short unsigned int type;
    short unsigned int nr_ctx;
    struct blk_mq_ctx * * ctxs;
    spinlock_t dispatch_wait_lock;
    wait_queue_entry_t dispatch_wait;
    atomic_t wait_index;
    struct blk_mq_tags * tags;
    struct blk_mq_tags * sched_tags;
    long unsigned int queued;
    long unsigned int run;
    long unsigned int[7] dispatched;
    unsigned int numa_node;
    unsigned int queue_num;
    atomic_t nr_active;
    struct hlist_node cpuhp_online;
    struct hlist_node cpuhp_dead;
    struct kobject kobj;
    long unsigned int poll_considered;
    long unsigned int poll_invoked;
    long unsigned int poll_success;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct list_head hctx_list;
    struct srcu_struct[0] srcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_hw_ctx {
    spinlock_t lock;
    struct list_head dispatch;
    long unsigned int state;
    struct delayed_work run_work;
    cpumask_var_t cpumask;
    int next_cpu;
    int next_cpu_batch;
    long unsigned int flags;
    void * sched_data;
    struct request_queue * queue;
    struct blk_flush_queue * fq;
    void * driver_data;
    struct sbitmap ctx_map;
    struct blk_mq_ctx * dispatch_from;
    unsigned int dispatch_busy;
    short unsigned int type;
    short unsigned int nr_ctx;
    struct blk_mq_ctx * * ctxs;
    spinlock_t dispatch_wait_lock;
    wait_queue_entry_t dispatch_wait;
    atomic_t wait_index;
    struct blk_mq_tags * tags;
    struct blk_mq_tags * sched_tags;
    long unsigned int queued;
    long unsigned int run;
    unsigned int numa_node;
    unsigned int queue_num;
    atomic_t nr_active;
    struct hlist_node cpuhp_online;
    struct hlist_node cpuhp_dead;
    struct kobject kobj;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct list_head hctx_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_hw_ctx {
    spinlock_t lock;
    struct list_head dispatch;
    long unsigned int state;
    struct delayed_work run_work;
    cpumask_var_t cpumask;
    int next_cpu;
    int next_cpu_batch;
    long unsigned int flags;
    void * sched_data;
    struct request_queue * queue;
    struct blk_flush_queue * fq;
    void * driver_data;
    struct sbitmap ctx_map;
    struct blk_mq_ctx * dispatch_from;
    unsigned int dispatch_busy;
    short unsigned int type;
    short unsigned int nr_ctx;
    struct blk_mq_ctx * * ctxs;
    spinlock_t dispatch_wait_lock;
    wait_queue_entry_t dispatch_wait;
    atomic_t wait_index;
    struct blk_mq_tags * tags;
    struct blk_mq_tags * sched_tags;
    long unsigned int queued;
    long unsigned int run;
    unsigned int numa_node;
    unsigned int queue_num;
    atomic_t nr_active;
    struct hlist_node cpuhp_online;
    struct hlist_node cpuhp_dead;
    struct kobject kobj;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct list_head hctx_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_hw_ctx {
    spinlock_t lock;
    struct list_head dispatch;
    long unsigned int state;
    struct delayed_work run_work;
    cpumask_var_t cpumask;
    int next_cpu;
    int next_cpu_batch;
    long unsigned int flags;
    void * sched_data;
    struct request_queue * queue;
    struct blk_flush_queue * fq;
    void * driver_data;
    struct sbitmap ctx_map;
    struct blk_mq_ctx * dispatch_from;
    unsigned int dispatch_busy;
    short unsigned int type;
    short unsigned int nr_ctx;
    struct blk_mq_ctx * * ctxs;
    spinlock_t dispatch_wait_lock;
    wait_queue_entry_t dispatch_wait;
    atomic_t wait_index;
    struct blk_mq_tags * tags;
    struct blk_mq_tags * sched_tags;
    long unsigned int run;
    unsigned int numa_node;
    unsigned int queue_num;
    atomic_t nr_active;
    struct hlist_node cpuhp_online;
    struct hlist_node cpuhp_dead;
    struct kobject kobj;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct list_head hctx_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_hw_ctx {
    spinlock_t lock;
    struct list_head dispatch;
    long unsigned int state;
    struct delayed_work run_work;
    cpumask_var_t cpumask;
    int next_cpu;
    int next_cpu_batch;
    long unsigned int flags;
    void * sched_data;
    struct request_queue * queue;
    struct blk_flush_queue * fq;
    void * driver_data;
    struct sbitmap ctx_map;
    struct blk_mq_ctx * dispatch_from;
    unsigned int dispatch_busy;
    short unsigned int type;
    short unsigned int nr_ctx;
    struct blk_mq_ctx * * ctxs;
    spinlock_t dispatch_wait_lock;
    wait_queue_entry_t dispatch_wait;
    atomic_t wait_index;
    struct blk_mq_tags * tags;
    struct blk_mq_tags * sched_tags;
    unsigned int numa_node;
    unsigned int queue_num;
    atomic_t nr_active;
    struct hlist_node cpuhp_online;
    struct hlist_node cpuhp_dead;
    struct kobject kobj;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct list_head hctx_list;
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
struct blk_mq_hw_ctx {
    spinlock_t lock;
    struct list_head dispatch;
    long unsigned int state;
    struct delayed_work run_work;
    cpumask_var_t cpumask;
    int next_cpu;
    int next_cpu_batch;
    long unsigned int flags;
    void * sched_data;
    struct request_queue * queue;
    struct blk_flush_queue * fq;
    void * driver_data;
    struct sbitmap ctx_map;
    struct blk_mq_ctx * dispatch_from;
    unsigned int dispatch_busy;
    short unsigned int type;
    short unsigned int nr_ctx;
    struct blk_mq_ctx * * ctxs;
    spinlock_t dispatch_wait_lock;
    wait_queue_entry_t dispatch_wait;
    atomic_t wait_index;
    struct blk_mq_tags * tags;
    struct blk_mq_tags * sched_tags;
    long unsigned int queued;
    long unsigned int run;
    long unsigned int[7] dispatched;
    unsigned int numa_node;
    unsigned int queue_num;
    atomic_t nr_active;
    struct hlist_node cpuhp_dead;
    struct kobject kobj;
    long unsigned int poll_considered;
    long unsigned int poll_invoked;
    long unsigned int poll_success;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct list_head hctx_list;
    struct srcu_struct[0] srcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct blk_mq_hw_ctx {
    spinlock_t lock;
    struct list_head dispatch;
    long unsigned int state;
    struct delayed_work run_work;
    cpumask_var_t cpumask;
    int next_cpu;
    int next_cpu_batch;
    long unsigned int flags;
    void * sched_data;
    struct request_queue * queue;
    struct blk_flush_queue * fq;
    void * driver_data;
    struct sbitmap ctx_map;
    struct blk_mq_ctx * dispatch_from;
    unsigned int dispatch_busy;
    short unsigned int type;
    short unsigned int nr_ctx;
    struct blk_mq_ctx * * ctxs;
    spinlock_t dispatch_wait_lock;
    wait_queue_entry_t dispatch_wait;
    atomic_t wait_index;
    struct blk_mq_tags * tags;
    struct blk_mq_tags * sched_tags;
    long unsigned int queued;
    long unsigned int run;
    long unsigned int[7] dispatched;
    unsigned int numa_node;
    unsigned int queue_num;
    atomic_t nr_active;
    struct hlist_node cpuhp_dead;
    struct kobject kobj;
    long unsigned int poll_considered;
    long unsigned int poll_invoked;
    long unsigned int poll_success;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct list_head hctx_list;
    struct srcu_struct[0] srcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct blk_mq_hw_ctx {
    spinlock_t lock;
    struct list_head dispatch;
    long unsigned int state;
    struct delayed_work run_work;
    cpumask_var_t cpumask;
    int next_cpu;
    int next_cpu_batch;
    long unsigned int flags;
    void * sched_data;
    struct request_queue * queue;
    struct blk_flush_queue * fq;
    void * driver_data;
    struct sbitmap ctx_map;
    struct blk_mq_ctx * dispatch_from;
    unsigned int dispatch_busy;
    short unsigned int type;
    short unsigned int nr_ctx;
    struct blk_mq_ctx * * ctxs;
    spinlock_t dispatch_wait_lock;
    wait_queue_entry_t dispatch_wait;
    atomic_t wait_index;
    struct blk_mq_tags * tags;
    struct blk_mq_tags * sched_tags;
    long unsigned int queued;
    long unsigned int run;
    long unsigned int[7] dispatched;
    unsigned int numa_node;
    unsigned int queue_num;
    atomic_t nr_active;
    struct hlist_node cpuhp_dead;
    struct kobject kobj;
    long unsigned int poll_considered;
    long unsigned int poll_invoked;
    long unsigned int poll_success;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct list_head hctx_list;
    struct srcu_struct[0] srcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct blk_mq_hw_ctx {
    spinlock_t lock;
    struct list_head dispatch;
    long unsigned int state;
    struct delayed_work run_work;
    cpumask_var_t cpumask;
    int next_cpu;
    int next_cpu_batch;
    long unsigned int flags;
    void * sched_data;
    struct request_queue * queue;
    struct blk_flush_queue * fq;
    void * driver_data;
    struct sbitmap ctx_map;
    struct blk_mq_ctx * dispatch_from;
    unsigned int dispatch_busy;
    short unsigned int type;
    short unsigned int nr_ctx;
    struct blk_mq_ctx * * ctxs;
    spinlock_t dispatch_wait_lock;
    wait_queue_entry_t dispatch_wait;
    atomic_t wait_index;
    struct blk_mq_tags * tags;
    struct blk_mq_tags * sched_tags;
    long unsigned int queued;
    long unsigned int run;
    long unsigned int[7] dispatched;
    unsigned int numa_node;
    unsigned int queue_num;
    atomic_t nr_active;
    struct hlist_node cpuhp_dead;
    struct kobject kobj;
    long unsigned int poll_considered;
    long unsigned int poll_invoked;
    long unsigned int poll_success;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct list_head hctx_list;
    struct srcu_struct[0] srcu;
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
struct blk_mq_hw_ctx {
    spinlock_t lock;
    struct list_head dispatch;
    long unsigned int state;
    struct delayed_work run_work;
    cpumask_var_t cpumask;
    int next_cpu;
    int next_cpu_batch;
    long unsigned int flags;
    void * sched_data;
    struct request_queue * queue;
    struct blk_flush_queue * fq;
    void * driver_data;
    struct sbitmap ctx_map;
    struct blk_mq_ctx * dispatch_from;
    unsigned int dispatch_busy;
    short unsigned int type;
    short unsigned int nr_ctx;
    struct blk_mq_ctx * * ctxs;
    spinlock_t dispatch_wait_lock;
    wait_queue_entry_t dispatch_wait;
    atomic_t wait_index;
    struct blk_mq_tags * tags;
    struct blk_mq_tags * sched_tags;
    long unsigned int queued;
    long unsigned int run;
    long unsigned int[7] dispatched;
    unsigned int numa_node;
    unsigned int queue_num;
    atomic_t nr_active;
    struct hlist_node cpuhp_dead;
    struct kobject kobj;
    long unsigned int poll_considered;
    long unsigned int poll_invoked;
    long unsigned int poll_success;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct list_head hctx_list;
    struct srcu_struct[0] srcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct blk_mq_hw_ctx {
    spinlock_t lock;
    struct list_head dispatch;
    long unsigned int state;
    struct delayed_work run_work;
    cpumask_var_t cpumask;
    int next_cpu;
    int next_cpu_batch;
    long unsigned int flags;
    void * sched_data;
    struct request_queue * queue;
    struct blk_flush_queue * fq;
    void * driver_data;
    struct sbitmap ctx_map;
    struct blk_mq_ctx * dispatch_from;
    unsigned int dispatch_busy;
    short unsigned int type;
    short unsigned int nr_ctx;
    struct blk_mq_ctx * * ctxs;
    spinlock_t dispatch_wait_lock;
    wait_queue_entry_t dispatch_wait;
    atomic_t wait_index;
    struct blk_mq_tags * tags;
    struct blk_mq_tags * sched_tags;
    long unsigned int queued;
    long unsigned int run;
    long unsigned int[7] dispatched;
    unsigned int numa_node;
    unsigned int queue_num;
    atomic_t nr_active;
    struct hlist_node cpuhp_dead;
    struct kobject kobj;
    long unsigned int poll_considered;
    long unsigned int poll_invoked;
    long unsigned int poll_success;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct list_head hctx_list;
    struct srcu_struct[0] srcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct blk_mq_hw_ctx {
    spinlock_t lock;
    struct list_head dispatch;
    long unsigned int state;
    struct delayed_work run_work;
    cpumask_var_t cpumask;
    int next_cpu;
    int next_cpu_batch;
    long unsigned int flags;
    void * sched_data;
    struct request_queue * queue;
    struct blk_flush_queue * fq;
    void * driver_data;
    struct sbitmap ctx_map;
    struct blk_mq_ctx * dispatch_from;
    unsigned int dispatch_busy;
    short unsigned int type;
    short unsigned int nr_ctx;
    struct blk_mq_ctx * * ctxs;
    spinlock_t dispatch_wait_lock;
    wait_queue_entry_t dispatch_wait;
    atomic_t wait_index;
    struct blk_mq_tags * tags;
    struct blk_mq_tags * sched_tags;
    long unsigned int queued;
    long unsigned int run;
    long unsigned int[7] dispatched;
    unsigned int numa_node;
    unsigned int queue_num;
    atomic_t nr_active;
    struct hlist_node cpuhp_dead;
    struct kobject kobj;
    long unsigned int poll_considered;
    long unsigned int poll_invoked;
    long unsigned int poll_success;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct list_head hctx_list;
    struct srcu_struct[0] srcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct blk_mq_hw_ctx {
    spinlock_t lock;
    struct list_head dispatch;
    long unsigned int state;
    struct delayed_work run_work;
    cpumask_var_t cpumask;
    int next_cpu;
    int next_cpu_batch;
    long unsigned int flags;
    void * sched_data;
    struct request_queue * queue;
    struct blk_flush_queue * fq;
    void * driver_data;
    struct sbitmap ctx_map;
    struct blk_mq_ctx * dispatch_from;
    unsigned int dispatch_busy;
    short unsigned int type;
    short unsigned int nr_ctx;
    struct blk_mq_ctx * * ctxs;
    spinlock_t dispatch_wait_lock;
    wait_queue_entry_t dispatch_wait;
    atomic_t wait_index;
    struct blk_mq_tags * tags;
    struct blk_mq_tags * sched_tags;
    long unsigned int queued;
    long unsigned int run;
    long unsigned int[7] dispatched;
    unsigned int numa_node;
    unsigned int queue_num;
    atomic_t nr_active;
    struct hlist_node cpuhp_dead;
    struct kobject kobj;
    long unsigned int poll_considered;
    long unsigned int poll_invoked;
    long unsigned int poll_success;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct list_head hctx_list;
    struct srcu_struct[0] srcu;
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
<code>struct srcu_struct queue_rq_srcu</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_node cpuhp_dead</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int poll_considered</code>
</li>
<li>
<b>Field removed. </b>
<code>struct blk_mq_cpu_notifier cpu_notifier</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct delayed_work run_work</code> ➡️ <code>struct work_struct run_work</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct blk_mq_ctxmap ctx_map</code> ➡️ <code>struct sbitmap ctx_map</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int[10] dispatched</code> ➡️ <code>long unsigned int[7] dispatched</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void * sched_data</code>
</li>
<li>
<b>Field added. </b>
<code>wait_queue_entry_t dispatch_wait</code>
</li>
<li>
<b>Field added. </b>
<code>struct blk_mq_tags * sched_tags</code>
</li>
<li>
<b>Field added. </b>
<code>struct dentry * debugfs_dir</code>
</li>
<li>
<b>Field added. </b>
<code>struct dentry * sched_debugfs_dir</code>
</li>
<li>
<b>Field removed. </b>
<code>struct delayed_work delay_work</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct work_struct run_work</code> ➡️ <code>struct delayed_work run_work</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct srcu_struct queue_rq_srcu</code> ➡️ <code>struct srcu_struct[0] queue_rq_srcu</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct blk_mq_ctx * dispatch_from</code>
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
<code>unsigned int nr_expired</code>
</li>
<li>
<b>Field added. </b>
<code>struct srcu_struct[0] srcu</code>
</li>
<li>
<b>Field removed. </b>
<code>struct srcu_struct[0] queue_rq_srcu</code>
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
<code>unsigned int dispatch_busy</code>
</li>
<li>
<b>Field added. </b>
<code>short unsigned int type</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t dispatch_wait_lock</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int nr_ctx</code> ➡️ <code>short unsigned int nr_ctx</code>
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
<code>struct list_head hctx_list</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int nr_expired</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct hlist_node cpuhp_online</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>atomic_t elevator_queued</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>atomic_t elevator_queued</code>
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
<code>long unsigned int[7] dispatched</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int poll_considered</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int poll_invoked</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int poll_success</code>
</li>
<li>
<b>Field removed. </b>
<code>struct srcu_struct[0] srcu</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>long unsigned int queued</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>long unsigned int run</code>
</li>
</ul>
</details>
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
