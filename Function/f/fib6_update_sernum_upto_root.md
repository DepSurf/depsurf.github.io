# Function: <code>fib6_update_sernum_upto_root</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fib6_update_sernum_upto_root",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588426966,
      "name": "fib6_update_sernum_upto_root",
      "external": false,
      "loc": "net/ipv6/ip6_fib.c:1110",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_add"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void fib6_update_sernum_upto_root(struct net * net, struct fib6_info * rt)
```

```json
{
  "name": "fib6_update_sernum_upto_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588787328,
      "name": "fib6_update_sernum_upto_root",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1187",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588787328,
      "name": "fib6_update_sernum_upto_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void fib6_update_sernum_upto_root(struct net * net, struct fib6_info * rt)
```

```json
{
  "name": "fib6_update_sernum_upto_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589007712,
      "name": "fib6_update_sernum_upto_root",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1221",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589007712,
      "name": "fib6_update_sernum_upto_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void fib6_update_sernum_upto_root(struct net * net, struct fib6_info * rt)
```

```json
{
  "name": "fib6_update_sernum_upto_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589461232,
      "name": "fib6_update_sernum_upto_root",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1282",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_update_sernum_stub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589461232,
      "name": "fib6_update_sernum_upto_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void fib6_update_sernum_upto_root(struct net * net, struct fib6_info * rt)
```

```json
{
  "name": "fib6_update_sernum_upto_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589685584,
      "name": "fib6_update_sernum_upto_root",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1283",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_update_sernum_stub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589685584,
      "name": "fib6_update_sernum_upto_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void fib6_update_sernum_upto_root(struct net * net, struct fib6_info * rt)
```

```json
{
  "name": "fib6_update_sernum_upto_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590701886,
      "name": "fib6_update_sernum_upto_root",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1348",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_update_sernum_stub"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_ifup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590701776,
      "name": "fib6_update_sernum_upto_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void fib6_update_sernum_upto_root(struct net * net, struct fib6_info * rt)
```

```json
{
  "name": "fib6_update_sernum_upto_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590762430,
      "name": "fib6_update_sernum_upto_root",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1351",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_update_sernum_stub"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_ifup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590762320,
      "name": "fib6_update_sernum_upto_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void fib6_update_sernum_upto_root(struct net * net, struct fib6_info * rt)
```

```json
{
  "name": "fib6_update_sernum_upto_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590689310,
      "name": "fib6_update_sernum_upto_root",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1352",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_update_sernum_stub"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_ifup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590689200,
      "name": "fib6_update_sernum_upto_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void fib6_update_sernum_upto_root(struct net * net, struct fib6_info * rt)
```

```json
{
  "name": "fib6_update_sernum_upto_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591505278,
      "name": "fib6_update_sernum_upto_root",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1354",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_update_sernum_stub"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_ifup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591505168,
      "name": "fib6_update_sernum_upto_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void fib6_update_sernum_upto_root(struct net * net, struct fib6_info * rt)
```

```json
{
  "name": "fib6_update_sernum_upto_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593190142,
      "name": "fib6_update_sernum_upto_root",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1355",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_update_sernum_stub"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_ifup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593190016,
      "name": "fib6_update_sernum_upto_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void fib6_update_sernum_upto_root(struct net * net, struct fib6_info * rt)
```

```json
{
  "name": "fib6_update_sernum_upto_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595089454,
      "name": "fib6_update_sernum_upto_root",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1354",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_update_sernum_stub"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_ifup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595089344,
      "name": "fib6_update_sernum_upto_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void fib6_update_sernum_upto_root(struct net * net, struct fib6_info * rt)
```

```json
{
  "name": "fib6_update_sernum_upto_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595483198,
      "name": "fib6_update_sernum_upto_root",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1354",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_update_sernum_stub"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_ifup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595483088,
      "name": "fib6_update_sernum_upto_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void fib6_update_sernum_upto_root(struct net * net, struct fib6_info * rt)
```

```json
{
  "name": "fib6_update_sernum_upto_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596325822,
      "name": "fib6_update_sernum_upto_root",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1354",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_update_sernum_stub"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_ifup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596325712,
      "name": "fib6_update_sernum_upto_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void fib6_update_sernum_upto_root(struct net * net, struct fib6_info * rt)
```

```json
{
  "name": "fib6_update_sernum_upto_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503375036,
      "name": "fib6_update_sernum_upto_root",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1283",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_update_sernum_stub"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503374864,
      "name": "fib6_update_sernum_upto_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void fib6_update_sernum_upto_root(struct net * net, struct fib6_info * rt)
```

```json
{
  "name": "fib6_update_sernum_upto_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236038924,
      "name": "fib6_update_sernum_upto_root",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1283",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_update_sernum_stub"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3236038820,
      "name": "fib6_update_sernum_upto_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void fib6_update_sernum_upto_root(struct net * net, struct fib6_info * rt)
```

```json
{
  "name": "fib6_update_sernum_upto_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297145376,
      "name": "fib6_update_sernum_upto_root",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1283",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_update_sernum_stub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297145376,
      "name": "fib6_update_sernum_upto_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void fib6_update_sernum_upto_root(struct net * net, struct fib6_info * rt)
```

```json
{
  "name": "fib6_update_sernum_upto_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279377254,
      "name": "fib6_update_sernum_upto_root",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1283",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_update_sernum_stub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279377254,
      "name": "fib6_update_sernum_upto_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void fib6_update_sernum_upto_root(struct net * net, struct fib6_info * rt)
```

```json
{
  "name": "fib6_update_sernum_upto_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589289952,
      "name": "fib6_update_sernum_upto_root",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1283",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_update_sernum_stub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589289952,
      "name": "fib6_update_sernum_upto_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void fib6_update_sernum_upto_root(struct net * net, struct fib6_info * rt)
```

```json
{
  "name": "fib6_update_sernum_upto_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589014944,
      "name": "fib6_update_sernum_upto_root",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1283",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_update_sernum_stub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589014944,
      "name": "fib6_update_sernum_upto_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void fib6_update_sernum_upto_root(struct net * net, struct fib6_info * rt)
```

```json
{
  "name": "fib6_update_sernum_upto_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589726816,
      "name": "fib6_update_sernum_upto_root",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1283",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_update_sernum_stub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589726816,
      "name": "fib6_update_sernum_upto_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void fib6_update_sernum_upto_root(struct net * net, struct fib6_info * rt)
```

```json
{
  "name": "fib6_update_sernum_upto_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589777184,
      "name": "fib6_update_sernum_upto_root",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1283",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_update_sernum_stub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589777184,
      "name": "fib6_update_sernum_upto_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void fib6_update_sernum_upto_root(struct net * net, struct fib6_info * rt)
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
