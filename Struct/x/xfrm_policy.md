# Struct: <code>xfrm_policy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct xfrm_policy {
    possible_net_t xp_net;
    struct hlist_node bydst;
    struct hlist_node byidx;
    rwlock_t lock;
    atomic_t refcnt;
    struct timer_list timer;
    struct flow_cache_object flo;
    atomic_t genid;
    u32 priority;
    u32 index;
    struct xfrm_mark mark;
    struct xfrm_selector selector;
    struct xfrm_lifetime_cfg lft;
    struct xfrm_lifetime_cur curlft;
    struct xfrm_policy_walk_entry walk;
    struct xfrm_policy_queue polq;
    u8 type;
    u8 action;
    u8 flags;
    u8 xfrm_nr;
    u16 family;
    struct xfrm_sec_ctx * security;
    struct xfrm_tmpl[6] xfrm_vec;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct xfrm_policy {
    possible_net_t xp_net;
    struct hlist_node bydst;
    struct hlist_node byidx;
    rwlock_t lock;
    atomic_t refcnt;
    struct timer_list timer;
    struct flow_cache_object flo;
    atomic_t genid;
    u32 priority;
    u32 index;
    struct xfrm_mark mark;
    struct xfrm_selector selector;
    struct xfrm_lifetime_cfg lft;
    struct xfrm_lifetime_cur curlft;
    struct xfrm_policy_walk_entry walk;
    struct xfrm_policy_queue polq;
    u8 type;
    u8 action;
    u8 flags;
    u8 xfrm_nr;
    u16 family;
    struct xfrm_sec_ctx * security;
    struct xfrm_tmpl[6] xfrm_vec;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct xfrm_policy {
    possible_net_t xp_net;
    struct hlist_node bydst;
    struct hlist_node byidx;
    rwlock_t lock;
    atomic_t refcnt;
    struct timer_list timer;
    struct flow_cache_object flo;
    atomic_t genid;
    u32 priority;
    u32 index;
    struct xfrm_mark mark;
    struct xfrm_selector selector;
    struct xfrm_lifetime_cfg lft;
    struct xfrm_lifetime_cur curlft;
    struct xfrm_policy_walk_entry walk;
    struct xfrm_policy_queue polq;
    u8 type;
    u8 action;
    u8 flags;
    u8 xfrm_nr;
    u16 family;
    struct xfrm_sec_ctx * security;
    struct xfrm_tmpl[6] xfrm_vec;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct xfrm_policy {
    possible_net_t xp_net;
    struct hlist_node bydst;
    struct hlist_node byidx;
    rwlock_t lock;
    refcount_t refcnt;
    struct timer_list timer;
    struct flow_cache_object flo;
    atomic_t genid;
    u32 priority;
    u32 index;
    struct xfrm_mark mark;
    struct xfrm_selector selector;
    struct xfrm_lifetime_cfg lft;
    struct xfrm_lifetime_cur curlft;
    struct xfrm_policy_walk_entry walk;
    struct xfrm_policy_queue polq;
    u8 type;
    u8 action;
    u8 flags;
    u8 xfrm_nr;
    u16 family;
    struct xfrm_sec_ctx * security;
    struct xfrm_tmpl[6] xfrm_vec;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct xfrm_policy {
    possible_net_t xp_net;
    struct hlist_node bydst;
    struct hlist_node byidx;
    rwlock_t lock;
    refcount_t refcnt;
    struct timer_list timer;
    atomic_t genid;
    u32 priority;
    u32 index;
    struct xfrm_mark mark;
    struct xfrm_selector selector;
    struct xfrm_lifetime_cfg lft;
    struct xfrm_lifetime_cur curlft;
    struct xfrm_policy_walk_entry walk;
    struct xfrm_policy_queue polq;
    u8 type;
    u8 action;
    u8 flags;
    u8 xfrm_nr;
    u16 family;
    struct xfrm_sec_ctx * security;
    struct xfrm_tmpl[6] xfrm_vec;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct xfrm_policy {
    possible_net_t xp_net;
    struct hlist_node bydst;
    struct hlist_node byidx;
    rwlock_t lock;
    refcount_t refcnt;
    struct timer_list timer;
    atomic_t genid;
    u32 priority;
    u32 index;
    struct xfrm_mark mark;
    struct xfrm_selector selector;
    struct xfrm_lifetime_cfg lft;
    struct xfrm_lifetime_cur curlft;
    struct xfrm_policy_walk_entry walk;
    struct xfrm_policy_queue polq;
    u8 type;
    u8 action;
    u8 flags;
    u8 xfrm_nr;
    u16 family;
    struct xfrm_sec_ctx * security;
    struct xfrm_tmpl[6] xfrm_vec;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct xfrm_policy {
    possible_net_t xp_net;
    struct hlist_node bydst;
    struct hlist_node byidx;
    rwlock_t lock;
    refcount_t refcnt;
    u32 pos;
    struct timer_list timer;
    atomic_t genid;
    u32 priority;
    u32 index;
    u32 if_id;
    struct xfrm_mark mark;
    struct xfrm_selector selector;
    struct xfrm_lifetime_cfg lft;
    struct xfrm_lifetime_cur curlft;
    struct xfrm_policy_walk_entry walk;
    struct xfrm_policy_queue polq;
    bool bydst_reinsert;
    u8 type;
    u8 action;
    u8 flags;
    u8 xfrm_nr;
    u16 family;
    struct xfrm_sec_ctx * security;
    struct xfrm_tmpl[6] xfrm_vec;
    struct hlist_node bydst_inexact_list;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct xfrm_policy {
    possible_net_t xp_net;
    struct hlist_node bydst;
    struct hlist_node byidx;
    rwlock_t lock;
    refcount_t refcnt;
    u32 pos;
    struct timer_list timer;
    atomic_t genid;
    u32 priority;
    u32 index;
    u32 if_id;
    struct xfrm_mark mark;
    struct xfrm_selector selector;
    struct xfrm_lifetime_cfg lft;
    struct xfrm_lifetime_cur curlft;
    struct xfrm_policy_walk_entry walk;
    struct xfrm_policy_queue polq;
    bool bydst_reinsert;
    u8 type;
    u8 action;
    u8 flags;
    u8 xfrm_nr;
    u16 family;
    struct xfrm_sec_ctx * security;
    struct xfrm_tmpl[6] xfrm_vec;
    struct hlist_node bydst_inexact_list;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct xfrm_policy {
    possible_net_t xp_net;
    struct hlist_node bydst;
    struct hlist_node byidx;
    rwlock_t lock;
    refcount_t refcnt;
    u32 pos;
    struct timer_list timer;
    atomic_t genid;
    u32 priority;
    u32 index;
    u32 if_id;
    struct xfrm_mark mark;
    struct xfrm_selector selector;
    struct xfrm_lifetime_cfg lft;
    struct xfrm_lifetime_cur curlft;
    struct xfrm_policy_walk_entry walk;
    struct xfrm_policy_queue polq;
    bool bydst_reinsert;
    u8 type;
    u8 action;
    u8 flags;
    u8 xfrm_nr;
    u16 family;
    struct xfrm_sec_ctx * security;
    struct xfrm_tmpl[6] xfrm_vec;
    struct hlist_node bydst_inexact_list;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct xfrm_policy {
    possible_net_t xp_net;
    struct hlist_node bydst;
    struct hlist_node byidx;
    rwlock_t lock;
    refcount_t refcnt;
    u32 pos;
    struct timer_list timer;
    atomic_t genid;
    u32 priority;
    u32 index;
    u32 if_id;
    struct xfrm_mark mark;
    struct xfrm_selector selector;
    struct xfrm_lifetime_cfg lft;
    struct xfrm_lifetime_cur curlft;
    struct xfrm_policy_walk_entry walk;
    struct xfrm_policy_queue polq;
    bool bydst_reinsert;
    u8 type;
    u8 action;
    u8 flags;
    u8 xfrm_nr;
    u16 family;
    struct xfrm_sec_ctx * security;
    struct xfrm_tmpl[6] xfrm_vec;
    struct hlist_node bydst_inexact_list;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct xfrm_policy {
    possible_net_t xp_net;
    struct hlist_node bydst;
    struct hlist_node byidx;
    rwlock_t lock;
    refcount_t refcnt;
    u32 pos;
    struct timer_list timer;
    atomic_t genid;
    u32 priority;
    u32 index;
    u32 if_id;
    struct xfrm_mark mark;
    struct xfrm_selector selector;
    struct xfrm_lifetime_cfg lft;
    struct xfrm_lifetime_cur curlft;
    struct xfrm_policy_walk_entry walk;
    struct xfrm_policy_queue polq;
    bool bydst_reinsert;
    u8 type;
    u8 action;
    u8 flags;
    u8 xfrm_nr;
    u16 family;
    struct xfrm_sec_ctx * security;
    struct xfrm_tmpl[6] xfrm_vec;
    struct hlist_node bydst_inexact_list;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct xfrm_policy {
    possible_net_t xp_net;
    struct hlist_node bydst;
    struct hlist_node byidx;
    rwlock_t lock;
    refcount_t refcnt;
    u32 pos;
    struct timer_list timer;
    atomic_t genid;
    u32 priority;
    u32 index;
    u32 if_id;
    struct xfrm_mark mark;
    struct xfrm_selector selector;
    struct xfrm_lifetime_cfg lft;
    struct xfrm_lifetime_cur curlft;
    struct xfrm_policy_walk_entry walk;
    struct xfrm_policy_queue polq;
    bool bydst_reinsert;
    u8 type;
    u8 action;
    u8 flags;
    u8 xfrm_nr;
    u16 family;
    struct xfrm_sec_ctx * security;
    struct xfrm_tmpl[6] xfrm_vec;
    struct hlist_node bydst_inexact_list;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct xfrm_policy {
    possible_net_t xp_net;
    struct hlist_node bydst;
    struct hlist_node byidx;
    rwlock_t lock;
    refcount_t refcnt;
    u32 pos;
    struct timer_list timer;
    atomic_t genid;
    u32 priority;
    u32 index;
    u32 if_id;
    struct xfrm_mark mark;
    struct xfrm_selector selector;
    struct xfrm_lifetime_cfg lft;
    struct xfrm_lifetime_cur curlft;
    struct xfrm_policy_walk_entry walk;
    struct xfrm_policy_queue polq;
    bool bydst_reinsert;
    u8 type;
    u8 action;
    u8 flags;
    u8 xfrm_nr;
    u16 family;
    struct xfrm_sec_ctx * security;
    struct xfrm_tmpl[6] xfrm_vec;
    struct hlist_node bydst_inexact_list;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct xfrm_policy {
    possible_net_t xp_net;
    struct hlist_node bydst;
    struct hlist_node byidx;
    rwlock_t lock;
    refcount_t refcnt;
    u32 pos;
    struct timer_list timer;
    atomic_t genid;
    u32 priority;
    u32 index;
    u32 if_id;
    struct xfrm_mark mark;
    struct xfrm_selector selector;
    struct xfrm_lifetime_cfg lft;
    struct xfrm_lifetime_cur curlft;
    struct xfrm_policy_walk_entry walk;
    struct xfrm_policy_queue polq;
    bool bydst_reinsert;
    u8 type;
    u8 action;
    u8 flags;
    u8 xfrm_nr;
    u16 family;
    struct xfrm_sec_ctx * security;
    struct xfrm_tmpl[6] xfrm_vec;
    struct hlist_node bydst_inexact_list;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct xfrm_policy {
    possible_net_t xp_net;
    struct hlist_node bydst;
    struct hlist_node byidx;
    rwlock_t lock;
    refcount_t refcnt;
    u32 pos;
    struct timer_list timer;
    atomic_t genid;
    u32 priority;
    u32 index;
    u32 if_id;
    struct xfrm_mark mark;
    struct xfrm_selector selector;
    struct xfrm_lifetime_cfg lft;
    struct xfrm_lifetime_cur curlft;
    struct xfrm_policy_walk_entry walk;
    struct xfrm_policy_queue polq;
    bool bydst_reinsert;
    u8 type;
    u8 action;
    u8 flags;
    u8 xfrm_nr;
    u16 family;
    struct xfrm_sec_ctx * security;
    struct xfrm_tmpl[6] xfrm_vec;
    struct hlist_node bydst_inexact_list;
    struct callback_head rcu;
    struct xfrm_dev_offload xdo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct xfrm_policy {
    possible_net_t xp_net;
    struct hlist_node bydst;
    struct hlist_node byidx;
    rwlock_t lock;
    refcount_t refcnt;
    u32 pos;
    struct timer_list timer;
    atomic_t genid;
    u32 priority;
    u32 index;
    u32 if_id;
    struct xfrm_mark mark;
    struct xfrm_selector selector;
    struct xfrm_lifetime_cfg lft;
    struct xfrm_lifetime_cur curlft;
    struct xfrm_policy_walk_entry walk;
    struct xfrm_policy_queue polq;
    bool bydst_reinsert;
    u8 type;
    u8 action;
    u8 flags;
    u8 xfrm_nr;
    u16 family;
    struct xfrm_sec_ctx * security;
    struct xfrm_tmpl[6] xfrm_vec;
    struct hlist_node bydst_inexact_list;
    struct callback_head rcu;
    struct xfrm_dev_offload xdo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct xfrm_policy {
    possible_net_t xp_net;
    struct hlist_node bydst;
    struct hlist_node byidx;
    rwlock_t lock;
    refcount_t refcnt;
    u32 pos;
    struct timer_list timer;
    atomic_t genid;
    u32 priority;
    u32 index;
    u32 if_id;
    struct xfrm_mark mark;
    struct xfrm_selector selector;
    struct xfrm_lifetime_cfg lft;
    struct xfrm_lifetime_cur curlft;
    struct xfrm_policy_walk_entry walk;
    struct xfrm_policy_queue polq;
    bool bydst_reinsert;
    u8 type;
    u8 action;
    u8 flags;
    u8 xfrm_nr;
    u16 family;
    struct xfrm_sec_ctx * security;
    struct xfrm_tmpl[6] xfrm_vec;
    struct hlist_node bydst_inexact_list;
    struct callback_head rcu;
    struct xfrm_dev_offload xdo;
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
struct xfrm_policy {
    possible_net_t xp_net;
    struct hlist_node bydst;
    struct hlist_node byidx;
    rwlock_t lock;
    refcount_t refcnt;
    u32 pos;
    struct timer_list timer;
    atomic_t genid;
    u32 priority;
    u32 index;
    u32 if_id;
    struct xfrm_mark mark;
    struct xfrm_selector selector;
    struct xfrm_lifetime_cfg lft;
    struct xfrm_lifetime_cur curlft;
    struct xfrm_policy_walk_entry walk;
    struct xfrm_policy_queue polq;
    bool bydst_reinsert;
    u8 type;
    u8 action;
    u8 flags;
    u8 xfrm_nr;
    u16 family;
    struct xfrm_sec_ctx * security;
    struct xfrm_tmpl[6] xfrm_vec;
    struct hlist_node bydst_inexact_list;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct xfrm_policy {
    possible_net_t xp_net;
    struct hlist_node bydst;
    struct hlist_node byidx;
    rwlock_t lock;
    refcount_t refcnt;
    u32 pos;
    struct timer_list timer;
    atomic_t genid;
    u32 priority;
    u32 index;
    u32 if_id;
    struct xfrm_mark mark;
    struct xfrm_selector selector;
    struct xfrm_lifetime_cfg lft;
    struct xfrm_lifetime_cur curlft;
    struct xfrm_policy_walk_entry walk;
    struct xfrm_policy_queue polq;
    bool bydst_reinsert;
    u8 type;
    u8 action;
    u8 flags;
    u8 xfrm_nr;
    u16 family;
    struct xfrm_sec_ctx * security;
    struct xfrm_tmpl[6] xfrm_vec;
    struct hlist_node bydst_inexact_list;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct xfrm_policy {
    possible_net_t xp_net;
    struct hlist_node bydst;
    struct hlist_node byidx;
    rwlock_t lock;
    refcount_t refcnt;
    u32 pos;
    struct timer_list timer;
    atomic_t genid;
    u32 priority;
    u32 index;
    u32 if_id;
    struct xfrm_mark mark;
    struct xfrm_selector selector;
    struct xfrm_lifetime_cfg lft;
    struct xfrm_lifetime_cur curlft;
    struct xfrm_policy_walk_entry walk;
    struct xfrm_policy_queue polq;
    bool bydst_reinsert;
    u8 type;
    u8 action;
    u8 flags;
    u8 xfrm_nr;
    u16 family;
    struct xfrm_sec_ctx * security;
    struct xfrm_tmpl[6] xfrm_vec;
    struct hlist_node bydst_inexact_list;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct xfrm_policy {
    possible_net_t xp_net;
    struct hlist_node bydst;
    struct hlist_node byidx;
    rwlock_t lock;
    refcount_t refcnt;
    u32 pos;
    struct timer_list timer;
    atomic_t genid;
    u32 priority;
    u32 index;
    u32 if_id;
    struct xfrm_mark mark;
    struct xfrm_selector selector;
    struct xfrm_lifetime_cfg lft;
    struct xfrm_lifetime_cur curlft;
    struct xfrm_policy_walk_entry walk;
    struct xfrm_policy_queue polq;
    bool bydst_reinsert;
    u8 type;
    u8 action;
    u8 flags;
    u8 xfrm_nr;
    u16 family;
    struct xfrm_sec_ctx * security;
    struct xfrm_tmpl[6] xfrm_vec;
    struct hlist_node bydst_inexact_list;
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
struct xfrm_policy {
    possible_net_t xp_net;
    struct hlist_node bydst;
    struct hlist_node byidx;
    rwlock_t lock;
    refcount_t refcnt;
    u32 pos;
    struct timer_list timer;
    atomic_t genid;
    u32 priority;
    u32 index;
    u32 if_id;
    struct xfrm_mark mark;
    struct xfrm_selector selector;
    struct xfrm_lifetime_cfg lft;
    struct xfrm_lifetime_cur curlft;
    struct xfrm_policy_walk_entry walk;
    struct xfrm_policy_queue polq;
    bool bydst_reinsert;
    u8 type;
    u8 action;
    u8 flags;
    u8 xfrm_nr;
    u16 family;
    struct xfrm_sec_ctx * security;
    struct xfrm_tmpl[6] xfrm_vec;
    struct hlist_node bydst_inexact_list;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct xfrm_policy {
    possible_net_t xp_net;
    struct hlist_node bydst;
    struct hlist_node byidx;
    rwlock_t lock;
    refcount_t refcnt;
    u32 pos;
    struct timer_list timer;
    atomic_t genid;
    u32 priority;
    u32 index;
    u32 if_id;
    struct xfrm_mark mark;
    struct xfrm_selector selector;
    struct xfrm_lifetime_cfg lft;
    struct xfrm_lifetime_cur curlft;
    struct xfrm_policy_walk_entry walk;
    struct xfrm_policy_queue polq;
    bool bydst_reinsert;
    u8 type;
    u8 action;
    u8 flags;
    u8 xfrm_nr;
    u16 family;
    struct xfrm_sec_ctx * security;
    struct xfrm_tmpl[6] xfrm_vec;
    struct hlist_node bydst_inexact_list;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct xfrm_policy {
    possible_net_t xp_net;
    struct hlist_node bydst;
    struct hlist_node byidx;
    rwlock_t lock;
    refcount_t refcnt;
    u32 pos;
    struct timer_list timer;
    atomic_t genid;
    u32 priority;
    u32 index;
    u32 if_id;
    struct xfrm_mark mark;
    struct xfrm_selector selector;
    struct xfrm_lifetime_cfg lft;
    struct xfrm_lifetime_cur curlft;
    struct xfrm_policy_walk_entry walk;
    struct xfrm_policy_queue polq;
    bool bydst_reinsert;
    u8 type;
    u8 action;
    u8 flags;
    u8 xfrm_nr;
    u16 family;
    struct xfrm_sec_ctx * security;
    struct xfrm_tmpl[6] xfrm_vec;
    struct hlist_node bydst_inexact_list;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct xfrm_policy {
    possible_net_t xp_net;
    struct hlist_node bydst;
    struct hlist_node byidx;
    rwlock_t lock;
    refcount_t refcnt;
    u32 pos;
    struct timer_list timer;
    atomic_t genid;
    u32 priority;
    u32 index;
    u32 if_id;
    struct xfrm_mark mark;
    struct xfrm_selector selector;
    struct xfrm_lifetime_cfg lft;
    struct xfrm_lifetime_cur curlft;
    struct xfrm_policy_walk_entry walk;
    struct xfrm_policy_queue polq;
    bool bydst_reinsert;
    u8 type;
    u8 action;
    u8 flags;
    u8 xfrm_nr;
    u16 family;
    struct xfrm_sec_ctx * security;
    struct xfrm_tmpl[6] xfrm_vec;
    struct hlist_node bydst_inexact_list;
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
<code>struct flow_cache_object flo</code>
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
<b>Field added. </b>
<code>u32 pos</code>
</li>
<li>
<b>Field added. </b>
<code>u32 if_id</code>
</li>
<li>
<b>Field added. </b>
<code>bool bydst_reinsert</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_node bydst_inexact_list</code>
</li>
</ul>
</details>
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
<code>struct xfrm_dev_offload xdo</code>
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
