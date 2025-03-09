# Function: <code>__udp4_lib_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct sock * __udp4_lib_lookup(struct net * net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, struct udp_table * udptable)
```

```json
{
  "name": "__udp4_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586746368,
      "name": "__udp4_lib_lookup",
      "external": true,
      "loc": "net/ipv4/udp.c:495",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp4_lib_lookup",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586746368,
      "name": "__udp4_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1092
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
struct sock * __udp4_lib_lookup(struct net * net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp4_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587194896,
      "name": "__udp4_lib_lookup",
      "external": true,
      "loc": "net/ipv4/udp.c:491",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:udp4_lib_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587194896,
      "name": "__udp4_lib_lookup",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct sock * __udp4_lib_lookup(struct net * net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp4_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587395440,
      "name": "__udp4_lib_lookup",
      "external": true,
      "loc": "net/ipv4/udp.c:492",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:udp4_lib_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587395440,
      "name": "__udp4_lib_lookup",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct sock * __udp4_lib_lookup(struct net * net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp4_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587532512,
      "name": "__udp4_lib_lookup",
      "external": true,
      "loc": "net/ipv4/udp.c:479",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:udp4_lib_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587532512,
      "name": "__udp4_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 813
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
struct sock * __udp4_lib_lookup(struct net * net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp4_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588055360,
      "name": "__udp4_lib_lookup",
      "external": true,
      "loc": "net/ipv4/udp.c:482",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:udp4_lib_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588055360,
      "name": "__udp4_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 827
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
struct sock * __udp4_lib_lookup(struct net * net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp4_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588408064,
      "name": "__udp4_lib_lookup",
      "external": true,
      "loc": "net/ipv4/udp.c:463",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:udp4_lib_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588408064,
      "name": "__udp4_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 729
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
struct sock * __udp4_lib_lookup(struct net * net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp4_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588594528,
      "name": "__udp4_lib_lookup",
      "external": true,
      "loc": "net/ipv4/udp.c:460",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:udp4_lib_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588594528,
      "name": "__udp4_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
struct sock * __udp4_lib_lookup(struct net * net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp4_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589005696,
      "name": "__udp4_lib_lookup",
      "external": true,
      "loc": "net/ipv4/udp.c:445",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:udp4_lib_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589005696,
      "name": "__udp4_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
struct sock * __udp4_lib_lookup(struct net * net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp4_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589230096,
      "name": "__udp4_lib_lookup",
      "external": true,
      "loc": "net/ipv4/udp.c:445",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:udp4_lib_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589230096,
      "name": "__udp4_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
struct sock * __udp4_lib_lookup(struct net * net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp4_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590197488,
      "name": "__udp4_lib_lookup",
      "external": true,
      "loc": "net/ipv4/udp.c:451",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:__udp4_lib_err_encap",
        "net/ipv4/udp.c:udp4_lib_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590197488,
      "name": "__udp4_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
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
struct sock * __udp4_lib_lookup(struct net * net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp4_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590246752,
      "name": "__udp4_lib_lookup",
      "external": true,
      "loc": "net/ipv4/udp.c:484",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:__udp4_lib_err_encap",
        "net/ipv4/udp.c:udp4_lib_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup_skb",
        "net/ipv4/udp_offload.c:udp4_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590246752,
      "name": "__udp4_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 630
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
struct sock * __udp4_lib_lookup(struct net * net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp4_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590160464,
      "name": "__udp4_lib_lookup",
      "external": true,
      "loc": "net/ipv4/udp.c:484",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:udp4_lib_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup_skb",
        "net/ipv4/udp_offload.c:udp4_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590160464,
      "name": "__udp4_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 654
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
struct sock * __udp4_lib_lookup(struct net * net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp4_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590941968,
      "name": "__udp4_lib_lookup",
      "external": true,
      "loc": "net/ipv4/udp.c:485",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:udp4_lib_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup_skb",
        "net/ipv4/udp_offload.c:udp4_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590941968,
      "name": "__udp4_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 649
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
struct sock * __udp4_lib_lookup(struct net * net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp4_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592591904,
      "name": "__udp4_lib_lookup",
      "external": true,
      "loc": "net/ipv4/udp.c:485",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:udp4_lib_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup_skb",
        "net/ipv4/udp_offload.c:udp4_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592591904,
      "name": "__udp4_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 657
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
struct sock * __udp4_lib_lookup(struct net * net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp4_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594455312,
      "name": "__udp4_lib_lookup",
      "external": true,
      "loc": "net/ipv4/udp.c:492",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:udp4_lib_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup_skb",
        "net/ipv4/udp_offload.c:udp4_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594455312,
      "name": "__udp4_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 657
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
struct sock * __udp4_lib_lookup(struct net * net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp4_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594846640,
      "name": "__udp4_lib_lookup",
      "external": true,
      "loc": "net/ipv4/udp.c:504",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:udp4_lib_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup_skb",
        "net/ipv4/udp_offload.c:udp4_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594846640,
      "name": "__udp4_lib_lookup",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct sock * __udp4_lib_lookup(struct net * net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp4_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595657664,
      "name": "__udp4_lib_lookup",
      "external": true,
      "loc": "net/ipv4/udp.c:472",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:udp4_lib_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup_skb",
        "net/ipv4/udp_offload.c:udp4_gro_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595657664,
      "name": "__udp4_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 466
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
struct sock * __udp4_lib_lookup(struct net * net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp4_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502849776,
      "name": "__udp4_lib_lookup",
      "external": true,
      "loc": "net/ipv4/udp.c:445",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:udp4_lib_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502849776,
      "name": "__udp4_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
struct sock * __udp4_lib_lookup(struct net * net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp4_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235559352,
      "name": "__udp4_lib_lookup",
      "external": true,
      "loc": "net/ipv4/udp.c:445",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:udp4_lib_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235559352,
      "name": "__udp4_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
struct sock * __udp4_lib_lookup(struct net * net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp4_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296518976,
      "name": "__udp4_lib_lookup",
      "external": true,
      "loc": "net/ipv4/udp.c:445",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:udp4_lib_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup_skb",
        "net/ipv4/udp.c:udp4_lib_lookup_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296518976,
      "name": "__udp4_lib_lookup",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct sock * __udp4_lib_lookup(struct net * net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp4_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278962598,
      "name": "__udp4_lib_lookup",
      "external": true,
      "loc": "net/ipv4/udp.c:445",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:udp4_lib_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278962598,
      "name": "__udp4_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 486
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
struct sock * __udp4_lib_lookup(struct net * net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp4_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588836480,
      "name": "__udp4_lib_lookup",
      "external": true,
      "loc": "net/ipv4/udp.c:445",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:udp4_lib_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588836480,
      "name": "__udp4_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
struct sock * __udp4_lib_lookup(struct net * net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp4_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588548416,
      "name": "__udp4_lib_lookup",
      "external": true,
      "loc": "net/ipv4/udp.c:445",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:udp4_lib_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588548416,
      "name": "__udp4_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
struct sock * __udp4_lib_lookup(struct net * net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp4_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589272656,
      "name": "__udp4_lib_lookup",
      "external": true,
      "loc": "net/ipv4/udp.c:445",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:udp4_lib_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589272656,
      "name": "__udp4_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
struct sock * __udp4_lib_lookup(struct net * net, __be32 saddr, __be16 sport, __be32 daddr, __be16 dport, int dif, int sdif, struct udp_table * udptable, struct sk_buff * skb)
```

```json
{
  "name": "__udp4_lib_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589319776,
      "name": "__udp4_lib_lookup",
      "external": true,
      "loc": "net/ipv4/udp.c:445",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:__udp4_lib_err",
        "net/ipv4/udp.c:udp4_lib_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589319776,
      "name": "__udp4_lib_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
