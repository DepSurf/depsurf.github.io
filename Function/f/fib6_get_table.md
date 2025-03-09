# Function: <code>fib6_get_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fib6_table * fib6_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib6_get_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587075296,
      "name": "fib6_get_table",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:246",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_new_table"
      ],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_get_prefix_route",
        "net/ipv6/route.c:rt6_get_route_info",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:rt6_get_dflt_router",
        "net/ipv6/route.c:rt6_purge_dflt_routers",
        "net/ipv6/route.c:addrconf_dst_alloc",
        "net/ipv6/fib6_rules.c:fib6_rule_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587075296,
      "name": "fib6_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fib6_table * fib6_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib6_get_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587531445,
      "name": "fib6_get_table",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:246",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_new_table"
      ],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_get_prefix_route",
        "net/ipv6/route.c:addrconf_dst_alloc",
        "net/ipv6/route.c:rt6_purge_dflt_routers",
        "net/ipv6/route.c:rt6_get_dflt_router",
        "net/ipv6/route.c:rt6_get_route_info",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/fib6_rules.c:fib6_rule_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587525680,
      "name": "fib6_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fib6_table * fib6_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib6_get_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587735813,
      "name": "fib6_get_table",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:246",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_new_table"
      ],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_get_prefix_route",
        "net/ipv6/route.c:addrconf_dst_alloc",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_get_dflt_router",
        "net/ipv6/route.c:rt6_get_route_info",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/fib6_rules.c:fib6_rule_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587730032,
      "name": "fib6_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct fib6_table * fib6_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib6_get_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587889205,
      "name": "fib6_get_table",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:261",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_new_table"
      ],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_get_prefix_route",
        "net/ipv6/route.c:addrconf_dst_alloc",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_get_dflt_router",
        "net/ipv6/route.c:rt6_get_route_info",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/fib6_rules.c:fib6_rule_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587884048,
      "name": "fib6_get_table",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fib6_table * fib6_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib6_get_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588421701,
      "name": "fib6_get_table",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:264",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_new_table"
      ],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_get_prefix_route",
        "net/ipv6/route.c:addrconf_dst_alloc",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_get_dflt_router",
        "net/ipv6/route.c:rt6_get_route_info",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/seg6_local.c:lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588418016,
      "name": "fib6_get_table",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fib6_table * fib6_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib6_get_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588779488,
      "name": "fib6_get_table",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:304",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_new_table"
      ],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_get_prefix_route",
        "net/ipv6/route.c:addrconf_f6i_alloc",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_get_dflt_router",
        "net/ipv6/route.c:rt6_get_route_info",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588779488,
      "name": "fib6_get_table",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fib6_table * fib6_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib6_get_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589003238,
      "name": "fib6_get_table",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:303",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:inet6_dump_fib",
        "net/ipv6/ip6_fib.c:fib6_new_table"
      ],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_get_prefix_route",
        "net/ipv6/route.c:addrconf_f6i_alloc",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_get_dflt_router",
        "net/ipv6/route.c:rt6_get_route_info",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588999568,
      "name": "fib6_get_table",
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
struct fib6_table * fib6_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib6_get_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589450608,
      "name": "fib6_get_table",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:271",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_get_prefix_route",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_get_dflt_router",
        "net/ipv6/route.c:rt6_get_route_info",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/ip6_fib.c:inet6_dump_fib",
        "net/ipv6/ip6_fib.c:fib6_new_table",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589450608,
      "name": "fib6_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
struct fib6_table * fib6_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib6_get_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589674928,
      "name": "fib6_get_table",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:271",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_get_prefix_route",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_get_dflt_router",
        "net/ipv6/route.c:rt6_get_route_info",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/ip6_fib.c:inet6_dump_fib",
        "net/ipv6/ip6_fib.c:fib6_new_table",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589674928,
      "name": "fib6_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
struct fib6_table * fib6_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib6_get_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590688304,
      "name": "fib6_get_table",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:271",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_get_prefix_route",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_get_dflt_router",
        "net/ipv6/route.c:rt6_get_route_info",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/ip6_fib.c:inet6_dump_fib",
        "net/ipv6/ip6_fib.c:fib6_new_table",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/seg6_local.c:seg6_lookup_any_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590688304,
      "name": "fib6_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
struct fib6_table * fib6_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib6_get_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590749216,
      "name": "fib6_get_table",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:271",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_get_prefix_route",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_get_dflt_router",
        "net/ipv6/route.c:rt6_get_route_info",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/ip6_fib.c:inet6_dump_fib",
        "net/ipv6/ip6_fib.c:fib6_new_table",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/seg6_local.c:seg6_lookup_any_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590749216,
      "name": "fib6_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
struct fib6_table * fib6_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib6_get_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590675952,
      "name": "fib6_get_table",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:271",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_get_prefix_route",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_get_dflt_router",
        "net/ipv6/route.c:rt6_get_route_info",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/ip6_fib.c:inet6_dump_fib",
        "net/ipv6/ip6_fib.c:fib6_new_table",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/seg6_local.c:seg6_lookup_any_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590675952,
      "name": "fib6_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
