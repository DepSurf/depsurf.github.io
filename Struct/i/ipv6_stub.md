# Struct: <code>ipv6_stub</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ipv6_stub {
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_join;
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_drop;
    int (*)(struct net *, struct sock *, struct dst_entry * *, struct flowi6 *) ipv6_dst_lookup;
    void (*)() udpv6_encap_enable;
    void (*)(struct net_device *, const struct in6_addr *, const struct in6_addr *, bool, bool, bool, bool) ndisc_send_na;
    struct neigh_table * nd_tbl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct ipv6_stub {
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_join;
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_drop;
    int (*)(struct net *, struct sock *, struct dst_entry * *, struct flowi6 *) ipv6_dst_lookup;
    void (*)() udpv6_encap_enable;
    void (*)(struct net_device *, const struct in6_addr *, const struct in6_addr *, bool, bool, bool, bool) ndisc_send_na;
    struct neigh_table * nd_tbl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct ipv6_stub {
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_join;
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_drop;
    int (*)(struct net *, struct sock *, struct dst_entry * *, struct flowi6 *) ipv6_dst_lookup;
    void (*)() udpv6_encap_enable;
    void (*)(struct net_device *, const struct in6_addr *, const struct in6_addr *, bool, bool, bool, bool) ndisc_send_na;
    struct neigh_table * nd_tbl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct ipv6_stub {
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_join;
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_drop;
    int (*)(struct net *, struct sock *, struct dst_entry * *, struct flowi6 *) ipv6_dst_lookup;
    void (*)() udpv6_encap_enable;
    void (*)(struct net_device *, const struct in6_addr *, const struct in6_addr *, bool, bool, bool, bool) ndisc_send_na;
    struct neigh_table * nd_tbl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ipv6_stub {
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_join;
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_drop;
    int (*)(struct net *, struct sock *, struct dst_entry * *, struct flowi6 *) ipv6_dst_lookup;
    void (*)() udpv6_encap_enable;
    void (*)(struct net_device *, const struct in6_addr *, const struct in6_addr *, bool, bool, bool, bool) ndisc_send_na;
    struct neigh_table * nd_tbl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ipv6_stub {
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_join;
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_drop;
    int (*)(struct net *, struct sock *, struct dst_entry * *, struct flowi6 *) ipv6_dst_lookup;
    struct fib6_table * (*)(struct net *, u32) fib6_get_table;
    struct fib6_info * (*)(struct net *, int, struct flowi6 *, int) fib6_lookup;
    struct fib6_info * (*)(struct net *, struct fib6_table *, int, struct flowi6 *, int) fib6_table_lookup;
    struct fib6_info * (*)(const struct net *, struct fib6_info *, struct flowi6 *, int, const struct sk_buff *, int) fib6_multipath_select;
    u32 (*)(struct fib6_info *, struct in6_addr *, struct in6_addr *) ip6_mtu_from_fib6;
    void (*)() udpv6_encap_enable;
    void (*)(struct net_device *, const struct in6_addr *, const struct in6_addr *, bool, bool, bool, bool) ndisc_send_na;
    struct neigh_table * nd_tbl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ipv6_stub {
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_join;
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_drop;
    int (*)(struct net *, struct sock *, struct dst_entry * *, struct flowi6 *) ipv6_dst_lookup;
    struct fib6_table * (*)(struct net *, u32) fib6_get_table;
    struct fib6_info * (*)(struct net *, int, struct flowi6 *, int) fib6_lookup;
    struct fib6_info * (*)(struct net *, struct fib6_table *, int, struct flowi6 *, int) fib6_table_lookup;
    struct fib6_info * (*)(const struct net *, struct fib6_info *, struct flowi6 *, int, const struct sk_buff *, int) fib6_multipath_select;
    u32 (*)(struct fib6_info *, struct in6_addr *, struct in6_addr *) ip6_mtu_from_fib6;
    void (*)() udpv6_encap_enable;
    void (*)(struct net_device *, const struct in6_addr *, const struct in6_addr *, bool, bool, bool, bool) ndisc_send_na;
    struct neigh_table * nd_tbl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ipv6_stub {
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_join;
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_drop;
    int (*)(struct net *, struct sock *, struct dst_entry * *, struct flowi6 *) ipv6_dst_lookup;
    int (*)(struct sk_buff *) ipv6_route_input;
    struct fib6_table * (*)(struct net *, u32) fib6_get_table;
    int (*)(struct net *, int, struct flowi6 *, struct fib6_result *, int) fib6_lookup;
    int (*)(struct net *, struct fib6_table *, int, struct flowi6 *, struct fib6_result *, int) fib6_table_lookup;
    void (*)(const struct net *, struct fib6_result *, struct flowi6 *, int, bool, const struct sk_buff *, int) fib6_select_path;
    u32 (*)(const struct fib6_result *, const struct in6_addr *, const struct in6_addr *) ip6_mtu_from_fib6;
    int (*)(struct net *, struct fib6_nh *, struct fib6_config *, gfp_t, struct netlink_ext_ack *) fib6_nh_init;
    void (*)(struct fib6_nh *) fib6_nh_release;
    void (*)(struct net *, struct fib6_info *) fib6_update_sernum;
    int (*)(struct net *, struct fib6_info *) ip6_del_rt;
    void (*)(struct net *, struct fib6_info *, struct nl_info *) fib6_rt_update;
    void (*)() udpv6_encap_enable;
    void (*)(struct net_device *, const struct in6_addr *, const struct in6_addr *, bool, bool, bool, bool) ndisc_send_na;
    struct neigh_table * nd_tbl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ipv6_stub {
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_join;
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_drop;
    struct dst_entry * (*)(struct net *, const struct sock *, struct flowi6 *, const struct in6_addr *) ipv6_dst_lookup_flow;
    int (*)(struct sk_buff *) ipv6_route_input;
    struct fib6_table * (*)(struct net *, u32) fib6_get_table;
    int (*)(struct net *, int, struct flowi6 *, struct fib6_result *, int) fib6_lookup;
    int (*)(struct net *, struct fib6_table *, int, struct flowi6 *, struct fib6_result *, int) fib6_table_lookup;
    void (*)(const struct net *, struct fib6_result *, struct flowi6 *, int, bool, const struct sk_buff *, int) fib6_select_path;
    u32 (*)(const struct fib6_result *, const struct in6_addr *, const struct in6_addr *) ip6_mtu_from_fib6;
    int (*)(struct net *, struct fib6_nh *, struct fib6_config *, gfp_t, struct netlink_ext_ack *) fib6_nh_init;
    void (*)(struct fib6_nh *) fib6_nh_release;
    void (*)(struct net *, struct fib6_info *) fib6_update_sernum;
    int (*)(struct net *, struct fib6_info *) ip6_del_rt;
    void (*)(struct net *, struct fib6_info *, struct nl_info *) fib6_rt_update;
    void (*)() udpv6_encap_enable;
    void (*)(struct net_device *, const struct in6_addr *, const struct in6_addr *, bool, bool, bool, bool) ndisc_send_na;
    struct neigh_table * nd_tbl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ipv6_stub {
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_join;
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_drop;
    struct dst_entry * (*)(struct net *, const struct sock *, struct flowi6 *, const struct in6_addr *) ipv6_dst_lookup_flow;
    int (*)(struct sk_buff *) ipv6_route_input;
    struct fib6_table * (*)(struct net *, u32) fib6_get_table;
    int (*)(struct net *, int, struct flowi6 *, struct fib6_result *, int) fib6_lookup;
    int (*)(struct net *, struct fib6_table *, int, struct flowi6 *, struct fib6_result *, int) fib6_table_lookup;
    void (*)(const struct net *, struct fib6_result *, struct flowi6 *, int, bool, const struct sk_buff *, int) fib6_select_path;
    u32 (*)(const struct fib6_result *, const struct in6_addr *, const struct in6_addr *) ip6_mtu_from_fib6;
    int (*)(struct net *, struct fib6_nh *, struct fib6_config *, gfp_t, struct netlink_ext_ack *) fib6_nh_init;
    void (*)(struct fib6_nh *) fib6_nh_release;
    void (*)(struct net *, struct fib6_info *) fib6_update_sernum;
    int (*)(struct net *, struct fib6_info *, bool) ip6_del_rt;
    void (*)(struct net *, struct fib6_info *, struct nl_info *) fib6_rt_update;
    void (*)() udpv6_encap_enable;
    void (*)(struct net_device *, const struct in6_addr *, const struct in6_addr *, bool, bool, bool, bool) ndisc_send_na;
    void (*)(struct sk_buff *, u32) xfrm6_local_rxpmtu;
    int (*)(struct sock *, struct sk_buff *) xfrm6_udp_encap_rcv;
    int (*)(struct sk_buff *, int, __be32, int) xfrm6_rcv_encap;
    struct neigh_table * nd_tbl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ipv6_stub {
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_join;
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_drop;
    struct dst_entry * (*)(struct net *, const struct sock *, struct flowi6 *, const struct in6_addr *) ipv6_dst_lookup_flow;
    int (*)(struct sk_buff *) ipv6_route_input;
    struct fib6_table * (*)(struct net *, u32) fib6_get_table;
    int (*)(struct net *, int, struct flowi6 *, struct fib6_result *, int) fib6_lookup;
    int (*)(struct net *, struct fib6_table *, int, struct flowi6 *, struct fib6_result *, int) fib6_table_lookup;
    void (*)(const struct net *, struct fib6_result *, struct flowi6 *, int, bool, const struct sk_buff *, int) fib6_select_path;
    u32 (*)(const struct fib6_result *, const struct in6_addr *, const struct in6_addr *) ip6_mtu_from_fib6;
    int (*)(struct net *, struct fib6_nh *, struct fib6_config *, gfp_t, struct netlink_ext_ack *) fib6_nh_init;
    void (*)(struct fib6_nh *) fib6_nh_release;
    void (*)(struct net *, struct fib6_info *) fib6_update_sernum;
    int (*)(struct net *, struct fib6_info *, bool) ip6_del_rt;
    void (*)(struct net *, struct fib6_info *, struct nl_info *) fib6_rt_update;
    void (*)() udpv6_encap_enable;
    void (*)(struct net_device *, const struct in6_addr *, const struct in6_addr *, bool, bool, bool, bool) ndisc_send_na;
    void (*)(struct sk_buff *, u32) xfrm6_local_rxpmtu;
    int (*)(struct sock *, struct sk_buff *) xfrm6_udp_encap_rcv;
    int (*)(struct sk_buff *, int, __be32, int) xfrm6_rcv_encap;
    struct neigh_table * nd_tbl;
    int (*)(struct net *, struct sock *, struct sk_buff *, int (*)(struct net *, struct sock *, struct sk_buff *)) ipv6_fragment;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ipv6_stub {
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_join;
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_drop;
    struct dst_entry * (*)(struct net *, const struct sock *, struct flowi6 *, const struct in6_addr *) ipv6_dst_lookup_flow;
    int (*)(struct sk_buff *) ipv6_route_input;
    struct fib6_table * (*)(struct net *, u32) fib6_get_table;
    int (*)(struct net *, int, struct flowi6 *, struct fib6_result *, int) fib6_lookup;
    int (*)(struct net *, struct fib6_table *, int, struct flowi6 *, struct fib6_result *, int) fib6_table_lookup;
    void (*)(const struct net *, struct fib6_result *, struct flowi6 *, int, bool, const struct sk_buff *, int) fib6_select_path;
    u32 (*)(const struct fib6_result *, const struct in6_addr *, const struct in6_addr *) ip6_mtu_from_fib6;
    int (*)(struct net *, struct fib6_nh *, struct fib6_config *, gfp_t, struct netlink_ext_ack *) fib6_nh_init;
    void (*)(struct fib6_nh *) fib6_nh_release;
    void (*)(struct net *, struct fib6_info *) fib6_update_sernum;
    int (*)(struct net *, struct fib6_info *, bool) ip6_del_rt;
    void (*)(struct net *, struct fib6_info *, struct nl_info *) fib6_rt_update;
    void (*)() udpv6_encap_enable;
    void (*)(struct net_device *, const struct in6_addr *, const struct in6_addr *, bool, bool, bool, bool) ndisc_send_na;
    void (*)(struct sk_buff *, u32) xfrm6_local_rxpmtu;
    int (*)(struct sock *, struct sk_buff *) xfrm6_udp_encap_rcv;
    int (*)(struct sk_buff *, int, __be32, int) xfrm6_rcv_encap;
    struct neigh_table * nd_tbl;
    int (*)(struct net *, struct sock *, struct sk_buff *, int (*)(struct net *, struct sock *, struct sk_buff *)) ipv6_fragment;
    struct net_device * (*)(struct net *, const struct in6_addr *, struct net_device *) ipv6_dev_find;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ipv6_stub {
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_join;
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_drop;
    struct dst_entry * (*)(struct net *, const struct sock *, struct flowi6 *, const struct in6_addr *) ipv6_dst_lookup_flow;
    int (*)(struct sk_buff *) ipv6_route_input;
    struct fib6_table * (*)(struct net *, u32) fib6_get_table;
    int (*)(struct net *, int, struct flowi6 *, struct fib6_result *, int) fib6_lookup;
    int (*)(struct net *, struct fib6_table *, int, struct flowi6 *, struct fib6_result *, int) fib6_table_lookup;
    void (*)(const struct net *, struct fib6_result *, struct flowi6 *, int, bool, const struct sk_buff *, int) fib6_select_path;
    u32 (*)(const struct fib6_result *, const struct in6_addr *, const struct in6_addr *) ip6_mtu_from_fib6;
    int (*)(struct net *, struct fib6_nh *, struct fib6_config *, gfp_t, struct netlink_ext_ack *) fib6_nh_init;
    void (*)(struct fib6_nh *) fib6_nh_release;
    void (*)(struct fib6_nh *) fib6_nh_release_dsts;
    void (*)(struct net *, struct fib6_info *) fib6_update_sernum;
    int (*)(struct net *, struct fib6_info *, bool) ip6_del_rt;
    void (*)(struct net *, struct fib6_info *, struct nl_info *) fib6_rt_update;
    void (*)() udpv6_encap_enable;
    void (*)(struct net_device *, const struct in6_addr *, const struct in6_addr *, bool, bool, bool, bool) ndisc_send_na;
    void (*)(struct sk_buff *, u32) xfrm6_local_rxpmtu;
    int (*)(struct sock *, struct sk_buff *) xfrm6_udp_encap_rcv;
    int (*)(struct sk_buff *, int, __be32, int) xfrm6_rcv_encap;
    struct neigh_table * nd_tbl;
    int (*)(struct net *, struct sock *, struct sk_buff *, int (*)(struct net *, struct sock *, struct sk_buff *)) ipv6_fragment;
    struct net_device * (*)(struct net *, const struct in6_addr *, struct net_device *) ipv6_dev_find;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ipv6_stub {
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_join;
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_drop;
    struct dst_entry * (*)(struct net *, const struct sock *, struct flowi6 *, const struct in6_addr *) ipv6_dst_lookup_flow;
    int (*)(struct sk_buff *) ipv6_route_input;
    struct fib6_table * (*)(struct net *, u32) fib6_get_table;
    int (*)(struct net *, int, struct flowi6 *, struct fib6_result *, int) fib6_lookup;
    int (*)(struct net *, struct fib6_table *, int, struct flowi6 *, struct fib6_result *, int) fib6_table_lookup;
    void (*)(const struct net *, struct fib6_result *, struct flowi6 *, int, bool, const struct sk_buff *, int) fib6_select_path;
    u32 (*)(const struct fib6_result *, const struct in6_addr *, const struct in6_addr *) ip6_mtu_from_fib6;
    int (*)(struct net *, struct fib6_nh *, struct fib6_config *, gfp_t, struct netlink_ext_ack *) fib6_nh_init;
    void (*)(struct fib6_nh *) fib6_nh_release;
    void (*)(struct fib6_nh *) fib6_nh_release_dsts;
    void (*)(struct net *, struct fib6_info *) fib6_update_sernum;
    int (*)(struct net *, struct fib6_info *, bool) ip6_del_rt;
    void (*)(struct net *, struct fib6_info *, struct nl_info *) fib6_rt_update;
    void (*)() udpv6_encap_enable;
    void (*)(struct net_device *, const struct in6_addr *, const struct in6_addr *, bool, bool, bool, bool) ndisc_send_na;
    void (*)(struct sk_buff *, u32) xfrm6_local_rxpmtu;
    int (*)(struct sock *, struct sk_buff *) xfrm6_udp_encap_rcv;
    int (*)(struct sk_buff *, int, __be32, int) xfrm6_rcv_encap;
    struct neigh_table * nd_tbl;
    int (*)(struct net *, struct sock *, struct sk_buff *, int (*)(struct net *, struct sock *, struct sk_buff *)) ipv6_fragment;
    struct net_device * (*)(struct net *, const struct in6_addr *, struct net_device *) ipv6_dev_find;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ipv6_stub {
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_join;
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_drop;
    struct dst_entry * (*)(struct net *, const struct sock *, struct flowi6 *, const struct in6_addr *) ipv6_dst_lookup_flow;
    int (*)(struct sk_buff *) ipv6_route_input;
    struct fib6_table * (*)(struct net *, u32) fib6_get_table;
    int (*)(struct net *, int, struct flowi6 *, struct fib6_result *, int) fib6_lookup;
    int (*)(struct net *, struct fib6_table *, int, struct flowi6 *, struct fib6_result *, int) fib6_table_lookup;
    void (*)(const struct net *, struct fib6_result *, struct flowi6 *, int, bool, const struct sk_buff *, int) fib6_select_path;
    u32 (*)(const struct fib6_result *, const struct in6_addr *, const struct in6_addr *) ip6_mtu_from_fib6;
    int (*)(struct net *, struct fib6_nh *, struct fib6_config *, gfp_t, struct netlink_ext_ack *) fib6_nh_init;
    void (*)(struct fib6_nh *) fib6_nh_release;
    void (*)(struct fib6_nh *) fib6_nh_release_dsts;
    void (*)(struct net *, struct fib6_info *) fib6_update_sernum;
    int (*)(struct net *, struct fib6_info *, bool) ip6_del_rt;
    void (*)(struct net *, struct fib6_info *, struct nl_info *) fib6_rt_update;
    void (*)() udpv6_encap_enable;
    void (*)(struct net_device *, const struct in6_addr *, const struct in6_addr *, bool, bool, bool, bool) ndisc_send_na;
    void (*)(struct sk_buff *, u32) xfrm6_local_rxpmtu;
    int (*)(struct sock *, struct sk_buff *) xfrm6_udp_encap_rcv;
    int (*)(struct sk_buff *, int, __be32, int) xfrm6_rcv_encap;
    struct neigh_table * nd_tbl;
    int (*)(struct net *, struct sock *, struct sk_buff *, int (*)(struct net *, struct sock *, struct sk_buff *)) ipv6_fragment;
    struct net_device * (*)(struct net *, const struct in6_addr *, struct net_device *) ipv6_dev_find;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ipv6_stub {
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_join;
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_drop;
    struct dst_entry * (*)(struct net *, const struct sock *, struct flowi6 *, const struct in6_addr *) ipv6_dst_lookup_flow;
    int (*)(struct sk_buff *) ipv6_route_input;
    struct fib6_table * (*)(struct net *, u32) fib6_get_table;
    int (*)(struct net *, int, struct flowi6 *, struct fib6_result *, int) fib6_lookup;
    int (*)(struct net *, struct fib6_table *, int, struct flowi6 *, struct fib6_result *, int) fib6_table_lookup;
    void (*)(const struct net *, struct fib6_result *, struct flowi6 *, int, bool, const struct sk_buff *, int) fib6_select_path;
    u32 (*)(const struct fib6_result *, const struct in6_addr *, const struct in6_addr *) ip6_mtu_from_fib6;
    int (*)(struct net *, struct fib6_nh *, struct fib6_config *, gfp_t, struct netlink_ext_ack *) fib6_nh_init;
    void (*)(struct fib6_nh *) fib6_nh_release;
    void (*)(struct fib6_nh *) fib6_nh_release_dsts;
    void (*)(struct net *, struct fib6_info *) fib6_update_sernum;
    int (*)(struct net *, struct fib6_info *, bool) ip6_del_rt;
    void (*)(struct net *, struct fib6_info *, struct nl_info *) fib6_rt_update;
    void (*)() udpv6_encap_enable;
    void (*)(struct net_device *, const struct in6_addr *, const struct in6_addr *, bool, bool, bool, bool) ndisc_send_na;
    void (*)(struct sk_buff *, u32) xfrm6_local_rxpmtu;
    int (*)(struct sock *, struct sk_buff *) xfrm6_udp_encap_rcv;
    int (*)(struct sk_buff *, int, __be32, int) xfrm6_rcv_encap;
    struct neigh_table * nd_tbl;
    int (*)(struct net *, struct sock *, struct sk_buff *, int (*)(struct net *, struct sock *, struct sk_buff *)) ipv6_fragment;
    struct net_device * (*)(struct net *, const struct in6_addr *, struct net_device *) ipv6_dev_find;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ipv6_stub {
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_join;
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_drop;
    struct dst_entry * (*)(struct net *, const struct sock *, struct flowi6 *, const struct in6_addr *) ipv6_dst_lookup_flow;
    int (*)(struct sk_buff *) ipv6_route_input;
    struct fib6_table * (*)(struct net *, u32) fib6_get_table;
    int (*)(struct net *, int, struct flowi6 *, struct fib6_result *, int) fib6_lookup;
    int (*)(struct net *, struct fib6_table *, int, struct flowi6 *, struct fib6_result *, int) fib6_table_lookup;
    void (*)(const struct net *, struct fib6_result *, struct flowi6 *, int, bool, const struct sk_buff *, int) fib6_select_path;
    u32 (*)(const struct fib6_result *, const struct in6_addr *, const struct in6_addr *) ip6_mtu_from_fib6;
    int (*)(struct net *, struct fib6_nh *, struct fib6_config *, gfp_t, struct netlink_ext_ack *) fib6_nh_init;
    void (*)(struct fib6_nh *) fib6_nh_release;
    void (*)(struct fib6_nh *) fib6_nh_release_dsts;
    void (*)(struct net *, struct fib6_info *) fib6_update_sernum;
    int (*)(struct net *, struct fib6_info *, bool) ip6_del_rt;
    void (*)(struct net *, struct fib6_info *, struct nl_info *) fib6_rt_update;
    void (*)() udpv6_encap_enable;
    void (*)(struct net_device *, const struct in6_addr *, const struct in6_addr *, bool, bool, bool, bool) ndisc_send_na;
    void (*)(struct sk_buff *, u32) xfrm6_local_rxpmtu;
    int (*)(struct sock *, struct sk_buff *) xfrm6_udp_encap_rcv;
    struct sk_buff * (*)(struct sock *, struct list_head *, struct sk_buff *) xfrm6_gro_udp_encap_rcv;
    int (*)(struct sk_buff *, int, __be32, int) xfrm6_rcv_encap;
    struct neigh_table * nd_tbl;
    int (*)(struct net *, struct sock *, struct sk_buff *, int (*)(struct net *, struct sock *, struct sk_buff *)) ipv6_fragment;
    struct net_device * (*)(struct net *, const struct in6_addr *, struct net_device *) ipv6_dev_find;
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
struct ipv6_stub {
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_join;
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_drop;
    struct dst_entry * (*)(struct net *, const struct sock *, struct flowi6 *, const struct in6_addr *) ipv6_dst_lookup_flow;
    int (*)(struct sk_buff *) ipv6_route_input;
    struct fib6_table * (*)(struct net *, u32) fib6_get_table;
    int (*)(struct net *, int, struct flowi6 *, struct fib6_result *, int) fib6_lookup;
    int (*)(struct net *, struct fib6_table *, int, struct flowi6 *, struct fib6_result *, int) fib6_table_lookup;
    void (*)(const struct net *, struct fib6_result *, struct flowi6 *, int, bool, const struct sk_buff *, int) fib6_select_path;
    u32 (*)(const struct fib6_result *, const struct in6_addr *, const struct in6_addr *) ip6_mtu_from_fib6;
    int (*)(struct net *, struct fib6_nh *, struct fib6_config *, gfp_t, struct netlink_ext_ack *) fib6_nh_init;
    void (*)(struct fib6_nh *) fib6_nh_release;
    void (*)(struct net *, struct fib6_info *) fib6_update_sernum;
    int (*)(struct net *, struct fib6_info *) ip6_del_rt;
    void (*)(struct net *, struct fib6_info *, struct nl_info *) fib6_rt_update;
    void (*)() udpv6_encap_enable;
    void (*)(struct net_device *, const struct in6_addr *, const struct in6_addr *, bool, bool, bool, bool) ndisc_send_na;
    struct neigh_table * nd_tbl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ipv6_stub {
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_join;
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_drop;
    struct dst_entry * (*)(struct net *, const struct sock *, struct flowi6 *, const struct in6_addr *) ipv6_dst_lookup_flow;
    int (*)(struct sk_buff *) ipv6_route_input;
    struct fib6_table * (*)(struct net *, u32) fib6_get_table;
    int (*)(struct net *, int, struct flowi6 *, struct fib6_result *, int) fib6_lookup;
    int (*)(struct net *, struct fib6_table *, int, struct flowi6 *, struct fib6_result *, int) fib6_table_lookup;
    void (*)(const struct net *, struct fib6_result *, struct flowi6 *, int, bool, const struct sk_buff *, int) fib6_select_path;
    u32 (*)(const struct fib6_result *, const struct in6_addr *, const struct in6_addr *) ip6_mtu_from_fib6;
    int (*)(struct net *, struct fib6_nh *, struct fib6_config *, gfp_t, struct netlink_ext_ack *) fib6_nh_init;
    void (*)(struct fib6_nh *) fib6_nh_release;
    void (*)(struct net *, struct fib6_info *) fib6_update_sernum;
    int (*)(struct net *, struct fib6_info *) ip6_del_rt;
    void (*)(struct net *, struct fib6_info *, struct nl_info *) fib6_rt_update;
    void (*)() udpv6_encap_enable;
    void (*)(struct net_device *, const struct in6_addr *, const struct in6_addr *, bool, bool, bool, bool) ndisc_send_na;
    struct neigh_table * nd_tbl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ipv6_stub {
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_join;
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_drop;
    struct dst_entry * (*)(struct net *, const struct sock *, struct flowi6 *, const struct in6_addr *) ipv6_dst_lookup_flow;
    int (*)(struct sk_buff *) ipv6_route_input;
    struct fib6_table * (*)(struct net *, u32) fib6_get_table;
    int (*)(struct net *, int, struct flowi6 *, struct fib6_result *, int) fib6_lookup;
    int (*)(struct net *, struct fib6_table *, int, struct flowi6 *, struct fib6_result *, int) fib6_table_lookup;
    void (*)(const struct net *, struct fib6_result *, struct flowi6 *, int, bool, const struct sk_buff *, int) fib6_select_path;
    u32 (*)(const struct fib6_result *, const struct in6_addr *, const struct in6_addr *) ip6_mtu_from_fib6;
    int (*)(struct net *, struct fib6_nh *, struct fib6_config *, gfp_t, struct netlink_ext_ack *) fib6_nh_init;
    void (*)(struct fib6_nh *) fib6_nh_release;
    void (*)(struct net *, struct fib6_info *) fib6_update_sernum;
    int (*)(struct net *, struct fib6_info *) ip6_del_rt;
    void (*)(struct net *, struct fib6_info *, struct nl_info *) fib6_rt_update;
    void (*)() udpv6_encap_enable;
    void (*)(struct net_device *, const struct in6_addr *, const struct in6_addr *, bool, bool, bool, bool) ndisc_send_na;
    struct neigh_table * nd_tbl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ipv6_stub {
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_join;
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_drop;
    struct dst_entry * (*)(struct net *, const struct sock *, struct flowi6 *, const struct in6_addr *) ipv6_dst_lookup_flow;
    int (*)(struct sk_buff *) ipv6_route_input;
    struct fib6_table * (*)(struct net *, u32) fib6_get_table;
    int (*)(struct net *, int, struct flowi6 *, struct fib6_result *, int) fib6_lookup;
    int (*)(struct net *, struct fib6_table *, int, struct flowi6 *, struct fib6_result *, int) fib6_table_lookup;
    void (*)(const struct net *, struct fib6_result *, struct flowi6 *, int, bool, const struct sk_buff *, int) fib6_select_path;
    u32 (*)(const struct fib6_result *, const struct in6_addr *, const struct in6_addr *) ip6_mtu_from_fib6;
    int (*)(struct net *, struct fib6_nh *, struct fib6_config *, gfp_t, struct netlink_ext_ack *) fib6_nh_init;
    void (*)(struct fib6_nh *) fib6_nh_release;
    void (*)(struct net *, struct fib6_info *) fib6_update_sernum;
    int (*)(struct net *, struct fib6_info *) ip6_del_rt;
    void (*)(struct net *, struct fib6_info *, struct nl_info *) fib6_rt_update;
    void (*)() udpv6_encap_enable;
    void (*)(struct net_device *, const struct in6_addr *, const struct in6_addr *, bool, bool, bool, bool) ndisc_send_na;
    struct neigh_table * nd_tbl;
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
struct ipv6_stub {
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_join;
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_drop;
    struct dst_entry * (*)(struct net *, const struct sock *, struct flowi6 *, const struct in6_addr *) ipv6_dst_lookup_flow;
    int (*)(struct sk_buff *) ipv6_route_input;
    struct fib6_table * (*)(struct net *, u32) fib6_get_table;
    int (*)(struct net *, int, struct flowi6 *, struct fib6_result *, int) fib6_lookup;
    int (*)(struct net *, struct fib6_table *, int, struct flowi6 *, struct fib6_result *, int) fib6_table_lookup;
    void (*)(const struct net *, struct fib6_result *, struct flowi6 *, int, bool, const struct sk_buff *, int) fib6_select_path;
    u32 (*)(const struct fib6_result *, const struct in6_addr *, const struct in6_addr *) ip6_mtu_from_fib6;
    int (*)(struct net *, struct fib6_nh *, struct fib6_config *, gfp_t, struct netlink_ext_ack *) fib6_nh_init;
    void (*)(struct fib6_nh *) fib6_nh_release;
    void (*)(struct net *, struct fib6_info *) fib6_update_sernum;
    int (*)(struct net *, struct fib6_info *) ip6_del_rt;
    void (*)(struct net *, struct fib6_info *, struct nl_info *) fib6_rt_update;
    void (*)() udpv6_encap_enable;
    void (*)(struct net_device *, const struct in6_addr *, const struct in6_addr *, bool, bool, bool, bool) ndisc_send_na;
    struct neigh_table * nd_tbl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ipv6_stub {
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_join;
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_drop;
    struct dst_entry * (*)(struct net *, const struct sock *, struct flowi6 *, const struct in6_addr *) ipv6_dst_lookup_flow;
    int (*)(struct sk_buff *) ipv6_route_input;
    struct fib6_table * (*)(struct net *, u32) fib6_get_table;
    int (*)(struct net *, int, struct flowi6 *, struct fib6_result *, int) fib6_lookup;
    int (*)(struct net *, struct fib6_table *, int, struct flowi6 *, struct fib6_result *, int) fib6_table_lookup;
    void (*)(const struct net *, struct fib6_result *, struct flowi6 *, int, bool, const struct sk_buff *, int) fib6_select_path;
    u32 (*)(const struct fib6_result *, const struct in6_addr *, const struct in6_addr *) ip6_mtu_from_fib6;
    int (*)(struct net *, struct fib6_nh *, struct fib6_config *, gfp_t, struct netlink_ext_ack *) fib6_nh_init;
    void (*)(struct fib6_nh *) fib6_nh_release;
    void (*)(struct net *, struct fib6_info *) fib6_update_sernum;
    int (*)(struct net *, struct fib6_info *) ip6_del_rt;
    void (*)(struct net *, struct fib6_info *, struct nl_info *) fib6_rt_update;
    void (*)() udpv6_encap_enable;
    void (*)(struct net_device *, const struct in6_addr *, const struct in6_addr *, bool, bool, bool, bool) ndisc_send_na;
    struct neigh_table * nd_tbl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ipv6_stub {
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_join;
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_drop;
    struct dst_entry * (*)(struct net *, const struct sock *, struct flowi6 *, const struct in6_addr *) ipv6_dst_lookup_flow;
    int (*)(struct sk_buff *) ipv6_route_input;
    struct fib6_table * (*)(struct net *, u32) fib6_get_table;
    int (*)(struct net *, int, struct flowi6 *, struct fib6_result *, int) fib6_lookup;
    int (*)(struct net *, struct fib6_table *, int, struct flowi6 *, struct fib6_result *, int) fib6_table_lookup;
    void (*)(const struct net *, struct fib6_result *, struct flowi6 *, int, bool, const struct sk_buff *, int) fib6_select_path;
    u32 (*)(const struct fib6_result *, const struct in6_addr *, const struct in6_addr *) ip6_mtu_from_fib6;
    int (*)(struct net *, struct fib6_nh *, struct fib6_config *, gfp_t, struct netlink_ext_ack *) fib6_nh_init;
    void (*)(struct fib6_nh *) fib6_nh_release;
    void (*)(struct net *, struct fib6_info *) fib6_update_sernum;
    int (*)(struct net *, struct fib6_info *) ip6_del_rt;
    void (*)(struct net *, struct fib6_info *, struct nl_info *) fib6_rt_update;
    void (*)() udpv6_encap_enable;
    void (*)(struct net_device *, const struct in6_addr *, const struct in6_addr *, bool, bool, bool, bool) ndisc_send_na;
    struct neigh_table * nd_tbl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ipv6_stub {
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_join;
    int (*)(struct sock *, int, const struct in6_addr *) ipv6_sock_mc_drop;
    struct dst_entry * (*)(struct net *, const struct sock *, struct flowi6 *, const struct in6_addr *) ipv6_dst_lookup_flow;
    int (*)(struct sk_buff *) ipv6_route_input;
    struct fib6_table * (*)(struct net *, u32) fib6_get_table;
    int (*)(struct net *, int, struct flowi6 *, struct fib6_result *, int) fib6_lookup;
    int (*)(struct net *, struct fib6_table *, int, struct flowi6 *, struct fib6_result *, int) fib6_table_lookup;
    void (*)(const struct net *, struct fib6_result *, struct flowi6 *, int, bool, const struct sk_buff *, int) fib6_select_path;
    u32 (*)(const struct fib6_result *, const struct in6_addr *, const struct in6_addr *) ip6_mtu_from_fib6;
    int (*)(struct net *, struct fib6_nh *, struct fib6_config *, gfp_t, struct netlink_ext_ack *) fib6_nh_init;
    void (*)(struct fib6_nh *) fib6_nh_release;
    void (*)(struct net *, struct fib6_info *) fib6_update_sernum;
    int (*)(struct net *, struct fib6_info *) ip6_del_rt;
    void (*)(struct net *, struct fib6_info *, struct nl_info *) fib6_rt_update;
    void (*)() udpv6_encap_enable;
    void (*)(struct net_device *, const struct in6_addr *, const struct in6_addr *, bool, bool, bool, bool) ndisc_send_na;
    struct neigh_table * nd_tbl;
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct fib6_table * (*)(struct net *, u32) fib6_get_table</code>
</li>
<li>
<b>Field added. </b>
<code>struct fib6_info * (*)(struct net *, int, struct flowi6 *, int) fib6_lookup</code>
</li>
<li>
<b>Field added. </b>
<code>struct fib6_info * (*)(struct net *, struct fib6_table *, int, struct flowi6 *, int) fib6_table_lookup</code>
</li>
<li>
<b>Field added. </b>
<code>struct fib6_info * (*)(const struct net *, struct fib6_info *, struct flowi6 *, int, const struct sk_buff *, int) fib6_multipath_select</code>
</li>
<li>
<b>Field added. </b>
<code>u32 (*)(struct fib6_info *, struct in6_addr *, struct in6_addr *) ip6_mtu_from_fib6</code>
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
<code>int (*)(struct sk_buff *) ipv6_route_input</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(const struct net *, struct fib6_result *, struct flowi6 *, int, bool, const struct sk_buff *, int) fib6_select_path</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct net *, struct fib6_nh *, struct fib6_config *, gfp_t, struct netlink_ext_ack *) fib6_nh_init</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct fib6_nh *) fib6_nh_release</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct net *, struct fib6_info *) fib6_update_sernum</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct net *, struct fib6_info *) ip6_del_rt</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct net *, struct fib6_info *, struct nl_info *) fib6_rt_update</code>
</li>
<li>
<b>Field removed. </b>
<code>struct fib6_info * (*)(const struct net *, struct fib6_info *, struct flowi6 *, int, const struct sk_buff *, int) fib6_multipath_select</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct fib6_info * (*)(struct net *, int, struct flowi6 *, int) fib6_lookup</code> ➡️ <code>int (*)(struct net *, int, struct flowi6 *, struct fib6_result *, int) fib6_lookup</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct fib6_info * (*)(struct net *, struct fib6_table *, int, struct flowi6 *, int) fib6_table_lookup</code> ➡️ <code>int (*)(struct net *, struct fib6_table *, int, struct flowi6 *, struct fib6_result *, int) fib6_table_lookup</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32 (*)(struct fib6_info *, struct in6_addr *, struct in6_addr *) ip6_mtu_from_fib6</code> ➡️ <code>u32 (*)(const struct fib6_result *, const struct in6_addr *, const struct in6_addr *) ip6_mtu_from_fib6</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct dst_entry * (*)(struct net *, const struct sock *, struct flowi6 *, const struct in6_addr *) ipv6_dst_lookup_flow</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct net *, struct sock *, struct dst_entry * *, struct flowi6 *) ipv6_dst_lookup</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct sk_buff *, u32) xfrm6_local_rxpmtu</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct sock *, struct sk_buff *) xfrm6_udp_encap_rcv</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct sk_buff *, int, __be32, int) xfrm6_rcv_encap</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct net *, struct fib6_info *) ip6_del_rt</code> ➡️ <code>int (*)(struct net *, struct fib6_info *, bool) ip6_del_rt</code>
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
<code>int (*)(struct net *, struct sock *, struct sk_buff *, int (*)(struct net *, struct sock *, struct sk_buff *)) ipv6_fragment</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct net_device * (*)(struct net *, const struct in6_addr *, struct net_device *) ipv6_dev_find</code>
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
<code>void (*)(struct fib6_nh *) fib6_nh_release_dsts</code>
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
<code>struct sk_buff * (*)(struct sock *, struct list_head *, struct sk_buff *) xfrm6_gro_udp_encap_rcv</code>
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
