# Struct: <code>request_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct request_queue {
    struct list_head queue_head;
    struct request * last_merge;
    struct elevator_queue * elevator;
    int[2] nr_rqs;
    int nr_rqs_elvpriv;
    struct request_list root_rl;
    request_fn_proc * request_fn;
    make_request_fn * make_request_fn;
    prep_rq_fn * prep_rq_fn;
    unprep_rq_fn * unprep_rq_fn;
    softirq_done_fn * softirq_done_fn;
    rq_timed_out_fn * rq_timed_out_fn;
    dma_drain_needed_fn * dma_drain_needed;
    lld_busy_fn * lld_busy_fn;
    struct blk_mq_ops * mq_ops;
    unsigned int * mq_map;
    struct blk_mq_ctx * queue_ctx;
    unsigned int nr_queues;
    struct blk_mq_hw_ctx * * queue_hw_ctx;
    unsigned int nr_hw_queues;
    sector_t end_sector;
    struct request * boundary_rq;
    struct delayed_work delay_work;
    struct backing_dev_info backing_dev_info;
    void * queuedata;
    long unsigned int queue_flags;
    int id;
    gfp_t bounce_gfp;
    spinlock_t __queue_lock;
    spinlock_t * queue_lock;
    struct kobject kobj;
    struct kobject mq_kobj;
    struct blk_integrity integrity;
    struct device * dev;
    int rpm_status;
    unsigned int nr_pending;
    long unsigned int nr_requests;
    unsigned int nr_congestion_on;
    unsigned int nr_congestion_off;
    unsigned int nr_batching;
    unsigned int dma_drain_size;
    void * dma_drain_buffer;
    unsigned int dma_pad_mask;
    unsigned int dma_alignment;
    struct blk_queue_tag * queue_tags;
    struct list_head tag_busy_list;
    unsigned int nr_sorted;
    unsigned int[2] in_flight;
    unsigned int request_fn_active;
    unsigned int rq_timeout;
    struct timer_list timeout;
    struct list_head timeout_list;
    struct list_head icq_list;
    long unsigned int[1] blkcg_pols;
    struct blkcg_gq * root_blkg;
    struct list_head blkg_list;
    struct queue_limits limits;
    unsigned int sg_timeout;
    unsigned int sg_reserved_size;
    int node;
    struct blk_trace * blk_trace;
    unsigned int flush_flags;
    unsigned int flush_not_queueable;
    struct blk_flush_queue * fq;
    struct list_head requeue_list;
    spinlock_t requeue_lock;
    struct work_struct requeue_work;
    struct mutex sysfs_lock;
    int bypass_depth;
    atomic_t mq_freeze_depth;
    bsg_job_fn * bsg_job_fn;
    int bsg_job_size;
    struct bsg_class_device bsg_dev;
    struct throtl_data * td;
    struct callback_head callback_head;
    wait_queue_head_t mq_freeze_wq;
    struct percpu_ref q_usage_counter;
    struct list_head all_q_node;
    struct blk_mq_tag_set * tag_set;
    struct list_head tag_set_list;
    struct bio_set * bio_split;
    bool mq_sysfs_init_done;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct request_queue {
    struct list_head queue_head;
    struct request * last_merge;
    struct elevator_queue * elevator;
    int[2] nr_rqs;
    int nr_rqs_elvpriv;
    struct request_list root_rl;
    request_fn_proc * request_fn;
    make_request_fn * make_request_fn;
    prep_rq_fn * prep_rq_fn;
    unprep_rq_fn * unprep_rq_fn;
    softirq_done_fn * softirq_done_fn;
    rq_timed_out_fn * rq_timed_out_fn;
    dma_drain_needed_fn * dma_drain_needed;
    lld_busy_fn * lld_busy_fn;
    struct blk_mq_ops * mq_ops;
    unsigned int * mq_map;
    struct blk_mq_ctx * queue_ctx;
    unsigned int nr_queues;
    struct blk_mq_hw_ctx * * queue_hw_ctx;
    unsigned int nr_hw_queues;
    sector_t end_sector;
    struct request * boundary_rq;
    struct delayed_work delay_work;
    struct backing_dev_info backing_dev_info;
    void * queuedata;
    long unsigned int queue_flags;
    int id;
    gfp_t bounce_gfp;
    spinlock_t __queue_lock;
    spinlock_t * queue_lock;
    struct kobject kobj;
    struct kobject mq_kobj;
    struct blk_integrity integrity;
    struct device * dev;
    int rpm_status;
    unsigned int nr_pending;
    long unsigned int nr_requests;
    unsigned int nr_congestion_on;
    unsigned int nr_congestion_off;
    unsigned int nr_batching;
    unsigned int dma_drain_size;
    void * dma_drain_buffer;
    unsigned int dma_pad_mask;
    unsigned int dma_alignment;
    struct blk_queue_tag * queue_tags;
    struct list_head tag_busy_list;
    unsigned int nr_sorted;
    unsigned int[2] in_flight;
    unsigned int request_fn_active;
    unsigned int rq_timeout;
    struct timer_list timeout;
    struct work_struct timeout_work;
    struct list_head timeout_list;
    struct list_head icq_list;
    long unsigned int[1] blkcg_pols;
    struct blkcg_gq * root_blkg;
    struct list_head blkg_list;
    struct queue_limits limits;
    unsigned int sg_timeout;
    unsigned int sg_reserved_size;
    int node;
    struct blk_trace * blk_trace;
    struct blk_flush_queue * fq;
    struct list_head requeue_list;
    spinlock_t requeue_lock;
    struct work_struct requeue_work;
    struct mutex sysfs_lock;
    int bypass_depth;
    atomic_t mq_freeze_depth;
    bsg_job_fn * bsg_job_fn;
    int bsg_job_size;
    struct bsg_class_device bsg_dev;
    struct throtl_data * td;
    struct callback_head callback_head;
    wait_queue_head_t mq_freeze_wq;
    struct percpu_ref q_usage_counter;
    struct list_head all_q_node;
    struct blk_mq_tag_set * tag_set;
    struct list_head tag_set_list;
    struct bio_set * bio_split;
    bool mq_sysfs_init_done;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct request_queue {
    struct list_head queue_head;
    struct request * last_merge;
    struct elevator_queue * elevator;
    int[2] nr_rqs;
    int nr_rqs_elvpriv;
    struct rq_wb * rq_wb;
    struct request_list root_rl;
    request_fn_proc * request_fn;
    make_request_fn * make_request_fn;
    prep_rq_fn * prep_rq_fn;
    unprep_rq_fn * unprep_rq_fn;
    softirq_done_fn * softirq_done_fn;
    rq_timed_out_fn * rq_timed_out_fn;
    dma_drain_needed_fn * dma_drain_needed;
    lld_busy_fn * lld_busy_fn;
    struct blk_mq_ops * mq_ops;
    unsigned int * mq_map;
    struct blk_mq_ctx * queue_ctx;
    unsigned int nr_queues;
    unsigned int queue_depth;
    struct blk_mq_hw_ctx * * queue_hw_ctx;
    unsigned int nr_hw_queues;
    sector_t end_sector;
    struct request * boundary_rq;
    struct delayed_work delay_work;
    struct backing_dev_info backing_dev_info;
    void * queuedata;
    long unsigned int queue_flags;
    int id;
    gfp_t bounce_gfp;
    spinlock_t __queue_lock;
    spinlock_t * queue_lock;
    struct kobject kobj;
    struct kobject mq_kobj;
    struct blk_integrity integrity;
    struct device * dev;
    int rpm_status;
    unsigned int nr_pending;
    long unsigned int nr_requests;
    unsigned int nr_congestion_on;
    unsigned int nr_congestion_off;
    unsigned int nr_batching;
    unsigned int dma_drain_size;
    void * dma_drain_buffer;
    unsigned int dma_pad_mask;
    unsigned int dma_alignment;
    struct blk_queue_tag * queue_tags;
    struct list_head tag_busy_list;
    unsigned int nr_sorted;
    unsigned int[2] in_flight;
    struct blk_rq_stat[2] rq_stats;
    unsigned int request_fn_active;
    unsigned int rq_timeout;
    int poll_nsec;
    struct timer_list timeout;
    struct work_struct timeout_work;
    struct list_head timeout_list;
    struct list_head icq_list;
    long unsigned int[1] blkcg_pols;
    struct blkcg_gq * root_blkg;
    struct list_head blkg_list;
    struct queue_limits limits;
    unsigned int sg_timeout;
    unsigned int sg_reserved_size;
    int node;
    struct blk_trace * blk_trace;
    struct blk_flush_queue * fq;
    struct list_head requeue_list;
    spinlock_t requeue_lock;
    struct delayed_work requeue_work;
    struct mutex sysfs_lock;
    int bypass_depth;
    atomic_t mq_freeze_depth;
    bsg_job_fn * bsg_job_fn;
    int bsg_job_size;
    struct bsg_class_device bsg_dev;
    struct throtl_data * td;
    struct callback_head callback_head;
    wait_queue_head_t mq_freeze_wq;
    struct percpu_ref q_usage_counter;
    struct list_head all_q_node;
    struct blk_mq_tag_set * tag_set;
    struct list_head tag_set_list;
    struct bio_set * bio_split;
    bool mq_sysfs_init_done;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct request_queue {
    struct list_head queue_head;
    struct request * last_merge;
    struct elevator_queue * elevator;
    int[2] nr_rqs;
    int nr_rqs_elvpriv;
    atomic_t shared_hctx_restart;
    struct blk_queue_stats * stats;
    struct rq_wb * rq_wb;
    struct request_list root_rl;
    request_fn_proc * request_fn;
    make_request_fn * make_request_fn;
    prep_rq_fn * prep_rq_fn;
    unprep_rq_fn * unprep_rq_fn;
    softirq_done_fn * softirq_done_fn;
    rq_timed_out_fn * rq_timed_out_fn;
    dma_drain_needed_fn * dma_drain_needed;
    lld_busy_fn * lld_busy_fn;
    init_rq_fn * init_rq_fn;
    exit_rq_fn * exit_rq_fn;
    void (*)(struct request *) initialize_rq_fn;
    const struct blk_mq_ops * mq_ops;
    unsigned int * mq_map;
    struct blk_mq_ctx * queue_ctx;
    unsigned int nr_queues;
    unsigned int queue_depth;
    struct blk_mq_hw_ctx * * queue_hw_ctx;
    unsigned int nr_hw_queues;
    sector_t end_sector;
    struct request * boundary_rq;
    struct delayed_work delay_work;
    struct backing_dev_info * backing_dev_info;
    void * queuedata;
    long unsigned int queue_flags;
    int id;
    gfp_t bounce_gfp;
    spinlock_t __queue_lock;
    spinlock_t * queue_lock;
    struct kobject kobj;
    struct kobject mq_kobj;
    struct blk_integrity integrity;
    struct device * dev;
    int rpm_status;
    unsigned int nr_pending;
    long unsigned int nr_requests;
    unsigned int nr_congestion_on;
    unsigned int nr_congestion_off;
    unsigned int nr_batching;
    unsigned int dma_drain_size;
    void * dma_drain_buffer;
    unsigned int dma_pad_mask;
    unsigned int dma_alignment;
    struct blk_queue_tag * queue_tags;
    struct list_head tag_busy_list;
    unsigned int nr_sorted;
    unsigned int[2] in_flight;
    unsigned int request_fn_active;
    unsigned int rq_timeout;
    int poll_nsec;
    struct blk_stat_callback * poll_cb;
    struct blk_rq_stat[16] poll_stat;
    struct timer_list timeout;
    struct work_struct timeout_work;
    struct list_head timeout_list;
    struct list_head icq_list;
    long unsigned int[1] blkcg_pols;
    struct blkcg_gq * root_blkg;
    struct list_head blkg_list;
    struct queue_limits limits;
    unsigned int sg_timeout;
    unsigned int sg_reserved_size;
    int node;
    struct blk_trace * blk_trace;
    struct blk_flush_queue * fq;
    struct list_head requeue_list;
    spinlock_t requeue_lock;
    struct delayed_work requeue_work;
    struct mutex sysfs_lock;
    int bypass_depth;
    atomic_t mq_freeze_depth;
    bsg_job_fn * bsg_job_fn;
    struct bsg_class_device bsg_dev;
    struct throtl_data * td;
    struct callback_head callback_head;
    wait_queue_head_t mq_freeze_wq;
    struct percpu_ref q_usage_counter;
    struct list_head all_q_node;
    struct blk_mq_tag_set * tag_set;
    struct list_head tag_set_list;
    struct bio_set * bio_split;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    bool mq_sysfs_init_done;
    size_t cmd_size;
    void * rq_alloc_data;
    struct work_struct release_work;
    u64[5] write_hints;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct request_queue {
    struct list_head queue_head;
    struct request * last_merge;
    struct elevator_queue * elevator;
    int[2] nr_rqs;
    int nr_rqs_elvpriv;
    atomic_t shared_hctx_restart;
    struct blk_queue_stats * stats;
    struct rq_wb * rq_wb;
    struct request_list root_rl;
    request_fn_proc * request_fn;
    make_request_fn * make_request_fn;
    poll_q_fn * poll_fn;
    prep_rq_fn * prep_rq_fn;
    unprep_rq_fn * unprep_rq_fn;
    softirq_done_fn * softirq_done_fn;
    rq_timed_out_fn * rq_timed_out_fn;
    dma_drain_needed_fn * dma_drain_needed;
    lld_busy_fn * lld_busy_fn;
    init_rq_fn * init_rq_fn;
    exit_rq_fn * exit_rq_fn;
    void (*)(struct request *) initialize_rq_fn;
    const struct blk_mq_ops * mq_ops;
    unsigned int * mq_map;
    struct blk_mq_ctx * queue_ctx;
    unsigned int nr_queues;
    unsigned int queue_depth;
    struct blk_mq_hw_ctx * * queue_hw_ctx;
    unsigned int nr_hw_queues;
    sector_t end_sector;
    struct request * boundary_rq;
    struct delayed_work delay_work;
    struct backing_dev_info * backing_dev_info;
    void * queuedata;
    long unsigned int queue_flags;
    int id;
    gfp_t bounce_gfp;
    spinlock_t __queue_lock;
    spinlock_t * queue_lock;
    struct kobject kobj;
    struct kobject mq_kobj;
    struct blk_integrity integrity;
    struct device * dev;
    int rpm_status;
    unsigned int nr_pending;
    long unsigned int nr_requests;
    unsigned int nr_congestion_on;
    unsigned int nr_congestion_off;
    unsigned int nr_batching;
    unsigned int dma_drain_size;
    void * dma_drain_buffer;
    unsigned int dma_pad_mask;
    unsigned int dma_alignment;
    struct blk_queue_tag * queue_tags;
    struct list_head tag_busy_list;
    unsigned int nr_sorted;
    unsigned int[2] in_flight;
    unsigned int request_fn_active;
    unsigned int rq_timeout;
    int poll_nsec;
    struct blk_stat_callback * poll_cb;
    struct blk_rq_stat[16] poll_stat;
    struct timer_list timeout;
    struct work_struct timeout_work;
    struct list_head timeout_list;
    struct list_head icq_list;
    long unsigned int[1] blkcg_pols;
    struct blkcg_gq * root_blkg;
    struct list_head blkg_list;
    struct queue_limits limits;
    unsigned int sg_timeout;
    unsigned int sg_reserved_size;
    int node;
    struct blk_trace * blk_trace;
    struct mutex blk_trace_mutex;
    struct blk_flush_queue * fq;
    struct list_head requeue_list;
    spinlock_t requeue_lock;
    struct delayed_work requeue_work;
    struct mutex sysfs_lock;
    int bypass_depth;
    atomic_t mq_freeze_depth;
    bsg_job_fn * bsg_job_fn;
    struct bsg_class_device bsg_dev;
    struct throtl_data * td;
    struct callback_head callback_head;
    wait_queue_head_t mq_freeze_wq;
    struct percpu_ref q_usage_counter;
    struct list_head all_q_node;
    struct blk_mq_tag_set * tag_set;
    struct list_head tag_set_list;
    struct bio_set * bio_split;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    bool mq_sysfs_init_done;
    size_t cmd_size;
    void * rq_alloc_data;
    struct work_struct release_work;
    u64[5] write_hints;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct request_queue {
    struct list_head queue_head;
    struct request * last_merge;
    struct elevator_queue * elevator;
    int[2] nr_rqs;
    int nr_rqs_elvpriv;
    atomic_t shared_hctx_restart;
    struct blk_queue_stats * stats;
    struct rq_wb * rq_wb;
    struct request_list root_rl;
    request_fn_proc * request_fn;
    make_request_fn * make_request_fn;
    poll_q_fn * poll_fn;
    prep_rq_fn * prep_rq_fn;
    unprep_rq_fn * unprep_rq_fn;
    softirq_done_fn * softirq_done_fn;
    rq_timed_out_fn * rq_timed_out_fn;
    dma_drain_needed_fn * dma_drain_needed;
    lld_busy_fn * lld_busy_fn;
    init_rq_fn * init_rq_fn;
    exit_rq_fn * exit_rq_fn;
    void (*)(struct request *) initialize_rq_fn;
    const struct blk_mq_ops * mq_ops;
    unsigned int * mq_map;
    struct blk_mq_ctx * queue_ctx;
    unsigned int nr_queues;
    unsigned int queue_depth;
    struct blk_mq_hw_ctx * * queue_hw_ctx;
    unsigned int nr_hw_queues;
    sector_t end_sector;
    struct request * boundary_rq;
    struct delayed_work delay_work;
    struct backing_dev_info * backing_dev_info;
    void * queuedata;
    long unsigned int queue_flags;
    int id;
    gfp_t bounce_gfp;
    spinlock_t __queue_lock;
    spinlock_t * queue_lock;
    struct kobject kobj;
    struct kobject mq_kobj;
    struct blk_integrity integrity;
    struct device * dev;
    int rpm_status;
    unsigned int nr_pending;
    long unsigned int nr_requests;
    unsigned int nr_congestion_on;
    unsigned int nr_congestion_off;
    unsigned int nr_batching;
    unsigned int dma_drain_size;
    void * dma_drain_buffer;
    unsigned int dma_pad_mask;
    unsigned int dma_alignment;
    struct blk_queue_tag * queue_tags;
    unsigned int nr_sorted;
    unsigned int[2] in_flight;
    unsigned int request_fn_active;
    unsigned int rq_timeout;
    int poll_nsec;
    struct blk_stat_callback * poll_cb;
    struct blk_rq_stat[16] poll_stat;
    struct timer_list timeout;
    struct work_struct timeout_work;
    struct list_head timeout_list;
    struct list_head icq_list;
    long unsigned int[1] blkcg_pols;
    struct blkcg_gq * root_blkg;
    struct list_head blkg_list;
    struct queue_limits limits;
    unsigned int nr_zones;
    long unsigned int * seq_zones_bitmap;
    long unsigned int * seq_zones_wlock;
    unsigned int sg_timeout;
    unsigned int sg_reserved_size;
    int node;
    struct blk_trace * blk_trace;
    struct mutex blk_trace_mutex;
    struct blk_flush_queue * fq;
    struct list_head requeue_list;
    spinlock_t requeue_lock;
    struct delayed_work requeue_work;
    struct mutex sysfs_lock;
    int bypass_depth;
    atomic_t mq_freeze_depth;
    bsg_job_fn * bsg_job_fn;
    struct bsg_class_device bsg_dev;
    struct throtl_data * td;
    struct callback_head callback_head;
    wait_queue_head_t mq_freeze_wq;
    struct percpu_ref q_usage_counter;
    struct list_head all_q_node;
    struct blk_mq_tag_set * tag_set;
    struct list_head tag_set_list;
    struct bio_set bio_split;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    bool mq_sysfs_init_done;
    size_t cmd_size;
    void * rq_alloc_data;
    struct work_struct release_work;
    u64[5] write_hints;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct request_queue {
    struct list_head queue_head;
    struct request * last_merge;
    struct elevator_queue * elevator;
    struct blk_queue_stats * stats;
    struct rq_qos * rq_qos;
    make_request_fn * make_request_fn;
    dma_drain_needed_fn * dma_drain_needed;
    const struct blk_mq_ops * mq_ops;
    struct blk_mq_ctx * queue_ctx;
    unsigned int nr_queues;
    unsigned int queue_depth;
    struct blk_mq_hw_ctx * * queue_hw_ctx;
    unsigned int nr_hw_queues;
    struct backing_dev_info * backing_dev_info;
    void * queuedata;
    long unsigned int queue_flags;
    atomic_t pm_only;
    int id;
    gfp_t bounce_gfp;
    spinlock_t queue_lock;
    struct kobject kobj;
    struct kobject * mq_kobj;
    struct blk_integrity integrity;
    struct device * dev;
    int rpm_status;
    unsigned int nr_pending;
    long unsigned int nr_requests;
    unsigned int dma_drain_size;
    void * dma_drain_buffer;
    unsigned int dma_pad_mask;
    unsigned int dma_alignment;
    unsigned int rq_timeout;
    int poll_nsec;
    struct blk_stat_callback * poll_cb;
    struct blk_rq_stat[16] poll_stat;
    struct timer_list timeout;
    struct work_struct timeout_work;
    struct list_head icq_list;
    long unsigned int[1] blkcg_pols;
    struct blkcg_gq * root_blkg;
    struct list_head blkg_list;
    struct queue_limits limits;
    unsigned int nr_zones;
    long unsigned int * seq_zones_bitmap;
    long unsigned int * seq_zones_wlock;
    unsigned int sg_timeout;
    unsigned int sg_reserved_size;
    int node;
    struct blk_trace * blk_trace;
    struct mutex blk_trace_mutex;
    struct blk_flush_queue * fq;
    struct list_head requeue_list;
    spinlock_t requeue_lock;
    struct delayed_work requeue_work;
    struct mutex sysfs_lock;
    atomic_t mq_freeze_depth;
    struct bsg_class_device bsg_dev;
    struct throtl_data * td;
    struct callback_head callback_head;
    wait_queue_head_t mq_freeze_wq;
    struct percpu_ref q_usage_counter;
    struct list_head all_q_node;
    struct blk_mq_tag_set * tag_set;
    struct list_head tag_set_list;
    struct bio_set bio_split;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct dentry * rqos_debugfs_dir;
    bool mq_sysfs_init_done;
    size_t cmd_size;
    struct work_struct release_work;
    u64[5] write_hints;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct request_queue {
    struct list_head queue_head;
    struct request * last_merge;
    struct elevator_queue * elevator;
    struct blk_queue_stats * stats;
    struct rq_qos * rq_qos;
    make_request_fn * make_request_fn;
    dma_drain_needed_fn * dma_drain_needed;
    const struct blk_mq_ops * mq_ops;
    struct blk_mq_ctx * queue_ctx;
    unsigned int nr_queues;
    unsigned int queue_depth;
    struct blk_mq_hw_ctx * * queue_hw_ctx;
    unsigned int nr_hw_queues;
    struct backing_dev_info * backing_dev_info;
    void * queuedata;
    long unsigned int queue_flags;
    atomic_t pm_only;
    int id;
    gfp_t bounce_gfp;
    spinlock_t queue_lock;
    struct kobject kobj;
    struct kobject * mq_kobj;
    struct blk_integrity integrity;
    struct device * dev;
    int rpm_status;
    unsigned int nr_pending;
    long unsigned int nr_requests;
    unsigned int dma_drain_size;
    void * dma_drain_buffer;
    unsigned int dma_pad_mask;
    unsigned int dma_alignment;
    unsigned int rq_timeout;
    int poll_nsec;
    struct blk_stat_callback * poll_cb;
    struct blk_rq_stat[16] poll_stat;
    struct timer_list timeout;
    struct work_struct timeout_work;
    struct list_head icq_list;
    long unsigned int[1] blkcg_pols;
    struct blkcg_gq * root_blkg;
    struct list_head blkg_list;
    struct queue_limits limits;
    unsigned int nr_zones;
    long unsigned int * seq_zones_bitmap;
    long unsigned int * seq_zones_wlock;
    unsigned int sg_timeout;
    unsigned int sg_reserved_size;
    int node;
    struct blk_trace * blk_trace;
    struct mutex blk_trace_mutex;
    struct blk_flush_queue * fq;
    struct list_head requeue_list;
    spinlock_t requeue_lock;
    struct delayed_work requeue_work;
    struct mutex sysfs_lock;
    struct list_head unused_hctx_list;
    spinlock_t unused_hctx_lock;
    int mq_freeze_depth;
    struct bsg_class_device bsg_dev;
    struct throtl_data * td;
    struct callback_head callback_head;
    wait_queue_head_t mq_freeze_wq;
    struct mutex mq_freeze_lock;
    struct percpu_ref q_usage_counter;
    struct blk_mq_tag_set * tag_set;
    struct list_head tag_set_list;
    struct bio_set bio_split;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct dentry * rqos_debugfs_dir;
    bool mq_sysfs_init_done;
    size_t cmd_size;
    struct work_struct release_work;
    u64[5] write_hints;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct request_queue {
    struct request * last_merge;
    struct elevator_queue * elevator;
    struct blk_queue_stats * stats;
    struct rq_qos * rq_qos;
    make_request_fn * make_request_fn;
    dma_drain_needed_fn * dma_drain_needed;
    const struct blk_mq_ops * mq_ops;
    struct blk_mq_ctx * queue_ctx;
    unsigned int nr_queues;
    unsigned int queue_depth;
    struct blk_mq_hw_ctx * * queue_hw_ctx;
    unsigned int nr_hw_queues;
    struct backing_dev_info * backing_dev_info;
    void * queuedata;
    long unsigned int queue_flags;
    atomic_t pm_only;
    int id;
    gfp_t bounce_gfp;
    spinlock_t queue_lock;
    struct kobject kobj;
    struct kobject * mq_kobj;
    struct blk_integrity integrity;
    struct device * dev;
    int rpm_status;
    unsigned int nr_pending;
    long unsigned int nr_requests;
    unsigned int dma_drain_size;
    void * dma_drain_buffer;
    unsigned int dma_pad_mask;
    unsigned int dma_alignment;
    unsigned int rq_timeout;
    int poll_nsec;
    struct blk_stat_callback * poll_cb;
    struct blk_rq_stat[16] poll_stat;
    struct timer_list timeout;
    struct work_struct timeout_work;
    struct list_head icq_list;
    long unsigned int[1] blkcg_pols;
    struct blkcg_gq * root_blkg;
    struct list_head blkg_list;
    struct queue_limits limits;
    unsigned int required_elevator_features;
    unsigned int nr_zones;
    long unsigned int * seq_zones_bitmap;
    long unsigned int * seq_zones_wlock;
    unsigned int sg_timeout;
    unsigned int sg_reserved_size;
    int node;
    struct blk_trace * blk_trace;
    struct mutex blk_trace_mutex;
    struct blk_flush_queue * fq;
    struct list_head requeue_list;
    spinlock_t requeue_lock;
    struct delayed_work requeue_work;
    struct mutex sysfs_lock;
    struct mutex sysfs_dir_lock;
    struct list_head unused_hctx_list;
    spinlock_t unused_hctx_lock;
    int mq_freeze_depth;
    struct bsg_class_device bsg_dev;
    struct throtl_data * td;
    struct callback_head callback_head;
    wait_queue_head_t mq_freeze_wq;
    struct mutex mq_freeze_lock;
    struct percpu_ref q_usage_counter;
    struct blk_mq_tag_set * tag_set;
    struct list_head tag_set_list;
    struct bio_set bio_split;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct dentry * rqos_debugfs_dir;
    bool mq_sysfs_init_done;
    size_t cmd_size;
    struct work_struct release_work;
    u64[5] write_hints;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct request_queue {
    struct request * last_merge;
    struct elevator_queue * elevator;
    struct blk_queue_stats * stats;
    struct rq_qos * rq_qos;
    make_request_fn * make_request_fn;
    const struct blk_mq_ops * mq_ops;
    struct blk_mq_ctx * queue_ctx;
    unsigned int queue_depth;
    struct blk_mq_hw_ctx * * queue_hw_ctx;
    unsigned int nr_hw_queues;
    struct backing_dev_info * backing_dev_info;
    void * queuedata;
    long unsigned int queue_flags;
    atomic_t pm_only;
    int id;
    gfp_t bounce_gfp;
    spinlock_t queue_lock;
    struct kobject kobj;
    struct kobject * mq_kobj;
    struct blk_integrity integrity;
    struct device * dev;
    int rpm_status;
    unsigned int nr_pending;
    long unsigned int nr_requests;
    unsigned int dma_pad_mask;
    unsigned int dma_alignment;
    struct blk_keyslot_manager * ksm;
    unsigned int rq_timeout;
    int poll_nsec;
    struct blk_stat_callback * poll_cb;
    struct blk_rq_stat[16] poll_stat;
    struct timer_list timeout;
    struct work_struct timeout_work;
    struct list_head icq_list;
    long unsigned int[1] blkcg_pols;
    struct blkcg_gq * root_blkg;
    struct list_head blkg_list;
    struct queue_limits limits;
    unsigned int required_elevator_features;
    unsigned int nr_zones;
    long unsigned int * conv_zones_bitmap;
    long unsigned int * seq_zones_wlock;
    unsigned int sg_timeout;
    unsigned int sg_reserved_size;
    int node;
    struct blk_trace * blk_trace;
    struct mutex blk_trace_mutex;
    struct blk_flush_queue * fq;
    struct list_head requeue_list;
    spinlock_t requeue_lock;
    struct delayed_work requeue_work;
    struct mutex sysfs_lock;
    struct mutex sysfs_dir_lock;
    struct list_head unused_hctx_list;
    spinlock_t unused_hctx_lock;
    int mq_freeze_depth;
    struct bsg_class_device bsg_dev;
    struct throtl_data * td;
    struct callback_head callback_head;
    wait_queue_head_t mq_freeze_wq;
    struct mutex mq_freeze_lock;
    struct percpu_ref q_usage_counter;
    struct blk_mq_tag_set * tag_set;
    struct list_head tag_set_list;
    struct bio_set bio_split;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct dentry * rqos_debugfs_dir;
    bool mq_sysfs_init_done;
    size_t cmd_size;
    struct work_struct release_work;
    u64[5] write_hints;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct request_queue {
    struct request * last_merge;
    struct elevator_queue * elevator;
    struct percpu_ref q_usage_counter;
    struct blk_queue_stats * stats;
    struct rq_qos * rq_qos;
    const struct blk_mq_ops * mq_ops;
    struct blk_mq_ctx * queue_ctx;
    unsigned int queue_depth;
    struct blk_mq_hw_ctx * * queue_hw_ctx;
    unsigned int nr_hw_queues;
    struct backing_dev_info * backing_dev_info;
    void * queuedata;
    long unsigned int queue_flags;
    atomic_t pm_only;
    int id;
    gfp_t bounce_gfp;
    spinlock_t queue_lock;
    struct kobject kobj;
    struct kobject * mq_kobj;
    struct blk_integrity integrity;
    struct device * dev;
    enum rpm_status rpm_status;
    unsigned int nr_pending;
    long unsigned int nr_requests;
    unsigned int dma_pad_mask;
    unsigned int dma_alignment;
    struct blk_keyslot_manager * ksm;
    unsigned int rq_timeout;
    int poll_nsec;
    struct blk_stat_callback * poll_cb;
    struct blk_rq_stat[16] poll_stat;
    struct timer_list timeout;
    struct work_struct timeout_work;
    atomic_t nr_active_requests_shared_sbitmap;
    struct list_head icq_list;
    long unsigned int[1] blkcg_pols;
    struct blkcg_gq * root_blkg;
    struct list_head blkg_list;
    struct queue_limits limits;
    unsigned int required_elevator_features;
    unsigned int nr_zones;
    long unsigned int * conv_zones_bitmap;
    long unsigned int * seq_zones_wlock;
    unsigned int max_open_zones;
    unsigned int max_active_zones;
    unsigned int sg_timeout;
    unsigned int sg_reserved_size;
    int node;
    struct mutex debugfs_mutex;
    struct blk_trace * blk_trace;
    struct blk_flush_queue * fq;
    struct list_head requeue_list;
    spinlock_t requeue_lock;
    struct delayed_work requeue_work;
    struct mutex sysfs_lock;
    struct mutex sysfs_dir_lock;
    struct list_head unused_hctx_list;
    spinlock_t unused_hctx_lock;
    int mq_freeze_depth;
    struct bsg_class_device bsg_dev;
    struct throtl_data * td;
    struct callback_head callback_head;
    wait_queue_head_t mq_freeze_wq;
    struct mutex mq_freeze_lock;
    struct blk_mq_tag_set * tag_set;
    struct list_head tag_set_list;
    struct bio_set bio_split;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct dentry * rqos_debugfs_dir;
    bool mq_sysfs_init_done;
    size_t cmd_size;
    u64[5] write_hints;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct request_queue {
    struct request * last_merge;
    struct elevator_queue * elevator;
    struct percpu_ref q_usage_counter;
    struct blk_queue_stats * stats;
    struct rq_qos * rq_qos;
    const struct blk_mq_ops * mq_ops;
    struct blk_mq_ctx * queue_ctx;
    unsigned int queue_depth;
    struct blk_mq_hw_ctx * * queue_hw_ctx;
    unsigned int nr_hw_queues;
    struct backing_dev_info * backing_dev_info;
    void * queuedata;
    long unsigned int queue_flags;
    atomic_t pm_only;
    int id;
    spinlock_t queue_lock;
    struct kobject kobj;
    struct kobject * mq_kobj;
    struct blk_integrity integrity;
    struct device * dev;
    enum rpm_status rpm_status;
    long unsigned int nr_requests;
    unsigned int dma_pad_mask;
    unsigned int dma_alignment;
    struct blk_keyslot_manager * ksm;
    unsigned int rq_timeout;
    int poll_nsec;
    struct blk_stat_callback * poll_cb;
    struct blk_rq_stat[16] poll_stat;
    struct timer_list timeout;
    struct work_struct timeout_work;
    atomic_t nr_active_requests_shared_sbitmap;
    struct list_head icq_list;
    long unsigned int[1] blkcg_pols;
    struct blkcg_gq * root_blkg;
    struct list_head blkg_list;
    struct queue_limits limits;
    unsigned int required_elevator_features;
    unsigned int nr_zones;
    long unsigned int * conv_zones_bitmap;
    long unsigned int * seq_zones_wlock;
    unsigned int max_open_zones;
    unsigned int max_active_zones;
    unsigned int sg_timeout;
    unsigned int sg_reserved_size;
    int node;
    struct mutex debugfs_mutex;
    struct blk_trace * blk_trace;
    struct blk_flush_queue * fq;
    struct list_head requeue_list;
    spinlock_t requeue_lock;
    struct delayed_work requeue_work;
    struct mutex sysfs_lock;
    struct mutex sysfs_dir_lock;
    struct list_head unused_hctx_list;
    spinlock_t unused_hctx_lock;
    int mq_freeze_depth;
    struct bsg_class_device bsg_dev;
    struct throtl_data * td;
    struct callback_head callback_head;
    wait_queue_head_t mq_freeze_wq;
    struct mutex mq_freeze_lock;
    struct blk_mq_tag_set * tag_set;
    struct list_head tag_set_list;
    struct bio_set bio_split;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct dentry * rqos_debugfs_dir;
    bool mq_sysfs_init_done;
    size_t cmd_size;
    u64[5] write_hints;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct request_queue {
    struct request * last_merge;
    struct elevator_queue * elevator;
    struct percpu_ref q_usage_counter;
    struct blk_queue_stats * stats;
    struct rq_qos * rq_qos;
    const struct blk_mq_ops * mq_ops;
    struct blk_mq_ctx * queue_ctx;
    unsigned int queue_depth;
    struct blk_mq_hw_ctx * * queue_hw_ctx;
    unsigned int nr_hw_queues;
    void * queuedata;
    long unsigned int queue_flags;
    atomic_t pm_only;
    int id;
    spinlock_t queue_lock;
    struct gendisk * disk;
    struct kobject kobj;
    struct kobject * mq_kobj;
    struct blk_integrity integrity;
    struct device * dev;
    enum rpm_status rpm_status;
    long unsigned int nr_requests;
    unsigned int dma_pad_mask;
    unsigned int dma_alignment;
    struct blk_keyslot_manager * ksm;
    unsigned int rq_timeout;
    int poll_nsec;
    struct blk_stat_callback * poll_cb;
    struct blk_rq_stat[16] poll_stat;
    struct timer_list timeout;
    struct work_struct timeout_work;
    atomic_t nr_active_requests_shared_sbitmap;
    struct sbitmap_queue sched_bitmap_tags;
    struct sbitmap_queue sched_breserved_tags;
    struct list_head icq_list;
    long unsigned int[1] blkcg_pols;
    struct blkcg_gq * root_blkg;
    struct list_head blkg_list;
    struct queue_limits limits;
    unsigned int required_elevator_features;
    unsigned int nr_zones;
    long unsigned int * conv_zones_bitmap;
    long unsigned int * seq_zones_wlock;
    unsigned int max_open_zones;
    unsigned int max_active_zones;
    int node;
    struct mutex debugfs_mutex;
    struct blk_trace * blk_trace;
    struct blk_flush_queue * fq;
    struct list_head requeue_list;
    spinlock_t requeue_lock;
    struct delayed_work requeue_work;
    struct mutex sysfs_lock;
    struct mutex sysfs_dir_lock;
    struct list_head unused_hctx_list;
    spinlock_t unused_hctx_lock;
    int mq_freeze_depth;
    struct throtl_data * td;
    struct callback_head callback_head;
    wait_queue_head_t mq_freeze_wq;
    struct mutex mq_freeze_lock;
    struct blk_mq_tag_set * tag_set;
    struct list_head tag_set_list;
    struct bio_set bio_split;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct dentry * rqos_debugfs_dir;
    bool mq_sysfs_init_done;
    size_t cmd_size;
    u64[5] write_hints;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct request_queue {
    struct request * last_merge;
    struct elevator_queue * elevator;
    struct percpu_ref q_usage_counter;
    struct blk_queue_stats * stats;
    struct rq_qos * rq_qos;
    const struct blk_mq_ops * mq_ops;
    struct blk_mq_ctx * queue_ctx;
    unsigned int queue_depth;
    struct xarray hctx_table;
    unsigned int nr_hw_queues;
    void * queuedata;
    long unsigned int queue_flags;
    atomic_t pm_only;
    int id;
    spinlock_t queue_lock;
    struct gendisk * disk;
    struct kobject kobj;
    struct kobject * mq_kobj;
    struct blk_integrity integrity;
    struct device * dev;
    enum rpm_status rpm_status;
    long unsigned int nr_requests;
    unsigned int dma_pad_mask;
    unsigned int dma_alignment;
    struct blk_crypto_profile * crypto_profile;
    struct kobject * crypto_kobject;
    unsigned int rq_timeout;
    int poll_nsec;
    struct blk_stat_callback * poll_cb;
    struct blk_rq_stat * poll_stat;
    struct timer_list timeout;
    struct work_struct timeout_work;
    atomic_t nr_active_requests_shared_tags;
    struct blk_mq_tags * sched_shared_tags;
    struct list_head icq_list;
    long unsigned int[1] blkcg_pols;
    struct blkcg_gq * root_blkg;
    struct list_head blkg_list;
    struct queue_limits limits;
    unsigned int required_elevator_features;
    unsigned int nr_zones;
    long unsigned int * conv_zones_bitmap;
    long unsigned int * seq_zones_wlock;
    unsigned int max_open_zones;
    unsigned int max_active_zones;
    int node;
    struct blk_trace * blk_trace;
    struct blk_flush_queue * fq;
    struct list_head requeue_list;
    spinlock_t requeue_lock;
    struct delayed_work requeue_work;
    struct mutex sysfs_lock;
    struct mutex sysfs_dir_lock;
    struct list_head unused_hctx_list;
    spinlock_t unused_hctx_lock;
    int mq_freeze_depth;
    struct throtl_data * td;
    struct callback_head callback_head;
    wait_queue_head_t mq_freeze_wq;
    struct mutex mq_freeze_lock;
    int quiesce_depth;
    struct blk_mq_tag_set * tag_set;
    struct list_head tag_set_list;
    struct bio_set bio_split;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct dentry * rqos_debugfs_dir;
    struct mutex debugfs_mutex;
    bool mq_sysfs_init_done;
    struct blk_independent_access_ranges * ia_ranges;
    struct srcu_struct[0] srcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct request_queue {
    struct request * last_merge;
    struct elevator_queue * elevator;
    struct percpu_ref q_usage_counter;
    struct blk_queue_stats * stats;
    struct rq_qos * rq_qos;
    const struct blk_mq_ops * mq_ops;
    struct blk_mq_ctx * queue_ctx;
    unsigned int queue_depth;
    struct xarray hctx_table;
    unsigned int nr_hw_queues;
    void * queuedata;
    long unsigned int queue_flags;
    atomic_t pm_only;
    int id;
    spinlock_t queue_lock;
    struct gendisk * disk;
    refcount_t refs;
    struct kobject * mq_kobj;
    struct blk_integrity integrity;
    struct device * dev;
    enum rpm_status rpm_status;
    long unsigned int nr_requests;
    unsigned int dma_pad_mask;
    struct blk_crypto_profile * crypto_profile;
    struct kobject * crypto_kobject;
    unsigned int rq_timeout;
    int poll_nsec;
    struct blk_stat_callback * poll_cb;
    struct blk_rq_stat * poll_stat;
    struct timer_list timeout;
    struct work_struct timeout_work;
    atomic_t nr_active_requests_shared_tags;
    struct blk_mq_tags * sched_shared_tags;
    struct list_head icq_list;
    long unsigned int[1] blkcg_pols;
    struct blkcg_gq * root_blkg;
    struct list_head blkg_list;
    struct queue_limits limits;
    unsigned int required_elevator_features;
    int node;
    struct blk_trace * blk_trace;
    struct blk_flush_queue * fq;
    struct list_head requeue_list;
    spinlock_t requeue_lock;
    struct delayed_work requeue_work;
    struct mutex sysfs_lock;
    struct mutex sysfs_dir_lock;
    struct list_head unused_hctx_list;
    spinlock_t unused_hctx_lock;
    int mq_freeze_depth;
    struct throtl_data * td;
    struct callback_head callback_head;
    wait_queue_head_t mq_freeze_wq;
    struct mutex mq_freeze_lock;
    int quiesce_depth;
    struct blk_mq_tag_set * tag_set;
    struct list_head tag_set_list;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct dentry * rqos_debugfs_dir;
    struct mutex debugfs_mutex;
    bool mq_sysfs_init_done;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct request_queue {
    struct request * last_merge;
    struct elevator_queue * elevator;
    struct percpu_ref q_usage_counter;
    struct blk_queue_stats * stats;
    struct rq_qos * rq_qos;
    struct mutex rq_qos_mutex;
    const struct blk_mq_ops * mq_ops;
    struct blk_mq_ctx * queue_ctx;
    unsigned int queue_depth;
    struct xarray hctx_table;
    unsigned int nr_hw_queues;
    void * queuedata;
    long unsigned int queue_flags;
    atomic_t pm_only;
    int id;
    spinlock_t queue_lock;
    struct gendisk * disk;
    refcount_t refs;
    struct kobject * mq_kobj;
    struct blk_integrity integrity;
    struct device * dev;
    enum rpm_status rpm_status;
    long unsigned int nr_requests;
    unsigned int dma_pad_mask;
    struct blk_crypto_profile * crypto_profile;
    struct kobject * crypto_kobject;
    unsigned int rq_timeout;
    struct timer_list timeout;
    struct work_struct timeout_work;
    atomic_t nr_active_requests_shared_tags;
    struct blk_mq_tags * sched_shared_tags;
    struct list_head icq_list;
    long unsigned int[1] blkcg_pols;
    struct blkcg_gq * root_blkg;
    struct list_head blkg_list;
    struct mutex blkcg_mutex;
    struct queue_limits limits;
    unsigned int required_elevator_features;
    int node;
    struct blk_trace * blk_trace;
    struct blk_flush_queue * fq;
    struct list_head flush_list;
    struct list_head requeue_list;
    spinlock_t requeue_lock;
    struct delayed_work requeue_work;
    struct mutex sysfs_lock;
    struct mutex sysfs_dir_lock;
    struct list_head unused_hctx_list;
    spinlock_t unused_hctx_lock;
    int mq_freeze_depth;
    struct throtl_data * td;
    struct callback_head callback_head;
    wait_queue_head_t mq_freeze_wq;
    struct mutex mq_freeze_lock;
    int quiesce_depth;
    struct blk_mq_tag_set * tag_set;
    struct list_head tag_set_list;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct dentry * rqos_debugfs_dir;
    struct mutex debugfs_mutex;
    bool mq_sysfs_init_done;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct request_queue {
    void * queuedata;
    struct elevator_queue * elevator;
    const struct blk_mq_ops * mq_ops;
    struct blk_mq_ctx * queue_ctx;
    long unsigned int queue_flags;
    unsigned int rq_timeout;
    unsigned int queue_depth;
    refcount_t refs;
    unsigned int nr_hw_queues;
    struct xarray hctx_table;
    struct percpu_ref q_usage_counter;
    struct request * last_merge;
    spinlock_t queue_lock;
    int quiesce_depth;
    struct gendisk * disk;
    struct kobject * mq_kobj;
    struct queue_limits limits;
    struct blk_integrity integrity;
    struct device * dev;
    enum rpm_status rpm_status;
    atomic_t pm_only;
    struct blk_queue_stats * stats;
    struct rq_qos * rq_qos;
    struct mutex rq_qos_mutex;
    int id;
    unsigned int dma_pad_mask;
    long unsigned int nr_requests;
    struct blk_crypto_profile * crypto_profile;
    struct kobject * crypto_kobject;
    struct timer_list timeout;
    struct work_struct timeout_work;
    atomic_t nr_active_requests_shared_tags;
    unsigned int required_elevator_features;
    struct blk_mq_tags * sched_shared_tags;
    struct list_head icq_list;
    long unsigned int[1] blkcg_pols;
    struct blkcg_gq * root_blkg;
    struct list_head blkg_list;
    struct mutex blkcg_mutex;
    int node;
    spinlock_t requeue_lock;
    struct list_head requeue_list;
    struct delayed_work requeue_work;
    struct blk_trace * blk_trace;
    struct blk_flush_queue * fq;
    struct list_head flush_list;
    struct mutex sysfs_lock;
    struct mutex sysfs_dir_lock;
    struct list_head unused_hctx_list;
    spinlock_t unused_hctx_lock;
    int mq_freeze_depth;
    struct throtl_data * td;
    struct callback_head callback_head;
    wait_queue_head_t mq_freeze_wq;
    struct mutex mq_freeze_lock;
    struct blk_mq_tag_set * tag_set;
    struct list_head tag_set_list;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct dentry * rqos_debugfs_dir;
    struct mutex debugfs_mutex;
    bool mq_sysfs_init_done;
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
struct request_queue {
    struct request * last_merge;
    struct elevator_queue * elevator;
    struct blk_queue_stats * stats;
    struct rq_qos * rq_qos;
    make_request_fn * make_request_fn;
    dma_drain_needed_fn * dma_drain_needed;
    const struct blk_mq_ops * mq_ops;
    struct blk_mq_ctx * queue_ctx;
    unsigned int nr_queues;
    unsigned int queue_depth;
    struct blk_mq_hw_ctx * * queue_hw_ctx;
    unsigned int nr_hw_queues;
    struct backing_dev_info * backing_dev_info;
    void * queuedata;
    long unsigned int queue_flags;
    atomic_t pm_only;
    int id;
    gfp_t bounce_gfp;
    spinlock_t queue_lock;
    struct kobject kobj;
    struct kobject * mq_kobj;
    struct blk_integrity integrity;
    struct device * dev;
    int rpm_status;
    unsigned int nr_pending;
    long unsigned int nr_requests;
    unsigned int dma_drain_size;
    void * dma_drain_buffer;
    unsigned int dma_pad_mask;
    unsigned int dma_alignment;
    unsigned int rq_timeout;
    int poll_nsec;
    struct blk_stat_callback * poll_cb;
    struct blk_rq_stat[16] poll_stat;
    struct timer_list timeout;
    struct work_struct timeout_work;
    struct list_head icq_list;
    long unsigned int[1] blkcg_pols;
    struct blkcg_gq * root_blkg;
    struct list_head blkg_list;
    struct queue_limits limits;
    unsigned int required_elevator_features;
    unsigned int nr_zones;
    long unsigned int * seq_zones_bitmap;
    long unsigned int * seq_zones_wlock;
    unsigned int sg_timeout;
    unsigned int sg_reserved_size;
    int node;
    struct blk_trace * blk_trace;
    struct mutex blk_trace_mutex;
    struct blk_flush_queue * fq;
    struct list_head requeue_list;
    spinlock_t requeue_lock;
    struct delayed_work requeue_work;
    struct mutex sysfs_lock;
    struct mutex sysfs_dir_lock;
    struct list_head unused_hctx_list;
    spinlock_t unused_hctx_lock;
    int mq_freeze_depth;
    struct bsg_class_device bsg_dev;
    struct throtl_data * td;
    struct callback_head callback_head;
    wait_queue_head_t mq_freeze_wq;
    struct mutex mq_freeze_lock;
    struct percpu_ref q_usage_counter;
    struct blk_mq_tag_set * tag_set;
    struct list_head tag_set_list;
    struct bio_set bio_split;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct dentry * rqos_debugfs_dir;
    bool mq_sysfs_init_done;
    size_t cmd_size;
    struct work_struct release_work;
    u64[5] write_hints;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct request_queue {
    struct request * last_merge;
    struct elevator_queue * elevator;
    struct blk_queue_stats * stats;
    struct rq_qos * rq_qos;
    make_request_fn * make_request_fn;
    dma_drain_needed_fn * dma_drain_needed;
    const struct blk_mq_ops * mq_ops;
    struct blk_mq_ctx * queue_ctx;
    unsigned int nr_queues;
    unsigned int queue_depth;
    struct blk_mq_hw_ctx * * queue_hw_ctx;
    unsigned int nr_hw_queues;
    struct backing_dev_info * backing_dev_info;
    void * queuedata;
    long unsigned int queue_flags;
    atomic_t pm_only;
    int id;
    gfp_t bounce_gfp;
    spinlock_t queue_lock;
    struct kobject kobj;
    struct kobject * mq_kobj;
    struct blk_integrity integrity;
    struct device * dev;
    int rpm_status;
    unsigned int nr_pending;
    long unsigned int nr_requests;
    unsigned int dma_drain_size;
    void * dma_drain_buffer;
    unsigned int dma_pad_mask;
    unsigned int dma_alignment;
    unsigned int rq_timeout;
    int poll_nsec;
    struct blk_stat_callback * poll_cb;
    struct blk_rq_stat[16] poll_stat;
    struct timer_list timeout;
    struct work_struct timeout_work;
    struct list_head icq_list;
    long unsigned int[1] blkcg_pols;
    struct blkcg_gq * root_blkg;
    struct list_head blkg_list;
    struct queue_limits limits;
    unsigned int required_elevator_features;
    unsigned int nr_zones;
    long unsigned int * seq_zones_bitmap;
    long unsigned int * seq_zones_wlock;
    unsigned int sg_timeout;
    unsigned int sg_reserved_size;
    int node;
    struct blk_trace * blk_trace;
    struct mutex blk_trace_mutex;
    struct blk_flush_queue * fq;
    struct list_head requeue_list;
    spinlock_t requeue_lock;
    struct delayed_work requeue_work;
    struct mutex sysfs_lock;
    struct mutex sysfs_dir_lock;
    struct list_head unused_hctx_list;
    spinlock_t unused_hctx_lock;
    int mq_freeze_depth;
    struct bsg_class_device bsg_dev;
    struct throtl_data * td;
    struct callback_head callback_head;
    wait_queue_head_t mq_freeze_wq;
    struct mutex mq_freeze_lock;
    struct percpu_ref q_usage_counter;
    struct blk_mq_tag_set * tag_set;
    struct list_head tag_set_list;
    struct bio_set bio_split;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct dentry * rqos_debugfs_dir;
    bool mq_sysfs_init_done;
    size_t cmd_size;
    struct work_struct release_work;
    u64[5] write_hints;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct request_queue {
    struct request * last_merge;
    struct elevator_queue * elevator;
    struct blk_queue_stats * stats;
    struct rq_qos * rq_qos;
    make_request_fn * make_request_fn;
    dma_drain_needed_fn * dma_drain_needed;
    const struct blk_mq_ops * mq_ops;
    struct blk_mq_ctx * queue_ctx;
    unsigned int nr_queues;
    unsigned int queue_depth;
    struct blk_mq_hw_ctx * * queue_hw_ctx;
    unsigned int nr_hw_queues;
    struct backing_dev_info * backing_dev_info;
    void * queuedata;
    long unsigned int queue_flags;
    atomic_t pm_only;
    int id;
    gfp_t bounce_gfp;
    spinlock_t queue_lock;
    struct kobject kobj;
    struct kobject * mq_kobj;
    struct blk_integrity integrity;
    struct device * dev;
    int rpm_status;
    unsigned int nr_pending;
    long unsigned int nr_requests;
    unsigned int dma_drain_size;
    void * dma_drain_buffer;
    unsigned int dma_pad_mask;
    unsigned int dma_alignment;
    unsigned int rq_timeout;
    int poll_nsec;
    struct blk_stat_callback * poll_cb;
    struct blk_rq_stat[16] poll_stat;
    struct timer_list timeout;
    struct work_struct timeout_work;
    struct list_head icq_list;
    long unsigned int[1] blkcg_pols;
    struct blkcg_gq * root_blkg;
    struct list_head blkg_list;
    struct queue_limits limits;
    unsigned int required_elevator_features;
    unsigned int nr_zones;
    long unsigned int * seq_zones_bitmap;
    long unsigned int * seq_zones_wlock;
    unsigned int sg_timeout;
    unsigned int sg_reserved_size;
    int node;
    struct blk_trace * blk_trace;
    struct mutex blk_trace_mutex;
    struct blk_flush_queue * fq;
    struct list_head requeue_list;
    spinlock_t requeue_lock;
    struct delayed_work requeue_work;
    struct mutex sysfs_lock;
    struct mutex sysfs_dir_lock;
    struct list_head unused_hctx_list;
    spinlock_t unused_hctx_lock;
    int mq_freeze_depth;
    struct bsg_class_device bsg_dev;
    struct throtl_data * td;
    struct callback_head callback_head;
    wait_queue_head_t mq_freeze_wq;
    struct mutex mq_freeze_lock;
    struct percpu_ref q_usage_counter;
    struct blk_mq_tag_set * tag_set;
    struct list_head tag_set_list;
    struct bio_set bio_split;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct dentry * rqos_debugfs_dir;
    bool mq_sysfs_init_done;
    size_t cmd_size;
    struct work_struct release_work;
    u64[5] write_hints;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct request_queue {
    struct request * last_merge;
    struct elevator_queue * elevator;
    struct blk_queue_stats * stats;
    struct rq_qos * rq_qos;
    make_request_fn * make_request_fn;
    dma_drain_needed_fn * dma_drain_needed;
    const struct blk_mq_ops * mq_ops;
    struct blk_mq_ctx * queue_ctx;
    unsigned int nr_queues;
    unsigned int queue_depth;
    struct blk_mq_hw_ctx * * queue_hw_ctx;
    unsigned int nr_hw_queues;
    struct backing_dev_info * backing_dev_info;
    void * queuedata;
    long unsigned int queue_flags;
    atomic_t pm_only;
    int id;
    gfp_t bounce_gfp;
    spinlock_t queue_lock;
    struct kobject kobj;
    struct kobject * mq_kobj;
    struct blk_integrity integrity;
    struct device * dev;
    int rpm_status;
    unsigned int nr_pending;
    long unsigned int nr_requests;
    unsigned int dma_drain_size;
    void * dma_drain_buffer;
    unsigned int dma_pad_mask;
    unsigned int dma_alignment;
    unsigned int rq_timeout;
    int poll_nsec;
    struct blk_stat_callback * poll_cb;
    struct blk_rq_stat[16] poll_stat;
    struct timer_list timeout;
    struct work_struct timeout_work;
    struct list_head icq_list;
    long unsigned int[1] blkcg_pols;
    struct blkcg_gq * root_blkg;
    struct list_head blkg_list;
    struct queue_limits limits;
    unsigned int required_elevator_features;
    unsigned int nr_zones;
    long unsigned int * seq_zones_bitmap;
    long unsigned int * seq_zones_wlock;
    unsigned int sg_timeout;
    unsigned int sg_reserved_size;
    int node;
    struct blk_trace * blk_trace;
    struct mutex blk_trace_mutex;
    struct blk_flush_queue * fq;
    struct list_head requeue_list;
    spinlock_t requeue_lock;
    struct delayed_work requeue_work;
    struct mutex sysfs_lock;
    struct mutex sysfs_dir_lock;
    struct list_head unused_hctx_list;
    spinlock_t unused_hctx_lock;
    int mq_freeze_depth;
    struct bsg_class_device bsg_dev;
    struct throtl_data * td;
    struct callback_head callback_head;
    wait_queue_head_t mq_freeze_wq;
    struct mutex mq_freeze_lock;
    struct percpu_ref q_usage_counter;
    struct blk_mq_tag_set * tag_set;
    struct list_head tag_set_list;
    struct bio_set bio_split;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct dentry * rqos_debugfs_dir;
    bool mq_sysfs_init_done;
    size_t cmd_size;
    struct work_struct release_work;
    u64[5] write_hints;
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
struct request_queue {
    struct request * last_merge;
    struct elevator_queue * elevator;
    struct blk_queue_stats * stats;
    struct rq_qos * rq_qos;
    make_request_fn * make_request_fn;
    dma_drain_needed_fn * dma_drain_needed;
    const struct blk_mq_ops * mq_ops;
    struct blk_mq_ctx * queue_ctx;
    unsigned int nr_queues;
    unsigned int queue_depth;
    struct blk_mq_hw_ctx * * queue_hw_ctx;
    unsigned int nr_hw_queues;
    struct backing_dev_info * backing_dev_info;
    void * queuedata;
    long unsigned int queue_flags;
    atomic_t pm_only;
    int id;
    gfp_t bounce_gfp;
    spinlock_t queue_lock;
    struct kobject kobj;
    struct kobject * mq_kobj;
    struct blk_integrity integrity;
    struct device * dev;
    int rpm_status;
    unsigned int nr_pending;
    long unsigned int nr_requests;
    unsigned int dma_drain_size;
    void * dma_drain_buffer;
    unsigned int dma_pad_mask;
    unsigned int dma_alignment;
    unsigned int rq_timeout;
    int poll_nsec;
    struct blk_stat_callback * poll_cb;
    struct blk_rq_stat[16] poll_stat;
    struct timer_list timeout;
    struct work_struct timeout_work;
    struct list_head icq_list;
    long unsigned int[1] blkcg_pols;
    struct blkcg_gq * root_blkg;
    struct list_head blkg_list;
    struct queue_limits limits;
    unsigned int required_elevator_features;
    unsigned int nr_zones;
    long unsigned int * seq_zones_bitmap;
    long unsigned int * seq_zones_wlock;
    unsigned int sg_timeout;
    unsigned int sg_reserved_size;
    int node;
    struct blk_trace * blk_trace;
    struct mutex blk_trace_mutex;
    struct blk_flush_queue * fq;
    struct list_head requeue_list;
    spinlock_t requeue_lock;
    struct delayed_work requeue_work;
    struct mutex sysfs_lock;
    struct mutex sysfs_dir_lock;
    struct list_head unused_hctx_list;
    spinlock_t unused_hctx_lock;
    int mq_freeze_depth;
    struct bsg_class_device bsg_dev;
    struct throtl_data * td;
    struct callback_head callback_head;
    wait_queue_head_t mq_freeze_wq;
    struct mutex mq_freeze_lock;
    struct percpu_ref q_usage_counter;
    struct blk_mq_tag_set * tag_set;
    struct list_head tag_set_list;
    struct bio_set bio_split;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct dentry * rqos_debugfs_dir;
    bool mq_sysfs_init_done;
    size_t cmd_size;
    struct work_struct release_work;
    u64[5] write_hints;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct request_queue {
    struct request * last_merge;
    struct elevator_queue * elevator;
    struct blk_queue_stats * stats;
    struct rq_qos * rq_qos;
    make_request_fn * make_request_fn;
    dma_drain_needed_fn * dma_drain_needed;
    const struct blk_mq_ops * mq_ops;
    struct blk_mq_ctx * queue_ctx;
    unsigned int nr_queues;
    unsigned int queue_depth;
    struct blk_mq_hw_ctx * * queue_hw_ctx;
    unsigned int nr_hw_queues;
    struct backing_dev_info * backing_dev_info;
    void * queuedata;
    long unsigned int queue_flags;
    atomic_t pm_only;
    int id;
    gfp_t bounce_gfp;
    spinlock_t queue_lock;
    struct kobject kobj;
    struct kobject * mq_kobj;
    struct blk_integrity integrity;
    struct device * dev;
    int rpm_status;
    unsigned int nr_pending;
    long unsigned int nr_requests;
    unsigned int dma_drain_size;
    void * dma_drain_buffer;
    unsigned int dma_pad_mask;
    unsigned int dma_alignment;
    unsigned int rq_timeout;
    int poll_nsec;
    struct blk_stat_callback * poll_cb;
    struct blk_rq_stat[16] poll_stat;
    struct timer_list timeout;
    struct work_struct timeout_work;
    struct list_head icq_list;
    long unsigned int[1] blkcg_pols;
    struct blkcg_gq * root_blkg;
    struct list_head blkg_list;
    struct queue_limits limits;
    unsigned int required_elevator_features;
    unsigned int nr_zones;
    long unsigned int * seq_zones_bitmap;
    long unsigned int * seq_zones_wlock;
    unsigned int sg_timeout;
    unsigned int sg_reserved_size;
    int node;
    struct blk_trace * blk_trace;
    struct mutex blk_trace_mutex;
    struct blk_flush_queue * fq;
    struct list_head requeue_list;
    spinlock_t requeue_lock;
    struct delayed_work requeue_work;
    struct mutex sysfs_lock;
    struct mutex sysfs_dir_lock;
    struct list_head unused_hctx_list;
    spinlock_t unused_hctx_lock;
    int mq_freeze_depth;
    struct bsg_class_device bsg_dev;
    struct throtl_data * td;
    struct callback_head callback_head;
    wait_queue_head_t mq_freeze_wq;
    struct mutex mq_freeze_lock;
    struct percpu_ref q_usage_counter;
    struct blk_mq_tag_set * tag_set;
    struct list_head tag_set_list;
    struct bio_set bio_split;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct dentry * rqos_debugfs_dir;
    bool mq_sysfs_init_done;
    size_t cmd_size;
    struct work_struct release_work;
    u64[5] write_hints;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct request_queue {
    struct request * last_merge;
    struct elevator_queue * elevator;
    struct blk_queue_stats * stats;
    struct rq_qos * rq_qos;
    make_request_fn * make_request_fn;
    dma_drain_needed_fn * dma_drain_needed;
    const struct blk_mq_ops * mq_ops;
    struct blk_mq_ctx * queue_ctx;
    unsigned int nr_queues;
    unsigned int queue_depth;
    struct blk_mq_hw_ctx * * queue_hw_ctx;
    unsigned int nr_hw_queues;
    struct backing_dev_info * backing_dev_info;
    void * queuedata;
    long unsigned int queue_flags;
    atomic_t pm_only;
    int id;
    gfp_t bounce_gfp;
    spinlock_t queue_lock;
    struct kobject kobj;
    struct kobject * mq_kobj;
    struct blk_integrity integrity;
    struct device * dev;
    int rpm_status;
    unsigned int nr_pending;
    long unsigned int nr_requests;
    unsigned int dma_drain_size;
    void * dma_drain_buffer;
    unsigned int dma_pad_mask;
    unsigned int dma_alignment;
    unsigned int rq_timeout;
    int poll_nsec;
    struct blk_stat_callback * poll_cb;
    struct blk_rq_stat[16] poll_stat;
    struct timer_list timeout;
    struct work_struct timeout_work;
    struct list_head icq_list;
    long unsigned int[1] blkcg_pols;
    struct blkcg_gq * root_blkg;
    struct list_head blkg_list;
    struct queue_limits limits;
    unsigned int required_elevator_features;
    unsigned int nr_zones;
    long unsigned int * seq_zones_bitmap;
    long unsigned int * seq_zones_wlock;
    unsigned int sg_timeout;
    unsigned int sg_reserved_size;
    int node;
    struct blk_trace * blk_trace;
    struct mutex blk_trace_mutex;
    struct blk_flush_queue * fq;
    struct list_head requeue_list;
    spinlock_t requeue_lock;
    struct delayed_work requeue_work;
    struct mutex sysfs_lock;
    struct mutex sysfs_dir_lock;
    struct list_head unused_hctx_list;
    spinlock_t unused_hctx_lock;
    int mq_freeze_depth;
    struct bsg_class_device bsg_dev;
    struct throtl_data * td;
    struct callback_head callback_head;
    wait_queue_head_t mq_freeze_wq;
    struct mutex mq_freeze_lock;
    struct percpu_ref q_usage_counter;
    struct blk_mq_tag_set * tag_set;
    struct list_head tag_set_list;
    struct bio_set bio_split;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct dentry * rqos_debugfs_dir;
    bool mq_sysfs_init_done;
    size_t cmd_size;
    struct work_struct release_work;
    u64[5] write_hints;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct request_queue {
    struct request * last_merge;
    struct elevator_queue * elevator;
    struct blk_queue_stats * stats;
    struct rq_qos * rq_qos;
    make_request_fn * make_request_fn;
    dma_drain_needed_fn * dma_drain_needed;
    const struct blk_mq_ops * mq_ops;
    struct blk_mq_ctx * queue_ctx;
    unsigned int nr_queues;
    unsigned int queue_depth;
    struct blk_mq_hw_ctx * * queue_hw_ctx;
    unsigned int nr_hw_queues;
    struct backing_dev_info * backing_dev_info;
    void * queuedata;
    long unsigned int queue_flags;
    atomic_t pm_only;
    int id;
    gfp_t bounce_gfp;
    spinlock_t queue_lock;
    struct kobject kobj;
    struct kobject * mq_kobj;
    struct blk_integrity integrity;
    struct device * dev;
    int rpm_status;
    unsigned int nr_pending;
    long unsigned int nr_requests;
    unsigned int dma_drain_size;
    void * dma_drain_buffer;
    unsigned int dma_pad_mask;
    unsigned int dma_alignment;
    unsigned int rq_timeout;
    int poll_nsec;
    struct blk_stat_callback * poll_cb;
    struct blk_rq_stat[16] poll_stat;
    struct timer_list timeout;
    struct work_struct timeout_work;
    struct list_head icq_list;
    long unsigned int[1] blkcg_pols;
    struct blkcg_gq * root_blkg;
    struct list_head blkg_list;
    struct queue_limits limits;
    unsigned int required_elevator_features;
    unsigned int nr_zones;
    long unsigned int * seq_zones_bitmap;
    long unsigned int * seq_zones_wlock;
    unsigned int sg_timeout;
    unsigned int sg_reserved_size;
    int node;
    struct blk_trace * blk_trace;
    struct mutex blk_trace_mutex;
    struct blk_flush_queue * fq;
    struct list_head requeue_list;
    spinlock_t requeue_lock;
    struct delayed_work requeue_work;
    struct mutex sysfs_lock;
    struct mutex sysfs_dir_lock;
    struct list_head unused_hctx_list;
    spinlock_t unused_hctx_lock;
    int mq_freeze_depth;
    struct bsg_class_device bsg_dev;
    struct throtl_data * td;
    struct callback_head callback_head;
    wait_queue_head_t mq_freeze_wq;
    struct mutex mq_freeze_lock;
    struct percpu_ref q_usage_counter;
    struct blk_mq_tag_set * tag_set;
    struct list_head tag_set_list;
    struct bio_set bio_split;
    struct dentry * debugfs_dir;
    struct dentry * sched_debugfs_dir;
    struct dentry * rqos_debugfs_dir;
    bool mq_sysfs_init_done;
    size_t cmd_size;
    struct work_struct release_work;
    u64[5] write_hints;
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
<code>struct work_struct timeout_work</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int flush_flags</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int flush_not_queueable</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct rq_wb * rq_wb</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int queue_depth</code>
</li>
<li>
<b>Field added. </b>
<code>struct blk_rq_stat[2] rq_stats</code>
</li>
<li>
<b>Field added. </b>
<code>int poll_nsec</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct work_struct requeue_work</code> ➡️ <code>struct delayed_work requeue_work</code>
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
<code>atomic_t shared_hctx_restart</code>
</li>
<li>
<b>Field added. </b>
<code>struct blk_queue_stats * stats</code>
</li>
<li>
<b>Field added. </b>
<code>init_rq_fn * init_rq_fn</code>
</li>
<li>
<b>Field added. </b>
<code>exit_rq_fn * exit_rq_fn</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct request *) initialize_rq_fn</code>
</li>
<li>
<b>Field added. </b>
<code>struct blk_stat_callback * poll_cb</code>
</li>
<li>
<b>Field added. </b>
<code>struct blk_rq_stat[16] poll_stat</code>
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
<b>Field added. </b>
<code>size_t cmd_size</code>
</li>
<li>
<b>Field added. </b>
<code>void * rq_alloc_data</code>
</li>
<li>
<b>Field added. </b>
<code>struct work_struct release_work</code>
</li>
<li>
<b>Field added. </b>
<code>u64[5] write_hints</code>
</li>
<li>
<b>Field removed. </b>
<code>struct blk_rq_stat[2] rq_stats</code>
</li>
<li>
<b>Field removed. </b>
<code>int bsg_job_size</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct blk_mq_ops * mq_ops</code> ➡️ <code>const struct blk_mq_ops * mq_ops</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct backing_dev_info backing_dev_info</code> ➡️ <code>struct backing_dev_info * backing_dev_info</code>
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
<code>poll_q_fn * poll_fn</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex blk_trace_mutex</code>
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
<code>unsigned int nr_zones</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int * seq_zones_bitmap</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int * seq_zones_wlock</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head tag_busy_list</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct bio_set * bio_split</code> ➡️ <code>struct bio_set bio_split</code>
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
<code>struct rq_qos * rq_qos</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t pm_only</code>
</li>
<li>
<b>Field added. </b>
<code>struct dentry * rqos_debugfs_dir</code>
</li>
<li>
<b>Field removed. </b>
<code>int[2] nr_rqs</code>
</li>
<li>
<b>Field removed. </b>
<code>int nr_rqs_elvpriv</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t shared_hctx_restart</code>
</li>
<li>
<b>Field removed. </b>
<code>struct rq_wb * rq_wb</code>
</li>
<li>
<b>Field removed. </b>
<code>struct request_list root_rl</code>
</li>
<li>
<b>Field removed. </b>
<code>request_fn_proc * request_fn</code>
</li>
<li>
<b>Field removed. </b>
<code>poll_q_fn * poll_fn</code>
</li>
<li>
<b>Field removed. </b>
<code>prep_rq_fn * prep_rq_fn</code>
</li>
<li>
<b>Field removed. </b>
<code>unprep_rq_fn * unprep_rq_fn</code>
</li>
<li>
<b>Field removed. </b>
<code>softirq_done_fn * softirq_done_fn</code>
</li>
<li>
<b>Field removed. </b>
<code>rq_timed_out_fn * rq_timed_out_fn</code>
</li>
<li>
<b>Field removed. </b>
<code>lld_busy_fn * lld_busy_fn</code>
</li>
<li>
<b>Field removed. </b>
<code>init_rq_fn * init_rq_fn</code>
</li>
<li>
<b>Field removed. </b>
<code>exit_rq_fn * exit_rq_fn</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct request *) initialize_rq_fn</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int * mq_map</code>
</li>
<li>
<b>Field removed. </b>
<code>sector_t end_sector</code>
</li>
<li>
<b>Field removed. </b>
<code>struct request * boundary_rq</code>
</li>
<li>
<b>Field removed. </b>
<code>struct delayed_work delay_work</code>
</li>
<li>
<b>Field removed. </b>
<code>spinlock_t __queue_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int nr_congestion_on</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int nr_congestion_off</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int nr_batching</code>
</li>
<li>
<b>Field removed. </b>
<code>struct blk_queue_tag * queue_tags</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int nr_sorted</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int[2] in_flight</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int request_fn_active</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head timeout_list</code>
</li>
<li>
<b>Field removed. </b>
<code>int bypass_depth</code>
</li>
<li>
<b>Field removed. </b>
<code>bsg_job_fn * bsg_job_fn</code>
</li>
<li>
<b>Field removed. </b>
<code>void * rq_alloc_data</code>
</li>
<li>
<b>Field type changed. </b>
<code>spinlock_t * queue_lock</code> ➡️ <code>spinlock_t queue_lock</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct kobject mq_kobj</code> ➡️ <code>struct kobject * mq_kobj</code>
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
<code>struct list_head unused_hctx_list</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t unused_hctx_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex mq_freeze_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head all_q_node</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_t mq_freeze_depth</code> ➡️ <code>int mq_freeze_depth</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int required_elevator_features</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex sysfs_dir_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head queue_head</code>
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
<code>struct blk_keyslot_manager * ksm</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int * conv_zones_bitmap</code>
</li>
<li>
<b>Field removed. </b>
<code>dma_drain_needed_fn * dma_drain_needed</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int nr_queues</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int dma_drain_size</code>
</li>
<li>
<b>Field removed. </b>
<code>void * dma_drain_buffer</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int * seq_zones_bitmap</code>
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
<code>atomic_t nr_active_requests_shared_sbitmap</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int max_open_zones</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int max_active_zones</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex debugfs_mutex</code>
</li>
<li>
<b>Field removed. </b>
<code>make_request_fn * make_request_fn</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mutex blk_trace_mutex</code>
</li>
<li>
<b>Field removed. </b>
<code>struct work_struct release_work</code>
</li>
<li>
<b>Field type changed. </b>
<code>int rpm_status</code> ➡️ <code>enum rpm_status rpm_status</code>
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
<code>gfp_t bounce_gfp</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int nr_pending</code>
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
<code>struct gendisk * disk</code>
</li>
<li>
<b>Field added. </b>
<code>struct sbitmap_queue sched_bitmap_tags</code>
</li>
<li>
<b>Field added. </b>
<code>struct sbitmap_queue sched_breserved_tags</code>
</li>
<li>
<b>Field removed. </b>
<code>struct backing_dev_info * backing_dev_info</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int sg_timeout</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int sg_reserved_size</code>
</li>
<li>
<b>Field removed. </b>
<code>struct bsg_class_device bsg_dev</code>
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
<code>struct xarray hctx_table</code>
</li>
<li>
<b>Field added. </b>
<code>struct blk_crypto_profile * crypto_profile</code>
</li>
<li>
<b>Field added. </b>
<code>struct kobject * crypto_kobject</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t nr_active_requests_shared_tags</code>
</li>
<li>
<b>Field added. </b>
<code>struct blk_mq_tags * sched_shared_tags</code>
</li>
<li>
<b>Field added. </b>
<code>int quiesce_depth</code>
</li>
<li>
<b>Field added. </b>
<code>struct blk_independent_access_ranges * ia_ranges</code>
</li>
<li>
<b>Field added. </b>
<code>struct srcu_struct[0] srcu</code>
</li>
<li>
<b>Field removed. </b>
<code>struct blk_mq_hw_ctx * * queue_hw_ctx</code>
</li>
<li>
<b>Field removed. </b>
<code>struct blk_keyslot_manager * ksm</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t nr_active_requests_shared_sbitmap</code>
</li>
<li>
<b>Field removed. </b>
<code>struct sbitmap_queue sched_bitmap_tags</code>
</li>
<li>
<b>Field removed. </b>
<code>struct sbitmap_queue sched_breserved_tags</code>
</li>
<li>
<b>Field removed. </b>
<code>size_t cmd_size</code>
</li>
<li>
<b>Field removed. </b>
<code>u64[5] write_hints</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct blk_rq_stat[16] poll_stat</code> ➡️ <code>struct blk_rq_stat * poll_stat</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>refcount_t refs</code>
</li>
<li>
<b>Field removed. </b>
<code>struct kobject kobj</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int dma_alignment</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int nr_zones</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int * conv_zones_bitmap</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int * seq_zones_wlock</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int max_open_zones</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int max_active_zones</code>
</li>
<li>
<b>Field removed. </b>
<code>struct bio_set bio_split</code>
</li>
<li>
<b>Field removed. </b>
<code>struct blk_independent_access_ranges * ia_ranges</code>
</li>
<li>
<b>Field removed. </b>
<code>struct srcu_struct[0] srcu</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct mutex rq_qos_mutex</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex blkcg_mutex</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head flush_list</code>
</li>
<li>
<b>Field removed. </b>
<code>int poll_nsec</code>
</li>
<li>
<b>Field removed. </b>
<code>struct blk_stat_callback * poll_cb</code>
</li>
<li>
<b>Field removed. </b>
<code>struct blk_rq_stat * poll_stat</code>
</li>
</ul>
</details>
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
