# Struct: <code>in_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct in_device {
    struct net_device * dev;
    atomic_t refcnt;
    int dead;
    struct in_ifaddr * ifa_list;
    struct ip_mc_list * mc_list;
    struct ip_mc_list * * mc_hash;
    int mc_count;
    spinlock_t mc_tomb_lock;
    struct ip_mc_list * mc_tomb;
    long unsigned int mr_v1_seen;
    long unsigned int mr_v2_seen;
    long unsigned int mr_maxdelay;
    unsigned char mr_qrv;
    unsigned char mr_gq_running;
    unsigned char mr_ifc_count;
    struct timer_list mr_gq_timer;
    struct timer_list mr_ifc_timer;
    struct neigh_parms * arp_parms;
    struct ipv4_devconf cnf;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct in_device {
    struct net_device * dev;
    atomic_t refcnt;
    int dead;
    struct in_ifaddr * ifa_list;
    struct ip_mc_list * mc_list;
    struct ip_mc_list * * mc_hash;
    int mc_count;
    spinlock_t mc_tomb_lock;
    struct ip_mc_list * mc_tomb;
    long unsigned int mr_v1_seen;
    long unsigned int mr_v2_seen;
    long unsigned int mr_maxdelay;
    unsigned char mr_qrv;
    unsigned char mr_gq_running;
    unsigned char mr_ifc_count;
    struct timer_list mr_gq_timer;
    struct timer_list mr_ifc_timer;
    struct neigh_parms * arp_parms;
    struct ipv4_devconf cnf;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct in_device {
    struct net_device * dev;
    atomic_t refcnt;
    int dead;
    struct in_ifaddr * ifa_list;
    struct ip_mc_list * mc_list;
    struct ip_mc_list * * mc_hash;
    int mc_count;
    spinlock_t mc_tomb_lock;
    struct ip_mc_list * mc_tomb;
    long unsigned int mr_v1_seen;
    long unsigned int mr_v2_seen;
    long unsigned int mr_maxdelay;
    unsigned char mr_qrv;
    unsigned char mr_gq_running;
    unsigned char mr_ifc_count;
    struct timer_list mr_gq_timer;
    struct timer_list mr_ifc_timer;
    struct neigh_parms * arp_parms;
    struct ipv4_devconf cnf;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct in_device {
    struct net_device * dev;
    refcount_t refcnt;
    int dead;
    struct in_ifaddr * ifa_list;
    struct ip_mc_list * mc_list;
    struct ip_mc_list * * mc_hash;
    int mc_count;
    spinlock_t mc_tomb_lock;
    struct ip_mc_list * mc_tomb;
    long unsigned int mr_v1_seen;
    long unsigned int mr_v2_seen;
    long unsigned int mr_maxdelay;
    unsigned char mr_qrv;
    unsigned char mr_gq_running;
    unsigned char mr_ifc_count;
    struct timer_list mr_gq_timer;
    struct timer_list mr_ifc_timer;
    struct neigh_parms * arp_parms;
    struct ipv4_devconf cnf;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct in_device {
    struct net_device * dev;
    refcount_t refcnt;
    int dead;
    struct in_ifaddr * ifa_list;
    struct ip_mc_list * mc_list;
    struct ip_mc_list * * mc_hash;
    int mc_count;
    spinlock_t mc_tomb_lock;
    struct ip_mc_list * mc_tomb;
    long unsigned int mr_v1_seen;
    long unsigned int mr_v2_seen;
    long unsigned int mr_maxdelay;
    unsigned char mr_qrv;
    unsigned char mr_gq_running;
    unsigned char mr_ifc_count;
    struct timer_list mr_gq_timer;
    struct timer_list mr_ifc_timer;
    struct neigh_parms * arp_parms;
    struct ipv4_devconf cnf;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct in_device {
    struct net_device * dev;
    refcount_t refcnt;
    int dead;
    struct in_ifaddr * ifa_list;
    struct ip_mc_list * mc_list;
    struct ip_mc_list * * mc_hash;
    int mc_count;
    spinlock_t mc_tomb_lock;
    struct ip_mc_list * mc_tomb;
    long unsigned int mr_v1_seen;
    long unsigned int mr_v2_seen;
    long unsigned int mr_maxdelay;
    unsigned char mr_qrv;
    unsigned char mr_gq_running;
    unsigned char mr_ifc_count;
    struct timer_list mr_gq_timer;
    struct timer_list mr_ifc_timer;
    struct neigh_parms * arp_parms;
    struct ipv4_devconf cnf;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct in_device {
    struct net_device * dev;
    refcount_t refcnt;
    int dead;
    struct in_ifaddr * ifa_list;
    struct ip_mc_list * mc_list;
    struct ip_mc_list * * mc_hash;
    int mc_count;
    spinlock_t mc_tomb_lock;
    struct ip_mc_list * mc_tomb;
    long unsigned int mr_v1_seen;
    long unsigned int mr_v2_seen;
    long unsigned int mr_maxdelay;
    long unsigned int mr_qi;
    long unsigned int mr_qri;
    unsigned char mr_qrv;
    unsigned char mr_gq_running;
    unsigned char mr_ifc_count;
    struct timer_list mr_gq_timer;
    struct timer_list mr_ifc_timer;
    struct neigh_parms * arp_parms;
    struct ipv4_devconf cnf;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct in_device {
    struct net_device * dev;
    refcount_t refcnt;
    int dead;
    struct in_ifaddr * ifa_list;
    struct ip_mc_list * mc_list;
    struct ip_mc_list * * mc_hash;
    int mc_count;
    spinlock_t mc_tomb_lock;
    struct ip_mc_list * mc_tomb;
    long unsigned int mr_v1_seen;
    long unsigned int mr_v2_seen;
    long unsigned int mr_maxdelay;
    long unsigned int mr_qi;
    long unsigned int mr_qri;
    unsigned char mr_qrv;
    unsigned char mr_gq_running;
    unsigned char mr_ifc_count;
    struct timer_list mr_gq_timer;
    struct timer_list mr_ifc_timer;
    struct neigh_parms * arp_parms;
    struct ipv4_devconf cnf;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct in_device {
    struct net_device * dev;
    refcount_t refcnt;
    int dead;
    struct in_ifaddr * ifa_list;
    struct ip_mc_list * mc_list;
    struct ip_mc_list * * mc_hash;
    int mc_count;
    spinlock_t mc_tomb_lock;
    struct ip_mc_list * mc_tomb;
    long unsigned int mr_v1_seen;
    long unsigned int mr_v2_seen;
    long unsigned int mr_maxdelay;
    long unsigned int mr_qi;
    long unsigned int mr_qri;
    unsigned char mr_qrv;
    unsigned char mr_gq_running;
    unsigned char mr_ifc_count;
    struct timer_list mr_gq_timer;
    struct timer_list mr_ifc_timer;
    struct neigh_parms * arp_parms;
    struct ipv4_devconf cnf;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct in_device {
    struct net_device * dev;
    refcount_t refcnt;
    int dead;
    struct in_ifaddr * ifa_list;
    struct ip_mc_list * mc_list;
    struct ip_mc_list * * mc_hash;
    int mc_count;
    spinlock_t mc_tomb_lock;
    struct ip_mc_list * mc_tomb;
    long unsigned int mr_v1_seen;
    long unsigned int mr_v2_seen;
    long unsigned int mr_maxdelay;
    long unsigned int mr_qi;
    long unsigned int mr_qri;
    unsigned char mr_qrv;
    unsigned char mr_gq_running;
    unsigned char mr_ifc_count;
    struct timer_list mr_gq_timer;
    struct timer_list mr_ifc_timer;
    struct neigh_parms * arp_parms;
    struct ipv4_devconf cnf;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct in_device {
    struct net_device * dev;
    refcount_t refcnt;
    int dead;
    struct in_ifaddr * ifa_list;
    struct ip_mc_list * mc_list;
    struct ip_mc_list * * mc_hash;
    int mc_count;
    spinlock_t mc_tomb_lock;
    struct ip_mc_list * mc_tomb;
    long unsigned int mr_v1_seen;
    long unsigned int mr_v2_seen;
    long unsigned int mr_maxdelay;
    long unsigned int mr_qi;
    long unsigned int mr_qri;
    unsigned char mr_qrv;
    unsigned char mr_gq_running;
    unsigned char mr_ifc_count;
    struct timer_list mr_gq_timer;
    struct timer_list mr_ifc_timer;
    struct neigh_parms * arp_parms;
    struct ipv4_devconf cnf;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct in_device {
    struct net_device * dev;
    refcount_t refcnt;
    int dead;
    struct in_ifaddr * ifa_list;
    struct ip_mc_list * mc_list;
    struct ip_mc_list * * mc_hash;
    int mc_count;
    spinlock_t mc_tomb_lock;
    struct ip_mc_list * mc_tomb;
    long unsigned int mr_v1_seen;
    long unsigned int mr_v2_seen;
    long unsigned int mr_maxdelay;
    long unsigned int mr_qi;
    long unsigned int mr_qri;
    unsigned char mr_qrv;
    unsigned char mr_gq_running;
    u32 mr_ifc_count;
    struct timer_list mr_gq_timer;
    struct timer_list mr_ifc_timer;
    struct neigh_parms * arp_parms;
    struct ipv4_devconf cnf;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct in_device {
    struct net_device * dev;
    refcount_t refcnt;
    int dead;
    struct in_ifaddr * ifa_list;
    struct ip_mc_list * mc_list;
    struct ip_mc_list * * mc_hash;
    int mc_count;
    spinlock_t mc_tomb_lock;
    struct ip_mc_list * mc_tomb;
    long unsigned int mr_v1_seen;
    long unsigned int mr_v2_seen;
    long unsigned int mr_maxdelay;
    long unsigned int mr_qi;
    long unsigned int mr_qri;
    unsigned char mr_qrv;
    unsigned char mr_gq_running;
    u32 mr_ifc_count;
    struct timer_list mr_gq_timer;
    struct timer_list mr_ifc_timer;
    struct neigh_parms * arp_parms;
    struct ipv4_devconf cnf;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct in_device {
    struct net_device * dev;
    netdevice_tracker dev_tracker;
    refcount_t refcnt;
    int dead;
    struct in_ifaddr * ifa_list;
    struct ip_mc_list * mc_list;
    struct ip_mc_list * * mc_hash;
    int mc_count;
    spinlock_t mc_tomb_lock;
    struct ip_mc_list * mc_tomb;
    long unsigned int mr_v1_seen;
    long unsigned int mr_v2_seen;
    long unsigned int mr_maxdelay;
    long unsigned int mr_qi;
    long unsigned int mr_qri;
    unsigned char mr_qrv;
    unsigned char mr_gq_running;
    u32 mr_ifc_count;
    struct timer_list mr_gq_timer;
    struct timer_list mr_ifc_timer;
    struct neigh_parms * arp_parms;
    struct ipv4_devconf cnf;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct in_device {
    struct net_device * dev;
    netdevice_tracker dev_tracker;
    refcount_t refcnt;
    int dead;
    struct in_ifaddr * ifa_list;
    struct ip_mc_list * mc_list;
    struct ip_mc_list * * mc_hash;
    int mc_count;
    spinlock_t mc_tomb_lock;
    struct ip_mc_list * mc_tomb;
    long unsigned int mr_v1_seen;
    long unsigned int mr_v2_seen;
    long unsigned int mr_maxdelay;
    long unsigned int mr_qi;
    long unsigned int mr_qri;
    unsigned char mr_qrv;
    unsigned char mr_gq_running;
    u32 mr_ifc_count;
    struct timer_list mr_gq_timer;
    struct timer_list mr_ifc_timer;
    struct neigh_parms * arp_parms;
    struct ipv4_devconf cnf;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct in_device {
    struct net_device * dev;
    netdevice_tracker dev_tracker;
    refcount_t refcnt;
    int dead;
    struct in_ifaddr * ifa_list;
    struct ip_mc_list * mc_list;
    struct ip_mc_list * * mc_hash;
    int mc_count;
    spinlock_t mc_tomb_lock;
    struct ip_mc_list * mc_tomb;
    long unsigned int mr_v1_seen;
    long unsigned int mr_v2_seen;
    long unsigned int mr_maxdelay;
    long unsigned int mr_qi;
    long unsigned int mr_qri;
    unsigned char mr_qrv;
    unsigned char mr_gq_running;
    u32 mr_ifc_count;
    struct timer_list mr_gq_timer;
    struct timer_list mr_ifc_timer;
    struct neigh_parms * arp_parms;
    struct ipv4_devconf cnf;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct in_device {
    struct net_device * dev;
    netdevice_tracker dev_tracker;
    refcount_t refcnt;
    int dead;
    struct in_ifaddr * ifa_list;
    struct ip_mc_list * mc_list;
    struct ip_mc_list * * mc_hash;
    int mc_count;
    spinlock_t mc_tomb_lock;
    struct ip_mc_list * mc_tomb;
    long unsigned int mr_v1_seen;
    long unsigned int mr_v2_seen;
    long unsigned int mr_maxdelay;
    long unsigned int mr_qi;
    long unsigned int mr_qri;
    unsigned char mr_qrv;
    unsigned char mr_gq_running;
    u32 mr_ifc_count;
    struct timer_list mr_gq_timer;
    struct timer_list mr_ifc_timer;
    struct neigh_parms * arp_parms;
    struct ipv4_devconf cnf;
    struct callback_head callback_head;
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
struct in_device {
    struct net_device * dev;
    refcount_t refcnt;
    int dead;
    struct in_ifaddr * ifa_list;
    struct ip_mc_list * mc_list;
    struct ip_mc_list * * mc_hash;
    int mc_count;
    spinlock_t mc_tomb_lock;
    struct ip_mc_list * mc_tomb;
    long unsigned int mr_v1_seen;
    long unsigned int mr_v2_seen;
    long unsigned int mr_maxdelay;
    long unsigned int mr_qi;
    long unsigned int mr_qri;
    unsigned char mr_qrv;
    unsigned char mr_gq_running;
    unsigned char mr_ifc_count;
    struct timer_list mr_gq_timer;
    struct timer_list mr_ifc_timer;
    struct neigh_parms * arp_parms;
    struct ipv4_devconf cnf;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct in_device {
    struct net_device * dev;
    refcount_t refcnt;
    int dead;
    struct in_ifaddr * ifa_list;
    struct ip_mc_list * mc_list;
    struct ip_mc_list * * mc_hash;
    int mc_count;
    spinlock_t mc_tomb_lock;
    struct ip_mc_list * mc_tomb;
    long unsigned int mr_v1_seen;
    long unsigned int mr_v2_seen;
    long unsigned int mr_maxdelay;
    long unsigned int mr_qi;
    long unsigned int mr_qri;
    unsigned char mr_qrv;
    unsigned char mr_gq_running;
    unsigned char mr_ifc_count;
    struct timer_list mr_gq_timer;
    struct timer_list mr_ifc_timer;
    struct neigh_parms * arp_parms;
    struct ipv4_devconf cnf;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct in_device {
    struct net_device * dev;
    refcount_t refcnt;
    int dead;
    struct in_ifaddr * ifa_list;
    struct ip_mc_list * mc_list;
    struct ip_mc_list * * mc_hash;
    int mc_count;
    spinlock_t mc_tomb_lock;
    struct ip_mc_list * mc_tomb;
    long unsigned int mr_v1_seen;
    long unsigned int mr_v2_seen;
    long unsigned int mr_maxdelay;
    long unsigned int mr_qi;
    long unsigned int mr_qri;
    unsigned char mr_qrv;
    unsigned char mr_gq_running;
    unsigned char mr_ifc_count;
    struct timer_list mr_gq_timer;
    struct timer_list mr_ifc_timer;
    struct neigh_parms * arp_parms;
    struct ipv4_devconf cnf;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct in_device {
    struct net_device * dev;
    refcount_t refcnt;
    int dead;
    struct in_ifaddr * ifa_list;
    struct ip_mc_list * mc_list;
    struct ip_mc_list * * mc_hash;
    int mc_count;
    spinlock_t mc_tomb_lock;
    struct ip_mc_list * mc_tomb;
    long unsigned int mr_v1_seen;
    long unsigned int mr_v2_seen;
    long unsigned int mr_maxdelay;
    long unsigned int mr_qi;
    long unsigned int mr_qri;
    unsigned char mr_qrv;
    unsigned char mr_gq_running;
    unsigned char mr_ifc_count;
    struct timer_list mr_gq_timer;
    struct timer_list mr_ifc_timer;
    struct neigh_parms * arp_parms;
    struct ipv4_devconf cnf;
    struct callback_head callback_head;
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
struct in_device {
    struct net_device * dev;
    refcount_t refcnt;
    int dead;
    struct in_ifaddr * ifa_list;
    struct ip_mc_list * mc_list;
    struct ip_mc_list * * mc_hash;
    int mc_count;
    spinlock_t mc_tomb_lock;
    struct ip_mc_list * mc_tomb;
    long unsigned int mr_v1_seen;
    long unsigned int mr_v2_seen;
    long unsigned int mr_maxdelay;
    long unsigned int mr_qi;
    long unsigned int mr_qri;
    unsigned char mr_qrv;
    unsigned char mr_gq_running;
    unsigned char mr_ifc_count;
    struct timer_list mr_gq_timer;
    struct timer_list mr_ifc_timer;
    struct neigh_parms * arp_parms;
    struct ipv4_devconf cnf;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct in_device {
    struct net_device * dev;
    refcount_t refcnt;
    int dead;
    struct in_ifaddr * ifa_list;
    struct ip_mc_list * mc_list;
    struct ip_mc_list * * mc_hash;
    int mc_count;
    spinlock_t mc_tomb_lock;
    struct ip_mc_list * mc_tomb;
    long unsigned int mr_v1_seen;
    long unsigned int mr_v2_seen;
    long unsigned int mr_maxdelay;
    long unsigned int mr_qi;
    long unsigned int mr_qri;
    unsigned char mr_qrv;
    unsigned char mr_gq_running;
    unsigned char mr_ifc_count;
    struct timer_list mr_gq_timer;
    struct timer_list mr_ifc_timer;
    struct neigh_parms * arp_parms;
    struct ipv4_devconf cnf;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct in_device {
    struct net_device * dev;
    refcount_t refcnt;
    int dead;
    struct in_ifaddr * ifa_list;
    struct ip_mc_list * mc_list;
    struct ip_mc_list * * mc_hash;
    int mc_count;
    spinlock_t mc_tomb_lock;
    struct ip_mc_list * mc_tomb;
    long unsigned int mr_v1_seen;
    long unsigned int mr_v2_seen;
    long unsigned int mr_maxdelay;
    long unsigned int mr_qi;
    long unsigned int mr_qri;
    unsigned char mr_qrv;
    unsigned char mr_gq_running;
    unsigned char mr_ifc_count;
    struct timer_list mr_gq_timer;
    struct timer_list mr_ifc_timer;
    struct neigh_parms * arp_parms;
    struct ipv4_devconf cnf;
    struct callback_head callback_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct in_device {
    struct net_device * dev;
    refcount_t refcnt;
    int dead;
    struct in_ifaddr * ifa_list;
    struct ip_mc_list * mc_list;
    struct ip_mc_list * * mc_hash;
    int mc_count;
    spinlock_t mc_tomb_lock;
    struct ip_mc_list * mc_tomb;
    long unsigned int mr_v1_seen;
    long unsigned int mr_v2_seen;
    long unsigned int mr_maxdelay;
    long unsigned int mr_qi;
    long unsigned int mr_qri;
    unsigned char mr_qrv;
    unsigned char mr_gq_running;
    unsigned char mr_ifc_count;
    struct timer_list mr_gq_timer;
    struct timer_list mr_ifc_timer;
    struct neigh_parms * arp_parms;
    struct ipv4_devconf cnf;
    struct callback_head callback_head;
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int mr_qi</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int mr_qri</code>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>unsigned char mr_ifc_count</code> ➡️ <code>u32 mr_ifc_count</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>netdevice_tracker dev_tracker</code>
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
