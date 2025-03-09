# Function: <code>ip6_route_output_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dst_entry * ip6_route_output_flags(struct net * net, const struct sock * sk, struct flowi6 * fl6, int flags)
```

```json
{
  "name": "ip6_route_output_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587055792,
      "name": "ip6_route_output_flags",
      "external": true,
      "loc": "net/ipv6/route.c:1177",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/netfilter.c:nf_ip6_route",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587055792,
      "name": "ip6_route_output_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
struct dst_entry * ip6_route_output_flags(struct net * net, const struct sock * sk, struct flowi6 * fl6, int flags)
```

```json
{
  "name": "ip6_route_output_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587503776,
      "name": "ip6_route_output_flags",
      "external": true,
      "loc": "net/ipv6/route.c:1188",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/netfilter.c:nf_ip6_route",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587503776,
      "name": "ip6_route_output_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
struct dst_entry * ip6_route_output_flags(struct net * net, const struct sock * sk, struct flowi6 * fl6, int flags)
```

```json
{
  "name": "ip6_route_output_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587705296,
      "name": "ip6_route_output_flags",
      "external": true,
      "loc": "net/ipv6/route.c:1193",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/netfilter.c:nf_ip6_route",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/seg6_iptunnel.c:seg6_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587705296,
      "name": "ip6_route_output_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
struct dst_entry * ip6_route_output_flags(struct net * net, const struct sock * sk, struct flowi6 * fl6, int flags)
```

```json
{
  "name": "ip6_route_output_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587855264,
      "name": "ip6_route_output_flags",
      "external": true,
      "loc": "net/ipv6/route.c:1218",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/netfilter.c:nf_ip6_route",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/seg6_iptunnel.c:seg6_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587855264,
      "name": "ip6_route_output_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
struct dst_entry * ip6_route_output_flags(struct net * net, const struct sock * sk, struct flowi6 * fl6, int flags)
```

```json
{
  "name": "ip6_route_output_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588384544,
      "name": "ip6_route_output_flags",
      "external": true,
      "loc": "net/ipv6/route.c:1896",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/netfilter.c:nf_ip6_route",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/seg6_iptunnel.c:seg6_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588384544,
      "name": "ip6_route_output_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
struct dst_entry * ip6_route_output_flags(struct net * net, const struct sock * sk, struct flowi6 * fl6, int flags)
```

```json
{
  "name": "ip6_route_output_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588744224,
      "name": "ip6_route_output_flags",
      "external": true,
      "loc": "net/ipv6/route.c:2094",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/netfilter.c:nf_ip6_route",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/seg6_iptunnel.c:seg6_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588744224,
      "name": "ip6_route_output_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
struct dst_entry * ip6_route_output_flags(struct net * net, const struct sock * sk, struct flowi6 * fl6, int flags)
```

```json
{
  "name": "ip6_route_output_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588964432,
      "name": "ip6_route_output_flags",
      "external": true,
      "loc": "net/ipv6/route.c:2085",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ip6mr.c:ip6mr_forward2",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/netfilter.c:nf_ip6_route",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/seg6_iptunnel.c:seg6_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588964432,
      "name": "ip6_route_output_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
struct dst_entry * ip6_route_output_flags(struct net * net, const struct sock * sk, struct flowi6 * fl6, int flags)
```

```json
{
  "name": "ip6_route_output_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6_route_output_flags",
      "external": true,
      "loc": "net/ipv6/route.c:2488",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow",
        "net/ipv6/ip6mr.c:ip6mr_forward2",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/netfilter.c:__nf_ip6_route",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/seg6_iptunnel.c:seg6_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589450420,
      "name": "ip6_route_output_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071589417168,
      "name": "ip6_route_output_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
struct dst_entry * ip6_route_output_flags(struct net * net, const struct sock * sk, struct flowi6 * fl6, int flags)
```

```json
{
  "name": "ip6_route_output_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589641392,
      "name": "ip6_route_output_flags",
      "external": true,
      "loc": "net/ipv6/route.c:2494",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow",
        "net/ipv6/ip6mr.c:ip6mr_forward2",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/netfilter.c:__nf_ip6_route",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/seg6_iptunnel.c:seg6_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589641392,
      "name": "ip6_route_output_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
struct dst_entry * ip6_route_output_flags(struct net * net, const struct sock * sk, struct flowi6 * fl6, int flags)
```

```json
{
  "name": "ip6_route_output_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590645216,
      "name": "ip6_route_output_flags",
      "external": true,
      "loc": "net/ipv6/route.c:2513",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/netfilter.c:__nf_ip6_route",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/seg6_iptunnel.c:seg6_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590645216,
      "name": "ip6_route_output_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
struct dst_entry * ip6_route_output_flags(struct net * net, const struct sock * sk, struct flowi6 * fl6, int flags)
```

```json
{
  "name": "ip6_route_output_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590705296,
      "name": "ip6_route_output_flags",
      "external": true,
      "loc": "net/ipv6/route.c:2496",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/netfilter.c:__nf_ip6_route",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/seg6_iptunnel.c:seg6_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590705296,
      "name": "ip6_route_output_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
struct dst_entry * ip6_route_output_flags(struct net * net, const struct sock * sk, struct flowi6 * fl6, int flags)
```

```json
{
  "name": "ip6_route_output_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590630848,
      "name": "ip6_route_output_flags",
      "external": true,
      "loc": "net/ipv6/route.c:2503",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/netfilter.c:__nf_ip6_route",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/seg6_iptunnel.c:seg6_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590630848,
      "name": "ip6_route_output_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
struct dst_entry * ip6_route_output_flags(struct net * net, const struct sock * sk, struct flowi6 * fl6, int flags)
```

```json
{
  "name": "ip6_route_output_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591450192,
      "name": "ip6_route_output_flags",
      "external": true,
      "loc": "net/ipv6/route.c:2633",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/netfilter.c:__nf_ip6_route",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/seg6_iptunnel.c:seg6_output_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591450192,
      "name": "ip6_route_output_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
struct dst_entry * ip6_route_output_flags(struct net * net, const struct sock * sk, struct flowi6 * fl6, int flags)
```

```json
{
  "name": "ip6_route_output_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593131040,
      "name": "ip6_route_output_flags",
      "external": true,
      "loc": "net/ipv6/route.c:2629",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/netfilter.c:__nf_ip6_route",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/seg6_iptunnel.c:seg6_output_core",
        "net/ipv6/ioam6_iptunnel.c:ioam6_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593131040,
      "name": "ip6_route_output_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
struct dst_entry * ip6_route_output_flags(struct net * net, const struct sock * sk, struct flowi6 * fl6, int flags)
```

```json
{
  "name": "ip6_route_output_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595027648,
      "name": "ip6_route_output_flags",
      "external": true,
      "loc": "net/ipv6/route.c:2629",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/netfilter.c:__nf_ip6_route",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/seg6_iptunnel.c:seg6_output_core",
        "net/ipv6/ioam6_iptunnel.c:ioam6_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595027648,
      "name": "ip6_route_output_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
struct dst_entry * ip6_route_output_flags(struct net * net, const struct sock * sk, struct flowi6 * fl6, int flags)
```

```json
{
  "name": "ip6_route_output_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6_route_output_flags",
      "external": true,
      "loc": "net/ipv6/route.c:2628",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/netfilter.c:__nf_ip6_route",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/seg6_iptunnel.c:seg6_output_core",
        "net/ipv6/ioam6_iptunnel.c:ioam6_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596887358,
      "name": "ip6_route_output_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071595420240,
      "name": "ip6_route_output_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
struct dst_entry * ip6_route_output_flags(struct net * net, const struct sock * sk, struct flowi6 * fl6, int flags)
```

```json
{
  "name": "ip6_route_output_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6_route_output_flags",
      "external": true,
      "loc": "net/ipv6/route.c:2630",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/netfilter.c:__nf_ip6_route",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/seg6_iptunnel.c:seg6_output_core",
        "net/ipv6/ioam6_iptunnel.c:ioam6_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597811714,
      "name": "ip6_route_output_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071596262064,
      "name": "ip6_route_output_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
struct dst_entry * ip6_route_output_flags(struct net * net, const struct sock * sk, struct flowi6 * fl6, int flags)
```

```json
{
  "name": "ip6_route_output_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503333272,
      "name": "ip6_route_output_flags",
      "external": true,
      "loc": "net/ipv6/route.c:2494",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow",
        "net/ipv6/ip6mr.c:ip6mr_forward2",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/netfilter.c:__nf_ip6_route",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/seg6_iptunnel.c:seg6_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503333272,
      "name": "ip6_route_output_flags",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dst_entry * ip6_route_output_flags(struct net * net, const struct sock * sk, struct flowi6 * fl6, int flags)
```

```json
{
  "name": "ip6_route_output_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235992900,
      "name": "ip6_route_output_flags",
      "external": true,
      "loc": "net/ipv6/route.c:2494",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow",
        "net/ipv6/ip6mr.c:ip6mr_forward2",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/netfilter.c:__nf_ip6_route",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/seg6_iptunnel.c:seg6_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235992900,
      "name": "ip6_route_output_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
struct dst_entry * ip6_route_output_flags(struct net * net, const struct sock * sk, struct flowi6 * fl6, int flags)
```

```json
{
  "name": "ip6_route_output_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297074400,
      "name": "ip6_route_output_flags",
      "external": true,
      "loc": "net/ipv6/route.c:2494",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow",
        "net/ipv6/ip6mr.c:ip6mr_forward2",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/netfilter.c:__nf_ip6_route",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/seg6_iptunnel.c:seg6_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297074400,
      "name": "ip6_route_output_flags",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct dst_entry * ip6_route_output_flags(struct net * net, const struct sock * sk, struct flowi6 * fl6, int flags)
```

```json
{
  "name": "ip6_route_output_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279334572,
      "name": "ip6_route_output_flags",
      "external": true,
      "loc": "net/ipv6/route.c:2494",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow",
        "net/ipv6/ip6mr.c:ip6mr_forward2",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/netfilter.c:__nf_ip6_route",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/seg6_iptunnel.c:seg6_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279334572,
      "name": "ip6_route_output_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
struct dst_entry * ip6_route_output_flags(struct net * net, const struct sock * sk, struct flowi6 * fl6, int flags)
```

```json
{
  "name": "ip6_route_output_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589245760,
      "name": "ip6_route_output_flags",
      "external": true,
      "loc": "net/ipv6/route.c:2494",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow",
        "net/ipv6/ip6mr.c:ip6mr_forward2",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/netfilter.c:__nf_ip6_route",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/seg6_iptunnel.c:seg6_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589245760,
      "name": "ip6_route_output_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
struct dst_entry * ip6_route_output_flags(struct net * net, const struct sock * sk, struct flowi6 * fl6, int flags)
```

```json
{
  "name": "ip6_route_output_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588970752,
      "name": "ip6_route_output_flags",
      "external": true,
      "loc": "net/ipv6/route.c:2494",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow",
        "net/ipv6/ip6mr.c:ip6mr_forward2",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/netfilter.c:__nf_ip6_route",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/seg6_iptunnel.c:seg6_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588970752,
      "name": "ip6_route_output_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
struct dst_entry * ip6_route_output_flags(struct net * net, const struct sock * sk, struct flowi6 * fl6, int flags)
```

```json
{
  "name": "ip6_route_output_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589682624,
      "name": "ip6_route_output_flags",
      "external": true,
      "loc": "net/ipv6/route.c:2494",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow",
        "net/ipv6/ip6mr.c:ip6mr_forward2",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/netfilter.c:__nf_ip6_route",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/seg6_iptunnel.c:seg6_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589682624,
      "name": "ip6_route_output_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
struct dst_entry * ip6_route_output_flags(struct net * net, const struct sock * sk, struct flowi6 * fl6, int flags)
```

```json
{
  "name": "ip6_route_output_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589731776,
      "name": "ip6_route_output_flags",
      "external": true,
      "loc": "net/ipv6/route.c:2494",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_update_pmtu",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow",
        "net/ipv6/ip6mr.c:ip6mr_forward2",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_lookup",
        "net/ipv6/netfilter.c:__nf_ip6_route",
        "net/ipv6/netfilter.c:ip6_route_me_harder",
        "net/ipv6/seg6_iptunnel.c:seg6_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589731776,
      "name": "ip6_route_output_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
