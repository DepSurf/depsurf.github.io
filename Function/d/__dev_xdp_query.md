# Function: <code>__dev_xdp_query</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __dev_xdp_query(struct net_device * dev, bpf_op_t bpf_op, struct netdev_bpf * xdp)
```

```json
{
  "name": "__dev_xdp_query",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587851712,
      "name": "__dev_xdp_query",
      "external": true,
      "loc": "net/core/dev.c:7282",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_xdp_uninstall",
        "net/core/rtnetlink.c:rtnl_xdp_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587851712,
      "name": "__dev_xdp_query",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u32 __dev_xdp_query(struct net_device * dev, bpf_op_t bpf_op, enum bpf_netdev_command cmd)
```

```json
{
  "name": "__dev_xdp_query",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587992381,
      "name": "__dev_xdp_query",
      "external": true,
      "loc": "net/core/dev.c:7900",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd"
      ],
      "caller_func": [
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/rtnetlink.c:rtnl_xdp_prog_hw",
        "net/core/rtnetlink.c:rtnl_xdp_prog_drv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587952624,
      "name": "__dev_xdp_query.part.139",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071587992224,
      "name": "__dev_xdp_query",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u32 __dev_xdp_query(struct net_device * dev, bpf_op_t bpf_op, enum bpf_netdev_command cmd)
```

```json
{
  "name": "__dev_xdp_query",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588304054,
      "name": "__dev_xdp_query",
      "external": true,
      "loc": "net/core/dev.c:7997",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd"
      ],
      "caller_func": [
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/rtnetlink.c:rtnl_xdp_prog_hw",
        "net/core/rtnetlink.c:rtnl_xdp_prog_drv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588263488,
      "name": "__dev_xdp_query.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071588311498,
      "name": "__dev_xdp_query.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071588303904,
      "name": "__dev_xdp_query",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u32 __dev_xdp_query(struct net_device * dev, bpf_op_t bpf_op, enum bpf_netdev_command cmd)
```

```json
{
  "name": "__dev_xdp_query",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588510582,
      "name": "__dev_xdp_query",
      "external": true,
      "loc": "net/core/dev.c:8296",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd"
      ],
      "caller_func": [
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/rtnetlink.c:rtnl_xdp_prog_hw",
        "net/core/rtnetlink.c:rtnl_xdp_prog_drv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588468624,
      "name": "__dev_xdp_query.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071588510432,
      "name": "__dev_xdp_query",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u32 __dev_xdp_query(struct net_device * dev, bpf_op_t bpf_op, enum bpf_netdev_command cmd)
```

```json
{
  "name": "__dev_xdp_query",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589381813,
      "name": "__dev_xdp_query",
      "external": true,
      "loc": "net/core/dev.c:8709",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_xdp_uninstall",
        "net/core/dev.c:dev_xdp_uninstall"
      ],
      "caller_func": [
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/rtnetlink.c:rtnl_xdp_fill",
        "net/core/rtnetlink.c:rtnl_xdp_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589332400,
      "name": "__dev_xdp_query.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071589381664,
      "name": "__dev_xdp_query",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
u32 __dev_xdp_query(struct net_device * dev, bpf_op_t bpf_op, enum bpf_netdev_command cmd)
```

```json
{
  "name": "__dev_xdp_query",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502044144,
      "name": "__dev_xdp_query",
      "external": true,
      "loc": "net/core/dev.c:8296",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd"
      ],
      "caller_func": [
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/rtnetlink.c:rtnl_xdp_prog_hw",
        "net/core/rtnetlink.c:rtnl_xdp_prog_drv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501990920,
      "name": "__dev_xdp_query.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446603336502043968,
      "name": "__dev_xdp_query",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
u32 __dev_xdp_query(struct net_device * dev, bpf_op_t bpf_op, enum bpf_netdev_command cmd)
```

```json
{
  "name": "__dev_xdp_query",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234795892,
      "name": "__dev_xdp_query",
      "external": true,
      "loc": "net/core/dev.c:8296",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd"
      ],
      "caller_func": [
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/rtnetlink.c:rtnl_xdp_prog_hw",
        "net/core/rtnetlink.c:rtnl_xdp_prog_drv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234753028,
      "name": "__dev_xdp_query.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 3234795744,
      "name": "__dev_xdp_query",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
u32 __dev_xdp_query(struct net_device * dev, bpf_op_t bpf_op, enum bpf_netdev_command cmd)
```

```json
{
  "name": "__dev_xdp_query",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295492116,
      "name": "__dev_xdp_query",
      "external": true,
      "loc": "net/core/dev.c:8296",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd"
      ],
      "caller_func": [
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/rtnetlink.c:rtnl_xdp_prog_hw",
        "net/core/rtnetlink.c:rtnl_xdp_prog_drv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295431040,
      "name": "__dev_xdp_query.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 13835058055295491904,
      "name": "__dev_xdp_query",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
u32 __dev_xdp_query(struct net_device * dev, bpf_op_t bpf_op, enum bpf_netdev_command cmd)
```

```json
{
  "name": "__dev_xdp_query",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278330632,
      "name": "__dev_xdp_query",
      "external": true,
      "loc": "net/core/dev.c:8296",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd"
      ],
      "caller_func": [
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/rtnetlink.c:rtnl_xdp_prog_hw",
        "net/core/rtnetlink.c:rtnl_xdp_prog_drv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278291610,
      "name": "__dev_xdp_query.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446743936278330464,
      "name": "__dev_xdp_query",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u32 __dev_xdp_query(struct net_device * dev, bpf_op_t bpf_op, enum bpf_netdev_command cmd)
```

```json
{
  "name": "__dev_xdp_query",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588117318,
      "name": "__dev_xdp_query",
      "external": true,
      "loc": "net/core/dev.c:8296",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd"
      ],
      "caller_func": [
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/rtnetlink.c:rtnl_xdp_prog_hw",
        "net/core/rtnetlink.c:rtnl_xdp_prog_drv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588075408,
      "name": "__dev_xdp_query.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071588117168,
      "name": "__dev_xdp_query",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u32 __dev_xdp_query(struct net_device * dev, bpf_op_t bpf_op, enum bpf_netdev_command cmd)
```

```json
{
  "name": "__dev_xdp_query",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587830150,
      "name": "__dev_xdp_query",
      "external": true,
      "loc": "net/core/dev.c:8296",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd"
      ],
      "caller_func": [
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/rtnetlink.c:rtnl_xdp_prog_hw",
        "net/core/rtnetlink.c:rtnl_xdp_prog_drv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587788976,
      "name": "__dev_xdp_query.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071587830000,
      "name": "__dev_xdp_query",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u32 __dev_xdp_query(struct net_device * dev, bpf_op_t bpf_op, enum bpf_netdev_command cmd)
```

```json
{
  "name": "__dev_xdp_query",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588449142,
      "name": "__dev_xdp_query",
      "external": true,
      "loc": "net/core/dev.c:8296",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd"
      ],
      "caller_func": [
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/rtnetlink.c:rtnl_xdp_prog_hw",
        "net/core/rtnetlink.c:rtnl_xdp_prog_drv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588407184,
      "name": "__dev_xdp_query.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071588448992,
      "name": "__dev_xdp_query",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u32 __dev_xdp_query(struct net_device * dev, bpf_op_t bpf_op, enum bpf_netdev_command cmd)
```

```json
{
  "name": "__dev_xdp_query",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588586054,
      "name": "__dev_xdp_query",
      "external": true,
      "loc": "net/core/dev.c:8296",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd"
      ],
      "caller_func": [
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/dev.c:dev_change_xdp_fd",
        "net/core/rtnetlink.c:rtnl_xdp_prog_hw",
        "net/core/rtnetlink.c:rtnl_xdp_prog_drv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588544768,
      "name": "__dev_xdp_query.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071588585904,
      "name": "__dev_xdp_query",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void __dev_xdp_query(struct net_device * dev, bpf_op_t bpf_op, struct netdev_bpf * xdp)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum bpf_netdev_command cmd</code>
</li>
<li>
<b>Param removed. </b>
<code>struct netdev_bpf * xdp</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>u32</code>
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
u32 __dev_xdp_query(struct net_device * dev, bpf_op_t bpf_op, enum bpf_netdev_command cmd)
```
</details>
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