struct fib6_table * fib6_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib6_get_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591491776,
      "name": "fib6_get_table",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:272",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_get_prefix_route",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_get_dflt_router",
        "net/ipv6/route.c:rt6_get_route_info",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/ip6_fib.c:inet6_dump_fib",
        "net/ipv6/ip6_fib.c:fib6_new_table",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/seg6_local.c:seg6_lookup_any_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591491776,
      "name": "fib6_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
struct fib6_table * fib6_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib6_get_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593181769,
      "name": "fib6_get_table",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:273",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:inet6_dump_fib",
        "net/ipv6/ip6_fib.c:fib6_new_table"
      ],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_get_prefix_route",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_get_dflt_router",
        "net/ipv6/route.c:rt6_get_route_info",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/seg6_local.c:seg6_lookup_any_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593175680,
      "name": "fib6_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct fib6_table * fib6_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib6_get_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595080761,
      "name": "fib6_get_table",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:272",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:inet6_dump_fib",
        "net/ipv6/ip6_fib.c:fib6_new_table"
      ],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_get_prefix_route",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_get_dflt_router",
        "net/ipv6/route.c:rt6_get_route_info",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/seg6_local.c:seg6_lookup_any_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595074320,
      "name": "fib6_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct fib6_table * fib6_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib6_get_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595474519,
      "name": "fib6_get_table",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:272",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:inet6_dump_fib",
        "net/ipv6/ip6_fib.c:fib6_new_table"
      ],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_get_prefix_route",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_get_dflt_router",
        "net/ipv6/route.c:rt6_get_route_info",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/seg6_local.c:seg6_lookup_any_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595468064,
      "name": "fib6_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct fib6_table * fib6_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib6_get_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596317063,
      "name": "fib6_get_table",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:272",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:inet6_dump_fib",
        "net/ipv6/ip6_fib.c:fib6_new_table"
      ],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_get_prefix_route",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_get_dflt_router",
        "net/ipv6/route.c:rt6_get_route_info",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/seg6_local.c:seg6_lookup_any_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596310384,
      "name": "fib6_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct fib6_table * fib6_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib6_get_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503362528,
      "name": "fib6_get_table",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:271",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_get_prefix_route",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_get_dflt_router",
        "net/ipv6/route.c:rt6_get_route_info",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/ip6_fib.c:inet6_dump_fib",
        "net/ipv6/ip6_fib.c:fib6_new_table",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503362528,
      "name": "fib6_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
struct fib6_table * fib6_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib6_get_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236027564,
      "name": "fib6_get_table",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:271",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_get_prefix_route",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_get_dflt_router",
        "net/ipv6/route.c:rt6_get_route_info",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_nh_lookup_table",
        "net/ipv6/ip6_fib.c:inet6_dump_fib",
        "net/ipv6/ip6_fib.c:fib6_new_table",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236027564,
      "name": "fib6_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct fib6_table * fib6_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib6_get_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297129936,
      "name": "fib6_get_table",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:271",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_get_prefix_route",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_get_dflt_router",
        "net/ipv6/route.c:rt6_get_route_info",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/ip6_fib.c:inet6_dump_fib",
        "net/ipv6/ip6_fib.c:fib6_new_table",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297129936,
      "name": "fib6_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
struct fib6_table * fib6_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib6_get_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279367688,
      "name": "fib6_get_table",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:271",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_get_prefix_route",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_get_dflt_router",
        "net/ipv6/route.c:rt6_get_route_info",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_nh_lookup_table",
        "net/ipv6/ip6_fib.c:inet6_dump_fib",
        "net/ipv6/ip6_fib.c:fib6_new_table",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279367688,
      "name": "fib6_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
struct fib6_table * fib6_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib6_get_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589279296,
      "name": "fib6_get_table",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:271",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_get_prefix_route",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_get_dflt_router",
        "net/ipv6/route.c:rt6_get_route_info",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/ip6_fib.c:inet6_dump_fib",
        "net/ipv6/ip6_fib.c:fib6_new_table",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589279296,
      "name": "fib6_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
struct fib6_table * fib6_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib6_get_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589004288,
      "name": "fib6_get_table",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:271",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_get_prefix_route",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_get_dflt_router",
        "net/ipv6/route.c:rt6_get_route_info",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/ip6_fib.c:inet6_dump_fib",
        "net/ipv6/ip6_fib.c:fib6_new_table",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589004288,
      "name": "fib6_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
struct fib6_table * fib6_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib6_get_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589716160,
      "name": "fib6_get_table",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:271",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_get_prefix_route",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_get_dflt_router",
        "net/ipv6/route.c:rt6_get_route_info",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/ip6_fib.c:inet6_dump_fib",
        "net/ipv6/ip6_fib.c:fib6_new_table",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589716160,
      "name": "fib6_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
struct fib6_table * fib6_get_table(struct net * net, u32 id)
```

```json
{
  "name": "fib6_get_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589767408,
      "name": "fib6_get_table",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:271",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:addrconf_get_prefix_route",
        "net/ipv6/route.c:rt6_add_dflt_router",
        "net/ipv6/route.c:rt6_get_dflt_router",
        "net/ipv6/route.c:rt6_get_route_info",
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/ip6_fib.c:inet6_dump_fib",
        "net/ipv6/ip6_fib.c:fib6_new_table",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589767408,
      "name": "fib6_get_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
