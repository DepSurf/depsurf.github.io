# Function: <code>netdev_master_upper_dev_get_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct net_device * netdev_master_upper_dev_get_rcu(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586267456,
      "name": "netdev_master_upper_dev_get_rcu",
      "external": true,
      "loc": "net/core/dev.c:5149",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586267456,
      "name": "netdev_master_upper_dev_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
struct net_device * netdev_master_upper_dev_get_rcu(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586692944,
      "name": "netdev_master_upper_dev_get_rcu",
      "external": true,
      "loc": "net/core/dev.c:5539",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_rcv_finish",
        "net/ipv6/ip6_input.c:ip6_rcv_finish",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/l3mdev/l3mdev.c:l3mdev_get_saddr6",
        "net/l3mdev/l3mdev.c:l3mdev_get_rt6_dst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586692944,
      "name": "netdev_master_upper_dev_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
struct net_device * netdev_master_upper_dev_get_rcu(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586879200,
      "name": "netdev_master_upper_dev_get_rcu",
      "external": true,
      "loc": "net/core/dev.c:5786",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__ip_route_output_key_hash",
        "net/ipv4/route.c:ip_route_input_noref",
        "net/ipv4/ip_input.c:ip_rcv_finish",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv4/ipmr.c:ip_mr_forward",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ip6_rcv_finish",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:addrconf_dst_alloc",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/output_core.c:__ip6_local_out",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586879200,
      "name": "netdev_master_upper_dev_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
struct net_device * netdev_master_upper_dev_get_rcu(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587003632,
      "name": "netdev_master_upper_dev_get_rcu",
      "external": true,
      "loc": "net/core/dev.c:5992",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/ip_input.c:ip_rcv_finish",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ip6_rcv_finish",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:addrconf_dst_alloc",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/output_core.c:__ip6_local_out",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587003632,
      "name": "netdev_master_upper_dev_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct net_device * netdev_master_upper_dev_get_rcu(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587502176,
      "name": "netdev_master_upper_dev_get_rcu",
      "external": true,
      "loc": "net/core/dev.c:6133",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:if_nlmsg_size",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/ip_input.c:ip_rcv_finish",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ip6_rcv_finish",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/output_core.c:__ip6_local_out",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587502176,
      "name": "netdev_master_upper_dev_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
struct net_device * netdev_master_upper_dev_get_rcu(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587805168,
      "name": "netdev_master_upper_dev_get_rcu",
      "external": true,
      "loc": "net/core/dev.c:6263",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:if_nlmsg_size",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/ip_input.c:ip_rcv_finish",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ip6_rcv_finish",
        "net/ipv6/addrconf.c:ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/output_core.c:__ip6_local_out",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587805168,
      "name": "netdev_master_upper_dev_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
struct net_device * netdev_master_upper_dev_get_rcu(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587940720,
      "name": "netdev_master_upper_dev_get_rcu",
      "external": true,
      "loc": "net/core/dev.c:6838",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:if_nlmsg_size",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv_finish",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ip6_rcv_finish",
        "net/ipv6/addrconf.c:ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/output_core.c:__ip6_local_out",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587940720,
      "name": "netdev_master_upper_dev_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct net_device * netdev_master_upper_dev_get_rcu(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588251488,
      "name": "netdev_master_upper_dev_get_rcu",
      "external": true,
      "loc": "net/core/dev.c:6848",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:if_nlmsg_size",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv_finish",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ip6_rcv_finish",
        "net/ipv6/addrconf.c:ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/output_core.c:__ip6_local_out",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588251488,
      "name": "netdev_master_upper_dev_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
struct net_device * netdev_master_upper_dev_get_rcu(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588456704,
      "name": "netdev_master_upper_dev_get_rcu",
      "external": true,
      "loc": "net/core/dev.c:7058",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:if_nlmsg_size",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv_finish",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ip6_rcv_finish",
        "net/ipv6/addrconf.c:ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/output_core.c:__ip6_local_out",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588456704,
      "name": "netdev_master_upper_dev_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct net_device * netdev_master_upper_dev_get_rcu(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589324336,
      "name": "netdev_master_upper_dev_get_rcu",
      "external": true,
      "loc": "net/core/dev.c:7449",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_link_get_size",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/ip_input.c:ip_rcv_finish",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/addrconf.c:ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/output_core.c:__ip6_local_out",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589324336,
      "name": "netdev_master_upper_dev_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct net_device * netdev_master_upper_dev_get_rcu(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589323296,
      "name": "netdev_master_upper_dev_get_rcu",
      "external": true,
      "loc": "net/core/dev.c:7623",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_link_get_size",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/ip_input.c:ip_rcv_finish",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/output_core.c:__ip6_local_out",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589323296,
      "name": "netdev_master_upper_dev_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct net_device * netdev_master_upper_dev_get_rcu(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589219008,
      "name": "netdev_master_upper_dev_get_rcu",
      "external": true,
      "loc": "net/core/dev.c:7882",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_link_get_size",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/output_core.c:__ip6_local_out",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589219008,
      "name": "netdev_master_upper_dev_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
struct net_device * netdev_master_upper_dev_get_rcu(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_master_upper_dev_get_rcu",
      "external": true,
      "loc": "net/core/dev.c:7872",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_link_get_size",
        "net/core/filter.c:xdp_master_redirect",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/output_core.c:__ip6_local_out",
        "net/switchdev/switchdev.c:__switchdev_handle_fdb_add_to_device",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592695737,
      "name": "netdev_master_upper_dev_get_rcu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589948512,
      "name": "netdev_master_upper_dev_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
struct net_device * netdev_master_upper_dev_get_rcu(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_master_upper_dev_get_rcu",
      "external": true,
      "loc": "net/core/dev.c:7403",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_link_get_size",
        "net/core/filter.c:xdp_master_redirect",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/output_core.c:__ip6_local_out",
        "net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup",
        "net/l3mdev/l3mdev.c:l3mdev_fib_table_rcu",
        "net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu",
        "net/l3mdev/l3mdev.c:l3mdev_master_ifindex_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594581413,
      "name": "netdev_master_upper_dev_get_rcu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071591484000,
      "name": "netdev_master_upper_dev_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
struct net_device * netdev_master_upper_dev_get_rcu(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_master_upper_dev_get_rcu",
      "external": true,
      "loc": "net/core/dev.c:7389",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_link_get_size",
        "net/core/filter.c:xdp_master_redirect",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/output_core.c:__ip6_local_out",
        "net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup",
        "net/l3mdev/l3mdev.c:l3mdev_fib_table_rcu",
        "net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu",
        "net/l3mdev/l3mdev.c:l3mdev_master_ifindex_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596323076,
      "name": "netdev_master_upper_dev_get_rcu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593252432,
      "name": "netdev_master_upper_dev_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct net_device * netdev_master_upper_dev_get_rcu(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_master_upper_dev_get_rcu",
      "external": true,
      "loc": "net/core/dev.c:7394",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_link_get_size",
        "net/core/filter.c:xdp_master_redirect",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv4/udp.c:udp4_lib_lookup_skb",
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/udp.c:udp6_lib_lookup_skb",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/output_core.c:__ip6_local_out",
        "net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup",
        "net/l3mdev/l3mdev.c:l3mdev_fib_table_rcu",
        "net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu",
        "net/l3mdev/l3mdev.c:l3mdev_master_ifindex_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596853165,
      "name": "netdev_master_upper_dev_get_rcu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593713280,
      "name": "netdev_master_upper_dev_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct net_device * netdev_master_upper_dev_get_rcu(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_master_upper_dev_get_rcu",
      "external": true,
      "loc": "net/core/dev.c:7512",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_link_get_size",
        "net/core/filter.c:xdp_master_redirect",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv4/udp.c:udp4_lib_lookup_skb",
        "net/ipv4/udp_offload.c:udp4_gro_receive",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ipv6_rcv",
        "net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/udp.c:udp6_lib_lookup_skb",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/udp_offload.c:udp6_gro_receive",
        "net/ipv6/output_core.c:__ip6_local_out",
        "net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_update_flow",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup",
        "net/l3mdev/l3mdev.c:l3mdev_fib_table_rcu",
        "net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu",
        "net/l3mdev/l3mdev.c:l3mdev_master_ifindex_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597778135,
      "name": "netdev_master_upper_dev_get_rcu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071594492512,
      "name": "netdev_master_upper_dev_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
struct net_device * netdev_master_upper_dev_get_rcu(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501981744,
      "name": "netdev_master_upper_dev_get_rcu",
      "external": true,
      "loc": "net/core/dev.c:7058",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:if_nlmsg_size",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv_finish",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ip6_rcv_finish",
        "net/ipv6/addrconf.c:ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/output_core.c:__ip6_local_out",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501981744,
      "name": "netdev_master_upper_dev_get_rcu",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct net_device * netdev_master_upper_dev_get_rcu(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234736044,
      "name": "netdev_master_upper_dev_get_rcu",
      "external": true,
      "loc": "net/core/dev.c:7058",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:if_nlmsg_size",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv_finish",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ip6_rcv_finish",
        "net/ipv6/addrconf.c:ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/output_core.c:__ip6_local_out",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234736044,
      "name": "netdev_master_upper_dev_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
struct net_device * netdev_master_upper_dev_get_rcu(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295410288,
      "name": "netdev_master_upper_dev_get_rcu",
      "external": true,
      "loc": "net/core/dev.c:7058",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:if_nlmsg_size",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv_finish",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ip6_rcv_finish",
        "net/ipv6/addrconf.c:ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/output_core.c:__ip6_local_out",
        "net/8021q/vlan_core.c:__vlan_find_dev_deep_rcu",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295410288,
      "name": "netdev_master_upper_dev_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct net_device * netdev_master_upper_dev_get_rcu(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278280010,
      "name": "netdev_master_upper_dev_get_rcu",
      "external": true,
      "loc": "net/core/dev.c:7058",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:if_nlmsg_size",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv_finish",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ip6_rcv_finish",
        "net/ipv6/addrconf.c:ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/output_core.c:__ip6_local_out",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278280010,
      "name": "netdev_master_upper_dev_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
struct net_device * netdev_master_upper_dev_get_rcu(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588063488,
      "name": "netdev_master_upper_dev_get_rcu",
      "external": true,
      "loc": "net/core/dev.c:7058",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:if_nlmsg_size",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv_finish",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ip6_rcv_finish",
        "net/ipv6/addrconf.c:ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/output_core.c:__ip6_local_out",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588063488,
      "name": "netdev_master_upper_dev_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
struct net_device * netdev_master_upper_dev_get_rcu(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587776576,
      "name": "netdev_master_upper_dev_get_rcu",
      "external": true,
      "loc": "net/core/dev.c:7058",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:if_nlmsg_size",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv_finish",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ip6_rcv_finish",
        "net/ipv6/addrconf.c:ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/output_core.c:__ip6_local_out",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587776576,
      "name": "netdev_master_upper_dev_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
struct net_device * netdev_master_upper_dev_get_rcu(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588395264,
      "name": "netdev_master_upper_dev_get_rcu",
      "external": true,
      "loc": "net/core/dev.c:7058",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:if_nlmsg_size",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv_finish",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ip6_rcv_finish",
        "net/ipv6/addrconf.c:ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/output_core.c:__ip6_local_out",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588395264,
      "name": "netdev_master_upper_dev_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
struct net_device * netdev_master_upper_dev_get_rcu(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588531280,
      "name": "netdev_master_upper_dev_get_rcu",
      "external": true,
      "loc": "net/core/dev.c:7058",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:if_nlmsg_size",
        "net/core/lwt_bpf.c:bpf_lwt_xmit_reroute",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/ip_input.c:ip_sublist_rcv",
        "net/ipv4/ip_input.c:ip_rcv_finish",
        "net/ipv4/ip_output.c:__ip_local_out",
        "net/ipv6/ip6_output.c:ip6_xmit",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ip6_rcv_finish",
        "net/ipv6/addrconf.c:ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:ipv6_chk_addr_and_flags",
        "net/ipv6/addrconf.c:ipv6_dev_get_saddr",
        "net/ipv6/route.c:ip6_rt_get_dev_rcu",
        "net/ipv6/ndisc.c:ndisc_recv_ns",
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/output_core.c:__ip6_local_out",
        "net/l3mdev/l3mdev.c:l3mdev_link_scope_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588531280,
      "name": "netdev_master_upper_dev_get_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
