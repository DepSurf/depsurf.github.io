# Struct: <code>bdi_writeback</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct bdi_writeback {
    struct backing_dev_info * bdi;
    long unsigned int state;
    long unsigned int last_old_flush;
    struct list_head b_dirty;
    struct list_head b_io;
    struct list_head b_more_io;
    struct list_head b_dirty_time;
    spinlock_t list_lock;
    struct percpu_counter[4] stat;
    struct bdi_writeback_congested * congested;
    long unsigned int bw_time_stamp;
    long unsigned int dirtied_stamp;
    long unsigned int written_stamp;
    long unsigned int write_bandwidth;
    long unsigned int avg_write_bandwidth;
    long unsigned int dirty_ratelimit;
    long unsigned int balanced_dirty_ratelimit;
    struct fprop_local_percpu completions;
    int dirty_exceeded;
    spinlock_t work_lock;
    struct list_head work_list;
    struct delayed_work dwork;
    struct list_head bdi_node;
    struct percpu_ref refcnt;
    struct fprop_local_percpu memcg_completions;
    struct cgroup_subsys_state * memcg_css;
    struct cgroup_subsys_state * blkcg_css;
    struct list_head memcg_node;
    struct list_head blkcg_node;
    struct work_struct release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct bdi_writeback {
    struct backing_dev_info * bdi;
    long unsigned int state;
    long unsigned int last_old_flush;
    struct list_head b_dirty;
    struct list_head b_io;
    struct list_head b_more_io;
    struct list_head b_dirty_time;
    spinlock_t list_lock;
    struct percpu_counter[4] stat;
    struct bdi_writeback_congested * congested;
    long unsigned int bw_time_stamp;
    long unsigned int dirtied_stamp;
    long unsigned int written_stamp;
    long unsigned int write_bandwidth;
    long unsigned int avg_write_bandwidth;
    long unsigned int dirty_ratelimit;
    long unsigned int balanced_dirty_ratelimit;
    struct fprop_local_percpu completions;
    int dirty_exceeded;
    spinlock_t work_lock;
    struct list_head work_list;
    struct delayed_work dwork;
    struct list_head bdi_node;
    struct percpu_ref refcnt;
    struct fprop_local_percpu memcg_completions;
    struct cgroup_subsys_state * memcg_css;
    struct cgroup_subsys_state * blkcg_css;
    struct list_head memcg_node;
    struct list_head blkcg_node;
    struct work_struct release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct bdi_writeback {
    struct backing_dev_info * bdi;
    long unsigned int state;
    long unsigned int last_old_flush;
    struct list_head b_dirty;
    struct list_head b_io;
    struct list_head b_more_io;
    struct list_head b_dirty_time;
    spinlock_t list_lock;
    struct percpu_counter[4] stat;
    struct bdi_writeback_congested * congested;
    long unsigned int bw_time_stamp;
    long unsigned int dirtied_stamp;
    long unsigned int written_stamp;
    long unsigned int write_bandwidth;
    long unsigned int avg_write_bandwidth;
    long unsigned int dirty_ratelimit;
    long unsigned int balanced_dirty_ratelimit;
    struct fprop_local_percpu completions;
    int dirty_exceeded;
    spinlock_t work_lock;
    struct list_head work_list;
    struct delayed_work dwork;
    long unsigned int dirty_sleep;
    struct list_head bdi_node;
    struct percpu_ref refcnt;
    struct fprop_local_percpu memcg_completions;
    struct cgroup_subsys_state * memcg_css;
    struct cgroup_subsys_state * blkcg_css;
    struct list_head memcg_node;
    struct list_head blkcg_node;
    struct work_struct release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct bdi_writeback {
    struct backing_dev_info * bdi;
    long unsigned int state;
    long unsigned int last_old_flush;
    struct list_head b_dirty;
    struct list_head b_io;
    struct list_head b_more_io;
    struct list_head b_dirty_time;
    spinlock_t list_lock;
    struct percpu_counter[4] stat;
    struct bdi_writeback_congested * congested;
    long unsigned int bw_time_stamp;
    long unsigned int dirtied_stamp;
    long unsigned int written_stamp;
    long unsigned int write_bandwidth;
    long unsigned int avg_write_bandwidth;
    long unsigned int dirty_ratelimit;
    long unsigned int balanced_dirty_ratelimit;
    struct fprop_local_percpu completions;
    int dirty_exceeded;
    spinlock_t work_lock;
    struct list_head work_list;
    struct delayed_work dwork;
    long unsigned int dirty_sleep;
    struct list_head bdi_node;
    struct percpu_ref refcnt;
    struct fprop_local_percpu memcg_completions;
    struct cgroup_subsys_state * memcg_css;
    struct cgroup_subsys_state * blkcg_css;
    struct list_head memcg_node;
    struct list_head blkcg_node;
    struct work_struct release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct bdi_writeback {
    struct backing_dev_info * bdi;
    long unsigned int state;
    long unsigned int last_old_flush;
    struct list_head b_dirty;
    struct list_head b_io;
    struct list_head b_more_io;
    struct list_head b_dirty_time;
    spinlock_t list_lock;
    struct percpu_counter[4] stat;
    struct bdi_writeback_congested * congested;
    long unsigned int bw_time_stamp;
    long unsigned int dirtied_stamp;
    long unsigned int written_stamp;
    long unsigned int write_bandwidth;
    long unsigned int avg_write_bandwidth;
    long unsigned int dirty_ratelimit;
    long unsigned int balanced_dirty_ratelimit;
    struct fprop_local_percpu completions;
    int dirty_exceeded;
    enum wb_reason start_all_reason;
    spinlock_t work_lock;
    struct list_head work_list;
    struct delayed_work dwork;
    long unsigned int dirty_sleep;
    struct list_head bdi_node;
    struct percpu_ref refcnt;
    struct fprop_local_percpu memcg_completions;
    struct cgroup_subsys_state * memcg_css;
    struct cgroup_subsys_state * blkcg_css;
    struct list_head memcg_node;
    struct list_head blkcg_node;
    struct work_struct release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct bdi_writeback {
    struct backing_dev_info * bdi;
    long unsigned int state;
    long unsigned int last_old_flush;
    struct list_head b_dirty;
    struct list_head b_io;
    struct list_head b_more_io;
    struct list_head b_dirty_time;
    spinlock_t list_lock;
    struct percpu_counter[4] stat;
    struct bdi_writeback_congested * congested;
    long unsigned int bw_time_stamp;
    long unsigned int dirtied_stamp;
    long unsigned int written_stamp;
    long unsigned int write_bandwidth;
    long unsigned int avg_write_bandwidth;
    long unsigned int dirty_ratelimit;
    long unsigned int balanced_dirty_ratelimit;
    struct fprop_local_percpu completions;
    int dirty_exceeded;
    enum wb_reason start_all_reason;
    spinlock_t work_lock;
    struct list_head work_list;
    struct delayed_work dwork;
    long unsigned int dirty_sleep;
    struct list_head bdi_node;
    struct percpu_ref refcnt;
    struct fprop_local_percpu memcg_completions;
    struct cgroup_subsys_state * memcg_css;
    struct cgroup_subsys_state * blkcg_css;
    struct list_head memcg_node;
    struct list_head blkcg_node;
    struct work_struct release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct bdi_writeback {
    struct backing_dev_info * bdi;
    long unsigned int state;
    long unsigned int last_old_flush;
    struct list_head b_dirty;
    struct list_head b_io;
    struct list_head b_more_io;
    struct list_head b_dirty_time;
    spinlock_t list_lock;
    struct percpu_counter[4] stat;
    struct bdi_writeback_congested * congested;
    long unsigned int bw_time_stamp;
    long unsigned int dirtied_stamp;
    long unsigned int written_stamp;
    long unsigned int write_bandwidth;
    long unsigned int avg_write_bandwidth;
    long unsigned int dirty_ratelimit;
    long unsigned int balanced_dirty_ratelimit;
    struct fprop_local_percpu completions;
    int dirty_exceeded;
    enum wb_reason start_all_reason;
    spinlock_t work_lock;
    struct list_head work_list;
    struct delayed_work dwork;
    long unsigned int dirty_sleep;
    struct list_head bdi_node;
    struct percpu_ref refcnt;
    struct fprop_local_percpu memcg_completions;
    struct cgroup_subsys_state * memcg_css;
    struct cgroup_subsys_state * blkcg_css;
    struct list_head memcg_node;
    struct list_head blkcg_node;
    struct work_struct release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct bdi_writeback {
    struct backing_dev_info * bdi;
    long unsigned int state;
    long unsigned int last_old_flush;
    struct list_head b_dirty;
    struct list_head b_io;
    struct list_head b_more_io;
    struct list_head b_dirty_time;
    spinlock_t list_lock;
    struct percpu_counter[4] stat;
    struct bdi_writeback_congested * congested;
    long unsigned int bw_time_stamp;
    long unsigned int dirtied_stamp;
    long unsigned int written_stamp;
    long unsigned int write_bandwidth;
    long unsigned int avg_write_bandwidth;
    long unsigned int dirty_ratelimit;
    long unsigned int balanced_dirty_ratelimit;
    struct fprop_local_percpu completions;
    int dirty_exceeded;
    enum wb_reason start_all_reason;
    spinlock_t work_lock;
    struct list_head work_list;
    struct delayed_work dwork;
    long unsigned int dirty_sleep;
    struct list_head bdi_node;
    struct percpu_ref refcnt;
    struct fprop_local_percpu memcg_completions;
    struct cgroup_subsys_state * memcg_css;
    struct cgroup_subsys_state * blkcg_css;
    struct list_head memcg_node;
    struct list_head blkcg_node;
    struct work_struct release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct bdi_writeback {
    struct backing_dev_info * bdi;
    long unsigned int state;
    long unsigned int last_old_flush;
    struct list_head b_dirty;
    struct list_head b_io;
    struct list_head b_more_io;
    struct list_head b_dirty_time;
    spinlock_t list_lock;
    struct percpu_counter[4] stat;
    struct bdi_writeback_congested * congested;
    long unsigned int bw_time_stamp;
    long unsigned int dirtied_stamp;
    long unsigned int written_stamp;
    long unsigned int write_bandwidth;
    long unsigned int avg_write_bandwidth;
    long unsigned int dirty_ratelimit;
    long unsigned int balanced_dirty_ratelimit;
    struct fprop_local_percpu completions;
    int dirty_exceeded;
    enum wb_reason start_all_reason;
    spinlock_t work_lock;
    struct list_head work_list;
    struct delayed_work dwork;
    long unsigned int dirty_sleep;
    struct list_head bdi_node;
    struct percpu_ref refcnt;
    struct fprop_local_percpu memcg_completions;
    struct cgroup_subsys_state * memcg_css;
    struct cgroup_subsys_state * blkcg_css;
    struct list_head memcg_node;
    struct list_head blkcg_node;
    struct work_struct release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct bdi_writeback {
    struct backing_dev_info * bdi;
    long unsigned int state;
    long unsigned int last_old_flush;
    struct list_head b_dirty;
    struct list_head b_io;
    struct list_head b_more_io;
    struct list_head b_dirty_time;
    spinlock_t list_lock;
    struct percpu_counter[4] stat;
    struct bdi_writeback_congested * congested;
    long unsigned int bw_time_stamp;
    long unsigned int dirtied_stamp;
    long unsigned int written_stamp;
    long unsigned int write_bandwidth;
    long unsigned int avg_write_bandwidth;
    long unsigned int dirty_ratelimit;
    long unsigned int balanced_dirty_ratelimit;
    struct fprop_local_percpu completions;
    int dirty_exceeded;
    enum wb_reason start_all_reason;
    spinlock_t work_lock;
    struct list_head work_list;
    struct delayed_work dwork;
    long unsigned int dirty_sleep;
    struct list_head bdi_node;
    struct percpu_ref refcnt;
    struct fprop_local_percpu memcg_completions;
    struct cgroup_subsys_state * memcg_css;
    struct cgroup_subsys_state * blkcg_css;
    struct list_head memcg_node;
    struct list_head blkcg_node;
    struct work_struct release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct bdi_writeback {
    struct backing_dev_info * bdi;
    long unsigned int state;
    long unsigned int last_old_flush;
    struct list_head b_dirty;
    struct list_head b_io;
    struct list_head b_more_io;
    struct list_head b_dirty_time;
    spinlock_t list_lock;
    struct percpu_counter[4] stat;
    long unsigned int congested;
    long unsigned int bw_time_stamp;
    long unsigned int dirtied_stamp;
    long unsigned int written_stamp;
    long unsigned int write_bandwidth;
    long unsigned int avg_write_bandwidth;
    long unsigned int dirty_ratelimit;
    long unsigned int balanced_dirty_ratelimit;
    struct fprop_local_percpu completions;
    int dirty_exceeded;
    enum wb_reason start_all_reason;
    spinlock_t work_lock;
    struct list_head work_list;
    struct delayed_work dwork;
    long unsigned int dirty_sleep;
    struct list_head bdi_node;
    struct percpu_ref refcnt;
    struct fprop_local_percpu memcg_completions;
    struct cgroup_subsys_state * memcg_css;
    struct cgroup_subsys_state * blkcg_css;
    struct list_head memcg_node;
    struct list_head blkcg_node;
    struct work_struct release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct bdi_writeback {
    struct backing_dev_info * bdi;
    long unsigned int state;
    long unsigned int last_old_flush;
    struct list_head b_dirty;
    struct list_head b_io;
    struct list_head b_more_io;
    struct list_head b_dirty_time;
    spinlock_t list_lock;
    struct percpu_counter[4] stat;
    long unsigned int congested;
    long unsigned int bw_time_stamp;
    long unsigned int dirtied_stamp;
    long unsigned int written_stamp;
    long unsigned int write_bandwidth;
    long unsigned int avg_write_bandwidth;
    long unsigned int dirty_ratelimit;
    long unsigned int balanced_dirty_ratelimit;
    struct fprop_local_percpu completions;
    int dirty_exceeded;
    enum wb_reason start_all_reason;
    spinlock_t work_lock;
    struct list_head work_list;
    struct delayed_work dwork;
    long unsigned int dirty_sleep;
    struct list_head bdi_node;
    struct percpu_ref refcnt;
    struct fprop_local_percpu memcg_completions;
    struct cgroup_subsys_state * memcg_css;
    struct cgroup_subsys_state * blkcg_css;
    struct list_head memcg_node;
    struct list_head blkcg_node;
    struct work_struct release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct bdi_writeback {
    struct backing_dev_info * bdi;
    long unsigned int state;
    long unsigned int last_old_flush;
    struct list_head b_dirty;
    struct list_head b_io;
    struct list_head b_more_io;
    struct list_head b_dirty_time;
    spinlock_t list_lock;
    atomic_t writeback_inodes;
    struct percpu_counter[4] stat;
    long unsigned int congested;
    long unsigned int bw_time_stamp;
    long unsigned int dirtied_stamp;
    long unsigned int written_stamp;
    long unsigned int write_bandwidth;
    long unsigned int avg_write_bandwidth;
    long unsigned int dirty_ratelimit;
    long unsigned int balanced_dirty_ratelimit;
    struct fprop_local_percpu completions;
    int dirty_exceeded;
    enum wb_reason start_all_reason;
    spinlock_t work_lock;
    struct list_head work_list;
    struct delayed_work dwork;
    struct delayed_work bw_dwork;
    long unsigned int dirty_sleep;
    struct list_head bdi_node;
    struct percpu_ref refcnt;
    struct fprop_local_percpu memcg_completions;
    struct cgroup_subsys_state * memcg_css;
    struct cgroup_subsys_state * blkcg_css;
    struct list_head memcg_node;
    struct list_head blkcg_node;
    struct list_head b_attached;
    struct list_head offline_node;
    struct work_struct release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct bdi_writeback {
    struct backing_dev_info * bdi;
    long unsigned int state;
    long unsigned int last_old_flush;
    struct list_head b_dirty;
    struct list_head b_io;
    struct list_head b_more_io;
    struct list_head b_dirty_time;
    spinlock_t list_lock;
    atomic_t writeback_inodes;
    struct percpu_counter[4] stat;
    long unsigned int congested;
    long unsigned int bw_time_stamp;
    long unsigned int dirtied_stamp;
    long unsigned int written_stamp;
    long unsigned int write_bandwidth;
    long unsigned int avg_write_bandwidth;
    long unsigned int dirty_ratelimit;
    long unsigned int balanced_dirty_ratelimit;
    struct fprop_local_percpu completions;
    int dirty_exceeded;
    enum wb_reason start_all_reason;
    spinlock_t work_lock;
    struct list_head work_list;
    struct delayed_work dwork;
    struct delayed_work bw_dwork;
    long unsigned int dirty_sleep;
    struct list_head bdi_node;
    struct percpu_ref refcnt;
    struct fprop_local_percpu memcg_completions;
    struct cgroup_subsys_state * memcg_css;
    struct cgroup_subsys_state * blkcg_css;
    struct list_head memcg_node;
    struct list_head blkcg_node;
    struct list_head b_attached;
    struct list_head offline_node;
    struct work_struct release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct bdi_writeback {
    struct backing_dev_info * bdi;
    long unsigned int state;
    long unsigned int last_old_flush;
    struct list_head b_dirty;
    struct list_head b_io;
    struct list_head b_more_io;
    struct list_head b_dirty_time;
    spinlock_t list_lock;
    atomic_t writeback_inodes;
    struct percpu_counter[4] stat;
    long unsigned int bw_time_stamp;
    long unsigned int dirtied_stamp;
    long unsigned int written_stamp;
    long unsigned int write_bandwidth;
    long unsigned int avg_write_bandwidth;
    long unsigned int dirty_ratelimit;
    long unsigned int balanced_dirty_ratelimit;
    struct fprop_local_percpu completions;
    int dirty_exceeded;
    enum wb_reason start_all_reason;
    spinlock_t work_lock;
    struct list_head work_list;
    struct delayed_work dwork;
    struct delayed_work bw_dwork;
    long unsigned int dirty_sleep;
    struct list_head bdi_node;
    struct percpu_ref refcnt;
    struct fprop_local_percpu memcg_completions;
    struct cgroup_subsys_state * memcg_css;
    struct cgroup_subsys_state * blkcg_css;
    struct list_head memcg_node;
    struct list_head blkcg_node;
    struct list_head b_attached;
    struct list_head offline_node;
    struct work_struct release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct bdi_writeback {
    struct backing_dev_info * bdi;
    long unsigned int state;
    long unsigned int last_old_flush;
    struct list_head b_dirty;
    struct list_head b_io;
    struct list_head b_more_io;
    struct list_head b_dirty_time;
    spinlock_t list_lock;
    atomic_t writeback_inodes;
    struct percpu_counter[4] stat;
    long unsigned int bw_time_stamp;
    long unsigned int dirtied_stamp;
    long unsigned int written_stamp;
    long unsigned int write_bandwidth;
    long unsigned int avg_write_bandwidth;
    long unsigned int dirty_ratelimit;
    long unsigned int balanced_dirty_ratelimit;
    struct fprop_local_percpu completions;
    int dirty_exceeded;
    enum wb_reason start_all_reason;
    spinlock_t work_lock;
    struct list_head work_list;
    struct delayed_work dwork;
    struct delayed_work bw_dwork;
    long unsigned int dirty_sleep;
    struct list_head bdi_node;
    struct percpu_ref refcnt;
    struct fprop_local_percpu memcg_completions;
    struct cgroup_subsys_state * memcg_css;
    struct cgroup_subsys_state * blkcg_css;
    struct list_head memcg_node;
    struct list_head blkcg_node;
    struct list_head b_attached;
    struct list_head offline_node;
    struct work_struct release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct bdi_writeback {
    struct backing_dev_info * bdi;
    long unsigned int state;
    long unsigned int last_old_flush;
    struct list_head b_dirty;
    struct list_head b_io;
    struct list_head b_more_io;
    struct list_head b_dirty_time;
    spinlock_t list_lock;
    atomic_t writeback_inodes;
    struct percpu_counter[4] stat;
    long unsigned int bw_time_stamp;
    long unsigned int dirtied_stamp;
    long unsigned int written_stamp;
    long unsigned int write_bandwidth;
    long unsigned int avg_write_bandwidth;
    long unsigned int dirty_ratelimit;
    long unsigned int balanced_dirty_ratelimit;
    struct fprop_local_percpu completions;
    int dirty_exceeded;
    enum wb_reason start_all_reason;
    spinlock_t work_lock;
    struct list_head work_list;
    struct delayed_work dwork;
    struct delayed_work bw_dwork;
    struct list_head bdi_node;
    struct percpu_ref refcnt;
    struct fprop_local_percpu memcg_completions;
    struct cgroup_subsys_state * memcg_css;
    struct cgroup_subsys_state * blkcg_css;
    struct list_head memcg_node;
    struct list_head blkcg_node;
    struct list_head b_attached;
    struct list_head offline_node;
    struct work_struct release_work;
    struct callback_head rcu;
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
struct bdi_writeback {
    struct backing_dev_info * bdi;
    long unsigned int state;
    long unsigned int last_old_flush;
    struct list_head b_dirty;
    struct list_head b_io;
    struct list_head b_more_io;
    struct list_head b_dirty_time;
    spinlock_t list_lock;
    struct percpu_counter[4] stat;
    struct bdi_writeback_congested * congested;
    long unsigned int bw_time_stamp;
    long unsigned int dirtied_stamp;
    long unsigned int written_stamp;
    long unsigned int write_bandwidth;
    long unsigned int avg_write_bandwidth;
    long unsigned int dirty_ratelimit;
    long unsigned int balanced_dirty_ratelimit;
    struct fprop_local_percpu completions;
    int dirty_exceeded;
    enum wb_reason start_all_reason;
    spinlock_t work_lock;
    struct list_head work_list;
    struct delayed_work dwork;
    long unsigned int dirty_sleep;
    struct list_head bdi_node;
    struct percpu_ref refcnt;
    struct fprop_local_percpu memcg_completions;
    struct cgroup_subsys_state * memcg_css;
    struct cgroup_subsys_state * blkcg_css;
    struct list_head memcg_node;
    struct list_head blkcg_node;
    struct work_struct release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct bdi_writeback {
    struct backing_dev_info * bdi;
    long unsigned int state;
    long unsigned int last_old_flush;
    struct list_head b_dirty;
    struct list_head b_io;
    struct list_head b_more_io;
    struct list_head b_dirty_time;
    spinlock_t list_lock;
    struct percpu_counter[4] stat;
    struct bdi_writeback_congested * congested;
    long unsigned int bw_time_stamp;
    long unsigned int dirtied_stamp;
    long unsigned int written_stamp;
    long unsigned int write_bandwidth;
    long unsigned int avg_write_bandwidth;
    long unsigned int dirty_ratelimit;
    long unsigned int balanced_dirty_ratelimit;
    struct fprop_local_percpu completions;
    int dirty_exceeded;
    enum wb_reason start_all_reason;
    spinlock_t work_lock;
    struct list_head work_list;
    struct delayed_work dwork;
    long unsigned int dirty_sleep;
    struct list_head bdi_node;
    struct percpu_ref refcnt;
    struct fprop_local_percpu memcg_completions;
    struct cgroup_subsys_state * memcg_css;
    struct cgroup_subsys_state * blkcg_css;
    struct list_head memcg_node;
    struct list_head blkcg_node;
    struct work_struct release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct bdi_writeback {
    struct backing_dev_info * bdi;
    long unsigned int state;
    long unsigned int last_old_flush;
    struct list_head b_dirty;
    struct list_head b_io;
    struct list_head b_more_io;
    struct list_head b_dirty_time;
    spinlock_t list_lock;
    struct percpu_counter[4] stat;
    struct bdi_writeback_congested * congested;
    long unsigned int bw_time_stamp;
    long unsigned int dirtied_stamp;
    long unsigned int written_stamp;
    long unsigned int write_bandwidth;
    long unsigned int avg_write_bandwidth;
    long unsigned int dirty_ratelimit;
    long unsigned int balanced_dirty_ratelimit;
    struct fprop_local_percpu completions;
    int dirty_exceeded;
    enum wb_reason start_all_reason;
    spinlock_t work_lock;
    struct list_head work_list;
    struct delayed_work dwork;
    long unsigned int dirty_sleep;
    struct list_head bdi_node;
    struct percpu_ref refcnt;
    struct fprop_local_percpu memcg_completions;
    struct cgroup_subsys_state * memcg_css;
    struct cgroup_subsys_state * blkcg_css;
    struct list_head memcg_node;
    struct list_head blkcg_node;
    struct work_struct release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct bdi_writeback {
    struct backing_dev_info * bdi;
    long unsigned int state;
    long unsigned int last_old_flush;
    struct list_head b_dirty;
    struct list_head b_io;
    struct list_head b_more_io;
    struct list_head b_dirty_time;
    spinlock_t list_lock;
    struct percpu_counter[4] stat;
    struct bdi_writeback_congested * congested;
    long unsigned int bw_time_stamp;
    long unsigned int dirtied_stamp;
    long unsigned int written_stamp;
    long unsigned int write_bandwidth;
    long unsigned int avg_write_bandwidth;
    long unsigned int dirty_ratelimit;
    long unsigned int balanced_dirty_ratelimit;
    struct fprop_local_percpu completions;
    int dirty_exceeded;
    enum wb_reason start_all_reason;
    spinlock_t work_lock;
    struct list_head work_list;
    struct delayed_work dwork;
    long unsigned int dirty_sleep;
    struct list_head bdi_node;
    struct percpu_ref refcnt;
    struct fprop_local_percpu memcg_completions;
    struct cgroup_subsys_state * memcg_css;
    struct cgroup_subsys_state * blkcg_css;
    struct list_head memcg_node;
    struct list_head blkcg_node;
    struct work_struct release_work;
    struct callback_head rcu;
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
struct bdi_writeback {
    struct backing_dev_info * bdi;
    long unsigned int state;
    long unsigned int last_old_flush;
    struct list_head b_dirty;
    struct list_head b_io;
    struct list_head b_more_io;
    struct list_head b_dirty_time;
    spinlock_t list_lock;
    struct percpu_counter[4] stat;
    struct bdi_writeback_congested * congested;
    long unsigned int bw_time_stamp;
    long unsigned int dirtied_stamp;
    long unsigned int written_stamp;
    long unsigned int write_bandwidth;
    long unsigned int avg_write_bandwidth;
    long unsigned int dirty_ratelimit;
    long unsigned int balanced_dirty_ratelimit;
    struct fprop_local_percpu completions;
    int dirty_exceeded;
    enum wb_reason start_all_reason;
    spinlock_t work_lock;
    struct list_head work_list;
    struct delayed_work dwork;
    long unsigned int dirty_sleep;
    struct list_head bdi_node;
    struct percpu_ref refcnt;
    struct fprop_local_percpu memcg_completions;
    struct cgroup_subsys_state * memcg_css;
    struct cgroup_subsys_state * blkcg_css;
    struct list_head memcg_node;
    struct list_head blkcg_node;
    struct work_struct release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct bdi_writeback {
    struct backing_dev_info * bdi;
    long unsigned int state;
    long unsigned int last_old_flush;
    struct list_head b_dirty;
    struct list_head b_io;
    struct list_head b_more_io;
    struct list_head b_dirty_time;
    spinlock_t list_lock;
    struct percpu_counter[4] stat;
    struct bdi_writeback_congested * congested;
    long unsigned int bw_time_stamp;
    long unsigned int dirtied_stamp;
    long unsigned int written_stamp;
    long unsigned int write_bandwidth;
    long unsigned int avg_write_bandwidth;
    long unsigned int dirty_ratelimit;
    long unsigned int balanced_dirty_ratelimit;
    struct fprop_local_percpu completions;
    int dirty_exceeded;
    enum wb_reason start_all_reason;
    spinlock_t work_lock;
    struct list_head work_list;
    struct delayed_work dwork;
    long unsigned int dirty_sleep;
    struct list_head bdi_node;
    struct percpu_ref refcnt;
    struct fprop_local_percpu memcg_completions;
    struct cgroup_subsys_state * memcg_css;
    struct cgroup_subsys_state * blkcg_css;
    struct list_head memcg_node;
    struct list_head blkcg_node;
    struct work_struct release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct bdi_writeback {
    struct backing_dev_info * bdi;
    long unsigned int state;
    long unsigned int last_old_flush;
    struct list_head b_dirty;
    struct list_head b_io;
    struct list_head b_more_io;
    struct list_head b_dirty_time;
    spinlock_t list_lock;
    struct percpu_counter[4] stat;
    struct bdi_writeback_congested * congested;
    long unsigned int bw_time_stamp;
    long unsigned int dirtied_stamp;
    long unsigned int written_stamp;
    long unsigned int write_bandwidth;
    long unsigned int avg_write_bandwidth;
    long unsigned int dirty_ratelimit;
    long unsigned int balanced_dirty_ratelimit;
    struct fprop_local_percpu completions;
    int dirty_exceeded;
    enum wb_reason start_all_reason;
    spinlock_t work_lock;
    struct list_head work_list;
    struct delayed_work dwork;
    long unsigned int dirty_sleep;
    struct list_head bdi_node;
    struct percpu_ref refcnt;
    struct fprop_local_percpu memcg_completions;
    struct cgroup_subsys_state * memcg_css;
    struct cgroup_subsys_state * blkcg_css;
    struct list_head memcg_node;
    struct list_head blkcg_node;
    struct work_struct release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct bdi_writeback {
    struct backing_dev_info * bdi;
    long unsigned int state;
    long unsigned int last_old_flush;
    struct list_head b_dirty;
    struct list_head b_io;
    struct list_head b_more_io;
    struct list_head b_dirty_time;
    spinlock_t list_lock;
    struct percpu_counter[4] stat;
    struct bdi_writeback_congested * congested;
    long unsigned int bw_time_stamp;
    long unsigned int dirtied_stamp;
    long unsigned int written_stamp;
    long unsigned int write_bandwidth;
    long unsigned int avg_write_bandwidth;
    long unsigned int dirty_ratelimit;
    long unsigned int balanced_dirty_ratelimit;
    struct fprop_local_percpu completions;
    int dirty_exceeded;
    enum wb_reason start_all_reason;
    spinlock_t work_lock;
    struct list_head work_list;
    struct delayed_work dwork;
    long unsigned int dirty_sleep;
    struct list_head bdi_node;
    struct percpu_ref refcnt;
    struct fprop_local_percpu memcg_completions;
    struct cgroup_subsys_state * memcg_css;
    struct cgroup_subsys_state * blkcg_css;
    struct list_head memcg_node;
    struct list_head blkcg_node;
    struct work_struct release_work;
    struct callback_head rcu;
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
<code>long unsigned int dirty_sleep</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>enum wb_reason start_all_reason</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct bdi_writeback_congested * congested</code> ➡️ <code>long unsigned int congested</code>
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
<code>atomic_t writeback_inodes</code>
</li>
<li>
<b>Field added. </b>
<code>struct delayed_work bw_dwork</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head b_attached</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head offline_node</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>long unsigned int congested</code>
</li>
</ul>
</details>
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
<code>long unsigned int dirty_sleep</code>
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
