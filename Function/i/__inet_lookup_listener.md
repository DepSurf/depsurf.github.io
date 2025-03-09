# Function: <code>__inet_lookup_listener</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct sock * __inet_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif)
```

```json
{
  "name": "__inet_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586587840,
      "name": "__inet_lookup_listener",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:206",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586587840,
      "name": "__inet_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 692
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
struct sock * __inet_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif)
```

```json
{
  "name": "__inet_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587029760,
      "name": "__inet_lookup_listener",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:208",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587029760,
      "name": "__inet_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
struct sock * __inet_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif)
```

```json
{
  "name": "__inet_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587225760,
      "name": "__inet_lookup_listener",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:209",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587225760,
      "name": "__inet_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
struct sock * __inet_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif)
```

```json
{
  "name": "__inet_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587357904,
      "name": "__inet_lookup_listener",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:206",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587357904,
      "name": "__inet_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 427
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
struct sock * __inet_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587877840,
      "name": "__inet_lookup_listener",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:210",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587877840,
      "name": "__inet_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
struct sock * __inet_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588224928,
      "name": "__inet_lookup_listener",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:299",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588224928,
      "name": "__inet_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 760
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
struct sock * __inet_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588411808,
      "name": "__inet_lookup_listener",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:295",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588411808,
      "name": "__inet_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
struct sock * __inet_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588815552,
      "name": "__inet_lookup_listener",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:291",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588815552,
      "name": "__inet_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
struct sock * __inet_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589038880,
      "name": "__inet_lookup_listener",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:291",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589038880,
      "name": "__inet_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
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
struct sock * __inet_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589999936,
      "name": "__inet_lookup_listener",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:292",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589999936,
      "name": "__inet_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
struct sock * __inet_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590042224,
      "name": "__inet_lookup_listener",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:327",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590042224,
      "name": "__inet_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 626
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
struct sock * __inet_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589956400,
      "name": "__inet_lookup_listener",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:327",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589956400,
      "name": "__inet_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
struct sock * __inet_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590723600,
      "name": "__inet_lookup_listener",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:329",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590723600,
      "name": "__inet_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
struct sock * __inet_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592353568,
      "name": "__inet_lookup_listener",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:292",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592353568,
      "name": "__inet_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 624
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
struct sock * __inet_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594193168,
      "name": "__inet_lookup_listener",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:408",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594193168,
      "name": "__inet_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 624
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
struct sock * __inet_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594580304,
      "name": "__inet_lookup_listener",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:408",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594580304,
      "name": "__inet_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 616
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
struct sock * __inet_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595386432,
      "name": "__inet_lookup_listener",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:427",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset",
        "net/ipv4/tcp_ipv4.c:__inet_lookup_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595386432,
      "name": "__inet_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
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
struct sock * __inet_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502648600,
      "name": "__inet_lookup_listener",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:291",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502648600,
      "name": "__inet_lookup_listener",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct sock * __inet_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235353756,
      "name": "__inet_lookup_listener",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:291",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235353756,
      "name": "__inet_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
struct sock * __inet_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296250896,
      "name": "__inet_lookup_listener",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:291",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296250896,
      "name": "__inet_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
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
struct sock * __inet_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278789522,
      "name": "__inet_lookup_listener",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:291",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278789522,
      "name": "__inet_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 474
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
struct sock * __inet_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588645264,
      "name": "__inet_lookup_listener",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:291",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588645264,
      "name": "__inet_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
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
struct sock * __inet_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588357248,
      "name": "__inet_lookup_listener",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:291",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588357248,
      "name": "__inet_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
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
struct sock * __inet_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589081440,
      "name": "__inet_lookup_listener",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:291",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589081440,
      "name": "__inet_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
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
struct sock * __inet_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589121584,
      "name": "__inet_lookup_listener",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:291",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589121584,
      "name": "__inet_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
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
<li>
<b>Param added. </b>
<code>int doff</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, hashinfo, saddr, sport, daddr, hnum, dif</code> ➡️ <code>net, hashinfo, skb, doff, saddr, sport, daddr, hnum, dif</code>
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
<code>const int sdif</code>
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
