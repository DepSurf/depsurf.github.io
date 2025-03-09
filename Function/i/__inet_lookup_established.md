# Function: <code>__inet_lookup_established</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct sock * __inet_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif)
```

```json
{
  "name": "__inet_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586588768,
      "name": "__inet_lookup_established",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:283",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586588768,
      "name": "__inet_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
struct sock * __inet_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif)
```

```json
{
  "name": "__inet_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587030624,
      "name": "__inet_lookup_established",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:268",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587030624,
      "name": "__inet_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
struct sock * __inet_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif)
```

```json
{
  "name": "__inet_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587226736,
      "name": "__inet_lookup_established",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:270",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587226736,
      "name": "__inet_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
struct sock * __inet_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif)
```

```json
{
  "name": "__inet_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587358752,
      "name": "__inet_lookup_established",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:267",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587358752,
      "name": "__inet_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
struct sock * __inet_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587879424,
      "name": "__inet_lookup_established",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:272",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587879424,
      "name": "__inet_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
struct sock * __inet_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588223904,
      "name": "__inet_lookup_established",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:386",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588223904,
      "name": "__inet_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
struct sock * __inet_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588411216,
      "name": "__inet_lookup_established",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:350",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588411216,
      "name": "__inet_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
struct sock * __inet_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588815040,
      "name": "__inet_lookup_established",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:346",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588815040,
      "name": "__inet_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
struct sock * __inet_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589038368,
      "name": "__inet_lookup_established",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:346",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589038368,
      "name": "__inet_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
struct sock * __inet_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589999232,
      "name": "__inet_lookup_established",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:347",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589999232,
      "name": "__inet_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
struct sock * __inet_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590041520,
      "name": "__inet_lookup_established",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:390",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590041520,
      "name": "__inet_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
struct sock * __inet_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589955712,
      "name": "__inet_lookup_established",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:390",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589955712,
      "name": "__inet_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
struct sock * __inet_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590722912,
      "name": "__inet_lookup_established",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:392",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590722912,
      "name": "__inet_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
struct sock * __inet_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592352048,
      "name": "__inet_lookup_established",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:355",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592352048,
      "name": "__inet_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 433
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
struct sock * __inet_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594191600,
      "name": "__inet_lookup_established",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:471",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594191600,
      "name": "__inet_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 433
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
struct sock * __inet_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594578704,
      "name": "__inet_lookup_established",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:471",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594578704,
      "name": "__inet_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 429
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
struct sock * __inet_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595382368,
      "name": "__inet_lookup_established",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:492",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:__inet_lookup_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595382368,
      "name": "__inet_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 429
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
struct sock * __inet_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502648232,
      "name": "__inet_lookup_established",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:346",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502648232,
      "name": "__inet_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
struct sock * __inet_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235352652,
      "name": "__inet_lookup_established",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:346",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235352652,
      "name": "__inet_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
struct sock * __inet_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296249392,
      "name": "__inet_lookup_established",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:346",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296249392,
      "name": "__inet_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 536
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
struct sock * __inet_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278788980,
      "name": "__inet_lookup_established",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:346",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278788980,
      "name": "__inet_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
struct sock * __inet_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588644752,
      "name": "__inet_lookup_established",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:346",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588644752,
      "name": "__inet_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
struct sock * __inet_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588356736,
      "name": "__inet_lookup_established",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:346",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588356736,
      "name": "__inet_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
struct sock * __inet_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589080928,
      "name": "__inet_lookup_established",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:346",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589080928,
      "name": "__inet_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
struct sock * __inet_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589120560,
      "name": "__inet_lookup_established",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:346",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_early_demux",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589120560,
      "name": "__inet_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
