# Function: <code>__dev_get_by_index</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * __dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "__dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586264544,
      "name": "__dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:798",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_new_index",
        "net/core/dev.c:register_netdevice"
      ],
      "caller_func": [
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_ctl_tfilter",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/mcast.c:ipv6_sock_mc_join",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:ipv6_sock_mc_close",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586264544,
      "name": "__dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * __dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "__dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586738689,
      "name": "__dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:802",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_new_index"
      ],
      "caller_func": [
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_ctl_tfilter",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/mcast.c:ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:ipv6_sock_mc_join",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586689664,
      "name": "__dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * __dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "__dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586924481,
      "name": "__dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:801",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_new_index"
      ],
      "caller_func": [
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_ctl_tfilter",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:ipv6_sock_mc_join",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586875616,
      "name": "__dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * __dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "__dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587050508,
      "name": "__dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:808",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_new_index"
      ],
      "caller_func": [
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_ctl_tfilter",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/addrlabel.c:ip6addrlbl_newdel",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:ipv6_sock_mc_join",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587000112,
      "name": "__dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * __dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "__dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587551231,
      "name": "__dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:811",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_new_index"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_prog_offload_init",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_ctl_tfilter",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:ipv6_sock_mc_join",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587498752,
      "name": "__dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * __dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "__dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587823031,
      "name": "__dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:811",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_new_index"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/fib_semantics.c:fib_check_nh",
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587803440,
      "name": "__dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * __dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "__dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587956512,
      "name": "__dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:813",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_new_index"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/fib_frontend.c:ip_valid_fib_dump_req",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587938672,
      "name": "__dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * __dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "__dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588271216,
      "name": "__dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:809",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_new_index"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/fib_frontend.c:ip_valid_fib_dump_req",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588248144,
      "name": "__dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * __dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "__dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588477586,
      "name": "__dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:727",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_new_index"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/fib_frontend.c:ip_valid_fib_dump_req",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588452304,
      "name": "__dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * __dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "__dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589350456,
      "name": "__dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:925",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:do_set_master",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv4/devinet.c:rtm_to_ifaddr",
        "net/ipv4/fib_frontend.c:ip_valid_fib_dump_req",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/anycast.c:__ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/packet/af_packet.c:packet_mc_drop",
        "net/packet/af_packet.c:packet_mc_add",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:init_prb_bdqc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589320480,
      "name": "__dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * __dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "__dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589352024,
      "name": "__dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:928",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:do_set_master",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv4/devinet.c:rtm_to_ifaddr",
        "net/ipv4/fib_frontend.c:ip_valid_fib_dump_req",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/anycast.c:__ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/packet/af_packet.c:packet_mc_drop",
        "net/packet/af_packet.c:packet_mc_add",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:init_prb_bdqc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589319488,
      "name": "__dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * __dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "__dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589254251,
      "name": "__dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:976",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:do_set_master",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv4/devinet.c:rtm_to_ifaddr",
        "net/ipv4/fib_frontend.c:ip_valid_fib_dump_req",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/anycast.c:__ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rtnl",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_mc_add",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589215152,
      "name": "__dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * __dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "__dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589979787,
      "name": "__dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:852",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:do_set_master",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv4/devinet.c:rtm_to_ifaddr",
        "net/ipv4/fib_frontend.c:ip_valid_fib_dump_req",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/anycast.c:__ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rtnl",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_mc_add",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589938256,
      "name": "__dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * __dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "__dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591523129,
      "name": "__dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:799",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_stats_set",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:do_set_master",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv4/fib_frontend.c:ip_valid_fib_dump_req",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/anycast.c:__ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rtnl",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_mc_add",
        "net/packet/af_packet.c:packet_release",
        "net/mctp/device.c:mctp_rtm_deladdr",
        "net/mctp/device.c:mctp_rtm_newaddr",
        "net/mctp/neigh.c:mctp_rtm_delneigh",
        "net/mctp/neigh.c:mctp_rtm_newneigh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591471152,
      "name": "__dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * __dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "__dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593296697,
      "name": "__dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:799",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_stats_set",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:do_set_master",
        "net/core/link_watch.c:rfc2863_policy",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv4/fib_frontend.c:ip_valid_fib_dump_req",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/anycast.c:__ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rtnl",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_mc_add",
        "net/packet/af_packet.c:packet_release",
        "net/mctp/device.c:mctp_rtm_deladdr",
        "net/mctp/device.c:mctp_rtm_newaddr",
        "net/mctp/neigh.c:mctp_rtm_delneigh",
        "net/mctp/neigh.c:mctp_rtm_newneigh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593240240,
      "name": "__dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * __dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "__dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593756409,
      "name": "__dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:811",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_mdb_del",
        "net/core/rtnetlink.c:rtnl_mdb_add",
        "net/core/rtnetlink.c:rtnl_stats_set",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:do_set_master",
        "net/core/link_watch.c:rfc2863_policy",
        "net/core/netdev-genl.c:netdev_nl_dev_get_doit",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv4/fib_frontend.c:ip_valid_fib_dump_req",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/anycast.c:__ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rtnl",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_mc_add",
        "net/packet/af_packet.c:packet_release",
        "net/mctp/device.c:mctp_rtm_deladdr",
        "net/mctp/device.c:mctp_rtm_newaddr",
        "net/mctp/neigh.c:mctp_rtm_delneigh",
        "net/mctp/neigh.c:mctp_rtm_newneigh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593701008,
      "name": "__dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct net_device * __dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "__dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594479376,
      "name": "__dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:828",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "kernel/bpf/tcx.c:tcx_link_attach",
        "kernel/bpf/tcx.c:tcx_prog_query",
        "kernel/bpf/tcx.c:tcx_prog_detach",
        "kernel/bpf/tcx.c:tcx_prog_attach",
        "drivers/net/netkit.c:netkit_dev_fetch",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_mdb_del",
        "net/core/rtnetlink.c:rtnl_mdb_add",
        "net/core/rtnetlink.c:rtnl_mdb_get",
        "net/core/rtnetlink.c:rtnl_stats_set",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:do_set_master",
        "net/core/link_watch.c:rfc2863_policy",
        "net/core/netdev-genl.c:netdev_nl_queue_get_dumpit",
        "net/core/netdev-genl.c:netdev_nl_queue_get_doit",
        "net/core/netdev-genl.c:netdev_nl_napi_get_dumpit",
        "net/core/netdev-genl.c:netdev_nl_dev_get_doit",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv4/fib_frontend.c:ip_valid_fib_dump_req",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/anycast.c:__ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ip6_mc_find_dev_rtnl",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_mc_add",
        "net/packet/af_packet.c:packet_release",
        "net/mctp/device.c:mctp_rtm_deladdr",
        "net/mctp/device.c:mctp_rtm_newaddr",
        "net/mctp/neigh.c:mctp_rtm_delneigh",
        "net/mctp/neigh.c:mctp_rtm_newneigh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594479376,
      "name": "__dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct net_device * __dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "__dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502005620,
      "name": "__dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:727",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_new_index"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/fib_frontend.c:ip_valid_fib_dump_req",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501976600,
      "name": "__dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct net_device * __dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "__dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234761136,
      "name": "__dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:727",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_new_index"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/fib_frontend.c:ip_valid_fib_dump_req",
        "net/ipv4/fib_semantics.c:fib_check_nh",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234731060,
      "name": "__dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct net_device * __dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "__dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295446344,
      "name": "__dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:727",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_new_index"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/fib_frontend.c:ip_valid_fib_dump_req",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295404544,
      "name": "__dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct net_device * __dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "__dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278296192,
      "name": "__dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:727",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_new_index"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/fib_frontend.c:ip_valid_fib_dump_req",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278275436,
      "name": "__dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * __dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "__dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588084370,
      "name": "__dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:727",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_new_index"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/fib_frontend.c:ip_valid_fib_dump_req",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588059088,
      "name": "__dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * __dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "__dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587797938,
      "name": "__dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:727",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_new_index"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "drivers/net/vxlan.c:__vxlan_dev_create",
        "drivers/net/vxlan.c:vxlan_config_validate",
        "drivers/net/vxlan.c:vxlan_change_mtu",
        "drivers/net/vxlan.c:vxlan_fdb_parse",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/fib_frontend.c:ip_valid_fib_dump_req",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv4/ip_tunnel.c:ip_tunnel_bind_dev",
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587772176,
      "name": "__dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * __dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "__dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588416146,
      "name": "__dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:727",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_new_index"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/fib_frontend.c:ip_valid_fib_dump_req",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588390864,
      "name": "__dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct net_device * __dev_get_by_index(struct net * net, int ifindex)
```

```json
{
  "name": "__dev_get_by_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588554786,
      "name": "__dev_get_by_index",
      "external": true,
      "loc": "net/core/dev.c:727",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:dev_new_index"
      ],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_map_offload_map_alloc",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_add",
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/ipv4/route.c:ip_error",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/fib_frontend.c:ip_valid_fib_dump_req",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv4/ipmr.c:ipmr_rtm_route",
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/anycast.c:ipv6_sock_ac_drop",
        "net/ipv6/anycast.c:ipv6_sock_ac_join",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_addr_del",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop",
        "net/ipv6/mcast.c:__ipv6_sock_mc_join",
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588526736,
      "name": "__dev_get_by_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
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
