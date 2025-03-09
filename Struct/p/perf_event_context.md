# Struct: <code>perf_event_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct perf_event_context {
    struct pmu * pmu;
    raw_spinlock_t lock;
    struct mutex mutex;
    struct list_head active_ctx_list;
    struct list_head pinned_groups;
    struct list_head flexible_groups;
    struct list_head event_list;
    int nr_events;
    int nr_active;
    int is_active;
    int nr_stat;
    int nr_freq;
    int rotate_disable;
    atomic_t refcount;
    struct task_struct * task;
    u64 time;
    u64 timestamp;
    struct perf_event_context * parent_ctx;
    u64 parent_gen;
    u64 generation;
    int pin_count;
    int nr_cgroups;
    void * task_ctx_data;
    struct callback_head callback_head;
    struct delayed_work orphans_remove;
    bool orphans_remove_sched;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct perf_event_context {
    struct pmu * pmu;
    raw_spinlock_t lock;
    struct mutex mutex;
    struct list_head active_ctx_list;
    struct list_head pinned_groups;
    struct list_head flexible_groups;
    struct list_head event_list;
    int nr_events;
    int nr_active;
    int is_active;
    int nr_stat;
    int nr_freq;
    int rotate_disable;
    atomic_t refcount;
    struct task_struct * task;
    u64 time;
    u64 timestamp;
    struct perf_event_context * parent_ctx;
    u64 parent_gen;
    u64 generation;
    int pin_count;
    int nr_cgroups;
    void * task_ctx_data;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct perf_event_context {
    struct pmu * pmu;
    raw_spinlock_t lock;
    struct mutex mutex;
    struct list_head active_ctx_list;
    struct list_head pinned_groups;
    struct list_head flexible_groups;
    struct list_head event_list;
    int nr_events;
    int nr_active;
    int is_active;
    int nr_stat;
    int nr_freq;
    int rotate_disable;
    atomic_t refcount;
    struct task_struct * task;
    u64 time;
    u64 timestamp;
    struct perf_event_context * parent_ctx;
    u64 parent_gen;
    u64 generation;
    int pin_count;
    int nr_cgroups;
    void * task_ctx_data;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct perf_event_context {
    struct pmu * pmu;
    raw_spinlock_t lock;
    struct mutex mutex;
    struct list_head active_ctx_list;
    struct list_head pinned_groups;
    struct list_head flexible_groups;
    struct list_head event_list;
    int nr_events;
    int nr_active;
    int is_active;
    int nr_stat;
    int nr_freq;
    int rotate_disable;
    atomic_t refcount;
    struct task_struct * task;
    u64 time;
    u64 timestamp;
    struct perf_event_context * parent_ctx;
    u64 parent_gen;
    u64 generation;
    int pin_count;
    int nr_cgroups;
    void * task_ctx_data;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct perf_event_context {
    struct pmu * pmu;
    raw_spinlock_t lock;
    struct mutex mutex;
    struct list_head active_ctx_list;
    struct list_head pinned_groups;
    struct list_head flexible_groups;
    struct list_head event_list;
    int nr_events;
    int nr_active;
    int is_active;
    int nr_stat;
    int nr_freq;
    int rotate_disable;
    atomic_t refcount;
    struct task_struct * task;
    u64 time;
    u64 timestamp;
    struct perf_event_context * parent_ctx;
    u64 parent_gen;
    u64 generation;
    int pin_count;
    int nr_cgroups;
    void * task_ctx_data;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct perf_event_context {
    struct pmu * pmu;
    raw_spinlock_t lock;
    struct mutex mutex;
    struct list_head active_ctx_list;
    struct perf_event_groups pinned_groups;
    struct perf_event_groups flexible_groups;
    struct list_head event_list;
    struct list_head pinned_active;
    struct list_head flexible_active;
    int nr_events;
    int nr_active;
    int is_active;
    int nr_stat;
    int nr_freq;
    int rotate_disable;
    atomic_t refcount;
    struct task_struct * task;
    u64 time;
    u64 timestamp;
    struct perf_event_context * parent_ctx;
    u64 parent_gen;
    u64 generation;
    int pin_count;
    int nr_cgroups;
    void * task_ctx_data;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct perf_event_context {
    struct pmu * pmu;
    raw_spinlock_t lock;
    struct mutex mutex;
    struct list_head active_ctx_list;
    struct perf_event_groups pinned_groups;
    struct perf_event_groups flexible_groups;
    struct list_head event_list;
    struct list_head pinned_active;
    struct list_head flexible_active;
    int nr_events;
    int nr_active;
    int is_active;
    int nr_stat;
    int nr_freq;
    int rotate_disable;
    atomic_t refcount;
    struct task_struct * task;
    u64 time;
    u64 timestamp;
    struct perf_event_context * parent_ctx;
    u64 parent_gen;
    u64 generation;
    int pin_count;
    int nr_cgroups;
    void * task_ctx_data;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct perf_event_context {
    struct pmu * pmu;
    raw_spinlock_t lock;
    struct mutex mutex;
    struct list_head active_ctx_list;
    struct perf_event_groups pinned_groups;
    struct perf_event_groups flexible_groups;
    struct list_head event_list;
    struct list_head pinned_active;
    struct list_head flexible_active;
    int nr_events;
    int nr_active;
    int is_active;
    int nr_stat;
    int nr_freq;
    int rotate_disable;
    int rotate_necessary;
    refcount_t refcount;
    struct task_struct * task;
    u64 time;
    u64 timestamp;
    struct perf_event_context * parent_ctx;
    u64 parent_gen;
    u64 generation;
    int pin_count;
    int nr_cgroups;
    void * task_ctx_data;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct perf_event_context {
    struct pmu * pmu;
    raw_spinlock_t lock;
    struct mutex mutex;
    struct list_head active_ctx_list;
    struct perf_event_groups pinned_groups;
    struct perf_event_groups flexible_groups;
    struct list_head event_list;
    struct list_head pinned_active;
    struct list_head flexible_active;
    int nr_events;
    int nr_active;
    int is_active;
    int nr_stat;
    int nr_freq;
    int rotate_disable;
    int rotate_necessary;
    refcount_t refcount;
    struct task_struct * task;
    u64 time;
    u64 timestamp;
    struct perf_event_context * parent_ctx;
    u64 parent_gen;
    u64 generation;
    int pin_count;
    int nr_cgroups;
    void * task_ctx_data;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct perf_event_context {
    struct pmu * pmu;
    raw_spinlock_t lock;
    struct mutex mutex;
    struct list_head active_ctx_list;
    struct perf_event_groups pinned_groups;
    struct perf_event_groups flexible_groups;
    struct list_head event_list;
    struct list_head pinned_active;
    struct list_head flexible_active;
    int nr_events;
    int nr_active;
    int is_active;
    int nr_stat;
    int nr_freq;
    int rotate_disable;
    int rotate_necessary;
    refcount_t refcount;
    struct task_struct * task;
    u64 time;
    u64 timestamp;
    struct perf_event_context * parent_ctx;
    u64 parent_gen;
    u64 generation;
    int pin_count;
    int nr_cgroups;
    void * task_ctx_data;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct perf_event_context {
    struct pmu * pmu;
    raw_spinlock_t lock;
    struct mutex mutex;
    struct list_head active_ctx_list;
    struct perf_event_groups pinned_groups;
    struct perf_event_groups flexible_groups;
    struct list_head event_list;
    struct list_head pinned_active;
    struct list_head flexible_active;
    int nr_events;
    int nr_active;
    int is_active;
    int nr_stat;
    int nr_freq;
    int rotate_disable;
    int rotate_necessary;
    refcount_t refcount;
    struct task_struct * task;
    u64 time;
    u64 timestamp;
    struct perf_event_context * parent_ctx;
    u64 parent_gen;
    u64 generation;
    int pin_count;
    int nr_cgroups;
    void * task_ctx_data;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct perf_event_context {
    struct pmu * pmu;
    raw_spinlock_t lock;
    struct mutex mutex;
    struct list_head active_ctx_list;
    struct perf_event_groups pinned_groups;
    struct perf_event_groups flexible_groups;
    struct list_head event_list;
    struct list_head pinned_active;
    struct list_head flexible_active;
    int nr_events;
    int nr_active;
    int is_active;
    int nr_stat;
    int nr_freq;
    int rotate_disable;
    int rotate_necessary;
    refcount_t refcount;
    struct task_struct * task;
    u64 time;
    u64 timestamp;
    struct perf_event_context * parent_ctx;
    u64 parent_gen;
    u64 generation;
    int pin_count;
    int nr_cgroups;
    void * task_ctx_data;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct perf_event_context {
    struct pmu * pmu;
    raw_spinlock_t lock;
    struct mutex mutex;
    struct list_head active_ctx_list;
    struct perf_event_groups pinned_groups;
    struct perf_event_groups flexible_groups;
    struct list_head event_list;
    struct list_head pinned_active;
    struct list_head flexible_active;
    int nr_events;
    int nr_active;
    int is_active;
    int nr_stat;
    int nr_freq;
    int rotate_disable;
    int rotate_necessary;
    refcount_t refcount;
    struct task_struct * task;
    u64 time;
    u64 timestamp;
    u64 timeoffset;
    struct perf_event_context * parent_ctx;
    u64 parent_gen;
    u64 generation;
    int pin_count;
    int nr_cgroups;
    void * task_ctx_data;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct perf_event_context {
    struct pmu * pmu;
    raw_spinlock_t lock;
    struct mutex mutex;
    struct list_head active_ctx_list;
    struct perf_event_groups pinned_groups;
    struct perf_event_groups flexible_groups;
    struct list_head event_list;
    struct list_head pinned_active;
    struct list_head flexible_active;
    int nr_events;
    int nr_active;
    int nr_user;
    int is_active;
    int nr_stat;
    int nr_freq;
    int rotate_disable;
    int rotate_necessary;
    refcount_t refcount;
    struct task_struct * task;
    u64 time;
    u64 timestamp;
    u64 timeoffset;
    struct perf_event_context * parent_ctx;
    u64 parent_gen;
    u64 generation;
    int pin_count;
    int nr_cgroups;
    void * task_ctx_data;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct perf_event_context {
    raw_spinlock_t lock;
    struct mutex mutex;
    struct list_head pmu_ctx_list;
    struct perf_event_groups pinned_groups;
    struct perf_event_groups flexible_groups;
    struct list_head event_list;
    int nr_events;
    int nr_user;
    int is_active;
    int nr_task_data;
    int nr_stat;
    int nr_freq;
    int rotate_disable;
    refcount_t refcount;
    struct task_struct * task;
    u64 time;
    u64 timestamp;
    u64 timeoffset;
    struct perf_event_context * parent_ctx;
    u64 parent_gen;
    u64 generation;
    int pin_count;
    int nr_cgroups;
    struct callback_head callback_head;
    local_t nr_pending;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct perf_event_context {
    raw_spinlock_t lock;
    struct mutex mutex;
    struct list_head pmu_ctx_list;
    struct perf_event_groups pinned_groups;
    struct perf_event_groups flexible_groups;
    struct list_head event_list;
    int nr_events;
    int nr_user;
    int is_active;
    int nr_task_data;
    int nr_stat;
    int nr_freq;
    int rotate_disable;
    refcount_t refcount;
    struct task_struct * task;
    u64 time;
    u64 timestamp;
    u64 timeoffset;
    struct perf_event_context * parent_ctx;
    u64 parent_gen;
    u64 generation;
    int pin_count;
    int nr_cgroups;
    struct callback_head callback_head;
    local_t nr_pending;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct perf_event_context {
    raw_spinlock_t lock;
    struct mutex mutex;
    struct list_head pmu_ctx_list;
    struct perf_event_groups pinned_groups;
    struct perf_event_groups flexible_groups;
    struct list_head event_list;
    int nr_events;
    int nr_user;
    int is_active;
    int nr_task_data;
    int nr_stat;
    int nr_freq;
    int rotate_disable;
    refcount_t refcount;
    struct task_struct * task;
    u64 time;
    u64 timestamp;
    u64 timeoffset;
    struct perf_event_context * parent_ctx;
    u64 parent_gen;
    u64 generation;
    int pin_count;
    int nr_cgroups;
    struct callback_head callback_head;
    local_t nr_pending;
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
struct perf_event_context {
    struct pmu * pmu;
    raw_spinlock_t lock;
    struct mutex mutex;
    struct list_head active_ctx_list;
    struct perf_event_groups pinned_groups;
    struct perf_event_groups flexible_groups;
    struct list_head event_list;
    struct list_head pinned_active;
    struct list_head flexible_active;
    int nr_events;
    int nr_active;
    int is_active;
    int nr_stat;
    int nr_freq;
    int rotate_disable;
    int rotate_necessary;
    refcount_t refcount;
    struct task_struct * task;
    u64 time;
    u64 timestamp;
    struct perf_event_context * parent_ctx;
    u64 parent_gen;
    u64 generation;
    int pin_count;
    int nr_cgroups;
    void * task_ctx_data;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct perf_event_context {
    struct pmu * pmu;
    raw_spinlock_t lock;
    struct mutex mutex;
    struct list_head active_ctx_list;
    struct perf_event_groups pinned_groups;
    struct perf_event_groups flexible_groups;
    struct list_head event_list;
    struct list_head pinned_active;
    struct list_head flexible_active;
    int nr_events;
    int nr_active;
    int is_active;
    int nr_stat;
    int nr_freq;
    int rotate_disable;
    int rotate_necessary;
    refcount_t refcount;
    struct task_struct * task;
    u64 time;
    u64 timestamp;
    struct perf_event_context * parent_ctx;
    u64 parent_gen;
    u64 generation;
    int pin_count;
    int nr_cgroups;
    void * task_ctx_data;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct perf_event_context {
    struct pmu * pmu;
    raw_spinlock_t lock;
    struct mutex mutex;
    struct list_head active_ctx_list;
    struct perf_event_groups pinned_groups;
    struct perf_event_groups flexible_groups;
    struct list_head event_list;
    struct list_head pinned_active;
    struct list_head flexible_active;
    int nr_events;
    int nr_active;
    int is_active;
    int nr_stat;
    int nr_freq;
    int rotate_disable;
    int rotate_necessary;
    refcount_t refcount;
    struct task_struct * task;
    u64 time;
    u64 timestamp;
    struct perf_event_context * parent_ctx;
    u64 parent_gen;
    u64 generation;
    int pin_count;
    int nr_cgroups;
    void * task_ctx_data;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct perf_event_context {
    struct pmu * pmu;
    raw_spinlock_t lock;
    struct mutex mutex;
    struct list_head active_ctx_list;
    struct perf_event_groups pinned_groups;
    struct perf_event_groups flexible_groups;
    struct list_head event_list;
    struct list_head pinned_active;
    struct list_head flexible_active;
    int nr_events;
    int nr_active;
    int is_active;
    int nr_stat;
    int nr_freq;
    int rotate_disable;
    int rotate_necessary;
    refcount_t refcount;
    struct task_struct * task;
    u64 time;
    u64 timestamp;
    struct perf_event_context * parent_ctx;
    u64 parent_gen;
    u64 generation;
    int pin_count;
    int nr_cgroups;
    void * task_ctx_data;
    struct callback_head callback_head;
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
struct perf_event_context {
    struct pmu * pmu;
    raw_spinlock_t lock;
    struct mutex mutex;
    struct list_head active_ctx_list;
    struct perf_event_groups pinned_groups;
    struct perf_event_groups flexible_groups;
    struct list_head event_list;
    struct list_head pinned_active;
    struct list_head flexible_active;
    int nr_events;
    int nr_active;
    int is_active;
    int nr_stat;
    int nr_freq;
    int rotate_disable;
    int rotate_necessary;
    refcount_t refcount;
    struct task_struct * task;
    u64 time;
    u64 timestamp;
    struct perf_event_context * parent_ctx;
    u64 parent_gen;
    u64 generation;
    int pin_count;
    int nr_cgroups;
    void * task_ctx_data;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct perf_event_context {
    struct pmu * pmu;
    raw_spinlock_t lock;
    struct mutex mutex;
    struct list_head active_ctx_list;
    struct perf_event_groups pinned_groups;
    struct perf_event_groups flexible_groups;
    struct list_head event_list;
    struct list_head pinned_active;
    struct list_head flexible_active;
    int nr_events;
    int nr_active;
    int is_active;
    int nr_stat;
    int nr_freq;
    int rotate_disable;
    int rotate_necessary;
    refcount_t refcount;
    struct task_struct * task;
    u64 time;
    u64 timestamp;
    struct perf_event_context * parent_ctx;
    u64 parent_gen;
    u64 generation;
    int pin_count;
    int nr_cgroups;
    void * task_ctx_data;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct perf_event_context {
    struct pmu * pmu;
    raw_spinlock_t lock;
    struct mutex mutex;
    struct list_head active_ctx_list;
    struct perf_event_groups pinned_groups;
    struct perf_event_groups flexible_groups;
    struct list_head event_list;
    struct list_head pinned_active;
    struct list_head flexible_active;
    int nr_events;
    int nr_active;
    int is_active;
    int nr_stat;
    int nr_freq;
    int rotate_disable;
    int rotate_necessary;
    refcount_t refcount;
    struct task_struct * task;
    u64 time;
    u64 timestamp;
    struct perf_event_context * parent_ctx;
    u64 parent_gen;
    u64 generation;
    int pin_count;
    int nr_cgroups;
    void * task_ctx_data;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct perf_event_context {
    struct pmu * pmu;
    raw_spinlock_t lock;
    struct mutex mutex;
    struct list_head active_ctx_list;
    struct perf_event_groups pinned_groups;
    struct perf_event_groups flexible_groups;
    struct list_head event_list;
    struct list_head pinned_active;
    struct list_head flexible_active;
    int nr_events;
    int nr_active;
    int is_active;
    int nr_stat;
    int nr_freq;
    int rotate_disable;
    int rotate_necessary;
    refcount_t refcount;
    struct task_struct * task;
    u64 time;
    u64 timestamp;
    struct perf_event_context * parent_ctx;
    u64 parent_gen;
    u64 generation;
    int pin_count;
    int nr_cgroups;
    void * task_ctx_data;
    struct callback_head callback_head;
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
<b>Field removed. </b>
<code>struct delayed_work orphans_remove</code>
</li>
<li>
<b>Field removed. </b>
<code>bool orphans_remove_sched</code>
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct list_head pinned_active</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head flexible_active</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head pinned_groups</code> ➡️ <code>struct perf_event_groups pinned_groups</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head flexible_groups</code> ➡️ <code>struct perf_event_groups flexible_groups</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int rotate_necessary</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_t refcount</code> ➡️ <code>refcount_t refcount</code>
</li>
</ul>
</details>
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
<code>u64 timeoffset</code>
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
<code>int nr_user</code>
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
<code>struct list_head pmu_ctx_list</code>
</li>
<li>
<b>Field added. </b>
<code>int nr_task_data</code>
</li>
<li>
<b>Field added. </b>
<code>local_t nr_pending</code>
</li>
<li>
<b>Field removed. </b>
<code>struct pmu * pmu</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head active_ctx_list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head pinned_active</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head flexible_active</code>
</li>
<li>
<b>Field removed. </b>
<code>int nr_active</code>
</li>
<li>
<b>Field removed. </b>
<code>int rotate_necessary</code>
</li>
<li>
<b>Field removed. </b>
<code>void * task_ctx_data</code>
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
