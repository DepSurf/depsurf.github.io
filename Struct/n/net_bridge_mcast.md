# Struct: <code>net_bridge_mcast</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct net_bridge_mcast {
    struct net_bridge * br;
    struct net_bridge_vlan * vlan;
    u32 multicast_last_member_count;
    u32 multicast_startup_query_count;
    u8 multicast_querier;
    u8 multicast_igmp_version;
    u8 multicast_router;
    u8 multicast_mld_version;
    long unsigned int multicast_last_member_interval;
    long unsigned int multicast_membership_interval;
    long unsigned int multicast_querier_interval;
    long unsigned int multicast_query_interval;
    long unsigned int multicast_query_response_interval;
    long unsigned int multicast_startup_query_interval;
    struct hlist_head ip4_mc_router_list;
    struct timer_list ip4_mc_router_timer;
    struct bridge_mcast_other_query ip4_other_query;
    struct bridge_mcast_own_query ip4_own_query;
    struct bridge_mcast_querier ip4_querier;
    struct hlist_head ip6_mc_router_list;
    struct timer_list ip6_mc_router_timer;
    struct bridge_mcast_other_query ip6_other_query;
    struct bridge_mcast_own_query ip6_own_query;
    struct bridge_mcast_querier ip6_querier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct net_bridge_mcast {
    struct net_bridge * br;
    struct net_bridge_vlan * vlan;
    u32 multicast_last_member_count;
    u32 multicast_startup_query_count;
    u8 multicast_querier;
    u8 multicast_igmp_version;
    u8 multicast_router;
    u8 multicast_mld_version;
    long unsigned int multicast_last_member_interval;
    long unsigned int multicast_membership_interval;
    long unsigned int multicast_querier_interval;
    long unsigned int multicast_query_interval;
    long unsigned int multicast_query_response_interval;
    long unsigned int multicast_startup_query_interval;
    struct hlist_head ip4_mc_router_list;
    struct timer_list ip4_mc_router_timer;
    struct bridge_mcast_other_query ip4_other_query;
    struct bridge_mcast_own_query ip4_own_query;
    struct bridge_mcast_querier ip4_querier;
    struct hlist_head ip6_mc_router_list;
    struct timer_list ip6_mc_router_timer;
    struct bridge_mcast_other_query ip6_other_query;
    struct bridge_mcast_own_query ip6_own_query;
    struct bridge_mcast_querier ip6_querier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct net_bridge_mcast {
    struct net_bridge * br;
    struct net_bridge_vlan * vlan;
    u32 multicast_last_member_count;
    u32 multicast_startup_query_count;
    u8 multicast_querier;
    u8 multicast_igmp_version;
    u8 multicast_router;
    u8 multicast_mld_version;
    long unsigned int multicast_last_member_interval;
    long unsigned int multicast_membership_interval;
    long unsigned int multicast_querier_interval;
    long unsigned int multicast_query_interval;
    long unsigned int multicast_query_response_interval;
    long unsigned int multicast_startup_query_interval;
    struct hlist_head ip4_mc_router_list;
    struct timer_list ip4_mc_router_timer;
    struct bridge_mcast_other_query ip4_other_query;
    struct bridge_mcast_own_query ip4_own_query;
    struct bridge_mcast_querier ip4_querier;
    struct hlist_head ip6_mc_router_list;
    struct timer_list ip6_mc_router_timer;
    struct bridge_mcast_other_query ip6_other_query;
    struct bridge_mcast_own_query ip6_own_query;
    struct bridge_mcast_querier ip6_querier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct net_bridge_mcast {
    struct net_bridge * br;
    struct net_bridge_vlan * vlan;
    u32 multicast_last_member_count;
    u32 multicast_startup_query_count;
    u8 multicast_querier;
    u8 multicast_igmp_version;
    u8 multicast_router;
    u8 multicast_mld_version;
    long unsigned int multicast_last_member_interval;
    long unsigned int multicast_membership_interval;
    long unsigned int multicast_querier_interval;
    long unsigned int multicast_query_interval;
    long unsigned int multicast_query_response_interval;
    long unsigned int multicast_startup_query_interval;
    struct hlist_head ip4_mc_router_list;
    struct timer_list ip4_mc_router_timer;
    struct bridge_mcast_other_query ip4_other_query;
    struct bridge_mcast_own_query ip4_own_query;
    struct bridge_mcast_querier ip4_querier;
    struct hlist_head ip6_mc_router_list;
    struct timer_list ip6_mc_router_timer;
    struct bridge_mcast_other_query ip6_other_query;
    struct bridge_mcast_own_query ip6_own_query;
    struct bridge_mcast_querier ip6_querier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct net_bridge_mcast {
    struct net_bridge * br;
    struct net_bridge_vlan * vlan;
    u32 multicast_last_member_count;
    u32 multicast_startup_query_count;
    u8 multicast_querier;
    u8 multicast_igmp_version;
    u8 multicast_router;
    u8 multicast_mld_version;
    long unsigned int multicast_last_member_interval;
    long unsigned int multicast_membership_interval;
    long unsigned int multicast_querier_interval;
    long unsigned int multicast_query_interval;
    long unsigned int multicast_query_response_interval;
    long unsigned int multicast_startup_query_interval;
    struct hlist_head ip4_mc_router_list;
    struct timer_list ip4_mc_router_timer;
    struct bridge_mcast_other_query ip4_other_query;
    struct bridge_mcast_own_query ip4_own_query;
    struct bridge_mcast_querier ip4_querier;
    struct hlist_head ip6_mc_router_list;
    struct timer_list ip6_mc_router_timer;
    struct bridge_mcast_other_query ip6_other_query;
    struct bridge_mcast_own_query ip6_own_query;
    struct bridge_mcast_querier ip6_querier;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
struct net_bridge_mcast {
    struct net_bridge * br;
    struct net_bridge_vlan * vlan;
    u32 multicast_last_member_count;
    u32 multicast_startup_query_count;
    u8 multicast_querier;
    u8 multicast_igmp_version;
    u8 multicast_router;
    u8 multicast_mld_version;
    long unsigned int multicast_last_member_interval;
    long unsigned int multicast_membership_interval;
    long unsigned int multicast_querier_interval;
    long unsigned int multicast_query_interval;
    long unsigned int multicast_query_response_interval;
    long unsigned int multicast_startup_query_interval;
    struct hlist_head ip4_mc_router_list;
    struct timer_list ip4_mc_router_timer;
    struct bridge_mcast_other_query ip4_other_query;
    struct bridge_mcast_own_query ip4_own_query;
    struct bridge_mcast_querier ip4_querier;
    struct hlist_head ip6_mc_router_list;
    struct timer_list ip6_mc_router_timer;
    struct bridge_mcast_other_query ip6_other_query;
    struct bridge_mcast_own_query ip6_own_query;
    struct bridge_mcast_querier ip6_querier;
}
```
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
