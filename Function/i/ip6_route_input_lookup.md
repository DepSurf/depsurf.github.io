# Function: <code>ip6_route_input_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_input_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587055696,
      "name": "ip6_route_input_lookup",
      "external": false,
      "loc": "net/ipv6/route.c:1139",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_input",
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587055696,
      "name": "ip6_route_input_lookup.isra.40",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_input_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587503680,
      "name": "ip6_route_input_lookup",
      "external": false,
      "loc": "net/ipv6/route.c:1150",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_route_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587503680,
      "name": "ip6_route_input_lookup.isra.43",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
struct dst_entry * ip6_route_input_lookup(struct net * net, struct net_device * dev, struct flowi6 * fl6, int flags)
```

```json
{
  "name": "ip6_route_input_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587705200,
      "name": "ip6_route_input_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:1154",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_route_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587705200,
      "name": "ip6_route_input_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
struct dst_entry * ip6_route_input_lookup(struct net * net, struct net_device * dev, struct flowi6 * fl6, int flags)
```

```json
{
  "name": "ip6_route_input_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587855168,
      "name": "ip6_route_input_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:1179",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_route_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587855168,
      "name": "ip6_route_input_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
struct dst_entry * ip6_route_input_lookup(struct net * net, struct net_device * dev, struct flowi6 * fl6, int flags)
```

```json
{
  "name": "ip6_route_input_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588384240,
      "name": "ip6_route_input_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:1807",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_route_input",
        "net/ipv6/seg6_local.c:lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588384240,
      "name": "ip6_route_input_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
struct dst_entry * ip6_route_input_lookup(struct net * net, struct net_device * dev, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_route_input_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588743520,
      "name": "ip6_route_input_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:1937",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_route_input",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588743520,
      "name": "ip6_route_input_lookup",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dst_entry * ip6_route_input_lookup(struct net * net, struct net_device * dev, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_route_input_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588963728,
      "name": "ip6_route_input_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:1928",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_route_input",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588963728,
      "name": "ip6_route_input_lookup",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dst_entry * ip6_route_input_lookup(struct net * net, struct net_device * dev, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_route_input_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589408048,
      "name": "ip6_route_input_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:2261",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_route_input",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589408048,
      "name": "ip6_route_input_lookup",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct dst_entry * ip6_route_input_lookup(struct net * net, struct net_device * dev, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_route_input_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589632288,
      "name": "ip6_route_input_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:2267",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_route_input",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589632288,
      "name": "ip6_route_input_lookup",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dst_entry * ip6_route_input_lookup(struct net * net, struct net_device * dev, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_route_input_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590665110,
      "name": "ip6_route_input_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:2289",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_route_input"
      ],
      "caller_func": [
        "net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap",
        "net/ipv6/seg6_local.c:seg6_lookup_any_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590642528,
      "name": "ip6_route_input_lookup",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dst_entry * ip6_route_input_lookup(struct net * net, struct net_device * dev, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_route_input_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590724924,
      "name": "ip6_route_input_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:2272",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_route_input"
      ],
      "caller_func": [
        "net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap",
        "net/ipv6/seg6_local.c:seg6_lookup_any_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590702624,
      "name": "ip6_route_input_lookup",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dst_entry * ip6_route_input_lookup(struct net * net, struct net_device * dev, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_route_input_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590648994,
      "name": "ip6_route_input_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:2279",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_route_input"
      ],
      "caller_func": [
        "net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap",
        "net/ipv6/seg6_local.c:seg6_lookup_any_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590628432,
      "name": "ip6_route_input_lookup",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dst_entry * ip6_route_input_lookup(struct net * net, struct net_device * dev, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_route_input_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591467474,
      "name": "ip6_route_input_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:2282",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_route_input"
      ],
      "caller_func": [
        "net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap",
        "net/ipv6/seg6_local.c:seg6_lookup_any_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591441904,
      "name": "ip6_route_input_lookup",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dst_entry * ip6_route_input_lookup(struct net * net, struct net_device * dev, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_route_input_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593151395,
      "name": "ip6_route_input_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:2278",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_route_input"
      ],
      "caller_func": [
        "net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap",
        "net/ipv6/seg6_local.c:seg6_lookup_any_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593121264,
      "name": "ip6_route_input_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct dst_entry * ip6_route_input_lookup(struct net * net, struct net_device * dev, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_route_input_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595049043,
      "name": "ip6_route_input_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:2278",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_route_input"
      ],
      "caller_func": [
        "net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap",
        "net/ipv6/seg6_local.c:seg6_lookup_any_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595017376,
      "name": "ip6_route_input_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct dst_entry * ip6_route_input_lookup(struct net * net, struct net_device * dev, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_route_input_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595442483,
      "name": "ip6_route_input_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:2277",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_route_input"
      ],
      "caller_func": [
        "net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap",
        "net/ipv6/seg6_local.c:seg6_lookup_any_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595410912,
      "name": "ip6_route_input_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct dst_entry * ip6_route_input_lookup(struct net * net, struct net_device * dev, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_route_input_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596284485,
      "name": "ip6_route_input_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:2279",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_route_input"
      ],
      "caller_func": [
        "net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap",
        "net/ipv6/seg6_local.c:seg6_lookup_any_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596252608,
      "name": "ip6_route_input_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct dst_entry * ip6_route_input_lookup(struct net * net, struct net_device * dev, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_route_input_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503315264,
      "name": "ip6_route_input_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:2267",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_route_input",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503315264,
      "name": "ip6_route_input_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
struct dst_entry * ip6_route_input_lookup(struct net * net, struct net_device * dev, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_route_input_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235983144,
      "name": "ip6_route_input_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:2267",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_route_input",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235983144,
      "name": "ip6_route_input_lookup",
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
struct dst_entry * ip6_route_input_lookup(struct net * net, struct net_device * dev, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_route_input_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297073360,
      "name": "ip6_route_input_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:2267",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_route_input",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297073360,
      "name": "ip6_route_input_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
struct dst_entry * ip6_route_input_lookup(struct net * net, struct net_device * dev, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_route_input_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279330950,
      "name": "ip6_route_input_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:2267",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_route_input",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279330950,
      "name": "ip6_route_input_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
struct dst_entry * ip6_route_input_lookup(struct net * net, struct net_device * dev, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_route_input_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589236656,
      "name": "ip6_route_input_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:2267",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_route_input",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589236656,
      "name": "ip6_route_input_lookup",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct dst_entry * ip6_route_input_lookup(struct net * net, struct net_device * dev, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_route_input_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588961648,
      "name": "ip6_route_input_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:2267",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_route_input",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588961648,
      "name": "ip6_route_input_lookup",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct dst_entry * ip6_route_input_lookup(struct net * net, struct net_device * dev, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_route_input_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589673520,
      "name": "ip6_route_input_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:2267",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_route_input",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589673520,
      "name": "ip6_route_input_lookup",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dst_entry * ip6_route_input_lookup(struct net * net, struct net_device * dev, struct flowi6 * fl6, const struct sk_buff * skb, int flags)
```

```json
{
  "name": "ip6_route_input_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589722656,
      "name": "ip6_route_input_lookup",
      "external": true,
      "loc": "net/ipv6/route.c:2267",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:ip6_route_input",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589722656,
      "name": "ip6_route_input_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
struct dst_entry * ip6_route_input_lookup(struct net * net, struct net_device * dev, struct flowi6 * fl6, int flags)
```
</details>
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
<code>net, dev, fl6, flags</code> ➡️ <code>net, dev, fl6, skb, flags</code>
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
