# Function: <code>rtm_getroute_parse_ip_proto</code>

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
int rtm_getroute_parse_ip_proto(struct nlattr * attr, u8 * ip_proto, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_getroute_parse_ip_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588530832,
      "name": "rtm_getroute_parse_ip_proto",
      "external": true,
      "loc": "net/ipv4/netlink.c:8",
      "file": "net/ipv4/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588530832,
      "name": "rtm_getroute_parse_ip_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int rtm_getroute_parse_ip_proto(struct nlattr * attr, u8 * ip_proto, u8 family, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_getroute_parse_ip_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588726800,
      "name": "rtm_getroute_parse_ip_proto",
      "external": true,
      "loc": "net/ipv4/netlink.c:9",
      "file": "net/ipv4/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588726800,
      "name": "rtm_getroute_parse_ip_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int rtm_getroute_parse_ip_proto(struct nlattr * attr, u8 * ip_proto, u8 family, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_getroute_parse_ip_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589147936,
      "name": "rtm_getroute_parse_ip_proto",
      "external": true,
      "loc": "net/ipv4/netlink.c:10",
      "file": "net/ipv4/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589147936,
      "name": "rtm_getroute_parse_ip_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int rtm_getroute_parse_ip_proto(struct nlattr * attr, u8 * ip_proto, u8 family, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_getroute_parse_ip_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589372048,
      "name": "rtm_getroute_parse_ip_proto",
      "external": true,
      "loc": "net/ipv4/netlink.c:10",
      "file": "net/ipv4/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589372048,
      "name": "rtm_getroute_parse_ip_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int rtm_getroute_parse_ip_proto(struct nlattr * attr, u8 * ip_proto, u8 family, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_getroute_parse_ip_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590357088,
      "name": "rtm_getroute_parse_ip_proto",
      "external": true,
      "loc": "net/ipv4/netlink.c:10",
      "file": "net/ipv4/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590357088,
      "name": "rtm_getroute_parse_ip_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int rtm_getroute_parse_ip_proto(struct nlattr * attr, u8 * ip_proto, u8 family, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_getroute_parse_ip_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590412320,
      "name": "rtm_getroute_parse_ip_proto",
      "external": true,
      "loc": "net/ipv4/netlink.c:10",
      "file": "net/ipv4/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590412320,
      "name": "rtm_getroute_parse_ip_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int rtm_getroute_parse_ip_proto(struct nlattr * attr, u8 * ip_proto, u8 family, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_getroute_parse_ip_proto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590328448,
      "name": "rtm_getroute_parse_ip_proto",
      "external": true,
      "loc": "net/ipv4/netlink.c:10",
      "file": "net/ipv4/netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590328448,
      "name": "rtm_getroute_parse_ip_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int rtm_getroute_parse_ip_proto(struct nlattr * attr, u8 * ip_proto, u8 family, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_getroute_parse_ip_proto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591116192,
      "name": "rtm_getroute_parse_ip_proto",
      "external": true,
      "loc": "net/ipv4/netlink.c:10",
      "file": "net/ipv4/netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591116192,
      "name": "rtm_getroute_parse_ip_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int rtm_getroute_parse_ip_proto(struct nlattr * attr, u8 * ip_proto, u8 family, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_getroute_parse_ip_proto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592769056,
      "name": "rtm_getroute_parse_ip_proto",
      "external": true,
      "loc": "net/ipv4/netlink.c:10",
      "file": "net/ipv4/netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592769056,
      "name": "rtm_getroute_parse_ip_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int rtm_getroute_parse_ip_proto(struct nlattr * attr, u8 * ip_proto, u8 family, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_getroute_parse_ip_proto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594642096,
      "name": "rtm_getroute_parse_ip_proto",
      "external": true,
      "loc": "net/ipv4/netlink.c:10",
      "file": "net/ipv4/netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594642096,
      "name": "rtm_getroute_parse_ip_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int rtm_getroute_parse_ip_proto(struct nlattr * attr, u8 * ip_proto, u8 family, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_getroute_parse_ip_proto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595034528,
      "name": "rtm_getroute_parse_ip_proto",
      "external": true,
      "loc": "net/ipv4/netlink.c:10",
      "file": "net/ipv4/netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595034528,
      "name": "rtm_getroute_parse_ip_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int rtm_getroute_parse_ip_proto(struct nlattr * attr, u8 * ip_proto, u8 family, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_getroute_parse_ip_proto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595847424,
      "name": "rtm_getroute_parse_ip_proto",
      "external": true,
      "loc": "net/ipv4/netlink.c:10",
      "file": "net/ipv4/netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595847424,
      "name": "rtm_getroute_parse_ip_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int rtm_getroute_parse_ip_proto(struct nlattr * attr, u8 * ip_proto, u8 family, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_getroute_parse_ip_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503014488,
      "name": "rtm_getroute_parse_ip_proto",
      "external": true,
      "loc": "net/ipv4/netlink.c:10",
      "file": "net/ipv4/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503014488,
      "name": "rtm_getroute_parse_ip_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int rtm_getroute_parse_ip_proto(struct nlattr * attr, u8 * ip_proto, u8 family, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_getroute_parse_ip_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235703936,
      "name": "rtm_getroute_parse_ip_proto",
      "external": true,
      "loc": "net/ipv4/netlink.c:10",
      "file": "net/ipv4/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235703936,
      "name": "rtm_getroute_parse_ip_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int rtm_getroute_parse_ip_proto(struct nlattr * attr, u8 * ip_proto, u8 family, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_getroute_parse_ip_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296708752,
      "name": "rtm_getroute_parse_ip_proto",
      "external": true,
      "loc": "net/ipv4/netlink.c:10",
      "file": "net/ipv4/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296708752,
      "name": "rtm_getroute_parse_ip_proto",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int rtm_getroute_parse_ip_proto(struct nlattr * attr, u8 * ip_proto, u8 family, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_getroute_parse_ip_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279087018,
      "name": "rtm_getroute_parse_ip_proto",
      "external": true,
      "loc": "net/ipv4/netlink.c:10",
      "file": "net/ipv4/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279087018,
      "name": "rtm_getroute_parse_ip_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int rtm_getroute_parse_ip_proto(struct nlattr * attr, u8 * ip_proto, u8 family, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_getroute_parse_ip_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588978224,
      "name": "rtm_getroute_parse_ip_proto",
      "external": true,
      "loc": "net/ipv4/netlink.c:10",
      "file": "net/ipv4/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588978224,
      "name": "rtm_getroute_parse_ip_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int rtm_getroute_parse_ip_proto(struct nlattr * attr, u8 * ip_proto, u8 family, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_getroute_parse_ip_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588690160,
      "name": "rtm_getroute_parse_ip_proto",
      "external": true,
      "loc": "net/ipv4/netlink.c:10",
      "file": "net/ipv4/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588690160,
      "name": "rtm_getroute_parse_ip_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int rtm_getroute_parse_ip_proto(struct nlattr * attr, u8 * ip_proto, u8 family, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_getroute_parse_ip_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589414608,
      "name": "rtm_getroute_parse_ip_proto",
      "external": true,
      "loc": "net/ipv4/netlink.c:10",
      "file": "net/ipv4/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589414608,
      "name": "rtm_getroute_parse_ip_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int rtm_getroute_parse_ip_proto(struct nlattr * attr, u8 * ip_proto, u8 family, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtm_getroute_parse_ip_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589458144,
      "name": "rtm_getroute_parse_ip_proto",
      "external": true,
      "loc": "net/ipv4/netlink.c:10",
      "file": "net/ipv4/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:inet_rtm_getroute",
        "net/ipv6/route.c:inet6_rtm_getroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589458144,
      "name": "rtm_getroute_parse_ip_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int rtm_getroute_parse_ip_proto(struct nlattr * attr, u8 * ip_proto, struct netlink_ext_ack * extack)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 family</code>
</li>
<li>
<b>Param reordered. </b>
<code>attr, ip_proto, extack</code> ➡️ <code>attr, ip_proto, family, extack</code>
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
