# Function: <code>ip6_neigh_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct neighbour * ip6_neigh_lookup(const struct dst_entry * dst, struct sk_buff * skb, const void * daddr)
```

```json
{
  "name": "ip6_neigh_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587058544,
      "name": "ip6_neigh_lookup",
      "external": false,
      "loc": "net/ipv6/route.c:203",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587058544,
      "name": "ip6_neigh_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
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
struct neighbour * ip6_neigh_lookup(const struct dst_entry * dst, struct sk_buff * skb, const void * daddr)
```

```json
{
  "name": "ip6_neigh_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587508864,
      "name": "ip6_neigh_lookup",
      "external": false,
      "loc": "net/ipv6/route.c:204",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587508864,
      "name": "ip6_neigh_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
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
struct neighbour * ip6_neigh_lookup(const struct dst_entry * dst, struct sk_buff * skb, const void * daddr)
```

```json
{
  "name": "ip6_neigh_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587713008,
      "name": "ip6_neigh_lookup",
      "external": false,
      "loc": "net/ipv6/route.c:206",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587713008,
      "name": "ip6_neigh_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
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
struct neighbour * ip6_neigh_lookup(const struct dst_entry * dst, struct sk_buff * skb, const void * daddr)
```

```json
{
  "name": "ip6_neigh_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587862432,
      "name": "ip6_neigh_lookup",
      "external": false,
      "loc": "net/ipv6/route.c:211",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587862432,
      "name": "ip6_neigh_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
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
struct neighbour * ip6_neigh_lookup(const struct dst_entry * dst, struct sk_buff * skb, const void * daddr)
```

```json
{
  "name": "ip6_neigh_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588391920,
      "name": "ip6_neigh_lookup",
      "external": false,
      "loc": "net/ipv6/route.c:217",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588391920,
      "name": "ip6_neigh_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
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
struct neighbour * ip6_neigh_lookup(const struct in6_addr * gw, struct net_device * dev, struct sk_buff * skb, const void * daddr)
```

```json
{
  "name": "ip6_neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588762976,
      "name": "ip6_neigh_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:202",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_dst_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588762976,
      "name": "ip6_neigh_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
struct neighbour * ip6_neigh_lookup(const struct in6_addr * gw, struct net_device * dev, struct sk_buff * skb, const void * daddr)
```

```json
{
  "name": "ip6_neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588983200,
      "name": "ip6_neigh_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:202",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_dst_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588983200,
      "name": "ip6_neigh_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
struct neighbour * ip6_neigh_lookup(const struct in6_addr * gw, struct net_device * dev, struct sk_buff * skb, const void * daddr)
```

```json
{
  "name": "ip6_neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589432112,
      "name": "ip6_neigh_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:199",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_dst_neigh_lookup",
        "net/ipv6/route.c:ip6_dst_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589432112,
      "name": "ip6_neigh_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
struct neighbour * ip6_neigh_lookup(const struct in6_addr * gw, struct net_device * dev, struct sk_buff * skb, const void * daddr)
```

```json
{
  "name": "ip6_neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589656464,
      "name": "ip6_neigh_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:200",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_dst_neigh_lookup",
        "net/ipv6/route.c:ip6_dst_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589656464,
      "name": "ip6_neigh_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
struct neighbour * ip6_neigh_lookup(const struct in6_addr * gw, struct net_device * dev, struct sk_buff * skb, const void * daddr)
```

```json
{
  "name": "ip6_neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590670032,
      "name": "ip6_neigh_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:200",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_dst_neigh_lookup",
        "net/ipv6/route.c:ip6_dst_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590670032,
      "name": "ip6_neigh_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
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
struct neighbour * ip6_neigh_lookup(const struct in6_addr * gw, struct net_device * dev, struct sk_buff * skb, const void * daddr)
```

```json
{
  "name": "ip6_neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590730448,
      "name": "ip6_neigh_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:201",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_dst_neigh_lookup",
        "net/ipv6/route.c:ip6_dst_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590730448,
      "name": "ip6_neigh_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
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
struct neighbour * ip6_neigh_lookup(const struct in6_addr * gw, struct net_device * dev, struct sk_buff * skb, const void * daddr)
```

```json
{
  "name": "ip6_neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590655728,
      "name": "ip6_neigh_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:204",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_dst_neigh_lookup",
        "net/ipv6/route.c:ip6_dst_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590655728,
      "name": "ip6_neigh_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct neighbour * ip6_neigh_lookup(const struct in6_addr * gw, struct net_device * dev, struct sk_buff * skb, const void * daddr)
```

```json
{
  "name": "ip6_neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6_neigh_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:204",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_dst_neigh_lookup",
        "net/ipv6/route.c:ip6_dst_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592738772,
      "name": "ip6_neigh_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071591469648,
      "name": "ip6_neigh_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 401
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct neighbour * ip6_neigh_lookup(const struct in6_addr * gw, struct net_device * dev, struct sk_buff * skb, const void * daddr)
```

```json
{
  "name": "ip6_neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6_neigh_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:209",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_dst_neigh_lookup",
        "net/ipv6/route.c:ip6_dst_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594625358,
      "name": "ip6_neigh_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071593152272,
      "name": "ip6_neigh_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
struct neighbour * ip6_neigh_lookup(const struct in6_addr * gw, struct net_device * dev, struct sk_buff * skb, const void * daddr)
```

```json
{
  "name": "ip6_neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6_neigh_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:209",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_dst_neigh_lookup",
        "net/ipv6/route.c:ip6_dst_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596359583,
      "name": "ip6_neigh_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071595049968,
      "name": "ip6_neigh_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
struct neighbour * ip6_neigh_lookup(const struct in6_addr * gw, struct net_device * dev, struct sk_buff * skb, const void * daddr)
```

```json
{
  "name": "ip6_neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6_neigh_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:209",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_dst_neigh_lookup",
        "net/ipv6/route.c:ip6_dst_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596888166,
      "name": "ip6_neigh_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071595443408,
      "name": "ip6_neigh_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 381
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
struct neighbour * ip6_neigh_lookup(const struct in6_addr * gw, struct net_device * dev, struct sk_buff * skb, const void * daddr)
```

```json
{
  "name": "ip6_neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ip6_neigh_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:209",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_dst_neigh_lookup",
        "net/ipv6/route.c:ip6_dst_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597812522,
      "name": "ip6_neigh_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071596285408,
      "name": "ip6_neigh_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 381
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
struct neighbour * ip6_neigh_lookup(const struct in6_addr * gw, struct net_device * dev, struct sk_buff * skb, const void * daddr)
```

```json
{
  "name": "ip6_neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503342696,
      "name": "ip6_neigh_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:200",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_dst_neigh_lookup",
        "net/ipv6/route.c:ip6_dst_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503342696,
      "name": "ip6_neigh_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
struct neighbour * ip6_neigh_lookup(const struct in6_addr * gw, struct net_device * dev, struct sk_buff * skb, const void * daddr)
```

```json
{
  "name": "ip6_neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236008504,
      "name": "ip6_neigh_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:200",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_dst_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236008504,
      "name": "ip6_neigh_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
struct neighbour * ip6_neigh_lookup(const struct in6_addr * gw, struct net_device * dev, struct sk_buff * skb, const void * daddr)
```

```json
{
  "name": "ip6_neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297105664,
      "name": "ip6_neigh_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:200",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_dst_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297105664,
      "name": "ip6_neigh_lookup",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct neighbour * ip6_neigh_lookup(const struct in6_addr * gw, struct net_device * dev, struct sk_buff * skb, const void * daddr)
```

```json
{
  "name": "ip6_neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279351766,
      "name": "ip6_neigh_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:200",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_dst_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279351766,
      "name": "ip6_neigh_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
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
struct neighbour * ip6_neigh_lookup(const struct in6_addr * gw, struct net_device * dev, struct sk_buff * skb, const void * daddr)
```

```json
{
  "name": "ip6_neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589260832,
      "name": "ip6_neigh_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:200",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_dst_neigh_lookup",
        "net/ipv6/route.c:ip6_dst_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589260832,
      "name": "ip6_neigh_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
struct neighbour * ip6_neigh_lookup(const struct in6_addr * gw, struct net_device * dev, struct sk_buff * skb, const void * daddr)
```

```json
{
  "name": "ip6_neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588985824,
      "name": "ip6_neigh_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:200",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_dst_neigh_lookup",
        "net/ipv6/route.c:ip6_dst_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588985824,
      "name": "ip6_neigh_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
struct neighbour * ip6_neigh_lookup(const struct in6_addr * gw, struct net_device * dev, struct sk_buff * skb, const void * daddr)
```

```json
{
  "name": "ip6_neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589697696,
      "name": "ip6_neigh_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:200",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_dst_neigh_lookup",
        "net/ipv6/route.c:ip6_dst_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589697696,
      "name": "ip6_neigh_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
struct neighbour * ip6_neigh_lookup(const struct in6_addr * gw, struct net_device * dev, struct sk_buff * skb, const void * daddr)
```

```json
{
  "name": "ip6_neigh_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589747424,
      "name": "ip6_neigh_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:200",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_dst_neigh_lookup",
        "net/ipv6/route.c:ip6_dst_neigh_lookup",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589747424,
      "name": "ip6_neigh_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct in6_addr * gw</code>
</li>
<li>
<b>Param added. </b>
<code>struct net_device * dev</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct dst_entry * dst</code>
</li>
<li>
<b>Param reordered. </b>
<code>dst, skb, daddr</code> ➡️ <code>gw, dev, skb, daddr</code>
</li>
</ul>
</details>
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
