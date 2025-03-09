# Function: <code>nla_reserve</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct nlattr * nla_reserve(struct sk_buff * skb, int attrtype, int attrlen)
```

```json
{
  "name": "nla_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583128128,
      "name": "nla_reserve",
      "external": true,
      "loc": "lib/nlattr.c:390",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "kernel/taskstats.c:mk_reply",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/rtnetlink.c:rtnl_fill_stats",
        "net/core/rtnetlink.c:rtnl_fill_stats",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/ipv4/devinet.c:inet_fill_link_af",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583128128,
      "name": "nla_reserve",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nlattr * nla_reserve(struct sk_buff * skb, int attrtype, int attrlen)
```

```json
{
  "name": "nla_reserve",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583422352,
      "name": "nla_reserve",
      "external": true,
      "loc": "lib/nlattr.c:414",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/rtnetlink.c:rtnl_fill_stats",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/ipv4/devinet.c:inet_fill_link_af",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583422352,
      "name": "nla_reserve",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nlattr * nla_reserve(struct sk_buff * skb, int attrtype, int attrlen)
```

```json
{
  "name": "nla_reserve",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583547984,
      "name": "nla_reserve",
      "external": true,
      "loc": "lib/nlattr.c:414",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/rtnetlink.c:rtnl_fill_stats",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/ipv4/devinet.c:inet_fill_link_af",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/seg6_iptunnel.c:nla_put_srh",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583547984,
      "name": "nla_reserve",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nlattr * nla_reserve(struct sk_buff * skb, int attrtype, int attrlen)
```

```json
{
  "name": "nla_reserve",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583585648,
      "name": "nla_reserve",
      "external": true,
      "loc": "lib/nlattr.c:417",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/rtnetlink.c:rtnl_fill_stats",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/ipv4/devinet.c:inet_fill_link_af",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583585648,
      "name": "nla_reserve",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nlattr * nla_reserve(struct sk_buff * skb, int attrtype, int attrlen)
```

```json
{
  "name": "nla_reserve",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583831808,
      "name": "nla_reserve",
      "external": true,
      "loc": "lib/nlattr.c:495",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/rtnetlink.c:rtnl_fill_stats",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/sched/act_api.c:tc_dump_action",
        "net/ipv4/devinet.c:inet_fill_link_af",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info",
        "net/ipv6/seg6_local.c:put_nla_nh6",
        "net/ipv6/seg6_local.c:put_nla_nh4",
        "net/ipv6/seg6_local.c:put_nla_srh",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583831808,
      "name": "nla_reserve",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct nlattr * nla_reserve(struct sk_buff * skb, int attrtype, int attrlen)
```

```json
{
  "name": "nla_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584031792,
      "name": "nla_reserve",
      "external": true,
      "loc": "lib/nlattr.c:495",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/rtnetlink.c:rtnl_fill_stats",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/sched/act_api.c:tc_dump_action",
        "net/ipv4/devinet.c:inet_fill_link_af",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info",
        "net/ipv6/seg6_local.c:put_nla_nh6",
        "net/ipv6/seg6_local.c:put_nla_nh4",
        "net/ipv6/seg6_local.c:put_nla_srh",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584031792,
      "name": "nla_reserve",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct nlattr * nla_reserve(struct sk_buff * skb, int attrtype, int attrlen)
```

```json
{
  "name": "nla_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584113008,
      "name": "nla_reserve",
      "external": true,
      "loc": "lib/nlattr.c:670",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/rtnetlink.c:rtnl_fill_stats",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/sched/act_api.c:tc_dump_action",
        "net/ipv4/devinet.c:inet_fill_link_af",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info",
        "net/ipv6/seg6_local.c:put_nla_nh6",
        "net/ipv6/seg6_local.c:put_nla_nh4",
        "net/ipv6/seg6_local.c:put_nla_srh",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584113008,
      "name": "nla_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct nlattr * nla_reserve(struct sk_buff * skb, int attrtype, int attrlen)
```

```json
{
  "name": "nla_reserve",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584303920,
      "name": "nla_reserve",
      "external": true,
      "loc": "lib/nlattr.c:702",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/rtnetlink.c:rtnl_fill_stats",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/sched/act_api.c:tc_dump_action",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/devinet.c:inet_fill_link_af",
        "net/ipv4/fib_semantics.c:fib_nexthop_info",
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info",
        "net/ipv6/seg6_local.c:put_nla_nh6",
        "net/ipv6/seg6_local.c:put_nla_nh4",
        "net/ipv6/seg6_local.c:put_nla_srh",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584303920,
      "name": "nla_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct nlattr * nla_reserve(struct sk_buff * skb, int attrtype, int attrlen)
```

```json
{
  "name": "nla_reserve",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584438624,
      "name": "nla_reserve",
      "external": true,
      "loc": "lib/nlattr.c:702",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/rtnetlink.c:rtnl_fill_stats",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/drop_monitor.c:reset_per_cpu_data",
        "net/sched/act_api.c:tc_dump_action",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/devinet.c:inet_fill_link_af",
        "net/ipv4/fib_semantics.c:fib_nexthop_info",
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info",
        "net/ipv6/seg6_local.c:put_nla_nh6",
        "net/ipv6/seg6_local.c:put_nla_nh4",
        "net/ipv6/seg6_local.c:put_nla_srh",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584438624,
      "name": "nla_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct nlattr * nla_reserve(struct sk_buff * skb, int attrtype, int attrlen)
```

```json
{
  "name": "nla_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584999152,
      "name": "nla_reserve",
      "external": true,
      "loc": "lib/nlattr.c:854",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "net/core/rtnetlink.c:rtnl_fill_stats",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/drop_monitor.c:reset_per_cpu_data",
        "net/sched/act_api.c:tc_dump_action",
        "net/ethtool/bitset.c:ethnl_put_bitset32",
        "net/ethtool/bitset.c:ethnl_put_bitset32",
        "net/ethtool/bitset.c:ethnl_put_bitset32",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/devinet.c:inet_fill_link_af",
        "net/ipv4/fib_semantics.c:fib_nexthop_info",
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info",
        "net/ipv6/seg6_local.c:put_nla_nh6",
        "net/ipv6/seg6_local.c:put_nla_nh4",
        "net/ipv6/seg6_local.c:put_nla_srh",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584999152,
      "name": "nla_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct nlattr * nla_reserve(struct sk_buff * skb, int attrtype, int attrlen)
```

```json
{
  "name": "nla_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585119632,
      "name": "nla_reserve",
      "external": true,
      "loc": "lib/nlattr.c:920",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "net/core/rtnetlink.c:rtnl_fill_stats",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/drop_monitor.c:reset_per_cpu_data",
        "net/sched/act_api.c:tc_dump_action",
        "net/ethtool/bitset.c:ethnl_put_bitset32",
        "net/ethtool/bitset.c:ethnl_put_bitset32",
        "net/ethtool/bitset.c:ethnl_put_bitset32",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/devinet.c:inet_fill_link_af",
        "net/ipv4/fib_semantics.c:fib_nexthop_info",
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info",
        "net/ipv6/seg6_local.c:put_nla_nh6",
        "net/ipv6/seg6_local.c:put_nla_nh4",
        "net/ipv6/seg6_local.c:put_nla_srh",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585119632,
      "name": "nla_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct nlattr * nla_reserve(struct sk_buff * skb, int attrtype, int attrlen)
```

```json
{
  "name": "nla_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584999888,
      "name": "nla_reserve",
      "external": true,
      "loc": "lib/nlattr.c:920",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "net/core/rtnetlink.c:rtnl_fill_stats",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/drop_monitor.c:reset_per_cpu_data",
        "net/sched/act_api.c:tc_dump_action",
        "net/ethtool/bitset.c:ethnl_put_bitset32",
        "net/ethtool/bitset.c:ethnl_put_bitset32",
        "net/ethtool/bitset.c:ethnl_put_bitset32",
        "net/ethtool/strset.c:strset_fill_reply",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/devinet.c:inet_fill_link_af",
        "net/ipv4/fib_semantics.c:fib_nexthop_info",
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info",
        "net/ipv6/seg6_local.c:put_nla_nh6",
        "net/ipv6/seg6_local.c:put_nla_nh4",
        "net/ipv6/seg6_local.c:put_nla_srh",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584999888,
      "name": "nla_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct nlattr * nla_reserve(struct sk_buff * skb, int attrtype, int attrlen)
```

```json
{
  "name": "nla_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585441104,
      "name": "nla_reserve",
      "external": true,
      "loc": "lib/nlattr.c:920",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "net/core/rtnetlink.c:rtnl_fill_stats",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/drop_monitor.c:reset_per_cpu_data",
        "net/sched/act_api.c:tc_dump_action",
        "net/ethtool/bitset.c:ethnl_put_bitset32",
        "net/ethtool/bitset.c:ethnl_put_bitset32",
        "net/ethtool/bitset.c:ethnl_put_bitset32",
        "net/ethtool/strset.c:strset_fill_reply",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/devinet.c:inet_fill_link_af",
        "net/ipv4/fib_semantics.c:fib_nexthop_info",
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info",
        "net/ipv6/seg6_local.c:put_nla_nh6",
        "net/ipv6/seg6_local.c:put_nla_nh4",
        "net/ipv6/seg6_local.c:put_nla_srh",
        "net/ipv6/ioam6_iptunnel.c:ioam6_fill_encap_info",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585441104,
      "name": "nla_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct nlattr * nla_reserve(struct sk_buff * skb, int attrtype, int attrlen)
```

```json
{
  "name": "nla_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586581792,
      "name": "nla_reserve",
      "external": true,
      "loc": "lib/nlattr.c:920",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "net/core/rtnetlink.c:rtnl_fill_stats",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/drop_monitor.c:reset_per_cpu_data",
        "net/sched/act_api.c:tc_dump_action",
        "net/ethtool/bitset.c:ethnl_put_bitset32",
        "net/ethtool/bitset.c:ethnl_put_bitset32",
        "net/ethtool/bitset.c:ethnl_put_bitset32",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/devinet.c:inet_fill_link_af",
        "net/ipv4/fib_semantics.c:fib_nexthop_info",
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info",
        "net/ipv6/seg6_local.c:put_nla_nh6",
        "net/ipv6/seg6_local.c:put_nla_nh4",
        "net/ipv6/seg6_local.c:put_nla_srh",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586581792,
      "name": "nla_reserve",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct nlattr * nla_reserve(struct sk_buff * skb, int attrtype, int attrlen)
```

```json
{
  "name": "nla_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587821344,
      "name": "nla_reserve",
      "external": true,
      "loc": "lib/nlattr.c:935",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "net/core/rtnetlink.c:rtnl_fill_stats",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/drop_monitor.c:reset_per_cpu_data",
        "net/sched/act_api.c:tc_dump_action",
        "net/ethtool/bitset.c:ethnl_put_bitset32",
        "net/ethtool/bitset.c:ethnl_put_bitset32",
        "net/ethtool/bitset.c:ethnl_put_bitset32",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/devinet.c:inet_fill_link_af",
        "net/ipv4/fib_semantics.c:fib_nexthop_info",
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/seg6_local.c:put_nla_nh6",
        "net/ipv6/seg6_local.c:put_nla_nh4",
        "net/ipv6/seg6_local.c:put_nla_srh",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587821344,
      "name": "nla_reserve",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct nlattr * nla_reserve(struct sk_buff * skb, int attrtype, int attrlen)
```

```json
{
  "name": "nla_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588092768,
      "name": "nla_reserve",
      "external": true,
      "loc": "lib/nlattr.c:935",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "net/core/rtnetlink.c:rtnl_fill_stats",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/drop_monitor.c:reset_per_cpu_data",
        "net/sched/act_api.c:tc_dump_action",
        "net/ethtool/bitset.c:ethnl_put_bitset32",
        "net/ethtool/bitset.c:ethnl_put_bitset32",
        "net/ethtool/bitset.c:ethnl_put_bitset32",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/devinet.c:inet_fill_link_af",
        "net/ipv4/fib_semantics.c:fib_nexthop_info",
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/seg6_local.c:put_nla_nh6",
        "net/ipv6/seg6_local.c:put_nla_nh4",
        "net/ipv6/seg6_local.c:put_nla_srh",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588092768,
      "name": "nla_reserve",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct nlattr * nla_reserve(struct sk_buff * skb, int attrtype, int attrlen)
```

```json
{
  "name": "nla_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588428640,
      "name": "nla_reserve",
      "external": true,
      "loc": "lib/nlattr.c:967",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/regulator/event.c:reg_generate_netlink_event",
        "net/core/rtnetlink.c:rtnl_fill_stats",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/drop_monitor.c:reset_per_cpu_data",
        "net/sched/act_api.c:tc_dump_action",
        "net/ethtool/bitset.c:ethnl_put_bitset32",
        "net/ethtool/bitset.c:ethnl_put_bitset32",
        "net/ethtool/bitset.c:ethnl_put_bitset32",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/devinet.c:inet_fill_link_af",
        "net/ipv4/fib_semantics.c:fib_nexthop_info",
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/ipmr.c:igmpmsg_netlink_event",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/ip6mr.c:mrt6msg_netlink_event",
        "net/ipv6/seg6_local.c:put_nla_nh6",
        "net/ipv6/seg6_local.c:put_nla_nh4",
        "net/ipv6/seg6_local.c:put_nla_srh",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588428640,
      "name": "nla_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct nlattr * nla_reserve(struct sk_buff * skb, int attrtype, int attrlen)
```

```json
{
  "name": "nla_reserve",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496324080,
      "name": "nla_reserve",
      "external": true,
      "loc": "lib/nlattr.c:702",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/rtnetlink.c:rtnl_fill_stats",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/drop_monitor.c:reset_per_cpu_data",
        "net/sched/act_api.c:tc_dump_action",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/devinet.c:inet_fill_link_af",
        "net/ipv4/fib_semantics.c:fib_nexthop_info",
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info",
        "net/ipv6/seg6_local.c:put_nla_nh6",
        "net/ipv6/seg6_local.c:put_nla_nh4",
        "net/ipv6/seg6_local.c:put_nla_srh",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496324080,
      "name": "nla_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct nlattr * nla_reserve(struct sk_buff * skb, int attrtype, int attrlen)
```

```json
{
  "name": "nla_reserve",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229658752,
      "name": "nla_reserve",
      "external": true,
      "loc": "lib/nlattr.c:702",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/rtnetlink.c:rtnl_fill_stats",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/drop_monitor.c:reset_per_cpu_data",
        "net/sched/act_api.c:tc_dump_action",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/devinet.c:inet_fill_link_af",
        "net/ipv4/fib_semantics.c:fib_nexthop_info",
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info",
        "net/ipv6/seg6_local.c:put_nla_nh6",
        "net/ipv6/seg6_local.c:put_nla_nh4",
        "net/ipv6/seg6_local.c:put_nla_srh",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229658752,
      "name": "nla_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct nlattr * nla_reserve(struct sk_buff * skb, int attrtype, int attrlen)
```

```json
{
  "name": "nla_reserve",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290642480,
      "name": "nla_reserve",
      "external": true,
      "loc": "lib/nlattr.c:702",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/rtnetlink.c:rtnl_fill_stats",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/drop_monitor.c:reset_per_cpu_data",
        "net/sched/act_api.c:tc_dump_action",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/devinet.c:inet_fill_link_af",
        "net/ipv4/fib_semantics.c:fib_nexthop_info",
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info",
        "net/ipv6/seg6_local.c:put_nla_nh6",
        "net/ipv6/seg6_local.c:put_nla_nh4",
        "net/ipv6/seg6_local.c:put_nla_srh",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290642480,
      "name": "nla_reserve",
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
struct nlattr * nla_reserve(struct sk_buff * skb, int attrtype, int attrlen)
```

```json
{
  "name": "nla_reserve",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275375982,
      "name": "nla_reserve",
      "external": true,
      "loc": "lib/nlattr.c:702",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/nlattr.c:__nla_reserve_64bit"
      ],
      "caller_func": [
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/rtnetlink.c:rtnl_fill_stats",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/drop_monitor.c:reset_per_cpu_data",
        "net/sched/act_api.c:tc_dump_action",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/devinet.c:inet_fill_link_af",
        "net/ipv4/fib_semantics.c:fib_nexthop_info",
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info",
        "net/ipv6/seg6_local.c:put_nla_nh6",
        "net/ipv6/seg6_local.c:put_nla_nh4",
        "net/ipv6/seg6_local.c:put_nla_srh",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275375866,
      "name": "nla_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct nlattr * nla_reserve(struct sk_buff * skb, int attrtype, int attrlen)
```

```json
{
  "name": "nla_reserve",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584407360,
      "name": "nla_reserve",
      "external": true,
      "loc": "lib/nlattr.c:702",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/rtnetlink.c:rtnl_fill_stats",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/drop_monitor.c:reset_per_cpu_data",
        "net/sched/act_api.c:tc_dump_action",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/devinet.c:inet_fill_link_af",
        "net/ipv4/fib_semantics.c:fib_nexthop_info",
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info",
        "net/ipv6/seg6_local.c:put_nla_nh6",
        "net/ipv6/seg6_local.c:put_nla_nh4",
        "net/ipv6/seg6_local.c:put_nla_srh",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584407360,
      "name": "nla_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct nlattr * nla_reserve(struct sk_buff * skb, int attrtype, int attrlen)
```

```json
{
  "name": "nla_reserve",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584342560,
      "name": "nla_reserve",
      "external": true,
      "loc": "lib/nlattr.c:702",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/rtnetlink.c:rtnl_fill_stats",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/drop_monitor.c:reset_per_cpu_data",
        "net/sched/act_api.c:tc_dump_action",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/devinet.c:inet_fill_link_af",
        "net/ipv4/fib_semantics.c:fib_nexthop_info",
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info",
        "net/ipv6/seg6_local.c:put_nla_nh6",
        "net/ipv6/seg6_local.c:put_nla_nh4",
        "net/ipv6/seg6_local.c:put_nla_srh",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584342560,
      "name": "nla_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct nlattr * nla_reserve(struct sk_buff * skb, int attrtype, int attrlen)
```

```json
{
  "name": "nla_reserve",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584390272,
      "name": "nla_reserve",
      "external": true,
      "loc": "lib/nlattr.c:702",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/rtnetlink.c:rtnl_fill_stats",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/sock_diag.c:sock_diag_put_filterinfo",
        "net/core/drop_monitor.c:reset_per_cpu_data",
        "net/sched/act_api.c:tc_dump_action",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/devinet.c:inet_fill_link_af",
        "net/ipv4/fib_semantics.c:fib_nexthop_info",
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info",
        "net/ipv6/seg6_local.c:put_nla_nh6",
        "net/ipv6/seg6_local.c:put_nla_nh4",
        "net/ipv6/seg6_local.c:put_nla_srh",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584390272,
      "name": "nla_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct nlattr * nla_reserve(struct sk_buff * skb, int attrtype, int attrlen)
```

```json
{
  "name": "nla_reserve",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584496336,
      "name": "nla_reserve",
      "external": true,
      "loc": "lib/nlattr.c:702",
      "file": "lib/nlattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/rtnetlink.c:rtnl_fill_stats",
        "net/core/drop_monitor.c:reset_per_cpu_data",
        "net/sched/act_api.c:tc_dump_action",
        "net/ipv4/route.c:rt_fill_info",
        "net/ipv4/devinet.c:inet_fill_link_af",
        "net/ipv4/fib_semantics.c:fib_nexthop_info",
        "net/ipv4/nexthop.c:nh_fill_node",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info",
        "net/ipv6/seg6_local.c:put_nla_nh6",
        "net/ipv6/seg6_local.c:put_nla_nh4",
        "net/ipv6/seg6_local.c:put_nla_srh",
        "net/wireless/wext-core.c:wireless_send_event",
        "net/wireless/wext-core.c:wireless_send_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584496336,
      "name": "nla_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
