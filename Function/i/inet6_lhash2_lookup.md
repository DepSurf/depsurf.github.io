# Function: <code>inet6_lhash2_lookup</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct sock * inet6_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet6_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588988416,
      "name": "inet6_lhash2_lookup",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:128",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588988416,
      "name": "inet6_lhash2_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
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
struct sock * inet6_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet6_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589212640,
      "name": "inet6_lhash2_lookup",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:119",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589212640,
      "name": "inet6_lhash2_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
struct sock * inet6_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet6_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589666592,
      "name": "inet6_lhash2_lookup",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:115",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589666592,
      "name": "inet6_lhash2_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
struct sock * inet6_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet6_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589890848,
      "name": "inet6_lhash2_lookup",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:115",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589890848,
      "name": "inet6_lhash2_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inet6_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590921376,
      "name": "inet6_lhash2_lookup",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:115",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590921376,
      "name": "inet6_lhash2_lookup.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inet6_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590984944,
      "name": "inet6_lhash2_lookup",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:134",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590984944,
      "name": "inet6_lhash2_lookup.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inet6_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590915584,
      "name": "inet6_lhash2_lookup",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:134",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590915584,
      "name": "inet6_lhash2_lookup.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
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
struct sock * inet6_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet6_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591751376,
      "name": "inet6_lhash2_lookup",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:134",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591751376,
      "name": "inet6_lhash2_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 365
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
struct sock * inet6_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet6_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593457856,
      "name": "inet6_lhash2_lookup",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:134",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593457856,
      "name": "inet6_lhash2_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
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
struct sock * inet6_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet6_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595375008,
      "name": "inet6_lhash2_lookup",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:132",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595375008,
      "name": "inet6_lhash2_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
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
struct sock * inet6_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet6_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595771904,
      "name": "inet6_lhash2_lookup",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:132",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595771904,
      "name": "inet6_lhash2_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
struct sock * inet6_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet6_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596620560,
      "name": "inet6_lhash2_lookup",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:151",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596620560,
      "name": "inet6_lhash2_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
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
struct sock * inet6_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet6_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503613416,
      "name": "inet6_lhash2_lookup",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:115",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503613416,
      "name": "inet6_lhash2_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
struct sock * inet6_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet6_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236257236,
      "name": "inet6_lhash2_lookup",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:115",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236257236,
      "name": "inet6_lhash2_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
struct sock * inet6_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet6_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297427216,
      "name": "inet6_lhash2_lookup",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:115",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297427216,
      "name": "inet6_lhash2_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
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
struct sock * inet6_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet6_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279564264,
      "name": "inet6_lhash2_lookup",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:115",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279564264,
      "name": "inet6_lhash2_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
struct sock * inet6_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet6_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589495216,
      "name": "inet6_lhash2_lookup",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:115",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589495216,
      "name": "inet6_lhash2_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
struct sock * inet6_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet6_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589220208,
      "name": "inet6_lhash2_lookup",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:115",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589220208,
      "name": "inet6_lhash2_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
struct sock * inet6_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet6_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589936480,
      "name": "inet6_lhash2_lookup",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:115",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589936480,
      "name": "inet6_lhash2_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
struct sock * inet6_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet6_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589985968,
      "name": "inet6_lhash2_lookup",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:115",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589985968,
      "name": "inet6_lhash2_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct sock * inet6_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct sock * inet6_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
struct sock * inet6_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const struct in6_addr * saddr, const __be16 sport, const struct in6_addr * daddr, const short unsigned int hnum, const int dif, const int sdif)
```
</details>
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
