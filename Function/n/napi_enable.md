# Function: <code>napi_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "napi_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585077557,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:506",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585123221,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:506",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:xennet_open"
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
  "name": "napi_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585468997,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:510",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585516245,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:510",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:xennet_open"
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
  "name": "napi_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585704452,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:500",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_open"
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
  "name": "napi_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585790878,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:500",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:xennet_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587207834,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:500",
      "file": "net/core/gro_cells.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "napi_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586185416,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:500",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586229548,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:500",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:xennet_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587722161,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:500",
      "file": "net/core/gro_cells.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "napi_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586438322,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:502",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586485656,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:502",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:talk_to_netback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588055757,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:502",
      "file": "net/core/gro_cells.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "napi_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586585400,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:513",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586632317,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:513",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_create_queues",
        "drivers/net/xen-netfront.c:xennet_create_queues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588231661,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:513",
      "file": "net/core/gro_cells.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "napi_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586838546,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:510",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586885690,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:510",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_create_queues",
        "drivers/net/xen-netfront.c:xennet_create_queues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588620416,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:510",
      "file": "net/core/gro_cells.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "napi_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586986666,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:514",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587031674,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:514",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_create_queues",
        "drivers/net/xen-netfront.c:xennet_create_queues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588842448,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:514",
      "file": "net/core/gro_cells.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "napi_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587820700,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:519",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587857947,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:519",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_create_queues",
        "drivers/net/xen-netfront.c:xennet_create_queues",
        "drivers/net/xen-netfront.c:xennet_open",
        "drivers/net/xen-netfront.c:xennet_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589726247,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:519",
      "file": "net/core/gro_cells.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "napi_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587878942,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:514",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587916275,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:514",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_create_queues",
        "drivers/net/xen-netfront.c:xennet_create_queues",
        "drivers/net/xen-netfront.c:xennet_open",
        "drivers/net/xen-netfront.c:xennet_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589761223,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:514",
      "file": "net/core/gro_cells.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void napi_enable(struct napi_struct * n)
```

```json
{
  "name": "napi_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589236064,
      "name": "napi_enable",
      "external": true,
      "loc": "net/core/dev.c:6950",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_create_queues",
        "drivers/net/xen-netfront.c:xennet_open",
        "net/mptcp/protocol.c:mptcp_proto_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589236064,
      "name": "napi_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void napi_enable(struct napi_struct * n)
```

```json
{
  "name": "napi_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589942288,
      "name": "napi_enable",
      "external": true,
      "loc": "net/core/dev.c:6936",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_open",
        "net/mptcp/protocol.c:mptcp_proto_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589942288,
      "name": "napi_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void napi_enable(struct napi_struct * n)
```

```json
{
  "name": "napi_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591476032,
      "name": "napi_enable",
      "external": true,
      "loc": "net/core/dev.c:6431",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_open",
        "net/mptcp/protocol.c:mptcp_proto_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591476032,
      "name": "napi_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void napi_enable(struct napi_struct * n)
```

```json
{
  "name": "napi_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593245760,
      "name": "napi_enable",
      "external": true,
      "loc": "net/core/dev.c:6418",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_open",
        "net/mptcp/protocol.c:mptcp_proto_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593245760,
      "name": "napi_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void napi_enable(struct napi_struct * n)
```

```json
{
  "name": "napi_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593706448,
      "name": "napi_enable",
      "external": true,
      "loc": "net/core/dev.c:6399",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:virtnet_xdp_set",
        "drivers/net/virtio_net.c:virtnet_xdp_set",
        "drivers/net/virtio_net.c:virtnet_xdp_set",
        "drivers/net/virtio_net.c:virtnet_xdp_set",
        "drivers/net/virtio_net.c:virtnet_set_ringparam",
        "drivers/net/virtio_net.c:virtnet_set_ringparam",
        "drivers/net/virtio_net.c:virtnet_open",
        "drivers/net/virtio_net.c:virtnet_open",
        "drivers/net/virtio_net.c:refill_work",
        "drivers/net/xen-netfront.c:xennet_open",
        "net/mptcp/protocol.c:mptcp_proto_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593706448,
      "name": "napi_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void napi_enable(struct napi_struct * n)
```

```json
{
  "name": "napi_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594484784,
      "name": "napi_enable",
      "external": true,
      "loc": "net/core/dev.c:6515",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:virtnet_xdp_set",
        "drivers/net/virtio_net.c:virtnet_xdp_set",
        "drivers/net/virtio_net.c:virtnet_xdp_set",
        "drivers/net/virtio_net.c:virtnet_xdp_set",
        "drivers/net/virtio_net.c:virtnet_set_ringparam",
        "drivers/net/virtio_net.c:virtnet_set_ringparam",
        "drivers/net/virtio_net.c:virtnet_open",
        "drivers/net/virtio_net.c:virtnet_open",
        "drivers/net/virtio_net.c:refill_work",
        "drivers/net/xen-netfront.c:xennet_open",
        "net/mptcp/protocol.c:mptcp_proto_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594484784,
      "name": "napi_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "napi_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499979852,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:514",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500003184,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:514",
      "file": "drivers/net/ethernet/broadcom/bgmac.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500029500,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:514",
      "file": "drivers/net/ethernet/freescale/fec_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_resume",
        "drivers/net/ethernet/freescale/fec_main.c:fec_resume",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500149288,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:514",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_create_queues",
        "drivers/net/xen-netfront.c:xennet_create_queues",
        "drivers/net/xen-netfront.c:xennet_open",
        "drivers/net/xen-netfront.c:xennet_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502414700,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:514",
      "file": "net/core/gro_cells.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline ❓</summary>

```c
void napi_enable(struct napi_struct * n)
```

```json
{
  "name": "napi_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232511400,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:514",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 3232549980,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:514",
      "file": "drivers/net/ethernet/freescale/fec_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_resume",
        "drivers/net/ethernet/freescale/fec_main.c:fec_resume",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work"
      ],
      "caller_func": []
    },
    {
      "addr": 3232590028,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:514",
      "file": "drivers/net/ethernet/ti/cpsw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open"
      ]
    },
    {
      "addr": 3235150832,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:514",
      "file": "net/core/gro_cells.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3232590028,
      "name": "napi_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "napi_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293302724,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:514",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295966284,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:514",
      "file": "net/core/gro_cells.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "napi_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277057222,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:514",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278621316,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:514",
      "file": "net/core/gro_cells.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "napi_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586743690,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:514",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586789018,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:514",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_create_queues",
        "drivers/net/xen-netfront.c:xennet_create_queues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588448832,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:514",
      "file": "net/core/gro_cells.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "napi_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586610906,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:514",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588161520,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:514",
      "file": "net/core/gro_cells.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "napi_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586941226,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:514",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586986234,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:514",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_create_queues",
        "drivers/net/xen-netfront.c:xennet_create_queues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588781008,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:514",
      "file": "net/core/gro_cells.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "napi_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587043434,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:514",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587093434,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:514",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_create_queues",
        "drivers/net/xen-netfront.c:xennet_create_queues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588921600,
      "name": "napi_enable",
      "external": false,
      "loc": "include/linux/netdevice.h:514",
      "file": "net/core/gro_cells.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void napi_enable(struct napi_struct * n)
```
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void napi_enable(struct napi_struct * n)
```
</details>
</li>
</ul>
