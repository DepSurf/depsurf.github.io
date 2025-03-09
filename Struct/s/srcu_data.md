# Struct: <code>srcu_data</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct srcu_data {
    long unsigned int[2] srcu_lock_count;
    long unsigned int[2] srcu_unlock_count;
    raw_spinlock_t lock;
    struct rcu_segcblist srcu_cblist;
    long unsigned int srcu_gp_seq_needed;
    long unsigned int srcu_gp_seq_needed_exp;
    bool srcu_cblist_invoking;
    struct delayed_work work;
    struct callback_head srcu_barrier_head;
    struct srcu_node * mynode;
    long unsigned int grpmask;
    int cpu;
    struct srcu_struct * sp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct srcu_data {
    long unsigned int[2] srcu_lock_count;
    long unsigned int[2] srcu_unlock_count;
    raw_spinlock_t lock;
    struct rcu_segcblist srcu_cblist;
    long unsigned int srcu_gp_seq_needed;
    long unsigned int srcu_gp_seq_needed_exp;
    bool srcu_cblist_invoking;
    struct delayed_work work;
    struct callback_head srcu_barrier_head;
    struct srcu_node * mynode;
    long unsigned int grpmask;
    int cpu;
    struct srcu_struct * sp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct srcu_data {
    long unsigned int[2] srcu_lock_count;
    long unsigned int[2] srcu_unlock_count;
    spinlock_t lock;
    struct rcu_segcblist srcu_cblist;
    long unsigned int srcu_gp_seq_needed;
    long unsigned int srcu_gp_seq_needed_exp;
    bool srcu_cblist_invoking;
    struct delayed_work work;
    struct callback_head srcu_barrier_head;
    struct srcu_node * mynode;
    long unsigned int grpmask;
    int cpu;
    struct srcu_struct * sp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct srcu_data {
    long unsigned int[2] srcu_lock_count;
    long unsigned int[2] srcu_unlock_count;
    spinlock_t lock;
    struct rcu_segcblist srcu_cblist;
    long unsigned int srcu_gp_seq_needed;
    long unsigned int srcu_gp_seq_needed_exp;
    bool srcu_cblist_invoking;
    struct delayed_work work;
    struct callback_head srcu_barrier_head;
    struct srcu_node * mynode;
    long unsigned int grpmask;
    int cpu;
    struct srcu_struct * ssp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct srcu_data {
    long unsigned int[2] srcu_lock_count;
    long unsigned int[2] srcu_unlock_count;
    spinlock_t lock;
    struct rcu_segcblist srcu_cblist;
    long unsigned int srcu_gp_seq_needed;
    long unsigned int srcu_gp_seq_needed_exp;
    bool srcu_cblist_invoking;
    struct timer_list delay_work;
    struct work_struct work;
    struct callback_head srcu_barrier_head;
    struct srcu_node * mynode;
    long unsigned int grpmask;
    int cpu;
    struct srcu_struct * ssp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct srcu_data {
    long unsigned int[2] srcu_lock_count;
    long unsigned int[2] srcu_unlock_count;
    spinlock_t lock;
    struct rcu_segcblist srcu_cblist;
    long unsigned int srcu_gp_seq_needed;
    long unsigned int srcu_gp_seq_needed_exp;
    bool srcu_cblist_invoking;
    struct timer_list delay_work;
    struct work_struct work;
    struct callback_head srcu_barrier_head;
    struct srcu_node * mynode;
    long unsigned int grpmask;
    int cpu;
    struct srcu_struct * ssp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct srcu_data {
    long unsigned int[2] srcu_lock_count;
    long unsigned int[2] srcu_unlock_count;
    spinlock_t lock;
    struct rcu_segcblist srcu_cblist;
    long unsigned int srcu_gp_seq_needed;
    long unsigned int srcu_gp_seq_needed_exp;
    bool srcu_cblist_invoking;
    struct timer_list delay_work;
    struct work_struct work;
    struct callback_head srcu_barrier_head;
    struct srcu_node * mynode;
    long unsigned int grpmask;
    int cpu;
    struct srcu_struct * ssp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct srcu_data {
    long unsigned int[2] srcu_lock_count;
    long unsigned int[2] srcu_unlock_count;
    spinlock_t lock;
    struct rcu_segcblist srcu_cblist;
    long unsigned int srcu_gp_seq_needed;
    long unsigned int srcu_gp_seq_needed_exp;
    bool srcu_cblist_invoking;
    struct timer_list delay_work;
    struct work_struct work;
    struct callback_head srcu_barrier_head;
    struct srcu_node * mynode;
    long unsigned int grpmask;
    int cpu;
    struct srcu_struct * ssp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct srcu_data {
    long unsigned int[2] srcu_lock_count;
    long unsigned int[2] srcu_unlock_count;
    spinlock_t lock;
    struct rcu_segcblist srcu_cblist;
    long unsigned int srcu_gp_seq_needed;
    long unsigned int srcu_gp_seq_needed_exp;
    bool srcu_cblist_invoking;
    struct timer_list delay_work;
    struct work_struct work;
    struct callback_head srcu_barrier_head;
    struct srcu_node * mynode;
    long unsigned int grpmask;
    int cpu;
    struct srcu_struct * ssp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct srcu_data {
    long unsigned int[2] srcu_lock_count;
    long unsigned int[2] srcu_unlock_count;
    spinlock_t lock;
    struct rcu_segcblist srcu_cblist;
    long unsigned int srcu_gp_seq_needed;
    long unsigned int srcu_gp_seq_needed_exp;
    bool srcu_cblist_invoking;
    struct timer_list delay_work;
    struct work_struct work;
    struct callback_head srcu_barrier_head;
    struct srcu_node * mynode;
    long unsigned int grpmask;
    int cpu;
    struct srcu_struct * ssp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct srcu_data {
    long unsigned int[2] srcu_lock_count;
    long unsigned int[2] srcu_unlock_count;
    spinlock_t lock;
    struct rcu_segcblist srcu_cblist;
    long unsigned int srcu_gp_seq_needed;
    long unsigned int srcu_gp_seq_needed_exp;
    bool srcu_cblist_invoking;
    struct timer_list delay_work;
    struct work_struct work;
    struct callback_head srcu_barrier_head;
    struct srcu_node * mynode;
    long unsigned int grpmask;
    int cpu;
    struct srcu_struct * ssp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct srcu_data {
    atomic_long_t[2] srcu_lock_count;
    atomic_long_t[2] srcu_unlock_count;
    int srcu_nmi_safety;
    spinlock_t lock;
    struct rcu_segcblist srcu_cblist;
    long unsigned int srcu_gp_seq_needed;
    long unsigned int srcu_gp_seq_needed_exp;
    bool srcu_cblist_invoking;
    struct timer_list delay_work;
    struct work_struct work;
    struct callback_head srcu_barrier_head;
    struct srcu_node * mynode;
    long unsigned int grpmask;
    int cpu;
    struct srcu_struct * ssp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct srcu_data {
    atomic_long_t[2] srcu_lock_count;
    atomic_long_t[2] srcu_unlock_count;
    int srcu_nmi_safety;
    spinlock_t lock;
    struct rcu_segcblist srcu_cblist;
    long unsigned int srcu_gp_seq_needed;
    long unsigned int srcu_gp_seq_needed_exp;
    bool srcu_cblist_invoking;
    struct timer_list delay_work;
    struct work_struct work;
    struct callback_head srcu_barrier_head;
    struct srcu_node * mynode;
    long unsigned int grpmask;
    int cpu;
    struct srcu_struct * ssp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct srcu_data {
    atomic_long_t[2] srcu_lock_count;
    atomic_long_t[2] srcu_unlock_count;
    int srcu_nmi_safety;
    spinlock_t lock;
    struct rcu_segcblist srcu_cblist;
    long unsigned int srcu_gp_seq_needed;
    long unsigned int srcu_gp_seq_needed_exp;
    bool srcu_cblist_invoking;
    struct timer_list delay_work;
    struct work_struct work;
    struct callback_head srcu_barrier_head;
    struct srcu_node * mynode;
    long unsigned int grpmask;
    int cpu;
    struct srcu_struct * ssp;
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
struct srcu_data {
    long unsigned int[2] srcu_lock_count;
    long unsigned int[2] srcu_unlock_count;
    spinlock_t lock;
    struct rcu_segcblist srcu_cblist;
    long unsigned int srcu_gp_seq_needed;
    long unsigned int srcu_gp_seq_needed_exp;
    bool srcu_cblist_invoking;
    struct timer_list delay_work;
    struct work_struct work;
    struct callback_head srcu_barrier_head;
    struct srcu_node * mynode;
    long unsigned int grpmask;
    int cpu;
    struct srcu_struct * ssp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct srcu_data {
    long unsigned int[2] srcu_lock_count;
    long unsigned int[2] srcu_unlock_count;
    spinlock_t lock;
    struct rcu_segcblist srcu_cblist;
    long unsigned int srcu_gp_seq_needed;
    long unsigned int srcu_gp_seq_needed_exp;
    bool srcu_cblist_invoking;
    struct timer_list delay_work;
    struct work_struct work;
    struct callback_head srcu_barrier_head;
    struct srcu_node * mynode;
    long unsigned int grpmask;
    int cpu;
    struct srcu_struct * ssp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct srcu_data {
    long unsigned int[2] srcu_lock_count;
    long unsigned int[2] srcu_unlock_count;
    spinlock_t lock;
    struct rcu_segcblist srcu_cblist;
    long unsigned int srcu_gp_seq_needed;
    long unsigned int srcu_gp_seq_needed_exp;
    bool srcu_cblist_invoking;
    struct timer_list delay_work;
    struct work_struct work;
    struct callback_head srcu_barrier_head;
    struct srcu_node * mynode;
    long unsigned int grpmask;
    int cpu;
    struct srcu_struct * ssp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct srcu_data {
    long unsigned int[2] srcu_lock_count;
    long unsigned int[2] srcu_unlock_count;
    spinlock_t lock;
    struct rcu_segcblist srcu_cblist;
    long unsigned int srcu_gp_seq_needed;
    long unsigned int srcu_gp_seq_needed_exp;
    bool srcu_cblist_invoking;
    struct timer_list delay_work;
    struct work_struct work;
    struct callback_head srcu_barrier_head;
    struct srcu_node * mynode;
    long unsigned int grpmask;
    int cpu;
    struct srcu_struct * ssp;
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
struct srcu_data {
    long unsigned int[2] srcu_lock_count;
    long unsigned int[2] srcu_unlock_count;
    spinlock_t lock;
    struct rcu_segcblist srcu_cblist;
    long unsigned int srcu_gp_seq_needed;
    long unsigned int srcu_gp_seq_needed_exp;
    bool srcu_cblist_invoking;
    struct timer_list delay_work;
    struct work_struct work;
    struct callback_head srcu_barrier_head;
    struct srcu_node * mynode;
    long unsigned int grpmask;
    int cpu;
    struct srcu_struct * ssp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct srcu_data {
    long unsigned int[2] srcu_lock_count;
    long unsigned int[2] srcu_unlock_count;
    spinlock_t lock;
    struct rcu_segcblist srcu_cblist;
    long unsigned int srcu_gp_seq_needed;
    long unsigned int srcu_gp_seq_needed_exp;
    bool srcu_cblist_invoking;
    struct timer_list delay_work;
    struct work_struct work;
    struct callback_head srcu_barrier_head;
    struct srcu_node * mynode;
    long unsigned int grpmask;
    int cpu;
    struct srcu_struct * ssp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct srcu_data {
    long unsigned int[2] srcu_lock_count;
    long unsigned int[2] srcu_unlock_count;
    spinlock_t lock;
    struct rcu_segcblist srcu_cblist;
    long unsigned int srcu_gp_seq_needed;
    long unsigned int srcu_gp_seq_needed_exp;
    bool srcu_cblist_invoking;
    struct timer_list delay_work;
    struct work_struct work;
    struct callback_head srcu_barrier_head;
    struct srcu_node * mynode;
    long unsigned int grpmask;
    int cpu;
    struct srcu_struct * ssp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct srcu_data {
    long unsigned int[2] srcu_lock_count;
    long unsigned int[2] srcu_unlock_count;
    spinlock_t lock;
    struct rcu_segcblist srcu_cblist;
    long unsigned int srcu_gp_seq_needed;
    long unsigned int srcu_gp_seq_needed_exp;
    bool srcu_cblist_invoking;
    struct timer_list delay_work;
    struct work_struct work;
    struct callback_head srcu_barrier_head;
    struct srcu_node * mynode;
    long unsigned int grpmask;
    int cpu;
    struct srcu_struct * ssp;
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct srcu_data {
    long unsigned int[2] srcu_lock_count;
    long unsigned int[2] srcu_unlock_count;
    raw_spinlock_t lock;
    struct rcu_segcblist srcu_cblist;
    long unsigned int srcu_gp_seq_needed;
    long unsigned int srcu_gp_seq_needed_exp;
    bool srcu_cblist_invoking;
    struct delayed_work work;
    struct callback_head srcu_barrier_head;
    struct srcu_node * mynode;
    long unsigned int grpmask;
    int cpu;
    struct srcu_struct * sp;
}
```
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
<code>raw_spinlock_t lock</code> ➡️ <code>spinlock_t lock</code>
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
<code>struct srcu_struct * ssp</code>
</li>
<li>
<b>Field removed. </b>
<code>struct srcu_struct * sp</code>
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
<code>struct timer_list delay_work</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct delayed_work work</code> ➡️ <code>struct work_struct work</code>
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
<code>int srcu_nmi_safety</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int[2] srcu_lock_count</code> ➡️ <code>atomic_long_t[2] srcu_lock_count</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int[2] srcu_unlock_count</code> ➡️ <code>atomic_long_t[2] srcu_unlock_count</code>
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
