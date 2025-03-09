# Function: <code>netdev_reg_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netdev_reg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583126180,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:3962",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586290207,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:3962",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
  "name": "netdev_reg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583420324,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:4256",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586739036,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:4256",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
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
  "name": "netdev_reg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583546020,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:4210",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586924828,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:4210",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const char * netdev_reg_state(const struct net_device * dev)
```

```json
{
  "name": "netdev_reg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583583754,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:4273",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587048498,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:4273",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:dev_disable_lro"
      ],
      "caller_func": [
        "net/core/dev.c:register_netdevice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587003344,
      "name": "netdev_reg_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
  "name": "netdev_reg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583829578,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:4307",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587551669,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:4307",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
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
  "name": "netdev_reg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584026222,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:4414",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587858754,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:4414",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
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
  "name": "netdev_reg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584110638,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:4656",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587999138,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:4656",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const char * netdev_reg_state(const struct net_device * dev)
```

```json
{
  "name": "netdev_reg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584299118,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:4682",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588308737,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:4682",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:dev_disable_lro"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588252416,
      "name": "netdev_reg_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const char * netdev_reg_state(const struct net_device * dev)
```

```json
{
  "name": "netdev_reg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584433838,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:4695",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588515008,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:4695",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:dev_disable_lro"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588457632,
      "name": "netdev_reg_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const char * netdev_reg_state(const struct net_device * dev)
```

```json
{
  "name": "netdev_reg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584995998,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:4888",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589387955,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:4888",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:netdev_sync_lower_features",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:dev_disable_lro"
      ],
      "caller_func": [
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:__netdev_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589390402,
      "name": "netdev_reg_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
const char * netdev_reg_state(const struct net_device * dev)
```

```json
{
  "name": "netdev_reg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585118094,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:5089",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589391507,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:5089",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:netdev_sync_lower_features",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:dev_disable_lro"
      ],
      "caller_func": [
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:__netdev_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591627574,
      "name": "netdev_reg_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
const char * netdev_reg_state(const struct net_device * dev)
```

```json
{
  "name": "netdev_reg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584998411,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:5220",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589288511,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:5220",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:dev_disable_lro"
      ],
      "caller_func": [
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:__netdev_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591570972,
      "name": "netdev_reg_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
const char * netdev_reg_state(const struct net_device * dev)
```

```json
{
  "name": "netdev_reg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585439371,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:5268",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590016030,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:5268",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:dev_disable_lro",
        "net/core/dev.c:dev_disable_lro"
      ],
      "caller_func": [
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:__netdev_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592696086,
      "name": "netdev_reg_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
const char * netdev_reg_state(const struct net_device * dev)
```

```json
{
  "name": "netdev_reg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586575748,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:5088",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591557905,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:5088",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:dev_disable_lro",
        "net/core/dev.c:dev_disable_lro"
      ],
      "caller_func": [
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:__netdev_printk"
      ]
    },
    {
      "addr": 18446744071591564356,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:5088",
      "file": "net/core/dev_addr_lists.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev_addr_lists.c:dev_addr_check"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594581803,
      "name": "netdev_reg_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
  "name": "netdev_reg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587811684,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:5127",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593276703,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:5127",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:dev_disable_lro",
        "net/core/dev.c:dev_disable_lro"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593342266,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:5127",
      "file": "net/core/dev_addr_lists.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev_addr_lists.c:dev_addr_check"
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
  "name": "netdev_reg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588083412,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:5171",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593732543,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:5171",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:dev_disable_lro",
        "net/core/dev.c:dev_disable_lro"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593804026,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:5171",
      "file": "net/core/dev_addr_lists.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev_addr_lists.c:dev_addr_check"
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
  "name": "netdev_reg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588418924,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:5252",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594511807,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:5252",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:generic_xdp_install",
        "net/core/dev.c:dev_disable_lro",
        "net/core/dev.c:dev_disable_lro"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594585418,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:5252",
      "file": "net/core/dev_addr_lists.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev_addr_lists.c:dev_addr_check"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
const char * netdev_reg_state(const struct net_device * dev)
```

```json
{
  "name": "netdev_reg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496320140,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:4695",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502048312,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:4695",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:dev_disable_lro"
      ],
      "caller_func": [
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:__netdev_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501982544,
      "name": "netdev_reg_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline ❓</summary>

```c
const char * netdev_reg_state(const struct net_device * dev)
```

```json
{
  "name": "netdev_reg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229654784,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:4695",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 3234801640,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:4695",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:dev_disable_lro"
      ],
      "caller_func": [
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:__netdev_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234736168,
      "name": "netdev_reg_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
const char * netdev_reg_state(const struct net_device * dev)
```

```json
{
  "name": "netdev_reg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290630372,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:4695",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295497684,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:4695",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:dev_disable_lro"
      ],
      "caller_func": [
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:__netdev_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295412752,
      "name": "netdev_reg_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Duplicate, Selective Inline ❓</summary>

```c
const char * netdev_reg_state(const struct net_device * dev)
```

```json
{
  "name": "netdev_reg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275372670,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:4695",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278334564,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:4695",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:dev_disable_lro"
      ],
      "caller_func": [
        "net/core/dev.c:__netdev_printk",
        "net/core/dev.c:__netdev_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278280902,
      "name": "netdev_reg_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const char * netdev_reg_state(const struct net_device * dev)
```

```json
{
  "name": "netdev_reg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584402574,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:4695",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588121744,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:4695",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:dev_disable_lro"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588064416,
      "name": "netdev_reg_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const char * netdev_reg_state(const struct net_device * dev)
```

```json
{
  "name": "netdev_reg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584337774,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:4695",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587834576,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:4695",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:dev_disable_lro"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587777504,
      "name": "netdev_reg_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const char * netdev_reg_state(const struct net_device * dev)
```

```json
{
  "name": "netdev_reg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584385486,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:4695",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588453568,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:4695",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:dev_disable_lro"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588396192,
      "name": "netdev_reg_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const char * netdev_reg_state(const struct net_device * dev)
```

```json
{
  "name": "netdev_reg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584491550,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:4695",
      "file": "lib/dynamic_debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dynamic_debug.c:__dynamic_netdev_dbg",
        "lib/dynamic_debug.c:__dynamic_netdev_dbg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588590475,
      "name": "netdev_reg_state",
      "external": false,
      "loc": "include/linux/netdevice.h:4695",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:__netdev_update_features",
        "net/core/dev.c:dev_disable_lro"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588532608,
      "name": "netdev_reg_state",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
const char * netdev_reg_state(const struct net_device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
const char * netdev_reg_state(const struct net_device * dev)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
const char * netdev_reg_state(const struct net_device * dev)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
const char * netdev_reg_state(const struct net_device * dev)
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
