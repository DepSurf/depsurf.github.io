# Function: <code>inet6_ehashfn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
u32 inet6_ehashfn(const struct net * net, const struct in6_addr * laddr, const u16 lport, const struct in6_addr * faddr, const __be16 fport)
```

```json
{
  "name": "inet6_ehashfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587241024,
      "name": "inet6_ehashfn",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:26",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/inet6_hashtables.c:__inet6_lookup_established",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587241024,
      "name": "inet6_ehashfn",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
u32 inet6_ehashfn(const struct net * net, const struct in6_addr * laddr, const u16 lport, const struct in6_addr * faddr, const __be16 fport)
```

```json
{
  "name": "inet6_ehashfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587704752,
      "name": "inet6_ehashfn",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:28",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:__inet6_lookup_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587704752,
      "name": "inet6_ehashfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 425
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
u32 inet6_ehashfn(const struct net * net, const struct in6_addr * laddr, const u16 lport, const struct in6_addr * faddr, const __be16 fport)
```

```json
{
  "name": "inet6_ehashfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587919312,
      "name": "inet6_ehashfn",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:28",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:__inet6_lookup_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587919312,
      "name": "inet6_ehashfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 425
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
u32 inet6_ehashfn(const struct net * net, const struct in6_addr * laddr, const u16 lport, const struct in6_addr * faddr, const __be16 fport)
```

```json
{
  "name": "inet6_ehashfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588077264,
      "name": "inet6_ehashfn",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:28",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:__inet6_lookup_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588077264,
      "name": "inet6_ehashfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 425
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
u32 inet6_ehashfn(const struct net * net, const struct in6_addr * laddr, const u16 lport, const struct in6_addr * faddr, const __be16 fport)
```

```json
{
  "name": "inet6_ehashfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588621552,
      "name": "inet6_ehashfn",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:28",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:__inet6_lookup_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588621552,
      "name": "inet6_ehashfn",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
u32 inet6_ehashfn(const struct net * net, const struct in6_addr * laddr, const u16 lport, const struct in6_addr * faddr, const __be16 fport)
```

```json
{
  "name": "inet6_ehashfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588987520,
      "name": "inet6_ehashfn",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:28",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup",
        "net/ipv6/inet6_hashtables.c:__inet6_lookup_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588987520,
      "name": "inet6_ehashfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 425
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
u32 inet6_ehashfn(const struct net * net, const struct in6_addr * laddr, const u16 lport, const struct in6_addr * faddr, const __be16 fport)
```

```json
{
  "name": "inet6_ehashfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589211744,
      "name": "inet6_ehashfn",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:28",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup",
        "net/ipv6/inet6_hashtables.c:__inet6_lookup_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589211744,
      "name": "inet6_ehashfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 425
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
u32 inet6_ehashfn(const struct net * net, const struct in6_addr * laddr, const u16 lport, const struct in6_addr * faddr, const __be16 fport)
```

```json
{
  "name": "inet6_ehashfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589665776,
      "name": "inet6_ehashfn",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:24",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup",
        "net/ipv6/inet6_hashtables.c:__inet6_lookup_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589665776,
      "name": "inet6_ehashfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 426
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
u32 inet6_ehashfn(const struct net * net, const struct in6_addr * laddr, const u16 lport, const struct in6_addr * faddr, const __be16 fport)
```

```json
{
  "name": "inet6_ehashfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589890032,
      "name": "inet6_ehashfn",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:24",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup",
        "net/ipv6/inet6_hashtables.c:__inet6_lookup_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589890032,
      "name": "inet6_ehashfn",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
u32 inet6_ehashfn(const struct net * net, const struct in6_addr * laddr, const u16 lport, const struct in6_addr * faddr, const __be16 fport)
```

```json
{
  "name": "inet6_ehashfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590919728,
      "name": "inet6_ehashfn",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:24",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/ipv6/inet6_hashtables.c:__inet6_lookup_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590919728,
      "name": "inet6_ehashfn",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
u32 inet6_ehashfn(const struct net * net, const struct in6_addr * laddr, const u16 lport, const struct in6_addr * faddr, const __be16 fport)
```

```json
{
  "name": "inet6_ehashfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590983312,
      "name": "inet6_ehashfn",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:26",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:__inet6_lookup_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590983312,
      "name": "inet6_ehashfn",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
u32 inet6_ehashfn(const struct net * net, const struct in6_addr * laddr, const u16 lport, const struct in6_addr * faddr, const __be16 fport)
```

```json
{
  "name": "inet6_ehashfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590913952,
      "name": "inet6_ehashfn",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:26",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:__inet6_lookup_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590913952,
      "name": "inet6_ehashfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
u32 inet6_ehashfn(const struct net * net, const struct in6_addr * laddr, const u16 lport, const struct in6_addr * faddr, const __be16 fport)
```

```json
{
  "name": "inet6_ehashfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591749744,
      "name": "inet6_ehashfn",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:26",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup",
        "net/ipv6/inet6_hashtables.c:__inet6_lookup_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591749744,
      "name": "inet6_ehashfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
u32 inet6_ehashfn(const struct net * net, const struct in6_addr * laddr, const u16 lport, const struct in6_addr * faddr, const __be16 fport)
```

```json
{
  "name": "inet6_ehashfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593456032,
      "name": "inet6_ehashfn",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:26",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup",
        "net/ipv6/inet6_hashtables.c:__inet6_lookup_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593456032,
      "name": "inet6_ehashfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 465
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
u32 inet6_ehashfn(const struct net * net, const struct in6_addr * laddr, const u16 lport, const struct in6_addr * faddr, const __be16 fport)
```

```json
{
  "name": "inet6_ehashfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595373136,
      "name": "inet6_ehashfn",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:24",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup",
        "net/ipv6/inet6_hashtables.c:__inet6_lookup_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595373136,
      "name": "inet6_ehashfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 465
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
u32 inet6_ehashfn(const struct net * net, const struct in6_addr * laddr, const u16 lport, const struct in6_addr * faddr, const __be16 fport)
```

```json
{
  "name": "inet6_ehashfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595769952,
      "name": "inet6_ehashfn",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:24",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup",
        "net/ipv6/inet6_hashtables.c:__inet6_lookup_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595769952,
      "name": "inet6_ehashfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
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
u32 inet6_ehashfn(const struct net * net, const struct in6_addr * laddr, const u16 lport, const struct in6_addr * faddr, const __be16 fport)
```

```json
{
  "name": "inet6_ehashfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596618192,
      "name": "inet6_ehashfn",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:24",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup",
        "net/ipv6/inet6_hashtables.c:__inet6_lookup_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596618192,
      "name": "inet6_ehashfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
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
u32 inet6_ehashfn(const struct net * net, const struct in6_addr * laddr, const u16 lport, const struct in6_addr * faddr, const __be16 fport)
```

```json
{
  "name": "inet6_ehashfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503612392,
      "name": "inet6_ehashfn",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:24",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup",
        "net/ipv6/inet6_hashtables.c:__inet6_lookup_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503612392,
      "name": "inet6_ehashfn",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
u32 inet6_ehashfn(const struct net * net, const struct in6_addr * laddr, const u16 lport, const struct in6_addr * faddr, const __be16 fport)
```

```json
{
  "name": "inet6_ehashfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236256156,
      "name": "inet6_ehashfn",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:24",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup",
        "net/ipv6/inet6_hashtables.c:__inet6_lookup_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236256156,
      "name": "inet6_ehashfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
u32 inet6_ehashfn(const struct net * net, const struct in6_addr * laddr, const u16 lport, const struct in6_addr * faddr, const __be16 fport)
```

```json
{
  "name": "inet6_ehashfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297425920,
      "name": "inet6_ehashfn",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:24",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup",
        "net/ipv6/inet6_hashtables.c:__inet6_lookup_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297425920,
      "name": "inet6_ehashfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
u32 inet6_ehashfn(const struct net * net, const struct in6_addr * laddr, const u16 lport, const struct in6_addr * faddr, const __be16 fport)
```

```json
{
  "name": "inet6_ehashfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279563184,
      "name": "inet6_ehashfn",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:24",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup",
        "net/ipv6/inet6_hashtables.c:__inet6_lookup_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279563184,
      "name": "inet6_ehashfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 516
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
u32 inet6_ehashfn(const struct net * net, const struct in6_addr * laddr, const u16 lport, const struct in6_addr * faddr, const __be16 fport)
```

```json
{
  "name": "inet6_ehashfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589494400,
      "name": "inet6_ehashfn",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:24",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup",
        "net/ipv6/inet6_hashtables.c:__inet6_lookup_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589494400,
      "name": "inet6_ehashfn",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
u32 inet6_ehashfn(const struct net * net, const struct in6_addr * laddr, const u16 lport, const struct in6_addr * faddr, const __be16 fport)
```

```json
{
  "name": "inet6_ehashfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589219392,
      "name": "inet6_ehashfn",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:24",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup",
        "net/ipv6/inet6_hashtables.c:__inet6_lookup_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589219392,
      "name": "inet6_ehashfn",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
u32 inet6_ehashfn(const struct net * net, const struct in6_addr * laddr, const u16 lport, const struct in6_addr * faddr, const __be16 fport)
```

```json
{
  "name": "inet6_ehashfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589935664,
      "name": "inet6_ehashfn",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:24",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup",
        "net/ipv6/inet6_hashtables.c:__inet6_lookup_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589935664,
      "name": "inet6_ehashfn",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
u32 inet6_ehashfn(const struct net * net, const struct in6_addr * laddr, const u16 lport, const struct in6_addr * faddr, const __be16 fport)
```

```json
{
  "name": "inet6_ehashfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589985152,
      "name": "inet6_ehashfn",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:24",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv6/inet6_hashtables.c:__inet6_check_established",
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup",
        "net/ipv6/inet6_hashtables.c:__inet6_lookup_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589985152,
      "name": "inet6_ehashfn",
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
