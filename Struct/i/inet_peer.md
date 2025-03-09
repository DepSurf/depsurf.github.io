# Struct: <code>inet_peer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct inet_peer {
    struct inet_peer * avl_left;
    struct inet_peer * avl_right;
    struct inetpeer_addr daddr;
    __u32 avl_height;
    u32[16] metrics;
    u32 rate_tokens;
    long unsigned int rate_last;
    struct list_head gc_list;
    struct callback_head gc_rcu;
    atomic_t rid;
    struct callback_head rcu;
    struct inet_peer * gc_next;
    __u32 dtime;
    atomic_t refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct inet_peer {
    struct inet_peer * avl_left;
    struct inet_peer * avl_right;
    struct inetpeer_addr daddr;
    __u32 avl_height;
    u32[16] metrics;
    u32 rate_tokens;
    long unsigned int rate_last;
    struct list_head gc_list;
    struct callback_head gc_rcu;
    atomic_t rid;
    struct callback_head rcu;
    struct inet_peer * gc_next;
    __u32 dtime;
    atomic_t refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct inet_peer {
    struct inet_peer * avl_left;
    struct inet_peer * avl_right;
    struct inetpeer_addr daddr;
    __u32 avl_height;
    u32[16] metrics;
    u32 rate_tokens;
    long unsigned int rate_last;
    struct list_head gc_list;
    struct callback_head gc_rcu;
    atomic_t rid;
    struct callback_head rcu;
    struct inet_peer * gc_next;
    __u32 dtime;
    atomic_t refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct inet_peer {
    struct inet_peer * avl_left;
    struct inet_peer * avl_right;
    struct inetpeer_addr daddr;
    __u32 avl_height;
    u32[16] metrics;
    u32 rate_tokens;
    long unsigned int rate_last;
    struct list_head gc_list;
    struct callback_head gc_rcu;
    atomic_t rid;
    struct callback_head rcu;
    struct inet_peer * gc_next;
    __u32 dtime;
    refcount_t refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct inet_peer {
    struct rb_node rb_node;
    struct inetpeer_addr daddr;
    u32[17] metrics;
    u32 rate_tokens;
    long unsigned int rate_last;
    atomic_t rid;
    struct callback_head rcu;
    __u32 dtime;
    refcount_t refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct inet_peer {
    struct rb_node rb_node;
    struct inetpeer_addr daddr;
    u32[17] metrics;
    u32 rate_tokens;
    long unsigned int rate_last;
    atomic_t rid;
    struct callback_head rcu;
    __u32 dtime;
    refcount_t refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct inet_peer {
    struct rb_node rb_node;
    struct inetpeer_addr daddr;
    u32[17] metrics;
    u32 rate_tokens;
    u32 n_redirects;
    long unsigned int rate_last;
    atomic_t rid;
    struct callback_head rcu;
    __u32 dtime;
    refcount_t refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct inet_peer {
    struct rb_node rb_node;
    struct inetpeer_addr daddr;
    u32[17] metrics;
    u32 rate_tokens;
    u32 n_redirects;
    long unsigned int rate_last;
    atomic_t rid;
    struct callback_head rcu;
    __u32 dtime;
    refcount_t refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct inet_peer {
    struct rb_node rb_node;
    struct inetpeer_addr daddr;
    u32[17] metrics;
    u32 rate_tokens;
    u32 n_redirects;
    long unsigned int rate_last;
    atomic_t rid;
    struct callback_head rcu;
    __u32 dtime;
    refcount_t refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct inet_peer {
    struct rb_node rb_node;
    struct inetpeer_addr daddr;
    u32[17] metrics;
    u32 rate_tokens;
    u32 n_redirects;
    long unsigned int rate_last;
    atomic_t rid;
    struct callback_head rcu;
    __u32 dtime;
    refcount_t refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct inet_peer {
    struct rb_node rb_node;
    struct inetpeer_addr daddr;
    u32[17] metrics;
    u32 rate_tokens;
    u32 n_redirects;
    long unsigned int rate_last;
    atomic_t rid;
    struct callback_head rcu;
    __u32 dtime;
    refcount_t refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct inet_peer {
    struct rb_node rb_node;
    struct inetpeer_addr daddr;
    u32[17] metrics;
    u32 rate_tokens;
    u32 n_redirects;
    long unsigned int rate_last;
    atomic_t rid;
    struct callback_head rcu;
    __u32 dtime;
    refcount_t refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct inet_peer {
    struct rb_node rb_node;
    struct inetpeer_addr daddr;
    u32[17] metrics;
    u32 rate_tokens;
    u32 n_redirects;
    long unsigned int rate_last;
    atomic_t rid;
    struct callback_head rcu;
    __u32 dtime;
    refcount_t refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct inet_peer {
    struct rb_node rb_node;
    struct inetpeer_addr daddr;
    u32[17] metrics;
    u32 rate_tokens;
    u32 n_redirects;
    long unsigned int rate_last;
    atomic_t rid;
    struct callback_head rcu;
    __u32 dtime;
    refcount_t refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct inet_peer {
    struct rb_node rb_node;
    struct inetpeer_addr daddr;
    u32[17] metrics;
    u32 rate_tokens;
    u32 n_redirects;
    long unsigned int rate_last;
    atomic_t rid;
    struct callback_head rcu;
    __u32 dtime;
    refcount_t refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct inet_peer {
    struct rb_node rb_node;
    struct inetpeer_addr daddr;
    u32[17] metrics;
    u32 rate_tokens;
    u32 n_redirects;
    long unsigned int rate_last;
    atomic_t rid;
    struct callback_head rcu;
    __u32 dtime;
    refcount_t refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct inet_peer {
    struct rb_node rb_node;
    struct inetpeer_addr daddr;
    u32[17] metrics;
    u32 rate_tokens;
    u32 n_redirects;
    long unsigned int rate_last;
    atomic_t rid;
    struct callback_head rcu;
    __u32 dtime;
    refcount_t refcnt;
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
struct inet_peer {
    struct rb_node rb_node;
    struct inetpeer_addr daddr;
    u32[17] metrics;
    u32 rate_tokens;
    u32 n_redirects;
    long unsigned int rate_last;
    atomic_t rid;
    struct callback_head rcu;
    __u32 dtime;
    refcount_t refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct inet_peer {
    struct rb_node rb_node;
    struct inetpeer_addr daddr;
    u32[17] metrics;
    u32 rate_tokens;
    u32 n_redirects;
    long unsigned int rate_last;
    atomic_t rid;
    struct callback_head rcu;
    __u32 dtime;
    refcount_t refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct inet_peer {
    struct rb_node rb_node;
    struct inetpeer_addr daddr;
    u32[17] metrics;
    u32 rate_tokens;
    u32 n_redirects;
    long unsigned int rate_last;
    atomic_t rid;
    struct callback_head rcu;
    __u32 dtime;
    refcount_t refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct inet_peer {
    struct rb_node rb_node;
    struct inetpeer_addr daddr;
    u32[17] metrics;
    u32 rate_tokens;
    u32 n_redirects;
    long unsigned int rate_last;
    atomic_t rid;
    struct callback_head rcu;
    __u32 dtime;
    refcount_t refcnt;
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
struct inet_peer {
    struct rb_node rb_node;
    struct inetpeer_addr daddr;
    u32[17] metrics;
    u32 rate_tokens;
    u32 n_redirects;
    long unsigned int rate_last;
    atomic_t rid;
    struct callback_head rcu;
    __u32 dtime;
    refcount_t refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct inet_peer {
    struct rb_node rb_node;
    struct inetpeer_addr daddr;
    u32[17] metrics;
    u32 rate_tokens;
    u32 n_redirects;
    long unsigned int rate_last;
    atomic_t rid;
    struct callback_head rcu;
    __u32 dtime;
    refcount_t refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct inet_peer {
    struct rb_node rb_node;
    struct inetpeer_addr daddr;
    u32[17] metrics;
    u32 rate_tokens;
    u32 n_redirects;
    long unsigned int rate_last;
    atomic_t rid;
    struct callback_head rcu;
    __u32 dtime;
    refcount_t refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct inet_peer {
    struct rb_node rb_node;
    struct inetpeer_addr daddr;
    u32[17] metrics;
    u32 rate_tokens;
    u32 n_redirects;
    long unsigned int rate_last;
    atomic_t rid;
    struct callback_head rcu;
    __u32 dtime;
    refcount_t refcnt;
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
<b>Field added. </b>
<code>struct rb_node rb_node</code>
</li>
<li>
<b>Field removed. </b>
<code>struct inet_peer * avl_left</code>
</li>
<li>
<b>Field removed. </b>
<code>struct inet_peer * avl_right</code>
</li>
<li>
<b>Field removed. </b>
<code>__u32 avl_height</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head gc_list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct callback_head gc_rcu</code>
</li>
<li>
<b>Field removed. </b>
<code>struct inet_peer * gc_next</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32[16] metrics</code> ➡️ <code>u32[17] metrics</code>
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
<code>u32 n_redirects</code>
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
