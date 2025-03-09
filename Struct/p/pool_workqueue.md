# Struct: <code>pool_workqueue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct pool_workqueue {
    struct worker_pool * pool;
    struct workqueue_struct * wq;
    int work_color;
    int flush_color;
    int refcnt;
    int[15] nr_in_flight;
    int nr_active;
    int max_active;
    struct list_head delayed_works;
    struct list_head pwqs_node;
    struct list_head mayday_node;
    struct work_struct unbound_release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct pool_workqueue {
    struct worker_pool * pool;
    struct workqueue_struct * wq;
    int work_color;
    int flush_color;
    int refcnt;
    int[15] nr_in_flight;
    int nr_active;
    int max_active;
    struct list_head delayed_works;
    struct list_head pwqs_node;
    struct list_head mayday_node;
    struct work_struct unbound_release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct pool_workqueue {
    struct worker_pool * pool;
    struct workqueue_struct * wq;
    int work_color;
    int flush_color;
    int refcnt;
    int[15] nr_in_flight;
    int nr_active;
    int max_active;
    struct list_head delayed_works;
    struct list_head pwqs_node;
    struct list_head mayday_node;
    struct work_struct unbound_release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct pool_workqueue {
    struct worker_pool * pool;
    struct workqueue_struct * wq;
    int work_color;
    int flush_color;
    int refcnt;
    int[15] nr_in_flight;
    int nr_active;
    int max_active;
    struct list_head delayed_works;
    struct list_head pwqs_node;
    struct list_head mayday_node;
    struct work_struct unbound_release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct pool_workqueue {
    struct worker_pool * pool;
    struct workqueue_struct * wq;
    int work_color;
    int flush_color;
    int refcnt;
    int[15] nr_in_flight;
    int nr_active;
    int max_active;
    struct list_head delayed_works;
    struct list_head pwqs_node;
    struct list_head mayday_node;
    struct work_struct unbound_release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct pool_workqueue {
    struct worker_pool * pool;
    struct workqueue_struct * wq;
    int work_color;
    int flush_color;
    int refcnt;
    int[15] nr_in_flight;
    int nr_active;
    int max_active;
    struct list_head delayed_works;
    struct list_head pwqs_node;
    struct list_head mayday_node;
    struct work_struct unbound_release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct pool_workqueue {
    struct worker_pool * pool;
    struct workqueue_struct * wq;
    int work_color;
    int flush_color;
    int refcnt;
    int[15] nr_in_flight;
    int nr_active;
    int max_active;
    struct list_head delayed_works;
    struct list_head pwqs_node;
    struct list_head mayday_node;
    struct work_struct unbound_release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct pool_workqueue {
    struct worker_pool * pool;
    struct workqueue_struct * wq;
    int work_color;
    int flush_color;
    int refcnt;
    int[15] nr_in_flight;
    int nr_active;
    int max_active;
    struct list_head delayed_works;
    struct list_head pwqs_node;
    struct list_head mayday_node;
    struct work_struct unbound_release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct pool_workqueue {
    struct worker_pool * pool;
    struct workqueue_struct * wq;
    int work_color;
    int flush_color;
    int refcnt;
    int[15] nr_in_flight;
    int nr_active;
    int max_active;
    struct list_head delayed_works;
    struct list_head pwqs_node;
    struct list_head mayday_node;
    struct work_struct unbound_release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct pool_workqueue {
    struct worker_pool * pool;
    struct workqueue_struct * wq;
    int work_color;
    int flush_color;
    int refcnt;
    int[15] nr_in_flight;
    int nr_active;
    int max_active;
    struct list_head delayed_works;
    struct list_head pwqs_node;
    struct list_head mayday_node;
    struct work_struct unbound_release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct pool_workqueue {
    struct worker_pool * pool;
    struct workqueue_struct * wq;
    int work_color;
    int flush_color;
    int refcnt;
    int[15] nr_in_flight;
    int nr_active;
    int max_active;
    struct list_head delayed_works;
    struct list_head pwqs_node;
    struct list_head mayday_node;
    struct work_struct unbound_release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct pool_workqueue {
    struct worker_pool * pool;
    struct workqueue_struct * wq;
    int work_color;
    int flush_color;
    int refcnt;
    int[15] nr_in_flight;
    int nr_active;
    int max_active;
    struct list_head delayed_works;
    struct list_head pwqs_node;
    struct list_head mayday_node;
    struct work_struct unbound_release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct pool_workqueue {
    struct worker_pool * pool;
    struct workqueue_struct * wq;
    int work_color;
    int flush_color;
    int refcnt;
    int[16] nr_in_flight;
    int nr_active;
    int max_active;
    struct list_head inactive_works;
    struct list_head pwqs_node;
    struct list_head mayday_node;
    struct work_struct unbound_release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct pool_workqueue {
    struct worker_pool * pool;
    struct workqueue_struct * wq;
    int work_color;
    int flush_color;
    int refcnt;
    int[16] nr_in_flight;
    int nr_active;
    int max_active;
    struct list_head inactive_works;
    struct list_head pwqs_node;
    struct list_head mayday_node;
    struct work_struct unbound_release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct pool_workqueue {
    struct worker_pool * pool;
    struct workqueue_struct * wq;
    int work_color;
    int flush_color;
    int refcnt;
    int[16] nr_in_flight;
    int nr_active;
    int max_active;
    struct list_head inactive_works;
    struct list_head pwqs_node;
    struct list_head mayday_node;
    struct work_struct unbound_release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct pool_workqueue {
    struct worker_pool * pool;
    struct workqueue_struct * wq;
    int work_color;
    int flush_color;
    int refcnt;
    int[16] nr_in_flight;
    int nr_active;
    int max_active;
    struct list_head inactive_works;
    struct list_head pwqs_node;
    struct list_head mayday_node;
    u64[7] stats;
    struct work_struct unbound_release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct pool_workqueue {
    struct worker_pool * pool;
    struct workqueue_struct * wq;
    int work_color;
    int flush_color;
    int refcnt;
    int[16] nr_in_flight;
    int nr_active;
    int max_active;
    struct list_head inactive_works;
    struct list_head pwqs_node;
    struct list_head mayday_node;
    u64[8] stats;
    struct kthread_work release_work;
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
struct pool_workqueue {
    struct worker_pool * pool;
    struct workqueue_struct * wq;
    int work_color;
    int flush_color;
    int refcnt;
    int[15] nr_in_flight;
    int nr_active;
    int max_active;
    struct list_head delayed_works;
    struct list_head pwqs_node;
    struct list_head mayday_node;
    struct work_struct unbound_release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct pool_workqueue {
    struct worker_pool * pool;
    struct workqueue_struct * wq;
    int work_color;
    int flush_color;
    int refcnt;
    int[15] nr_in_flight;
    int nr_active;
    int max_active;
    struct list_head delayed_works;
    struct list_head pwqs_node;
    struct list_head mayday_node;
    struct work_struct unbound_release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct pool_workqueue {
    struct worker_pool * pool;
    struct workqueue_struct * wq;
    int work_color;
    int flush_color;
    int refcnt;
    int[15] nr_in_flight;
    int nr_active;
    int max_active;
    struct list_head delayed_works;
    struct list_head pwqs_node;
    struct list_head mayday_node;
    struct work_struct unbound_release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct pool_workqueue {
    struct worker_pool * pool;
    struct workqueue_struct * wq;
    int work_color;
    int flush_color;
    int refcnt;
    int[15] nr_in_flight;
    int nr_active;
    int max_active;
    struct list_head delayed_works;
    struct list_head pwqs_node;
    struct list_head mayday_node;
    struct work_struct unbound_release_work;
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
struct pool_workqueue {
    struct worker_pool * pool;
    struct workqueue_struct * wq;
    int work_color;
    int flush_color;
    int refcnt;
    int[15] nr_in_flight;
    int nr_active;
    int max_active;
    struct list_head delayed_works;
    struct list_head pwqs_node;
    struct list_head mayday_node;
    struct work_struct unbound_release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct pool_workqueue {
    struct worker_pool * pool;
    struct workqueue_struct * wq;
    int work_color;
    int flush_color;
    int refcnt;
    int[15] nr_in_flight;
    int nr_active;
    int max_active;
    struct list_head delayed_works;
    struct list_head pwqs_node;
    struct list_head mayday_node;
    struct work_struct unbound_release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct pool_workqueue {
    struct worker_pool * pool;
    struct workqueue_struct * wq;
    int work_color;
    int flush_color;
    int refcnt;
    int[15] nr_in_flight;
    int nr_active;
    int max_active;
    struct list_head delayed_works;
    struct list_head pwqs_node;
    struct list_head mayday_node;
    struct work_struct unbound_release_work;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct pool_workqueue {
    struct worker_pool * pool;
    struct workqueue_struct * wq;
    int work_color;
    int flush_color;
    int refcnt;
    int[15] nr_in_flight;
    int nr_active;
    int max_active;
    struct list_head delayed_works;
    struct list_head pwqs_node;
    struct list_head mayday_node;
    struct work_struct unbound_release_work;
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct list_head inactive_works</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head delayed_works</code>
</li>
<li>
<b>Field type changed. </b>
<code>int[15] nr_in_flight</code> ➡️ <code>int[16] nr_in_flight</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64[7] stats</code>
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
<code>struct kthread_work release_work</code>
</li>
<li>
<b>Field removed. </b>
<code>struct work_struct unbound_release_work</code>
</li>
<li>
<b>Field type changed. </b>
<code>u64[7] stats</code> ➡️ <code>u64[8] stats</code>
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
