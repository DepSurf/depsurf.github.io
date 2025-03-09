# Function: <code>lwtunnel_build_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int lwtunnel_build_state(struct net_device * dev, u16 encap_type, struct nlattr * encap, unsigned int family, const void * cfg, struct lwtunnel_state * * lws)
```

```json
{
  "name": "lwtunnel_build_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586439296,
      "name": "lwtunnel_build_state",
      "external": true,
      "loc": "net/core/lwtunnel.c:74",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586439296,
      "name": "lwtunnel_build_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int lwtunnel_build_state(struct net_device * dev, u16 encap_type, struct nlattr * encap, unsigned int family, const void * cfg, struct lwtunnel_state * * lws)
```

```json
{
  "name": "lwtunnel_build_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586883968,
      "name": "lwtunnel_build_state",
      "external": true,
      "loc": "net/core/lwtunnel.c:99",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586883968,
      "name": "lwtunnel_build_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int lwtunnel_build_state(struct net_device * dev, u16 encap_type, struct nlattr * encap, unsigned int family, const void * cfg, struct lwtunnel_state * * lws)
```

```json
{
  "name": "lwtunnel_build_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587075328,
      "name": "lwtunnel_build_state",
      "external": true,
      "loc": "net/core/lwtunnel.c:104",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587075328,
      "name": "lwtunnel_build_state",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int lwtunnel_build_state(u16 encap_type, struct nlattr * encap, unsigned int family, const void * cfg, struct lwtunnel_state * * lws, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_build_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587203392,
      "name": "lwtunnel_build_state",
      "external": true,
      "loc": "net/core/lwtunnel.c:104",
      "file": "net/core/lwtunnel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587203392,
      "name": "lwtunnel_build_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
int lwtunnel_build_state(u16 encap_type, struct nlattr * encap, unsigned int family, const void * cfg, struct lwtunnel_state * * lws, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_build_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587717664,
      "name": "lwtunnel_build_state",
      "external": true,
      "loc": "net/core/lwtunnel.c:106",
      "file": "net/core/lwtunnel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587717664,
      "name": "lwtunnel_build_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int lwtunnel_build_state(u16 encap_type, struct nlattr * encap, unsigned int family, const void * cfg, struct lwtunnel_state * * lws, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_build_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588050768,
      "name": "lwtunnel_build_state",
      "external": true,
      "loc": "net/core/lwtunnel.c:106",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588050768,
      "name": "lwtunnel_build_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int lwtunnel_build_state(u16 encap_type, struct nlattr * encap, unsigned int family, const void * cfg, struct lwtunnel_state * * lws, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_build_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588219024,
      "name": "lwtunnel_build_state",
      "external": true,
      "loc": "net/core/lwtunnel.c:106",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588219024,
      "name": "lwtunnel_build_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int lwtunnel_build_state(u16 encap_type, struct nlattr * encap, unsigned int family, const void * cfg, struct lwtunnel_state * * lws, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_build_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588553136,
      "name": "lwtunnel_build_state",
      "external": true,
      "loc": "net/core/lwtunnel.c:101",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_nh_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588553136,
      "name": "lwtunnel_build_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int lwtunnel_build_state(u16 encap_type, struct nlattr * encap, unsigned int family, const void * cfg, struct lwtunnel_state * * lws, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_build_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588770032,
      "name": "lwtunnel_build_state",
      "external": true,
      "loc": "net/core/lwtunnel.c:101",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_nh_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588770032,
      "name": "lwtunnel_build_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int lwtunnel_build_state(struct net * net, u16 encap_type, struct nlattr * encap, unsigned int family, const void * cfg, struct lwtunnel_state * * lws, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_build_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589641904,
      "name": "lwtunnel_build_state",
      "external": true,
      "loc": "net/core/lwtunnel.c:103",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_nh_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589641904,
      "name": "lwtunnel_build_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
int lwtunnel_build_state(struct net * net, u16 encap_type, struct nlattr * encap, unsigned int family, const void * cfg, struct lwtunnel_state * * lws, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_build_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589665456,
      "name": "lwtunnel_build_state",
      "external": true,
      "loc": "net/core/lwtunnel.c:103",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_nh_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589665456,
      "name": "lwtunnel_build_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
int lwtunnel_build_state(struct net * net, u16 encap_type, struct nlattr * encap, unsigned int family, const void * cfg, struct lwtunnel_state * * lws, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_build_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589557088,
      "name": "lwtunnel_build_state",
      "external": true,
      "loc": "net/core/lwtunnel.c:103",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_nh_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589557088,
      "name": "lwtunnel_build_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int lwtunnel_build_state(struct net * net, u16 encap_type, struct nlattr * encap, unsigned int family, const void * cfg, struct lwtunnel_state * * lws, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_build_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590301648,
      "name": "lwtunnel_build_state",
      "external": true,
      "loc": "net/core/lwtunnel.c:108",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_nh_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590301648,
      "name": "lwtunnel_build_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
int lwtunnel_build_state(struct net * net, u16 encap_type, struct nlattr * encap, unsigned int family, const void * cfg, struct lwtunnel_state * * lws, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_build_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591885856,
      "name": "lwtunnel_build_state",
      "external": true,
      "loc": "net/core/lwtunnel.c:108",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_common_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591885856,
      "name": "lwtunnel_build_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
int lwtunnel_build_state(struct net * net, u16 encap_type, struct nlattr * encap, unsigned int family, const void * cfg, struct lwtunnel_state * * lws, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_build_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593687872,
      "name": "lwtunnel_build_state",
      "external": true,
      "loc": "net/core/lwtunnel.c:111",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_common_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593687872,
      "name": "lwtunnel_build_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
int lwtunnel_build_state(struct net * net, u16 encap_type, struct nlattr * encap, unsigned int family, const void * cfg, struct lwtunnel_state * * lws, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_build_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594168656,
      "name": "lwtunnel_build_state",
      "external": true,
      "loc": "net/core/lwtunnel.c:111",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_common_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594168656,
      "name": "lwtunnel_build_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
int lwtunnel_build_state(struct net * net, u16 encap_type, struct nlattr * encap, unsigned int family, const void * cfg, struct lwtunnel_state * * lws, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_build_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594965200,
      "name": "lwtunnel_build_state",
      "external": true,
      "loc": "net/core/lwtunnel.c:111",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_nh_match",
        "net/ipv4/fib_semantics.c:fib_nh_common_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594965200,
      "name": "lwtunnel_build_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
int lwtunnel_build_state(u16 encap_type, struct nlattr * encap, unsigned int family, const void * cfg, struct lwtunnel_state * * lws, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_build_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502335968,
      "name": "lwtunnel_build_state",
      "external": true,
      "loc": "net/core/lwtunnel.c:101",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_nh_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502335968,
      "name": "lwtunnel_build_state",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int lwtunnel_build_state(u16 encap_type, struct nlattr * encap, unsigned int family, const void * cfg, struct lwtunnel_state * * lws, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_build_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235075728,
      "name": "lwtunnel_build_state",
      "external": true,
      "loc": "net/core/lwtunnel.c:101",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_nh_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235075728,
      "name": "lwtunnel_build_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int lwtunnel_build_state(u16 encap_type, struct nlattr * encap, unsigned int family, const void * cfg, struct lwtunnel_state * * lws, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_build_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295856176,
      "name": "lwtunnel_build_state",
      "external": true,
      "loc": "net/core/lwtunnel.c:101",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_nh_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295856176,
      "name": "lwtunnel_build_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
int lwtunnel_build_state(u16 encap_type, struct nlattr * encap, unsigned int family, const void * cfg, struct lwtunnel_state * * lws, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_build_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278558198,
      "name": "lwtunnel_build_state",
      "external": true,
      "loc": "net/core/lwtunnel.c:101",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_nh_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278558198,
      "name": "lwtunnel_build_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int lwtunnel_build_state(u16 encap_type, struct nlattr * encap, unsigned int family, const void * cfg, struct lwtunnel_state * * lws, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_build_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588376416,
      "name": "lwtunnel_build_state",
      "external": true,
      "loc": "net/core/lwtunnel.c:101",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_nh_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588376416,
      "name": "lwtunnel_build_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int lwtunnel_build_state(u16 encap_type, struct nlattr * encap, unsigned int family, const void * cfg, struct lwtunnel_state * * lws, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_build_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588089104,
      "name": "lwtunnel_build_state",
      "external": true,
      "loc": "net/core/lwtunnel.c:101",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_nh_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588089104,
      "name": "lwtunnel_build_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int lwtunnel_build_state(u16 encap_type, struct nlattr * encap, unsigned int family, const void * cfg, struct lwtunnel_state * * lws, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_build_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588708592,
      "name": "lwtunnel_build_state",
      "external": true,
      "loc": "net/core/lwtunnel.c:101",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_nh_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588708592,
      "name": "lwtunnel_build_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int lwtunnel_build_state(u16 encap_type, struct nlattr * encap, unsigned int family, const void * cfg, struct lwtunnel_state * * lws, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_build_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588848512,
      "name": "lwtunnel_build_state",
      "external": true,
      "loc": "net/core/lwtunnel.c:101",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_nh_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588848512,
      "name": "lwtunnel_build_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack * extack</code>
</li>
<li>
<b>Param removed. </b>
<code>struct net_device * dev</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, encap_type, encap, family, cfg, lws</code> ➡️ <code>encap_type, encap, family, cfg, lws, extack</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net * net</code>
</li>
<li>
<b>Param reordered. </b>
<code>encap_type, encap, family, cfg, lws, extack</code> ➡️ <code>net, encap_type, encap, family, cfg, lws, extack</code>
</li>
</ul>
</details>
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
