# Function: <code>fib_table_flush</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int fib_table_flush(struct fib_table * tb)
```

```json
{
  "name": "fib_table_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586844480,
      "name": "fib_table_flush",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1809",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:fib_flush",
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:ip_fib_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586844480,
      "name": "fib_table_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 419
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
int fib_table_flush(struct fib_table * tb)
```

```json
{
  "name": "fib_table_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587294176,
      "name": "fib_table_flush",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1808",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:fib_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587294176,
      "name": "fib_table_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 433
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
int fib_table_flush(struct net * net, struct fib_table * tb)
```

```json
{
  "name": "fib_table_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587496128,
      "name": "fib_table_flush",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1918",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:fib_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587496128,
      "name": "fib_table_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 523
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
int fib_table_flush(struct net * net, struct fib_table * tb)
```

```json
{
  "name": "fib_table_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587632784,
      "name": "fib_table_flush",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1837",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:fib_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587632784,
      "name": "fib_table_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 619
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
int fib_table_flush(struct net * net, struct fib_table * tb)
```

```json
{
  "name": "fib_table_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588157360,
      "name": "fib_table_flush",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1835",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:fib_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588157360,
      "name": "fib_table_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
int fib_table_flush(struct net * net, struct fib_table * tb)
```

```json
{
  "name": "fib_table_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588512480,
      "name": "fib_table_flush",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1859",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:fib_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588512480,
      "name": "fib_table_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 533
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
int fib_table_flush(struct net * net, struct fib_table * tb, bool flush_all)
```

```json
{
  "name": "fib_table_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588707536,
      "name": "fib_table_flush",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1859",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:fib_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588707536,
      "name": "fib_table_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 529
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
int fib_table_flush(struct net * net, struct fib_table * tb, bool flush_all)
```

```json
{
  "name": "fib_table_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589125824,
      "name": "fib_table_flush",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1861",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:fib_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589125824,
      "name": "fib_table_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 559
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
int fib_table_flush(struct net * net, struct fib_table * tb, bool flush_all)
```

```json
{
  "name": "fib_table_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589349904,
      "name": "fib_table_flush",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1861",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:fib_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589349904,
      "name": "fib_table_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 561
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
int fib_table_flush(struct net * net, struct fib_table * tb, bool flush_all)
```

```json
{
  "name": "fib_table_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590331472,
      "name": "fib_table_flush",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1974",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:fib_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590331472,
      "name": "fib_table_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
int fib_table_flush(struct net * net, struct fib_table * tb, bool flush_all)
```

```json
{
  "name": "fib_table_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590384208,
      "name": "fib_table_flush",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1974",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:fib_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590384208,
      "name": "fib_table_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
int fib_table_flush(struct net * net, struct fib_table * tb, bool flush_all)
```

```json
{
  "name": "fib_table_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590299920,
      "name": "fib_table_flush",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:2011",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:fib_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590299920,
      "name": "fib_table_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 547
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int fib_table_flush(struct net * net, struct fib_table * tb, bool flush_all)
```

```json
{
  "name": "fib_table_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib_table_flush",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:2015",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:fib_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592729045,
      "name": "fib_table_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071591087200,
      "name": "fib_table_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 646
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int fib_table_flush(struct net * net, struct fib_table * tb, bool flush_all)
```

```json
{
  "name": "fib_table_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib_table_flush",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:2024",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:fib_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594615496,
      "name": "fib_table_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071592737664,
      "name": "fib_table_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 657
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int fib_table_flush(struct net * net, struct fib_table * tb, bool flush_all)
```

```json
{
  "name": "fib_table_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib_table_flush",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:2026",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:fib_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596350354,
      "name": "fib_table_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071594608560,
      "name": "fib_table_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 657
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int fib_table_flush(struct net * net, struct fib_table * tb, bool flush_all)
```

```json
{
  "name": "fib_table_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib_table_flush",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:2026",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:fib_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596879306,
      "name": "fib_table_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071595000512,
      "name": "fib_table_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 657
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int fib_table_flush(struct net * net, struct fib_table * tb, bool flush_all)
```

```json
{
  "name": "fib_table_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib_table_flush",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:2028",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:fib_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597803400,
      "name": "fib_table_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071595813024,
      "name": "fib_table_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 830
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
int fib_table_flush(struct net * net, struct fib_table * tb, bool flush_all)
```

```json
{
  "name": "fib_table_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502990320,
      "name": "fib_table_flush",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1861",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:fib_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502990320,
      "name": "fib_table_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
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
int fib_table_flush(struct net * net, struct fib_table * tb, bool flush_all)
```

```json
{
  "name": "fib_table_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235680112,
      "name": "fib_table_flush",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1861",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:fib_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235680112,
      "name": "fib_table_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
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
int fib_table_flush(struct net * net, struct fib_table * tb, bool flush_all)
```

```json
{
  "name": "fib_table_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296677680,
      "name": "fib_table_flush",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1861",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:fib_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296677680,
      "name": "fib_table_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 812
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
int fib_table_flush(struct net * net, struct fib_table * tb, bool flush_all)
```

```json
{
  "name": "fib_table_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279066866,
      "name": "fib_table_flush",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1861",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:fib_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279066866,
      "name": "fib_table_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 510
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
int fib_table_flush(struct net * net, struct fib_table * tb, bool flush_all)
```

```json
{
  "name": "fib_table_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588956080,
      "name": "fib_table_flush",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1861",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:fib_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588956080,
      "name": "fib_table_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 561
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
int fib_table_flush(struct net * net, struct fib_table * tb, bool flush_all)
```

```json
{
  "name": "fib_table_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588668016,
      "name": "fib_table_flush",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1861",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:fib_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588668016,
      "name": "fib_table_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 561
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
int fib_table_flush(struct net * net, struct fib_table * tb, bool flush_all)
```

```json
{
  "name": "fib_table_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589392464,
      "name": "fib_table_flush",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1861",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:fib_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589392464,
      "name": "fib_table_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 561
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
int fib_table_flush(struct net * net, struct fib_table * tb, bool flush_all)
```

```json
{
  "name": "fib_table_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589435552,
      "name": "fib_table_flush",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:1861",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:ip_fib_net_exit",
        "net/ipv4/fib_frontend.c:fib_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589435552,
      "name": "fib_table_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 561
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net * net</code>
</li>
<li>
<b>Param reordered. </b>
<code>tb</code> ➡️ <code>net, tb</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool flush_all</code>
</li>
</ul>
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
