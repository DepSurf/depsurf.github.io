# Struct: <code>rt_rq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct rt_rq {
    struct rt_prio_array active;
    unsigned int rt_nr_running;
    struct (anon) highest_prio;
    long unsigned int rt_nr_migratory;
    long unsigned int rt_nr_total;
    int overloaded;
    struct plist_head pushable_tasks;
    int push_flags;
    int push_cpu;
    struct irq_work push_work;
    raw_spinlock_t push_lock;
    int rt_queued;
    int rt_throttled;
    u64 rt_time;
    u64 rt_runtime;
    raw_spinlock_t rt_runtime_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct rt_rq {
    struct rt_prio_array active;
    unsigned int rt_nr_running;
    unsigned int rr_nr_running;
    struct (anon) highest_prio;
    long unsigned int rt_nr_migratory;
    long unsigned int rt_nr_total;
    int overloaded;
    struct plist_head pushable_tasks;
    int push_flags;
    int push_cpu;
    struct irq_work push_work;
    raw_spinlock_t push_lock;
    int rt_queued;
    int rt_throttled;
    u64 rt_time;
    u64 rt_runtime;
    raw_spinlock_t rt_runtime_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct rt_rq {
    struct rt_prio_array active;
    unsigned int rt_nr_running;
    unsigned int rr_nr_running;
    struct (anon) highest_prio;
    long unsigned int rt_nr_migratory;
    long unsigned int rt_nr_total;
    int overloaded;
    struct plist_head pushable_tasks;
    int push_flags;
    int push_cpu;
    struct irq_work push_work;
    raw_spinlock_t push_lock;
    int rt_queued;
    int rt_throttled;
    u64 rt_time;
    u64 rt_runtime;
    raw_spinlock_t rt_runtime_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct rt_rq {
    struct rt_prio_array active;
    unsigned int rt_nr_running;
    unsigned int rr_nr_running;
    struct (anon) highest_prio;
    long unsigned int rt_nr_migratory;
    long unsigned int rt_nr_total;
    int overloaded;
    struct plist_head pushable_tasks;
    int push_flags;
    int push_cpu;
    struct irq_work push_work;
    raw_spinlock_t push_lock;
    int rt_queued;
    int rt_throttled;
    u64 rt_time;
    u64 rt_runtime;
    raw_spinlock_t rt_runtime_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct rt_rq {
    struct rt_prio_array active;
    unsigned int rt_nr_running;
    unsigned int rr_nr_running;
    struct (anon) highest_prio;
    long unsigned int rt_nr_migratory;
    long unsigned int rt_nr_total;
    int overloaded;
    struct plist_head pushable_tasks;
    int rt_queued;
    int rt_throttled;
    u64 rt_time;
    u64 rt_runtime;
    raw_spinlock_t rt_runtime_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct rt_rq {
    struct rt_prio_array active;
    unsigned int rt_nr_running;
    unsigned int rr_nr_running;
    struct (anon) highest_prio;
    long unsigned int rt_nr_migratory;
    long unsigned int rt_nr_total;
    int overloaded;
    struct plist_head pushable_tasks;
    int rt_queued;
    int rt_throttled;
    u64 rt_time;
    u64 rt_runtime;
    raw_spinlock_t rt_runtime_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct rt_rq {
    struct rt_prio_array active;
    unsigned int rt_nr_running;
    unsigned int rr_nr_running;
    struct (anon) highest_prio;
    long unsigned int rt_nr_migratory;
    long unsigned int rt_nr_total;
    int overloaded;
    struct plist_head pushable_tasks;
    int rt_queued;
    int rt_throttled;
    u64 rt_time;
    u64 rt_runtime;
    raw_spinlock_t rt_runtime_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct rt_rq {
    struct rt_prio_array active;
    unsigned int rt_nr_running;
    unsigned int rr_nr_running;
    struct (anon) highest_prio;
    long unsigned int rt_nr_migratory;
    long unsigned int rt_nr_total;
    int overloaded;
    struct plist_head pushable_tasks;
    int rt_queued;
    int rt_throttled;
    u64 rt_time;
    u64 rt_runtime;
    raw_spinlock_t rt_runtime_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct rt_rq {
    struct rt_prio_array active;
    unsigned int rt_nr_running;
    unsigned int rr_nr_running;
    struct (anon) highest_prio;
    long unsigned int rt_nr_migratory;
    long unsigned int rt_nr_total;
    int overloaded;
    struct plist_head pushable_tasks;
    int rt_queued;
    int rt_throttled;
    u64 rt_time;
    u64 rt_runtime;
    raw_spinlock_t rt_runtime_lock;
    long unsigned int rt_nr_boosted;
    struct rq * rq;
    struct task_group * tg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct rt_rq {
    struct rt_prio_array active;
    unsigned int rt_nr_running;
    unsigned int rr_nr_running;
    struct (anon) highest_prio;
    long unsigned int rt_nr_migratory;
    long unsigned int rt_nr_total;
    int overloaded;
    struct plist_head pushable_tasks;
    int rt_queued;
    int rt_throttled;
    u64 rt_time;
    u64 rt_runtime;
    raw_spinlock_t rt_runtime_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct rt_rq {
    struct rt_prio_array active;
    unsigned int rt_nr_running;
    unsigned int rr_nr_running;
    struct (anon) highest_prio;
    long unsigned int rt_nr_migratory;
    long unsigned int rt_nr_total;
    int overloaded;
    struct plist_head pushable_tasks;
    int rt_queued;
    int rt_throttled;
    u64 rt_time;
    u64 rt_runtime;
    raw_spinlock_t rt_runtime_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct rt_rq {
    struct rt_prio_array active;
    unsigned int rt_nr_running;
    unsigned int rr_nr_running;
    struct (anon) highest_prio;
    long unsigned int rt_nr_migratory;
    long unsigned int rt_nr_total;
    int overloaded;
    struct plist_head pushable_tasks;
    int rt_queued;
    int rt_throttled;
    u64 rt_time;
    u64 rt_runtime;
    raw_spinlock_t rt_runtime_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct rt_rq {
    struct rt_prio_array active;
    unsigned int rt_nr_running;
    unsigned int rr_nr_running;
    struct (anon) highest_prio;
    unsigned int rt_nr_migratory;
    unsigned int rt_nr_total;
    int overloaded;
    struct plist_head pushable_tasks;
    int rt_queued;
    int rt_throttled;
    u64 rt_time;
    u64 rt_runtime;
    raw_spinlock_t rt_runtime_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct rt_rq {
    struct rt_prio_array active;
    unsigned int rt_nr_running;
    unsigned int rr_nr_running;
    struct (anon) highest_prio;
    unsigned int rt_nr_migratory;
    unsigned int rt_nr_total;
    int overloaded;
    struct plist_head pushable_tasks;
    int rt_queued;
    int rt_throttled;
    u64 rt_time;
    u64 rt_runtime;
    raw_spinlock_t rt_runtime_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct rt_rq {
    struct rt_prio_array active;
    unsigned int rt_nr_running;
    unsigned int rr_nr_running;
    struct (anon) highest_prio;
    unsigned int rt_nr_migratory;
    unsigned int rt_nr_total;
    int overloaded;
    struct plist_head pushable_tasks;
    int rt_queued;
    int rt_throttled;
    u64 rt_time;
    u64 rt_runtime;
    raw_spinlock_t rt_runtime_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct rt_rq {
    struct rt_prio_array active;
    unsigned int rt_nr_running;
    unsigned int rr_nr_running;
    struct (anon) highest_prio;
    unsigned int rt_nr_migratory;
    unsigned int rt_nr_total;
    int overloaded;
    struct plist_head pushable_tasks;
    int rt_queued;
    int rt_throttled;
    u64 rt_time;
    u64 rt_runtime;
    raw_spinlock_t rt_runtime_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct rt_rq {
    struct rt_prio_array active;
    unsigned int rt_nr_running;
    unsigned int rr_nr_running;
    struct (anon) highest_prio;
    int overloaded;
    struct plist_head pushable_tasks;
    int rt_queued;
    int rt_throttled;
    u64 rt_time;
    u64 rt_runtime;
    raw_spinlock_t rt_runtime_lock;
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
struct rt_rq {
    struct rt_prio_array active;
    unsigned int rt_nr_running;
    unsigned int rr_nr_running;
    struct (anon) highest_prio;
    long unsigned int rt_nr_migratory;
    long unsigned int rt_nr_total;
    int overloaded;
    struct plist_head pushable_tasks;
    int rt_queued;
    int rt_throttled;
    u64 rt_time;
    u64 rt_runtime;
    raw_spinlock_t rt_runtime_lock;
    long unsigned int rt_nr_boosted;
    struct rq * rq;
    struct task_group * tg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct rt_rq {
    struct rt_prio_array active;
    unsigned int rt_nr_running;
    unsigned int rr_nr_running;
    struct (anon) highest_prio;
    long unsigned int rt_nr_migratory;
    long unsigned int rt_nr_total;
    int overloaded;
    struct plist_head pushable_tasks;
    int rt_queued;
    int rt_throttled;
    u64 rt_time;
    u64 rt_runtime;
    raw_spinlock_t rt_runtime_lock;
    long unsigned int rt_nr_boosted;
    struct rq * rq;
    struct task_group * tg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct rt_rq {
    struct rt_prio_array active;
    unsigned int rt_nr_running;
    unsigned int rr_nr_running;
    struct (anon) highest_prio;
    long unsigned int rt_nr_migratory;
    long unsigned int rt_nr_total;
    int overloaded;
    struct plist_head pushable_tasks;
    int rt_queued;
    int rt_throttled;
    u64 rt_time;
    u64 rt_runtime;
    raw_spinlock_t rt_runtime_lock;
    long unsigned int rt_nr_boosted;
    struct rq * rq;
    struct task_group * tg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct rt_rq {
    struct rt_prio_array active;
    unsigned int rt_nr_running;
    unsigned int rr_nr_running;
    struct (anon) highest_prio;
    long unsigned int rt_nr_migratory;
    long unsigned int rt_nr_total;
    int overloaded;
    struct plist_head pushable_tasks;
    int rt_queued;
    int rt_throttled;
    u64 rt_time;
    u64 rt_runtime;
    raw_spinlock_t rt_runtime_lock;
    long unsigned int rt_nr_boosted;
    struct rq * rq;
    struct task_group * tg;
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
struct rt_rq {
    struct rt_prio_array active;
    unsigned int rt_nr_running;
    unsigned int rr_nr_running;
    struct (anon) highest_prio;
    long unsigned int rt_nr_migratory;
    long unsigned int rt_nr_total;
    int overloaded;
    struct plist_head pushable_tasks;
    int rt_queued;
    int rt_throttled;
    u64 rt_time;
    u64 rt_runtime;
    raw_spinlock_t rt_runtime_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct rt_rq {
    struct rt_prio_array active;
    unsigned int rt_nr_running;
    unsigned int rr_nr_running;
    struct (anon) highest_prio;
    long unsigned int rt_nr_migratory;
    long unsigned int rt_nr_total;
    int overloaded;
    struct plist_head pushable_tasks;
    int rt_queued;
    int rt_throttled;
    u64 rt_time;
    u64 rt_runtime;
    raw_spinlock_t rt_runtime_lock;
    long unsigned int rt_nr_boosted;
    struct rq * rq;
    struct task_group * tg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct rt_rq {
    struct rt_prio_array active;
    unsigned int rt_nr_running;
    unsigned int rr_nr_running;
    struct (anon) highest_prio;
    long unsigned int rt_nr_migratory;
    long unsigned int rt_nr_total;
    int overloaded;
    struct plist_head pushable_tasks;
    int rt_queued;
    int rt_throttled;
    u64 rt_time;
    u64 rt_runtime;
    raw_spinlock_t rt_runtime_lock;
    long unsigned int rt_nr_boosted;
    struct rq * rq;
    struct task_group * tg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct rt_rq {
    struct rt_prio_array active;
    unsigned int rt_nr_running;
    unsigned int rr_nr_running;
    struct (anon) highest_prio;
    long unsigned int rt_nr_migratory;
    long unsigned int rt_nr_total;
    int overloaded;
    struct plist_head pushable_tasks;
    int rt_queued;
    int rt_throttled;
    u64 rt_time;
    u64 rt_runtime;
    raw_spinlock_t rt_runtime_lock;
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
<code>unsigned int rr_nr_running</code>
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int push_flags</code>
</li>
<li>
<b>Field removed. </b>
<code>int push_cpu</code>
</li>
<li>
<b>Field removed. </b>
<code>struct irq_work push_work</code>
</li>
<li>
<b>Field removed. </b>
<code>raw_spinlock_t push_lock</code>
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int rt_nr_boosted</code>
</li>
<li>
<b>Field added. </b>
<code>struct rq * rq</code>
</li>
<li>
<b>Field added. </b>
<code>struct task_group * tg</code>
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
<code>long unsigned int rt_nr_boosted</code>
</li>
<li>
<b>Field removed. </b>
<code>struct rq * rq</code>
</li>
<li>
<b>Field removed. </b>
<code>struct task_group * tg</code>
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
<b>Field type changed. </b>
<code>long unsigned int rt_nr_migratory</code> ➡️ <code>unsigned int rt_nr_migratory</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int rt_nr_total</code> ➡️ <code>unsigned int rt_nr_total</code>
</li>
</ul>
</details>
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
<code>unsigned int rt_nr_migratory</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int rt_nr_total</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>long unsigned int rt_nr_boosted</code>
</li>
<li>
<b>Field removed. </b>
<code>struct rq * rq</code>
</li>
<li>
<b>Field removed. </b>
<code>struct task_group * tg</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>long unsigned int rt_nr_boosted</code>
</li>
<li>
<b>Field removed. </b>
<code>struct rq * rq</code>
</li>
<li>
<b>Field removed. </b>
<code>struct task_group * tg</code>
</li>
</ul>
</details>
</li>
</ul>
