# Struct: <code>rcu_tasks_percpu</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct rcu_tasks_percpu {
    struct rcu_segcblist cblist;
    raw_spinlock_t lock;
    long unsigned int rtp_jiffies;
    long unsigned int rtp_n_lock_retries;
    struct work_struct rtp_work;
    struct irq_work rtp_irq_work;
    struct callback_head barrier_q_head;
    int cpu;
    struct rcu_tasks * rtpp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct rcu_tasks_percpu {
    struct rcu_segcblist cblist;
    raw_spinlock_t lock;
    long unsigned int rtp_jiffies;
    long unsigned int rtp_n_lock_retries;
    struct work_struct rtp_work;
    struct irq_work rtp_irq_work;
    struct callback_head barrier_q_head;
    struct list_head rtp_blkd_tasks;
    int cpu;
    struct rcu_tasks * rtpp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct rcu_tasks_percpu {
    struct rcu_segcblist cblist;
    raw_spinlock_t lock;
    long unsigned int rtp_jiffies;
    long unsigned int rtp_n_lock_retries;
    struct work_struct rtp_work;
    struct irq_work rtp_irq_work;
    struct callback_head barrier_q_head;
    struct list_head rtp_blkd_tasks;
    int cpu;
    struct rcu_tasks * rtpp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct rcu_tasks_percpu {
    struct rcu_segcblist cblist;
    raw_spinlock_t lock;
    long unsigned int rtp_jiffies;
    long unsigned int rtp_n_lock_retries;
    struct timer_list lazy_timer;
    unsigned int urgent_gp;
    struct work_struct rtp_work;
    struct irq_work rtp_irq_work;
    struct callback_head barrier_q_head;
    struct list_head rtp_blkd_tasks;
    int cpu;
    struct rcu_tasks * rtpp;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
struct rcu_tasks_percpu {
    struct rcu_segcblist cblist;
    raw_spinlock_t lock;
    long unsigned int rtp_jiffies;
    long unsigned int rtp_n_lock_retries;
    struct work_struct rtp_work;
    struct irq_work rtp_irq_work;
    struct callback_head barrier_q_head;
    int cpu;
    struct rcu_tasks * rtpp;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct list_head rtp_blkd_tasks</code>
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
<b>Field added. </b>
<code>struct timer_list lazy_timer</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int urgent_gp</code>
</li>
</ul>
</details>
</li>
</ul>
