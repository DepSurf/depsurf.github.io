# Struct: <code>cfq_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct cfq_data {
    struct request_queue * queue;
    struct cfq_rb_root grp_service_tree;
    struct cfq_group * root_group;
    enum wl_class_t serving_wl_class;
    enum wl_type_t serving_wl_type;
    long unsigned int workload_expires;
    struct cfq_group * serving_group;
    struct rb_root[8] prio_trees;
    unsigned int busy_queues;
    unsigned int busy_sync_queues;
    int rq_in_driver;
    int[2] rq_in_flight;
    int rq_queued;
    int hw_tag;
    int hw_tag_est_depth;
    unsigned int hw_tag_samples;
    struct timer_list idle_slice_timer;
    struct work_struct unplug_work;
    struct cfq_queue * active_queue;
    struct cfq_io_cq * active_cic;
    sector_t last_position;
    unsigned int cfq_quantum;
    unsigned int[2] cfq_fifo_expire;
    unsigned int cfq_back_penalty;
    unsigned int cfq_back_max;
    unsigned int[2] cfq_slice;
    unsigned int cfq_slice_async_rq;
    unsigned int cfq_slice_idle;
    unsigned int cfq_group_idle;
    unsigned int cfq_latency;
    unsigned int cfq_target_latency;
    struct cfq_queue oom_cfqq;
    long unsigned int last_delayed_sync;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct cfq_data {
    struct request_queue * queue;
    struct cfq_rb_root grp_service_tree;
    struct cfq_group * root_group;
    enum wl_class_t serving_wl_class;
    enum wl_type_t serving_wl_type;
    u64 workload_expires;
    struct cfq_group * serving_group;
    struct rb_root[8] prio_trees;
    unsigned int busy_queues;
    unsigned int busy_sync_queues;
    int rq_in_driver;
    int[2] rq_in_flight;
    int rq_queued;
    int hw_tag;
    int hw_tag_est_depth;
    unsigned int hw_tag_samples;
    struct hrtimer idle_slice_timer;
    struct work_struct unplug_work;
    struct cfq_queue * active_queue;
    struct cfq_io_cq * active_cic;
    sector_t last_position;
    unsigned int cfq_quantum;
    unsigned int cfq_back_penalty;
    unsigned int cfq_back_max;
    unsigned int cfq_slice_async_rq;
    unsigned int cfq_latency;
    u64[2] cfq_fifo_expire;
    u64[2] cfq_slice;
    u64 cfq_slice_idle;
    u64 cfq_group_idle;
    u64 cfq_target_latency;
    struct cfq_queue oom_cfqq;
    u64 last_delayed_sync;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct cfq_data {
    struct request_queue * queue;
    struct cfq_rb_root grp_service_tree;
    struct cfq_group * root_group;
    enum wl_class_t serving_wl_class;
    enum wl_type_t serving_wl_type;
    u64 workload_expires;
    struct cfq_group * serving_group;
    struct rb_root[8] prio_trees;
    unsigned int busy_queues;
    unsigned int busy_sync_queues;
    int rq_in_driver;
    int[2] rq_in_flight;
    int rq_queued;
    int hw_tag;
    int hw_tag_est_depth;
    unsigned int hw_tag_samples;
    struct hrtimer idle_slice_timer;
    struct work_struct unplug_work;
    struct cfq_queue * active_queue;
    struct cfq_io_cq * active_cic;
    sector_t last_position;
    unsigned int cfq_quantum;
    unsigned int cfq_back_penalty;
    unsigned int cfq_back_max;
    unsigned int cfq_slice_async_rq;
    unsigned int cfq_latency;
    u64[2] cfq_fifo_expire;
    u64[2] cfq_slice;
    u64 cfq_slice_idle;
    u64 cfq_group_idle;
    u64 cfq_target_latency;
    struct cfq_queue oom_cfqq;
    u64 last_delayed_sync;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct cfq_data {
    struct request_queue * queue;
    struct cfq_rb_root grp_service_tree;
    struct cfq_group * root_group;
    enum wl_class_t serving_wl_class;
    enum wl_type_t serving_wl_type;
    u64 workload_expires;
    struct cfq_group * serving_group;
    struct rb_root[8] prio_trees;
    unsigned int busy_queues;
    unsigned int busy_sync_queues;
    int rq_in_driver;
    int[2] rq_in_flight;
    int rq_queued;
    int hw_tag;
    int hw_tag_est_depth;
    unsigned int hw_tag_samples;
    struct hrtimer idle_slice_timer;
    struct work_struct unplug_work;
    struct cfq_queue * active_queue;
    struct cfq_io_cq * active_cic;
    sector_t last_position;
    unsigned int cfq_quantum;
    unsigned int cfq_back_penalty;
    unsigned int cfq_back_max;
    unsigned int cfq_slice_async_rq;
    unsigned int cfq_latency;
    u64[2] cfq_fifo_expire;
    u64[2] cfq_slice;
    u64 cfq_slice_idle;
    u64 cfq_group_idle;
    u64 cfq_target_latency;
    struct cfq_queue oom_cfqq;
    u64 last_delayed_sync;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct cfq_data {
    struct request_queue * queue;
    struct cfq_rb_root grp_service_tree;
    struct cfq_group * root_group;
    enum wl_class_t serving_wl_class;
    enum wl_type_t serving_wl_type;
    u64 workload_expires;
    struct cfq_group * serving_group;
    struct rb_root[8] prio_trees;
    unsigned int busy_queues;
    unsigned int busy_sync_queues;
    int rq_in_driver;
    int[2] rq_in_flight;
    int rq_queued;
    int hw_tag;
    int hw_tag_est_depth;
    unsigned int hw_tag_samples;
    struct hrtimer idle_slice_timer;
    struct work_struct unplug_work;
    struct cfq_queue * active_queue;
    struct cfq_io_cq * active_cic;
    sector_t last_position;
    unsigned int cfq_quantum;
    unsigned int cfq_back_penalty;
    unsigned int cfq_back_max;
    unsigned int cfq_slice_async_rq;
    unsigned int cfq_latency;
    u64[2] cfq_fifo_expire;
    u64[2] cfq_slice;
    u64 cfq_slice_idle;
    u64 cfq_group_idle;
    u64 cfq_target_latency;
    struct cfq_queue oom_cfqq;
    u64 last_delayed_sync;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct cfq_data {
    struct request_queue * queue;
    struct cfq_rb_root grp_service_tree;
    struct cfq_group * root_group;
    enum wl_class_t serving_wl_class;
    enum wl_type_t serving_wl_type;
    u64 workload_expires;
    struct cfq_group * serving_group;
    struct rb_root[8] prio_trees;
    unsigned int busy_queues;
    unsigned int busy_sync_queues;
    int rq_in_driver;
    int[2] rq_in_flight;
    int rq_queued;
    int hw_tag;
    int hw_tag_est_depth;
    unsigned int hw_tag_samples;
    struct hrtimer idle_slice_timer;
    struct work_struct unplug_work;
    struct cfq_queue * active_queue;
    struct cfq_io_cq * active_cic;
    sector_t last_position;
    unsigned int cfq_quantum;
    unsigned int cfq_back_penalty;
    unsigned int cfq_back_max;
    unsigned int cfq_slice_async_rq;
    unsigned int cfq_latency;
    u64[2] cfq_fifo_expire;
    u64[2] cfq_slice;
    u64 cfq_slice_idle;
    u64 cfq_group_idle;
    u64 cfq_target_latency;
    struct cfq_queue oom_cfqq;
    u64 last_delayed_sync;
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
<b>Field type changed. </b>
<code>long unsigned int workload_expires</code> ➡️ <code>u64 workload_expires</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct timer_list idle_slice_timer</code> ➡️ <code>struct hrtimer idle_slice_timer</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int[2] cfq_fifo_expire</code> ➡️ <code>u64[2] cfq_fifo_expire</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int[2] cfq_slice</code> ➡️ <code>u64[2] cfq_slice</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int cfq_slice_idle</code> ➡️ <code>u64 cfq_slice_idle</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int cfq_group_idle</code> ➡️ <code>u64 cfq_group_idle</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int cfq_target_latency</code> ➡️ <code>u64 cfq_target_latency</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int last_delayed_sync</code> ➡️ <code>u64 last_delayed_sync</code>
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
struct cfq_data {
    struct request_queue * queue;
    struct cfq_rb_root grp_service_tree;
    struct cfq_group * root_group;
    enum wl_class_t serving_wl_class;
    enum wl_type_t serving_wl_type;
    u64 workload_expires;
    struct cfq_group * serving_group;
    struct rb_root[8] prio_trees;
    unsigned int busy_queues;
    unsigned int busy_sync_queues;
    int rq_in_driver;
    int[2] rq_in_flight;
    int rq_queued;
    int hw_tag;
    int hw_tag_est_depth;
    unsigned int hw_tag_samples;
    struct hrtimer idle_slice_timer;
    struct work_struct unplug_work;
    struct cfq_queue * active_queue;
    struct cfq_io_cq * active_cic;
    sector_t last_position;
    unsigned int cfq_quantum;
    unsigned int cfq_back_penalty;
    unsigned int cfq_back_max;
    unsigned int cfq_slice_async_rq;
    unsigned int cfq_latency;
    u64[2] cfq_fifo_expire;
    u64[2] cfq_slice;
    u64 cfq_slice_idle;
    u64 cfq_group_idle;
    u64 cfq_target_latency;
    struct cfq_queue oom_cfqq;
    u64 last_delayed_sync;
}
```
</details>
</li>
</ul>
