# Function: <code>ipmr_get_route</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ipmr_get_route(struct net * net, struct sk_buff * skb, __be32 saddr, __be32 daddr, struct rtmsg * rtm, int nowait)
```

```json
{
  "name": "ipmr_get_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586884384,
      "name": "ipmr_get_route",
      "external": true,
      "loc": "net/ipv4/ipmr.c:2191",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586884384,
      "name": "ipmr_get_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 631
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
int ipmr_get_route(struct net * net, struct sk_buff * skb, __be32 saddr, __be32 daddr, struct rtmsg * rtm, int nowait, u32 portid)
```

```json
{
  "name": "ipmr_get_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587333632,
      "name": "ipmr_get_route",
      "external": true,
      "loc": "net/ipv4/ipmr.c:2124",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587333632,
      "name": "ipmr_get_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 668
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
int ipmr_get_route(struct net * net, struct sk_buff * skb, __be32 saddr, __be32 daddr, struct rtmsg * rtm, int nowait, u32 portid)
```

```json
{
  "name": "ipmr_get_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587536480,
      "name": "ipmr_get_route",
      "external": true,
      "loc": "net/ipv4/ipmr.c:2135",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587536480,
      "name": "ipmr_get_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 668
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
int ipmr_get_route(struct net * net, struct sk_buff * skb, __be32 saddr, __be32 daddr, struct rtmsg * rtm, u32 portid)
```

```json
{
  "name": "ipmr_get_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587682288,
      "name": "ipmr_get_route",
      "external": true,
      "loc": "net/ipv4/ipmr.c:2193",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587682288,
      "name": "ipmr_get_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 843
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
int ipmr_get_route(struct net * net, struct sk_buff * skb, __be32 saddr, __be32 daddr, struct rtmsg * rtm, u32 portid)
```

```json
{
  "name": "ipmr_get_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588208928,
      "name": "ipmr_get_route",
      "external": true,
      "loc": "net/ipv4/ipmr.c:2358",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588208928,
      "name": "ipmr_get_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 859
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
int ipmr_get_route(struct net * net, struct sk_buff * skb, __be32 saddr, __be32 daddr, struct rtmsg * rtm, u32 portid)
```

```json
{
  "name": "ipmr_get_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588560336,
      "name": "ipmr_get_route",
      "external": true,
      "loc": "net/ipv4/ipmr.c:2232",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588560336,
      "name": "ipmr_get_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 669
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
int ipmr_get_route(struct net * net, struct sk_buff * skb, __be32 saddr, __be32 daddr, struct rtmsg * rtm, u32 portid)
```

```json
{
  "name": "ipmr_get_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588757280,
      "name": "ipmr_get_route",
      "external": true,
      "loc": "net/ipv4/ipmr.c:2245",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588757280,
      "name": "ipmr_get_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 669
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
int ipmr_get_route(struct net * net, struct sk_buff * skb, __be32 saddr, __be32 daddr, struct rtmsg * rtm, u32 portid)
```

```json
{
  "name": "ipmr_get_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589190160,
      "name": "ipmr_get_route",
      "external": true,
      "loc": "net/ipv4/ipmr.c:2257",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:rt_fill_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589190160,
      "name": "ipmr_get_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
int ipmr_get_route(struct net * net, struct sk_buff * skb, __be32 saddr, __be32 daddr, struct rtmsg * rtm, u32 portid)
```

```json
{
  "name": "ipmr_get_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589415728,
      "name": "ipmr_get_route",
      "external": true,
      "loc": "net/ipv4/ipmr.c:2257",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:rt_fill_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589415728,
      "name": "ipmr_get_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 633
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
int ipmr_get_route(struct net * net, struct sk_buff * skb, __be32 saddr, __be32 daddr, struct rtmsg * rtm, u32 portid)
```

```json
{
  "name": "ipmr_get_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590402736,
      "name": "ipmr_get_route",
      "external": true,
      "loc": "net/ipv4/ipmr.c:2225",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:rt_fill_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590402736,
      "name": "ipmr_get_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 635
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
int ipmr_get_route(struct net * net, struct sk_buff * skb, __be32 saddr, __be32 daddr, struct rtmsg * rtm, u32 portid)
```

```json
{
  "name": "ipmr_get_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590460624,
      "name": "ipmr_get_route",
      "external": true,
      "loc": "net/ipv4/ipmr.c:2232",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:rt_fill_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590460624,
      "name": "ipmr_get_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 650
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
int ipmr_get_route(struct net * net, struct sk_buff * skb, __be32 saddr, __be32 daddr, struct rtmsg * rtm, u32 portid)
```

```json
{
  "name": "ipmr_get_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590386448,
      "name": "ipmr_get_route",
      "external": true,
      "loc": "net/ipv4/ipmr.c:2232",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:rt_fill_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590386448,
      "name": "ipmr_get_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 656
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
int ipmr_get_route(struct net * net, struct sk_buff * skb, __be32 saddr, __be32 daddr, struct rtmsg * rtm, u32 portid)
```

```json
{
  "name": "ipmr_get_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591180528,
      "name": "ipmr_get_route",
      "external": true,
      "loc": "net/ipv4/ipmr.c:2234",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:rt_fill_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591180528,
      "name": "ipmr_get_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 749
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
int ipmr_get_route(struct net * net, struct sk_buff * skb, __be32 saddr, __be32 daddr, struct rtmsg * rtm, u32 portid)
```

```json
{
  "name": "ipmr_get_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592839280,
      "name": "ipmr_get_route",
      "external": true,
      "loc": "net/ipv4/ipmr.c:2228",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:rt_fill_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592839280,
      "name": "ipmr_get_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 804
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
int ipmr_get_route(struct net * net, struct sk_buff * skb, __be32 saddr, __be32 daddr, struct rtmsg * rtm, u32 portid)
```

```json
{
  "name": "ipmr_get_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594716384,
      "name": "ipmr_get_route",
      "external": true,
      "loc": "net/ipv4/ipmr.c:2241",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:rt_fill_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594716384,
      "name": "ipmr_get_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 665
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
int ipmr_get_route(struct net * net, struct sk_buff * skb, __be32 saddr, __be32 daddr, struct rtmsg * rtm, u32 portid)
```

```json
{
  "name": "ipmr_get_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595108384,
      "name": "ipmr_get_route",
      "external": true,
      "loc": "net/ipv4/ipmr.c:2256",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:rt_fill_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595108384,
      "name": "ipmr_get_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 665
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
int ipmr_get_route(struct net * net, struct sk_buff * skb, __be32 saddr, __be32 daddr, struct rtmsg * rtm, u32 portid)
```

```json
{
  "name": "ipmr_get_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595921056,
      "name": "ipmr_get_route",
      "external": true,
      "loc": "net/ipv4/ipmr.c:2254",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:rt_fill_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595921056,
      "name": "ipmr_get_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 665
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
int ipmr_get_route(struct net * net, struct sk_buff * skb, __be32 saddr, __be32 daddr, struct rtmsg * rtm, u32 portid)
```

```json
{
  "name": "ipmr_get_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503066160,
      "name": "ipmr_get_route",
      "external": true,
      "loc": "net/ipv4/ipmr.c:2257",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:rt_fill_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503066160,
      "name": "ipmr_get_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 864
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
int ipmr_get_route(struct net * net, struct sk_buff * skb, __be32 saddr, __be32 daddr, struct rtmsg * rtm, u32 portid)
```

```json
{
  "name": "ipmr_get_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235750940,
      "name": "ipmr_get_route",
      "external": true,
      "loc": "net/ipv4/ipmr.c:2257",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:rt_fill_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235750940,
      "name": "ipmr_get_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 740
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
int ipmr_get_route(struct net * net, struct sk_buff * skb, __be32 saddr, __be32 daddr, struct rtmsg * rtm, u32 portid)
```

```json
{
  "name": "ipmr_get_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296770160,
      "name": "ipmr_get_route",
      "external": true,
      "loc": "net/ipv4/ipmr.c:2257",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:rt_fill_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296770160,
      "name": "ipmr_get_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 908
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
int ipmr_get_route(struct net * net, struct sk_buff * skb, __be32 saddr, __be32 daddr, struct rtmsg * rtm, u32 portid)
```

```json
{
  "name": "ipmr_get_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279125658,
      "name": "ipmr_get_route",
      "external": true,
      "loc": "net/ipv4/ipmr.c:2257",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:rt_fill_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279125658,
      "name": "ipmr_get_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
int ipmr_get_route(struct net * net, struct sk_buff * skb, __be32 saddr, __be32 daddr, struct rtmsg * rtm, u32 portid)
```

```json
{
  "name": "ipmr_get_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589020128,
      "name": "ipmr_get_route",
      "external": true,
      "loc": "net/ipv4/ipmr.c:2257",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:rt_fill_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589020128,
      "name": "ipmr_get_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
int ipmr_get_route(struct net * net, struct sk_buff * skb, __be32 saddr, __be32 daddr, struct rtmsg * rtm, u32 portid)
```

```json
{
  "name": "ipmr_get_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588743184,
      "name": "ipmr_get_route",
      "external": true,
      "loc": "net/ipv4/ipmr.c:2257",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:rt_fill_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588743184,
      "name": "ipmr_get_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
int ipmr_get_route(struct net * net, struct sk_buff * skb, __be32 saddr, __be32 daddr, struct rtmsg * rtm, u32 portid)
```

```json
{
  "name": "ipmr_get_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589456512,
      "name": "ipmr_get_route",
      "external": true,
      "loc": "net/ipv4/ipmr.c:2257",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:rt_fill_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589456512,
      "name": "ipmr_get_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
int ipmr_get_route(struct net * net, struct sk_buff * skb, __be32 saddr, __be32 daddr, struct rtmsg * rtm, u32 portid)
```

```json
{
  "name": "ipmr_get_route",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589502720,
      "name": "ipmr_get_route",
      "external": true,
      "loc": "net/ipv4/ipmr.c:2257",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:rt_fill_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589502720,
      "name": "ipmr_get_route",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 670
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 portid</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int nowait</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, skb, saddr, daddr, rtm, nowait, portid</code> ➡️ <code>net, skb, saddr, daddr, rtm, portid</code>
</li>
</ul>
</details>
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
