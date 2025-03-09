# Function: <code>nexthop_select_path</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nexthop * nexthop_select_path(struct nexthop * nh, int hash)
```

```json
{
  "name": "nexthop_select_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589153792,
      "name": "nexthop_select_path",
      "external": true,
      "loc": "net/ipv4/nexthop.c:480",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv6/route.c:fib6_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589153792,
      "name": "nexthop_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 633
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
struct nexthop * nexthop_select_path(struct nexthop * nh, int hash)
```

```json
{
  "name": "nexthop_select_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589377888,
      "name": "nexthop_select_path",
      "external": true,
      "loc": "net/ipv4/nexthop.c:482",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv6/route.c:fib6_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589377888,
      "name": "nexthop_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 633
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
struct nexthop * nexthop_select_path(struct nexthop * nh, int hash)
```

```json
{
  "name": "nexthop_select_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590363616,
      "name": "nexthop_select_path",
      "external": true,
      "loc": "net/ipv4/nexthop.c:545",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv6/route.c:fib6_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590363616,
      "name": "nexthop_select_path.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
    },
    {
      "addr": 18446744071590364240,
      "name": "nexthop_select_path",
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
struct nexthop * nexthop_select_path(struct nexthop * nh, int hash)
```

```json
{
  "name": "nexthop_select_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590418976,
      "name": "nexthop_select_path",
      "external": true,
      "loc": "net/ipv4/nexthop.c:673",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv6/route.c:fib6_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590418976,
      "name": "nexthop_select_path.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
    },
    {
      "addr": 18446744071590419600,
      "name": "nexthop_select_path",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nexthop * nexthop_select_path(struct nexthop * nh, int hash)
```

```json
{
  "name": "nexthop_select_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590333136,
      "name": "nexthop_select_path",
      "external": true,
      "loc": "net/ipv4/nexthop.c:1207",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv6/route.c:fib6_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590333136,
      "name": "nexthop_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
struct nexthop * nexthop_select_path(struct nexthop * nh, int hash)
```

```json
{
  "name": "nexthop_select_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591121789,
      "name": "nexthop_select_path",
      "external": true,
      "loc": "net/ipv4/nexthop.c:1207",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv6/route.c:fib6_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592730765,
      "name": "nexthop_select_path.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071591121744,
      "name": "nexthop_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
struct nexthop * nexthop_select_path(struct nexthop * nh, int hash)
```

```json
{
  "name": "nexthop_select_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592775341,
      "name": "nexthop_select_path",
      "external": true,
      "loc": "net/ipv4/nexthop.c:1208",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv6/route.c:fib6_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594617193,
      "name": "nexthop_select_path.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071592775296,
      "name": "nexthop_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
struct nexthop * nexthop_select_path(struct nexthop * nh, int hash)
```

```json
{
  "name": "nexthop_select_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594648749,
      "name": "nexthop_select_path",
      "external": true,
      "loc": "net/ipv4/nexthop.c:1208",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv6/route.c:fib6_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596352030,
      "name": "nexthop_select_path.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071594648704,
      "name": "nexthop_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
struct nexthop * nexthop_select_path(struct nexthop * nh, int hash)
```

```json
{
  "name": "nexthop_select_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595041133,
      "name": "nexthop_select_path",
      "external": true,
      "loc": "net/ipv4/nexthop.c:1208",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv6/route.c:fib6_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596880846,
      "name": "nexthop_select_path.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071595041088,
      "name": "nexthop_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
struct nexthop * nexthop_select_path(struct nexthop * nh, int hash)
```

```json
{
  "name": "nexthop_select_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595858029,
      "name": "nexthop_select_path",
      "external": true,
      "loc": "net/ipv4/nexthop.c:1231",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv6/route.c:fib6_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597805039,
      "name": "nexthop_select_path.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071595857984,
      "name": "nexthop_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
struct nexthop * nexthop_select_path(struct nexthop * nh, int hash)
```

```json
{
  "name": "nexthop_select_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503020872,
      "name": "nexthop_select_path",
      "external": true,
      "loc": "net/ipv4/nexthop.c:482",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv6/route.c:fib6_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503020872,
      "name": "nexthop_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 660
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
struct nexthop * nexthop_select_path(struct nexthop * nh, int hash)
```

```json
{
  "name": "nexthop_select_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235710932,
      "name": "nexthop_select_path",
      "external": true,
      "loc": "net/ipv4/nexthop.c:482",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv6/route.c:fib6_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235710932,
      "name": "nexthop_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 684
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
struct nexthop * nexthop_select_path(struct nexthop * nh, int hash)
```

```json
{
  "name": "nexthop_select_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296716832,
      "name": "nexthop_select_path",
      "external": true,
      "loc": "net/ipv4/nexthop.c:482",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv6/route.c:fib6_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296716832,
      "name": "nexthop_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 820
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
struct nexthop * nexthop_select_path(struct nexthop * nh, int hash)
```

```json
{
  "name": "nexthop_select_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279093432,
      "name": "nexthop_select_path",
      "external": true,
      "loc": "net/ipv4/nexthop.c:482",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv6/route.c:fib6_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279093432,
      "name": "nexthop_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 612
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
struct nexthop * nexthop_select_path(struct nexthop * nh, int hash)
```

```json
{
  "name": "nexthop_select_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588984064,
      "name": "nexthop_select_path",
      "external": true,
      "loc": "net/ipv4/nexthop.c:482",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv6/route.c:fib6_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588984064,
      "name": "nexthop_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 633
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
struct nexthop * nexthop_select_path(struct nexthop * nh, int hash)
```

```json
{
  "name": "nexthop_select_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588696000,
      "name": "nexthop_select_path",
      "external": true,
      "loc": "net/ipv4/nexthop.c:482",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv6/route.c:fib6_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588696000,
      "name": "nexthop_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 633
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
struct nexthop * nexthop_select_path(struct nexthop * nh, int hash)
```

```json
{
  "name": "nexthop_select_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589420448,
      "name": "nexthop_select_path",
      "external": true,
      "loc": "net/ipv4/nexthop.c:482",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv6/route.c:fib6_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589420448,
      "name": "nexthop_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 633
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
struct nexthop * nexthop_select_path(struct nexthop * nh, int hash)
```

```json
{
  "name": "nexthop_select_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589464032,
      "name": "nexthop_select_path",
      "external": true,
      "loc": "net/ipv4/nexthop.c:482",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_select_multipath",
        "net/ipv6/route.c:fib6_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589464032,
      "name": "nexthop_select_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 633
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct nexthop * nexthop_select_path(struct nexthop * nh, int hash)
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
