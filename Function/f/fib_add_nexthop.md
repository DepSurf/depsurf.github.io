# Function: <code>fib_add_nexthop</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int fib_add_nexthop(struct sk_buff * skb, const struct fib_nh_common * nhc, int nh_weight, u8 rt_family)
```

```json
{
  "name": "fib_add_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589098832,
      "name": "fib_add_nexthop",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:1656",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:rt6_fill_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589098832,
      "name": "fib_add_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int fib_add_nexthop(struct sk_buff * skb, const struct fib_nh_common * nhc, int nh_weight, u8 rt_family)
```

```json
{
  "name": "fib_add_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589323008,
      "name": "fib_add_nexthop",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:1656",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:rt6_fill_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589323008,
      "name": "fib_add_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int fib_add_nexthop(struct sk_buff * skb, const struct fib_nh_common * nhc, int nh_weight, u8 rt_family)
```

```json
{
  "name": "fib_add_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590300704,
      "name": "fib_add_nexthop",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:1665",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_add_multipath",
        "net/ipv4/fib_semantics.c:fib_add_multipath",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:rt6_fill_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590300704,
      "name": "fib_add_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int fib_add_nexthop(struct sk_buff * skb, const struct fib_nh_common * nhc, int nh_weight, u8 rt_family)
```

```json
{
  "name": "fib_add_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590354928,
      "name": "fib_add_nexthop",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:1664",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_add_multipath",
        "net/ipv4/fib_semantics.c:fib_add_multipath",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:rt6_fill_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590354928,
      "name": "fib_add_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int fib_add_nexthop(struct sk_buff * skb, const struct fib_nh_common * nhc, int nh_weight, u8 rt_family)
```

```json
{
  "name": "fib_add_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590270768,
      "name": "fib_add_nexthop",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:1665",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:rt6_fill_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590270768,
      "name": "fib_add_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int fib_add_nexthop(struct sk_buff * skb, const struct fib_nh_common * nhc, int nh_weight, u8 rt_family, u32 nh_tclassid)
```

```json
{
  "name": "fib_add_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591054128,
      "name": "fib_add_nexthop",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:1707",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:rt6_fill_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591054128,
      "name": "fib_add_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int fib_add_nexthop(struct sk_buff * skb, const struct fib_nh_common * nhc, int nh_weight, u8 rt_family, u32 nh_tclassid)
```

```json
{
  "name": "fib_add_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592703152,
      "name": "fib_add_nexthop",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:1694",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:rt6_fill_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592703152,
      "name": "fib_add_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
int fib_add_nexthop(struct sk_buff * skb, const struct fib_nh_common * nhc, int nh_weight, u8 rt_family, u32 nh_tclassid)
```

```json
{
  "name": "fib_add_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594573024,
      "name": "fib_add_nexthop",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:1700",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:rt6_fill_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594573024,
      "name": "fib_add_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
int fib_add_nexthop(struct sk_buff * skb, const struct fib_nh_common * nhc, int nh_weight, u8 rt_family, u32 nh_tclassid)
```

```json
{
  "name": "fib_add_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594964832,
      "name": "fib_add_nexthop",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:1700",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:rt6_fill_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594964832,
      "name": "fib_add_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
int fib_add_nexthop(struct sk_buff * skb, const struct fib_nh_common * nhc, int nh_weight, u8 rt_family, u32 nh_tclassid)
```

```json
{
  "name": "fib_add_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595777328,
      "name": "fib_add_nexthop",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:1707",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:rt6_fill_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595777328,
      "name": "fib_add_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
int fib_add_nexthop(struct sk_buff * skb, const struct fib_nh_common * nhc, int nh_weight, u8 rt_family)
```

```json
{
  "name": "fib_add_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502960752,
      "name": "fib_add_nexthop",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:1656",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:rt6_fill_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502960752,
      "name": "fib_add_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int fib_add_nexthop(struct sk_buff * skb, const struct fib_nh_common * nhc, int nh_weight, u8 rt_family)
```

```json
{
  "name": "fib_add_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235650940,
      "name": "fib_add_nexthop",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:1656",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:rt6_fill_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235650940,
      "name": "fib_add_nexthop",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int fib_add_nexthop(struct sk_buff * skb, const struct fib_nh_common * nhc, int nh_weight, u8 rt_family)
```

```json
{
  "name": "fib_add_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296639488,
      "name": "fib_add_nexthop",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:1656",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:rt6_fill_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296639488,
      "name": "fib_add_nexthop",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int fib_add_nexthop(struct sk_buff * skb, const struct fib_nh_common * nhc, int nh_weight, u8 rt_family)
```

```json
{
  "name": "fib_add_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279042570,
      "name": "fib_add_nexthop",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:1656",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:rt6_fill_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279042570,
      "name": "fib_add_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int fib_add_nexthop(struct sk_buff * skb, const struct fib_nh_common * nhc, int nh_weight, u8 rt_family)
```

```json
{
  "name": "fib_add_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588929184,
      "name": "fib_add_nexthop",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:1656",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:rt6_fill_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588929184,
      "name": "fib_add_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int fib_add_nexthop(struct sk_buff * skb, const struct fib_nh_common * nhc, int nh_weight, u8 rt_family)
```

```json
{
  "name": "fib_add_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588641120,
      "name": "fib_add_nexthop",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:1656",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:rt6_fill_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588641120,
      "name": "fib_add_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int fib_add_nexthop(struct sk_buff * skb, const struct fib_nh_common * nhc, int nh_weight, u8 rt_family)
```

```json
{
  "name": "fib_add_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589365568,
      "name": "fib_add_nexthop",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:1656",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:rt6_fill_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589365568,
      "name": "fib_add_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int fib_add_nexthop(struct sk_buff * skb, const struct fib_nh_common * nhc, int nh_weight, u8 rt_family)
```

```json
{
  "name": "fib_add_nexthop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589408416,
      "name": "fib_add_nexthop",
      "external": true,
      "loc": "net/ipv4/fib_semantics.c:1656",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv4/fib_semantics.c:fib_dump_info",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:rt6_fill_node",
        "net/ipv6/route.c:rt6_fill_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589408416,
      "name": "fib_add_nexthop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int fib_add_nexthop(struct sk_buff * skb, const struct fib_nh_common * nhc, int nh_weight, u8 rt_family)
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 nh_tclassid</code>
</li>
</ul>
</details>
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
