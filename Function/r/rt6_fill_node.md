# Function: <code>rt6_fill_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt6_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587071392,
      "name": "rt6_fill_node",
      "external": false,
      "loc": "net/ipv6/route.c:3045",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:inet6_rt_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587071392,
      "name": "rt6_fill_node.constprop.48",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1507
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
  "name": "rt6_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587503984,
      "name": "rt6_fill_node",
      "external": false,
      "loc": "net/ipv6/route.c:3109",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:rt6_dump_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587503984,
      "name": "rt6_fill_node.constprop.52",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1601
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt6_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587708096,
      "name": "rt6_fill_node",
      "external": false,
      "loc": "net/ipv6/route.c:3178",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:rt6_dump_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587708096,
      "name": "rt6_fill_node.constprop.54",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1609
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
int rt6_fill_node(struct net * net, struct sk_buff * skb, struct rt6_info * rt, struct in6_addr * dst, struct in6_addr * src, int iif, int type, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt6_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587859216,
      "name": "rt6_fill_node",
      "external": false,
      "loc": "net/ipv6/route.c:3382",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:ip6_route_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587859216,
      "name": "rt6_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1580
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
int rt6_fill_node(struct net * net, struct sk_buff * skb, struct rt6_info * rt, struct in6_addr * dst, struct in6_addr * src, int iif, int type, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt6_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588388368,
      "name": "rt6_fill_node",
      "external": false,
      "loc": "net/ipv6/route.c:4072",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:ip6_route_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588388368,
      "name": "rt6_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1586
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
int rt6_fill_node(struct net * net, struct sk_buff * skb, struct fib6_info * rt, struct dst_entry * dst, struct in6_addr * dest, struct in6_addr * src, int iif, int type, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt6_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588749104,
      "name": "rt6_fill_node",
      "external": false,
      "loc": "net/ipv6/route.c:4665",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:ip6_route_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588749104,
      "name": "rt6_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1482
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
int rt6_fill_node(struct net * net, struct sk_buff * skb, struct fib6_info * rt, struct dst_entry * dst, struct in6_addr * dest, struct in6_addr * src, int iif, int type, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt6_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588968064,
      "name": "rt6_fill_node",
      "external": false,
      "loc": "net/ipv6/route.c:4638",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:ip6_route_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588968064,
      "name": "rt6_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1490
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
int rt6_fill_node(struct net * net, struct sk_buff * skb, struct fib6_info * rt, struct dst_entry * dst, struct in6_addr * dest, struct in6_addr * src, int iif, int type, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt6_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rt6_fill_node",
      "external": false,
      "loc": "net/ipv6/route.c:5355",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_nh_dump_exceptions",
        "net/ipv6/route.c:ip6_route_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589412048,
      "name": "rt6_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2100
    },
    {
      "addr": 18446744071589450368,
      "name": "rt6_fill_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
int rt6_fill_node(struct net * net, struct sk_buff * skb, struct fib6_info * rt, struct dst_entry * dst, struct in6_addr * dest, struct in6_addr * src, int iif, int type, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt6_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589636288,
      "name": "rt6_fill_node",
      "external": false,
      "loc": "net/ipv6/route.c:5369",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_nh_dump_exceptions",
        "net/ipv6/route.c:ip6_route_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589636288,
      "name": "rt6_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2107
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
int rt6_fill_node(struct net * net, struct sk_buff * skb, struct fib6_info * rt, struct dst_entry * dst, struct in6_addr * dest, struct in6_addr * src, int iif, int type, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt6_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590661664,
      "name": "rt6_fill_node",
      "external": false,
      "loc": "net/ipv6/route.c:5449",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_nh_dump_exceptions",
        "net/ipv6/route.c:__ip6_del_rt_siblings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590661664,
      "name": "rt6_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2100
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
int rt6_fill_node(struct net * net, struct sk_buff * skb, struct fib6_info * rt, struct dst_entry * dst, struct in6_addr * dest, struct in6_addr * src, int iif, int type, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt6_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590721440,
      "name": "rt6_fill_node",
      "external": false,
      "loc": "net/ipv6/route.c:5434",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_nh_dump_exceptions",
        "net/ipv6/route.c:__ip6_del_rt_siblings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590721440,
      "name": "rt6_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2135
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
int rt6_fill_node(struct net * net, struct sk_buff * skb, struct fib6_info * rt, struct dst_entry * dst, struct in6_addr * dest, struct in6_addr * src, int iif, int type, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt6_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590645088,
      "name": "rt6_fill_node",
      "external": false,
      "loc": "net/ipv6/route.c:5451",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_info_hw_flags_set",
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_nh_dump_exceptions",
        "net/ipv6/route.c:__ip6_del_rt_siblings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590645088,
      "name": "rt6_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2155
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
int rt6_fill_node(struct net * net, struct sk_buff * skb, struct fib6_info * rt, struct dst_entry * dst, struct in6_addr * dest, struct in6_addr * src, int iif, int type, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt6_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rt6_fill_node",
      "external": false,
      "loc": "net/ipv6/route.c:5609",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_info_hw_flags_set",
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_nh_dump_exceptions",
        "net/ipv6/route.c:__ip6_del_rt_siblings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591463472,
      "name": "rt6_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2299
    },
    {
      "addr": 18446744071592738553,
      "name": "rt6_fill_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
int rt6_fill_node(struct net * net, struct sk_buff * skb, struct fib6_info * rt, struct dst_entry * dst, struct in6_addr * dest, struct in6_addr * src, int iif, int type, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt6_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rt6_fill_node",
      "external": false,
      "loc": "net/ipv6/route.c:5602",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_info_hw_flags_set",
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_nh_dump_exceptions",
        "net/ipv6/route.c:__ip6_del_rt_siblings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593145568,
      "name": "rt6_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2375
    },
    {
      "addr": 18446744071594625142,
      "name": "rt6_fill_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
int rt6_fill_node(struct net * net, struct sk_buff * skb, struct fib6_info * rt, struct dst_entry * dst, struct in6_addr * dest, struct in6_addr * src, int iif, int type, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt6_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rt6_fill_node",
      "external": false,
      "loc": "net/ipv6/route.c:5603",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_info_hw_flags_set",
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_nh_dump_exceptions",
        "net/ipv6/route.c:__ip6_del_rt_siblings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595043104,
      "name": "rt6_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2375
    },
    {
      "addr": 18446744071596359367,
      "name": "rt6_fill_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
int rt6_fill_node(struct net * net, struct sk_buff * skb, struct fib6_info * rt, struct dst_entry * dst, struct in6_addr * dest, struct in6_addr * src, int iif, int type, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt6_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rt6_fill_node",
      "external": false,
      "loc": "net/ipv6/route.c:5601",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_info_hw_flags_set",
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_nh_dump_exceptions",
        "net/ipv6/route.c:__ip6_del_rt_siblings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595436560,
      "name": "rt6_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2381
    },
    {
      "addr": 18446744071596887950,
      "name": "rt6_fill_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
int rt6_fill_node(struct net * net, struct sk_buff * skb, struct fib6_info * rt, struct dst_entry * dst, struct in6_addr * dest, struct in6_addr * src, int iif, int type, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt6_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rt6_fill_node",
      "external": false,
      "loc": "net/ipv6/route.c:5594",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_info_hw_flags_set",
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_nh_dump_exceptions",
        "net/ipv6/route.c:__ip6_del_rt_siblings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596278560,
      "name": "rt6_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2381
    },
    {
      "addr": 18446744071597812306,
      "name": "rt6_fill_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
int rt6_fill_node(struct net * net, struct sk_buff * skb, struct fib6_info * rt, struct dst_entry * dst, struct in6_addr * dest, struct in6_addr * src, int iif, int type, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt6_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503318976,
      "name": "rt6_fill_node",
      "external": false,
      "loc": "net/ipv6/route.c:5369",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_nh_dump_exceptions",
        "net/ipv6/route.c:ip6_route_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503318976,
      "name": "rt6_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1864
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
int rt6_fill_node(struct net * net, struct sk_buff * skb, struct fib6_info * rt, struct dst_entry * dst, struct in6_addr * dest, struct in6_addr * src, int iif, int type, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt6_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235988016,
      "name": "rt6_fill_node",
      "external": false,
      "loc": "net/ipv6/route.c:5369",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_nh_dump_exceptions",
        "net/ipv6/route.c:ip6_route_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235988016,
      "name": "rt6_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2064
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
int rt6_fill_node(struct net * net, struct sk_buff * skb, struct fib6_info * rt, struct dst_entry * dst, struct in6_addr * dest, struct in6_addr * src, int iif, int type, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt6_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297079152,
      "name": "rt6_fill_node",
      "external": false,
      "loc": "net/ipv6/route.c:5369",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_nh_dump_exceptions",
        "net/ipv6/route.c:ip6_route_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297079152,
      "name": "rt6_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2564
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
int rt6_fill_node(struct net * net, struct sk_buff * skb, struct fib6_info * rt, struct dst_entry * dst, struct in6_addr * dest, struct in6_addr * src, int iif, int type, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt6_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279336590,
      "name": "rt6_fill_node",
      "external": false,
      "loc": "net/ipv6/route.c:5369",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_nh_dump_exceptions",
        "net/ipv6/route.c:ip6_route_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279336590,
      "name": "rt6_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1552
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
int rt6_fill_node(struct net * net, struct sk_buff * skb, struct fib6_info * rt, struct dst_entry * dst, struct in6_addr * dest, struct in6_addr * src, int iif, int type, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt6_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589240656,
      "name": "rt6_fill_node",
      "external": false,
      "loc": "net/ipv6/route.c:5369",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_nh_dump_exceptions",
        "net/ipv6/route.c:ip6_route_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589240656,
      "name": "rt6_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2107
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
int rt6_fill_node(struct net * net, struct sk_buff * skb, struct fib6_info * rt, struct dst_entry * dst, struct in6_addr * dest, struct in6_addr * src, int iif, int type, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt6_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588965648,
      "name": "rt6_fill_node",
      "external": false,
      "loc": "net/ipv6/route.c:5369",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_nh_dump_exceptions",
        "net/ipv6/route.c:ip6_route_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588965648,
      "name": "rt6_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2107
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
int rt6_fill_node(struct net * net, struct sk_buff * skb, struct fib6_info * rt, struct dst_entry * dst, struct in6_addr * dest, struct in6_addr * src, int iif, int type, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt6_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589677520,
      "name": "rt6_fill_node",
      "external": false,
      "loc": "net/ipv6/route.c:5369",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_nh_dump_exceptions",
        "net/ipv6/route.c:ip6_route_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589677520,
      "name": "rt6_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2107
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
int rt6_fill_node(struct net * net, struct sk_buff * skb, struct fib6_info * rt, struct dst_entry * dst, struct in6_addr * dest, struct in6_addr * src, int iif, int type, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt6_fill_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589726656,
      "name": "rt6_fill_node",
      "external": false,
      "loc": "net/ipv6/route.c:5369",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/route.c:inet6_rt_notify",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:inet6_rtm_getroute",
        "net/ipv6/route.c:rt6_dump_route",
        "net/ipv6/route.c:rt6_nh_dump_exceptions",
        "net/ipv6/route.c:ip6_route_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589726656,
      "name": "rt6_fill_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2107
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int rt6_fill_node(struct net * net, struct sk_buff * skb, struct rt6_info * rt, struct in6_addr * dst, struct in6_addr * src, int iif, int type, u32 portid, u32 seq, unsigned int flags)
```
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
<code>struct in6_addr * dest</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, skb, rt, dst, src, iif, type, portid, seq, flags</code> ➡️ <code>net, skb, rt, dst, dest, src, iif, type, portid, seq, flags</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct rt6_info * rt</code> ➡️ <code>struct fib6_info * rt</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct in6_addr * dst</code> ➡️ <code>struct dst_entry * dst</code>
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
