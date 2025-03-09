# Function: <code>ndisc_update</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void ndisc_update(const struct net_device * dev, struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options * ndopts)
```

```json
{
  "name": "ndisc_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587552512,
      "name": "ndisc_update",
      "external": true,
      "loc": "net/ipv6/ndisc.c:723",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587552512,
      "name": "ndisc_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void ndisc_update(const struct net_device * dev, struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options * ndopts)
```

```json
{
  "name": "ndisc_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587757024,
      "name": "ndisc_update",
      "external": true,
      "loc": "net/ipv6/ndisc.c:731",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587757024,
      "name": "ndisc_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void ndisc_update(const struct net_device * dev, struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options * ndopts)
```

```json
{
  "name": "ndisc_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587912912,
      "name": "ndisc_update",
      "external": true,
      "loc": "net/ipv6/ndisc.c:731",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587912912,
      "name": "ndisc_update",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void ndisc_update(const struct net_device * dev, struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options * ndopts)
```

```json
{
  "name": "ndisc_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588447968,
      "name": "ndisc_update",
      "external": true,
      "loc": "net/ipv6/ndisc.c:744",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588447968,
      "name": "ndisc_update",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void ndisc_update(const struct net_device * dev, struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options * ndopts)
```

```json
{
  "name": "ndisc_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588809344,
      "name": "ndisc_update",
      "external": true,
      "loc": "net/ipv6/ndisc.c:744",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588809344,
      "name": "ndisc_update",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void ndisc_update(const struct net_device * dev, struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options * ndopts)
```

```json
{
  "name": "ndisc_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589032080,
      "name": "ndisc_update",
      "external": true,
      "loc": "net/ipv6/ndisc.c:744",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589032080,
      "name": "ndisc_update",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void ndisc_update(const struct net_device * dev, struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options * ndopts)
```

```json
{
  "name": "ndisc_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589485344,
      "name": "ndisc_update",
      "external": true,
      "loc": "net/ipv6/ndisc.c:757",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589485344,
      "name": "ndisc_update",
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
void ndisc_update(const struct net_device * dev, struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options * ndopts)
```

```json
{
  "name": "ndisc_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589709216,
      "name": "ndisc_update",
      "external": true,
      "loc": "net/ipv6/ndisc.c:758",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589709216,
      "name": "ndisc_update",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ndisc_update(const struct net_device * dev, struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options * ndopts)
```

```json
{
  "name": "ndisc_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590728322,
      "name": "ndisc_update",
      "external": true,
      "loc": "net/ipv6/ndisc.c:759",
      "file": "net/ipv6/ndisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590734688,
      "name": "ndisc_update",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ndisc_update(const struct net_device * dev, struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options * ndopts)
```

```json
{
  "name": "ndisc_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590787234,
      "name": "ndisc_update",
      "external": true,
      "loc": "net/ipv6/ndisc.c:761",
      "file": "net/ipv6/ndisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590793680,
      "name": "ndisc_update",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ndisc_update(const struct net_device * dev, struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options * ndopts)
```

```json
{
  "name": "ndisc_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590714432,
      "name": "ndisc_update",
      "external": true,
      "loc": "net/ipv6/ndisc.c:761",
      "file": "net/ipv6/ndisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590720704,
      "name": "ndisc_update",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ndisc_update(const struct net_device * dev, struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options * ndopts)
```

```json
{
  "name": "ndisc_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591530736,
      "name": "ndisc_update",
      "external": true,
      "loc": "net/ipv6/ndisc.c:761",
      "file": "net/ipv6/ndisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591537104,
      "name": "ndisc_update",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ndisc_update(const struct net_device * dev, struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options * ndopts)
```

```json
{
  "name": "ndisc_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593218904,
      "name": "ndisc_update",
      "external": true,
      "loc": "net/ipv6/ndisc.c:776",
      "file": "net/ipv6/ndisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593226016,
      "name": "ndisc_update",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ndisc_update(const struct net_device * dev, struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options * ndopts)
```

```json
{
  "name": "ndisc_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595118424,
      "name": "ndisc_update",
      "external": true,
      "loc": "net/ipv6/ndisc.c:777",
      "file": "net/ipv6/ndisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595125728,
      "name": "ndisc_update",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ndisc_update(const struct net_device * dev, struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options * ndopts)
```

```json
{
  "name": "ndisc_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595512317,
      "name": "ndisc_update",
      "external": true,
      "loc": "net/ipv6/ndisc.c:778",
      "file": "net/ipv6/ndisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595519776,
      "name": "ndisc_update",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ndisc_update(const struct net_device * dev, struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options * ndopts)
```

```json
{
  "name": "ndisc_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596355760,
      "name": "ndisc_update",
      "external": true,
      "loc": "net/ipv6/ndisc.c:778",
      "file": "net/ipv6/ndisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596363136,
      "name": "ndisc_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void ndisc_update(const struct net_device * dev, struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options * ndopts)
```

```json
{
  "name": "ndisc_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503400760,
      "name": "ndisc_update",
      "external": true,
      "loc": "net/ipv6/ndisc.c:758",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503400760,
      "name": "ndisc_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void ndisc_update(const struct net_device * dev, struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options * ndopts)
```

```json
{
  "name": "ndisc_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236062156,
      "name": "ndisc_update",
      "external": true,
      "loc": "net/ipv6/ndisc.c:758",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_rcv",
        "net/ipv6/ndisc.c:ndisc_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236062156,
      "name": "ndisc_update",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void ndisc_update(const struct net_device * dev, struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options * ndopts)
```

```json
{
  "name": "ndisc_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297175696,
      "name": "ndisc_update",
      "external": true,
      "loc": "net/ipv6/ndisc.c:758",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297175696,
      "name": "ndisc_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void ndisc_update(const struct net_device * dev, struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options * ndopts)
```

```json
{
  "name": "ndisc_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279394120,
      "name": "ndisc_update",
      "external": true,
      "loc": "net/ipv6/ndisc.c:758",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279394120,
      "name": "ndisc_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void ndisc_update(const struct net_device * dev, struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options * ndopts)
```

```json
{
  "name": "ndisc_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589313584,
      "name": "ndisc_update",
      "external": true,
      "loc": "net/ipv6/ndisc.c:758",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589313584,
      "name": "ndisc_update",
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
void ndisc_update(const struct net_device * dev, struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options * ndopts)
```

```json
{
  "name": "ndisc_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589038576,
      "name": "ndisc_update",
      "external": true,
      "loc": "net/ipv6/ndisc.c:758",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589038576,
      "name": "ndisc_update",
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
void ndisc_update(const struct net_device * dev, struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options * ndopts)
```

```json
{
  "name": "ndisc_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589750448,
      "name": "ndisc_update",
      "external": true,
      "loc": "net/ipv6/ndisc.c:758",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589750448,
      "name": "ndisc_update",
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
void ndisc_update(const struct net_device * dev, struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options * ndopts)
```

```json
{
  "name": "ndisc_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589801104,
      "name": "ndisc_update",
      "external": true,
      "loc": "net/ipv6/ndisc.c:758",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_recv_rs",
        "net/ipv6/ndisc.c:ndisc_recv_na",
        "net/ipv6/ndisc.c:ndisc_recv_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589801104,
      "name": "ndisc_update",
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
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void ndisc_update(const struct net_device * dev, struct neighbour * neigh, const u8 * lladdr, u8 new, u32 flags, u8 icmp6_type, struct ndisc_options * ndopts)
```
</details>
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
