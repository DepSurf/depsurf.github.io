# Struct: <code>kfree_rcu_cpu</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct kfree_rcu_cpu {
    struct callback_head * head;
    struct kfree_rcu_bulk_data * bhead;
    struct kfree_rcu_bulk_data * bcached;
    struct kfree_rcu_cpu_work[2] krw_arr;
    spinlock_t lock;
    struct delayed_work monitor_work;
    bool monitor_todo;
    bool initialized;
    int count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct kfree_rcu_cpu {
    struct callback_head * head;
    struct kvfree_rcu_bulk_data *[2] bkvhead;
    struct kfree_rcu_cpu_work[2] krw_arr;
    raw_spinlock_t lock;
    struct delayed_work monitor_work;
    bool monitor_todo;
    bool initialized;
    int count;
    struct work_struct page_cache_work;
    atomic_t work_in_progress;
    struct hrtimer hrtimer;
    struct llist_head bkvcache;
    int nr_bkv_objs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct kfree_rcu_cpu {
    struct callback_head * head;
    struct kvfree_rcu_bulk_data *[2] bkvhead;
    struct kfree_rcu_cpu_work[2] krw_arr;
    raw_spinlock_t lock;
    struct delayed_work monitor_work;
    bool monitor_todo;
    bool initialized;
    int count;
    struct work_struct page_cache_work;
    atomic_t work_in_progress;
    struct hrtimer hrtimer;
    struct llist_head bkvcache;
    int nr_bkv_objs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct kfree_rcu_cpu {
    struct callback_head * head;
    struct kvfree_rcu_bulk_data *[2] bkvhead;
    struct kfree_rcu_cpu_work[2] krw_arr;
    raw_spinlock_t lock;
    struct delayed_work monitor_work;
    bool monitor_todo;
    bool initialized;
    int count;
    struct delayed_work page_cache_work;
    atomic_t backoff_page_cache_fill;
    atomic_t work_in_progress;
    struct hrtimer hrtimer;
    struct llist_head bkvcache;
    int nr_bkv_objs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct kfree_rcu_cpu {
    struct callback_head * head;
    struct kvfree_rcu_bulk_data *[2] bkvhead;
    struct kfree_rcu_cpu_work[2] krw_arr;
    raw_spinlock_t lock;
    struct delayed_work monitor_work;
    bool monitor_todo;
    bool initialized;
    int count;
    struct delayed_work page_cache_work;
    atomic_t backoff_page_cache_fill;
    atomic_t work_in_progress;
    struct hrtimer hrtimer;
    struct llist_head bkvcache;
    int nr_bkv_objs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct kfree_rcu_cpu {
    struct callback_head * head;
    struct kvfree_rcu_bulk_data *[2] bkvhead;
    struct kfree_rcu_cpu_work[2] krw_arr;
    raw_spinlock_t lock;
    struct delayed_work monitor_work;
    bool initialized;
    int count;
    struct delayed_work page_cache_work;
    atomic_t backoff_page_cache_fill;
    atomic_t work_in_progress;
    struct hrtimer hrtimer;
    struct llist_head bkvcache;
    int nr_bkv_objs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct kfree_rcu_cpu {
    struct callback_head * head;
    long unsigned int head_gp_snap;
    atomic_t head_count;
    struct list_head[2] bulk_head;
    atomic_t[2] bulk_count;
    struct kfree_rcu_cpu_work[2] krw_arr;
    raw_spinlock_t lock;
    struct delayed_work monitor_work;
    bool initialized;
    struct delayed_work page_cache_work;
    atomic_t backoff_page_cache_fill;
    atomic_t work_in_progress;
    struct hrtimer hrtimer;
    struct llist_head bkvcache;
    int nr_bkv_objs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct kfree_rcu_cpu {
    struct callback_head * head;
    long unsigned int head_gp_snap;
    atomic_t head_count;
    struct list_head[2] bulk_head;
    atomic_t[2] bulk_count;
    struct kfree_rcu_cpu_work[2] krw_arr;
    raw_spinlock_t lock;
    struct delayed_work monitor_work;
    bool initialized;
    struct delayed_work page_cache_work;
    atomic_t backoff_page_cache_fill;
    atomic_t work_in_progress;
    struct hrtimer hrtimer;
    struct llist_head bkvcache;
    int nr_bkv_objs;
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct kfree_rcu_cpu {
    struct callback_head * head;
    struct kfree_rcu_bulk_data * bhead;
    struct kfree_rcu_bulk_data * bcached;
    struct kfree_rcu_cpu_work[2] krw_arr;
    spinlock_t lock;
    struct delayed_work monitor_work;
    bool monitor_todo;
    bool initialized;
    int count;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct kvfree_rcu_bulk_data *[2] bkvhead</code>
</li>
<li>
<b>Field added. </b>
<code>struct work_struct page_cache_work</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t work_in_progress</code>
</li>
<li>
<b>Field added. </b>
<code>struct hrtimer hrtimer</code>
</li>
<li>
<b>Field added. </b>
<code>struct llist_head bkvcache</code>
</li>
<li>
<b>Field added. </b>
<code>int nr_bkv_objs</code>
</li>
<li>
<b>Field removed. </b>
<code>struct kfree_rcu_bulk_data * bhead</code>
</li>
<li>
<b>Field removed. </b>
<code>struct kfree_rcu_bulk_data * bcached</code>
</li>
<li>
<b>Field type changed. </b>
<code>spinlock_t lock</code> ➡️ <code>raw_spinlock_t lock</code>
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
<code>atomic_t backoff_page_cache_fill</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct work_struct page_cache_work</code> ➡️ <code>struct delayed_work page_cache_work</code>
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
<b>Field removed. </b>
<code>bool monitor_todo</code>
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
<code>long unsigned int head_gp_snap</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t head_count</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head[2] bulk_head</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t[2] bulk_count</code>
</li>
<li>
<b>Field removed. </b>
<code>struct kvfree_rcu_bulk_data *[2] bkvhead</code>
</li>
<li>
<b>Field removed. </b>
<code>int count</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
