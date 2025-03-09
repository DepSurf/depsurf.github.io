# Function: <code>__inet6_lookup_established</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct sock * __inet6_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const u16 hnum, const int dif)
```

```json
{
  "name": "__inet6_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587241456,
      "name": "__inet6_lookup_established",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:51",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587241456,
      "name": "__inet6_lookup_established",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct sock * __inet6_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const u16 hnum, const int dif)
```

```json
{
  "name": "__inet6_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587705184,
      "name": "__inet6_lookup_established",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:53",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587705184,
      "name": "__inet6_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
struct sock * __inet6_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const u16 hnum, const int dif)
```

```json
{
  "name": "__inet6_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587919744,
      "name": "__inet6_lookup_established",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:53",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587919744,
      "name": "__inet6_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
struct sock * __inet6_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const u16 hnum, const int dif)
```

```json
{
  "name": "__inet6_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588077696,
      "name": "__inet6_lookup_established",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:53",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588077696,
      "name": "__inet6_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
struct sock * __inet6_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet6_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588621984,
      "name": "__inet6_lookup_established",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:53",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588621984,
      "name": "__inet6_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 454
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
struct sock * __inet6_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet6_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588987952,
      "name": "__inet6_lookup_established",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:53",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588987952,
      "name": "__inet6_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 454
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
struct sock * __inet6_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet6_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589212176,
      "name": "__inet6_lookup_established",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:53",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589212176,
      "name": "__inet6_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
struct sock * __inet6_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet6_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589666208,
      "name": "__inet6_lookup_established",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:49",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589666208,
      "name": "__inet6_lookup_established",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct sock * __inet6_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet6_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589890464,
      "name": "__inet6_lookup_established",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:49",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589890464,
      "name": "__inet6_lookup_established",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct sock * __inet6_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet6_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590920160,
      "name": "__inet6_lookup_established",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:49",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590920160,
      "name": "__inet6_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
struct sock * __inet6_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet6_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590983744,
      "name": "__inet6_lookup_established",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:51",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590983744,
      "name": "__inet6_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
struct sock * __inet6_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet6_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590914400,
      "name": "__inet6_lookup_established",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:51",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590914400,
      "name": "__inet6_lookup_established",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct sock * __inet6_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet6_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591750192,
      "name": "__inet6_lookup_established",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:51",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591750192,
      "name": "__inet6_lookup_established",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct sock * __inet6_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet6_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593456512,
      "name": "__inet6_lookup_established",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:51",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_early_demux",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593456512,
      "name": "__inet6_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 514
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
struct sock * __inet6_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet6_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595373632,
      "name": "__inet6_lookup_established",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:49",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_early_demux",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595373632,
      "name": "__inet6_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 514
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
struct sock * __inet6_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet6_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595770512,
      "name": "__inet6_lookup_established",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:49",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_early_demux",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595770512,
      "name": "__inet6_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 497
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
struct sock * __inet6_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet6_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596618752,
      "name": "__inet6_lookup_established",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:50",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_early_demux",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:__inet6_lookup_skb",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596618752,
      "name": "__inet6_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 497
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
struct sock * __inet6_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet6_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503612928,
      "name": "__inet6_lookup_established",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:49",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503612928,
      "name": "__inet6_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
struct sock * __inet6_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet6_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236256620,
      "name": "__inet6_lookup_established",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:49",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236256620,
      "name": "__inet6_lookup_established",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct sock * __inet6_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet6_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297426528,
      "name": "__inet6_lookup_established",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:49",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297426528,
      "name": "__inet6_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 676
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
struct sock * __inet6_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet6_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279563700,
      "name": "__inet6_lookup_established",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:49",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279563700,
      "name": "__inet6_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
struct sock * __inet6_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet6_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589494832,
      "name": "__inet6_lookup_established",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:49",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589494832,
      "name": "__inet6_lookup_established",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct sock * __inet6_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet6_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589219824,
      "name": "__inet6_lookup_established",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:49",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589219824,
      "name": "__inet6_lookup_established",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct sock * __inet6_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet6_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589936096,
      "name": "__inet6_lookup_established",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:49",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589936096,
      "name": "__inet6_lookup_established",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct sock * __inet6_lookup_established(struct net * net, struct inet_hashinfo * hashinfo, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const u16 hnum, const int dif, const int sdif)
```

```json
{
  "name": "__inet6_lookup_established",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589985584,
      "name": "__inet6_lookup_established",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:49",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589985584,
      "name": "__inet6_lookup_established",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
