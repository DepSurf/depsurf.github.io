# Function: <code>__xfrm_decode_session</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __xfrm_decode_session(struct sk_buff * skb, struct flowi * fl, unsigned int family, int reverse)
```

```json
{
  "name": "__xfrm_decode_session",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586910624,
      "name": "__xfrm_decode_session",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:2434",
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
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586910624,
      "name": "__xfrm_decode_session",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int __xfrm_decode_session(struct sk_buff * skb, struct flowi * fl, unsigned int family, int reverse)
```

```json
{
  "name": "__xfrm_decode_session",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587356912,
      "name": "__xfrm_decode_session",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:2438",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/icmp.c:icmp_route_lookup",
        "net/ipv4/icmp.c:icmp_route_lookup",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587356912,
      "name": "__xfrm_decode_session",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int __xfrm_decode_session(struct sk_buff * skb, struct flowi * fl, unsigned int family, int reverse)
```

```json
{
  "name": "__xfrm_decode_session",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587559792,
      "name": "__xfrm_decode_session",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:2466",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/icmp.c:icmp_route_lookup",
        "net/ipv4/icmp.c:icmp_route_lookup",
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587559792,
      "name": "__xfrm_decode_session",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int __xfrm_decode_session(struct sk_buff * skb, struct flowi * fl, unsigned int family, int reverse)
```

```json
{
  "name": "__xfrm_decode_session",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587706240,
      "name": "__xfrm_decode_session",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:2412",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587706240,
      "name": "__xfrm_decode_session",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int __xfrm_decode_session(struct sk_buff * skb, struct flowi * fl, unsigned int family, int reverse)
```

```json
{
  "name": "__xfrm_decode_session",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588232960,
      "name": "__xfrm_decode_session",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:2354",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588232960,
      "name": "__xfrm_decode_session",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int __xfrm_decode_session(struct sk_buff * skb, struct flowi * fl, unsigned int family, int reverse)
```

```json
{
  "name": "__xfrm_decode_session",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588587232,
      "name": "__xfrm_decode_session",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:2364",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588587232,
      "name": "__xfrm_decode_session",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int __xfrm_decode_session(struct sk_buff * skb, struct flowi * fl, unsigned int family, int reverse)
```

```json
{
  "name": "__xfrm_decode_session",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588792112,
      "name": "__xfrm_decode_session",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3266",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588792112,
      "name": "__xfrm_decode_session",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int __xfrm_decode_session(struct sk_buff * skb, struct flowi * fl, unsigned int family, int reverse)
```

```json
{
  "name": "__xfrm_decode_session",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589233872,
      "name": "__xfrm_decode_session",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3473",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589233872,
      "name": "__xfrm_decode_session",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2066
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
int __xfrm_decode_session(struct sk_buff * skb, struct flowi * fl, unsigned int family, int reverse)
```

```json
{
  "name": "__xfrm_decode_session",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589459168,
      "name": "__xfrm_decode_session",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3475",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589459168,
      "name": "__xfrm_decode_session",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2066
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
int __xfrm_decode_session(struct sk_buff * skb, struct flowi * fl, unsigned int family, int reverse)
```

```json
{
  "name": "__xfrm_decode_session",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590468669,
      "name": "__xfrm_decode_session",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3465",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590454944,
      "name": "__xfrm_decode_session",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int __xfrm_decode_session(struct sk_buff * skb, struct flowi * fl, unsigned int family, int reverse)
```

```json
{
  "name": "__xfrm_decode_session",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590527149,
      "name": "__xfrm_decode_session",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3486",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590513392,
      "name": "__xfrm_decode_session",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int __xfrm_decode_session(struct sk_buff * skb, struct flowi * fl, unsigned int family, int reverse)
```

```json
{
  "name": "__xfrm_decode_session",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590452445,
      "name": "__xfrm_decode_session",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3446",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590438288,
      "name": "__xfrm_decode_session",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int __xfrm_decode_session(struct sk_buff * skb, struct flowi * fl, unsigned int family, int reverse)
```

```json
{
  "name": "__xfrm_decode_session",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591254061,
      "name": "__xfrm_decode_session",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3471",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591238272,
      "name": "__xfrm_decode_session",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int __xfrm_decode_session(struct sk_buff * skb, struct flowi * fl, unsigned int family, int reverse)
```

```json
{
  "name": "__xfrm_decode_session",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592919150,
      "name": "__xfrm_decode_session",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3473",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592901632,
      "name": "__xfrm_decode_session",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __xfrm_decode_session(struct sk_buff * skb, struct flowi * fl, unsigned int family, int reverse)
```

```json
{
  "name": "__xfrm_decode_session",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594800078,
      "name": "__xfrm_decode_session",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3547",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594781808,
      "name": "__xfrm_decode_session",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __xfrm_decode_session(struct sk_buff * skb, struct flowi * fl, unsigned int family, int reverse)
```

```json
{
  "name": "__xfrm_decode_session",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595191694,
      "name": "__xfrm_decode_session",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3557",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process"
      ],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595179504,
      "name": "__xfrm_decode_session",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int __xfrm_decode_session(struct net * net, struct sk_buff * skb, struct flowi * fl, unsigned int family, int reverse)
```

```json
{
  "name": "__xfrm_decode_session",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595996320,
      "name": "__xfrm_decode_session",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3458",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595996320,
      "name": "__xfrm_decode_session",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 662
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
int __xfrm_decode_session(struct sk_buff * skb, struct flowi * fl, unsigned int family, int reverse)
```

```json
{
  "name": "__xfrm_decode_session",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503112816,
      "name": "__xfrm_decode_session",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3475",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503112816,
      "name": "__xfrm_decode_session",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1844
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
int __xfrm_decode_session(struct sk_buff * skb, struct flowi * fl, unsigned int family, int reverse)
```

```json
{
  "name": "__xfrm_decode_session",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235798496,
      "name": "__xfrm_decode_session",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3475",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235798496,
      "name": "__xfrm_decode_session",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2236
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
int __xfrm_decode_session(struct sk_buff * skb, struct flowi * fl, unsigned int family, int reverse)
```

```json
{
  "name": "__xfrm_decode_session",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296844928,
      "name": "__xfrm_decode_session",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3475",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296844928,
      "name": "__xfrm_decode_session",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2648
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
int __xfrm_decode_session(struct sk_buff * skb, struct flowi * fl, unsigned int family, int reverse)
```

```json
{
  "name": "__xfrm_decode_session",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279170464,
      "name": "__xfrm_decode_session",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3475",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279170464,
      "name": "__xfrm_decode_session",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1554
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
int __xfrm_decode_session(struct sk_buff * skb, struct flowi * fl, unsigned int family, int reverse)
```

```json
{
  "name": "__xfrm_decode_session",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589063536,
      "name": "__xfrm_decode_session",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3475",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589063536,
      "name": "__xfrm_decode_session",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2066
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
int __xfrm_decode_session(struct sk_buff * skb, struct flowi * fl, unsigned int family, int reverse)
```

```json
{
  "name": "__xfrm_decode_session",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588788576,
      "name": "__xfrm_decode_session",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3475",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588788576,
      "name": "__xfrm_decode_session",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2066
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
int __xfrm_decode_session(struct sk_buff * skb, struct flowi * fl, unsigned int family, int reverse)
```

```json
{
  "name": "__xfrm_decode_session",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589500400,
      "name": "__xfrm_decode_session",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3475",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589500400,
      "name": "__xfrm_decode_session",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2066
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
int __xfrm_decode_session(struct sk_buff * skb, struct flowi * fl, unsigned int family, int reverse)
```

```json
{
  "name": "__xfrm_decode_session",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589546880,
      "name": "__xfrm_decode_session",
      "external": true,
      "loc": "net/xfrm/xfrm_policy.c:3475",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/netfilter.c:ip_route_me_harder",
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:__xfrm_policy_check",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/ipv6/icmp.c:icmpv6_route_lookup",
        "net/ipv6/netfilter.c:ip6_route_me_harder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589546880,
      "name": "__xfrm_decode_session",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2066
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net * net</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb, fl, family, reverse</code> ➡️ <code>net, skb, fl, family, reverse</code>
</li>
</ul>
</details>
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
