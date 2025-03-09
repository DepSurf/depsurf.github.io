# Function: <code>cookie_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c)
```

```json
{
  "name": "cookie_hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586885024,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv4/syncookies.c:56",
      "file": "net/ipv4/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence",
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_check"
      ]
    },
    {
      "addr": 18446744071587229408,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv6/syncookies.c:47",
      "file": "net/ipv6/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence",
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586885024,
      "name": "cookie_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
    },
    {
      "addr": 18446744071587229408,
      "name": "cookie_hash",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c)
```

```json
{
  "name": "cookie_hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587334304,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv4/syncookies.c:53",
      "file": "net/ipv4/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ]
    },
    {
      "addr": 18446744071587686512,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv6/syncookies.c:46",
      "file": "net/ipv6/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587334304,
      "name": "cookie_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
    },
    {
      "addr": 18446744071587686512,
      "name": "cookie_hash",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c)
```

```json
{
  "name": "cookie_hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587537152,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv4/syncookies.c:53",
      "file": "net/ipv4/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ]
    },
    {
      "addr": 18446744071587895232,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv6/syncookies.c:46",
      "file": "net/ipv6/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587537152,
      "name": "cookie_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
    },
    {
      "addr": 18446744071587895232,
      "name": "cookie_hash",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision ❓</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c)
