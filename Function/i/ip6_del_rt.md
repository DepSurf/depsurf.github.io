# Function: <code>ip6_del_rt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ip6_del_rt(struct rt6_info * rt)
```

```json
{
  "name": "ip6_del_rt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587067840,
      "name": "ip6_del_rt",
      "external": true,
      "loc": "net/ipv6/route.c:2046",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:__ipv6_dev_ac_dec",
        "net/ipv6/anycast.c:ipv6_ac_destroy_dev",
        "net/ipv6/addrconf.c:cleanup_prefix_route",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_link_failure",
        "net/ipv6/route.c:ip6_negative_advice",
        "net/ipv6/route.c:rt6_route_rcv",
        "net/ipv6/route.c:rt6_purge_dflt_routers",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587067840,
      "name": "ip6_del_rt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int ip6_del_rt(struct rt6_info * rt)
```

```json
{
  "name": "ip6_del_rt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587520240,
      "name": "ip6_del_rt",
      "external": true,
      "loc": "net/ipv6/route.c:2117",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_ac_destroy_dev",
        "net/ipv6/anycast.c:__ipv6_dev_ac_dec",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:cleanup_prefix_route",
        "net/ipv6/route.c:rt6_purge_dflt_routers",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_link_failure",
        "net/ipv6/route.c:ip6_negative_advice",
        "net/ipv6/route.c:rt6_route_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587520240,
      "name": "ip6_del_rt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int ip6_del_rt(struct rt6_info * rt)
```

```json
{
  "name": "ip6_del_rt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587724368,
      "name": "ip6_del_rt",
      "external": true,
      "loc": "net/ipv6/route.c:2138",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_ac_destroy_dev",
        "net/ipv6/anycast.c:__ipv6_dev_ac_dec",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:cleanup_prefix_route",
        "net/ipv6/route.c:rt6_purge_dflt_routers",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_link_failure",
        "net/ipv6/route.c:ip6_negative_advice",
        "net/ipv6/route.c:rt6_route_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587724368,
      "name": "ip6_del_rt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int ip6_del_rt(struct rt6_info * rt)
```

```json
{
  "name": "ip6_del_rt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587876320,
      "name": "ip6_del_rt",
      "external": true,
      "loc": "net/ipv6/route.c:2154",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_ac_destroy_dev",
        "net/ipv6/anycast.c:__ipv6_dev_ac_dec",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:cleanup_prefix_route",
        "net/ipv6/route.c:rt6_purge_dflt_routers",
        "net/ipv6/route.c:rt6_do_redirect",
        "net/ipv6/route.c:ip6_link_failure",
        "net/ipv6/route.c:rt6_route_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587876320,
      "name": "ip6_del_rt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int ip6_del_rt(struct rt6_info * rt)
```

```json
{
  "name": "ip6_del_rt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588412224,
      "name": "ip6_del_rt",
      "external": true,
      "loc": "net/ipv6/route.c:2851",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_ac_destroy_dev",
        "net/ipv6/anycast.c:__ipv6_dev_ac_dec",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:cleanup_prefix_route",
        "net/ipv6/route.c:rt6_purge_dflt_routers",
        "net/ipv6/route.c:ip6_link_failure",
        "net/ipv6/route.c:rt6_route_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588412224,
      "name": "ip6_del_rt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ip6_del_rt(struct net * net, struct fib6_info * rt)
```

```json
{
  "name": "ip6_del_rt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588774855,
      "name": "ip6_del_rt",
      "external": true,
      "loc": "net/ipv6/route.c:3191",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_purge_dflt_routers",
        "net/ipv6/route.c:rt6_route_rcv"
      ],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_ac_destroy_dev",
        "net/ipv6/anycast.c:__ipv6_dev_ac_dec",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:cleanup_prefix_route",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588773328,
      "name": "ip6_del_rt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int ip6_del_rt(struct net * net, struct fib6_info * rt)
```

```json
{
  "name": "ip6_del_rt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588994999,
      "name": "ip6_del_rt",
      "external": true,
      "loc": "net/ipv6/route.c:3171",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_purge_dflt_routers",
        "net/ipv6/route.c:rt6_route_rcv"
      ],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_ac_destroy_dev",
        "net/ipv6/anycast.c:__ipv6_dev_ac_dec",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:cleanup_prefix_route",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588993472,
      "name": "ip6_del_rt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int ip6_del_rt(struct net * net, struct fib6_info * rt)
```

```json
{
  "name": "ip6_del_rt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589444984,
      "name": "ip6_del_rt",
      "external": true,
      "loc": "net/ipv6/route.c:3728",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_purge_dflt_routers",
        "net/ipv6/route.c:rt6_route_rcv"
      ],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_ac_destroy_dev",
        "net/ipv6/anycast.c:__ipv6_dev_ac_dec",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:cleanup_prefix_route",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589443376,
      "name": "ip6_del_rt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int ip6_del_rt(struct net * net, struct fib6_info * rt)
```

```json
{
  "name": "ip6_del_rt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589669368,
      "name": "ip6_del_rt",
      "external": true,
      "loc": "net/ipv6/route.c:3741",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_purge_dflt_routers",
        "net/ipv6/route.c:rt6_route_rcv"
      ],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_ac_destroy_dev",
        "net/ipv6/anycast.c:__ipv6_dev_ac_dec",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:modify_prefix_route",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:cleanup_prefix_route",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589667760,
      "name": "ip6_del_rt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int ip6_del_rt(struct net * net, struct fib6_info * rt, bool skip_notify)
```

```json
{
  "name": "ip6_del_rt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590681312,
      "name": "ip6_del_rt",
      "external": true,
      "loc": "net/ipv6/route.c:3770",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_ac_destroy_dev",
        "net/ipv6/anycast.c:__ipv6_dev_ac_dec",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:modify_prefix_route",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:cleanup_prefix_route",
        "net/ipv6/route.c:__rt6_purge_dflt_routers",
        "net/ipv6/route.c:rt6_route_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590681312,
      "name": "ip6_del_rt",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int ip6_del_rt(struct net * net, struct fib6_info * rt, bool skip_notify)
```

```json
{
  "name": "ip6_del_rt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590741760,
      "name": "ip6_del_rt",
      "external": true,
      "loc": "net/ipv6/route.c:3754",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_ac_destroy_dev",
        "net/ipv6/anycast.c:__ipv6_dev_ac_dec",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:modify_prefix_route",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:cleanup_prefix_route",
        "net/ipv6/route.c:__rt6_purge_dflt_routers",
        "net/ipv6/route.c:rt6_route_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590741760,
      "name": "ip6_del_rt",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ip6_del_rt(struct net * net, struct fib6_info * rt, bool skip_notify)
```

```json
{
  "name": "ip6_del_rt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590669191,
      "name": "ip6_del_rt",
      "external": true,
      "loc": "net/ipv6/route.c:3768",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_purge_dflt_routers"
      ],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_ac_destroy_dev",
        "net/ipv6/anycast.c:__ipv6_dev_ac_dec",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:modify_prefix_route",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:cleanup_prefix_route",
        "net/ipv6/route.c:rt6_route_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590667296,
      "name": "ip6_del_rt",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ip6_del_rt(struct net * net, struct fib6_info * rt, bool skip_notify)
```

```json
{
  "name": "ip6_del_rt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591484888,
      "name": "ip6_del_rt",
      "external": true,
      "loc": "net/ipv6/route.c:3898",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_purge_dflt_routers"
      ],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_ac_destroy_dev",
        "net/ipv6/anycast.c:__ipv6_dev_ac_dec",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:modify_prefix_route",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:cleanup_prefix_route",
        "net/ipv6/route.c:rt6_route_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591482976,
      "name": "ip6_del_rt",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ip6_del_rt(struct net * net, struct fib6_info * rt, bool skip_notify)
```

```json
{
  "name": "ip6_del_rt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593168357,
      "name": "ip6_del_rt",
      "external": true,
      "loc": "net/ipv6/route.c:3874",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_purge_dflt_routers"
      ],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_ac_destroy_dev",
        "net/ipv6/anycast.c:__ipv6_dev_ac_dec",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:modify_prefix_route",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:cleanup_prefix_route",
        "net/ipv6/route.c:rt6_route_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593166384,
      "name": "ip6_del_rt",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ip6_del_rt(struct net * net, struct fib6_info * rt, bool skip_notify)
```

```json
{
  "name": "ip6_del_rt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595066597,
      "name": "ip6_del_rt",
      "external": true,
      "loc": "net/ipv6/route.c:3874",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_purge_dflt_routers"
      ],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_ac_destroy_dev",
        "net/ipv6/anycast.c:__ipv6_dev_ac_dec",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:modify_prefix_route",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:cleanup_prefix_route",
        "net/ipv6/route.c:rt6_route_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595064560,
      "name": "ip6_del_rt",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ip6_del_rt(struct net * net, struct fib6_info * rt, bool skip_notify)
```

```json
{
  "name": "ip6_del_rt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595460317,
      "name": "ip6_del_rt",
      "external": true,
      "loc": "net/ipv6/route.c:3872",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_purge_dflt_routers"
      ],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_ac_destroy_dev",
        "net/ipv6/anycast.c:__ipv6_dev_ac_dec",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:modify_prefix_route",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:cleanup_prefix_route",
        "net/ipv6/route.c:rt6_route_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595458160,
      "name": "ip6_del_rt",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ip6_del_rt(struct net * net, struct fib6_info * rt, bool skip_notify)
```

```json
{
  "name": "ip6_del_rt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596302429,
      "name": "ip6_del_rt",
      "external": true,
      "loc": "net/ipv6/route.c:3874",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_purge_dflt_routers"
      ],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_ac_destroy_dev",
        "net/ipv6/anycast.c:__ipv6_dev_ac_dec",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:modify_prefix_route",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:cleanup_prefix_route",
        "net/ipv6/route.c:rt6_route_rcv",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596300272,
      "name": "ip6_del_rt",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int ip6_del_rt(struct net * net, struct fib6_info * rt)
```

```json
{
  "name": "ip6_del_rt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503355720,
      "name": "ip6_del_rt",
      "external": true,
      "loc": "net/ipv6/route.c:3741",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_purge_dflt_routers",
        "net/ipv6/route.c:rt6_route_rcv"
      ],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_ac_destroy_dev",
        "net/ipv6/anycast.c:__ipv6_dev_ac_dec",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:modify_prefix_route",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:cleanup_prefix_route",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503354224,
      "name": "ip6_del_rt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int ip6_del_rt(struct net * net, struct fib6_info * rt)
```

```json
{
  "name": "ip6_del_rt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236021852,
      "name": "ip6_del_rt",
      "external": true,
      "loc": "net/ipv6/route.c:3741",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_purge_dflt_routers",
        "net/ipv6/route.c:rt6_route_rcv"
      ],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_ac_destroy_dev",
        "net/ipv6/anycast.c:__ipv6_dev_ac_dec",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:modify_prefix_route",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:cleanup_prefix_route",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236020252,
      "name": "ip6_del_rt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int ip6_del_rt(struct net * net, struct fib6_info * rt)
```

```json
{
  "name": "ip6_del_rt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297122832,
      "name": "ip6_del_rt",
      "external": true,
      "loc": "net/ipv6/route.c:3741",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_purge_dflt_routers",
        "net/ipv6/route.c:rt6_route_rcv"
      ],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_ac_destroy_dev",
        "net/ipv6/anycast.c:__ipv6_dev_ac_dec",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:modify_prefix_route",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:cleanup_prefix_route",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297120576,
      "name": "ip6_del_rt",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int ip6_del_rt(struct net * net, struct fib6_info * rt)
```

```json
{
  "name": "ip6_del_rt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279362922,
      "name": "ip6_del_rt",
      "external": true,
      "loc": "net/ipv6/route.c:3741",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_purge_dflt_routers",
        "net/ipv6/route.c:rt6_route_rcv"
      ],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_ac_destroy_dev",
        "net/ipv6/anycast.c:__ipv6_dev_ac_dec",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:modify_prefix_route",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:cleanup_prefix_route",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279361590,
      "name": "ip6_del_rt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int ip6_del_rt(struct net * net, struct fib6_info * rt)
```

```json
{
  "name": "ip6_del_rt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589273736,
      "name": "ip6_del_rt",
      "external": true,
      "loc": "net/ipv6/route.c:3741",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_purge_dflt_routers",
        "net/ipv6/route.c:rt6_route_rcv"
      ],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_ac_destroy_dev",
        "net/ipv6/anycast.c:__ipv6_dev_ac_dec",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:modify_prefix_route",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:cleanup_prefix_route",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589272128,
      "name": "ip6_del_rt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int ip6_del_rt(struct net * net, struct fib6_info * rt)
```

```json
{
  "name": "ip6_del_rt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588998728,
      "name": "ip6_del_rt",
      "external": true,
      "loc": "net/ipv6/route.c:3741",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_purge_dflt_routers",
        "net/ipv6/route.c:rt6_route_rcv"
      ],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_ac_destroy_dev",
        "net/ipv6/anycast.c:__ipv6_dev_ac_dec",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:modify_prefix_route",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:cleanup_prefix_route",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588997120,
      "name": "ip6_del_rt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int ip6_del_rt(struct net * net, struct fib6_info * rt)
```

```json
{
  "name": "ip6_del_rt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589710600,
      "name": "ip6_del_rt",
      "external": true,
      "loc": "net/ipv6/route.c:3741",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_purge_dflt_routers",
        "net/ipv6/route.c:rt6_route_rcv"
      ],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_ac_destroy_dev",
        "net/ipv6/anycast.c:__ipv6_dev_ac_dec",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:modify_prefix_route",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:cleanup_prefix_route",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589708992,
      "name": "ip6_del_rt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int ip6_del_rt(struct net * net, struct fib6_info * rt)
```

```json
{
  "name": "ip6_del_rt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589760751,
      "name": "ip6_del_rt",
      "external": true,
      "loc": "net/ipv6/route.c:3741",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_purge_dflt_routers",
        "net/ipv6/route.c:rt6_route_rcv"
      ],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_ac_destroy_dev",
        "net/ipv6/anycast.c:__ipv6_dev_ac_dec",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:__ipv6_ifa_notify",
        "net/ipv6/addrconf.c:modify_prefix_route",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:cleanup_prefix_route",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589759072,
      "name": "ip6_del_rt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
<code>rt</code> ➡️ <code>net, rt</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct rt6_info * rt</code> ➡️ <code>struct fib6_info * rt</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool skip_notify</code>
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
