# Function: <code>in6_dev_finish_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587231968,
      "name": "in6_dev_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:155",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:ipv6_regen_rndid",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:rt6_ifdown",
        "net/ipv6/ndisc.c:ndisc_constructor",
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_gq_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:ipv6_dev_mc_inc",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587231968,
      "name": "in6_dev_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
void in6_dev_finish_destroy(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587696528,
      "name": "in6_dev_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:155",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_regen_rndid",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/route.c:rt6_ifdown",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_gq_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587696528,
      "name": "in6_dev_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void in6_dev_finish_destroy(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587910880,
      "name": "in6_dev_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:155",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/route.c:rt6_ifdown",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_gq_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587910880,
      "name": "in6_dev_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void in6_dev_finish_destroy(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588069296,
      "name": "in6_dev_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:174",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_ifdown",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_gq_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588069296,
      "name": "in6_dev_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void in6_dev_finish_destroy(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588613472,
      "name": "in6_dev_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:175",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_ifdown",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_gq_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588613472,
      "name": "in6_dev_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "in6_dev_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:214",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_gq_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588979810,
      "name": "in6_dev_finish_destroy.cold.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071588979424,
      "name": "in6_dev_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "in6_dev_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:214",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_gq_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589203826,
      "name": "in6_dev_finish_destroy.cold.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071589203440,
      "name": "in6_dev_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "in6_dev_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:237",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_gq_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589657833,
      "name": "in6_dev_finish_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071589657408,
      "name": "in6_dev_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "in6_dev_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:239",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_gq_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589882233,
      "name": "in6_dev_finish_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071589881824,
      "name": "in6_dev_finish_destroy",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "in6_dev_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:240",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:ipv6_add_dev",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_gq_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590911018,
      "name": "in6_dev_finish_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071590910832,
      "name": "in6_dev_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "in6_dev_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:248",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:ipv6_add_dev",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_gq_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:mld_send_cr",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591637386,
      "name": "in6_dev_finish_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071590974064,
      "name": "in6_dev_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "in6_dev_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:255",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:ipv6_add_dev",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor",
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
        "net/ipv6/mcast.c:mld_del_delrec",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591580814,
      "name": "in6_dev_finish_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071590904944,
      "name": "in6_dev_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "in6_dev_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:255",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:ipv6_add_dev",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor",
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
        "net/ipv6/mcast.c:mld_del_delrec",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592745090,
      "name": "in6_dev_finish_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071591740560,
      "name": "in6_dev_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "in6_dev_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:255",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:ipv6_add_dev",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor",
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
        "net/ipv6/mcast.c:mld_del_delrec",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594631657,
      "name": "in6_dev_finish_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071593445408,
      "name": "in6_dev_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595361712,
      "name": "in6_dev_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:255",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:ipv6_add_dev",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor",
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
        "net/ipv6/mcast.c:mld_del_delrec",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595361712,
      "name": "in6_dev_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595758896,
      "name": "in6_dev_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:255",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:ipv6_add_dev",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor",
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
        "net/ipv6/mcast.c:mld_del_delrec",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595758896,
      "name": "in6_dev_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void in6_dev_finish_destroy(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596607072,
      "name": "in6_dev_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:262",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrconf.c:ipv6_add_dev",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor",
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
        "net/ipv6/mcast.c:mld_del_delrec",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_ifdown",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596607072,
      "name": "in6_dev_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void in6_dev_finish_destroy(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503602936,
      "name": "in6_dev_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:239",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_gq_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503602936,
      "name": "in6_dev_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void in6_dev_finish_destroy(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236247268,
      "name": "in6_dev_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:239",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_gq_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236247268,
      "name": "in6_dev_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void in6_dev_finish_destroy(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297414096,
      "name": "in6_dev_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:239",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_gq_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297414096,
      "name": "in6_dev_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void in6_dev_finish_destroy(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279555030,
      "name": "in6_dev_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:239",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_gq_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279555030,
      "name": "in6_dev_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "in6_dev_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:239",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_gq_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589486601,
      "name": "in6_dev_finish_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071589486192,
      "name": "in6_dev_finish_destroy",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "in6_dev_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:239",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_gq_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589211593,
      "name": "in6_dev_finish_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071589211184,
      "name": "in6_dev_finish_destroy",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "in6_dev_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:239",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_gq_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589927865,
      "name": "in6_dev_finish_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071589927456,
      "name": "in6_dev_finish_destroy",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void in6_dev_finish_destroy(struct inet6_dev * idev)
```

```json
{
  "name": "in6_dev_finish_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "in6_dev_finish_destroy",
      "external": true,
      "loc": "net/ipv6/addrconf_core.c:239",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/addrconf.c:ipv6_add_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:ip6_route_dev_notify",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_dst_ifdown",
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change",
        "net/ipv6/ndisc.c:ndisc_netdev_event",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/ndisc.c:ndisc_send_unsol_na",
        "net/ipv6/ndisc.c:ndisc_constructor",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_gq_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:__ipv6_dev_mc_inc",
        "net/ipv6/mcast.c:mld_clear_delrec",
        "net/ipv6/mcast.c:mld_del_delrec",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589977193,
      "name": "in6_dev_finish_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071589976784,
      "name": "in6_dev_finish_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
