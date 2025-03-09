# Function: <code>inet_getpeer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct inet_peer * inet_getpeer(struct inet_peer_base * base, const struct inetpeer_addr * daddr, int create)
```

```json
{
  "name": "inet_getpeer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586545952,
      "name": "inet_getpeer",
      "external": true,
      "loc": "net/ipv4/inetpeer.c:403",
      "file": "net/ipv4/inetpeer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip4_frag_init",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586545952,
      "name": "inet_getpeer.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1045
    },
    {
      "addr": 18446744071586547008,
      "name": "inet_getpeer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct inet_peer * inet_getpeer(struct inet_peer_base * base, const struct inetpeer_addr * daddr, int create)
```

```json
{
  "name": "inet_getpeer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586989008,
      "name": "inet_getpeer",
      "external": true,
      "loc": "net/ipv4/inetpeer.c:403",
      "file": "net/ipv4/inetpeer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip4_frag_init",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586989008,
      "name": "inet_getpeer.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1095
    },
    {
      "addr": 18446744071586990112,
      "name": "inet_getpeer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct inet_peer * inet_getpeer(struct inet_peer_base * base, const struct inetpeer_addr * daddr, int create)
```

```json
{
  "name": "inet_getpeer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587184368,
      "name": "inet_getpeer",
      "external": true,
      "loc": "net/ipv4/inetpeer.c:403",
      "file": "net/ipv4/inetpeer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip4_frag_init",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587184368,
      "name": "inet_getpeer.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1095
    },
    {
      "addr": 18446744071587185472,
      "name": "inet_getpeer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct inet_peer * inet_getpeer(struct inet_peer_base * base, const struct inetpeer_addr * daddr, int create)
```

```json
{
  "name": "inet_getpeer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587316448,
      "name": "inet_getpeer",
      "external": true,
      "loc": "net/ipv4/inetpeer.c:403",
      "file": "net/ipv4/inetpeer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip4_frag_init",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587316448,
      "name": "inet_getpeer.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1168
    },
    {
      "addr": 18446744071587317616,
      "name": "inet_getpeer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
struct inet_peer * inet_getpeer(struct inet_peer_base * base, const struct inetpeer_addr * daddr, int create)
```

```json
{
  "name": "inet_getpeer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587837520,
      "name": "inet_getpeer",
      "external": true,
      "loc": "net/ipv4/inetpeer.c:176",
      "file": "net/ipv4/inetpeer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip4_frag_init",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587837520,
      "name": "inet_getpeer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 728
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct inet_peer * inet_getpeer(struct inet_peer_base * base, const struct inetpeer_addr * daddr, int create)
```

```json
{
  "name": "inet_getpeer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588182432,
      "name": "inet_getpeer",
      "external": true,
      "loc": "net/ipv4/inetpeer.c:177",
      "file": "net/ipv4/inetpeer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip4_frag_init",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588182432,
      "name": "inet_getpeer.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 737
    },
    {
      "addr": 18446744071588183184,
      "name": "inet_getpeer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct inet_peer * inet_getpeer(struct inet_peer_base * base, const struct inetpeer_addr * daddr, int create)
```

```json
{
  "name": "inet_getpeer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588366416,
      "name": "inet_getpeer",
      "external": true,
      "loc": "net/ipv4/inetpeer.c:177",
      "file": "net/ipv4/inetpeer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip4_frag_init",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588366416,
      "name": "inet_getpeer.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 737
    },
    {
      "addr": 18446744071588367168,
      "name": "inet_getpeer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct inet_peer * inet_getpeer(struct inet_peer_base * base, const struct inetpeer_addr * daddr, int create)
```

```json
{
  "name": "inet_getpeer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588768880,
      "name": "inet_getpeer",
      "external": true,
      "loc": "net/ipv4/inetpeer.c:177",
      "file": "net/ipv4/inetpeer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip4_frag_init",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588768880,
      "name": "inet_getpeer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 774
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
struct inet_peer * inet_getpeer(struct inet_peer_base * base, const struct inetpeer_addr * daddr, int create)
```

```json
{
  "name": "inet_getpeer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588992512,
      "name": "inet_getpeer",
      "external": true,
      "loc": "net/ipv4/inetpeer.c:182",
      "file": "net/ipv4/inetpeer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip4_frag_init",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588992512,
      "name": "inet_getpeer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 776
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
struct inet_peer * inet_getpeer(struct inet_peer_base * base, const struct inetpeer_addr * daddr, int create)
```

```json
{
  "name": "inet_getpeer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589950864,
      "name": "inet_getpeer",
      "external": true,
      "loc": "net/ipv4/inetpeer.c:182",
      "file": "net/ipv4/inetpeer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip4_frag_init",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589950864,
      "name": "inet_getpeer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
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
struct inet_peer * inet_getpeer(struct inet_peer_base * base, const struct inetpeer_addr * daddr, int create)
```

```json
{
  "name": "inet_getpeer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589991760,
      "name": "inet_getpeer",
      "external": true,
      "loc": "net/ipv4/inetpeer.c:182",
      "file": "net/ipv4/inetpeer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip4_frag_init",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589991760,
      "name": "inet_getpeer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 516
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
struct inet_peer * inet_getpeer(struct inet_peer_base * base, const struct inetpeer_addr * daddr, int create)
```

```json
{
  "name": "inet_getpeer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589905568,
      "name": "inet_getpeer",
      "external": true,
      "loc": "net/ipv4/inetpeer.c:175",
      "file": "net/ipv4/inetpeer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip4_frag_init",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589905568,
      "name": "inet_getpeer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 739
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
struct inet_peer * inet_getpeer(struct inet_peer_base * base, const struct inetpeer_addr * daddr, int create)
```

```json
{
  "name": "inet_getpeer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590671840,
      "name": "inet_getpeer",
      "external": true,
      "loc": "net/ipv4/inetpeer.c:175",
      "file": "net/ipv4/inetpeer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip4_frag_init",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590671840,
      "name": "inet_getpeer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 739
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
struct inet_peer * inet_getpeer(struct inet_peer_base * base, const struct inetpeer_addr * daddr, int create)
```

```json
{
  "name": "inet_getpeer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592298416,
      "name": "inet_getpeer",
      "external": true,
      "loc": "net/ipv4/inetpeer.c:179",
      "file": "net/ipv4/inetpeer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip4_frag_init",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592298416,
      "name": "inet_getpeer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 829
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
struct inet_peer * inet_getpeer(struct inet_peer_base * base, const struct inetpeer_addr * daddr, int create)
```

```json
{
  "name": "inet_getpeer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594134160,
      "name": "inet_getpeer",
      "external": true,
      "loc": "net/ipv4/inetpeer.c:179",
      "file": "net/ipv4/inetpeer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip4_frag_init",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594134160,
      "name": "inet_getpeer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 829
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
struct inet_peer * inet_getpeer(struct inet_peer_base * base, const struct inetpeer_addr * daddr, int create)
```

```json
{
  "name": "inet_getpeer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594521184,
      "name": "inet_getpeer",
      "external": true,
      "loc": "net/ipv4/inetpeer.c:179",
      "file": "net/ipv4/inetpeer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip4_frag_init",
        "net/ipv4/icmp.c:icmpv4_xrlim_allow",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594521184,
      "name": "inet_getpeer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 832
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
struct inet_peer * inet_getpeer(struct inet_peer_base * base, const struct inetpeer_addr * daddr, int create)
```

```json
{
  "name": "inet_getpeer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595323888,
      "name": "inet_getpeer",
      "external": true,
      "loc": "net/ipv4/inetpeer.c:179",
      "file": "net/ipv4/inetpeer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip4_frag_init",
        "net/ipv4/icmp.c:icmpv4_xrlim_allow",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595323888,
      "name": "inet_getpeer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 832
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
struct inet_peer * inet_getpeer(struct inet_peer_base * base, const struct inetpeer_addr * daddr, int create)
```

```json
{
  "name": "inet_getpeer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502597976,
      "name": "inet_getpeer",
      "external": true,
      "loc": "net/ipv4/inetpeer.c:182",
      "file": "net/ipv4/inetpeer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip4_frag_init",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502597976,
      "name": "inet_getpeer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 820
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
struct inet_peer * inet_getpeer(struct inet_peer_base * base, const struct inetpeer_addr * daddr, int create)
```

```json
{
  "name": "inet_getpeer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235302696,
      "name": "inet_getpeer",
      "external": true,
      "loc": "net/ipv4/inetpeer.c:182",
      "file": "net/ipv4/inetpeer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip4_frag_init",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235302696,
      "name": "inet_getpeer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 808
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
struct inet_peer * inet_getpeer(struct inet_peer_base * base, const struct inetpeer_addr * daddr, int create)
```

```json
{
  "name": "inet_getpeer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296187984,
      "name": "inet_getpeer",
      "external": true,
      "loc": "net/ipv4/inetpeer.c:182",
      "file": "net/ipv4/inetpeer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip4_frag_init",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296187984,
      "name": "inet_getpeer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 972
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
struct inet_peer * inet_getpeer(struct inet_peer_base * base, const struct inetpeer_addr * daddr, int create)
```

```json
{
  "name": "inet_getpeer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278749750,
      "name": "inet_getpeer",
      "external": true,
      "loc": "net/ipv4/inetpeer.c:182",
      "file": "net/ipv4/inetpeer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip4_frag_init",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278749750,
      "name": "inet_getpeer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 626
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
struct inet_peer * inet_getpeer(struct inet_peer_base * base, const struct inetpeer_addr * daddr, int create)
```

```json
{
  "name": "inet_getpeer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588598896,
      "name": "inet_getpeer",
      "external": true,
      "loc": "net/ipv4/inetpeer.c:182",
      "file": "net/ipv4/inetpeer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip4_frag_init",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588598896,
      "name": "inet_getpeer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 776
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
struct inet_peer * inet_getpeer(struct inet_peer_base * base, const struct inetpeer_addr * daddr, int create)
```

```json
{
  "name": "inet_getpeer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588310880,
      "name": "inet_getpeer",
      "external": true,
      "loc": "net/ipv4/inetpeer.c:182",
      "file": "net/ipv4/inetpeer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip4_frag_init",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588310880,
      "name": "inet_getpeer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 776
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
struct inet_peer * inet_getpeer(struct inet_peer_base * base, const struct inetpeer_addr * daddr, int create)
```

```json
{
  "name": "inet_getpeer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589035072,
      "name": "inet_getpeer",
      "external": true,
      "loc": "net/ipv4/inetpeer.c:182",
      "file": "net/ipv4/inetpeer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip4_frag_init",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589035072,
      "name": "inet_getpeer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 776
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
struct inet_peer * inet_getpeer(struct inet_peer_base * base, const struct inetpeer_addr * daddr, int create)
```

```json
{
  "name": "inet_getpeer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589074096,
      "name": "inet_getpeer",
      "external": true,
      "loc": "net/ipv4/inetpeer.c:182",
      "file": "net/ipv4/inetpeer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_error",
        "net/ipv4/route.c:ip_rt_send_redirect",
        "net/ipv4/ip_fragment.c:ip4_frag_init",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ndisc.c:ndisc_send_redirect",
        "net/ipv6/icmp.c:icmpv6_xrlim_allow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589074096,
      "name": "inet_getpeer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 768
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
