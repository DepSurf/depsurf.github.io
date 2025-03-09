# Function: <code>nla_find</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct nlattr * nla_find(const struct nlattr * head, int len, int attrtype)
```

```json
{
  "name": "nla_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583126928,
      "name": "nla_find",
      "external": true,
      "loc": "lib/nlattr.c:222",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_getlink",
        "net/core/filter.c:__skb_get_nlattr_nest",
        "net/core/filter.c:__skb_get_nlattr",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583126928,
      "name": "nla_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
struct nlattr * nla_find(const struct nlattr * head, int len, int attrtype)
```

```json
{
  "name": "nla_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583421072,
      "name": "nla_find",
      "external": true,
      "loc": "lib/nlattr.c:222",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_bridge_getlink",
        "net/core/filter.c:__skb_get_nlattr_nest",
        "net/core/filter.c:__skb_get_nlattr",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/switchdev/switchdev.c:switchdev_port_bridge_dellink",
        "net/switchdev/switchdev.c:switchdev_port_bridge_setlink",
        "net/switchdev/switchdev.c:switchdev_port_bridge_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583421072,
      "name": "nla_find",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct nlattr * nla_find(const struct nlattr * head, int len, int attrtype)
```

```json
{
  "name": "nla_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583546752,
      "name": "nla_find",
      "external": true,
      "loc": "lib/nlattr.c:222",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_bridge_getlink",
        "net/core/filter.c:__skb_get_nlattr_nest",
        "net/core/filter.c:__skb_get_nlattr",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/switchdev/switchdev.c:switchdev_port_bridge_dellink",
        "net/switchdev/switchdev.c:switchdev_port_bridge_setlink",
        "net/switchdev/switchdev.c:switchdev_port_bridge_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583546752,
      "name": "nla_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct nlattr * nla_find(const struct nlattr * head, int len, int attrtype)
```

```json
{
  "name": "nla_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583584464,
      "name": "nla_find",
      "external": true,
      "loc": "lib/nlattr.c:230",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_bridge_getlink",
        "net/core/filter.c:__skb_get_nlattr_nest",
        "net/core/filter.c:__skb_get_nlattr",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add",
        "net/switchdev/switchdev.c:switchdev_port_bridge_dellink",
        "net/switchdev/switchdev.c:switchdev_port_bridge_setlink",
        "net/switchdev/switchdev.c:switchdev_port_bridge_setlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583584464,
      "name": "nla_find",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct nlattr * nla_find(const struct nlattr * head, int len, int attrtype)
```

```json
{
  "name": "nla_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583830336,
      "name": "nla_find",
      "external": true,
      "loc": "lib/nlattr.c:284",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_bridge_getlink",
        "net/core/filter.c:__skb_get_nlattr_nest",
        "net/core/filter.c:__skb_get_nlattr",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583830336,
      "name": "nla_find",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nlattr * nla_find(const struct nlattr * head, int len, int attrtype)
```

```json
{
  "name": "nla_find",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584032384,
      "name": "nla_find",
      "external": true,
      "loc": "lib/nlattr.c:284",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_bridge_getlink",
        "net/core/filter.c:bpf_skb_get_nlattr_nest",
        "net/core/filter.c:bpf_skb_get_nlattr",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584032384,
      "name": "nla_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
struct nlattr * nla_find(const struct nlattr * head, int len, int attrtype)
```

```json
{
  "name": "nla_find",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584113568,
      "name": "nla_find",
      "external": true,
      "loc": "lib/nlattr.c:459",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/filter.c:bpf_skb_get_nlattr_nest",
        "net/core/filter.c:bpf_skb_get_nlattr",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584113568,
      "name": "nla_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
struct nlattr * nla_find(const struct nlattr * head, int len, int attrtype)
```

```json
{
  "name": "nla_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584301376,
      "name": "nla_find",
      "external": true,
      "loc": "lib/nlattr.c:491",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/filter.c:bpf_skb_get_nlattr_nest",
        "net/core/filter.c:bpf_skb_get_nlattr",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584301376,
      "name": "nla_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
struct nlattr * nla_find(const struct nlattr * head, int len, int attrtype)
```

```json
{
  "name": "nla_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584436096,
      "name": "nla_find",
      "external": true,
      "loc": "lib/nlattr.c:491",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/filter.c:bpf_skb_get_nlattr_nest",
        "net/core/filter.c:bpf_skb_get_nlattr",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584436096,
      "name": "nla_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
struct nlattr * nla_find(const struct nlattr * head, int len, int attrtype)
```

```json
{
  "name": "nla_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584998592,
      "name": "nla_find",
      "external": true,
      "loc": "lib/nlattr.c:643",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/filter.c:bpf_skb_get_nlattr_nest",
        "net/core/filter.c:bpf_skb_get_nlattr",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584998592,
      "name": "nla_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
struct nlattr * nla_find(const struct nlattr * head, int len, int attrtype)
```

```json
{
  "name": "nla_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585119040,
      "name": "nla_find",
      "external": true,
      "loc": "lib/nlattr.c:698",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/filter.c:bpf_skb_get_nlattr_nest",
        "net/core/filter.c:bpf_skb_get_nlattr",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585119040,
      "name": "nla_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
struct nlattr * nla_find(const struct nlattr * head, int len, int attrtype)
```

```json
{
  "name": "nla_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584999312,
      "name": "nla_find",
      "external": true,
      "loc": "lib/nlattr.c:698",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/filter.c:bpf_skb_get_nlattr_nest",
        "net/core/filter.c:bpf_skb_get_nlattr",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584999312,
      "name": "nla_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct nlattr * nla_find(const struct nlattr * head, int len, int attrtype)
```

```json
{
  "name": "nla_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585440528,
      "name": "nla_find",
      "external": true,
      "loc": "lib/nlattr.c:698",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/filter.c:bpf_skb_get_nlattr_nest",
        "net/core/filter.c:bpf_skb_get_nlattr",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585440528,
      "name": "nla_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct nlattr * nla_find(const struct nlattr * head, int len, int attrtype)
```

```json
{
  "name": "nla_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586581088,
      "name": "nla_find",
      "external": true,
      "loc": "lib/nlattr.c:698",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/filter.c:bpf_skb_get_nlattr_nest",
        "net/core/filter.c:bpf_skb_get_nlattr",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586581088,
      "name": "nla_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
struct nlattr * nla_find(const struct nlattr * head, int len, int attrtype)
```

```json
{
  "name": "nla_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587820944,
      "name": "nla_find",
      "external": true,
      "loc": "lib/nlattr.c:713",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/filter.c:bpf_skb_get_nlattr_nest",
        "net/core/filter.c:bpf_skb_get_nlattr",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587820944,
      "name": "nla_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
struct nlattr * nla_find(const struct nlattr * head, int len, int attrtype)
```

```json
{
  "name": "nla_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588092368,
      "name": "nla_find",
      "external": true,
      "loc": "lib/nlattr.c:713",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/filter.c:bpf_skb_get_nlattr_nest",
        "net/core/filter.c:bpf_skb_get_nlattr",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588092368,
      "name": "nla_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
struct nlattr * nla_find(const struct nlattr * head, int len, int attrtype)
```

```json
{
  "name": "nla_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588428224,
      "name": "nla_find",
      "external": true,
      "loc": "lib/nlattr.c:745",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/filter.c:bpf_skb_get_nlattr_nest",
        "net/core/filter.c:bpf_skb_get_nlattr",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588428224,
      "name": "nla_find",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct nlattr * nla_find(const struct nlattr * head, int len, int attrtype)
```

```json
{
  "name": "nla_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496321288,
      "name": "nla_find",
      "external": true,
      "loc": "lib/nlattr.c:491",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/filter.c:bpf_skb_get_nlattr_nest",
        "net/core/filter.c:bpf_skb_get_nlattr",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496321288,
      "name": "nla_find",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct nlattr * nla_find(const struct nlattr * head, int len, int attrtype)
```

```json
{
  "name": "nla_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229655860,
      "name": "nla_find",
      "external": true,
      "loc": "lib/nlattr.c:491",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/filter.c:bpf_skb_get_nlattr_nest",
        "net/core/filter.c:bpf_skb_get_nlattr",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229655860,
      "name": "nla_find",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct nlattr * nla_find(const struct nlattr * head, int len, int attrtype)
```

```json
{
  "name": "nla_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290638432,
      "name": "nla_find",
      "external": true,
      "loc": "lib/nlattr.c:491",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/filter.c:bpf_skb_get_nlattr_nest",
        "net/core/filter.c:bpf_skb_get_nlattr",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290638432,
      "name": "nla_find",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct nlattr * nla_find(const struct nlattr * head, int len, int attrtype)
```

```json
{
  "name": "nla_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275373576,
      "name": "nla_find",
      "external": true,
      "loc": "lib/nlattr.c:491",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/filter.c:bpf_skb_get_nlattr_nest",
        "net/core/filter.c:bpf_skb_get_nlattr",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275373576,
      "name": "nla_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
struct nlattr * nla_find(const struct nlattr * head, int len, int attrtype)
```

```json
{
  "name": "nla_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584404832,
      "name": "nla_find",
      "external": true,
      "loc": "lib/nlattr.c:491",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/filter.c:bpf_skb_get_nlattr_nest",
        "net/core/filter.c:bpf_skb_get_nlattr",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584404832,
      "name": "nla_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
struct nlattr * nla_find(const struct nlattr * head, int len, int attrtype)
```

```json
{
  "name": "nla_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584340032,
      "name": "nla_find",
      "external": true,
      "loc": "lib/nlattr.c:491",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/filter.c:bpf_skb_get_nlattr_nest",
        "net/core/filter.c:bpf_skb_get_nlattr",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584340032,
      "name": "nla_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
struct nlattr * nla_find(const struct nlattr * head, int len, int attrtype)
```

```json
{
  "name": "nla_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584387744,
      "name": "nla_find",
      "external": true,
      "loc": "lib/nlattr.c:491",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/filter.c:bpf_skb_get_nlattr_nest",
        "net/core/filter.c:bpf_skb_get_nlattr",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584387744,
      "name": "nla_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
struct nlattr * nla_find(const struct nlattr * head, int len, int attrtype)
```

```json
{
  "name": "nla_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584493808,
      "name": "nla_find",
      "external": true,
      "loc": "lib/nlattr.c:491",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_delete",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/filter.c:bpf_skb_get_nlattr_nest",
        "net/core/filter.c:bpf_skb_get_nlattr",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv4/fib_semantics.c:fib_get_nhs",
        "net/ipv6/route.c:ip6_route_multipath_del",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584493808,
      "name": "nla_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
