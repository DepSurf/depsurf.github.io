# Struct: <code>k_itimer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct k_itimer {
    struct list_head list;
    struct hlist_node t_hash;
    spinlock_t it_lock;
    clockid_t it_clock;
    timer_t it_id;
    int it_overrun;
    int it_overrun_last;
    int it_requeue_pending;
    int it_sigev_notify;
    struct signal_struct * it_signal;
    struct pid * it_pid;
    struct task_struct * it_process;
    struct sigqueue * sigq;
    union (anon) it;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct k_itimer {
    struct list_head list;
    struct hlist_node t_hash;
    spinlock_t it_lock;
    clockid_t it_clock;
    timer_t it_id;
    int it_overrun;
    int it_overrun_last;
    int it_requeue_pending;
    int it_sigev_notify;
    struct signal_struct * it_signal;
    struct pid * it_pid;
    struct task_struct * it_process;
    struct sigqueue * sigq;
    union (anon) it;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct k_itimer {
    struct list_head list;
    struct hlist_node t_hash;
    spinlock_t it_lock;
    clockid_t it_clock;
    timer_t it_id;
    int it_overrun;
    int it_overrun_last;
    int it_requeue_pending;
    int it_sigev_notify;
    struct signal_struct * it_signal;
    struct pid * it_pid;
    struct task_struct * it_process;
    struct sigqueue * sigq;
    union (anon) it;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct k_itimer {
    struct list_head list;
    struct hlist_node t_hash;
    spinlock_t it_lock;
    const struct k_clock * kclock;
    clockid_t it_clock;
    timer_t it_id;
    int it_active;
    int it_overrun;
    int it_overrun_last;
    int it_requeue_pending;
    int it_sigev_notify;
    ktime_t it_interval;
    struct signal_struct * it_signal;
    struct pid * it_pid;
    struct task_struct * it_process;
    struct sigqueue * sigq;
    union (anon) it;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct k_itimer {
    struct list_head list;
    struct hlist_node t_hash;
    spinlock_t it_lock;
    const struct k_clock * kclock;
    clockid_t it_clock;
    timer_t it_id;
    int it_active;
    int it_overrun;
    int it_overrun_last;
    int it_requeue_pending;
    int it_sigev_notify;
    ktime_t it_interval;
    struct signal_struct * it_signal;
    struct pid * it_pid;
    struct task_struct * it_process;
    struct sigqueue * sigq;
    union (anon) it;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct k_itimer {
    struct list_head list;
    struct hlist_node t_hash;
    spinlock_t it_lock;
    const struct k_clock * kclock;
    clockid_t it_clock;
    timer_t it_id;
    int it_active;
    s64 it_overrun;
    s64 it_overrun_last;
    int it_requeue_pending;
    int it_sigev_notify;
    ktime_t it_interval;
    struct signal_struct * it_signal;
    struct pid * it_pid;
    struct task_struct * it_process;
    struct sigqueue * sigq;
    union (anon) it;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct k_itimer {
    struct list_head list;
    struct hlist_node t_hash;
    spinlock_t it_lock;
    const struct k_clock * kclock;
    clockid_t it_clock;
    timer_t it_id;
    int it_active;
    s64 it_overrun;
    s64 it_overrun_last;
    int it_requeue_pending;
    int it_sigev_notify;
    ktime_t it_interval;
    struct signal_struct * it_signal;
    struct pid * it_pid;
    struct task_struct * it_process;
    struct sigqueue * sigq;
    union (anon) it;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct k_itimer {
    struct list_head list;
    struct hlist_node t_hash;
    spinlock_t it_lock;
    const struct k_clock * kclock;
    clockid_t it_clock;
    timer_t it_id;
    int it_active;
    s64 it_overrun;
    s64 it_overrun_last;
    int it_requeue_pending;
    int it_sigev_notify;
    ktime_t it_interval;
    struct signal_struct * it_signal;
    struct pid * it_pid;
    struct task_struct * it_process;
    struct sigqueue * sigq;
    union (anon) it;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct k_itimer {
    struct list_head list;
    struct hlist_node t_hash;
    spinlock_t it_lock;
    const struct k_clock * kclock;
    clockid_t it_clock;
    timer_t it_id;
    int it_active;
    s64 it_overrun;
    s64 it_overrun_last;
    int it_requeue_pending;
    int it_sigev_notify;
    ktime_t it_interval;
    struct signal_struct * it_signal;
    struct pid * it_pid;
    struct task_struct * it_process;
    struct sigqueue * sigq;
    union (anon) it;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct k_itimer {
    struct list_head list;
    struct hlist_node t_hash;
    spinlock_t it_lock;
    const struct k_clock * kclock;
    clockid_t it_clock;
    timer_t it_id;
    int it_active;
    s64 it_overrun;
    s64 it_overrun_last;
    int it_requeue_pending;
    int it_sigev_notify;
    ktime_t it_interval;
    struct signal_struct * it_signal;
    struct pid * it_pid;
    struct task_struct * it_process;
    struct sigqueue * sigq;
    union (anon) it;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct k_itimer {
    struct list_head list;
    struct hlist_node t_hash;
    spinlock_t it_lock;
    const struct k_clock * kclock;
    clockid_t it_clock;
    timer_t it_id;
    int it_active;
    s64 it_overrun;
    s64 it_overrun_last;
    int it_requeue_pending;
    int it_sigev_notify;
    ktime_t it_interval;
    struct signal_struct * it_signal;
    struct pid * it_pid;
    struct task_struct * it_process;
    struct sigqueue * sigq;
    union (anon) it;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct k_itimer {
    struct list_head list;
    struct hlist_node t_hash;
    spinlock_t it_lock;
    const struct k_clock * kclock;
    clockid_t it_clock;
    timer_t it_id;
    int it_active;
    s64 it_overrun;
    s64 it_overrun_last;
    int it_requeue_pending;
    int it_sigev_notify;
    ktime_t it_interval;
    struct signal_struct * it_signal;
    struct pid * it_pid;
    struct task_struct * it_process;
    struct sigqueue * sigq;
    union (anon) it;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct k_itimer {
    struct list_head list;
    struct hlist_node t_hash;
    spinlock_t it_lock;
    const struct k_clock * kclock;
    clockid_t it_clock;
    timer_t it_id;
    int it_active;
    s64 it_overrun;
    s64 it_overrun_last;
    int it_requeue_pending;
    int it_sigev_notify;
    ktime_t it_interval;
    struct signal_struct * it_signal;
    struct pid * it_pid;
    struct task_struct * it_process;
    struct sigqueue * sigq;
    union (anon) it;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct k_itimer {
    struct list_head list;
    struct hlist_node t_hash;
    spinlock_t it_lock;
    const struct k_clock * kclock;
    clockid_t it_clock;
    timer_t it_id;
    int it_active;
    s64 it_overrun;
    s64 it_overrun_last;
    int it_requeue_pending;
    int it_sigev_notify;
    ktime_t it_interval;
    struct signal_struct * it_signal;
    struct pid * it_pid;
    struct task_struct * it_process;
    struct sigqueue * sigq;
    union (anon) it;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct k_itimer {
    struct list_head list;
    struct hlist_node t_hash;
    spinlock_t it_lock;
    const struct k_clock * kclock;
    clockid_t it_clock;
    timer_t it_id;
    int it_active;
    s64 it_overrun;
    s64 it_overrun_last;
    int it_requeue_pending;
    int it_sigev_notify;
    ktime_t it_interval;
    struct signal_struct * it_signal;
    struct pid * it_pid;
    struct task_struct * it_process;
    struct sigqueue * sigq;
    union (anon) it;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct k_itimer {
    struct list_head list;
    struct hlist_node t_hash;
    spinlock_t it_lock;
    const struct k_clock * kclock;
    clockid_t it_clock;
    timer_t it_id;
    int it_active;
    s64 it_overrun;
    s64 it_overrun_last;
    int it_requeue_pending;
    int it_sigev_notify;
    ktime_t it_interval;
    struct signal_struct * it_signal;
    struct pid * it_pid;
    struct task_struct * it_process;
    struct sigqueue * sigq;
    union (anon) it;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct k_itimer {
    struct list_head list;
    struct hlist_node t_hash;
    spinlock_t it_lock;
    const struct k_clock * kclock;
    clockid_t it_clock;
    timer_t it_id;
    int it_active;
    s64 it_overrun;
    s64 it_overrun_last;
    int it_requeue_pending;
    int it_sigev_notify;
    ktime_t it_interval;
    struct signal_struct * it_signal;
    struct pid * it_pid;
    struct task_struct * it_process;
    struct sigqueue * sigq;
    union (anon) it;
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
struct k_itimer {
    struct list_head list;
    struct hlist_node t_hash;
    spinlock_t it_lock;
    const struct k_clock * kclock;
    clockid_t it_clock;
    timer_t it_id;
    int it_active;
    s64 it_overrun;
    s64 it_overrun_last;
    int it_requeue_pending;
    int it_sigev_notify;
    ktime_t it_interval;
    struct signal_struct * it_signal;
    struct pid * it_pid;
    struct task_struct * it_process;
    struct sigqueue * sigq;
    union (anon) it;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct k_itimer {
    struct list_head list;
    struct hlist_node t_hash;
    spinlock_t it_lock;
    const struct k_clock * kclock;
    clockid_t it_clock;
    timer_t it_id;
    int it_active;
    s64 it_overrun;
    s64 it_overrun_last;
    int it_requeue_pending;
    int it_sigev_notify;
    ktime_t it_interval;
    struct signal_struct * it_signal;
    struct pid * it_pid;
    struct task_struct * it_process;
    struct sigqueue * sigq;
    union (anon) it;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct k_itimer {
    struct list_head list;
    struct hlist_node t_hash;
    spinlock_t it_lock;
    const struct k_clock * kclock;
    clockid_t it_clock;
    timer_t it_id;
    int it_active;
    s64 it_overrun;
    s64 it_overrun_last;
    int it_requeue_pending;
    int it_sigev_notify;
    ktime_t it_interval;
    struct signal_struct * it_signal;
    struct pid * it_pid;
    struct task_struct * it_process;
    struct sigqueue * sigq;
    union (anon) it;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct k_itimer {
    struct list_head list;
    struct hlist_node t_hash;
    spinlock_t it_lock;
    const struct k_clock * kclock;
    clockid_t it_clock;
    timer_t it_id;
    int it_active;
    s64 it_overrun;
    s64 it_overrun_last;
    int it_requeue_pending;
    int it_sigev_notify;
    ktime_t it_interval;
    struct signal_struct * it_signal;
    struct pid * it_pid;
    struct task_struct * it_process;
    struct sigqueue * sigq;
    union (anon) it;
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
struct k_itimer {
    struct list_head list;
    struct hlist_node t_hash;
    spinlock_t it_lock;
    const struct k_clock * kclock;
    clockid_t it_clock;
    timer_t it_id;
    int it_active;
    s64 it_overrun;
    s64 it_overrun_last;
    int it_requeue_pending;
    int it_sigev_notify;
    ktime_t it_interval;
    struct signal_struct * it_signal;
    struct pid * it_pid;
    struct task_struct * it_process;
    struct sigqueue * sigq;
    union (anon) it;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct k_itimer {
    struct list_head list;
    struct hlist_node t_hash;
    spinlock_t it_lock;
    const struct k_clock * kclock;
    clockid_t it_clock;
    timer_t it_id;
    int it_active;
    s64 it_overrun;
    s64 it_overrun_last;
    int it_requeue_pending;
    int it_sigev_notify;
    ktime_t it_interval;
    struct signal_struct * it_signal;
    struct pid * it_pid;
    struct task_struct * it_process;
    struct sigqueue * sigq;
    union (anon) it;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct k_itimer {
    struct list_head list;
    struct hlist_node t_hash;
    spinlock_t it_lock;
    const struct k_clock * kclock;
    clockid_t it_clock;
    timer_t it_id;
    int it_active;
    s64 it_overrun;
    s64 it_overrun_last;
    int it_requeue_pending;
    int it_sigev_notify;
    ktime_t it_interval;
    struct signal_struct * it_signal;
    struct pid * it_pid;
    struct task_struct * it_process;
    struct sigqueue * sigq;
    union (anon) it;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct k_itimer {
    struct list_head list;
    struct hlist_node t_hash;
    spinlock_t it_lock;
    const struct k_clock * kclock;
    clockid_t it_clock;
    timer_t it_id;
    int it_active;
    s64 it_overrun;
    s64 it_overrun_last;
    int it_requeue_pending;
    int it_sigev_notify;
    ktime_t it_interval;
    struct signal_struct * it_signal;
    struct pid * it_pid;
    struct task_struct * it_process;
    struct sigqueue * sigq;
    union (anon) it;
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
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const struct k_clock * kclock</code>
</li>
<li>
<b>Field added. </b>
<code>int it_active</code>
</li>
<li>
<b>Field added. </b>
<code>ktime_t it_interval</code>
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
<code>int it_overrun</code> ➡️ <code>s64 it_overrun</code>
</li>
<li>
<b>Field type changed. </b>
<code>int it_overrun_last</code> ➡️ <code>s64 it_overrun_last</code>
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
<code>struct callback_head rcu</code>
</li>
</ul>
</details>
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
