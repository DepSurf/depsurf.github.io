# Function: <code>in6_dev_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void in6_dev_put(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586986952,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:296",
      "file": "net/ipv6/anycast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587009360,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:296",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:ipv6_regen_rndid",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv"
      ],
      "caller_func": [
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv"
      ]
    },
    {
      "addr": 18446744071587058484,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:296",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:rt6_ifdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587097895,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:296",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_constructor",
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_netdev_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587148648,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:296",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_gq_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:ipv6_dev_mc_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587217181,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:296",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587009360,
      "name": "in6_dev_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void in6_dev_put(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587433624,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:309",
      "file": "net/ipv6/anycast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587483398,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:309",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_regen_rndid",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy"
      ],
      "caller_func": [
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr"
      ]
    },
    {
      "addr": 18446744071587524528,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:309",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_ifdown",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587549174,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:309",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587602314,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:309",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_gq_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587674093,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:309",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587826528,
      "name": "in6_dev_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void in6_dev_put(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587637000,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:311",
      "file": "net/ipv6/anycast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587686856,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:311",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy"
      ],
      "caller_func": [
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr"
      ]
    },
    {
      "addr": 18446744071587728882,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:311",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_ifdown",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587753606,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:311",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587806938,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:311",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_gq_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587882573,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:311",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588041082,
      "name": "in6_dev_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void in6_dev_put(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587785977,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:333",
      "file": "net/ipv6/anycast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587837890,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:333",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy"
      ],
      "caller_func": [
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr"
      ]
    },
    {
      "addr": 18446744071587866859,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:333",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_ifdown",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587909585,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:333",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587964301,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:333",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_gq_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588039533,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:333",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587850393,
      "name": "in6_dev_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void in6_dev_put(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588314896,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:332",
      "file": "net/ipv6/anycast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588367024,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:332",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": [
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr"
      ]
    },
    {
      "addr": 18446744071588402824,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:332",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_ifdown",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588444623,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:332",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588499684,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:332",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_gq_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588577709,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:332",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588379753,
      "name": "in6_dev_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void in6_dev_put(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588725158,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:382",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": [
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr"
      ]
    },
    {
      "addr": 18446744071588761020,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:382",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588806016,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:382",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588863819,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:382",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_gq_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588941149,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:382",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588695520,
      "name": "in6_dev_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void in6_dev_put(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588944966,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:390",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": [
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr"
      ]
    },
    {
      "addr": 18446744071588981244,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:390",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589028720,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:390",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589086539,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:390",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_gq_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589165437,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:390",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588913760,
      "name": "in6_dev_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void in6_dev_put(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589388802,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": [
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr"
      ]
    },
    {
      "addr": 18446744071589426748,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589481951,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589541306,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_gq_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589620141,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589356016,
      "name": "in6_dev_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void in6_dev_put(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589613378,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": [
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr"
      ]
    },
    {
      "addr": 18446744071589651084,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589705823,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589765386,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_gq_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589844317,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589580128,
      "name": "in6_dev_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void in6_dev_put(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590623907,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:373",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590658126,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:373",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590724960,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:373",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590784743,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:373",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_gq_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590872287,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:373",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590593856,
      "name": "in6_dev_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void in6_dev_put(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590684595,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:376",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590719822,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:376",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590783861,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:376",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590844039,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:376",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_gq_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590933583,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:376",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590653776,
      "name": "in6_dev_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void in6_dev_put(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590609717,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:375",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590644446,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:375",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590710920,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:375",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590769636,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:375",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_ifc_work",
        "net/ipv6/mcast.c:mld_gq_work",
        "net/ipv6/mcast.c:mld_dad_work",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:mld_query_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590863103,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:375",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590579568,
      "name": "in6_dev_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void in6_dev_put(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591422677,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:375",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591457038,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:375",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591526968,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:375",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591586724,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:375",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_ifc_work",
        "net/ipv6/mcast.c:mld_gq_work",
        "net/ipv6/mcast.c:mld_dad_work",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:mld_query_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591693167,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:375",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591391888,
      "name": "in6_dev_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void in6_dev_put(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593100586,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:377",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593138088,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:377",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593214569,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:377",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593281076,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:377",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_ifc_work",
        "net/ipv6/mcast.c:mld_gq_work",
        "net/ipv6/mcast.c:mld_dad_work",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:mld_query_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593390735,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:377",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593068224,
      "name": "in6_dev_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "in6_dev_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594996183,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:377",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595035400,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:377",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595113818,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:377",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595184786,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:377",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_ifc_work",
        "net/ipv6/mcast.c:mld_gq_work",
        "net/ipv6/mcast.c:mld_dad_work",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:mld_query_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595300063,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:377",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "in6_dev_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595389724,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:377",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595428856,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:377",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595507882,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:377",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595580473,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:377",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_ifc_work",
        "net/ipv6/mcast.c:mld_gq_work",
        "net/ipv6/mcast.c:mld_dad_work",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:mld_query_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595694991,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:377",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "in6_dev_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596231228,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:385",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596270824,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:385",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596351409,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:385",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596423241,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:385",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_ifc_work",
        "net/ipv6/mcast.c:mld_gq_work",
        "net/ipv6/mcast.c:mld_dad_work",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:mld_query_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596542498,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:385",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_ifdown",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "in6_dev_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503293160,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503323544,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503396152,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503458592,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_gq_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503559944,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
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
  "name": "in6_dev_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235962760,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 3235997208,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 3236058928,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor"
      ],
      "caller_func": []
    },
    {
      "addr": 3236119356,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_gq_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec"
      ],
      "caller_func": []
    },
    {
      "addr": 3236207680,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
void in6_dev_put(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297046540,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": [
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr"
      ]
    },
    {
      "addr": 13835058055297091424,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297169112,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297250388,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_gq_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297357924,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297000928,
      "name": "in6_dev_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "in6_dev_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279312538,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279332396,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279390134,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279446252,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_gq_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279518568,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void in6_dev_put(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589217746,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": [
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr"
      ]
    },
    {
      "addr": 18446744071589255452,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589310191,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589369754,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_gq_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589448685,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589184496,
      "name": "in6_dev_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void in6_dev_put(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588942738,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": [
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr"
      ]
    },
    {
      "addr": 18446744071588980444,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589035183,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589094746,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_gq_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589173677,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588909488,
      "name": "in6_dev_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void in6_dev_put(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589654610,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": [
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr"
      ]
    },
    {
      "addr": 18446744071589692316,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589747055,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589806618,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_gq_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589885549,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589621360,
      "name": "in6_dev_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void in6_dev_put(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589703686,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": [
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr"
      ]
    },
    {
      "addr": 18446744071589741870,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589797643,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589857434,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_gq_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589937725,
      "name": "in6_dev_put",
      "external": false,
      "loc": "include/net/addrconf.h:371",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589669888,
      "name": "in6_dev_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void in6_dev_put(struct inet6_dev * idev)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void in6_dev_put(struct inet6_dev * idev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void in6_dev_put(struct inet6_dev * idev)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void in6_dev_put(struct inet6_dev * idev)
```
</details>
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
