# Struct: <code>worker</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct worker {
    struct list_head entry;
    struct hlist_node hentry;
    struct work_struct * current_work;
    work_func_t current_func;
    struct pool_workqueue * current_pwq;
    bool desc_valid;
    struct list_head scheduled;
    struct task_struct * task;
    struct worker_pool * pool;
    struct list_head node;
    long unsigned int last_active;
    unsigned int flags;
    int id;
    char[24] desc;
    struct workqueue_struct * rescue_wq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct worker {
    struct list_head entry;
    struct hlist_node hentry;
    struct work_struct * current_work;
    work_func_t current_func;
    struct pool_workqueue * current_pwq;
    bool desc_valid;
    struct list_head scheduled;
    struct task_struct * task;
    struct worker_pool * pool;
    struct list_head node;
    long unsigned int last_active;
    unsigned int flags;
    int id;
    char[24] desc;
    struct workqueue_struct * rescue_wq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct worker {
    struct list_head entry;
    struct hlist_node hentry;
    struct work_struct * current_work;
    work_func_t current_func;
    struct pool_workqueue * current_pwq;
    bool desc_valid;
    struct list_head scheduled;
    struct task_struct * task;
    struct worker_pool * pool;
    struct list_head node;
    long unsigned int last_active;
    unsigned int flags;
    int id;
    char[24] desc;
    struct workqueue_struct * rescue_wq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct worker {
    struct list_head entry;
    struct hlist_node hentry;
    struct work_struct * current_work;
    work_func_t current_func;
    struct pool_workqueue * current_pwq;
    bool desc_valid;
    struct list_head scheduled;
    struct task_struct * task;
    struct worker_pool * pool;
    struct list_head node;
    long unsigned int last_active;
    unsigned int flags;
    int id;
    char[24] desc;
    struct workqueue_struct * rescue_wq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct worker {
    struct list_head entry;
    struct hlist_node hentry;
    struct work_struct * current_work;
    work_func_t current_func;
    struct pool_workqueue * current_pwq;
    bool desc_valid;
    struct list_head scheduled;
    struct task_struct * task;
    struct worker_pool * pool;
    struct list_head node;
    long unsigned int last_active;
    unsigned int flags;
    int id;
    char[24] desc;
    struct workqueue_struct * rescue_wq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct worker {
    struct list_head entry;
    struct hlist_node hentry;
    struct work_struct * current_work;
    work_func_t current_func;
    struct pool_workqueue * current_pwq;
    struct list_head scheduled;
    struct task_struct * task;
    struct worker_pool * pool;
    struct list_head node;
    long unsigned int last_active;
    unsigned int flags;
    int id;
    char[24] desc;
    struct workqueue_struct * rescue_wq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct worker {
    struct list_head entry;
    struct hlist_node hentry;
    struct work_struct * current_work;
    work_func_t current_func;
    struct pool_workqueue * current_pwq;
    struct list_head scheduled;
    struct task_struct * task;
    struct worker_pool * pool;
    struct list_head node;
    long unsigned int last_active;
    unsigned int flags;
    int id;
    char[24] desc;
    struct workqueue_struct * rescue_wq;
    work_func_t last_func;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct worker {
    struct list_head entry;
    struct hlist_node hentry;
    struct work_struct * current_work;
    work_func_t current_func;
    struct pool_workqueue * current_pwq;
    struct list_head scheduled;
    struct task_struct * task;
    struct worker_pool * pool;
    struct list_head node;
    long unsigned int last_active;
    unsigned int flags;
    int id;
    int sleeping;
    char[24] desc;
    struct workqueue_struct * rescue_wq;
    work_func_t last_func;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct worker {
    struct list_head entry;
    struct hlist_node hentry;
    struct work_struct * current_work;
    work_func_t current_func;
    struct pool_workqueue * current_pwq;
    struct list_head scheduled;
    struct task_struct * task;
    struct worker_pool * pool;
    struct list_head node;
    long unsigned int last_active;
    unsigned int flags;
    int id;
    int sleeping;
    char[24] desc;
    struct workqueue_struct * rescue_wq;
    work_func_t last_func;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct worker {
    struct list_head entry;
    struct hlist_node hentry;
    struct work_struct * current_work;
    work_func_t current_func;
    struct pool_workqueue * current_pwq;
    struct list_head scheduled;
    struct task_struct * task;
    struct worker_pool * pool;
    struct list_head node;
    long unsigned int last_active;
    unsigned int flags;
    int id;
    int sleeping;
    char[24] desc;
    struct workqueue_struct * rescue_wq;
    work_func_t last_func;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct worker {
    struct list_head entry;
    struct hlist_node hentry;
    struct work_struct * current_work;
    work_func_t current_func;
    struct pool_workqueue * current_pwq;
    struct list_head scheduled;
    struct task_struct * task;
    struct worker_pool * pool;
    struct list_head node;
    long unsigned int last_active;
    unsigned int flags;
    int id;
    int sleeping;
    char[24] desc;
    struct workqueue_struct * rescue_wq;
    work_func_t last_func;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct worker {
    struct list_head entry;
    struct hlist_node hentry;
    struct work_struct * current_work;
    work_func_t current_func;
    struct pool_workqueue * current_pwq;
    struct list_head scheduled;
    struct task_struct * task;
    struct worker_pool * pool;
    struct list_head node;
    long unsigned int last_active;
    unsigned int flags;
    int id;
    int sleeping;
    char[24] desc;
    struct workqueue_struct * rescue_wq;
    work_func_t last_func;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct worker {
    struct list_head entry;
    struct hlist_node hentry;
    struct work_struct * current_work;
    work_func_t current_func;
    struct pool_workqueue * current_pwq;
    unsigned int current_color;
    struct list_head scheduled;
    struct task_struct * task;
    struct worker_pool * pool;
    struct list_head node;
    long unsigned int last_active;
    unsigned int flags;
    int id;
    int sleeping;
    char[24] desc;
    struct workqueue_struct * rescue_wq;
    work_func_t last_func;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct worker {
    struct list_head entry;
    struct hlist_node hentry;
    struct work_struct * current_work;
    work_func_t current_func;
    struct pool_workqueue * current_pwq;
    unsigned int current_color;
    struct list_head scheduled;
    struct task_struct * task;
    struct worker_pool * pool;
    struct list_head node;
    long unsigned int last_active;
    unsigned int flags;
    int id;
    int sleeping;
    char[24] desc;
    struct workqueue_struct * rescue_wq;
    work_func_t last_func;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct worker {
    struct list_head entry;
    struct hlist_node hentry;
    struct work_struct * current_work;
    work_func_t current_func;
    struct pool_workqueue * current_pwq;
    unsigned int current_color;
    struct list_head scheduled;
    struct task_struct * task;
    struct worker_pool * pool;
    struct list_head node;
    long unsigned int last_active;
    unsigned int flags;
    int id;
    int sleeping;
    char[24] desc;
    struct workqueue_struct * rescue_wq;
    work_func_t last_func;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct worker {
    struct list_head entry;
    struct hlist_node hentry;
    struct work_struct * current_work;
    work_func_t current_func;
    struct pool_workqueue * current_pwq;
    u64 current_at;
    unsigned int current_color;
    int sleeping;
    work_func_t last_func;
    struct list_head scheduled;
    struct task_struct * task;
    struct worker_pool * pool;
    struct list_head node;
    long unsigned int last_active;
    unsigned int flags;
    int id;
    char[24] desc;
    struct workqueue_struct * rescue_wq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct worker {
    struct list_head entry;
    struct hlist_node hentry;
    struct work_struct * current_work;
    work_func_t current_func;
    struct pool_workqueue * current_pwq;
    u64 current_at;
    unsigned int current_color;
    int sleeping;
    work_func_t last_func;
    struct list_head scheduled;
    struct task_struct * task;
    struct worker_pool * pool;
    struct list_head node;
    long unsigned int last_active;
    unsigned int flags;
    int id;
    char[24] desc;
    struct workqueue_struct * rescue_wq;
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
struct worker {
    struct list_head entry;
    struct hlist_node hentry;
    struct work_struct * current_work;
    work_func_t current_func;
    struct pool_workqueue * current_pwq;
    struct list_head scheduled;
    struct task_struct * task;
    struct worker_pool * pool;
    struct list_head node;
    long unsigned int last_active;
    unsigned int flags;
    int id;
    int sleeping;
    char[24] desc;
    struct workqueue_struct * rescue_wq;
    work_func_t last_func;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct worker {
    struct list_head entry;
    struct hlist_node hentry;
    struct work_struct * current_work;
    work_func_t current_func;
    struct pool_workqueue * current_pwq;
    struct list_head scheduled;
    struct task_struct * task;
    struct worker_pool * pool;
    struct list_head node;
    long unsigned int last_active;
    unsigned int flags;
    int id;
    int sleeping;
    char[24] desc;
    struct workqueue_struct * rescue_wq;
    work_func_t last_func;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct worker {
    struct list_head entry;
    struct hlist_node hentry;
    struct work_struct * current_work;
    work_func_t current_func;
    struct pool_workqueue * current_pwq;
    struct list_head scheduled;
    struct task_struct * task;
    struct worker_pool * pool;
    struct list_head node;
    long unsigned int last_active;
    unsigned int flags;
    int id;
    int sleeping;
    char[24] desc;
    struct workqueue_struct * rescue_wq;
    work_func_t last_func;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct worker {
    struct list_head entry;
    struct hlist_node hentry;
    struct work_struct * current_work;
    work_func_t current_func;
    struct pool_workqueue * current_pwq;
    struct list_head scheduled;
    struct task_struct * task;
    struct worker_pool * pool;
    struct list_head node;
    long unsigned int last_active;
    unsigned int flags;
    int id;
    int sleeping;
    char[24] desc;
    struct workqueue_struct * rescue_wq;
    work_func_t last_func;
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
struct worker {
    struct list_head entry;
    struct hlist_node hentry;
    struct work_struct * current_work;
    work_func_t current_func;
    struct pool_workqueue * current_pwq;
    struct list_head scheduled;
    struct task_struct * task;
    struct worker_pool * pool;
    struct list_head node;
    long unsigned int last_active;
    unsigned int flags;
    int id;
    int sleeping;
    char[24] desc;
    struct workqueue_struct * rescue_wq;
    work_func_t last_func;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct worker {
    struct list_head entry;
    struct hlist_node hentry;
    struct work_struct * current_work;
    work_func_t current_func;
    struct pool_workqueue * current_pwq;
    struct list_head scheduled;
    struct task_struct * task;
    struct worker_pool * pool;
    struct list_head node;
    long unsigned int last_active;
    unsigned int flags;
    int id;
    int sleeping;
    char[24] desc;
    struct workqueue_struct * rescue_wq;
    work_func_t last_func;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct worker {
    struct list_head entry;
    struct hlist_node hentry;
    struct work_struct * current_work;
    work_func_t current_func;
    struct pool_workqueue * current_pwq;
    struct list_head scheduled;
    struct task_struct * task;
    struct worker_pool * pool;
    struct list_head node;
    long unsigned int last_active;
    unsigned int flags;
    int id;
    int sleeping;
    char[24] desc;
    struct workqueue_struct * rescue_wq;
    work_func_t last_func;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct worker {
    struct list_head entry;
    struct hlist_node hentry;
    struct work_struct * current_work;
    work_func_t current_func;
    struct pool_workqueue * current_pwq;
    struct list_head scheduled;
    struct task_struct * task;
    struct worker_pool * pool;
    struct list_head node;
    long unsigned int last_active;
    unsigned int flags;
    int id;
    int sleeping;
    char[24] desc;
    struct workqueue_struct * rescue_wq;
    work_func_t last_func;
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>bool desc_valid</code>
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
<code>work_func_t last_func</code>
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
<code>int sleeping</code>
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int current_color</code>
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
<code>u64 current_at</code>
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
