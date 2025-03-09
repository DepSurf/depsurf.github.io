# Function: <code>inet6_rt_notify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void inet6_rt_notify(int event, struct rt6_info * rt, struct nl_info * info, unsigned int nlm_flags)
```

```json
{
  "name": "inet6_rt_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587074512,
      "name": "inet6_rt_notify",
      "external": true,
      "loc": "net/ipv6/route.c:3318",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ip6_fib.c:fib6_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587074512,
      "name": "inet6_rt_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
void inet6_rt_notify(int event, struct rt6_info * rt, struct nl_info * info, unsigned int nlm_flags)
```

```json
{
  "name": "inet6_rt_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587524896,
      "name": "inet6_rt_notify",
      "external": true,
      "loc": "net/ipv6/route.c:3386",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ip6_fib.c:fib6_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587524896,
      "name": "inet6_rt_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
void inet6_rt_notify(int event, struct rt6_info * rt, struct nl_info * info, unsigned int nlm_flags)
```

```json
{
  "name": "inet6_rt_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587729248,
      "name": "inet6_rt_notify",
      "external": true,
      "loc": "net/ipv6/route.c:3457",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ip6_fib.c:fib6_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587729248,
      "name": "inet6_rt_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
void inet6_rt_notify(int event, struct rt6_info * rt, struct nl_info * info, unsigned int nlm_flags)
```

```json
{
  "name": "inet6_rt_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587881376,
      "name": "inet6_rt_notify",
      "external": true,
      "loc": "net/ipv6/route.c:3680",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_mpath_notify",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ip6_fib.c:fib6_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587881376,
      "name": "inet6_rt_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
void inet6_rt_notify(int event, struct rt6_info * rt, struct nl_info * info, unsigned int nlm_flags)
```

```json
{
  "name": "inet6_rt_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588415360,
      "name": "inet6_rt_notify",
      "external": true,
      "loc": "net/ipv6/route.c:4380",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_mpath_notify",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ip6_fib.c:fib6_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588415360,
      "name": "inet6_rt_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
void inet6_rt_notify(int event, struct fib6_info * rt, struct nl_info * info, unsigned int nlm_flags)
```

```json
{
  "name": "inet6_rt_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588776656,
      "name": "inet6_rt_notify",
      "external": true,
      "loc": "net/ipv6/route.c:4981",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_mpath_notify",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ip6_fib.c:fib6_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588776656,
      "name": "inet6_rt_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
void inet6_rt_notify(int event, struct fib6_info * rt, struct nl_info * info, unsigned int nlm_flags)
```

```json
{
  "name": "inet6_rt_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588996944,
      "name": "inet6_rt_notify",
      "external": true,
      "loc": "net/ipv6/route.c:4978",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_mpath_notify",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ip6_fib.c:fib6_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588996944,
      "name": "inet6_rt_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void inet6_rt_notify(int event, struct fib6_info * rt, struct nl_info * info, unsigned int nlm_flags)
```

```json
{
  "name": "inet6_rt_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet6_rt_notify",
      "external": true,
      "loc": "net/ipv6/route.c:5899",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_mpath_notify",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589450482,
      "name": "inet6_rt_notify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071589447440,
      "name": "inet6_rt_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
void inet6_rt_notify(int event, struct fib6_info * rt, struct nl_info * info, unsigned int nlm_flags)
```

```json
{
  "name": "inet6_rt_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589671824,
      "name": "inet6_rt_notify",
      "external": true,
      "loc": "net/ipv6/route.c:5913",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_mpath_notify",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589671824,
      "name": "inet6_rt_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
void inet6_rt_notify(int event, struct fib6_info * rt, struct nl_info * info, unsigned int nlm_flags)
```

```json
{
  "name": "inet6_rt_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590684960,
      "name": "inet6_rt_notify",
      "external": true,
      "loc": "net/ipv6/route.c:6001",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590684960,
      "name": "inet6_rt_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
void inet6_rt_notify(int event, struct fib6_info * rt, struct nl_info * info, unsigned int nlm_flags)
```

```json
{
  "name": "inet6_rt_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590745520,
      "name": "inet6_rt_notify",
      "external": true,
      "loc": "net/ipv6/route.c:5990",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590745520,
      "name": "inet6_rt_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
void inet6_rt_notify(int event, struct fib6_info * rt, struct nl_info * info, unsigned int nlm_flags)
```

```json
{
  "name": "inet6_rt_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590671984,
      "name": "inet6_rt_notify",
      "external": true,
      "loc": "net/ipv6/route.c:6009",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590671984,
      "name": "inet6_rt_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
void inet6_rt_notify(int event, struct fib6_info * rt, struct nl_info * info, unsigned int nlm_flags)
```

```json
{
  "name": "inet6_rt_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591487728,
      "name": "inet6_rt_notify",
      "external": true,
      "loc": "net/ipv6/route.c:6168",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591487728,
      "name": "inet6_rt_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
void inet6_rt_notify(int event, struct fib6_info * rt, struct nl_info * info, unsigned int nlm_flags)
```

```json
{
  "name": "inet6_rt_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593171696,
      "name": "inet6_rt_notify",
      "external": true,
      "loc": "net/ipv6/route.c:6161",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593171696,
      "name": "inet6_rt_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 358
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
void inet6_rt_notify(int event, struct fib6_info * rt, struct nl_info * info, unsigned int nlm_flags)
```

```json
{
  "name": "inet6_rt_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595070128,
      "name": "inet6_rt_notify",
      "external": true,
      "loc": "net/ipv6/route.c:6162",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595070128,
      "name": "inet6_rt_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 358
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
void inet6_rt_notify(int event, struct fib6_info * rt, struct nl_info * info, unsigned int nlm_flags)
```

```json
{
  "name": "inet6_rt_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595463872,
      "name": "inet6_rt_notify",
      "external": true,
      "loc": "net/ipv6/route.c:6160",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595463872,
      "name": "inet6_rt_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 358
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
void inet6_rt_notify(int event, struct fib6_info * rt, struct nl_info * info, unsigned int nlm_flags)
```

```json
{
  "name": "inet6_rt_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596306000,
      "name": "inet6_rt_notify",
      "external": true,
      "loc": "net/ipv6/route.c:6153",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596306000,
      "name": "inet6_rt_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 358
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
void inet6_rt_notify(int event, struct fib6_info * rt, struct nl_info * info, unsigned int nlm_flags)
```

```json
{
  "name": "inet6_rt_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503358752,
      "name": "inet6_rt_notify",
      "external": true,
      "loc": "net/ipv6/route.c:5913",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_mpath_notify",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503358752,
      "name": "inet6_rt_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
void inet6_rt_notify(int event, struct fib6_info * rt, struct nl_info * info, unsigned int nlm_flags)
```

```json
{
  "name": "inet6_rt_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236024520,
      "name": "inet6_rt_notify",
      "external": true,
      "loc": "net/ipv6/route.c:5913",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_mpath_notify",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236024520,
      "name": "inet6_rt_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
void inet6_rt_notify(int event, struct fib6_info * rt, struct nl_info * info, unsigned int nlm_flags)
```

```json
{
  "name": "inet6_rt_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297126144,
      "name": "inet6_rt_notify",
      "external": true,
      "loc": "net/ipv6/route.c:5913",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_mpath_notify",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297126144,
      "name": "inet6_rt_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
void inet6_rt_notify(int event, struct fib6_info * rt, struct nl_info * info, unsigned int nlm_flags)
```

```json
{
  "name": "inet6_rt_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279365052,
      "name": "inet6_rt_notify",
      "external": true,
      "loc": "net/ipv6/route.c:5913",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_mpath_notify",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279365052,
      "name": "inet6_rt_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void inet6_rt_notify(int event, struct fib6_info * rt, struct nl_info * info, unsigned int nlm_flags)
```

```json
{
  "name": "inet6_rt_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589276192,
      "name": "inet6_rt_notify",
      "external": true,
      "loc": "net/ipv6/route.c:5913",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_mpath_notify",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589276192,
      "name": "inet6_rt_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
void inet6_rt_notify(int event, struct fib6_info * rt, struct nl_info * info, unsigned int nlm_flags)
```

```json
{
  "name": "inet6_rt_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589001184,
      "name": "inet6_rt_notify",
      "external": true,
      "loc": "net/ipv6/route.c:5913",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_mpath_notify",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589001184,
      "name": "inet6_rt_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
void inet6_rt_notify(int event, struct fib6_info * rt, struct nl_info * info, unsigned int nlm_flags)
```

```json
{
  "name": "inet6_rt_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589713056,
      "name": "inet6_rt_notify",
      "external": true,
      "loc": "net/ipv6/route.c:5913",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_mpath_notify",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589713056,
      "name": "inet6_rt_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
void inet6_rt_notify(int event, struct fib6_info * rt, struct nl_info * info, unsigned int nlm_flags)
```

```json
{
  "name": "inet6_rt_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589763248,
      "name": "inet6_rt_notify",
      "external": true,
      "loc": "net/ipv6/route.c:5913",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_mpath_notify",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589763248,
      "name": "inet6_rt_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
