# Function: <code>inet6_lookup_listener</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct sock * inet6_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif)
```

```json
{
  "name": "inet6_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587241872,
      "name": "inet6_lookup_listener",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:123",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587241872,
      "name": "inet6_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 726
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
struct sock * inet6_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif)
```

```json
{
  "name": "inet6_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587705600,
      "name": "inet6_lookup_listener",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:124",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587705600,
      "name": "inet6_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 461
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
struct sock * inet6_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif)
```

```json
{
  "name": "inet6_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587920160,
      "name": "inet6_lookup_listener",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:124",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587920160,
      "name": "inet6_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
struct sock * inet6_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif)
```

```json
{
  "name": "inet6_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588078096,
      "name": "inet6_lookup_listener",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:124",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588078096,
      "name": "inet6_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 451
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
struct sock * inet6_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet6_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588622448,
      "name": "inet6_lookup_listener",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:128",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588622448,
      "name": "inet6_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
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
struct sock * inet6_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet6_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588988816,
      "name": "inet6_lookup_listener",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:162",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588988816,
      "name": "inet6_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1275
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
struct sock * inet6_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet6_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589212976,
      "name": "inet6_lookup_listener",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:153",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589212976,
      "name": "inet6_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 796
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
struct sock * inet6_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet6_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589666944,
      "name": "inet6_lookup_listener",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:149",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589666944,
      "name": "inet6_lookup_listener",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct sock * inet6_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet6_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589891200,
      "name": "inet6_lookup_listener",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:149",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589891200,
      "name": "inet6_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 755
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
struct sock * inet6_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet6_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590921728,
      "name": "inet6_lookup_listener",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:149",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590921728,
      "name": "inet6_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
struct sock * inet6_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet6_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590985312,
      "name": "inet6_lookup_listener",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:187",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590985312,
      "name": "inet6_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 491
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
struct sock * inet6_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet6_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590915952,
      "name": "inet6_lookup_listener",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:187",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590915952,
      "name": "inet6_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 485
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
struct sock * inet6_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet6_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591751744,
      "name": "inet6_lookup_listener",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:187",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591751744,
      "name": "inet6_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 481
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
struct sock * inet6_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet6_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593458224,
      "name": "inet6_lookup_listener",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:186",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593458224,
      "name": "inet6_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 508
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
struct sock * inet6_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet6_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595375392,
      "name": "inet6_lookup_listener",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:184",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595375392,
      "name": "inet6_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 507
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
struct sock * inet6_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet6_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595772288,
      "name": "inet6_lookup_listener",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:184",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595772288,
      "name": "inet6_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 966
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
struct sock * inet6_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet6_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596620928,
      "name": "inet6_lookup_listener",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:203",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:__inet6_lookup_skb",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596620928,
      "name": "inet6_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 930
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
struct sock * inet6_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet6_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503613824,
      "name": "inet6_lookup_listener",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:149",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503613824,
      "name": "inet6_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1012
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
struct sock * inet6_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet6_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236257648,
      "name": "inet6_lookup_listener",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:149",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236257648,
      "name": "inet6_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 960
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
struct sock * inet6_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet6_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297427760,
      "name": "inet6_lookup_listener",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:149",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297427760,
      "name": "inet6_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1000
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
struct sock * inet6_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet6_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279564582,
      "name": "inet6_lookup_listener",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:149",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279564582,
      "name": "inet6_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1320
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
struct sock * inet6_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet6_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589495568,
      "name": "inet6_lookup_listener",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:149",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589495568,
      "name": "inet6_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 755
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
struct sock * inet6_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet6_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589220560,
      "name": "inet6_lookup_listener",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:149",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589220560,
      "name": "inet6_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 755
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
struct sock * inet6_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet6_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589936832,
      "name": "inet6_lookup_listener",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:149",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589936832,
      "name": "inet6_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 755
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
struct sock * inet6_lookup_listener(struct net * net, struct inet_hashinfo * hashinfo, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet6_lookup_listener",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589986320,
      "name": "inet6_lookup_listener",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:149",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_lookup",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/inet6_hashtables.c:inet6_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589986320,
      "name": "inet6_lookup_listener",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 755
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
