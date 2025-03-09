# Function: <code>reuseport_select_sock</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct sock * reuseport_select_sock(struct sock * sk, u32 hash, struct sk_buff * skb, int hdr_len)
```

```json
{
  "name": "reuseport_select_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586840512,
      "name": "reuseport_select_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:207",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/udp.c:__udp4_lib_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586840512,
      "name": "reuseport_select_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 700
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
struct sock * reuseport_select_sock(struct sock * sk, u32 hash, struct sk_buff * skb, int hdr_len)
```

```json
{
  "name": "reuseport_select_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587031440,
      "name": "reuseport_select_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:206",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/udp.c:__udp4_lib_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587031440,
      "name": "reuseport_select_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 700
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
struct sock * reuseport_select_sock(struct sock * sk, u32 hash, struct sk_buff * skb, int hdr_len)
```

```json
{
  "name": "reuseport_select_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587159600,
      "name": "reuseport_select_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:206",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/udp.c:__udp4_lib_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587159600,
      "name": "reuseport_select_sock",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct sock * reuseport_select_sock(struct sock * sk, u32 hash, struct sk_buff * skb, int hdr_len)
```

```json
{
  "name": "reuseport_select_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587668080,
      "name": "reuseport_select_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:218",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/udp.c:__udp4_lib_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587668080,
      "name": "reuseport_select_sock",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct sock * reuseport_select_sock(struct sock * sk, u32 hash, struct sk_buff * skb, int hdr_len)
```

```json
{
  "name": "reuseport_select_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587994960,
      "name": "reuseport_select_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:218",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup",
        "net/ipv4/udp.c:__udp4_lib_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587994960,
      "name": "reuseport_select_sock",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct sock * reuseport_select_sock(struct sock * sk, u32 hash, struct sk_buff * skb, int hdr_len)
```

```json
{
  "name": "reuseport_select_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588154080,
      "name": "reuseport_select_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:263",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588154080,
      "name": "reuseport_select_sock",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct sock * reuseport_select_sock(struct sock * sk, u32 hash, struct sk_buff * skb, int hdr_len)
```

```json
{
  "name": "reuseport_select_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588475264,
      "name": "reuseport_select_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:265",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588475264,
      "name": "reuseport_select_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 674
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
struct sock * reuseport_select_sock(struct sock * sk, u32 hash, struct sk_buff * skb, int hdr_len)
```

```json
{
  "name": "reuseport_select_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588680688,
      "name": "reuseport_select_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:265",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588680688,
      "name": "reuseport_select_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 674
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
struct sock * reuseport_select_sock(struct sock * sk, u32 hash, struct sk_buff * skb, int hdr_len)
```

```json
{
  "name": "reuseport_select_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589546944,
      "name": "reuseport_select_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:257",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589546944,
      "name": "reuseport_select_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
struct sock * reuseport_select_sock(struct sock * sk, u32 hash, struct sk_buff * skb, int hdr_len)
```

```json
{
  "name": "reuseport_select_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589555984,
      "name": "reuseport_select_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:257",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/udp.c:__udp4_lib_lookup",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589555984,
      "name": "reuseport_select_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
struct sock * reuseport_select_sock(struct sock * sk, u32 hash, struct sk_buff * skb, int hdr_len)
```

```json
{
  "name": "reuseport_select_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589453936,
      "name": "reuseport_select_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:257",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/udp.c:__udp4_lib_lookup",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589453936,
      "name": "reuseport_select_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
struct sock * reuseport_select_sock(struct sock * sk, u32 hash, struct sk_buff * skb, int hdr_len)
```

```json
{
  "name": "reuseport_select_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590190256,
      "name": "reuseport_select_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:469",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup",
        "net/ipv4/udp.c:__udp4_lib_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590190256,
      "name": "reuseport_select_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
struct sock * reuseport_select_sock(struct sock * sk, u32 hash, struct sk_buff * skb, int hdr_len)
```

```json
{
  "name": "reuseport_select_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591753056,
      "name": "reuseport_select_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:469",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup",
        "net/ipv4/udp.c:__udp4_lib_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591753056,
      "name": "reuseport_select_sock",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct sock * reuseport_select_sock(struct sock * sk, u32 hash, struct sk_buff * skb, int hdr_len)
```

```json
{
  "name": "reuseport_select_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593542896,
      "name": "reuseport_select_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:569",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup",
        "net/ipv4/udp.c:__udp4_lib_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593542896,
      "name": "reuseport_select_sock",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct sock * reuseport_select_sock(struct sock * sk, u32 hash, struct sk_buff * skb, int hdr_len)
```

```json
{
  "name": "reuseport_select_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594011968,
      "name": "reuseport_select_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:569",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup",
        "net/ipv4/udp.c:__udp4_lib_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594011968,
      "name": "reuseport_select_sock",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct sock * reuseport_select_sock(struct sock * sk, u32 hash, struct sk_buff * skb, int hdr_len)
```

```json
{
  "name": "reuseport_select_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594798336,
      "name": "reuseport_select_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:569",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup",
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594798336,
      "name": "reuseport_select_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
struct sock * reuseport_select_sock(struct sock * sk, u32 hash, struct sk_buff * skb, int hdr_len)
```

```json
{
  "name": "reuseport_select_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502234208,
      "name": "reuseport_select_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:265",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502234208,
      "name": "reuseport_select_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 672
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
struct sock * reuseport_select_sock(struct sock * sk, u32 hash, struct sk_buff * skb, int hdr_len)
```

```json
{
  "name": "reuseport_select_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234980128,
      "name": "reuseport_select_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:265",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234980128,
      "name": "reuseport_select_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 788
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
struct sock * reuseport_select_sock(struct sock * sk, u32 hash, struct sk_buff * skb, int hdr_len)
```

```json
{
  "name": "reuseport_select_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295725072,
      "name": "reuseport_select_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:265",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295725072,
      "name": "reuseport_select_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1024
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
struct sock * reuseport_select_sock(struct sock * sk, u32 hash, struct sk_buff * skb, int hdr_len)
```

```json
{
  "name": "reuseport_select_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278477018,
      "name": "reuseport_select_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:265",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278477018,
      "name": "reuseport_select_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 586
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
struct sock * reuseport_select_sock(struct sock * sk, u32 hash, struct sk_buff * skb, int hdr_len)
```

```json
{
  "name": "reuseport_select_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588287424,
      "name": "reuseport_select_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:265",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588287424,
      "name": "reuseport_select_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 674
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
struct sock * reuseport_select_sock(struct sock * sk, u32 hash, struct sk_buff * skb, int hdr_len)
```

```json
{
  "name": "reuseport_select_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588000240,
      "name": "reuseport_select_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:265",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588000240,
      "name": "reuseport_select_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 674
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
struct sock * reuseport_select_sock(struct sock * sk, u32 hash, struct sk_buff * skb, int hdr_len)
```

```json
{
  "name": "reuseport_select_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588619248,
      "name": "reuseport_select_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:265",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588619248,
      "name": "reuseport_select_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 674
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
struct sock * reuseport_select_sock(struct sock * sk, u32 hash, struct sk_buff * skb, int hdr_len)
```

```json
{
  "name": "reuseport_select_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588757040,
      "name": "reuseport_select_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:265",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588757040,
      "name": "reuseport_select_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 727
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct sock * reuseport_select_sock(struct sock * sk, u32 hash, struct sk_buff * skb, int hdr_len)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
