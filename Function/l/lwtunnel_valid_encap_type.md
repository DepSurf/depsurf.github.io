# Function: <code>lwtunnel_valid_encap_type</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type(u16 encap_type)
```

```json
{
  "name": "lwtunnel_valid_encap_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587075520,
      "name": "lwtunnel_valid_encap_type",
      "external": true,
      "loc": "net/core/lwtunnel.c:129",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587075520,
      "name": "lwtunnel_valid_encap_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587203960,
      "name": "lwtunnel_valid_encap_type",
      "external": true,
      "loc": "net/core/lwtunnel.c:143",
      "file": "net/core/lwtunnel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr"
      ],
      "caller_func": [
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587203616,
      "name": "lwtunnel_valid_encap_type.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    },
    {
      "addr": 18446744071587203792,
      "name": "lwtunnel_valid_encap_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587718232,
      "name": "lwtunnel_valid_encap_type",
      "external": true,
      "loc": "net/core/lwtunnel.c:145",
      "file": "net/core/lwtunnel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr"
      ],
      "caller_func": [
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587717888,
      "name": "lwtunnel_valid_encap_type.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 18446744071587718064,
      "name": "lwtunnel_valid_encap_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588050992,
      "name": "lwtunnel_valid_encap_type",
      "external": true,
      "loc": "net/core/lwtunnel.c:145",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588050992,
      "name": "lwtunnel_valid_encap_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588219248,
      "name": "lwtunnel_valid_encap_type",
      "external": true,
      "loc": "net/core/lwtunnel.c:145",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588219248,
      "name": "lwtunnel_valid_encap_type",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lwtunnel_valid_encap_type",
      "external": true,
      "loc": "net/core/lwtunnel.c:140",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588554812,
      "name": "lwtunnel_valid_encap_type.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071588553360,
      "name": "lwtunnel_valid_encap_type",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588770256,
      "name": "lwtunnel_valid_encap_type",
      "external": true,
      "loc": "net/core/lwtunnel.c:140",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588770256,
      "name": "lwtunnel_valid_encap_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589642144,
      "name": "lwtunnel_valid_encap_type",
      "external": true,
      "loc": "net/core/lwtunnel.c:142",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589642144,
      "name": "lwtunnel_valid_encap_type",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589665728,
      "name": "lwtunnel_valid_encap_type",
      "external": true,
      "loc": "net/core/lwtunnel.c:142",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589665728,
      "name": "lwtunnel_valid_encap_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589557392,
      "name": "lwtunnel_valid_encap_type",
      "external": true,
      "loc": "net/core/lwtunnel.c:142",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589557392,
      "name": "lwtunnel_valid_encap_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590301984,
      "name": "lwtunnel_valid_encap_type",
      "external": true,
      "loc": "net/core/lwtunnel.c:147",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590301984,
      "name": "lwtunnel_valid_encap_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
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
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591886256,
      "name": "lwtunnel_valid_encap_type",
      "external": true,
      "loc": "net/core/lwtunnel.c:147",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591886256,
      "name": "lwtunnel_valid_encap_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 386
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
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593688288,
      "name": "lwtunnel_valid_encap_type",
      "external": true,
      "loc": "net/core/lwtunnel.c:150",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593688288,
      "name": "lwtunnel_valid_encap_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 401
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
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594169072,
      "name": "lwtunnel_valid_encap_type",
      "external": true,
      "loc": "net/core/lwtunnel.c:150",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594169072,
      "name": "lwtunnel_valid_encap_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594965616,
      "name": "lwtunnel_valid_encap_type",
      "external": true,
      "loc": "net/core/lwtunnel.c:150",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594965616,
      "name": "lwtunnel_valid_encap_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502336240,
      "name": "lwtunnel_valid_encap_type",
      "external": true,
      "loc": "net/core/lwtunnel.c:140",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502336240,
      "name": "lwtunnel_valid_encap_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235075968,
      "name": "lwtunnel_valid_encap_type",
      "external": true,
      "loc": "net/core/lwtunnel.c:140",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235075968,
      "name": "lwtunnel_valid_encap_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295856576,
      "name": "lwtunnel_valid_encap_type",
      "external": true,
      "loc": "net/core/lwtunnel.c:140",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295856576,
      "name": "lwtunnel_valid_encap_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278558388,
      "name": "lwtunnel_valid_encap_type",
      "external": true,
      "loc": "net/core/lwtunnel.c:140",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278558388,
      "name": "lwtunnel_valid_encap_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588376640,
      "name": "lwtunnel_valid_encap_type",
      "external": true,
      "loc": "net/core/lwtunnel.c:140",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588376640,
      "name": "lwtunnel_valid_encap_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588089328,
      "name": "lwtunnel_valid_encap_type",
      "external": true,
      "loc": "net/core/lwtunnel.c:140",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588089328,
      "name": "lwtunnel_valid_encap_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588708816,
      "name": "lwtunnel_valid_encap_type",
      "external": true,
      "loc": "net/core/lwtunnel.c:140",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588708816,
      "name": "lwtunnel_valid_encap_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
int lwtunnel_valid_encap_type(u16 encap_type, struct netlink_ext_ack * extack)
```

```json
{
  "name": "lwtunnel_valid_encap_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588848752,
      "name": "lwtunnel_valid_encap_type",
      "external": true,
      "loc": "net/core/lwtunnel.c:140",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr",
        "net/ipv4/fib_frontend.c:rtm_to_fib_config",
        "net/ipv4/nexthop.c:rtm_to_nh_config",
        "net/ipv6/route.c:rtm_to_fib6_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588848752,
      "name": "lwtunnel_valid_encap_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int lwtunnel_valid_encap_type(u16 encap_type)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack * extack</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
