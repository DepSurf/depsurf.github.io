# Function: <code>neigh_flush_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "neigh_flush_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586347344,
      "name": "neigh_flush_dev",
      "external": false,
      "loc": "net/core/neighbour.c:195",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_changeaddr",
        "net/core/neighbour.c:neigh_ifdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586347344,
      "name": "neigh_flush_dev.isra.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "neigh_flush_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586780256,
      "name": "neigh_flush_dev",
      "external": false,
      "loc": "net/core/neighbour.c:195",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_ifdown",
        "net/core/neighbour.c:neigh_changeaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586780256,
      "name": "neigh_flush_dev.isra.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "neigh_flush_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586966832,
      "name": "neigh_flush_dev",
      "external": false,
      "loc": "net/core/neighbour.c:196",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_ifdown",
        "net/core/neighbour.c:neigh_changeaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586966832,
      "name": "neigh_flush_dev.isra.37",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "neigh_flush_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587089712,
      "name": "neigh_flush_dev",
      "external": false,
      "loc": "net/core/neighbour.c:232",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_ifdown",
        "net/core/neighbour.c:neigh_changeaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587089712,
      "name": "neigh_flush_dev.isra.40",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
  "name": "neigh_flush_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587595712,
      "name": "neigh_flush_dev",
      "external": false,
      "loc": "net/core/neighbour.c:232",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_ifdown",
        "net/core/neighbour.c:neigh_changeaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587595712,
      "name": "neigh_flush_dev.isra.40",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
  "name": "neigh_flush_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587904048,
      "name": "neigh_flush_dev",
      "external": false,
      "loc": "net/core/neighbour.c:235",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_ifdown",
        "net/core/neighbour.c:neigh_changeaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587904048,
      "name": "neigh_flush_dev.isra.48",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
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
void neigh_flush_dev(struct neigh_table * tbl, struct net_device * dev, bool skip_perm)
```

```json
{
  "name": "neigh_flush_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588048320,
      "name": "neigh_flush_dev",
      "external": false,
      "loc": "net/core/neighbour.c:289",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:__neigh_ifdown",
        "net/core/neighbour.c:neigh_changeaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588048320,
      "name": "neigh_flush_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 413
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
void neigh_flush_dev(struct neigh_table * tbl, struct net_device * dev, bool skip_perm)
```

```json
{
  "name": "neigh_flush_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588359952,
      "name": "neigh_flush_dev",
      "external": false,
      "loc": "net/core/neighbour.c:289",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:__neigh_ifdown",
        "net/core/neighbour.c:neigh_changeaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588359952,
      "name": "neigh_flush_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
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
void neigh_flush_dev(struct neigh_table * tbl, struct net_device * dev, bool skip_perm)
```

```json
{
  "name": "neigh_flush_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588566384,
      "name": "neigh_flush_dev",
      "external": false,
      "loc": "net/core/neighbour.c:286",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:__neigh_ifdown",
        "net/core/neighbour.c:neigh_changeaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588566384,
      "name": "neigh_flush_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "neigh_flush_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589418256,
      "name": "neigh_flush_dev",
      "external": false,
      "loc": "net/core/neighbour.c:286",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_changeaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589418256,
      "name": "neigh_flush_dev.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "neigh_flush_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589419008,
      "name": "neigh_flush_dev",
      "external": false,
      "loc": "net/core/neighbour.c:288",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_changeaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589419008,
      "name": "neigh_flush_dev.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "neigh_flush_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589315424,
      "name": "neigh_flush_dev",
      "external": false,
      "loc": "net/core/neighbour.c:292",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_changeaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589315424,
      "name": "neigh_flush_dev.isra.0",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "neigh_flush_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "neigh_flush_dev",
      "external": false,
      "loc": "net/core/neighbour.c:292",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_changeaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590044576,
      "name": "neigh_flush_dev.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 471
    },
    {
      "addr": 18446744071592700930,
      "name": "neigh_flush_dev.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "neigh_flush_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "neigh_flush_dev",
      "external": false,
      "loc": "net/core/neighbour.c:335",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_changeaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591588032,
      "name": "neigh_flush_dev.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
    },
    {
      "addr": 18446744071594587395,
      "name": "neigh_flush_dev.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "neigh_flush_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "neigh_flush_dev",
      "external": false,
      "loc": "net/core/neighbour.c:372",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_changeaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593368576,
      "name": "neigh_flush_dev.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
    },
    {
      "addr": 18446744071596326105,
      "name": "neigh_flush_dev.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "neigh_flush_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "neigh_flush_dev",
      "external": false,
      "loc": "net/core/neighbour.c:372",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_changeaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593830736,
      "name": "neigh_flush_dev.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
    },
    {
      "addr": 18446744071596856368,
      "name": "neigh_flush_dev.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "neigh_flush_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "neigh_flush_dev",
      "external": false,
      "loc": "net/core/neighbour.c:380",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_changeaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594612336,
      "name": "neigh_flush_dev.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
    },
    {
      "addr": 18446744071597781373,
      "name": "neigh_flush_dev.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "neigh_flush_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502100992,
      "name": "neigh_flush_dev",
      "external": false,
      "loc": "net/core/neighbour.c:286",
      "file": "net/core/neighbour.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:__neigh_ifdown",
        "net/core/neighbour.c:neigh_changeaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502100992,
      "name": "neigh_flush_dev.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
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
void neigh_flush_dev(struct neigh_table * tbl, struct net_device * dev, bool skip_perm)
```

```json
{
  "name": "neigh_flush_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234853284,
      "name": "neigh_flush_dev",
      "external": false,
      "loc": "net/core/neighbour.c:286",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:__neigh_ifdown",
        "net/core/neighbour.c:neigh_changeaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234853284,
      "name": "neigh_flush_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
void neigh_flush_dev(struct neigh_table * tbl, struct net_device * dev, bool skip_perm)
```

```json
{
  "name": "neigh_flush_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295566944,
      "name": "neigh_flush_dev",
      "external": false,
      "loc": "net/core/neighbour.c:286",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:__neigh_ifdown",
        "net/core/neighbour.c:neigh_changeaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295566944,
      "name": "neigh_flush_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 648
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
void neigh_flush_dev(struct neigh_table * tbl, struct net_device * dev, bool skip_perm)
```

```json
{
  "name": "neigh_flush_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278377682,
      "name": "neigh_flush_dev",
      "external": false,
      "loc": "net/core/neighbour.c:286",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:__neigh_ifdown",
        "net/core/neighbour.c:neigh_changeaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278377682,
      "name": "neigh_flush_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
void neigh_flush_dev(struct neigh_table * tbl, struct net_device * dev, bool skip_perm)
```

```json
{
  "name": "neigh_flush_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588173120,
      "name": "neigh_flush_dev",
      "external": false,
      "loc": "net/core/neighbour.c:286",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:__neigh_ifdown",
        "net/core/neighbour.c:neigh_changeaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588173120,
      "name": "neigh_flush_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
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
void neigh_flush_dev(struct neigh_table * tbl, struct net_device * dev, bool skip_perm)
```

```json
{
  "name": "neigh_flush_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587885952,
      "name": "neigh_flush_dev",
      "external": false,
      "loc": "net/core/neighbour.c:286",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:__neigh_ifdown",
        "net/core/neighbour.c:neigh_changeaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587885952,
      "name": "neigh_flush_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
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
void neigh_flush_dev(struct neigh_table * tbl, struct net_device * dev, bool skip_perm)
```

```json
{
  "name": "neigh_flush_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588504944,
      "name": "neigh_flush_dev",
      "external": false,
      "loc": "net/core/neighbour.c:286",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:__neigh_ifdown",
        "net/core/neighbour.c:neigh_changeaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588504944,
      "name": "neigh_flush_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
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
void neigh_flush_dev(struct neigh_table * tbl, struct net_device * dev, bool skip_perm)
```

```json
{
  "name": "neigh_flush_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588642048,
      "name": "neigh_flush_dev",
      "external": false,
      "loc": "net/core/neighbour.c:286",
      "file": "net/core/neighbour.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:__neigh_ifdown",
        "net/core/neighbour.c:neigh_changeaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588642048,
      "name": "neigh_flush_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
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
void neigh_flush_dev(struct neigh_table * tbl, struct net_device * dev, bool skip_perm)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void neigh_flush_dev(struct neigh_table * tbl, struct net_device * dev, bool skip_perm)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void neigh_flush_dev(struct neigh_table * tbl, struct net_device * dev, bool skip_perm)
```
</details>
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
