# Function: <code>rt_set_nexthop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void rt_set_nexthop(struct rtable * rt, __be32 daddr, const struct fib_result * res, struct fib_nh_exception * fnhe, struct fib_info * fi, u16 type, u32 itag)
```

```json
{
  "name": "rt_set_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586530256,
      "name": "rt_set_nexthop",
      "external": false,
      "loc": "net/ipv4/route.c:1396",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__ip_route_output_key_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586530256,
      "name": "rt_set_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 634
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
  "name": "rt_set_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586973008,
      "name": "rt_set_nexthop",
      "external": false,
      "loc": "net/ipv4/route.c:1402",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__ip_route_output_key_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586973008,
      "name": "rt_set_nexthop.constprop.42",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 653
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
  "name": "rt_set_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587166048,
      "name": "rt_set_nexthop",
      "external": false,
      "loc": "net/ipv4/route.c:1412",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__ip_route_output_key_hash",
        "net/ipv4/route.c:ip_route_input_noref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587166048,
      "name": "rt_set_nexthop.constprop.50",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 650
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
  "name": "rt_set_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587301200,
      "name": "rt_set_nexthop",
      "external": false,
      "loc": "net/ipv4/route.c:1441",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587301200,
      "name": "rt_set_nexthop.constprop.47",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 754
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
  "name": "rt_set_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587822544,
      "name": "rt_set_nexthop",
      "external": false,
      "loc": "net/ipv4/route.c:1448",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587822544,
      "name": "rt_set_nexthop.constprop.47",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 755
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
  "name": "rt_set_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588168304,
      "name": "rt_set_nexthop",
      "external": false,
      "loc": "net/ipv4/route.c:1521",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588168304,
      "name": "rt_set_nexthop.constprop.53",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 791
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
  "name": "rt_set_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588352384,
      "name": "rt_set_nexthop",
      "external": false,
      "loc": "net/ipv4/route.c:1521",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588352384,
      "name": "rt_set_nexthop.constprop.56",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 819
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt_set_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "rt_set_nexthop",
      "external": false,
      "loc": "net/ipv4/route.c:1560",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588755472,
      "name": "rt_set_nexthop.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 774
    },
    {
      "addr": 18446744071588768408,
      "name": "rt_set_nexthop.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt_set_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588979232,
      "name": "rt_set_nexthop",
      "external": false,
      "loc": "net/ipv4/route.c:1562",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588979232,
      "name": "rt_set_nexthop.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 797
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
  "name": "rt_set_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589934944,
      "name": "rt_set_nexthop",
      "external": false,
      "loc": "net/ipv4/route.c:1566",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__mkroute_output",
        "net/ipv4/route.c:__mkroute_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589934944,
      "name": "rt_set_nexthop.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1037
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
  "name": "rt_set_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589975568,
      "name": "rt_set_nexthop",
      "external": false,
      "loc": "net/ipv4/route.c:1572",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__mkroute_output",
        "net/ipv4/route.c:__mkroute_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589975568,
      "name": "rt_set_nexthop.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1037
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
  "name": "rt_set_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589889440,
      "name": "rt_set_nexthop",
      "external": false,
      "loc": "net/ipv4/route.c:1560",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__mkroute_output",
        "net/ipv4/route.c:__mkroute_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589889440,
      "name": "rt_set_nexthop.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1034
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
  "name": "rt_set_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "rt_set_nexthop",
      "external": false,
      "loc": "net/ipv4/route.c:1556",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__mkroute_output",
        "net/ipv4/route.c:__mkroute_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590653184,
      "name": "rt_set_nexthop.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1051
    },
    {
      "addr": 18446744071592713734,
      "name": "rt_set_nexthop.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
  "name": "rt_set_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "rt_set_nexthop",
      "external": false,
      "loc": "net/ipv4/route.c:1569",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__mkroute_output",
        "net/ipv4/route.c:__mkroute_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592277856,
      "name": "rt_set_nexthop.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1093
    },
    {
      "addr": 18446744071594599755,
      "name": "rt_set_nexthop.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
  "name": "rt_set_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "rt_set_nexthop",
      "external": false,
      "loc": "net/ipv4/route.c:1568",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__mkroute_output",
        "net/ipv4/route.c:__mkroute_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594113392,
      "name": "rt_set_nexthop.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1093
    },
    {
      "addr": 18446744071596335345,
      "name": "rt_set_nexthop.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
  "name": "rt_set_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "rt_set_nexthop",
      "external": false,
      "loc": "net/ipv4/route.c:1568",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__mkroute_output",
        "net/ipv4/route.c:__mkroute_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594500208,
      "name": "rt_set_nexthop.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1119
    },
    {
      "addr": 18446744071596865007,
      "name": "rt_set_nexthop.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
  "name": "rt_set_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "rt_set_nexthop",
      "external": false,
      "loc": "net/ipv4/route.c:1570",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:__mkroute_output",
        "net/ipv4/route.c:__mkroute_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595303376,
      "name": "rt_set_nexthop.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1119
    },
    {
      "addr": 18446744071597790124,
      "name": "rt_set_nexthop.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
  "name": "rt_set_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502584368,
      "name": "rt_set_nexthop",
      "external": false,
      "loc": "net/ipv4/route.c:1562",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502584368,
      "name": "rt_set_nexthop.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 988
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "rt_set_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235289640,
      "name": "rt_set_nexthop",
      "external": false,
      "loc": "net/ipv4/route.c:1562",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235289640,
      "name": "rt_set_nexthop.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 856
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "rt_set_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296171824,
      "name": "rt_set_nexthop",
      "external": false,
      "loc": "net/ipv4/route.c:1562",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296171824,
      "name": "rt_set_nexthop.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "rt_set_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278739350,
      "name": "rt_set_nexthop",
      "external": false,
      "loc": "net/ipv4/route.c:1562",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278739350,
      "name": "rt_set_nexthop.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 742
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt_set_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588585616,
      "name": "rt_set_nexthop",
      "external": false,
      "loc": "net/ipv4/route.c:1562",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588585616,
      "name": "rt_set_nexthop.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 797
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt_set_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588297600,
      "name": "rt_set_nexthop",
      "external": false,
      "loc": "net/ipv4/route.c:1562",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588297600,
      "name": "rt_set_nexthop.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 797
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt_set_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589021792,
      "name": "rt_set_nexthop",
      "external": false,
      "loc": "net/ipv4/route.c:1562",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589021792,
      "name": "rt_set_nexthop.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 797
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt_set_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589060512,
      "name": "rt_set_nexthop",
      "external": false,
      "loc": "net/ipv4/route.c:1562",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589060512,
      "name": "rt_set_nexthop.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 797
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
void rt_set_nexthop(struct rtable * rt, __be32 daddr, const struct fib_result * res, struct fib_nh_exception * fnhe, struct fib_info * fi, u16 type, u32 itag)
```
</details>
</li>
</ul>
