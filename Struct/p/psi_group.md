# Struct: <code>psi_group</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct psi_group {
    struct mutex stat_lock;
    struct psi_group_cpu * pcpu;
    u64[5] total_prev;
    u64 last_update;
    u64 next_update;
    struct delayed_work clock_work;
    u64[5] total;
    long unsigned int[15] avg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct psi_group {
    struct mutex avgs_lock;
    struct psi_group_cpu * pcpu;
    u64[5] avg_total;
    u64 avg_last_update;
    u64 avg_next_update;
    struct delayed_work avgs_work;
    u64[10] total;
    long unsigned int[15] avg;
    atomic_t poll_scheduled;
    struct kthread_worker * poll_kworker;
    struct kthread_delayed_work poll_work;
    struct mutex trigger_lock;
    struct list_head triggers;
    u32[5] nr_triggers;
    u32 poll_states;
    u64 poll_min_period;
    u64[5] polling_total;
    u64 polling_next_update;
    u64 polling_until;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct psi_group {
    struct mutex avgs_lock;
    struct psi_group_cpu * pcpu;
    u64[5] avg_total;
    u64 avg_last_update;
    u64 avg_next_update;
    struct delayed_work avgs_work;
    u64[10] total;
    long unsigned int[15] avg;
    atomic_t poll_scheduled;
    struct kthread_worker * poll_kworker;
    struct kthread_delayed_work poll_work;
    struct mutex trigger_lock;
    struct list_head triggers;
    u32[5] nr_triggers;
    u32 poll_states;
    u64 poll_min_period;
    u64[5] polling_total;
    u64 polling_next_update;
    u64 polling_until;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct psi_group {
    struct mutex avgs_lock;
    struct psi_group_cpu * pcpu;
    u64[5] avg_total;
    u64 avg_last_update;
    u64 avg_next_update;
    struct delayed_work avgs_work;
    u64[10] total;
    long unsigned int[15] avg;
    atomic_t poll_scheduled;
    struct kthread_worker * poll_kworker;
    struct kthread_delayed_work poll_work;
    struct mutex trigger_lock;
    struct list_head triggers;
    u32[5] nr_triggers;
    u32 poll_states;
    u64 poll_min_period;
    u64[5] polling_total;
    u64 polling_next_update;
    u64 polling_until;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct psi_group {
    struct mutex avgs_lock;
    struct psi_group_cpu * pcpu;
    u64[5] avg_total;
    u64 avg_last_update;
    u64 avg_next_update;
    struct delayed_work avgs_work;
    u64[10] total;
    long unsigned int[15] avg;
    struct task_struct * poll_task;
    struct timer_list poll_timer;
    wait_queue_head_t poll_wait;
    atomic_t poll_wakeup;
    struct mutex trigger_lock;
    struct list_head triggers;
    u32[5] nr_triggers;
    u32 poll_states;
    u64 poll_min_period;
    u64[5] polling_total;
    u64 polling_next_update;
    u64 polling_until;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct psi_group {
    struct mutex avgs_lock;
    struct psi_group_cpu * pcpu;
    u64[6] avg_total;
    u64 avg_last_update;
    u64 avg_next_update;
    struct delayed_work avgs_work;
    u64[12] total;
    long unsigned int[18] avg;
    struct task_struct * poll_task;
    struct timer_list poll_timer;
    wait_queue_head_t poll_wait;
    atomic_t poll_wakeup;
    struct mutex trigger_lock;
    struct list_head triggers;
    u32[6] nr_triggers;
    u32 poll_states;
    u64 poll_min_period;
    u64[6] polling_total;
    u64 polling_next_update;
    u64 polling_until;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct psi_group {
    struct mutex avgs_lock;
    struct psi_group_cpu * pcpu;
    u64[6] avg_total;
    u64 avg_last_update;
    u64 avg_next_update;
    struct delayed_work avgs_work;
    u64[12] total;
    long unsigned int[18] avg;
    struct task_struct * poll_task;
    struct timer_list poll_timer;
    wait_queue_head_t poll_wait;
    atomic_t poll_wakeup;
    struct mutex trigger_lock;
    struct list_head triggers;
    u32[6] nr_triggers;
    u32 poll_states;
    u64 poll_min_period;
    u64[6] polling_total;
    u64 polling_next_update;
    u64 polling_until;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct psi_group {
    struct mutex avgs_lock;
    struct psi_group_cpu * pcpu;
    u64[6] avg_total;
    u64 avg_last_update;
    u64 avg_next_update;
    struct delayed_work avgs_work;
    u64[12] total;
    long unsigned int[18] avg;
    struct task_struct * poll_task;
    struct timer_list poll_timer;
    wait_queue_head_t poll_wait;
    atomic_t poll_wakeup;
    struct mutex trigger_lock;
    struct list_head triggers;
    u32[6] nr_triggers;
    u32 poll_states;
    u64 poll_min_period;
    u64[6] polling_total;
    u64 polling_next_update;
    u64 polling_until;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct psi_group {
    struct psi_group * parent;
    bool enabled;
    struct mutex avgs_lock;
    struct psi_group_cpu * pcpu;
    u64[6] avg_total;
    u64 avg_last_update;
    u64 avg_next_update;
    struct delayed_work avgs_work;
    u64[12] total;
    long unsigned int[18] avg;
    struct task_struct * poll_task;
    struct timer_list poll_timer;
    wait_queue_head_t poll_wait;
    atomic_t poll_wakeup;
    atomic_t poll_scheduled;
    struct mutex trigger_lock;
    struct list_head triggers;
    u32[6] nr_triggers;
    u32 poll_states;
    u64 poll_min_period;
    u64[6] polling_total;
    u64 polling_next_update;
    u64 polling_until;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct psi_group {
    struct psi_group * parent;
    bool enabled;
    struct mutex avgs_lock;
    struct psi_group_cpu * pcpu;
    u64[6] avg_total;
    u64 avg_last_update;
    u64 avg_next_update;
    struct delayed_work avgs_work;
    struct list_head avg_triggers;
    u32[6] avg_nr_triggers;
    u64[12] total;
    long unsigned int[18] avg;
    struct task_struct * rtpoll_task;
    struct timer_list rtpoll_timer;
    wait_queue_head_t rtpoll_wait;
    atomic_t rtpoll_wakeup;
    atomic_t rtpoll_scheduled;
    struct mutex rtpoll_trigger_lock;
    struct list_head rtpoll_triggers;
    u32[6] rtpoll_nr_triggers;
    u32 rtpoll_states;
    u64 rtpoll_min_period;
    u64[6] rtpoll_total;
    u64 rtpoll_next_update;
    u64 rtpoll_until;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct psi_group {
    struct psi_group * parent;
    bool enabled;
    struct mutex avgs_lock;
    struct psi_group_cpu * pcpu;
    u64[6] avg_total;
    u64 avg_last_update;
    u64 avg_next_update;
    struct delayed_work avgs_work;
    struct list_head avg_triggers;
    u32[6] avg_nr_triggers;
    u64[12] total;
    long unsigned int[18] avg;
    struct task_struct * rtpoll_task;
    struct timer_list rtpoll_timer;
    wait_queue_head_t rtpoll_wait;
    atomic_t rtpoll_wakeup;
    atomic_t rtpoll_scheduled;
    struct mutex rtpoll_trigger_lock;
    struct list_head rtpoll_triggers;
    u32[6] rtpoll_nr_triggers;
    u32 rtpoll_states;
    u64 rtpoll_min_period;
    u64[6] rtpoll_total;
    u64 rtpoll_next_update;
    u64 rtpoll_until;
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
struct psi_group {
    struct mutex avgs_lock;
    struct psi_group_cpu * pcpu;
    u64[5] avg_total;
    u64 avg_last_update;
    u64 avg_next_update;
    struct delayed_work avgs_work;
    u64[10] total;
    long unsigned int[15] avg;
    atomic_t poll_scheduled;
    struct kthread_worker * poll_kworker;
    struct kthread_delayed_work poll_work;
    struct mutex trigger_lock;
    struct list_head triggers;
    u32[5] nr_triggers;
    u32 poll_states;
    u64 poll_min_period;
    u64[5] polling_total;
    u64 polling_next_update;
    u64 polling_until;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct psi_group {
    struct mutex avgs_lock;
    struct psi_group_cpu * pcpu;
    u64[5] avg_total;
    u64 avg_last_update;
    u64 avg_next_update;
    struct delayed_work avgs_work;
    u64[10] total;
    long unsigned int[15] avg;
    atomic_t poll_scheduled;
    struct kthread_worker * poll_kworker;
    struct kthread_delayed_work poll_work;
    struct mutex trigger_lock;
    struct list_head triggers;
    u32[5] nr_triggers;
    u32 poll_states;
    u64 poll_min_period;
    u64[5] polling_total;
    u64 polling_next_update;
    u64 polling_until;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct psi_group {
    struct mutex avgs_lock;
    struct psi_group_cpu * pcpu;
    u64[5] avg_total;
    u64 avg_last_update;
    u64 avg_next_update;
    struct delayed_work avgs_work;
    u64[10] total;
    long unsigned int[15] avg;
    atomic_t poll_scheduled;
    struct kthread_worker * poll_kworker;
    struct kthread_delayed_work poll_work;
    struct mutex trigger_lock;
    struct list_head triggers;
    u32[5] nr_triggers;
    u32 poll_states;
    u64 poll_min_period;
    u64[5] polling_total;
    u64 polling_next_update;
    u64 polling_until;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct psi_group {
    struct mutex avgs_lock;
    struct psi_group_cpu * pcpu;
    u64[5] avg_total;
    u64 avg_last_update;
    u64 avg_next_update;
    struct delayed_work avgs_work;
    u64[10] total;
    long unsigned int[15] avg;
    atomic_t poll_scheduled;
    struct kthread_worker * poll_kworker;
    struct kthread_delayed_work poll_work;
    struct mutex trigger_lock;
    struct list_head triggers;
    u32[5] nr_triggers;
    u32 poll_states;
    u64 poll_min_period;
    u64[5] polling_total;
    u64 polling_next_update;
    u64 polling_until;
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
struct psi_group {
    struct mutex avgs_lock;
    struct psi_group_cpu * pcpu;
    u64[5] avg_total;
    u64 avg_last_update;
    u64 avg_next_update;
    struct delayed_work avgs_work;
    u64[10] total;
    long unsigned int[15] avg;
    atomic_t poll_scheduled;
    struct kthread_worker * poll_kworker;
    struct kthread_delayed_work poll_work;
    struct mutex trigger_lock;
    struct list_head triggers;
    u32[5] nr_triggers;
    u32 poll_states;
    u64 poll_min_period;
    u64[5] polling_total;
    u64 polling_next_update;
    u64 polling_until;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct psi_group {
    struct mutex avgs_lock;
    struct psi_group_cpu * pcpu;
    u64[5] avg_total;
    u64 avg_last_update;
    u64 avg_next_update;
    struct delayed_work avgs_work;
    u64[10] total;
    long unsigned int[15] avg;
    atomic_t poll_scheduled;
    struct kthread_worker * poll_kworker;
    struct kthread_delayed_work poll_work;
    struct mutex trigger_lock;
    struct list_head triggers;
    u32[5] nr_triggers;
    u32 poll_states;
    u64 poll_min_period;
    u64[5] polling_total;
    u64 polling_next_update;
    u64 polling_until;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct psi_group {
    struct mutex avgs_lock;
    struct psi_group_cpu * pcpu;
    u64[5] avg_total;
    u64 avg_last_update;
    u64 avg_next_update;
    struct delayed_work avgs_work;
    u64[10] total;
    long unsigned int[15] avg;
    atomic_t poll_scheduled;
    struct kthread_worker * poll_kworker;
    struct kthread_delayed_work poll_work;
    struct mutex trigger_lock;
    struct list_head triggers;
    u32[5] nr_triggers;
    u32 poll_states;
    u64 poll_min_period;
    u64[5] polling_total;
    u64 polling_next_update;
    u64 polling_until;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct psi_group {
    struct mutex avgs_lock;
    struct psi_group_cpu * pcpu;
    u64[5] avg_total;
    u64 avg_last_update;
    u64 avg_next_update;
    struct delayed_work avgs_work;
    u64[10] total;
    long unsigned int[15] avg;
    atomic_t poll_scheduled;
    struct kthread_worker * poll_kworker;
    struct kthread_delayed_work poll_work;
    struct mutex trigger_lock;
    struct list_head triggers;
    u32[5] nr_triggers;
    u32 poll_states;
    u64 poll_min_period;
    u64[5] polling_total;
    u64 polling_next_update;
    u64 polling_until;
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct psi_group {
    struct mutex stat_lock;
    struct psi_group_cpu * pcpu;
    u64[5] total_prev;
    u64 last_update;
    u64 next_update;
    struct delayed_work clock_work;
    u64[5] total;
    long unsigned int[15] avg;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct mutex avgs_lock</code>
</li>
<li>
<b>Field added. </b>
<code>u64[5] avg_total</code>
</li>
<li>
<b>Field added. </b>
<code>u64 avg_last_update</code>
</li>
<li>
<b>Field added. </b>
<code>u64 avg_next_update</code>
</li>
<li>
<b>Field added. </b>
<code>struct delayed_work avgs_work</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t poll_scheduled</code>
</li>
<li>
<b>Field added. </b>
<code>struct kthread_worker * poll_kworker</code>
</li>
<li>
<b>Field added. </b>
<code>struct kthread_delayed_work poll_work</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex trigger_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head triggers</code>
</li>
<li>
<b>Field added. </b>
<code>u32[5] nr_triggers</code>
</li>
<li>
<b>Field added. </b>
<code>u32 poll_states</code>
</li>
<li>
<b>Field added. </b>
<code>u64 poll_min_period</code>
</li>
<li>
<b>Field added. </b>
<code>u64[5] polling_total</code>
</li>
<li>
<b>Field added. </b>
<code>u64 polling_next_update</code>
</li>
<li>
<b>Field added. </b>
<code>u64 polling_until</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mutex stat_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>u64[5] total_prev</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 last_update</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 next_update</code>
</li>
<li>
<b>Field removed. </b>
<code>struct delayed_work clock_work</code>
</li>
<li>
<b>Field type changed. </b>
<code>u64[5] total</code> ➡️ <code>u64[10] total</code>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct task_struct * poll_task</code>
</li>
<li>
<b>Field added. </b>
<code>struct timer_list poll_timer</code>
</li>
<li>
<b>Field added. </b>
<code>wait_queue_head_t poll_wait</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t poll_wakeup</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t poll_scheduled</code>
</li>
<li>
<b>Field removed. </b>
<code>struct kthread_worker * poll_kworker</code>
</li>
<li>
<b>Field removed. </b>
<code>struct kthread_delayed_work poll_work</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>u64[5] avg_total</code> ➡️ <code>u64[6] avg_total</code>
</li>
<li>
<b>Field type changed. </b>
<code>u64[10] total</code> ➡️ <code>u64[12] total</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int[15] avg</code> ➡️ <code>long unsigned int[18] avg</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32[5] nr_triggers</code> ➡️ <code>u32[6] nr_triggers</code>
</li>
<li>
<b>Field type changed. </b>
<code>u64[5] polling_total</code> ➡️ <code>u64[6] polling_total</code>
</li>
</ul>
</details>
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
<b>Field added. </b>
<code>struct psi_group * parent</code>
</li>
<li>
<b>Field added. </b>
<code>bool enabled</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t poll_scheduled</code>
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
<code>struct list_head avg_triggers</code>
</li>
<li>
<b>Field added. </b>
<code>u32[6] avg_nr_triggers</code>
</li>
<li>
<b>Field added. </b>
<code>struct task_struct * rtpoll_task</code>
</li>
<li>
<b>Field added. </b>
<code>struct timer_list rtpoll_timer</code>
</li>
<li>
<b>Field added. </b>
<code>wait_queue_head_t rtpoll_wait</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t rtpoll_wakeup</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t rtpoll_scheduled</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex rtpoll_trigger_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head rtpoll_triggers</code>
</li>
<li>
<b>Field added. </b>
<code>u32[6] rtpoll_nr_triggers</code>
</li>
<li>
<b>Field added. </b>
<code>u32 rtpoll_states</code>
</li>
<li>
<b>Field added. </b>
<code>u64 rtpoll_min_period</code>
</li>
<li>
<b>Field added. </b>
<code>u64[6] rtpoll_total</code>
</li>
<li>
<b>Field added. </b>
<code>u64 rtpoll_next_update</code>
</li>
<li>
<b>Field added. </b>
<code>u64 rtpoll_until</code>
</li>
<li>
<b>Field removed. </b>
<code>struct task_struct * poll_task</code>
</li>
<li>
<b>Field removed. </b>
<code>struct timer_list poll_timer</code>
</li>
<li>
<b>Field removed. </b>
<code>wait_queue_head_t poll_wait</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t poll_wakeup</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t poll_scheduled</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mutex trigger_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head triggers</code>
</li>
<li>
<b>Field removed. </b>
<code>u32[6] nr_triggers</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 poll_states</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 poll_min_period</code>
</li>
<li>
<b>Field removed. </b>
<code>u64[6] polling_total</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 polling_next_update</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 polling_until</code>
</li>
</ul>
</details>
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
