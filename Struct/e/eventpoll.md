# Struct: <code>eventpoll</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct eventpoll {
    spinlock_t lock;
    struct mutex mtx;
    wait_queue_head_t wq;
    wait_queue_head_t poll_wait;
    struct list_head rdllist;
    struct rb_root rbr;
    struct epitem * ovflist;
    struct wakeup_source * ws;
    struct user_struct * user;
    struct file * file;
    int visited;
    struct list_head visited_list_link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct eventpoll {
    spinlock_t lock;
    struct mutex mtx;
    wait_queue_head_t wq;
    wait_queue_head_t poll_wait;
    struct list_head rdllist;
    struct rb_root rbr;
    struct epitem * ovflist;
    struct wakeup_source * ws;
    struct user_struct * user;
    struct file * file;
    int visited;
    struct list_head visited_list_link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct eventpoll {
    spinlock_t lock;
    struct mutex mtx;
    wait_queue_head_t wq;
    wait_queue_head_t poll_wait;
    struct list_head rdllist;
    struct rb_root rbr;
    struct epitem * ovflist;
    struct wakeup_source * ws;
    struct user_struct * user;
    struct file * file;
    int visited;
    struct list_head visited_list_link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct eventpoll {
    spinlock_t lock;
    struct mutex mtx;
    wait_queue_head_t wq;
    wait_queue_head_t poll_wait;
    struct list_head rdllist;
    struct rb_root rbr;
    struct epitem * ovflist;
    struct wakeup_source * ws;
    struct user_struct * user;
    struct file * file;
    int visited;
    struct list_head visited_list_link;
    unsigned int napi_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct eventpoll {
    spinlock_t lock;
    struct mutex mtx;
    wait_queue_head_t wq;
    wait_queue_head_t poll_wait;
    struct list_head rdllist;
    struct rb_root_cached rbr;
    struct epitem * ovflist;
    struct wakeup_source * ws;
    struct user_struct * user;
    struct file * file;
    int visited;
    struct list_head visited_list_link;
    unsigned int napi_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct eventpoll {
    spinlock_t lock;
    struct mutex mtx;
    wait_queue_head_t wq;
    wait_queue_head_t poll_wait;
    struct list_head rdllist;
    struct rb_root_cached rbr;
    struct epitem * ovflist;
    struct wakeup_source * ws;
    struct user_struct * user;
    struct file * file;
    int visited;
    struct list_head visited_list_link;
    unsigned int napi_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct eventpoll {
    struct mutex mtx;
    wait_queue_head_t wq;
    wait_queue_head_t poll_wait;
    struct list_head rdllist;
    struct rb_root_cached rbr;
    struct epitem * ovflist;
    struct wakeup_source * ws;
    struct user_struct * user;
    struct file * file;
    int visited;
    struct list_head visited_list_link;
    unsigned int napi_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct eventpoll {
    struct mutex mtx;
    wait_queue_head_t wq;
    wait_queue_head_t poll_wait;
    struct list_head rdllist;
    rwlock_t lock;
    struct rb_root_cached rbr;
    struct epitem * ovflist;
    struct wakeup_source * ws;
    struct user_struct * user;
    struct file * file;
    int visited;
    struct list_head visited_list_link;
    unsigned int napi_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct eventpoll {
    struct mutex mtx;
    wait_queue_head_t wq;
    wait_queue_head_t poll_wait;
    struct list_head rdllist;
    rwlock_t lock;
    struct rb_root_cached rbr;
    struct epitem * ovflist;
    struct wakeup_source * ws;
    struct user_struct * user;
    struct file * file;
    int visited;
    struct list_head visited_list_link;
    unsigned int napi_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct eventpoll {
    struct mutex mtx;
    wait_queue_head_t wq;
    wait_queue_head_t poll_wait;
    struct list_head rdllist;
    rwlock_t lock;
    struct rb_root_cached rbr;
    struct epitem * ovflist;
    struct wakeup_source * ws;
    struct user_struct * user;
    struct file * file;
    u64 gen;
    unsigned int napi_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct eventpoll {
    struct mutex mtx;
    wait_queue_head_t wq;
    wait_queue_head_t poll_wait;
    struct list_head rdllist;
    rwlock_t lock;
    struct rb_root_cached rbr;
    struct epitem * ovflist;
    struct wakeup_source * ws;
    struct user_struct * user;
    struct file * file;
    u64 gen;
    struct hlist_head refs;
    unsigned int napi_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct eventpoll {
    struct mutex mtx;
    wait_queue_head_t wq;
    wait_queue_head_t poll_wait;
    struct list_head rdllist;
    rwlock_t lock;
    struct rb_root_cached rbr;
    struct epitem * ovflist;
    struct wakeup_source * ws;
    struct user_struct * user;
    struct file * file;
    u64 gen;
    struct hlist_head refs;
    unsigned int napi_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct eventpoll {
    struct mutex mtx;
    wait_queue_head_t wq;
    wait_queue_head_t poll_wait;
    struct list_head rdllist;
    rwlock_t lock;
    struct rb_root_cached rbr;
    struct epitem * ovflist;
    struct wakeup_source * ws;
    struct user_struct * user;
    struct file * file;
    u64 gen;
    struct hlist_head refs;
    unsigned int napi_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct eventpoll {
    struct mutex mtx;
    wait_queue_head_t wq;
    wait_queue_head_t poll_wait;
    struct list_head rdllist;
    rwlock_t lock;
    struct rb_root_cached rbr;
    struct epitem * ovflist;
    struct wakeup_source * ws;
    struct user_struct * user;
    struct file * file;
    u64 gen;
    struct hlist_head refs;
    unsigned int napi_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct eventpoll {
    struct mutex mtx;
    wait_queue_head_t wq;
    wait_queue_head_t poll_wait;
    struct list_head rdllist;
    rwlock_t lock;
    struct rb_root_cached rbr;
    struct epitem * ovflist;
    struct wakeup_source * ws;
    struct user_struct * user;
    struct file * file;
    u64 gen;
    struct hlist_head refs;
    unsigned int napi_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct eventpoll {
    struct mutex mtx;
    wait_queue_head_t wq;
    wait_queue_head_t poll_wait;
    struct list_head rdllist;
    rwlock_t lock;
    struct rb_root_cached rbr;
    struct epitem * ovflist;
    struct wakeup_source * ws;
    struct user_struct * user;
    struct file * file;
    u64 gen;
    struct hlist_head refs;
    refcount_t refcount;
    unsigned int napi_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct eventpoll {
    struct mutex mtx;
    wait_queue_head_t wq;
    wait_queue_head_t poll_wait;
    struct list_head rdllist;
    rwlock_t lock;
    struct rb_root_cached rbr;
    struct epitem * ovflist;
    struct wakeup_source * ws;
    struct user_struct * user;
    struct file * file;
    u64 gen;
    struct hlist_head refs;
    refcount_t refcount;
    unsigned int napi_id;
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
struct eventpoll {
    struct mutex mtx;
    wait_queue_head_t wq;
    wait_queue_head_t poll_wait;
    struct list_head rdllist;
    rwlock_t lock;
    struct rb_root_cached rbr;
    struct epitem * ovflist;
    struct wakeup_source * ws;
    struct user_struct * user;
    struct file * file;
    int visited;
    struct list_head visited_list_link;
    unsigned int napi_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct eventpoll {
    struct mutex mtx;
    wait_queue_head_t wq;
    wait_queue_head_t poll_wait;
    struct list_head rdllist;
    rwlock_t lock;
    struct rb_root_cached rbr;
    struct epitem * ovflist;
    struct wakeup_source * ws;
    struct user_struct * user;
    struct file * file;
    int visited;
    struct list_head visited_list_link;
    unsigned int napi_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct eventpoll {
    struct mutex mtx;
    wait_queue_head_t wq;
    wait_queue_head_t poll_wait;
    struct list_head rdllist;
    rwlock_t lock;
    struct rb_root_cached rbr;
    struct epitem * ovflist;
    struct wakeup_source * ws;
    struct user_struct * user;
    struct file * file;
    int visited;
    struct list_head visited_list_link;
    unsigned int napi_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct eventpoll {
    struct mutex mtx;
    wait_queue_head_t wq;
    wait_queue_head_t poll_wait;
    struct list_head rdllist;
    rwlock_t lock;
    struct rb_root_cached rbr;
    struct epitem * ovflist;
    struct wakeup_source * ws;
    struct user_struct * user;
    struct file * file;
    int visited;
    struct list_head visited_list_link;
    unsigned int napi_id;
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
struct eventpoll {
    struct mutex mtx;
    wait_queue_head_t wq;
    wait_queue_head_t poll_wait;
    struct list_head rdllist;
    rwlock_t lock;
    struct rb_root_cached rbr;
    struct epitem * ovflist;
    struct wakeup_source * ws;
    struct user_struct * user;
    struct file * file;
    int visited;
    struct list_head visited_list_link;
    unsigned int napi_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct eventpoll {
    struct mutex mtx;
    wait_queue_head_t wq;
    wait_queue_head_t poll_wait;
    struct list_head rdllist;
    rwlock_t lock;
    struct rb_root_cached rbr;
    struct epitem * ovflist;
    struct wakeup_source * ws;
    struct user_struct * user;
    struct file * file;
    int visited;
    struct list_head visited_list_link;
    unsigned int napi_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct eventpoll {
    struct mutex mtx;
    wait_queue_head_t wq;
    wait_queue_head_t poll_wait;
    struct list_head rdllist;
    rwlock_t lock;
    struct rb_root_cached rbr;
    struct epitem * ovflist;
    struct wakeup_source * ws;
    struct user_struct * user;
    struct file * file;
    int visited;
    struct list_head visited_list_link;
    unsigned int napi_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct eventpoll {
    struct mutex mtx;
    wait_queue_head_t wq;
    wait_queue_head_t poll_wait;
    struct list_head rdllist;
    rwlock_t lock;
    struct rb_root_cached rbr;
    struct epitem * ovflist;
    struct wakeup_source * ws;
    struct user_struct * user;
    struct file * file;
    int visited;
    struct list_head visited_list_link;
    unsigned int napi_id;
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
<code>unsigned int napi_id</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct rb_root rbr</code> ➡️ <code>struct rb_root_cached rbr</code>
</li>
</ul>
</details>
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
<code>spinlock_t lock</code>
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
<code>rwlock_t lock</code>
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
<code>u64 gen</code>
</li>
<li>
<b>Field removed. </b>
<code>int visited</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head visited_list_link</code>
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
<code>struct hlist_head refs</code>
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
<code>refcount_t refcount</code>
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
