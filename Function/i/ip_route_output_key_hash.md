# Function: <code>ip_route_output_key_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct rtable * ip_route_output_key_hash(struct net * net, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "ip_route_output_key_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587310800,
      "name": "ip_route_output_key_hash",
      "external": true,
      "loc": "net/ipv4/route.c:2272",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_flow",
        "net/ipv4/route.c:ipv4_sk_redirect",
        "net/ipv4/route.c:ipv4_redirect",
        "net/ipv4/route.c:ipv4_update_pmtu",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587310800,
      "name": "ip_route_output_key_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
struct rtable * ip_route_output_key_hash(struct net * net, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "ip_route_output_key_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587832592,
      "name": "ip_route_output_key_hash",
      "external": true,
      "loc": "net/ipv4/route.c:2287",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_flow",
        "net/ipv4/route.c:ipv4_sk_redirect",
        "net/ipv4/route.c:ipv4_redirect",
        "net/ipv4/route.c:ipv4_update_pmtu",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587832592,
      "name": "ip_route_output_key_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
struct rtable * ip_route_output_key_hash(struct net * net, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "ip_route_output_key_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588176608,
      "name": "ip_route_output_key_hash",
      "external": true,
      "loc": "net/ipv4/route.c:2309",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_flow",
        "net/ipv4/route.c:ipv4_sk_redirect",
        "net/ipv4/route.c:ipv4_redirect",
        "net/ipv4/route.c:ipv4_update_pmtu",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588176608,
      "name": "ip_route_output_key_hash",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct rtable * ip_route_output_key_hash(struct net * net, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "ip_route_output_key_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588360704,
      "name": "ip_route_output_key_hash",
      "external": true,
      "loc": "net/ipv4/route.c:2311",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_flow",
        "net/ipv4/route.c:ipv4_sk_redirect",
        "net/ipv4/route.c:ipv4_redirect",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ipv4_update_pmtu",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588360704,
      "name": "ip_route_output_key_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
struct rtable * ip_route_output_key_hash(struct net * net, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "ip_route_output_key_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588763536,
      "name": "ip_route_output_key_hash",
      "external": true,
      "loc": "net/ipv4/route.c:2438",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_flow",
        "net/ipv4/route.c:ipv4_sk_redirect",
        "net/ipv4/route.c:ipv4_redirect",
        "net/ipv4/route.c:ipv4_update_pmtu",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588763536,
      "name": "ip_route_output_key_hash",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct rtable * ip_route_output_key_hash(struct net * net, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "ip_route_output_key_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588987296,
      "name": "ip_route_output_key_hash",
      "external": true,
      "loc": "net/ipv4/route.c:2442",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_flow",
        "net/ipv4/route.c:ipv4_sk_redirect",
        "net/ipv4/route.c:ipv4_redirect",
        "net/ipv4/route.c:ipv4_update_pmtu",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588987296,
      "name": "ip_route_output_key_hash",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct rtable * ip_route_output_key_hash(struct net * net, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "ip_route_output_key_hash",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589947947,
      "name": "ip_route_output_key_hash",
      "external": true,
      "loc": "net/ipv4/route.c:2483",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_output_flow"
      ],
      "caller_func": [
        "net/ipv4/route.c:ipv4_sk_redirect",
        "net/ipv4/route.c:ipv4_redirect",
        "net/ipv4/route.c:__ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ipv4_update_pmtu",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/af_inet.c:inet_sk_reselect_saddr",
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589945248,
      "name": "ip_route_output_key_hash",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct rtable * ip_route_output_key_hash(struct net * net, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "ip_route_output_key_hash",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589989085,
      "name": "ip_route_output_key_hash",
      "external": true,
      "loc": "net/ipv4/route.c:2489",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_output_flow"
      ],
      "caller_func": [
        "net/ipv4/route.c:ipv4_sk_redirect",
        "net/ipv4/route.c:ipv4_redirect",
        "net/ipv4/route.c:__ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ipv4_update_pmtu",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/af_inet.c:inet_sk_reselect_saddr",
        "net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589986352,
      "name": "ip_route_output_key_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct rtable * ip_route_output_key_hash(struct net * net, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "ip_route_output_key_hash",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589902861,
      "name": "ip_route_output_key_hash",
      "external": true,
      "loc": "net/ipv4/route.c:2490",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_output_flow"
      ],
      "caller_func": [
        "net/ipv4/route.c:ipv4_sk_redirect",
        "net/ipv4/route.c:ipv4_redirect",
        "net/ipv4/route.c:__ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ipv4_update_pmtu",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589900144,
      "name": "ip_route_output_key_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct rtable * ip_route_output_key_hash(struct net * net, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "ip_route_output_key_hash",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590668701,
      "name": "ip_route_output_key_hash",
      "external": true,
      "loc": "net/ipv4/route.c:2609",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_output_flow"
      ],
      "caller_func": [
        "net/ipv4/route.c:ipv4_sk_redirect",
        "net/ipv4/route.c:ipv4_redirect",
        "net/ipv4/route.c:__ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ipv4_update_pmtu",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590665904,
      "name": "ip_route_output_key_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct rtable * ip_route_output_key_hash(struct net * net, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "ip_route_output_key_hash",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592294920,
      "name": "ip_route_output_key_hash",
      "external": true,
      "loc": "net/ipv4/route.c:2637",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_output_flow"
      ],
      "caller_func": [
        "net/ipv4/route.c:ipv4_sk_redirect",
        "net/ipv4/route.c:ipv4_redirect",
        "net/ipv4/route.c:__ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ipv4_update_pmtu",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592291408,
      "name": "ip_route_output_key_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct rtable * ip_route_output_key_hash(struct net * net, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "ip_route_output_key_hash",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594130472,
      "name": "ip_route_output_key_hash",
      "external": true,
      "loc": "net/ipv4/route.c:2628",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_output_flow"
      ],
      "caller_func": [
        "net/ipv4/route.c:ipv4_sk_redirect",
        "net/ipv4/route.c:ipv4_redirect",
        "net/ipv4/route.c:__ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ipv4_update_pmtu",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/xfrm4_policy.c:xfrm4_dst_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594127152,
      "name": "ip_route_output_key_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct rtable * ip_route_output_key_hash(struct net * net, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "ip_route_output_key_hash",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594517464,
      "name": "ip_route_output_key_hash",
      "external": true,
      "loc": "net/ipv4/route.c:2626",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_output_flow"
      ],
      "caller_func": [
        "net/ipv4/route.c:ipv4_sk_redirect",
        "net/ipv4/route.c:ipv4_redirect",
        "net/ipv4/route.c:__ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ipv4_update_pmtu",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594514128,
      "name": "ip_route_output_key_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct rtable * ip_route_output_key_hash(struct net * net, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "ip_route_output_key_hash",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595320632,
      "name": "ip_route_output_key_hash",
      "external": true,
      "loc": "net/ipv4/route.c:2629",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_output_flow"
      ],
      "caller_func": [
        "net/ipv4/route.c:ipv4_sk_redirect",
        "net/ipv4/route.c:ipv4_redirect",
        "net/ipv4/route.c:__ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ipv4_update_pmtu",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595317280,
      "name": "ip_route_output_key_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct rtable * ip_route_output_key_hash(struct net * net, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "ip_route_output_key_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502592056,
      "name": "ip_route_output_key_hash",
      "external": true,
      "loc": "net/ipv4/route.c:2442",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_flow",
        "net/ipv4/route.c:ipv4_sk_redirect",
        "net/ipv4/route.c:ipv4_redirect",
        "net/ipv4/route.c:ipv4_update_pmtu",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502592056,
      "name": "ip_route_output_key_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
struct rtable * ip_route_output_key_hash(struct net * net, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "ip_route_output_key_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235297628,
      "name": "ip_route_output_key_hash",
      "external": true,
      "loc": "net/ipv4/route.c:2442",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_flow",
        "net/ipv4/route.c:ipv4_sk_redirect",
        "net/ipv4/route.c:ipv4_redirect",
        "net/ipv4/route.c:__ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ipv4_update_pmtu",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235297628,
      "name": "ip_route_output_key_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
struct rtable * ip_route_output_key_hash(struct net * net, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "ip_route_output_key_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296181744,
      "name": "ip_route_output_key_hash",
      "external": true,
      "loc": "net/ipv4/route.c:2442",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_flow",
        "net/ipv4/route.c:ipv4_sk_redirect",
        "net/ipv4/route.c:ipv4_redirect",
        "net/ipv4/route.c:ipv4_update_pmtu",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296181744,
      "name": "ip_route_output_key_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
struct rtable * ip_route_output_key_hash(struct net * net, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "ip_route_output_key_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278745772,
      "name": "ip_route_output_key_hash",
      "external": true,
      "loc": "net/ipv4/route.c:2442",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_flow",
        "net/ipv4/route.c:ipv4_sk_redirect",
        "net/ipv4/route.c:ipv4_redirect",
        "net/ipv4/route.c:ipv4_update_pmtu",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278745772,
      "name": "ip_route_output_key_hash",
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
struct rtable * ip_route_output_key_hash(struct net * net, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "ip_route_output_key_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588593680,
      "name": "ip_route_output_key_hash",
      "external": true,
      "loc": "net/ipv4/route.c:2442",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_flow",
        "net/ipv4/route.c:ipv4_sk_redirect",
        "net/ipv4/route.c:ipv4_redirect",
        "net/ipv4/route.c:ipv4_update_pmtu",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588593680,
      "name": "ip_route_output_key_hash",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct rtable * ip_route_output_key_hash(struct net * net, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "ip_route_output_key_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588305664,
      "name": "ip_route_output_key_hash",
      "external": true,
      "loc": "net/ipv4/route.c:2442",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_flow",
        "net/ipv4/route.c:ipv4_sk_redirect",
        "net/ipv4/route.c:ipv4_redirect",
        "net/ipv4/route.c:ipv4_update_pmtu",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588305664,
      "name": "ip_route_output_key_hash",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct rtable * ip_route_output_key_hash(struct net * net, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "ip_route_output_key_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589029856,
      "name": "ip_route_output_key_hash",
      "external": true,
      "loc": "net/ipv4/route.c:2442",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_flow",
        "net/ipv4/route.c:ipv4_sk_redirect",
        "net/ipv4/route.c:ipv4_redirect",
        "net/ipv4/route.c:ipv4_update_pmtu",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589029856,
      "name": "ip_route_output_key_hash",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct rtable * ip_route_output_key_hash(struct net * net, struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "ip_route_output_key_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589068832,
      "name": "ip_route_output_key_hash",
      "external": true,
      "loc": "net/ipv4/route.c:2442",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_flow",
        "net/ipv4/route.c:ipv4_sk_redirect",
        "net/ipv4/route.c:ipv4_redirect",
        "net/ipv4/route.c:ipv4_update_pmtu",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589068832,
      "name": "ip_route_output_key_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
struct rtable * ip_route_output_key_hash(struct net * net, struct flowi4 * fl4, const struct sk_buff * skb)
```
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
