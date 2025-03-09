# Function: <code>fib6_check_nexthop</code>

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
int fib6_check_nexthop(struct nexthop * nh, struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_check_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589148080,
      "name": "fib6_check_nexthop",
      "external": true,
      "loc": "net/ipv4/nexthop.c:561",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589148080,
      "name": "fib6_check_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int fib6_check_nexthop(struct nexthop * nh, struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_check_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589372192,
      "name": "fib6_check_nexthop",
      "external": true,
      "loc": "net/ipv4/nexthop.c:563",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589372192,
      "name": "fib6_check_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int fib6_check_nexthop(struct nexthop * nh, struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_check_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590357232,
      "name": "fib6_check_nexthop",
      "external": true,
      "loc": "net/ipv4/nexthop.c:629",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590357232,
      "name": "fib6_check_nexthop",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int fib6_check_nexthop(struct nexthop * nh, struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_check_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590412464,
      "name": "fib6_check_nexthop",
      "external": true,
      "loc": "net/ipv4/nexthop.c:757",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590412464,
      "name": "fib6_check_nexthop",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int fib6_check_nexthop(struct nexthop * nh, struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_check_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590330848,
      "name": "fib6_check_nexthop",
      "external": true,
      "loc": "net/ipv4/nexthop.c:1266",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:fib6_check_nh_list",
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590330848,
      "name": "fib6_check_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int fib6_check_nexthop(struct nexthop * nh, struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_check_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib6_check_nexthop",
      "external": true,
      "loc": "net/ipv4/nexthop.c:1266",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:fib6_check_nh_list",
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592730013,
      "name": "fib6_check_nexthop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071591118928,
      "name": "fib6_check_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
int fib6_check_nexthop(struct nexthop * nh, struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_check_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib6_check_nexthop",
      "external": true,
      "loc": "net/ipv4/nexthop.c:1267",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:fib6_check_nh_list",
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594616418,
      "name": "fib6_check_nexthop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071592772512,
      "name": "fib6_check_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
int fib6_check_nexthop(struct nexthop * nh, struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_check_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib6_check_nexthop",
      "external": true,
      "loc": "net/ipv4/nexthop.c:1267",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:fib6_check_nh_list",
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596351255,
      "name": "fib6_check_nexthop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071594645808,
      "name": "fib6_check_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
int fib6_check_nexthop(struct nexthop * nh, struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_check_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib6_check_nexthop",
      "external": true,
      "loc": "net/ipv4/nexthop.c:1267",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:fib6_check_nh_list",
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596880119,
      "name": "fib6_check_nexthop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071595038240,
      "name": "fib6_check_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
int fib6_check_nexthop(struct nexthop * nh, struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_check_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib6_check_nexthop",
      "external": true,
      "loc": "net/ipv4/nexthop.c:1290",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:fib6_check_nh_list",
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597804198,
      "name": "fib6_check_nexthop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071595851136,
      "name": "fib6_check_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
int fib6_check_nexthop(struct nexthop * nh, struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_check_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503014760,
      "name": "fib6_check_nexthop",
      "external": true,
      "loc": "net/ipv4/nexthop.c:563",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503014760,
      "name": "fib6_check_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int fib6_check_nexthop(struct nexthop * nh, struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_check_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235704140,
      "name": "fib6_check_nexthop",
      "external": true,
      "loc": "net/ipv4/nexthop.c:563",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235704140,
      "name": "fib6_check_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int fib6_check_nexthop(struct nexthop * nh, struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_check_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296708992,
      "name": "fib6_check_nexthop",
      "external": true,
      "loc": "net/ipv4/nexthop.c:563",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296708992,
      "name": "fib6_check_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int fib6_check_nexthop(struct nexthop * nh, struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_check_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279087238,
      "name": "fib6_check_nexthop",
      "external": true,
      "loc": "net/ipv4/nexthop.c:563",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279087238,
      "name": "fib6_check_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int fib6_check_nexthop(struct nexthop * nh, struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_check_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588978368,
      "name": "fib6_check_nexthop",
      "external": true,
      "loc": "net/ipv4/nexthop.c:563",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588978368,
      "name": "fib6_check_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int fib6_check_nexthop(struct nexthop * nh, struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_check_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588690304,
      "name": "fib6_check_nexthop",
      "external": true,
      "loc": "net/ipv4/nexthop.c:563",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588690304,
      "name": "fib6_check_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int fib6_check_nexthop(struct nexthop * nh, struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_check_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589414752,
      "name": "fib6_check_nexthop",
      "external": true,
      "loc": "net/ipv4/nexthop.c:563",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589414752,
      "name": "fib6_check_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int fib6_check_nexthop(struct nexthop * nh, struct fib6_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_check_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589458288,
      "name": "fib6_check_nexthop",
      "external": true,
      "loc": "net/ipv4/nexthop.c:563",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_info_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589458288,
      "name": "fib6_check_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int fib6_check_nexthop(struct nexthop * nh, struct fib6_config * cfg, struct netlink_ext_ack * extack)
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
