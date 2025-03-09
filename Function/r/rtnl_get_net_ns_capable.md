# Function: <code>rtnl_get_net_ns_capable</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct net * rtnl_get_net_ns_capable(struct sock * sk, int netnsid)
```

```json
{
  "name": "rtnl_get_net_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588067744,
      "name": "rtnl_get_net_ns_capable",
      "external": true,
      "loc": "net/core/rtnetlink.c:1862",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588067744,
      "name": "rtnl_get_net_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
struct net * rtnl_get_net_ns_capable(struct sock * sk, int netnsid)
```

```json
{
  "name": "rtnl_get_net_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588384096,
      "name": "rtnl_get_net_ns_capable",
      "external": true,
      "loc": "net/core/rtnetlink.c:1864",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588384096,
      "name": "rtnl_get_net_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct net * rtnl_get_net_ns_capable(struct sock * sk, int netnsid)
```

```json
{
  "name": "rtnl_get_net_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588590464,
      "name": "rtnl_get_net_ns_capable",
      "external": true,
      "loc": "net/core/rtnetlink.c:1864",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588590464,
      "name": "rtnl_get_net_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct net * rtnl_get_net_ns_capable(struct sock * sk, int netnsid)
```

```json
{
  "name": "rtnl_get_net_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589441504,
      "name": "rtnl_get_net_ns_capable",
      "external": true,
      "loc": "net/core/rtnetlink.c:1950",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589441504,
      "name": "rtnl_get_net_ns_capable",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct net * rtnl_get_net_ns_capable(struct sock * sk, int netnsid)
```

```json
{
  "name": "rtnl_get_net_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589443280,
      "name": "rtnl_get_net_ns_capable",
      "external": true,
      "loc": "net/core/rtnetlink.c:1993",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589443280,
      "name": "rtnl_get_net_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
struct net * rtnl_get_net_ns_capable(struct sock * sk, int netnsid)
```

```json
{
  "name": "rtnl_get_net_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589337104,
      "name": "rtnl_get_net_ns_capable",
      "external": true,
      "loc": "net/core/rtnetlink.c:1996",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589337104,
      "name": "rtnl_get_net_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
struct net * rtnl_get_net_ns_capable(struct sock * sk, int netnsid)
```

```json
{
  "name": "rtnl_get_net_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590066944,
      "name": "rtnl_get_net_ns_capable",
      "external": true,
      "loc": "net/core/rtnetlink.c:2005",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_valid_dump_ifaddr_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590066944,
      "name": "rtnl_get_net_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
struct net * rtnl_get_net_ns_capable(struct sock * sk, int netnsid)
```

```json
{
  "name": "rtnl_get_net_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591614672,
      "name": "rtnl_get_net_ns_capable",
      "external": true,
      "loc": "net/core/rtnetlink.c:2051",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591614672,
      "name": "rtnl_get_net_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
struct net * rtnl_get_net_ns_capable(struct sock * sk, int netnsid)
```

```json
{
  "name": "rtnl_get_net_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593396848,
      "name": "rtnl_get_net_ns_capable",
      "external": true,
      "loc": "net/core/rtnetlink.c:2091",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593396848,
      "name": "rtnl_get_net_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
struct net * rtnl_get_net_ns_capable(struct sock * sk, int netnsid)
```

```json
{
  "name": "rtnl_get_net_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593859504,
      "name": "rtnl_get_net_ns_capable",
      "external": true,
      "loc": "net/core/rtnetlink.c:2106",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593859504,
      "name": "rtnl_get_net_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
struct net * rtnl_get_net_ns_capable(struct sock * sk, int netnsid)
```

```json
{
  "name": "rtnl_get_net_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594640512,
      "name": "rtnl_get_net_ns_capable",
      "external": true,
      "loc": "net/core/rtnetlink.c:2138",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594640512,
      "name": "rtnl_get_net_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
struct net * rtnl_get_net_ns_capable(struct sock * sk, int netnsid)
```

```json
{
  "name": "rtnl_get_net_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502133480,
      "name": "rtnl_get_net_ns_capable",
      "external": true,
      "loc": "net/core/rtnetlink.c:1864",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502133480,
      "name": "rtnl_get_net_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
struct net * rtnl_get_net_ns_capable(struct sock * sk, int netnsid)
```

```json
{
  "name": "rtnl_get_net_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234875948,
      "name": "rtnl_get_net_ns_capable",
      "external": true,
      "loc": "net/core/rtnetlink.c:1864",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/ipv4/devinet.c:inet_dump_ifaddr",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_dump_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234875948,
      "name": "rtnl_get_net_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct net * rtnl_get_net_ns_capable(struct sock * sk, int netnsid)
```

```json
{
  "name": "rtnl_get_net_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295597760,
      "name": "rtnl_get_net_ns_capable",
      "external": true,
      "loc": "net/core/rtnetlink.c:1864",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295597760,
      "name": "rtnl_get_net_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
struct net * rtnl_get_net_ns_capable(struct sock * sk, int netnsid)
```

```json
{
  "name": "rtnl_get_net_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278388322,
      "name": "rtnl_get_net_ns_capable",
      "external": true,
      "loc": "net/core/rtnetlink.c:1864",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278388322,
      "name": "rtnl_get_net_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
struct net * rtnl_get_net_ns_capable(struct sock * sk, int netnsid)
```

```json
{
  "name": "rtnl_get_net_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588197200,
      "name": "rtnl_get_net_ns_capable",
      "external": true,
      "loc": "net/core/rtnetlink.c:1864",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588197200,
      "name": "rtnl_get_net_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct net * rtnl_get_net_ns_capable(struct sock * sk, int netnsid)
```

```json
{
  "name": "rtnl_get_net_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587910032,
      "name": "rtnl_get_net_ns_capable",
      "external": true,
      "loc": "net/core/rtnetlink.c:1864",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587910032,
      "name": "rtnl_get_net_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct net * rtnl_get_net_ns_capable(struct sock * sk, int netnsid)
```

```json
{
  "name": "rtnl_get_net_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588529024,
      "name": "rtnl_get_net_ns_capable",
      "external": true,
      "loc": "net/core/rtnetlink.c:1864",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588529024,
      "name": "rtnl_get_net_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct net * rtnl_get_net_ns_capable(struct sock * sk, int netnsid)
```

```json
{
  "name": "rtnl_get_net_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588666352,
      "name": "rtnl_get_net_ns_capable",
      "external": true,
      "loc": "net/core/rtnetlink.c:1864",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/ipv6/addrconf.c:inet6_rtm_getaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588666352,
      "name": "rtnl_get_net_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct net * rtnl_get_net_ns_capable(struct sock * sk, int netnsid)
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
