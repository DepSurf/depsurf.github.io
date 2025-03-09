# Struct: <code>Qdisc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct Qdisc {
    int (*)(struct sk_buff *, struct Qdisc *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    unsigned int flags;
    u32 limit;
    const struct Qdisc_ops * ops;
    struct qdisc_size_table * stab;
    struct list_head list;
    u32 handle;
    u32 parent;
    int (*)(struct sk_buff *, struct Qdisc *) reshape_fail;
    void * u32_node;
    struct Qdisc * __parent;
    struct netdev_queue * dev_queue;
    struct gnet_stats_rate_est64 rate_est;
    struct gnet_stats_basic_cpu * cpu_bstats;
    struct gnet_stats_queue * cpu_qstats;
    struct Qdisc * next_sched;
    struct sk_buff * gso_skb;
    long unsigned int state;
    struct sk_buff_head q;
    struct gnet_stats_basic_packed bstats;
    unsigned int __state;
    struct gnet_stats_queue qstats;
    struct callback_head callback_head;
    int padded;
    atomic_t refcnt;
    spinlock_t busylock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct Qdisc {
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    unsigned int flags;
    u32 limit;
    const struct Qdisc_ops * ops;
    struct qdisc_size_table * stab;
    struct list_head list;
    u32 handle;
    u32 parent;
    void * u32_node;
    struct netdev_queue * dev_queue;
    struct gnet_stats_rate_est64 rate_est;
    struct gnet_stats_basic_cpu * cpu_bstats;
    struct gnet_stats_queue * cpu_qstats;
    struct sk_buff * gso_skb;
    struct sk_buff_head q;
    struct gnet_stats_basic_packed bstats;
    seqcount_t running;
    struct gnet_stats_queue qstats;
    long unsigned int state;
    struct Qdisc * next_sched;
    struct sk_buff * skb_bad_txq;
    struct callback_head callback_head;
    int padded;
    atomic_t refcnt;
    spinlock_t busylock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct Qdisc {
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    unsigned int flags;
    u32 limit;
    const struct Qdisc_ops * ops;
    struct qdisc_size_table * stab;
    struct hlist_node hash;
    u32 handle;
    u32 parent;
    void * u32_node;
    struct netdev_queue * dev_queue;
    struct net_rate_estimator * rate_est;
    struct gnet_stats_basic_cpu * cpu_bstats;
    struct gnet_stats_queue * cpu_qstats;
    struct sk_buff * gso_skb;
    struct qdisc_skb_head q;
    struct gnet_stats_basic_packed bstats;
    seqcount_t running;
    struct gnet_stats_queue qstats;
    long unsigned int state;
    struct Qdisc * next_sched;
    struct sk_buff * skb_bad_txq;
    struct callback_head callback_head;
    int padded;
    atomic_t refcnt;
    spinlock_t busylock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct Qdisc {
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    unsigned int flags;
    u32 limit;
    const struct Qdisc_ops * ops;
    struct qdisc_size_table * stab;
    struct hlist_node hash;
    u32 handle;
    u32 parent;
    void * u32_node;
    struct netdev_queue * dev_queue;
    struct net_rate_estimator * rate_est;
    struct gnet_stats_basic_cpu * cpu_bstats;
    struct gnet_stats_queue * cpu_qstats;
    struct sk_buff * gso_skb;
    struct qdisc_skb_head q;
    struct gnet_stats_basic_packed bstats;
    seqcount_t running;
    struct gnet_stats_queue qstats;
    long unsigned int state;
    struct Qdisc * next_sched;
    struct sk_buff * skb_bad_txq;
    struct callback_head callback_head;
    int padded;
    refcount_t refcnt;
    spinlock_t busylock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct Qdisc {
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    unsigned int flags;
    u32 limit;
    const struct Qdisc_ops * ops;
    struct qdisc_size_table * stab;
    struct hlist_node hash;
    u32 handle;
    u32 parent;
    struct netdev_queue * dev_queue;
    struct net_rate_estimator * rate_est;
    struct gnet_stats_basic_cpu * cpu_bstats;
    struct gnet_stats_queue * cpu_qstats;
    struct sk_buff * gso_skb;
    struct qdisc_skb_head q;
    struct gnet_stats_basic_packed bstats;
    seqcount_t running;
    struct gnet_stats_queue qstats;
    long unsigned int state;
    struct Qdisc * next_sched;
    struct sk_buff * skb_bad_txq;
    int padded;
    refcount_t refcnt;
    spinlock_t busylock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct Qdisc {
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    unsigned int flags;
    u32 limit;
    const struct Qdisc_ops * ops;
    struct qdisc_size_table * stab;
    struct hlist_node hash;
    u32 handle;
    u32 parent;
    struct netdev_queue * dev_queue;
    struct net_rate_estimator * rate_est;
    struct gnet_stats_basic_cpu * cpu_bstats;
    struct gnet_stats_queue * cpu_qstats;
    int padded;
    refcount_t refcnt;
    struct sk_buff_head gso_skb;
    struct qdisc_skb_head q;
    struct gnet_stats_basic_packed bstats;
    seqcount_t running;
    struct gnet_stats_queue qstats;
    long unsigned int state;
    struct Qdisc * next_sched;
    struct sk_buff_head skb_bad_txq;
    spinlock_t busylock;
    spinlock_t seqlock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct Qdisc {
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    unsigned int flags;
    u32 limit;
    const struct Qdisc_ops * ops;
    struct qdisc_size_table * stab;
    struct hlist_node hash;
    u32 handle;
    u32 parent;
    struct netdev_queue * dev_queue;
    struct net_rate_estimator * rate_est;
    struct gnet_stats_basic_cpu * cpu_bstats;
    struct gnet_stats_queue * cpu_qstats;
    int padded;
    refcount_t refcnt;
    struct sk_buff_head gso_skb;
    struct qdisc_skb_head q;
    struct gnet_stats_basic_packed bstats;
    seqcount_t running;
    struct gnet_stats_queue qstats;
    long unsigned int state;
    struct Qdisc * next_sched;
    struct sk_buff_head skb_bad_txq;
    spinlock_t busylock;
    spinlock_t seqlock;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct Qdisc {
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    unsigned int flags;
    u32 limit;
    const struct Qdisc_ops * ops;
    struct qdisc_size_table * stab;
    struct hlist_node hash;
    u32 handle;
    u32 parent;
    struct netdev_queue * dev_queue;
    struct net_rate_estimator * rate_est;
    struct gnet_stats_basic_cpu * cpu_bstats;
    struct gnet_stats_queue * cpu_qstats;
    int padded;
    refcount_t refcnt;
    struct sk_buff_head gso_skb;
    struct qdisc_skb_head q;
    struct gnet_stats_basic_packed bstats;
    seqcount_t running;
    struct gnet_stats_queue qstats;
    long unsigned int state;
    struct Qdisc * next_sched;
    struct sk_buff_head skb_bad_txq;
    spinlock_t busylock;
    spinlock_t seqlock;
    bool empty;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct Qdisc {
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    unsigned int flags;
    u32 limit;
    const struct Qdisc_ops * ops;
    struct qdisc_size_table * stab;
    struct hlist_node hash;
    u32 handle;
    u32 parent;
    struct netdev_queue * dev_queue;
    struct net_rate_estimator * rate_est;
    struct gnet_stats_basic_cpu * cpu_bstats;
    struct gnet_stats_queue * cpu_qstats;
    int padded;
    refcount_t refcnt;
    struct sk_buff_head gso_skb;
    struct qdisc_skb_head q;
    struct gnet_stats_basic_packed bstats;
    seqcount_t running;
    struct gnet_stats_queue qstats;
    long unsigned int state;
    struct Qdisc * next_sched;
    struct sk_buff_head skb_bad_txq;
    spinlock_t busylock;
    spinlock_t seqlock;
    bool empty;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct Qdisc {
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    unsigned int flags;
    u32 limit;
    const struct Qdisc_ops * ops;
    struct qdisc_size_table * stab;
    struct hlist_node hash;
    u32 handle;
    u32 parent;
    struct netdev_queue * dev_queue;
    struct net_rate_estimator * rate_est;
    struct gnet_stats_basic_cpu * cpu_bstats;
    struct gnet_stats_queue * cpu_qstats;
    int padded;
    refcount_t refcnt;
    struct sk_buff_head gso_skb;
    struct qdisc_skb_head q;
    struct gnet_stats_basic_packed bstats;
    seqcount_t running;
    struct gnet_stats_queue qstats;
    long unsigned int state;
    struct Qdisc * next_sched;
    struct sk_buff_head skb_bad_txq;
    spinlock_t busylock;
    spinlock_t seqlock;
    bool empty;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct Qdisc {
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    unsigned int flags;
    u32 limit;
    const struct Qdisc_ops * ops;
    struct qdisc_size_table * stab;
    struct hlist_node hash;
    u32 handle;
    u32 parent;
    struct netdev_queue * dev_queue;
    struct net_rate_estimator * rate_est;
    struct gnet_stats_basic_cpu * cpu_bstats;
    struct gnet_stats_queue * cpu_qstats;
    int pad;
    refcount_t refcnt;
    struct sk_buff_head gso_skb;
    struct qdisc_skb_head q;
    struct gnet_stats_basic_packed bstats;
    seqcount_t running;
    struct gnet_stats_queue qstats;
    long unsigned int state;
    struct Qdisc * next_sched;
    struct sk_buff_head skb_bad_txq;
    spinlock_t busylock;
    spinlock_t seqlock;
    bool empty;
    struct callback_head rcu;
    long int[0] privdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct Qdisc {
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    unsigned int flags;
    u32 limit;
    const struct Qdisc_ops * ops;
    struct qdisc_size_table * stab;
    struct hlist_node hash;
    u32 handle;
    u32 parent;
    struct netdev_queue * dev_queue;
    struct net_rate_estimator * rate_est;
    struct gnet_stats_basic_cpu * cpu_bstats;
    struct gnet_stats_queue * cpu_qstats;
    int pad;
    refcount_t refcnt;
    struct sk_buff_head gso_skb;
    struct qdisc_skb_head q;
    struct gnet_stats_basic_packed bstats;
    seqcount_t running;
    struct gnet_stats_queue qstats;
    long unsigned int state;
    struct Qdisc * next_sched;
    struct sk_buff_head skb_bad_txq;
    spinlock_t busylock;
    spinlock_t seqlock;
    bool empty;
    struct callback_head rcu;
    long int[0] privdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct Qdisc {
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    unsigned int flags;
    u32 limit;
    const struct Qdisc_ops * ops;
    struct qdisc_size_table * stab;
    struct hlist_node hash;
    u32 handle;
    u32 parent;
    struct netdev_queue * dev_queue;
    struct net_rate_estimator * rate_est;
    struct gnet_stats_basic_cpu * cpu_bstats;
    struct gnet_stats_queue * cpu_qstats;
    int pad;
    refcount_t refcnt;
    struct sk_buff_head gso_skb;
    struct qdisc_skb_head q;
    struct gnet_stats_basic_packed bstats;
    seqcount_t running;
    struct gnet_stats_queue qstats;
    long unsigned int state;
    struct Qdisc * next_sched;
    struct sk_buff_head skb_bad_txq;
    spinlock_t busylock;
    spinlock_t seqlock;
    struct callback_head rcu;
    long int[0] privdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct Qdisc {
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    unsigned int flags;
    u32 limit;
    const struct Qdisc_ops * ops;
    struct qdisc_size_table * stab;
    struct hlist_node hash;
    u32 handle;
    u32 parent;
    struct netdev_queue * dev_queue;
    struct net_rate_estimator * rate_est;
    struct gnet_stats_basic_sync * cpu_bstats;
    struct gnet_stats_queue * cpu_qstats;
    int pad;
    refcount_t refcnt;
    struct sk_buff_head gso_skb;
    struct qdisc_skb_head q;
    struct gnet_stats_basic_sync bstats;
    struct gnet_stats_queue qstats;
    long unsigned int state;
    long unsigned int state2;
    struct Qdisc * next_sched;
    struct sk_buff_head skb_bad_txq;
    spinlock_t busylock;
    spinlock_t seqlock;
    struct callback_head rcu;
    netdevice_tracker dev_tracker;
    long int[0] privdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct Qdisc {
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    unsigned int flags;
    u32 limit;
    const struct Qdisc_ops * ops;
    struct qdisc_size_table * stab;
    struct hlist_node hash;
    u32 handle;
    u32 parent;
    struct netdev_queue * dev_queue;
    struct net_rate_estimator * rate_est;
    struct gnet_stats_basic_sync * cpu_bstats;
    struct gnet_stats_queue * cpu_qstats;
    int pad;
    refcount_t refcnt;
    struct sk_buff_head gso_skb;
    struct qdisc_skb_head q;
    struct gnet_stats_basic_sync bstats;
    struct gnet_stats_queue qstats;
    long unsigned int state;
    long unsigned int state2;
    struct Qdisc * next_sched;
    struct sk_buff_head skb_bad_txq;
    spinlock_t busylock;
    spinlock_t seqlock;
    struct callback_head rcu;
    netdevice_tracker dev_tracker;
    long int[0] privdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct Qdisc {
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    unsigned int flags;
    u32 limit;
    const struct Qdisc_ops * ops;
    struct qdisc_size_table * stab;
    struct hlist_node hash;
    u32 handle;
    u32 parent;
    struct netdev_queue * dev_queue;
    struct net_rate_estimator * rate_est;
    struct gnet_stats_basic_sync * cpu_bstats;
    struct gnet_stats_queue * cpu_qstats;
    int pad;
    refcount_t refcnt;
    struct sk_buff_head gso_skb;
    struct qdisc_skb_head q;
    struct gnet_stats_basic_sync bstats;
    struct gnet_stats_queue qstats;
    long unsigned int state;
    long unsigned int state2;
    struct Qdisc * next_sched;
    struct sk_buff_head skb_bad_txq;
    spinlock_t busylock;
    spinlock_t seqlock;
    struct callback_head rcu;
    netdevice_tracker dev_tracker;
    long int[0] privdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct Qdisc {
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    unsigned int flags;
    u32 limit;
    const struct Qdisc_ops * ops;
    struct qdisc_size_table * stab;
    struct hlist_node hash;
    u32 handle;
    u32 parent;
    struct netdev_queue * dev_queue;
    struct net_rate_estimator * rate_est;
    struct gnet_stats_basic_sync * cpu_bstats;
    struct gnet_stats_queue * cpu_qstats;
    int pad;
    refcount_t refcnt;
    struct sk_buff_head gso_skb;
    struct qdisc_skb_head q;
    struct gnet_stats_basic_sync bstats;
    struct gnet_stats_queue qstats;
    long unsigned int state;
    long unsigned int state2;
    struct Qdisc * next_sched;
    struct sk_buff_head skb_bad_txq;
    spinlock_t busylock;
    spinlock_t seqlock;
    struct callback_head rcu;
    netdevice_tracker dev_tracker;
    long int[0] privdata;
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
struct Qdisc {
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    unsigned int flags;
    u32 limit;
    const struct Qdisc_ops * ops;
    struct qdisc_size_table * stab;
    struct hlist_node hash;
    u32 handle;
    u32 parent;
    struct netdev_queue * dev_queue;
    struct net_rate_estimator * rate_est;
    struct gnet_stats_basic_cpu * cpu_bstats;
    struct gnet_stats_queue * cpu_qstats;
    int padded;
    refcount_t refcnt;
    struct sk_buff_head gso_skb;
    struct qdisc_skb_head q;
    struct gnet_stats_basic_packed bstats;
    seqcount_t running;
    struct gnet_stats_queue qstats;
    long unsigned int state;
    struct Qdisc * next_sched;
    struct sk_buff_head skb_bad_txq;
    spinlock_t busylock;
    spinlock_t seqlock;
    bool empty;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct Qdisc {
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    unsigned int flags;
    u32 limit;
    const struct Qdisc_ops * ops;
    struct qdisc_size_table * stab;
    struct hlist_node hash;
    u32 handle;
    u32 parent;
    struct netdev_queue * dev_queue;
    struct net_rate_estimator * rate_est;
    struct gnet_stats_basic_cpu * cpu_bstats;
    struct gnet_stats_queue * cpu_qstats;
    int padded;
    refcount_t refcnt;
    struct sk_buff_head gso_skb;
    struct qdisc_skb_head q;
    struct gnet_stats_basic_packed bstats;
    seqcount_t running;
    struct gnet_stats_queue qstats;
    long unsigned int state;
    struct Qdisc * next_sched;
    struct sk_buff_head skb_bad_txq;
    spinlock_t busylock;
    spinlock_t seqlock;
    bool empty;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct Qdisc {
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    unsigned int flags;
    u32 limit;
    const struct Qdisc_ops * ops;
    struct qdisc_size_table * stab;
    struct hlist_node hash;
    u32 handle;
    u32 parent;
    struct netdev_queue * dev_queue;
    struct net_rate_estimator * rate_est;
    struct gnet_stats_basic_cpu * cpu_bstats;
    struct gnet_stats_queue * cpu_qstats;
    int padded;
    refcount_t refcnt;
    struct sk_buff_head gso_skb;
    struct qdisc_skb_head q;
    struct gnet_stats_basic_packed bstats;
    seqcount_t running;
    struct gnet_stats_queue qstats;
    long unsigned int state;
    struct Qdisc * next_sched;
    struct sk_buff_head skb_bad_txq;
    spinlock_t busylock;
    spinlock_t seqlock;
    bool empty;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct Qdisc {
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    unsigned int flags;
    u32 limit;
    const struct Qdisc_ops * ops;
    struct qdisc_size_table * stab;
    struct hlist_node hash;
    u32 handle;
    u32 parent;
    struct netdev_queue * dev_queue;
    struct net_rate_estimator * rate_est;
    struct gnet_stats_basic_cpu * cpu_bstats;
    struct gnet_stats_queue * cpu_qstats;
    int padded;
    refcount_t refcnt;
    struct sk_buff_head gso_skb;
    struct qdisc_skb_head q;
    struct gnet_stats_basic_packed bstats;
    seqcount_t running;
    struct gnet_stats_queue qstats;
    long unsigned int state;
    struct Qdisc * next_sched;
    struct sk_buff_head skb_bad_txq;
    spinlock_t busylock;
    spinlock_t seqlock;
    bool empty;
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
struct Qdisc {
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    unsigned int flags;
    u32 limit;
    const struct Qdisc_ops * ops;
    struct qdisc_size_table * stab;
    struct hlist_node hash;
    u32 handle;
    u32 parent;
    struct netdev_queue * dev_queue;
    struct net_rate_estimator * rate_est;
    struct gnet_stats_basic_cpu * cpu_bstats;
    struct gnet_stats_queue * cpu_qstats;
    int padded;
    refcount_t refcnt;
    struct sk_buff_head gso_skb;
    struct qdisc_skb_head q;
    struct gnet_stats_basic_packed bstats;
    seqcount_t running;
    struct gnet_stats_queue qstats;
    long unsigned int state;
    struct Qdisc * next_sched;
    struct sk_buff_head skb_bad_txq;
    spinlock_t busylock;
    spinlock_t seqlock;
    bool empty;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct Qdisc {
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    unsigned int flags;
    u32 limit;
    const struct Qdisc_ops * ops;
    struct qdisc_size_table * stab;
    struct hlist_node hash;
    u32 handle;
    u32 parent;
    struct netdev_queue * dev_queue;
    struct net_rate_estimator * rate_est;
    struct gnet_stats_basic_cpu * cpu_bstats;
    struct gnet_stats_queue * cpu_qstats;
    int padded;
    refcount_t refcnt;
    struct sk_buff_head gso_skb;
    struct qdisc_skb_head q;
    struct gnet_stats_basic_packed bstats;
    seqcount_t running;
    struct gnet_stats_queue qstats;
    long unsigned int state;
    struct Qdisc * next_sched;
    struct sk_buff_head skb_bad_txq;
    spinlock_t busylock;
    spinlock_t seqlock;
    bool empty;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct Qdisc {
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    unsigned int flags;
    u32 limit;
    const struct Qdisc_ops * ops;
    struct qdisc_size_table * stab;
    struct hlist_node hash;
    u32 handle;
    u32 parent;
    struct netdev_queue * dev_queue;
    struct net_rate_estimator * rate_est;
    struct gnet_stats_basic_cpu * cpu_bstats;
    struct gnet_stats_queue * cpu_qstats;
    int padded;
    refcount_t refcnt;
    struct sk_buff_head gso_skb;
    struct qdisc_skb_head q;
    struct gnet_stats_basic_packed bstats;
    seqcount_t running;
    struct gnet_stats_queue qstats;
    long unsigned int state;
    struct Qdisc * next_sched;
    struct sk_buff_head skb_bad_txq;
    spinlock_t busylock;
    spinlock_t seqlock;
    bool empty;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct Qdisc {
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    unsigned int flags;
    u32 limit;
    const struct Qdisc_ops * ops;
    struct qdisc_size_table * stab;
    struct hlist_node hash;
    u32 handle;
    u32 parent;
    struct netdev_queue * dev_queue;
    struct net_rate_estimator * rate_est;
    struct gnet_stats_basic_cpu * cpu_bstats;
    struct gnet_stats_queue * cpu_qstats;
    int padded;
    refcount_t refcnt;
    struct sk_buff_head gso_skb;
    struct qdisc_skb_head q;
    struct gnet_stats_basic_packed bstats;
    seqcount_t running;
    struct gnet_stats_queue qstats;
    long unsigned int state;
    struct Qdisc * next_sched;
    struct sk_buff_head skb_bad_txq;
    spinlock_t busylock;
    spinlock_t seqlock;
    bool empty;
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
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>seqcount_t running</code>
</li>
<li>
<b>Field added. </b>
<code>struct sk_buff * skb_bad_txq</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct sk_buff *, struct Qdisc *) reshape_fail</code>
</li>
<li>
<b>Field removed. </b>
<code>struct Qdisc * __parent</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int __state</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct sk_buff *, struct Qdisc *) enqueue</code> ➡️ <code>int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue</code>
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
<code>struct hlist_node hash</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head list</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct gnet_stats_rate_est64 rate_est</code> ➡️ <code>struct net_rate_estimator * rate_est</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct sk_buff_head q</code> ➡️ <code>struct qdisc_skb_head q</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>atomic_t refcnt</code> ➡️ <code>refcount_t refcnt</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>void * u32_node</code>
</li>
<li>
<b>Field removed. </b>
<code>struct callback_head callback_head</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>spinlock_t seqlock</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct sk_buff * gso_skb</code> ➡️ <code>struct sk_buff_head gso_skb</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct sk_buff * skb_bad_txq</code> ➡️ <code>struct sk_buff_head skb_bad_txq</code>
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
<code>struct callback_head rcu</code>
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
<code>bool empty</code>
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
<code>int pad</code>
</li>
<li>
<b>Field added. </b>
<code>long int[0] privdata</code>
</li>
<li>
<b>Field removed. </b>
<code>int padded</code>
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
<b>Field removed. </b>
<code>bool empty</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int state2</code>
</li>
<li>
<b>Field added. </b>
<code>netdevice_tracker dev_tracker</code>
</li>
<li>
<b>Field removed. </b>
<code>seqcount_t running</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct gnet_stats_basic_cpu * cpu_bstats</code> ➡️ <code>struct gnet_stats_basic_sync * cpu_bstats</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct gnet_stats_basic_packed bstats</code> ➡️ <code>struct gnet_stats_basic_sync bstats</code>
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
