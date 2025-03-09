# Function: <code>xfrm_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dst_entry * xfrm_lookup(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags)
```

```json
{
  "name": "xfrm_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586929200,
      "name": "xfrm_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:2205",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/icmp.c:icmp_route_lookup",
        "net/ipv4/icmp.c:icmp_route_lookup",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586929200,
      "name": "xfrm_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1005
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
struct dst_entry * xfrm_lookup(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags)
```

```json
{
  "name": "xfrm_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587375696,
      "name": "xfrm_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:2209",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/icmp.c:icmp_route_lookup",
        "net/ipv4/icmp.c:icmp_route_lookup",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587375696,
      "name": "xfrm_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 996
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
struct dst_entry * xfrm_lookup(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags)
```

```json
{
  "name": "xfrm_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587578768,
      "name": "xfrm_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:2237",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/icmp.c:icmp_route_lookup",
        "net/ipv4/icmp.c:icmp_route_lookup",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587578768,
      "name": "xfrm_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 996
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
struct dst_entry * xfrm_lookup(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags)
```

```json
{
  "name": "xfrm_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587724800,
      "name": "xfrm_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:2185",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587724800,
      "name": "xfrm_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1041
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
struct dst_entry * xfrm_lookup(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags)
```

```json
{
  "name": "xfrm_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588250144,
      "name": "xfrm_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:2127",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588250144,
      "name": "xfrm_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2293
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
struct dst_entry * xfrm_lookup(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags)
```

```json
{
  "name": "xfrm_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xfrm_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:2134",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588611644,
      "name": "xfrm_lookup.cold.58",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071588604960,
      "name": "xfrm_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2308
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
struct dst_entry * xfrm_lookup(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags)
```

```json
{
  "name": "xfrm_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588819056,
      "name": "xfrm_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3171",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588817744,
      "name": "xfrm_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
struct dst_entry * xfrm_lookup(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags)
```

```json
{
  "name": "xfrm_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589252198,
      "name": "xfrm_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3170",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589251040,
      "name": "xfrm_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
struct dst_entry * xfrm_lookup(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags)
```

```json
{
  "name": "xfrm_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589477494,
      "name": "xfrm_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3172",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589476336,
      "name": "xfrm_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
struct dst_entry * xfrm_lookup(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags)
```

```json
{
  "name": "xfrm_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590468738,
      "name": "xfrm_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3162",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590467184,
      "name": "xfrm_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
struct dst_entry * xfrm_lookup(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags)
```

```json
{
  "name": "xfrm_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590527218,
      "name": "xfrm_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3183",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590525584,
      "name": "xfrm_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
struct dst_entry * xfrm_lookup(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags)
```

```json
{
  "name": "xfrm_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590452514,
      "name": "xfrm_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3182",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590450832,
      "name": "xfrm_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
struct dst_entry * xfrm_lookup(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags)
```

```json
{
  "name": "xfrm_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591254134,
      "name": "xfrm_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3187",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591252352,
      "name": "xfrm_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
struct dst_entry * xfrm_lookup(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags)
```

```json
{
  "name": "xfrm_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592919230,
      "name": "xfrm_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3190",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592917376,
      "name": "xfrm_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct dst_entry * xfrm_lookup(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags)
```

```json
{
  "name": "xfrm_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594800158,
      "name": "xfrm_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3264",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594798256,
      "name": "xfrm_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct dst_entry * xfrm_lookup(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags)
```

```json
{
  "name": "xfrm_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595191855,
      "name": "xfrm_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3266",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595189856,
      "name": "xfrm_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct dst_entry * xfrm_lookup(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags)
```

```json
{
  "name": "xfrm_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596032458,
      "name": "xfrm_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3288",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596030544,
      "name": "xfrm_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct dst_entry * xfrm_lookup(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags)
```

```json
{
  "name": "xfrm_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503135952,
      "name": "xfrm_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3172",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503134376,
      "name": "xfrm_lookup",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct dst_entry * xfrm_lookup(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags)
```

```json
{
  "name": "xfrm_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235816032,
      "name": "xfrm_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3172",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235814560,
      "name": "xfrm_lookup",
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
struct dst_entry * xfrm_lookup(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags)
```

```json
{
  "name": "xfrm_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296856924,
      "name": "xfrm_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3172",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296855184,
      "name": "xfrm_lookup",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct dst_entry * xfrm_lookup(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags)
```

```json
{
  "name": "xfrm_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279182038,
      "name": "xfrm_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3172",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279180828,
      "name": "xfrm_lookup",
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
struct dst_entry * xfrm_lookup(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags)
```

```json
{
  "name": "xfrm_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589081862,
      "name": "xfrm_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3172",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589080704,
      "name": "xfrm_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
struct dst_entry * xfrm_lookup(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags)
```

```json
{
  "name": "xfrm_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588806902,
      "name": "xfrm_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3172",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588805744,
      "name": "xfrm_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
struct dst_entry * xfrm_lookup(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags)
```

```json
{
  "name": "xfrm_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589518726,
      "name": "xfrm_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3172",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589517568,
      "name": "xfrm_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
struct dst_entry * xfrm_lookup(struct net * net, struct dst_entry * dst_orig, const struct flowi * fl, const struct sock * sk, int flags)
```

```json
{
  "name": "xfrm_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589565798,
      "name": "xfrm_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3172",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589564608,
      "name": "xfrm_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
