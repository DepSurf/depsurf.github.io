# Function: <code>nlmsg_trim</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void nlmsg_trim(struct sk_buff * skb, const void * mark)
```

```json
{
  "name": "nlmsg_trim",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580149831,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:520",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:mk_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586250328,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:520",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586341846,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:520",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_dump_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586357504,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:520",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnetlink_put_metrics",
        "net/core/rtnetlink.c:rtnetlink_put_metrics",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink"
      ]
    },
    {
      "addr": 18446744071586422500,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:520",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586439997,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:520",
      "file": "net/core/lwtunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586462037,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:520",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586471231,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:520",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_exts_dump",
        "net/sched/cls_api.c:tcf_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586478342,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:520",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tcf_action_dump_1",
        "net/sched/act_api.c:tcf_action_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586511888,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:520",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:ctrl_fill_info",
        "net/netlink/genetlink.c:genl_ctrl_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586528893,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:520",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586714841,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:520",
      "file": "net/ipv4/tcp_metrics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586775893,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:520",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586831048,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:520",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586875001,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:520",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587019046,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:520",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587046872,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:520",
      "file": "net/ipv6/addrlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587071751,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:520",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587205582,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:520",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587273764,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:520",
      "file": "net/wireless/wext-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587289966,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:520",
      "file": "net/netlabel/netlabel_mgmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587293302,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:520",
      "file": "net/netlabel/netlabel_unlabeled.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587298658,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:520",
      "file": "net/netlabel/netlabel_cipso_v4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587314771,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:520",
      "file": "net/dcb/dcbnl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/dcb/dcbnl.c:dcbnl_getnumtcs",
        "net/dcb/dcbnl.c:dcbnl_getapp",
        "net/dcb/dcbnl.c:dcbnl_bcn_getcfg",
        "net/dcb/dcbnl.c:dcbnl_getpfccfg",
        "net/dcb/dcbnl.c:dcbnl_getfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_getcap"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586357504,
      "name": "nlmsg_trim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void nlmsg_trim(struct sk_buff * skb, const void * mark)
```

```json
{
  "name": "nlmsg_trim",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580184188,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:mk_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586674584,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586779070,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_fill_parms"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586812021,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnetlink_put_metrics",
        "net/core/rtnetlink.c:rtnetlink_put_metrics"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo"
      ]
    },
    {
      "addr": 18446744071586865641,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586884777,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/core/lwtunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586908129,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586917523,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_exts_dump",
        "net/sched/cls_api.c:tcf_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586925704,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tcf_action_dump",
        "net/sched/act_api.c:tcf_action_dump_1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586956637,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:genl_ctrl_event",
        "net/netlink/genetlink.c:ctrl_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586971457,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587163577,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/ipv4/tcp_metrics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587225283,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587280399,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587323761,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587465550,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587496088,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/ipv6/addrlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587504393,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587662787,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587739428,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/wireless/wext-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587758159,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/netlabel/netlabel_mgmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587761920,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/netlabel/netlabel_unlabeled.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587767344,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/netlabel/netlabel_cipso_v4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587771440,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587793266,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/dcb/dcbnl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/dcb/dcbnl.c:dcbnl_getfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_bcn_getcfg",
        "net/dcb/dcbnl.c:dcbnl_getapp",
        "net/dcb/dcbnl.c:dcbnl_getnumtcs",
        "net/dcb/dcbnl.c:dcbnl_getcap",
        "net/dcb/dcbnl.c:dcbnl_getpfccfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587802731,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/switchdev/switchdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/switchdev/switchdev.c:switchdev_port_fdb_dump_cb"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586790208,
      "name": "nlmsg_trim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nlmsg_trim",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580224716,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:mk_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586859032,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586965602,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_fill_parms"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586999845,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnetlink_put_metrics",
        "net/core/rtnetlink.c:rtnetlink_put_metrics"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587056962,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587076681,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/core/lwtunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587102497,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587112210,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_exts_dump",
        "net/sched/cls_api.c:tcf_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587120456,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tcf_action_dump",
        "net/sched/act_api.c:tcf_action_dump_1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587151469,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:genl_ctrl_event",
        "net/netlink/genetlink.c:ctrl_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587180800,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587362761,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/ipv4/tcp_metrics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587425827,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587481384,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587526433,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587669118,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587699992,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/ipv6/addrlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587708505,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587862865,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587871251,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587954660,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/wireless/wext-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587973375,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/netlabel/netlabel_mgmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587977136,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/netlabel/netlabel_unlabeled.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587982560,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/netlabel/netlabel_cipso_v4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587986640,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588008338,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/dcb/dcbnl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/dcb/dcbnl.c:dcbnl_getfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_bcn_getcfg",
        "net/dcb/dcbnl.c:dcbnl_getapp",
        "net/dcb/dcbnl.c:dcbnl_getnumtcs",
        "net/dcb/dcbnl.c:dcbnl_getcap",
        "net/dcb/dcbnl.c:dcbnl_getpfccfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588016699,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:531",
      "file": "net/switchdev/switchdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/switchdev/switchdev.c:switchdev_port_fdb_dump_cb"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void nlmsg_trim(struct sk_buff * skb, const void * mark)
```

```json
{
  "name": "nlmsg_trim",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580234446,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:540",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:mk_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586982232,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:540",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587093341,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:540",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_fill_parms"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587125046,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:540",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnetlink_put_metrics",
        "net/core/rtnetlink.c:rtnetlink_put_metrics"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink"
      ]
    },
    {
      "addr": 18446744071587184858,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:540",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587204206,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:540",
      "file": "net/core/lwtunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587231084,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:540",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587241210,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:540",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_exts_dump",
        "net/sched/cls_api.c:tcf_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587250040,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:540",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tcf_action_dump",
        "net/sched/act_api.c:tcf_action_dump_1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587282385,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:540",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:genl_ctrl_event",
        "net/netlink/genetlink.c:ctrl_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587314369,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:540",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587496347,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:540",
      "file": "net/ipv4/tcp_metrics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587558174,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:540",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587618427,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:540",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587670536,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:540",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:__ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587817940,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:540",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587850904,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:540",
      "file": "net/ipv6/addrlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587860063,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:540",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588019038,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:540",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588027864,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:540",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:__ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588112834,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:540",
      "file": "net/wireless/wext-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588131458,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:540",
      "file": "net/netlabel/netlabel_mgmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588135071,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:540",
      "file": "net/netlabel/netlabel_unlabeled.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588140484,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:540",
      "file": "net/netlabel/netlabel_cipso_v4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588144580,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:540",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588166473,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:540",
      "file": "net/dcb/dcbnl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/dcb/dcbnl.c:dcbnl_getfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_bcn_getcfg",
        "net/dcb/dcbnl.c:dcbnl_getapp",
        "net/dcb/dcbnl.c:dcbnl_getnumtcs",
        "net/dcb/dcbnl.c:dcbnl_getcap",
        "net/dcb/dcbnl.c:dcbnl_getpfccfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588174674,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:540",
      "file": "net/switchdev/switchdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/switchdev/switchdev.c:switchdev_port_fdb_dump_cb"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587101616,
      "name": "nlmsg_trim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void nlmsg_trim(struct sk_buff * skb, const void * mark)
```

```json
{
  "name": "nlmsg_trim",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580285646,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:mk_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587480216,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587593949,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_fill_parms"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587629014,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnetlink_put_metrics",
        "net/core/rtnetlink.c:rtnetlink_put_metrics"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink"
      ]
    },
    {
      "addr": 18446744071587690559,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587718481,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/core/lwtunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587746530,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587757418,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_exts_dump",
        "net/sched/cls_api.c:tcf_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587767868,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tcf_action_dump",
        "net/sched/act_api.c:tcf_action_dump_1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587802465,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:genl_ctrl_event",
        "net/netlink/genetlink.c:ctrl_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587836196,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588017467,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/ipv4/tcp_metrics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588081486,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588142763,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588196755,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:__ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588347940,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588380423,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/ipv6/addrlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588389221,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588555822,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588566808,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:__ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588660626,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/wireless/wext-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588679266,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/netlabel/netlabel_mgmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588682882,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/netlabel/netlabel_unlabeled.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588688308,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/netlabel/netlabel_cipso_v4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588692420,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588714847,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/dcb/dcbnl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/dcb/dcbnl.c:dcbnl_getfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_bcn_getcfg",
        "net/dcb/dcbnl.c:dcbnl_getapp",
        "net/dcb/dcbnl.c:dcbnl_getnumtcs",
        "net/dcb/dcbnl.c:dcbnl_getcap",
        "net/dcb/dcbnl.c:dcbnl_getpfccfg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587603584,
      "name": "nlmsg_trim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nlmsg_trim",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580346910,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:mk_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587785976,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587901582,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_fill_parms"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587931782,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_xdp_fill",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnetlink_put_metrics",
        "net/core/rtnetlink.c:rtnetlink_put_metrics"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588024362,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588052069,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/core/lwtunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588083966,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588106340,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_exts_dump",
        "net/sched/cls_api.c:tcf_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588110643,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tcf_action_dump",
        "net/sched/act_api.c:tcf_action_dump_1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588144011,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:genl_ctrl_event",
        "net/netlink/genetlink.c:ctrl_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588180765,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588368689,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/ipv4/tcp_metrics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588437269,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588497958,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588551032,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588562401,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr_base.c:mr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588705332,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:inet6_dump_addr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588738503,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/ipv6/addrlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588749978,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588920132,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588925960,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589027250,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/wireless/wext-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589045882,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/netlabel/netlabel_mgmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589049439,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/netlabel/netlabel_unlabeled.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589054980,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/netlabel/netlabel_cipso_v4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589059172,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589082852,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/dcb/dcbnl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/dcb/dcbnl.c:dcbnl_getfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_bcn_getcfg",
        "net/dcb/dcbnl.c:dcbnl_getapp",
        "net/dcb/dcbnl.c:dcbnl_getnumtcs",
        "net/dcb/dcbnl.c:dcbnl_getcap",
        "net/dcb/dcbnl.c:dcbnl_getpfccfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589114189,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:546",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nlmsg_trim",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580402926,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:689",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:mk_reply",
        "kernel/taskstats.c:mk_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587918879,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:689",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:rtnl_net_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588043473,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:689",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_fill_parms"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588087075,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:689",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnetlink_put_metrics",
        "net/core/rtnetlink.c:rtnetlink_put_metrics"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588191799,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:689",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588220357,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:689",
      "file": "net/core/lwtunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588261016,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:689",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588273966,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:689",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_exts_dump",
        "net/sched/cls_api.c:tc_chain_fill_node",
        "net/sched/cls_api.c:tcf_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588292907,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:689",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_dump",
        "net/sched/act_api.c:tcf_action_dump_1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588326731,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:689",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:genl_ctrl_event",
        "net/netlink/genetlink.c:ctrl_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588364755,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:689",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588559598,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:689",
      "file": "net/ipv4/tcp_metrics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588629682,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:689",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588692851,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:689",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588745767,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:689",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588759681,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:689",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr_base.c:mr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588923969,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:689",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588958548,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:689",
      "file": "net/ipv6/addrlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588968946,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:689",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589144340,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:689",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589150053,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:689",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589253231,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:689",
      "file": "net/wireless/wext-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589273274,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:689",
      "file": "net/netlabel/netlabel_mgmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589275359,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:689",
      "file": "net/netlabel/netlabel_unlabeled.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589280852,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:689",
      "file": "net/netlabel/netlabel_cipso_v4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589284868,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:689",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589308148,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:689",
      "file": "net/dcb/dcbnl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/dcb/dcbnl.c:dcbnl_getfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_bcn_getcfg",
        "net/dcb/dcbnl.c:dcbnl_getapp",
        "net/dcb/dcbnl.c:dcbnl_getnumtcs",
        "net/dcb/dcbnl.c:dcbnl_getcap",
        "net/dcb/dcbnl.c:dcbnl_getpfccfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589346329,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:689",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nlmsg_trim",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580455832,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:mk_reply",
        "kernel/taskstats.c:mk_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588226239,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:rtnl_net_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588354802,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_fill_parms"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588402129,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588518041,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588554608,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/lwtunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588616818,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_action_put",
        "net/core/devlink.c:devlink_dpipe_match_put",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588652376,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588665539,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_exts_dump",
        "net/sched/cls_api.c:tc_chain_fill_node",
        "net/sched/cls_api.c:tcf_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588690833,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_dump",
        "net/sched/act_api.c:tcf_action_dump_1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588725060,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:genl_ctrl_event",
        "net/netlink/genetlink.c:ctrl_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588745917,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:rt_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588971663,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/tcp_metrics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589039138,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589109414,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589177775,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589192642,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr_base.c:mr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589366812,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589402100,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/addrlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589412977,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589598547,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589601252,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589708381,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/wireless/wext-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589728693,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_mgmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589730912,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_unlabeled.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589736618,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_cipso_v4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589740730,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589764200,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/dcb/dcbnl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/dcb/dcbnl.c:dcbnl_getfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_bcn_getcfg",
        "net/dcb/dcbnl.c:dcbnl_getapp",
        "net/dcb/dcbnl.c:dcbnl_getnumtcs",
        "net/dcb/dcbnl.c:dcbnl_getcap",
        "net/dcb/dcbnl.c:dcbnl_getpfccfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589801714,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nlmsg_trim",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580504782,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:mk_reply",
        "kernel/taskstats.c:mk_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588430863,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:rtnl_net_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588561250,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_fill_parms"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588608516,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588726630,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588767157,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_report_in_port_put",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588771477,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/lwtunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588821917,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_trap_stats_put",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_action_put",
        "net/core/devlink.c:devlink_dpipe_match_put",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588874744,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588888192,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_exts_dump",
        "net/sched/cls_api.c:tc_chain_fill_node",
        "net/sched/cls_api.c:tcf_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588914961,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_dump",
        "net/sched/act_api.c:tcf_action_dump_1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588948724,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:genl_ctrl_event",
        "net/netlink/genetlink.c:ctrl_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588969690,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:rt_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589196127,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/tcp_metrics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589263650,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589333606,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589402782,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589418082,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr_base.c:mr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589589804,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589626388,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/addrlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589637217,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589822931,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589825604,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589932681,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/wireless/wext-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589952986,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_mgmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589955053,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_unlabeled.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589960805,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_cipso_v4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589964869,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589989144,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/dcb/dcbnl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/dcb/dcbnl.c:dcbnl_getfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_bcn_getcfg",
        "net/dcb/dcbnl.c:dcbnl_getapp",
        "net/dcb/dcbnl.c:dcbnl_getnumtcs",
        "net/dcb/dcbnl.c:dcbnl_getcap",
        "net/dcb/dcbnl.c:dcbnl_getpfccfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590024914,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nlmsg_trim",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580592211,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:mk_reply",
        "kernel/taskstats.c:mk_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589298399,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:rtnl_net_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589413353,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_fill_parms"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589466658,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_link_af",
        "net/core/rtnetlink.c:rtnl_xdp_fill",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_vf_ports_fill",
        "net/core/rtnetlink.c:rtnl_vf_ports_fill",
        "net/core/rtnetlink.c:rtnl_link_fill",
        "net/core/rtnetlink.c:rtnl_link_fill",
        "net/core/rtnetlink.c:rtnl_link_slave_info_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589594650,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_nl_fill_rule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589638978,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_hw_stats_put",
        "net/core/drop_monitor.c:net_dm_stats_put",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_in_port_put",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:net_dm_hw_entries_put",
        "net/core/drop_monitor.c:net_dm_hw_entries_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589643355,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/core/lwtunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589721917,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_trap_policer_fill",
        "net/core/devlink.c:devlink_trap_policer_stats_put",
        "net/core/devlink.c:devlink_nl_trap_group_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_trap_stats_put",
        "net/core/devlink.c:devlink_trap_metadata_put",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_info_version_put",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify_build",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:devlink_nl_param_value_fill_one",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_dpipe_header_put",
        "net/core/devlink.c:devlink_dpipe_header_put",
        "net/core/devlink.c:devlink_dpipe_fields_put",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_action_put",
        "net/core/devlink.c:devlink_dpipe_match_put",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589730660,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put_all",
        "net/core/bpf_sk_storage.c:diag_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589759800,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589796048,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_exts_terse_dump",
        "net/sched/cls_api.c:tcf_exts_dump",
        "net/sched/cls_api.c:tc_chain_fill_node",
        "net/sched/cls_api.c:tcf_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589803631,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_flush",
        "net/sched/act_api.c:tcf_action_dump",
        "net/sched/act_api.c:tcf_action_dump_1",
        "net/sched/act_api.c:tcf_action_dump_terse",
        "net/sched/act_api.c:tcf_del_walker",
        "net/sched/act_api.c:tcf_dump_walker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589840624,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:ctrl_dumppolicy",
        "net/netlink/genetlink.c:ctrl_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589845634,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/netlink/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/policy.c:netlink_policy_dump_write",
        "net/netlink/policy.c:netlink_policy_dump_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589878319,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/ethtool/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589885363,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/ethtool/bitset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/bitset.c:ethnl_put_bitset32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589888464,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/ethtool/strset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/strset.c:strset_fill_reply",
        "net/ethtool/strset.c:strset_fill_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589909102,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/ethtool/cabletest.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/cabletest.c:ethnl_cable_test_step",
        "net/ethtool/cabletest.c:ethnl_cable_test_pulse",
        "net/ethtool/cabletest.c:ethnl_cable_test_amplitude",
        "net/ethtool/cabletest.c:ethnl_cable_test_fault_length",
        "net/ethtool/cabletest.c:ethnl_cable_test_result"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589925956,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:rt_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590166383,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/ipv4/tcp_metrics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590239594,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590312949,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590353342,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_opts_erspan",
        "net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_opts_geneve"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590358828,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/ipv4/nexthop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:nh_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590399070,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/ipv4/ipmr.c:ipmr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590405202,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr_base.c:mr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590596524,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:inet6_fill_ifacaddr",
        "net/ipv6/addrconf.c:inet6_fill_ifmcaddr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590637748,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/ipv6/addrlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590662597,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590846883,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590856046,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590961561,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/wireless/wext-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590983418,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/netlabel/netlabel_mgmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590984985,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/netlabel/netlabel_unlabeled.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590991029,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/netlabel/netlabel_cipso_v4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590994965,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591018710,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/dcb/dcbnl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/dcb/dcbnl.c:dcbnl_getfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_bcn_getcfg",
        "net/dcb/dcbnl.c:dcbnl_getapp",
        "net/dcb/dcbnl.c:dcbnl_getnumtcs",
        "net/dcb/dcbnl.c:dcbnl_getcap",
        "net/dcb/dcbnl.c:dcbnl_getpfccfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591058114,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591111412,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/mptcp/diag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/diag.c:subflow_get_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591115068,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:975",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs",
        "net/mptcp/pm_netlink.c:mptcp_nl_fill_addr"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nlmsg_trim",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580581379,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:mk_reply",
        "kernel/taskstats.c:mk_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588673425,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "drivers/thermal/thermal_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id",
        "drivers/thermal/thermal_netlink.c:thermal_genl_send_event",
        "drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589296959,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:rtnl_net_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589414033,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_fill_parms"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589459887,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_link_af",
        "net/core/rtnetlink.c:rtnl_xdp_fill",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_vf_ports_fill",
        "net/core/rtnetlink.c:rtnl_vf_ports_fill",
        "net/core/rtnetlink.c:rtnl_link_fill",
        "net/core/rtnetlink.c:rtnl_link_fill",
        "net/core/rtnetlink.c:rtnl_link_slave_info_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589606170,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_nl_fill_rule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589662578,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_hw_stats_put",
        "net/core/drop_monitor.c:net_dm_stats_put",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_in_port_put",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:net_dm_hw_entries_put",
        "net/core/drop_monitor.c:net_dm_hw_entries_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589667134,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/core/lwtunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589756717,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_trap_policer_fill",
        "net/core/devlink.c:devlink_trap_policer_stats_put",
        "net/core/devlink.c:devlink_nl_trap_group_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_trap_stats_put",
        "net/core/devlink.c:devlink_trap_metadata_put",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_info_version_put",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify_build",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:devlink_nl_param_value_fill_one",
        "net/core/devlink.c:devlink_nl_flash_update_fill",
        "net/core/devlink.c:devlink_dpipe_header_put",
        "net/core/devlink.c:devlink_dpipe_header_put",
        "net/core/devlink.c:devlink_dpipe_fields_put",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_action_put",
        "net/core/devlink.c:devlink_dpipe_match_put",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_port_function_attrs_put",
        "net/core/devlink.c:devlink_nl_fill",
        "net/core/devlink.c:devlink_nl_fill",
        "net/core/devlink.c:devlink_reload_stats_put",
        "net/core/devlink.c:devlink_reload_stats_put",
        "net/core/devlink.c:devlink_reload_stats_put",
        "net/core/devlink.c:devlink_reload_stats_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589765710,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put_all",
        "net/core/bpf_sk_storage.c:diag_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589794394,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589831504,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_exts_terse_dump",
        "net/sched/cls_api.c:tcf_exts_dump",
        "net/sched/cls_api.c:tc_chain_fill_node",
        "net/sched/cls_api.c:tcf_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589839471,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_flush",
        "net/sched/act_api.c:tcf_action_dump",
        "net/sched/act_api.c:tcf_action_dump_1",
        "net/sched/act_api.c:tcf_del_walker",
        "net/sched/act_api.c:tcf_dump_walker",
        "net/sched/act_api.c:tcf_action_dump_terse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589878475,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:ctrl_dumppolicy",
        "net/netlink/genetlink.c:ctrl_dumppolicy_put_op",
        "net/netlink/genetlink.c:ctrl_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589884963,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/netlink/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/policy.c:netlink_policy_dump_write",
        "net/netlink/policy.c:netlink_policy_dump_write",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589917628,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ethtool/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589924654,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ethtool/bitset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/bitset.c:ethnl_put_bitset32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589927774,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ethtool/strset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/strset.c:strset_fill_reply",
        "net/ethtool/strset.c:strset_fill_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589942808,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ethtool/pause.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/pause.c:pause_put_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589947822,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ethtool/cabletest.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/cabletest.c:ethnl_cable_test_step",
        "net/ethtool/cabletest.c:ethnl_cable_test_pulse",
        "net/ethtool/cabletest.c:ethnl_cable_test_amplitude",
        "net/ethtool/cabletest.c:ethnl_cable_test_fault_length",
        "net/ethtool/cabletest.c:ethnl_cable_test_result"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589951663,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ethtool/tunnels.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589966533,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:rt_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590215481,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv4/tcp_metrics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590292298,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590366005,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590408462,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_opts_erspan",
        "net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_opts_geneve"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590413820,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv4/nexthop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:nh_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590456782,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/ipv4/ipmr.c:ipmr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590463042,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr_base.c:mr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590656977,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:inet6_fill_ifacaddr",
        "net/ipv6/addrconf.c:inet6_fill_ifmcaddr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590697780,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv6/addrlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590722408,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590907651,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590916830,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591026242,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/wireless/wext-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591048010,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/netlabel/netlabel_mgmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591049567,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/netlabel/netlabel_unlabeled.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591055653,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/netlabel/netlabel_cipso_v4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591059589,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591083494,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/dcb/dcbnl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/dcb/dcbnl.c:dcbnl_getfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_bcn_getcfg",
        "net/dcb/dcbnl.c:dcbnl_getapp",
        "net/dcb/dcbnl.c:dcbnl_getnumtcs",
        "net/dcb/dcbnl.c:dcbnl_getcap",
        "net/dcb/dcbnl.c:dcbnl_getpfccfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591120792,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591194409,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/mptcp/diag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/diag.c:subflow_get_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591197649,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs",
        "net/mptcp/pm_netlink.c:mptcp_nl_fill_addr"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nlmsg_trim",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580583715,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:mk_reply",
        "kernel/taskstats.c:mk_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588556021,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "drivers/thermal/thermal_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id",
        "drivers/thermal/thermal_netlink.c:thermal_genl_send_event",
        "drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589190847,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:rtnl_net_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589309985,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_fill_parms"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589357695,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_xdp_fill",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_link_fill",
        "net/core/rtnetlink.c:rtnl_link_fill",
        "net/core/rtnetlink.c:rtnl_link_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589494906,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_nl_fill_rule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589551839,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_in_port_put",
        "net/core/drop_monitor.c:net_dm_hw_summary_report_fill",
        "net/core/drop_monitor.c:net_dm_hw_summary_report_fill",
        "net/core/drop_monitor.c:net_dm_hw_summary_report_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589558867,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/core/lwtunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589605423,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_trap_policer_fill",
        "net/core/devlink.c:devlink_nl_trap_policer_fill",
        "net/core/devlink.c:devlink_nl_trap_group_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_trap_stats_put",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_info_version_put",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify_build",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:devlink_nl_param_value_fill_one",
        "net/core/devlink.c:devlink_nl_flash_update_fill",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_action_put",
        "net/core/devlink.c:devlink_dpipe_match_put",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill",
        "net/core/devlink.c:devlink_nl_fill",
        "net/core/devlink.c:devlink_reload_stats_put",
        "net/core/devlink.c:devlink_reload_stats_put",
        "net/core/devlink.c:devlink_reload_stats_put",
        "net/core/devlink.c:devlink_reload_stats_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589669293,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put",
        "net/core/bpf_sk_storage.c:diag_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589698090,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589720448,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_exts_terse_dump",
        "net/sched/cls_api.c:tcf_exts_dump",
        "net/sched/cls_api.c:tc_chain_fill_node",
        "net/sched/cls_api.c:tcf_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589744288,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_flush",
        "net/sched/act_api.c:tcf_action_dump",
        "net/sched/act_api.c:tcf_action_dump_1",
        "net/sched/act_api.c:tcf_del_walker",
        "net/sched/act_api.c:tcf_dump_walker",
        "net/sched/act_api.c:tcf_action_dump_terse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589786734,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:ctrl_dumppolicy",
        "net/netlink/genetlink.c:ctrl_dumppolicy_put_op",
        "net/netlink/genetlink.c:ctrl_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589790963,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/netlink/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/policy.c:netlink_policy_dump_write",
        "net/netlink/policy.c:netlink_policy_dump_write",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589825853,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ethtool/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/netlink.c:ethnl_default_dumpit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589832492,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ethtool/bitset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/bitset.c:ethnl_put_bitset32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589836543,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ethtool/strset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/strset.c:strset_fill_reply",
        "net/ethtool/strset.c:strset_fill_reply",
        "net/ethtool/strset.c:strset_fill_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589851541,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ethtool/pause.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/pause.c:pause_fill_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589856375,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ethtool/cabletest.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/cabletest.c:ethnl_cable_test_step",
        "net/ethtool/cabletest.c:ethnl_cable_test_pulse",
        "net/ethtool/cabletest.c:ethnl_cable_test_amplitude",
        "net/ethtool/cabletest.c:ethnl_cable_test_fault_length",
        "net/ethtool/cabletest.c:ethnl_cable_test_result"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589860110,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ethtool/tunnels.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589860838,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ethtool/fec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589863961,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ethtool/stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/stats.c:stats_put_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589881573,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:rt_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590129833,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv4/tcp_metrics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590208138,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590282106,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590324503,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590342469,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv4/nexthop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/nexthop.c:nla_put_nh_group_res"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590382020,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/ipv4/ipmr.c:ipmr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590388798,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr_base.c:mr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590582321,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifacaddr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590622660,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv6/addrlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590646061,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590836995,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590846304,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590892573,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:put_nla_counters"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590956866,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/wireless/wext-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590978666,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/netlabel/netlabel_mgmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590980223,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/netlabel/netlabel_unlabeled.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590986346,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/netlabel/netlabel_cipso_v4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590990330,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591014278,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/dcb/dcbnl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/dcb/dcbnl.c:dcbnl_getfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_bcn_getcfg",
        "net/dcb/dcbnl.c:dcbnl_getapp",
        "net/dcb/dcbnl.c:dcbnl_getnumtcs",
        "net/dcb/dcbnl.c:dcbnl_getcap",
        "net/dcb/dcbnl.c:dcbnl_getpfccfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591051124,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591132249,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/mptcp/diag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/diag.c:subflow_get_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591138087,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs",
        "net/mptcp/pm_netlink.c:mptcp_nl_fill_addr"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nlmsg_trim",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580754211,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:mk_reply",
        "kernel/taskstats.c:mk_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589230534,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "drivers/thermal/thermal_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id",
        "drivers/thermal/thermal_netlink.c:thermal_genl_send_event",
        "drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589912402,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:rtnl_net_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590038113,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_fill_parms"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590087903,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_xdp_fill",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_link_fill",
        "net/core/rtnetlink.c:rtnl_link_fill",
        "net/core/rtnetlink.c:rtnl_link_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590235674,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_nl_fill_rule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590296273,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_in_port_put",
        "net/core/drop_monitor.c:net_dm_hw_summary_report_fill",
        "net/core/drop_monitor.c:net_dm_hw_summary_report_fill",
        "net/core/drop_monitor.c:net_dm_hw_summary_report_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590303870,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/core/lwtunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590352031,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_trap_policer_fill",
        "net/core/devlink.c:devlink_nl_trap_policer_fill",
        "net/core/devlink.c:devlink_nl_trap_group_fill",
        "net/core/devlink.c:devlink_nl_trap_group_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_info_version_put",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify_build",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:devlink_nl_param_value_fill_one",
        "net/core/devlink.c:devlink_nl_flash_update_fill",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_action_put",
        "net/core/devlink.c:devlink_dpipe_match_put",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_port_function_attrs_put",
        "net/core/devlink.c:devlink_nl_fill",
        "net/core/devlink.c:devlink_nl_fill",
        "net/core/devlink.c:devlink_reload_stats_put",
        "net/core/devlink.c:devlink_reload_stats_put",
        "net/core/devlink.c:devlink_reload_stats_put",
        "net/core/devlink.c:devlink_reload_stats_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590425629,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put",
        "net/core/bpf_sk_storage.c:diag_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590456042,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590477888,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_exts_terse_dump",
        "net/sched/cls_api.c:tcf_exts_dump",
        "net/sched/cls_api.c:tc_chain_fill_node",
        "net/sched/cls_api.c:tcf_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590502768,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_flush",
        "net/sched/act_api.c:tcf_action_dump",
        "net/sched/act_api.c:tcf_action_dump_1",
        "net/sched/act_api.c:tcf_del_walker",
        "net/sched/act_api.c:tcf_dump_walker",
        "net/sched/act_api.c:tcf_action_dump_terse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590543886,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:ctrl_dumppolicy",
        "net/netlink/genetlink.c:ctrl_dumppolicy_put_op",
        "net/netlink/genetlink.c:ctrl_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590550595,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/netlink/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/policy.c:netlink_policy_dump_write",
        "net/netlink/policy.c:netlink_policy_dump_write",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590588173,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ethtool/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/netlink.c:ethnl_default_dumpit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590595388,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ethtool/bitset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/bitset.c:ethnl_put_bitset32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590599400,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ethtool/strset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/strset.c:strset_fill_reply",
        "net/ethtool/strset.c:strset_fill_reply",
        "net/ethtool/strset.c:strset_fill_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590613493,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ethtool/pause.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/pause.c:pause_fill_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590617671,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ethtool/cabletest.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/cabletest.c:ethnl_cable_test_step",
        "net/ethtool/cabletest.c:ethnl_cable_test_pulse",
        "net/ethtool/cabletest.c:ethnl_cable_test_amplitude",
        "net/ethtool/cabletest.c:ethnl_cable_test_fault_length",
        "net/ethtool/cabletest.c:ethnl_cable_test_result"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590621278,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ethtool/tunnels.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590622054,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ethtool/fec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590624729,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ethtool/stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/stats.c:stats_put_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590645285,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:rt_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590907026,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv4/tcp_metrics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590989754,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591068331,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591112231,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591127227,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv4/nexthop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/nexthop.c:nla_put_nh_group_res"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591174166,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/ipv4/ipmr.c:ipmr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591183144,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr_base.c:mr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591393489,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifacaddr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591435748,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv6/addrlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591464451,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591656531,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591662684,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv6/ioam6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ioam6.c:ioam6_genl_dumpsc",
        "net/ipv6/ioam6.c:ioam6_genl_dumpns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591674896,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591724510,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:put_nla_counters"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591793378,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/wireless/wext-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591816202,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/netlabel/netlabel_mgmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591817759,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/netlabel/netlabel_unlabeled.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591823882,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/netlabel/netlabel_cipso_v4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591828010,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591848436,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/dcb/dcbnl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/dcb/dcbnl.c:dcbnl_getfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_bcn_getcfg",
        "net/dcb/dcbnl.c:dcbnl_getapp",
        "net/dcb/dcbnl.c:dcbnl_getnumtcs",
        "net/dcb/dcbnl.c:dcbnl_getcap",
        "net/dcb/dcbnl.c:dcbnl_getpfccfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591893204,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591981481,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/mptcp/diag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/diag.c:subflow_get_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591987095,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs",
        "net/mptcp/pm_netlink.c:mptcp_nl_fill_addr"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void nlmsg_trim(struct sk_buff * skb, const void * mark)
```

```json
{
  "name": "nlmsg_trim",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580969318,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:mk_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590695056,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "drivers/thermal/thermal_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id",
        "drivers/thermal/thermal_netlink.c:thermal_genl_send_event",
        "drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change",
        "drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591443399,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:rtnl_net_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591582326,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_fill_parms"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591637531,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_offload_xstats_fill",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_xdp_fill",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnetlink_put_metrics",
        "net/core/rtnetlink.c:rtnetlink_put_metrics",
        "net/core/rtnetlink.c:rtnl_link_fill",
        "net/core/rtnetlink.c:rtnl_link_fill",
        "net/core/rtnetlink.c:rtnl_link_fill"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_offload_xstats_fill"
      ]
    },
    {
      "addr": 18446744071591814246,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_nl_fill_rule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591879698,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_in_port_put",
        "net/core/drop_monitor.c:net_dm_hw_summary_report_fill",
        "net/core/drop_monitor.c:net_dm_hw_summary_report_fill",
        "net/core/drop_monitor.c:net_dm_hw_summary_report_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591887194,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/core/lwtunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwtunnel.c:lwtunnel_fill_encap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591936951,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_trap_policer_fill",
        "net/core/devlink.c:devlink_nl_trap_policer_fill",
        "net/core/devlink.c:devlink_nl_trap_group_fill",
        "net/core/devlink.c:devlink_nl_trap_group_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_info_version_put",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify_build",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:devlink_nl_param_value_fill_one",
        "net/core/devlink.c:devlink_nl_flash_update_fill",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_action_put",
        "net/core/devlink.c:devlink_dpipe_match_put",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_port_function_attrs_put",
        "net/core/devlink.c:devlink_nl_fill",
        "net/core/devlink.c:devlink_nl_fill",
        "net/core/devlink.c:devlink_reload_stats_put",
        "net/core/devlink.c:devlink_reload_stats_put",
        "net/core/devlink.c:devlink_reload_stats_put",
        "net/core/devlink.c:devlink_reload_stats_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592024044,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:diag_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592063158,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592093134,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_exts_terse_dump",
        "net/sched/cls_api.c:tcf_exts_dump",
        "net/sched/cls_api.c:tc_chain_fill_node",
        "net/sched/cls_api.c:tcf_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592106853,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_flush",
        "net/sched/act_api.c:tcf_action_dump",
        "net/sched/act_api.c:tcf_action_dump_1",
        "net/sched/act_api.c:tcf_dump_walker",
        "net/sched/act_api.c:tcf_action_dump_terse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592153598,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:ctrl_dumppolicy",
        "net/netlink/genetlink.c:ctrl_dumppolicy_put_op",
        "net/netlink/genetlink.c:ctrl_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592160859,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/netlink/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/policy.c:netlink_policy_dump_write",
        "net/netlink/policy.c:netlink_policy_dump_write",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592209095,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ethtool/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/netlink.c:ethnl_default_dumpit",
        "net/ethtool/netlink.c:ethnl_fill_reply_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592214764,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ethtool/bitset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/bitset.c:ethnl_put_bitset32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592219409,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ethtool/strset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/strset.c:strset_fill_reply",
        "net/ethtool/strset.c:strset_fill_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592234997,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ethtool/pause.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/pause.c:pause_fill_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592239420,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ethtool/cabletest.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/cabletest.c:ethnl_cable_test_step",
        "net/ethtool/cabletest.c:ethnl_cable_test_pulse",
        "net/ethtool/cabletest.c:ethnl_cable_test_amplitude",
        "net/ethtool/cabletest.c:ethnl_cable_test_fault_length",
        "net/ethtool/cabletest.c:ethnl_cable_test_result"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592243141,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ethtool/tunnels.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592243866,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ethtool/fec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592247345,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ethtool/stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/stats.c:stats_put_stats",
        "net/ethtool/stats.c:stats_put_rmon_hist",
        "net/ethtool/stats.c:stat_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592270170,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:rt_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592546468,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv4/tcp_metrics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592635419,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592717883,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592757792,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592781307,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv4/nexthop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/nexthop.c:nla_put_nh_group_res"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592829804,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/ipv4/ipmr.c:ipmr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592841687,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr_base.c:mr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593069948,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifacaddr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593114936,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv6/addrlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593146567,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593351196,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593356569,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv6/ioam6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ioam6.c:ioam6_genl_dumpsc",
        "net/ipv6/ioam6.c:ioam6_genl_dumpns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593371602,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593425683,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:put_nla_counters"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593503311,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/wireless/wext-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593528908,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/netlabel/netlabel_mgmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593530870,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/netlabel/netlabel_unlabeled.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593537278,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/netlabel/netlabel_cipso_v4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593541662,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593564504,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/dcb/dcbnl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/dcb/dcbnl.c:dcbnl_getfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_bcn_getcfg",
        "net/dcb/dcbnl.c:dcbnl_getapp",
        "net/dcb/dcbnl.c:dcbnl_getnumtcs",
        "net/dcb/dcbnl.c:dcbnl_getcap",
        "net/dcb/dcbnl.c:dcbnl_getpfccfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593612391,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593712093,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/mptcp/diag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/diag.c:subflow_get_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593718480,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs",
        "net/mptcp/pm_netlink.c:mptcp_nl_fill_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593754594,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/mctp/device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mctp/device.c:mctp_fill_addrinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593759559,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/mctp/route.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593768121,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:988",
      "file": "net/mctp/neigh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mctp/neigh.c:mctp_rtm_getneigh"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591602960,
      "name": "nlmsg_trim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071592757792,
      "name": "nlmsg_trim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void nlmsg_trim(struct sk_buff * skb, const void * mark)
```

```json
{
  "name": "nlmsg_trim",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581264342,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:mk_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592365456,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "drivers/thermal/thermal_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id",
        "drivers/thermal/thermal_netlink.c:thermal_genl_send_event",
        "drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change",
        "drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593210487,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:rtnl_net_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593360566,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_fill_parms"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593420347,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_offload_xstats_fill",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_xdp_fill",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnetlink_put_metrics",
        "net/core/rtnetlink.c:rtnetlink_put_metrics",
        "net/core/rtnetlink.c:rtnl_link_fill",
        "net/core/rtnetlink.c:rtnl_link_fill",
        "net/core/rtnetlink.c:rtnl_link_fill"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_offload_xstats_fill"
      ]
    },
    {
      "addr": 18446744071593610122,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_nl_fill_rule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593681051,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_in_port_put",
        "net/core/drop_monitor.c:net_dm_hw_summary_report_fill",
        "net/core/drop_monitor.c:net_dm_hw_summary_report_fill",
        "net/core/drop_monitor.c:net_dm_hw_summary_report_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593689290,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/core/lwtunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwtunnel.c:lwtunnel_fill_encap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593790599,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_trap_policer_fill",
        "net/core/devlink.c:devlink_nl_trap_policer_fill",
        "net/core/devlink.c:devlink_nl_trap_group_fill",
        "net/core/devlink.c:devlink_nl_trap_group_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_info_version_put",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify_build",
        "net/core/devlink.c:devlink_nl_param_value_fill_one",
        "net/core/devlink.c:devlink_nl_cmd_selftests_run",
        "net/core/devlink.c:devlink_nl_cmd_selftests_run",
        "net/core/devlink.c:devlink_nl_selftests_fill",
        "net/core/devlink.c:devlink_nl_flash_update_fill",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_entry_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_action_put",
        "net/core/devlink.c:devlink_dpipe_match_put",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill",
        "net/core/devlink.c:devlink_nl_fill",
        "net/core/devlink.c:devlink_reload_stats_put",
        "net/core/devlink.c:devlink_reload_stats_put",
        "net/core/devlink.c:devlink_reload_stats_put",
        "net/core/devlink.c:devlink_reload_stats_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593840033,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:diag_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593882950,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593914350,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_exts_terse_dump",
        "net/sched/cls_api.c:tcf_exts_dump",
        "net/sched/cls_api.c:tc_chain_fill_node",
        "net/sched/cls_api.c:tcf_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593933850,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_flush",
        "net/sched/act_api.c:tcf_action_dump",
        "net/sched/act_api.c:tcf_action_dump_1",
        "net/sched/act_api.c:tcf_dump_walker",
        "net/sched/act_api.c:tcf_action_dump_terse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593980368,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:ctrl_dumppolicy",
        "net/netlink/genetlink.c:ctrl_dumppolicy_put_op",
        "net/netlink/genetlink.c:ctrl_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593987835,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/netlink/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/policy.c:netlink_policy_dump_write",
        "net/netlink/policy.c:netlink_policy_dump_write",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594038759,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/ethtool/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/netlink.c:ethnl_default_dumpit",
        "net/ethtool/netlink.c:ethnl_fill_reply_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594044668,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/ethtool/bitset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/bitset.c:ethnl_put_bitset32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594049617,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/ethtool/strset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/strset.c:strset_fill_reply",
        "net/ethtool/strset.c:strset_fill_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594067189,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/ethtool/pause.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/pause.c:pause_fill_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594071852,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/ethtool/cabletest.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/cabletest.c:ethnl_cable_test_step",
        "net/ethtool/cabletest.c:ethnl_cable_test_pulse",
        "net/ethtool/cabletest.c:ethnl_cable_test_amplitude",
        "net/ethtool/cabletest.c:ethnl_cable_test_fault_length",
        "net/ethtool/cabletest.c:ethnl_cable_test_result"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594075669,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/ethtool/tunnels.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594076442,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/ethtool/fec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594080081,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/ethtool/stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/stats.c:stats_put_stats",
        "net/ethtool/stats.c:stats_put_rmon_hist",
        "net/ethtool/stats.c:stat_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594105559,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:rt_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594405428,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/ipv4/tcp_metrics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594501563,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594588075,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594630096,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594654875,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/ipv4/nexthop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/nexthop.c:nla_put_nh_group_res"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594705868,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/ipv4/ipmr.c:ipmr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594719201,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr_base.c:mr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594964124,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifacaddr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595010511,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/ipv6/addrlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595044103,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595257772,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595263673,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/ipv6/ioam6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ioam6.c:ioam6_genl_dumpsc",
        "net/ipv6/ioam6.c:ioam6_genl_dumpns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595279602,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595343886,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:put_nla_flavors",
        "net/ipv6/seg6_local.c:put_nla_counters"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595422199,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/wireless/wext-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595449516,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/netlabel/netlabel_mgmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595451478,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/netlabel/netlabel_unlabeled.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595458110,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/netlabel/netlabel_cipso_v4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595462622,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595486632,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/dcb/dcbnl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/dcb/dcbnl.c:dcbnl_getfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_ieee_fill",
        "net/dcb/dcbnl.c:dcbnl_bcn_getcfg",
        "net/dcb/dcbnl.c:dcbnl_getapp",
        "net/dcb/dcbnl.c:dcbnl_getnumtcs",
        "net/dcb/dcbnl.c:dcbnl_getcap",
        "net/dcb/dcbnl.c:dcbnl_getpfccfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595541447,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595646829,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/mptcp/diag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/diag.c:subflow_get_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595653578,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs",
        "net/mptcp/pm_netlink.c:mptcp_nl_fill_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595692562,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/mctp/device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mctp/device.c:mctp_fill_addrinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595697671,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/mctp/route.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595707257,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1037",
      "file": "net/mctp/neigh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mctp/neigh.c:mctp_rtm_getneigh"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593384112,
      "name": "nlmsg_trim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071594630096,
      "name": "nlmsg_trim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void nlmsg_trim(struct sk_buff * skb, const void * mark)
```

```json
{
  "name": "nlmsg_trim",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581359494,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:mk_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592792928,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "drivers/thermal/thermal_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id",
        "drivers/thermal/thermal_netlink.c:thermal_genl_send_event",
        "drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change",
        "drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593670727,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:rtnl_net_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593822850,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_fill_parms"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593883149,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_offload_xstats_fill",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_xdp_fill",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_port_fill",
        "net/core/rtnetlink.c:rtnl_port_fill",
        "net/core/rtnetlink.c:rtnl_port_fill",
        "net/core/rtnetlink.c:rtnetlink_put_metrics",
        "net/core/rtnetlink.c:rtnetlink_put_metrics",
        "net/core/rtnetlink.c:rtnl_link_fill",
        "net/core/rtnetlink.c:rtnl_link_fill",
        "net/core/rtnetlink.c:rtnl_link_fill"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_offload_xstats_fill"
      ]
    },
    {
      "addr": 18446744071594036950,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/core/netdev-genl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594083482,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_nl_fill_rule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594161723,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_in_port_put",
        "net/core/drop_monitor.c:net_dm_hw_summary_report_fill",
        "net/core/drop_monitor.c:net_dm_hw_summary_report_fill",
        "net/core/drop_monitor.c:net_dm_hw_summary_report_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594170118,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/core/lwtunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwtunnel.c:lwtunnel_fill_encap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594214598,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:diag_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594259893,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594276606,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_exts_terse_dump",
        "net/sched/cls_api.c:tcf_exts_dump",
        "net/sched/cls_api.c:tc_chain_fill_node",
        "net/sched/cls_api.c:tcf_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594310832,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_flush",
        "net/sched/act_api.c:tcf_action_dump",
        "net/sched/act_api.c:tcf_action_dump_1",
        "net/sched/act_api.c:tcf_dump_walker",
        "net/sched/act_api.c:tcf_action_dump_terse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594357472,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:ctrl_dumppolicy",
        "net/netlink/genetlink.c:ctrl_dumppolicy_put_op",
        "net/netlink/genetlink.c:ctrl_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594364955,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/netlink/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/policy.c:netlink_policy_dump_write",
        "net/netlink/policy.c:netlink_policy_dump_write",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594417063,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/ethtool/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/netlink.c:ethnl_default_dumpit",
        "net/ethtool/netlink.c:ethnl_fill_reply_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594423023,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/ethtool/bitset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/bitset.c:ethnl_put_bitset32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594428298,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/ethtool/strset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/strset.c:strset_fill_reply",
        "net/ethtool/strset.c:strset_fill_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594446987,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/ethtool/pause.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/pause.c:pause_fill_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594451036,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/ethtool/cabletest.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/cabletest.c:ethnl_cable_test_step",
        "net/ethtool/cabletest.c:ethnl_cable_test_pulse",
        "net/ethtool/cabletest.c:ethnl_cable_test_amplitude",
        "net/ethtool/cabletest.c:ethnl_cable_test_fault_length",
        "net/ethtool/cabletest.c:ethnl_cable_test_result"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594455031,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/ethtool/tunnels.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594455914,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/ethtool/fec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594460065,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/ethtool/stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/stats.c:stats_put_stats",
        "net/ethtool/stats.c:stats_put_rmon_hist",
        "net/ethtool/stats.c:stat_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594466108,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/ethtool/mm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/mm.c:mm_fill_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594492425,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:rt_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594794463,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/ipv4/tcp_metrics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594893177,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594979723,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595022464,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595047275,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/ipv4/nexthop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/nexthop.c:nla_put_nh_group_res"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595097804,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/ipv4/ipmr.c:ipmr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595111214,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr_base.c:mr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595356618,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifacaddr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595403778,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/ipv6/addrlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595437565,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595653132,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595659337,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/ipv6/ioam6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ioam6.c:ioam6_genl_dumpsc",
        "net/ipv6/ioam6.c:ioam6_genl_dumpns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595674770,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595739406,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:put_nla_flavors",
        "net/ipv6/seg6_local.c:put_nla_counters"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595849803,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/devlink/leftover.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/devlink/leftover.c:devlink_nl_trap_policer_fill",
        "net/devlink/leftover.c:devlink_nl_trap_policer_fill",
        "net/devlink/leftover.c:devlink_nl_trap_group_fill",
        "net/devlink/leftover.c:devlink_nl_trap_group_fill",
        "net/devlink/leftover.c:devlink_nl_trap_fill",
        "net/devlink/leftover.c:devlink_nl_trap_fill",
        "net/devlink/leftover.c:devlink_nl_trap_fill",
        "net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit",
        "net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit",
        "net/devlink/leftover.c:devlink_nl_region_notify_build",
        "net/devlink/leftover.c:devlink_nl_param_value_fill_one",
        "net/devlink/leftover.c:devlink_dpipe_entry_put",
        "net/devlink/leftover.c:devlink_dpipe_entry_put",
        "net/devlink/leftover.c:devlink_dpipe_entry_put",
        "net/devlink/leftover.c:devlink_dpipe_entry_put",
        "net/devlink/leftover.c:devlink_dpipe_entry_put",
        "net/devlink/leftover.c:devlink_dpipe_table_put",
        "net/devlink/leftover.c:devlink_dpipe_table_put",
        "net/devlink/leftover.c:devlink_dpipe_action_put",
        "net/devlink/leftover.c:devlink_dpipe_match_put",
        "net/devlink/leftover.c:devlink_nl_port_fill",
        "net/devlink/leftover.c:devlink_nl_port_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595907754,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/devlink/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/devlink/dev.c:devlink_nl_cmd_selftests_run",
        "net/devlink/dev.c:devlink_nl_cmd_selftests_run",
        "net/devlink/dev.c:devlink_nl_selftests_fill",
        "net/devlink/dev.c:devlink_nl_flash_update_fill",
        "net/devlink/dev.c:devlink_info_version_put",
        "net/devlink/dev.c:devlink_nl_cmd_reload",
        "net/devlink/dev.c:devlink_nl_fill",
        "net/devlink/dev.c:devlink_nl_fill",
        "net/devlink/dev.c:devlink_reload_stats_put",
        "net/devlink/dev.c:devlink_reload_stats_put",
        "net/devlink/dev.c:devlink_reload_stats_put",
        "net/devlink/dev.c:devlink_reload_stats_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595918379,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/devlink/health.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/devlink/health.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/devlink/health.c:devlink_nl_health_reporter_fill",
        "net/devlink/health.c:devlink_nl_health_reporter_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595929122,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/wireless/wext-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595956588,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/netlabel/netlabel_mgmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595958550,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/netlabel/netlabel_unlabeled.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595965230,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/netlabel/netlabel_cipso_v4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595969710,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595995159,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/dcb/dcbnl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/dcb/dcbnl.c:dcbnl_getfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_ieee_fill",
        "net/dcb/dcbnl.c:dcbnl_ieee_fill",
        "net/dcb/dcbnl.c:dcbnl_bcn_getcfg",
        "net/dcb/dcbnl.c:dcbnl_getapp",
        "net/dcb/dcbnl.c:dcbnl_getnumtcs",
        "net/dcb/dcbnl.c:dcbnl_getcap",
        "net/dcb/dcbnl.c:dcbnl_getpfccfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596050023,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596155620,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/mptcp/diag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/diag.c:subflow_get_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596162315,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs",
        "net/mptcp/pm_netlink.c:mptcp_nl_fill_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596203986,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/mctp/device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mctp/device.c:mctp_fill_addrinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596209143,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/mctp/route.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596218777,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/mctp/neigh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mctp/neigh.c:mctp_rtm_getneigh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596221853,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/handshake/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/handshake/netlink.c:handshake_genl_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596229044,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1038",
      "file": "net/handshake/tlshd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/handshake/tlshd.c:tls_handshake_accept",
        "net/handshake/tlshd.c:tls_handshake_accept"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593846272,
      "name": "nlmsg_trim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071595022464,
      "name": "nlmsg_trim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void nlmsg_trim(struct sk_buff * skb, const void * mark)
```

```json
{
  "name": "nlmsg_trim",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581465670,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:mk_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593541200,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "drivers/thermal/thermal_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_id",
        "drivers/thermal/thermal_netlink.c:thermal_genl_send_event",
        "drivers/thermal/thermal_netlink.c:thermal_genl_event_cpu_capability_change",
        "drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594293686,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "drivers/dpll/dpll_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dpll/dpll_netlink.c:dpll_nl_device_get_dumpit",
        "drivers/dpll/dpll_netlink.c:dpll_nl_pin_get_dumpit",
        "drivers/dpll/dpll_netlink.c:dpll_pin_event_send",
        "drivers/dpll/dpll_netlink.c:dpll_device_event_send",
        "drivers/dpll/dpll_netlink.c:dpll_msg_add_pin_parents",
        "drivers/dpll/dpll_netlink.c:dpll_msg_add_pin_freq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594448807,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:rtnl_net_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594604098,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_fill_parms"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594666339,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_offload_xstats_fill",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_xdp_fill",
        "net/core/rtnetlink.c:rtnl_fill_vf",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_port_fill",
        "net/core/rtnetlink.c:rtnl_port_fill",
        "net/core/rtnetlink.c:rtnl_port_fill",
        "net/core/rtnetlink.c:rtnetlink_put_metrics",
        "net/core/rtnetlink.c:rtnetlink_put_metrics",
        "net/core/rtnetlink.c:rtnl_link_fill",
        "net/core/rtnetlink.c:rtnl_link_fill",
        "net/core/rtnetlink.c:rtnl_link_fill"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_offload_xstats_fill"
      ]
    },
    {
      "addr": 18446744071594824362,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/core/netdev-genl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netdev-genl.c:netdev_nl_queue_fill_one",
        "net/core/netdev-genl.c:netdev_nl_napi_fill_one",
        "net/core/netdev-genl.c:netdev_nl_dev_fill",
        "net/core/netdev-genl.c:netdev_nl_dev_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594857376,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/core/page_pool_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool_user.c:page_pool_nl_fill",
        "net/core/page_pool_user.c:page_pool_nl_stats_fill",
        "net/core/page_pool_user.c:page_pool_nl_stats_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594878122,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_nl_fill_rule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594958251,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_in_port_put",
        "net/core/drop_monitor.c:net_dm_hw_summary_report_fill",
        "net/core/drop_monitor.c:net_dm_hw_summary_report_fill",
        "net/core/drop_monitor.c:net_dm_hw_summary_report_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594966662,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/core/lwtunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwtunnel.c:lwtunnel_fill_encap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595011974,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:diag_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595057349,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595074734,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_exts_terse_dump",
        "net/sched/cls_api.c:tcf_exts_dump",
        "net/sched/cls_api.c:tc_chain_fill_node",
        "net/sched/cls_api.c:tcf_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595109984,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_flush",
        "net/sched/act_api.c:tcf_action_dump",
        "net/sched/act_api.c:tcf_action_dump_1",
        "net/sched/act_api.c:tcf_dump_walker",
        "net/sched/act_api.c:tcf_action_dump_terse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595157456,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:ctrl_dumppolicy",
        "net/netlink/genetlink.c:ctrl_dumppolicy_put_op",
        "net/netlink/genetlink.c:ctrl_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595165771,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/netlink/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/policy.c:netlink_policy_dump_write",
        "net/netlink/policy.c:netlink_policy_dump_write",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr",
        "net/netlink/policy.c:__netlink_policy_dump_write_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595219427,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/ethtool/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/netlink.c:ethnl_default_dumpit",
        "net/ethtool/netlink.c:ethnl_fill_reply_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595225263,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/ethtool/bitset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/bitset.c:ethnl_put_bitset32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595230554,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/ethtool/strset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/strset.c:strset_fill_reply",
        "net/ethtool/strset.c:strset_fill_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595249435,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/ethtool/pause.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/pause.c:pause_fill_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595253484,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/ethtool/cabletest.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/cabletest.c:ethnl_cable_test_step",
        "net/ethtool/cabletest.c:ethnl_cable_test_pulse",
        "net/ethtool/cabletest.c:ethnl_cable_test_amplitude",
        "net/ethtool/cabletest.c:ethnl_cable_test_fault_length",
        "net/ethtool/cabletest.c:ethnl_cable_test_result"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595257380,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/ethtool/tunnels.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595258186,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/ethtool/fec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595262337,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/ethtool/stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/stats.c:stats_put_stats",
        "net/ethtool/stats.c:stats_put_rmon_hist",
        "net/ethtool/stats.c:stat_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595268380,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/ethtool/mm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/mm.c:mm_fill_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595295321,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:rt_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595605647,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/ipv4/tcp_metrics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595704489,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595792219,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595835344,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595860315,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/ipv4/nexthop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/nexthop.c:nla_put_nh_group_res"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595910476,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_fill_vif",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/ipv4/ipmr.c:ipmr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595923886,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr_base.c:mr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596197474,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifacaddr",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596245410,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/ipv6/addrlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596279565,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596500636,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596507065,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/ipv6/ioam6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ioam6.c:ioam6_genl_dumpsc",
        "net/ipv6/ioam6.c:ioam6_genl_dumpns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596522594,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596586814,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:put_nla_flavors",
        "net/ipv6/seg6_local.c:put_nla_counters"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596677010,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/devlink/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/devlink/netlink.c:devlink_nl_put_nested_handle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596692461,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/devlink/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/devlink/dev.c:devlink_nl_selftests_run_doit",
        "net/devlink/dev.c:devlink_nl_selftests_run_doit",
        "net/devlink/dev.c:devlink_nl_selftests_fill",
        "net/devlink/dev.c:devlink_nl_flash_update_fill",
        "net/devlink/dev.c:devlink_info_version_put",
        "net/devlink/dev.c:devlink_nl_reload_doit",
        "net/devlink/dev.c:devlink_nl_fill",
        "net/devlink/dev.c:devlink_nl_fill",
        "net/devlink/dev.c:devlink_reload_stats_put",
        "net/devlink/dev.c:devlink_reload_stats_put",
        "net/devlink/dev.c:devlink_reload_stats_put",
        "net/devlink/dev.c:devlink_reload_stats_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596698243,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/devlink/port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/devlink/port.c:devlink_nl_port_fill",
        "net/devlink/port.c:devlink_nl_port_function_attrs_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596706195,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/devlink/sb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596718122,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/devlink/dpipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/devlink/dpipe.c:devlink_dpipe_entry_put",
        "net/devlink/dpipe.c:devlink_dpipe_entry_put",
        "net/devlink/dpipe.c:devlink_dpipe_entry_put",
        "net/devlink/dpipe.c:devlink_dpipe_entry_put",
        "net/devlink/dpipe.c:devlink_dpipe_entry_put",
        "net/devlink/dpipe.c:devlink_dpipe_table_put",
        "net/devlink/dpipe.c:devlink_dpipe_table_put",
        "net/devlink/dpipe.c:devlink_dpipe_action_put",
        "net/devlink/dpipe.c:devlink_dpipe_match_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596721866,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/devlink/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596727281,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/devlink/param.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/devlink/param.c:devlink_nl_param_value_fill_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596741778,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/devlink/region.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/devlink/region.c:devlink_nl_region_read_dumpit",
        "net/devlink/region.c:devlink_nl_region_read_dumpit",
        "net/devlink/region.c:devlink_nl_region_notify_build"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596754327,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/devlink/health.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/devlink/health.c:devlink_nl_health_reporter_dump_get_dumpit",
        "net/devlink/health.c:devlink_nl_health_reporter_fill",
        "net/devlink/health.c:devlink_nl_health_reporter_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596756091,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/devlink/trap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/devlink/trap.c:devlink_nl_trap_policer_fill",
        "net/devlink/trap.c:devlink_nl_trap_policer_fill",
        "net/devlink/trap.c:devlink_nl_trap_group_fill",
        "net/devlink/trap.c:devlink_nl_trap_group_fill",
        "net/devlink/trap.c:devlink_nl_trap_fill",
        "net/devlink/trap.c:devlink_nl_trap_fill",
        "net/devlink/trap.c:devlink_nl_trap_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596771847,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/devlink/rate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596776007,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/devlink/linecard.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596790438,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/wireless/wext-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596818748,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/netlabel/netlabel_mgmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596820829,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/netlabel/netlabel_unlabeled.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596827406,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/netlabel/netlabel_cipso_v4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596832142,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596859274,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/dcb/dcbnl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/dcb/dcbnl.c:dcbnl_getfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_ieee_fill",
        "net/dcb/dcbnl.c:dcbnl_getapptrust",
        "net/dcb/dcbnl.c:dcbnl_bcn_getcfg",
        "net/dcb/dcbnl.c:dcbnl_getapp",
        "net/dcb/dcbnl.c:dcbnl_getnumtcs",
        "net/dcb/dcbnl.c:dcbnl_getcap",
        "net/dcb/dcbnl.c:dcbnl_getpfccfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596914919,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597029660,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/mptcp/diag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/diag.c:subflow_get_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597047915,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_get_addr_dumpit",
        "net/mptcp/pm_netlink.c:mptcp_nl_fill_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597081746,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/mctp/device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mctp/device.c:mctp_fill_addrinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597086935,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/mctp/route.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071597096761,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/mctp/neigh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mctp/neigh.c:mctp_rtm_getneigh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597100675,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/handshake/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/handshake/netlink.c:handshake_genl_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597107924,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:1059",
      "file": "net/handshake/tlshd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/handshake/tlshd.c:tls_handshake_accept",
        "net/handshake/tlshd.c:tls_handshake_accept"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594627936,
      "name": "nlmsg_trim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071595835344,
      "name": "nlmsg_trim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "nlmsg_trim",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491783580,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:mk_reply",
        "kernel/taskstats.c:mk_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501951840,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:rtnl_net_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502100040,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_fill_parms"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502154996,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502292408,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502332040,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_report_in_port_put",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502338012,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/lwtunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502395348,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_trap_stats_put",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_action_put",
        "net/core/devlink.c:devlink_dpipe_match_put",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502463588,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502477680,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_exts_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502507792,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_dump",
        "net/sched/act_api.c:tcf_action_dump_1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502549964,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:genl_ctrl_event",
        "net/netlink/genetlink.c:ctrl_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502572456,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:rt_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502813900,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/tcp_metrics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502892440,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502973000,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503041916,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503069656,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr_base.c:mr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503273480,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503309568,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/addrlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503319696,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503531360,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503534524,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503659680,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/wireless/wext-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503686068,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_mgmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503688608,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_unlabeled.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503695084,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_cipso_v4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503699508,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503728992,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/dcb/dcbnl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/dcb/dcbnl.c:dcbnl_getfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_bcn_getcfg",
        "net/dcb/dcbnl.c:dcbnl_getapp",
        "net/dcb/dcbnl.c:dcbnl_getnumtcs",
        "net/dcb/dcbnl.c:dcbnl_getcap",
        "net/dcb/dcbnl.c:dcbnl_getpfccfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503775528,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "nlmsg_trim",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225730908,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:mk_reply",
        "kernel/taskstats.c:mk_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 3234707548,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:rtnl_net_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 3234850024,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_fill_parms"
      ],
      "caller_func": []
    },
    {
      "addr": 3234897600,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 3235031400,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_nl_fill_rule"
      ],
      "caller_func": []
    },
    {
      "addr": 3235072536,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_report_in_port_put",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work"
      ],
      "caller_func": []
    },
    {
      "addr": 3235077448,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/lwtunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235129184,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_trap_group_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_trap_stats_put",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_info_version_put",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_action_put",
        "net/core/devlink.c:devlink_dpipe_match_put",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 3235178972,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc"
      ],
      "caller_func": []
    },
    {
      "addr": 3235193504,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_exts_dump",
        "net/sched/cls_api.c:tc_chain_fill_node",
        "net/sched/cls_api.c:tcf_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 3235219196,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_flush",
        "net/sched/act_api.c:tcf_action_dump",
        "net/sched/act_api.c:tcf_action_dump_1"
      ],
      "caller_func": []
    },
    {
      "addr": 3235255428,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:genl_ctrl_event",
        "net/netlink/genetlink.c:ctrl_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 3235279352,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:rt_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 3235515444,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/tcp_metrics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 3235586292,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 3235661788,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
      ],
      "caller_func": []
    },
    {
      "addr": 3235733276,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 3235753816,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr_base.c:mr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 3235939888,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 3235976400,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/addrlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235988916,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 3236184404,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
      ],
      "caller_func": []
    },
    {
      "addr": 3236187388,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 3236300336,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/wireless/wext-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/wireless/wext-core.c:wireless_send_event"
      ],
      "caller_func": []
    },
    {
      "addr": 3236322244,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_mgmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_protocols_cb",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 3236324880,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_unlabeled.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen"
      ],
      "caller_func": []
    },
    {
      "addr": 3236330712,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_cipso_v4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 3236335032,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 3236360104,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/dcb/dcbnl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/dcb/dcbnl.c:dcbnl_getfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_bcn_getcfg",
        "net/dcb/dcbnl.c:dcbnl_getapp",
        "net/dcb/dcbnl.c:dcbnl_getnumtcs",
        "net/dcb/dcbnl.c:dcbnl_getcap",
        "net/dcb/dcbnl.c:dcbnl_getpfccfg"
      ],
      "caller_func": []
    },
    {
      "addr": 3236396836,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "nlmsg_trim",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284831616,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:mk_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295373816,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:rtnl_net_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295562976,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_fill_parms"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295623804,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295795264,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055295851188,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_report_in_port_put",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295859020,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/lwtunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055295937856,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_trap_stats_put",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_action_put",
        "net/core/devlink.c:devlink_dpipe_match_put",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296024000,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296036940,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_exts_dump",
        "net/sched/cls_api.c:tc_chain_fill_node",
        "net/sched/cls_api.c:tcf_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296075848,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_dump",
        "net/sched/act_api.c:tcf_action_dump_1"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296125180,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:genl_ctrl_event",
        "net/netlink/genetlink.c:ctrl_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296158640,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:rt_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296461712,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/tcp_metrics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296554880,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296655168,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296750572,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296773664,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr_base.c:mr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297016128,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297063904,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/addrlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297080160,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297327120,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297331760,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297482832,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/wireless/wext-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297511744,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_mgmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297517264,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_unlabeled.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297525032,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_cipso_v4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297530792,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297566920,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/dcb/dcbnl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/dcb/dcbnl.c:dcbnl_getfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_bcn_getcfg",
        "net/dcb/dcbnl.c:dcbnl_getapp",
        "net/dcb/dcbnl.c:dcbnl_getnumtcs",
        "net/dcb/dcbnl.c:dcbnl_getcap",
        "net/dcb/dcbnl.c:dcbnl_getpfccfg"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297617208,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "nlmsg_trim",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272098880,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:mk_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278255134,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:rtnl_net_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278374914,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_fill_parms"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278410346,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278522248,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278554980,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_report_in_port_put",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278559666,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/lwtunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278607786,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_trap_stats_put",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_action_put",
        "net/core/devlink.c:devlink_dpipe_match_put",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278647978,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278658528,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_exts_dump",
        "net/sched/cls_api.c:tc_chain_fill_node",
        "net/sched/cls_api.c:tcf_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278681104,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_dump",
        "net/sched/act_api.c:tcf_action_dump_1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278711874,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:genl_ctrl_event",
        "net/netlink/genetlink.c:ctrl_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278730820,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:rt_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278930064,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/tcp_metrics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278990920,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279051800,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279114842,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279127744,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr_base.c:mr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279292914,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279324484,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/addrlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279337254,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279498276,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279501380,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279601180,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/wireless/wext-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/wireless/wext-core.c:wireless_send_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279620644,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_mgmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279622230,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_unlabeled.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279627332,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_cipso_v4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279630836,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279652156,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/dcb/dcbnl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/dcb/dcbnl.c:dcbnl_getfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_bcn_getcfg",
        "net/dcb/dcbnl.c:dcbnl_getapp",
        "net/dcb/dcbnl.c:dcbnl_getnumtcs",
        "net/dcb/dcbnl.c:dcbnl_getcap",
        "net/dcb/dcbnl.c:dcbnl_getpfccfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279686436,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nlmsg_trim",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580473582,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:mk_reply",
        "kernel/taskstats.c:mk_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588037647,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:rtnl_net_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588167986,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_fill_parms"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588215252,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588333366,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588373893,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_report_in_port_put",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588377861,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/lwtunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588428301,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_trap_stats_put",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_action_put",
        "net/core/devlink.c:devlink_dpipe_match_put",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588481128,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588494576,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_exts_dump",
        "net/sched/cls_api.c:tc_chain_fill_node",
        "net/sched/cls_api.c:tcf_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588521345,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_dump",
        "net/sched/act_api.c:tcf_action_dump_1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588555108,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:genl_ctrl_event",
        "net/netlink/genetlink.c:ctrl_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588576074,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:rt_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588802511,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/tcp_metrics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588869826,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588939782,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589007799,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589022450,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr_base.c:mr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589194172,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589230756,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/addrlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589241585,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589427299,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589429972,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589537049,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/wireless/wext-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589556586,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_mgmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589558653,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_unlabeled.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589564405,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_cipso_v4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589568469,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589592744,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/dcb/dcbnl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/dcb/dcbnl.c:dcbnl_getfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_bcn_getcfg",
        "net/dcb/dcbnl.c:dcbnl_getapp",
        "net/dcb/dcbnl.c:dcbnl_getnumtcs",
        "net/dcb/dcbnl.c:dcbnl_getcap",
        "net/dcb/dcbnl.c:dcbnl_getpfccfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589628514,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nlmsg_trim",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580420622,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:mk_reply",
        "kernel/taskstats.c:mk_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586631520,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "drivers/net/vxlan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/vxlan.c:vxlan_fdb_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587750735,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:rtnl_net_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587880818,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_fill_parms"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587928084,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588046070,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588086581,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_report_in_port_put",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588090549,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/lwtunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588140989,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_trap_stats_put",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_action_put",
        "net/core/devlink.c:devlink_dpipe_match_put",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588193128,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588206576,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_exts_dump",
        "net/sched/cls_api.c:tc_chain_fill_node",
        "net/sched/cls_api.c:tcf_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588233345,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_dump",
        "net/sched/act_api.c:tcf_action_dump_1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588267092,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:genl_ctrl_event",
        "net/netlink/genetlink.c:ctrl_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588288058,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:rt_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588514447,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/tcp_metrics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588581762,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588651718,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588730855,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588745506,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr_base.c:mr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588919164,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588955748,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/addrlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588966577,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589152291,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589154964,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589263113,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/wireless/wext-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589281162,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_mgmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589283229,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_unlabeled.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589288981,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_cipso_v4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589293045,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589317272,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/dcb/dcbnl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/dcb/dcbnl.c:dcbnl_getfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_bcn_getcfg",
        "net/dcb/dcbnl.c:dcbnl_getapp",
        "net/dcb/dcbnl.c:dcbnl_getnumtcs",
        "net/dcb/dcbnl.c:dcbnl_getcap",
        "net/dcb/dcbnl.c:dcbnl_getpfccfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589353042,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nlmsg_trim",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580464830,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:mk_reply",
        "kernel/taskstats.c:mk_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588369423,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:rtnl_net_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588499810,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_fill_parms"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588547076,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588665190,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588705717,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_report_in_port_put",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588710037,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/lwtunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588760477,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_trap_stats_put",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_action_put",
        "net/core/devlink.c:devlink_dpipe_match_put",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588813304,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588826752,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_exts_dump",
        "net/sched/cls_api.c:tc_chain_fill_node",
        "net/sched/cls_api.c:tcf_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588853521,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_dump",
        "net/sched/act_api.c:tcf_action_dump_1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588887284,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:genl_ctrl_event",
        "net/netlink/genetlink.c:ctrl_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588997081,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netfilter/nf_conntrack_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_exp_stat_cpu_dump",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_expect_event",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_stat_ct",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_ct_stat_cpu_dump",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_conntrack_event",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589012250,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:rt_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589238687,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/tcp_metrics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589306210,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589376166,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589444183,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589458834,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr_base.c:mr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589631036,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589667620,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/addrlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589678449,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589864163,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589866836,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589978313,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/wireless/wext-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589998618,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_mgmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590000685,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_unlabeled.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590006437,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_cipso_v4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590010501,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590034776,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/dcb/dcbnl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/dcb/dcbnl.c:dcbnl_getfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_bcn_getcfg",
        "net/dcb/dcbnl.c:dcbnl_getapp",
        "net/dcb/dcbnl.c:dcbnl_getnumtcs",
        "net/dcb/dcbnl.c:dcbnl_getcap",
        "net/dcb/dcbnl.c:dcbnl_getpfccfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590070546,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nlmsg_trim",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580520494,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:mk_reply",
        "kernel/taskstats.c:mk_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588505071,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:rtnl_net_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588636786,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neightbl_dump_info",
        "net/core/neighbour.c:neightbl_fill_parms"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588684564,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo",
        "net/core/rtnetlink.c:rtnl_fill_vfinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588805046,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588845637,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_report_in_port_put",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588850255,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/lwtunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588901005,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_trap_stats_put",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_resource_put",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_entry_ctx_append",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_table_put",
        "net/core/devlink.c:devlink_dpipe_action_put",
        "net/core/devlink.c:devlink_dpipe_match_put",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588953938,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_fill_tclass",
        "net/sched/sch_api.c:tc_fill_qdisc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588968048,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_exts_dump",
        "net/sched/cls_api.c:tc_chain_fill_node",
        "net/sched/cls_api.c:tcf_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588994945,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tc_dump_action",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_dump",
        "net/sched/act_api.c:tcf_action_dump_1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589029358,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:genl_ctrl_event",
        "net/netlink/genetlink.c:ctrl_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589050842,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:rt_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589279023,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/tcp_metrics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589347954,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_netconf_fill_devconf",
        "net/ipv4/devinet.c:inet_fill_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589419142,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_dump_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589489070,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_rtm_dumplink",
        "net/ipv4/ipmr.c:ipmr_fill_mroute",
        "net/ipv4/ipmr.c:ipmr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589505122,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr_base.c:mr_fill_mroute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589679964,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_fill_ifinfo",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:in6_dump_addrs",
        "net/ipv6/addrconf.c:inet6_fill_ifaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_fill_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589716756,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/addrlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589727585,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589915635,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/seg6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_genl_dumphmac"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589918244,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_fill_mroute",
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590027977,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/wireless/wext-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/wireless/wext-core.c:rtnetlink_ifinfo_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590048650,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_mgmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590050893,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_unlabeled.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590056485,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_cipso_v4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590060581,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590084808,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/dcb/dcbnl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/dcb/dcbnl.c:dcbnl_getfeatcfg",
        "net/dcb/dcbnl.c:dcbnl_bcn_getcfg",
        "net/dcb/dcbnl.c:dcbnl_getapp",
        "net/dcb/dcbnl.c:dcbnl_getnumtcs",
        "net/dcb/dcbnl.c:dcbnl_getcap",
        "net/dcb/dcbnl.c:dcbnl_getpfccfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590120626,
      "name": "nlmsg_trim",
      "external": false,
      "loc": "include/net/netlink.h:923",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info",
        "net/ncsi/ncsi-netlink.c:ncsi_write_package_info"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
void nlmsg_trim(struct sk_buff * skb, const void * mark)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void nlmsg_trim(struct sk_buff * skb, const void * mark)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void nlmsg_trim(struct sk_buff * skb, const void * mark)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void nlmsg_trim(struct sk_buff * skb, const void * mark)
```
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