```

```json
{
  "name": "cookie_hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587683136,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv4/syncookies.c:52",
      "file": "net/ipv4/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ]
    },
    {
      "addr": 18446744071588052496,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv6/syncookies.c:45",
      "file": "net/ipv6/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587683136,
      "name": "cookie_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
    },
    {
      "addr": 18446744071588052496,
      "name": "cookie_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision ❓</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c)
```

```json
{
  "name": "cookie_hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588209792,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv4/syncookies.c:52",
      "file": "net/ipv4/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ]
    },
    {
      "addr": 18446744071588590512,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv6/syncookies.c:45",
      "file": "net/ipv6/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588209792,
      "name": "cookie_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071588590512,
      "name": "cookie_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision ❓</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c)
```

```json
{
  "name": "cookie_hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588564496,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv4/syncookies.c:52",
      "file": "net/ipv4/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ]
    },
    {
      "addr": 18446744071588955744,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv6/syncookies.c:45",
      "file": "net/ipv6/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588564496,
      "name": "cookie_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    },
    {
      "addr": 18446744071588955744,
      "name": "cookie_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision ❓</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c)
```

```json
{
  "name": "cookie_hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588761856,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv4/syncookies.c:52",
      "file": "net/ipv4/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ]
    },
    {
      "addr": 18446744071589179760,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv6/syncookies.c:45",
      "file": "net/ipv6/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588761856,
      "name": "cookie_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    },
    {
      "addr": 18446744071589179760,
      "name": "cookie_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision ❓</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c)
```

```json
{
  "name": "cookie_hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589194928,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv4/syncookies.c:48",
      "file": "net/ipv4/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ]
    },
    {
      "addr": 18446744071589633520,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv6/syncookies.c:40",
      "file": "net/ipv6/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589194928,
      "name": "cookie_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071589633520,
      "name": "cookie_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision ❓</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c)
```

```json
{
  "name": "cookie_hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589420368,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv4/syncookies.c:48",
      "file": "net/ipv4/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ]
    },
    {
      "addr": 18446744071589857712,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv6/syncookies.c:40",
      "file": "net/ipv6/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589420368,
      "name": "cookie_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071589857712,
      "name": "cookie_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c)
```

```json
{
  "name": "cookie_hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590407616,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv4/syncookies.c:48",
      "file": "net/ipv4/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ]
    },
    {
      "addr": 18446744071590884928,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv6/syncookies.c:40",
      "file": "net/ipv6/syncookies.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590407616,
      "name": "cookie_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071590884928,
      "name": "cookie_hash.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c)
```

```json
{
  "name": "cookie_hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590465456,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv4/syncookies.c:48",
      "file": "net/ipv4/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ]
    },
    {
      "addr": 18446744071590946432,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv6/syncookies.c:40",
      "file": "net/ipv6/syncookies.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590465456,
      "name": "cookie_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071590946432,
      "name": "cookie_hash.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c)
```

```json
{
  "name": "cookie_hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590391216,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv4/syncookies.c:48",
      "file": "net/ipv4/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ]
    },
    {
      "addr": 18446744071590876368,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv6/syncookies.c:40",
      "file": "net/ipv6/syncookies.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590391216,
      "name": "cookie_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    },
    {
      "addr": 18446744071590876368,
      "name": "cookie_hash.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c)
```

```json
{
  "name": "cookie_hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591186368,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv4/syncookies.c:48",
      "file": "net/ipv4/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ]
    },
    {
      "addr": 18446744071591706928,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv6/syncookies.c:40",
      "file": "net/ipv6/syncookies.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591186368,
      "name": "cookie_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
    },
    {
      "addr": 18446744071591706928,
      "name": "cookie_hash.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c)
```

```json
{
  "name": "cookie_hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592845584,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv4/syncookies.c:46",
      "file": "net/ipv4/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ]
    },
    {
      "addr": 18446744071593406592,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv6/syncookies.c:40",
      "file": "net/ipv6/syncookies.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592845584,
      "name": "cookie_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
    },
    {
      "addr": 18446744071593406592,
      "name": "cookie_hash.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c)
```

```json
{
  "name": "cookie_hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594722560,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv4/syncookies.c:46",
      "file": "net/ipv4/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ]
    },
    {
      "addr": 18446744071595316928,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv6/syncookies.c:40",
      "file": "net/ipv6/syncookies.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594722560,
      "name": "cookie_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
    },
    {
      "addr": 18446744071595316928,
      "name": "cookie_hash.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c)
```

```json
{
  "name": "cookie_hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595114640,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv4/syncookies.c:46",
      "file": "net/ipv4/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ]
    },
    {
      "addr": 18446744071595711968,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv6/syncookies.c:40",
      "file": "net/ipv6/syncookies.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595114640,
      "name": "cookie_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
    },
    {
      "addr": 18446744071595711968,
      "name": "cookie_hash.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c)
```

```json
{
  "name": "cookie_hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595927360,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv4/syncookies.c:45",
      "file": "net/ipv4/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ]
    },
    {
      "addr": 18446744071596560176,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv6/syncookies.c:40",
      "file": "net/ipv6/syncookies.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595927360,
      "name": "cookie_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
    },
    {
      "addr": 18446744071596560176,
      "name": "cookie_hash.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c)
```

```json
{
  "name": "cookie_hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503073120,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv4/syncookies.c:48",
      "file": "net/ipv4/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ]
    },
    {
      "addr": 18446603336503574984,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv6/syncookies.c:40",
      "file": "net/ipv6/syncookies.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503073120,
      "name": "cookie_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    },
    {
      "addr": 18446603336503574984,
      "name": "cookie_hash.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c)
```

```json
{
  "name": "cookie_hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235756000,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv4/syncookies.c:48",
      "file": "net/ipv4/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ]
    },
    {
      "addr": 3236221968,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv6/syncookies.c:40",
      "file": "net/ipv6/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235756000,
      "name": "cookie_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 3236221968,
      "name": "cookie_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c)
```

```json
{
  "name": "cookie_hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296777104,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv4/syncookies.c:48",
      "file": "net/ipv4/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ]
    },
    {
      "addr": 13835058055297378240,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv6/syncookies.c:40",
      "file": "net/ipv6/syncookies.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296777104,
      "name": "cookie_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    },
    {
      "addr": 13835058055297378240,
      "name": "cookie_hash.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision ❓</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c)
```

```json
{
  "name": "cookie_hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279129596,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv4/syncookies.c:48",
      "file": "net/ipv4/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ]
    },
    {
      "addr": 18446743936279531370,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv6/syncookies.c:40",
      "file": "net/ipv6/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279129596,
      "name": "cookie_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446743936279531370,
      "name": "cookie_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision ❓</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c)
```

```json
{
  "name": "cookie_hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589024736,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv4/syncookies.c:48",
      "file": "net/ipv4/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ]
    },
    {
      "addr": 18446744071589462080,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv6/syncookies.c:40",
      "file": "net/ipv6/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589024736,
      "name": "cookie_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071589462080,
      "name": "cookie_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision ❓</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c)
```

```json
{
  "name": "cookie_hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588749776,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv4/syncookies.c:48",
      "file": "net/ipv4/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ]
    },
    {
      "addr": 18446744071589187072,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv6/syncookies.c:40",
      "file": "net/ipv6/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588749776,
      "name": "cookie_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071589187072,
      "name": "cookie_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision ❓</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c)
```

```json
{
  "name": "cookie_hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589461120,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv4/syncookies.c:48",
      "file": "net/ipv4/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ]
    },
    {
      "addr": 18446744071589898944,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv6/syncookies.c:40",
      "file": "net/ipv6/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589461120,
      "name": "cookie_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071589898944,
      "name": "cookie_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision ❓</summary>

```c
u32 cookie_hash(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 count, int c)
```

```json
{
  "name": "cookie_hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589507456,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv4/syncookies.c:48",
      "file": "net/ipv4/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ]
    },
    {
      "addr": 18446744071589951264,
      "name": "cookie_hash",
      "external": false,
      "loc": "net/ipv6/syncookies.c:40",
      "file": "net/ipv6/syncookies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589507456,
      "name": "cookie_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071589951264,
      "name": "cookie_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
