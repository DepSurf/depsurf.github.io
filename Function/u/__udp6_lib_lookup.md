# Function: <code>__udp6_lib_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct sock * __udp6_lib_lookup(struct net * net, const struct in6_addr * saddr, __be16 sport, const struct in6_addr * daddr, __be16 dport, int dif, struct udp_table * udptable)
```

```json
{
  "name": "__udp6_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587117456,
      "name": "__udp6_lib_lookup",
      "external": true,
      "loc": "net/ipv6/udp.c:287",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udp6_lib_lookup",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587117456,
      "name": "__udp6_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1042
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
struct sock * __udp6_lib_lookup(struct net * net, const struct in6_addr * saddr, __be16 sport, const struct in6_addr * daddr, __be16 dport, int dif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp6_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587568992,
      "name": "__udp6_lib_lookup",
      "external": true,
      "loc": "net/ipv6/udp.c:205",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587568992,
      "name": "__udp6_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 642
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
struct sock * __udp6_lib_lookup(struct net * net, const struct in6_addr * saddr, __be16 sport, const struct in6_addr * daddr, __be16 dport, int dif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp6_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587773216,
      "name": "__udp6_lib_lookup",
      "external": true,
      "loc": "net/ipv6/udp.c:205",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587773216,
      "name": "__udp6_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 642
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
struct sock * __udp6_lib_lookup(struct net * net, const struct in6_addr * saddr, __be16 sport, const struct in6_addr * daddr, __be16 dport, int dif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp6_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587929552,
      "name": "__udp6_lib_lookup",
      "external": true,
      "loc": "net/ipv6/udp.c:216",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587929552,
      "name": "__udp6_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 703
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
struct sock * __udp6_lib_lookup(struct net * net, const struct in6_addr * saddr, __be16 sport, const struct in6_addr * daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp6_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588464592,
      "name": "__udp6_lib_lookup",
      "external": true,
      "loc": "net/ipv6/udp.c:220",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588464592,
      "name": "__udp6_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 717
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
struct sock * __udp6_lib_lookup(struct net * net, const struct in6_addr * saddr, __be16 sport, const struct in6_addr * daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp6_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588828768,
      "name": "__udp6_lib_lookup",
      "external": true,
      "loc": "net/ipv6/udp.c:197",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588828768,
      "name": "__udp6_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1252
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
struct sock * __udp6_lib_lookup(struct net * net, const struct in6_addr * saddr, __be16 sport, const struct in6_addr * daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp6_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589051856,
      "name": "__udp6_lib_lookup",
      "external": true,
      "loc": "net/ipv6/udp.c:191",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589051856,
      "name": "__udp6_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 943
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
struct sock * __udp6_lib_lookup(struct net * net, const struct in6_addr * saddr, __be16 sport, const struct in6_addr * daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp6_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589505472,
      "name": "__udp6_lib_lookup",
      "external": true,
      "loc": "net/ipv6/udp.c:179",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589505472,
      "name": "__udp6_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 769
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
struct sock * __udp6_lib_lookup(struct net * net, const struct in6_addr * saddr, __be16 sport, const struct in6_addr * daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp6_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589729568,
      "name": "__udp6_lib_lookup",
      "external": true,
      "loc": "net/ipv6/udp.c:179",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589729568,
      "name": "__udp6_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 775
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
struct sock * __udp6_lib_lookup(struct net * net, const struct in6_addr * saddr, __be16 sport, const struct in6_addr * daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp6_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590748480,
      "name": "__udp6_lib_lookup",
      "external": true,
      "loc": "net/ipv6/udp.c:182",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err_encap",
        "net/ipv6/udp.c:udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590748480,
      "name": "__udp6_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
struct sock * __udp6_lib_lookup(struct net * net, const struct in6_addr * saddr, __be16 sport, const struct in6_addr * daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp6_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590807456,
      "name": "__udp6_lib_lookup",
      "external": true,
      "loc": "net/ipv6/udp.c:217",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err_encap",
        "net/ipv6/udp.c:udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup_skb",
        "net/ipv6/udp_offload.c:udp6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590807456,
      "name": "__udp6_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 516
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
struct sock * __udp6_lib_lookup(struct net * net, const struct in6_addr * saddr, __be16 sport, const struct in6_addr * daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp6_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590734480,
      "name": "__udp6_lib_lookup",
      "external": true,
      "loc": "net/ipv6/udp.c:217",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup_skb",
        "net/ipv6/udp_offload.c:udp6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590734480,
      "name": "__udp6_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 511
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
struct sock * __udp6_lib_lookup(struct net * net, const struct in6_addr * saddr, __be16 sport, const struct in6_addr * daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp6_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591543280,
      "name": "__udp6_lib_lookup",
      "external": true,
      "loc": "net/ipv6/udp.c:219",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup_skb",
        "net/ipv6/udp_offload.c:udp6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591543280,
      "name": "__udp6_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 506
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
struct sock * __udp6_lib_lookup(struct net * net, const struct in6_addr * saddr, __be16 sport, const struct in6_addr * daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp6_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593232880,
      "name": "__udp6_lib_lookup",
      "external": true,
      "loc": "net/ipv6/udp.c:221",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup_skb",
        "net/ipv6/udp_offload.c:udp6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593232880,
      "name": "__udp6_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
struct sock * __udp6_lib_lookup(struct net * net, const struct in6_addr * saddr, __be16 sport, const struct in6_addr * daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp6_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595133504,
      "name": "__udp6_lib_lookup",
      "external": true,
      "loc": "net/ipv6/udp.c:235",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup_skb",
        "net/ipv6/udp_offload.c:udp6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595133504,
      "name": "__udp6_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 563
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
struct sock * __udp6_lib_lookup(struct net * net, const struct in6_addr * saddr, __be16 sport, const struct in6_addr * daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp6_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595535504,
      "name": "__udp6_lib_lookup",
      "external": true,
      "loc": "net/ipv6/udp.c:246",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup_skb",
        "net/ipv6/udp_offload.c:udp6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595535504,
      "name": "__udp6_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 557
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
struct sock * __udp6_lib_lookup(struct net * net, const struct in6_addr * saddr, __be16 sport, const struct in6_addr * daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp6_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596379520,
      "name": "__udp6_lib_lookup",
      "external": true,
      "loc": "net/ipv6/udp.c:211",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup_skb",
        "net/ipv6/udp_offload.c:udp6_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596379520,
      "name": "__udp6_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 361
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
struct sock * __udp6_lib_lookup(struct net * net, const struct in6_addr * saddr, __be16 sport, const struct in6_addr * daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp6_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503412712,
      "name": "__udp6_lib_lookup",
      "external": true,
      "loc": "net/ipv6/udp.c:179",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503412712,
      "name": "__udp6_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1008
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
struct sock * __udp6_lib_lookup(struct net * net, const struct in6_addr * saddr, __be16 sport, const struct in6_addr * daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp6_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236083200,
      "name": "__udp6_lib_lookup",
      "external": true,
      "loc": "net/ipv6/udp.c:179",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236083200,
      "name": "__udp6_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 860
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
struct sock * __udp6_lib_lookup(struct net * net, const struct in6_addr * saddr, __be16 sport, const struct in6_addr * daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp6_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297200336,
      "name": "__udp6_lib_lookup",
      "external": true,
      "loc": "net/ipv6/udp.c:179",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup_skb",
        "net/ipv6/udp.c:udp6_lib_lookup_skb",
        "net/ipv6/udp.c:udp6_lib_lookup_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297200336,
      "name": "__udp6_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 968
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
struct sock * __udp6_lib_lookup(struct net * net, const struct in6_addr * saddr, __be16 sport, const struct in6_addr * daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp6_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279413762,
      "name": "__udp6_lib_lookup",
      "external": true,
      "loc": "net/ipv6/udp.c:179",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279413762,
      "name": "__udp6_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1276
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
struct sock * __udp6_lib_lookup(struct net * net, const struct in6_addr * saddr, __be16 sport, const struct in6_addr * daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp6_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589333936,
      "name": "__udp6_lib_lookup",
      "external": true,
      "loc": "net/ipv6/udp.c:179",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589333936,
      "name": "__udp6_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 775
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
struct sock * __udp6_lib_lookup(struct net * net, const struct in6_addr * saddr, __be16 sport, const struct in6_addr * daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp6_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589058928,
      "name": "__udp6_lib_lookup",
      "external": true,
      "loc": "net/ipv6/udp.c:179",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589058928,
      "name": "__udp6_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 775
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
struct sock * __udp6_lib_lookup(struct net * net, const struct in6_addr * saddr, __be16 sport, const struct in6_addr * daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp6_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589770800,
      "name": "__udp6_lib_lookup",
      "external": true,
      "loc": "net/ipv6/udp.c:179",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589770800,
      "name": "__udp6_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 775
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
struct sock * __udp6_lib_lookup(struct net * net, const struct in6_addr * saddr, __be16 sport, const struct in6_addr * daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp6_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589821504,
      "name": "__udp6_lib_lookup",
      "external": true,
      "loc": "net/ipv6/udp.c:179",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589821504,
      "name": "__udp6_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 775
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
<code>struct sk_buff * skb</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int sdif</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, saddr, sport, daddr, dport, dif, udptable, skb</code> ➡️ <code>net, saddr, sport, daddr, dport, dif, sdif, udptable, skb</code>
</li>
</ul>
</details>
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
