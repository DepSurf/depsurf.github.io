# Function: <code>ipv6_dev_get_saddr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ipv6_dev_get_saddr(struct net * net, const struct net_device * dst_dev, const struct in6_addr * daddr, unsigned int prefs, struct in6_addr * saddr)
```

```json
{
  "name": "ipv6_dev_get_saddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587029984,
      "name": "ipv6_dev_get_saddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1520",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_get_saddr",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/xfrm6_policy.c:xfrm6_get_saddr",
        "net/ipv6/fib6_rules.c:fib6_rule_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587029984,
      "name": "ipv6_dev_get_saddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
int ipv6_dev_get_saddr(struct net * net, const struct net_device * dst_dev, const struct in6_addr * daddr, unsigned int prefs, struct in6_addr * saddr)
```

```json
{
  "name": "ipv6_dev_get_saddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587477984,
      "name": "ipv6_dev_get_saddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1556",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/xfrm6_policy.c:xfrm6_get_saddr",
        "net/ipv6/fib6_rules.c:fib6_rule_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587477984,
      "name": "ipv6_dev_get_saddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 791
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
int ipv6_dev_get_saddr(struct net * net, const struct net_device * dst_dev, const struct in6_addr * daddr, unsigned int prefs, struct in6_addr * saddr)
```

```json
{
  "name": "ipv6_dev_get_saddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587681248,
      "name": "ipv6_dev_get_saddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1604",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/xfrm6_policy.c:xfrm6_get_saddr",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587681248,
      "name": "ipv6_dev_get_saddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 791
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
int ipv6_dev_get_saddr(struct net * net, const struct net_device * dst_dev, const struct in6_addr * daddr, unsigned int prefs, struct in6_addr * saddr)
```

```json
{
  "name": "ipv6_dev_get_saddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587832336,
      "name": "ipv6_dev_get_saddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1646",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/xfrm6_policy.c:xfrm6_get_saddr",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587832336,
      "name": "ipv6_dev_get_saddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 855
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
int ipv6_dev_get_saddr(struct net * net, const struct net_device * dst_dev, const struct in6_addr * daddr, unsigned int prefs, struct in6_addr * saddr)
```

```json
{
  "name": "ipv6_dev_get_saddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588345184,
      "name": "ipv6_dev_get_saddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1690",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/xfrm6_policy.c:xfrm6_get_saddr",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588345184,
      "name": "ipv6_dev_get_saddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 825
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
int ipv6_dev_get_saddr(struct net * net, const struct net_device * dst_dev, const struct in6_addr * daddr, unsigned int prefs, struct in6_addr * saddr)
```

```json
{
  "name": "ipv6_dev_get_saddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588701776,
      "name": "ipv6_dev_get_saddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1691",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/xfrm6_policy.c:xfrm6_get_saddr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588701776,
      "name": "ipv6_dev_get_saddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 771
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
int ipv6_dev_get_saddr(struct net * net, const struct net_device * dst_dev, const struct in6_addr * daddr, unsigned int prefs, struct in6_addr * saddr)
```

```json
{
  "name": "ipv6_dev_get_saddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588920432,
      "name": "ipv6_dev_get_saddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1707",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/xfrm6_policy.c:xfrm6_get_saddr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588920432,
      "name": "ipv6_dev_get_saddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 771
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
int ipv6_dev_get_saddr(struct net * net, const struct net_device * dst_dev, const struct in6_addr * daddr, unsigned int prefs, struct in6_addr * saddr)
```

```json
{
  "name": "ipv6_dev_get_saddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589362256,
      "name": "ipv6_dev_get_saddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1740",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/xfrm6_policy.c:xfrm6_get_saddr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589362256,
      "name": "ipv6_dev_get_saddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 590
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
int ipv6_dev_get_saddr(struct net * net, const struct net_device * dst_dev, const struct in6_addr * daddr, unsigned int prefs, struct in6_addr * saddr)
```

```json
{
  "name": "ipv6_dev_get_saddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589586368,
      "name": "ipv6_dev_get_saddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1742",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/xfrm6_policy.c:xfrm6_get_saddr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589586368,
      "name": "ipv6_dev_get_saddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 590
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
int ipv6_dev_get_saddr(struct net * net, const struct net_device * dst_dev, const struct in6_addr * daddr, unsigned int prefs, struct in6_addr * saddr)
```

```json
{
  "name": "ipv6_dev_get_saddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590589552,
      "name": "ipv6_dev_get_saddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1733",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/xfrm6_policy.c:xfrm6_get_saddr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590589552,
      "name": "ipv6_dev_get_saddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
int ipv6_dev_get_saddr(struct net * net, const struct net_device * dst_dev, const struct in6_addr * daddr, unsigned int prefs, struct in6_addr * saddr)
```

```json
{
  "name": "ipv6_dev_get_saddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590649248,
      "name": "ipv6_dev_get_saddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1733",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/xfrm6_policy.c:xfrm6_get_saddr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590649248,
      "name": "ipv6_dev_get_saddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 582
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
int ipv6_dev_get_saddr(struct net * net, const struct net_device * dst_dev, const struct in6_addr * daddr, unsigned int prefs, struct in6_addr * saddr)
```

```json
{
  "name": "ipv6_dev_get_saddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590574736,
      "name": "ipv6_dev_get_saddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1735",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/xfrm6_policy.c:xfrm6_get_saddr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590574736,
      "name": "ipv6_dev_get_saddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 582
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
int ipv6_dev_get_saddr(struct net * net, const struct net_device * dst_dev, const struct in6_addr * daddr, unsigned int prefs, struct in6_addr * saddr)
```

```json
{
  "name": "ipv6_dev_get_saddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591386624,
      "name": "ipv6_dev_get_saddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1742",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/xfrm6_policy.c:xfrm6_get_saddr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591386624,
      "name": "ipv6_dev_get_saddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 661
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
int ipv6_dev_get_saddr(struct net * net, const struct net_device * dst_dev, const struct in6_addr * daddr, unsigned int prefs, struct in6_addr * saddr)
```

```json
{
  "name": "ipv6_dev_get_saddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593062384,
      "name": "ipv6_dev_get_saddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1749",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/xfrm6_policy.c:xfrm6_get_saddr",
        "net/ipv6/fib6_rules.c:fib6_rule_saddr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593062384,
      "name": "ipv6_dev_get_saddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 854
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
int ipv6_dev_get_saddr(struct net * net, const struct net_device * dst_dev, const struct in6_addr * daddr, unsigned int prefs, struct in6_addr * saddr)
```

```json
{
  "name": "ipv6_dev_get_saddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594954416,
      "name": "ipv6_dev_get_saddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1749",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/xfrm6_policy.c:xfrm6_get_saddr",
        "net/ipv6/fib6_rules.c:fib6_rule_saddr",
        "net/ipv6/seg6_iptunnel.c:set_tun_src",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594954416,
      "name": "ipv6_dev_get_saddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 854
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
int ipv6_dev_get_saddr(struct net * net, const struct net_device * dst_dev, const struct in6_addr * daddr, unsigned int prefs, struct in6_addr * saddr)
```

```json
{
  "name": "ipv6_dev_get_saddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595346896,
      "name": "ipv6_dev_get_saddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1748",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/xfrm6_policy.c:xfrm6_get_saddr",
        "net/ipv6/fib6_rules.c:fib6_rule_saddr",
        "net/ipv6/seg6_iptunnel.c:set_tun_src",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595346896,
      "name": "ipv6_dev_get_saddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 854
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
int ipv6_dev_get_saddr(struct net * net, const struct net_device * dst_dev, const struct in6_addr * daddr, unsigned int prefs, struct in6_addr * saddr)
```

```json
{
  "name": "ipv6_dev_get_saddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596187648,
      "name": "ipv6_dev_get_saddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1776",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/xfrm6_policy.c:xfrm6_get_saddr",
        "net/ipv6/fib6_rules.c:fib6_rule_saddr",
        "net/ipv6/seg6_iptunnel.c:set_tun_src",
        "net/ipv6/ioam6_iptunnel.c:ioam6_do_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596187648,
      "name": "ipv6_dev_get_saddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 860
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
int ipv6_dev_get_saddr(struct net * net, const struct net_device * dst_dev, const struct in6_addr * daddr, unsigned int prefs, struct in6_addr * saddr)
```

```json
{
  "name": "ipv6_dev_get_saddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503260600,
      "name": "ipv6_dev_get_saddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1742",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/xfrm6_policy.c:xfrm6_get_saddr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503260600,
      "name": "ipv6_dev_get_saddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 552
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
int ipv6_dev_get_saddr(struct net * net, const struct net_device * dst_dev, const struct in6_addr * daddr, unsigned int prefs, struct in6_addr * saddr)
```

```json
{
  "name": "ipv6_dev_get_saddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235936988,
      "name": "ipv6_dev_get_saddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1742",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/xfrm6_policy.c:xfrm6_get_saddr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235936988,
      "name": "ipv6_dev_get_saddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 624
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
int ipv6_dev_get_saddr(struct net * net, const struct net_device * dst_dev, const struct in6_addr * daddr, unsigned int prefs, struct in6_addr * saddr)
```

```json
{
  "name": "ipv6_dev_get_saddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297010832,
      "name": "ipv6_dev_get_saddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1742",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/xfrm6_policy.c:xfrm6_get_saddr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297010832,
      "name": "ipv6_dev_get_saddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 764
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
int ipv6_dev_get_saddr(struct net * net, const struct net_device * dst_dev, const struct in6_addr * daddr, unsigned int prefs, struct in6_addr * saddr)
```

```json
{
  "name": "ipv6_dev_get_saddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279289508,
      "name": "ipv6_dev_get_saddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1742",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/xfrm6_policy.c:xfrm6_get_saddr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279289508,
      "name": "ipv6_dev_get_saddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 466
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
int ipv6_dev_get_saddr(struct net * net, const struct net_device * dst_dev, const struct in6_addr * daddr, unsigned int prefs, struct in6_addr * saddr)
```

```json
{
  "name": "ipv6_dev_get_saddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589190736,
      "name": "ipv6_dev_get_saddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1742",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/xfrm6_policy.c:xfrm6_get_saddr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589190736,
      "name": "ipv6_dev_get_saddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 590
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
int ipv6_dev_get_saddr(struct net * net, const struct net_device * dst_dev, const struct in6_addr * daddr, unsigned int prefs, struct in6_addr * saddr)
```

```json
{
  "name": "ipv6_dev_get_saddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588915728,
      "name": "ipv6_dev_get_saddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1742",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/xfrm6_policy.c:xfrm6_get_saddr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588915728,
      "name": "ipv6_dev_get_saddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 590
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
int ipv6_dev_get_saddr(struct net * net, const struct net_device * dst_dev, const struct in6_addr * daddr, unsigned int prefs, struct in6_addr * saddr)
```

```json
{
  "name": "ipv6_dev_get_saddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589627600,
      "name": "ipv6_dev_get_saddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1742",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/xfrm6_policy.c:xfrm6_get_saddr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589627600,
      "name": "ipv6_dev_get_saddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 590
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
int ipv6_dev_get_saddr(struct net * net, const struct net_device * dst_dev, const struct in6_addr * daddr, unsigned int prefs, struct in6_addr * saddr)
```

```json
{
  "name": "ipv6_dev_get_saddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589676544,
      "name": "ipv6_dev_get_saddr",
      "external": true,
      "loc": "net/ipv6/addrconf.c:1742",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/ndisc.c:ndisc_send_na",
        "net/ipv6/xfrm6_policy.c:xfrm6_get_saddr",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589676544,
      "name": "ipv6_dev_get_saddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 759
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
