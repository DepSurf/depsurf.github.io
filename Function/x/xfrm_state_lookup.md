# Function: <code>xfrm_state_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct xfrm_state * xfrm_state_lookup(struct net * net, u32 mark, const xfrm_address_t * daddr, __be32 spi, u8 proto, short unsigned int family)
```

```json
{
  "name": "xfrm_state_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586944112,
      "name": "xfrm_state_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:1392",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586944112,
      "name": "xfrm_state_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
struct xfrm_state * xfrm_state_lookup(struct net * net, u32 mark, const xfrm_address_t * daddr, __be32 spi, u8 proto, short unsigned int family)
```

```json
{
  "name": "xfrm_state_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587386944,
      "name": "xfrm_state_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:1393",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587386944,
      "name": "xfrm_state_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xfrm_state * xfrm_state_lookup(struct net * net, u32 mark, const xfrm_address_t * daddr, __be32 spi, u8 proto, short unsigned int family)
```

```json
{
  "name": "xfrm_state_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587598544,
      "name": "xfrm_state_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:1422",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587590144,
      "name": "xfrm_state_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xfrm_state * xfrm_state_lookup(struct net * net, u32 mark, const xfrm_address_t * daddr, __be32 spi, u8 proto, short unsigned int family)
```

```json
{
  "name": "xfrm_state_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587741831,
      "name": "xfrm_state_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:1577",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587739856,
      "name": "xfrm_state_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xfrm_state * xfrm_state_lookup(struct net * net, u32 mark, const xfrm_address_t * daddr, __be32 spi, u8 proto, short unsigned int family)
```

```json
{
  "name": "xfrm_state_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588268349,
      "name": "xfrm_state_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:1593",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588268128,
      "name": "xfrm_state_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xfrm_state * xfrm_state_lookup(struct net * net, u32 mark, const xfrm_address_t * daddr, __be32 spi, u8 proto, short unsigned int family)
```

```json
{
  "name": "xfrm_state_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588624479,
      "name": "xfrm_state_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:1594",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588622544,
      "name": "xfrm_state_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xfrm_state * xfrm_state_lookup(struct net * net, u32 mark, const xfrm_address_t * daddr, __be32 spi, u8 proto, short unsigned int family)
```

```json
{
  "name": "xfrm_state_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588837797,
      "name": "xfrm_state_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:1628",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588834992,
      "name": "xfrm_state_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xfrm_state * xfrm_state_lookup(struct net * net, u32 mark, const xfrm_address_t * daddr, __be32 spi, u8 proto, short unsigned int family)
```

```json
{
  "name": "xfrm_state_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589271424,
      "name": "xfrm_state_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:1726",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589268672,
      "name": "xfrm_state_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xfrm_state * xfrm_state_lookup(struct net * net, u32 mark, const xfrm_address_t * daddr, __be32 spi, u8 proto, short unsigned int family)
```

```json
{
  "name": "xfrm_state_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589496400,
      "name": "xfrm_state_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:1728",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589493648,
      "name": "xfrm_state_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xfrm_state * xfrm_state_lookup(struct net * net, u32 mark, const xfrm_address_t * daddr, __be32 spi, u8 proto, short unsigned int family)
```

```json
{
  "name": "xfrm_state_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590489149,
      "name": "xfrm_state_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:1731",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590485952,
      "name": "xfrm_state_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xfrm_state * xfrm_state_lookup(struct net * net, u32 mark, const xfrm_address_t * daddr, __be32 spi, u8 proto, short unsigned int family)
```

```json
{
  "name": "xfrm_state_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590548466,
      "name": "xfrm_state_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:1765",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590544336,
      "name": "xfrm_state_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xfrm_state * xfrm_state_lookup(struct net * net, u32 mark, const xfrm_address_t * daddr, __be32 spi, u8 proto, short unsigned int family)
```

```json
{
  "name": "xfrm_state_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590473778,
      "name": "xfrm_state_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:1764",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590469568,
      "name": "xfrm_state_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xfrm_state * xfrm_state_lookup(struct net * net, u32 mark, const xfrm_address_t * daddr, __be32 spi, u8 proto, short unsigned int family)
```

```json
{
  "name": "xfrm_state_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591277538,
      "name": "xfrm_state_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:1808",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591271280,
      "name": "xfrm_state_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xfrm_state * xfrm_state_lookup(struct net * net, u32 mark, const xfrm_address_t * daddr, __be32 spi, u8 proto, short unsigned int family)
```

```json
{
  "name": "xfrm_state_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592943977,
      "name": "xfrm_state_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:1810",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592938336,
      "name": "xfrm_state_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xfrm_state * xfrm_state_lookup(struct net * net, u32 mark, const xfrm_address_t * daddr, __be32 spi, u8 proto, short unsigned int family)
```

```json
{
  "name": "xfrm_state_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594827131,
      "name": "xfrm_state_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:1964",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594820864,
      "name": "xfrm_state_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xfrm_state * xfrm_state_lookup(struct net * net, u32 mark, const xfrm_address_t * daddr, __be32 spi, u8 proto, short unsigned int family)
```

```json
{
  "name": "xfrm_state_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595218613,
      "name": "xfrm_state_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:1961",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595212368,
      "name": "xfrm_state_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xfrm_state * xfrm_state_lookup(struct net * net, u32 mark, const xfrm_address_t * daddr, __be32 spi, u8 proto, short unsigned int family)
```

```json
{
  "name": "xfrm_state_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596059157,
      "name": "xfrm_state_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:1961",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_state_bpf.c:bpf_xdp_get_xfrm_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596052912,
      "name": "xfrm_state_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct xfrm_state * xfrm_state_lookup(struct net * net, u32 mark, const xfrm_address_t * daddr, __be32 spi, u8 proto, short unsigned int family)
```

```json
{
  "name": "xfrm_state_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503164232,
      "name": "xfrm_state_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:1728",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503149872,
      "name": "xfrm_state_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct xfrm_state * xfrm_state_lookup(struct net * net, u32 mark, const xfrm_address_t * daddr, __be32 spi, u8 proto, short unsigned int family)
```

```json
{
  "name": "xfrm_state_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235835860,
      "name": "xfrm_state_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:1728",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235833028,
      "name": "xfrm_state_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct xfrm_state * xfrm_state_lookup(struct net * net, u32 mark, const xfrm_address_t * daddr, __be32 spi, u8 proto, short unsigned int family)
```

```json
{
  "name": "xfrm_state_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296884152,
      "name": "xfrm_state_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:1728",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296880592,
      "name": "xfrm_state_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct xfrm_state * xfrm_state_lookup(struct net * net, u32 mark, const xfrm_address_t * daddr, __be32 spi, u8 proto, short unsigned int family)
```

```json
{
  "name": "xfrm_state_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279205238,
      "name": "xfrm_state_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:1728",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279198900,
      "name": "xfrm_state_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct xfrm_state * xfrm_state_lookup(struct net * net, u32 mark, const xfrm_address_t * daddr, __be32 spi, u8 proto, short unsigned int family)
```

```json
{
  "name": "xfrm_state_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589100768,
      "name": "xfrm_state_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:1728",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589098016,
      "name": "xfrm_state_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct xfrm_state * xfrm_state_lookup(struct net * net, u32 mark, const xfrm_address_t * daddr, __be32 spi, u8 proto, short unsigned int family)
```

```json
{
  "name": "xfrm_state_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588825808,
      "name": "xfrm_state_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:1728",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588823056,
      "name": "xfrm_state_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct xfrm_state * xfrm_state_lookup(struct net * net, u32 mark, const xfrm_address_t * daddr, __be32 spi, u8 proto, short unsigned int family)
```

```json
{
  "name": "xfrm_state_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589537632,
      "name": "xfrm_state_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:1728",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589534880,
      "name": "xfrm_state_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct xfrm_state * xfrm_state_lookup(struct net * net, u32 mark, const xfrm_address_t * daddr, __be32 spi, u8 proto, short unsigned int family)
```

```json
{
  "name": "xfrm_state_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589585031,
      "name": "xfrm_state_lookup",
      "external": true,
      "loc": "net/xfrm/xfrm_state.c:1728",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi"
      ],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589582176,
      "name": "xfrm_state_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
