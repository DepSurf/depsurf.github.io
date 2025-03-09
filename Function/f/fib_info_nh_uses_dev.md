# Function: <code>fib_info_nh_uses_dev</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
bool fib_info_nh_uses_dev(struct fib_info * fi, const struct net_device * dev)
```

```json
{
  "name": "fib_info_nh_uses_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588674016,
      "name": "fib_info_nh_uses_dev",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:318",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_trie.c:fib_table_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588674016,
      "name": "fib_info_nh_uses_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
bool fib_info_nh_uses_dev(struct fib_info * fi, const struct net_device * dev)
```

```json
{
  "name": "fib_info_nh_uses_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589087264,
      "name": "fib_info_nh_uses_dev",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:317",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_trie.c:fib_table_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589087264,
      "name": "fib_info_nh_uses_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
bool fib_info_nh_uses_dev(struct fib_info * fi, const struct net_device * dev)
```

```json
{
  "name": "fib_info_nh_uses_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589311424,
      "name": "fib_info_nh_uses_dev",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:318",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_trie.c:fib_table_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589311424,
      "name": "fib_info_nh_uses_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool fib_info_nh_uses_dev(struct fib_info * fi, const struct net_device * dev)
```

```json
{
  "name": "fib_info_nh_uses_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590289712,
      "name": "fib_info_nh_uses_dev",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:308",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:__fib_validate_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590289712,
      "name": "fib_info_nh_uses_dev.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    },
    {
      "addr": 18446744071590289952,
      "name": "fib_info_nh_uses_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool fib_info_nh_uses_dev(struct fib_info * fi, const struct net_device * dev)
```

```json
{
  "name": "fib_info_nh_uses_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590342544,
      "name": "fib_info_nh_uses_dev",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:308",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:__fib_validate_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590342544,
      "name": "fib_info_nh_uses_dev.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    },
    {
      "addr": 18446744071590342784,
      "name": "fib_info_nh_uses_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
bool fib_info_nh_uses_dev(struct fib_info * fi, const struct net_device * dev)
```

```json
{
  "name": "fib_info_nh_uses_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590258432,
      "name": "fib_info_nh_uses_dev",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:308",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:__fib_validate_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590258432,
      "name": "fib_info_nh_uses_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool fib_info_nh_uses_dev(struct fib_info * fi, const struct net_device * dev)
```

```json
{
  "name": "fib_info_nh_uses_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "fib_info_nh_uses_dev",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:308",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_trie.c:fn_trie_dump_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592724122,
      "name": "fib_info_nh_uses_dev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071591042832,
      "name": "fib_info_nh_uses_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 493
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool fib_info_nh_uses_dev(struct fib_info * fi, const struct net_device * dev)
```

```json
{
  "name": "fib_info_nh_uses_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "fib_info_nh_uses_dev",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:309",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_trie.c:fn_trie_dump_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594610399,
      "name": "fib_info_nh_uses_dev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071592691168,
      "name": "fib_info_nh_uses_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 513
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool fib_info_nh_uses_dev(struct fib_info * fi, const struct net_device * dev)
```

```json
{
  "name": "fib_info_nh_uses_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "fib_info_nh_uses_dev",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:309",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_trie.c:fn_trie_dump_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596345400,
      "name": "fib_info_nh_uses_dev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071594560208,
      "name": "fib_info_nh_uses_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 513
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool fib_info_nh_uses_dev(struct fib_info * fi, const struct net_device * dev)
```

```json
{
  "name": "fib_info_nh_uses_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "fib_info_nh_uses_dev",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:309",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_trie.c:fn_trie_dump_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596874431,
      "name": "fib_info_nh_uses_dev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071594951952,
      "name": "fib_info_nh_uses_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 513
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool fib_info_nh_uses_dev(struct fib_info * fi, const struct net_device * dev)
```

```json
{
  "name": "fib_info_nh_uses_dev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "fib_info_nh_uses_dev",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:309",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_trie.c:fn_trie_dump_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597798525,
      "name": "fib_info_nh_uses_dev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071595764368,
      "name": "fib_info_nh_uses_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 513
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
bool fib_info_nh_uses_dev(struct fib_info * fi, const struct net_device * dev)
```

```json
{
  "name": "fib_info_nh_uses_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502948448,
      "name": "fib_info_nh_uses_dev",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:318",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_trie.c:fib_table_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502948448,
      "name": "fib_info_nh_uses_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
bool fib_info_nh_uses_dev(struct fib_info * fi, const struct net_device * dev)
```

```json
{
  "name": "fib_info_nh_uses_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235637772,
      "name": "fib_info_nh_uses_dev",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:318",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_trie.c:fib_table_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235637772,
      "name": "fib_info_nh_uses_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
bool fib_info_nh_uses_dev(struct fib_info * fi, const struct net_device * dev)
```

```json
{
  "name": "fib_info_nh_uses_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296623936,
      "name": "fib_info_nh_uses_dev",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:318",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_trie.c:fib_table_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296623936,
      "name": "fib_info_nh_uses_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
bool fib_info_nh_uses_dev(struct fib_info * fi, const struct net_device * dev)
```

```json
{
  "name": "fib_info_nh_uses_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279033118,
      "name": "fib_info_nh_uses_dev",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:318",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_trie.c:fib_table_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279033118,
      "name": "fib_info_nh_uses_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
bool fib_info_nh_uses_dev(struct fib_info * fi, const struct net_device * dev)
```

```json
{
  "name": "fib_info_nh_uses_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588917600,
      "name": "fib_info_nh_uses_dev",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:318",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_trie.c:fib_table_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588917600,
      "name": "fib_info_nh_uses_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
bool fib_info_nh_uses_dev(struct fib_info * fi, const struct net_device * dev)
```

```json
{
  "name": "fib_info_nh_uses_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588629536,
      "name": "fib_info_nh_uses_dev",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:318",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_trie.c:fib_table_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588629536,
      "name": "fib_info_nh_uses_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
bool fib_info_nh_uses_dev(struct fib_info * fi, const struct net_device * dev)
```

```json
{
  "name": "fib_info_nh_uses_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589353984,
      "name": "fib_info_nh_uses_dev",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:318",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_trie.c:fib_table_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589353984,
      "name": "fib_info_nh_uses_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
bool fib_info_nh_uses_dev(struct fib_info * fi, const struct net_device * dev)
```

```json
{
  "name": "fib_info_nh_uses_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589396432,
      "name": "fib_info_nh_uses_dev",
      "external": true,
      "loc": "net/ipv4/fib_frontend.c:318",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:__fib_validate_source",
        "net/ipv4/fib_trie.c:fib_table_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589396432,
      "name": "fib_info_nh_uses_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
bool fib_info_nh_uses_dev(struct fib_info * fi, const struct net_device * dev)
```
</details>
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
