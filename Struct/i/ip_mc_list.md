# Struct: <code>ip_mc_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ip_mc_list {
    struct in_device * interface;
    __be32 multiaddr;
    unsigned int sfmode;
    struct ip_sf_list * sources;
    struct ip_sf_list * tomb;
    long unsigned int[2] sfcount;
    struct ip_mc_list * next;
    struct ip_mc_list * next_rcu;
    struct ip_mc_list * next_hash;
    struct timer_list timer;
    int users;
    atomic_t refcnt;
    spinlock_t lock;
    char tm_running;
    char reporter;
    char unsolicit_count;
    char loaded;
    unsigned char gsquery;
    unsigned char crcount;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct ip_mc_list {
    struct in_device * interface;
    __be32 multiaddr;
    unsigned int sfmode;
    struct ip_sf_list * sources;
    struct ip_sf_list * tomb;
    long unsigned int[2] sfcount;
    struct ip_mc_list * next;
    struct ip_mc_list * next_rcu;
    struct ip_mc_list * next_hash;
    struct timer_list timer;
    int users;
    atomic_t refcnt;
    spinlock_t lock;
    char tm_running;
    char reporter;
    char unsolicit_count;
    char loaded;
    unsigned char gsquery;
    unsigned char crcount;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct ip_mc_list {
    struct in_device * interface;
    __be32 multiaddr;
    unsigned int sfmode;
    struct ip_sf_list * sources;
    struct ip_sf_list * tomb;
    long unsigned int[2] sfcount;
    struct ip_mc_list * next;
    struct ip_mc_list * next_rcu;
    struct ip_mc_list * next_hash;
    struct timer_list timer;
    int users;
    atomic_t refcnt;
    spinlock_t lock;
    char tm_running;
    char reporter;
    char unsolicit_count;
    char loaded;
    unsigned char gsquery;
    unsigned char crcount;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct ip_mc_list {
    struct in_device * interface;
    __be32 multiaddr;
    unsigned int sfmode;
    struct ip_sf_list * sources;
    struct ip_sf_list * tomb;
    long unsigned int[2] sfcount;
    struct ip_mc_list * next;
    struct ip_mc_list * next_rcu;
    struct ip_mc_list * next_hash;
    struct timer_list timer;
    int users;
    refcount_t refcnt;
    spinlock_t lock;
    char tm_running;
    char reporter;
    char unsolicit_count;
    char loaded;
    unsigned char gsquery;
    unsigned char crcount;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ip_mc_list {
    struct in_device * interface;
    __be32 multiaddr;
    unsigned int sfmode;
    struct ip_sf_list * sources;
    struct ip_sf_list * tomb;
    long unsigned int[2] sfcount;
    struct ip_mc_list * next;
    struct ip_mc_list * next_rcu;
    struct ip_mc_list * next_hash;
    struct timer_list timer;
    int users;
    refcount_t refcnt;
    spinlock_t lock;
    char tm_running;
    char reporter;
    char unsolicit_count;
    char loaded;
    unsigned char gsquery;
    unsigned char crcount;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ip_mc_list {
    struct in_device * interface;
    __be32 multiaddr;
    unsigned int sfmode;
    struct ip_sf_list * sources;
    struct ip_sf_list * tomb;
    long unsigned int[2] sfcount;
    struct ip_mc_list * next;
    struct ip_mc_list * next_rcu;
    struct ip_mc_list * next_hash;
    struct timer_list timer;
    int users;
    refcount_t refcnt;
    spinlock_t lock;
    char tm_running;
    char reporter;
    char unsolicit_count;
    char loaded;
    unsigned char gsquery;
    unsigned char crcount;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ip_mc_list {
    struct in_device * interface;
    __be32 multiaddr;
    unsigned int sfmode;
    struct ip_sf_list * sources;
    struct ip_sf_list * tomb;
    long unsigned int[2] sfcount;
    struct ip_mc_list * next;
    struct ip_mc_list * next_rcu;
    struct ip_mc_list * next_hash;
    struct timer_list timer;
    int users;
    refcount_t refcnt;
    spinlock_t lock;
    char tm_running;
    char reporter;
    char unsolicit_count;
    char loaded;
    unsigned char gsquery;
    unsigned char crcount;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ip_mc_list {
    struct in_device * interface;
    __be32 multiaddr;
    unsigned int sfmode;
    struct ip_sf_list * sources;
    struct ip_sf_list * tomb;
    long unsigned int[2] sfcount;
    struct ip_mc_list * next;
    struct ip_mc_list * next_rcu;
    struct ip_mc_list * next_hash;
    struct timer_list timer;
    int users;
    refcount_t refcnt;
    spinlock_t lock;
    char tm_running;
    char reporter;
    char unsolicit_count;
    char loaded;
    unsigned char gsquery;
    unsigned char crcount;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ip_mc_list {
    struct in_device * interface;
    __be32 multiaddr;
    unsigned int sfmode;
    struct ip_sf_list * sources;
    struct ip_sf_list * tomb;
    long unsigned int[2] sfcount;
    struct ip_mc_list * next;
    struct ip_mc_list * next_rcu;
    struct ip_mc_list * next_hash;
    struct timer_list timer;
    int users;
    refcount_t refcnt;
    spinlock_t lock;
    char tm_running;
    char reporter;
    char unsolicit_count;
    char loaded;
    unsigned char gsquery;
    unsigned char crcount;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ip_mc_list {
    struct in_device * interface;
    __be32 multiaddr;
    unsigned int sfmode;
    struct ip_sf_list * sources;
    struct ip_sf_list * tomb;
    long unsigned int[2] sfcount;
    struct ip_mc_list * next;
    struct ip_mc_list * next_rcu;
    struct ip_mc_list * next_hash;
    struct timer_list timer;
    int users;
    refcount_t refcnt;
    spinlock_t lock;
    char tm_running;
    char reporter;
    char unsolicit_count;
    char loaded;
    unsigned char gsquery;
    unsigned char crcount;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ip_mc_list {
    struct in_device * interface;
    __be32 multiaddr;
    unsigned int sfmode;
    struct ip_sf_list * sources;
    struct ip_sf_list * tomb;
    long unsigned int[2] sfcount;
    struct ip_mc_list * next;
    struct ip_mc_list * next_rcu;
    struct ip_mc_list * next_hash;
    struct timer_list timer;
    int users;
    refcount_t refcnt;
    spinlock_t lock;
    char tm_running;
    char reporter;
    char unsolicit_count;
    char loaded;
    unsigned char gsquery;
    unsigned char crcount;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ip_mc_list {
    struct in_device * interface;
    __be32 multiaddr;
    unsigned int sfmode;
    struct ip_sf_list * sources;
    struct ip_sf_list * tomb;
    long unsigned int[2] sfcount;
    struct ip_mc_list * next;
    struct ip_mc_list * next_rcu;
    struct ip_mc_list * next_hash;
    struct timer_list timer;
    int users;
    refcount_t refcnt;
    spinlock_t lock;
    char tm_running;
    char reporter;
    char unsolicit_count;
    char loaded;
    unsigned char gsquery;
    unsigned char crcount;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ip_mc_list {
    struct in_device * interface;
    __be32 multiaddr;
    unsigned int sfmode;
    struct ip_sf_list * sources;
    struct ip_sf_list * tomb;
    long unsigned int[2] sfcount;
    struct ip_mc_list * next;
    struct ip_mc_list * next_rcu;
    struct ip_mc_list * next_hash;
    struct timer_list timer;
    int users;
    refcount_t refcnt;
    spinlock_t lock;
    char tm_running;
    char reporter;
    char unsolicit_count;
    char loaded;
    unsigned char gsquery;
    unsigned char crcount;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ip_mc_list {
    struct in_device * interface;
    __be32 multiaddr;
    unsigned int sfmode;
    struct ip_sf_list * sources;
    struct ip_sf_list * tomb;
    long unsigned int[2] sfcount;
    struct ip_mc_list * next;
    struct ip_mc_list * next_rcu;
    struct ip_mc_list * next_hash;
    struct timer_list timer;
    int users;
    refcount_t refcnt;
    spinlock_t lock;
    char tm_running;
    char reporter;
    char unsolicit_count;
    char loaded;
    unsigned char gsquery;
    unsigned char crcount;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ip_mc_list {
    struct in_device * interface;
    __be32 multiaddr;
    unsigned int sfmode;
    struct ip_sf_list * sources;
    struct ip_sf_list * tomb;
    long unsigned int[2] sfcount;
    struct ip_mc_list * next;
    struct ip_mc_list * next_rcu;
    struct ip_mc_list * next_hash;
    struct timer_list timer;
    int users;
    refcount_t refcnt;
    spinlock_t lock;
    char tm_running;
    char reporter;
    char unsolicit_count;
    char loaded;
    unsigned char gsquery;
    unsigned char crcount;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ip_mc_list {
    struct in_device * interface;
    __be32 multiaddr;
    unsigned int sfmode;
    struct ip_sf_list * sources;
    struct ip_sf_list * tomb;
    long unsigned int[2] sfcount;
    struct ip_mc_list * next;
    struct ip_mc_list * next_rcu;
    struct ip_mc_list * next_hash;
    struct timer_list timer;
    int users;
    refcount_t refcnt;
    spinlock_t lock;
    char tm_running;
    char reporter;
    char unsolicit_count;
    char loaded;
    unsigned char gsquery;
    unsigned char crcount;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ip_mc_list {
    struct in_device * interface;
    __be32 multiaddr;
    unsigned int sfmode;
    struct ip_sf_list * sources;
    struct ip_sf_list * tomb;
    long unsigned int[2] sfcount;
    struct ip_mc_list * next;
    struct ip_mc_list * next_rcu;
    struct ip_mc_list * next_hash;
    struct timer_list timer;
    int users;
    refcount_t refcnt;
    spinlock_t lock;
    char tm_running;
    char reporter;
    char unsolicit_count;
    char loaded;
    unsigned char gsquery;
    unsigned char crcount;
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
struct ip_mc_list {
    struct in_device * interface;
    __be32 multiaddr;
    unsigned int sfmode;
    struct ip_sf_list * sources;
    struct ip_sf_list * tomb;
    long unsigned int[2] sfcount;
    struct ip_mc_list * next;
    struct ip_mc_list * next_rcu;
    struct ip_mc_list * next_hash;
    struct timer_list timer;
    int users;
    refcount_t refcnt;
    spinlock_t lock;
    char tm_running;
    char reporter;
    char unsolicit_count;
    char loaded;
    unsigned char gsquery;
    unsigned char crcount;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ip_mc_list {
    struct in_device * interface;
    __be32 multiaddr;
    unsigned int sfmode;
    struct ip_sf_list * sources;
    struct ip_sf_list * tomb;
    long unsigned int[2] sfcount;
    struct ip_mc_list * next;
    struct ip_mc_list * next_rcu;
    struct ip_mc_list * next_hash;
    struct timer_list timer;
    int users;
    refcount_t refcnt;
    spinlock_t lock;
    char tm_running;
    char reporter;
    char unsolicit_count;
    char loaded;
    unsigned char gsquery;
    unsigned char crcount;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ip_mc_list {
    struct in_device * interface;
    __be32 multiaddr;
    unsigned int sfmode;
    struct ip_sf_list * sources;
    struct ip_sf_list * tomb;
    long unsigned int[2] sfcount;
    struct ip_mc_list * next;
    struct ip_mc_list * next_rcu;
    struct ip_mc_list * next_hash;
    struct timer_list timer;
    int users;
    refcount_t refcnt;
    spinlock_t lock;
    char tm_running;
    char reporter;
    char unsolicit_count;
    char loaded;
    unsigned char gsquery;
    unsigned char crcount;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ip_mc_list {
    struct in_device * interface;
    __be32 multiaddr;
    unsigned int sfmode;
    struct ip_sf_list * sources;
    struct ip_sf_list * tomb;
    long unsigned int[2] sfcount;
    struct ip_mc_list * next;
    struct ip_mc_list * next_rcu;
    struct ip_mc_list * next_hash;
    struct timer_list timer;
    int users;
    refcount_t refcnt;
    spinlock_t lock;
    char tm_running;
    char reporter;
    char unsolicit_count;
    char loaded;
    unsigned char gsquery;
    unsigned char crcount;
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
struct ip_mc_list {
    struct in_device * interface;
    __be32 multiaddr;
    unsigned int sfmode;
    struct ip_sf_list * sources;
    struct ip_sf_list * tomb;
    long unsigned int[2] sfcount;
    struct ip_mc_list * next;
    struct ip_mc_list * next_rcu;
    struct ip_mc_list * next_hash;
    struct timer_list timer;
    int users;
    refcount_t refcnt;
    spinlock_t lock;
    char tm_running;
    char reporter;
    char unsolicit_count;
    char loaded;
    unsigned char gsquery;
    unsigned char crcount;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ip_mc_list {
    struct in_device * interface;
    __be32 multiaddr;
    unsigned int sfmode;
    struct ip_sf_list * sources;
    struct ip_sf_list * tomb;
    long unsigned int[2] sfcount;
    struct ip_mc_list * next;
    struct ip_mc_list * next_rcu;
    struct ip_mc_list * next_hash;
    struct timer_list timer;
    int users;
    refcount_t refcnt;
    spinlock_t lock;
    char tm_running;
    char reporter;
    char unsolicit_count;
    char loaded;
    unsigned char gsquery;
    unsigned char crcount;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ip_mc_list {
    struct in_device * interface;
    __be32 multiaddr;
    unsigned int sfmode;
    struct ip_sf_list * sources;
    struct ip_sf_list * tomb;
    long unsigned int[2] sfcount;
    struct ip_mc_list * next;
    struct ip_mc_list * next_rcu;
    struct ip_mc_list * next_hash;
    struct timer_list timer;
    int users;
    refcount_t refcnt;
    spinlock_t lock;
    char tm_running;
    char reporter;
    char unsolicit_count;
    char loaded;
    unsigned char gsquery;
    unsigned char crcount;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ip_mc_list {
    struct in_device * interface;
    __be32 multiaddr;
    unsigned int sfmode;
    struct ip_sf_list * sources;
    struct ip_sf_list * tomb;
    long unsigned int[2] sfcount;
    struct ip_mc_list * next;
    struct ip_mc_list * next_rcu;
    struct ip_mc_list * next_hash;
    struct timer_list timer;
    int users;
    refcount_t refcnt;
    spinlock_t lock;
    char tm_running;
    char reporter;
    char unsolicit_count;
    char loaded;
    unsigned char gsquery;
    unsigned char crcount;
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
