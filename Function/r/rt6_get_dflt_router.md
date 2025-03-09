# Function: <code>rt6_get_dflt_router</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct rt6_info * rt6_get_dflt_router(const struct in6_addr * addr, struct net_device * dev)
```

```json
{
  "name": "rt6_get_dflt_router",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587069360,
      "name": "rt6_get_dflt_router",
      "external": true,
      "loc": "net/ipv6/route.c:2311",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_route_rcv",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587069360,
      "name": "rt6_get_dflt_router",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct rt6_info * rt6_get_dflt_router(const struct in6_addr * addr, struct net_device * dev)
```

```json
{
  "name": "rt6_get_dflt_router",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587522064,
      "name": "rt6_get_dflt_router",
      "external": true,
      "loc": "net/ipv6/route.c:2382",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_route_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587522064,
      "name": "rt6_get_dflt_router",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct rt6_info * rt6_get_dflt_router(const struct in6_addr * addr, struct net_device * dev)
```

```json
{
  "name": "rt6_get_dflt_router",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587726224,
      "name": "rt6_get_dflt_router",
      "external": true,
      "loc": "net/ipv6/route.c:2409",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_route_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587726224,
      "name": "rt6_get_dflt_router",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct rt6_info * rt6_get_dflt_router(const struct in6_addr * addr, struct net_device * dev)
```

```json
{
  "name": "rt6_get_dflt_router",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587878336,
      "name": "rt6_get_dflt_router",
      "external": true,
      "loc": "net/ipv6/route.c:2492",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_route_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587878336,
      "name": "rt6_get_dflt_router",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
struct rt6_info * rt6_get_dflt_router(const struct in6_addr * addr, struct net_device * dev)
```

```json
{
  "name": "rt6_get_dflt_router",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588412528,
      "name": "rt6_get_dflt_router",
      "external": true,
      "loc": "net/ipv6/route.c:3190",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_route_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588412528,
      "name": "rt6_get_dflt_router",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
struct fib6_info * rt6_get_dflt_router(struct net * net, const struct in6_addr * addr, struct net_device * dev)
```

```json
{
  "name": "rt6_get_dflt_router",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588773424,
      "name": "rt6_get_dflt_router",
      "external": true,
      "loc": "net/ipv6/route.c:3528",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_route_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588773424,
      "name": "rt6_get_dflt_router",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
struct fib6_info * rt6_get_dflt_router(struct net * net, const struct in6_addr * addr, struct net_device * dev)
```

```json
{
  "name": "rt6_get_dflt_router",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588993568,
      "name": "rt6_get_dflt_router",
      "external": true,
      "loc": "net/ipv6/route.c:3508",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_route_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588993568,
      "name": "rt6_get_dflt_router",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
struct fib6_info * rt6_get_dflt_router(struct net * net, const struct in6_addr * addr, struct net_device * dev)
```

```json
{
  "name": "rt6_get_dflt_router",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589443472,
      "name": "rt6_get_dflt_router",
      "external": true,
      "loc": "net/ipv6/route.c:4152",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_route_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589443472,
      "name": "rt6_get_dflt_router",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
struct fib6_info * rt6_get_dflt_router(struct net * net, const struct in6_addr * addr, struct net_device * dev)
```

```json
{
  "name": "rt6_get_dflt_router",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589667856,
      "name": "rt6_get_dflt_router",
      "external": true,
      "loc": "net/ipv6/route.c:4165",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_route_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589667856,
      "name": "rt6_get_dflt_router",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
struct fib6_info * rt6_get_dflt_router(struct net * net, const struct in6_addr * addr, struct net_device * dev)
```

```json
{
  "name": "rt6_get_dflt_router",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590681824,
      "name": "rt6_get_dflt_router",
      "external": true,
      "loc": "net/ipv6/route.c:4218",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_route_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590681824,
      "name": "rt6_get_dflt_router",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
struct fib6_info * rt6_get_dflt_router(struct net * net, const struct in6_addr * addr, struct net_device * dev)
```

```json
{
  "name": "rt6_get_dflt_router",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590742288,
      "name": "rt6_get_dflt_router",
      "external": true,
      "loc": "net/ipv6/route.c:4202",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_route_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590742288,
      "name": "rt6_get_dflt_router",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
struct fib6_info * rt6_get_dflt_router(struct net * net, const struct in6_addr * addr, struct net_device * dev)
```

```json
{
  "name": "rt6_get_dflt_router",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590667520,
      "name": "rt6_get_dflt_router",
      "external": true,
      "loc": "net/ipv6/route.c:4216",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_route_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590667520,
      "name": "rt6_get_dflt_router",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
struct fib6_info * rt6_get_dflt_router(struct net * net, const struct in6_addr * addr, struct net_device * dev)
```

```json
{
  "name": "rt6_get_dflt_router",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591483200,
      "name": "rt6_get_dflt_router",
      "external": true,
      "loc": "net/ipv6/route.c:4346",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_route_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591483200,
      "name": "rt6_get_dflt_router",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
struct fib6_info * rt6_get_dflt_router(struct net * net, const struct in6_addr * addr, struct net_device * dev)
```

```json
{
  "name": "rt6_get_dflt_router",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593166624,
      "name": "rt6_get_dflt_router",
      "external": true,
      "loc": "net/ipv6/route.c:4322",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_route_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593166624,
      "name": "rt6_get_dflt_router",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
struct fib6_info * rt6_get_dflt_router(struct net * net, const struct in6_addr * addr, struct net_device * dev)
```

```json
{
  "name": "rt6_get_dflt_router",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595064816,
      "name": "rt6_get_dflt_router",
      "external": true,
      "loc": "net/ipv6/route.c:4322",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_route_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595064816,
      "name": "rt6_get_dflt_router",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
struct fib6_info * rt6_get_dflt_router(struct net * net, const struct in6_addr * addr, struct net_device * dev)
```

```json
{
  "name": "rt6_get_dflt_router",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595458416,
      "name": "rt6_get_dflt_router",
      "external": true,
      "loc": "net/ipv6/route.c:4320",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_route_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595458416,
      "name": "rt6_get_dflt_router",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
struct fib6_info * rt6_get_dflt_router(struct net * net, const struct in6_addr * addr, struct net_device * dev)
```

```json
{
  "name": "rt6_get_dflt_router",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596300528,
      "name": "rt6_get_dflt_router",
      "external": true,
      "loc": "net/ipv6/route.c:4322",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_route_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596300528,
      "name": "rt6_get_dflt_router",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
struct fib6_info * rt6_get_dflt_router(struct net * net, const struct in6_addr * addr, struct net_device * dev)
```

```json
{
  "name": "rt6_get_dflt_router",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503354328,
      "name": "rt6_get_dflt_router",
      "external": true,
      "loc": "net/ipv6/route.c:4165",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_route_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503354328,
      "name": "rt6_get_dflt_router",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
struct fib6_info * rt6_get_dflt_router(struct net * net, const struct in6_addr * addr, struct net_device * dev)
```

```json
{
  "name": "rt6_get_dflt_router",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236020368,
      "name": "rt6_get_dflt_router",
      "external": true,
      "loc": "net/ipv6/route.c:4165",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_route_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236020368,
      "name": "rt6_get_dflt_router",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
struct fib6_info * rt6_get_dflt_router(struct net * net, const struct in6_addr * addr, struct net_device * dev)
```

```json
{
  "name": "rt6_get_dflt_router",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297120704,
      "name": "rt6_get_dflt_router",
      "external": true,
      "loc": "net/ipv6/route.c:4165",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_route_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297120704,
      "name": "rt6_get_dflt_router",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
struct fib6_info * rt6_get_dflt_router(struct net * net, const struct in6_addr * addr, struct net_device * dev)
```

```json
{
  "name": "rt6_get_dflt_router",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279361654,
      "name": "rt6_get_dflt_router",
      "external": true,
      "loc": "net/ipv6/route.c:4165",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_route_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279361654,
      "name": "rt6_get_dflt_router",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
struct fib6_info * rt6_get_dflt_router(struct net * net, const struct in6_addr * addr, struct net_device * dev)
```

```json
{
  "name": "rt6_get_dflt_router",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589272224,
      "name": "rt6_get_dflt_router",
      "external": true,
      "loc": "net/ipv6/route.c:4165",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_route_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589272224,
      "name": "rt6_get_dflt_router",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
struct fib6_info * rt6_get_dflt_router(struct net * net, const struct in6_addr * addr, struct net_device * dev)
```

```json
{
  "name": "rt6_get_dflt_router",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588997216,
      "name": "rt6_get_dflt_router",
      "external": true,
      "loc": "net/ipv6/route.c:4165",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_route_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588997216,
      "name": "rt6_get_dflt_router",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
struct fib6_info * rt6_get_dflt_router(struct net * net, const struct in6_addr * addr, struct net_device * dev)
```

```json
{
  "name": "rt6_get_dflt_router",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589709088,
      "name": "rt6_get_dflt_router",
      "external": true,
      "loc": "net/ipv6/route.c:4165",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_route_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589709088,
      "name": "rt6_get_dflt_router",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
struct fib6_info * rt6_get_dflt_router(struct net * net, const struct in6_addr * addr, struct net_device * dev)
```

```json
{
  "name": "rt6_get_dflt_router",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589759168,
      "name": "rt6_get_dflt_router",
      "external": true,
      "loc": "net/ipv6/route.c:4165",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_route_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589759168,
      "name": "rt6_get_dflt_router",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
<code>struct net * net</code>
</li>
<li>
<b>Param reordered. </b>
<code>addr, dev</code> ➡️ <code>net, addr, dev</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct rt6_info *</code> ➡️ <code>struct fib6_info *</code>
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
