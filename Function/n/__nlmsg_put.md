# Function: <code>__nlmsg_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct nlmsghdr * __nlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, int type, int len, int flags)
```

```json
{
  "name": "__nlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586489392,
      "name": "__nlmsg_put",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2759",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:audit_make_reply",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/cls_api.c:tcf_fill_node",
        "net/sched/act_api.c:tca_action_flush",
        "net/sched/act_api.c:tc_dump_action",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/genetlink.c:genlmsg_put",
        "net/ipv4/devinet.c:inet_fill_ifaddr",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586489392,
      "name": "__nlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct nlmsghdr * __nlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, int type, int len, int flags)
```

```json
{
  "name": "__nlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586935984,
      "name": "__nlmsg_put",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2034",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:audit_make_reply",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/cls_api.c:tcf_fill_node",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_flush",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/genetlink.c:genlmsg_put",
        "net/ipv4/devinet.c:inet_fill_ifaddr",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep",
        "net/switchdev/switchdev.c:switchdev_port_fdb_dump_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586935984,
      "name": "__nlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct nlmsghdr * __nlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, int type, int len, int flags)
```

```json
{
  "name": "__nlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587131216,
      "name": "__nlmsg_put",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2051",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_make_reply",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/cls_api.c:tcf_fill_node",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_flush",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/genetlink.c:genlmsg_put",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_fill_ifaddr",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep",
        "net/switchdev/switchdev.c:switchdev_port_fdb_dump_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587131216,
      "name": "__nlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct nlmsghdr * __nlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, int type, int len, int flags)
```

```json
{
  "name": "__nlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587261616,
      "name": "__nlmsg_put",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2102",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_make_reply",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/cls_api.c:tcf_fill_node",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_flush",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/genetlink.c:genlmsg_put",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep",
        "net/switchdev/switchdev.c:switchdev_port_fdb_dump_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587261616,
      "name": "__nlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct nlmsghdr * __nlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, int type, int len, int flags)
```

```json
{
  "name": "__nlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587781008,
      "name": "__nlmsg_put",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2115",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_make_reply",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/cls_api.c:tcf_fill_node",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_flush",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/genetlink.c:genlmsg_put",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587781008,
      "name": "__nlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct nlmsghdr * __nlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, int type, int len, int flags)
```

```json
{
  "name": "__nlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588123440,
      "name": "__nlmsg_put",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2156",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_make_reply",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/cls_api.c:tcf_fill_node",
        "net/sched/act_api.c:tc_dump_action",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/genetlink.c:genlmsg_put",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588123440,
      "name": "__nlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct nlmsghdr * __nlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, int type, int len, int flags)
```

```json
{
  "name": "__nlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588305696,
      "name": "__nlmsg_put",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2165",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_make_reply",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/net_namespace.c:rtnl_net_fill",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/cls_api.c:tc_chain_fill_node",
        "net/sched/cls_api.c:tcf_fill_node",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_gd",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/genetlink.c:genlmsg_put",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588305696,
      "name": "__nlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct nlmsghdr * __nlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, int type, int len, int flags)
```

```json
{
  "name": "__nlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588703600,
      "name": "__nlmsg_put",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2165",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_make_reply",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/net_namespace.c:rtnl_net_fill",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/cls_api.c:tc_chain_fill_node",
        "net/sched/cls_api.c:tcf_fill_node",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_gd",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/genetlink.c:genlmsg_put",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588703600,
      "name": "__nlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct nlmsghdr * __nlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, int type, int len, int flags)
```

```json
{
  "name": "__nlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588927472,
      "name": "__nlmsg_put",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2166",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_make_reply",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/net_namespace.c:rtnl_net_fill",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/cls_api.c:tc_chain_fill_node",
        "net/sched/cls_api.c:tcf_fill_node",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_gd",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/genetlink.c:genlmsg_put",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588927472,
      "name": "__nlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
struct nlmsghdr * __nlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, int type, int len, int flags)
```

```json
{
  "name": "__nlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589822538,
      "name": "__nlmsg_put",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2166",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_dump"
      ],
      "caller_func": [
        "kernel/audit.c:audit_buffer_alloc",
        "kernel/audit.c:audit_make_reply",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/net_namespace.c:rtnl_net_fill",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/fib_rules.c:fib_nl_fill_rule",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/cls_api.c:tc_chain_fill_node",
        "net/sched/cls_api.c:tcf_fill_node",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_flush",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/genetlink.c:genlmsg_put",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:inet6_fill_ifacaddr",
        "net/ipv6/addrconf.c:inet6_fill_ifmcaddr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_ra_useropt",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep",
        "net/dcb/dcbnl.c:dcbnl_newmsg",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589816272,
      "name": "__nlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
struct nlmsghdr * __nlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, int type, int len, int flags)
```

```json
{
  "name": "__nlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589856424,
      "name": "__nlmsg_put",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2167",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_dump_done"
      ],
      "caller_func": [
        "kernel/audit.c:audit_buffer_alloc",
        "kernel/audit.c:audit_make_reply",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/net_namespace.c:rtnl_net_fill",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/fib_rules.c:fib_nl_fill_rule",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/cls_api.c:tc_chain_fill_node",
        "net/sched/cls_api.c:tcf_fill_node",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_flush",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/genetlink.c:ctrl_dumppolicy_prep",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:inet6_fill_ifacaddr",
        "net/ipv6/addrconf.c:inet6_fill_ifmcaddr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_ra_useropt",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep",
        "net/dcb/dcbnl.c:dcbnl_newmsg",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589852448,
      "name": "__nlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
struct nlmsghdr * __nlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, int type, int len, int flags)
```

```json
{
  "name": "__nlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589762049,
      "name": "__nlmsg_put",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2177",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_dump_done"
      ],
      "caller_func": [
        "kernel/audit.c:audit_make_reply",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/net_namespace.c:rtnl_net_fill",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/fib_rules.c:fib_nl_fill_rule",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/cls_api.c:tc_chain_fill_node",
        "net/sched/cls_api.c:tcf_fill_node",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_flush",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/genetlink.c:ctrl_dumppolicy_prep",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifacaddr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_ra_useropt",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep",
        "net/dcb/dcbnl.c:dcbnl_newmsg",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589758208,
      "name": "__nlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
struct nlmsghdr * __nlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, int type, int len, int flags)
```

```json
{
  "name": "__nlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590521265,
      "name": "__nlmsg_put",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2188",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_dump_done"
      ],
      "caller_func": [
        "kernel/audit.c:audit_make_reply",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "drivers/net/wwan/wwan_core.c:wwan_create_default_link",
        "net/core/net_namespace.c:rtnl_net_fill",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/fib_rules.c:fib_nl_fill_rule",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/cls_api.c:tc_chain_fill_node",
        "net/sched/cls_api.c:tcf_fill_node",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_flush",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/genetlink.c:ctrl_dumppolicy_prep",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifacaddr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_ra_useropt",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep",
        "net/dcb/dcbnl.c:dcbnl_newmsg",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590517360,
      "name": "__nlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
struct nlmsghdr * __nlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, int type, int len, int flags)
```

```json
{
  "name": "__nlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592129894,
      "name": "__nlmsg_put",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2167",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_dump_done"
      ],
      "caller_func": [
        "kernel/audit.c:audit_buffer_aux_new",
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:audit_make_reply",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "drivers/net/wwan/wwan_core.c:wwan_create_default_link",
        "net/core/net_namespace.c:rtnl_net_fill",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/fib_rules.c:fib_nl_fill_rule",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/cls_api.c:tc_chain_fill_node",
        "net/sched/cls_api.c:tcf_fill_node",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_flush",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/genetlink.c:genlmsg_put",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifacaddr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_ra_useropt",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep",
        "net/dcb/dcbnl.c:dcbnl_newmsg",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err",
        "net/mctp/device.c:mctp_fill_addrinfo",
        "net/mctp/neigh.c:mctp_rtm_getneigh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592124976,
      "name": "__nlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
struct nlmsghdr * __nlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, int type, int len, int flags)
```

```json
{
  "name": "__nlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593969533,
      "name": "__nlmsg_put",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2188",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_dump_done"
      ],
      "caller_func": [
        "kernel/audit.c:audit_buffer_aux_new",
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:audit_make_reply",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "drivers/net/wwan/wwan_core.c:wwan_create_default_link",
        "net/core/net_namespace.c:rtnl_net_fill",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/fib_rules.c:fib_nl_fill_rule",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/cls_api.c:tc_chain_fill_node",
        "net/sched/cls_api.c:tcf_fill_node",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_flush",
        "net/netlink/genetlink.c:genlmsg_put",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifacaddr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_ra_useropt",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep",
        "net/dcb/dcbnl.c:dcbnl_newmsg",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err",
        "net/mctp/device.c:mctp_fill_addrinfo",
        "net/mctp/neigh.c:mctp_rtm_getneigh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593947920,
      "name": "__nlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
struct nlmsghdr * __nlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, int type, int len, int flags)
```

```json
{
  "name": "__nlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594346461,
      "name": "__nlmsg_put",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2159",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_dump_done"
      ],
      "caller_func": [
        "kernel/audit.c:audit_buffer_aux_new",
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:audit_make_reply",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "drivers/net/wwan/wwan_core.c:wwan_create_default_link",
        "net/core/net_namespace.c:rtnl_net_fill",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/fib_rules.c:fib_nl_fill_rule",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/cls_api.c:tc_chain_fill_node",
        "net/sched/cls_api.c:tcf_fill_node",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_flush",
        "net/netlink/genetlink.c:genlmsg_put",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifacaddr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_ra_useropt",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/devlink/leftover.c:devlink_nl_cmd_dpipe_entries_get",
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep",
        "net/dcb/dcbnl.c:dcbnl_newmsg",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err",
        "net/mctp/device.c:mctp_fill_addrinfo",
        "net/mctp/neigh.c:mctp_rtm_getneigh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594324224,
      "name": "__nlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nlmsghdr * __nlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, int type, int len, int flags)
```

```json
{
  "name": "__nlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595145961,
      "name": "__nlmsg_put",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2154",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_dump_done"
      ],
      "caller_func": [
        "kernel/audit.c:audit_buffer_aux_new",
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:audit_make_reply",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/net_namespace.c:rtnl_net_fill",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/fib_rules.c:fib_nl_fill_rule",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/cls_api.c:tc_chain_fill_node",
        "net/sched/cls_api.c:tcf_fill_node",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_flush",
        "net/netlink/genetlink.c:genlmsg_put",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifacaddr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_ra_useropt",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/devlink/dpipe.c:devlink_nl_dpipe_entries_get_doit",
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep",
        "net/dcb/dcbnl.c:dcbnl_newmsg",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err",
        "net/mctp/device.c:mctp_fill_addrinfo",
        "net/mctp/neigh.c:mctp_rtm_getneigh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595123792,
      "name": "__nlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct nlmsghdr * __nlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, int type, int len, int flags)
```

```json
{
  "name": "__nlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502521032,
      "name": "__nlmsg_put",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2166",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_make_reply",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/net_namespace.c:rtnl_net_fill",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_gd",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/genetlink.c:genlmsg_put",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502521032,
      "name": "__nlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct nlmsghdr * __nlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, int type, int len, int flags)
```

```json
{
  "name": "__nlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235231856,
      "name": "__nlmsg_put",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2166",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_make_reply",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/net_namespace.c:rtnl_net_fill",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/fib_rules.c:fib_nl_fill_rule",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/cls_api.c:tc_chain_fill_node",
        "net/sched/cls_api.c:tcf_fill_node",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_flush",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/genetlink.c:genlmsg_put",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235231856,
      "name": "__nlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct nlmsghdr * __nlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, int type, int len, int flags)
```

```json
{
  "name": "__nlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296093680,
      "name": "__nlmsg_put",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2166",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_make_reply",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/net_namespace.c:rtnl_net_fill",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/cls_api.c:tc_chain_fill_node",
        "net/sched/cls_api.c:tcf_fill_node",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_gd",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/genetlink.c:genlmsg_put",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep",
        "net/dcb/dcbnl.c:dcbnl_newmsg",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296093680,
      "name": "__nlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct nlmsghdr * __nlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, int type, int len, int flags)
```

```json
{
  "name": "__nlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278691814,
      "name": "__nlmsg_put",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2166",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_make_reply",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/net_namespace.c:rtnl_net_fill",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/cls_api.c:tc_chain_fill_node",
        "net/sched/cls_api.c:tcf_fill_node",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_gd",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/genetlink.c:genlmsg_put",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278691814,
      "name": "__nlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct nlmsghdr * __nlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, int type, int len, int flags)
```

```json
{
  "name": "__nlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588533856,
      "name": "__nlmsg_put",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2166",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_make_reply",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/net_namespace.c:rtnl_net_fill",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/cls_api.c:tc_chain_fill_node",
        "net/sched/cls_api.c:tcf_fill_node",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_gd",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/genetlink.c:genlmsg_put",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588533856,
      "name": "__nlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct nlmsghdr * __nlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, int type, int len, int flags)
```

```json
{
  "name": "__nlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588245856,
      "name": "__nlmsg_put",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2166",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_make_reply",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "drivers/scsi/scsi_transport_fc.c:fc_host_post_fc_event",
        "drivers/net/vxlan.c:vxlan_fdb_info",
        "net/core/net_namespace.c:rtnl_net_fill",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/cls_api.c:tc_chain_fill_node",
        "net/sched/cls_api.c:tcf_fill_node",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_gd",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/genetlink.c:genlmsg_put",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588245856,
      "name": "__nlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct nlmsghdr * __nlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, int type, int len, int flags)
```

```json
{
  "name": "__nlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588866032,
      "name": "__nlmsg_put",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2166",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_make_reply",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/net_namespace.c:rtnl_net_fill",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/cls_api.c:tc_chain_fill_node",
        "net/sched/cls_api.c:tcf_fill_node",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_gd",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/genetlink.c:genlmsg_put",
        "net/netfilter/nfnetlink_log.c:__build_packet_message",
        "net/netfilter/nfnetlink_log.c:__nfulnl_send",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_exp_stat_cpu_dump",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_expect_event",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_stat_ct",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_ct_stat_cpu_dump",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_conntrack_event",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_fill_info",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588866032,
      "name": "__nlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct nlmsghdr * __nlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, int type, int len, int flags)
```

```json
{
  "name": "__nlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589007520,
      "name": "__nlmsg_put",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2166",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_make_reply",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/net_namespace.c:rtnl_net_fill",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc",
        "net/sched/cls_api.c:tc_chain_fill_node",
        "net/sched/cls_api.c:tcf_fill_node",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_gd",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_dump",
        "net/netlink/genetlink.c:genlmsg_put",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589007520,
      "name": "__nlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
