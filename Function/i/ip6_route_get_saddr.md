# Function: <code>ip6_route_get_saddr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ip6_route_get_saddr(struct net * net, struct rt6_info * rt, const struct in6_addr * daddr, unsigned int prefs, struct in6_addr * saddr)
```

```json
{
  "name": "ip6_route_get_saddr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587071312,
      "name": "ip6_route_get_saddr",
      "external": true,
      "loc": "net/ipv6/route.c:2527",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587071312,
      "name": "ip6_route_get_saddr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
  "name": "ip6_route_get_saddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587436157,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:92",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587504311,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:92",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_get_saddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587639507,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:96",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587708423,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:96",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_get_saddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587788934,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:98",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587860198,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:98",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_get_saddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588318006,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:104",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588389356,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:104",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_get_saddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588674809,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:112",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588750061,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:112",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_get_saddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588891288,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:112",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588969029,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:112",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_get_saddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589332561,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:132",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589413160,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:132",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_get_saddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589556769,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:132",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589637400,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:132",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_get_saddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590561617,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:133",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590662679,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:133",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_get_saddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590621537,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:133",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590722490,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:133",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_get_saddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590547316,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:133",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590646141,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:133",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_get_saddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591362908,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:133",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591464531,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:133",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_get_saddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593035770,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:133",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593146093,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:133",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_get_saddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594927578,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:133",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595043629,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:133",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_get_saddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595319072,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:129",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595437088,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:129",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_get_saddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596160496,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:128",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596279088,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:128",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
  "name": "ip6_route_get_saddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503238188,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:132",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503319804,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:132",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_get_saddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235899048,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:132",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail"
      ],
      "caller_func": []
    },
    {
      "addr": 3235989088,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:132",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_get_saddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296969700,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:132",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297080292,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:132",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_get_saddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279261850,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:132",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279337374,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:132",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
  "name": "ip6_route_get_saddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589161137,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:132",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589241768,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:132",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_get_saddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588886129,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:132",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588966760,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:132",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_get_saddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589598001,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:132",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589678632,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:132",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_route_get_saddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589646120,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:132",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_dst_lookup_tail"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589727768,
      "name": "ip6_route_get_saddr",
      "external": false,
      "loc": "include/net/ip6_route.h:132",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_fill_node"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
int ip6_route_get_saddr(struct net * net, struct rt6_info * rt, const struct in6_addr * daddr, unsigned int prefs, struct in6_addr * saddr)
```
</details>
</li>
</ul>
