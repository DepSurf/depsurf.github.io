# Struct: <code>perf_cpu_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct perf_cpu_context {
    struct perf_event_context ctx;
    struct perf_event_context * task_ctx;
    int active_oncpu;
    int exclusive;
    raw_spinlock_t hrtimer_lock;
    struct hrtimer hrtimer;
    ktime_t hrtimer_interval;
    unsigned int hrtimer_active;
    struct pmu * unique_pmu;
    struct perf_cgroup * cgrp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct perf_cpu_context {
    struct perf_event_context ctx;
    struct perf_event_context * task_ctx;
    int active_oncpu;
    int exclusive;
    raw_spinlock_t hrtimer_lock;
    struct hrtimer hrtimer;
    ktime_t hrtimer_interval;
    unsigned int hrtimer_active;
    struct pmu * unique_pmu;
    struct perf_cgroup * cgrp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct perf_cpu_context {
    struct perf_event_context ctx;
    struct perf_event_context * task_ctx;
    int active_oncpu;
    int exclusive;
    raw_spinlock_t hrtimer_lock;
    struct hrtimer hrtimer;
    ktime_t hrtimer_interval;
    unsigned int hrtimer_active;
    struct pmu * unique_pmu;
    struct perf_cgroup * cgrp;
    struct list_head sched_cb_entry;
    int sched_cb_usage;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct perf_cpu_context {
    struct perf_event_context ctx;
    struct perf_event_context * task_ctx;
    int active_oncpu;
    int exclusive;
    raw_spinlock_t hrtimer_lock;
    struct hrtimer hrtimer;
    ktime_t hrtimer_interval;
    unsigned int hrtimer_active;
    struct perf_cgroup * cgrp;
    struct list_head cgrp_cpuctx_entry;
    struct list_head sched_cb_entry;
    int sched_cb_usage;
    int online;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct perf_cpu_context {
    struct perf_event_context ctx;
    struct perf_event_context * task_ctx;
    int active_oncpu;
    int exclusive;
    raw_spinlock_t hrtimer_lock;
    struct hrtimer hrtimer;
    ktime_t hrtimer_interval;
    unsigned int hrtimer_active;
    struct perf_cgroup * cgrp;
    struct list_head cgrp_cpuctx_entry;
    struct list_head sched_cb_entry;
    int sched_cb_usage;
    int online;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct perf_cpu_context {
    struct perf_event_context ctx;
    struct perf_event_context * task_ctx;
    int active_oncpu;
    int exclusive;
    raw_spinlock_t hrtimer_lock;
    struct hrtimer hrtimer;
    ktime_t hrtimer_interval;
    unsigned int hrtimer_active;
    struct perf_cgroup * cgrp;
    struct list_head cgrp_cpuctx_entry;
    struct list_head sched_cb_entry;
    int sched_cb_usage;
    int online;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct perf_cpu_context {
    struct perf_event_context ctx;
    struct perf_event_context * task_ctx;
    int active_oncpu;
    int exclusive;
    raw_spinlock_t hrtimer_lock;
    struct hrtimer hrtimer;
    ktime_t hrtimer_interval;
    unsigned int hrtimer_active;
    struct perf_cgroup * cgrp;
    struct list_head cgrp_cpuctx_entry;
    struct list_head sched_cb_entry;
    int sched_cb_usage;
    int online;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct perf_cpu_context {
    struct perf_event_context ctx;
    struct perf_event_context * task_ctx;
    int active_oncpu;
    int exclusive;
    raw_spinlock_t hrtimer_lock;
    struct hrtimer hrtimer;
    ktime_t hrtimer_interval;
    unsigned int hrtimer_active;
    struct perf_cgroup * cgrp;
    struct list_head cgrp_cpuctx_entry;
    struct list_head sched_cb_entry;
    int sched_cb_usage;
    int online;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct perf_cpu_context {
    struct perf_event_context ctx;
    struct perf_event_context * task_ctx;
    int active_oncpu;
    int exclusive;
    raw_spinlock_t hrtimer_lock;
    struct hrtimer hrtimer;
    ktime_t hrtimer_interval;
    unsigned int hrtimer_active;
    struct perf_cgroup * cgrp;
    struct list_head cgrp_cpuctx_entry;
    struct list_head sched_cb_entry;
    int sched_cb_usage;
    int online;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct perf_cpu_context {
    struct perf_event_context ctx;
    struct perf_event_context * task_ctx;
    int active_oncpu;
    int exclusive;
    raw_spinlock_t hrtimer_lock;
    struct hrtimer hrtimer;
    ktime_t hrtimer_interval;
    unsigned int hrtimer_active;
    struct perf_cgroup * cgrp;
    struct list_head cgrp_cpuctx_entry;
    struct list_head sched_cb_entry;
    int sched_cb_usage;
    int online;
    int heap_size;
    struct perf_event * * heap;
    struct perf_event *[2] heap_default;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct perf_cpu_context {
    struct perf_event_context ctx;
    struct perf_event_context * task_ctx;
    int active_oncpu;
    int exclusive;
    raw_spinlock_t hrtimer_lock;
    struct hrtimer hrtimer;
    ktime_t hrtimer_interval;
    unsigned int hrtimer_active;
    struct perf_cgroup * cgrp;
    struct list_head cgrp_cpuctx_entry;
    struct list_head sched_cb_entry;
    int sched_cb_usage;
    int online;
    int heap_size;
    struct perf_event * * heap;
    struct perf_event *[2] heap_default;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct perf_cpu_context {
    struct perf_event_context ctx;
    struct perf_event_context * task_ctx;
    int active_oncpu;
    int exclusive;
    raw_spinlock_t hrtimer_lock;
    struct hrtimer hrtimer;
    ktime_t hrtimer_interval;
    unsigned int hrtimer_active;
    struct perf_cgroup * cgrp;
    struct list_head cgrp_cpuctx_entry;
    struct list_head sched_cb_entry;
    int sched_cb_usage;
    int online;
    int heap_size;
    struct perf_event * * heap;
    struct perf_event *[2] heap_default;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct perf_cpu_context {
    struct perf_event_context ctx;
    struct perf_event_context * task_ctx;
    int active_oncpu;
    int exclusive;
    raw_spinlock_t hrtimer_lock;
    struct hrtimer hrtimer;
    ktime_t hrtimer_interval;
    unsigned int hrtimer_active;
    struct perf_cgroup * cgrp;
    struct list_head cgrp_cpuctx_entry;
    struct list_head sched_cb_entry;
    int sched_cb_usage;
    int online;
    int heap_size;
    struct perf_event * * heap;
    struct perf_event *[2] heap_default;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct perf_cpu_context {
    struct perf_event_context ctx;
    struct perf_event_context * task_ctx;
    int active_oncpu;
    int exclusive;
    raw_spinlock_t hrtimer_lock;
    struct hrtimer hrtimer;
    ktime_t hrtimer_interval;
    unsigned int hrtimer_active;
    struct perf_cgroup * cgrp;
    struct list_head cgrp_cpuctx_entry;
    struct list_head sched_cb_entry;
    int sched_cb_usage;
    int online;
    int heap_size;
    struct perf_event * * heap;
    struct perf_event *[2] heap_default;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct perf_cpu_context {
    struct perf_event_context ctx;
    struct perf_event_context * task_ctx;
    int online;
    struct perf_cgroup * cgrp;
    int heap_size;
    struct perf_event * * heap;
    struct perf_event *[2] heap_default;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct perf_cpu_context {
    struct perf_event_context ctx;
    struct perf_event_context * task_ctx;
    int online;
    struct perf_cgroup * cgrp;
    int heap_size;
    struct perf_event * * heap;
    struct perf_event *[2] heap_default;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct perf_cpu_context {
    struct perf_event_context ctx;
    struct perf_event_context * task_ctx;
    int online;
    struct perf_cgroup * cgrp;
    int heap_size;
    struct perf_event * * heap;
    struct perf_event *[2] heap_default;
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
struct perf_cpu_context {
    struct perf_event_context ctx;
    struct perf_event_context * task_ctx;
    int active_oncpu;
    int exclusive;
    raw_spinlock_t hrtimer_lock;
    struct hrtimer hrtimer;
    ktime_t hrtimer_interval;
    unsigned int hrtimer_active;
    struct perf_cgroup * cgrp;
    struct list_head cgrp_cpuctx_entry;
    struct list_head sched_cb_entry;
    int sched_cb_usage;
    int online;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct perf_cpu_context {
    struct perf_event_context ctx;
    struct perf_event_context * task_ctx;
    int active_oncpu;
    int exclusive;
    raw_spinlock_t hrtimer_lock;
    struct hrtimer hrtimer;
    ktime_t hrtimer_interval;
    unsigned int hrtimer_active;
    struct perf_cgroup * cgrp;
    struct list_head cgrp_cpuctx_entry;
    struct list_head sched_cb_entry;
    int sched_cb_usage;
    int online;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct perf_cpu_context {
    struct perf_event_context ctx;
    struct perf_event_context * task_ctx;
    int active_oncpu;
    int exclusive;
    raw_spinlock_t hrtimer_lock;
    struct hrtimer hrtimer;
    ktime_t hrtimer_interval;
    unsigned int hrtimer_active;
    struct perf_cgroup * cgrp;
    struct list_head cgrp_cpuctx_entry;
    struct list_head sched_cb_entry;
    int sched_cb_usage;
    int online;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct perf_cpu_context {
    struct perf_event_context ctx;
    struct perf_event_context * task_ctx;
    int active_oncpu;
    int exclusive;
    raw_spinlock_t hrtimer_lock;
    struct hrtimer hrtimer;
    ktime_t hrtimer_interval;
    unsigned int hrtimer_active;
    struct perf_cgroup * cgrp;
    struct list_head cgrp_cpuctx_entry;
    struct list_head sched_cb_entry;
    int sched_cb_usage;
    int online;
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
struct perf_cpu_context {
    struct perf_event_context ctx;
    struct perf_event_context * task_ctx;
    int active_oncpu;
    int exclusive;
    raw_spinlock_t hrtimer_lock;
    struct hrtimer hrtimer;
    ktime_t hrtimer_interval;
    unsigned int hrtimer_active;
    struct perf_cgroup * cgrp;
    struct list_head cgrp_cpuctx_entry;
    struct list_head sched_cb_entry;
    int sched_cb_usage;
    int online;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct perf_cpu_context {
    struct perf_event_context ctx;
    struct perf_event_context * task_ctx;
    int active_oncpu;
    int exclusive;
    raw_spinlock_t hrtimer_lock;
    struct hrtimer hrtimer;
    ktime_t hrtimer_interval;
    unsigned int hrtimer_active;
    struct perf_cgroup * cgrp;
    struct list_head cgrp_cpuctx_entry;
    struct list_head sched_cb_entry;
    int sched_cb_usage;
    int online;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct perf_cpu_context {
    struct perf_event_context ctx;
    struct perf_event_context * task_ctx;
    int active_oncpu;
    int exclusive;
    raw_spinlock_t hrtimer_lock;
    struct hrtimer hrtimer;
    ktime_t hrtimer_interval;
    unsigned int hrtimer_active;
    struct perf_cgroup * cgrp;
    struct list_head cgrp_cpuctx_entry;
    struct list_head sched_cb_entry;
    int sched_cb_usage;
    int online;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct perf_cpu_context {
    struct perf_event_context ctx;
    struct perf_event_context * task_ctx;
    int active_oncpu;
    int exclusive;
    raw_spinlock_t hrtimer_lock;
    struct hrtimer hrtimer;
    ktime_t hrtimer_interval;
    unsigned int hrtimer_active;
    struct perf_cgroup * cgrp;
    struct list_head cgrp_cpuctx_entry;
    struct list_head sched_cb_entry;
    int sched_cb_usage;
    int online;
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
<code>struct list_head sched_cb_entry</code>
</li>
<li>
<b>Field added. </b>
<code>int sched_cb_usage</code>
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
<code>struct list_head cgrp_cpuctx_entry</code>
</li>
<li>
<b>Field added. </b>
<code>int online</code>
</li>
<li>
<b>Field removed. </b>
<code>struct pmu * unique_pmu</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int heap_size</code>
</li>
<li>
<b>Field added. </b>
<code>struct perf_event * * heap</code>
</li>
<li>
<b>Field added. </b>
<code>struct perf_event *[2] heap_default</code>
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
<b>Field removed. </b>
<code>int active_oncpu</code>
</li>
<li>
<b>Field removed. </b>
<code>int exclusive</code>
</li>
<li>
<b>Field removed. </b>
<code>raw_spinlock_t hrtimer_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>struct hrtimer hrtimer</code>
</li>
<li>
<b>Field removed. </b>
<code>ktime_t hrtimer_interval</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int hrtimer_active</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head cgrp_cpuctx_entry</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head sched_cb_entry</code>
</li>
<li>
<b>Field removed. </b>
<code>int sched_cb_usage</code>
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
