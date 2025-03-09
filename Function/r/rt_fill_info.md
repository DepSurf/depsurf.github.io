# Function: <code>rt_fill_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt_fill_info",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586528064,
      "name": "rt_fill_info",
      "external": false,
      "loc": "net/ipv4/route.c:2399",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586528064,
      "name": "rt_fill_info.constprop.40",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1318
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
  "name": "rt_fill_info",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586970640,
      "name": "rt_fill_info",
      "external": false,
      "loc": "net/ipv4/route.c:2422",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586970640,
      "name": "rt_fill_info.constprop.41",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1295
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
  "name": "rt_fill_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587179823,
      "name": "rt_fill_info",
      "external": false,
      "loc": "net/ipv4/route.c:2457",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt_fill_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587313452,
      "name": "rt_fill_info",
      "external": false,
      "loc": "net/ipv4/route.c:2552",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt_fill_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587835270,
      "name": "rt_fill_info",
      "external": false,
      "loc": "net/ipv4/route.c:2573",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt_fill_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588179551,
      "name": "rt_fill_info",
      "external": false,
      "loc": "net/ipv4/route.c:2597",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt_fill_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588363579,
      "name": "rt_fill_info",
      "external": false,
      "loc": "net/ipv4/route.c:2599",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int rt_fill_info(struct net * net, __be32 dst, __be32 src, struct rtable * rt, u32 table_id, struct flowi4 * fl4, struct sk_buff * skb, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt_fill_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rt_fill_info",
      "external": false,
      "loc": "net/ipv4/route.c:2729",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:fib_dump_info_fnhe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588745152,
      "name": "rt_fill_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1477
    },
    {
      "addr": 18446744071588768103,
      "name": "rt_fill_info.cold",
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
int rt_fill_info(struct net * net, __be32 dst, __be32 src, struct rtable * rt, u32 table_id, struct flowi4 * fl4, struct sk_buff * skb, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt_fill_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588968896,
      "name": "rt_fill_info",
      "external": false,
      "loc": "net/ipv4/route.c:2738",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:fib_dump_info_fnhe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588968896,
      "name": "rt_fill_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1495
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
int rt_fill_info(struct net * net, __be32 dst, __be32 src, struct rtable * rt, u32 table_id, struct flowi4 * fl4, struct sk_buff * skb, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt_fill_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589925168,
      "name": "rt_fill_info",
      "external": false,
      "loc": "net/ipv4/route.c:2825",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:fnhe_dump_bucket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589925168,
      "name": "rt_fill_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1481
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
int rt_fill_info(struct net * net, __be32 dst, __be32 src, struct rtable * rt, u32 table_id, struct flowi4 * fl4, struct sk_buff * skb, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt_fill_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589965712,
      "name": "rt_fill_info",
      "external": false,
      "loc": "net/ipv4/route.c:2804",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:fnhe_dump_bucket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589965712,
      "name": "rt_fill_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1516
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
int rt_fill_info(struct net * net, __be32 dst, __be32 src, struct rtable * rt, u32 table_id, struct flowi4 * fl4, struct sk_buff * skb, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt_fill_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589880752,
      "name": "rt_fill_info",
      "external": false,
      "loc": "net/ipv4/route.c:2805",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:fib_dump_info_fnhe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589880752,
      "name": "rt_fill_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1514
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
int rt_fill_info(struct net * net, __be32 dst, __be32 src, struct rtable * rt, u32 table_id, struct flowi4 * fl4, struct sk_buff * skb, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt_fill_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590644464,
      "name": "rt_fill_info",
      "external": false,
      "loc": "net/ipv4/route.c:2923",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:fib_dump_info_fnhe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590644464,
      "name": "rt_fill_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1514
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
int rt_fill_info(struct net * net, __be32 dst, __be32 src, struct rtable * rt, u32 table_id, struct flowi4 * fl4, struct sk_buff * skb, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt_fill_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592269168,
      "name": "rt_fill_info",
      "external": false,
      "loc": "net/ipv4/route.c:2947",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:fib_dump_info_fnhe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592269168,
      "name": "rt_fill_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1477
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
int rt_fill_info(struct net * net, __be32 dst, __be32 src, struct rtable * rt, u32 table_id, struct flowi4 * fl4, struct sk_buff * skb, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt_fill_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594104512,
      "name": "rt_fill_info",
      "external": false,
      "loc": "net/ipv4/route.c:2938",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:fib_dump_info_fnhe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594104512,
      "name": "rt_fill_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1536
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
int rt_fill_info(struct net * net, __be32 dst, __be32 src, struct rtable * rt, u32 table_id, struct flowi4 * fl4, struct sk_buff * skb, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt_fill_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594491360,
      "name": "rt_fill_info",
      "external": false,
      "loc": "net/ipv4/route.c:2934",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:fib_dump_info_fnhe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594491360,
      "name": "rt_fill_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1560
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
int rt_fill_info(struct net * net, __be32 dst, __be32 src, struct rtable * rt, u32 table_id, struct flowi4 * fl4, struct sk_buff * skb, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt_fill_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595294256,
      "name": "rt_fill_info",
      "external": false,
      "loc": "net/ipv4/route.c:2889",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:fib_dump_info_fnhe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595294256,
      "name": "rt_fill_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1560
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
int rt_fill_info(struct net * net, __be32 dst, __be32 src, struct rtable * rt, u32 table_id, struct flowi4 * fl4, struct sk_buff * skb, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt_fill_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502571648,
      "name": "rt_fill_info",
      "external": false,
      "loc": "net/ipv4/route.c:2738",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:fib_dump_info_fnhe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502571648,
      "name": "rt_fill_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1192
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
int rt_fill_info(struct net * net, __be32 dst, __be32 src, struct rtable * rt, u32 table_id, struct flowi4 * fl4, struct sk_buff * skb, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt_fill_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235278592,
      "name": "rt_fill_info",
      "external": false,
      "loc": "net/ipv4/route.c:2738",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:fib_dump_info_fnhe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235278592,
      "name": "rt_fill_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1372
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
int rt_fill_info(struct net * net, __be32 dst, __be32 src, struct rtable * rt, u32 table_id, struct flowi4 * fl4, struct sk_buff * skb, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt_fill_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296157664,
      "name": "rt_fill_info",
      "external": false,
      "loc": "net/ipv4/route.c:2738",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:fib_dump_info_fnhe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296157664,
      "name": "rt_fill_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1636
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
int rt_fill_info(struct net * net, __be32 dst, __be32 src, struct rtable * rt, u32 table_id, struct flowi4 * fl4, struct sk_buff * skb, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt_fill_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278730236,
      "name": "rt_fill_info",
      "external": false,
      "loc": "net/ipv4/route.c:2738",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:fib_dump_info_fnhe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278730236,
      "name": "rt_fill_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 992
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
int rt_fill_info(struct net * net, __be32 dst, __be32 src, struct rtable * rt, u32 table_id, struct flowi4 * fl4, struct sk_buff * skb, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt_fill_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588575280,
      "name": "rt_fill_info",
      "external": false,
      "loc": "net/ipv4/route.c:2738",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:fib_dump_info_fnhe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588575280,
      "name": "rt_fill_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1495
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
int rt_fill_info(struct net * net, __be32 dst, __be32 src, struct rtable * rt, u32 table_id, struct flowi4 * fl4, struct sk_buff * skb, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt_fill_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588287264,
      "name": "rt_fill_info",
      "external": false,
      "loc": "net/ipv4/route.c:2738",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:fib_dump_info_fnhe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588287264,
      "name": "rt_fill_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1495
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
int rt_fill_info(struct net * net, __be32 dst, __be32 src, struct rtable * rt, u32 table_id, struct flowi4 * fl4, struct sk_buff * skb, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt_fill_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589011456,
      "name": "rt_fill_info",
      "external": false,
      "loc": "net/ipv4/route.c:2738",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:fib_dump_info_fnhe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589011456,
      "name": "rt_fill_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1495
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
int rt_fill_info(struct net * net, __be32 dst, __be32 src, struct rtable * rt, u32 table_id, struct flowi4 * fl4, struct sk_buff * skb, u32 portid, u32 seq, unsigned int flags)
```

```json
{
  "name": "rt_fill_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589050048,
      "name": "rt_fill_info",
      "external": false,
      "loc": "net/ipv4/route.c:2738",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv4/route.c:fib_dump_info_fnhe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589050048,
      "name": "rt_fill_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1495
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int rt_fill_info(struct net * net, __be32 dst, __be32 src, struct rtable * rt, u32 table_id, struct flowi4 * fl4, struct sk_buff * skb, u32 portid, u32 seq, unsigned int flags)
```
</details>
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
