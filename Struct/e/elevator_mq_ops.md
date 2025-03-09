# Struct: <code>elevator_mq_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct elevator_mq_ops {
    int (*)(struct request_queue *, struct elevator_type *) init_sched;
    void (*)(struct elevator_queue *) exit_sched;
    int (*)(struct blk_mq_hw_ctx *, unsigned int) init_hctx;
    void (*)(struct blk_mq_hw_ctx *, unsigned int) exit_hctx;
    bool (*)(struct request_queue *, struct request *, struct bio *) allow_merge;
    bool (*)(struct blk_mq_hw_ctx *, struct bio *) bio_merge;
    int (*)(struct request_queue *, struct request * *, struct bio *) request_merge;
    void (*)(struct request_queue *, struct request *, enum elv_merge) request_merged;
    void (*)(struct request_queue *, struct request *, struct request *) requests_merged;
    void (*)(unsigned int, struct blk_mq_alloc_data *) limit_depth;
    void (*)(struct request *, struct bio *) prepare_request;
    void (*)(struct request *) finish_request;
    void (*)(struct blk_mq_hw_ctx *, struct list_head *, bool) insert_requests;
    struct request * (*)(struct blk_mq_hw_ctx *) dispatch_request;
    bool (*)(struct blk_mq_hw_ctx *) has_work;
    void (*)(struct request *) completed_request;
    void (*)(struct request *) started_request;
    void (*)(struct request *) requeue_request;
    struct request * (*)(struct request_queue *, struct request *) former_request;
    struct request * (*)(struct request_queue *, struct request *) next_request;
    void (*)(struct io_cq *) init_icq;
    void (*)(struct io_cq *) exit_icq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct elevator_mq_ops {
    int (*)(struct request_queue *, struct elevator_type *) init_sched;
    void (*)(struct elevator_queue *) exit_sched;
    int (*)(struct blk_mq_hw_ctx *, unsigned int) init_hctx;
    void (*)(struct blk_mq_hw_ctx *, unsigned int) exit_hctx;
    bool (*)(struct request_queue *, struct request *, struct bio *) allow_merge;
    bool (*)(struct blk_mq_hw_ctx *, struct bio *) bio_merge;
    int (*)(struct request_queue *, struct request * *, struct bio *) request_merge;
    void (*)(struct request_queue *, struct request *, enum elv_merge) request_merged;
    void (*)(struct request_queue *, struct request *, struct request *) requests_merged;
    void (*)(unsigned int, struct blk_mq_alloc_data *) limit_depth;
    void (*)(struct request *, struct bio *) prepare_request;
    void (*)(struct request *) finish_request;
    void (*)(struct blk_mq_hw_ctx *, struct list_head *, bool) insert_requests;
    struct request * (*)(struct blk_mq_hw_ctx *) dispatch_request;
    bool (*)(struct blk_mq_hw_ctx *) has_work;
    void (*)(struct request *) completed_request;
    void (*)(struct request *) started_request;
    void (*)(struct request *) requeue_request;
    struct request * (*)(struct request_queue *, struct request *) former_request;
    struct request * (*)(struct request_queue *, struct request *) next_request;
    void (*)(struct io_cq *) init_icq;
    void (*)(struct io_cq *) exit_icq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct elevator_mq_ops {
    int (*)(struct request_queue *, struct elevator_type *) init_sched;
    void (*)(struct elevator_queue *) exit_sched;
    int (*)(struct blk_mq_hw_ctx *, unsigned int) init_hctx;
    void (*)(struct blk_mq_hw_ctx *, unsigned int) exit_hctx;
    bool (*)(struct request_queue *, struct request *, struct bio *) allow_merge;
    bool (*)(struct blk_mq_hw_ctx *, struct bio *) bio_merge;
    int (*)(struct request_queue *, struct request * *, struct bio *) request_merge;
    void (*)(struct request_queue *, struct request *, enum elv_merge) request_merged;
    void (*)(struct request_queue *, struct request *, struct request *) requests_merged;
    void (*)(unsigned int, struct blk_mq_alloc_data *) limit_depth;
    void (*)(struct request *, struct bio *) prepare_request;
    void (*)(struct request *) finish_request;
    void (*)(struct blk_mq_hw_ctx *, struct list_head *, bool) insert_requests;
    struct request * (*)(struct blk_mq_hw_ctx *) dispatch_request;
    bool (*)(struct blk_mq_hw_ctx *) has_work;
    void (*)(struct request *) completed_request;
    void (*)(struct request *) started_request;
    void (*)(struct request *) requeue_request;
    struct request * (*)(struct request_queue *, struct request *) former_request;
    struct request * (*)(struct request_queue *, struct request *) next_request;
    void (*)(struct io_cq *) init_icq;
    void (*)(struct io_cq *) exit_icq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct elevator_mq_ops {
    int (*)(struct request_queue *, struct elevator_type *) init_sched;
    void (*)(struct elevator_queue *) exit_sched;
    int (*)(struct blk_mq_hw_ctx *, unsigned int) init_hctx;
    void (*)(struct blk_mq_hw_ctx *, unsigned int) exit_hctx;
    bool (*)(struct request_queue *, struct request *, struct bio *) allow_merge;
    bool (*)(struct blk_mq_hw_ctx *, struct bio *) bio_merge;
    int (*)(struct request_queue *, struct request * *, struct bio *) request_merge;
    void (*)(struct request_queue *, struct request *, enum elv_merge) request_merged;
    void (*)(struct request_queue *, struct request *, struct request *) requests_merged;
    void (*)(unsigned int, struct blk_mq_alloc_data *) limit_depth;
    void (*)(struct request *, struct bio *) prepare_request;
    void (*)(struct request *) finish_request;
    void (*)(struct blk_mq_hw_ctx *, struct list_head *, bool) insert_requests;
    struct request * (*)(struct blk_mq_hw_ctx *) dispatch_request;
    bool (*)(struct blk_mq_hw_ctx *) has_work;
    void (*)(struct request *, u64) completed_request;
    void (*)(struct request *) started_request;
    void (*)(struct request *) requeue_request;
    struct request * (*)(struct request_queue *, struct request *) former_request;
    struct request * (*)(struct request_queue *, struct request *) next_request;
    void (*)(struct io_cq *) init_icq;
    void (*)(struct io_cq *) exit_icq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct elevator_mq_ops {
    int (*)(struct request_queue *, struct elevator_type *) init_sched;
    void (*)(struct elevator_queue *) exit_sched;
    int (*)(struct blk_mq_hw_ctx *, unsigned int) init_hctx;
    void (*)(struct blk_mq_hw_ctx *, unsigned int) exit_hctx;
    void (*)(struct blk_mq_hw_ctx *) depth_updated;
    bool (*)(struct request_queue *, struct request *, struct bio *) allow_merge;
    bool (*)(struct blk_mq_hw_ctx *, struct bio *, unsigned int) bio_merge;
    int (*)(struct request_queue *, struct request * *, struct bio *) request_merge;
    void (*)(struct request_queue *, struct request *, enum elv_merge) request_merged;
    void (*)(struct request_queue *, struct request *, struct request *) requests_merged;
    void (*)(unsigned int, struct blk_mq_alloc_data *) limit_depth;
    void (*)(struct request *, struct bio *) prepare_request;
    void (*)(struct request *) finish_request;
    void (*)(struct blk_mq_hw_ctx *, struct list_head *, bool) insert_requests;
    struct request * (*)(struct blk_mq_hw_ctx *) dispatch_request;
    bool (*)(struct blk_mq_hw_ctx *) has_work;
    void (*)(struct request *, u64) completed_request;
    void (*)(struct request *) requeue_request;
    struct request * (*)(struct request_queue *, struct request *) former_request;
    struct request * (*)(struct request_queue *, struct request *) next_request;
    void (*)(struct io_cq *) init_icq;
    void (*)(struct io_cq *) exit_icq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct elevator_mq_ops {
    int (*)(struct request_queue *, struct elevator_type *) init_sched;
    void (*)(struct elevator_queue *) exit_sched;
    int (*)(struct blk_mq_hw_ctx *, unsigned int) init_hctx;
    void (*)(struct blk_mq_hw_ctx *, unsigned int) exit_hctx;
    void (*)(struct blk_mq_hw_ctx *) depth_updated;
    bool (*)(struct request_queue *, struct request *, struct bio *) allow_merge;
    bool (*)(struct blk_mq_hw_ctx *, struct bio *, unsigned int) bio_merge;
    int (*)(struct request_queue *, struct request * *, struct bio *) request_merge;
    void (*)(struct request_queue *, struct request *, enum elv_merge) request_merged;
    void (*)(struct request_queue *, struct request *, struct request *) requests_merged;
    void (*)(unsigned int, struct blk_mq_alloc_data *) limit_depth;
    void (*)(struct request *, struct bio *) prepare_request;
    void (*)(struct request *) finish_request;
    void (*)(struct blk_mq_hw_ctx *, struct list_head *, bool) insert_requests;
    struct request * (*)(struct blk_mq_hw_ctx *) dispatch_request;
    bool (*)(struct blk_mq_hw_ctx *) has_work;
    void (*)(struct request *, u64) completed_request;
    void (*)(struct request *) requeue_request;
    struct request * (*)(struct request_queue *, struct request *) former_request;
    struct request * (*)(struct request_queue *, struct request *) next_request;
    void (*)(struct io_cq *) init_icq;
    void (*)(struct io_cq *) exit_icq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct elevator_mq_ops {
    int (*)(struct request_queue *, struct elevator_type *) init_sched;
    void (*)(struct elevator_queue *) exit_sched;
    int (*)(struct blk_mq_hw_ctx *, unsigned int) init_hctx;
    void (*)(struct blk_mq_hw_ctx *, unsigned int) exit_hctx;
    void (*)(struct blk_mq_hw_ctx *) depth_updated;
    bool (*)(struct request_queue *, struct request *, struct bio *) allow_merge;
    bool (*)(struct blk_mq_hw_ctx *, struct bio *, unsigned int) bio_merge;
    int (*)(struct request_queue *, struct request * *, struct bio *) request_merge;
    void (*)(struct request_queue *, struct request *, enum elv_merge) request_merged;
    void (*)(struct request_queue *, struct request *, struct request *) requests_merged;
    void (*)(unsigned int, struct blk_mq_alloc_data *) limit_depth;
    void (*)(struct request *) prepare_request;
    void (*)(struct request *) finish_request;
    void (*)(struct blk_mq_hw_ctx *, struct list_head *, bool) insert_requests;
    struct request * (*)(struct blk_mq_hw_ctx *) dispatch_request;
    bool (*)(struct blk_mq_hw_ctx *) has_work;
    void (*)(struct request *, u64) completed_request;
    void (*)(struct request *) requeue_request;
    struct request * (*)(struct request_queue *, struct request *) former_request;
    struct request * (*)(struct request_queue *, struct request *) next_request;
    void (*)(struct io_cq *) init_icq;
    void (*)(struct io_cq *) exit_icq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct elevator_mq_ops {
    int (*)(struct request_queue *, struct elevator_type *) init_sched;
    void (*)(struct elevator_queue *) exit_sched;
    int (*)(struct blk_mq_hw_ctx *, unsigned int) init_hctx;
    void (*)(struct blk_mq_hw_ctx *, unsigned int) exit_hctx;
    void (*)(struct blk_mq_hw_ctx *) depth_updated;
    bool (*)(struct request_queue *, struct request *, struct bio *) allow_merge;
    bool (*)(struct blk_mq_hw_ctx *, struct bio *, unsigned int) bio_merge;
    int (*)(struct request_queue *, struct request * *, struct bio *) request_merge;
    void (*)(struct request_queue *, struct request *, enum elv_merge) request_merged;
    void (*)(struct request_queue *, struct request *, struct request *) requests_merged;
    void (*)(unsigned int, struct blk_mq_alloc_data *) limit_depth;
    void (*)(struct request *) prepare_request;
    void (*)(struct request *) finish_request;
    void (*)(struct blk_mq_hw_ctx *, struct list_head *, bool) insert_requests;
    struct request * (*)(struct blk_mq_hw_ctx *) dispatch_request;
    bool (*)(struct blk_mq_hw_ctx *) has_work;
    void (*)(struct request *, u64) completed_request;
    void (*)(struct request *) requeue_request;
    struct request * (*)(struct request_queue *, struct request *) former_request;
    struct request * (*)(struct request_queue *, struct request *) next_request;
    void (*)(struct io_cq *) init_icq;
    void (*)(struct io_cq *) exit_icq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct elevator_mq_ops {
    int (*)(struct request_queue *, struct elevator_type *) init_sched;
    void (*)(struct elevator_queue *) exit_sched;
    int (*)(struct blk_mq_hw_ctx *, unsigned int) init_hctx;
    void (*)(struct blk_mq_hw_ctx *, unsigned int) exit_hctx;
    void (*)(struct blk_mq_hw_ctx *) depth_updated;
    bool (*)(struct request_queue *, struct request *, struct bio *) allow_merge;
    bool (*)(struct request_queue *, struct bio *, unsigned int) bio_merge;
    int (*)(struct request_queue *, struct request * *, struct bio *) request_merge;
    void (*)(struct request_queue *, struct request *, enum elv_merge) request_merged;
    void (*)(struct request_queue *, struct request *, struct request *) requests_merged;
    void (*)(unsigned int, struct blk_mq_alloc_data *) limit_depth;
    void (*)(struct request *) prepare_request;
    void (*)(struct request *) finish_request;
    void (*)(struct blk_mq_hw_ctx *, struct list_head *, bool) insert_requests;
    struct request * (*)(struct blk_mq_hw_ctx *) dispatch_request;
    bool (*)(struct blk_mq_hw_ctx *) has_work;
    void (*)(struct request *, u64) completed_request;
    void (*)(struct request *) requeue_request;
    struct request * (*)(struct request_queue *, struct request *) former_request;
    struct request * (*)(struct request_queue *, struct request *) next_request;
    void (*)(struct io_cq *) init_icq;
    void (*)(struct io_cq *) exit_icq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct elevator_mq_ops {
    int (*)(struct request_queue *, struct elevator_type *) init_sched;
    void (*)(struct elevator_queue *) exit_sched;
    int (*)(struct blk_mq_hw_ctx *, unsigned int) init_hctx;
    void (*)(struct blk_mq_hw_ctx *, unsigned int) exit_hctx;
    void (*)(struct blk_mq_hw_ctx *) depth_updated;
    bool (*)(struct request_queue *, struct request *, struct bio *) allow_merge;
    bool (*)(struct request_queue *, struct bio *, unsigned int) bio_merge;
    int (*)(struct request_queue *, struct request * *, struct bio *) request_merge;
    void (*)(struct request_queue *, struct request *, enum elv_merge) request_merged;
    void (*)(struct request_queue *, struct request *, struct request *) requests_merged;
    void (*)(unsigned int, struct blk_mq_alloc_data *) limit_depth;
    void (*)(struct request *) prepare_request;
    void (*)(struct request *) finish_request;
    void (*)(struct blk_mq_hw_ctx *, struct list_head *, bool) insert_requests;
    struct request * (*)(struct blk_mq_hw_ctx *) dispatch_request;
    bool (*)(struct blk_mq_hw_ctx *) has_work;
    void (*)(struct request *, u64) completed_request;
    void (*)(struct request *) requeue_request;
    struct request * (*)(struct request_queue *, struct request *) former_request;
    struct request * (*)(struct request_queue *, struct request *) next_request;
    void (*)(struct io_cq *) init_icq;
    void (*)(struct io_cq *) exit_icq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct elevator_mq_ops {
    int (*)(struct request_queue *, struct elevator_type *) init_sched;
    void (*)(struct elevator_queue *) exit_sched;
    int (*)(struct blk_mq_hw_ctx *, unsigned int) init_hctx;
    void (*)(struct blk_mq_hw_ctx *, unsigned int) exit_hctx;
    void (*)(struct blk_mq_hw_ctx *) depth_updated;
    bool (*)(struct request_queue *, struct request *, struct bio *) allow_merge;
    bool (*)(struct request_queue *, struct bio *, unsigned int) bio_merge;
    int (*)(struct request_queue *, struct request * *, struct bio *) request_merge;
    void (*)(struct request_queue *, struct request *, enum elv_merge) request_merged;
    void (*)(struct request_queue *, struct request *, struct request *) requests_merged;
    void (*)(unsigned int, struct blk_mq_alloc_data *) limit_depth;
    void (*)(struct request *) prepare_request;
    void (*)(struct request *) finish_request;
    void (*)(struct blk_mq_hw_ctx *, struct list_head *, bool) insert_requests;
    struct request * (*)(struct blk_mq_hw_ctx *) dispatch_request;
    bool (*)(struct blk_mq_hw_ctx *) has_work;
    void (*)(struct request *, u64) completed_request;
    void (*)(struct request *) requeue_request;
    struct request * (*)(struct request_queue *, struct request *) former_request;
    struct request * (*)(struct request_queue *, struct request *) next_request;
    void (*)(struct io_cq *) init_icq;
    void (*)(struct io_cq *) exit_icq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct elevator_mq_ops {
    int (*)(struct request_queue *, struct elevator_type *) init_sched;
    void (*)(struct elevator_queue *) exit_sched;
    int (*)(struct blk_mq_hw_ctx *, unsigned int) init_hctx;
    void (*)(struct blk_mq_hw_ctx *, unsigned int) exit_hctx;
    void (*)(struct blk_mq_hw_ctx *) depth_updated;
    bool (*)(struct request_queue *, struct request *, struct bio *) allow_merge;
    bool (*)(struct request_queue *, struct bio *, unsigned int) bio_merge;
    int (*)(struct request_queue *, struct request * *, struct bio *) request_merge;
    void (*)(struct request_queue *, struct request *, enum elv_merge) request_merged;
    void (*)(struct request_queue *, struct request *, struct request *) requests_merged;
    void (*)(blk_opf_t, struct blk_mq_alloc_data *) limit_depth;
    void (*)(struct request *) prepare_request;
    void (*)(struct request *) finish_request;
    void (*)(struct blk_mq_hw_ctx *, struct list_head *, bool) insert_requests;
    struct request * (*)(struct blk_mq_hw_ctx *) dispatch_request;
    bool (*)(struct blk_mq_hw_ctx *) has_work;
    void (*)(struct request *, u64) completed_request;
    void (*)(struct request *) requeue_request;
    struct request * (*)(struct request_queue *, struct request *) former_request;
    struct request * (*)(struct request_queue *, struct request *) next_request;
    void (*)(struct io_cq *) init_icq;
    void (*)(struct io_cq *) exit_icq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct elevator_mq_ops {
    int (*)(struct request_queue *, struct elevator_type *) init_sched;
    void (*)(struct elevator_queue *) exit_sched;
    int (*)(struct blk_mq_hw_ctx *, unsigned int) init_hctx;
    void (*)(struct blk_mq_hw_ctx *, unsigned int) exit_hctx;
    void (*)(struct blk_mq_hw_ctx *) depth_updated;
    bool (*)(struct request_queue *, struct request *, struct bio *) allow_merge;
    bool (*)(struct request_queue *, struct bio *, unsigned int) bio_merge;
    int (*)(struct request_queue *, struct request * *, struct bio *) request_merge;
    void (*)(struct request_queue *, struct request *, enum elv_merge) request_merged;
    void (*)(struct request_queue *, struct request *, struct request *) requests_merged;
    void (*)(blk_opf_t, struct blk_mq_alloc_data *) limit_depth;
    void (*)(struct request *) prepare_request;
    void (*)(struct request *) finish_request;
    void (*)(struct blk_mq_hw_ctx *, struct list_head *, blk_insert_t) insert_requests;
    struct request * (*)(struct blk_mq_hw_ctx *) dispatch_request;
    bool (*)(struct blk_mq_hw_ctx *) has_work;
    void (*)(struct request *, u64) completed_request;
    void (*)(struct request *) requeue_request;
    struct request * (*)(struct request_queue *, struct request *) former_request;
    struct request * (*)(struct request_queue *, struct request *) next_request;
    void (*)(struct io_cq *) init_icq;
    void (*)(struct io_cq *) exit_icq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct elevator_mq_ops {
    int (*)(struct request_queue *, struct elevator_type *) init_sched;
    void (*)(struct elevator_queue *) exit_sched;
    int (*)(struct blk_mq_hw_ctx *, unsigned int) init_hctx;
    void (*)(struct blk_mq_hw_ctx *, unsigned int) exit_hctx;
    void (*)(struct blk_mq_hw_ctx *) depth_updated;
    bool (*)(struct request_queue *, struct request *, struct bio *) allow_merge;
    bool (*)(struct request_queue *, struct bio *, unsigned int) bio_merge;
    int (*)(struct request_queue *, struct request * *, struct bio *) request_merge;
    void (*)(struct request_queue *, struct request *, enum elv_merge) request_merged;
    void (*)(struct request_queue *, struct request *, struct request *) requests_merged;
    void (*)(blk_opf_t, struct blk_mq_alloc_data *) limit_depth;
    void (*)(struct request *) prepare_request;
    void (*)(struct request *) finish_request;
    void (*)(struct blk_mq_hw_ctx *, struct list_head *, blk_insert_t) insert_requests;
    struct request * (*)(struct blk_mq_hw_ctx *) dispatch_request;
    bool (*)(struct blk_mq_hw_ctx *) has_work;
    void (*)(struct request *, u64) completed_request;
    void (*)(struct request *) requeue_request;
    struct request * (*)(struct request_queue *, struct request *) former_request;
    struct request * (*)(struct request_queue *, struct request *) next_request;
    void (*)(struct io_cq *) init_icq;
    void (*)(struct io_cq *) exit_icq;
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
struct elevator_mq_ops {
    int (*)(struct request_queue *, struct elevator_type *) init_sched;
    void (*)(struct elevator_queue *) exit_sched;
    int (*)(struct blk_mq_hw_ctx *, unsigned int) init_hctx;
    void (*)(struct blk_mq_hw_ctx *, unsigned int) exit_hctx;
    void (*)(struct blk_mq_hw_ctx *) depth_updated;
    bool (*)(struct request_queue *, struct request *, struct bio *) allow_merge;
    bool (*)(struct blk_mq_hw_ctx *, struct bio *, unsigned int) bio_merge;
    int (*)(struct request_queue *, struct request * *, struct bio *) request_merge;
    void (*)(struct request_queue *, struct request *, enum elv_merge) request_merged;
    void (*)(struct request_queue *, struct request *, struct request *) requests_merged;
    void (*)(unsigned int, struct blk_mq_alloc_data *) limit_depth;
    void (*)(struct request *, struct bio *) prepare_request;
    void (*)(struct request *) finish_request;
    void (*)(struct blk_mq_hw_ctx *, struct list_head *, bool) insert_requests;
    struct request * (*)(struct blk_mq_hw_ctx *) dispatch_request;
    bool (*)(struct blk_mq_hw_ctx *) has_work;
    void (*)(struct request *, u64) completed_request;
    void (*)(struct request *) requeue_request;
    struct request * (*)(struct request_queue *, struct request *) former_request;
    struct request * (*)(struct request_queue *, struct request *) next_request;
    void (*)(struct io_cq *) init_icq;
    void (*)(struct io_cq *) exit_icq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct elevator_mq_ops {
    int (*)(struct request_queue *, struct elevator_type *) init_sched;
    void (*)(struct elevator_queue *) exit_sched;
    int (*)(struct blk_mq_hw_ctx *, unsigned int) init_hctx;
    void (*)(struct blk_mq_hw_ctx *, unsigned int) exit_hctx;
    void (*)(struct blk_mq_hw_ctx *) depth_updated;
    bool (*)(struct request_queue *, struct request *, struct bio *) allow_merge;
    bool (*)(struct blk_mq_hw_ctx *, struct bio *, unsigned int) bio_merge;
    int (*)(struct request_queue *, struct request * *, struct bio *) request_merge;
    void (*)(struct request_queue *, struct request *, enum elv_merge) request_merged;
    void (*)(struct request_queue *, struct request *, struct request *) requests_merged;
    void (*)(unsigned int, struct blk_mq_alloc_data *) limit_depth;
    void (*)(struct request *, struct bio *) prepare_request;
    void (*)(struct request *) finish_request;
    void (*)(struct blk_mq_hw_ctx *, struct list_head *, bool) insert_requests;
    struct request * (*)(struct blk_mq_hw_ctx *) dispatch_request;
    bool (*)(struct blk_mq_hw_ctx *) has_work;
    void (*)(struct request *, u64) completed_request;
    void (*)(struct request *) requeue_request;
    struct request * (*)(struct request_queue *, struct request *) former_request;
    struct request * (*)(struct request_queue *, struct request *) next_request;
    void (*)(struct io_cq *) init_icq;
    void (*)(struct io_cq *) exit_icq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct elevator_mq_ops {
    int (*)(struct request_queue *, struct elevator_type *) init_sched;
    void (*)(struct elevator_queue *) exit_sched;
    int (*)(struct blk_mq_hw_ctx *, unsigned int) init_hctx;
    void (*)(struct blk_mq_hw_ctx *, unsigned int) exit_hctx;
    void (*)(struct blk_mq_hw_ctx *) depth_updated;
    bool (*)(struct request_queue *, struct request *, struct bio *) allow_merge;
    bool (*)(struct blk_mq_hw_ctx *, struct bio *, unsigned int) bio_merge;
    int (*)(struct request_queue *, struct request * *, struct bio *) request_merge;
    void (*)(struct request_queue *, struct request *, enum elv_merge) request_merged;
    void (*)(struct request_queue *, struct request *, struct request *) requests_merged;
    void (*)(unsigned int, struct blk_mq_alloc_data *) limit_depth;
    void (*)(struct request *, struct bio *) prepare_request;
    void (*)(struct request *) finish_request;
    void (*)(struct blk_mq_hw_ctx *, struct list_head *, bool) insert_requests;
    struct request * (*)(struct blk_mq_hw_ctx *) dispatch_request;
    bool (*)(struct blk_mq_hw_ctx *) has_work;
    void (*)(struct request *, u64) completed_request;
    void (*)(struct request *) requeue_request;
    struct request * (*)(struct request_queue *, struct request *) former_request;
    struct request * (*)(struct request_queue *, struct request *) next_request;
    void (*)(struct io_cq *) init_icq;
    void (*)(struct io_cq *) exit_icq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct elevator_mq_ops {
    int (*)(struct request_queue *, struct elevator_type *) init_sched;
    void (*)(struct elevator_queue *) exit_sched;
    int (*)(struct blk_mq_hw_ctx *, unsigned int) init_hctx;
    void (*)(struct blk_mq_hw_ctx *, unsigned int) exit_hctx;
    void (*)(struct blk_mq_hw_ctx *) depth_updated;
    bool (*)(struct request_queue *, struct request *, struct bio *) allow_merge;
    bool (*)(struct blk_mq_hw_ctx *, struct bio *, unsigned int) bio_merge;
    int (*)(struct request_queue *, struct request * *, struct bio *) request_merge;
    void (*)(struct request_queue *, struct request *, enum elv_merge) request_merged;
    void (*)(struct request_queue *, struct request *, struct request *) requests_merged;
    void (*)(unsigned int, struct blk_mq_alloc_data *) limit_depth;
    void (*)(struct request *, struct bio *) prepare_request;
    void (*)(struct request *) finish_request;
    void (*)(struct blk_mq_hw_ctx *, struct list_head *, bool) insert_requests;
    struct request * (*)(struct blk_mq_hw_ctx *) dispatch_request;
    bool (*)(struct blk_mq_hw_ctx *) has_work;
    void (*)(struct request *, u64) completed_request;
    void (*)(struct request *) requeue_request;
    struct request * (*)(struct request_queue *, struct request *) former_request;
    struct request * (*)(struct request_queue *, struct request *) next_request;
    void (*)(struct io_cq *) init_icq;
    void (*)(struct io_cq *) exit_icq;
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
struct elevator_mq_ops {
    int (*)(struct request_queue *, struct elevator_type *) init_sched;
    void (*)(struct elevator_queue *) exit_sched;
    int (*)(struct blk_mq_hw_ctx *, unsigned int) init_hctx;
    void (*)(struct blk_mq_hw_ctx *, unsigned int) exit_hctx;
    void (*)(struct blk_mq_hw_ctx *) depth_updated;
    bool (*)(struct request_queue *, struct request *, struct bio *) allow_merge;
    bool (*)(struct blk_mq_hw_ctx *, struct bio *, unsigned int) bio_merge;
    int (*)(struct request_queue *, struct request * *, struct bio *) request_merge;
    void (*)(struct request_queue *, struct request *, enum elv_merge) request_merged;
    void (*)(struct request_queue *, struct request *, struct request *) requests_merged;
    void (*)(unsigned int, struct blk_mq_alloc_data *) limit_depth;
    void (*)(struct request *, struct bio *) prepare_request;
    void (*)(struct request *) finish_request;
    void (*)(struct blk_mq_hw_ctx *, struct list_head *, bool) insert_requests;
    struct request * (*)(struct blk_mq_hw_ctx *) dispatch_request;
    bool (*)(struct blk_mq_hw_ctx *) has_work;
    void (*)(struct request *, u64) completed_request;
    void (*)(struct request *) requeue_request;
    struct request * (*)(struct request_queue *, struct request *) former_request;
    struct request * (*)(struct request_queue *, struct request *) next_request;
    void (*)(struct io_cq *) init_icq;
    void (*)(struct io_cq *) exit_icq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct elevator_mq_ops {
    int (*)(struct request_queue *, struct elevator_type *) init_sched;
    void (*)(struct elevator_queue *) exit_sched;
    int (*)(struct blk_mq_hw_ctx *, unsigned int) init_hctx;
    void (*)(struct blk_mq_hw_ctx *, unsigned int) exit_hctx;
    void (*)(struct blk_mq_hw_ctx *) depth_updated;
    bool (*)(struct request_queue *, struct request *, struct bio *) allow_merge;
    bool (*)(struct blk_mq_hw_ctx *, struct bio *, unsigned int) bio_merge;
    int (*)(struct request_queue *, struct request * *, struct bio *) request_merge;
    void (*)(struct request_queue *, struct request *, enum elv_merge) request_merged;
    void (*)(struct request_queue *, struct request *, struct request *) requests_merged;
    void (*)(unsigned int, struct blk_mq_alloc_data *) limit_depth;
    void (*)(struct request *, struct bio *) prepare_request;
    void (*)(struct request *) finish_request;
    void (*)(struct blk_mq_hw_ctx *, struct list_head *, bool) insert_requests;
    struct request * (*)(struct blk_mq_hw_ctx *) dispatch_request;
    bool (*)(struct blk_mq_hw_ctx *) has_work;
    void (*)(struct request *, u64) completed_request;
    void (*)(struct request *) requeue_request;
    struct request * (*)(struct request_queue *, struct request *) former_request;
    struct request * (*)(struct request_queue *, struct request *) next_request;
    void (*)(struct io_cq *) init_icq;
    void (*)(struct io_cq *) exit_icq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct elevator_mq_ops {
    int (*)(struct request_queue *, struct elevator_type *) init_sched;
    void (*)(struct elevator_queue *) exit_sched;
    int (*)(struct blk_mq_hw_ctx *, unsigned int) init_hctx;
    void (*)(struct blk_mq_hw_ctx *, unsigned int) exit_hctx;
    void (*)(struct blk_mq_hw_ctx *) depth_updated;
    bool (*)(struct request_queue *, struct request *, struct bio *) allow_merge;
    bool (*)(struct blk_mq_hw_ctx *, struct bio *, unsigned int) bio_merge;
    int (*)(struct request_queue *, struct request * *, struct bio *) request_merge;
    void (*)(struct request_queue *, struct request *, enum elv_merge) request_merged;
    void (*)(struct request_queue *, struct request *, struct request *) requests_merged;
    void (*)(unsigned int, struct blk_mq_alloc_data *) limit_depth;
    void (*)(struct request *, struct bio *) prepare_request;
    void (*)(struct request *) finish_request;
    void (*)(struct blk_mq_hw_ctx *, struct list_head *, bool) insert_requests;
    struct request * (*)(struct blk_mq_hw_ctx *) dispatch_request;
    bool (*)(struct blk_mq_hw_ctx *) has_work;
    void (*)(struct request *, u64) completed_request;
    void (*)(struct request *) requeue_request;
    struct request * (*)(struct request_queue *, struct request *) former_request;
    struct request * (*)(struct request_queue *, struct request *) next_request;
    void (*)(struct io_cq *) init_icq;
    void (*)(struct io_cq *) exit_icq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct elevator_mq_ops {
    int (*)(struct request_queue *, struct elevator_type *) init_sched;
    void (*)(struct elevator_queue *) exit_sched;
    int (*)(struct blk_mq_hw_ctx *, unsigned int) init_hctx;
    void (*)(struct blk_mq_hw_ctx *, unsigned int) exit_hctx;
    void (*)(struct blk_mq_hw_ctx *) depth_updated;
    bool (*)(struct request_queue *, struct request *, struct bio *) allow_merge;
    bool (*)(struct blk_mq_hw_ctx *, struct bio *, unsigned int) bio_merge;
    int (*)(struct request_queue *, struct request * *, struct bio *) request_merge;
    void (*)(struct request_queue *, struct request *, enum elv_merge) request_merged;
    void (*)(struct request_queue *, struct request *, struct request *) requests_merged;
    void (*)(unsigned int, struct blk_mq_alloc_data *) limit_depth;
    void (*)(struct request *, struct bio *) prepare_request;
    void (*)(struct request *) finish_request;
    void (*)(struct blk_mq_hw_ctx *, struct list_head *, bool) insert_requests;
    struct request * (*)(struct blk_mq_hw_ctx *) dispatch_request;
    bool (*)(struct blk_mq_hw_ctx *) has_work;
    void (*)(struct request *, u64) completed_request;
    void (*)(struct request *) requeue_request;
    struct request * (*)(struct request_queue *, struct request *) former_request;
    struct request * (*)(struct request_queue *, struct request *) next_request;
    void (*)(struct io_cq *) init_icq;
    void (*)(struct io_cq *) exit_icq;
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct elevator_mq_ops {
    int (*)(struct request_queue *, struct elevator_type *) init_sched;
    void (*)(struct elevator_queue *) exit_sched;
    int (*)(struct blk_mq_hw_ctx *, unsigned int) init_hctx;
    void (*)(struct blk_mq_hw_ctx *, unsigned int) exit_hctx;
    bool (*)(struct request_queue *, struct request *, struct bio *) allow_merge;
    bool (*)(struct blk_mq_hw_ctx *, struct bio *) bio_merge;
    int (*)(struct request_queue *, struct request * *, struct bio *) request_merge;
    void (*)(struct request_queue *, struct request *, enum elv_merge) request_merged;
    void (*)(struct request_queue *, struct request *, struct request *) requests_merged;
    void (*)(unsigned int, struct blk_mq_alloc_data *) limit_depth;
    void (*)(struct request *, struct bio *) prepare_request;
    void (*)(struct request *) finish_request;
    void (*)(struct blk_mq_hw_ctx *, struct list_head *, bool) insert_requests;
    struct request * (*)(struct blk_mq_hw_ctx *) dispatch_request;
    bool (*)(struct blk_mq_hw_ctx *) has_work;
    void (*)(struct request *) completed_request;
    void (*)(struct request *) started_request;
    void (*)(struct request *) requeue_request;
    struct request * (*)(struct request_queue *, struct request *) former_request;
    struct request * (*)(struct request_queue *, struct request *) next_request;
    void (*)(struct io_cq *) init_icq;
    void (*)(struct io_cq *) exit_icq;
}
```
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
<b>Field type changed. </b>
<code>void (*)(struct request *) completed_request</code> ➡️ <code>void (*)(struct request *, u64) completed_request</code>
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
<code>void (*)(struct blk_mq_hw_ctx *) depth_updated</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct request *) started_request</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool (*)(struct blk_mq_hw_ctx *, struct bio *) bio_merge</code> ➡️ <code>bool (*)(struct blk_mq_hw_ctx *, struct bio *, unsigned int) bio_merge</code>
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
<b>Field type changed. </b>
<code>void (*)(struct request *, struct bio *) prepare_request</code> ➡️ <code>void (*)(struct request *) prepare_request</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>bool (*)(struct blk_mq_hw_ctx *, struct bio *, unsigned int) bio_merge</code> ➡️ <code>bool (*)(struct request_queue *, struct bio *, unsigned int) bio_merge</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>void (*)(unsigned int, struct blk_mq_alloc_data *) limit_depth</code> ➡️ <code>void (*)(blk_opf_t, struct blk_mq_alloc_data *) limit_depth</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>void (*)(struct blk_mq_hw_ctx *, struct list_head *, bool) insert_requests</code> ➡️ <code>void (*)(struct blk_mq_hw_ctx *, struct list_head *, blk_insert_t) insert_requests</code>
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
