# Function: <code>fib6_purge_rt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fib6_purge_rt(struct rt6_info * rt, struct fib6_node * fn, struct net * net)
```

```json
{
  "name": "fib6_purge_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587078640,
      "name": "fib6_purge_rt",
      "external": false,
      "loc": "net/ipv6/ip6_fib.c:705",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ip6_fib.c:fib6_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587078640,
      "name": "fib6_purge_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fib6_purge_rt(struct rt6_info * rt, struct fib6_node * fn, struct net * net)
```

```json
{
  "name": "fib6_purge_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587530272,
      "name": "fib6_purge_rt",
      "external": false,
      "loc": "net/ipv6/ip6_fib.c:707",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ip6_fib.c:fib6_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587530272,
      "name": "fib6_purge_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void fib6_purge_rt(struct rt6_info * rt, struct fib6_node * fn, struct net * net)
```

```json
{
  "name": "fib6_purge_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587734640,
      "name": "fib6_purge_rt",
      "external": false,
      "loc": "net/ipv6/ip6_fib.c:707",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ip6_fib.c:fib6_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587734640,
      "name": "fib6_purge_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void fib6_purge_rt(struct rt6_info * rt, struct fib6_node * fn, struct net * net)
```

```json
{
  "name": "fib6_purge_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587887984,
      "name": "fib6_purge_rt",
      "external": false,
      "loc": "net/ipv6/ip6_fib.c:736",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ip6_fib.c:fib6_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587887984,
      "name": "fib6_purge_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fib6_purge_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588429588,
      "name": "fib6_purge_rt",
      "external": false,
      "loc": "net/ipv6/ip6_fib.c:845",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ip6_fib.c:fib6_add"
      ],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ip6_fib.c:fib6_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588424080,
      "name": "fib6_purge_rt.part.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fib6_purge_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588790938,
      "name": "fib6_purge_rt",
      "external": false,
      "loc": "net/ipv6/ip6_fib.c:898",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ip6_fib.c:fib6_add"
      ],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ip6_fib.c:fib6_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588785424,
      "name": "fib6_purge_rt.part.27",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fib6_purge_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589011322,
      "name": "fib6_purge_rt",
      "external": false,
      "loc": "net/ipv6/ip6_fib.c:932",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ip6_fib.c:fib6_add"
      ],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ip6_fib.c:fib6_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589005792,
      "name": "fib6_purge_rt.part.29",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fib6_purge_rt(struct fib6_info * rt, struct fib6_node * fn, struct net * net)
```

```json
{
  "name": "fib6_purge_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589456256,
      "name": "fib6_purge_rt",
      "external": false,
      "loc": "net/ipv6/ip6_fib.c:971",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589456256,
      "name": "fib6_purge_rt",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fib6_purge_rt(struct fib6_info * rt, struct fib6_node * fn, struct net * net)
```

```json
{
  "name": "fib6_purge_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589680608,
      "name": "fib6_purge_rt",
      "external": false,
      "loc": "net/ipv6/ip6_fib.c:971",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589680608,
      "name": "fib6_purge_rt",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void fib6_purge_rt(struct fib6_info * rt, struct fib6_node * fn, struct net * net)
```

```json
{
  "name": "fib6_purge_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590694624,
      "name": "fib6_purge_rt",
      "external": false,
      "loc": "net/ipv6/ip6_fib.c:1022",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590694624,
      "name": "fib6_purge_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 495
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
void fib6_purge_rt(struct fib6_info * rt, struct fib6_node * fn, struct net * net)
```

```json
{
  "name": "fib6_purge_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590755168,
      "name": "fib6_purge_rt",
      "external": false,
      "loc": "net/ipv6/ip6_fib.c:1023",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590755168,
      "name": "fib6_purge_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 503
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
void fib6_purge_rt(struct fib6_info * rt, struct fib6_node * fn, struct net * net)
```

```json
{
  "name": "fib6_purge_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590681888,
      "name": "fib6_purge_rt",
      "external": false,
      "loc": "net/ipv6/ip6_fib.c:1024",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590681888,
      "name": "fib6_purge_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 499
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
void fib6_purge_rt(struct fib6_info * rt, struct fib6_node * fn, struct net * net)
```

```json
{
  "name": "fib6_purge_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591497856,
      "name": "fib6_purge_rt",
      "external": false,
      "loc": "net/ipv6/ip6_fib.c:1026",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591497856,
      "name": "fib6_purge_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 499
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
void fib6_purge_rt(struct fib6_info * rt, struct fib6_node * fn, struct net * net)
```

```json
{
  "name": "fib6_purge_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593182368,
      "name": "fib6_purge_rt",
      "external": false,
      "loc": "net/ipv6/ip6_fib.c:1027",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593182368,
      "name": "fib6_purge_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 505
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
void fib6_purge_rt(struct fib6_info * rt, struct fib6_node * fn, struct net * net)
```

```json
{
  "name": "fib6_purge_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595081376,
      "name": "fib6_purge_rt",
      "external": false,
      "loc": "net/ipv6/ip6_fib.c:1026",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595081376,
      "name": "fib6_purge_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 505
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
void fib6_purge_rt(struct fib6_info * rt, struct fib6_node * fn, struct net * net)
```

```json
{
  "name": "fib6_purge_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595475136,
      "name": "fib6_purge_rt",
      "external": false,
      "loc": "net/ipv6/ip6_fib.c:1026",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595475136,
      "name": "fib6_purge_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 505
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
void fib6_purge_rt(struct fib6_info * rt, struct fib6_node * fn, struct net * net)
```

```json
{
  "name": "fib6_purge_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596317728,
      "name": "fib6_purge_rt",
      "external": false,
      "loc": "net/ipv6/ip6_fib.c:1026",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596317728,
      "name": "fib6_purge_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 505
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
void fib6_purge_rt(struct fib6_info * rt, struct fib6_node * fn, struct net * net)
```

```json
{
  "name": "fib6_purge_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503365664,
      "name": "fib6_purge_rt",
      "external": false,
      "loc": "net/ipv6/ip6_fib.c:971",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503365664,
      "name": "fib6_purge_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
void fib6_purge_rt(struct fib6_info * rt, struct fib6_node * fn, struct net * net)
```

```json
{
  "name": "fib6_purge_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236034132,
      "name": "fib6_purge_rt",
      "external": false,
      "loc": "net/ipv6/ip6_fib.c:971",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236034132,
      "name": "fib6_purge_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
void fib6_purge_rt(struct fib6_info * rt, struct fib6_node * fn, struct net * net)
```

```json
{
  "name": "fib6_purge_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297137744,
      "name": "fib6_purge_rt",
      "external": false,
      "loc": "net/ipv6/ip6_fib.c:971",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297137744,
      "name": "fib6_purge_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
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
void fib6_purge_rt(struct fib6_info * rt, struct fib6_node * fn, struct net * net)
```

```json
{
  "name": "fib6_purge_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279372782,
      "name": "fib6_purge_rt",
      "external": false,
      "loc": "net/ipv6/ip6_fib.c:971",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279372782,
      "name": "fib6_purge_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
void fib6_purge_rt(struct fib6_info * rt, struct fib6_node * fn, struct net * net)
```

```json
{
  "name": "fib6_purge_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589284976,
      "name": "fib6_purge_rt",
      "external": false,
      "loc": "net/ipv6/ip6_fib.c:971",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589284976,
      "name": "fib6_purge_rt",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void fib6_purge_rt(struct fib6_info * rt, struct fib6_node * fn, struct net * net)
```

```json
{
  "name": "fib6_purge_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589009968,
      "name": "fib6_purge_rt",
      "external": false,
      "loc": "net/ipv6/ip6_fib.c:971",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589009968,
      "name": "fib6_purge_rt",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void fib6_purge_rt(struct fib6_info * rt, struct fib6_node * fn, struct net * net)
```

```json
{
  "name": "fib6_purge_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589721840,
      "name": "fib6_purge_rt",
      "external": false,
      "loc": "net/ipv6/ip6_fib.c:971",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589721840,
      "name": "fib6_purge_rt",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void fib6_purge_rt(struct fib6_info * rt, struct fib6_node * fn, struct net * net)
```

```json
{
  "name": "fib6_purge_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589772192,
      "name": "fib6_purge_rt",
      "external": false,
      "loc": "net/ipv6/ip6_fib.c:971",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589772192,
      "name": "fib6_purge_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
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
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void fib6_purge_rt(struct rt6_info * rt, struct fib6_node * fn, struct net * net)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void fib6_purge_rt(struct fib6_info * rt, struct fib6_node * fn, struct net * net)
```
</details>
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
