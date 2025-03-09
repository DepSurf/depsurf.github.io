# Function: <code>rtnl_notify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rtnl_notify(struct sk_buff * skb, struct net * net, u32 pid, u32 group, struct nlmsghdr * nlh, gfp_t flags)
```

```json
{
  "name": "rtnl_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586357408,
      "name": "rtnl_notify",
      "external": true,
      "loc": "net/core/rtnetlink.c:642",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify"
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
        "net/wireless/wext-core.c:wireless_nlevent_flush",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586357408,
      "name": "rtnl_notify",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rtnl_notify(struct sk_buff * skb, struct net * net, u32 pid, u32 group, struct nlmsghdr * nlh, gfp_t flags)
```

```json
{
  "name": "rtnl_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586791532,
      "name": "rtnl_notify",
      "external": true,
      "loc": "net/core/rtnetlink.c:664",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify"
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
        "net/wireless/wext-core.c:wireless_nlevent_flush",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586790096,
      "name": "rtnl_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void rtnl_notify(struct sk_buff * skb, struct net * net, u32 pid, u32 group, struct nlmsghdr * nlh, gfp_t flags)
```

```json
{
  "name": "rtnl_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586978028,
      "name": "rtnl_notify",
      "external": true,
      "loc": "net/core/rtnetlink.c:665",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify"
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
        "net/wireless/wext-core.c:wireless_nlevent_flush",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586976672,
      "name": "rtnl_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void rtnl_notify(struct sk_buff * skb, struct net * net, u32 pid, u32 group, struct nlmsghdr * nlh, gfp_t flags)
```

```json
{
  "name": "rtnl_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587102860,
      "name": "rtnl_notify",
      "external": true,
      "loc": "net/core/rtnetlink.c:667",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify"
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
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/wireless/wext-core.c:wireless_nlevent_flush",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587101520,
      "name": "rtnl_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void rtnl_notify(struct sk_buff * skb, struct net * net, u32 pid, u32 group, struct nlmsghdr * nlh, gfp_t flags)
```

```json
{
  "name": "rtnl_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587604834,
      "name": "rtnl_notify",
      "external": true,
      "loc": "net/core/rtnetlink.c:640",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify"
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
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/wireless/wext-core.c:wireless_nlevent_flush",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587603488,
      "name": "rtnl_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void rtnl_notify(struct sk_buff * skb, struct net * net, u32 pid, u32 group, struct nlmsghdr * nlh, gfp_t flags)
```

```json
{
  "name": "rtnl_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587914212,
      "name": "rtnl_notify",
      "external": true,
      "loc": "net/core/rtnetlink.c:723",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify"
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
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/wireless/wext-core.c:wireless_nlevent_flush",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587912912,
      "name": "rtnl_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void rtnl_notify(struct sk_buff * skb, struct net * net, u32 pid, u32 group, struct nlmsghdr * nlh, gfp_t flags)
```

```json
{
  "name": "rtnl_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588059197,
      "name": "rtnl_notify",
      "external": true,
      "loc": "net/core/rtnetlink.c:733",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify"
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
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/wireless/wext-core.c:wireless_nlevent_flush",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588057728,
      "name": "rtnl_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void rtnl_notify(struct sk_buff * skb, struct net * net, u32 pid, u32 group, struct nlmsghdr * nlh, gfp_t flags)
```

```json
{
  "name": "rtnl_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588374558,
      "name": "rtnl_notify",
      "external": true,
      "loc": "net/core/rtnetlink.c:728",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify"
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
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/wireless/wext-core.c:wireless_nlevent_flush",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588373072,
      "name": "rtnl_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void rtnl_notify(struct sk_buff * skb, struct net * net, u32 pid, u32 group, struct nlmsghdr * nlh, gfp_t flags)
```

```json
{
  "name": "rtnl_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588580974,
      "name": "rtnl_notify",
      "external": true,
      "loc": "net/core/rtnetlink.c:728",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify"
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
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/wireless/wext-core.c:wireless_nlevent_flush",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588579456,
      "name": "rtnl_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void rtnl_notify(struct sk_buff * skb, struct net * net, u32 pid, u32 group, struct nlmsghdr * nlh, gfp_t flags)
```

```json
{
  "name": "rtnl_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589468655,
      "name": "rtnl_notify",
      "external": true,
      "loc": "net/core/rtnetlink.c:728",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnetlink_event",
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify",
        "net/core/rtnetlink.c:rtmsg_ifinfo_newnet",
        "net/core/rtnetlink.c:rtmsg_ifinfo"
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
        "net/ipv6/route.c:__ip6_del_rt_siblings",
        "net/ipv6/ndisc.c:ndisc_ra_useropt",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/wireless/wext-core.c:wireless_nlevent_flush",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589430896,
      "name": "rtnl_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void rtnl_notify(struct sk_buff * skb, struct net * net, u32 pid, u32 group, struct nlmsghdr * nlh, gfp_t flags)
```

```json
{
  "name": "rtnl_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589469743,
      "name": "rtnl_notify",
      "external": true,
      "loc": "net/core/rtnetlink.c:730",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnetlink_event",
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify",
        "net/core/rtnetlink.c:rtmsg_ifinfo_newnet",
        "net/core/rtnetlink.c:rtmsg_ifinfo"
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
        "net/ipv6/route.c:__ip6_del_rt_siblings",
        "net/ipv6/ndisc.c:ndisc_ra_useropt",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/wireless/wext-core.c:wireless_nlevent_flush",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589431072,
      "name": "rtnl_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void rtnl_notify(struct sk_buff * skb, struct net * net, u32 pid, u32 group, struct nlmsghdr * nlh, gfp_t flags)
```

```json
{
  "name": "rtnl_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589368164,
      "name": "rtnl_notify",
      "external": true,
      "loc": "net/core/rtnetlink.c:732",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnetlink_event",
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify",
        "net/core/rtnetlink.c:rtmsg_ifinfo_newnet",
        "net/core/rtnetlink.c:rtmsg_ifinfo"
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
        "net/ipv6/route.c:__ip6_del_rt_siblings",
        "net/ipv6/ndisc.c:ndisc_ra_useropt",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/wireless/wext-core.c:wireless_nlevent_flush",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589328368,
      "name": "rtnl_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void rtnl_notify(struct sk_buff * skb, struct net * net, u32 pid, u32 group, struct nlmsghdr * nlh, gfp_t flags)
```

```json
{
  "name": "rtnl_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590098484,
      "name": "rtnl_notify",
      "external": true,
      "loc": "net/core/rtnetlink.c:725",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnetlink_event",
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify",
        "net/core/rtnetlink.c:rtmsg_ifinfo_newnet",
        "net/core/rtnetlink.c:rtmsg_ifinfo"
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
        "net/ipv6/route.c:__ip6_del_rt_siblings",
        "net/ipv6/ndisc.c:ndisc_ra_useropt",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/wireless/wext-core.c:wireless_nlevent_flush",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590058128,
      "name": "rtnl_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void rtnl_notify(struct sk_buff * skb, struct net * net, u32 pid, u32 group, struct nlmsghdr * nlh, gfp_t flags)
```

```json
{
  "name": "rtnl_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591648936,
      "name": "rtnl_notify",
      "external": true,
      "loc": "net/core/rtnetlink.c:762",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnetlink_event",
        "net/core/rtnetlink.c:rtnl_offload_xstats_notify",
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify",
        "net/core/rtnetlink.c:rtmsg_ifinfo_newnet",
        "net/core/rtnetlink.c:rtmsg_ifinfo"
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
        "net/ipv6/route.c:__ip6_del_rt_siblings",
        "net/ipv6/ndisc.c:ndisc_ra_useropt",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/wireless/wext-core.c:wireless_nlevent_flush",
        "net/dcb/dcbnl.c:dcbnl_notify",
        "net/mctp/device.c:mctp_addr_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591602768,
      "name": "rtnl_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void rtnl_notify(struct sk_buff * skb, struct net * net, u32 pid, u32 group, const struct nlmsghdr * nlh, gfp_t flags)
```

```json
{
  "name": "rtnl_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593432175,
      "name": "rtnl_notify",
      "external": true,
      "loc": "net/core/rtnetlink.c:763",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnetlink_event",
        "net/core/rtnetlink.c:rtnl_offload_xstats_notify",
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify",
        "net/core/rtnetlink.c:rtmsg_ifinfo_newnet",
        "net/core/rtnetlink.c:rtmsg_ifinfo"
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
        "net/ipv6/route.c:__ip6_del_rt_siblings",
        "net/ipv6/ndisc.c:ndisc_ra_useropt",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/wireless/wext-core.c:wireless_nlevent_flush",
        "net/dcb/dcbnl.c:dcbnl_notify",
        "net/mctp/device.c:mctp_addr_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593383872,
      "name": "rtnl_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void rtnl_notify(struct sk_buff * skb, struct net * net, u32 pid, u32 group, const struct nlmsghdr * nlh, gfp_t flags)
```

```json
{
  "name": "rtnl_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593897167,
      "name": "rtnl_notify",
      "external": true,
      "loc": "net/core/rtnetlink.c:766",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnetlink_event",
        "net/core/rtnetlink.c:rtnl_offload_xstats_notify",
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify",
        "net/core/rtnetlink.c:rtmsg_ifinfo_newnet",
        "net/core/rtnetlink.c:rtmsg_ifinfo"
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
        "net/ipv6/route.c:__ip6_del_rt_siblings",
        "net/ipv6/ndisc.c:ndisc_ra_useropt",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/wireless/wext-core.c:wireless_nlevent_flush",
        "net/dcb/dcbnl.c:dcbnl_notify",
        "net/mctp/device.c:mctp_addr_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593846032,
      "name": "rtnl_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void rtnl_notify(struct sk_buff * skb, struct net * net, u32 pid, u32 group, const struct nlmsghdr * nlh, gfp_t flags)
```

```json
{
  "name": "rtnl_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594680463,
      "name": "rtnl_notify",
      "external": true,
      "loc": "net/core/rtnetlink.c:761",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnetlink_event",
        "net/core/rtnetlink.c:rtnl_offload_xstats_notify",
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify",
        "net/core/rtnetlink.c:rtmsg_ifinfo_newnet",
        "net/core/rtnetlink.c:rtmsg_ifinfo"
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
        "net/ipv6/route.c:__ip6_del_rt_siblings",
        "net/ipv6/ndisc.c:ndisc_ra_useropt",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/wireless/wext-core.c:wireless_nlevent_flush",
        "net/dcb/dcbnl.c:dcbnl_notify",
        "net/mctp/device.c:mctp_addr_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594627696,
      "name": "rtnl_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void rtnl_notify(struct sk_buff * skb, struct net * net, u32 pid, u32 group, struct nlmsghdr * nlh, gfp_t flags)
```

```json
{
  "name": "rtnl_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502126688,
      "name": "rtnl_notify",
      "external": true,
      "loc": "net/core/rtnetlink.c:728",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify"
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
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/wireless/wext-core.c:wireless_nlevent_flush",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502125864,
      "name": "rtnl_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void rtnl_notify(struct sk_buff * skb, struct net * net, u32 pid, u32 group, struct nlmsghdr * nlh, gfp_t flags)
```

```json
{
  "name": "rtnl_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234870912,
      "name": "rtnl_notify",
      "external": true,
      "loc": "net/core/rtnetlink.c:728",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify"
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
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/wireless/wext-core.c:wireless_nlevent_flush",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234868884,
      "name": "rtnl_notify",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void rtnl_notify(struct sk_buff * skb, struct net * net, u32 pid, u32 group, struct nlmsghdr * nlh, gfp_t flags)
```

```json
{
  "name": "rtnl_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295588756,
      "name": "rtnl_notify",
      "external": true,
      "loc": "net/core/rtnetlink.c:728",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify"
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
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/wireless/wext-core.c:wireless_nlevent_flush",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295585680,
      "name": "rtnl_notify",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void rtnl_notify(struct sk_buff * skb, struct net * net, u32 pid, u32 group, struct nlmsghdr * nlh, gfp_t flags)
```

```json
{
  "name": "rtnl_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278389706,
      "name": "rtnl_notify",
      "external": true,
      "loc": "net/core/rtnetlink.c:728",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify"
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
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/wireless/wext-core.c:wireless_nlevent_flush",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278387948,
      "name": "rtnl_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void rtnl_notify(struct sk_buff * skb, struct net * net, u32 pid, u32 group, struct nlmsghdr * nlh, gfp_t flags)
```

```json
{
  "name": "rtnl_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588187710,
      "name": "rtnl_notify",
      "external": true,
      "loc": "net/core/rtnetlink.c:728",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify"
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
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/wireless/wext-core.c:wireless_nlevent_flush",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588186192,
      "name": "rtnl_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void rtnl_notify(struct sk_buff * skb, struct net * net, u32 pid, u32 group, struct nlmsghdr * nlh, gfp_t flags)
```

```json
{
  "name": "rtnl_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587900542,
      "name": "rtnl_notify",
      "external": true,
      "loc": "net/core/rtnetlink.c:728",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify"
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
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/wireless/wext-core.c:wireless_nlevent_flush",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587899024,
      "name": "rtnl_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void rtnl_notify(struct sk_buff * skb, struct net * net, u32 pid, u32 group, struct nlmsghdr * nlh, gfp_t flags)
```

```json
{
  "name": "rtnl_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588519534,
      "name": "rtnl_notify",
      "external": true,
      "loc": "net/core/rtnetlink.c:728",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify"
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
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/wireless/wext-core.c:wireless_nlevent_flush",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588518016,
      "name": "rtnl_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void rtnl_notify(struct sk_buff * skb, struct net * net, u32 pid, u32 group, struct nlmsghdr * nlh, gfp_t flags)
```

```json
{
  "name": "rtnl_notify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588656798,
      "name": "rtnl_notify",
      "external": true,
      "loc": "net/core/rtnetlink.c:728",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_bridge_notify",
        "net/core/rtnetlink.c:rtnl_fdb_notify"
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
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ip6mr.c:mr6_netlink_event",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/wireless/wext-core.c:wireless_nlevent_flush",
        "net/dcb/dcbnl.c:dcbnl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588654944,
      "name": "rtnl_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct nlmsghdr * nlh</code> ➡️ <code>const struct nlmsghdr * nlh</code>
</li>
</ul>
</details>
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
