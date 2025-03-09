# Function: <code>ip6_route_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ip6_route_add(struct fib6_config * cfg)
```

```json
{
  "name": "ip6_route_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587067248,
      "name": "ip6_route_add",
      "external": true,
      "loc": "net/ipv6/route.c:1995",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_prefix_route",
        "net/ipv6/addrconf.c:addrconf_add_mroute",
        "net/ipv6/route.c:rt6_add_route_info",
        "net/ipv6/route.c:inet6_rtm_newroute",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:ipv6_route_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587067248,
      "name": "ip6_route_add",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int ip6_route_add(struct fib6_config * cfg)
```

```json
{
  "name": "ip6_route_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587519648,
      "name": "ip6_route_add",
      "external": true,
      "loc": "net/ipv6/route.c:2066",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_mroute",
        "net/ipv6/addrconf.c:addrconf_prefix_route",
        "net/ipv6/route.c:inet6_rtm_newroute",
        "net/ipv6/route.c:ipv6_route_ioctl",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_add_route_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587519648,
      "name": "ip6_route_add",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int ip6_route_add(struct fib6_config * cfg)
```

```json
{
  "name": "ip6_route_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587723776,
      "name": "ip6_route_add",
      "external": true,
      "loc": "net/ipv6/route.c:2087",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_mroute",
        "net/ipv6/addrconf.c:addrconf_prefix_route",
        "net/ipv6/route.c:inet6_rtm_newroute",
        "net/ipv6/route.c:ipv6_route_ioctl",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_add_route_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587723776,
      "name": "ip6_route_add",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int ip6_route_add(struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587875824,
      "name": "ip6_route_add",
      "external": true,
      "loc": "net/ipv6/route.c:2103",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_mroute",
        "net/ipv6/addrconf.c:addrconf_prefix_route",
        "net/ipv6/route.c:inet6_rtm_newroute",
        "net/ipv6/route.c:ipv6_route_ioctl",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_add_route_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587875824,
      "name": "ip6_route_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int ip6_route_add(struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588411744,
      "name": "ip6_route_add",
      "external": true,
      "loc": "net/ipv6/route.c:2800",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_mroute",
        "net/ipv6/addrconf.c:addrconf_prefix_route",
        "net/ipv6/route.c:inet6_rtm_newroute",
        "net/ipv6/route.c:ipv6_route_ioctl",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_add_route_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588411744,
      "name": "ip6_route_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int ip6_route_add(struct fib6_config * cfg, gfp_t gfp_flags, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588772912,
      "name": "ip6_route_add",
      "external": true,
      "loc": "net/ipv6/route.c:3154",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_mroute",
        "net/ipv6/route.c:inet6_rtm_newroute",
        "net/ipv6/route.c:ipv6_route_ioctl",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_add_route_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588772912,
      "name": "ip6_route_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int ip6_route_add(struct fib6_config * cfg, gfp_t gfp_flags, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588993056,
      "name": "ip6_route_add",
      "external": true,
      "loc": "net/ipv6/route.c:3134",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_mroute",
        "net/ipv6/route.c:inet6_rtm_newroute",
        "net/ipv6/route.c:ipv6_route_ioctl",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_add_route_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588993056,
      "name": "ip6_route_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int ip6_route_add(struct fib6_config * cfg, gfp_t gfp_flags, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589442960,
      "name": "ip6_route_add",
      "external": true,
      "loc": "net/ipv6/route.c:3691",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_mroute",
        "net/ipv6/route.c:inet6_rtm_newroute",
        "net/ipv6/route.c:ipv6_route_ioctl",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_add_route_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589442960,
      "name": "ip6_route_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int ip6_route_add(struct fib6_config * cfg, gfp_t gfp_flags, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589667344,
      "name": "ip6_route_add",
      "external": true,
      "loc": "net/ipv6/route.c:3704",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_mroute",
        "net/ipv6/route.c:inet6_rtm_newroute",
        "net/ipv6/route.c:ipv6_route_ioctl",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_add_route_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589667344,
      "name": "ip6_route_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int ip6_route_add(struct fib6_config * cfg, gfp_t gfp_flags, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590680816,
      "name": "ip6_route_add",
      "external": true,
      "loc": "net/ipv6/route.c:3733",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_mroute",
        "net/ipv6/addrconf.c:addrconf_prefix_route",
        "net/ipv6/route.c:inet6_rtm_newroute",
        "net/ipv6/route.c:ipv6_route_ioctl",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_add_route_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590680816,
      "name": "ip6_route_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
int ip6_route_add(struct fib6_config * cfg, gfp_t gfp_flags, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590741248,
      "name": "ip6_route_add",
      "external": true,
      "loc": "net/ipv6/route.c:3717",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_mroute",
        "net/ipv6/addrconf.c:addrconf_prefix_route",
        "net/ipv6/route.c:inet6_rtm_newroute",
        "net/ipv6/route.c:ipv6_route_ioctl",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_add_route_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590741248,
      "name": "ip6_route_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
int ip6_route_add(struct fib6_config * cfg, gfp_t gfp_flags, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590666784,
      "name": "ip6_route_add",
      "external": true,
      "loc": "net/ipv6/route.c:3731",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_mroute",
        "net/ipv6/addrconf.c:addrconf_prefix_route",
        "net/ipv6/route.c:inet6_rtm_newroute",
        "net/ipv6/route.c:ipv6_route_ioctl",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_add_route_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590666784,
      "name": "ip6_route_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
int ip6_route_add(struct fib6_config * cfg, gfp_t gfp_flags, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591482464,
      "name": "ip6_route_add",
      "external": true,
      "loc": "net/ipv6/route.c:3861",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_mroute",
        "net/ipv6/addrconf.c:addrconf_prefix_route",
        "net/ipv6/route.c:inet6_rtm_newroute",
        "net/ipv6/route.c:ipv6_route_ioctl",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_add_route_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591482464,
      "name": "ip6_route_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
int ip6_route_add(struct fib6_config * cfg, gfp_t gfp_flags, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593165808,
      "name": "ip6_route_add",
      "external": true,
      "loc": "net/ipv6/route.c:3837",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_mroute",
        "net/ipv6/addrconf.c:addrconf_prefix_route",
        "net/ipv6/route.c:inet6_rtm_newroute",
        "net/ipv6/route.c:ipv6_route_ioctl",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_add_route_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593165808,
      "name": "ip6_route_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
int ip6_route_add(struct fib6_config * cfg, gfp_t gfp_flags, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595063952,
      "name": "ip6_route_add",
      "external": true,
      "loc": "net/ipv6/route.c:3837",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_mroute",
        "net/ipv6/addrconf.c:addrconf_prefix_route",
        "net/ipv6/route.c:inet6_rtm_newroute",
        "net/ipv6/route.c:ipv6_route_ioctl",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_add_route_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595063952,
      "name": "ip6_route_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
int ip6_route_add(struct fib6_config * cfg, gfp_t gfp_flags, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595457552,
      "name": "ip6_route_add",
      "external": true,
      "loc": "net/ipv6/route.c:3835",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_mroute",
        "net/ipv6/addrconf.c:addrconf_prefix_route",
        "net/ipv6/route.c:inet6_rtm_newroute",
        "net/ipv6/route.c:ipv6_route_ioctl",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_add_route_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595457552,
      "name": "ip6_route_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
int ip6_route_add(struct fib6_config * cfg, gfp_t gfp_flags, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596299664,
      "name": "ip6_route_add",
      "external": true,
      "loc": "net/ipv6/route.c:3837",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_mroute",
        "net/ipv6/addrconf.c:addrconf_prefix_route",
        "net/ipv6/route.c:inet6_rtm_newroute",
        "net/ipv6/route.c:ipv6_route_ioctl",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_add_route_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596299664,
      "name": "ip6_route_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
int ip6_route_add(struct fib6_config * cfg, gfp_t gfp_flags, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503353728,
      "name": "ip6_route_add",
      "external": true,
      "loc": "net/ipv6/route.c:3704",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_mroute",
        "net/ipv6/route.c:inet6_rtm_newroute",
        "net/ipv6/route.c:ipv6_route_ioctl",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_add_route_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503353728,
      "name": "ip6_route_add",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int ip6_route_add(struct fib6_config * cfg, gfp_t gfp_flags, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236019852,
      "name": "ip6_route_add",
      "external": true,
      "loc": "net/ipv6/route.c:3704",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_mroute",
        "net/ipv6/addrconf.c:addrconf_prefix_route",
        "net/ipv6/route.c:inet6_rtm_newroute",
        "net/ipv6/route.c:ipv6_route_ioctl",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_add_route_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236019852,
      "name": "ip6_route_add",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int ip6_route_add(struct fib6_config * cfg, gfp_t gfp_flags, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297119936,
      "name": "ip6_route_add",
      "external": true,
      "loc": "net/ipv6/route.c:3704",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_mroute",
        "net/ipv6/route.c:inet6_rtm_newroute",
        "net/ipv6/route.c:ipv6_route_ioctl",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_add_route_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297119936,
      "name": "ip6_route_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int ip6_route_add(struct fib6_config * cfg, gfp_t gfp_flags, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279361156,
      "name": "ip6_route_add",
      "external": true,
      "loc": "net/ipv6/route.c:3704",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_mroute",
        "net/ipv6/addrconf.c:addrconf_prefix_route",
        "net/ipv6/route.c:inet6_rtm_newroute",
        "net/ipv6/route.c:ipv6_route_ioctl",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_add_route_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279361156,
      "name": "ip6_route_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int ip6_route_add(struct fib6_config * cfg, gfp_t gfp_flags, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589271712,
      "name": "ip6_route_add",
      "external": true,
      "loc": "net/ipv6/route.c:3704",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_mroute",
        "net/ipv6/route.c:inet6_rtm_newroute",
        "net/ipv6/route.c:ipv6_route_ioctl",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_add_route_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589271712,
      "name": "ip6_route_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int ip6_route_add(struct fib6_config * cfg, gfp_t gfp_flags, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588996704,
      "name": "ip6_route_add",
      "external": true,
      "loc": "net/ipv6/route.c:3704",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_mroute",
        "net/ipv6/route.c:inet6_rtm_newroute",
        "net/ipv6/route.c:ipv6_route_ioctl",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_add_route_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588996704,
      "name": "ip6_route_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int ip6_route_add(struct fib6_config * cfg, gfp_t gfp_flags, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589708576,
      "name": "ip6_route_add",
      "external": true,
      "loc": "net/ipv6/route.c:3704",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_mroute",
        "net/ipv6/route.c:inet6_rtm_newroute",
        "net/ipv6/route.c:ipv6_route_ioctl",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_add_route_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589708576,
      "name": "ip6_route_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int ip6_route_add(struct fib6_config * cfg, gfp_t gfp_flags, struct netlink_ext_ack * extack)
```

```json
{
  "name": "ip6_route_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589758624,
      "name": "ip6_route_add",
      "external": true,
      "loc": "net/ipv6/route.c:3704",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_add_mroute",
        "net/ipv6/route.c:inet6_rtm_newroute",
        "net/ipv6/route.c:ipv6_route_ioctl",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_add_route_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589758624,
      "name": "ip6_route_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
</ul>
</details>
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
<code>gfp_t gfp_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>cfg, extack</code> ➡️ <code>cfg, gfp_flags, extack</code>
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
