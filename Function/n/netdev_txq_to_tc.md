# Function: <code>netdev_txq_to_tc</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int netdev_txq_to_tc(struct net_device * dev, unsigned int txq)
```

```json
{
  "name": "netdev_txq_to_tc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586895259,
      "name": "netdev_txq_to_tc",
      "external": true,
      "loc": "net/core/dev.c:1968",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_set_xps_queue"
      ],
      "caller_func": [
        "net/core/net-sysfs.c:show_xps_map",
        "net/core/net-sysfs.c:show_traffic_class"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586913952,
      "name": "netdev_txq_to_tc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int netdev_txq_to_tc(struct net_device * dev, unsigned int txq)
```

```json
{
  "name": "netdev_txq_to_tc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587021130,
      "name": "netdev_txq_to_tc",
      "external": true,
      "loc": "net/core/dev.c:2002",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_set_xps_queue"
      ],
      "caller_func": [
        "net/core/net-sysfs.c:show_xps_map",
        "net/core/net-sysfs.c:show_traffic_class"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587034384,
      "name": "netdev_txq_to_tc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int netdev_txq_to_tc(struct net_device * dev, unsigned int txq)
```

```json
{
  "name": "netdev_txq_to_tc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587518490,
      "name": "netdev_txq_to_tc",
      "external": true,
      "loc": "net/core/dev.c:2021",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_set_xps_queue"
      ],
      "caller_func": [
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:traffic_class_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587520176,
      "name": "netdev_txq_to_tc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int netdev_txq_to_tc(struct net_device * dev, unsigned int txq)
```

```json
{
  "name": "netdev_txq_to_tc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587819002,
      "name": "netdev_txq_to_tc",
      "external": true,
      "loc": "net/core/dev.c:2065",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_set_xps_queue"
      ],
      "caller_func": [
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:traffic_class_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587821312,
      "name": "netdev_txq_to_tc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int netdev_txq_to_tc(struct net_device * dev, unsigned int txq)
```

```json
{
  "name": "netdev_txq_to_tc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587965272,
      "name": "netdev_txq_to_tc",
      "external": true,
      "loc": "net/core/dev.c:2113",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ],
      "caller_func": [
        "net/core/net-sysfs.c:xps_rxqs_show",
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:traffic_class_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587954464,
      "name": "netdev_txq_to_tc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int netdev_txq_to_tc(struct net_device * dev, unsigned int txq)
```

```json
{
  "name": "netdev_txq_to_tc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588279895,
      "name": "netdev_txq_to_tc",
      "external": true,
      "loc": "net/core/dev.c:2123",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ],
      "caller_func": [
        "net/core/net-sysfs.c:xps_rxqs_show",
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:traffic_class_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588265200,
      "name": "netdev_txq_to_tc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int netdev_txq_to_tc(struct net_device * dev, unsigned int txq)
```

```json
{
  "name": "netdev_txq_to_tc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588485495,
      "name": "netdev_txq_to_tc",
      "external": true,
      "loc": "net/core/dev.c:2041",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ],
      "caller_func": [
        "net/core/net-sysfs.c:xps_rxqs_show",
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:traffic_class_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588471952,
      "name": "netdev_txq_to_tc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int netdev_txq_to_tc(struct net_device * dev, unsigned int txq)
```

```json
{
  "name": "netdev_txq_to_tc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589353279,
      "name": "netdev_txq_to_tc",
      "external": true,
      "loc": "net/core/dev.c:2401",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ],
      "caller_func": [
        "net/core/net-sysfs.c:xps_rxqs_show",
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:traffic_class_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589334160,
      "name": "netdev_txq_to_tc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int netdev_txq_to_tc(struct net_device * dev, unsigned int txq)
```

```json
{
  "name": "netdev_txq_to_tc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589359423,
      "name": "netdev_txq_to_tc",
      "external": true,
      "loc": "net/core/dev.c:2426",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ],
      "caller_func": [
        "net/core/net-sysfs.c:xps_rxqs_show",
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:traffic_class_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589335200,
      "name": "netdev_txq_to_tc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int netdev_txq_to_tc(struct net_device * dev, unsigned int txq)
```

```json
{
  "name": "netdev_txq_to_tc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589243289,
      "name": "netdev_txq_to_tc",
      "external": true,
      "loc": "net/core/dev.c:2491",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ],
      "caller_func": [
        "net/core/net-sysfs.c:xps_rxqs_show",
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:traffic_class_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589230848,
      "name": "netdev_txq_to_tc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int netdev_txq_to_tc(struct net_device * dev, unsigned int txq)
```

```json
{
  "name": "netdev_txq_to_tc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589967945,
      "name": "netdev_txq_to_tc",
      "external": true,
      "loc": "net/core/dev.c:2366",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ],
      "caller_func": [
        "net/core/net-sysfs.c:xps_rxqs_show",
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:traffic_class_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589953568,
      "name": "netdev_txq_to_tc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int netdev_txq_to_tc(struct net_device * dev, unsigned int txq)
```

```json
{
  "name": "netdev_txq_to_tc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591505510,
      "name": "netdev_txq_to_tc",
      "external": true,
      "loc": "net/core/dev.c:2343",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ],
      "caller_func": [
        "net/core/net-sysfs.c:xps_rxqs_show",
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:traffic_class_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591492608,
      "name": "netdev_txq_to_tc",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int netdev_txq_to_tc(struct net_device * dev, unsigned int txq)
```

```json
{
  "name": "netdev_txq_to_tc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593282852,
      "name": "netdev_txq_to_tc",
      "external": true,
      "loc": "net/core/dev.c:2328",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ],
      "caller_func": [
        "net/core/net-sysfs.c:xps_rxqs_show",
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:traffic_class_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593260800,
      "name": "netdev_txq_to_tc",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int netdev_txq_to_tc(struct net_device * dev, unsigned int txq)
```

```json
{
  "name": "netdev_txq_to_tc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593736452,
      "name": "netdev_txq_to_tc",
      "external": true,
      "loc": "net/core/dev.c:2354",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ],
      "caller_func": [
        "net/core/net-sysfs.c:xps_rxqs_show",
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:traffic_class_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593718704,
      "name": "netdev_txq_to_tc",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int netdev_txq_to_tc(struct net_device * dev, unsigned int txq)
```

```json
{
  "name": "netdev_txq_to_tc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594517582,
      "name": "netdev_txq_to_tc",
      "external": true,
      "loc": "net/core/dev.c:2358",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ],
      "caller_func": [
        "net/core/net-sysfs.c:xps_rxqs_show",
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:traffic_class_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594500416,
      "name": "netdev_txq_to_tc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int netdev_txq_to_tc(struct net_device * dev, unsigned int txq)
```

```json
{
  "name": "netdev_txq_to_tc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501994400,
      "name": "netdev_txq_to_tc",
      "external": true,
      "loc": "net/core/dev.c:2041",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ],
      "caller_func": [
        "net/core/net-sysfs.c:xps_rxqs_show",
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:traffic_class_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501991512,
      "name": "netdev_txq_to_tc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int netdev_txq_to_tc(struct net_device * dev, unsigned int txq)
```

```json
{
  "name": "netdev_txq_to_tc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234767780,
      "name": "netdev_txq_to_tc",
      "external": true,
      "loc": "net/core/dev.c:2041",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ],
      "caller_func": [
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_setup_tc",
        "net/core/net-sysfs.c:xps_rxqs_show",
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:traffic_class_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234757780,
      "name": "netdev_txq_to_tc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int netdev_txq_to_tc(struct net_device * dev, unsigned int txq)
```

```json
{
  "name": "netdev_txq_to_tc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295455332,
      "name": "netdev_txq_to_tc",
      "external": true,
      "loc": "net/core/dev.c:2041",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ],
      "caller_func": [
        "net/core/net-sysfs.c:xps_rxqs_show",
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:traffic_class_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295432656,
      "name": "netdev_txq_to_tc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int netdev_txq_to_tc(struct net_device * dev, unsigned int txq)
```

```json
{
  "name": "netdev_txq_to_tc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278307580,
      "name": "netdev_txq_to_tc",
      "external": true,
      "loc": "net/core/dev.c:2041",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ],
      "caller_func": [
        "net/core/net-sysfs.c:xps_rxqs_show",
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:traffic_class_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278294318,
      "name": "netdev_txq_to_tc",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int netdev_txq_to_tc(struct net_device * dev, unsigned int txq)
```

```json
{
  "name": "netdev_txq_to_tc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588092279,
      "name": "netdev_txq_to_tc",
      "external": true,
      "loc": "net/core/dev.c:2041",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ],
      "caller_func": [
        "net/core/net-sysfs.c:xps_rxqs_show",
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:traffic_class_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588078736,
      "name": "netdev_txq_to_tc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int netdev_txq_to_tc(struct net_device * dev, unsigned int txq)
```

```json
{
  "name": "netdev_txq_to_tc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587805191,
      "name": "netdev_txq_to_tc",
      "external": true,
      "loc": "net/core/dev.c:2041",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ],
      "caller_func": [
        "net/core/net-sysfs.c:xps_rxqs_show",
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:traffic_class_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587792304,
      "name": "netdev_txq_to_tc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int netdev_txq_to_tc(struct net_device * dev, unsigned int txq)
```

```json
{
  "name": "netdev_txq_to_tc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588424055,
      "name": "netdev_txq_to_tc",
      "external": true,
      "loc": "net/core/dev.c:2041",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ],
      "caller_func": [
        "net/core/net-sysfs.c:xps_rxqs_show",
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:traffic_class_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588410512,
      "name": "netdev_txq_to_tc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int netdev_txq_to_tc(struct net_device * dev, unsigned int txq)
```

```json
{
  "name": "netdev_txq_to_tc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588560295,
      "name": "netdev_txq_to_tc",
      "external": true,
      "loc": "net/core/dev.c:2041",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue"
      ],
      "caller_func": [
        "net/core/net-sysfs.c:xps_rxqs_show",
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:traffic_class_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588549104,
      "name": "netdev_txq_to_tc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int netdev_txq_to_tc(struct net_device * dev, unsigned int txq)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
