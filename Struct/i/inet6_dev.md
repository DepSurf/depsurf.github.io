# Struct: <code>inet6_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct inet6_dev {
    struct net_device * dev;
    struct list_head addr_list;
    struct ifmcaddr6 * mc_list;
    struct ifmcaddr6 * mc_tomb;
    spinlock_t mc_lock;
    unsigned char mc_qrv;
    unsigned char mc_gq_running;
    unsigned char mc_ifc_count;
    unsigned char mc_dad_count;
    long unsigned int mc_v1_seen;
    long unsigned int mc_qi;
    long unsigned int mc_qri;
    long unsigned int mc_maxdelay;
    struct timer_list mc_gq_timer;
    struct timer_list mc_ifc_timer;
    struct timer_list mc_dad_timer;
    struct ifacaddr6 * ac_list;
    rwlock_t lock;
    atomic_t refcnt;
    __u32 if_flags;
    int dead;
    u8[8] rndid;
    struct timer_list regen_timer;
    struct list_head tempaddr_list;
    struct in6_addr token;
    struct neigh_parms * nd_parms;
    struct ipv6_devconf cnf;
    struct ipv6_devstat stats;
    struct timer_list rs_timer;
    __u8 rs_probes;
    __u8 addr_gen_mode;
    long unsigned int tstamp;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct inet6_dev {
    struct net_device * dev;
    struct list_head addr_list;
    struct ifmcaddr6 * mc_list;
    struct ifmcaddr6 * mc_tomb;
    spinlock_t mc_lock;
    unsigned char mc_qrv;
    unsigned char mc_gq_running;
    unsigned char mc_ifc_count;
    unsigned char mc_dad_count;
    long unsigned int mc_v1_seen;
    long unsigned int mc_qi;
    long unsigned int mc_qri;
    long unsigned int mc_maxdelay;
    struct timer_list mc_gq_timer;
    struct timer_list mc_ifc_timer;
    struct timer_list mc_dad_timer;
    struct ifacaddr6 * ac_list;
    rwlock_t lock;
    atomic_t refcnt;
    __u32 if_flags;
    int dead;
    u8[8] rndid;
    struct timer_list regen_timer;
    struct list_head tempaddr_list;
    struct in6_addr token;
    struct neigh_parms * nd_parms;
    struct ipv6_devconf cnf;
    struct ipv6_devstat stats;
    struct timer_list rs_timer;
    __u8 rs_probes;
    __u8 addr_gen_mode;
    long unsigned int tstamp;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct inet6_dev {
    struct net_device * dev;
    struct list_head addr_list;
    struct ifmcaddr6 * mc_list;
    struct ifmcaddr6 * mc_tomb;
    spinlock_t mc_lock;
    unsigned char mc_qrv;
    unsigned char mc_gq_running;
    unsigned char mc_ifc_count;
    unsigned char mc_dad_count;
    long unsigned int mc_v1_seen;
    long unsigned int mc_qi;
    long unsigned int mc_qri;
    long unsigned int mc_maxdelay;
    struct timer_list mc_gq_timer;
    struct timer_list mc_ifc_timer;
    struct timer_list mc_dad_timer;
    struct ifacaddr6 * ac_list;
    rwlock_t lock;
    atomic_t refcnt;
    __u32 if_flags;
    int dead;
    u32 desync_factor;
    u8[8] rndid;
    struct list_head tempaddr_list;
    struct in6_addr token;
    struct neigh_parms * nd_parms;
    struct ipv6_devconf cnf;
    struct ipv6_devstat stats;
    struct timer_list rs_timer;
    __s32 rs_interval;
    __u8 rs_probes;
    __u8 addr_gen_mode;
    long unsigned int tstamp;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct inet6_dev {
    struct net_device * dev;
    struct list_head addr_list;
    struct ifmcaddr6 * mc_list;
    struct ifmcaddr6 * mc_tomb;
    spinlock_t mc_lock;
    unsigned char mc_qrv;
    unsigned char mc_gq_running;
    unsigned char mc_ifc_count;
    unsigned char mc_dad_count;
    long unsigned int mc_v1_seen;
    long unsigned int mc_qi;
    long unsigned int mc_qri;
    long unsigned int mc_maxdelay;
    struct timer_list mc_gq_timer;
    struct timer_list mc_ifc_timer;
    struct timer_list mc_dad_timer;
    struct ifacaddr6 * ac_list;
    rwlock_t lock;
    refcount_t refcnt;
    __u32 if_flags;
    int dead;
    u32 desync_factor;
    u8[8] rndid;
    struct list_head tempaddr_list;
    struct in6_addr token;
    struct neigh_parms * nd_parms;
    struct ipv6_devconf cnf;
    struct ipv6_devstat stats;
    struct timer_list rs_timer;
    __s32 rs_interval;
    __u8 rs_probes;
    long unsigned int tstamp;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct inet6_dev {
    struct net_device * dev;
    struct list_head addr_list;
    struct ifmcaddr6 * mc_list;
    struct ifmcaddr6 * mc_tomb;
    spinlock_t mc_lock;
    unsigned char mc_qrv;
    unsigned char mc_gq_running;
    unsigned char mc_ifc_count;
    unsigned char mc_dad_count;
    long unsigned int mc_v1_seen;
    long unsigned int mc_qi;
    long unsigned int mc_qri;
    long unsigned int mc_maxdelay;
    struct timer_list mc_gq_timer;
    struct timer_list mc_ifc_timer;
    struct timer_list mc_dad_timer;
    struct ifacaddr6 * ac_list;
    rwlock_t lock;
    refcount_t refcnt;
    __u32 if_flags;
    int dead;
    u32 desync_factor;
    u8[8] rndid;
    struct list_head tempaddr_list;
    struct in6_addr token;
    struct neigh_parms * nd_parms;
    struct ipv6_devconf cnf;
    struct ipv6_devstat stats;
    struct timer_list rs_timer;
    __s32 rs_interval;
    __u8 rs_probes;
    long unsigned int tstamp;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct inet6_dev {
    struct net_device * dev;
    struct list_head addr_list;
    struct ifmcaddr6 * mc_list;
    struct ifmcaddr6 * mc_tomb;
    spinlock_t mc_lock;
    unsigned char mc_qrv;
    unsigned char mc_gq_running;
    unsigned char mc_ifc_count;
    unsigned char mc_dad_count;
    long unsigned int mc_v1_seen;
    long unsigned int mc_qi;
    long unsigned int mc_qri;
    long unsigned int mc_maxdelay;
    struct timer_list mc_gq_timer;
    struct timer_list mc_ifc_timer;
    struct timer_list mc_dad_timer;
    struct ifacaddr6 * ac_list;
    rwlock_t lock;
    refcount_t refcnt;
    __u32 if_flags;
    int dead;
    u32 desync_factor;
    u8[8] rndid;
    struct list_head tempaddr_list;
    struct in6_addr token;
    struct neigh_parms * nd_parms;
    struct ipv6_devconf cnf;
    struct ipv6_devstat stats;
    struct timer_list rs_timer;
    __s32 rs_interval;
    __u8 rs_probes;
    long unsigned int tstamp;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct inet6_dev {
    struct net_device * dev;
    struct list_head addr_list;
    struct ifmcaddr6 * mc_list;
    struct ifmcaddr6 * mc_tomb;
    spinlock_t mc_lock;
    unsigned char mc_qrv;
    unsigned char mc_gq_running;
    unsigned char mc_ifc_count;
    unsigned char mc_dad_count;
    long unsigned int mc_v1_seen;
    long unsigned int mc_qi;
    long unsigned int mc_qri;
    long unsigned int mc_maxdelay;
    struct timer_list mc_gq_timer;
    struct timer_list mc_ifc_timer;
    struct timer_list mc_dad_timer;
    struct ifacaddr6 * ac_list;
    rwlock_t lock;
    refcount_t refcnt;
    __u32 if_flags;
    int dead;
    u32 desync_factor;
    u8[8] rndid;
    struct list_head tempaddr_list;
    struct in6_addr token;
    struct neigh_parms * nd_parms;
    struct ipv6_devconf cnf;
    struct ipv6_devstat stats;
    struct timer_list rs_timer;
    __s32 rs_interval;
    __u8 rs_probes;
    long unsigned int tstamp;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct inet6_dev {
    struct net_device * dev;
    struct list_head addr_list;
    struct ifmcaddr6 * mc_list;
    struct ifmcaddr6 * mc_tomb;
    spinlock_t mc_lock;
    unsigned char mc_qrv;
    unsigned char mc_gq_running;
    unsigned char mc_ifc_count;
    unsigned char mc_dad_count;
    long unsigned int mc_v1_seen;
    long unsigned int mc_qi;
    long unsigned int mc_qri;
    long unsigned int mc_maxdelay;
    struct timer_list mc_gq_timer;
    struct timer_list mc_ifc_timer;
    struct timer_list mc_dad_timer;
    struct ifacaddr6 * ac_list;
    rwlock_t lock;
    refcount_t refcnt;
    __u32 if_flags;
    int dead;
    u32 desync_factor;
    u8[8] rndid;
    struct list_head tempaddr_list;
    struct in6_addr token;
    struct neigh_parms * nd_parms;
    struct ipv6_devconf cnf;
    struct ipv6_devstat stats;
    struct timer_list rs_timer;
    __s32 rs_interval;
    __u8 rs_probes;
    long unsigned int tstamp;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct inet6_dev {
    struct net_device * dev;
    struct list_head addr_list;
    struct ifmcaddr6 * mc_list;
    struct ifmcaddr6 * mc_tomb;
    spinlock_t mc_lock;
    unsigned char mc_qrv;
    unsigned char mc_gq_running;
    unsigned char mc_ifc_count;
    unsigned char mc_dad_count;
    long unsigned int mc_v1_seen;
    long unsigned int mc_qi;
    long unsigned int mc_qri;
    long unsigned int mc_maxdelay;
    struct timer_list mc_gq_timer;
    struct timer_list mc_ifc_timer;
    struct timer_list mc_dad_timer;
    struct ifacaddr6 * ac_list;
    rwlock_t lock;
    refcount_t refcnt;
    __u32 if_flags;
    int dead;
    u32 desync_factor;
    u8[8] rndid;
    struct list_head tempaddr_list;
    struct in6_addr token;
    struct neigh_parms * nd_parms;
    struct ipv6_devconf cnf;
    struct ipv6_devstat stats;
    struct timer_list rs_timer;
    __s32 rs_interval;
    __u8 rs_probes;
    long unsigned int tstamp;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct inet6_dev {
    struct net_device * dev;
    struct list_head addr_list;
    struct ifmcaddr6 * mc_list;
    struct ifmcaddr6 * mc_tomb;
    spinlock_t mc_lock;
    unsigned char mc_qrv;
    unsigned char mc_gq_running;
    unsigned char mc_ifc_count;
    unsigned char mc_dad_count;
    long unsigned int mc_v1_seen;
    long unsigned int mc_qi;
    long unsigned int mc_qri;
    long unsigned int mc_maxdelay;
    struct timer_list mc_gq_timer;
    struct timer_list mc_ifc_timer;
    struct timer_list mc_dad_timer;
    struct ifacaddr6 * ac_list;
    rwlock_t lock;
    refcount_t refcnt;
    __u32 if_flags;
    int dead;
    u32 desync_factor;
    struct list_head tempaddr_list;
    struct in6_addr token;
    struct neigh_parms * nd_parms;
    struct ipv6_devconf cnf;
    struct ipv6_devstat stats;
    struct timer_list rs_timer;
    __s32 rs_interval;
    __u8 rs_probes;
    long unsigned int tstamp;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct inet6_dev {
    struct net_device * dev;
    struct list_head addr_list;
    struct ifmcaddr6 * mc_list;
    struct ifmcaddr6 * mc_tomb;
    spinlock_t mc_lock;
    unsigned char mc_qrv;
    unsigned char mc_gq_running;
    unsigned char mc_ifc_count;
    unsigned char mc_dad_count;
    long unsigned int mc_v1_seen;
    long unsigned int mc_qi;
    long unsigned int mc_qri;
    long unsigned int mc_maxdelay;
    struct timer_list mc_gq_timer;
    struct timer_list mc_ifc_timer;
    struct timer_list mc_dad_timer;
    struct ifacaddr6 * ac_list;
    rwlock_t lock;
    refcount_t refcnt;
    __u32 if_flags;
    int dead;
    u32 desync_factor;
    struct list_head tempaddr_list;
    struct in6_addr token;
    struct neigh_parms * nd_parms;
    struct ipv6_devconf cnf;
    struct ipv6_devstat stats;
    struct timer_list rs_timer;
    __s32 rs_interval;
    __u8 rs_probes;
    long unsigned int tstamp;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct inet6_dev {
    struct net_device * dev;
    struct list_head addr_list;
    struct ifmcaddr6 * mc_list;
    struct ifmcaddr6 * mc_tomb;
    unsigned char mc_qrv;
    unsigned char mc_gq_running;
    unsigned char mc_ifc_count;
    unsigned char mc_dad_count;
    long unsigned int mc_v1_seen;
    long unsigned int mc_qi;
    long unsigned int mc_qri;
    long unsigned int mc_maxdelay;
    struct delayed_work mc_gq_work;
    struct delayed_work mc_ifc_work;
    struct delayed_work mc_dad_work;
    struct delayed_work mc_query_work;
    struct delayed_work mc_report_work;
    struct sk_buff_head mc_query_queue;
    struct sk_buff_head mc_report_queue;
    spinlock_t mc_query_lock;
    spinlock_t mc_report_lock;
    struct mutex mc_lock;
    struct ifacaddr6 * ac_list;
    rwlock_t lock;
    refcount_t refcnt;
    __u32 if_flags;
    int dead;
    u32 desync_factor;
    struct list_head tempaddr_list;
    struct in6_addr token;
    struct neigh_parms * nd_parms;
    struct ipv6_devconf cnf;
    struct ipv6_devstat stats;
    struct timer_list rs_timer;
    __s32 rs_interval;
    __u8 rs_probes;
    long unsigned int tstamp;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct inet6_dev {
    struct net_device * dev;
    struct list_head addr_list;
    struct ifmcaddr6 * mc_list;
    struct ifmcaddr6 * mc_tomb;
    unsigned char mc_qrv;
    unsigned char mc_gq_running;
    unsigned char mc_ifc_count;
    unsigned char mc_dad_count;
    long unsigned int mc_v1_seen;
    long unsigned int mc_qi;
    long unsigned int mc_qri;
    long unsigned int mc_maxdelay;
    struct delayed_work mc_gq_work;
    struct delayed_work mc_ifc_work;
    struct delayed_work mc_dad_work;
    struct delayed_work mc_query_work;
    struct delayed_work mc_report_work;
    struct sk_buff_head mc_query_queue;
    struct sk_buff_head mc_report_queue;
    spinlock_t mc_query_lock;
    spinlock_t mc_report_lock;
    struct mutex mc_lock;
    struct ifacaddr6 * ac_list;
    rwlock_t lock;
    refcount_t refcnt;
    __u32 if_flags;
    int dead;
    u32 desync_factor;
    struct list_head tempaddr_list;
    struct in6_addr token;
    struct neigh_parms * nd_parms;
    struct ipv6_devconf cnf;
    struct ipv6_devstat stats;
    struct timer_list rs_timer;
    __s32 rs_interval;
    __u8 rs_probes;
    long unsigned int tstamp;
    struct callback_head rcu;
    unsigned int ra_mtu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct inet6_dev {
    struct net_device * dev;
    netdevice_tracker dev_tracker;
    struct list_head addr_list;
    struct ifmcaddr6 * mc_list;
    struct ifmcaddr6 * mc_tomb;
    unsigned char mc_qrv;
    unsigned char mc_gq_running;
    unsigned char mc_ifc_count;
    unsigned char mc_dad_count;
    long unsigned int mc_v1_seen;
    long unsigned int mc_qi;
    long unsigned int mc_qri;
    long unsigned int mc_maxdelay;
    struct delayed_work mc_gq_work;
    struct delayed_work mc_ifc_work;
    struct delayed_work mc_dad_work;
    struct delayed_work mc_query_work;
    struct delayed_work mc_report_work;
    struct sk_buff_head mc_query_queue;
    struct sk_buff_head mc_report_queue;
    spinlock_t mc_query_lock;
    spinlock_t mc_report_lock;
    struct mutex mc_lock;
    struct ifacaddr6 * ac_list;
    rwlock_t lock;
    refcount_t refcnt;
    __u32 if_flags;
    int dead;
    u32 desync_factor;
    struct list_head tempaddr_list;
    struct in6_addr token;
    struct neigh_parms * nd_parms;
    struct ipv6_devconf cnf;
    struct ipv6_devstat stats;
    struct timer_list rs_timer;
    __s32 rs_interval;
    __u8 rs_probes;
    long unsigned int tstamp;
    struct callback_head rcu;
    unsigned int ra_mtu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct inet6_dev {
    struct net_device * dev;
    netdevice_tracker dev_tracker;
    struct list_head addr_list;
    struct ifmcaddr6 * mc_list;
    struct ifmcaddr6 * mc_tomb;
    unsigned char mc_qrv;
    unsigned char mc_gq_running;
    unsigned char mc_ifc_count;
    unsigned char mc_dad_count;
    long unsigned int mc_v1_seen;
    long unsigned int mc_qi;
    long unsigned int mc_qri;
    long unsigned int mc_maxdelay;
    struct delayed_work mc_gq_work;
    struct delayed_work mc_ifc_work;
    struct delayed_work mc_dad_work;
    struct delayed_work mc_query_work;
    struct delayed_work mc_report_work;
    struct sk_buff_head mc_query_queue;
    struct sk_buff_head mc_report_queue;
    spinlock_t mc_query_lock;
    spinlock_t mc_report_lock;
    struct mutex mc_lock;
    struct ifacaddr6 * ac_list;
    rwlock_t lock;
    refcount_t refcnt;
    __u32 if_flags;
    int dead;
    u32 desync_factor;
    struct list_head tempaddr_list;
    struct in6_addr token;
    struct neigh_parms * nd_parms;
    struct ipv6_devconf cnf;
    struct ipv6_devstat stats;
    struct timer_list rs_timer;
    __s32 rs_interval;
    __u8 rs_probes;
    long unsigned int tstamp;
    struct callback_head rcu;
    unsigned int ra_mtu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct inet6_dev {
    struct net_device * dev;
    netdevice_tracker dev_tracker;
    struct list_head addr_list;
    struct ifmcaddr6 * mc_list;
    struct ifmcaddr6 * mc_tomb;
    unsigned char mc_qrv;
    unsigned char mc_gq_running;
    unsigned char mc_ifc_count;
    unsigned char mc_dad_count;
    long unsigned int mc_v1_seen;
    long unsigned int mc_qi;
    long unsigned int mc_qri;
    long unsigned int mc_maxdelay;
    struct delayed_work mc_gq_work;
    struct delayed_work mc_ifc_work;
    struct delayed_work mc_dad_work;
    struct delayed_work mc_query_work;
    struct delayed_work mc_report_work;
    struct sk_buff_head mc_query_queue;
    struct sk_buff_head mc_report_queue;
    spinlock_t mc_query_lock;
    spinlock_t mc_report_lock;
    struct mutex mc_lock;
    struct ifacaddr6 * ac_list;
    rwlock_t lock;
    refcount_t refcnt;
    __u32 if_flags;
    int dead;
    u32 desync_factor;
    struct list_head tempaddr_list;
    struct in6_addr token;
    struct neigh_parms * nd_parms;
    struct ipv6_devconf cnf;
    struct ipv6_devstat stats;
    struct timer_list rs_timer;
    __s32 rs_interval;
    __u8 rs_probes;
    long unsigned int tstamp;
    struct callback_head rcu;
    unsigned int ra_mtu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct inet6_dev {
    struct net_device * dev;
    netdevice_tracker dev_tracker;
    struct list_head addr_list;
    struct ifmcaddr6 * mc_list;
    struct ifmcaddr6 * mc_tomb;
    unsigned char mc_qrv;
    unsigned char mc_gq_running;
    unsigned char mc_ifc_count;
    unsigned char mc_dad_count;
    long unsigned int mc_v1_seen;
    long unsigned int mc_qi;
    long unsigned int mc_qri;
    long unsigned int mc_maxdelay;
    struct delayed_work mc_gq_work;
    struct delayed_work mc_ifc_work;
    struct delayed_work mc_dad_work;
    struct delayed_work mc_query_work;
    struct delayed_work mc_report_work;
    struct sk_buff_head mc_query_queue;
    struct sk_buff_head mc_report_queue;
    spinlock_t mc_query_lock;
    spinlock_t mc_report_lock;
    struct mutex mc_lock;
    struct ifacaddr6 * ac_list;
    rwlock_t lock;
    refcount_t refcnt;
    __u32 if_flags;
    int dead;
    u32 desync_factor;
    struct list_head tempaddr_list;
    struct in6_addr token;
    struct neigh_parms * nd_parms;
    struct ipv6_devconf cnf;
    struct ipv6_devstat stats;
    struct timer_list rs_timer;
    __s32 rs_interval;
    __u8 rs_probes;
    long unsigned int tstamp;
    struct callback_head rcu;
    unsigned int ra_mtu;
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
struct inet6_dev {
    struct net_device * dev;
    struct list_head addr_list;
    struct ifmcaddr6 * mc_list;
    struct ifmcaddr6 * mc_tomb;
    spinlock_t mc_lock;
    unsigned char mc_qrv;
    unsigned char mc_gq_running;
    unsigned char mc_ifc_count;
    unsigned char mc_dad_count;
    long unsigned int mc_v1_seen;
    long unsigned int mc_qi;
    long unsigned int mc_qri;
    long unsigned int mc_maxdelay;
    struct timer_list mc_gq_timer;
    struct timer_list mc_ifc_timer;
    struct timer_list mc_dad_timer;
    struct ifacaddr6 * ac_list;
    rwlock_t lock;
    refcount_t refcnt;
    __u32 if_flags;
    int dead;
    u32 desync_factor;
    u8[8] rndid;
    struct list_head tempaddr_list;
    struct in6_addr token;
    struct neigh_parms * nd_parms;
    struct ipv6_devconf cnf;
    struct ipv6_devstat stats;
    struct timer_list rs_timer;
    __s32 rs_interval;
    __u8 rs_probes;
    long unsigned int tstamp;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct inet6_dev {
    struct net_device * dev;
    struct list_head addr_list;
    struct ifmcaddr6 * mc_list;
    struct ifmcaddr6 * mc_tomb;
    spinlock_t mc_lock;
    unsigned char mc_qrv;
    unsigned char mc_gq_running;
    unsigned char mc_ifc_count;
    unsigned char mc_dad_count;
    long unsigned int mc_v1_seen;
    long unsigned int mc_qi;
    long unsigned int mc_qri;
    long unsigned int mc_maxdelay;
    struct timer_list mc_gq_timer;
    struct timer_list mc_ifc_timer;
    struct timer_list mc_dad_timer;
    struct ifacaddr6 * ac_list;
    rwlock_t lock;
    refcount_t refcnt;
    __u32 if_flags;
    int dead;
    u32 desync_factor;
    u8[8] rndid;
    struct list_head tempaddr_list;
    struct in6_addr token;
    struct neigh_parms * nd_parms;
    struct ipv6_devconf cnf;
    struct ipv6_devstat stats;
    struct timer_list rs_timer;
    __s32 rs_interval;
    __u8 rs_probes;
    long unsigned int tstamp;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct inet6_dev {
    struct net_device * dev;
    struct list_head addr_list;
    struct ifmcaddr6 * mc_list;
    struct ifmcaddr6 * mc_tomb;
    spinlock_t mc_lock;
    unsigned char mc_qrv;
    unsigned char mc_gq_running;
    unsigned char mc_ifc_count;
    unsigned char mc_dad_count;
    long unsigned int mc_v1_seen;
    long unsigned int mc_qi;
    long unsigned int mc_qri;
    long unsigned int mc_maxdelay;
    struct timer_list mc_gq_timer;
    struct timer_list mc_ifc_timer;
    struct timer_list mc_dad_timer;
    struct ifacaddr6 * ac_list;
    rwlock_t lock;
    refcount_t refcnt;
    __u32 if_flags;
    int dead;
    u32 desync_factor;
    u8[8] rndid;
    struct list_head tempaddr_list;
    struct in6_addr token;
    struct neigh_parms * nd_parms;
    struct ipv6_devconf cnf;
    struct ipv6_devstat stats;
    struct timer_list rs_timer;
    __s32 rs_interval;
    __u8 rs_probes;
    long unsigned int tstamp;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct inet6_dev {
    struct net_device * dev;
    struct list_head addr_list;
    struct ifmcaddr6 * mc_list;
    struct ifmcaddr6 * mc_tomb;
    spinlock_t mc_lock;
    unsigned char mc_qrv;
    unsigned char mc_gq_running;
    unsigned char mc_ifc_count;
    unsigned char mc_dad_count;
    long unsigned int mc_v1_seen;
    long unsigned int mc_qi;
    long unsigned int mc_qri;
    long unsigned int mc_maxdelay;
    struct timer_list mc_gq_timer;
    struct timer_list mc_ifc_timer;
    struct timer_list mc_dad_timer;
    struct ifacaddr6 * ac_list;
    rwlock_t lock;
    refcount_t refcnt;
    __u32 if_flags;
    int dead;
    u32 desync_factor;
    u8[8] rndid;
    struct list_head tempaddr_list;
    struct in6_addr token;
    struct neigh_parms * nd_parms;
    struct ipv6_devconf cnf;
    struct ipv6_devstat stats;
    struct timer_list rs_timer;
    __s32 rs_interval;
    __u8 rs_probes;
    long unsigned int tstamp;
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
struct inet6_dev {
    struct net_device * dev;
    struct list_head addr_list;
    struct ifmcaddr6 * mc_list;
    struct ifmcaddr6 * mc_tomb;
    spinlock_t mc_lock;
    unsigned char mc_qrv;
    unsigned char mc_gq_running;
    unsigned char mc_ifc_count;
    unsigned char mc_dad_count;
    long unsigned int mc_v1_seen;
    long unsigned int mc_qi;
    long unsigned int mc_qri;
    long unsigned int mc_maxdelay;
    struct timer_list mc_gq_timer;
    struct timer_list mc_ifc_timer;
    struct timer_list mc_dad_timer;
    struct ifacaddr6 * ac_list;
    rwlock_t lock;
    refcount_t refcnt;
    __u32 if_flags;
    int dead;
    u32 desync_factor;
    u8[8] rndid;
    struct list_head tempaddr_list;
    struct in6_addr token;
    struct neigh_parms * nd_parms;
    struct ipv6_devconf cnf;
    struct ipv6_devstat stats;
    struct timer_list rs_timer;
    __s32 rs_interval;
    __u8 rs_probes;
    long unsigned int tstamp;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct inet6_dev {
    struct net_device * dev;
    struct list_head addr_list;
    struct ifmcaddr6 * mc_list;
    struct ifmcaddr6 * mc_tomb;
    spinlock_t mc_lock;
    unsigned char mc_qrv;
    unsigned char mc_gq_running;
    unsigned char mc_ifc_count;
    unsigned char mc_dad_count;
    long unsigned int mc_v1_seen;
    long unsigned int mc_qi;
    long unsigned int mc_qri;
    long unsigned int mc_maxdelay;
    struct timer_list mc_gq_timer;
    struct timer_list mc_ifc_timer;
    struct timer_list mc_dad_timer;
    struct ifacaddr6 * ac_list;
    rwlock_t lock;
    refcount_t refcnt;
    __u32 if_flags;
    int dead;
    u32 desync_factor;
    u8[8] rndid;
    struct list_head tempaddr_list;
    struct in6_addr token;
    struct neigh_parms * nd_parms;
    struct ipv6_devconf cnf;
    struct ipv6_devstat stats;
    struct timer_list rs_timer;
    __s32 rs_interval;
    __u8 rs_probes;
    long unsigned int tstamp;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct inet6_dev {
    struct net_device * dev;
    struct list_head addr_list;
    struct ifmcaddr6 * mc_list;
    struct ifmcaddr6 * mc_tomb;
    spinlock_t mc_lock;
    unsigned char mc_qrv;
    unsigned char mc_gq_running;
    unsigned char mc_ifc_count;
    unsigned char mc_dad_count;
    long unsigned int mc_v1_seen;
    long unsigned int mc_qi;
    long unsigned int mc_qri;
    long unsigned int mc_maxdelay;
    struct timer_list mc_gq_timer;
    struct timer_list mc_ifc_timer;
    struct timer_list mc_dad_timer;
    struct ifacaddr6 * ac_list;
    rwlock_t lock;
    refcount_t refcnt;
    __u32 if_flags;
    int dead;
    u32 desync_factor;
    u8[8] rndid;
    struct list_head tempaddr_list;
    struct in6_addr token;
    struct neigh_parms * nd_parms;
    struct ipv6_devconf cnf;
    struct ipv6_devstat stats;
    struct timer_list rs_timer;
    __s32 rs_interval;
    __u8 rs_probes;
    long unsigned int tstamp;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct inet6_dev {
    struct net_device * dev;
    struct list_head addr_list;
    struct ifmcaddr6 * mc_list;
    struct ifmcaddr6 * mc_tomb;
    spinlock_t mc_lock;
    unsigned char mc_qrv;
    unsigned char mc_gq_running;
    unsigned char mc_ifc_count;
    unsigned char mc_dad_count;
    long unsigned int mc_v1_seen;
    long unsigned int mc_qi;
    long unsigned int mc_qri;
    long unsigned int mc_maxdelay;
    struct timer_list mc_gq_timer;
    struct timer_list mc_ifc_timer;
    struct timer_list mc_dad_timer;
    struct ifacaddr6 * ac_list;
    rwlock_t lock;
    refcount_t refcnt;
    __u32 if_flags;
    int dead;
    u32 desync_factor;
    u8[8] rndid;
    struct list_head tempaddr_list;
    struct in6_addr token;
    struct neigh_parms * nd_parms;
    struct ipv6_devconf cnf;
    struct ipv6_devstat stats;
    struct timer_list rs_timer;
    __s32 rs_interval;
    __u8 rs_probes;
    long unsigned int tstamp;
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 desync_factor</code>
</li>
<li>
<b>Field added. </b>
<code>__s32 rs_interval</code>
</li>
<li>
<b>Field removed. </b>
<code>struct timer_list regen_timer</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>__u8 addr_gen_mode</code>
</li>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>u8[8] rndid</code>
</li>
</ul>
</details>
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
<code>struct delayed_work mc_gq_work</code>
</li>
<li>
<b>Field added. </b>
<code>struct delayed_work mc_ifc_work</code>
</li>
<li>
<b>Field added. </b>
<code>struct delayed_work mc_dad_work</code>
</li>
<li>
<b>Field added. </b>
<code>struct delayed_work mc_query_work</code>
</li>
<li>
<b>Field added. </b>
<code>struct delayed_work mc_report_work</code>
</li>
<li>
<b>Field added. </b>
<code>struct sk_buff_head mc_query_queue</code>
</li>
<li>
<b>Field added. </b>
<code>struct sk_buff_head mc_report_queue</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t mc_query_lock</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t mc_report_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>struct timer_list mc_gq_timer</code>
</li>
<li>
<b>Field removed. </b>
<code>struct timer_list mc_ifc_timer</code>
</li>
<li>
<b>Field removed. </b>
<code>struct timer_list mc_dad_timer</code>
</li>
<li>
<b>Field type changed. </b>
<code>spinlock_t mc_lock</code> ➡️ <code>struct mutex mc_lock</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int ra_mtu</code>
</li>
</ul>
</details>
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
