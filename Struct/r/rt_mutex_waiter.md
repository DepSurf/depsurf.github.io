# Struct: <code>rt_mutex_waiter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct rt_mutex_waiter {
    struct rb_node tree_entry;
    struct rb_node pi_tree_entry;
    struct task_struct * task;
    struct rt_mutex * lock;
    int prio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct rt_mutex_waiter {
    struct rb_node tree_entry;
    struct rb_node pi_tree_entry;
    struct task_struct * task;
    struct rt_mutex * lock;
    int prio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct rt_mutex_waiter {
    struct rb_node tree_entry;
    struct rb_node pi_tree_entry;
    struct task_struct * task;
    struct rt_mutex * lock;
    int prio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct rt_mutex_waiter {
    struct rb_node tree_entry;
    struct rb_node pi_tree_entry;
    struct task_struct * task;
    struct rt_mutex * lock;
    int prio;
    u64 deadline;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct rt_mutex_waiter {
    struct rb_node tree_entry;
    struct rb_node pi_tree_entry;
    struct task_struct * task;
    struct rt_mutex * lock;
    int prio;
    u64 deadline;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct rt_mutex_waiter {
    struct rb_node tree_entry;
    struct rb_node pi_tree_entry;
    struct task_struct * task;
    struct rt_mutex * lock;
    int prio;
    u64 deadline;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct rt_mutex_waiter {
    struct rb_node tree_entry;
    struct rb_node pi_tree_entry;
    struct task_struct * task;
    struct rt_mutex * lock;
    int prio;
    u64 deadline;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct rt_mutex_waiter {
    struct rb_node tree_entry;
    struct rb_node pi_tree_entry;
    struct task_struct * task;
    struct rt_mutex * lock;
    int prio;
    u64 deadline;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct rt_mutex_waiter {
    struct rb_node tree_entry;
    struct rb_node pi_tree_entry;
    struct task_struct * task;
    struct rt_mutex * lock;
    int prio;
    u64 deadline;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct rt_mutex_waiter {
    struct rb_node tree_entry;
    struct rb_node pi_tree_entry;
    struct task_struct * task;
    struct rt_mutex * lock;
    int prio;
    u64 deadline;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct rt_mutex_waiter {
    struct rb_node tree_entry;
    struct rb_node pi_tree_entry;
    struct task_struct * task;
    struct rt_mutex * lock;
    int prio;
    u64 deadline;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct rt_mutex_waiter {
    struct rb_node tree_entry;
    struct rb_node pi_tree_entry;
    struct task_struct * task;
    struct rt_mutex * lock;
    int prio;
    u64 deadline;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct rt_mutex_waiter {
    struct rb_node tree_entry;
    struct rb_node pi_tree_entry;
    struct task_struct * task;
    struct rt_mutex_base * lock;
    unsigned int wake_state;
    int prio;
    u64 deadline;
    struct ww_acquire_ctx * ww_ctx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct rt_mutex_waiter {
    struct rb_node tree_entry;
    struct rb_node pi_tree_entry;
    struct task_struct * task;
    struct rt_mutex_base * lock;
    unsigned int wake_state;
    int prio;
    u64 deadline;
    struct ww_acquire_ctx * ww_ctx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct rt_mutex_waiter {
    struct rb_node tree_entry;
    struct rb_node pi_tree_entry;
    struct task_struct * task;
    struct rt_mutex_base * lock;
    unsigned int wake_state;
    int prio;
    u64 deadline;
    struct ww_acquire_ctx * ww_ctx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct rt_mutex_waiter {
    struct rt_waiter_node tree;
    struct rt_waiter_node pi_tree;
    struct task_struct * task;
    struct rt_mutex_base * lock;
    unsigned int wake_state;
    struct ww_acquire_ctx * ww_ctx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct rt_mutex_waiter {
    struct rt_waiter_node tree;
    struct rt_waiter_node pi_tree;
    struct task_struct * task;
    struct rt_mutex_base * lock;
    unsigned int wake_state;
    struct ww_acquire_ctx * ww_ctx;
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
struct rt_mutex_waiter {
    struct rb_node tree_entry;
    struct rb_node pi_tree_entry;
    struct task_struct * task;
    struct rt_mutex * lock;
    int prio;
    u64 deadline;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct rt_mutex_waiter {
    struct rb_node tree_entry;
    struct rb_node pi_tree_entry;
    struct task_struct * task;
    struct rt_mutex * lock;
    int prio;
    u64 deadline;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct rt_mutex_waiter {
    struct rb_node tree_entry;
    struct rb_node pi_tree_entry;
    struct task_struct * task;
    struct rt_mutex * lock;
    int prio;
    u64 deadline;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct rt_mutex_waiter {
    struct rb_node tree_entry;
    struct rb_node pi_tree_entry;
    struct task_struct * task;
    struct rt_mutex * lock;
    int prio;
    u64 deadline;
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
struct rt_mutex_waiter {
    struct rb_node tree_entry;
    struct rb_node pi_tree_entry;
    struct task_struct * task;
    struct rt_mutex * lock;
    int prio;
    u64 deadline;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct rt_mutex_waiter {
    struct rb_node tree_entry;
    struct rb_node pi_tree_entry;
    struct task_struct * task;
    struct rt_mutex * lock;
    int prio;
    u64 deadline;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct rt_mutex_waiter {
    struct rb_node tree_entry;
    struct rb_node pi_tree_entry;
    struct task_struct * task;
    struct rt_mutex * lock;
    int prio;
    u64 deadline;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct rt_mutex_waiter {
    struct rb_node tree_entry;
    struct rb_node pi_tree_entry;
    struct task_struct * task;
    struct rt_mutex * lock;
    int prio;
    u64 deadline;
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
<code>u64 deadline</code>
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
<code>unsigned int wake_state</code>
</li>
<li>
<b>Field added. </b>
<code>struct ww_acquire_ctx * ww_ctx</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct rt_mutex * lock</code> ➡️ <code>struct rt_mutex_base * lock</code>
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
<code>struct rt_waiter_node tree</code>
</li>
<li>
<b>Field added. </b>
<code>struct rt_waiter_node pi_tree</code>
</li>
<li>
<b>Field removed. </b>
<code>struct rb_node tree_entry</code>
</li>
<li>
<b>Field removed. </b>
<code>struct rb_node pi_tree_entry</code>
</li>
<li>
<b>Field removed. </b>
<code>int prio</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 deadline</code>
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
