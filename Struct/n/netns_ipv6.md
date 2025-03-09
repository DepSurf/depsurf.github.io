# Struct: <code>netns_ipv6</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct netns_ipv6 {
    struct netns_sysctl_ipv6 sysctl;
    struct ipv6_devconf * devconf_all;
    struct ipv6_devconf * devconf_dflt;
    struct inet_peer_base * peers;
    struct netns_frags frags;
    struct xt_table * ip6table_filter;
    struct xt_table * ip6table_mangle;
    struct xt_table * ip6table_raw;
    struct xt_table * ip6table_security;
    struct xt_table * ip6table_nat;
    struct rt6_info * ip6_null_entry;
    struct rt6_statistics * rt6_stats;
    struct timer_list ip6_fib_timer;
    struct hlist_head * fib_table_hash;
    struct fib6_table * fib6_main_tbl;
    struct dst_ops ip6_dst_ops;
    unsigned int ip6_rt_gc_expire;
    long unsigned int ip6_rt_last_gc;
    struct rt6_info * ip6_prohibit_entry;
    struct rt6_info * ip6_blk_hole_entry;
    struct fib6_table * fib6_local_tbl;
    struct fib_rules_ops * fib6_rules_ops;
    struct sock * * icmp_sk;
    struct sock * ndisc_sk;
    struct sock * tcp_sk;
    struct sock * igmp_sk;
    struct sock * mc_autojoin_sk;
    struct list_head mr6_tables;
    struct fib_rules_ops * mr6_rules_ops;
    atomic_t dev_addr_genid;
    atomic_t fib6_sernum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct netns_ipv6 {
    struct netns_sysctl_ipv6 sysctl;
    struct ipv6_devconf * devconf_all;
    struct ipv6_devconf * devconf_dflt;
    struct inet_peer_base * peers;
    struct netns_frags frags;
    struct xt_table * ip6table_filter;
    struct xt_table * ip6table_mangle;
    struct xt_table * ip6table_raw;
    struct xt_table * ip6table_security;
    struct xt_table * ip6table_nat;
    struct rt6_info * ip6_null_entry;
    struct rt6_statistics * rt6_stats;
    struct timer_list ip6_fib_timer;
    struct hlist_head * fib_table_hash;
    struct fib6_table * fib6_main_tbl;
    struct list_head fib6_walkers;
    struct dst_ops ip6_dst_ops;
    rwlock_t fib6_walker_lock;
    spinlock_t fib6_gc_lock;
    unsigned int ip6_rt_gc_expire;
    long unsigned int ip6_rt_last_gc;
    struct rt6_info * ip6_prohibit_entry;
    struct rt6_info * ip6_blk_hole_entry;
    struct fib6_table * fib6_local_tbl;
    struct fib_rules_ops * fib6_rules_ops;
    struct sock * * icmp_sk;
    struct sock * ndisc_sk;
    struct sock * tcp_sk;
    struct sock * igmp_sk;
    struct sock * mc_autojoin_sk;
    struct list_head mr6_tables;
    struct fib_rules_ops * mr6_rules_ops;
    atomic_t dev_addr_genid;
    atomic_t fib6_sernum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct netns_ipv6 {
    struct netns_sysctl_ipv6 sysctl;
    struct ipv6_devconf * devconf_all;
    struct ipv6_devconf * devconf_dflt;
    struct inet_peer_base * peers;
    struct netns_frags frags;
    struct xt_table * ip6table_filter;
    struct xt_table * ip6table_mangle;
    struct xt_table * ip6table_raw;
    struct xt_table * ip6table_security;
    struct xt_table * ip6table_nat;
    struct rt6_info * ip6_null_entry;
    struct rt6_statistics * rt6_stats;
    struct timer_list ip6_fib_timer;
    struct hlist_head * fib_table_hash;
    struct fib6_table * fib6_main_tbl;
    struct list_head fib6_walkers;
    struct dst_ops ip6_dst_ops;
    rwlock_t fib6_walker_lock;
    spinlock_t fib6_gc_lock;
    unsigned int ip6_rt_gc_expire;
    long unsigned int ip6_rt_last_gc;
    struct rt6_info * ip6_prohibit_entry;
    struct rt6_info * ip6_blk_hole_entry;
    struct fib6_table * fib6_local_tbl;
    struct fib_rules_ops * fib6_rules_ops;
    struct sock * * icmp_sk;
    struct sock * ndisc_sk;
    struct sock * tcp_sk;
    struct sock * igmp_sk;
    struct sock * mc_autojoin_sk;
    struct list_head mr6_tables;
    struct fib_rules_ops * mr6_rules_ops;
    atomic_t dev_addr_genid;
    atomic_t fib6_sernum;
    struct seg6_pernet_data * seg6_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct netns_ipv6 {
    struct netns_sysctl_ipv6 sysctl;
    struct ipv6_devconf * devconf_all;
    struct ipv6_devconf * devconf_dflt;
    struct inet_peer_base * peers;
    struct netns_frags frags;
    struct xt_table * ip6table_filter;
    struct xt_table * ip6table_mangle;
    struct xt_table * ip6table_raw;
    struct xt_table * ip6table_security;
    struct xt_table * ip6table_nat;
    struct rt6_info * ip6_null_entry;
    struct rt6_statistics * rt6_stats;
    struct timer_list ip6_fib_timer;
    struct hlist_head * fib_table_hash;
    struct fib6_table * fib6_main_tbl;
    struct list_head fib6_walkers;
    struct dst_ops ip6_dst_ops;
    rwlock_t fib6_walker_lock;
    spinlock_t fib6_gc_lock;
    unsigned int ip6_rt_gc_expire;
    long unsigned int ip6_rt_last_gc;
    struct rt6_info * ip6_prohibit_entry;
    struct rt6_info * ip6_blk_hole_entry;
    struct fib6_table * fib6_local_tbl;
    struct fib_rules_ops * fib6_rules_ops;
    struct sock * * icmp_sk;
    struct sock * ndisc_sk;
    struct sock * tcp_sk;
    struct sock * igmp_sk;
    struct sock * mc_autojoin_sk;
    struct list_head mr6_tables;
    struct fib_rules_ops * mr6_rules_ops;
    atomic_t dev_addr_genid;
    atomic_t fib6_sernum;
    struct seg6_pernet_data * seg6_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct netns_ipv6 {
    struct netns_sysctl_ipv6 sysctl;
    struct ipv6_devconf * devconf_all;
    struct ipv6_devconf * devconf_dflt;
    struct inet_peer_base * peers;
    struct netns_frags frags;
    struct xt_table * ip6table_filter;
    struct xt_table * ip6table_mangle;
    struct xt_table * ip6table_raw;
    struct xt_table * ip6table_security;
    struct xt_table * ip6table_nat;
    struct rt6_info * ip6_null_entry;
    struct rt6_statistics * rt6_stats;
    struct timer_list ip6_fib_timer;
    struct hlist_head * fib_table_hash;
    struct fib6_table * fib6_main_tbl;
    struct list_head fib6_walkers;
    struct dst_ops ip6_dst_ops;
    rwlock_t fib6_walker_lock;
    spinlock_t fib6_gc_lock;
    unsigned int ip6_rt_gc_expire;
    long unsigned int ip6_rt_last_gc;
    bool fib6_has_custom_rules;
    struct rt6_info * ip6_prohibit_entry;
    struct rt6_info * ip6_blk_hole_entry;
    struct fib6_table * fib6_local_tbl;
    struct fib_rules_ops * fib6_rules_ops;
    struct sock * * icmp_sk;
    struct sock * ndisc_sk;
    struct sock * tcp_sk;
    struct sock * igmp_sk;
    struct sock * mc_autojoin_sk;
    struct list_head mr6_tables;
    struct fib_rules_ops * mr6_rules_ops;
    atomic_t dev_addr_genid;
    atomic_t fib6_sernum;
    struct seg6_pernet_data * seg6_data;
    struct fib_notifier_ops * notifier_ops;
    struct (anon) ip6addrlbl_table;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct netns_ipv6 {
    struct netns_sysctl_ipv6 sysctl;
    struct ipv6_devconf * devconf_all;
    struct ipv6_devconf * devconf_dflt;
    struct inet_peer_base * peers;
    struct netns_frags frags;
    struct xt_table * ip6table_filter;
    struct xt_table * ip6table_mangle;
    struct xt_table * ip6table_raw;
    struct xt_table * ip6table_security;
    struct xt_table * ip6table_nat;
    struct fib6_info * fib6_null_entry;
    struct rt6_info * ip6_null_entry;
    struct rt6_statistics * rt6_stats;
    struct timer_list ip6_fib_timer;
    struct hlist_head * fib_table_hash;
    struct fib6_table * fib6_main_tbl;
    struct list_head fib6_walkers;
    struct dst_ops ip6_dst_ops;
    rwlock_t fib6_walker_lock;
    spinlock_t fib6_gc_lock;
    unsigned int ip6_rt_gc_expire;
    long unsigned int ip6_rt_last_gc;
    unsigned int fib6_rules_require_fldissect;
    bool fib6_has_custom_rules;
    struct rt6_info * ip6_prohibit_entry;
    struct rt6_info * ip6_blk_hole_entry;
    struct fib6_table * fib6_local_tbl;
    struct fib_rules_ops * fib6_rules_ops;
    struct sock * * icmp_sk;
    struct sock * ndisc_sk;
    struct sock * tcp_sk;
    struct sock * igmp_sk;
    struct sock * mc_autojoin_sk;
    struct list_head mr6_tables;
    struct fib_rules_ops * mr6_rules_ops;
    atomic_t dev_addr_genid;
    atomic_t fib6_sernum;
    struct seg6_pernet_data * seg6_data;
    struct fib_notifier_ops * notifier_ops;
    struct fib_notifier_ops * ip6mr_notifier_ops;
    unsigned int ipmr_seq;
    struct (anon) ip6addrlbl_table;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct netns_ipv6 {
    struct netns_sysctl_ipv6 sysctl;
    struct ipv6_devconf * devconf_all;
    struct ipv6_devconf * devconf_dflt;
    struct inet_peer_base * peers;
    struct netns_frags frags;
    struct xt_table * ip6table_filter;
    struct xt_table * ip6table_mangle;
    struct xt_table * ip6table_raw;
    struct xt_table * ip6table_security;
    struct xt_table * ip6table_nat;
    struct fib6_info * fib6_null_entry;
    struct rt6_info * ip6_null_entry;
    struct rt6_statistics * rt6_stats;
    struct timer_list ip6_fib_timer;
    struct hlist_head * fib_table_hash;
    struct fib6_table * fib6_main_tbl;
    struct list_head fib6_walkers;
    struct dst_ops ip6_dst_ops;
    rwlock_t fib6_walker_lock;
    spinlock_t fib6_gc_lock;
    unsigned int ip6_rt_gc_expire;
    long unsigned int ip6_rt_last_gc;
    unsigned int fib6_rules_require_fldissect;
    bool fib6_has_custom_rules;
    struct rt6_info * ip6_prohibit_entry;
    struct rt6_info * ip6_blk_hole_entry;
    struct fib6_table * fib6_local_tbl;
    struct fib_rules_ops * fib6_rules_ops;
    struct sock * * icmp_sk;
    struct sock * ndisc_sk;
    struct sock * tcp_sk;
    struct sock * igmp_sk;
    struct sock * mc_autojoin_sk;
    struct list_head mr6_tables;
    struct fib_rules_ops * mr6_rules_ops;
    atomic_t dev_addr_genid;
    atomic_t fib6_sernum;
    struct seg6_pernet_data * seg6_data;
    struct fib_notifier_ops * notifier_ops;
    struct fib_notifier_ops * ip6mr_notifier_ops;
    unsigned int ipmr_seq;
    struct (anon) ip6addrlbl_table;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct netns_ipv6 {
    struct netns_sysctl_ipv6 sysctl;
    struct ipv6_devconf * devconf_all;
    struct ipv6_devconf * devconf_dflt;
    struct inet_peer_base * peers;
    struct fqdir * fqdir;
    struct xt_table * ip6table_filter;
    struct xt_table * ip6table_mangle;
    struct xt_table * ip6table_raw;
    struct xt_table * ip6table_security;
    struct xt_table * ip6table_nat;
    struct fib6_info * fib6_null_entry;
    struct rt6_info * ip6_null_entry;
    struct rt6_statistics * rt6_stats;
    struct timer_list ip6_fib_timer;
    struct hlist_head * fib_table_hash;
    struct fib6_table * fib6_main_tbl;
    struct list_head fib6_walkers;
    struct dst_ops ip6_dst_ops;
    rwlock_t fib6_walker_lock;
    spinlock_t fib6_gc_lock;
    unsigned int ip6_rt_gc_expire;
    long unsigned int ip6_rt_last_gc;
    unsigned int fib6_rules_require_fldissect;
    bool fib6_has_custom_rules;
    struct rt6_info * ip6_prohibit_entry;
    struct rt6_info * ip6_blk_hole_entry;
    struct fib6_table * fib6_local_tbl;
    struct fib_rules_ops * fib6_rules_ops;
    struct sock * * icmp_sk;
    struct sock * ndisc_sk;
    struct sock * tcp_sk;
    struct sock * igmp_sk;
    struct sock * mc_autojoin_sk;
    struct list_head mr6_tables;
    struct fib_rules_ops * mr6_rules_ops;
    atomic_t dev_addr_genid;
    atomic_t fib6_sernum;
    struct seg6_pernet_data * seg6_data;
    struct fib_notifier_ops * notifier_ops;
    struct fib_notifier_ops * ip6mr_notifier_ops;
    unsigned int ipmr_seq;
    struct (anon) ip6addrlbl_table;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct netns_ipv6 {
    struct netns_sysctl_ipv6 sysctl;
    struct ipv6_devconf * devconf_all;
    struct ipv6_devconf * devconf_dflt;
    struct inet_peer_base * peers;
    struct fqdir * fqdir;
    struct xt_table * ip6table_filter;
    struct xt_table * ip6table_mangle;
    struct xt_table * ip6table_raw;
    struct xt_table * ip6table_security;
    struct xt_table * ip6table_nat;
    struct fib6_info * fib6_null_entry;
    struct rt6_info * ip6_null_entry;
    struct rt6_statistics * rt6_stats;
    struct timer_list ip6_fib_timer;
    struct hlist_head * fib_table_hash;
    struct fib6_table * fib6_main_tbl;
    struct list_head fib6_walkers;
    struct dst_ops ip6_dst_ops;
    rwlock_t fib6_walker_lock;
    spinlock_t fib6_gc_lock;
    unsigned int ip6_rt_gc_expire;
    long unsigned int ip6_rt_last_gc;
    unsigned int fib6_rules_require_fldissect;
    bool fib6_has_custom_rules;
    struct rt6_info * ip6_prohibit_entry;
    struct rt6_info * ip6_blk_hole_entry;
    struct fib6_table * fib6_local_tbl;
    struct fib_rules_ops * fib6_rules_ops;
    struct sock * * icmp_sk;
    struct sock * ndisc_sk;
    struct sock * tcp_sk;
    struct sock * igmp_sk;
    struct sock * mc_autojoin_sk;
    struct list_head mr6_tables;
    struct fib_rules_ops * mr6_rules_ops;
    atomic_t dev_addr_genid;
    atomic_t fib6_sernum;
    struct seg6_pernet_data * seg6_data;
    struct fib_notifier_ops * notifier_ops;
    struct fib_notifier_ops * ip6mr_notifier_ops;
    unsigned int ipmr_seq;
    struct (anon) ip6addrlbl_table;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct netns_ipv6 {
    struct netns_sysctl_ipv6 sysctl;
    struct ipv6_devconf * devconf_all;
    struct ipv6_devconf * devconf_dflt;
    struct inet_peer_base * peers;
    struct fqdir * fqdir;
    struct xt_table * ip6table_filter;
    struct xt_table * ip6table_mangle;
    struct xt_table * ip6table_raw;
    struct xt_table * ip6table_security;
    struct xt_table * ip6table_nat;
    struct fib6_info * fib6_null_entry;
    struct rt6_info * ip6_null_entry;
    struct rt6_statistics * rt6_stats;
    struct timer_list ip6_fib_timer;
    struct hlist_head * fib_table_hash;
    struct fib6_table * fib6_main_tbl;
    struct list_head fib6_walkers;
    struct dst_ops ip6_dst_ops;
    rwlock_t fib6_walker_lock;
    spinlock_t fib6_gc_lock;
    unsigned int ip6_rt_gc_expire;
    long unsigned int ip6_rt_last_gc;
    unsigned int fib6_rules_require_fldissect;
    bool fib6_has_custom_rules;
    unsigned int fib6_routes_require_src;
    struct rt6_info * ip6_prohibit_entry;
    struct rt6_info * ip6_blk_hole_entry;
    struct fib6_table * fib6_local_tbl;
    struct fib_rules_ops * fib6_rules_ops;
    struct sock * * icmp_sk;
    struct sock * ndisc_sk;
    struct sock * tcp_sk;
    struct sock * igmp_sk;
    struct sock * mc_autojoin_sk;
    struct list_head mr6_tables;
    struct fib_rules_ops * mr6_rules_ops;
    atomic_t dev_addr_genid;
    atomic_t fib6_sernum;
    struct seg6_pernet_data * seg6_data;
    struct fib_notifier_ops * notifier_ops;
    struct fib_notifier_ops * ip6mr_notifier_ops;
    unsigned int ipmr_seq;
    struct (anon) ip6addrlbl_table;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct netns_ipv6 {
    struct netns_sysctl_ipv6 sysctl;
    struct ipv6_devconf * devconf_all;
    struct ipv6_devconf * devconf_dflt;
    struct inet_peer_base * peers;
    struct fqdir * fqdir;
    struct xt_table * ip6table_filter;
    struct xt_table * ip6table_mangle;
    struct xt_table * ip6table_raw;
    struct xt_table * ip6table_security;
    struct xt_table * ip6table_nat;
    struct fib6_info * fib6_null_entry;
    struct rt6_info * ip6_null_entry;
    struct rt6_statistics * rt6_stats;
    struct timer_list ip6_fib_timer;
    struct hlist_head * fib_table_hash;
    struct fib6_table * fib6_main_tbl;
    struct list_head fib6_walkers;
    struct dst_ops ip6_dst_ops;
    rwlock_t fib6_walker_lock;
    spinlock_t fib6_gc_lock;
    unsigned int ip6_rt_gc_expire;
    long unsigned int ip6_rt_last_gc;
    unsigned int fib6_rules_require_fldissect;
    bool fib6_has_custom_rules;
    unsigned int fib6_routes_require_src;
    struct rt6_info * ip6_prohibit_entry;
    struct rt6_info * ip6_blk_hole_entry;
    struct fib6_table * fib6_local_tbl;
    struct fib_rules_ops * fib6_rules_ops;
    struct sock * * icmp_sk;
    struct sock * ndisc_sk;
    struct sock * tcp_sk;
    struct sock * igmp_sk;
    struct sock * mc_autojoin_sk;
    struct list_head mr6_tables;
    struct fib_rules_ops * mr6_rules_ops;
    atomic_t dev_addr_genid;
    atomic_t fib6_sernum;
    struct seg6_pernet_data * seg6_data;
    struct fib_notifier_ops * notifier_ops;
    struct fib_notifier_ops * ip6mr_notifier_ops;
    unsigned int ipmr_seq;
    struct (anon) ip6addrlbl_table;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct netns_ipv6 {
    struct dst_ops ip6_dst_ops;
    struct netns_sysctl_ipv6 sysctl;
    struct ipv6_devconf * devconf_all;
    struct ipv6_devconf * devconf_dflt;
    struct inet_peer_base * peers;
    struct fqdir * fqdir;
    struct fib6_info * fib6_null_entry;
    struct rt6_info * ip6_null_entry;
    struct rt6_statistics * rt6_stats;
    struct timer_list ip6_fib_timer;
    struct hlist_head * fib_table_hash;
    struct fib6_table * fib6_main_tbl;
    struct list_head fib6_walkers;
    rwlock_t fib6_walker_lock;
    spinlock_t fib6_gc_lock;
    unsigned int ip6_rt_gc_expire;
    long unsigned int ip6_rt_last_gc;
    unsigned int fib6_rules_require_fldissect;
    bool fib6_has_custom_rules;
    unsigned int fib6_routes_require_src;
    struct rt6_info * ip6_prohibit_entry;
    struct rt6_info * ip6_blk_hole_entry;
    struct fib6_table * fib6_local_tbl;
    struct fib_rules_ops * fib6_rules_ops;
    struct sock * * icmp_sk;
    struct sock * ndisc_sk;
    struct sock * tcp_sk;
    struct sock * igmp_sk;
    struct sock * mc_autojoin_sk;
    struct list_head mr6_tables;
    struct fib_rules_ops * mr6_rules_ops;
    atomic_t dev_addr_genid;
    atomic_t fib6_sernum;
    struct seg6_pernet_data * seg6_data;
    struct fib_notifier_ops * notifier_ops;
    struct fib_notifier_ops * ip6mr_notifier_ops;
    unsigned int ipmr_seq;
    struct (anon) ip6addrlbl_table;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct netns_ipv6 {
    struct dst_ops ip6_dst_ops;
    struct netns_sysctl_ipv6 sysctl;
    struct ipv6_devconf * devconf_all;
    struct ipv6_devconf * devconf_dflt;
    struct inet_peer_base * peers;
    struct fqdir * fqdir;
    struct fib6_info * fib6_null_entry;
    struct rt6_info * ip6_null_entry;
    struct rt6_statistics * rt6_stats;
    struct timer_list ip6_fib_timer;
    struct hlist_head * fib_table_hash;
    struct fib6_table * fib6_main_tbl;
    struct list_head fib6_walkers;
    rwlock_t fib6_walker_lock;
    spinlock_t fib6_gc_lock;
    unsigned int ip6_rt_gc_expire;
    long unsigned int ip6_rt_last_gc;
    unsigned char flowlabel_has_excl;
    bool fib6_has_custom_rules;
    unsigned int fib6_rules_require_fldissect;
    unsigned int fib6_routes_require_src;
    struct rt6_info * ip6_prohibit_entry;
    struct rt6_info * ip6_blk_hole_entry;
    struct fib6_table * fib6_local_tbl;
    struct fib_rules_ops * fib6_rules_ops;
    struct sock * * icmp_sk;
    struct sock * ndisc_sk;
    struct sock * tcp_sk;
    struct sock * igmp_sk;
    struct sock * mc_autojoin_sk;
    struct list_head mr6_tables;
    struct fib_rules_ops * mr6_rules_ops;
    atomic_t dev_addr_genid;
    atomic_t fib6_sernum;
    struct seg6_pernet_data * seg6_data;
    struct fib_notifier_ops * notifier_ops;
    struct fib_notifier_ops * ip6mr_notifier_ops;
    unsigned int ipmr_seq;
    struct (anon) ip6addrlbl_table;
    struct ioam6_pernet_data * ioam6_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct netns_ipv6 {
    struct dst_ops ip6_dst_ops;
    struct netns_sysctl_ipv6 sysctl;
    struct ipv6_devconf * devconf_all;
    struct ipv6_devconf * devconf_dflt;
    struct inet_peer_base * peers;
    struct fqdir * fqdir;
    struct fib6_info * fib6_null_entry;
    struct rt6_info * ip6_null_entry;
    struct rt6_statistics * rt6_stats;
    struct timer_list ip6_fib_timer;
    struct hlist_head * fib_table_hash;
    struct fib6_table * fib6_main_tbl;
    struct list_head fib6_walkers;
    rwlock_t fib6_walker_lock;
    spinlock_t fib6_gc_lock;
    atomic_t ip6_rt_gc_expire;
    long unsigned int ip6_rt_last_gc;
    unsigned char flowlabel_has_excl;
    bool fib6_has_custom_rules;
    unsigned int fib6_rules_require_fldissect;
    unsigned int fib6_routes_require_src;
    struct rt6_info * ip6_prohibit_entry;
    struct rt6_info * ip6_blk_hole_entry;
    struct fib6_table * fib6_local_tbl;
    struct fib_rules_ops * fib6_rules_ops;
    struct sock * ndisc_sk;
    struct sock * tcp_sk;
    struct sock * igmp_sk;
    struct sock * mc_autojoin_sk;
    struct hlist_head * inet6_addr_lst;
    spinlock_t addrconf_hash_lock;
    struct delayed_work addr_chk_work;
    struct list_head mr6_tables;
    struct fib_rules_ops * mr6_rules_ops;
    atomic_t dev_addr_genid;
    atomic_t fib6_sernum;
    struct seg6_pernet_data * seg6_data;
    struct fib_notifier_ops * notifier_ops;
    struct fib_notifier_ops * ip6mr_notifier_ops;
    unsigned int ipmr_seq;
    struct (anon) ip6addrlbl_table;
    struct ioam6_pernet_data * ioam6_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct netns_ipv6 {
    struct dst_ops ip6_dst_ops;
    struct netns_sysctl_ipv6 sysctl;
    struct ipv6_devconf * devconf_all;
    struct ipv6_devconf * devconf_dflt;
    struct inet_peer_base * peers;
    struct fqdir * fqdir;
    struct fib6_info * fib6_null_entry;
    struct rt6_info * ip6_null_entry;
    struct rt6_statistics * rt6_stats;
    struct timer_list ip6_fib_timer;
    struct hlist_head * fib_table_hash;
    struct fib6_table * fib6_main_tbl;
    struct list_head fib6_walkers;
    rwlock_t fib6_walker_lock;
    spinlock_t fib6_gc_lock;
    atomic_t ip6_rt_gc_expire;
    long unsigned int ip6_rt_last_gc;
    unsigned char flowlabel_has_excl;
    bool fib6_has_custom_rules;
    unsigned int fib6_rules_require_fldissect;
    unsigned int fib6_routes_require_src;
    struct rt6_info * ip6_prohibit_entry;
    struct rt6_info * ip6_blk_hole_entry;
    struct fib6_table * fib6_local_tbl;
    struct fib_rules_ops * fib6_rules_ops;
    struct sock * ndisc_sk;
    struct sock * tcp_sk;
    struct sock * igmp_sk;
    struct sock * mc_autojoin_sk;
    struct hlist_head * inet6_addr_lst;
    spinlock_t addrconf_hash_lock;
    struct delayed_work addr_chk_work;
    struct list_head mr6_tables;
    struct fib_rules_ops * mr6_rules_ops;
    atomic_t dev_addr_genid;
    atomic_t fib6_sernum;
    struct seg6_pernet_data * seg6_data;
    struct fib_notifier_ops * notifier_ops;
    struct fib_notifier_ops * ip6mr_notifier_ops;
    unsigned int ipmr_seq;
    struct (anon) ip6addrlbl_table;
    struct ioam6_pernet_data * ioam6_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct netns_ipv6 {
    struct dst_ops ip6_dst_ops;
    struct netns_sysctl_ipv6 sysctl;
    struct ipv6_devconf * devconf_all;
    struct ipv6_devconf * devconf_dflt;
    struct inet_peer_base * peers;
    struct fqdir * fqdir;
    struct fib6_info * fib6_null_entry;
    struct rt6_info * ip6_null_entry;
    struct rt6_statistics * rt6_stats;
    struct timer_list ip6_fib_timer;
    struct hlist_head * fib_table_hash;
    struct fib6_table * fib6_main_tbl;
    struct list_head fib6_walkers;
    rwlock_t fib6_walker_lock;
    spinlock_t fib6_gc_lock;
    atomic_t ip6_rt_gc_expire;
    long unsigned int ip6_rt_last_gc;
    unsigned char flowlabel_has_excl;
    bool fib6_has_custom_rules;
    unsigned int fib6_rules_require_fldissect;
    unsigned int fib6_routes_require_src;
    struct rt6_info * ip6_prohibit_entry;
    struct rt6_info * ip6_blk_hole_entry;
    struct fib6_table * fib6_local_tbl;
    struct fib_rules_ops * fib6_rules_ops;
    struct sock * ndisc_sk;
    struct sock * tcp_sk;
    struct sock * igmp_sk;
    struct sock * mc_autojoin_sk;
    struct hlist_head * inet6_addr_lst;
    spinlock_t addrconf_hash_lock;
    struct delayed_work addr_chk_work;
    struct list_head mr6_tables;
    struct fib_rules_ops * mr6_rules_ops;
    atomic_t dev_addr_genid;
    atomic_t fib6_sernum;
    struct seg6_pernet_data * seg6_data;
    struct fib_notifier_ops * notifier_ops;
    struct fib_notifier_ops * ip6mr_notifier_ops;
    unsigned int ipmr_seq;
    struct (anon) ip6addrlbl_table;
    struct ioam6_pernet_data * ioam6_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct netns_ipv6 {
    struct dst_ops ip6_dst_ops;
    struct netns_sysctl_ipv6 sysctl;
    struct ipv6_devconf * devconf_all;
    struct ipv6_devconf * devconf_dflt;
    struct inet_peer_base * peers;
    struct fqdir * fqdir;
    struct fib6_info * fib6_null_entry;
    struct rt6_info * ip6_null_entry;
    struct rt6_statistics * rt6_stats;
    struct timer_list ip6_fib_timer;
    struct hlist_head * fib_table_hash;
    struct fib6_table * fib6_main_tbl;
    struct list_head fib6_walkers;
    rwlock_t fib6_walker_lock;
    spinlock_t fib6_gc_lock;
    atomic_t ip6_rt_gc_expire;
    long unsigned int ip6_rt_last_gc;
    unsigned char flowlabel_has_excl;
    bool fib6_has_custom_rules;
    unsigned int fib6_rules_require_fldissect;
    unsigned int fib6_routes_require_src;
    struct rt6_info * ip6_prohibit_entry;
    struct rt6_info * ip6_blk_hole_entry;
    struct fib6_table * fib6_local_tbl;
    struct fib_rules_ops * fib6_rules_ops;
    struct sock * ndisc_sk;
    struct sock * tcp_sk;
    struct sock * igmp_sk;
    struct sock * mc_autojoin_sk;
    struct hlist_head * inet6_addr_lst;
    spinlock_t addrconf_hash_lock;
    struct delayed_work addr_chk_work;
    struct list_head mr6_tables;
    struct fib_rules_ops * mr6_rules_ops;
    atomic_t dev_addr_genid;
    atomic_t fib6_sernum;
    struct seg6_pernet_data * seg6_data;
    struct fib_notifier_ops * notifier_ops;
    struct fib_notifier_ops * ip6mr_notifier_ops;
    unsigned int ipmr_seq;
    struct (anon) ip6addrlbl_table;
    struct ioam6_pernet_data * ioam6_data;
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
struct netns_ipv6 {
    struct netns_sysctl_ipv6 sysctl;
    struct ipv6_devconf * devconf_all;
    struct ipv6_devconf * devconf_dflt;
    struct inet_peer_base * peers;
    struct fqdir * fqdir;
    struct xt_table * ip6table_filter;
    struct xt_table * ip6table_mangle;
    struct xt_table * ip6table_raw;
    struct xt_table * ip6table_security;
    struct xt_table * ip6table_nat;
    struct fib6_info * fib6_null_entry;
    struct rt6_info * ip6_null_entry;
    struct rt6_statistics * rt6_stats;
    struct timer_list ip6_fib_timer;
    struct hlist_head * fib_table_hash;
    struct fib6_table * fib6_main_tbl;
    struct list_head fib6_walkers;
    struct dst_ops ip6_dst_ops;
    rwlock_t fib6_walker_lock;
    spinlock_t fib6_gc_lock;
    unsigned int ip6_rt_gc_expire;
    long unsigned int ip6_rt_last_gc;
    unsigned int fib6_rules_require_fldissect;
    bool fib6_has_custom_rules;
    struct rt6_info * ip6_prohibit_entry;
    struct rt6_info * ip6_blk_hole_entry;
    struct fib6_table * fib6_local_tbl;
    struct fib_rules_ops * fib6_rules_ops;
    struct sock * * icmp_sk;
    struct sock * ndisc_sk;
    struct sock * tcp_sk;
    struct sock * igmp_sk;
    struct sock * mc_autojoin_sk;
    struct list_head mr6_tables;
    struct fib_rules_ops * mr6_rules_ops;
    atomic_t dev_addr_genid;
    atomic_t fib6_sernum;
    struct seg6_pernet_data * seg6_data;
    struct fib_notifier_ops * notifier_ops;
    struct fib_notifier_ops * ip6mr_notifier_ops;
    unsigned int ipmr_seq;
    struct (anon) ip6addrlbl_table;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct netns_ipv6 {
    struct netns_sysctl_ipv6 sysctl;
    struct ipv6_devconf * devconf_all;
    struct ipv6_devconf * devconf_dflt;
    struct inet_peer_base * peers;
    struct fqdir * fqdir;
    struct xt_table * ip6table_filter;
    struct xt_table * ip6table_mangle;
    struct xt_table * ip6table_raw;
    struct xt_table * ip6table_security;
    struct xt_table * ip6table_nat;
    struct fib6_info * fib6_null_entry;
    struct rt6_info * ip6_null_entry;
    struct rt6_statistics * rt6_stats;
    struct timer_list ip6_fib_timer;
    struct hlist_head * fib_table_hash;
    struct fib6_table * fib6_main_tbl;
    struct list_head fib6_walkers;
    struct dst_ops ip6_dst_ops;
    rwlock_t fib6_walker_lock;
    spinlock_t fib6_gc_lock;
    unsigned int ip6_rt_gc_expire;
    long unsigned int ip6_rt_last_gc;
    unsigned int fib6_rules_require_fldissect;
    bool fib6_has_custom_rules;
    struct rt6_info * ip6_prohibit_entry;
    struct rt6_info * ip6_blk_hole_entry;
    struct fib6_table * fib6_local_tbl;
    struct fib_rules_ops * fib6_rules_ops;
    struct sock * * icmp_sk;
    struct sock * ndisc_sk;
    struct sock * tcp_sk;
    struct sock * igmp_sk;
    struct sock * mc_autojoin_sk;
    struct list_head mr6_tables;
    struct fib_rules_ops * mr6_rules_ops;
    atomic_t dev_addr_genid;
    atomic_t fib6_sernum;
    struct seg6_pernet_data * seg6_data;
    struct fib_notifier_ops * notifier_ops;
    struct fib_notifier_ops * ip6mr_notifier_ops;
    unsigned int ipmr_seq;
    struct (anon) ip6addrlbl_table;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct netns_ipv6 {
    struct netns_sysctl_ipv6 sysctl;
    struct ipv6_devconf * devconf_all;
    struct ipv6_devconf * devconf_dflt;
    struct inet_peer_base * peers;
    struct fqdir * fqdir;
    struct xt_table * ip6table_filter;
    struct xt_table * ip6table_mangle;
    struct xt_table * ip6table_raw;
    struct xt_table * ip6table_security;
    struct xt_table * ip6table_nat;
    struct fib6_info * fib6_null_entry;
    struct rt6_info * ip6_null_entry;
    struct rt6_statistics * rt6_stats;
    struct timer_list ip6_fib_timer;
    struct hlist_head * fib_table_hash;
    struct fib6_table * fib6_main_tbl;
    struct list_head fib6_walkers;
    struct dst_ops ip6_dst_ops;
    rwlock_t fib6_walker_lock;
    spinlock_t fib6_gc_lock;
    unsigned int ip6_rt_gc_expire;
    long unsigned int ip6_rt_last_gc;
    unsigned int fib6_rules_require_fldissect;
    bool fib6_has_custom_rules;
    struct rt6_info * ip6_prohibit_entry;
    struct rt6_info * ip6_blk_hole_entry;
    struct fib6_table * fib6_local_tbl;
    struct fib_rules_ops * fib6_rules_ops;
    struct sock * * icmp_sk;
    struct sock * ndisc_sk;
    struct sock * tcp_sk;
    struct sock * igmp_sk;
    struct sock * mc_autojoin_sk;
    struct list_head mr6_tables;
    struct fib_rules_ops * mr6_rules_ops;
    atomic_t dev_addr_genid;
    atomic_t fib6_sernum;
    struct seg6_pernet_data * seg6_data;
    struct fib_notifier_ops * notifier_ops;
    struct fib_notifier_ops * ip6mr_notifier_ops;
    unsigned int ipmr_seq;
    struct (anon) ip6addrlbl_table;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct netns_ipv6 {
    struct netns_sysctl_ipv6 sysctl;
    struct ipv6_devconf * devconf_all;
    struct ipv6_devconf * devconf_dflt;
    struct inet_peer_base * peers;
    struct fqdir * fqdir;
    struct xt_table * ip6table_filter;
    struct xt_table * ip6table_mangle;
    struct xt_table * ip6table_raw;
    struct xt_table * ip6table_security;
    struct xt_table * ip6table_nat;
    struct fib6_info * fib6_null_entry;
    struct rt6_info * ip6_null_entry;
    struct rt6_statistics * rt6_stats;
    struct timer_list ip6_fib_timer;
    struct hlist_head * fib_table_hash;
    struct fib6_table * fib6_main_tbl;
    struct list_head fib6_walkers;
    struct dst_ops ip6_dst_ops;
    rwlock_t fib6_walker_lock;
    spinlock_t fib6_gc_lock;
    unsigned int ip6_rt_gc_expire;
    long unsigned int ip6_rt_last_gc;
    unsigned int fib6_rules_require_fldissect;
    bool fib6_has_custom_rules;
    struct rt6_info * ip6_prohibit_entry;
    struct rt6_info * ip6_blk_hole_entry;
    struct fib6_table * fib6_local_tbl;
    struct fib_rules_ops * fib6_rules_ops;
    struct sock * * icmp_sk;
    struct sock * ndisc_sk;
    struct sock * tcp_sk;
    struct sock * igmp_sk;
    struct sock * mc_autojoin_sk;
    struct list_head mr6_tables;
    struct fib_rules_ops * mr6_rules_ops;
    atomic_t dev_addr_genid;
    atomic_t fib6_sernum;
    struct seg6_pernet_data * seg6_data;
    struct fib_notifier_ops * notifier_ops;
    struct fib_notifier_ops * ip6mr_notifier_ops;
    unsigned int ipmr_seq;
    struct (anon) ip6addrlbl_table;
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
struct netns_ipv6 {
    struct netns_sysctl_ipv6 sysctl;
    struct ipv6_devconf * devconf_all;
    struct ipv6_devconf * devconf_dflt;
    struct inet_peer_base * peers;
    struct fqdir * fqdir;
    struct xt_table * ip6table_filter;
    struct xt_table * ip6table_mangle;
    struct xt_table * ip6table_raw;
    struct xt_table * ip6table_security;
    struct xt_table * ip6table_nat;
    struct fib6_info * fib6_null_entry;
    struct rt6_info * ip6_null_entry;
    struct rt6_statistics * rt6_stats;
    struct timer_list ip6_fib_timer;
    struct hlist_head * fib_table_hash;
    struct fib6_table * fib6_main_tbl;
    struct list_head fib6_walkers;
    struct dst_ops ip6_dst_ops;
    rwlock_t fib6_walker_lock;
    spinlock_t fib6_gc_lock;
    unsigned int ip6_rt_gc_expire;
    long unsigned int ip6_rt_last_gc;
    unsigned int fib6_rules_require_fldissect;
    bool fib6_has_custom_rules;
    struct rt6_info * ip6_prohibit_entry;
    struct rt6_info * ip6_blk_hole_entry;
    struct fib6_table * fib6_local_tbl;
    struct fib_rules_ops * fib6_rules_ops;
    struct sock * * icmp_sk;
    struct sock * ndisc_sk;
    struct sock * tcp_sk;
    struct sock * igmp_sk;
    struct sock * mc_autojoin_sk;
    struct list_head mr6_tables;
    struct fib_rules_ops * mr6_rules_ops;
    atomic_t dev_addr_genid;
    atomic_t fib6_sernum;
    struct seg6_pernet_data * seg6_data;
    struct fib_notifier_ops * notifier_ops;
    struct fib_notifier_ops * ip6mr_notifier_ops;
    unsigned int ipmr_seq;
    struct (anon) ip6addrlbl_table;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct netns_ipv6 {
    struct netns_sysctl_ipv6 sysctl;
    struct ipv6_devconf * devconf_all;
    struct ipv6_devconf * devconf_dflt;
    struct inet_peer_base * peers;
    struct fqdir * fqdir;
    struct xt_table * ip6table_filter;
    struct xt_table * ip6table_mangle;
    struct xt_table * ip6table_raw;
    struct xt_table * ip6table_security;
    struct xt_table * ip6table_nat;
    struct fib6_info * fib6_null_entry;
    struct rt6_info * ip6_null_entry;
    struct rt6_statistics * rt6_stats;
    struct timer_list ip6_fib_timer;
    struct hlist_head * fib_table_hash;
    struct fib6_table * fib6_main_tbl;
    struct list_head fib6_walkers;
    struct dst_ops ip6_dst_ops;
    rwlock_t fib6_walker_lock;
    spinlock_t fib6_gc_lock;
    unsigned int ip6_rt_gc_expire;
    long unsigned int ip6_rt_last_gc;
    unsigned int fib6_rules_require_fldissect;
    bool fib6_has_custom_rules;
    struct rt6_info * ip6_prohibit_entry;
    struct rt6_info * ip6_blk_hole_entry;
    struct fib6_table * fib6_local_tbl;
    struct fib_rules_ops * fib6_rules_ops;
    struct sock * * icmp_sk;
    struct sock * ndisc_sk;
    struct sock * tcp_sk;
    struct sock * igmp_sk;
    struct sock * mc_autojoin_sk;
    struct list_head mr6_tables;
    struct fib_rules_ops * mr6_rules_ops;
    atomic_t dev_addr_genid;
    atomic_t fib6_sernum;
    struct seg6_pernet_data * seg6_data;
    struct fib_notifier_ops * notifier_ops;
    struct fib_notifier_ops * ip6mr_notifier_ops;
    unsigned int ipmr_seq;
    struct (anon) ip6addrlbl_table;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct netns_ipv6 {
    struct netns_sysctl_ipv6 sysctl;
    struct ipv6_devconf * devconf_all;
    struct ipv6_devconf * devconf_dflt;
    struct inet_peer_base * peers;
    struct fqdir * fqdir;
    struct xt_table * ip6table_filter;
    struct xt_table * ip6table_mangle;
    struct xt_table * ip6table_raw;
    struct xt_table * ip6table_security;
    struct xt_table * ip6table_nat;
    struct fib6_info * fib6_null_entry;
    struct rt6_info * ip6_null_entry;
    struct rt6_statistics * rt6_stats;
    struct timer_list ip6_fib_timer;
    struct hlist_head * fib_table_hash;
    struct fib6_table * fib6_main_tbl;
    struct list_head fib6_walkers;
    struct dst_ops ip6_dst_ops;
    rwlock_t fib6_walker_lock;
    spinlock_t fib6_gc_lock;
    unsigned int ip6_rt_gc_expire;
    long unsigned int ip6_rt_last_gc;
    unsigned int fib6_rules_require_fldissect;
    bool fib6_has_custom_rules;
    struct rt6_info * ip6_prohibit_entry;
    struct rt6_info * ip6_blk_hole_entry;
    struct fib6_table * fib6_local_tbl;
    struct fib_rules_ops * fib6_rules_ops;
    struct sock * * icmp_sk;
    struct sock * ndisc_sk;
    struct sock * tcp_sk;
    struct sock * igmp_sk;
    struct sock * mc_autojoin_sk;
    struct list_head mr6_tables;
    struct fib_rules_ops * mr6_rules_ops;
    atomic_t dev_addr_genid;
    atomic_t fib6_sernum;
    struct seg6_pernet_data * seg6_data;
    struct fib_notifier_ops * notifier_ops;
    struct fib_notifier_ops * ip6mr_notifier_ops;
    unsigned int ipmr_seq;
    struct (anon) ip6addrlbl_table;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct netns_ipv6 {
    struct netns_sysctl_ipv6 sysctl;
    struct ipv6_devconf * devconf_all;
    struct ipv6_devconf * devconf_dflt;
    struct inet_peer_base * peers;
    struct fqdir * fqdir;
    struct xt_table * ip6table_filter;
    struct xt_table * ip6table_mangle;
    struct xt_table * ip6table_raw;
    struct xt_table * ip6table_security;
    struct xt_table * ip6table_nat;
    struct fib6_info * fib6_null_entry;
    struct rt6_info * ip6_null_entry;
    struct rt6_statistics * rt6_stats;
    struct timer_list ip6_fib_timer;
    struct hlist_head * fib_table_hash;
    struct fib6_table * fib6_main_tbl;
    struct list_head fib6_walkers;
    struct dst_ops ip6_dst_ops;
    rwlock_t fib6_walker_lock;
    spinlock_t fib6_gc_lock;
    unsigned int ip6_rt_gc_expire;
    long unsigned int ip6_rt_last_gc;
    unsigned int fib6_rules_require_fldissect;
    bool fib6_has_custom_rules;
    struct rt6_info * ip6_prohibit_entry;
    struct rt6_info * ip6_blk_hole_entry;
    struct fib6_table * fib6_local_tbl;
    struct fib_rules_ops * fib6_rules_ops;
    struct sock * * icmp_sk;
    struct sock * ndisc_sk;
    struct sock * tcp_sk;
    struct sock * igmp_sk;
    struct sock * mc_autojoin_sk;
    struct list_head mr6_tables;
    struct fib_rules_ops * mr6_rules_ops;
    atomic_t dev_addr_genid;
    atomic_t fib6_sernum;
    struct seg6_pernet_data * seg6_data;
    struct fib_notifier_ops * notifier_ops;
    struct fib_notifier_ops * ip6mr_notifier_ops;
    unsigned int ipmr_seq;
    struct (anon) ip6addrlbl_table;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct list_head fib6_walkers</code>
</li>
<li>
<b>Field added. </b>
<code>rwlock_t fib6_walker_lock</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t fib6_gc_lock</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct seg6_pernet_data * seg6_data</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool fib6_has_custom_rules</code>
</li>
<li>
<b>Field added. </b>
<code>struct fib_notifier_ops * notifier_ops</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) ip6addrlbl_table</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct fib6_info * fib6_null_entry</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int fib6_rules_require_fldissect</code>
</li>
<li>
<b>Field added. </b>
<code>struct fib_notifier_ops * ip6mr_notifier_ops</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int ipmr_seq</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct fqdir * fqdir</code>
</li>
<li>
<b>Field removed. </b>
<code>struct netns_frags frags</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct xt_table * ip6table_filter</code> ➡️ <code>struct xt_table * ip6table_filter</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct xt_table * ip6table_mangle</code> ➡️ <code>struct xt_table * ip6table_mangle</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct xt_table * ip6table_raw</code> ➡️ <code>struct xt_table * ip6table_raw</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct xt_table * ip6table_security</code> ➡️ <code>struct xt_table * ip6table_security</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct xt_table * ip6table_nat</code> ➡️ <code>struct xt_table * ip6table_nat</code>
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
<code>unsigned int fib6_routes_require_src</code>
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
<b>Field removed. </b>
<code>struct xt_table * ip6table_filter</code>
</li>
<li>
<b>Field removed. </b>
<code>struct xt_table * ip6table_mangle</code>
</li>
<li>
<b>Field removed. </b>
<code>struct xt_table * ip6table_raw</code>
</li>
<li>
<b>Field removed. </b>
<code>struct xt_table * ip6table_security</code>
</li>
<li>
<b>Field removed. </b>
<code>struct xt_table * ip6table_nat</code>
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
<code>unsigned char flowlabel_has_excl</code>
</li>
<li>
<b>Field added. </b>
<code>struct ioam6_pernet_data * ioam6_data</code>
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
<code>struct hlist_head * inet6_addr_lst</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t addrconf_hash_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct delayed_work addr_chk_work</code>
</li>
<li>
<b>Field removed. </b>
<code>struct sock * * icmp_sk</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int ip6_rt_gc_expire</code> ➡️ <code>atomic_t ip6_rt_gc_expire</code>
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
