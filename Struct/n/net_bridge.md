# Struct: <code>net_bridge</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct net_bridge {
    spinlock_t lock;
    spinlock_t hash_lock;
    struct list_head port_list;
    struct net_device * dev;
    struct pcpu_sw_netstats * stats;
    u8 vlan_enabled;
    u8 vlan_stats_enabled;
    __be16 vlan_proto;
    u16 default_pvid;
    struct net_bridge_vlan_group * vlgrp;
    struct hlist_head[256] hash;
    struct rtable fake_rtable;
    struct rt6_info fake_rt6_info;
    bool nf_call_iptables;
    bool nf_call_ip6tables;
    bool nf_call_arptables;
    u16 group_fwd_mask;
    u16 group_fwd_mask_required;
    bridge_id designated_root;
    bridge_id bridge_id;
    u32 root_path_cost;
    unsigned char topology_change;
    unsigned char topology_change_detected;
    u16 root_port;
    long unsigned int max_age;
    long unsigned int hello_time;
    long unsigned int forward_delay;
    long unsigned int ageing_time;
    long unsigned int bridge_max_age;
    long unsigned int bridge_hello_time;
    long unsigned int bridge_forward_delay;
    long unsigned int bridge_ageing_time;
    u8[6] group_addr;
    bool group_addr_set;
    enum (anon) stp_enabled;
    unsigned char multicast_router;
    u8 multicast_disabled;
    u8 multicast_querier;
    u8 multicast_query_use_ifaddr;
    u8 has_ipv6_addr;
    u8 multicast_stats_enabled;
    u32 hash_elasticity;
    u32 hash_max;
    u32 multicast_last_member_count;
    u32 multicast_startup_query_count;
    u8 multicast_igmp_version;
    long unsigned int multicast_last_member_interval;
    long unsigned int multicast_membership_interval;
    long unsigned int multicast_querier_interval;
    long unsigned int multicast_query_interval;
    long unsigned int multicast_query_response_interval;
    long unsigned int multicast_startup_query_interval;
    spinlock_t multicast_lock;
    struct net_bridge_mdb_htable * mdb;
    struct hlist_head router_list;
    struct timer_list multicast_router_timer;
    struct bridge_mcast_other_query ip4_other_query;
    struct bridge_mcast_own_query ip4_own_query;
    struct bridge_mcast_querier ip4_querier;
    struct bridge_mcast_stats * mcast_stats;
    struct bridge_mcast_other_query ip6_other_query;
    struct bridge_mcast_own_query ip6_own_query;
    struct bridge_mcast_querier ip6_querier;
    u8 multicast_mld_version;
    struct timer_list hello_timer;
    struct timer_list tcn_timer;
    struct timer_list topology_change_timer;
    struct delayed_work gc_work;
    struct kobject * ifobj;
    u32 auto_cnt;
    int offload_fwd_mark;
    bool neigh_suppress_enabled;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct net_bridge {
    spinlock_t lock;
    spinlock_t hash_lock;
    struct list_head port_list;
    struct net_device * dev;
    struct pcpu_sw_netstats * stats;
    u8 vlan_enabled;
    u8 vlan_stats_enabled;
    __be16 vlan_proto;
    u16 default_pvid;
    struct net_bridge_vlan_group * vlgrp;
    struct rhashtable fdb_hash_tbl;
    struct rtable fake_rtable;
    struct rt6_info fake_rt6_info;
    bool nf_call_iptables;
    bool nf_call_ip6tables;
    bool nf_call_arptables;
    u16 group_fwd_mask;
    u16 group_fwd_mask_required;
    bridge_id designated_root;
    bridge_id bridge_id;
    u32 root_path_cost;
    unsigned char topology_change;
    unsigned char topology_change_detected;
    u16 root_port;
    long unsigned int max_age;
    long unsigned int hello_time;
    long unsigned int forward_delay;
    long unsigned int ageing_time;
    long unsigned int bridge_max_age;
    long unsigned int bridge_hello_time;
    long unsigned int bridge_forward_delay;
    long unsigned int bridge_ageing_time;
    u8[6] group_addr;
    bool group_addr_set;
    enum (anon) stp_enabled;
    unsigned char multicast_router;
    u8 multicast_disabled;
    u8 multicast_querier;
    u8 multicast_query_use_ifaddr;
    u8 has_ipv6_addr;
    u8 multicast_stats_enabled;
    u32 hash_elasticity;
    u32 hash_max;
    u32 multicast_last_member_count;
    u32 multicast_startup_query_count;
    u8 multicast_igmp_version;
    long unsigned int multicast_last_member_interval;
    long unsigned int multicast_membership_interval;
    long unsigned int multicast_querier_interval;
    long unsigned int multicast_query_interval;
    long unsigned int multicast_query_response_interval;
    long unsigned int multicast_startup_query_interval;
    spinlock_t multicast_lock;
    struct net_bridge_mdb_htable * mdb;
    struct hlist_head router_list;
    struct timer_list multicast_router_timer;
    struct bridge_mcast_other_query ip4_other_query;
    struct bridge_mcast_own_query ip4_own_query;
    struct bridge_mcast_querier ip4_querier;
    struct bridge_mcast_stats * mcast_stats;
    struct bridge_mcast_other_query ip6_other_query;
    struct bridge_mcast_own_query ip6_own_query;
    struct bridge_mcast_querier ip6_querier;
    u8 multicast_mld_version;
    struct timer_list hello_timer;
    struct timer_list tcn_timer;
    struct timer_list topology_change_timer;
    struct delayed_work gc_work;
    struct kobject * ifobj;
    u32 auto_cnt;
    int offload_fwd_mark;
    bool neigh_suppress_enabled;
    bool mtu_set_by_user;
    struct hlist_head fdb_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct net_bridge {
    spinlock_t lock;
    spinlock_t hash_lock;
    struct list_head port_list;
    struct net_device * dev;
    struct pcpu_sw_netstats * stats;
    long unsigned int options;
    __be16 vlan_proto;
    u16 default_pvid;
    struct net_bridge_vlan_group * vlgrp;
    struct rhashtable fdb_hash_tbl;
    struct rtable fake_rtable;
    struct rt6_info fake_rt6_info;
    u16 group_fwd_mask;
    u16 group_fwd_mask_required;
    bridge_id designated_root;
    bridge_id bridge_id;
    unsigned char topology_change;
    unsigned char topology_change_detected;
    u16 root_port;
    long unsigned int max_age;
    long unsigned int hello_time;
    long unsigned int forward_delay;
    long unsigned int ageing_time;
    long unsigned int bridge_max_age;
    long unsigned int bridge_hello_time;
    long unsigned int bridge_forward_delay;
    long unsigned int bridge_ageing_time;
    u32 root_path_cost;
    u8[6] group_addr;
    enum (anon) stp_enabled;
    u32 hash_max;
    u32 multicast_last_member_count;
    u32 multicast_startup_query_count;
    u8 multicast_igmp_version;
    u8 multicast_router;
    u8 multicast_mld_version;
    spinlock_t multicast_lock;
    long unsigned int multicast_last_member_interval;
    long unsigned int multicast_membership_interval;
    long unsigned int multicast_querier_interval;
    long unsigned int multicast_query_interval;
    long unsigned int multicast_query_response_interval;
    long unsigned int multicast_startup_query_interval;
    struct rhashtable mdb_hash_tbl;
    struct hlist_head mdb_list;
    struct hlist_head router_list;
    struct timer_list multicast_router_timer;
    struct bridge_mcast_other_query ip4_other_query;
    struct bridge_mcast_own_query ip4_own_query;
    struct bridge_mcast_querier ip4_querier;
    struct bridge_mcast_stats * mcast_stats;
    struct bridge_mcast_other_query ip6_other_query;
    struct bridge_mcast_own_query ip6_own_query;
    struct bridge_mcast_querier ip6_querier;
    struct timer_list hello_timer;
    struct timer_list tcn_timer;
    struct timer_list topology_change_timer;
    struct delayed_work gc_work;
    struct kobject * ifobj;
    u32 auto_cnt;
    int offload_fwd_mark;
    struct hlist_head fdb_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct net_bridge {
    spinlock_t lock;
    spinlock_t hash_lock;
    struct list_head port_list;
    struct net_device * dev;
    struct pcpu_sw_netstats * stats;
    long unsigned int options;
    __be16 vlan_proto;
    u16 default_pvid;
    struct net_bridge_vlan_group * vlgrp;
    struct rhashtable fdb_hash_tbl;
    struct rtable fake_rtable;
    struct rt6_info fake_rt6_info;
    u16 group_fwd_mask;
    u16 group_fwd_mask_required;
    bridge_id designated_root;
    bridge_id bridge_id;
    unsigned char topology_change;
    unsigned char topology_change_detected;
    u16 root_port;
    long unsigned int max_age;
    long unsigned int hello_time;
    long unsigned int forward_delay;
    long unsigned int ageing_time;
    long unsigned int bridge_max_age;
    long unsigned int bridge_hello_time;
    long unsigned int bridge_forward_delay;
    long unsigned int bridge_ageing_time;
    u32 root_path_cost;
    u8[6] group_addr;
    enum (anon) stp_enabled;
    u32 hash_max;
    u32 multicast_last_member_count;
    u32 multicast_startup_query_count;
    u8 multicast_igmp_version;
    u8 multicast_router;
    u8 multicast_mld_version;
    spinlock_t multicast_lock;
    long unsigned int multicast_last_member_interval;
    long unsigned int multicast_membership_interval;
    long unsigned int multicast_querier_interval;
    long unsigned int multicast_query_interval;
    long unsigned int multicast_query_response_interval;
    long unsigned int multicast_startup_query_interval;
    struct rhashtable mdb_hash_tbl;
    struct hlist_head mdb_list;
    struct hlist_head router_list;
    struct timer_list multicast_router_timer;
    struct bridge_mcast_other_query ip4_other_query;
    struct bridge_mcast_own_query ip4_own_query;
    struct bridge_mcast_querier ip4_querier;
    struct bridge_mcast_stats * mcast_stats;
    struct bridge_mcast_other_query ip6_other_query;
    struct bridge_mcast_own_query ip6_own_query;
    struct bridge_mcast_querier ip6_querier;
    struct timer_list hello_timer;
    struct timer_list tcn_timer;
    struct timer_list topology_change_timer;
    struct delayed_work gc_work;
    struct kobject * ifobj;
    u32 auto_cnt;
    int offload_fwd_mark;
    struct hlist_head fdb_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct net_bridge {
    spinlock_t lock;
    spinlock_t hash_lock;
    struct list_head port_list;
    struct net_device * dev;
    struct pcpu_sw_netstats * stats;
    long unsigned int options;
    __be16 vlan_proto;
    u16 default_pvid;
    struct net_bridge_vlan_group * vlgrp;
    struct rhashtable fdb_hash_tbl;
    struct rtable fake_rtable;
    struct rt6_info fake_rt6_info;
    u16 group_fwd_mask;
    u16 group_fwd_mask_required;
    bridge_id designated_root;
    bridge_id bridge_id;
    unsigned char topology_change;
    unsigned char topology_change_detected;
    u16 root_port;
    long unsigned int max_age;
    long unsigned int hello_time;
    long unsigned int forward_delay;
    long unsigned int ageing_time;
    long unsigned int bridge_max_age;
    long unsigned int bridge_hello_time;
    long unsigned int bridge_forward_delay;
    long unsigned int bridge_ageing_time;
    u32 root_path_cost;
    u8[6] group_addr;
    enum (anon) stp_enabled;
    u32 hash_max;
    u32 multicast_last_member_count;
    u32 multicast_startup_query_count;
    u8 multicast_igmp_version;
    u8 multicast_router;
    u8 multicast_mld_version;
    spinlock_t multicast_lock;
    long unsigned int multicast_last_member_interval;
    long unsigned int multicast_membership_interval;
    long unsigned int multicast_querier_interval;
    long unsigned int multicast_query_interval;
    long unsigned int multicast_query_response_interval;
    long unsigned int multicast_startup_query_interval;
    struct rhashtable mdb_hash_tbl;
    struct hlist_head mdb_list;
    struct hlist_head router_list;
    struct timer_list multicast_router_timer;
    struct bridge_mcast_other_query ip4_other_query;
    struct bridge_mcast_own_query ip4_own_query;
    struct bridge_mcast_querier ip4_querier;
    struct bridge_mcast_stats * mcast_stats;
    struct bridge_mcast_other_query ip6_other_query;
    struct bridge_mcast_own_query ip6_own_query;
    struct bridge_mcast_querier ip6_querier;
    struct timer_list hello_timer;
    struct timer_list tcn_timer;
    struct timer_list topology_change_timer;
    struct delayed_work gc_work;
    struct kobject * ifobj;
    u32 auto_cnt;
    int offload_fwd_mark;
    struct hlist_head fdb_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct net_bridge {
    spinlock_t lock;
    spinlock_t hash_lock;
    struct list_head port_list;
    struct net_device * dev;
    struct pcpu_sw_netstats * stats;
    long unsigned int options;
    __be16 vlan_proto;
    u16 default_pvid;
    struct net_bridge_vlan_group * vlgrp;
    struct rhashtable fdb_hash_tbl;
    struct rtable fake_rtable;
    struct rt6_info fake_rt6_info;
    u16 group_fwd_mask;
    u16 group_fwd_mask_required;
    bridge_id designated_root;
    bridge_id bridge_id;
    unsigned char topology_change;
    unsigned char topology_change_detected;
    u16 root_port;
    long unsigned int max_age;
    long unsigned int hello_time;
    long unsigned int forward_delay;
    long unsigned int ageing_time;
    long unsigned int bridge_max_age;
    long unsigned int bridge_hello_time;
    long unsigned int bridge_forward_delay;
    long unsigned int bridge_ageing_time;
    u32 root_path_cost;
    u8[6] group_addr;
    enum (anon) stp_enabled;
    u32 hash_max;
    u32 multicast_last_member_count;
    u32 multicast_startup_query_count;
    u8 multicast_igmp_version;
    u8 multicast_router;
    u8 multicast_mld_version;
    spinlock_t multicast_lock;
    long unsigned int multicast_last_member_interval;
    long unsigned int multicast_membership_interval;
    long unsigned int multicast_querier_interval;
    long unsigned int multicast_query_interval;
    long unsigned int multicast_query_response_interval;
    long unsigned int multicast_startup_query_interval;
    struct rhashtable mdb_hash_tbl;
    struct hlist_head mdb_list;
    struct hlist_head router_list;
    struct timer_list multicast_router_timer;
    struct bridge_mcast_other_query ip4_other_query;
    struct bridge_mcast_own_query ip4_own_query;
    struct bridge_mcast_querier ip4_querier;
    struct bridge_mcast_stats * mcast_stats;
    struct bridge_mcast_other_query ip6_other_query;
    struct bridge_mcast_own_query ip6_own_query;
    struct bridge_mcast_querier ip6_querier;
    struct timer_list hello_timer;
    struct timer_list tcn_timer;
    struct timer_list topology_change_timer;
    struct delayed_work gc_work;
    struct kobject * ifobj;
    u32 auto_cnt;
    int offload_fwd_mark;
    struct hlist_head fdb_list;
    struct list_head mrp_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct net_bridge {
    spinlock_t lock;
    spinlock_t hash_lock;
    struct hlist_head frame_type_list;
    struct net_device * dev;
    long unsigned int options;
    __be16 vlan_proto;
    u16 default_pvid;
    struct net_bridge_vlan_group * vlgrp;
    struct rhashtable fdb_hash_tbl;
    struct list_head port_list;
    struct rtable fake_rtable;
    struct rt6_info fake_rt6_info;
    u16 group_fwd_mask;
    u16 group_fwd_mask_required;
    bridge_id designated_root;
    bridge_id bridge_id;
    unsigned char topology_change;
    unsigned char topology_change_detected;
    u16 root_port;
    long unsigned int max_age;
    long unsigned int hello_time;
    long unsigned int forward_delay;
    long unsigned int ageing_time;
    long unsigned int bridge_max_age;
    long unsigned int bridge_hello_time;
    long unsigned int bridge_forward_delay;
    long unsigned int bridge_ageing_time;
    u32 root_path_cost;
    u8[6] group_addr;
    enum (anon) stp_enabled;
    u32 hash_max;
    u32 multicast_last_member_count;
    u32 multicast_startup_query_count;
    u8 multicast_igmp_version;
    u8 multicast_router;
    u8 multicast_mld_version;
    spinlock_t multicast_lock;
    long unsigned int multicast_last_member_interval;
    long unsigned int multicast_membership_interval;
    long unsigned int multicast_querier_interval;
    long unsigned int multicast_query_interval;
    long unsigned int multicast_query_response_interval;
    long unsigned int multicast_startup_query_interval;
    struct rhashtable mdb_hash_tbl;
    struct rhashtable sg_port_tbl;
    struct hlist_head mcast_gc_list;
    struct hlist_head mdb_list;
    struct hlist_head router_list;
    struct timer_list multicast_router_timer;
    struct bridge_mcast_other_query ip4_other_query;
    struct bridge_mcast_own_query ip4_own_query;
    struct bridge_mcast_querier ip4_querier;
    struct bridge_mcast_stats * mcast_stats;
    struct bridge_mcast_other_query ip6_other_query;
    struct bridge_mcast_own_query ip6_own_query;
    struct bridge_mcast_querier ip6_querier;
    struct work_struct mcast_gc_work;
    struct timer_list hello_timer;
    struct timer_list tcn_timer;
    struct timer_list topology_change_timer;
    struct delayed_work gc_work;
    struct kobject * ifobj;
    u32 auto_cnt;
    int offload_fwd_mark;
    struct hlist_head fdb_list;
    struct hlist_head mrp_list;
    struct hlist_head mep_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct net_bridge {
    spinlock_t lock;
    spinlock_t hash_lock;
    struct hlist_head frame_type_list;
    struct net_device * dev;
    long unsigned int options;
    __be16 vlan_proto;
    u16 default_pvid;
    struct net_bridge_vlan_group * vlgrp;
    struct rhashtable fdb_hash_tbl;
    struct list_head port_list;
    struct rtable fake_rtable;
    struct rt6_info fake_rt6_info;
    u16 group_fwd_mask;
    u16 group_fwd_mask_required;
    bridge_id designated_root;
    bridge_id bridge_id;
    unsigned char topology_change;
    unsigned char topology_change_detected;
    u16 root_port;
    long unsigned int max_age;
    long unsigned int hello_time;
    long unsigned int forward_delay;
    long unsigned int ageing_time;
    long unsigned int bridge_max_age;
    long unsigned int bridge_hello_time;
    long unsigned int bridge_forward_delay;
    long unsigned int bridge_ageing_time;
    u32 root_path_cost;
    u8[6] group_addr;
    enum (anon) stp_enabled;
    u32 hash_max;
    u32 multicast_last_member_count;
    u32 multicast_startup_query_count;
    u8 multicast_igmp_version;
    u8 multicast_router;
    u8 multicast_mld_version;
    spinlock_t multicast_lock;
    long unsigned int multicast_last_member_interval;
    long unsigned int multicast_membership_interval;
    long unsigned int multicast_querier_interval;
    long unsigned int multicast_query_interval;
    long unsigned int multicast_query_response_interval;
    long unsigned int multicast_startup_query_interval;
    struct rhashtable mdb_hash_tbl;
    struct rhashtable sg_port_tbl;
    struct hlist_head mcast_gc_list;
    struct hlist_head mdb_list;
    struct hlist_head router_list;
    struct timer_list multicast_router_timer;
    struct bridge_mcast_other_query ip4_other_query;
    struct bridge_mcast_own_query ip4_own_query;
    struct bridge_mcast_querier ip4_querier;
    struct bridge_mcast_stats * mcast_stats;
    struct bridge_mcast_other_query ip6_other_query;
    struct bridge_mcast_own_query ip6_own_query;
    struct bridge_mcast_querier ip6_querier;
    struct work_struct mcast_gc_work;
    struct timer_list hello_timer;
    struct timer_list tcn_timer;
    struct timer_list topology_change_timer;
    struct delayed_work gc_work;
    struct kobject * ifobj;
    u32 auto_cnt;
    int offload_fwd_mark;
    struct hlist_head fdb_list;
    struct hlist_head mrp_list;
    struct hlist_head mep_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct net_bridge {
    spinlock_t lock;
    spinlock_t hash_lock;
    struct hlist_head frame_type_list;
    struct net_device * dev;
    long unsigned int options;
    __be16 vlan_proto;
    u16 default_pvid;
    struct net_bridge_vlan_group * vlgrp;
    struct rhashtable fdb_hash_tbl;
    struct list_head port_list;
    struct rtable fake_rtable;
    struct rt6_info fake_rt6_info;
    u16 group_fwd_mask;
    u16 group_fwd_mask_required;
    bridge_id designated_root;
    bridge_id bridge_id;
    unsigned char topology_change;
    unsigned char topology_change_detected;
    u16 root_port;
    long unsigned int max_age;
    long unsigned int hello_time;
    long unsigned int forward_delay;
    long unsigned int ageing_time;
    long unsigned int bridge_max_age;
    long unsigned int bridge_hello_time;
    long unsigned int bridge_forward_delay;
    long unsigned int bridge_ageing_time;
    u32 root_path_cost;
    u8[6] group_addr;
    enum (anon) stp_enabled;
    struct net_bridge_mcast multicast_ctx;
    struct bridge_mcast_stats * mcast_stats;
    u32 hash_max;
    spinlock_t multicast_lock;
    struct rhashtable mdb_hash_tbl;
    struct rhashtable sg_port_tbl;
    struct hlist_head mcast_gc_list;
    struct hlist_head mdb_list;
    struct work_struct mcast_gc_work;
    struct timer_list hello_timer;
    struct timer_list tcn_timer;
    struct timer_list topology_change_timer;
    struct delayed_work gc_work;
    struct kobject * ifobj;
    u32 auto_cnt;
    int last_hwdom;
    long unsigned int busy_hwdoms;
    struct hlist_head fdb_list;
    struct hlist_head mrp_list;
    struct hlist_head mep_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct net_bridge {
    spinlock_t lock;
    spinlock_t hash_lock;
    struct hlist_head frame_type_list;
    struct net_device * dev;
    long unsigned int options;
    __be16 vlan_proto;
    u16 default_pvid;
    struct net_bridge_vlan_group * vlgrp;
    struct rhashtable fdb_hash_tbl;
    struct list_head port_list;
    struct rtable fake_rtable;
    struct rt6_info fake_rt6_info;
    u16 group_fwd_mask;
    u16 group_fwd_mask_required;
    bridge_id designated_root;
    bridge_id bridge_id;
    unsigned char topology_change;
    unsigned char topology_change_detected;
    u16 root_port;
    long unsigned int max_age;
    long unsigned int hello_time;
    long unsigned int forward_delay;
    long unsigned int ageing_time;
    long unsigned int bridge_max_age;
    long unsigned int bridge_hello_time;
    long unsigned int bridge_forward_delay;
    long unsigned int bridge_ageing_time;
    u32 root_path_cost;
    u8[6] group_addr;
    enum (anon) stp_enabled;
    struct net_bridge_mcast multicast_ctx;
    struct bridge_mcast_stats * mcast_stats;
    u32 hash_max;
    spinlock_t multicast_lock;
    struct rhashtable mdb_hash_tbl;
    struct rhashtable sg_port_tbl;
    struct hlist_head mcast_gc_list;
    struct hlist_head mdb_list;
    struct work_struct mcast_gc_work;
    struct timer_list hello_timer;
    struct timer_list tcn_timer;
    struct timer_list topology_change_timer;
    struct delayed_work gc_work;
    struct kobject * ifobj;
    u32 auto_cnt;
    int last_hwdom;
    long unsigned int busy_hwdoms;
    struct hlist_head fdb_list;
    struct hlist_head mrp_list;
    struct hlist_head mep_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct net_bridge {
    spinlock_t lock;
    spinlock_t hash_lock;
    struct hlist_head frame_type_list;
    struct net_device * dev;
    long unsigned int options;
    __be16 vlan_proto;
    u16 default_pvid;
    struct net_bridge_vlan_group * vlgrp;
    struct rhashtable fdb_hash_tbl;
    struct list_head port_list;
    struct rtable fake_rtable;
    struct rt6_info fake_rt6_info;
    u16 group_fwd_mask;
    u16 group_fwd_mask_required;
    bridge_id designated_root;
    bridge_id bridge_id;
    unsigned char topology_change;
    unsigned char topology_change_detected;
    u16 root_port;
    long unsigned int max_age;
    long unsigned int hello_time;
    long unsigned int forward_delay;
    long unsigned int ageing_time;
    long unsigned int bridge_max_age;
    long unsigned int bridge_hello_time;
    long unsigned int bridge_forward_delay;
    long unsigned int bridge_ageing_time;
    u32 root_path_cost;
    u8[6] group_addr;
    enum (anon) stp_enabled;
    struct net_bridge_mcast multicast_ctx;
    struct bridge_mcast_stats * mcast_stats;
    u32 hash_max;
    spinlock_t multicast_lock;
    struct rhashtable mdb_hash_tbl;
    struct rhashtable sg_port_tbl;
    struct hlist_head mcast_gc_list;
    struct hlist_head mdb_list;
    struct work_struct mcast_gc_work;
    struct timer_list hello_timer;
    struct timer_list tcn_timer;
    struct timer_list topology_change_timer;
    struct delayed_work gc_work;
    struct kobject * ifobj;
    u32 auto_cnt;
    int last_hwdom;
    long unsigned int busy_hwdoms;
    struct hlist_head fdb_list;
    struct hlist_head mrp_list;
    struct hlist_head mep_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct net_bridge {
    spinlock_t lock;
    spinlock_t hash_lock;
    struct hlist_head frame_type_list;
    struct net_device * dev;
    long unsigned int options;
    __be16 vlan_proto;
    u16 default_pvid;
    struct net_bridge_vlan_group * vlgrp;
    struct rhashtable fdb_hash_tbl;
    struct list_head port_list;
    struct rtable fake_rtable;
    struct rt6_info fake_rt6_info;
    u16 group_fwd_mask;
    u16 group_fwd_mask_required;
    bridge_id designated_root;
    bridge_id bridge_id;
    unsigned char topology_change;
    unsigned char topology_change_detected;
    u16 root_port;
    long unsigned int max_age;
    long unsigned int hello_time;
    long unsigned int forward_delay;
    long unsigned int ageing_time;
    long unsigned int bridge_max_age;
    long unsigned int bridge_hello_time;
    long unsigned int bridge_forward_delay;
    long unsigned int bridge_ageing_time;
    u32 root_path_cost;
    u8[6] group_addr;
    enum (anon) stp_enabled;
    struct net_bridge_mcast multicast_ctx;
    struct bridge_mcast_stats * mcast_stats;
    u32 hash_max;
    spinlock_t multicast_lock;
    struct rhashtable mdb_hash_tbl;
    struct rhashtable sg_port_tbl;
    struct hlist_head mcast_gc_list;
    struct hlist_head mdb_list;
    struct work_struct mcast_gc_work;
    struct timer_list hello_timer;
    struct timer_list tcn_timer;
    struct timer_list topology_change_timer;
    struct delayed_work gc_work;
    struct kobject * ifobj;
    u32 auto_cnt;
    int last_hwdom;
    long unsigned int busy_hwdoms;
    struct hlist_head fdb_list;
    struct hlist_head mrp_list;
    struct hlist_head mep_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct net_bridge {
    spinlock_t lock;
    spinlock_t hash_lock;
    struct hlist_head frame_type_list;
    struct net_device * dev;
    long unsigned int options;
    __be16 vlan_proto;
    u16 default_pvid;
    struct net_bridge_vlan_group * vlgrp;
    struct rhashtable fdb_hash_tbl;
    struct list_head port_list;
    struct rtable fake_rtable;
    struct rt6_info fake_rt6_info;
    u16 group_fwd_mask;
    u16 group_fwd_mask_required;
    bridge_id designated_root;
    bridge_id bridge_id;
    unsigned char topology_change;
    unsigned char topology_change_detected;
    u16 root_port;
    long unsigned int max_age;
    long unsigned int hello_time;
    long unsigned int forward_delay;
    long unsigned int ageing_time;
    long unsigned int bridge_max_age;
    long unsigned int bridge_hello_time;
    long unsigned int bridge_forward_delay;
    long unsigned int bridge_ageing_time;
    u32 root_path_cost;
    u8[6] group_addr;
    enum (anon) stp_enabled;
    struct net_bridge_mcast multicast_ctx;
    struct bridge_mcast_stats * mcast_stats;
    u32 hash_max;
    spinlock_t multicast_lock;
    struct rhashtable mdb_hash_tbl;
    struct rhashtable sg_port_tbl;
    struct hlist_head mcast_gc_list;
    struct hlist_head mdb_list;
    struct work_struct mcast_gc_work;
    struct timer_list hello_timer;
    struct timer_list tcn_timer;
    struct timer_list topology_change_timer;
    struct delayed_work gc_work;
    struct kobject * ifobj;
    u32 auto_cnt;
    atomic_t fdb_n_learned;
    u32 fdb_max_learned;
    int last_hwdom;
    long unsigned int busy_hwdoms;
    struct hlist_head fdb_list;
    struct hlist_head mrp_list;
    struct hlist_head mep_list;
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
struct net_bridge {
    spinlock_t lock;
    spinlock_t hash_lock;
    struct list_head port_list;
    struct net_device * dev;
    struct pcpu_sw_netstats * stats;
    long unsigned int options;
    __be16 vlan_proto;
    u16 default_pvid;
    struct net_bridge_vlan_group * vlgrp;
    struct rhashtable fdb_hash_tbl;
    struct rtable fake_rtable;
    struct rt6_info fake_rt6_info;
    u16 group_fwd_mask;
    u16 group_fwd_mask_required;
    bridge_id designated_root;
    bridge_id bridge_id;
    unsigned char topology_change;
    unsigned char topology_change_detected;
    u16 root_port;
    long unsigned int max_age;
    long unsigned int hello_time;
    long unsigned int forward_delay;
    long unsigned int ageing_time;
    long unsigned int bridge_max_age;
    long unsigned int bridge_hello_time;
    long unsigned int bridge_forward_delay;
    long unsigned int bridge_ageing_time;
    u32 root_path_cost;
    u8[6] group_addr;
    enum (anon) stp_enabled;
    u32 hash_max;
    u32 multicast_last_member_count;
    u32 multicast_startup_query_count;
    u8 multicast_igmp_version;
    u8 multicast_router;
    u8 multicast_mld_version;
    spinlock_t multicast_lock;
    long unsigned int multicast_last_member_interval;
    long unsigned int multicast_membership_interval;
    long unsigned int multicast_querier_interval;
    long unsigned int multicast_query_interval;
    long unsigned int multicast_query_response_interval;
    long unsigned int multicast_startup_query_interval;
    struct rhashtable mdb_hash_tbl;
    struct hlist_head mdb_list;
    struct hlist_head router_list;
    struct timer_list multicast_router_timer;
    struct bridge_mcast_other_query ip4_other_query;
    struct bridge_mcast_own_query ip4_own_query;
    struct bridge_mcast_querier ip4_querier;
    struct bridge_mcast_stats * mcast_stats;
    struct bridge_mcast_other_query ip6_other_query;
    struct bridge_mcast_own_query ip6_own_query;
    struct bridge_mcast_querier ip6_querier;
    struct timer_list hello_timer;
    struct timer_list tcn_timer;
    struct timer_list topology_change_timer;
    struct delayed_work gc_work;
    struct kobject * ifobj;
    u32 auto_cnt;
    int offload_fwd_mark;
    struct hlist_head fdb_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct net_bridge {
    spinlock_t lock;
    spinlock_t hash_lock;
    struct list_head port_list;
    struct net_device * dev;
    struct pcpu_sw_netstats * stats;
    long unsigned int options;
    __be16 vlan_proto;
    u16 default_pvid;
    struct net_bridge_vlan_group * vlgrp;
    struct rhashtable fdb_hash_tbl;
    struct rtable fake_rtable;
    struct rt6_info fake_rt6_info;
    u16 group_fwd_mask;
    u16 group_fwd_mask_required;
    bridge_id designated_root;
    bridge_id bridge_id;
    unsigned char topology_change;
    unsigned char topology_change_detected;
    u16 root_port;
    long unsigned int max_age;
    long unsigned int hello_time;
    long unsigned int forward_delay;
    long unsigned int ageing_time;
    long unsigned int bridge_max_age;
    long unsigned int bridge_hello_time;
    long unsigned int bridge_forward_delay;
    long unsigned int bridge_ageing_time;
    u32 root_path_cost;
    u8[6] group_addr;
    enum (anon) stp_enabled;
    u32 hash_max;
    u32 multicast_last_member_count;
    u32 multicast_startup_query_count;
    u8 multicast_igmp_version;
    u8 multicast_router;
    u8 multicast_mld_version;
    spinlock_t multicast_lock;
    long unsigned int multicast_last_member_interval;
    long unsigned int multicast_membership_interval;
    long unsigned int multicast_querier_interval;
    long unsigned int multicast_query_interval;
    long unsigned int multicast_query_response_interval;
    long unsigned int multicast_startup_query_interval;
    struct rhashtable mdb_hash_tbl;
    struct hlist_head mdb_list;
    struct hlist_head router_list;
    struct timer_list multicast_router_timer;
    struct bridge_mcast_other_query ip4_other_query;
    struct bridge_mcast_own_query ip4_own_query;
    struct bridge_mcast_querier ip4_querier;
    struct bridge_mcast_stats * mcast_stats;
    struct bridge_mcast_other_query ip6_other_query;
    struct bridge_mcast_own_query ip6_own_query;
    struct bridge_mcast_querier ip6_querier;
    struct timer_list hello_timer;
    struct timer_list tcn_timer;
    struct timer_list topology_change_timer;
    struct delayed_work gc_work;
    struct kobject * ifobj;
    u32 auto_cnt;
    int offload_fwd_mark;
    struct hlist_head fdb_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct net_bridge {
    spinlock_t lock;
    spinlock_t hash_lock;
    struct list_head port_list;
    struct net_device * dev;
    struct pcpu_sw_netstats * stats;
    long unsigned int options;
    __be16 vlan_proto;
    u16 default_pvid;
    struct net_bridge_vlan_group * vlgrp;
    struct rhashtable fdb_hash_tbl;
    struct rtable fake_rtable;
    struct rt6_info fake_rt6_info;
    u16 group_fwd_mask;
    u16 group_fwd_mask_required;
    bridge_id designated_root;
    bridge_id bridge_id;
    unsigned char topology_change;
    unsigned char topology_change_detected;
    u16 root_port;
    long unsigned int max_age;
    long unsigned int hello_time;
    long unsigned int forward_delay;
    long unsigned int ageing_time;
    long unsigned int bridge_max_age;
    long unsigned int bridge_hello_time;
    long unsigned int bridge_forward_delay;
    long unsigned int bridge_ageing_time;
    u32 root_path_cost;
    u8[6] group_addr;
    enum (anon) stp_enabled;
    u32 hash_max;
    u32 multicast_last_member_count;
    u32 multicast_startup_query_count;
    u8 multicast_igmp_version;
    u8 multicast_router;
    u8 multicast_mld_version;
    spinlock_t multicast_lock;
    long unsigned int multicast_last_member_interval;
    long unsigned int multicast_membership_interval;
    long unsigned int multicast_querier_interval;
    long unsigned int multicast_query_interval;
    long unsigned int multicast_query_response_interval;
    long unsigned int multicast_startup_query_interval;
    struct rhashtable mdb_hash_tbl;
    struct hlist_head mdb_list;
    struct hlist_head router_list;
    struct timer_list multicast_router_timer;
    struct bridge_mcast_other_query ip4_other_query;
    struct bridge_mcast_own_query ip4_own_query;
    struct bridge_mcast_querier ip4_querier;
    struct bridge_mcast_stats * mcast_stats;
    struct bridge_mcast_other_query ip6_other_query;
    struct bridge_mcast_own_query ip6_own_query;
    struct bridge_mcast_querier ip6_querier;
    struct timer_list hello_timer;
    struct timer_list tcn_timer;
    struct timer_list topology_change_timer;
    struct delayed_work gc_work;
    struct kobject * ifobj;
    u32 auto_cnt;
    int offload_fwd_mark;
    struct hlist_head fdb_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct net_bridge {
    spinlock_t lock;
    spinlock_t hash_lock;
    struct list_head port_list;
    struct net_device * dev;
    struct pcpu_sw_netstats * stats;
    long unsigned int options;
    __be16 vlan_proto;
    u16 default_pvid;
    struct net_bridge_vlan_group * vlgrp;
    struct rhashtable fdb_hash_tbl;
    struct rtable fake_rtable;
    struct rt6_info fake_rt6_info;
    u16 group_fwd_mask;
    u16 group_fwd_mask_required;
    bridge_id designated_root;
    bridge_id bridge_id;
    unsigned char topology_change;
    unsigned char topology_change_detected;
    u16 root_port;
    long unsigned int max_age;
    long unsigned int hello_time;
    long unsigned int forward_delay;
    long unsigned int ageing_time;
    long unsigned int bridge_max_age;
    long unsigned int bridge_hello_time;
    long unsigned int bridge_forward_delay;
    long unsigned int bridge_ageing_time;
    u32 root_path_cost;
    u8[6] group_addr;
    enum (anon) stp_enabled;
    u32 hash_max;
    u32 multicast_last_member_count;
    u32 multicast_startup_query_count;
    u8 multicast_igmp_version;
    u8 multicast_router;
    u8 multicast_mld_version;
    spinlock_t multicast_lock;
    long unsigned int multicast_last_member_interval;
    long unsigned int multicast_membership_interval;
    long unsigned int multicast_querier_interval;
    long unsigned int multicast_query_interval;
    long unsigned int multicast_query_response_interval;
    long unsigned int multicast_startup_query_interval;
    struct rhashtable mdb_hash_tbl;
    struct hlist_head mdb_list;
    struct hlist_head router_list;
    struct timer_list multicast_router_timer;
    struct bridge_mcast_other_query ip4_other_query;
    struct bridge_mcast_own_query ip4_own_query;
    struct bridge_mcast_querier ip4_querier;
    struct bridge_mcast_stats * mcast_stats;
    struct bridge_mcast_other_query ip6_other_query;
    struct bridge_mcast_own_query ip6_own_query;
    struct bridge_mcast_querier ip6_querier;
    struct timer_list hello_timer;
    struct timer_list tcn_timer;
    struct timer_list topology_change_timer;
    struct delayed_work gc_work;
    struct kobject * ifobj;
    u32 auto_cnt;
    int offload_fwd_mark;
    struct hlist_head fdb_list;
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
struct net_bridge {
    spinlock_t lock;
    spinlock_t hash_lock;
    struct list_head port_list;
    struct net_device * dev;
    struct pcpu_sw_netstats * stats;
    long unsigned int options;
    __be16 vlan_proto;
    u16 default_pvid;
    struct net_bridge_vlan_group * vlgrp;
    struct rhashtable fdb_hash_tbl;
    struct rtable fake_rtable;
    struct rt6_info fake_rt6_info;
    u16 group_fwd_mask;
    u16 group_fwd_mask_required;
    bridge_id designated_root;
    bridge_id bridge_id;
    unsigned char topology_change;
    unsigned char topology_change_detected;
    u16 root_port;
    long unsigned int max_age;
    long unsigned int hello_time;
    long unsigned int forward_delay;
    long unsigned int ageing_time;
    long unsigned int bridge_max_age;
    long unsigned int bridge_hello_time;
    long unsigned int bridge_forward_delay;
    long unsigned int bridge_ageing_time;
    u32 root_path_cost;
    u8[6] group_addr;
    enum (anon) stp_enabled;
    u32 hash_max;
    u32 multicast_last_member_count;
    u32 multicast_startup_query_count;
    u8 multicast_igmp_version;
    u8 multicast_router;
    u8 multicast_mld_version;
    spinlock_t multicast_lock;
    long unsigned int multicast_last_member_interval;
    long unsigned int multicast_membership_interval;
    long unsigned int multicast_querier_interval;
    long unsigned int multicast_query_interval;
    long unsigned int multicast_query_response_interval;
    long unsigned int multicast_startup_query_interval;
    struct rhashtable mdb_hash_tbl;
    struct hlist_head mdb_list;
    struct hlist_head router_list;
    struct timer_list multicast_router_timer;
    struct bridge_mcast_other_query ip4_other_query;
    struct bridge_mcast_own_query ip4_own_query;
    struct bridge_mcast_querier ip4_querier;
    struct bridge_mcast_stats * mcast_stats;
    struct bridge_mcast_other_query ip6_other_query;
    struct bridge_mcast_own_query ip6_own_query;
    struct bridge_mcast_querier ip6_querier;
    struct timer_list hello_timer;
    struct timer_list tcn_timer;
    struct timer_list topology_change_timer;
    struct delayed_work gc_work;
    struct kobject * ifobj;
    u32 auto_cnt;
    int offload_fwd_mark;
    struct hlist_head fdb_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct net_bridge {
    spinlock_t lock;
    spinlock_t hash_lock;
    struct list_head port_list;
    struct net_device * dev;
    struct pcpu_sw_netstats * stats;
    long unsigned int options;
    __be16 vlan_proto;
    u16 default_pvid;
    struct net_bridge_vlan_group * vlgrp;
    struct rhashtable fdb_hash_tbl;
    struct rtable fake_rtable;
    struct rt6_info fake_rt6_info;
    u16 group_fwd_mask;
    u16 group_fwd_mask_required;
    bridge_id designated_root;
    bridge_id bridge_id;
    unsigned char topology_change;
    unsigned char topology_change_detected;
    u16 root_port;
    long unsigned int max_age;
    long unsigned int hello_time;
    long unsigned int forward_delay;
    long unsigned int ageing_time;
    long unsigned int bridge_max_age;
    long unsigned int bridge_hello_time;
    long unsigned int bridge_forward_delay;
    long unsigned int bridge_ageing_time;
    u32 root_path_cost;
    u8[6] group_addr;
    enum (anon) stp_enabled;
    u32 hash_max;
    u32 multicast_last_member_count;
    u32 multicast_startup_query_count;
    u8 multicast_igmp_version;
    u8 multicast_router;
    u8 multicast_mld_version;
    spinlock_t multicast_lock;
    long unsigned int multicast_last_member_interval;
    long unsigned int multicast_membership_interval;
    long unsigned int multicast_querier_interval;
    long unsigned int multicast_query_interval;
    long unsigned int multicast_query_response_interval;
    long unsigned int multicast_startup_query_interval;
    struct rhashtable mdb_hash_tbl;
    struct hlist_head mdb_list;
    struct hlist_head router_list;
    struct timer_list multicast_router_timer;
    struct bridge_mcast_other_query ip4_other_query;
    struct bridge_mcast_own_query ip4_own_query;
    struct bridge_mcast_querier ip4_querier;
    struct bridge_mcast_stats * mcast_stats;
    struct bridge_mcast_other_query ip6_other_query;
    struct bridge_mcast_own_query ip6_own_query;
    struct bridge_mcast_querier ip6_querier;
    struct timer_list hello_timer;
    struct timer_list tcn_timer;
    struct timer_list topology_change_timer;
    struct delayed_work gc_work;
    struct kobject * ifobj;
    u32 auto_cnt;
    int offload_fwd_mark;
    struct hlist_head fdb_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct net_bridge {
    spinlock_t lock;
    spinlock_t hash_lock;
    struct list_head port_list;
    struct net_device * dev;
    struct pcpu_sw_netstats * stats;
    long unsigned int options;
    __be16 vlan_proto;
    u16 default_pvid;
    struct net_bridge_vlan_group * vlgrp;
    struct rhashtable fdb_hash_tbl;
    struct rtable fake_rtable;
    struct rt6_info fake_rt6_info;
    u16 group_fwd_mask;
    u16 group_fwd_mask_required;
    bridge_id designated_root;
    bridge_id bridge_id;
    unsigned char topology_change;
    unsigned char topology_change_detected;
    u16 root_port;
    long unsigned int max_age;
    long unsigned int hello_time;
    long unsigned int forward_delay;
    long unsigned int ageing_time;
    long unsigned int bridge_max_age;
    long unsigned int bridge_hello_time;
    long unsigned int bridge_forward_delay;
    long unsigned int bridge_ageing_time;
    u32 root_path_cost;
    u8[6] group_addr;
    enum (anon) stp_enabled;
    u32 hash_max;
    u32 multicast_last_member_count;
    u32 multicast_startup_query_count;
    u8 multicast_igmp_version;
    u8 multicast_router;
    u8 multicast_mld_version;
    spinlock_t multicast_lock;
    long unsigned int multicast_last_member_interval;
    long unsigned int multicast_membership_interval;
    long unsigned int multicast_querier_interval;
    long unsigned int multicast_query_interval;
    long unsigned int multicast_query_response_interval;
    long unsigned int multicast_startup_query_interval;
    struct rhashtable mdb_hash_tbl;
    struct hlist_head mdb_list;
    struct hlist_head router_list;
    struct timer_list multicast_router_timer;
    struct bridge_mcast_other_query ip4_other_query;
    struct bridge_mcast_own_query ip4_own_query;
    struct bridge_mcast_querier ip4_querier;
    struct bridge_mcast_stats * mcast_stats;
    struct bridge_mcast_other_query ip6_other_query;
    struct bridge_mcast_own_query ip6_own_query;
    struct bridge_mcast_querier ip6_querier;
    struct timer_list hello_timer;
    struct timer_list tcn_timer;
    struct timer_list topology_change_timer;
    struct delayed_work gc_work;
    struct kobject * ifobj;
    u32 auto_cnt;
    int offload_fwd_mark;
    struct hlist_head fdb_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct net_bridge {
    spinlock_t lock;
    spinlock_t hash_lock;
    struct list_head port_list;
    struct net_device * dev;
    struct pcpu_sw_netstats * stats;
    long unsigned int options;
    __be16 vlan_proto;
    u16 default_pvid;
    struct net_bridge_vlan_group * vlgrp;
    struct rhashtable fdb_hash_tbl;
    struct rtable fake_rtable;
    struct rt6_info fake_rt6_info;
    u16 group_fwd_mask;
    u16 group_fwd_mask_required;
    bridge_id designated_root;
    bridge_id bridge_id;
    unsigned char topology_change;
    unsigned char topology_change_detected;
    u16 root_port;
    long unsigned int max_age;
    long unsigned int hello_time;
    long unsigned int forward_delay;
    long unsigned int ageing_time;
    long unsigned int bridge_max_age;
    long unsigned int bridge_hello_time;
    long unsigned int bridge_forward_delay;
    long unsigned int bridge_ageing_time;
    u32 root_path_cost;
    u8[6] group_addr;
    enum (anon) stp_enabled;
    u32 hash_max;
    u32 multicast_last_member_count;
    u32 multicast_startup_query_count;
    u8 multicast_igmp_version;
    u8 multicast_router;
    u8 multicast_mld_version;
    spinlock_t multicast_lock;
    long unsigned int multicast_last_member_interval;
    long unsigned int multicast_membership_interval;
    long unsigned int multicast_querier_interval;
    long unsigned int multicast_query_interval;
    long unsigned int multicast_query_response_interval;
    long unsigned int multicast_startup_query_interval;
    struct rhashtable mdb_hash_tbl;
    struct hlist_head mdb_list;
    struct hlist_head router_list;
    struct timer_list multicast_router_timer;
    struct bridge_mcast_other_query ip4_other_query;
    struct bridge_mcast_own_query ip4_own_query;
    struct bridge_mcast_querier ip4_querier;
    struct bridge_mcast_stats * mcast_stats;
    struct bridge_mcast_other_query ip6_other_query;
    struct bridge_mcast_own_query ip6_own_query;
    struct bridge_mcast_querier ip6_querier;
    struct timer_list hello_timer;
    struct timer_list tcn_timer;
    struct timer_list topology_change_timer;
    struct delayed_work gc_work;
    struct kobject * ifobj;
    u32 auto_cnt;
    int offload_fwd_mark;
    struct hlist_head fdb_list;
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct net_bridge {
    spinlock_t lock;
    spinlock_t hash_lock;
    struct list_head port_list;
    struct net_device * dev;
    struct pcpu_sw_netstats * stats;
    u8 vlan_enabled;
    u8 vlan_stats_enabled;
    __be16 vlan_proto;
    u16 default_pvid;
    struct net_bridge_vlan_group * vlgrp;
    struct hlist_head[256] hash;
    struct rtable fake_rtable;
    struct rt6_info fake_rt6_info;
    bool nf_call_iptables;
    bool nf_call_ip6tables;
    bool nf_call_arptables;
    u16 group_fwd_mask;
    u16 group_fwd_mask_required;
    bridge_id designated_root;
    bridge_id bridge_id;
    u32 root_path_cost;
    unsigned char topology_change;
    unsigned char topology_change_detected;
    u16 root_port;
    long unsigned int max_age;
    long unsigned int hello_time;
    long unsigned int forward_delay;
    long unsigned int ageing_time;
    long unsigned int bridge_max_age;
    long unsigned int bridge_hello_time;
    long unsigned int bridge_forward_delay;
    long unsigned int bridge_ageing_time;
    u8[6] group_addr;
    bool group_addr_set;
    enum (anon) stp_enabled;
    unsigned char multicast_router;
    u8 multicast_disabled;
    u8 multicast_querier;
    u8 multicast_query_use_ifaddr;
    u8 has_ipv6_addr;
    u8 multicast_stats_enabled;
    u32 hash_elasticity;
    u32 hash_max;
    u32 multicast_last_member_count;
    u32 multicast_startup_query_count;
    u8 multicast_igmp_version;
    long unsigned int multicast_last_member_interval;
    long unsigned int multicast_membership_interval;
    long unsigned int multicast_querier_interval;
    long unsigned int multicast_query_interval;
    long unsigned int multicast_query_response_interval;
    long unsigned int multicast_startup_query_interval;
    spinlock_t multicast_lock;
    struct net_bridge_mdb_htable * mdb;
    struct hlist_head router_list;
    struct timer_list multicast_router_timer;
    struct bridge_mcast_other_query ip4_other_query;
    struct bridge_mcast_own_query ip4_own_query;
    struct bridge_mcast_querier ip4_querier;
    struct bridge_mcast_stats * mcast_stats;
    struct bridge_mcast_other_query ip6_other_query;
    struct bridge_mcast_own_query ip6_own_query;
    struct bridge_mcast_querier ip6_querier;
    u8 multicast_mld_version;
    struct timer_list hello_timer;
    struct timer_list tcn_timer;
    struct timer_list topology_change_timer;
    struct delayed_work gc_work;
    struct kobject * ifobj;
    u32 auto_cnt;
    int offload_fwd_mark;
    bool neigh_suppress_enabled;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct rhashtable fdb_hash_tbl</code>
</li>
<li>
<b>Field added. </b>
<code>bool mtu_set_by_user</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head fdb_list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct hlist_head[256] hash</code>
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
<code>long unsigned int options</code>
</li>
<li>
<b>Field added. </b>
<code>struct rhashtable mdb_hash_tbl</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head mdb_list</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 vlan_enabled</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 vlan_stats_enabled</code>
</li>
<li>
<b>Field removed. </b>
<code>bool nf_call_iptables</code>
</li>
<li>
<b>Field removed. </b>
<code>bool nf_call_ip6tables</code>
</li>
<li>
<b>Field removed. </b>
<code>bool nf_call_arptables</code>
</li>
<li>
<b>Field removed. </b>
<code>bool group_addr_set</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 multicast_disabled</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 multicast_querier</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 multicast_query_use_ifaddr</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 has_ipv6_addr</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 multicast_stats_enabled</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 hash_elasticity</code>
</li>
<li>
<b>Field removed. </b>
<code>struct net_bridge_mdb_htable * mdb</code>
</li>
<li>
<b>Field removed. </b>
<code>bool neigh_suppress_enabled</code>
</li>
<li>
<b>Field removed. </b>
<code>bool mtu_set_by_user</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned char multicast_router</code> ➡️ <code>u8 multicast_router</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct list_head mrp_list</code>
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
<code>struct hlist_head frame_type_list</code>
</li>
<li>
<b>Field added. </b>
<code>struct rhashtable sg_port_tbl</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head mcast_gc_list</code>
</li>
<li>
<b>Field added. </b>
<code>struct work_struct mcast_gc_work</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head mep_list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct pcpu_sw_netstats * stats</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head mrp_list</code> ➡️ <code>struct hlist_head mrp_list</code>
</li>
</ul>
</details>
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
<code>struct net_bridge_mcast multicast_ctx</code>
</li>
<li>
<b>Field added. </b>
<code>int last_hwdom</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int busy_hwdoms</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 multicast_last_member_count</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 multicast_startup_query_count</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 multicast_igmp_version</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 multicast_router</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 multicast_mld_version</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int multicast_last_member_interval</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int multicast_membership_interval</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int multicast_querier_interval</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int multicast_query_interval</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int multicast_query_response_interval</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int multicast_startup_query_interval</code>
</li>
<li>
<b>Field removed. </b>
<code>struct hlist_head router_list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct timer_list multicast_router_timer</code>
</li>
<li>
<b>Field removed. </b>
<code>struct bridge_mcast_other_query ip4_other_query</code>
</li>
<li>
<b>Field removed. </b>
<code>struct bridge_mcast_own_query ip4_own_query</code>
</li>
<li>
<b>Field removed. </b>
<code>struct bridge_mcast_querier ip4_querier</code>
</li>
<li>
<b>Field removed. </b>
<code>struct bridge_mcast_other_query ip6_other_query</code>
</li>
<li>
<b>Field removed. </b>
<code>struct bridge_mcast_own_query ip6_own_query</code>
</li>
<li>
<b>Field removed. </b>
<code>struct bridge_mcast_querier ip6_querier</code>
</li>
<li>
<b>Field removed. </b>
<code>int offload_fwd_mark</code>
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>atomic_t fdb_n_learned</code>
</li>
<li>
<b>Field added. </b>
<code>u32 fdb_max_learned</code>
</li>
</ul>
</details>
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
