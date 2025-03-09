# Struct: <code>sched_class</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct sched_class {
    const struct sched_class * next;
    void (*)(struct rq *, struct task_struct *, int) enqueue_task;
    void (*)(struct rq *, struct task_struct *, int) dequeue_task;
    void (*)(struct rq *) yield_task;
    bool (*)(struct rq *, struct task_struct *, bool) yield_to_task;
    void (*)(struct rq *, struct task_struct *, int) check_preempt_curr;
    struct task_struct * (*)(struct rq *, struct task_struct *) pick_next_task;
    void (*)(struct rq *, struct task_struct *) put_prev_task;
    int (*)(struct task_struct *, int, int, int) select_task_rq;
    void (*)(struct task_struct *) migrate_task_rq;
    void (*)(struct task_struct *) task_waking;
    void (*)(struct rq *, struct task_struct *) task_woken;
    void (*)(struct task_struct *, const struct cpumask *) set_cpus_allowed;
    void (*)(struct rq *) rq_online;
    void (*)(struct rq *) rq_offline;
    void (*)(struct rq *) set_curr_task;
    void (*)(struct rq *, struct task_struct *, int) task_tick;
    void (*)(struct task_struct *) task_fork;
    void (*)(struct task_struct *) task_dead;
    void (*)(struct rq *, struct task_struct *) switched_from;
    void (*)(struct rq *, struct task_struct *) switched_to;
    void (*)(struct rq *, struct task_struct *, int) prio_changed;
    unsigned int (*)(struct rq *, struct task_struct *) get_rr_interval;
    void (*)(struct rq *) update_curr;
    void (*)(struct task_struct *) task_move_group;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct sched_class {
    const struct sched_class * next;
    void (*)(struct rq *, struct task_struct *, int) enqueue_task;
    void (*)(struct rq *, struct task_struct *, int) dequeue_task;
    void (*)(struct rq *) yield_task;
    bool (*)(struct rq *, struct task_struct *, bool) yield_to_task;
    void (*)(struct rq *, struct task_struct *, int) check_preempt_curr;
    struct task_struct * (*)(struct rq *, struct task_struct *, struct pin_cookie) pick_next_task;
    void (*)(struct rq *, struct task_struct *) put_prev_task;
    int (*)(struct task_struct *, int, int, int) select_task_rq;
    void (*)(struct task_struct *) migrate_task_rq;
    void (*)(struct rq *, struct task_struct *) task_woken;
    void (*)(struct task_struct *, const struct cpumask *) set_cpus_allowed;
    void (*)(struct rq *) rq_online;
    void (*)(struct rq *) rq_offline;
    void (*)(struct rq *) set_curr_task;
    void (*)(struct rq *, struct task_struct *, int) task_tick;
    void (*)(struct task_struct *) task_fork;
    void (*)(struct task_struct *) task_dead;
    void (*)(struct rq *, struct task_struct *) switched_from;
    void (*)(struct rq *, struct task_struct *) switched_to;
    void (*)(struct rq *, struct task_struct *, int) prio_changed;
    unsigned int (*)(struct rq *, struct task_struct *) get_rr_interval;
    void (*)(struct rq *) update_curr;
    void (*)(struct task_struct *, int) task_change_group;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct sched_class {
    const struct sched_class * next;
    void (*)(struct rq *, struct task_struct *, int) enqueue_task;
    void (*)(struct rq *, struct task_struct *, int) dequeue_task;
    void (*)(struct rq *) yield_task;
    bool (*)(struct rq *, struct task_struct *, bool) yield_to_task;
    void (*)(struct rq *, struct task_struct *, int) check_preempt_curr;
    struct task_struct * (*)(struct rq *, struct task_struct *, struct pin_cookie) pick_next_task;
    void (*)(struct rq *, struct task_struct *) put_prev_task;
    int (*)(struct task_struct *, int, int, int) select_task_rq;
    void (*)(struct task_struct *) migrate_task_rq;
    void (*)(struct rq *, struct task_struct *) task_woken;
    void (*)(struct task_struct *, const struct cpumask *) set_cpus_allowed;
    void (*)(struct rq *) rq_online;
    void (*)(struct rq *) rq_offline;
    void (*)(struct rq *) set_curr_task;
    void (*)(struct rq *, struct task_struct *, int) task_tick;
    void (*)(struct task_struct *) task_fork;
    void (*)(struct task_struct *) task_dead;
    void (*)(struct rq *, struct task_struct *) switched_from;
    void (*)(struct rq *, struct task_struct *) switched_to;
    void (*)(struct rq *, struct task_struct *, int) prio_changed;
    unsigned int (*)(struct rq *, struct task_struct *) get_rr_interval;
    void (*)(struct rq *) update_curr;
    void (*)(struct task_struct *, int) task_change_group;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct sched_class {
    const struct sched_class * next;
    void (*)(struct rq *, struct task_struct *, int) enqueue_task;
    void (*)(struct rq *, struct task_struct *, int) dequeue_task;
    void (*)(struct rq *) yield_task;
    bool (*)(struct rq *, struct task_struct *, bool) yield_to_task;
    void (*)(struct rq *, struct task_struct *, int) check_preempt_curr;
    struct task_struct * (*)(struct rq *, struct task_struct *, struct rq_flags *) pick_next_task;
    void (*)(struct rq *, struct task_struct *) put_prev_task;
    int (*)(struct task_struct *, int, int, int) select_task_rq;
    void (*)(struct task_struct *) migrate_task_rq;
    void (*)(struct rq *, struct task_struct *) task_woken;
    void (*)(struct task_struct *, const struct cpumask *) set_cpus_allowed;
    void (*)(struct rq *) rq_online;
    void (*)(struct rq *) rq_offline;
    void (*)(struct rq *) set_curr_task;
    void (*)(struct rq *, struct task_struct *, int) task_tick;
    void (*)(struct task_struct *) task_fork;
    void (*)(struct task_struct *) task_dead;
    void (*)(struct rq *, struct task_struct *) switched_from;
    void (*)(struct rq *, struct task_struct *) switched_to;
    void (*)(struct rq *, struct task_struct *, int) prio_changed;
    unsigned int (*)(struct rq *, struct task_struct *) get_rr_interval;
    void (*)(struct rq *) update_curr;
    void (*)(struct task_struct *, int) task_change_group;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct sched_class {
    const struct sched_class * next;
    void (*)(struct rq *, struct task_struct *, int) enqueue_task;
    void (*)(struct rq *, struct task_struct *, int) dequeue_task;
    void (*)(struct rq *) yield_task;
    bool (*)(struct rq *, struct task_struct *, bool) yield_to_task;
    void (*)(struct rq *, struct task_struct *, int) check_preempt_curr;
    struct task_struct * (*)(struct rq *, struct task_struct *, struct rq_flags *) pick_next_task;
    void (*)(struct rq *, struct task_struct *) put_prev_task;
    int (*)(struct task_struct *, int, int, int) select_task_rq;
    void (*)(struct task_struct *) migrate_task_rq;
    void (*)(struct rq *, struct task_struct *) task_woken;
    void (*)(struct task_struct *, const struct cpumask *) set_cpus_allowed;
    void (*)(struct rq *) rq_online;
    void (*)(struct rq *) rq_offline;
    void (*)(struct rq *) set_curr_task;
    void (*)(struct rq *, struct task_struct *, int) task_tick;
    void (*)(struct task_struct *) task_fork;
    void (*)(struct task_struct *) task_dead;
    void (*)(struct rq *, struct task_struct *) switched_from;
    void (*)(struct rq *, struct task_struct *) switched_to;
    void (*)(struct rq *, struct task_struct *, int) prio_changed;
    unsigned int (*)(struct rq *, struct task_struct *) get_rr_interval;
    void (*)(struct rq *) update_curr;
    void (*)(struct task_struct *, int) task_change_group;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct sched_class {
    const struct sched_class * next;
    void (*)(struct rq *, struct task_struct *, int) enqueue_task;
    void (*)(struct rq *, struct task_struct *, int) dequeue_task;
    void (*)(struct rq *) yield_task;
    bool (*)(struct rq *, struct task_struct *, bool) yield_to_task;
    void (*)(struct rq *, struct task_struct *, int) check_preempt_curr;
    struct task_struct * (*)(struct rq *, struct task_struct *, struct rq_flags *) pick_next_task;
    void (*)(struct rq *, struct task_struct *) put_prev_task;
    int (*)(struct task_struct *, int, int, int) select_task_rq;
    void (*)(struct task_struct *) migrate_task_rq;
    void (*)(struct rq *, struct task_struct *) task_woken;
    void (*)(struct task_struct *, const struct cpumask *) set_cpus_allowed;
    void (*)(struct rq *) rq_online;
    void (*)(struct rq *) rq_offline;
    void (*)(struct rq *) set_curr_task;
    void (*)(struct rq *, struct task_struct *, int) task_tick;
    void (*)(struct task_struct *) task_fork;
    void (*)(struct task_struct *) task_dead;
    void (*)(struct rq *, struct task_struct *) switched_from;
    void (*)(struct rq *, struct task_struct *) switched_to;
    void (*)(struct rq *, struct task_struct *, int) prio_changed;
    unsigned int (*)(struct rq *, struct task_struct *) get_rr_interval;
    void (*)(struct rq *) update_curr;
    void (*)(struct task_struct *, int) task_change_group;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct sched_class {
    const struct sched_class * next;
    void (*)(struct rq *, struct task_struct *, int) enqueue_task;
    void (*)(struct rq *, struct task_struct *, int) dequeue_task;
    void (*)(struct rq *) yield_task;
    bool (*)(struct rq *, struct task_struct *, bool) yield_to_task;
    void (*)(struct rq *, struct task_struct *, int) check_preempt_curr;
    struct task_struct * (*)(struct rq *, struct task_struct *, struct rq_flags *) pick_next_task;
    void (*)(struct rq *, struct task_struct *) put_prev_task;
    int (*)(struct task_struct *, int, int, int) select_task_rq;
    void (*)(struct task_struct *, int) migrate_task_rq;
    void (*)(struct rq *, struct task_struct *) task_woken;
    void (*)(struct task_struct *, const struct cpumask *) set_cpus_allowed;
    void (*)(struct rq *) rq_online;
    void (*)(struct rq *) rq_offline;
    void (*)(struct rq *) set_curr_task;
    void (*)(struct rq *, struct task_struct *, int) task_tick;
    void (*)(struct task_struct *) task_fork;
    void (*)(struct task_struct *) task_dead;
    void (*)(struct rq *, struct task_struct *) switched_from;
    void (*)(struct rq *, struct task_struct *) switched_to;
    void (*)(struct rq *, struct task_struct *, int) prio_changed;
    unsigned int (*)(struct rq *, struct task_struct *) get_rr_interval;
    void (*)(struct rq *) update_curr;
    void (*)(struct task_struct *, int) task_change_group;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct sched_class {
    const struct sched_class * next;
    int uclamp_enabled;
    void (*)(struct rq *, struct task_struct *, int) enqueue_task;
    void (*)(struct rq *, struct task_struct *, int) dequeue_task;
    void (*)(struct rq *) yield_task;
    bool (*)(struct rq *, struct task_struct *, bool) yield_to_task;
    void (*)(struct rq *, struct task_struct *, int) check_preempt_curr;
    struct task_struct * (*)(struct rq *, struct task_struct *, struct rq_flags *) pick_next_task;
    void (*)(struct rq *, struct task_struct *) put_prev_task;
    int (*)(struct task_struct *, int, int, int) select_task_rq;
    void (*)(struct task_struct *, int) migrate_task_rq;
    void (*)(struct rq *, struct task_struct *) task_woken;
    void (*)(struct task_struct *, const struct cpumask *) set_cpus_allowed;
    void (*)(struct rq *) rq_online;
    void (*)(struct rq *) rq_offline;
    void (*)(struct rq *) set_curr_task;
    void (*)(struct rq *, struct task_struct *, int) task_tick;
    void (*)(struct task_struct *) task_fork;
    void (*)(struct task_struct *) task_dead;
    void (*)(struct rq *, struct task_struct *) switched_from;
    void (*)(struct rq *, struct task_struct *) switched_to;
    void (*)(struct rq *, struct task_struct *, int) prio_changed;
    unsigned int (*)(struct rq *, struct task_struct *) get_rr_interval;
    void (*)(struct rq *) update_curr;
    void (*)(struct task_struct *, int) task_change_group;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct sched_class {
    const struct sched_class * next;
    int uclamp_enabled;
    void (*)(struct rq *, struct task_struct *, int) enqueue_task;
    void (*)(struct rq *, struct task_struct *, int) dequeue_task;
    void (*)(struct rq *) yield_task;
    bool (*)(struct rq *, struct task_struct *, bool) yield_to_task;
    void (*)(struct rq *, struct task_struct *, int) check_preempt_curr;
    struct task_struct * (*)(struct rq *, struct task_struct *, struct rq_flags *) pick_next_task;
    void (*)(struct rq *, struct task_struct *) put_prev_task;
    void (*)(struct rq *, struct task_struct *, bool) set_next_task;
    int (*)(struct rq *, struct task_struct *, struct rq_flags *) balance;
    int (*)(struct task_struct *, int, int, int) select_task_rq;
    void (*)(struct task_struct *, int) migrate_task_rq;
    void (*)(struct rq *, struct task_struct *) task_woken;
    void (*)(struct task_struct *, const struct cpumask *) set_cpus_allowed;
    void (*)(struct rq *) rq_online;
    void (*)(struct rq *) rq_offline;
    void (*)(struct rq *, struct task_struct *, int) task_tick;
    void (*)(struct task_struct *) task_fork;
    void (*)(struct task_struct *) task_dead;
    void (*)(struct rq *, struct task_struct *) switched_from;
    void (*)(struct rq *, struct task_struct *) switched_to;
    void (*)(struct rq *, struct task_struct *, int) prio_changed;
    unsigned int (*)(struct rq *, struct task_struct *) get_rr_interval;
    void (*)(struct rq *) update_curr;
    void (*)(struct task_struct *, int) task_change_group;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct sched_class {
    const struct sched_class * next;
    int uclamp_enabled;
    void (*)(struct rq *, struct task_struct *, int) enqueue_task;
    void (*)(struct rq *, struct task_struct *, int) dequeue_task;
    void (*)(struct rq *) yield_task;
    bool (*)(struct rq *, struct task_struct *, bool) yield_to_task;
    void (*)(struct rq *, struct task_struct *, int) check_preempt_curr;
    struct task_struct * (*)(struct rq *) pick_next_task;
    void (*)(struct rq *, struct task_struct *) put_prev_task;
    void (*)(struct rq *, struct task_struct *, bool) set_next_task;
    int (*)(struct rq *, struct task_struct *, struct rq_flags *) balance;
    int (*)(struct task_struct *, int, int, int) select_task_rq;
    void (*)(struct task_struct *, int) migrate_task_rq;
    void (*)(struct rq *, struct task_struct *) task_woken;
    void (*)(struct task_struct *, const struct cpumask *) set_cpus_allowed;
    void (*)(struct rq *) rq_online;
    void (*)(struct rq *) rq_offline;
    void (*)(struct rq *, struct task_struct *, int) task_tick;
    void (*)(struct task_struct *) task_fork;
    void (*)(struct task_struct *) task_dead;
    void (*)(struct rq *, struct task_struct *) switched_from;
    void (*)(struct rq *, struct task_struct *) switched_to;
    void (*)(struct rq *, struct task_struct *, int) prio_changed;
    unsigned int (*)(struct rq *, struct task_struct *) get_rr_interval;
    void (*)(struct rq *) update_curr;
    void (*)(struct task_struct *, int) task_change_group;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct sched_class {
    int uclamp_enabled;
    void (*)(struct rq *, struct task_struct *, int) enqueue_task;
    void (*)(struct rq *, struct task_struct *, int) dequeue_task;
    void (*)(struct rq *) yield_task;
    bool (*)(struct rq *, struct task_struct *) yield_to_task;
    void (*)(struct rq *, struct task_struct *, int) check_preempt_curr;
    struct task_struct * (*)(struct rq *) pick_next_task;
    void (*)(struct rq *, struct task_struct *) put_prev_task;
    void (*)(struct rq *, struct task_struct *, bool) set_next_task;
    int (*)(struct rq *, struct task_struct *, struct rq_flags *) balance;
    int (*)(struct task_struct *, int, int) select_task_rq;
    void (*)(struct task_struct *, int) migrate_task_rq;
    void (*)(struct rq *, struct task_struct *) task_woken;
    void (*)(struct task_struct *, const struct cpumask *, u32) set_cpus_allowed;
    void (*)(struct rq *) rq_online;
    void (*)(struct rq *) rq_offline;
    struct rq * (*)(struct task_struct *, struct rq *) find_lock_rq;
    void (*)(struct rq *, struct task_struct *, int) task_tick;
    void (*)(struct task_struct *) task_fork;
    void (*)(struct task_struct *) task_dead;
    void (*)(struct rq *, struct task_struct *) switched_from;
    void (*)(struct rq *, struct task_struct *) switched_to;
    void (*)(struct rq *, struct task_struct *, int) prio_changed;
    unsigned int (*)(struct rq *, struct task_struct *) get_rr_interval;
    void (*)(struct rq *) update_curr;
    void (*)(struct task_struct *, int) task_change_group;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct sched_class {
    int uclamp_enabled;
    void (*)(struct rq *, struct task_struct *, int) enqueue_task;
    void (*)(struct rq *, struct task_struct *, int) dequeue_task;
    void (*)(struct rq *) yield_task;
    bool (*)(struct rq *, struct task_struct *) yield_to_task;
    void (*)(struct rq *, struct task_struct *, int) check_preempt_curr;
    struct task_struct * (*)(struct rq *) pick_next_task;
    void (*)(struct rq *, struct task_struct *) put_prev_task;
    void (*)(struct rq *, struct task_struct *, bool) set_next_task;
    int (*)(struct rq *, struct task_struct *, struct rq_flags *) balance;
    int (*)(struct task_struct *, int, int) select_task_rq;
    void (*)(struct task_struct *, int) migrate_task_rq;
    void (*)(struct rq *, struct task_struct *) task_woken;
    void (*)(struct task_struct *, const struct cpumask *, u32) set_cpus_allowed;
    void (*)(struct rq *) rq_online;
    void (*)(struct rq *) rq_offline;
    struct rq * (*)(struct task_struct *, struct rq *) find_lock_rq;
    void (*)(struct rq *, struct task_struct *, int) task_tick;
    void (*)(struct task_struct *) task_fork;
    void (*)(struct task_struct *) task_dead;
    void (*)(struct rq *, struct task_struct *) switched_from;
    void (*)(struct rq *, struct task_struct *) switched_to;
    void (*)(struct rq *, struct task_struct *, int) prio_changed;
    unsigned int (*)(struct rq *, struct task_struct *) get_rr_interval;
    void (*)(struct rq *) update_curr;
    void (*)(struct task_struct *, int) task_change_group;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct sched_class {
    int uclamp_enabled;
    void (*)(struct rq *, struct task_struct *, int) enqueue_task;
    void (*)(struct rq *, struct task_struct *, int) dequeue_task;
    void (*)(struct rq *) yield_task;
    bool (*)(struct rq *, struct task_struct *) yield_to_task;
    void (*)(struct rq *, struct task_struct *, int) check_preempt_curr;
    struct task_struct * (*)(struct rq *) pick_next_task;
    void (*)(struct rq *, struct task_struct *) put_prev_task;
    void (*)(struct rq *, struct task_struct *, bool) set_next_task;
    int (*)(struct rq *, struct task_struct *, struct rq_flags *) balance;
    int (*)(struct task_struct *, int, int) select_task_rq;
    struct task_struct * (*)(struct rq *) pick_task;
    void (*)(struct task_struct *, int) migrate_task_rq;
    void (*)(struct rq *, struct task_struct *) task_woken;
    void (*)(struct task_struct *, const struct cpumask *, u32) set_cpus_allowed;
    void (*)(struct rq *) rq_online;
    void (*)(struct rq *) rq_offline;
    struct rq * (*)(struct task_struct *, struct rq *) find_lock_rq;
    void (*)(struct rq *, struct task_struct *, int) task_tick;
    void (*)(struct task_struct *) task_fork;
    void (*)(struct task_struct *) task_dead;
    void (*)(struct rq *, struct task_struct *) switched_from;
    void (*)(struct rq *, struct task_struct *) switched_to;
    void (*)(struct rq *, struct task_struct *, int) prio_changed;
    unsigned int (*)(struct rq *, struct task_struct *) get_rr_interval;
    void (*)(struct rq *) update_curr;
    void (*)(struct task_struct *, int) task_change_group;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct sched_class {
    int uclamp_enabled;
    void (*)(struct rq *, struct task_struct *, int) enqueue_task;
    void (*)(struct rq *, struct task_struct *, int) dequeue_task;
    void (*)(struct rq *) yield_task;
    bool (*)(struct rq *, struct task_struct *) yield_to_task;
    void (*)(struct rq *, struct task_struct *, int) check_preempt_curr;
    struct task_struct * (*)(struct rq *) pick_next_task;
    void (*)(struct rq *, struct task_struct *) put_prev_task;
    void (*)(struct rq *, struct task_struct *, bool) set_next_task;
    int (*)(struct rq *, struct task_struct *, struct rq_flags *) balance;
    int (*)(struct task_struct *, int, int) select_task_rq;
    struct task_struct * (*)(struct rq *) pick_task;
    void (*)(struct task_struct *, int) migrate_task_rq;
    void (*)(struct rq *, struct task_struct *) task_woken;
    void (*)(struct task_struct *, const struct cpumask *, u32) set_cpus_allowed;
    void (*)(struct rq *) rq_online;
    void (*)(struct rq *) rq_offline;
    struct rq * (*)(struct task_struct *, struct rq *) find_lock_rq;
    void (*)(struct rq *, struct task_struct *, int) task_tick;
    void (*)(struct task_struct *) task_fork;
    void (*)(struct task_struct *) task_dead;
    void (*)(struct rq *, struct task_struct *) switched_from;
    void (*)(struct rq *, struct task_struct *) switched_to;
    void (*)(struct rq *, struct task_struct *, int) prio_changed;
    unsigned int (*)(struct rq *, struct task_struct *) get_rr_interval;
    void (*)(struct rq *) update_curr;
    void (*)(struct task_struct *, int) task_change_group;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct sched_class {
    int uclamp_enabled;
    void (*)(struct rq *, struct task_struct *, int) enqueue_task;
    void (*)(struct rq *, struct task_struct *, int) dequeue_task;
    void (*)(struct rq *) yield_task;
    bool (*)(struct rq *, struct task_struct *) yield_to_task;
    void (*)(struct rq *, struct task_struct *, int) check_preempt_curr;
    struct task_struct * (*)(struct rq *) pick_next_task;
    void (*)(struct rq *, struct task_struct *) put_prev_task;
    void (*)(struct rq *, struct task_struct *, bool) set_next_task;
    int (*)(struct rq *, struct task_struct *, struct rq_flags *) balance;
    int (*)(struct task_struct *, int, int) select_task_rq;
    struct task_struct * (*)(struct rq *) pick_task;
    void (*)(struct task_struct *, int) migrate_task_rq;
    void (*)(struct rq *, struct task_struct *) task_woken;
    void (*)(struct task_struct *, struct affinity_context *) set_cpus_allowed;
    void (*)(struct rq *) rq_online;
    void (*)(struct rq *) rq_offline;
    struct rq * (*)(struct task_struct *, struct rq *) find_lock_rq;
    void (*)(struct rq *, struct task_struct *, int) task_tick;
    void (*)(struct task_struct *) task_fork;
    void (*)(struct task_struct *) task_dead;
    void (*)(struct rq *, struct task_struct *) switched_from;
    void (*)(struct rq *, struct task_struct *) switched_to;
    void (*)(struct rq *, struct task_struct *, int) prio_changed;
    unsigned int (*)(struct rq *, struct task_struct *) get_rr_interval;
    void (*)(struct rq *) update_curr;
    void (*)(struct task_struct *) task_change_group;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct sched_class {
    int uclamp_enabled;
    void (*)(struct rq *, struct task_struct *, int) enqueue_task;
    void (*)(struct rq *, struct task_struct *, int) dequeue_task;
    void (*)(struct rq *) yield_task;
    bool (*)(struct rq *, struct task_struct *) yield_to_task;
    void (*)(struct rq *, struct task_struct *, int) check_preempt_curr;
    struct task_struct * (*)(struct rq *) pick_next_task;
    void (*)(struct rq *, struct task_struct *) put_prev_task;
    void (*)(struct rq *, struct task_struct *, bool) set_next_task;
    int (*)(struct rq *, struct task_struct *, struct rq_flags *) balance;
    int (*)(struct task_struct *, int, int) select_task_rq;
    struct task_struct * (*)(struct rq *) pick_task;
    void (*)(struct task_struct *, int) migrate_task_rq;
    void (*)(struct rq *, struct task_struct *) task_woken;
    void (*)(struct task_struct *, struct affinity_context *) set_cpus_allowed;
    void (*)(struct rq *) rq_online;
    void (*)(struct rq *) rq_offline;
    struct rq * (*)(struct task_struct *, struct rq *) find_lock_rq;
    void (*)(struct rq *, struct task_struct *, int) task_tick;
    void (*)(struct task_struct *) task_fork;
    void (*)(struct task_struct *) task_dead;
    void (*)(struct rq *, struct task_struct *) switched_from;
    void (*)(struct rq *, struct task_struct *) switched_to;
    void (*)(struct rq *, struct task_struct *, int) prio_changed;
    unsigned int (*)(struct rq *, struct task_struct *) get_rr_interval;
    void (*)(struct rq *) update_curr;
    void (*)(struct task_struct *) task_change_group;
    int (*)(struct task_struct *, int) task_is_throttled;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct sched_class {
    int uclamp_enabled;
    void (*)(struct rq *, struct task_struct *, int) enqueue_task;
    void (*)(struct rq *, struct task_struct *, int) dequeue_task;
    void (*)(struct rq *) yield_task;
    bool (*)(struct rq *, struct task_struct *) yield_to_task;
    void (*)(struct rq *, struct task_struct *, int) wakeup_preempt;
    struct task_struct * (*)(struct rq *) pick_next_task;
    void (*)(struct rq *, struct task_struct *) put_prev_task;
    void (*)(struct rq *, struct task_struct *, bool) set_next_task;
    int (*)(struct rq *, struct task_struct *, struct rq_flags *) balance;
    int (*)(struct task_struct *, int, int) select_task_rq;
    struct task_struct * (*)(struct rq *) pick_task;
    void (*)(struct task_struct *, int) migrate_task_rq;
    void (*)(struct rq *, struct task_struct *) task_woken;
    void (*)(struct task_struct *, struct affinity_context *) set_cpus_allowed;
    void (*)(struct rq *) rq_online;
    void (*)(struct rq *) rq_offline;
    struct rq * (*)(struct task_struct *, struct rq *) find_lock_rq;
    void (*)(struct rq *, struct task_struct *, int) task_tick;
    void (*)(struct task_struct *) task_fork;
    void (*)(struct task_struct *) task_dead;
    void (*)(struct rq *, struct task_struct *) switched_from;
    void (*)(struct rq *, struct task_struct *) switched_to;
    void (*)(struct rq *, struct task_struct *, int) prio_changed;
    unsigned int (*)(struct rq *, struct task_struct *) get_rr_interval;
    void (*)(struct rq *) update_curr;
    void (*)(struct task_struct *) task_change_group;
    int (*)(struct task_struct *, int) task_is_throttled;
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
struct sched_class {
    const struct sched_class * next;
    int uclamp_enabled;
    void (*)(struct rq *, struct task_struct *, int) enqueue_task;
    void (*)(struct rq *, struct task_struct *, int) dequeue_task;
    void (*)(struct rq *) yield_task;
    bool (*)(struct rq *, struct task_struct *, bool) yield_to_task;
    void (*)(struct rq *, struct task_struct *, int) check_preempt_curr;
    struct task_struct * (*)(struct rq *, struct task_struct *, struct rq_flags *) pick_next_task;
    void (*)(struct rq *, struct task_struct *) put_prev_task;
    void (*)(struct rq *, struct task_struct *, bool) set_next_task;
    int (*)(struct rq *, struct task_struct *, struct rq_flags *) balance;
    int (*)(struct task_struct *, int, int, int) select_task_rq;
    void (*)(struct task_struct *, int) migrate_task_rq;
    void (*)(struct rq *, struct task_struct *) task_woken;
    void (*)(struct task_struct *, const struct cpumask *) set_cpus_allowed;
    void (*)(struct rq *) rq_online;
    void (*)(struct rq *) rq_offline;
    void (*)(struct rq *, struct task_struct *, int) task_tick;
    void (*)(struct task_struct *) task_fork;
    void (*)(struct task_struct *) task_dead;
    void (*)(struct rq *, struct task_struct *) switched_from;
    void (*)(struct rq *, struct task_struct *) switched_to;
    void (*)(struct rq *, struct task_struct *, int) prio_changed;
    unsigned int (*)(struct rq *, struct task_struct *) get_rr_interval;
    void (*)(struct rq *) update_curr;
    void (*)(struct task_struct *, int) task_change_group;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct sched_class {
    const struct sched_class * next;
    int uclamp_enabled;
    void (*)(struct rq *, struct task_struct *, int) enqueue_task;
    void (*)(struct rq *, struct task_struct *, int) dequeue_task;
    void (*)(struct rq *) yield_task;
    bool (*)(struct rq *, struct task_struct *, bool) yield_to_task;
    void (*)(struct rq *, struct task_struct *, int) check_preempt_curr;
    struct task_struct * (*)(struct rq *, struct task_struct *, struct rq_flags *) pick_next_task;
    void (*)(struct rq *, struct task_struct *) put_prev_task;
    void (*)(struct rq *, struct task_struct *, bool) set_next_task;
    int (*)(struct rq *, struct task_struct *, struct rq_flags *) balance;
    int (*)(struct task_struct *, int, int, int) select_task_rq;
    void (*)(struct task_struct *, int) migrate_task_rq;
    void (*)(struct rq *, struct task_struct *) task_woken;
    void (*)(struct task_struct *, const struct cpumask *) set_cpus_allowed;
    void (*)(struct rq *) rq_online;
    void (*)(struct rq *) rq_offline;
    void (*)(struct rq *, struct task_struct *, int) task_tick;
    void (*)(struct task_struct *) task_fork;
    void (*)(struct task_struct *) task_dead;
    void (*)(struct rq *, struct task_struct *) switched_from;
    void (*)(struct rq *, struct task_struct *) switched_to;
    void (*)(struct rq *, struct task_struct *, int) prio_changed;
    unsigned int (*)(struct rq *, struct task_struct *) get_rr_interval;
    void (*)(struct rq *) update_curr;
    void (*)(struct task_struct *, int) task_change_group;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct sched_class {
    const struct sched_class * next;
    int uclamp_enabled;
    void (*)(struct rq *, struct task_struct *, int) enqueue_task;
    void (*)(struct rq *, struct task_struct *, int) dequeue_task;
    void (*)(struct rq *) yield_task;
    bool (*)(struct rq *, struct task_struct *, bool) yield_to_task;
    void (*)(struct rq *, struct task_struct *, int) check_preempt_curr;
    struct task_struct * (*)(struct rq *, struct task_struct *, struct rq_flags *) pick_next_task;
    void (*)(struct rq *, struct task_struct *) put_prev_task;
    void (*)(struct rq *, struct task_struct *, bool) set_next_task;
    int (*)(struct rq *, struct task_struct *, struct rq_flags *) balance;
    int (*)(struct task_struct *, int, int, int) select_task_rq;
    void (*)(struct task_struct *, int) migrate_task_rq;
    void (*)(struct rq *, struct task_struct *) task_woken;
    void (*)(struct task_struct *, const struct cpumask *) set_cpus_allowed;
    void (*)(struct rq *) rq_online;
    void (*)(struct rq *) rq_offline;
    void (*)(struct rq *, struct task_struct *, int) task_tick;
    void (*)(struct task_struct *) task_fork;
    void (*)(struct task_struct *) task_dead;
    void (*)(struct rq *, struct task_struct *) switched_from;
    void (*)(struct rq *, struct task_struct *) switched_to;
    void (*)(struct rq *, struct task_struct *, int) prio_changed;
    unsigned int (*)(struct rq *, struct task_struct *) get_rr_interval;
    void (*)(struct rq *) update_curr;
    void (*)(struct task_struct *, int) task_change_group;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct sched_class {
    const struct sched_class * next;
    void (*)(struct rq *, struct task_struct *, int) enqueue_task;
    void (*)(struct rq *, struct task_struct *, int) dequeue_task;
    void (*)(struct rq *) yield_task;
    bool (*)(struct rq *, struct task_struct *, bool) yield_to_task;
    void (*)(struct rq *, struct task_struct *, int) check_preempt_curr;
    struct task_struct * (*)(struct rq *, struct task_struct *, struct rq_flags *) pick_next_task;
    void (*)(struct rq *, struct task_struct *) put_prev_task;
    void (*)(struct rq *, struct task_struct *, bool) set_next_task;
    int (*)(struct rq *, struct task_struct *, struct rq_flags *) balance;
    int (*)(struct task_struct *, int, int, int) select_task_rq;
    void (*)(struct task_struct *, int) migrate_task_rq;
    void (*)(struct rq *, struct task_struct *) task_woken;
    void (*)(struct task_struct *, const struct cpumask *) set_cpus_allowed;
    void (*)(struct rq *) rq_online;
    void (*)(struct rq *) rq_offline;
    void (*)(struct rq *, struct task_struct *, int) task_tick;
    void (*)(struct task_struct *) task_fork;
    void (*)(struct task_struct *) task_dead;
    void (*)(struct rq *, struct task_struct *) switched_from;
    void (*)(struct rq *, struct task_struct *) switched_to;
    void (*)(struct rq *, struct task_struct *, int) prio_changed;
    unsigned int (*)(struct rq *, struct task_struct *) get_rr_interval;
    void (*)(struct rq *) update_curr;
    void (*)(struct task_struct *, int) task_change_group;
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
struct sched_class {
    const struct sched_class * next;
    int uclamp_enabled;
    void (*)(struct rq *, struct task_struct *, int) enqueue_task;
    void (*)(struct rq *, struct task_struct *, int) dequeue_task;
    void (*)(struct rq *) yield_task;
    bool (*)(struct rq *, struct task_struct *, bool) yield_to_task;
    void (*)(struct rq *, struct task_struct *, int) check_preempt_curr;
    struct task_struct * (*)(struct rq *, struct task_struct *, struct rq_flags *) pick_next_task;
    void (*)(struct rq *, struct task_struct *) put_prev_task;
    void (*)(struct rq *, struct task_struct *, bool) set_next_task;
    int (*)(struct rq *, struct task_struct *, struct rq_flags *) balance;
    int (*)(struct task_struct *, int, int, int) select_task_rq;
    void (*)(struct task_struct *, int) migrate_task_rq;
    void (*)(struct rq *, struct task_struct *) task_woken;
    void (*)(struct task_struct *, const struct cpumask *) set_cpus_allowed;
    void (*)(struct rq *) rq_online;
    void (*)(struct rq *) rq_offline;
    void (*)(struct rq *, struct task_struct *, int) task_tick;
    void (*)(struct task_struct *) task_fork;
    void (*)(struct task_struct *) task_dead;
    void (*)(struct rq *, struct task_struct *) switched_from;
    void (*)(struct rq *, struct task_struct *) switched_to;
    void (*)(struct rq *, struct task_struct *, int) prio_changed;
    unsigned int (*)(struct rq *, struct task_struct *) get_rr_interval;
    void (*)(struct rq *) update_curr;
    void (*)(struct task_struct *, int) task_change_group;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct sched_class {
    const struct sched_class * next;
    int uclamp_enabled;
    void (*)(struct rq *, struct task_struct *, int) enqueue_task;
    void (*)(struct rq *, struct task_struct *, int) dequeue_task;
    void (*)(struct rq *) yield_task;
    bool (*)(struct rq *, struct task_struct *, bool) yield_to_task;
    void (*)(struct rq *, struct task_struct *, int) check_preempt_curr;
    struct task_struct * (*)(struct rq *, struct task_struct *, struct rq_flags *) pick_next_task;
    void (*)(struct rq *, struct task_struct *) put_prev_task;
    void (*)(struct rq *, struct task_struct *, bool) set_next_task;
    int (*)(struct rq *, struct task_struct *, struct rq_flags *) balance;
    int (*)(struct task_struct *, int, int, int) select_task_rq;
    void (*)(struct task_struct *, int) migrate_task_rq;
    void (*)(struct rq *, struct task_struct *) task_woken;
    void (*)(struct task_struct *, const struct cpumask *) set_cpus_allowed;
    void (*)(struct rq *) rq_online;
    void (*)(struct rq *) rq_offline;
    void (*)(struct rq *, struct task_struct *, int) task_tick;
    void (*)(struct task_struct *) task_fork;
    void (*)(struct task_struct *) task_dead;
    void (*)(struct rq *, struct task_struct *) switched_from;
    void (*)(struct rq *, struct task_struct *) switched_to;
    void (*)(struct rq *, struct task_struct *, int) prio_changed;
    unsigned int (*)(struct rq *, struct task_struct *) get_rr_interval;
    void (*)(struct rq *) update_curr;
    void (*)(struct task_struct *, int) task_change_group;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct sched_class {
    const struct sched_class * next;
    void (*)(struct rq *, struct task_struct *, int) enqueue_task;
    void (*)(struct rq *, struct task_struct *, int) dequeue_task;
    void (*)(struct rq *) yield_task;
    bool (*)(struct rq *, struct task_struct *, bool) yield_to_task;
    void (*)(struct rq *, struct task_struct *, int) check_preempt_curr;
    struct task_struct * (*)(struct rq *, struct task_struct *, struct rq_flags *) pick_next_task;
    void (*)(struct rq *, struct task_struct *) put_prev_task;
    void (*)(struct rq *, struct task_struct *, bool) set_next_task;
    int (*)(struct rq *, struct task_struct *, struct rq_flags *) balance;
    int (*)(struct task_struct *, int, int, int) select_task_rq;
    void (*)(struct task_struct *, int) migrate_task_rq;
    void (*)(struct rq *, struct task_struct *) task_woken;
    void (*)(struct task_struct *, const struct cpumask *) set_cpus_allowed;
    void (*)(struct rq *) rq_online;
    void (*)(struct rq *) rq_offline;
    void (*)(struct rq *, struct task_struct *, int) task_tick;
    void (*)(struct task_struct *) task_fork;
    void (*)(struct task_struct *) task_dead;
    void (*)(struct rq *, struct task_struct *) switched_from;
    void (*)(struct rq *, struct task_struct *) switched_to;
    void (*)(struct rq *, struct task_struct *, int) prio_changed;
    unsigned int (*)(struct rq *, struct task_struct *) get_rr_interval;
    void (*)(struct rq *) update_curr;
    void (*)(struct task_struct *, int) task_change_group;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct sched_class {
    const struct sched_class * next;
    int uclamp_enabled;
    void (*)(struct rq *, struct task_struct *, int) enqueue_task;
    void (*)(struct rq *, struct task_struct *, int) dequeue_task;
    void (*)(struct rq *) yield_task;
    bool (*)(struct rq *, struct task_struct *, bool) yield_to_task;
    void (*)(struct rq *, struct task_struct *, int) check_preempt_curr;
    struct task_struct * (*)(struct rq *, struct task_struct *, struct rq_flags *) pick_next_task;
    void (*)(struct rq *, struct task_struct *) put_prev_task;
    void (*)(struct rq *, struct task_struct *, bool) set_next_task;
    int (*)(struct rq *, struct task_struct *, struct rq_flags *) balance;
    int (*)(struct task_struct *, int, int, int) select_task_rq;
    void (*)(struct task_struct *, int) migrate_task_rq;
    void (*)(struct rq *, struct task_struct *) task_woken;
    void (*)(struct task_struct *, const struct cpumask *) set_cpus_allowed;
    void (*)(struct rq *) rq_online;
    void (*)(struct rq *) rq_offline;
    void (*)(struct rq *, struct task_struct *, int) task_tick;
    void (*)(struct task_struct *) task_fork;
    void (*)(struct task_struct *) task_dead;
    void (*)(struct rq *, struct task_struct *) switched_from;
    void (*)(struct rq *, struct task_struct *) switched_to;
    void (*)(struct rq *, struct task_struct *, int) prio_changed;
    unsigned int (*)(struct rq *, struct task_struct *) get_rr_interval;
    void (*)(struct rq *) update_curr;
    void (*)(struct task_struct *, int) task_change_group;
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
<code>void (*)(struct task_struct *, int) task_change_group</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct task_struct *) task_waking</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct task_struct *) task_move_group</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct task_struct * (*)(struct rq *, struct task_struct *) pick_next_task</code> ➡️ <code>struct task_struct * (*)(struct rq *, struct task_struct *, struct pin_cookie) pick_next_task</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct task_struct * (*)(struct rq *, struct task_struct *, struct pin_cookie) pick_next_task</code> ➡️ <code>struct task_struct * (*)(struct rq *, struct task_struct *, struct rq_flags *) pick_next_task</code>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>void (*)(struct task_struct *) migrate_task_rq</code> ➡️ <code>void (*)(struct task_struct *, int) migrate_task_rq</code>
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
<code>int uclamp_enabled</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct rq *, struct task_struct *, bool) set_next_task</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct rq *, struct task_struct *, struct rq_flags *) balance</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct rq *) set_curr_task</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct task_struct * (*)(struct rq *, struct task_struct *, struct rq_flags *) pick_next_task</code> ➡️ <code>struct task_struct * (*)(struct rq *) pick_next_task</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct rq * (*)(struct task_struct *, struct rq *) find_lock_rq</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct sched_class * next</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool (*)(struct rq *, struct task_struct *, bool) yield_to_task</code> ➡️ <code>bool (*)(struct rq *, struct task_struct *) yield_to_task</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct task_struct *, int, int, int) select_task_rq</code> ➡️ <code>int (*)(struct task_struct *, int, int) select_task_rq</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct task_struct *, const struct cpumask *) set_cpus_allowed</code> ➡️ <code>void (*)(struct task_struct *, const struct cpumask *, u32) set_cpus_allowed</code>
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
<code>struct task_struct * (*)(struct rq *) pick_task</code>
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
<b>Field type changed. </b>
<code>void (*)(struct task_struct *, const struct cpumask *, u32) set_cpus_allowed</code> ➡️ <code>void (*)(struct task_struct *, struct affinity_context *) set_cpus_allowed</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct task_struct *, int) task_change_group</code> ➡️ <code>void (*)(struct task_struct *) task_change_group</code>
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
<code>int (*)(struct task_struct *, int) task_is_throttled</code>
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
<code>void (*)(struct rq *, struct task_struct *, int) wakeup_preempt</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct rq *, struct task_struct *, int) check_preempt_curr</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int uclamp_enabled</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int uclamp_enabled</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
