# Function: <code>rt6_multipath_rebalance</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rt6_multipath_rebalance(struct fib6_info * rt)
```

```json
{
  "name": "rt6_multipath_rebalance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588748889,
      "name": "rt6_multipath_rebalance",
      "external": true,
      "loc": "net/ipv6/route.c:3917",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588748160,
      "name": "rt6_multipath_rebalance.part.82",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
    },
    {
      "addr": 18446744071588775824,
      "name": "rt6_multipath_rebalance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rt6_multipath_rebalance(struct fib6_info * rt)
```

```json
{
  "name": "rt6_multipath_rebalance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588967849,
      "name": "rt6_multipath_rebalance",
      "external": true,
      "loc": "net/ipv6/route.c:3896",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588967120,
      "name": "rt6_multipath_rebalance.part.82",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
    },
    {
      "addr": 18446744071588995984,
      "name": "rt6_multipath_rebalance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rt6_multipath_rebalance(struct fib6_info * rt)
```

```json
{
  "name": "rt6_multipath_rebalance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589411815,
      "name": "rt6_multipath_rebalance",
      "external": true,
      "loc": "net/ipv6/route.c:4559",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589411072,
      "name": "rt6_multipath_rebalance.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    },
    {
      "addr": 18446744071589446112,
      "name": "rt6_multipath_rebalance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rt6_multipath_rebalance(struct fib6_info * rt)
```

```json
{
  "name": "rt6_multipath_rebalance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589636055,
      "name": "rt6_multipath_rebalance",
      "external": true,
      "loc": "net/ipv6/route.c:4572",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589635312,
      "name": "rt6_multipath_rebalance.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    },
    {
      "addr": 18446744071589670496,
      "name": "rt6_multipath_rebalance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void rt6_multipath_rebalance(struct fib6_info * rt)
```

```json
{
  "name": "rt6_multipath_rebalance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590661223,
      "name": "rt6_multipath_rebalance",
      "external": true,
      "loc": "net/ipv6/route.c:4613",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifup"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifup",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590649808,
      "name": "rt6_multipath_rebalance.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
    },
    {
      "addr": 18446744071590683840,
      "name": "rt6_multipath_rebalance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void rt6_multipath_rebalance(struct fib6_info * rt)
```

```json
{
  "name": "rt6_multipath_rebalance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590719607,
      "name": "rt6_multipath_rebalance",
      "external": true,
      "loc": "net/ipv6/route.c:4597",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifup"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifup",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590709504,
      "name": "rt6_multipath_rebalance.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
    },
    {
      "addr": 18446744071590744384,
      "name": "rt6_multipath_rebalance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rt6_multipath_rebalance(struct fib6_info * rt)
```

```json
{
  "name": "rt6_multipath_rebalance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590644231,
      "name": "rt6_multipath_rebalance",
      "external": true,
      "loc": "net/ipv6/route.c:4612",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifup"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifup",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590636032,
      "name": "rt6_multipath_rebalance.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
    },
    {
      "addr": 18446744071590670384,
      "name": "rt6_multipath_rebalance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void rt6_multipath_rebalance(struct fib6_info * rt)
```

```json
{
  "name": "rt6_multipath_rebalance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591456823,
      "name": "rt6_multipath_rebalance",
      "external": true,
      "loc": "net/ipv6/route.c:4742",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifup"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifup",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591449424,
      "name": "rt6_multipath_rebalance.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
    },
    {
      "addr": 18446744071591486080,
      "name": "rt6_multipath_rebalance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void rt6_multipath_rebalance(struct fib6_info * rt)
```

```json
{
  "name": "rt6_multipath_rebalance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593139130,
      "name": "rt6_multipath_rebalance",
      "external": true,
      "loc": "net/ipv6/route.c:4729",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifup"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifup",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593130080,
      "name": "rt6_multipath_rebalance.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
    },
    {
      "addr": 18446744071593169744,
      "name": "rt6_multipath_rebalance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void rt6_multipath_rebalance(struct fib6_info * rt)
```

```json
{
  "name": "rt6_multipath_rebalance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595036458,
      "name": "rt6_multipath_rebalance",
      "external": true,
      "loc": "net/ipv6/route.c:4729",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifup"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifup",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595026656,
      "name": "rt6_multipath_rebalance.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
    },
    {
      "addr": 18446744071595068064,
      "name": "rt6_multipath_rebalance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void rt6_multipath_rebalance(struct fib6_info * rt)
```

```json
{
  "name": "rt6_multipath_rebalance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595429934,
      "name": "rt6_multipath_rebalance",
      "external": true,
      "loc": "net/ipv6/route.c:4727",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifup"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifup",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595420688,
      "name": "rt6_multipath_rebalance.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
    },
    {
      "addr": 18446744071595461776,
      "name": "rt6_multipath_rebalance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void rt6_multipath_rebalance(struct fib6_info * rt)
```

```json
{
  "name": "rt6_multipath_rebalance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596271902,
      "name": "rt6_multipath_rebalance",
      "external": true,
      "loc": "net/ipv6/route.c:4727",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifup"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifup",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596262512,
      "name": "rt6_multipath_rebalance.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
    },
    {
      "addr": 18446744071596303904,
      "name": "rt6_multipath_rebalance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void rt6_multipath_rebalance(struct fib6_info * rt)
```

```json
{
  "name": "rt6_multipath_rebalance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503318720,
      "name": "rt6_multipath_rebalance",
      "external": true,
      "loc": "net/ipv6/route.c:4572",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503317968,
      "name": "rt6_multipath_rebalance.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
    },
    {
      "addr": 18446603336503357104,
      "name": "rt6_multipath_rebalance",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void rt6_multipath_rebalance(struct fib6_info * rt)
```

```json
{
  "name": "rt6_multipath_rebalance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235987636,
      "name": "rt6_multipath_rebalance",
      "external": true,
      "loc": "net/ipv6/route.c:4572",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235986908,
      "name": "rt6_multipath_rebalance.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
    },
    {
      "addr": 3236022988,
      "name": "rt6_multipath_rebalance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void rt6_multipath_rebalance(struct fib6_info * rt)
```

```json
{
  "name": "rt6_multipath_rebalance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297078816,
      "name": "rt6_multipath_rebalance",
      "external": true,
      "loc": "net/ipv6/route.c:4572",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297077808,
      "name": "rt6_multipath_rebalance.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    },
    {
      "addr": 13835058055297124160,
      "name": "rt6_multipath_rebalance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void rt6_multipath_rebalance(struct fib6_info * rt)
```

```json
{
  "name": "rt6_multipath_rebalance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279336390,
      "name": "rt6_multipath_rebalance",
      "external": true,
      "loc": "net/ipv6/route.c:4572",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279335838,
      "name": "rt6_multipath_rebalance.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
    },
    {
      "addr": 18446743936279363858,
      "name": "rt6_multipath_rebalance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rt6_multipath_rebalance(struct fib6_info * rt)
```

```json
{
  "name": "rt6_multipath_rebalance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589240423,
      "name": "rt6_multipath_rebalance",
      "external": true,
      "loc": "net/ipv6/route.c:4572",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589239680,
      "name": "rt6_multipath_rebalance.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    },
    {
      "addr": 18446744071589274864,
      "name": "rt6_multipath_rebalance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rt6_multipath_rebalance(struct fib6_info * rt)
```

```json
{
  "name": "rt6_multipath_rebalance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588965415,
      "name": "rt6_multipath_rebalance",
      "external": true,
      "loc": "net/ipv6/route.c:4572",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588964672,
      "name": "rt6_multipath_rebalance.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    },
    {
      "addr": 18446744071588999856,
      "name": "rt6_multipath_rebalance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rt6_multipath_rebalance(struct fib6_info * rt)
```

```json
{
  "name": "rt6_multipath_rebalance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589677287,
      "name": "rt6_multipath_rebalance",
      "external": true,
      "loc": "net/ipv6/route.c:4572",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589676544,
      "name": "rt6_multipath_rebalance.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    },
    {
      "addr": 18446744071589711728,
      "name": "rt6_multipath_rebalance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rt6_multipath_rebalance(struct fib6_info * rt)
```

```json
{
  "name": "rt6_multipath_rebalance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589726423,
      "name": "rt6_multipath_rebalance",
      "external": true,
      "loc": "net/ipv6/route.c:4572",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/route.c:fib6_ifdown",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589725680,
      "name": "rt6_multipath_rebalance.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    },
    {
      "addr": 18446744071589761872,
      "name": "rt6_multipath_rebalance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void rt6_multipath_rebalance(struct fib6_info * rt)
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
