# Function: <code>rtnl_set_sk_err</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rtnl_set_sk_err(struct net * net, u32 group, int error)
```

```json
{
  "name": "rtnl_set_sk_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586357472,
      "name": "rtnl_set_sk_err",
      "external": true,
      "loc": "net/core/rtnetlink.c:655",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify",
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_notifyid",
        "net/core/neighbour.c:__neigh_notify",
        "net/core/fib_rules.c:notify_rule_change",
        "net/ipv4/devinet.c:rtmsg_ifa",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/ipmr.c:mroute_netlink_event",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_ifinfo_notify",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586357472,
      "name": "rtnl_set_sk_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void rtnl_set_sk_err(struct net * net, u32 group, int error)
```

```json
{
  "name": "rtnl_set_sk_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586791487,
      "name": "rtnl_set_sk_err",
      "external": true,
      "loc": "net/core/rtnetlink.c:677",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify",
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_notifyid",
        "net/core/neighbour.c:__neigh_notify",
        "net/core/fib_rules.c:notify_rule_change",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf",
        "net/ipv4/devinet.c:rtmsg_ifa",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/ipmr.c:mroute_netlink_event",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_ifinfo_notify",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586790176,
      "name": "rtnl_set_sk_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void rtnl_set_sk_err(struct net * net, u32 group, int error)
```

```json
{
  "name": "rtnl_set_sk_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586977983,
      "name": "rtnl_set_sk_err",
      "external": true,
      "loc": "net/core/rtnetlink.c:678",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify",
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_notifyid",
        "net/core/neighbour.c:__neigh_notify",
        "net/core/fib_rules.c:notify_rule_change",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf",
        "net/ipv4/devinet.c:rtmsg_ifa",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/ipmr.c:mroute_netlink_event",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_ifinfo_notify",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586976752,
      "name": "rtnl_set_sk_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void rtnl_set_sk_err(struct net * net, u32 group, int error)
```

```json
{
  "name": "rtnl_set_sk_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587102830,
      "name": "rtnl_set_sk_err",
      "external": true,
      "loc": "net/core/rtnetlink.c:680",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify",
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_notifyid",
        "net/core/neighbour.c:__neigh_notify",
        "net/core/fib_rules.c:notify_rule_change",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf",
        "net/ipv4/devinet.c:rtmsg_ifa",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/ipmr.c:mroute_netlink_event",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_ifinfo_notify",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587101584,
      "name": "rtnl_set_sk_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void rtnl_set_sk_err(struct net * net, u32 group, int error)
```

```json
{
  "name": "rtnl_set_sk_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587604804,
      "name": "rtnl_set_sk_err",
      "external": true,
      "loc": "net/core/rtnetlink.c:653",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify",
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_notifyid",
        "net/core/neighbour.c:__neigh_notify",
        "net/core/fib_rules.c:notify_rule_change",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf",
        "net/ipv4/devinet.c:rtmsg_ifa",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/ipmr.c:mroute_netlink_event",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_ifinfo_notify",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587603552,
      "name": "rtnl_set_sk_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void rtnl_set_sk_err(struct net * net, u32 group, int error)
```

```json
{
  "name": "rtnl_set_sk_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587914283,
      "name": "rtnl_set_sk_err",
      "external": true,
      "loc": "net/core/rtnetlink.c:736",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify",
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_notifyid",
        "net/core/neighbour.c:__neigh_notify",
        "net/core/fib_rules.c:notify_rule_change",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf",
        "net/ipv4/devinet.c:rtmsg_ifa",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/ipmr.c:mroute_netlink_event",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_ifinfo_notify",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587912976,
      "name": "rtnl_set_sk_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void rtnl_set_sk_err(struct net * net, u32 group, int error)
```

```json
{
  "name": "rtnl_set_sk_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588059268,
      "name": "rtnl_set_sk_err",
      "external": true,
      "loc": "net/core/rtnetlink.c:746",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify",
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_notifyid",
        "net/core/neighbour.c:__neigh_notify",
        "net/core/fib_rules.c:notify_rule_change",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf",
        "net/ipv4/devinet.c:rtmsg_ifa",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/ipmr.c:mroute_netlink_event",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_ifinfo_notify",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588057792,
      "name": "rtnl_set_sk_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void rtnl_set_sk_err(struct net * net, u32 group, int error)
```

```json
{
  "name": "rtnl_set_sk_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588374630,
      "name": "rtnl_set_sk_err",
      "external": true,
      "loc": "net/core/rtnetlink.c:741",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify",
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_notifyid",
        "net/core/neighbour.c:__neigh_notify",
        "net/core/fib_rules.c:notify_rule_change",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf",
        "net/ipv4/devinet.c:rtmsg_ifa",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/nexthop.c:nexthop_notify",
        "net/ipv4/ipmr.c:mroute_netlink_event",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_ifinfo_notify",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf",
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588373136,
      "name": "rtnl_set_sk_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void rtnl_set_sk_err(struct net * net, u32 group, int error)
```

```json
{
  "name": "rtnl_set_sk_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588581048,
      "name": "rtnl_set_sk_err",
      "external": true,
      "loc": "net/core/rtnetlink.c:741",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify",
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_notifyid",
        "net/core/neighbour.c:__neigh_notify",
        "net/core/fib_rules.c:notify_rule_change",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf",
        "net/ipv4/devinet.c:rtmsg_ifa",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/nexthop.c:nexthop_notify",
        "net/ipv4/ipmr.c:mroute_netlink_event",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_ifinfo_notify",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf",
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588579520,
      "name": "rtnl_set_sk_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void rtnl_set_sk_err(struct net * net, u32 group, int error)
```

```json
{
  "name": "rtnl_set_sk_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589435352,
      "name": "rtnl_set_sk_err",
      "external": true,
      "loc": "net/core/rtnetlink.c:741",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify",
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_notifyid",
        "net/core/neighbour.c:__neigh_notify",
        "net/core/fib_rules.c:notify_rule_change",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf",
        "net/ipv4/devinet.c:rtmsg_ifa",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/nexthop.c:nexthop_notify",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/ipv4/ipmr.c:mroute_netlink_event",
        "net/ipv6/addrconf.c:inet6_ifinfo_notify",
        "net/ipv6/addrconf.c:inet6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf",
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/ndisc.c:ndisc_ra_useropt",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589430960,
      "name": "rtnl_set_sk_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void rtnl_set_sk_err(struct net * net, u32 group, int error)
```

```json
{
  "name": "rtnl_set_sk_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589435848,
      "name": "rtnl_set_sk_err",
      "external": true,
      "loc": "net/core/rtnetlink.c:743",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify",
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_notifyid",
        "net/core/neighbour.c:__neigh_notify",
        "net/core/fib_rules.c:notify_rule_change",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf",
        "net/ipv4/devinet.c:rtmsg_ifa",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/nexthop.c:nexthop_notify",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/ipv4/ipmr.c:mroute_netlink_event",
        "net/ipv6/addrconf.c:inet6_ifinfo_notify",
        "net/ipv6/addrconf.c:inet6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf",
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/ndisc.c:ndisc_ra_useropt",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589431136,
      "name": "rtnl_set_sk_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void rtnl_set_sk_err(struct net * net, u32 group, int error)
```

```json
{
  "name": "rtnl_set_sk_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589333432,
      "name": "rtnl_set_sk_err",
      "external": true,
      "loc": "net/core/rtnetlink.c:745",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify",
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_notifyid",
        "net/core/neighbour.c:__neigh_notify",
        "net/core/fib_rules.c:notify_rule_change",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf",
        "net/ipv4/devinet.c:rtmsg_ifa",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_trie.c:fib_alias_hw_flags_set",
        "net/ipv4/nexthop.c:nh_res_bucket_migrate",
        "net/ipv4/nexthop.c:nexthop_notify",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/ipv4/ipmr.c:mroute_netlink_event",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_ifinfo_notify",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf",
        "net/ipv6/route.c:fib6_info_hw_flags_set",
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/ndisc.c:ndisc_ra_useropt",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589328432,
      "name": "rtnl_set_sk_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void rtnl_set_sk_err(struct net * net, u32 group, int error)
```

```json
{
  "name": "rtnl_set_sk_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590063480,
      "name": "rtnl_set_sk_err",
      "external": true,
      "loc": "net/core/rtnetlink.c:734",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify",
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_notifyid",
        "net/core/neighbour.c:__neigh_notify",
        "net/core/fib_rules.c:notify_rule_change",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf",
        "net/ipv4/devinet.c:rtmsg_ifa",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_trie.c:fib_alias_hw_flags_set",
        "net/ipv4/nexthop.c:nh_res_table_upkeep",
        "net/ipv4/nexthop.c:nexthop_notify",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/ipv4/ipmr.c:mroute_netlink_event",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_ifinfo_notify",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf",
        "net/ipv6/route.c:fib6_info_hw_flags_set",
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/ndisc.c:ndisc_ra_useropt",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590058240,
      "name": "rtnl_set_sk_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void rtnl_set_sk_err(struct net * net, u32 group, int error)
```

```json
{
  "name": "rtnl_set_sk_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591640034,
      "name": "rtnl_set_sk_err",
      "external": true,
      "loc": "net/core/rtnetlink.c:771",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_offload_xstats_notify",
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify",
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_notifyid",
        "net/core/neighbour.c:__neigh_notify",
        "net/core/fib_rules.c:notify_rule_change",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf",
        "net/ipv4/devinet.c:rtmsg_ifa",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_trie.c:fib_alias_hw_flags_set",
        "net/ipv4/nexthop.c:nh_res_table_upkeep",
        "net/ipv4/nexthop.c:nexthop_notify",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/ipv4/ipmr.c:mroute_netlink_event",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_ifinfo_notify",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf",
        "net/ipv6/route.c:fib6_info_hw_flags_set",
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/ndisc.c:ndisc_ra_useropt",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/dcb/dcbnl.c:dcbnl_notify",
        "net/mctp/device.c:mctp_addr_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591602912,
      "name": "rtnl_set_sk_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void rtnl_set_sk_err(struct net * net, u32 group, int error)
```

```json
{
  "name": "rtnl_set_sk_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593422898,
      "name": "rtnl_set_sk_err",
      "external": true,
      "loc": "net/core/rtnetlink.c:772",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_offload_xstats_notify",
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify",
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_notifyid",
        "net/core/neighbour.c:__neigh_notify",
        "net/core/fib_rules.c:notify_rule_change",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf",
        "net/ipv4/devinet.c:rtmsg_ifa",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_trie.c:fib_alias_hw_flags_set",
        "net/ipv4/nexthop.c:nh_res_bucket_migrate",
        "net/ipv4/nexthop.c:nexthop_notify",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/ipv4/ipmr.c:mroute_netlink_event",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_ifinfo_notify",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf",
        "net/ipv6/route.c:fib6_info_hw_flags_set",
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/ndisc.c:ndisc_ra_useropt",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/dcb/dcbnl.c:dcbnl_notify",
        "net/mctp/device.c:mctp_addr_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593384048,
      "name": "rtnl_set_sk_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void rtnl_set_sk_err(struct net * net, u32 group, int error)
```

```json
{
  "name": "rtnl_set_sk_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593885730,
      "name": "rtnl_set_sk_err",
      "external": true,
      "loc": "net/core/rtnetlink.c:775",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_offload_xstats_notify",
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify",
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_notifyid",
        "net/core/neighbour.c:__neigh_notify",
        "net/core/fib_rules.c:notify_rule_change",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf",
        "net/ipv4/devinet.c:rtmsg_ifa",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_trie.c:fib_alias_hw_flags_set",
        "net/ipv4/nexthop.c:nh_res_bucket_migrate",
        "net/ipv4/nexthop.c:nexthop_notify",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/ipv4/ipmr.c:mroute_netlink_event",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_ifinfo_notify",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf",
        "net/ipv6/route.c:fib6_info_hw_flags_set",
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/ndisc.c:ndisc_ra_useropt",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/dcb/dcbnl.c:dcbnl_notify",
        "net/mctp/device.c:mctp_addr_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593846208,
      "name": "rtnl_set_sk_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void rtnl_set_sk_err(struct net * net, u32 group, int error)
```

```json
{
  "name": "rtnl_set_sk_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594668914,
      "name": "rtnl_set_sk_err",
      "external": true,
      "loc": "net/core/rtnetlink.c:770",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_offload_xstats_notify",
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify",
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_notifyid",
        "net/core/neighbour.c:__neigh_notify",
        "net/core/fib_rules.c:notify_rule_change",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf",
        "net/ipv4/devinet.c:rtmsg_ifa",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/fib_trie.c:fib_alias_hw_flags_set",
        "net/ipv4/nexthop.c:nh_res_bucket_migrate",
        "net/ipv4/nexthop.c:nexthop_notify",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/ipv4/ipmr.c:mroute_netlink_event",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_ifinfo_notify",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf",
        "net/ipv6/route.c:fib6_info_hw_flags_set",
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/ndisc.c:ndisc_ra_useropt",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/dcb/dcbnl.c:dcbnl_notify",
        "net/mctp/device.c:mctp_addr_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594627872,
      "name": "rtnl_set_sk_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void rtnl_set_sk_err(struct net * net, u32 group, int error)
```

```json
{
  "name": "rtnl_set_sk_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502126800,
      "name": "rtnl_set_sk_err",
      "external": true,
      "loc": "net/core/rtnetlink.c:741",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify",
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_notifyid",
        "net/core/neighbour.c:__neigh_notify",
        "net/core/fib_rules.c:notify_rule_change",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf",
        "net/ipv4/devinet.c:rtmsg_ifa",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/nexthop.c:nexthop_notify",
        "net/ipv4/ipmr.c:mroute_netlink_event",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_ifinfo_notify",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf",
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502125976,
      "name": "rtnl_set_sk_err",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void rtnl_set_sk_err(struct net * net, u32 group, int error)
```

```json
{
  "name": "rtnl_set_sk_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234871032,
      "name": "rtnl_set_sk_err",
      "external": true,
      "loc": "net/core/rtnetlink.c:741",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify",
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_notifyid",
        "net/core/neighbour.c:__neigh_notify",
        "net/core/fib_rules.c:notify_rule_change",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf",
        "net/ipv4/devinet.c:rtmsg_ifa",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/nexthop.c:nexthop_notify",
        "net/ipv4/ipmr.c:mroute_netlink_event",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_ifinfo_notify",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf",
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234868956,
      "name": "rtnl_set_sk_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void rtnl_set_sk_err(struct net * net, u32 group, int error)
```

```json
{
  "name": "rtnl_set_sk_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295588924,
      "name": "rtnl_set_sk_err",
      "external": true,
      "loc": "net/core/rtnetlink.c:741",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify",
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_notifyid",
        "net/core/neighbour.c:__neigh_notify",
        "net/core/fib_rules.c:notify_rule_change",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf",
        "net/ipv4/devinet.c:rtmsg_ifa",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/nexthop.c:nexthop_notify",
        "net/ipv4/ipmr.c:mroute_netlink_event",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_ifinfo_notify",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf",
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295585808,
      "name": "rtnl_set_sk_err",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void rtnl_set_sk_err(struct net * net, u32 group, int error)
```

```json
{
  "name": "rtnl_set_sk_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278389784,
      "name": "rtnl_set_sk_err",
      "external": true,
      "loc": "net/core/rtnetlink.c:741",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify",
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_notifyid",
        "net/core/neighbour.c:__neigh_notify",
        "net/core/fib_rules.c:notify_rule_change",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf",
        "net/ipv4/devinet.c:rtmsg_ifa",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/nexthop.c:nexthop_notify",
        "net/ipv4/ipmr.c:mroute_netlink_event",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_ifinfo_notify",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf",
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278388044,
      "name": "rtnl_set_sk_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void rtnl_set_sk_err(struct net * net, u32 group, int error)
```

```json
{
  "name": "rtnl_set_sk_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588187784,
      "name": "rtnl_set_sk_err",
      "external": true,
      "loc": "net/core/rtnetlink.c:741",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify",
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_notifyid",
        "net/core/neighbour.c:__neigh_notify",
        "net/core/fib_rules.c:notify_rule_change",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf",
        "net/ipv4/devinet.c:rtmsg_ifa",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/nexthop.c:nexthop_notify",
        "net/ipv4/ipmr.c:mroute_netlink_event",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_ifinfo_notify",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf",
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588186256,
      "name": "rtnl_set_sk_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void rtnl_set_sk_err(struct net * net, u32 group, int error)
```

```json
{
  "name": "rtnl_set_sk_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587900616,
      "name": "rtnl_set_sk_err",
      "external": true,
      "loc": "net/core/rtnetlink.c:741",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify",
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb"
      ],
      "caller_func": [
        "drivers/net/vxlan.c:__vxlan_fdb_notify",
        "net/core/net_namespace.c:rtnl_net_notifyid",
        "net/core/neighbour.c:__neigh_notify",
        "net/core/fib_rules.c:notify_rule_change",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf",
        "net/ipv4/devinet.c:rtmsg_ifa",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/nexthop.c:nexthop_notify",
        "net/ipv4/ipmr.c:mroute_netlink_event",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_ifinfo_notify",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf",
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587899088,
      "name": "rtnl_set_sk_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void rtnl_set_sk_err(struct net * net, u32 group, int error)
```

```json
{
  "name": "rtnl_set_sk_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588519608,
      "name": "rtnl_set_sk_err",
      "external": true,
      "loc": "net/core/rtnetlink.c:741",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify",
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_notifyid",
        "net/core/neighbour.c:__neigh_notify",
        "net/core/fib_rules.c:notify_rule_change",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf",
        "net/ipv4/devinet.c:rtmsg_ifa",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/nexthop.c:nexthop_notify",
        "net/ipv4/ipmr.c:mroute_netlink_event",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_ifinfo_notify",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf",
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588518080,
      "name": "rtnl_set_sk_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void rtnl_set_sk_err(struct net * net, u32 group, int error)
```

```json
{
  "name": "rtnl_set_sk_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588656872,
      "name": "rtnl_set_sk_err",
      "external": true,
      "loc": "net/core/rtnetlink.c:741",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify",
        "net/core/rtnetlink.c:rtmsg_ifinfo_build_skb"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_notifyid",
        "net/core/neighbour.c:__neigh_notify",
        "net/core/fib_rules.c:notify_rule_change",
        "net/ipv4/devinet.c:inet_netconf_notify_devconf",
        "net/ipv4/devinet.c:rtmsg_ifa",
        "net/ipv4/fib_semantics.c:rtmsg_fib",
        "net/ipv4/nexthop.c:nexthop_notify",
        "net/ipv4/ipmr.c:mroute_netlink_event",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_ifinfo_notify",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_notify_devconf",
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588655008,
      "name": "rtnl_set_sk_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
