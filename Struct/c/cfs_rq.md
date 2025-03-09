# Struct: <code>cfs_rq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct cfs_rq {
    struct load_weight load;
    unsigned int nr_running;
    unsigned int h_nr_running;
    u64 exec_clock;
    u64 min_vruntime;
    struct rb_root tasks_timeline;
    struct rb_node * rb_leftmost;
    struct sched_entity * curr;
    struct sched_entity * next;
    struct sched_entity * last;
    struct sched_entity * skip;
    unsigned int nr_spread_over;
    struct sched_avg avg;
    u64 runnable_load_sum;
    long unsigned int runnable_load_avg;
    long unsigned int tg_load_avg_contrib;
    atomic_long_t removed_load_avg;
    atomic_long_t removed_util_avg;
    long unsigned int h_load;
    u64 last_h_load_update;
    struct sched_entity * h_load_next;
    struct rq * rq;
    int on_list;
    struct list_head leaf_cfs_rq_list;
    struct task_group * tg;
    int runtime_enabled;
    u64 runtime_expires;
    s64 runtime_remaining;
    u64 throttled_clock;
    u64 throttled_clock_task;
    u64 throttled_clock_task_time;
    int throttled;
    int throttle_count;
    struct list_head throttled_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct cfs_rq {
    struct load_weight load;
    unsigned int nr_running;
    unsigned int h_nr_running;
    u64 exec_clock;
    u64 min_vruntime;
    struct rb_root tasks_timeline;
    struct rb_node * rb_leftmost;
    struct sched_entity * curr;
    struct sched_entity * next;
    struct sched_entity * last;
    struct sched_entity * skip;
    unsigned int nr_spread_over;
    struct sched_avg avg;
    u64 runnable_load_sum;
    long unsigned int runnable_load_avg;
    long unsigned int tg_load_avg_contrib;
    atomic_long_t removed_load_avg;
    atomic_long_t removed_util_avg;
    long unsigned int h_load;
    u64 last_h_load_update;
    struct sched_entity * h_load_next;
    struct rq * rq;
    int on_list;
    struct list_head leaf_cfs_rq_list;
    struct task_group * tg;
    int runtime_enabled;
    u64 runtime_expires;
    s64 runtime_remaining;
    u64 throttled_clock;
    u64 throttled_clock_task;
    u64 throttled_clock_task_time;
    int throttled;
    int throttle_count;
    struct list_head throttled_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct cfs_rq {
    struct load_weight load;
    unsigned int nr_running;
    unsigned int h_nr_running;
    u64 exec_clock;
    u64 min_vruntime;
    struct rb_root tasks_timeline;
    struct rb_node * rb_leftmost;
    struct sched_entity * curr;
    struct sched_entity * next;
    struct sched_entity * last;
    struct sched_entity * skip;
    unsigned int nr_spread_over;
    struct sched_avg avg;
    u64 runnable_load_sum;
    long unsigned int runnable_load_avg;
    long unsigned int tg_load_avg_contrib;
    long unsigned int propagate_avg;
    atomic_long_t removed_load_avg;
    atomic_long_t removed_util_avg;
    long unsigned int h_load;
    u64 last_h_load_update;
    struct sched_entity * h_load_next;
    struct rq * rq;
    int on_list;
    struct list_head leaf_cfs_rq_list;
    struct task_group * tg;
    int runtime_enabled;
    u64 runtime_expires;
    s64 runtime_remaining;
    u64 throttled_clock;
    u64 throttled_clock_task;
    u64 throttled_clock_task_time;
    int throttled;
    int throttle_count;
    struct list_head throttled_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct cfs_rq {
    struct load_weight load;
    unsigned int nr_running;
    unsigned int h_nr_running;
    u64 exec_clock;
    u64 min_vruntime;
    struct rb_root tasks_timeline;
    struct rb_node * rb_leftmost;
    struct sched_entity * curr;
    struct sched_entity * next;
    struct sched_entity * last;
    struct sched_entity * skip;
    unsigned int nr_spread_over;
    struct sched_avg avg;
    u64 runnable_load_sum;
    long unsigned int runnable_load_avg;
    long unsigned int tg_load_avg_contrib;
    long unsigned int propagate_avg;
    atomic_long_t removed_load_avg;
    atomic_long_t removed_util_avg;
    long unsigned int h_load;
    u64 last_h_load_update;
    struct sched_entity * h_load_next;
    struct rq * rq;
    int on_list;
    struct list_head leaf_cfs_rq_list;
    struct task_group * tg;
    int runtime_enabled;
    u64 runtime_expires;
    s64 runtime_remaining;
    u64 throttled_clock;
    u64 throttled_clock_task;
    u64 throttled_clock_task_time;
    int throttled;
    int throttle_count;
    struct list_head throttled_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct cfs_rq {
    struct load_weight load;
    long unsigned int runnable_weight;
    unsigned int nr_running;
    unsigned int h_nr_running;
    u64 exec_clock;
    u64 min_vruntime;
    struct rb_root_cached tasks_timeline;
    struct sched_entity * curr;
    struct sched_entity * next;
    struct sched_entity * last;
    struct sched_entity * skip;
    unsigned int nr_spread_over;
    struct sched_avg avg;
    struct (anon) removed;
    long unsigned int tg_load_avg_contrib;
    long int propagate;
    long int prop_runnable_sum;
    long unsigned int h_load;
    u64 last_h_load_update;
    struct sched_entity * h_load_next;
    struct rq * rq;
    int on_list;
    struct list_head leaf_cfs_rq_list;
    struct task_group * tg;
    int runtime_enabled;
    u64 runtime_expires;
    s64 runtime_remaining;
    u64 throttled_clock;
    u64 throttled_clock_task;
    u64 throttled_clock_task_time;
    int throttled;
    int throttle_count;
    struct list_head throttled_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct cfs_rq {
    struct load_weight load;
    long unsigned int runnable_weight;
    unsigned int nr_running;
    unsigned int h_nr_running;
    u64 exec_clock;
    u64 min_vruntime;
    struct rb_root_cached tasks_timeline;
    struct sched_entity * curr;
    struct sched_entity * next;
    struct sched_entity * last;
    struct sched_entity * skip;
    unsigned int nr_spread_over;
    struct sched_avg avg;
    struct (anon) removed;
    long unsigned int tg_load_avg_contrib;
    long int propagate;
    long int prop_runnable_sum;
    long unsigned int h_load;
    u64 last_h_load_update;
    struct sched_entity * h_load_next;
    struct rq * rq;
    int on_list;
    struct list_head leaf_cfs_rq_list;
    struct task_group * tg;
    int runtime_enabled;
    int expires_seq;
    u64 runtime_expires;
    s64 runtime_remaining;
    u64 throttled_clock;
    u64 throttled_clock_task;
    u64 throttled_clock_task_time;
    int throttled;
    int throttle_count;
    struct list_head throttled_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct cfs_rq {
    struct load_weight load;
    long unsigned int runnable_weight;
    unsigned int nr_running;
    unsigned int h_nr_running;
    u64 exec_clock;
    u64 min_vruntime;
    struct rb_root_cached tasks_timeline;
    struct sched_entity * curr;
    struct sched_entity * next;
    struct sched_entity * last;
    struct sched_entity * skip;
    unsigned int nr_spread_over;
    struct sched_avg avg;
    struct (anon) removed;
    long unsigned int tg_load_avg_contrib;
    long int propagate;
    long int prop_runnable_sum;
    long unsigned int h_load;
    u64 last_h_load_update;
    struct sched_entity * h_load_next;
    struct rq * rq;
    int on_list;
    struct list_head leaf_cfs_rq_list;
    struct task_group * tg;
    int runtime_enabled;
    int expires_seq;
    u64 runtime_expires;
    s64 runtime_remaining;
    u64 throttled_clock;
    u64 throttled_clock_task;
    u64 throttled_clock_task_time;
    int throttled;
    int throttle_count;
    struct list_head throttled_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct cfs_rq {
    struct load_weight load;
    long unsigned int runnable_weight;
    unsigned int nr_running;
    unsigned int h_nr_running;
    u64 exec_clock;
    u64 min_vruntime;
    struct rb_root_cached tasks_timeline;
    struct sched_entity * curr;
    struct sched_entity * next;
    struct sched_entity * last;
    struct sched_entity * skip;
    unsigned int nr_spread_over;
    struct sched_avg avg;
    struct (anon) removed;
    long unsigned int tg_load_avg_contrib;
    long int propagate;
    long int prop_runnable_sum;
    long unsigned int h_load;
    u64 last_h_load_update;
    struct sched_entity * h_load_next;
    struct rq * rq;
    int on_list;
    struct list_head leaf_cfs_rq_list;
    struct task_group * tg;
    int runtime_enabled;
    int expires_seq;
    u64 runtime_expires;
    s64 runtime_remaining;
    u64 throttled_clock;
    u64 throttled_clock_task;
    u64 throttled_clock_task_time;
    int throttled;
    int throttle_count;
    struct list_head throttled_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct cfs_rq {
    struct load_weight load;
    long unsigned int runnable_weight;
    unsigned int nr_running;
    unsigned int h_nr_running;
    unsigned int idle_h_nr_running;
    u64 exec_clock;
    u64 min_vruntime;
    struct rb_root_cached tasks_timeline;
    struct sched_entity * curr;
    struct sched_entity * next;
    struct sched_entity * last;
    struct sched_entity * skip;
    unsigned int nr_spread_over;
    struct sched_avg avg;
    struct (anon) removed;
    long unsigned int tg_load_avg_contrib;
    long int propagate;
    long int prop_runnable_sum;
    long unsigned int h_load;
    u64 last_h_load_update;
    struct sched_entity * h_load_next;
    struct rq * rq;
    int on_list;
    struct list_head leaf_cfs_rq_list;
    struct task_group * tg;
    int runtime_enabled;
    s64 runtime_remaining;
    u64 throttled_clock;
    u64 throttled_clock_task;
    u64 throttled_clock_task_time;
    int throttled;
    int throttle_count;
    struct list_head throttled_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct cfs_rq {
    struct load_weight load;
    unsigned int nr_running;
    unsigned int h_nr_running;
    unsigned int idle_h_nr_running;
    u64 exec_clock;
    u64 min_vruntime;
    struct rb_root_cached tasks_timeline;
    struct sched_entity * curr;
    struct sched_entity * next;
    struct sched_entity * last;
    struct sched_entity * skip;
    unsigned int nr_spread_over;
    struct sched_avg avg;
    struct (anon) removed;
    long unsigned int tg_load_avg_contrib;
    long int propagate;
    long int prop_runnable_sum;
    long unsigned int h_load;
    u64 last_h_load_update;
    struct sched_entity * h_load_next;
    struct rq * rq;
    int on_list;
    struct list_head leaf_cfs_rq_list;
    struct task_group * tg;
    int runtime_enabled;
    s64 runtime_remaining;
    u64 throttled_clock;
    u64 throttled_clock_task;
    u64 throttled_clock_task_time;
    int throttled;
    int throttle_count;
    struct list_head throttled_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct cfs_rq {
    struct load_weight load;
    unsigned int nr_running;
    unsigned int h_nr_running;
    unsigned int idle_h_nr_running;
    u64 exec_clock;
    u64 min_vruntime;
    struct rb_root_cached tasks_timeline;
    struct sched_entity * curr;
    struct sched_entity * next;
    struct sched_entity * last;
    struct sched_entity * skip;
    unsigned int nr_spread_over;
    struct sched_avg avg;
    struct (anon) removed;
    long unsigned int tg_load_avg_contrib;
    long int propagate;
    long int prop_runnable_sum;
    long unsigned int h_load;
    u64 last_h_load_update;
    struct sched_entity * h_load_next;
    struct rq * rq;
    int on_list;
    struct list_head leaf_cfs_rq_list;
    struct task_group * tg;
    int runtime_enabled;
    s64 runtime_remaining;
    u64 throttled_clock;
    u64 throttled_clock_task;
    u64 throttled_clock_task_time;
    int throttled;
    int throttle_count;
    struct list_head throttled_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct cfs_rq {
    struct load_weight load;
    unsigned int nr_running;
    unsigned int h_nr_running;
    unsigned int idle_h_nr_running;
    u64 exec_clock;
    u64 min_vruntime;
    struct rb_root_cached tasks_timeline;
    struct sched_entity * curr;
    struct sched_entity * next;
    struct sched_entity * last;
    struct sched_entity * skip;
    unsigned int nr_spread_over;
    struct sched_avg avg;
    struct (anon) removed;
    long unsigned int tg_load_avg_contrib;
    long int propagate;
    long int prop_runnable_sum;
    long unsigned int h_load;
    u64 last_h_load_update;
    struct sched_entity * h_load_next;
    struct rq * rq;
    int on_list;
    struct list_head leaf_cfs_rq_list;
    struct task_group * tg;
    int runtime_enabled;
    s64 runtime_remaining;
    u64 throttled_clock;
    u64 throttled_clock_task;
    u64 throttled_clock_task_time;
    int throttled;
    int throttle_count;
    struct list_head throttled_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct cfs_rq {
    struct load_weight load;
    unsigned int nr_running;
    unsigned int h_nr_running;
    unsigned int idle_h_nr_running;
    u64 exec_clock;
    u64 min_vruntime;
    unsigned int forceidle_seq;
    u64 min_vruntime_fi;
    struct rb_root_cached tasks_timeline;
    struct sched_entity * curr;
    struct sched_entity * next;
    struct sched_entity * last;
    struct sched_entity * skip;
    unsigned int nr_spread_over;
    struct sched_avg avg;
    struct (anon) removed;
    long unsigned int tg_load_avg_contrib;
    long int propagate;
    long int prop_runnable_sum;
    long unsigned int h_load;
    u64 last_h_load_update;
    struct sched_entity * h_load_next;
    struct rq * rq;
    int on_list;
    struct list_head leaf_cfs_rq_list;
    struct task_group * tg;
    int idle;
    int runtime_enabled;
    s64 runtime_remaining;
    u64 throttled_clock;
    u64 throttled_clock_task;
    u64 throttled_clock_task_time;
    int throttled;
    int throttle_count;
    struct list_head throttled_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct cfs_rq {
    struct load_weight load;
    unsigned int nr_running;
    unsigned int h_nr_running;
    unsigned int idle_nr_running;
    unsigned int idle_h_nr_running;
    u64 exec_clock;
    u64 min_vruntime;
    unsigned int forceidle_seq;
    u64 min_vruntime_fi;
    struct rb_root_cached tasks_timeline;
    struct sched_entity * curr;
    struct sched_entity * next;
    struct sched_entity * last;
    struct sched_entity * skip;
    unsigned int nr_spread_over;
    struct sched_avg avg;
    struct (anon) removed;
    long unsigned int tg_load_avg_contrib;
    long int propagate;
    long int prop_runnable_sum;
    long unsigned int h_load;
    u64 last_h_load_update;
    struct sched_entity * h_load_next;
    struct rq * rq;
    int on_list;
    struct list_head leaf_cfs_rq_list;
    struct task_group * tg;
    int idle;
    int runtime_enabled;
    s64 runtime_remaining;
    u64 throttled_clock;
    u64 throttled_clock_pelt;
    u64 throttled_clock_pelt_time;
    int throttled;
    int throttle_count;
    struct list_head throttled_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct cfs_rq {
    struct load_weight load;
    unsigned int nr_running;
    unsigned int h_nr_running;
    unsigned int idle_nr_running;
    unsigned int idle_h_nr_running;
    u64 exec_clock;
    u64 min_vruntime;
    unsigned int forceidle_seq;
    u64 min_vruntime_fi;
    struct rb_root_cached tasks_timeline;
    struct sched_entity * curr;
    struct sched_entity * next;
    struct sched_entity * last;
    struct sched_entity * skip;
    unsigned int nr_spread_over;
    struct sched_avg avg;
    struct (anon) removed;
    long unsigned int tg_load_avg_contrib;
    long int propagate;
    long int prop_runnable_sum;
    long unsigned int h_load;
    u64 last_h_load_update;
    struct sched_entity * h_load_next;
    struct rq * rq;
    int on_list;
    struct list_head leaf_cfs_rq_list;
    struct task_group * tg;
    int idle;
    int runtime_enabled;
    s64 runtime_remaining;
    u64 throttled_pelt_idle;
    u64 throttled_clock;
    u64 throttled_clock_pelt;
    u64 throttled_clock_pelt_time;
    int throttled;
    int throttle_count;
    struct list_head throttled_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct cfs_rq {
    struct load_weight load;
    unsigned int nr_running;
    unsigned int h_nr_running;
    unsigned int idle_nr_running;
    unsigned int idle_h_nr_running;
    u64 exec_clock;
    u64 min_vruntime;
    unsigned int forceidle_seq;
    u64 min_vruntime_fi;
    struct rb_root_cached tasks_timeline;
    struct sched_entity * curr;
    struct sched_entity * next;
    struct sched_entity * last;
    struct sched_entity * skip;
    unsigned int nr_spread_over;
    struct sched_avg avg;
    struct (anon) removed;
    long unsigned int tg_load_avg_contrib;
    long int propagate;
    long int prop_runnable_sum;
    long unsigned int h_load;
    u64 last_h_load_update;
    struct sched_entity * h_load_next;
    struct rq * rq;
    int on_list;
    struct list_head leaf_cfs_rq_list;
    struct task_group * tg;
    int idle;
    int runtime_enabled;
    s64 runtime_remaining;
    u64 throttled_pelt_idle;
    u64 throttled_clock;
    u64 throttled_clock_pelt;
    u64 throttled_clock_pelt_time;
    int throttled;
    int throttle_count;
    struct list_head throttled_list;
    struct list_head throttled_csd_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct cfs_rq {
    struct load_weight load;
    unsigned int nr_running;
    unsigned int h_nr_running;
    unsigned int idle_nr_running;
    unsigned int idle_h_nr_running;
    s64 avg_vruntime;
    u64 avg_load;
    u64 exec_clock;
    u64 min_vruntime;
    unsigned int forceidle_seq;
    u64 min_vruntime_fi;
    struct rb_root_cached tasks_timeline;
    struct sched_entity * curr;
    struct sched_entity * next;
    unsigned int nr_spread_over;
    struct sched_avg avg;
    struct (anon) removed;
    u64 last_update_tg_load_avg;
    long unsigned int tg_load_avg_contrib;
    long int propagate;
    long int prop_runnable_sum;
    long unsigned int h_load;
    u64 last_h_load_update;
    struct sched_entity * h_load_next;
    struct rq * rq;
    int on_list;
    struct list_head leaf_cfs_rq_list;
    struct task_group * tg;
    int idle;
    int runtime_enabled;
    s64 runtime_remaining;
    u64 throttled_pelt_idle;
    u64 throttled_clock;
    u64 throttled_clock_pelt;
    u64 throttled_clock_pelt_time;
    u64 throttled_clock_self;
    u64 throttled_clock_self_time;
    int throttled;
    int throttle_count;
    struct list_head throttled_list;
    struct list_head throttled_csd_list;
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
struct cfs_rq {
    struct load_weight load;
    long unsigned int runnable_weight;
    unsigned int nr_running;
    unsigned int h_nr_running;
    unsigned int idle_h_nr_running;
    u64 exec_clock;
    u64 min_vruntime;
    struct rb_root_cached tasks_timeline;
    struct sched_entity * curr;
    struct sched_entity * next;
    struct sched_entity * last;
    struct sched_entity * skip;
    unsigned int nr_spread_over;
    struct sched_avg avg;
    struct (anon) removed;
    long unsigned int tg_load_avg_contrib;
    long int propagate;
    long int prop_runnable_sum;
    long unsigned int h_load;
    u64 last_h_load_update;
    struct sched_entity * h_load_next;
    struct rq * rq;
    int on_list;
    struct list_head leaf_cfs_rq_list;
    struct task_group * tg;
    int runtime_enabled;
    s64 runtime_remaining;
    u64 throttled_clock;
    u64 throttled_clock_task;
    u64 throttled_clock_task_time;
    int throttled;
    int throttle_count;
    struct list_head throttled_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct cfs_rq {
    struct load_weight load;
    long unsigned int runnable_weight;
    unsigned int nr_running;
    unsigned int h_nr_running;
    unsigned int idle_h_nr_running;
    u64 exec_clock;
    u64 min_vruntime;
    u64 min_vruntime_copy;
    struct rb_root_cached tasks_timeline;
    struct sched_entity * curr;
    struct sched_entity * next;
    struct sched_entity * last;
    struct sched_entity * skip;
    unsigned int nr_spread_over;
    struct sched_avg avg;
    u64 load_last_update_time_copy;
    struct (anon) removed;
    long unsigned int tg_load_avg_contrib;
    long int propagate;
    long int prop_runnable_sum;
    long unsigned int h_load;
    u64 last_h_load_update;
    struct sched_entity * h_load_next;
    struct rq * rq;
    int on_list;
    struct list_head leaf_cfs_rq_list;
    struct task_group * tg;
    int runtime_enabled;
    s64 runtime_remaining;
    u64 throttled_clock;
    u64 throttled_clock_task;
    u64 throttled_clock_task_time;
    int throttled;
    int throttle_count;
    struct list_head throttled_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct cfs_rq {
    struct load_weight load;
    long unsigned int runnable_weight;
    unsigned int nr_running;
    unsigned int h_nr_running;
    unsigned int idle_h_nr_running;
    u64 exec_clock;
    u64 min_vruntime;
    struct rb_root_cached tasks_timeline;
    struct sched_entity * curr;
    struct sched_entity * next;
    struct sched_entity * last;
    struct sched_entity * skip;
    unsigned int nr_spread_over;
    struct sched_avg avg;
    struct (anon) removed;
    long unsigned int tg_load_avg_contrib;
    long int propagate;
    long int prop_runnable_sum;
    long unsigned int h_load;
    u64 last_h_load_update;
    struct sched_entity * h_load_next;
    struct rq * rq;
    int on_list;
    struct list_head leaf_cfs_rq_list;
    struct task_group * tg;
    int runtime_enabled;
    s64 runtime_remaining;
    u64 throttled_clock;
    u64 throttled_clock_task;
    u64 throttled_clock_task_time;
    int throttled;
    int throttle_count;
    struct list_head throttled_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct cfs_rq {
    struct load_weight load;
    long unsigned int runnable_weight;
    unsigned int nr_running;
    unsigned int h_nr_running;
    unsigned int idle_h_nr_running;
    u64 exec_clock;
    u64 min_vruntime;
    struct rb_root_cached tasks_timeline;
    struct sched_entity * curr;
    struct sched_entity * next;
    struct sched_entity * last;
    struct sched_entity * skip;
    unsigned int nr_spread_over;
    struct sched_avg avg;
    struct (anon) removed;
    long unsigned int tg_load_avg_contrib;
    long int propagate;
    long int prop_runnable_sum;
    long unsigned int h_load;
    u64 last_h_load_update;
    struct sched_entity * h_load_next;
    struct rq * rq;
    int on_list;
    struct list_head leaf_cfs_rq_list;
    struct task_group * tg;
    int runtime_enabled;
    s64 runtime_remaining;
    u64 throttled_clock;
    u64 throttled_clock_task;
    u64 throttled_clock_task_time;
    int throttled;
    int throttle_count;
    struct list_head throttled_list;
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
struct cfs_rq {
    struct load_weight load;
    long unsigned int runnable_weight;
    unsigned int nr_running;
    unsigned int h_nr_running;
    unsigned int idle_h_nr_running;
    u64 exec_clock;
    u64 min_vruntime;
    struct rb_root_cached tasks_timeline;
    struct sched_entity * curr;
    struct sched_entity * next;
    struct sched_entity * last;
    struct sched_entity * skip;
    unsigned int nr_spread_over;
    struct sched_avg avg;
    struct (anon) removed;
    long unsigned int tg_load_avg_contrib;
    long int propagate;
    long int prop_runnable_sum;
    long unsigned int h_load;
    u64 last_h_load_update;
    struct sched_entity * h_load_next;
    struct rq * rq;
    int on_list;
    struct list_head leaf_cfs_rq_list;
    struct task_group * tg;
    int runtime_enabled;
    s64 runtime_remaining;
    u64 throttled_clock;
    u64 throttled_clock_task;
    u64 throttled_clock_task_time;
    int throttled;
    int throttle_count;
    struct list_head throttled_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct cfs_rq {
    struct load_weight load;
    long unsigned int runnable_weight;
    unsigned int nr_running;
    unsigned int h_nr_running;
    unsigned int idle_h_nr_running;
    u64 exec_clock;
    u64 min_vruntime;
    struct rb_root_cached tasks_timeline;
    struct sched_entity * curr;
    struct sched_entity * next;
    struct sched_entity * last;
    struct sched_entity * skip;
    unsigned int nr_spread_over;
    struct sched_avg avg;
    struct (anon) removed;
    long unsigned int tg_load_avg_contrib;
    long int propagate;
    long int prop_runnable_sum;
    long unsigned int h_load;
    u64 last_h_load_update;
    struct sched_entity * h_load_next;
    struct rq * rq;
    int on_list;
    struct list_head leaf_cfs_rq_list;
    struct task_group * tg;
    int runtime_enabled;
    s64 runtime_remaining;
    u64 throttled_clock;
    u64 throttled_clock_task;
    u64 throttled_clock_task_time;
    int throttled;
    int throttle_count;
    struct list_head throttled_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct cfs_rq {
    struct load_weight load;
    long unsigned int runnable_weight;
    unsigned int nr_running;
    unsigned int h_nr_running;
    unsigned int idle_h_nr_running;
    u64 exec_clock;
    u64 min_vruntime;
    struct rb_root_cached tasks_timeline;
    struct sched_entity * curr;
    struct sched_entity * next;
    struct sched_entity * last;
    struct sched_entity * skip;
    unsigned int nr_spread_over;
    struct sched_avg avg;
    struct (anon) removed;
    long unsigned int tg_load_avg_contrib;
    long int propagate;
    long int prop_runnable_sum;
    long unsigned int h_load;
    u64 last_h_load_update;
    struct sched_entity * h_load_next;
    struct rq * rq;
    int on_list;
    struct list_head leaf_cfs_rq_list;
    struct task_group * tg;
    int runtime_enabled;
    s64 runtime_remaining;
    u64 throttled_clock;
    u64 throttled_clock_task;
    u64 throttled_clock_task_time;
    int throttled;
    int throttle_count;
    struct list_head throttled_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct cfs_rq {
    struct load_weight load;
    long unsigned int runnable_weight;
    unsigned int nr_running;
    unsigned int h_nr_running;
    unsigned int idle_h_nr_running;
    u64 exec_clock;
    u64 min_vruntime;
    struct rb_root_cached tasks_timeline;
    struct sched_entity * curr;
    struct sched_entity * next;
    struct sched_entity * last;
    struct sched_entity * skip;
    unsigned int nr_spread_over;
    struct sched_avg avg;
    struct (anon) removed;
    long unsigned int tg_load_avg_contrib;
    long int propagate;
    long int prop_runnable_sum;
    long unsigned int h_load;
    u64 last_h_load_update;
    struct sched_entity * h_load_next;
    struct rq * rq;
    int on_list;
    struct list_head leaf_cfs_rq_list;
    struct task_group * tg;
    int runtime_enabled;
    s64 runtime_remaining;
    u64 throttled_clock;
    u64 throttled_clock_task;
    u64 throttled_clock_task_time;
    int throttled;
    int throttle_count;
    struct list_head throttled_list;
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
<code>long unsigned int propagate_avg</code>
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
<code>long unsigned int runnable_weight</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) removed</code>
</li>
<li>
<b>Field added. </b>
<code>long int propagate</code>
</li>
<li>
<b>Field added. </b>
<code>long int prop_runnable_sum</code>
</li>
<li>
<b>Field removed. </b>
<code>struct rb_node * rb_leftmost</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 runnable_load_sum</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int runnable_load_avg</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int propagate_avg</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_long_t removed_load_avg</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_long_t removed_util_avg</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct rb_root tasks_timeline</code> ➡️ <code>struct rb_root_cached tasks_timeline</code>
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
<code>int expires_seq</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
<code>unsigned int idle_h_nr_running</code>
</li>
<li>
<b>Field removed. </b>
<code>int expires_seq</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 runtime_expires</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>long unsigned int runnable_weight</code>
</li>
</ul>
</details>
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
<code>unsigned int forceidle_seq</code>
</li>
<li>
<b>Field added. </b>
<code>u64 min_vruntime_fi</code>
</li>
<li>
<b>Field added. </b>
<code>int idle</code>
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
<code>unsigned int idle_nr_running</code>
</li>
<li>
<b>Field added. </b>
<code>u64 throttled_clock_pelt</code>
</li>
<li>
<b>Field added. </b>
<code>u64 throttled_clock_pelt_time</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 throttled_clock_task</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 throttled_clock_task_time</code>
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
<code>u64 throttled_pelt_idle</code>
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
<code>struct list_head throttled_csd_list</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>s64 avg_vruntime</code>
</li>
<li>
<b>Field added. </b>
<code>u64 avg_load</code>
</li>
<li>
<b>Field added. </b>
<code>u64 last_update_tg_load_avg</code>
</li>
<li>
<b>Field added. </b>
<code>u64 throttled_clock_self</code>
</li>
<li>
<b>Field added. </b>
<code>u64 throttled_clock_self_time</code>
</li>
<li>
<b>Field removed. </b>
<code>struct sched_entity * last</code>
</li>
<li>
<b>Field removed. </b>
<code>struct sched_entity * skip</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 min_vruntime_copy</code>
</li>
<li>
<b>Field added. </b>
<code>u64 load_last_update_time_copy</code>
</li>
</ul>
</details>
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
