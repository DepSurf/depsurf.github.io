# Function: <code>ip6_pol_route</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_pol_route",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587059872,
      "name": "ip6_pol_route",
      "external": false,
      "loc": "net/ipv6/route.c:1040",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route_input",
        "net/ipv6/route.c:ip6_pol_route_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587059872,
      "name": "ip6_pol_route.isra.39",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1526
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
struct rt6_info * ip6_pol_route(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, int flags)
```

```json
{
  "name": "ip6_pol_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587511552,
      "name": "ip6_pol_route",
      "external": true,
      "loc": "net/ipv6/route.c:1045",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_pol_route_output",
        "net/ipv6/route.c:ip6_pol_route_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587511552,
      "name": "ip6_pol_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1880
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
struct rt6_info * ip6_pol_route(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, int flags)
```

```json
{
  "name": "ip6_pol_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587715696,
      "name": "ip6_pol_route",
      "external": true,
      "loc": "net/ipv6/route.c:1048",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_pol_route_output",
        "net/ipv6/route.c:ip6_pol_route_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587715696,
      "name": "ip6_pol_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1880
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
struct rt6_info * ip6_pol_route(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, int flags)
```

```json
{
  "name": "ip6_pol_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587868640,
      "name": "ip6_pol_route",
      "external": true,
      "loc": "net/ipv6/route.c:1070",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_pol_route_output",
        "net/ipv6/route.c:ip6_pol_route_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587868640,
      "name": "ip6_pol_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2176
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
struct rt6_info * ip6_pol_route(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, int flags)
```

```json
{
  "name": "ip6_pol_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588404032,
      "name": "ip6_pol_route",
      "external": true,
      "loc": "net/ipv6/route.c:1679",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_info_create",
        "net/ipv6/route.c:ip6_pol_route_output",
        "net/ipv6/route.c:ip6_pol_route_input",
        "net/ipv6/seg6_local.c:lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588404032,
      "name": "ip6_pol_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2452
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
struct rt6_info * ip6_pol_route(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_pol_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588766912,
      "name": "ip6_pol_route",
      "external": true,
      "loc": "net/ipv6/route.c:1850",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route_output",
        "net/ipv6/route.c:ip6_pol_route_input",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588766912,
      "name": "ip6_pol_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 903
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
struct rt6_info * ip6_pol_route(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_pol_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588987040,
      "name": "ip6_pol_route",
      "external": true,
      "loc": "net/ipv6/route.c:1841",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route_output",
        "net/ipv6/route.c:ip6_pol_route_input",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588987040,
      "name": "ip6_pol_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 903
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
struct rt6_info * ip6_pol_route(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_pol_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589436272,
      "name": "ip6_pol_route",
      "external": true,
      "loc": "net/ipv6/route.c:2182",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route_output",
        "net/ipv6/route.c:ip6_pol_route_input",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589436272,
      "name": "ip6_pol_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 751
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
struct rt6_info * ip6_pol_route(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_pol_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589660640,
      "name": "ip6_pol_route",
      "external": true,
      "loc": "net/ipv6/route.c:2188",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route_output",
        "net/ipv6/route.c:ip6_pol_route_input",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589660640,
      "name": "ip6_pol_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 751
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
struct rt6_info * ip6_pol_route(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_pol_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590673360,
      "name": "ip6_pol_route",
      "external": true,
      "loc": "net/ipv6/route.c:2210",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route_output",
        "net/ipv6/route.c:ip6_pol_route_input",
        "net/ipv6/seg6_local.c:seg6_lookup_any_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590673360,
      "name": "ip6_pol_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 737
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
struct rt6_info * ip6_pol_route(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_pol_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590733728,
      "name": "ip6_pol_route",
      "external": true,
      "loc": "net/ipv6/route.c:2193",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route_output",
        "net/ipv6/route.c:ip6_pol_route_input",
        "net/ipv6/seg6_local.c:seg6_lookup_any_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590733728,
      "name": "ip6_pol_route",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct rt6_info * ip6_pol_route(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_pol_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590658992,
      "name": "ip6_pol_route",
      "external": true,
      "loc": "net/ipv6/route.c:2200",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route_output",
        "net/ipv6/route.c:ip6_pol_route_input",
        "net/ipv6/seg6_local.c:seg6_lookup_any_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590658992,
      "name": "ip6_pol_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 612
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
struct rt6_info * ip6_pol_route(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_pol_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591473936,
      "name": "ip6_pol_route",
      "external": true,
      "loc": "net/ipv6/route.c:2203",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route_output",
        "net/ipv6/route.c:ip6_pol_route_input",
        "net/ipv6/seg6_local.c:seg6_lookup_any_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591473936,
      "name": "ip6_pol_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1025
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
struct rt6_info * ip6_pol_route(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_pol_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593156864,
      "name": "ip6_pol_route",
      "external": true,
      "loc": "net/ipv6/route.c:2200",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route_output",
        "net/ipv6/route.c:ip6_pol_route_input",
        "net/ipv6/seg6_local.c:seg6_lookup_any_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593156864,
      "name": "ip6_pol_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1058
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
struct rt6_info * ip6_pol_route(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_pol_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595054704,
      "name": "ip6_pol_route",
      "external": true,
      "loc": "net/ipv6/route.c:2200",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route_output",
        "net/ipv6/route.c:ip6_pol_route_input",
        "net/ipv6/seg6_local.c:seg6_lookup_any_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595054704,
      "name": "ip6_pol_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1058
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
struct rt6_info * ip6_pol_route(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_pol_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595448080,
      "name": "ip6_pol_route",
      "external": true,
      "loc": "net/ipv6/route.c:2199",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route_output",
        "net/ipv6/route.c:ip6_pol_route_input",
        "net/ipv6/seg6_local.c:seg6_lookup_any_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595448080,
      "name": "ip6_pol_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1056
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
struct rt6_info * ip6_pol_route(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_pol_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596290160,
      "name": "ip6_pol_route",
      "external": true,
      "loc": "net/ipv6/route.c:2201",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route_output",
        "net/ipv6/route.c:ip6_pol_route_input",
        "net/ipv6/seg6_local.c:seg6_lookup_any_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596290160,
      "name": "ip6_pol_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1092
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
struct rt6_info * ip6_pol_route(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_pol_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503346968,
      "name": "ip6_pol_route",
      "external": true,
      "loc": "net/ipv6/route.c:2188",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route_output",
        "net/ipv6/route.c:ip6_pol_route_input",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503346968,
      "name": "ip6_pol_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 764
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
struct rt6_info * ip6_pol_route(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_pol_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236012908,
      "name": "ip6_pol_route",
      "external": true,
      "loc": "net/ipv6/route.c:2188",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route_output",
        "net/ipv6/route.c:ip6_pol_route_input",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236012908,
      "name": "ip6_pol_route",
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
struct rt6_info * ip6_pol_route(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_pol_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297111056,
      "name": "ip6_pol_route",
      "external": true,
      "loc": "net/ipv6/route.c:2188",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route_output",
        "net/ipv6/route.c:ip6_pol_route_input",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297111056,
      "name": "ip6_pol_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 960
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
struct rt6_info * ip6_pol_route(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_pol_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279355220,
      "name": "ip6_pol_route",
      "external": true,
      "loc": "net/ipv6/route.c:2188",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route_output",
        "net/ipv6/route.c:ip6_pol_route_input",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279355220,
      "name": "ip6_pol_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 672
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
struct rt6_info * ip6_pol_route(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_pol_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589265008,
      "name": "ip6_pol_route",
      "external": true,
      "loc": "net/ipv6/route.c:2188",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route_output",
        "net/ipv6/route.c:ip6_pol_route_input",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589265008,
      "name": "ip6_pol_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 751
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
struct rt6_info * ip6_pol_route(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_pol_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588990000,
      "name": "ip6_pol_route",
      "external": true,
      "loc": "net/ipv6/route.c:2188",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route_output",
        "net/ipv6/route.c:ip6_pol_route_input",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588990000,
      "name": "ip6_pol_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 751
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
struct rt6_info * ip6_pol_route(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_pol_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589701872,
      "name": "ip6_pol_route",
      "external": true,
      "loc": "net/ipv6/route.c:2188",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route_output",
        "net/ipv6/route.c:ip6_pol_route_input",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589701872,
      "name": "ip6_pol_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 751
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
struct rt6_info * ip6_pol_route(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_pol_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589751664,
      "name": "ip6_pol_route",
      "external": true,
      "loc": "net/ipv6/route.c:2188",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_pol_route_output",
        "net/ipv6/route.c:ip6_pol_route_input",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589751664,
      "name": "ip6_pol_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 801
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
struct rt6_info * ip6_pol_route(struct net * net, struct fib6_table * table, int oif, struct flowi6 * fl6, int flags)
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct sk_buff * skb</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, table, oif, fl6, flags</code> ➡️ <code>net, table, oif, fl6, skb, flags</code>
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
