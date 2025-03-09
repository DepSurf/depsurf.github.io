# Struct: <code>srcu_usage</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct srcu_usage {
    struct srcu_node * node;
    struct srcu_node *[4] level;
    int srcu_size_state;
    struct mutex srcu_cb_mutex;
    spinlock_t lock;
    struct mutex srcu_gp_mutex;
    long unsigned int srcu_gp_seq;
    long unsigned int srcu_gp_seq_needed;
    long unsigned int srcu_gp_seq_needed_exp;
    long unsigned int srcu_gp_start;
    long unsigned int srcu_last_gp_end;
    long unsigned int srcu_size_jiffies;
    long unsigned int srcu_n_lock_retries;
    long unsigned int srcu_n_exp_nodelay;
    bool sda_is_static;
    long unsigned int srcu_barrier_seq;
    struct mutex srcu_barrier_mutex;
    struct completion srcu_barrier_completion;
    atomic_t srcu_barrier_cpu_cnt;
    long unsigned int reschedule_jiffies;
    long unsigned int reschedule_count;
    struct delayed_work work;
    struct srcu_struct * srcu_ssp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct srcu_usage {
    struct srcu_node * node;
    struct srcu_node *[4] level;
    int srcu_size_state;
    struct mutex srcu_cb_mutex;
    spinlock_t lock;
    struct mutex srcu_gp_mutex;
    long unsigned int srcu_gp_seq;
    long unsigned int srcu_gp_seq_needed;
    long unsigned int srcu_gp_seq_needed_exp;
    long unsigned int srcu_gp_start;
    long unsigned int srcu_last_gp_end;
    long unsigned int srcu_size_jiffies;
    long unsigned int srcu_n_lock_retries;
    long unsigned int srcu_n_exp_nodelay;
    bool sda_is_static;
    long unsigned int srcu_barrier_seq;
    struct mutex srcu_barrier_mutex;
    struct completion srcu_barrier_completion;
    atomic_t srcu_barrier_cpu_cnt;
    long unsigned int reschedule_jiffies;
    long unsigned int reschedule_count;
    struct delayed_work work;
    struct srcu_struct * srcu_ssp;
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
struct srcu_usage {
    struct srcu_node * node;
    struct srcu_node *[4] level;
    int srcu_size_state;
    struct mutex srcu_cb_mutex;
    spinlock_t lock;
    struct mutex srcu_gp_mutex;
    long unsigned int srcu_gp_seq;
    long unsigned int srcu_gp_seq_needed;
    long unsigned int srcu_gp_seq_needed_exp;
    long unsigned int srcu_gp_start;
    long unsigned int srcu_last_gp_end;
    long unsigned int srcu_size_jiffies;
    long unsigned int srcu_n_lock_retries;
    long unsigned int srcu_n_exp_nodelay;
    bool sda_is_static;
    long unsigned int srcu_barrier_seq;
    struct mutex srcu_barrier_mutex;
    struct completion srcu_barrier_completion;
    atomic_t srcu_barrier_cpu_cnt;
    long unsigned int reschedule_jiffies;
    long unsigned int reschedule_count;
    struct delayed_work work;
    struct srcu_struct * srcu_ssp;
}
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
