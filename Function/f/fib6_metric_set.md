# Function: <code>fib6_metric_set</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void fib6_metric_set(struct fib6_info * f6i, int metric, u32 val)
```

```json
{
  "name": "fib6_metric_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588787152,
      "name": "fib6_metric_set",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:632",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_mtu_change_route",
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588787152,
      "name": "fib6_metric_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void fib6_metric_set(struct fib6_info * f6i, int metric, u32 val)
```

```json
{
  "name": "fib6_metric_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589007536,
      "name": "fib6_metric_set",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:666",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_mtu_change_route",
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589007536,
      "name": "fib6_metric_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void fib6_metric_set(struct fib6_info * f6i, int metric, u32 val)
```

```json
{
  "name": "fib6_metric_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589458992,
      "name": "fib6_metric_set",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:659",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_mtu_change",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589458992,
      "name": "fib6_metric_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void fib6_metric_set(struct fib6_info * f6i, int metric, u32 val)
```

```json
{
  "name": "fib6_metric_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589683376,
      "name": "fib6_metric_set",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:659",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_mtu_change",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589683376,
      "name": "fib6_metric_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void fib6_metric_set(struct fib6_info * f6i, int metric, u32 val)
```

```json
{
  "name": "fib6_metric_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590699818,
      "name": "fib6_metric_set",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:710",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_mtu_change",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590701600,
      "name": "fib6_metric_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void fib6_metric_set(struct fib6_info * f6i, int metric, u32 val)
```

```json
{
  "name": "fib6_metric_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590760376,
      "name": "fib6_metric_set",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:711",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_mtu_change",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590762144,
      "name": "fib6_metric_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void fib6_metric_set(struct fib6_info * f6i, int metric, u32 val)
```

```json
{
  "name": "fib6_metric_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590687187,
      "name": "fib6_metric_set",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:712",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_mtu_change",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590689024,
      "name": "fib6_metric_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void fib6_metric_set(struct fib6_info * f6i, int metric, u32 val)
```

```json
{
  "name": "fib6_metric_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591503123,
      "name": "fib6_metric_set",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:714",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_mtu_change",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591504960,
      "name": "fib6_metric_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void fib6_metric_set(struct fib6_info * f6i, int metric, u32 val)
```

```json
{
  "name": "fib6_metric_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593188332,
      "name": "fib6_metric_set",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:715",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_mtu_change",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593189760,
      "name": "fib6_metric_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void fib6_metric_set(struct fib6_info * f6i, int metric, u32 val)
```

```json
{
  "name": "fib6_metric_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595087384,
      "name": "fib6_metric_set",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:714",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_mtu_change",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595089056,
      "name": "fib6_metric_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void fib6_metric_set(struct fib6_info * f6i, int metric, u32 val)
```

```json
{
  "name": "fib6_metric_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595481125,
      "name": "fib6_metric_set",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:714",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_mtu_change",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595482800,
      "name": "fib6_metric_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void fib6_metric_set(struct fib6_info * f6i, int metric, u32 val)
```

```json
{
  "name": "fib6_metric_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596322704,
      "name": "fib6_metric_set",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:714",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_mtu_change",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596322704,
      "name": "fib6_metric_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
void fib6_metric_set(struct fib6_info * f6i, int metric, u32 val)
```

```json
{
  "name": "fib6_metric_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503372888,
      "name": "fib6_metric_set",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:659",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_mtu_change",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503372888,
      "name": "fib6_metric_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void fib6_metric_set(struct fib6_info * f6i, int metric, u32 val)
```

```json
{
  "name": "fib6_metric_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236036612,
      "name": "fib6_metric_set",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:659",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_mtu_change",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236036612,
      "name": "fib6_metric_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void fib6_metric_set(struct fib6_info * f6i, int metric, u32 val)
```

```json
{
  "name": "fib6_metric_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297142688,
      "name": "fib6_metric_set",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:659",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_mtu_change",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297142688,
      "name": "fib6_metric_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void fib6_metric_set(struct fib6_info * f6i, int metric, u32 val)
```

```json
{
  "name": "fib6_metric_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279375574,
      "name": "fib6_metric_set",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:659",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_mtu_change",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279375574,
      "name": "fib6_metric_set",
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
void fib6_metric_set(struct fib6_info * f6i, int metric, u32 val)
```

```json
{
  "name": "fib6_metric_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589287744,
      "name": "fib6_metric_set",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:659",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_mtu_change",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589287744,
      "name": "fib6_metric_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void fib6_metric_set(struct fib6_info * f6i, int metric, u32 val)
```

```json
{
  "name": "fib6_metric_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589012736,
      "name": "fib6_metric_set",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:659",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_mtu_change",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589012736,
      "name": "fib6_metric_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void fib6_metric_set(struct fib6_info * f6i, int metric, u32 val)
```

```json
{
  "name": "fib6_metric_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589724608,
      "name": "fib6_metric_set",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:659",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_mtu_change",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589724608,
      "name": "fib6_metric_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void fib6_metric_set(struct fib6_info * f6i, int metric, u32 val)
```

```json
{
  "name": "fib6_metric_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589774976,
      "name": "fib6_metric_set",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:659",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_nh_mtu_change",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ndisc.c:ndisc_router_discovery",
        "net/ipv6/ndisc.c:ndisc_router_discovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589774976,
      "name": "fib6_metric_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void fib6_metric_set(struct fib6_info * f6i, int metric, u32 val)
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
