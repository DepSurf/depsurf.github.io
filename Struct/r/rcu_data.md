# Struct: <code>rcu_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct rcu_data {
    long unsigned int completed;
    long unsigned int gpnum;
    long unsigned int rcu_qs_ctr_snap;
    union rcu_noqs cpu_no_qs;
    bool core_needs_qs;
    bool beenonline;
    bool gpwrap;
    struct rcu_node * mynode;
    long unsigned int grpmask;
    long unsigned int ticks_this_gp;
    struct callback_head * nxtlist;
    struct callback_head * *[4] nxttail;
    long unsigned int[4] nxtcompleted;
    long int qlen_lazy;
    long int qlen;
    long int qlen_last_fqs_check;
    long unsigned int n_cbs_invoked;
    long unsigned int n_nocbs_invoked;
    long unsigned int n_cbs_orphaned;
    long unsigned int n_cbs_adopted;
    long unsigned int n_force_qs_snap;
    long int blimit;
    struct rcu_dynticks * dynticks;
    int dynticks_snap;
    long unsigned int dynticks_fqs;
    long unsigned int offline_fqs;
    long unsigned int cond_resched_completed;
    long unsigned int n_rcu_pending;
    long unsigned int n_rp_core_needs_qs;
    long unsigned int n_rp_report_qs;
    long unsigned int n_rp_cb_ready;
    long unsigned int n_rp_cpu_needs_gp;
    long unsigned int n_rp_gp_completed;
    long unsigned int n_rp_gp_started;
    long unsigned int n_rp_nocb_defer_wakeup;
    long unsigned int n_rp_need_nothing;
    struct callback_head barrier_head;
    struct mutex exp_funnel_mutex;
    unsigned int softirq_snap;
    int cpu;
    struct rcu_state * rsp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct rcu_data {
    long unsigned int completed;
    long unsigned int gpnum;
    long unsigned int rcu_qs_ctr_snap;
    union rcu_noqs cpu_no_qs;
    bool core_needs_qs;
    bool beenonline;
    bool gpwrap;
    struct rcu_node * mynode;
    long unsigned int grpmask;
    long unsigned int ticks_this_gp;
    struct callback_head * nxtlist;
    struct callback_head * *[4] nxttail;
    long unsigned int[4] nxtcompleted;
    long int qlen_lazy;
    long int qlen;
    long int qlen_last_fqs_check;
    long unsigned int n_cbs_invoked;
    long unsigned int n_nocbs_invoked;
    long unsigned int n_cbs_orphaned;
    long unsigned int n_cbs_adopted;
    long unsigned int n_force_qs_snap;
    long int blimit;
    struct rcu_dynticks * dynticks;
    int dynticks_snap;
    long unsigned int dynticks_fqs;
    long unsigned int offline_fqs;
    long unsigned int cond_resched_completed;
    long unsigned int n_rcu_pending;
    long unsigned int n_rp_core_needs_qs;
    long unsigned int n_rp_report_qs;
    long unsigned int n_rp_cb_ready;
    long unsigned int n_rp_cpu_needs_gp;
    long unsigned int n_rp_gp_completed;
    long unsigned int n_rp_gp_started;
    long unsigned int n_rp_nocb_defer_wakeup;
    long unsigned int n_rp_need_nothing;
    struct callback_head barrier_head;
    atomic_long_t exp_workdone1;
    atomic_long_t exp_workdone2;
    atomic_long_t exp_workdone3;
    unsigned int softirq_snap;
    int cpu;
    struct rcu_state * rsp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct rcu_data {
    long unsigned int completed;
    long unsigned int gpnum;
    long unsigned int rcu_qs_ctr_snap;
    union rcu_noqs cpu_no_qs;
    bool core_needs_qs;
    bool beenonline;
    bool gpwrap;
    struct rcu_node * mynode;
    long unsigned int grpmask;
    long unsigned int ticks_this_gp;
    struct callback_head * nxtlist;
    struct callback_head * *[4] nxttail;
    long unsigned int[4] nxtcompleted;
    long int qlen_lazy;
    long int qlen;
    long int qlen_last_fqs_check;
    long unsigned int n_cbs_invoked;
    long unsigned int n_nocbs_invoked;
    long unsigned int n_cbs_orphaned;
    long unsigned int n_cbs_adopted;
    long unsigned int n_force_qs_snap;
    long int blimit;
    struct rcu_dynticks * dynticks;
    int dynticks_snap;
    long unsigned int dynticks_fqs;
    long unsigned int offline_fqs;
    long unsigned int cond_resched_completed;
    long unsigned int n_rcu_pending;
    long unsigned int n_rp_core_needs_qs;
    long unsigned int n_rp_report_qs;
    long unsigned int n_rp_cb_ready;
    long unsigned int n_rp_cpu_needs_gp;
    long unsigned int n_rp_gp_completed;
    long unsigned int n_rp_gp_started;
    long unsigned int n_rp_nocb_defer_wakeup;
    long unsigned int n_rp_need_nothing;
    struct callback_head barrier_head;
    atomic_long_t exp_workdone0;
    atomic_long_t exp_workdone1;
    atomic_long_t exp_workdone2;
    atomic_long_t exp_workdone3;
    int exp_dynticks_snap;
    unsigned int softirq_snap;
    int cpu;
    struct rcu_state * rsp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct rcu_data {
    long unsigned int completed;
    long unsigned int gpnum;
    long unsigned int rcu_qs_ctr_snap;
    union rcu_noqs cpu_no_qs;
    bool core_needs_qs;
    bool beenonline;
    bool gpwrap;
    struct rcu_node * mynode;
    long unsigned int grpmask;
    long unsigned int ticks_this_gp;
    struct rcu_segcblist cblist;
    long int qlen_last_fqs_check;
    long unsigned int n_cbs_invoked;
    long unsigned int n_nocbs_invoked;
    long unsigned int n_cbs_orphaned;
    long unsigned int n_cbs_adopted;
    long unsigned int n_force_qs_snap;
    long int blimit;
    struct rcu_dynticks * dynticks;
    int dynticks_snap;
    long unsigned int dynticks_fqs;
    long unsigned int offline_fqs;
    long unsigned int cond_resched_completed;
    long unsigned int n_rcu_pending;
    long unsigned int n_rp_core_needs_qs;
    long unsigned int n_rp_report_qs;
    long unsigned int n_rp_cb_ready;
    long unsigned int n_rp_cpu_needs_gp;
    long unsigned int n_rp_gp_completed;
    long unsigned int n_rp_gp_started;
    long unsigned int n_rp_nocb_defer_wakeup;
    long unsigned int n_rp_need_nothing;
    struct callback_head barrier_head;
    atomic_long_t exp_workdone0;
    atomic_long_t exp_workdone1;
    atomic_long_t exp_workdone2;
    atomic_long_t exp_workdone3;
    int exp_dynticks_snap;
    unsigned int softirq_snap;
    int cpu;
    struct rcu_state * rsp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct rcu_data {
    long unsigned int completed;
    long unsigned int gpnum;
    long unsigned int rcu_qs_ctr_snap;
    union rcu_noqs cpu_no_qs;
    bool core_needs_qs;
    bool beenonline;
    bool gpwrap;
    struct rcu_node * mynode;
    long unsigned int grpmask;
    long unsigned int ticks_this_gp;
    struct rcu_segcblist cblist;
    long int qlen_last_fqs_check;
    long unsigned int n_cbs_invoked;
    long unsigned int n_nocbs_invoked;
    long unsigned int n_force_qs_snap;
    long int blimit;
    struct rcu_dynticks * dynticks;
    int dynticks_snap;
    long unsigned int dynticks_fqs;
    long unsigned int offline_fqs;
    long unsigned int cond_resched_completed;
    long unsigned int n_rcu_pending;
    long unsigned int n_rp_core_needs_qs;
    long unsigned int n_rp_report_qs;
    long unsigned int n_rp_cb_ready;
    long unsigned int n_rp_cpu_needs_gp;
    long unsigned int n_rp_gp_completed;
    long unsigned int n_rp_gp_started;
    long unsigned int n_rp_nocb_defer_wakeup;
    long unsigned int n_rp_need_nothing;
    struct callback_head barrier_head;
    atomic_long_t exp_workdone0;
    atomic_long_t exp_workdone1;
    atomic_long_t exp_workdone2;
    atomic_long_t exp_workdone3;
    int exp_dynticks_snap;
    unsigned int softirq_snap;
    struct irq_work rcu_iw;
    bool rcu_iw_pending;
    long unsigned int rcu_iw_gpnum;
    int cpu;
    struct rcu_state * rsp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct rcu_data {
    long unsigned int completed;
    long unsigned int gpnum;
    long unsigned int rcu_qs_ctr_snap;
    union rcu_noqs cpu_no_qs;
    bool core_needs_qs;
    bool beenonline;
    bool gpwrap;
    struct rcu_node * mynode;
    long unsigned int grpmask;
    long unsigned int ticks_this_gp;
    struct rcu_segcblist cblist;
    long int qlen_last_fqs_check;
    long unsigned int n_force_qs_snap;
    long int blimit;
    struct rcu_dynticks * dynticks;
    int dynticks_snap;
    long unsigned int dynticks_fqs;
    long unsigned int offline_fqs;
    long unsigned int cond_resched_completed;
    struct callback_head barrier_head;
    int exp_dynticks_snap;
    unsigned int softirq_snap;
    struct irq_work rcu_iw;
    bool rcu_iw_pending;
    long unsigned int rcu_iw_gpnum;
    int cpu;
    struct rcu_state * rsp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct rcu_data {
    long unsigned int gp_seq;
    long unsigned int gp_seq_needed;
    union rcu_noqs cpu_no_qs;
    bool core_needs_qs;
    bool beenonline;
    bool gpwrap;
    bool deferred_qs;
    struct rcu_node * mynode;
    long unsigned int grpmask;
    long unsigned int ticks_this_gp;
    struct rcu_segcblist cblist;
    long int qlen_last_fqs_check;
    long unsigned int n_force_qs_snap;
    long int blimit;
    int dynticks_snap;
    long int dynticks_nesting;
    long int dynticks_nmi_nesting;
    atomic_t dynticks;
    bool rcu_need_heavy_qs;
    bool rcu_urgent_qs;
    struct callback_head barrier_head;
    int exp_dynticks_snap;
    unsigned int softirq_snap;
    struct irq_work rcu_iw;
    bool rcu_iw_pending;
    long unsigned int rcu_iw_gp_seq;
    long unsigned int rcu_ofl_gp_seq;
    short int rcu_ofl_gp_flags;
    long unsigned int rcu_onl_gp_seq;
    short int rcu_onl_gp_flags;
    long unsigned int last_fqs_resched;
    int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct rcu_data {
    long unsigned int gp_seq;
    long unsigned int gp_seq_needed;
    union rcu_noqs cpu_no_qs;
    bool core_needs_qs;
    bool beenonline;
    bool gpwrap;
    bool exp_deferred_qs;
    struct rcu_node * mynode;
    long unsigned int grpmask;
    long unsigned int ticks_this_gp;
    struct irq_work defer_qs_iw;
    bool defer_qs_iw_pending;
    struct rcu_segcblist cblist;
    long int qlen_last_fqs_check;
    long unsigned int n_force_qs_snap;
    long int blimit;
    int dynticks_snap;
    long int dynticks_nesting;
    long int dynticks_nmi_nesting;
    atomic_t dynticks;
    bool rcu_need_heavy_qs;
    bool rcu_urgent_qs;
    struct callback_head barrier_head;
    int exp_dynticks_snap;
    struct task_struct * rcu_cpu_kthread_task;
    unsigned int rcu_cpu_kthread_status;
    char rcu_cpu_has_work;
    unsigned int softirq_snap;
    struct irq_work rcu_iw;
    bool rcu_iw_pending;
    long unsigned int rcu_iw_gp_seq;
    long unsigned int rcu_ofl_gp_seq;
    short int rcu_ofl_gp_flags;
    long unsigned int rcu_onl_gp_seq;
    short int rcu_onl_gp_flags;
    long unsigned int last_fqs_resched;
    int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct rcu_data {
    long unsigned int gp_seq;
    long unsigned int gp_seq_needed;
    union rcu_noqs cpu_no_qs;
    bool core_needs_qs;
    bool beenonline;
    bool gpwrap;
    bool exp_deferred_qs;
    struct rcu_node * mynode;
    long unsigned int grpmask;
    long unsigned int ticks_this_gp;
    struct irq_work defer_qs_iw;
    bool defer_qs_iw_pending;
    struct rcu_segcblist cblist;
    long int qlen_last_fqs_check;
    long unsigned int n_force_qs_snap;
    long int blimit;
    int dynticks_snap;
    long int dynticks_nesting;
    long int dynticks_nmi_nesting;
    atomic_t dynticks;
    bool rcu_need_heavy_qs;
    bool rcu_urgent_qs;
    struct callback_head barrier_head;
    int exp_dynticks_snap;
    struct task_struct * rcu_cpu_kthread_task;
    unsigned int rcu_cpu_kthread_status;
    char rcu_cpu_has_work;
    unsigned int softirq_snap;
    struct irq_work rcu_iw;
    bool rcu_iw_pending;
    long unsigned int rcu_iw_gp_seq;
    long unsigned int rcu_ofl_gp_seq;
    short int rcu_ofl_gp_flags;
    long unsigned int rcu_onl_gp_seq;
    short int rcu_onl_gp_flags;
    long unsigned int last_fqs_resched;
    int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct rcu_data {
    long unsigned int gp_seq;
    long unsigned int gp_seq_needed;
    union rcu_noqs cpu_no_qs;
    bool core_needs_qs;
    bool beenonline;
    bool gpwrap;
    bool exp_deferred_qs;
    struct rcu_node * mynode;
    long unsigned int grpmask;
    long unsigned int ticks_this_gp;
    struct irq_work defer_qs_iw;
    bool defer_qs_iw_pending;
    struct rcu_segcblist cblist;
    long int qlen_last_fqs_check;
    long unsigned int n_force_qs_snap;
    long int blimit;
    int dynticks_snap;
    long int dynticks_nesting;
    long int dynticks_nmi_nesting;
    atomic_t dynticks;
    bool rcu_need_heavy_qs;
    bool rcu_urgent_qs;
    bool rcu_forced_tick;
    bool rcu_forced_tick_exp;
    struct callback_head barrier_head;
    int exp_dynticks_snap;
    struct task_struct * rcu_cpu_kthread_task;
    unsigned int rcu_cpu_kthread_status;
    char rcu_cpu_has_work;
    unsigned int softirq_snap;
    struct irq_work rcu_iw;
    bool rcu_iw_pending;
    long unsigned int rcu_iw_gp_seq;
    long unsigned int rcu_ofl_gp_seq;
    short int rcu_ofl_gp_flags;
    long unsigned int rcu_onl_gp_seq;
    short int rcu_onl_gp_flags;
    long unsigned int last_fqs_resched;
    int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct rcu_data {
    long unsigned int gp_seq;
    long unsigned int gp_seq_needed;
    union rcu_noqs cpu_no_qs;
    bool core_needs_qs;
    bool beenonline;
    bool gpwrap;
    bool exp_deferred_qs;
    bool cpu_started;
    struct rcu_node * mynode;
    long unsigned int grpmask;
    long unsigned int ticks_this_gp;
    struct irq_work defer_qs_iw;
    bool defer_qs_iw_pending;
    struct work_struct strict_work;
    struct rcu_segcblist cblist;
    long int qlen_last_fqs_check;
    long unsigned int n_cbs_invoked;
    long unsigned int n_force_qs_snap;
    long int blimit;
    int dynticks_snap;
    long int dynticks_nesting;
    long int dynticks_nmi_nesting;
    atomic_t dynticks;
    bool rcu_need_heavy_qs;
    bool rcu_urgent_qs;
    bool rcu_forced_tick;
    bool rcu_forced_tick_exp;
    struct callback_head barrier_head;
    int exp_dynticks_snap;
    struct task_struct * rcu_cpu_kthread_task;
    unsigned int rcu_cpu_kthread_status;
    char rcu_cpu_has_work;
    unsigned int softirq_snap;
    struct irq_work rcu_iw;
    bool rcu_iw_pending;
    long unsigned int rcu_iw_gp_seq;
    long unsigned int rcu_ofl_gp_seq;
    short int rcu_ofl_gp_flags;
    long unsigned int rcu_onl_gp_seq;
    short int rcu_onl_gp_flags;
    long unsigned int last_fqs_resched;
    int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct rcu_data {
    long unsigned int gp_seq;
    long unsigned int gp_seq_needed;
    union rcu_noqs cpu_no_qs;
    bool core_needs_qs;
    bool beenonline;
    bool gpwrap;
    bool exp_deferred_qs;
    bool cpu_started;
    struct rcu_node * mynode;
    long unsigned int grpmask;
    long unsigned int ticks_this_gp;
    struct irq_work defer_qs_iw;
    bool defer_qs_iw_pending;
    struct work_struct strict_work;
    struct rcu_segcblist cblist;
    long int qlen_last_fqs_check;
    long unsigned int n_cbs_invoked;
    long unsigned int n_force_qs_snap;
    long int blimit;
    int dynticks_snap;
    long int dynticks_nesting;
    long int dynticks_nmi_nesting;
    atomic_t dynticks;
    bool rcu_need_heavy_qs;
    bool rcu_urgent_qs;
    bool rcu_forced_tick;
    bool rcu_forced_tick_exp;
    struct callback_head barrier_head;
    int exp_dynticks_snap;
    struct task_struct * rcu_cpu_kthread_task;
    unsigned int rcu_cpu_kthread_status;
    char rcu_cpu_has_work;
    unsigned int softirq_snap;
    struct irq_work rcu_iw;
    bool rcu_iw_pending;
    long unsigned int rcu_iw_gp_seq;
    long unsigned int rcu_ofl_gp_seq;
    short int rcu_ofl_gp_flags;
    long unsigned int rcu_onl_gp_seq;
    short int rcu_onl_gp_flags;
    long unsigned int last_fqs_resched;
    int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct rcu_data {
    long unsigned int gp_seq;
    long unsigned int gp_seq_needed;
    union rcu_noqs cpu_no_qs;
    bool core_needs_qs;
    bool beenonline;
    bool gpwrap;
    bool exp_deferred_qs;
    bool cpu_started;
    struct rcu_node * mynode;
    long unsigned int grpmask;
    long unsigned int ticks_this_gp;
    struct irq_work defer_qs_iw;
    bool defer_qs_iw_pending;
    struct work_struct strict_work;
    struct rcu_segcblist cblist;
    long int qlen_last_fqs_check;
    long unsigned int n_cbs_invoked;
    long unsigned int n_force_qs_snap;
    long int blimit;
    int dynticks_snap;
    long int dynticks_nesting;
    long int dynticks_nmi_nesting;
    atomic_t dynticks;
    bool rcu_need_heavy_qs;
    bool rcu_urgent_qs;
    bool rcu_forced_tick;
    bool rcu_forced_tick_exp;
    struct callback_head barrier_head;
    int exp_dynticks_snap;
    struct task_struct * rcu_cpu_kthread_task;
    unsigned int rcu_cpu_kthread_status;
    char rcu_cpu_has_work;
    unsigned int softirq_snap;
    struct irq_work rcu_iw;
    bool rcu_iw_pending;
    long unsigned int rcu_iw_gp_seq;
    long unsigned int rcu_ofl_gp_seq;
    short int rcu_ofl_gp_flags;
    long unsigned int rcu_onl_gp_seq;
    short int rcu_onl_gp_flags;
    long unsigned int last_fqs_resched;
    int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct rcu_data {
    long unsigned int gp_seq;
    long unsigned int gp_seq_needed;
    union rcu_noqs cpu_no_qs;
    bool core_needs_qs;
    bool beenonline;
    bool gpwrap;
    bool cpu_started;
    struct rcu_node * mynode;
    long unsigned int grpmask;
    long unsigned int ticks_this_gp;
    struct irq_work defer_qs_iw;
    bool defer_qs_iw_pending;
    struct work_struct strict_work;
    struct rcu_segcblist cblist;
    long int qlen_last_fqs_check;
    long unsigned int n_cbs_invoked;
    long unsigned int n_force_qs_snap;
    long int blimit;
    int dynticks_snap;
    long int dynticks_nesting;
    long int dynticks_nmi_nesting;
    atomic_t dynticks;
    bool rcu_need_heavy_qs;
    bool rcu_urgent_qs;
    bool rcu_forced_tick;
    bool rcu_forced_tick_exp;
    long unsigned int barrier_seq_snap;
    struct callback_head barrier_head;
    int exp_dynticks_snap;
    struct task_struct * rcu_cpu_kthread_task;
    unsigned int rcu_cpu_kthread_status;
    char rcu_cpu_has_work;
    long unsigned int rcuc_activity;
    unsigned int softirq_snap;
    struct irq_work rcu_iw;
    bool rcu_iw_pending;
    long unsigned int rcu_iw_gp_seq;
    long unsigned int rcu_ofl_gp_seq;
    short int rcu_ofl_gp_flags;
    long unsigned int rcu_onl_gp_seq;
    short int rcu_onl_gp_flags;
    long unsigned int last_fqs_resched;
    long unsigned int last_sched_clock;
    int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct rcu_data {
    long unsigned int gp_seq;
    long unsigned int gp_seq_needed;
    union rcu_noqs cpu_no_qs;
    bool core_needs_qs;
    bool beenonline;
    bool gpwrap;
    bool cpu_started;
    struct rcu_node * mynode;
    long unsigned int grpmask;
    long unsigned int ticks_this_gp;
    struct irq_work defer_qs_iw;
    bool defer_qs_iw_pending;
    struct work_struct strict_work;
    struct rcu_segcblist cblist;
    long int qlen_last_fqs_check;
    long unsigned int n_cbs_invoked;
    long unsigned int n_force_qs_snap;
    long int blimit;
    int dynticks_snap;
    bool rcu_need_heavy_qs;
    bool rcu_urgent_qs;
    bool rcu_forced_tick;
    bool rcu_forced_tick_exp;
    long unsigned int barrier_seq_snap;
    struct callback_head barrier_head;
    int exp_dynticks_snap;
    struct task_struct * rcu_cpu_kthread_task;
    unsigned int rcu_cpu_kthread_status;
    char rcu_cpu_has_work;
    long unsigned int rcuc_activity;
    unsigned int softirq_snap;
    struct irq_work rcu_iw;
    bool rcu_iw_pending;
    long unsigned int rcu_iw_gp_seq;
    long unsigned int rcu_ofl_gp_seq;
    short int rcu_ofl_gp_flags;
    long unsigned int rcu_onl_gp_seq;
    short int rcu_onl_gp_flags;
    long unsigned int last_fqs_resched;
    long unsigned int last_sched_clock;
    long int lazy_len;
    int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct rcu_data {
    long unsigned int gp_seq;
    long unsigned int gp_seq_needed;
    union rcu_noqs cpu_no_qs;
    bool core_needs_qs;
    bool beenonline;
    bool gpwrap;
    bool cpu_started;
    struct rcu_node * mynode;
    long unsigned int grpmask;
    long unsigned int ticks_this_gp;
    struct irq_work defer_qs_iw;
    bool defer_qs_iw_pending;
    struct work_struct strict_work;
    struct rcu_segcblist cblist;
    long int qlen_last_fqs_check;
    long unsigned int n_cbs_invoked;
    long unsigned int n_force_qs_snap;
    long int blimit;
    int dynticks_snap;
    bool rcu_need_heavy_qs;
    bool rcu_urgent_qs;
    bool rcu_forced_tick;
    bool rcu_forced_tick_exp;
    long unsigned int barrier_seq_snap;
    struct callback_head barrier_head;
    int exp_dynticks_snap;
    struct task_struct * rcu_cpu_kthread_task;
    unsigned int rcu_cpu_kthread_status;
    char rcu_cpu_has_work;
    long unsigned int rcuc_activity;
    unsigned int softirq_snap;
    struct irq_work rcu_iw;
    bool rcu_iw_pending;
    long unsigned int rcu_iw_gp_seq;
    long unsigned int rcu_ofl_gp_seq;
    short int rcu_ofl_gp_flags;
    long unsigned int rcu_onl_gp_seq;
    short int rcu_onl_gp_flags;
    long unsigned int last_fqs_resched;
    long unsigned int last_sched_clock;
    struct rcu_snap_record snap_record;
    long int lazy_len;
    int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct rcu_data {
    long unsigned int gp_seq;
    long unsigned int gp_seq_needed;
    union rcu_noqs cpu_no_qs;
    bool core_needs_qs;
    bool beenonline;
    bool gpwrap;
    bool cpu_started;
    struct rcu_node * mynode;
    long unsigned int grpmask;
    long unsigned int ticks_this_gp;
    struct irq_work defer_qs_iw;
    bool defer_qs_iw_pending;
    struct work_struct strict_work;
    struct rcu_segcblist cblist;
    long int qlen_last_fqs_check;
    long unsigned int n_cbs_invoked;
    long unsigned int n_force_qs_snap;
    long int blimit;
    int dynticks_snap;
    bool rcu_need_heavy_qs;
    bool rcu_urgent_qs;
    bool rcu_forced_tick;
    bool rcu_forced_tick_exp;
    long unsigned int barrier_seq_snap;
    struct callback_head barrier_head;
    int exp_dynticks_snap;
    struct swait_queue_head nocb_cb_wq;
    struct swait_queue_head nocb_state_wq;
    struct task_struct * nocb_gp_kthread;
    raw_spinlock_t nocb_lock;
    atomic_t nocb_lock_contended;
    int nocb_defer_wakeup;
    struct timer_list nocb_timer;
    long unsigned int nocb_gp_adv_time;
    struct mutex nocb_gp_kthread_mutex;
    raw_spinlock_t nocb_bypass_lock;
    struct rcu_cblist nocb_bypass;
    long unsigned int nocb_bypass_first;
    long unsigned int nocb_nobypass_last;
    int nocb_nobypass_count;
    raw_spinlock_t nocb_gp_lock;
    u8 nocb_gp_sleep;
    u8 nocb_gp_bypass;
    u8 nocb_gp_gp;
    long unsigned int nocb_gp_seq;
    long unsigned int nocb_gp_loops;
    struct swait_queue_head nocb_gp_wq;
    bool nocb_cb_sleep;
    struct task_struct * nocb_cb_kthread;
    struct list_head nocb_head_rdp;
    struct list_head nocb_entry_rdp;
    struct rcu_data * nocb_toggling_rdp;
    struct rcu_data * nocb_gp_rdp;
    struct task_struct * rcu_cpu_kthread_task;
    unsigned int rcu_cpu_kthread_status;
    char rcu_cpu_has_work;
    long unsigned int rcuc_activity;
    unsigned int softirq_snap;
    struct irq_work rcu_iw;
    bool rcu_iw_pending;
    long unsigned int rcu_iw_gp_seq;
    long unsigned int rcu_ofl_gp_seq;
    short int rcu_ofl_gp_flags;
    long unsigned int rcu_onl_gp_seq;
    short int rcu_onl_gp_flags;
    long unsigned int last_fqs_resched;
    long unsigned int last_sched_clock;
    struct rcu_snap_record snap_record;
    long int lazy_len;
    int cpu;
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
struct rcu_data {
    long unsigned int gp_seq;
    long unsigned int gp_seq_needed;
    union rcu_noqs cpu_no_qs;
    bool core_needs_qs;
    bool beenonline;
    bool gpwrap;
    bool exp_deferred_qs;
    struct rcu_node * mynode;
    long unsigned int grpmask;
    long unsigned int ticks_this_gp;
    struct irq_work defer_qs_iw;
    bool defer_qs_iw_pending;
    struct rcu_segcblist cblist;
    long int qlen_last_fqs_check;
    long unsigned int n_force_qs_snap;
    long int blimit;
    int dynticks_snap;
    long int dynticks_nesting;
    long int dynticks_nmi_nesting;
    atomic_t dynticks;
    bool rcu_need_heavy_qs;
    bool rcu_urgent_qs;
    struct callback_head barrier_head;
    int exp_dynticks_snap;
    struct task_struct * rcu_cpu_kthread_task;
    unsigned int rcu_cpu_kthread_status;
    char rcu_cpu_has_work;
    unsigned int softirq_snap;
    struct irq_work rcu_iw;
    bool rcu_iw_pending;
    long unsigned int rcu_iw_gp_seq;
    long unsigned int rcu_ofl_gp_seq;
    short int rcu_ofl_gp_flags;
    long unsigned int rcu_onl_gp_seq;
    short int rcu_onl_gp_flags;
    long unsigned int last_fqs_resched;
    int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct rcu_data {
    long unsigned int gp_seq;
    long unsigned int gp_seq_needed;
    union rcu_noqs cpu_no_qs;
    bool core_needs_qs;
    bool beenonline;
    bool gpwrap;
    bool exp_deferred_qs;
    struct rcu_node * mynode;
    long unsigned int grpmask;
    long unsigned int ticks_this_gp;
    struct irq_work defer_qs_iw;
    bool defer_qs_iw_pending;
    struct rcu_segcblist cblist;
    long int qlen_last_fqs_check;
    long unsigned int n_force_qs_snap;
    long int blimit;
    int dynticks_snap;
    long int dynticks_nesting;
    long int dynticks_nmi_nesting;
    atomic_t dynticks;
    bool rcu_need_heavy_qs;
    bool rcu_urgent_qs;
    struct callback_head barrier_head;
    int exp_dynticks_snap;
    struct task_struct * rcu_cpu_kthread_task;
    unsigned int rcu_cpu_kthread_status;
    char rcu_cpu_has_work;
    unsigned int softirq_snap;
    struct irq_work rcu_iw;
    bool rcu_iw_pending;
    long unsigned int rcu_iw_gp_seq;
    long unsigned int rcu_ofl_gp_seq;
    short int rcu_ofl_gp_flags;
    long unsigned int rcu_onl_gp_seq;
    short int rcu_onl_gp_flags;
    long unsigned int last_fqs_resched;
    int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct rcu_data {
    long unsigned int gp_seq;
    long unsigned int gp_seq_needed;
    union rcu_noqs cpu_no_qs;
    bool core_needs_qs;
    bool beenonline;
    bool gpwrap;
    bool exp_deferred_qs;
    struct rcu_node * mynode;
    long unsigned int grpmask;
    long unsigned int ticks_this_gp;
    struct irq_work defer_qs_iw;
    bool defer_qs_iw_pending;
    struct rcu_segcblist cblist;
    long int qlen_last_fqs_check;
    long unsigned int n_force_qs_snap;
    long int blimit;
    int dynticks_snap;
    long int dynticks_nesting;
    long int dynticks_nmi_nesting;
    atomic_t dynticks;
    bool rcu_need_heavy_qs;
    bool rcu_urgent_qs;
    struct callback_head barrier_head;
    int exp_dynticks_snap;
    struct task_struct * rcu_cpu_kthread_task;
    unsigned int rcu_cpu_kthread_status;
    char rcu_cpu_has_work;
    unsigned int softirq_snap;
    struct irq_work rcu_iw;
    bool rcu_iw_pending;
    long unsigned int rcu_iw_gp_seq;
    long unsigned int rcu_ofl_gp_seq;
    short int rcu_ofl_gp_flags;
    long unsigned int rcu_onl_gp_seq;
    short int rcu_onl_gp_flags;
    long unsigned int last_fqs_resched;
    int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct rcu_data {
    long unsigned int gp_seq;
    long unsigned int gp_seq_needed;
    union rcu_noqs cpu_no_qs;
    bool core_needs_qs;
    bool beenonline;
    bool gpwrap;
    bool exp_deferred_qs;
    struct rcu_node * mynode;
    long unsigned int grpmask;
    long unsigned int ticks_this_gp;
    struct irq_work defer_qs_iw;
    bool defer_qs_iw_pending;
    struct rcu_segcblist cblist;
    long int qlen_last_fqs_check;
    long unsigned int n_force_qs_snap;
    long int blimit;
    int dynticks_snap;
    long int dynticks_nesting;
    long int dynticks_nmi_nesting;
    atomic_t dynticks;
    bool rcu_need_heavy_qs;
    bool rcu_urgent_qs;
    struct callback_head barrier_head;
    int exp_dynticks_snap;
    struct task_struct * rcu_cpu_kthread_task;
    unsigned int rcu_cpu_kthread_status;
    char rcu_cpu_has_work;
    unsigned int softirq_snap;
    struct irq_work rcu_iw;
    bool rcu_iw_pending;
    long unsigned int rcu_iw_gp_seq;
    long unsigned int rcu_ofl_gp_seq;
    short int rcu_ofl_gp_flags;
    long unsigned int rcu_onl_gp_seq;
    short int rcu_onl_gp_flags;
    long unsigned int last_fqs_resched;
    int cpu;
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
struct rcu_data {
    long unsigned int gp_seq;
    long unsigned int gp_seq_needed;
    union rcu_noqs cpu_no_qs;
    bool core_needs_qs;
    bool beenonline;
    bool gpwrap;
    bool exp_deferred_qs;
    struct rcu_node * mynode;
    long unsigned int grpmask;
    long unsigned int ticks_this_gp;
    struct irq_work defer_qs_iw;
    bool defer_qs_iw_pending;
    struct rcu_segcblist cblist;
    long int qlen_last_fqs_check;
    long unsigned int n_force_qs_snap;
    long int blimit;
    int dynticks_snap;
    long int dynticks_nesting;
    long int dynticks_nmi_nesting;
    atomic_t dynticks;
    bool rcu_need_heavy_qs;
    bool rcu_urgent_qs;
    struct callback_head barrier_head;
    int exp_dynticks_snap;
    struct task_struct * rcu_cpu_kthread_task;
    unsigned int rcu_cpu_kthread_status;
    char rcu_cpu_has_work;
    unsigned int softirq_snap;
    struct irq_work rcu_iw;
    bool rcu_iw_pending;
    long unsigned int rcu_iw_gp_seq;
    long unsigned int rcu_ofl_gp_seq;
    short int rcu_ofl_gp_flags;
    long unsigned int rcu_onl_gp_seq;
    short int rcu_onl_gp_flags;
    long unsigned int last_fqs_resched;
    int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct rcu_data {
    long unsigned int gp_seq;
    long unsigned int gp_seq_needed;
    union rcu_noqs cpu_no_qs;
    bool core_needs_qs;
    bool beenonline;
    bool gpwrap;
    bool exp_deferred_qs;
    struct rcu_node * mynode;
    long unsigned int grpmask;
    long unsigned int ticks_this_gp;
    struct irq_work defer_qs_iw;
    bool defer_qs_iw_pending;
    struct rcu_segcblist cblist;
    long int qlen_last_fqs_check;
    long unsigned int n_force_qs_snap;
    long int blimit;
    int dynticks_snap;
    long int dynticks_nesting;
    long int dynticks_nmi_nesting;
    atomic_t dynticks;
    bool rcu_need_heavy_qs;
    bool rcu_urgent_qs;
    struct callback_head barrier_head;
    int exp_dynticks_snap;
    struct swait_queue_head nocb_cb_wq;
    struct task_struct * nocb_gp_kthread;
    raw_spinlock_t nocb_lock;
    atomic_t nocb_lock_contended;
    int nocb_defer_wakeup;
    struct timer_list nocb_timer;
    long unsigned int nocb_gp_adv_time;
    raw_spinlock_t nocb_bypass_lock;
    struct rcu_cblist nocb_bypass;
    long unsigned int nocb_bypass_first;
    long unsigned int nocb_nobypass_last;
    int nocb_nobypass_count;
    raw_spinlock_t nocb_gp_lock;
    struct timer_list nocb_bypass_timer;
    u8 nocb_gp_sleep;
    u8 nocb_gp_bypass;
    u8 nocb_gp_gp;
    long unsigned int nocb_gp_seq;
    long unsigned int nocb_gp_loops;
    struct swait_queue_head nocb_gp_wq;
    bool nocb_cb_sleep;
    struct task_struct * nocb_cb_kthread;
    struct rcu_data * nocb_next_cb_rdp;
    struct rcu_data * nocb_gp_rdp;
    struct task_struct * rcu_cpu_kthread_task;
    unsigned int rcu_cpu_kthread_status;
    char rcu_cpu_has_work;
    unsigned int softirq_snap;
    struct irq_work rcu_iw;
    bool rcu_iw_pending;
    long unsigned int rcu_iw_gp_seq;
    long unsigned int rcu_ofl_gp_seq;
    short int rcu_ofl_gp_flags;
    long unsigned int rcu_onl_gp_seq;
    short int rcu_onl_gp_flags;
    long unsigned int last_fqs_resched;
    int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct rcu_data {
    long unsigned int gp_seq;
    long unsigned int gp_seq_needed;
    union rcu_noqs cpu_no_qs;
    bool core_needs_qs;
    bool beenonline;
    bool gpwrap;
    bool exp_deferred_qs;
    struct rcu_node * mynode;
    long unsigned int grpmask;
    long unsigned int ticks_this_gp;
    struct irq_work defer_qs_iw;
    bool defer_qs_iw_pending;
    struct rcu_segcblist cblist;
    long int qlen_last_fqs_check;
    long unsigned int n_force_qs_snap;
    long int blimit;
    int dynticks_snap;
    long int dynticks_nesting;
    long int dynticks_nmi_nesting;
    atomic_t dynticks;
    bool rcu_need_heavy_qs;
    bool rcu_urgent_qs;
    struct callback_head barrier_head;
    int exp_dynticks_snap;
    struct task_struct * rcu_cpu_kthread_task;
    unsigned int rcu_cpu_kthread_status;
    char rcu_cpu_has_work;
    unsigned int softirq_snap;
    struct irq_work rcu_iw;
    bool rcu_iw_pending;
    long unsigned int rcu_iw_gp_seq;
    long unsigned int rcu_ofl_gp_seq;
    short int rcu_ofl_gp_flags;
    long unsigned int rcu_onl_gp_seq;
    short int rcu_onl_gp_flags;
    long unsigned int last_fqs_resched;
    int cpu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct rcu_data {
    long unsigned int gp_seq;
    long unsigned int gp_seq_needed;
    union rcu_noqs cpu_no_qs;
    bool core_needs_qs;
    bool beenonline;
    bool gpwrap;
    bool exp_deferred_qs;
    struct rcu_node * mynode;
    long unsigned int grpmask;
    long unsigned int ticks_this_gp;
    struct irq_work defer_qs_iw;
    bool defer_qs_iw_pending;
    struct rcu_segcblist cblist;
    long int qlen_last_fqs_check;
    long unsigned int n_force_qs_snap;
    long int blimit;
    int dynticks_snap;
    long int dynticks_nesting;
    long int dynticks_nmi_nesting;
    atomic_t dynticks;
    bool rcu_need_heavy_qs;
    bool rcu_urgent_qs;
    struct callback_head barrier_head;
    int exp_dynticks_snap;
    struct task_struct * rcu_cpu_kthread_task;
    unsigned int rcu_cpu_kthread_status;
    char rcu_cpu_has_work;
    unsigned int softirq_snap;
    struct irq_work rcu_iw;
    bool rcu_iw_pending;
    long unsigned int rcu_iw_gp_seq;
    long unsigned int rcu_ofl_gp_seq;
    short int rcu_ofl_gp_flags;
    long unsigned int rcu_onl_gp_seq;
    short int rcu_onl_gp_flags;
    long unsigned int last_fqs_resched;
    int cpu;
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
<code>atomic_long_t exp_workdone1</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_long_t exp_workdone2</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_long_t exp_workdone3</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mutex exp_funnel_mutex</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>atomic_long_t exp_workdone0</code>
</li>
<li>
<b>Field added. </b>
<code>int exp_dynticks_snap</code>
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
<code>struct rcu_segcblist cblist</code>
</li>
<li>
<b>Field removed. </b>
<code>struct callback_head * nxtlist</code>
</li>
<li>
<b>Field removed. </b>
<code>struct callback_head * *[4] nxttail</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int[4] nxtcompleted</code>
</li>
<li>
<b>Field removed. </b>
<code>long int qlen_lazy</code>
</li>
<li>
<b>Field removed. </b>
<code>long int qlen</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct irq_work rcu_iw</code>
</li>
<li>
<b>Field added. </b>
<code>bool rcu_iw_pending</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int rcu_iw_gpnum</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int n_cbs_orphaned</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int n_cbs_adopted</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>long unsigned int n_cbs_invoked</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int n_nocbs_invoked</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int n_rcu_pending</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int n_rp_core_needs_qs</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int n_rp_report_qs</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int n_rp_cb_ready</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int n_rp_cpu_needs_gp</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int n_rp_gp_completed</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int n_rp_gp_started</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int n_rp_nocb_defer_wakeup</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int n_rp_need_nothing</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_long_t exp_workdone0</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_long_t exp_workdone1</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_long_t exp_workdone2</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_long_t exp_workdone3</code>
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
<code>long unsigned int gp_seq</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int gp_seq_needed</code>
</li>
<li>
<b>Field added. </b>
<code>bool deferred_qs</code>
</li>
<li>
<b>Field added. </b>
<code>long int dynticks_nesting</code>
</li>
<li>
<b>Field added. </b>
<code>long int dynticks_nmi_nesting</code>
</li>
<li>
<b>Field added. </b>
<code>bool rcu_need_heavy_qs</code>
</li>
<li>
<b>Field added. </b>
<code>bool rcu_urgent_qs</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int rcu_iw_gp_seq</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int rcu_ofl_gp_seq</code>
</li>
<li>
<b>Field added. </b>
<code>short int rcu_ofl_gp_flags</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int rcu_onl_gp_seq</code>
</li>
<li>
<b>Field added. </b>
<code>short int rcu_onl_gp_flags</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int last_fqs_resched</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int completed</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int gpnum</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int rcu_qs_ctr_snap</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int dynticks_fqs</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int offline_fqs</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int cond_resched_completed</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int rcu_iw_gpnum</code>
</li>
<li>
<b>Field removed. </b>
<code>struct rcu_state * rsp</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct rcu_dynticks * dynticks</code> ➡️ <code>atomic_t dynticks</code>
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
<code>bool exp_deferred_qs</code>
</li>
<li>
<b>Field added. </b>
<code>struct irq_work defer_qs_iw</code>
</li>
<li>
<b>Field added. </b>
<code>bool defer_qs_iw_pending</code>
</li>
<li>
<b>Field added. </b>
<code>struct task_struct * rcu_cpu_kthread_task</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int rcu_cpu_kthread_status</code>
</li>
<li>
<b>Field added. </b>
<code>char rcu_cpu_has_work</code>
</li>
<li>
<b>Field removed. </b>
<code>bool deferred_qs</code>
</li>
</ul>
</details>
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
<code>bool rcu_forced_tick</code>
</li>
<li>
<b>Field added. </b>
<code>bool rcu_forced_tick_exp</code>
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
<code>bool cpu_started</code>
</li>
<li>
<b>Field added. </b>
<code>struct work_struct strict_work</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int n_cbs_invoked</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int barrier_seq_snap</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int rcuc_activity</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int last_sched_clock</code>
</li>
<li>
<b>Field removed. </b>
<code>bool exp_deferred_qs</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long int lazy_len</code>
</li>
<li>
<b>Field removed. </b>
<code>long int dynticks_nesting</code>
</li>
<li>
<b>Field removed. </b>
<code>long int dynticks_nmi_nesting</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t dynticks</code>
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
<code>struct rcu_snap_record snap_record</code>
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
<code>struct swait_queue_head nocb_cb_wq</code>
</li>
<li>
<b>Field added. </b>
<code>struct swait_queue_head nocb_state_wq</code>
</li>
<li>
<b>Field added. </b>
<code>struct task_struct * nocb_gp_kthread</code>
</li>
<li>
<b>Field added. </b>
<code>raw_spinlock_t nocb_lock</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t nocb_lock_contended</code>
</li>
<li>
<b>Field added. </b>
<code>int nocb_defer_wakeup</code>
</li>
<li>
<b>Field added. </b>
<code>struct timer_list nocb_timer</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int nocb_gp_adv_time</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex nocb_gp_kthread_mutex</code>
</li>
<li>
<b>Field added. </b>
<code>raw_spinlock_t nocb_bypass_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct rcu_cblist nocb_bypass</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int nocb_bypass_first</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int nocb_nobypass_last</code>
</li>
<li>
<b>Field added. </b>
<code>int nocb_nobypass_count</code>
</li>
<li>
<b>Field added. </b>
<code>raw_spinlock_t nocb_gp_lock</code>
</li>
<li>
<b>Field added. </b>
<code>u8 nocb_gp_sleep</code>
</li>
<li>
<b>Field added. </b>
<code>u8 nocb_gp_bypass</code>
</li>
<li>
<b>Field added. </b>
<code>u8 nocb_gp_gp</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int nocb_gp_seq</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int nocb_gp_loops</code>
</li>
<li>
<b>Field added. </b>
<code>struct swait_queue_head nocb_gp_wq</code>
</li>
<li>
<b>Field added. </b>
<code>bool nocb_cb_sleep</code>
</li>
<li>
<b>Field added. </b>
<code>struct task_struct * nocb_cb_kthread</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head nocb_head_rdp</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head nocb_entry_rdp</code>
</li>
<li>
<b>Field added. </b>
<code>struct rcu_data * nocb_toggling_rdp</code>
</li>
<li>
<b>Field added. </b>
<code>struct rcu_data * nocb_gp_rdp</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct swait_queue_head nocb_cb_wq</code>
</li>
<li>
<b>Field added. </b>
<code>struct task_struct * nocb_gp_kthread</code>
</li>
<li>
<b>Field added. </b>
<code>raw_spinlock_t nocb_lock</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t nocb_lock_contended</code>
</li>
<li>
<b>Field added. </b>
<code>int nocb_defer_wakeup</code>
</li>
<li>
<b>Field added. </b>
<code>struct timer_list nocb_timer</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int nocb_gp_adv_time</code>
</li>
<li>
<b>Field added. </b>
<code>raw_spinlock_t nocb_bypass_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct rcu_cblist nocb_bypass</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int nocb_bypass_first</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int nocb_nobypass_last</code>
</li>
<li>
<b>Field added. </b>
<code>int nocb_nobypass_count</code>
</li>
<li>
<b>Field added. </b>
<code>raw_spinlock_t nocb_gp_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct timer_list nocb_bypass_timer</code>
</li>
<li>
<b>Field added. </b>
<code>u8 nocb_gp_sleep</code>
</li>
<li>
<b>Field added. </b>
<code>u8 nocb_gp_bypass</code>
</li>
<li>
<b>Field added. </b>
<code>u8 nocb_gp_gp</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int nocb_gp_seq</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int nocb_gp_loops</code>
</li>
<li>
<b>Field added. </b>
<code>struct swait_queue_head nocb_gp_wq</code>
</li>
<li>
<b>Field added. </b>
<code>bool nocb_cb_sleep</code>
</li>
<li>
<b>Field added. </b>
<code>struct task_struct * nocb_cb_kthread</code>
</li>
<li>
<b>Field added. </b>
<code>struct rcu_data * nocb_next_cb_rdp</code>
</li>
<li>
<b>Field added. </b>
<code>struct rcu_data * nocb_gp_rdp</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
