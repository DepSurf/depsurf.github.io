# Function: <code>inet_ehashfn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
u32 inet_ehashfn(const struct net * net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport)
```

```json
{
  "name": "inet_ehashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586586352,
      "name": "inet_ehashfn",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:28",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/inet_hashtables.c:__inet_lookup_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586586352,
      "name": "inet_ehashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
u32 inet_ehashfn(const struct net * net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport)
```

```json
{
  "name": "inet_ehashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587029504,
      "name": "inet_ehashfn",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:30",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_lookup_established",
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587029504,
      "name": "inet_ehashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
u32 inet_ehashfn(const struct net * net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport)
```

```json
{
  "name": "inet_ehashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587225504,
      "name": "inet_ehashfn",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:31",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_lookup_established",
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587225504,
      "name": "inet_ehashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
u32 inet_ehashfn(const struct net * net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport)
```

```json
{
  "name": "inet_ehashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587357632,
      "name": "inet_ehashfn",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:31",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_lookup_established",
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587357632,
      "name": "inet_ehashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
u32 inet_ehashfn(const struct net * net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport)
```

```json
{
  "name": "inet_ehashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587877568,
      "name": "inet_ehashfn",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:31",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_lookup_established",
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587877568,
      "name": "inet_ehashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
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
u32 inet_ehashfn(const struct net * net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport)
```

```json
{
  "name": "inet_ehashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588223248,
      "name": "inet_ehashfn",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:32",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_lookup_established",
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588223248,
      "name": "inet_ehashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
u32 inet_ehashfn(const struct net * net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport)
```

```json
{
  "name": "inet_ehashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588410608,
      "name": "inet_ehashfn",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:32",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_lookup_established",
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588410608,
      "name": "inet_ehashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
u32 inet_ehashfn(const struct net * net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport)
```

```json
{
  "name": "inet_ehashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588814432,
      "name": "inet_ehashfn",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:28",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_lookup_established",
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588814432,
      "name": "inet_ehashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
u32 inet_ehashfn(const struct net * net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport)
```

```json
{
  "name": "inet_ehashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589037744,
      "name": "inet_ehashfn",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:28",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_lookup_established",
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589037744,
      "name": "inet_ehashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
u32 inet_ehashfn(const struct net * net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport)
```

```json
{
  "name": "inet_ehashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589998960,
      "name": "inet_ehashfn",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:28",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_lookup_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589998960,
      "name": "inet_ehashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
u32 inet_ehashfn(const struct net * net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport)
```

```json
{
  "name": "inet_ehashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590041248,
      "name": "inet_ehashfn",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:31",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_lookup_established",
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590041248,
      "name": "inet_ehashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
u32 inet_ehashfn(const struct net * net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport)
```

```json
{
  "name": "inet_ehashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589955440,
      "name": "inet_ehashfn",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:31",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_lookup_established",
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589955440,
      "name": "inet_ehashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
u32 inet_ehashfn(const struct net * net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport)
```

```json
{
  "name": "inet_ehashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590722640,
      "name": "inet_ehashfn",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:31",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_lookup_established",
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590722640,
      "name": "inet_ehashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
u32 inet_ehashfn(const struct net * net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport)
```

```json
{
  "name": "inet_ehashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592351760,
      "name": "inet_ehashfn",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:31",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_lookup_established",
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592351760,
      "name": "inet_ehashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
u32 inet_ehashfn(const struct net * net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport)
```

```json
{
  "name": "inet_ehashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594191296,
      "name": "inet_ehashfn",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:31",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_lookup_established",
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594191296,
      "name": "inet_ehashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
u32 inet_ehashfn(const struct net * net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport)
```

```json
{
  "name": "inet_ehashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594578400,
      "name": "inet_ehashfn",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:31",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_lookup_established",
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594578400,
      "name": "inet_ehashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
u32 inet_ehashfn(const struct net * net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport)
```

```json
{
  "name": "inet_ehashfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595381904,
      "name": "inet_ehashfn",
      "external": true,
      "loc": "net/ipv4/inet_hashtables.c:31",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_lookup_established",
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595381904,
      "name": "inet_ehashfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
u32 inet_ehashfn(const struct net * net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport)
```

```json
{
  "name": "inet_ehashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502647512,
      "name": "inet_ehashfn",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:28",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_lookup_established",
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502647512,
      "name": "inet_ehashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
u32 inet_ehashfn(const struct net * net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport)
```

```json
{
  "name": "inet_ehashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235351996,
      "name": "inet_ehashfn",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:28",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_lookup_established",
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235351996,
      "name": "inet_ehashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
u32 inet_ehashfn(const struct net * net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport)
```

```json
{
  "name": "inet_ehashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296248448,
      "name": "inet_ehashfn",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:28",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_lookup_established",
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296248448,
      "name": "inet_ehashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
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
u32 inet_ehashfn(const struct net * net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport)
```

```json
{
  "name": "inet_ehashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278788416,
      "name": "inet_ehashfn",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:28",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_lookup_established",
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278788416,
      "name": "inet_ehashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
u32 inet_ehashfn(const struct net * net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport)
```

```json
{
  "name": "inet_ehashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588644128,
      "name": "inet_ehashfn",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:28",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_lookup_established",
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588644128,
      "name": "inet_ehashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
u32 inet_ehashfn(const struct net * net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport)
```

```json
{
  "name": "inet_ehashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588356112,
      "name": "inet_ehashfn",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:28",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_lookup_established",
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588356112,
      "name": "inet_ehashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
u32 inet_ehashfn(const struct net * net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport)
```

```json
{
  "name": "inet_ehashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589080304,
      "name": "inet_ehashfn",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:28",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_lookup_established",
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589080304,
      "name": "inet_ehashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
u32 inet_ehashfn(const struct net * net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport)
```

```json
{
  "name": "inet_ehashfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589119936,
      "name": "inet_ehashfn",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:28",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_ehash_insert",
        "net/ipv4/inet_hashtables.c:__inet_check_established",
        "net/ipv4/inet_hashtables.c:__inet_lookup_established",
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589119936,
      "name": "inet_ehashfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
