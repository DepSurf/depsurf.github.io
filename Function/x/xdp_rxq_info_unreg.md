# Function: <code>xdp_rxq_info_unreg</code>

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
void xdp_rxq_info_unreg(struct xdp_rxq_info * xdp_rxq)
```

```json
{
  "name": "xdp_rxq_info_unreg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587998736,
      "name": "xdp_rxq_info_unreg",
      "external": true,
      "loc": "net/core/xdp.c:111",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "net/core/dev.c:free_netdev",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/xdp.c:xdp_rxq_info_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587998736,
      "name": "xdp_rxq_info_unreg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 657
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
void xdp_rxq_info_unreg(struct xdp_rxq_info * xdp_rxq)
```

```json
{
  "name": "xdp_rxq_info_unreg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588159296,
      "name": "xdp_rxq_info_unreg",
      "external": true,
      "loc": "net/core/xdp.c:125",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "net/core/dev.c:free_netdev",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/xdp.c:xdp_rxq_info_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588159296,
      "name": "xdp_rxq_info_unreg",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void xdp_rxq_info_unreg(struct xdp_rxq_info * xdp_rxq)
```

```json
{
  "name": "xdp_rxq_info_unreg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588482416,
      "name": "xdp_rxq_info_unreg",
      "external": true,
      "loc": "net/core/xdp.c:188",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "net/core/dev.c:free_netdev",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/xdp.c:xdp_rxq_info_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588482416,
      "name": "xdp_rxq_info_unreg",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void xdp_rxq_info_unreg(struct xdp_rxq_info * xdp_rxq)
```

```json
{
  "name": "xdp_rxq_info_unreg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588687904,
      "name": "xdp_rxq_info_unreg",
      "external": true,
      "loc": "net/core/xdp.c:162",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "net/core/dev.c:free_netdev",
        "net/core/dev.c:alloc_netdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588687904,
      "name": "xdp_rxq_info_unreg",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void xdp_rxq_info_unreg(struct xdp_rxq_info * xdp_rxq)
```

```json
{
  "name": "xdp_rxq_info_unreg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589551200,
      "name": "xdp_rxq_info_unreg",
      "external": true,
      "loc": "net/core/xdp.c:135",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "net/core/dev.c:free_netdev",
        "net/core/dev.c:netif_alloc_rx_queues",
        "net/core/xdp.c:xdp_rxq_info_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589551200,
      "name": "xdp_rxq_info_unreg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void xdp_rxq_info_unreg(struct xdp_rxq_info * xdp_rxq)
```

```json
{
  "name": "xdp_rxq_info_unreg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589559936,
      "name": "xdp_rxq_info_unreg",
      "external": true,
      "loc": "net/core/xdp.c:135",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/xen-netfront.c:xennet_create_page_pool",
        "net/core/dev.c:free_netdev",
        "net/core/dev.c:netif_alloc_rx_queues",
        "net/core/xdp.c:xdp_rxq_info_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589559936,
      "name": "xdp_rxq_info_unreg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void xdp_rxq_info_unreg(struct xdp_rxq_info * xdp_rxq)
```

```json
{
  "name": "xdp_rxq_info_unreg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589457952,
      "name": "xdp_rxq_info_unreg",
      "external": true,
      "loc": "net/core/xdp.c:135",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/xen-netfront.c:xennet_create_queues",
        "net/core/dev.c:free_netdev",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/xdp.c:xdp_rxq_info_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589457952,
      "name": "xdp_rxq_info_unreg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void xdp_rxq_info_unreg(struct xdp_rxq_info * xdp_rxq)
```

```json
{
  "name": "xdp_rxq_info_unreg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590197862,
      "name": "xdp_rxq_info_unreg",
      "external": true,
      "loc": "net/core/xdp.c:140",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "net/core/dev.c:free_netdev",
        "net/core/dev.c:alloc_netdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590197968,
      "name": "xdp_rxq_info_unreg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
void xdp_rxq_info_unreg(struct xdp_rxq_info * xdp_rxq)
```

```json
{
  "name": "xdp_rxq_info_unreg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591761710,
      "name": "xdp_rxq_info_unreg",
      "external": true,
      "loc": "net/core/xdp.c:146",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_rxq_info_reg",
        "net/core/xdp.c:__xdp_rxq_info_reg"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "net/core/dev.c:free_netdev",
        "net/core/dev.c:alloc_netdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591761440,
      "name": "xdp_rxq_info_unreg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void xdp_rxq_info_unreg(struct xdp_rxq_info * xdp_rxq)
```

```json
{
  "name": "xdp_rxq_info_unreg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593552014,
      "name": "xdp_rxq_info_unreg",
      "external": true,
      "loc": "net/core/xdp.c:146",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_rxq_info_reg",
        "net/core/xdp.c:__xdp_rxq_info_reg"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "net/core/dev.c:free_netdev",
        "net/core/dev.c:alloc_netdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593551728,
      "name": "xdp_rxq_info_unreg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void xdp_rxq_info_unreg(struct xdp_rxq_info * xdp_rxq)
```

```json
{
  "name": "xdp_rxq_info_unreg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594021363,
      "name": "xdp_rxq_info_unreg",
      "external": true,
      "loc": "net/core/xdp.c:148",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_rxq_info_reg",
        "net/core/xdp.c:__xdp_rxq_info_reg"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/virtio_net.c:virtnet_close",
        "drivers/net/virtio_net.c:virtnet_open",
        "drivers/net/virtio_net.c:virtnet_open",
        "net/core/dev.c:free_netdev",
        "net/core/dev.c:alloc_netdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594020848,
      "name": "xdp_rxq_info_unreg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void xdp_rxq_info_unreg(struct xdp_rxq_info * xdp_rxq)
```

```json
{
  "name": "xdp_rxq_info_unreg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594807491,
      "name": "xdp_rxq_info_unreg",
      "external": true,
      "loc": "net/core/xdp.c:148",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_rxq_info_reg",
        "net/core/xdp.c:__xdp_rxq_info_reg"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/virtio_net.c:virtnet_close",
        "drivers/net/virtio_net.c:virtnet_open",
        "drivers/net/virtio_net.c:virtnet_open",
        "net/core/dev.c:free_netdev",
        "net/core/dev.c:alloc_netdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594806976,
      "name": "xdp_rxq_info_unreg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void xdp_rxq_info_unreg(struct xdp_rxq_info * xdp_rxq)
```

```json
{
  "name": "xdp_rxq_info_unreg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502242232,
      "name": "xdp_rxq_info_unreg",
      "external": true,
      "loc": "net/core/xdp.c:162",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "net/core/dev.c:free_netdev",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/xdp.c:xdp_rxq_info_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502242232,
      "name": "xdp_rxq_info_unreg",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void xdp_rxq_info_unreg(struct xdp_rxq_info * xdp_rxq)
```

```json
{
  "name": "xdp_rxq_info_unreg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234987716,
      "name": "xdp_rxq_info_unreg",
      "external": true,
      "loc": "net/core/xdp.c:162",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_create_xdp_rxqs",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_destroy_xdp_rxqs",
        "net/core/dev.c:free_netdev",
        "net/core/dev.c:alloc_netdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234987716,
      "name": "xdp_rxq_info_unreg",
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
void xdp_rxq_info_unreg(struct xdp_rxq_info * xdp_rxq)
```

```json
{
  "name": "xdp_rxq_info_unreg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295734384,
      "name": "xdp_rxq_info_unreg",
      "external": true,
      "loc": "net/core/xdp.c:162",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "net/core/dev.c:free_netdev",
        "net/core/dev.c:alloc_netdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295734384,
      "name": "xdp_rxq_info_unreg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void xdp_rxq_info_unreg(struct xdp_rxq_info * xdp_rxq)
```

```json
{
  "name": "xdp_rxq_info_unreg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278482996,
      "name": "xdp_rxq_info_unreg",
      "external": true,
      "loc": "net/core/xdp.c:162",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "net/core/dev.c:free_netdev",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/xdp.c:xdp_rxq_info_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278482996,
      "name": "xdp_rxq_info_unreg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void xdp_rxq_info_unreg(struct xdp_rxq_info * xdp_rxq)
```

```json
{
  "name": "xdp_rxq_info_unreg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588294640,
      "name": "xdp_rxq_info_unreg",
      "external": true,
      "loc": "net/core/xdp.c:162",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "net/core/dev.c:free_netdev",
        "net/core/dev.c:alloc_netdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588294640,
      "name": "xdp_rxq_info_unreg",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void xdp_rxq_info_unreg(struct xdp_rxq_info * xdp_rxq)
```

```json
{
  "name": "xdp_rxq_info_unreg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588007456,
      "name": "xdp_rxq_info_unreg",
      "external": true,
      "loc": "net/core/xdp.c:162",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "net/core/dev.c:free_netdev",
        "net/core/dev.c:alloc_netdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588007456,
      "name": "xdp_rxq_info_unreg",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void xdp_rxq_info_unreg(struct xdp_rxq_info * xdp_rxq)
```

```json
{
  "name": "xdp_rxq_info_unreg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588626464,
      "name": "xdp_rxq_info_unreg",
      "external": true,
      "loc": "net/core/xdp.c:162",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "net/core/dev.c:free_netdev",
        "net/core/dev.c:alloc_netdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588626464,
      "name": "xdp_rxq_info_unreg",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void xdp_rxq_info_unreg(struct xdp_rxq_info * xdp_rxq)
```

```json
{
  "name": "xdp_rxq_info_unreg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588764880,
      "name": "xdp_rxq_info_unreg",
      "external": true,
      "loc": "net/core/xdp.c:162",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach",
        "net/core/dev.c:free_netdev",
        "net/core/dev.c:alloc_netdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588764880,
      "name": "xdp_rxq_info_unreg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void xdp_rxq_info_unreg(struct xdp_rxq_info * xdp_rxq)
```
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
