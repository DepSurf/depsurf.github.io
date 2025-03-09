# Struct: <code>hrtimer_cpu_base</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct hrtimer_cpu_base {
    raw_spinlock_t lock;
    seqcount_t seq;
    struct hrtimer * running;
    unsigned int cpu;
    unsigned int active_bases;
    unsigned int clock_was_set_seq;
    bool migration_enabled;
    bool nohz_active;
    unsigned int in_hrtirq;
    unsigned int hres_active;
    unsigned int hang_detected;
    ktime_t expires_next;
    struct hrtimer * next_timer;
    unsigned int nr_events;
    unsigned int nr_retries;
    unsigned int nr_hangs;
    unsigned int max_hang_time;
    struct hrtimer_clock_base[4] clock_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct hrtimer_cpu_base {
    raw_spinlock_t lock;
    seqcount_t seq;
    struct hrtimer * running;
    unsigned int cpu;
    unsigned int active_bases;
    unsigned int clock_was_set_seq;
    bool migration_enabled;
    bool nohz_active;
    unsigned int in_hrtirq;
    unsigned int hres_active;
    unsigned int hang_detected;
    ktime_t expires_next;
    struct hrtimer * next_timer;
    unsigned int nr_events;
    unsigned int nr_retries;
    unsigned int nr_hangs;
    unsigned int max_hang_time;
    struct hrtimer_clock_base[4] clock_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct hrtimer_cpu_base {
    raw_spinlock_t lock;
    seqcount_t seq;
    struct hrtimer * running;
    unsigned int cpu;
    unsigned int active_bases;
    unsigned int clock_was_set_seq;
    bool migration_enabled;
    bool nohz_active;
    unsigned int in_hrtirq;
    unsigned int hres_active;
    unsigned int hang_detected;
    ktime_t expires_next;
    struct hrtimer * next_timer;
    unsigned int nr_events;
    unsigned int nr_retries;
    unsigned int nr_hangs;
    unsigned int max_hang_time;
    struct hrtimer_clock_base[4] clock_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct hrtimer_cpu_base {
    raw_spinlock_t lock;
    seqcount_t seq;
    struct hrtimer * running;
    unsigned int cpu;
    unsigned int active_bases;
    unsigned int clock_was_set_seq;
    bool migration_enabled;
    bool nohz_active;
    unsigned int in_hrtirq;
    unsigned int hres_active;
    unsigned int hang_detected;
    ktime_t expires_next;
    struct hrtimer * next_timer;
    unsigned int nr_events;
    unsigned int nr_retries;
    unsigned int nr_hangs;
    unsigned int max_hang_time;
    struct hrtimer_clock_base[4] clock_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct hrtimer_cpu_base {
    raw_spinlock_t lock;
    seqcount_t seq;
    struct hrtimer * running;
    unsigned int cpu;
    unsigned int active_bases;
    unsigned int clock_was_set_seq;
    bool migration_enabled;
    bool nohz_active;
    unsigned int in_hrtirq;
    unsigned int hres_active;
    unsigned int hang_detected;
    ktime_t expires_next;
    struct hrtimer * next_timer;
    unsigned int nr_events;
    unsigned int nr_retries;
    unsigned int nr_hangs;
    unsigned int max_hang_time;
    struct hrtimer_clock_base[4] clock_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct hrtimer_cpu_base {
    raw_spinlock_t lock;
    unsigned int cpu;
    unsigned int active_bases;
    unsigned int clock_was_set_seq;
    unsigned int hres_active;
    unsigned int in_hrtirq;
    unsigned int hang_detected;
    unsigned int softirq_activated;
    unsigned int nr_events;
    short unsigned int nr_retries;
    short unsigned int nr_hangs;
    unsigned int max_hang_time;
    ktime_t expires_next;
    struct hrtimer * next_timer;
    ktime_t softirq_expires_next;
    struct hrtimer * softirq_next_timer;
    struct hrtimer_clock_base[8] clock_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct hrtimer_cpu_base {
    raw_spinlock_t lock;
    unsigned int cpu;
    unsigned int active_bases;
    unsigned int clock_was_set_seq;
    unsigned int hres_active;
    unsigned int in_hrtirq;
    unsigned int hang_detected;
    unsigned int softirq_activated;
    unsigned int nr_events;
    short unsigned int nr_retries;
    short unsigned int nr_hangs;
    unsigned int max_hang_time;
    ktime_t expires_next;
    struct hrtimer * next_timer;
    ktime_t softirq_expires_next;
    struct hrtimer * softirq_next_timer;
    struct hrtimer_clock_base[8] clock_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct hrtimer_cpu_base {
    raw_spinlock_t lock;
    unsigned int cpu;
    unsigned int active_bases;
    unsigned int clock_was_set_seq;
    unsigned int hres_active;
    unsigned int in_hrtirq;
    unsigned int hang_detected;
    unsigned int softirq_activated;
    unsigned int nr_events;
    short unsigned int nr_retries;
    short unsigned int nr_hangs;
    unsigned int max_hang_time;
    ktime_t expires_next;
    struct hrtimer * next_timer;
    ktime_t softirq_expires_next;
    struct hrtimer * softirq_next_timer;
    struct hrtimer_clock_base[8] clock_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct hrtimer_cpu_base {
    raw_spinlock_t lock;
    unsigned int cpu;
    unsigned int active_bases;
    unsigned int clock_was_set_seq;
    unsigned int hres_active;
    unsigned int in_hrtirq;
    unsigned int hang_detected;
    unsigned int softirq_activated;
    unsigned int nr_events;
    short unsigned int nr_retries;
    short unsigned int nr_hangs;
    unsigned int max_hang_time;
    ktime_t expires_next;
    struct hrtimer * next_timer;
    ktime_t softirq_expires_next;
    struct hrtimer * softirq_next_timer;
    struct hrtimer_clock_base[8] clock_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct hrtimer_cpu_base {
    raw_spinlock_t lock;
    unsigned int cpu;
    unsigned int active_bases;
    unsigned int clock_was_set_seq;
    unsigned int hres_active;
    unsigned int in_hrtirq;
    unsigned int hang_detected;
    unsigned int softirq_activated;
    unsigned int nr_events;
    short unsigned int nr_retries;
    short unsigned int nr_hangs;
    unsigned int max_hang_time;
    ktime_t expires_next;
    struct hrtimer * next_timer;
    ktime_t softirq_expires_next;
    struct hrtimer * softirq_next_timer;
    struct hrtimer_clock_base[8] clock_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct hrtimer_cpu_base {
    raw_spinlock_t lock;
    unsigned int cpu;
    unsigned int active_bases;
    unsigned int clock_was_set_seq;
    unsigned int hres_active;
    unsigned int in_hrtirq;
    unsigned int hang_detected;
    unsigned int softirq_activated;
    unsigned int nr_events;
    short unsigned int nr_retries;
    short unsigned int nr_hangs;
    unsigned int max_hang_time;
    ktime_t expires_next;
    struct hrtimer * next_timer;
    ktime_t softirq_expires_next;
    struct hrtimer * softirq_next_timer;
    struct hrtimer_clock_base[8] clock_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct hrtimer_cpu_base {
    raw_spinlock_t lock;
    unsigned int cpu;
    unsigned int active_bases;
    unsigned int clock_was_set_seq;
    unsigned int hres_active;
    unsigned int in_hrtirq;
    unsigned int hang_detected;
    unsigned int softirq_activated;
    unsigned int nr_events;
    short unsigned int nr_retries;
    short unsigned int nr_hangs;
    unsigned int max_hang_time;
    ktime_t expires_next;
    struct hrtimer * next_timer;
    ktime_t softirq_expires_next;
    struct hrtimer * softirq_next_timer;
    struct hrtimer_clock_base[8] clock_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct hrtimer_cpu_base {
    raw_spinlock_t lock;
    unsigned int cpu;
    unsigned int active_bases;
    unsigned int clock_was_set_seq;
    unsigned int hres_active;
    unsigned int in_hrtirq;
    unsigned int hang_detected;
    unsigned int softirq_activated;
    unsigned int nr_events;
    short unsigned int nr_retries;
    short unsigned int nr_hangs;
    unsigned int max_hang_time;
    ktime_t expires_next;
    struct hrtimer * next_timer;
    ktime_t softirq_expires_next;
    struct hrtimer * softirq_next_timer;
    struct hrtimer_clock_base[8] clock_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct hrtimer_cpu_base {
    raw_spinlock_t lock;
    unsigned int cpu;
    unsigned int active_bases;
    unsigned int clock_was_set_seq;
    unsigned int hres_active;
    unsigned int in_hrtirq;
    unsigned int hang_detected;
    unsigned int softirq_activated;
    unsigned int nr_events;
    short unsigned int nr_retries;
    short unsigned int nr_hangs;
    unsigned int max_hang_time;
    ktime_t expires_next;
    struct hrtimer * next_timer;
    ktime_t softirq_expires_next;
    struct hrtimer * softirq_next_timer;
    struct hrtimer_clock_base[8] clock_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct hrtimer_cpu_base {
    raw_spinlock_t lock;
    unsigned int cpu;
    unsigned int active_bases;
    unsigned int clock_was_set_seq;
    unsigned int hres_active;
    unsigned int in_hrtirq;
    unsigned int hang_detected;
    unsigned int softirq_activated;
    unsigned int nr_events;
    short unsigned int nr_retries;
    short unsigned int nr_hangs;
    unsigned int max_hang_time;
    ktime_t expires_next;
    struct hrtimer * next_timer;
    ktime_t softirq_expires_next;
    struct hrtimer * softirq_next_timer;
    struct hrtimer_clock_base[8] clock_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct hrtimer_cpu_base {
    raw_spinlock_t lock;
    unsigned int cpu;
    unsigned int active_bases;
    unsigned int clock_was_set_seq;
    unsigned int hres_active;
    unsigned int in_hrtirq;
    unsigned int hang_detected;
    unsigned int softirq_activated;
    unsigned int nr_events;
    short unsigned int nr_retries;
    short unsigned int nr_hangs;
    unsigned int max_hang_time;
    ktime_t expires_next;
    struct hrtimer * next_timer;
    ktime_t softirq_expires_next;
    struct hrtimer * softirq_next_timer;
    struct hrtimer_clock_base[8] clock_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct hrtimer_cpu_base {
    raw_spinlock_t lock;
    unsigned int cpu;
    unsigned int active_bases;
    unsigned int clock_was_set_seq;
    unsigned int hres_active;
    unsigned int in_hrtirq;
    unsigned int hang_detected;
    unsigned int softirq_activated;
    unsigned int online;
    unsigned int nr_events;
    short unsigned int nr_retries;
    short unsigned int nr_hangs;
    unsigned int max_hang_time;
    ktime_t expires_next;
    struct hrtimer * next_timer;
    ktime_t softirq_expires_next;
    struct hrtimer * softirq_next_timer;
    struct hrtimer_clock_base[8] clock_base;
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
struct hrtimer_cpu_base {
    raw_spinlock_t lock;
    unsigned int cpu;
    unsigned int active_bases;
    unsigned int clock_was_set_seq;
    unsigned int hres_active;
    unsigned int in_hrtirq;
    unsigned int hang_detected;
    unsigned int softirq_activated;
    unsigned int nr_events;
    short unsigned int nr_retries;
    short unsigned int nr_hangs;
    unsigned int max_hang_time;
    ktime_t expires_next;
    struct hrtimer * next_timer;
    ktime_t softirq_expires_next;
    struct hrtimer * softirq_next_timer;
    struct hrtimer_clock_base[8] clock_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct hrtimer_cpu_base {
    raw_spinlock_t lock;
    unsigned int cpu;
    unsigned int active_bases;
    unsigned int clock_was_set_seq;
    unsigned int hres_active;
    unsigned int in_hrtirq;
    unsigned int hang_detected;
    unsigned int softirq_activated;
    unsigned int nr_events;
    short unsigned int nr_retries;
    short unsigned int nr_hangs;
    unsigned int max_hang_time;
    ktime_t expires_next;
    struct hrtimer * next_timer;
    ktime_t softirq_expires_next;
    struct hrtimer * softirq_next_timer;
    struct hrtimer_clock_base[8] clock_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct hrtimer_cpu_base {
    raw_spinlock_t lock;
    unsigned int cpu;
    unsigned int active_bases;
    unsigned int clock_was_set_seq;
    unsigned int hres_active;
    unsigned int in_hrtirq;
    unsigned int hang_detected;
    unsigned int softirq_activated;
    unsigned int nr_events;
    short unsigned int nr_retries;
    short unsigned int nr_hangs;
    unsigned int max_hang_time;
    ktime_t expires_next;
    struct hrtimer * next_timer;
    ktime_t softirq_expires_next;
    struct hrtimer * softirq_next_timer;
    struct hrtimer_clock_base[8] clock_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct hrtimer_cpu_base {
    raw_spinlock_t lock;
    unsigned int cpu;
    unsigned int active_bases;
    unsigned int clock_was_set_seq;
    unsigned int hres_active;
    unsigned int in_hrtirq;
    unsigned int hang_detected;
    unsigned int softirq_activated;
    unsigned int nr_events;
    short unsigned int nr_retries;
    short unsigned int nr_hangs;
    unsigned int max_hang_time;
    ktime_t expires_next;
    struct hrtimer * next_timer;
    ktime_t softirq_expires_next;
    struct hrtimer * softirq_next_timer;
    struct hrtimer_clock_base[8] clock_base;
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
struct hrtimer_cpu_base {
    raw_spinlock_t lock;
    unsigned int cpu;
    unsigned int active_bases;
    unsigned int clock_was_set_seq;
    unsigned int hres_active;
    unsigned int in_hrtirq;
    unsigned int hang_detected;
    unsigned int softirq_activated;
    unsigned int nr_events;
    short unsigned int nr_retries;
    short unsigned int nr_hangs;
    unsigned int max_hang_time;
    ktime_t expires_next;
    struct hrtimer * next_timer;
    ktime_t softirq_expires_next;
    struct hrtimer * softirq_next_timer;
    struct hrtimer_clock_base[8] clock_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct hrtimer_cpu_base {
    raw_spinlock_t lock;
    unsigned int cpu;
    unsigned int active_bases;
    unsigned int clock_was_set_seq;
    unsigned int hres_active;
    unsigned int in_hrtirq;
    unsigned int hang_detected;
    unsigned int softirq_activated;
    unsigned int nr_events;
    short unsigned int nr_retries;
    short unsigned int nr_hangs;
    unsigned int max_hang_time;
    ktime_t expires_next;
    struct hrtimer * next_timer;
    ktime_t softirq_expires_next;
    struct hrtimer * softirq_next_timer;
    struct hrtimer_clock_base[8] clock_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct hrtimer_cpu_base {
    raw_spinlock_t lock;
    unsigned int cpu;
    unsigned int active_bases;
    unsigned int clock_was_set_seq;
    unsigned int hres_active;
    unsigned int in_hrtirq;
    unsigned int hang_detected;
    unsigned int softirq_activated;
    unsigned int nr_events;
    short unsigned int nr_retries;
    short unsigned int nr_hangs;
    unsigned int max_hang_time;
    ktime_t expires_next;
    struct hrtimer * next_timer;
    ktime_t softirq_expires_next;
    struct hrtimer * softirq_next_timer;
    struct hrtimer_clock_base[8] clock_base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct hrtimer_cpu_base {
    raw_spinlock_t lock;
    unsigned int cpu;
    unsigned int active_bases;
    unsigned int clock_was_set_seq;
    unsigned int hres_active;
    unsigned int in_hrtirq;
    unsigned int hang_detected;
    unsigned int softirq_activated;
    unsigned int nr_events;
    short unsigned int nr_retries;
    short unsigned int nr_hangs;
    unsigned int max_hang_time;
    ktime_t expires_next;
    struct hrtimer * next_timer;
    ktime_t softirq_expires_next;
    struct hrtimer * softirq_next_timer;
    struct hrtimer_clock_base[8] clock_base;
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
<code>unsigned int softirq_activated</code>
</li>
<li>
<b>Field added. </b>
<code>ktime_t softirq_expires_next</code>
</li>
<li>
<b>Field added. </b>
<code>struct hrtimer * softirq_next_timer</code>
</li>
<li>
<b>Field removed. </b>
<code>seqcount_t seq</code>
</li>
<li>
<b>Field removed. </b>
<code>struct hrtimer * running</code>
</li>
<li>
<b>Field removed. </b>
<code>bool migration_enabled</code>
</li>
<li>
<b>Field removed. </b>
<code>bool nohz_active</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int nr_retries</code> ➡️ <code>short unsigned int nr_retries</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int nr_hangs</code> ➡️ <code>short unsigned int nr_hangs</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct hrtimer_clock_base[4] clock_base</code> ➡️ <code>struct hrtimer_clock_base[8] clock_base</code>
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
<b>Field added. </b>
<code>unsigned int online</code>
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
