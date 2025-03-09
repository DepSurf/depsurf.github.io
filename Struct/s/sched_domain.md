# Struct: <code>sched_domain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct sched_domain {
    struct sched_domain * parent;
    struct sched_domain * child;
    struct sched_group * groups;
    long unsigned int min_interval;
    long unsigned int max_interval;
    unsigned int busy_factor;
    unsigned int imbalance_pct;
    unsigned int cache_nice_tries;
    unsigned int busy_idx;
    unsigned int idle_idx;
    unsigned int newidle_idx;
    unsigned int wake_idx;
    unsigned int forkexec_idx;
    unsigned int smt_gain;
    int nohz_idle;
    int flags;
    int level;
    long unsigned int last_balance;
    unsigned int balance_interval;
    unsigned int nr_balance_failed;
    u64 max_newidle_lb_cost;
    long unsigned int next_decay_max_lb_cost;
    unsigned int[3] lb_count;
    unsigned int[3] lb_failed;
    unsigned int[3] lb_balanced;
    unsigned int[3] lb_imbalance;
    unsigned int[3] lb_gained;
    unsigned int[3] lb_hot_gained;
    unsigned int[3] lb_nobusyg;
    unsigned int[3] lb_nobusyq;
    unsigned int alb_count;
    unsigned int alb_failed;
    unsigned int alb_pushed;
    unsigned int sbe_count;
    unsigned int sbe_balanced;
    unsigned int sbe_pushed;
    unsigned int sbf_count;
    unsigned int sbf_balanced;
    unsigned int sbf_pushed;
    unsigned int ttwu_wake_remote;
    unsigned int ttwu_move_affine;
    unsigned int ttwu_move_balance;
    char * name;
    void * private;
    struct callback_head rcu;
    unsigned int span_weight;
    long unsigned int[0] span;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct sched_domain {
    struct sched_domain * parent;
    struct sched_domain * child;
    struct sched_group * groups;
    long unsigned int min_interval;
    long unsigned int max_interval;
    unsigned int busy_factor;
    unsigned int imbalance_pct;
    unsigned int cache_nice_tries;
    unsigned int busy_idx;
    unsigned int idle_idx;
    unsigned int newidle_idx;
    unsigned int wake_idx;
    unsigned int forkexec_idx;
    unsigned int smt_gain;
    int nohz_idle;
    int flags;
    int level;
    long unsigned int last_balance;
    unsigned int balance_interval;
    unsigned int nr_balance_failed;
    u64 max_newidle_lb_cost;
    long unsigned int next_decay_max_lb_cost;
    unsigned int[3] lb_count;
    unsigned int[3] lb_failed;
    unsigned int[3] lb_balanced;
    unsigned int[3] lb_imbalance;
    unsigned int[3] lb_gained;
    unsigned int[3] lb_hot_gained;
    unsigned int[3] lb_nobusyg;
    unsigned int[3] lb_nobusyq;
    unsigned int alb_count;
    unsigned int alb_failed;
    unsigned int alb_pushed;
    unsigned int sbe_count;
    unsigned int sbe_balanced;
    unsigned int sbe_pushed;
    unsigned int sbf_count;
    unsigned int sbf_balanced;
    unsigned int sbf_pushed;
    unsigned int ttwu_wake_remote;
    unsigned int ttwu_move_affine;
    unsigned int ttwu_move_balance;
    char * name;
    void * private;
    struct callback_head rcu;
    unsigned int span_weight;
    long unsigned int[0] span;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct sched_domain {
    struct sched_domain * parent;
    struct sched_domain * child;
    struct sched_group * groups;
    long unsigned int min_interval;
    long unsigned int max_interval;
    unsigned int busy_factor;
    unsigned int imbalance_pct;
    unsigned int cache_nice_tries;
    unsigned int busy_idx;
    unsigned int idle_idx;
    unsigned int newidle_idx;
    unsigned int wake_idx;
    unsigned int forkexec_idx;
    unsigned int smt_gain;
    int nohz_idle;
    int flags;
    int level;
    long unsigned int last_balance;
    unsigned int balance_interval;
    unsigned int nr_balance_failed;
    u64 max_newidle_lb_cost;
    long unsigned int next_decay_max_lb_cost;
    u64 avg_scan_cost;
    unsigned int[3] lb_count;
    unsigned int[3] lb_failed;
    unsigned int[3] lb_balanced;
    unsigned int[3] lb_imbalance;
    unsigned int[3] lb_gained;
    unsigned int[3] lb_hot_gained;
    unsigned int[3] lb_nobusyg;
    unsigned int[3] lb_nobusyq;
    unsigned int alb_count;
    unsigned int alb_failed;
    unsigned int alb_pushed;
    unsigned int sbe_count;
    unsigned int sbe_balanced;
    unsigned int sbe_pushed;
    unsigned int sbf_count;
    unsigned int sbf_balanced;
    unsigned int sbf_pushed;
    unsigned int ttwu_wake_remote;
    unsigned int ttwu_move_affine;
    unsigned int ttwu_move_balance;
    char * name;
    void * private;
    struct callback_head rcu;
    struct sched_domain_shared * shared;
    unsigned int span_weight;
    long unsigned int[0] span;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct sched_domain {
    struct sched_domain * parent;
    struct sched_domain * child;
    struct sched_group * groups;
    long unsigned int min_interval;
    long unsigned int max_interval;
    unsigned int busy_factor;
    unsigned int imbalance_pct;
    unsigned int cache_nice_tries;
    unsigned int busy_idx;
    unsigned int idle_idx;
    unsigned int newidle_idx;
    unsigned int wake_idx;
    unsigned int forkexec_idx;
    unsigned int smt_gain;
    int nohz_idle;
    int flags;
    int level;
    long unsigned int last_balance;
    unsigned int balance_interval;
    unsigned int nr_balance_failed;
    u64 max_newidle_lb_cost;
    long unsigned int next_decay_max_lb_cost;
    u64 avg_scan_cost;
    unsigned int[3] lb_count;
    unsigned int[3] lb_failed;
    unsigned int[3] lb_balanced;
    unsigned int[3] lb_imbalance;
    unsigned int[3] lb_gained;
    unsigned int[3] lb_hot_gained;
    unsigned int[3] lb_nobusyg;
    unsigned int[3] lb_nobusyq;
    unsigned int alb_count;
    unsigned int alb_failed;
    unsigned int alb_pushed;
    unsigned int sbe_count;
    unsigned int sbe_balanced;
    unsigned int sbe_pushed;
    unsigned int sbf_count;
    unsigned int sbf_balanced;
    unsigned int sbf_pushed;
    unsigned int ttwu_wake_remote;
    unsigned int ttwu_move_affine;
    unsigned int ttwu_move_balance;
    char * name;
    void * private;
    struct callback_head rcu;
    struct sched_domain_shared * shared;
    unsigned int span_weight;
    long unsigned int[0] span;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct sched_domain {
    struct sched_domain * parent;
    struct sched_domain * child;
    struct sched_group * groups;
    long unsigned int min_interval;
    long unsigned int max_interval;
    unsigned int busy_factor;
    unsigned int imbalance_pct;
    unsigned int cache_nice_tries;
    unsigned int busy_idx;
    unsigned int idle_idx;
    unsigned int newidle_idx;
    unsigned int wake_idx;
    unsigned int forkexec_idx;
    unsigned int smt_gain;
    int nohz_idle;
    int flags;
    int level;
    long unsigned int last_balance;
    unsigned int balance_interval;
    unsigned int nr_balance_failed;
    u64 max_newidle_lb_cost;
    long unsigned int next_decay_max_lb_cost;
    u64 avg_scan_cost;
    unsigned int[3] lb_count;
    unsigned int[3] lb_failed;
    unsigned int[3] lb_balanced;
    unsigned int[3] lb_imbalance;
    unsigned int[3] lb_gained;
    unsigned int[3] lb_hot_gained;
    unsigned int[3] lb_nobusyg;
    unsigned int[3] lb_nobusyq;
    unsigned int alb_count;
    unsigned int alb_failed;
    unsigned int alb_pushed;
    unsigned int sbe_count;
    unsigned int sbe_balanced;
    unsigned int sbe_pushed;
    unsigned int sbf_count;
    unsigned int sbf_balanced;
    unsigned int sbf_pushed;
    unsigned int ttwu_wake_remote;
    unsigned int ttwu_move_affine;
    unsigned int ttwu_move_balance;
    char * name;
    void * private;
    struct callback_head rcu;
    struct sched_domain_shared * shared;
    unsigned int span_weight;
    long unsigned int[0] span;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct sched_domain {
    struct sched_domain * parent;
    struct sched_domain * child;
    struct sched_group * groups;
    long unsigned int min_interval;
    long unsigned int max_interval;
    unsigned int busy_factor;
    unsigned int imbalance_pct;
    unsigned int cache_nice_tries;
    unsigned int busy_idx;
    unsigned int idle_idx;
    unsigned int newidle_idx;
    unsigned int wake_idx;
    unsigned int forkexec_idx;
    unsigned int smt_gain;
    int nohz_idle;
    int flags;
    int level;
    long unsigned int last_balance;
    unsigned int balance_interval;
    unsigned int nr_balance_failed;
    u64 max_newidle_lb_cost;
    long unsigned int next_decay_max_lb_cost;
    u64 avg_scan_cost;
    unsigned int[3] lb_count;
    unsigned int[3] lb_failed;
    unsigned int[3] lb_balanced;
    unsigned int[3] lb_imbalance;
    unsigned int[3] lb_gained;
    unsigned int[3] lb_hot_gained;
    unsigned int[3] lb_nobusyg;
    unsigned int[3] lb_nobusyq;
    unsigned int alb_count;
    unsigned int alb_failed;
    unsigned int alb_pushed;
    unsigned int sbe_count;
    unsigned int sbe_balanced;
    unsigned int sbe_pushed;
    unsigned int sbf_count;
    unsigned int sbf_balanced;
    unsigned int sbf_pushed;
    unsigned int ttwu_wake_remote;
    unsigned int ttwu_move_affine;
    unsigned int ttwu_move_balance;
    char * name;
    void * private;
    struct callback_head rcu;
    struct sched_domain_shared * shared;
    unsigned int span_weight;
    long unsigned int[0] span;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct sched_domain {
    struct sched_domain * parent;
    struct sched_domain * child;
    struct sched_group * groups;
    long unsigned int min_interval;
    long unsigned int max_interval;
    unsigned int busy_factor;
    unsigned int imbalance_pct;
    unsigned int cache_nice_tries;
    unsigned int busy_idx;
    unsigned int idle_idx;
    unsigned int newidle_idx;
    unsigned int wake_idx;
    unsigned int forkexec_idx;
    int nohz_idle;
    int flags;
    int level;
    long unsigned int last_balance;
    unsigned int balance_interval;
    unsigned int nr_balance_failed;
    u64 max_newidle_lb_cost;
    long unsigned int next_decay_max_lb_cost;
    u64 avg_scan_cost;
    unsigned int[3] lb_count;
    unsigned int[3] lb_failed;
    unsigned int[3] lb_balanced;
    unsigned int[3] lb_imbalance;
    unsigned int[3] lb_gained;
    unsigned int[3] lb_hot_gained;
    unsigned int[3] lb_nobusyg;
    unsigned int[3] lb_nobusyq;
    unsigned int alb_count;
    unsigned int alb_failed;
    unsigned int alb_pushed;
    unsigned int sbe_count;
    unsigned int sbe_balanced;
    unsigned int sbe_pushed;
    unsigned int sbf_count;
    unsigned int sbf_balanced;
    unsigned int sbf_pushed;
    unsigned int ttwu_wake_remote;
    unsigned int ttwu_move_affine;
    unsigned int ttwu_move_balance;
    char * name;
    void * private;
    struct callback_head rcu;
    struct sched_domain_shared * shared;
    unsigned int span_weight;
    long unsigned int[0] span;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct sched_domain {
    struct sched_domain * parent;
    struct sched_domain * child;
    struct sched_group * groups;
    long unsigned int min_interval;
    long unsigned int max_interval;
    unsigned int busy_factor;
    unsigned int imbalance_pct;
    unsigned int cache_nice_tries;
    int nohz_idle;
    int flags;
    int level;
    long unsigned int last_balance;
    unsigned int balance_interval;
    unsigned int nr_balance_failed;
    u64 max_newidle_lb_cost;
    long unsigned int next_decay_max_lb_cost;
    u64 avg_scan_cost;
    unsigned int[3] lb_count;
    unsigned int[3] lb_failed;
    unsigned int[3] lb_balanced;
    unsigned int[3] lb_imbalance;
    unsigned int[3] lb_gained;
    unsigned int[3] lb_hot_gained;
    unsigned int[3] lb_nobusyg;
    unsigned int[3] lb_nobusyq;
    unsigned int alb_count;
    unsigned int alb_failed;
    unsigned int alb_pushed;
    unsigned int sbe_count;
    unsigned int sbe_balanced;
    unsigned int sbe_pushed;
    unsigned int sbf_count;
    unsigned int sbf_balanced;
    unsigned int sbf_pushed;
    unsigned int ttwu_wake_remote;
    unsigned int ttwu_move_affine;
    unsigned int ttwu_move_balance;
    char * name;
    void * private;
    struct callback_head rcu;
    struct sched_domain_shared * shared;
    unsigned int span_weight;
    long unsigned int[0] span;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct sched_domain {
    struct sched_domain * parent;
    struct sched_domain * child;
    struct sched_group * groups;
    long unsigned int min_interval;
    long unsigned int max_interval;
    unsigned int busy_factor;
    unsigned int imbalance_pct;
    unsigned int cache_nice_tries;
    int nohz_idle;
    int flags;
    int level;
    long unsigned int last_balance;
    unsigned int balance_interval;
    unsigned int nr_balance_failed;
    u64 max_newidle_lb_cost;
    long unsigned int next_decay_max_lb_cost;
    u64 avg_scan_cost;
    unsigned int[3] lb_count;
    unsigned int[3] lb_failed;
    unsigned int[3] lb_balanced;
    unsigned int[3] lb_imbalance;
    unsigned int[3] lb_gained;
    unsigned int[3] lb_hot_gained;
    unsigned int[3] lb_nobusyg;
    unsigned int[3] lb_nobusyq;
    unsigned int alb_count;
    unsigned int alb_failed;
    unsigned int alb_pushed;
    unsigned int sbe_count;
    unsigned int sbe_balanced;
    unsigned int sbe_pushed;
    unsigned int sbf_count;
    unsigned int sbf_balanced;
    unsigned int sbf_pushed;
    unsigned int ttwu_wake_remote;
    unsigned int ttwu_move_affine;
    unsigned int ttwu_move_balance;
    char * name;
    void * private;
    struct callback_head rcu;
    struct sched_domain_shared * shared;
    unsigned int span_weight;
    long unsigned int[0] span;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct sched_domain {
    struct sched_domain * parent;
    struct sched_domain * child;
    struct sched_group * groups;
    long unsigned int min_interval;
    long unsigned int max_interval;
    unsigned int busy_factor;
    unsigned int imbalance_pct;
    unsigned int cache_nice_tries;
    int nohz_idle;
    int flags;
    int level;
    long unsigned int last_balance;
    unsigned int balance_interval;
    unsigned int nr_balance_failed;
    u64 max_newidle_lb_cost;
    long unsigned int next_decay_max_lb_cost;
    u64 avg_scan_cost;
    unsigned int[3] lb_count;
    unsigned int[3] lb_failed;
    unsigned int[3] lb_balanced;
    unsigned int[3] lb_imbalance;
    unsigned int[3] lb_gained;
    unsigned int[3] lb_hot_gained;
    unsigned int[3] lb_nobusyg;
    unsigned int[3] lb_nobusyq;
    unsigned int alb_count;
    unsigned int alb_failed;
    unsigned int alb_pushed;
    unsigned int sbe_count;
    unsigned int sbe_balanced;
    unsigned int sbe_pushed;
    unsigned int sbf_count;
    unsigned int sbf_balanced;
    unsigned int sbf_pushed;
    unsigned int ttwu_wake_remote;
    unsigned int ttwu_move_affine;
    unsigned int ttwu_move_balance;
    char * name;
    void * private;
    struct callback_head rcu;
    struct sched_domain_shared * shared;
    unsigned int span_weight;
    long unsigned int[0] span;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct sched_domain {
    struct sched_domain * parent;
    struct sched_domain * child;
    struct sched_group * groups;
    long unsigned int min_interval;
    long unsigned int max_interval;
    unsigned int busy_factor;
    unsigned int imbalance_pct;
    unsigned int cache_nice_tries;
    int nohz_idle;
    int flags;
    int level;
    long unsigned int last_balance;
    unsigned int balance_interval;
    unsigned int nr_balance_failed;
    u64 max_newidle_lb_cost;
    long unsigned int next_decay_max_lb_cost;
    u64 avg_scan_cost;
    unsigned int[3] lb_count;
    unsigned int[3] lb_failed;
    unsigned int[3] lb_balanced;
    unsigned int[3] lb_imbalance;
    unsigned int[3] lb_gained;
    unsigned int[3] lb_hot_gained;
    unsigned int[3] lb_nobusyg;
    unsigned int[3] lb_nobusyq;
    unsigned int alb_count;
    unsigned int alb_failed;
    unsigned int alb_pushed;
    unsigned int sbe_count;
    unsigned int sbe_balanced;
    unsigned int sbe_pushed;
    unsigned int sbf_count;
    unsigned int sbf_balanced;
    unsigned int sbf_pushed;
    unsigned int ttwu_wake_remote;
    unsigned int ttwu_move_affine;
    unsigned int ttwu_move_balance;
    char * name;
    void * private;
    struct callback_head rcu;
    struct sched_domain_shared * shared;
    unsigned int span_weight;
    long unsigned int[0] span;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct sched_domain {
    struct sched_domain * parent;
    struct sched_domain * child;
    struct sched_group * groups;
    long unsigned int min_interval;
    long unsigned int max_interval;
    unsigned int busy_factor;
    unsigned int imbalance_pct;
    unsigned int cache_nice_tries;
    int nohz_idle;
    int flags;
    int level;
    long unsigned int last_balance;
    unsigned int balance_interval;
    unsigned int nr_balance_failed;
    u64 max_newidle_lb_cost;
    long unsigned int next_decay_max_lb_cost;
    u64 avg_scan_cost;
    unsigned int[3] lb_count;
    unsigned int[3] lb_failed;
    unsigned int[3] lb_balanced;
    unsigned int[3] lb_imbalance;
    unsigned int[3] lb_gained;
    unsigned int[3] lb_hot_gained;
    unsigned int[3] lb_nobusyg;
    unsigned int[3] lb_nobusyq;
    unsigned int alb_count;
    unsigned int alb_failed;
    unsigned int alb_pushed;
    unsigned int sbe_count;
    unsigned int sbe_balanced;
    unsigned int sbe_pushed;
    unsigned int sbf_count;
    unsigned int sbf_balanced;
    unsigned int sbf_pushed;
    unsigned int ttwu_wake_remote;
    unsigned int ttwu_move_affine;
    unsigned int ttwu_move_balance;
    char * name;
    void * private;
    struct callback_head rcu;
    struct sched_domain_shared * shared;
    unsigned int span_weight;
    long unsigned int[0] span;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct sched_domain {
    struct sched_domain * parent;
    struct sched_domain * child;
    struct sched_group * groups;
    long unsigned int min_interval;
    long unsigned int max_interval;
    unsigned int busy_factor;
    unsigned int imbalance_pct;
    unsigned int cache_nice_tries;
    int nohz_idle;
    int flags;
    int level;
    long unsigned int last_balance;
    unsigned int balance_interval;
    unsigned int nr_balance_failed;
    u64 max_newidle_lb_cost;
    long unsigned int next_decay_max_lb_cost;
    u64 avg_scan_cost;
    unsigned int[3] lb_count;
    unsigned int[3] lb_failed;
    unsigned int[3] lb_balanced;
    unsigned int[3] lb_imbalance;
    unsigned int[3] lb_gained;
    unsigned int[3] lb_hot_gained;
    unsigned int[3] lb_nobusyg;
    unsigned int[3] lb_nobusyq;
    unsigned int alb_count;
    unsigned int alb_failed;
    unsigned int alb_pushed;
    unsigned int sbe_count;
    unsigned int sbe_balanced;
    unsigned int sbe_pushed;
    unsigned int sbf_count;
    unsigned int sbf_balanced;
    unsigned int sbf_pushed;
    unsigned int ttwu_wake_remote;
    unsigned int ttwu_move_affine;
    unsigned int ttwu_move_balance;
    char * name;
    void * private;
    struct callback_head rcu;
    struct sched_domain_shared * shared;
    unsigned int span_weight;
    long unsigned int[0] span;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct sched_domain {
    struct sched_domain * parent;
    struct sched_domain * child;
    struct sched_group * groups;
    long unsigned int min_interval;
    long unsigned int max_interval;
    unsigned int busy_factor;
    unsigned int imbalance_pct;
    unsigned int cache_nice_tries;
    unsigned int imb_numa_nr;
    int nohz_idle;
    int flags;
    int level;
    long unsigned int last_balance;
    unsigned int balance_interval;
    unsigned int nr_balance_failed;
    u64 max_newidle_lb_cost;
    long unsigned int last_decay_max_lb_cost;
    u64 avg_scan_cost;
    unsigned int[3] lb_count;
    unsigned int[3] lb_failed;
    unsigned int[3] lb_balanced;
    unsigned int[3] lb_imbalance;
    unsigned int[3] lb_gained;
    unsigned int[3] lb_hot_gained;
    unsigned int[3] lb_nobusyg;
    unsigned int[3] lb_nobusyq;
    unsigned int alb_count;
    unsigned int alb_failed;
    unsigned int alb_pushed;
    unsigned int sbe_count;
    unsigned int sbe_balanced;
    unsigned int sbe_pushed;
    unsigned int sbf_count;
    unsigned int sbf_balanced;
    unsigned int sbf_pushed;
    unsigned int ttwu_wake_remote;
    unsigned int ttwu_move_affine;
    unsigned int ttwu_move_balance;
    char * name;
    void * private;
    struct callback_head rcu;
    struct sched_domain_shared * shared;
    unsigned int span_weight;
    long unsigned int[0] span;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct sched_domain {
    struct sched_domain * parent;
    struct sched_domain * child;
    struct sched_group * groups;
    long unsigned int min_interval;
    long unsigned int max_interval;
    unsigned int busy_factor;
    unsigned int imbalance_pct;
    unsigned int cache_nice_tries;
    unsigned int imb_numa_nr;
    int nohz_idle;
    int flags;
    int level;
    long unsigned int last_balance;
    unsigned int balance_interval;
    unsigned int nr_balance_failed;
    u64 max_newidle_lb_cost;
    long unsigned int last_decay_max_lb_cost;
    u64 avg_scan_cost;
    unsigned int[3] lb_count;
    unsigned int[3] lb_failed;
    unsigned int[3] lb_balanced;
    unsigned int[3] lb_imbalance;
    unsigned int[3] lb_gained;
    unsigned int[3] lb_hot_gained;
    unsigned int[3] lb_nobusyg;
    unsigned int[3] lb_nobusyq;
    unsigned int alb_count;
    unsigned int alb_failed;
    unsigned int alb_pushed;
    unsigned int sbe_count;
    unsigned int sbe_balanced;
    unsigned int sbe_pushed;
    unsigned int sbf_count;
    unsigned int sbf_balanced;
    unsigned int sbf_pushed;
    unsigned int ttwu_wake_remote;
    unsigned int ttwu_move_affine;
    unsigned int ttwu_move_balance;
    char * name;
    void * private;
    struct callback_head rcu;
    struct sched_domain_shared * shared;
    unsigned int span_weight;
    long unsigned int[0] span;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct sched_domain {
    struct sched_domain * parent;
    struct sched_domain * child;
    struct sched_group * groups;
    long unsigned int min_interval;
    long unsigned int max_interval;
    unsigned int busy_factor;
    unsigned int imbalance_pct;
    unsigned int cache_nice_tries;
    unsigned int imb_numa_nr;
    int nohz_idle;
    int flags;
    int level;
    long unsigned int last_balance;
    unsigned int balance_interval;
    unsigned int nr_balance_failed;
    u64 max_newidle_lb_cost;
    long unsigned int last_decay_max_lb_cost;
    u64 avg_scan_cost;
    unsigned int[3] lb_count;
    unsigned int[3] lb_failed;
    unsigned int[3] lb_balanced;
    unsigned int[3] lb_imbalance;
    unsigned int[3] lb_gained;
    unsigned int[3] lb_hot_gained;
    unsigned int[3] lb_nobusyg;
    unsigned int[3] lb_nobusyq;
    unsigned int alb_count;
    unsigned int alb_failed;
    unsigned int alb_pushed;
    unsigned int sbe_count;
    unsigned int sbe_balanced;
    unsigned int sbe_pushed;
    unsigned int sbf_count;
    unsigned int sbf_balanced;
    unsigned int sbf_pushed;
    unsigned int ttwu_wake_remote;
    unsigned int ttwu_move_affine;
    unsigned int ttwu_move_balance;
    char * name;
    void * private;
    struct callback_head rcu;
    struct sched_domain_shared * shared;
    unsigned int span_weight;
    long unsigned int[0] span;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct sched_domain {
    struct sched_domain * parent;
    struct sched_domain * child;
    struct sched_group * groups;
    long unsigned int min_interval;
    long unsigned int max_interval;
    unsigned int busy_factor;
    unsigned int imbalance_pct;
    unsigned int cache_nice_tries;
    unsigned int imb_numa_nr;
    int nohz_idle;
    int flags;
    int level;
    long unsigned int last_balance;
    unsigned int balance_interval;
    unsigned int nr_balance_failed;
    u64 max_newidle_lb_cost;
    long unsigned int last_decay_max_lb_cost;
    unsigned int[3] lb_count;
    unsigned int[3] lb_failed;
    unsigned int[3] lb_balanced;
    unsigned int[3] lb_imbalance;
    unsigned int[3] lb_gained;
    unsigned int[3] lb_hot_gained;
    unsigned int[3] lb_nobusyg;
    unsigned int[3] lb_nobusyq;
    unsigned int alb_count;
    unsigned int alb_failed;
    unsigned int alb_pushed;
    unsigned int sbe_count;
    unsigned int sbe_balanced;
    unsigned int sbe_pushed;
    unsigned int sbf_count;
    unsigned int sbf_balanced;
    unsigned int sbf_pushed;
    unsigned int ttwu_wake_remote;
    unsigned int ttwu_move_affine;
    unsigned int ttwu_move_balance;
    char * name;
    void * private;
    struct callback_head rcu;
    struct sched_domain_shared * shared;
    unsigned int span_weight;
    long unsigned int[0] span;
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
struct sched_domain {
    struct sched_domain * parent;
    struct sched_domain * child;
    struct sched_group * groups;
    long unsigned int min_interval;
    long unsigned int max_interval;
    unsigned int busy_factor;
    unsigned int imbalance_pct;
    unsigned int cache_nice_tries;
    int nohz_idle;
    int flags;
    int level;
    long unsigned int last_balance;
    unsigned int balance_interval;
    unsigned int nr_balance_failed;
    u64 max_newidle_lb_cost;
    long unsigned int next_decay_max_lb_cost;
    u64 avg_scan_cost;
    unsigned int[3] lb_count;
    unsigned int[3] lb_failed;
    unsigned int[3] lb_balanced;
    unsigned int[3] lb_imbalance;
    unsigned int[3] lb_gained;
    unsigned int[3] lb_hot_gained;
    unsigned int[3] lb_nobusyg;
    unsigned int[3] lb_nobusyq;
    unsigned int alb_count;
    unsigned int alb_failed;
    unsigned int alb_pushed;
    unsigned int sbe_count;
    unsigned int sbe_balanced;
    unsigned int sbe_pushed;
    unsigned int sbf_count;
    unsigned int sbf_balanced;
    unsigned int sbf_pushed;
    unsigned int ttwu_wake_remote;
    unsigned int ttwu_move_affine;
    unsigned int ttwu_move_balance;
    char * name;
    void * private;
    struct callback_head rcu;
    struct sched_domain_shared * shared;
    unsigned int span_weight;
    long unsigned int[0] span;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct sched_domain {
    struct sched_domain * parent;
    struct sched_domain * child;
    struct sched_group * groups;
    long unsigned int min_interval;
    long unsigned int max_interval;
    unsigned int busy_factor;
    unsigned int imbalance_pct;
    unsigned int cache_nice_tries;
    int nohz_idle;
    int flags;
    int level;
    long unsigned int last_balance;
    unsigned int balance_interval;
    unsigned int nr_balance_failed;
    u64 max_newidle_lb_cost;
    long unsigned int next_decay_max_lb_cost;
    u64 avg_scan_cost;
    unsigned int[3] lb_count;
    unsigned int[3] lb_failed;
    unsigned int[3] lb_balanced;
    unsigned int[3] lb_imbalance;
    unsigned int[3] lb_gained;
    unsigned int[3] lb_hot_gained;
    unsigned int[3] lb_nobusyg;
    unsigned int[3] lb_nobusyq;
    unsigned int alb_count;
    unsigned int alb_failed;
    unsigned int alb_pushed;
    unsigned int sbe_count;
    unsigned int sbe_balanced;
    unsigned int sbe_pushed;
    unsigned int sbf_count;
    unsigned int sbf_balanced;
    unsigned int sbf_pushed;
    unsigned int ttwu_wake_remote;
    unsigned int ttwu_move_affine;
    unsigned int ttwu_move_balance;
    char * name;
    void * private;
    struct callback_head rcu;
    struct sched_domain_shared * shared;
    unsigned int span_weight;
    long unsigned int[0] span;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct sched_domain {
    struct sched_domain * parent;
    struct sched_domain * child;
    struct sched_group * groups;
    long unsigned int min_interval;
    long unsigned int max_interval;
    unsigned int busy_factor;
    unsigned int imbalance_pct;
    unsigned int cache_nice_tries;
    int nohz_idle;
    int flags;
    int level;
    long unsigned int last_balance;
    unsigned int balance_interval;
    unsigned int nr_balance_failed;
    u64 max_newidle_lb_cost;
    long unsigned int next_decay_max_lb_cost;
    u64 avg_scan_cost;
    unsigned int[3] lb_count;
    unsigned int[3] lb_failed;
    unsigned int[3] lb_balanced;
    unsigned int[3] lb_imbalance;
    unsigned int[3] lb_gained;
    unsigned int[3] lb_hot_gained;
    unsigned int[3] lb_nobusyg;
    unsigned int[3] lb_nobusyq;
    unsigned int alb_count;
    unsigned int alb_failed;
    unsigned int alb_pushed;
    unsigned int sbe_count;
    unsigned int sbe_balanced;
    unsigned int sbe_pushed;
    unsigned int sbf_count;
    unsigned int sbf_balanced;
    unsigned int sbf_pushed;
    unsigned int ttwu_wake_remote;
    unsigned int ttwu_move_affine;
    unsigned int ttwu_move_balance;
    char * name;
    void * private;
    struct callback_head rcu;
    struct sched_domain_shared * shared;
    unsigned int span_weight;
    long unsigned int[0] span;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct sched_domain {
    struct sched_domain * parent;
    struct sched_domain * child;
    struct sched_group * groups;
    long unsigned int min_interval;
    long unsigned int max_interval;
    unsigned int busy_factor;
    unsigned int imbalance_pct;
    unsigned int cache_nice_tries;
    int nohz_idle;
    int flags;
    int level;
    long unsigned int last_balance;
    unsigned int balance_interval;
    unsigned int nr_balance_failed;
    u64 max_newidle_lb_cost;
    long unsigned int next_decay_max_lb_cost;
    u64 avg_scan_cost;
    unsigned int[3] lb_count;
    unsigned int[3] lb_failed;
    unsigned int[3] lb_balanced;
    unsigned int[3] lb_imbalance;
    unsigned int[3] lb_gained;
    unsigned int[3] lb_hot_gained;
    unsigned int[3] lb_nobusyg;
    unsigned int[3] lb_nobusyq;
    unsigned int alb_count;
    unsigned int alb_failed;
    unsigned int alb_pushed;
    unsigned int sbe_count;
    unsigned int sbe_balanced;
    unsigned int sbe_pushed;
    unsigned int sbf_count;
    unsigned int sbf_balanced;
    unsigned int sbf_pushed;
    unsigned int ttwu_wake_remote;
    unsigned int ttwu_move_affine;
    unsigned int ttwu_move_balance;
    char * name;
    void * private;
    struct callback_head rcu;
    struct sched_domain_shared * shared;
    unsigned int span_weight;
    long unsigned int[0] span;
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
struct sched_domain {
    struct sched_domain * parent;
    struct sched_domain * child;
    struct sched_group * groups;
    long unsigned int min_interval;
    long unsigned int max_interval;
    unsigned int busy_factor;
    unsigned int imbalance_pct;
    unsigned int cache_nice_tries;
    int nohz_idle;
    int flags;
    int level;
    long unsigned int last_balance;
    unsigned int balance_interval;
    unsigned int nr_balance_failed;
    u64 max_newidle_lb_cost;
    long unsigned int next_decay_max_lb_cost;
    u64 avg_scan_cost;
    unsigned int[3] lb_count;
    unsigned int[3] lb_failed;
    unsigned int[3] lb_balanced;
    unsigned int[3] lb_imbalance;
    unsigned int[3] lb_gained;
    unsigned int[3] lb_hot_gained;
    unsigned int[3] lb_nobusyg;
    unsigned int[3] lb_nobusyq;
    unsigned int alb_count;
    unsigned int alb_failed;
    unsigned int alb_pushed;
    unsigned int sbe_count;
    unsigned int sbe_balanced;
    unsigned int sbe_pushed;
    unsigned int sbf_count;
    unsigned int sbf_balanced;
    unsigned int sbf_pushed;
    unsigned int ttwu_wake_remote;
    unsigned int ttwu_move_affine;
    unsigned int ttwu_move_balance;
    char * name;
    void * private;
    struct callback_head rcu;
    struct sched_domain_shared * shared;
    unsigned int span_weight;
    long unsigned int[0] span;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct sched_domain {
    struct sched_domain * parent;
    struct sched_domain * child;
    struct sched_group * groups;
    long unsigned int min_interval;
    long unsigned int max_interval;
    unsigned int busy_factor;
    unsigned int imbalance_pct;
    unsigned int cache_nice_tries;
    int nohz_idle;
    int flags;
    int level;
    long unsigned int last_balance;
    unsigned int balance_interval;
    unsigned int nr_balance_failed;
    u64 max_newidle_lb_cost;
    long unsigned int next_decay_max_lb_cost;
    u64 avg_scan_cost;
    unsigned int[3] lb_count;
    unsigned int[3] lb_failed;
    unsigned int[3] lb_balanced;
    unsigned int[3] lb_imbalance;
    unsigned int[3] lb_gained;
    unsigned int[3] lb_hot_gained;
    unsigned int[3] lb_nobusyg;
    unsigned int[3] lb_nobusyq;
    unsigned int alb_count;
    unsigned int alb_failed;
    unsigned int alb_pushed;
    unsigned int sbe_count;
    unsigned int sbe_balanced;
    unsigned int sbe_pushed;
    unsigned int sbf_count;
    unsigned int sbf_balanced;
    unsigned int sbf_pushed;
    unsigned int ttwu_wake_remote;
    unsigned int ttwu_move_affine;
    unsigned int ttwu_move_balance;
    char * name;
    void * private;
    struct callback_head rcu;
    struct sched_domain_shared * shared;
    unsigned int span_weight;
    long unsigned int[0] span;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct sched_domain {
    struct sched_domain * parent;
    struct sched_domain * child;
    struct sched_group * groups;
    long unsigned int min_interval;
    long unsigned int max_interval;
    unsigned int busy_factor;
    unsigned int imbalance_pct;
    unsigned int cache_nice_tries;
    int nohz_idle;
    int flags;
    int level;
    long unsigned int last_balance;
    unsigned int balance_interval;
    unsigned int nr_balance_failed;
    u64 max_newidle_lb_cost;
    long unsigned int next_decay_max_lb_cost;
    u64 avg_scan_cost;
    unsigned int[3] lb_count;
    unsigned int[3] lb_failed;
    unsigned int[3] lb_balanced;
    unsigned int[3] lb_imbalance;
    unsigned int[3] lb_gained;
    unsigned int[3] lb_hot_gained;
    unsigned int[3] lb_nobusyg;
    unsigned int[3] lb_nobusyq;
    unsigned int alb_count;
    unsigned int alb_failed;
    unsigned int alb_pushed;
    unsigned int sbe_count;
    unsigned int sbe_balanced;
    unsigned int sbe_pushed;
    unsigned int sbf_count;
    unsigned int sbf_balanced;
    unsigned int sbf_pushed;
    unsigned int ttwu_wake_remote;
    unsigned int ttwu_move_affine;
    unsigned int ttwu_move_balance;
    char * name;
    void * private;
    struct callback_head rcu;
    struct sched_domain_shared * shared;
    unsigned int span_weight;
    long unsigned int[0] span;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct sched_domain {
    struct sched_domain * parent;
    struct sched_domain * child;
    struct sched_group * groups;
    long unsigned int min_interval;
    long unsigned int max_interval;
    unsigned int busy_factor;
    unsigned int imbalance_pct;
    unsigned int cache_nice_tries;
    int nohz_idle;
    int flags;
    int level;
    long unsigned int last_balance;
    unsigned int balance_interval;
    unsigned int nr_balance_failed;
    u64 max_newidle_lb_cost;
    long unsigned int next_decay_max_lb_cost;
    u64 avg_scan_cost;
    unsigned int[3] lb_count;
    unsigned int[3] lb_failed;
    unsigned int[3] lb_balanced;
    unsigned int[3] lb_imbalance;
    unsigned int[3] lb_gained;
    unsigned int[3] lb_hot_gained;
    unsigned int[3] lb_nobusyg;
    unsigned int[3] lb_nobusyq;
    unsigned int alb_count;
    unsigned int alb_failed;
    unsigned int alb_pushed;
    unsigned int sbe_count;
    unsigned int sbe_balanced;
    unsigned int sbe_pushed;
    unsigned int sbf_count;
    unsigned int sbf_balanced;
    unsigned int sbf_pushed;
    unsigned int ttwu_wake_remote;
    unsigned int ttwu_move_affine;
    unsigned int ttwu_move_balance;
    char * name;
    void * private;
    struct callback_head rcu;
    struct sched_domain_shared * shared;
    unsigned int span_weight;
    long unsigned int[0] span;
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 avg_scan_cost</code>
</li>
<li>
<b>Field added. </b>
<code>struct sched_domain_shared * shared</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
<b>Field removed. </b>
<code>unsigned int smt_gain</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>unsigned int busy_idx</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int idle_idx</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int newidle_idx</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int wake_idx</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int forkexec_idx</code>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int imb_numa_nr</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int last_decay_max_lb_cost</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int next_decay_max_lb_cost</code>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>u64 avg_scan_cost</code>
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
