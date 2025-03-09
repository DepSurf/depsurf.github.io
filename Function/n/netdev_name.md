# Function: <code>netdev_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netdev_name",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583126238,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:3955",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586286684,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:3955",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:dev_disable_lro",
        "net/core/dev.c:register_netdevice"
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
  "name": "netdev_name",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583420382,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:4249",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586739150,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:4249",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:dev_disable_lro"
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
  "name": "netdev_name",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583546078,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:4203",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586924942,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:4203",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:dev_disable_lro"
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
  "name": "netdev_name",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583583948,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:4261",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587051321,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:4261",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:dev_disable_lro"
      ],
      "caller_func": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:skb_warn_bad_offload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587014928,
      "name": "netdev_name.part.82",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
  "name": "netdev_name",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583829784,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:4295",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587551744,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:4295",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:dev_disable_lro"
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
  "name": "netdev_name",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584026255,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:4402",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587858789,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:4402",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:dev_disable_lro"
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
  "name": "netdev_name",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584110671,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:4644",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587999173,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:4644",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:dev_disable_lro"
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
  "name": "netdev_name",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584299142,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:4670",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588308774,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:4670",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:dev_disable_lro"
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
  "name": "netdev_name",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584433862,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:4683",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588515033,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:4683",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:dev_disable_lro"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const char * netdev_name(const struct net_device * dev)
```

```json
{
  "name": "netdev_name",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584996022,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:4876",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589387980,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:4876",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:netdev_sync_lower_features",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:dev_disable_lro"
      ],
      "caller_func": [
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:__netdev_printk"
      ]
    },
    {
      "addr": 18446744071589877951,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:4876",
      "file": "net/ethtool/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/netlink.c:ethtool_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589897311,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:4876",
      "file": "net/ethtool/privflags.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/privflags.c:ethnl_get_priv_flags_info"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589390477,
      "name": "netdev_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const char * netdev_name(const struct net_device * dev)
```

```json
{
  "name": "netdev_name",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585118118,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5077",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589391532,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5077",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:netdev_sync_lower_features",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:dev_disable_lro"
      ],
      "caller_func": [
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:__netdev_printk"
      ]
    },
    {
      "addr": 18446744071589788225,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5077",
      "file": "net/sched/sch_frag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_frag.c:sch_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589917231,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5077",
      "file": "net/ethtool/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/netlink.c:ethtool_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589936319,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5077",
      "file": "net/ethtool/privflags.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/privflags.c:ethnl_get_priv_flags_info"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591627649,
      "name": "netdev_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const char * netdev_name(const struct net_device * dev)
```

```json
{
  "name": "netdev_name",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584998435,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5208",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589288536,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5208",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:dev_disable_lro"
      ],
      "caller_func": [
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:__netdev_printk"
      ]
    },
    {
      "addr": 18446744071589692207,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5208",
      "file": "net/sched/sch_frag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_frag.c:sch_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589824815,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5208",
      "file": "net/ethtool/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/netlink.c:ethtool_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589844670,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5208",
      "file": "net/ethtool/privflags.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/privflags.c:ethnl_get_priv_flags_info"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591571047,
      "name": "netdev_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const char * netdev_name(const struct net_device * dev)
```

```json
{
  "name": "netdev_name",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585439394,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5256",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590016055,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5256",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:dev_disable_lro"
      ],
      "caller_func": [
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:__netdev_printk"
      ]
    },
    {
      "addr": 18446744071590449937,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5256",
      "file": "net/sched/sch_frag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_frag.c:sch_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590587084,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5256",
      "file": "net/ethtool/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/netlink.c:ethtool_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590607114,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5256",
      "file": "net/ethtool/privflags.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/privflags.c:ethnl_get_priv_flags_info"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592695576,
      "name": "netdev_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const char * netdev_name(const struct net_device * dev)
```

```json
{
  "name": "netdev_name",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586575802,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5076",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591557921,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5076",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:dev_disable_lro"
      ],
      "caller_func": [
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:__netdev_printk"
      ]
    },
    {
      "addr": 18446744071594586620,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5076",
      "file": "net/core/dev_addr_lists.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev_addr_lists.c:dev_addr_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592051618,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5076",
      "file": "net/sched/sch_frag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_frag.c:sch_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592206477,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5076",
      "file": "net/ethtool/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/netlink.c:ethtool_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592227727,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5076",
      "file": "net/ethtool/privflags.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/privflags.c:ethnl_get_priv_flags_info"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594581227,
      "name": "netdev_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
  "name": "netdev_name",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587811700,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5120",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591376291,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5120",
      "file": "drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_port_debugfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593276754,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5120",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:dev_disable_lro"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593342285,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5120",
      "file": "net/core/dev_addr_lists.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev_addr_lists.c:dev_addr_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593870064,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5120",
      "file": "net/sched/sch_frag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_frag.c:sch_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594035965,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5120",
      "file": "net/ethtool/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/netlink.c:ethtool_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594059471,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5120",
      "file": "net/ethtool/privflags.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/privflags.c:ethnl_get_priv_flags_info"
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
  "name": "netdev_name",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588083428,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5164",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591782627,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5164",
      "file": "drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_port_debugfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593732594,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5164",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:dev_disable_lro"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593804045,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5164",
      "file": "net/core/dev_addr_lists.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev_addr_lists.c:dev_addr_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594245009,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5164",
      "file": "net/sched/sch_frag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_frag.c:sch_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594413757,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5164",
      "file": "net/ethtool/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/netlink.c:ethtool_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594438079,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5164",
      "file": "net/ethtool/privflags.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/privflags.c:ethnl_get_priv_flags_info"
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
  "name": "netdev_name",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588418940,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5245",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592530039,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5245",
      "file": "drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_port_debugfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594511858,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5245",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:dev_disable_lro"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594585437,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5245",
      "file": "net/core/dev_addr_lists.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev_addr_lists.c:dev_addr_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595042303,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5245",
      "file": "net/sched/sch_frag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_frag.c:sch_fragment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595216225,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5245",
      "file": "net/ethtool/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/netlink.c:ethtool_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595240435,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:5245",
      "file": "net/ethtool/privflags.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/privflags.c:ethnl_get_priv_flags_info"
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
  "name": "netdev_name",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496320104,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:4683",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502051936,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:4683",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:dev_disable_lro"
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
  "name": "netdev_name",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229654740,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:4683",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 3234803092,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:4683",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:dev_disable_lro"
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
  "name": "netdev_name",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290630316,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:4683",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295499868,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:4683",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:dev_disable_lro"
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
  "name": "netdev_name",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275372630,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:4683",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278336042,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:4683",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:dev_disable_lro"
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
  "name": "netdev_name",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584402598,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:4683",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588121769,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:4683",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:dev_disable_lro"
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
  "name": "netdev_name",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584337798,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:4683",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587834601,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:4683",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:dev_disable_lro"
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
  "name": "netdev_name",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584385510,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:4683",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588453593,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:4683",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:dev_disable_lro"
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
  "name": "netdev_name",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584491574,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:4683",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588590500,
      "name": "netdev_name",
      "external": false,
      "loc": "include/linux/netdevice.h:4683",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:skb_warn_bad_offload",
        "net/core/dev.c:dev_disable_lro"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
const char * netdev_name(const struct net_device * dev)
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
const char * netdev_name(const struct net_device * dev)
```
</details>
</li>
</ul>
