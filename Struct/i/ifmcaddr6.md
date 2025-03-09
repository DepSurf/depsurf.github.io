# Struct: <code>ifmcaddr6</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ifmcaddr6 {
    struct in6_addr mca_addr;
    struct inet6_dev * idev;
    struct ifmcaddr6 * next;
    struct ip6_sf_list * mca_sources;
    struct ip6_sf_list * mca_tomb;
    unsigned int mca_sfmode;
    unsigned char mca_crcount;
    long unsigned int[2] mca_sfcount;
    struct timer_list mca_timer;
    unsigned int mca_flags;
    int mca_users;
    atomic_t mca_refcnt;
    spinlock_t mca_lock;
    long unsigned int mca_cstamp;
    long unsigned int mca_tstamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct ifmcaddr6 {
    struct in6_addr mca_addr;
    struct inet6_dev * idev;
    struct ifmcaddr6 * next;
    struct ip6_sf_list * mca_sources;
    struct ip6_sf_list * mca_tomb;
    unsigned int mca_sfmode;
    unsigned char mca_crcount;
    long unsigned int[2] mca_sfcount;
    struct timer_list mca_timer;
    unsigned int mca_flags;
    int mca_users;
    atomic_t mca_refcnt;
    spinlock_t mca_lock;
    long unsigned int mca_cstamp;
    long unsigned int mca_tstamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct ifmcaddr6 {
    struct in6_addr mca_addr;
    struct inet6_dev * idev;
    struct ifmcaddr6 * next;
    struct ip6_sf_list * mca_sources;
    struct ip6_sf_list * mca_tomb;
    unsigned int mca_sfmode;
    unsigned char mca_crcount;
    long unsigned int[2] mca_sfcount;
    struct timer_list mca_timer;
    unsigned int mca_flags;
    int mca_users;
    atomic_t mca_refcnt;
    spinlock_t mca_lock;
    long unsigned int mca_cstamp;
    long unsigned int mca_tstamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct ifmcaddr6 {
    struct in6_addr mca_addr;
    struct inet6_dev * idev;
    struct ifmcaddr6 * next;
    struct ip6_sf_list * mca_sources;
    struct ip6_sf_list * mca_tomb;
    unsigned int mca_sfmode;
    unsigned char mca_crcount;
    long unsigned int[2] mca_sfcount;
    struct timer_list mca_timer;
    unsigned int mca_flags;
    int mca_users;
    refcount_t mca_refcnt;
    spinlock_t mca_lock;
    long unsigned int mca_cstamp;
    long unsigned int mca_tstamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ifmcaddr6 {
    struct in6_addr mca_addr;
    struct inet6_dev * idev;
    struct ifmcaddr6 * next;
    struct ip6_sf_list * mca_sources;
    struct ip6_sf_list * mca_tomb;
    unsigned int mca_sfmode;
    unsigned char mca_crcount;
    long unsigned int[2] mca_sfcount;
    struct timer_list mca_timer;
    unsigned int mca_flags;
    int mca_users;
    refcount_t mca_refcnt;
    spinlock_t mca_lock;
    long unsigned int mca_cstamp;
    long unsigned int mca_tstamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ifmcaddr6 {
    struct in6_addr mca_addr;
    struct inet6_dev * idev;
    struct ifmcaddr6 * next;
    struct ip6_sf_list * mca_sources;
    struct ip6_sf_list * mca_tomb;
    unsigned int mca_sfmode;
    unsigned char mca_crcount;
    long unsigned int[2] mca_sfcount;
    struct timer_list mca_timer;
    unsigned int mca_flags;
    int mca_users;
    refcount_t mca_refcnt;
    spinlock_t mca_lock;
    long unsigned int mca_cstamp;
    long unsigned int mca_tstamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ifmcaddr6 {
    struct in6_addr mca_addr;
    struct inet6_dev * idev;
    struct ifmcaddr6 * next;
    struct ip6_sf_list * mca_sources;
    struct ip6_sf_list * mca_tomb;
    unsigned int mca_sfmode;
    unsigned char mca_crcount;
    long unsigned int[2] mca_sfcount;
    struct timer_list mca_timer;
    unsigned int mca_flags;
    int mca_users;
    refcount_t mca_refcnt;
    spinlock_t mca_lock;
    long unsigned int mca_cstamp;
    long unsigned int mca_tstamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ifmcaddr6 {
    struct in6_addr mca_addr;
    struct inet6_dev * idev;
    struct ifmcaddr6 * next;
    struct ip6_sf_list * mca_sources;
    struct ip6_sf_list * mca_tomb;
    unsigned int mca_sfmode;
    unsigned char mca_crcount;
    long unsigned int[2] mca_sfcount;
    struct timer_list mca_timer;
    unsigned int mca_flags;
    int mca_users;
    refcount_t mca_refcnt;
    spinlock_t mca_lock;
    long unsigned int mca_cstamp;
    long unsigned int mca_tstamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ifmcaddr6 {
    struct in6_addr mca_addr;
    struct inet6_dev * idev;
    struct ifmcaddr6 * next;
    struct ip6_sf_list * mca_sources;
    struct ip6_sf_list * mca_tomb;
    unsigned int mca_sfmode;
    unsigned char mca_crcount;
    long unsigned int[2] mca_sfcount;
    struct timer_list mca_timer;
    unsigned int mca_flags;
    int mca_users;
    refcount_t mca_refcnt;
    spinlock_t mca_lock;
    long unsigned int mca_cstamp;
    long unsigned int mca_tstamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ifmcaddr6 {
    struct in6_addr mca_addr;
    struct inet6_dev * idev;
    struct ifmcaddr6 * next;
    struct ip6_sf_list * mca_sources;
    struct ip6_sf_list * mca_tomb;
    unsigned int mca_sfmode;
    unsigned char mca_crcount;
    long unsigned int[2] mca_sfcount;
    struct timer_list mca_timer;
    unsigned int mca_flags;
    int mca_users;
    refcount_t mca_refcnt;
    spinlock_t mca_lock;
    long unsigned int mca_cstamp;
    long unsigned int mca_tstamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ifmcaddr6 {
    struct in6_addr mca_addr;
    struct inet6_dev * idev;
    struct ifmcaddr6 * next;
    struct ip6_sf_list * mca_sources;
    struct ip6_sf_list * mca_tomb;
    unsigned int mca_sfmode;
    unsigned char mca_crcount;
    long unsigned int[2] mca_sfcount;
    struct timer_list mca_timer;
    unsigned int mca_flags;
    int mca_users;
    refcount_t mca_refcnt;
    spinlock_t mca_lock;
    long unsigned int mca_cstamp;
    long unsigned int mca_tstamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ifmcaddr6 {
    struct in6_addr mca_addr;
    struct inet6_dev * idev;
    struct ifmcaddr6 * next;
    struct ip6_sf_list * mca_sources;
    struct ip6_sf_list * mca_tomb;
    unsigned int mca_sfmode;
    unsigned char mca_crcount;
    long unsigned int[2] mca_sfcount;
    struct delayed_work mca_work;
    unsigned int mca_flags;
    int mca_users;
    refcount_t mca_refcnt;
    long unsigned int mca_cstamp;
    long unsigned int mca_tstamp;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ifmcaddr6 {
    struct in6_addr mca_addr;
    struct inet6_dev * idev;
    struct ifmcaddr6 * next;
    struct ip6_sf_list * mca_sources;
    struct ip6_sf_list * mca_tomb;
    unsigned int mca_sfmode;
    unsigned char mca_crcount;
    long unsigned int[2] mca_sfcount;
    struct delayed_work mca_work;
    unsigned int mca_flags;
    int mca_users;
    refcount_t mca_refcnt;
    long unsigned int mca_cstamp;
    long unsigned int mca_tstamp;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ifmcaddr6 {
    struct in6_addr mca_addr;
    struct inet6_dev * idev;
    struct ifmcaddr6 * next;
    struct ip6_sf_list * mca_sources;
    struct ip6_sf_list * mca_tomb;
    unsigned int mca_sfmode;
    unsigned char mca_crcount;
    long unsigned int[2] mca_sfcount;
    struct delayed_work mca_work;
    unsigned int mca_flags;
    int mca_users;
    refcount_t mca_refcnt;
    long unsigned int mca_cstamp;
    long unsigned int mca_tstamp;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ifmcaddr6 {
    struct in6_addr mca_addr;
    struct inet6_dev * idev;
    struct ifmcaddr6 * next;
    struct ip6_sf_list * mca_sources;
    struct ip6_sf_list * mca_tomb;
    unsigned int mca_sfmode;
    unsigned char mca_crcount;
    long unsigned int[2] mca_sfcount;
    struct delayed_work mca_work;
    unsigned int mca_flags;
    int mca_users;
    refcount_t mca_refcnt;
    long unsigned int mca_cstamp;
    long unsigned int mca_tstamp;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ifmcaddr6 {
    struct in6_addr mca_addr;
    struct inet6_dev * idev;
    struct ifmcaddr6 * next;
    struct ip6_sf_list * mca_sources;
    struct ip6_sf_list * mca_tomb;
    unsigned int mca_sfmode;
    unsigned char mca_crcount;
    long unsigned int[2] mca_sfcount;
    struct delayed_work mca_work;
    unsigned int mca_flags;
    int mca_users;
    refcount_t mca_refcnt;
    long unsigned int mca_cstamp;
    long unsigned int mca_tstamp;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ifmcaddr6 {
    struct in6_addr mca_addr;
    struct inet6_dev * idev;
    struct ifmcaddr6 * next;
    struct ip6_sf_list * mca_sources;
    struct ip6_sf_list * mca_tomb;
    unsigned int mca_sfmode;
    unsigned char mca_crcount;
    long unsigned int[2] mca_sfcount;
    struct delayed_work mca_work;
    unsigned int mca_flags;
    int mca_users;
    refcount_t mca_refcnt;
    long unsigned int mca_cstamp;
    long unsigned int mca_tstamp;
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
struct ifmcaddr6 {
    struct in6_addr mca_addr;
    struct inet6_dev * idev;
    struct ifmcaddr6 * next;
    struct ip6_sf_list * mca_sources;
    struct ip6_sf_list * mca_tomb;
    unsigned int mca_sfmode;
    unsigned char mca_crcount;
    long unsigned int[2] mca_sfcount;
    struct timer_list mca_timer;
    unsigned int mca_flags;
    int mca_users;
    refcount_t mca_refcnt;
    spinlock_t mca_lock;
    long unsigned int mca_cstamp;
    long unsigned int mca_tstamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ifmcaddr6 {
    struct in6_addr mca_addr;
    struct inet6_dev * idev;
    struct ifmcaddr6 * next;
    struct ip6_sf_list * mca_sources;
    struct ip6_sf_list * mca_tomb;
    unsigned int mca_sfmode;
    unsigned char mca_crcount;
    long unsigned int[2] mca_sfcount;
    struct timer_list mca_timer;
    unsigned int mca_flags;
    int mca_users;
    refcount_t mca_refcnt;
    spinlock_t mca_lock;
    long unsigned int mca_cstamp;
    long unsigned int mca_tstamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ifmcaddr6 {
    struct in6_addr mca_addr;
    struct inet6_dev * idev;
    struct ifmcaddr6 * next;
    struct ip6_sf_list * mca_sources;
    struct ip6_sf_list * mca_tomb;
    unsigned int mca_sfmode;
    unsigned char mca_crcount;
    long unsigned int[2] mca_sfcount;
    struct timer_list mca_timer;
    unsigned int mca_flags;
    int mca_users;
    refcount_t mca_refcnt;
    spinlock_t mca_lock;
    long unsigned int mca_cstamp;
    long unsigned int mca_tstamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ifmcaddr6 {
    struct in6_addr mca_addr;
    struct inet6_dev * idev;
    struct ifmcaddr6 * next;
    struct ip6_sf_list * mca_sources;
    struct ip6_sf_list * mca_tomb;
    unsigned int mca_sfmode;
    unsigned char mca_crcount;
    long unsigned int[2] mca_sfcount;
    struct timer_list mca_timer;
    unsigned int mca_flags;
    int mca_users;
    refcount_t mca_refcnt;
    spinlock_t mca_lock;
    long unsigned int mca_cstamp;
    long unsigned int mca_tstamp;
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
struct ifmcaddr6 {
    struct in6_addr mca_addr;
    struct inet6_dev * idev;
    struct ifmcaddr6 * next;
    struct ip6_sf_list * mca_sources;
    struct ip6_sf_list * mca_tomb;
    unsigned int mca_sfmode;
    unsigned char mca_crcount;
    long unsigned int[2] mca_sfcount;
    struct timer_list mca_timer;
    unsigned int mca_flags;
    int mca_users;
    refcount_t mca_refcnt;
    spinlock_t mca_lock;
    long unsigned int mca_cstamp;
    long unsigned int mca_tstamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ifmcaddr6 {
    struct in6_addr mca_addr;
    struct inet6_dev * idev;
    struct ifmcaddr6 * next;
    struct ip6_sf_list * mca_sources;
    struct ip6_sf_list * mca_tomb;
    unsigned int mca_sfmode;
    unsigned char mca_crcount;
    long unsigned int[2] mca_sfcount;
    struct timer_list mca_timer;
    unsigned int mca_flags;
    int mca_users;
    refcount_t mca_refcnt;
    spinlock_t mca_lock;
    long unsigned int mca_cstamp;
    long unsigned int mca_tstamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ifmcaddr6 {
    struct in6_addr mca_addr;
    struct inet6_dev * idev;
    struct ifmcaddr6 * next;
    struct ip6_sf_list * mca_sources;
    struct ip6_sf_list * mca_tomb;
    unsigned int mca_sfmode;
    unsigned char mca_crcount;
    long unsigned int[2] mca_sfcount;
    struct timer_list mca_timer;
    unsigned int mca_flags;
    int mca_users;
    refcount_t mca_refcnt;
    spinlock_t mca_lock;
    long unsigned int mca_cstamp;
    long unsigned int mca_tstamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ifmcaddr6 {
    struct in6_addr mca_addr;
    struct inet6_dev * idev;
    struct ifmcaddr6 * next;
    struct ip6_sf_list * mca_sources;
    struct ip6_sf_list * mca_tomb;
    unsigned int mca_sfmode;
    unsigned char mca_crcount;
    long unsigned int[2] mca_sfcount;
    struct timer_list mca_timer;
    unsigned int mca_flags;
    int mca_users;
    refcount_t mca_refcnt;
    spinlock_t mca_lock;
    long unsigned int mca_cstamp;
    long unsigned int mca_tstamp;
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
<code>atomic_t mca_refcnt</code> ➡️ <code>refcount_t mca_refcnt</code>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct delayed_work mca_work</code>
</li>
<li>
<b>Field added. </b>
<code>struct callback_head rcu</code>
</li>
<li>
<b>Field removed. </b>
<code>struct timer_list mca_timer</code>
</li>
<li>
<b>Field removed. </b>
<code>spinlock_t mca_lock</code>
</li>
</ul>
</details>
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
