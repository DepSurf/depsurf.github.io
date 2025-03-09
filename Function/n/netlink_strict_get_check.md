# Function: <code>netlink_strict_get_check</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool netlink_strict_get_check(struct sk_buff * skb)
```

```json
{
  "name": "netlink_strict_get_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588702080,
      "name": "netlink_strict_get_check",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1366",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588702080,
      "name": "netlink_strict_get_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
bool netlink_strict_get_check(struct sk_buff * skb)
```

```json
{
  "name": "netlink_strict_get_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588925968,
      "name": "netlink_strict_get_check",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1367",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588925968,
      "name": "netlink_strict_get_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
bool netlink_strict_get_check(struct sk_buff * skb)
```

```json
{
  "name": "netlink_strict_get_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589815376,
      "name": "netlink_strict_get_check",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1367",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/ipv4/route.c:inet_rtm_valid_getroute_req",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_valid_getroute_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589815376,
      "name": "netlink_strict_get_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
bool netlink_strict_get_check(struct sk_buff * skb)
```

```json
{
  "name": "netlink_strict_get_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589851584,
      "name": "netlink_strict_get_check",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1368",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/ipv4/route.c:inet_rtm_valid_getroute_req",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_valid_getroute_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589851584,
      "name": "netlink_strict_get_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
bool netlink_strict_get_check(struct sk_buff * skb)
```

```json
{
  "name": "netlink_strict_get_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589757024,
      "name": "netlink_strict_get_check",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1378",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/ipv4/route.c:inet_rtm_valid_getroute_req",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_valid_getroute_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589757024,
      "name": "netlink_strict_get_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
bool netlink_strict_get_check(struct sk_buff * skb)
```

```json
{
  "name": "netlink_strict_get_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590516096,
      "name": "netlink_strict_get_check",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1383",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/ipv4/route.c:inet_rtm_valid_getroute_req",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_valid_getroute_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590516096,
      "name": "netlink_strict_get_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
bool netlink_strict_get_check(struct sk_buff * skb)
```

```json
{
  "name": "netlink_strict_get_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592122816,
      "name": "netlink_strict_get_check",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1383",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/rtnetlink.c:rtnl_stats_set",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/ipv4/route.c:inet_rtm_valid_getroute_req",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_valid_getroute_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592122816,
      "name": "netlink_strict_get_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
bool netlink_strict_get_check(struct sk_buff * skb)
```

```json
{
  "name": "netlink_strict_get_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593945456,
      "name": "netlink_strict_get_check",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1403",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/rtnetlink.c:rtnl_stats_set",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/ipv4/route.c:inet_rtm_valid_getroute_req",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_valid_getroute_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593945456,
      "name": "netlink_strict_get_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
bool netlink_strict_get_check(struct sk_buff * skb)
```

```json
{
  "name": "netlink_strict_get_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594321712,
      "name": "netlink_strict_get_check",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1403",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/rtnetlink.c:rtnl_stats_set",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/ipv4/route.c:inet_rtm_valid_getroute_req",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_valid_getroute_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594321712,
      "name": "netlink_strict_get_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
bool netlink_strict_get_check(struct sk_buff * skb)
```

```json
{
  "name": "netlink_strict_get_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595121280,
      "name": "netlink_strict_get_check",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1405",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/rtnetlink.c:rtnl_stats_set",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/ipv4/route.c:inet_rtm_valid_getroute_req",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_valid_getroute_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595121280,
      "name": "netlink_strict_get_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
bool netlink_strict_get_check(struct sk_buff * skb)
```

```json
{
  "name": "netlink_strict_get_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502519776,
      "name": "netlink_strict_get_check",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1367",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502519776,
      "name": "netlink_strict_get_check",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
bool netlink_strict_get_check(struct sk_buff * skb)
```

```json
{
  "name": "netlink_strict_get_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235230424,
      "name": "netlink_strict_get_check",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1367",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235230424,
      "name": "netlink_strict_get_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
bool netlink_strict_get_check(struct sk_buff * skb)
```

```json
{
  "name": "netlink_strict_get_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296091424,
      "name": "netlink_strict_get_check",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1367",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296091424,
      "name": "netlink_strict_get_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
bool netlink_strict_get_check(struct sk_buff * skb)
```

```json
{
  "name": "netlink_strict_get_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278690316,
      "name": "netlink_strict_get_check",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1367",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278690316,
      "name": "netlink_strict_get_check",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
bool netlink_strict_get_check(struct sk_buff * skb)
```

```json
{
  "name": "netlink_strict_get_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588532352,
      "name": "netlink_strict_get_check",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1367",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588532352,
      "name": "netlink_strict_get_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
bool netlink_strict_get_check(struct sk_buff * skb)
```

```json
{
  "name": "netlink_strict_get_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588244352,
      "name": "netlink_strict_get_check",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1367",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588244352,
      "name": "netlink_strict_get_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
bool netlink_strict_get_check(struct sk_buff * skb)
```

```json
{
  "name": "netlink_strict_get_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588864528,
      "name": "netlink_strict_get_check",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1367",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588864528,
      "name": "netlink_strict_get_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
bool netlink_strict_get_check(struct sk_buff * skb)
```

```json
{
  "name": "netlink_strict_get_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589006000,
      "name": "netlink_strict_get_check",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1367",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/devinet.c:inet_netconf_get_devconf",
        "net/ipv4/ipmr.c:ipmr_rtm_getroute",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf",
        "net/ipv6/addrlabel.c:ip6addrlbl_get",
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589006000,
      "name": "netlink_strict_get_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
bool netlink_strict_get_check(struct sk_buff * skb)
```
</details>
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
