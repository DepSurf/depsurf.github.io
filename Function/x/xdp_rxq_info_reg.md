# Function: <code>xdp_rxq_info_reg</code>

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
int xdp_rxq_info_reg(struct xdp_rxq_info * xdp_rxq, struct net_device * dev, u32 queue_index)
```

```json
{
  "name": "xdp_rxq_info_reg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587999408,
      "name": "xdp_rxq_info_reg",
      "external": true,
      "loc": "net/core/xdp.c:136",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach",
        "net/core/dev.c:alloc_netdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587999408,
      "name": "xdp_rxq_info_reg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int xdp_rxq_info_reg(struct xdp_rxq_info * xdp_rxq, struct net_device * dev, u32 queue_index)
```

```json
{
  "name": "xdp_rxq_info_reg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588159376,
      "name": "xdp_rxq_info_reg",
      "external": true,
      "loc": "net/core/xdp.c:150",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach",
        "net/core/dev.c:alloc_netdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588159376,
      "name": "xdp_rxq_info_reg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int xdp_rxq_info_reg(struct xdp_rxq_info * xdp_rxq, struct net_device * dev, u32 queue_index)
```

```json
{
  "name": "xdp_rxq_info_reg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588482496,
      "name": "xdp_rxq_info_reg",
      "external": true,
      "loc": "net/core/xdp.c:213",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach",
        "net/core/dev.c:alloc_netdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588482496,
      "name": "xdp_rxq_info_reg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int xdp_rxq_info_reg(struct xdp_rxq_info * xdp_rxq, struct net_device * dev, u32 queue_index)
```

```json
{
  "name": "xdp_rxq_info_reg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588687984,
      "name": "xdp_rxq_info_reg",
      "external": true,
      "loc": "net/core/xdp.c:187",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach",
        "net/core/dev.c:alloc_netdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588687984,
      "name": "xdp_rxq_info_reg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int xdp_rxq_info_reg(struct xdp_rxq_info * xdp_rxq, struct net_device * dev, u32 queue_index)
```

```json
{
  "name": "xdp_rxq_info_reg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589551280,
      "name": "xdp_rxq_info_reg",
      "external": true,
      "loc": "net/core/xdp.c:160",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_alloc_rx_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589551280,
      "name": "xdp_rxq_info_reg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int xdp_rxq_info_reg(struct xdp_rxq_info * xdp_rxq, struct net_device * dev, u32 queue_index, unsigned int napi_id)
```

```json
{
  "name": "xdp_rxq_info_reg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589560016,
      "name": "xdp_rxq_info_reg",
      "external": true,
      "loc": "net/core/xdp.c:160",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_create_page_pool",
        "net/core/dev.c:netif_alloc_rx_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589560016,
      "name": "xdp_rxq_info_reg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int xdp_rxq_info_reg(struct xdp_rxq_info * xdp_rxq, struct net_device * dev, u32 queue_index, unsigned int napi_id)
```

```json
{
  "name": "xdp_rxq_info_reg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589458032,
      "name": "xdp_rxq_info_reg",
      "external": true,
      "loc": "net/core/xdp.c:160",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_create_queues",
        "net/core/dev.c:alloc_netdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589458032,
      "name": "xdp_rxq_info_reg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int xdp_rxq_info_reg(struct xdp_rxq_info * xdp_rxq, struct net_device * dev, u32 queue_index, unsigned int napi_id)
```

```json
{
  "name": "xdp_rxq_info_reg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590197728,
      "name": "xdp_rxq_info_reg",
      "external": true,
      "loc": "net/core/xdp.c:161",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:alloc_netdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590197728,
      "name": "xdp_rxq_info_reg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xdp_rxq_info_reg",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589742449,
      "name": "xdp_rxq_info_reg",
      "external": false,
      "loc": "include/net/xdp.h:364",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589797843,
      "name": "xdp_rxq_info_reg",
      "external": false,
      "loc": "include/net/xdp.h:364",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591505094,
      "name": "xdp_rxq_info_reg",
      "external": false,
      "loc": "include/net/xdp.h:364",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:alloc_netdev_mqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592166921,
      "name": "xdp_rxq_info_reg",
      "external": false,
      "loc": "include/net/xdp.h:364",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_test_run_xdp_live"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xdp_rxq_info_reg",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591360993,
      "name": "xdp_rxq_info_reg",
      "external": false,
      "loc": "include/net/xdp.h:364",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591446435,
      "name": "xdp_rxq_info_reg",
      "external": false,
      "loc": "include/net/xdp.h:364",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593274858,
      "name": "xdp_rxq_info_reg",
      "external": false,
      "loc": "include/net/xdp.h:364",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:alloc_netdev_mqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593994377,
      "name": "xdp_rxq_info_reg",
      "external": false,
      "loc": "include/net/xdp.h:364",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_test_run_xdp_live"
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
  "name": "xdp_rxq_info_reg",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591722872,
      "name": "xdp_rxq_info_reg",
      "external": false,
      "loc": "include/net/xdp.h:339",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591768416,
      "name": "xdp_rxq_info_reg",
      "external": false,
      "loc": "include/net/xdp.h:339",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:virtnet_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591861915,
      "name": "xdp_rxq_info_reg",
      "external": false,
      "loc": "include/net/xdp.h:339",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593730703,
      "name": "xdp_rxq_info_reg",
      "external": false,
      "loc": "include/net/xdp.h:339",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:alloc_netdev_mqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594371632,
      "name": "xdp_rxq_info_reg",
      "external": false,
      "loc": "include/net/xdp.h:339",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_test_run_xdp_live"
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
  "name": "xdp_rxq_info_reg",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592466680,
      "name": "xdp_rxq_info_reg",
      "external": false,
      "loc": "include/net/xdp.h:338",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592514960,
      "name": "xdp_rxq_info_reg",
      "external": false,
      "loc": "include/net/xdp.h:338",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:virtnet_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592601675,
      "name": "xdp_rxq_info_reg",
      "external": false,
      "loc": "include/net/xdp.h:338",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594510143,
      "name": "xdp_rxq_info_reg",
      "external": false,
      "loc": "include/net/xdp.h:338",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:alloc_netdev_mqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595172448,
      "name": "xdp_rxq_info_reg",
      "external": false,
      "loc": "include/net/xdp.h:338",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_test_run_xdp_live"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int xdp_rxq_info_reg(struct xdp_rxq_info * xdp_rxq, struct net_device * dev, u32 queue_index)
```

```json
{
  "name": "xdp_rxq_info_reg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502242336,
      "name": "xdp_rxq_info_reg",
      "external": true,
      "loc": "net/core/xdp.c:187",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/dev.c:alloc_netdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502242336,
      "name": "xdp_rxq_info_reg",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int xdp_rxq_info_reg(struct xdp_rxq_info * xdp_rxq, struct net_device * dev, u32 queue_index)
```

```json
{
  "name": "xdp_rxq_info_reg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234987828,
      "name": "xdp_rxq_info_reg",
      "external": true,
      "loc": "net/core/xdp.c:187",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_create_xdp_rxqs",
        "net/core/dev.c:alloc_netdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234987828,
      "name": "xdp_rxq_info_reg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int xdp_rxq_info_reg(struct xdp_rxq_info * xdp_rxq, struct net_device * dev, u32 queue_index)
```

```json
{
  "name": "xdp_rxq_info_reg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295734528,
      "name": "xdp_rxq_info_reg",
      "external": true,
      "loc": "net/core/xdp.c:187",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/dev.c:alloc_netdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295734528,
      "name": "xdp_rxq_info_reg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int xdp_rxq_info_reg(struct xdp_rxq_info * xdp_rxq, struct net_device * dev, u32 queue_index)
```

```json
{
  "name": "xdp_rxq_info_reg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278483084,
      "name": "xdp_rxq_info_reg",
      "external": true,
      "loc": "net/core/xdp.c:187",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/dev.c:alloc_netdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278483084,
      "name": "xdp_rxq_info_reg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int xdp_rxq_info_reg(struct xdp_rxq_info * xdp_rxq, struct net_device * dev, u32 queue_index)
```

```json
{
  "name": "xdp_rxq_info_reg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588294720,
      "name": "xdp_rxq_info_reg",
      "external": true,
      "loc": "net/core/xdp.c:187",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach",
        "net/core/dev.c:alloc_netdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588294720,
      "name": "xdp_rxq_info_reg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int xdp_rxq_info_reg(struct xdp_rxq_info * xdp_rxq, struct net_device * dev, u32 queue_index)
```

```json
{
  "name": "xdp_rxq_info_reg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588007536,
      "name": "xdp_rxq_info_reg",
      "external": true,
      "loc": "net/core/xdp.c:187",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach",
        "net/core/dev.c:alloc_netdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588007536,
      "name": "xdp_rxq_info_reg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int xdp_rxq_info_reg(struct xdp_rxq_info * xdp_rxq, struct net_device * dev, u32 queue_index)
```

```json
{
  "name": "xdp_rxq_info_reg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588626544,
      "name": "xdp_rxq_info_reg",
      "external": true,
      "loc": "net/core/xdp.c:187",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach",
        "net/core/dev.c:alloc_netdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588626544,
      "name": "xdp_rxq_info_reg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int xdp_rxq_info_reg(struct xdp_rxq_info * xdp_rxq, struct net_device * dev, u32 queue_index)
```

```json
{
  "name": "xdp_rxq_info_reg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588764960,
      "name": "xdp_rxq_info_reg",
      "external": true,
      "loc": "net/core/xdp.c:187",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach",
        "net/core/dev.c:alloc_netdev_mqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588764960,
      "name": "xdp_rxq_info_reg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int xdp_rxq_info_reg(struct xdp_rxq_info * xdp_rxq, struct net_device * dev, u32 queue_index)
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int napi_id</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int xdp_rxq_info_reg(struct xdp_rxq_info * xdp_rxq, struct net_device * dev, u32 queue_index, unsigned int napi_id)
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
