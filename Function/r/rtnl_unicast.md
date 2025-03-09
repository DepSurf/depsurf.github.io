# Function: <code>rtnl_unicast</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int rtnl_unicast(struct sk_buff * skb, struct net * net, u32 pid)
```

```json
{
  "name": "rtnl_unicast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586357360,
      "name": "rtnl_unicast",
      "external": true,
      "loc": "net/core/rtnetlink.c:634",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_getlink"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/sched/act_api.c:tca_action_gd",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv4/ipmr.c:ip_mroute_setsockopt",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586357360,
      "name": "rtnl_unicast",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int rtnl_unicast(struct sk_buff * skb, struct net * net, u32 pid)
```

```json
{
  "name": "rtnl_unicast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586801500,
      "name": "rtnl_unicast",
      "external": true,
      "loc": "net/core/rtnetlink.c:656",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_getlink"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/sched/act_api.c:tca_action_gd",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586790048,
      "name": "rtnl_unicast",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int rtnl_unicast(struct sk_buff * skb, struct net * net, u32 pid)
```

```json
{
  "name": "rtnl_unicast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586991545,
      "name": "rtnl_unicast",
      "external": true,
      "loc": "net/core/rtnetlink.c:657",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_getlink"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/sched/act_api.c:tca_action_gd",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586976624,
      "name": "rtnl_unicast",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int rtnl_unicast(struct sk_buff * skb, struct net * net, u32 pid)
```

```json
{
  "name": "rtnl_unicast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587117126,
      "name": "rtnl_unicast",
      "external": true,
      "loc": "net/core/rtnetlink.c:659",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_getlink"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/sched/act_api.c:tca_action_gd",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587101472,
      "name": "rtnl_unicast",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int rtnl_unicast(struct sk_buff * skb, struct net * net, u32 pid)
```

```json
{
  "name": "rtnl_unicast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587620735,
      "name": "rtnl_unicast",
      "external": true,
      "loc": "net/core/rtnetlink.c:632",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_getlink"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/sched/act_api.c:tca_action_gd",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587603440,
      "name": "rtnl_unicast",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int rtnl_unicast(struct sk_buff * skb, struct net * net, u32 pid)
```

```json
{
  "name": "rtnl_unicast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587930938,
      "name": "rtnl_unicast",
      "external": true,
      "loc": "net/core/rtnetlink.c:715",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_getlink"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/sched/act_api.c:tca_action_gd",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587912864,
      "name": "rtnl_unicast",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int rtnl_unicast(struct sk_buff * skb, struct net * net, u32 pid)
```

```json
{
  "name": "rtnl_unicast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588080170,
      "name": "rtnl_unicast",
      "external": true,
      "loc": "net/core/rtnetlink.c:725",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_getlink"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_get",
        "net/sched/act_api.c:tca_action_gd",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588057680,
      "name": "rtnl_unicast",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int rtnl_unicast(struct sk_buff * skb, struct net * net, u32 pid)
```

```json
{
  "name": "rtnl_unicast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588395066,
      "name": "rtnl_unicast",
      "external": true,
      "loc": "net/core/rtnetlink.c:720",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_getlink"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_get",
        "net/sched/act_api.c:tca_action_gd",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588373024,
      "name": "rtnl_unicast",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int rtnl_unicast(struct sk_buff * skb, struct net * net, u32 pid)
```

```json
{
  "name": "rtnl_unicast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588601457,
      "name": "rtnl_unicast",
      "external": true,
      "loc": "net/core/rtnetlink.c:720",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_getlink"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_get",
        "net/sched/act_api.c:tca_action_gd",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588579408,
      "name": "rtnl_unicast",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int rtnl_unicast(struct sk_buff * skb, struct net * net, u32 pid)
```

```json
{
  "name": "rtnl_unicast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589460471,
      "name": "rtnl_unicast",
      "external": true,
      "loc": "net/core/rtnetlink.c:720",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_getlink"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_get",
        "net/sched/act_api.c:tca_action_gd",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_cache_resolve",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/ip6mr.c:ip6mr_cache_resolve",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589430848,
      "name": "rtnl_unicast",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int rtnl_unicast(struct sk_buff * skb, struct net * net, u32 pid)
```

```json
{
  "name": "rtnl_unicast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589459031,
      "name": "rtnl_unicast",
      "external": true,
      "loc": "net/core/rtnetlink.c:722",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_getlink"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_get",
        "net/sched/act_api.c:tca_action_gd",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_cache_resolve",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/ip6mr.c:ip6mr_cache_resolve",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589431024,
      "name": "rtnl_unicast",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int rtnl_unicast(struct sk_buff * skb, struct net * net, u32 pid)
```

```json
{
  "name": "rtnl_unicast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589356796,
      "name": "rtnl_unicast",
      "external": true,
      "loc": "net/core/rtnetlink.c:724",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_getlink"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_get",
        "net/sched/act_api.c:tca_action_gd",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/nexthop.c:rtm_get_nexthop_bucket",
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589328320,
      "name": "rtnl_unicast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int rtnl_unicast(struct sk_buff * skb, struct net * net, u32 pid)
```

```json
{
  "name": "rtnl_unicast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590087548,
      "name": "rtnl_unicast",
      "external": true,
      "loc": "net/core/rtnetlink.c:717",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_getlink"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_get",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:tfilter_notify",
        "net/sched/act_api.c:tca_action_gd",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/nexthop.c:rtm_get_nexthop_bucket",
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590058192,
      "name": "rtnl_unicast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int rtnl_unicast(struct sk_buff * skb, struct net * net, u32 pid)
```

```json
{
  "name": "rtnl_unicast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591640946,
      "name": "rtnl_unicast",
      "external": true,
      "loc": "net/core/rtnetlink.c:754",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_getlink"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_get",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:tfilter_notify",
        "net/sched/act_api.c:tca_action_gd",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/nexthop.c:rtm_get_nexthop_bucket",
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_cache_resolve",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591602848,
      "name": "rtnl_unicast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int rtnl_unicast(struct sk_buff * skb, struct net * net, u32 pid)
```

```json
{
  "name": "rtnl_unicast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593423842,
      "name": "rtnl_unicast",
      "external": true,
      "loc": "net/core/rtnetlink.c:755",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_getlink"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_get",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:tfilter_notify",
        "net/sched/act_api.c:tca_action_gd",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/nexthop.c:rtm_get_nexthop_bucket",
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_cache_resolve",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_getroute",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593383968,
      "name": "rtnl_unicast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int rtnl_unicast(struct sk_buff * skb, struct net * net, u32 pid)
```

```json
{
  "name": "rtnl_unicast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593886674,
      "name": "rtnl_unicast",
      "external": true,
      "loc": "net/core/rtnetlink.c:758",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_getlink"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_get",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:tfilter_notify",
        "net/sched/act_api.c:tca_action_gd",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/nexthop.c:rtm_get_nexthop_bucket",
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_cache_resolve",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_getroute",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593846128,
      "name": "rtnl_unicast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int rtnl_unicast(struct sk_buff * skb, struct net * net, u32 pid)
```

```json
{
  "name": "rtnl_unicast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594669858,
      "name": "rtnl_unicast",
      "external": true,
      "loc": "net/core/rtnetlink.c:753",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_getlink"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_get",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:tfilter_notify",
        "net/sched/act_api.c:tca_action_gd",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/nexthop.c:rtm_get_nexthop_bucket",
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_cache_resolve",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/ip6mr.c:ip6mr_rtm_getroute",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594627792,
      "name": "rtnl_unicast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int rtnl_unicast(struct sk_buff * skb, struct net * net, u32 pid)
```

```json
{
  "name": "rtnl_unicast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502148556,
      "name": "rtnl_unicast",
      "external": true,
      "loc": "net/core/rtnetlink.c:720",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_getlink"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_get",
        "net/sched/act_api.c:tca_action_gd",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502125784,
      "name": "rtnl_unicast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int rtnl_unicast(struct sk_buff * skb, struct net * net, u32 pid)
```

```json
{
  "name": "rtnl_unicast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234890756,
      "name": "rtnl_unicast",
      "external": true,
      "loc": "net/core/rtnetlink.c:720",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_getlink"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_get",
        "net/sched/act_api.c:tca_action_gd",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234868836,
      "name": "rtnl_unicast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int rtnl_unicast(struct sk_buff * skb, struct net * net, u32 pid)
```

```json
{
  "name": "rtnl_unicast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295615328,
      "name": "rtnl_unicast",
      "external": true,
      "loc": "net/core/rtnetlink.c:720",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_getlink"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_get",
        "net/sched/act_api.c:tca_action_gd",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295585584,
      "name": "rtnl_unicast",
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
int rtnl_unicast(struct sk_buff * skb, struct net * net, u32 pid)
```

```json
{
  "name": "rtnl_unicast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278405162,
      "name": "rtnl_unicast",
      "external": true,
      "loc": "net/core/rtnetlink.c:720",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_getlink"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_get",
        "net/sched/act_api.c:tca_action_gd",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278387872,
      "name": "rtnl_unicast",
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
int rtnl_unicast(struct sk_buff * skb, struct net * net, u32 pid)
```

```json
{
  "name": "rtnl_unicast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588208193,
      "name": "rtnl_unicast",
      "external": true,
      "loc": "net/core/rtnetlink.c:720",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_getlink"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_get",
        "net/sched/act_api.c:tca_action_gd",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588186144,
      "name": "rtnl_unicast",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int rtnl_unicast(struct sk_buff * skb, struct net * net, u32 pid)
```

```json
{
  "name": "rtnl_unicast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587921025,
      "name": "rtnl_unicast",
      "external": true,
      "loc": "net/core/rtnetlink.c:720",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_getlink"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_get",
        "net/sched/act_api.c:tca_action_gd",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587898976,
      "name": "rtnl_unicast",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int rtnl_unicast(struct sk_buff * skb, struct net * net, u32 pid)
```

```json
{
  "name": "rtnl_unicast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588540017,
      "name": "rtnl_unicast",
      "external": true,
      "loc": "net/core/rtnetlink.c:720",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_getlink"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_get",
        "net/sched/act_api.c:tca_action_gd",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588517968,
      "name": "rtnl_unicast",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int rtnl_unicast(struct sk_buff * skb, struct net * net, u32 pid)
```

```json
{
  "name": "rtnl_unicast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588677423,
      "name": "rtnl_unicast",
      "external": true,
      "loc": "net/core/rtnetlink.c:720",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_getlink"
      ],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/neighbour.c:neigh_get",
        "net/core/neighbour.c:neigh_get",
        "net/sched/act_api.c:tca_action_gd",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/dcb/dcbnl.c:dcb_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588654896,
      "name": "rtnl_unicast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
