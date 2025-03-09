# Struct: <code>rq_wb</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct rq_wb {
    unsigned int wb_background;
    unsigned int wb_normal;
    unsigned int wb_max;
    int scale_step;
    bool scaled_max;
    short int enable_state;
    unsigned int unknown_cnt;
    u64 win_nsec;
    u64 cur_win_nsec;
    struct timer_list window_timer;
    s64 sync_issue;
    void * sync_cookie;
    unsigned int wc;
    unsigned int queue_depth;
    long unsigned int last_issue;
    long unsigned int last_comp;
    long unsigned int min_lat_nsec;
    struct request_queue * queue;
    struct rq_wait[2] rq_wait;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct rq_wb {
    unsigned int wb_background;
    unsigned int wb_normal;
    unsigned int wb_max;
    int scale_step;
    bool scaled_max;
    short int enable_state;
    unsigned int unknown_cnt;
    u64 win_nsec;
    u64 cur_win_nsec;
    struct blk_stat_callback * cb;
    s64 sync_issue;
    void * sync_cookie;
    unsigned int wc;
    unsigned int queue_depth;
    long unsigned int last_issue;
    long unsigned int last_comp;
    long unsigned int min_lat_nsec;
    struct request_queue * queue;
    struct rq_wait[2] rq_wait;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct rq_wb {
    unsigned int wb_background;
    unsigned int wb_normal;
    unsigned int wb_max;
    int scale_step;
    bool scaled_max;
    short int enable_state;
    unsigned int unknown_cnt;
    u64 win_nsec;
    u64 cur_win_nsec;
    struct blk_stat_callback * cb;
    s64 sync_issue;
    void * sync_cookie;
    unsigned int wc;
    unsigned int queue_depth;
    long unsigned int last_issue;
    long unsigned int last_comp;
    long unsigned int min_lat_nsec;
    struct request_queue * queue;
    struct rq_wait[2] rq_wait;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct rq_wb {
    unsigned int wb_background;
    unsigned int wb_normal;
    unsigned int wb_max;
    int scale_step;
    bool scaled_max;
    short int enable_state;
    unsigned int unknown_cnt;
    u64 win_nsec;
    u64 cur_win_nsec;
    struct blk_stat_callback * cb;
    u64 sync_issue;
    void * sync_cookie;
    unsigned int wc;
    unsigned int queue_depth;
    long unsigned int last_issue;
    long unsigned int last_comp;
    long unsigned int min_lat_nsec;
    struct request_queue * queue;
    struct rq_wait[3] rq_wait;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct rq_wb {
    unsigned int wb_background;
    unsigned int wb_normal;
    short int enable_state;
    unsigned int unknown_cnt;
    u64 win_nsec;
    u64 cur_win_nsec;
    struct blk_stat_callback * cb;
    u64 sync_issue;
    void * sync_cookie;
    unsigned int wc;
    long unsigned int last_issue;
    long unsigned int last_comp;
    long unsigned int min_lat_nsec;
    struct rq_qos rqos;
    struct rq_wait[3] rq_wait;
    struct rq_depth rq_depth;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct rq_wb {
    unsigned int wb_background;
    unsigned int wb_normal;
    short int enable_state;
    unsigned int unknown_cnt;
    u64 win_nsec;
    u64 cur_win_nsec;
    struct blk_stat_callback * cb;
    u64 sync_issue;
    void * sync_cookie;
    unsigned int wc;
    long unsigned int last_issue;
    long unsigned int last_comp;
    long unsigned int min_lat_nsec;
    struct rq_qos rqos;
    struct rq_wait[3] rq_wait;
    struct rq_depth rq_depth;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct rq_wb {
    unsigned int wb_background;
    unsigned int wb_normal;
    short int enable_state;
    unsigned int unknown_cnt;
    u64 win_nsec;
    u64 cur_win_nsec;
    struct blk_stat_callback * cb;
    u64 sync_issue;
    void * sync_cookie;
    unsigned int wc;
    long unsigned int last_issue;
    long unsigned int last_comp;
    long unsigned int min_lat_nsec;
    struct rq_qos rqos;
    struct rq_wait[3] rq_wait;
    struct rq_depth rq_depth;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct rq_wb {
    unsigned int wb_background;
    unsigned int wb_normal;
    short int enable_state;
    unsigned int unknown_cnt;
    u64 win_nsec;
    u64 cur_win_nsec;
    struct blk_stat_callback * cb;
    u64 sync_issue;
    void * sync_cookie;
    unsigned int wc;
    long unsigned int last_issue;
    long unsigned int last_comp;
    long unsigned int min_lat_nsec;
    struct rq_qos rqos;
    struct rq_wait[3] rq_wait;
    struct rq_depth rq_depth;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct rq_wb {
    unsigned int wb_background;
    unsigned int wb_normal;
    short int enable_state;
    unsigned int unknown_cnt;
    u64 win_nsec;
    u64 cur_win_nsec;
    struct blk_stat_callback * cb;
    u64 sync_issue;
    void * sync_cookie;
    unsigned int wc;
    long unsigned int last_issue;
    long unsigned int last_comp;
    long unsigned int min_lat_nsec;
    struct rq_qos rqos;
    struct rq_wait[3] rq_wait;
    struct rq_depth rq_depth;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct rq_wb {
    unsigned int wb_background;
    unsigned int wb_normal;
    short int enable_state;
    unsigned int unknown_cnt;
    u64 win_nsec;
    u64 cur_win_nsec;
    struct blk_stat_callback * cb;
    u64 sync_issue;
    void * sync_cookie;
    unsigned int wc;
    long unsigned int last_issue;
    long unsigned int last_comp;
    long unsigned int min_lat_nsec;
    struct rq_qos rqos;
    struct rq_wait[3] rq_wait;
    struct rq_depth rq_depth;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct rq_wb {
    unsigned int wb_background;
    unsigned int wb_normal;
    short int enable_state;
    unsigned int unknown_cnt;
    u64 win_nsec;
    u64 cur_win_nsec;
    struct blk_stat_callback * cb;
    u64 sync_issue;
    void * sync_cookie;
    unsigned int wc;
    long unsigned int last_issue;
    long unsigned int last_comp;
    long unsigned int min_lat_nsec;
    struct rq_qos rqos;
    struct rq_wait[3] rq_wait;
    struct rq_depth rq_depth;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct rq_wb {
    unsigned int wb_background;
    unsigned int wb_normal;
    short int enable_state;
    unsigned int unknown_cnt;
    u64 win_nsec;
    u64 cur_win_nsec;
    struct blk_stat_callback * cb;
    u64 sync_issue;
    void * sync_cookie;
    unsigned int wc;
    long unsigned int last_issue;
    long unsigned int last_comp;
    long unsigned int min_lat_nsec;
    struct rq_qos rqos;
    struct rq_wait[3] rq_wait;
    struct rq_depth rq_depth;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct rq_wb {
    unsigned int wb_background;
    unsigned int wb_normal;
    short int enable_state;
    unsigned int unknown_cnt;
    u64 win_nsec;
    u64 cur_win_nsec;
    struct blk_stat_callback * cb;
    u64 sync_issue;
    void * sync_cookie;
    unsigned int wc;
    long unsigned int last_issue;
    long unsigned int last_comp;
    long unsigned int min_lat_nsec;
    struct rq_qos rqos;
    struct rq_wait[3] rq_wait;
    struct rq_depth rq_depth;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct rq_wb {
    unsigned int wb_background;
    unsigned int wb_normal;
    short int enable_state;
    unsigned int unknown_cnt;
    u64 win_nsec;
    u64 cur_win_nsec;
    struct blk_stat_callback * cb;
    u64 sync_issue;
    void * sync_cookie;
    unsigned int wc;
    long unsigned int last_issue;
    long unsigned int last_comp;
    long unsigned int min_lat_nsec;
    struct rq_qos rqos;
    struct rq_wait[3] rq_wait;
    struct rq_depth rq_depth;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct rq_wb {
    unsigned int wb_background;
    unsigned int wb_normal;
    short int enable_state;
    unsigned int unknown_cnt;
    u64 win_nsec;
    u64 cur_win_nsec;
    struct blk_stat_callback * cb;
    u64 sync_issue;
    void * sync_cookie;
    long unsigned int last_issue;
    long unsigned int last_comp;
    long unsigned int min_lat_nsec;
    struct rq_qos rqos;
    struct rq_wait[3] rq_wait;
    struct rq_depth rq_depth;
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
struct rq_wb {
    unsigned int wb_background;
    unsigned int wb_normal;
    short int enable_state;
    unsigned int unknown_cnt;
    u64 win_nsec;
    u64 cur_win_nsec;
    struct blk_stat_callback * cb;
    u64 sync_issue;
    void * sync_cookie;
    unsigned int wc;
    long unsigned int last_issue;
    long unsigned int last_comp;
    long unsigned int min_lat_nsec;
    struct rq_qos rqos;
    struct rq_wait[3] rq_wait;
    struct rq_depth rq_depth;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct rq_wb {
    unsigned int wb_background;
    unsigned int wb_normal;
    short int enable_state;
    unsigned int unknown_cnt;
    u64 win_nsec;
    u64 cur_win_nsec;
    struct blk_stat_callback * cb;
    u64 sync_issue;
    void * sync_cookie;
    unsigned int wc;
    long unsigned int last_issue;
    long unsigned int last_comp;
    long unsigned int min_lat_nsec;
    struct rq_qos rqos;
    struct rq_wait[3] rq_wait;
    struct rq_depth rq_depth;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct rq_wb {
    unsigned int wb_background;
    unsigned int wb_normal;
    short int enable_state;
    unsigned int unknown_cnt;
    u64 win_nsec;
    u64 cur_win_nsec;
    struct blk_stat_callback * cb;
    u64 sync_issue;
    void * sync_cookie;
    unsigned int wc;
    long unsigned int last_issue;
    long unsigned int last_comp;
    long unsigned int min_lat_nsec;
    struct rq_qos rqos;
    struct rq_wait[3] rq_wait;
    struct rq_depth rq_depth;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct rq_wb {
    unsigned int wb_background;
    unsigned int wb_normal;
    short int enable_state;
    unsigned int unknown_cnt;
    u64 win_nsec;
    u64 cur_win_nsec;
    struct blk_stat_callback * cb;
    u64 sync_issue;
    void * sync_cookie;
    unsigned int wc;
    long unsigned int last_issue;
    long unsigned int last_comp;
    long unsigned int min_lat_nsec;
    struct rq_qos rqos;
    struct rq_wait[3] rq_wait;
    struct rq_depth rq_depth;
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
struct rq_wb {
    unsigned int wb_background;
    unsigned int wb_normal;
    short int enable_state;
    unsigned int unknown_cnt;
    u64 win_nsec;
    u64 cur_win_nsec;
    struct blk_stat_callback * cb;
    u64 sync_issue;
    void * sync_cookie;
    unsigned int wc;
    long unsigned int last_issue;
    long unsigned int last_comp;
    long unsigned int min_lat_nsec;
    struct rq_qos rqos;
    struct rq_wait[3] rq_wait;
    struct rq_depth rq_depth;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct rq_wb {
    unsigned int wb_background;
    unsigned int wb_normal;
    short int enable_state;
    unsigned int unknown_cnt;
    u64 win_nsec;
    u64 cur_win_nsec;
    struct blk_stat_callback * cb;
    u64 sync_issue;
    void * sync_cookie;
    unsigned int wc;
    long unsigned int last_issue;
    long unsigned int last_comp;
    long unsigned int min_lat_nsec;
    struct rq_qos rqos;
    struct rq_wait[3] rq_wait;
    struct rq_depth rq_depth;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct rq_wb {
    unsigned int wb_background;
    unsigned int wb_normal;
    short int enable_state;
    unsigned int unknown_cnt;
    u64 win_nsec;
    u64 cur_win_nsec;
    struct blk_stat_callback * cb;
    u64 sync_issue;
    void * sync_cookie;
    unsigned int wc;
    long unsigned int last_issue;
    long unsigned int last_comp;
    long unsigned int min_lat_nsec;
    struct rq_qos rqos;
    struct rq_wait[3] rq_wait;
    struct rq_depth rq_depth;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct rq_wb {
    unsigned int wb_background;
    unsigned int wb_normal;
    short int enable_state;
    unsigned int unknown_cnt;
    u64 win_nsec;
    u64 cur_win_nsec;
    struct blk_stat_callback * cb;
    u64 sync_issue;
    void * sync_cookie;
    unsigned int wc;
    long unsigned int last_issue;
    long unsigned int last_comp;
    long unsigned int min_lat_nsec;
    struct rq_qos rqos;
    struct rq_wait[3] rq_wait;
    struct rq_depth rq_depth;
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
struct rq_wb {
    unsigned int wb_background;
    unsigned int wb_normal;
    unsigned int wb_max;
    int scale_step;
    bool scaled_max;
    short int enable_state;
    unsigned int unknown_cnt;
    u64 win_nsec;
    u64 cur_win_nsec;
    struct timer_list window_timer;
    s64 sync_issue;
    void * sync_cookie;
    unsigned int wc;
    unsigned int queue_depth;
    long unsigned int last_issue;
    long unsigned int last_comp;
    long unsigned int min_lat_nsec;
    struct request_queue * queue;
    struct rq_wait[2] rq_wait;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct blk_stat_callback * cb</code>
</li>
<li>
<b>Field removed. </b>
<code>struct timer_list window_timer</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>s64 sync_issue</code> ➡️ <code>u64 sync_issue</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct rq_wait[2] rq_wait</code> ➡️ <code>struct rq_wait[3] rq_wait</code>
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
<code>struct rq_qos rqos</code>
</li>
<li>
<b>Field added. </b>
<code>struct rq_depth rq_depth</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int wb_max</code>
</li>
<li>
<b>Field removed. </b>
<code>int scale_step</code>
</li>
<li>
<b>Field removed. </b>
<code>bool scaled_max</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int queue_depth</code>
</li>
<li>
<b>Field removed. </b>
<code>struct request_queue * queue</code>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>unsigned int wc</code>
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
