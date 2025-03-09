# Function: <code>inet6_addr_modify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inet6_addr_modify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587037753,
      "name": "inet6_addr_modify",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4106",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_rtm_newaddr"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inet6_addr_modify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587486690,
      "name": "inet6_addr_modify",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4358",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_rtm_newaddr"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inet6_addr_modify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587690482,
      "name": "inet6_addr_modify",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4401",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_rtm_newaddr"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inet6_addr_modify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587841468,
      "name": "inet6_addr_modify",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4477",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_rtm_newaddr"
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
  "name": "inet6_addr_modify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588371006,
      "name": "inet6_addr_modify",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4481",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_rtm_newaddr"
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
  "name": "inet6_addr_modify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588729039,
      "name": "inet6_addr_modify",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4562",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_rtm_newaddr"
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
  "name": "inet6_addr_modify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588948995,
      "name": "inet6_addr_modify",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4584",
      "file": "net/ipv6/addrconf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_rtm_newaddr"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int inet6_addr_modify(struct inet6_ifaddr * ifp, struct ifa6_config * cfg)
```

```json
{
  "name": "inet6_addr_modify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589387232,
      "name": "inet6_addr_modify",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4620",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589387232,
      "name": "inet6_addr_modify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 973
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
int inet6_addr_modify(struct inet6_ifaddr * ifp, struct ifa6_config * cfg)
```

```json
{
  "name": "inet6_addr_modify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589611712,
      "name": "inet6_addr_modify",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4629",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589611712,
      "name": "inet6_addr_modify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1072
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
int inet6_addr_modify(struct inet6_ifaddr * ifp, struct ifa6_config * cfg)
```

```json
{
  "name": "inet6_addr_modify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590621616,
      "name": "inet6_addr_modify",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4646",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590621616,
      "name": "inet6_addr_modify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1146
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
int inet6_addr_modify(struct inet6_ifaddr * ifp, struct ifa6_config * cfg)
```

```json
{
  "name": "inet6_addr_modify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590682304,
      "name": "inet6_addr_modify",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4673",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590682304,
      "name": "inet6_addr_modify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1146
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
int inet6_addr_modify(struct inet6_ifaddr * ifp, struct ifa6_config * cfg)
```

```json
{
  "name": "inet6_addr_modify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590607536,
      "name": "inet6_addr_modify",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4677",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590607536,
      "name": "inet6_addr_modify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1080
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
int inet6_addr_modify(struct inet6_ifaddr * ifp, struct ifa6_config * cfg)
```

```json
{
  "name": "inet6_addr_modify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet6_addr_modify",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4713",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591420576,
      "name": "inet6_addr_modify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1092
    },
    {
      "addr": 18446744071592737267,
      "name": "inet6_addr_modify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int inet6_addr_modify(struct net * net, struct inet6_ifaddr * ifp, struct ifa6_config * cfg)
```

```json
{
  "name": "inet6_addr_modify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet6_addr_modify",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4720",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593098368,
      "name": "inet6_addr_modify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1149
    },
    {
      "addr": 18446744071594623846,
      "name": "inet6_addr_modify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int inet6_addr_modify(struct net * net, struct inet6_ifaddr * ifp, struct ifa6_config * cfg)
```

```json
{
  "name": "inet6_addr_modify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet6_addr_modify",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4733",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594993920,
      "name": "inet6_addr_modify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1149
    },
    {
      "addr": 18446744071596358476,
      "name": "inet6_addr_modify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int inet6_addr_modify(struct net * net, struct inet6_ifaddr * ifp, struct ifa6_config * cfg)
```

```json
{
  "name": "inet6_addr_modify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet6_addr_modify",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4739",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595387408,
      "name": "inet6_addr_modify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1149
    },
    {
      "addr": 18446744071596887101,
      "name": "inet6_addr_modify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int inet6_addr_modify(struct net * net, struct inet6_ifaddr * ifp, struct ifa6_config * cfg)
```

```json
{
  "name": "inet6_addr_modify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet6_addr_modify",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4790",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596228912,
      "name": "inet6_addr_modify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1149
    },
    {
      "addr": 18446744071597811457,
      "name": "inet6_addr_modify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int inet6_addr_modify(struct inet6_ifaddr * ifp, struct ifa6_config * cfg)
```

```json
{
  "name": "inet6_addr_modify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503291080,
      "name": "inet6_addr_modify",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4629",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503291080,
      "name": "inet6_addr_modify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1212
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
int inet6_addr_modify(struct inet6_ifaddr * ifp, struct ifa6_config * cfg)
```

```json
{
  "name": "inet6_addr_modify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235960988,
      "name": "inet6_addr_modify",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4629",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235960988,
      "name": "inet6_addr_modify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1144
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
int inet6_addr_modify(struct inet6_ifaddr * ifp, struct ifa6_config * cfg)
```

```json
{
  "name": "inet6_addr_modify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297044624,
      "name": "inet6_addr_modify",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4629",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297044624,
      "name": "inet6_addr_modify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1320
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
int inet6_addr_modify(struct inet6_ifaddr * ifp, struct ifa6_config * cfg)
```

```json
{
  "name": "inet6_addr_modify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279309168,
      "name": "inet6_addr_modify",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4629",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279309168,
      "name": "inet6_addr_modify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 936
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
int inet6_addr_modify(struct inet6_ifaddr * ifp, struct ifa6_config * cfg)
```

```json
{
  "name": "inet6_addr_modify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589216080,
      "name": "inet6_addr_modify",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4629",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589216080,
      "name": "inet6_addr_modify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1072
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
int inet6_addr_modify(struct inet6_ifaddr * ifp, struct ifa6_config * cfg)
```

```json
{
  "name": "inet6_addr_modify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588941072,
      "name": "inet6_addr_modify",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4629",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588941072,
      "name": "inet6_addr_modify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1072
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
int inet6_addr_modify(struct inet6_ifaddr * ifp, struct ifa6_config * cfg)
```

```json
{
  "name": "inet6_addr_modify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589652944,
      "name": "inet6_addr_modify",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4629",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589652944,
      "name": "inet6_addr_modify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1072
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
int inet6_addr_modify(struct inet6_ifaddr * ifp, struct ifa6_config * cfg)
```

```json
{
  "name": "inet6_addr_modify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589702000,
      "name": "inet6_addr_modify",
      "external": false,
      "loc": "net/ipv6/addrconf.c:4629",
      "file": "net/ipv6/addrconf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/addrconf.c:inet6_rtm_newaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589702000,
      "name": "inet6_addr_modify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1072
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
int inet6_addr_modify(struct inet6_ifaddr * ifp, struct ifa6_config * cfg)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net * net</code>
</li>
<li>
<b>Param reordered. </b>
<code>ifp, cfg</code> ➡️ <code>net, ifp, cfg</code>
</li>
</ul>
</details>
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
