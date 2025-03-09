# Function: <code>in6_dev_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "in6_dev_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587039521,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:275",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_prefix_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587050132,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:275",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:rt6_ifdown",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587097729,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:275",
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
      "addr": 18446744071587150921,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:275",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:ipv6_dev_mc_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587216715,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:275",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "in6_dev_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587488368,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:288",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_prefix_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595540310,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:288",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_ifdown",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587549098,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:288",
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
      "addr": 18446744071587603625,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:288",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:ipv6_dev_mc_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587673627,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:288",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "in6_dev_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587692160,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:290",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_prefix_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595796569,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:290",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_ifdown",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587753530,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:290",
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
      "addr": 18446744071587808245,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:290",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:ipv6_dev_mc_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587882107,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:290",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "in6_dev_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587843043,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:312",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_prefix_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596727907,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:312",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_ifdown",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_dst_ifdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587909509,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:312",
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
      "addr": 18446744071587965655,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:312",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:ipv6_dev_mc_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588039081,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:312",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct inet6_dev * in6_dev_get(const struct net_device * dev)
```

```json
{
  "name": "in6_dev_get",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588372678,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:311",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588402649,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:311",
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
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_dst_ifdown"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries"
      ]
    },
    {
      "addr": 18446744071588444545,
      "name": "in6_dev_get",
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
      "addr": 18446744071588501559,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:311",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:ipv6_dev_mc_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588577359,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:311",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588417874,
      "name": "in6_dev_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
struct inet6_dev * in6_dev_get(const struct net_device * dev)
```

```json
{
  "name": "in6_dev_get",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588730836,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:361",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588761198,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:361",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_dst_ifdown"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries"
      ]
    },
    {
      "addr": 18446744071588805938,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:361",
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
      "addr": 18446744071588864413,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:361",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588942046,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:361",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588779266,
      "name": "in6_dev_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
struct inet6_dev * in6_dev_get(const struct net_device * dev)
```

```json
{
  "name": "in6_dev_get",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588950841,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:369",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588981422,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:369",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_dst_ifdown"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries"
      ]
    },
    {
      "addr": 18446744071589028642,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:369",
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
      "addr": 18446744071589087836,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:369",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589166590,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:369",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588999394,
      "name": "in6_dev_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
struct inet6_dev * in6_dev_get(const struct net_device * dev)
```

```json
{
  "name": "in6_dev_get",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589393955,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589426919,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:ip6_route_check_nh",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_dst_ifdown"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries"
      ]
    },
    {
      "addr": 18446744071589481873,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
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
      "addr": 18446744071589542060,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589621249,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589450322,
      "name": "in6_dev_get",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct inet6_dev * in6_dev_get(const struct net_device * dev)
```

```json
{
  "name": "in6_dev_get",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589618531,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589651255,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:ip6_route_check_nh",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_dst_ifdown"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries"
      ]
    },
    {
      "addr": 18446744071589705745,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
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
      "addr": 18446744071589766140,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589845425,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589674786,
      "name": "in6_dev_get",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct inet6_dev * in6_dev_get(const struct net_device * dev)
```

```json
{
  "name": "in6_dev_get",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590630337,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:352",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590658353,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:352",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:ip6_route_check_nh",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_dst_ifdown"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries"
      ]
    },
    {
      "addr": 18446744071590724851,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:352",
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
      "addr": 18446744071590785820,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:352",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590871498,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:352",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590688190,
      "name": "in6_dev_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
struct inet6_dev * in6_dev_get(const struct net_device * dev)
```

```json
{
  "name": "in6_dev_get",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590690853,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:355",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590720049,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:355",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:ip6_route_check_nh",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_dst_ifdown"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries"
      ]
    },
    {
      "addr": 18446744071590783747,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:355",
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
      "addr": 18446744071590845116,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:355",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590932762,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:355",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591636149,
      "name": "in6_dev_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
struct inet6_dev * in6_dev_get(const struct net_device * dev)
```

```json
{
  "name": "in6_dev_get",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590616101,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:354",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590644673,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:354",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:ip6_route_check_nh",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_dst_ifdown"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries"
      ]
    },
    {
      "addr": 18446744071590710810,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:354",
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
      "addr": 18446744071590768202,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:354",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590862314,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:354",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591579591,
      "name": "in6_dev_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
struct inet6_dev * in6_dev_get(const struct net_device * dev)
```

```json
{
  "name": "in6_dev_get",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591429074,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:354",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591457265,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:354",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:ip6_route_check_nh",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_dst_ifdown"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries"
      ]
    },
    {
      "addr": 18446744071591526858,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:354",
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
      "addr": 18446744071591585263,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:354",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591692383,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:354",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592737781,
      "name": "in6_dev_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
struct inet6_dev * in6_dev_get(const struct net_device * dev)
```

```json
{
  "name": "in6_dev_get",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593107219,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:356",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593138315,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:356",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:ip6_route_check_nh",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_dst_ifdown"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries"
      ]
    },
    {
      "addr": 18446744071593214455,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:356",
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
      "addr": 18446744071593280071,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:356",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593389843,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:356",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594624366,
      "name": "in6_dev_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
  "name": "in6_dev_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595003123,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:356",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071628197865,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:356",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:ip6_route_check_nh",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_dst_ifdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595113700,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:356",
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
      "addr": 18446744071595180967,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:356",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595299139,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:356",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
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
  "name": "in6_dev_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595396555,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:356",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619966521,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:356",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_dst_ifdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595507764,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:356",
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
      "addr": 18446744071595576615,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:356",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595694067,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:356",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
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
  "name": "in6_dev_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596238157,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:364",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622278377,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:364",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_dst_ifdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596351291,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:364",
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
      "addr": 18446744071596419319,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:364",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596542410,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:364",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_ifdown",
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
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
  "name": "in6_dev_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503300072,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511341712,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:ip6_route_check_nh",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_dst_ifdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503396088,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
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
      "addr": 18446603336503465020,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503561192,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
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
  "name": "in6_dev_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235968372,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 3244005312,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:ip6_route_check_nh",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_dst_ifdown"
      ],
      "caller_func": []
    },
    {
      "addr": 3236058852,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
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
      "addr": 3236120608,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 3236208216,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
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
  "name": "in6_dev_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055297054108,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302897432,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:ip6_route_check_nh",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_dst_ifdown"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297169024,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
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
      "addr": 13835058055297251884,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297358800,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
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
  "name": "in6_dev_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279317836,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270873214,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:ip6_route_check_nh",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_dst_ifdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279390074,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
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
      "addr": 18446743936279444786,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279519098,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
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
struct inet6_dev * in6_dev_get(const struct net_device * dev)
```

```json
{
  "name": "in6_dev_get",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589222899,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589255623,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:ip6_route_check_nh",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_dst_ifdown"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries"
      ]
    },
    {
      "addr": 18446744071589310113,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
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
      "addr": 18446744071589370508,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589449793,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589279154,
      "name": "in6_dev_get",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct inet6_dev * in6_dev_get(const struct net_device * dev)
```

```json
{
  "name": "in6_dev_get",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588947891,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588980615,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:ip6_route_check_nh",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_dst_ifdown"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries"
      ]
    },
    {
      "addr": 18446744071589035105,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
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
      "addr": 18446744071589095500,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589174785,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589004146,
      "name": "in6_dev_get",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct inet6_dev * in6_dev_get(const struct net_device * dev)
```

```json
{
  "name": "in6_dev_get",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589659763,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589692487,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:ip6_route_check_nh",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_dst_ifdown"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries"
      ]
    },
    {
      "addr": 18446744071589746977,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
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
      "addr": 18446744071589807372,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589886657,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589716018,
      "name": "in6_dev_get",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct inet6_dev * in6_dev_get(const struct net_device * dev)
```

```json
{
  "name": "in6_dev_get",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589708952,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589742043,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:ip6_route_check_nh",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:ip6_dst_ifdown"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries",
        "net/ipv6/route.c:ip6_route_init_special_entries"
      ]
    },
    {
      "addr": 18446744071589797556,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
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
      "addr": 18446744071589858220,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589938874,
      "name": "in6_dev_get",
      "external": false,
      "loc": "include/net/addrconf.h:350",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589766210,
      "name": "in6_dev_get",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct inet6_dev * in6_dev_get(const struct net_device * dev)
```
</details>
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
struct inet6_dev * in6_dev_get(const struct net_device * dev)
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
struct inet6_dev * in6_dev_get(const struct net_device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct inet6_dev * in6_dev_get(const struct net_device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct inet6_dev * in6_dev_get(const struct net_device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct inet6_dev * in6_dev_get(const struct net_device * dev)
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
