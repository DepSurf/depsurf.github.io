# Struct: <code>cfs_bandwidth</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct cfs_bandwidth {
    raw_spinlock_t lock;
    ktime_t period;
    u64 quota;
    u64 runtime;
    s64 hierarchical_quota;
    u64 runtime_expires;
    int idle;
    int period_active;
    struct hrtimer period_timer;
    struct hrtimer slack_timer;
    struct list_head throttled_cfs_rq;
    int nr_periods;
    int nr_throttled;
    u64 throttled_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct cfs_bandwidth {
    raw_spinlock_t lock;
    ktime_t period;
    u64 quota;
    u64 runtime;
    s64 hierarchical_quota;
    u64 runtime_expires;
    int idle;
    int period_active;
    struct hrtimer period_timer;
    struct hrtimer slack_timer;
    struct list_head throttled_cfs_rq;
    int nr_periods;
    int nr_throttled;
    u64 throttled_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct cfs_bandwidth {
    raw_spinlock_t lock;
    ktime_t period;
    u64 quota;
    u64 runtime;
    s64 hierarchical_quota;
    u64 runtime_expires;
    int idle;
    int period_active;
    struct hrtimer period_timer;
    struct hrtimer slack_timer;
    struct list_head throttled_cfs_rq;
    int nr_periods;
    int nr_throttled;
    u64 throttled_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct cfs_bandwidth {
    raw_spinlock_t lock;
    ktime_t period;
    u64 quota;
    u64 runtime;
    s64 hierarchical_quota;
    u64 runtime_expires;
    int idle;
    int period_active;
    struct hrtimer period_timer;
    struct hrtimer slack_timer;
    struct list_head throttled_cfs_rq;
    int nr_periods;
    int nr_throttled;
    u64 throttled_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct cfs_bandwidth {
    raw_spinlock_t lock;
    ktime_t period;
    u64 quota;
    u64 runtime;
    s64 hierarchical_quota;
    u64 runtime_expires;
    int idle;
    int period_active;
    struct hrtimer period_timer;
    struct hrtimer slack_timer;
    struct list_head throttled_cfs_rq;
    int nr_periods;
    int nr_throttled;
    u64 throttled_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct cfs_bandwidth {
    raw_spinlock_t lock;
    ktime_t period;
    u64 quota;
    u64 runtime;
    s64 hierarchical_quota;
    u64 runtime_expires;
    int expires_seq;
    short int idle;
    short int period_active;
    struct hrtimer period_timer;
    struct hrtimer slack_timer;
    struct list_head throttled_cfs_rq;
    int nr_periods;
    int nr_throttled;
    u64 throttled_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct cfs_bandwidth {
    raw_spinlock_t lock;
    ktime_t period;
    u64 quota;
    u64 runtime;
    s64 hierarchical_quota;
    u64 runtime_expires;
    int expires_seq;
    short int idle;
    short int period_active;
    struct hrtimer period_timer;
    struct hrtimer slack_timer;
    struct list_head throttled_cfs_rq;
    int nr_periods;
    int nr_throttled;
    u64 throttled_time;
    bool distribute_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct cfs_bandwidth {
    raw_spinlock_t lock;
    ktime_t period;
    u64 quota;
    u64 runtime;
    s64 hierarchical_quota;
    u64 runtime_expires;
    int expires_seq;
    u8 idle;
    u8 period_active;
    u8 distribute_running;
    u8 slack_started;
    struct hrtimer period_timer;
    struct hrtimer slack_timer;
    struct list_head throttled_cfs_rq;
    int nr_periods;
    int nr_throttled;
    u64 throttled_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct cfs_bandwidth {
    raw_spinlock_t lock;
    ktime_t period;
    u64 quota;
    u64 runtime;
    s64 hierarchical_quota;
    u8 idle;
    u8 period_active;
    u8 distribute_running;
    u8 slack_started;
    struct hrtimer period_timer;
    struct hrtimer slack_timer;
    struct list_head throttled_cfs_rq;
    int nr_periods;
    int nr_throttled;
    u64 throttled_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct cfs_bandwidth {
    raw_spinlock_t lock;
    ktime_t period;
    u64 quota;
    u64 runtime;
    s64 hierarchical_quota;
    u8 idle;
    u8 period_active;
    u8 slack_started;
    struct hrtimer period_timer;
    struct hrtimer slack_timer;
    struct list_head throttled_cfs_rq;
    int nr_periods;
    int nr_throttled;
    u64 throttled_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct cfs_bandwidth {
    raw_spinlock_t lock;
    ktime_t period;
    u64 quota;
    u64 runtime;
    s64 hierarchical_quota;
    u8 idle;
    u8 period_active;
    u8 slack_started;
    struct hrtimer period_timer;
    struct hrtimer slack_timer;
    struct list_head throttled_cfs_rq;
    int nr_periods;
    int nr_throttled;
    u64 throttled_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct cfs_bandwidth {
    raw_spinlock_t lock;
    ktime_t period;
    u64 quota;
    u64 runtime;
    s64 hierarchical_quota;
    u8 idle;
    u8 period_active;
    u8 slack_started;
    struct hrtimer period_timer;
    struct hrtimer slack_timer;
    struct list_head throttled_cfs_rq;
    int nr_periods;
    int nr_throttled;
    u64 throttled_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct cfs_bandwidth {
    raw_spinlock_t lock;
    ktime_t period;
    u64 quota;
    u64 runtime;
    u64 burst;
    s64 hierarchical_quota;
    u8 idle;
    u8 period_active;
    u8 slack_started;
    struct hrtimer period_timer;
    struct hrtimer slack_timer;
    struct list_head throttled_cfs_rq;
    int nr_periods;
    int nr_throttled;
    u64 throttled_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct cfs_bandwidth {
    raw_spinlock_t lock;
    ktime_t period;
    u64 quota;
    u64 runtime;
    u64 burst;
    u64 runtime_snap;
    s64 hierarchical_quota;
    u8 idle;
    u8 period_active;
    u8 slack_started;
    struct hrtimer period_timer;
    struct hrtimer slack_timer;
    struct list_head throttled_cfs_rq;
    int nr_periods;
    int nr_throttled;
    int nr_burst;
    u64 throttled_time;
    u64 burst_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct cfs_bandwidth {
    raw_spinlock_t lock;
    ktime_t period;
    u64 quota;
    u64 runtime;
    u64 burst;
    u64 runtime_snap;
    s64 hierarchical_quota;
    u8 idle;
    u8 period_active;
    u8 slack_started;
    struct hrtimer period_timer;
    struct hrtimer slack_timer;
    struct list_head throttled_cfs_rq;
    int nr_periods;
    int nr_throttled;
    int nr_burst;
    u64 throttled_time;
    u64 burst_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct cfs_bandwidth {
    raw_spinlock_t lock;
    ktime_t period;
    u64 quota;
    u64 runtime;
    u64 burst;
    u64 runtime_snap;
    s64 hierarchical_quota;
    u8 idle;
    u8 period_active;
    u8 slack_started;
    struct hrtimer period_timer;
    struct hrtimer slack_timer;
    struct list_head throttled_cfs_rq;
    int nr_periods;
    int nr_throttled;
    int nr_burst;
    u64 throttled_time;
    u64 burst_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct cfs_bandwidth {
    raw_spinlock_t lock;
    ktime_t period;
    u64 quota;
    u64 runtime;
    u64 burst;
    u64 runtime_snap;
    s64 hierarchical_quota;
    u8 idle;
    u8 period_active;
    u8 slack_started;
    struct hrtimer period_timer;
    struct hrtimer slack_timer;
    struct list_head throttled_cfs_rq;
    int nr_periods;
    int nr_throttled;
    int nr_burst;
    u64 throttled_time;
    u64 burst_time;
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
struct cfs_bandwidth {
    raw_spinlock_t lock;
    ktime_t period;
    u64 quota;
    u64 runtime;
    s64 hierarchical_quota;
    u8 idle;
    u8 period_active;
    u8 distribute_running;
    u8 slack_started;
    struct hrtimer period_timer;
    struct hrtimer slack_timer;
    struct list_head throttled_cfs_rq;
    int nr_periods;
    int nr_throttled;
    u64 throttled_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct cfs_bandwidth {
    raw_spinlock_t lock;
    ktime_t period;
    u64 quota;
    u64 runtime;
    s64 hierarchical_quota;
    u8 idle;
    u8 period_active;
    u8 distribute_running;
    u8 slack_started;
    struct hrtimer period_timer;
    struct hrtimer slack_timer;
    struct list_head throttled_cfs_rq;
    int nr_periods;
    int nr_throttled;
    u64 throttled_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct cfs_bandwidth {
    raw_spinlock_t lock;
    ktime_t period;
    u64 quota;
    u64 runtime;
    s64 hierarchical_quota;
    u8 idle;
    u8 period_active;
    u8 distribute_running;
    u8 slack_started;
    struct hrtimer period_timer;
    struct hrtimer slack_timer;
    struct list_head throttled_cfs_rq;
    int nr_periods;
    int nr_throttled;
    u64 throttled_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct cfs_bandwidth {
    raw_spinlock_t lock;
    ktime_t period;
    u64 quota;
    u64 runtime;
    s64 hierarchical_quota;
    u8 idle;
    u8 period_active;
    u8 distribute_running;
    u8 slack_started;
    struct hrtimer period_timer;
    struct hrtimer slack_timer;
    struct list_head throttled_cfs_rq;
    int nr_periods;
    int nr_throttled;
    u64 throttled_time;
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
struct cfs_bandwidth {
    raw_spinlock_t lock;
    ktime_t period;
    u64 quota;
    u64 runtime;
    s64 hierarchical_quota;
    u8 idle;
    u8 period_active;
    u8 distribute_running;
    u8 slack_started;
    struct hrtimer period_timer;
    struct hrtimer slack_timer;
    struct list_head throttled_cfs_rq;
    int nr_periods;
    int nr_throttled;
    u64 throttled_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct cfs_bandwidth {
    raw_spinlock_t lock;
    ktime_t period;
    u64 quota;
    u64 runtime;
    s64 hierarchical_quota;
    u8 idle;
    u8 period_active;
    u8 distribute_running;
    u8 slack_started;
    struct hrtimer period_timer;
    struct hrtimer slack_timer;
    struct list_head throttled_cfs_rq;
    int nr_periods;
    int nr_throttled;
    u64 throttled_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct cfs_bandwidth {
    raw_spinlock_t lock;
    ktime_t period;
    u64 quota;
    u64 runtime;
    s64 hierarchical_quota;
    u8 idle;
    u8 period_active;
    u8 distribute_running;
    u8 slack_started;
    struct hrtimer period_timer;
    struct hrtimer slack_timer;
    struct list_head throttled_cfs_rq;
    int nr_periods;
    int nr_throttled;
    u64 throttled_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct cfs_bandwidth {
    raw_spinlock_t lock;
    ktime_t period;
    u64 quota;
    u64 runtime;
    s64 hierarchical_quota;
    u8 idle;
    u8 period_active;
    u8 distribute_running;
    u8 slack_started;
    struct hrtimer period_timer;
    struct hrtimer slack_timer;
    struct list_head throttled_cfs_rq;
    int nr_periods;
    int nr_throttled;
    u64 throttled_time;
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
<code>int expires_seq</code>
</li>
<li>
<b>Field type changed. </b>
<code>int idle</code> ➡️ <code>short int idle</code>
</li>
<li>
<b>Field type changed. </b>
<code>int period_active</code> ➡️ <code>short int period_active</code>
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
<code>bool distribute_running</code>
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
<code>u8 slack_started</code>
</li>
<li>
<b>Field type changed. </b>
<code>short int idle</code> ➡️ <code>u8 idle</code>
</li>
<li>
<b>Field type changed. </b>
<code>short int period_active</code> ➡️ <code>u8 period_active</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool distribute_running</code> ➡️ <code>u8 distribute_running</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>u64 runtime_expires</code>
</li>
<li>
<b>Field removed. </b>
<code>int expires_seq</code>
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
<code>u8 distribute_running</code>
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
<code>u64 burst</code>
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
<code>u64 runtime_snap</code>
</li>
<li>
<b>Field added. </b>
<code>int nr_burst</code>
</li>
<li>
<b>Field added. </b>
<code>u64 burst_time</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
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
