# Struct: <code>blk_mq_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_ops {
    queue_rq_fn * queue_rq;
    map_queue_fn * map_queue;
    timeout_fn * timeout;
    poll_fn * poll;
    softirq_done_fn * complete;
    init_hctx_fn * init_hctx;
    exit_hctx_fn * exit_hctx;
    init_request_fn * init_request;
    exit_request_fn * exit_request;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_ops {
    queue_rq_fn * queue_rq;
    map_queue_fn * map_queue;
    timeout_fn * timeout;
    poll_fn * poll;
    softirq_done_fn * complete;
    init_hctx_fn * init_hctx;
    exit_hctx_fn * exit_hctx;
    init_request_fn * init_request;
    exit_request_fn * exit_request;
    reinit_request_fn * reinit_request;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_ops {
    queue_rq_fn * queue_rq;
    timeout_fn * timeout;
    poll_fn * poll;
    softirq_done_fn * complete;
    init_hctx_fn * init_hctx;
    exit_hctx_fn * exit_hctx;
    init_request_fn * init_request;
    exit_request_fn * exit_request;
    reinit_request_fn * reinit_request;
    map_queues_fn * map_queues;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_ops {
    queue_rq_fn * queue_rq;
    timeout_fn * timeout;
    poll_fn * poll;
    softirq_done_fn * complete;
    init_hctx_fn * init_hctx;
    exit_hctx_fn * exit_hctx;
    init_request_fn * init_request;
    exit_request_fn * exit_request;
    reinit_request_fn * reinit_request;
    void (*)(struct request *) initialize_rq_fn;
    map_queues_fn * map_queues;
    void (*)(struct seq_file *, struct request *) show_rq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_ops {
    queue_rq_fn * queue_rq;
    get_budget_fn * get_budget;
    put_budget_fn * put_budget;
    timeout_fn * timeout;
    poll_fn * poll;
    softirq_done_fn * complete;
    init_hctx_fn * init_hctx;
    exit_hctx_fn * exit_hctx;
    init_request_fn * init_request;
    exit_request_fn * exit_request;
    void (*)(struct request *) initialize_rq_fn;
    map_queues_fn * map_queues;
    void (*)(struct seq_file *, struct request *) show_rq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_ops {
    queue_rq_fn * queue_rq;
    get_budget_fn * get_budget;
    put_budget_fn * put_budget;
    timeout_fn * timeout;
    poll_fn * poll;
    softirq_done_fn * complete;
    init_hctx_fn * init_hctx;
    exit_hctx_fn * exit_hctx;
    init_request_fn * init_request;
    exit_request_fn * exit_request;
    void (*)(struct request *) initialize_rq_fn;
    map_queues_fn * map_queues;
    void (*)(struct seq_file *, struct request *) show_rq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_ops {
    queue_rq_fn * queue_rq;
    commit_rqs_fn * commit_rqs;
    get_budget_fn * get_budget;
    put_budget_fn * put_budget;
    timeout_fn * timeout;
    poll_fn * poll;
    complete_fn * complete;
    init_hctx_fn * init_hctx;
    exit_hctx_fn * exit_hctx;
    init_request_fn * init_request;
    exit_request_fn * exit_request;
    void (*)(struct request *) initialize_rq_fn;
    busy_fn * busy;
    map_queues_fn * map_queues;
    void (*)(struct seq_file *, struct request *) show_rq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_ops {
    queue_rq_fn * queue_rq;
    commit_rqs_fn * commit_rqs;
    get_budget_fn * get_budget;
    put_budget_fn * put_budget;
    timeout_fn * timeout;
    poll_fn * poll;
    complete_fn * complete;
    init_hctx_fn * init_hctx;
    exit_hctx_fn * exit_hctx;
    init_request_fn * init_request;
    exit_request_fn * exit_request;
    void (*)(struct request *) initialize_rq_fn;
    busy_fn * busy;
    map_queues_fn * map_queues;
    void (*)(struct seq_file *, struct request *) show_rq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_ops {
    queue_rq_fn * queue_rq;
    commit_rqs_fn * commit_rqs;
    get_budget_fn * get_budget;
    put_budget_fn * put_budget;
    timeout_fn * timeout;
    poll_fn * poll;
    complete_fn * complete;
    init_hctx_fn * init_hctx;
    exit_hctx_fn * exit_hctx;
    init_request_fn * init_request;
    exit_request_fn * exit_request;
    void (*)(struct request *) initialize_rq_fn;
    cleanup_rq_fn * cleanup_rq;
    busy_fn * busy;
    map_queues_fn * map_queues;
    void (*)(struct seq_file *, struct request *) show_rq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_ops {
    queue_rq_fn * queue_rq;
    commit_rqs_fn * commit_rqs;
    get_budget_fn * get_budget;
    put_budget_fn * put_budget;
    timeout_fn * timeout;
    poll_fn * poll;
    complete_fn * complete;
    init_hctx_fn * init_hctx;
    exit_hctx_fn * exit_hctx;
    init_request_fn * init_request;
    exit_request_fn * exit_request;
    void (*)(struct request *) initialize_rq_fn;
    cleanup_rq_fn * cleanup_rq;
    busy_fn * busy;
    map_queues_fn * map_queues;
    void (*)(struct seq_file *, struct request *) show_rq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_ops {
    blk_status_t (*)(struct blk_mq_hw_ctx *, const struct blk_mq_queue_data *) queue_rq;
    void (*)(struct blk_mq_hw_ctx *) commit_rqs;
    bool (*)(struct request_queue *) get_budget;
    void (*)(struct request_queue *) put_budget;
    enum blk_eh_timer_return (*)(struct request *, bool) timeout;
    int (*)(struct blk_mq_hw_ctx *) poll;
    void (*)(struct request *) complete;
    int (*)(struct blk_mq_hw_ctx *, void *, unsigned int) init_hctx;
    void (*)(struct blk_mq_hw_ctx *, unsigned int) exit_hctx;
    int (*)(struct blk_mq_tag_set *, struct request *, unsigned int, unsigned int) init_request;
    void (*)(struct blk_mq_tag_set *, struct request *, unsigned int) exit_request;
    void (*)(struct request *) initialize_rq_fn;
    void (*)(struct request *) cleanup_rq;
    bool (*)(struct request_queue *) busy;
    int (*)(struct blk_mq_tag_set *) map_queues;
    void (*)(struct seq_file *, struct request *) show_rq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_ops {
    blk_status_t (*)(struct blk_mq_hw_ctx *, const struct blk_mq_queue_data *) queue_rq;
    void (*)(struct blk_mq_hw_ctx *) commit_rqs;
    int (*)(struct request_queue *) get_budget;
    void (*)(struct request_queue *, int) put_budget;
    void (*)(struct request *, int) set_rq_budget_token;
    int (*)(struct request *) get_rq_budget_token;
    enum blk_eh_timer_return (*)(struct request *, bool) timeout;
    int (*)(struct blk_mq_hw_ctx *) poll;
    void (*)(struct request *) complete;
    int (*)(struct blk_mq_hw_ctx *, void *, unsigned int) init_hctx;
    void (*)(struct blk_mq_hw_ctx *, unsigned int) exit_hctx;
    int (*)(struct blk_mq_tag_set *, struct request *, unsigned int, unsigned int) init_request;
    void (*)(struct blk_mq_tag_set *, struct request *, unsigned int) exit_request;
    void (*)(struct request *) initialize_rq_fn;
    void (*)(struct request *) cleanup_rq;
    bool (*)(struct request_queue *) busy;
    int (*)(struct blk_mq_tag_set *) map_queues;
    void (*)(struct seq_file *, struct request *) show_rq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_ops {
    blk_status_t (*)(struct blk_mq_hw_ctx *, const struct blk_mq_queue_data *) queue_rq;
    void (*)(struct blk_mq_hw_ctx *) commit_rqs;
    int (*)(struct request_queue *) get_budget;
    void (*)(struct request_queue *, int) put_budget;
    void (*)(struct request *, int) set_rq_budget_token;
    int (*)(struct request *) get_rq_budget_token;
    enum blk_eh_timer_return (*)(struct request *, bool) timeout;
    int (*)(struct blk_mq_hw_ctx *) poll;
    void (*)(struct request *) complete;
    int (*)(struct blk_mq_hw_ctx *, void *, unsigned int) init_hctx;
    void (*)(struct blk_mq_hw_ctx *, unsigned int) exit_hctx;
    int (*)(struct blk_mq_tag_set *, struct request *, unsigned int, unsigned int) init_request;
    void (*)(struct blk_mq_tag_set *, struct request *, unsigned int) exit_request;
    void (*)(struct request *) initialize_rq_fn;
    void (*)(struct request *) cleanup_rq;
    bool (*)(struct request_queue *) busy;
    int (*)(struct blk_mq_tag_set *) map_queues;
    void (*)(struct seq_file *, struct request *) show_rq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_ops {
    blk_status_t (*)(struct blk_mq_hw_ctx *, const struct blk_mq_queue_data *) queue_rq;
    void (*)(struct blk_mq_hw_ctx *) commit_rqs;
    void (*)(struct request * *) queue_rqs;
    int (*)(struct request_queue *) get_budget;
    void (*)(struct request_queue *, int) put_budget;
    void (*)(struct request *, int) set_rq_budget_token;
    int (*)(struct request *) get_rq_budget_token;
    enum blk_eh_timer_return (*)(struct request *, bool) timeout;
    int (*)(struct blk_mq_hw_ctx *, struct io_comp_batch *) poll;
    void (*)(struct request *) complete;
    int (*)(struct blk_mq_hw_ctx *, void *, unsigned int) init_hctx;
    void (*)(struct blk_mq_hw_ctx *, unsigned int) exit_hctx;
    int (*)(struct blk_mq_tag_set *, struct request *, unsigned int, unsigned int) init_request;
    void (*)(struct blk_mq_tag_set *, struct request *, unsigned int) exit_request;
    void (*)(struct request *) cleanup_rq;
    bool (*)(struct request_queue *) busy;
    int (*)(struct blk_mq_tag_set *) map_queues;
    void (*)(struct seq_file *, struct request *) show_rq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_ops {
    blk_status_t (*)(struct blk_mq_hw_ctx *, const struct blk_mq_queue_data *) queue_rq;
    void (*)(struct blk_mq_hw_ctx *) commit_rqs;
    void (*)(struct request * *) queue_rqs;
    int (*)(struct request_queue *) get_budget;
    void (*)(struct request_queue *, int) put_budget;
    void (*)(struct request *, int) set_rq_budget_token;
    int (*)(struct request *) get_rq_budget_token;
    enum blk_eh_timer_return (*)(struct request *) timeout;
    int (*)(struct blk_mq_hw_ctx *, struct io_comp_batch *) poll;
    void (*)(struct request *) complete;
    int (*)(struct blk_mq_hw_ctx *, void *, unsigned int) init_hctx;
    void (*)(struct blk_mq_hw_ctx *, unsigned int) exit_hctx;
    int (*)(struct blk_mq_tag_set *, struct request *, unsigned int, unsigned int) init_request;
    void (*)(struct blk_mq_tag_set *, struct request *, unsigned int) exit_request;
    void (*)(struct request *) cleanup_rq;
    bool (*)(struct request_queue *) busy;
    void (*)(struct blk_mq_tag_set *) map_queues;
    void (*)(struct seq_file *, struct request *) show_rq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_ops {
    blk_status_t (*)(struct blk_mq_hw_ctx *, const struct blk_mq_queue_data *) queue_rq;
    void (*)(struct blk_mq_hw_ctx *) commit_rqs;
    void (*)(struct request * *) queue_rqs;
    int (*)(struct request_queue *) get_budget;
    void (*)(struct request_queue *, int) put_budget;
    void (*)(struct request *, int) set_rq_budget_token;
    int (*)(struct request *) get_rq_budget_token;
    enum blk_eh_timer_return (*)(struct request *) timeout;
    int (*)(struct blk_mq_hw_ctx *, struct io_comp_batch *) poll;
    void (*)(struct request *) complete;
    int (*)(struct blk_mq_hw_ctx *, void *, unsigned int) init_hctx;
    void (*)(struct blk_mq_hw_ctx *, unsigned int) exit_hctx;
    int (*)(struct blk_mq_tag_set *, struct request *, unsigned int, unsigned int) init_request;
    void (*)(struct blk_mq_tag_set *, struct request *, unsigned int) exit_request;
    void (*)(struct request *) cleanup_rq;
    bool (*)(struct request_queue *) busy;
    void (*)(struct blk_mq_tag_set *) map_queues;
    void (*)(struct seq_file *, struct request *) show_rq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_ops {
    blk_status_t (*)(struct blk_mq_hw_ctx *, const struct blk_mq_queue_data *) queue_rq;
    void (*)(struct blk_mq_hw_ctx *) commit_rqs;
    void (*)(struct request * *) queue_rqs;
    int (*)(struct request_queue *) get_budget;
    void (*)(struct request_queue *, int) put_budget;
    void (*)(struct request *, int) set_rq_budget_token;
    int (*)(struct request *) get_rq_budget_token;
    enum blk_eh_timer_return (*)(struct request *) timeout;
    int (*)(struct blk_mq_hw_ctx *, struct io_comp_batch *) poll;
    void (*)(struct request *) complete;
    int (*)(struct blk_mq_hw_ctx *, void *, unsigned int) init_hctx;
    void (*)(struct blk_mq_hw_ctx *, unsigned int) exit_hctx;
    int (*)(struct blk_mq_tag_set *, struct request *, unsigned int, unsigned int) init_request;
    void (*)(struct blk_mq_tag_set *, struct request *, unsigned int) exit_request;
    void (*)(struct request *) cleanup_rq;
    bool (*)(struct request_queue *) busy;
    void (*)(struct blk_mq_tag_set *) map_queues;
    void (*)(struct seq_file *, struct request *) show_rq;
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
struct blk_mq_ops {
    queue_rq_fn * queue_rq;
    commit_rqs_fn * commit_rqs;
    get_budget_fn * get_budget;
    put_budget_fn * put_budget;
    timeout_fn * timeout;
    poll_fn * poll;
    complete_fn * complete;
    init_hctx_fn * init_hctx;
    exit_hctx_fn * exit_hctx;
    init_request_fn * init_request;
    exit_request_fn * exit_request;
    void (*)(struct request *) initialize_rq_fn;
    cleanup_rq_fn * cleanup_rq;
    busy_fn * busy;
    map_queues_fn * map_queues;
    void (*)(struct seq_file *, struct request *) show_rq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct blk_mq_ops {
    queue_rq_fn * queue_rq;
    commit_rqs_fn * commit_rqs;
    get_budget_fn * get_budget;
    put_budget_fn * put_budget;
    timeout_fn * timeout;
    poll_fn * poll;
    complete_fn * complete;
    init_hctx_fn * init_hctx;
    exit_hctx_fn * exit_hctx;
    init_request_fn * init_request;
    exit_request_fn * exit_request;
    void (*)(struct request *) initialize_rq_fn;
    cleanup_rq_fn * cleanup_rq;
    busy_fn * busy;
    map_queues_fn * map_queues;
    void (*)(struct seq_file *, struct request *) show_rq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct blk_mq_ops {
    queue_rq_fn * queue_rq;
    commit_rqs_fn * commit_rqs;
    get_budget_fn * get_budget;
    put_budget_fn * put_budget;
    timeout_fn * timeout;
    poll_fn * poll;
    complete_fn * complete;
    init_hctx_fn * init_hctx;
    exit_hctx_fn * exit_hctx;
    init_request_fn * init_request;
    exit_request_fn * exit_request;
    void (*)(struct request *) initialize_rq_fn;
    cleanup_rq_fn * cleanup_rq;
    busy_fn * busy;
    map_queues_fn * map_queues;
    void (*)(struct seq_file *, struct request *) show_rq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct blk_mq_ops {
    queue_rq_fn * queue_rq;
    commit_rqs_fn * commit_rqs;
    get_budget_fn * get_budget;
    put_budget_fn * put_budget;
    timeout_fn * timeout;
    poll_fn * poll;
    complete_fn * complete;
    init_hctx_fn * init_hctx;
    exit_hctx_fn * exit_hctx;
    init_request_fn * init_request;
    exit_request_fn * exit_request;
    void (*)(struct request *) initialize_rq_fn;
    cleanup_rq_fn * cleanup_rq;
    busy_fn * busy;
    map_queues_fn * map_queues;
    void (*)(struct seq_file *, struct request *) show_rq;
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
struct blk_mq_ops {
    queue_rq_fn * queue_rq;
    commit_rqs_fn * commit_rqs;
    get_budget_fn * get_budget;
    put_budget_fn * put_budget;
    timeout_fn * timeout;
    poll_fn * poll;
    complete_fn * complete;
    init_hctx_fn * init_hctx;
    exit_hctx_fn * exit_hctx;
    init_request_fn * init_request;
    exit_request_fn * exit_request;
    void (*)(struct request *) initialize_rq_fn;
    cleanup_rq_fn * cleanup_rq;
    busy_fn * busy;
    map_queues_fn * map_queues;
    void (*)(struct seq_file *, struct request *) show_rq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct blk_mq_ops {
    queue_rq_fn * queue_rq;
    commit_rqs_fn * commit_rqs;
    get_budget_fn * get_budget;
    put_budget_fn * put_budget;
    timeout_fn * timeout;
    poll_fn * poll;
    complete_fn * complete;
    init_hctx_fn * init_hctx;
    exit_hctx_fn * exit_hctx;
    init_request_fn * init_request;
    exit_request_fn * exit_request;
    void (*)(struct request *) initialize_rq_fn;
    cleanup_rq_fn * cleanup_rq;
    busy_fn * busy;
    map_queues_fn * map_queues;
    void (*)(struct seq_file *, struct request *) show_rq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct blk_mq_ops {
    queue_rq_fn * queue_rq;
    commit_rqs_fn * commit_rqs;
    get_budget_fn * get_budget;
    put_budget_fn * put_budget;
    timeout_fn * timeout;
    poll_fn * poll;
    complete_fn * complete;
    init_hctx_fn * init_hctx;
    exit_hctx_fn * exit_hctx;
    init_request_fn * init_request;
    exit_request_fn * exit_request;
    void (*)(struct request *) initialize_rq_fn;
    cleanup_rq_fn * cleanup_rq;
    busy_fn * busy;
    map_queues_fn * map_queues;
    void (*)(struct seq_file *, struct request *) show_rq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct blk_mq_ops {
    queue_rq_fn * queue_rq;
    commit_rqs_fn * commit_rqs;
    get_budget_fn * get_budget;
    put_budget_fn * put_budget;
    timeout_fn * timeout;
    poll_fn * poll;
    complete_fn * complete;
    init_hctx_fn * init_hctx;
    exit_hctx_fn * exit_hctx;
    init_request_fn * init_request;
    exit_request_fn * exit_request;
    void (*)(struct request *) initialize_rq_fn;
    cleanup_rq_fn * cleanup_rq;
    busy_fn * busy;
    map_queues_fn * map_queues;
    void (*)(struct seq_file *, struct request *) show_rq;
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
<code>reinit_request_fn * reinit_request</code>
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
<code>map_queues_fn * map_queues</code>
</li>
<li>
<b>Field removed. </b>
<code>map_queue_fn * map_queue</code>
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
<code>void (*)(struct request *) initialize_rq_fn</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct seq_file *, struct request *) show_rq</code>
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
<code>get_budget_fn * get_budget</code>
</li>
<li>
<b>Field added. </b>
<code>put_budget_fn * put_budget</code>
</li>
<li>
<b>Field removed. </b>
<code>reinit_request_fn * reinit_request</code>
</li>
</ul>
</details>
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
<code>commit_rqs_fn * commit_rqs</code>
</li>
<li>
<b>Field added. </b>
<code>busy_fn * busy</code>
</li>
<li>
<b>Field type changed. </b>
<code>softirq_done_fn * complete</code> ➡️ <code>complete_fn * complete</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>cleanup_rq_fn * cleanup_rq</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>queue_rq_fn * queue_rq</code> ➡️ <code>blk_status_t (*)(struct blk_mq_hw_ctx *, const struct blk_mq_queue_data *) queue_rq</code>
</li>
<li>
<b>Field type changed. </b>
<code>commit_rqs_fn * commit_rqs</code> ➡️ <code>void (*)(struct blk_mq_hw_ctx *) commit_rqs</code>
</li>
<li>
<b>Field type changed. </b>
<code>get_budget_fn * get_budget</code> ➡️ <code>bool (*)(struct request_queue *) get_budget</code>
</li>
<li>
<b>Field type changed. </b>
<code>put_budget_fn * put_budget</code> ➡️ <code>void (*)(struct request_queue *) put_budget</code>
</li>
<li>
<b>Field type changed. </b>
<code>timeout_fn * timeout</code> ➡️ <code>enum blk_eh_timer_return (*)(struct request *, bool) timeout</code>
</li>
<li>
<b>Field type changed. </b>
<code>poll_fn * poll</code> ➡️ <code>int (*)(struct blk_mq_hw_ctx *) poll</code>
</li>
<li>
<b>Field type changed. </b>
<code>complete_fn * complete</code> ➡️ <code>void (*)(struct request *) complete</code>
</li>
<li>
<b>Field type changed. </b>
<code>init_hctx_fn * init_hctx</code> ➡️ <code>int (*)(struct blk_mq_hw_ctx *, void *, unsigned int) init_hctx</code>
</li>
<li>
<b>Field type changed. </b>
<code>exit_hctx_fn * exit_hctx</code> ➡️ <code>void (*)(struct blk_mq_hw_ctx *, unsigned int) exit_hctx</code>
</li>
<li>
<b>Field type changed. </b>
<code>init_request_fn * init_request</code> ➡️ <code>int (*)(struct blk_mq_tag_set *, struct request *, unsigned int, unsigned int) init_request</code>
</li>
<li>
<b>Field type changed. </b>
<code>exit_request_fn * exit_request</code> ➡️ <code>void (*)(struct blk_mq_tag_set *, struct request *, unsigned int) exit_request</code>
</li>
<li>
<b>Field type changed. </b>
<code>cleanup_rq_fn * cleanup_rq</code> ➡️ <code>void (*)(struct request *) cleanup_rq</code>
</li>
<li>
<b>Field type changed. </b>
<code>busy_fn * busy</code> ➡️ <code>bool (*)(struct request_queue *) busy</code>
</li>
<li>
<b>Field type changed. </b>
<code>map_queues_fn * map_queues</code> ➡️ <code>int (*)(struct blk_mq_tag_set *) map_queues</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct request *, int) set_rq_budget_token</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct request *) get_rq_budget_token</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool (*)(struct request_queue *) get_budget</code> ➡️ <code>int (*)(struct request_queue *) get_budget</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct request_queue *) put_budget</code> ➡️ <code>void (*)(struct request_queue *, int) put_budget</code>
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
<b>Field added. </b>
<code>void (*)(struct request * *) queue_rqs</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct request *) initialize_rq_fn</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct blk_mq_hw_ctx *) poll</code> ➡️ <code>int (*)(struct blk_mq_hw_ctx *, struct io_comp_batch *) poll</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>enum blk_eh_timer_return (*)(struct request *, bool) timeout</code> ➡️ <code>enum blk_eh_timer_return (*)(struct request *) timeout</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct blk_mq_tag_set *) map_queues</code> ➡️ <code>void (*)(struct blk_mq_tag_set *) map_queues</code>
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
