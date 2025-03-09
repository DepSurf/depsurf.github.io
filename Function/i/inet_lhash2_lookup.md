# Function: <code>inet_lhash2_lookup</code>

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
struct sock * inet_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588223520,
      "name": "inet_lhash2_lookup",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:265",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588223520,
      "name": "inet_lhash2_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
struct sock * inet_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588410880,
      "name": "inet_lhash2_lookup",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:261",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588410880,
      "name": "inet_lhash2_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
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
struct sock * inet_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588814688,
      "name": "inet_lhash2_lookup",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:257",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588814688,
      "name": "inet_lhash2_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
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
struct sock * inet_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589038016,
      "name": "inet_lhash2_lookup",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:257",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589038016,
      "name": "inet_lhash2_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
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
  "name": "inet_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589999568,
      "name": "inet_lhash2_lookup",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:258",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589999568,
      "name": "inet_lhash2_lookup.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
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
  "name": "inet_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590041856,
      "name": "inet_lhash2_lookup",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:276",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590041856,
      "name": "inet_lhash2_lookup.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
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
  "name": "inet_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589956032,
      "name": "inet_lhash2_lookup",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:276",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589956032,
      "name": "inet_lhash2_lookup.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
struct sock * inet_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590723232,
      "name": "inet_lhash2_lookup",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:278",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590723232,
      "name": "inet_lhash2_lookup",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct sock * inet_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592353216,
      "name": "inet_lhash2_lookup",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:242",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592353216,
      "name": "inet_lhash2_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
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
struct sock * inet_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594192800,
      "name": "inet_lhash2_lookup",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:358",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594192800,
      "name": "inet_lhash2_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
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
struct sock * inet_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594579920,
      "name": "inet_lhash2_lookup",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:358",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594579920,
      "name": "inet_lhash2_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
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
struct sock * inet_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595383584,
      "name": "inet_lhash2_lookup",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:378",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595383584,
      "name": "inet_lhash2_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
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
struct sock * inet_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502647832,
      "name": "inet_lhash2_lookup",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:257",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502647832,
      "name": "inet_lhash2_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
struct sock * inet_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235352284,
      "name": "inet_lhash2_lookup",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:257",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235352284,
      "name": "inet_lhash2_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
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
struct sock * inet_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296248848,
      "name": "inet_lhash2_lookup",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:257",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296248848,
      "name": "inet_lhash2_lookup",
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
struct sock * inet_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278788696,
      "name": "inet_lhash2_lookup",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:257",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278788696,
      "name": "inet_lhash2_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
struct sock * inet_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588644400,
      "name": "inet_lhash2_lookup",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:257",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588644400,
      "name": "inet_lhash2_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
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
struct sock * inet_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588356384,
      "name": "inet_lhash2_lookup",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:257",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588356384,
      "name": "inet_lhash2_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
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
struct sock * inet_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589080576,
      "name": "inet_lhash2_lookup",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:257",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589080576,
      "name": "inet_lhash2_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
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
struct sock * inet_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```

```json
{
  "name": "inet_lhash2_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589120208,
      "name": "inet_lhash2_lookup",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:257",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589120208,
      "name": "inet_lhash2_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
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
struct sock * inet_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
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
struct sock * inet_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
struct sock * inet_lhash2_lookup(struct net * net, struct inet_listen_hashbucket * ilb2, struct sk_buff * skb, int doff, const __be32 saddr, __be16 sport, const __be32 daddr, const short unsigned int hnum, const int dif, const int sdif)
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
