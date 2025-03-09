# Function: <code>addrconf_prefix_route</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void addrconf_prefix_route(struct in6_addr * pfx, int plen, struct net_device * dev, long unsigned int expires, u32 flags)
```

```json
{
  "name": "addrconf_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587011024,
      "name": "addrconf_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:2153",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587011024,
      "name": "addrconf_prefix_route",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
void addrconf_prefix_route(struct in6_addr * pfx, int plen, struct net_device * dev, long unsigned int expires, u32 flags)
```

```json
{
  "name": "addrconf_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587457648,
      "name": "addrconf_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:2203",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587457648,
      "name": "addrconf_prefix_route",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
void addrconf_prefix_route(struct in6_addr * pfx, int plen, struct net_device * dev, long unsigned int expires, u32 flags)
```

```json
{
  "name": "addrconf_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587661360,
      "name": "addrconf_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:2218",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587661360,
      "name": "addrconf_prefix_route",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
void addrconf_prefix_route(struct in6_addr * pfx, int plen, struct net_device * dev, long unsigned int expires, u32 flags)
```

```json
{
  "name": "addrconf_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587810480,
      "name": "addrconf_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:2273",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587810480,
      "name": "addrconf_prefix_route",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
void addrconf_prefix_route(struct in6_addr * pfx, int plen, struct net_device * dev, long unsigned int expires, u32 flags)
```

```json
{
  "name": "addrconf_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588339776,
      "name": "addrconf_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:2297",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588339776,
      "name": "addrconf_prefix_route",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "addrconf_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588698448,
      "name": "addrconf_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:2320",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588698448,
      "name": "addrconf_prefix_route.isra.52",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "addrconf_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588917024,
      "name": "addrconf_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:2336",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588917024,
      "name": "addrconf_prefix_route.isra.54",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "addrconf_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589359200,
      "name": "addrconf_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:2369",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589359200,
      "name": "addrconf_prefix_route.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "addrconf_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589583312,
      "name": "addrconf_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:2371",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:modify_prefix_route",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589583312,
      "name": "addrconf_prefix_route.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
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
void addrconf_prefix_route(struct in6_addr * pfx, int plen, u32 metric, struct net_device * dev, long unsigned int expires, u32 flags, gfp_t gfp_flags)
```

```json
{
  "name": "addrconf_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590585920,
      "name": "addrconf_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:2360",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:modify_prefix_route",
        "net/ipv6/addrconf.c:fixup_permanent_addr",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:sit_add_v4_addrs",
        "net/ipv6/addrconf.c:sit_add_v4_addrs",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590585920,
      "name": "addrconf_prefix_route",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
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
void addrconf_prefix_route(struct in6_addr * pfx, int plen, u32 metric, struct net_device * dev, long unsigned int expires, u32 flags, gfp_t gfp_flags)
```

```json
{
  "name": "addrconf_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590651648,
      "name": "addrconf_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:2386",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:modify_prefix_route",
        "net/ipv6/addrconf.c:fixup_permanent_addr",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:sit_add_v4_addrs",
        "net/ipv6/addrconf.c:sit_add_v4_addrs",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590651648,
      "name": "addrconf_prefix_route",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
void addrconf_prefix_route(struct in6_addr * pfx, int plen, u32 metric, struct net_device * dev, long unsigned int expires, u32 flags, gfp_t gfp_flags)
```

```json
{
  "name": "addrconf_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590577744,
      "name": "addrconf_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:2388",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:modify_prefix_route",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:sit_add_v4_addrs",
        "net/ipv6/addrconf.c:sit_add_v4_addrs",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590577744,
      "name": "addrconf_prefix_route",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
void addrconf_prefix_route(struct in6_addr * pfx, int plen, u32 metric, struct net_device * dev, long unsigned int expires, u32 flags, gfp_t gfp_flags)
```

```json
{
  "name": "addrconf_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591389984,
      "name": "addrconf_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:2395",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:modify_prefix_route",
        "net/ipv6/addrconf.c:addrconf_permanent_addr",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_v4_addrs",
        "net/ipv6/addrconf.c:add_v4_addrs",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591389984,
      "name": "addrconf_prefix_route",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
void addrconf_prefix_route(struct in6_addr * pfx, int plen, u32 metric, struct net_device * dev, long unsigned int expires, u32 flags, gfp_t gfp_flags)
```

```json
{
  "name": "addrconf_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593065968,
      "name": "addrconf_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:2398",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:modify_prefix_route",
        "net/ipv6/addrconf.c:addrconf_permanent_addr",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_v4_addrs",
        "net/ipv6/addrconf.c:add_v4_addrs",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593065968,
      "name": "addrconf_prefix_route",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
void addrconf_prefix_route(struct in6_addr * pfx, int plen, u32 metric, struct net_device * dev, long unsigned int expires, u32 flags, gfp_t gfp_flags)
```

```json
{
  "name": "addrconf_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594959056,
      "name": "addrconf_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:2398",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:modify_prefix_route",
        "net/ipv6/addrconf.c:addrconf_permanent_addr",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_v4_addrs",
        "net/ipv6/addrconf.c:add_v4_addrs",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594959056,
      "name": "addrconf_prefix_route",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
void addrconf_prefix_route(struct in6_addr * pfx, int plen, u32 metric, struct net_device * dev, long unsigned int expires, u32 flags, gfp_t gfp_flags)
```

```json
{
  "name": "addrconf_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595351504,
      "name": "addrconf_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:2397",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:modify_prefix_route",
        "net/ipv6/addrconf.c:addrconf_permanent_addr",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_v4_addrs",
        "net/ipv6/addrconf.c:add_v4_addrs",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595351504,
      "name": "addrconf_prefix_route",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
void addrconf_prefix_route(struct in6_addr * pfx, int plen, u32 metric, struct net_device * dev, long unsigned int expires, u32 flags, gfp_t gfp_flags)
```

```json
{
  "name": "addrconf_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596192288,
      "name": "addrconf_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:2425",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:modify_prefix_route",
        "net/ipv6/addrconf.c:addrconf_permanent_addr",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:add_v4_addrs",
        "net/ipv6/addrconf.c:add_v4_addrs",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596192288,
      "name": "addrconf_prefix_route",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "addrconf_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503258552,
      "name": "addrconf_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:2371",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:modify_prefix_route",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503258552,
      "name": "addrconf_prefix_route.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
void addrconf_prefix_route(struct in6_addr * pfx, int plen, u32 metric, struct net_device * dev, long unsigned int expires, u32 flags, gfp_t gfp_flags)
```

```json
{
  "name": "addrconf_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235931512,
      "name": "addrconf_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:2371",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:modify_prefix_route",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235931512,
      "name": "addrconf_prefix_route",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "addrconf_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297006512,
      "name": "addrconf_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:2371",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:modify_prefix_route",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297006512,
      "name": "addrconf_prefix_route.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
void addrconf_prefix_route(struct in6_addr * pfx, int plen, u32 metric, struct net_device * dev, long unsigned int expires, u32 flags, gfp_t gfp_flags)
```

```json
{
  "name": "addrconf_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279284886,
      "name": "addrconf_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:2371",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:modify_prefix_route",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279284886,
      "name": "addrconf_prefix_route",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "addrconf_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589187680,
      "name": "addrconf_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:2371",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:modify_prefix_route",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589187680,
      "name": "addrconf_prefix_route.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "addrconf_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588912672,
      "name": "addrconf_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:2371",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:modify_prefix_route",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588912672,
      "name": "addrconf_prefix_route.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "addrconf_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589624544,
      "name": "addrconf_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:2371",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:modify_prefix_route",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589624544,
      "name": "addrconf_prefix_route.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "addrconf_prefix_route",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589673456,
      "name": "addrconf_prefix_route",
      "external": false,
      "loc": "net/ipv6/addrconf.c:2371",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:modify_prefix_route",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_notify",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589673456,
      "name": "addrconf_prefix_route.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void addrconf_prefix_route(struct in6_addr * pfx, int plen, struct net_device * dev, long unsigned int expires, u32 flags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void addrconf_prefix_route(struct in6_addr * pfx, int plen, u32 metric, struct net_device * dev, long unsigned int expires, u32 flags, gfp_t gfp_flags)
```
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void addrconf_prefix_route(struct in6_addr * pfx, int plen, u32 metric, struct net_device * dev, long unsigned int expires, u32 flags, gfp_t gfp_flags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void addrconf_prefix_route(struct in6_addr * pfx, int plen, u32 metric, struct net_device * dev, long unsigned int expires, u32 flags, gfp_t gfp_flags)
```
</details>
</li>
</ul>
