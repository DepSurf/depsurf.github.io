# Function: <code>fib6_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int fib6_add(struct fib6_node * root, struct rt6_info * rt, struct nl_info * info, struct mx6_config * mxc)
```

```json
{
  "name": "fib6_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587082272,
      "name": "fib6_add",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:943",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_ins_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587082272,
      "name": "fib6_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2658
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int fib6_add(struct fib6_node * root, struct rt6_info * rt, struct nl_info * info, struct mx6_config * mxc)
```

```json
{
  "name": "fib6_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587532848,
      "name": "fib6_add",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:945",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_ins_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587532848,
      "name": "fib6_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2549
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int fib6_add(struct fib6_node * root, struct rt6_info * rt, struct nl_info * info, struct mx6_config * mxc)
```

```json
{
  "name": "fib6_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587737216,
      "name": "fib6_add",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:951",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_ins_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587737216,
      "name": "fib6_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2618
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int fib6_add(struct fib6_node * root, struct rt6_info * rt, struct nl_info * info, struct mx6_config * mxc, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587891216,
      "name": "fib6_add",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:986",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_ins_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587891216,
      "name": "fib6_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2726
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int fib6_add(struct fib6_node * root, struct rt6_info * rt, struct nl_info * info, struct mx6_config * mxc, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588425792,
      "name": "fib6_add",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1132",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_ins_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588425792,
      "name": "fib6_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2976
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int fib6_add(struct fib6_node * root, struct fib6_info * rt, struct nl_info * info, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib6_add",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1199",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_ins_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588791991,
      "name": "fib6_add.cold.37",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071588787408,
      "name": "fib6_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2761
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int fib6_add(struct fib6_node * root, struct fib6_info * rt, struct nl_info * info, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib6_add",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1233",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_ins_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589012439,
      "name": "fib6_add.cold.38",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071589007792,
      "name": "fib6_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2761
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
int fib6_add(struct fib6_node * root, struct fib6_info * rt, struct nl_info * info, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib6_add",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1302",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_ins_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589464570,
      "name": "fib6_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071589461376,
      "name": "fib6_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1032
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int fib6_add(struct fib6_node * root, struct fib6_info * rt, struct nl_info * info, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib6_add",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1303",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_ins_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589688566,
      "name": "fib6_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071589685728,
      "name": "fib6_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1043
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int fib6_add(struct fib6_node * root, struct fib6_info * rt, struct nl_info * info, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib6_add",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1368",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_add",
        "net/ipv6/route.c:ip6_ins_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590704742,
      "name": "fib6_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071590701968,
      "name": "fib6_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1428
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int fib6_add(struct fib6_node * root, struct fib6_info * rt, struct nl_info * info, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib6_add",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1371",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_add",
        "net/ipv6/route.c:ip6_ins_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591636445,
      "name": "fib6_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071590762512,
      "name": "fib6_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1428
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int fib6_add(struct fib6_node * root, struct fib6_info * rt, struct nl_info * info, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib6_add",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1372",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_add",
        "net/ipv6/route.c:ip6_ins_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591579870,
      "name": "fib6_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071590689392,
      "name": "fib6_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1453
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
int fib6_add(struct fib6_node * root, struct fib6_info * rt, struct nl_info * info, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib6_add",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1374",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_add",
        "net/ipv6/route.c:ip6_ins_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592739689,
      "name": "fib6_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071591505360,
      "name": "fib6_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1359
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
int fib6_add(struct fib6_node * root, struct fib6_info * rt, struct nl_info * info, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib6_add",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1375",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_add",
        "net/ipv6/route.c:ip6_ins_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594626288,
      "name": "fib6_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071593190240,
      "name": "fib6_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1394
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
int fib6_add(struct fib6_node * root, struct fib6_info * rt, struct nl_info * info, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595089536,
      "name": "fib6_add",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1374",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_add",
        "net/ipv6/route.c:ip6_ins_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595089536,
      "name": "fib6_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1373
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
int fib6_add(struct fib6_node * root, struct fib6_info * rt, struct nl_info * info, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595483280,
      "name": "fib6_add",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1374",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_add",
        "net/ipv6/route.c:ip6_ins_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595483280,
      "name": "fib6_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1364
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
int fib6_add(struct fib6_node * root, struct fib6_info * rt, struct nl_info * info, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596325904,
      "name": "fib6_add",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1374",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_add",
        "net/ipv6/route.c:ip6_ins_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596325904,
      "name": "fib6_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1362
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
int fib6_add(struct fib6_node * root, struct fib6_info * rt, struct nl_info * info, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503375144,
      "name": "fib6_add",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1303",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_ins_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503375144,
      "name": "fib6_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 916
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
int fib6_add(struct fib6_node * root, struct fib6_info * rt, struct nl_info * info, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236038980,
      "name": "fib6_add",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1303",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_ins_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236038980,
      "name": "fib6_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 996
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
int fib6_add(struct fib6_node * root, struct fib6_info * rt, struct nl_info * info, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297145696,
      "name": "fib6_add",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1303",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_ins_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297145696,
      "name": "fib6_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1528
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
int fib6_add(struct fib6_node * root, struct fib6_info * rt, struct nl_info * info, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279377442,
      "name": "fib6_add",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1303",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_ins_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279377442,
      "name": "fib6_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 856
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int fib6_add(struct fib6_node * root, struct fib6_info * rt, struct nl_info * info, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib6_add",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1303",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_ins_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589292934,
      "name": "fib6_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071589290096,
      "name": "fib6_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1043
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int fib6_add(struct fib6_node * root, struct fib6_info * rt, struct nl_info * info, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib6_add",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1303",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_ins_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589017926,
      "name": "fib6_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071589015088,
      "name": "fib6_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1043
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int fib6_add(struct fib6_node * root, struct fib6_info * rt, struct nl_info * info, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib6_add",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1303",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_ins_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589729798,
      "name": "fib6_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071589726960,
      "name": "fib6_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1043
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int fib6_add(struct fib6_node * root, struct fib6_info * rt, struct nl_info * info, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fib6_add",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:1303",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_ins_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589780166,
      "name": "fib6_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071589777328,
      "name": "fib6_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1043
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct mx6_config * mxc</code>
</li>
<li>
<b>Param reordered. </b>
<code>root, rt, info, mxc, extack</code> ➡️ <code>root, rt, info, extack</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct rt6_info * rt</code> ➡️ <code>struct fib6_info * rt</code>
</li>
</ul>
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
