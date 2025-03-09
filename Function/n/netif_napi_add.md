# Function: <code>netif_napi_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void netif_napi_add(struct net_device * dev, struct napi_struct * napi, int (*)(struct napi_struct *, int) poll, int weight)
```

```json
{
  "name": "netif_napi_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586274704,
      "name": "netif_napi_add",
      "external": true,
      "loc": "net/core/dev.c:4734",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586274704,
      "name": "netif_napi_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
void netif_napi_add(struct net_device * dev, struct napi_struct * napi, int (*)(struct napi_struct *, int) poll, int weight)
```

```json
{
  "name": "netif_napi_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586704464,
      "name": "netif_napi_add",
      "external": true,
      "loc": "net/core/dev.c:5073",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586704464,
      "name": "netif_napi_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
void netif_napi_add(struct net_device * dev, struct napi_struct * napi, int (*)(struct napi_struct *, int) poll, int weight)
```

```json
{
  "name": "netif_napi_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586887376,
      "name": "netif_napi_add",
      "external": true,
      "loc": "net/core/dev.c:5222",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586887376,
      "name": "netif_napi_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 399
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
void netif_napi_add(struct net_device * dev, struct napi_struct * napi, int (*)(struct napi_struct *, int) poll, int weight)
```

```json
{
  "name": "netif_napi_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587011872,
      "name": "netif_napi_add",
      "external": true,
      "loc": "net/core/dev.c:5426",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587011872,
      "name": "netif_napi_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
void netif_napi_add(struct net_device * dev, struct napi_struct * napi, int (*)(struct napi_struct *, int) poll, int weight)
```

```json
{
  "name": "netif_napi_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587509824,
      "name": "netif_napi_add",
      "external": true,
      "loc": "net/core/dev.c:5567",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587509824,
      "name": "netif_napi_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
void netif_napi_add(struct net_device * dev, struct napi_struct * napi, int (*)(struct napi_struct *, int) poll, int weight)
```

```json
{
  "name": "netif_napi_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netif_napi_add",
      "external": true,
      "loc": "net/core/dev.c:5697",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587860533,
      "name": "netif_napi_add.cold.160",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071587829616,
      "name": "netif_napi_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
void netif_napi_add(struct net_device * dev, struct napi_struct * napi, int (*)(struct napi_struct *, int) poll, int weight)
```

```json
{
  "name": "netif_napi_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587963600,
      "name": "netif_napi_add",
      "external": true,
      "loc": "net/core/dev.c:6261",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach",
        "drivers/net/xen-netfront.c:xennet_create_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587963600,
      "name": "netif_napi_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 450
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
void netif_napi_add(struct net_device * dev, struct napi_struct * napi, int (*)(struct napi_struct *, int) poll, int weight)
```

```json
{
  "name": "netif_napi_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netif_napi_add",
      "external": true,
      "loc": "net/core/dev.c:6271",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach",
        "drivers/net/xen-netfront.c:xennet_create_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588311946,
      "name": "netif_napi_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071588277472,
      "name": "netif_napi_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
void netif_napi_add(struct net_device * dev, struct napi_struct * napi, int (*)(struct napi_struct *, int) poll, int weight)
```

```json
{
  "name": "netif_napi_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netif_napi_add",
      "external": true,
      "loc": "net/core/dev.c:6207",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach",
        "drivers/net/xen-netfront.c:xennet_create_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588518340,
      "name": "netif_napi_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071588483120,
      "name": "netif_napi_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
void netif_napi_add(struct net_device * dev, struct napi_struct * napi, int (*)(struct napi_struct *, int) poll, int weight)
```

```json
{
  "name": "netif_napi_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netif_napi_add",
      "external": true,
      "loc": "net/core/dev.c:6597",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_create_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589392192,
      "name": "netif_napi_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071589352400,
      "name": "netif_napi_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void netif_napi_add(struct net_device * dev, struct napi_struct * napi, int (*)(struct napi_struct *, int) poll, int weight)
```

```json
{
  "name": "netif_napi_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netif_napi_add",
      "external": true,
      "loc": "net/core/dev.c:6724",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_create_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591629392,
      "name": "netif_napi_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071589357792,
      "name": "netif_napi_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
void netif_napi_add(struct net_device * dev, struct napi_struct * napi, int (*)(struct napi_struct *, int) poll, int weight)
```

```json
{
  "name": "netif_napi_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netif_napi_add",
      "external": true,
      "loc": "net/core/dev.c:6889",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_create_queues",
        "net/mptcp/protocol.c:mptcp_proto_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591572834,
      "name": "netif_napi_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071589256096,
      "name": "netif_napi_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 550
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
void netif_napi_add(struct net_device * dev, struct napi_struct * napi, int (*)(struct napi_struct *, int) poll, int weight)
```

```json
{
  "name": "netif_napi_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netif_napi_add",
      "external": true,
      "loc": "net/core/dev.c:6875",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_proto_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592698604,
      "name": "netif_napi_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071589981648,
      "name": "netif_napi_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 667
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
  "name": "netif_napi_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589797907,
      "name": "netif_napi_add",
      "external": false,
      "loc": "include/linux/netdevice.h:2560",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591993949,
      "name": "netif_napi_add",
      "external": false,
      "loc": "include/linux/netdevice.h:2560",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netif_napi_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591446495,
      "name": "netif_napi_add",
      "external": false,
      "loc": "include/linux/netdevice.h:2586",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593807849,
      "name": "netif_napi_add",
      "external": false,
      "loc": "include/linux/netdevice.h:2586",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netif_napi_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591861975,
      "name": "netif_napi_add",
      "external": false,
      "loc": "include/linux/netdevice.h:2639",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594180073,
      "name": "netif_napi_add",
      "external": false,
      "loc": "include/linux/netdevice.h:2639",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netif_napi_add",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592601735,
      "name": "netif_napi_add",
      "external": false,
      "loc": "include/linux/netdevice.h:2707",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594976633,
      "name": "netif_napi_add",
      "external": false,
      "loc": "include/linux/netdevice.h:2707",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void netif_napi_add(struct net_device * dev, struct napi_struct * napi, int (*)(struct napi_struct *, int) poll, int weight)
```

```json
{
  "name": "netif_napi_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502011824,
      "name": "netif_napi_add",
      "external": true,
      "loc": "net/core/dev.c:6207",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_init",
        "drivers/net/xen-netfront.c:xennet_create_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502011824,
      "name": "netif_napi_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 628
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
void netif_napi_add(struct net_device * dev, struct napi_struct * napi, int (*)(struct napi_struct *, int) poll, int weight)
```

```json
{
  "name": "netif_napi_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234747584,
      "name": "netif_napi_add",
      "external": true,
      "loc": "net/core/dev.c:6207",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_init",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_probe",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234747584,
      "name": "netif_napi_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
void netif_napi_add(struct net_device * dev, struct napi_struct * napi, int (*)(struct napi_struct *, int) poll, int weight)
```

```json
{
  "name": "netif_napi_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295425904,
      "name": "netif_napi_add",
      "external": true,
      "loc": "net/core/dev.c:6207",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295425904,
      "name": "netif_napi_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 672
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
void netif_napi_add(struct net_device * dev, struct napi_struct * napi, int (*)(struct napi_struct *, int) poll, int weight)
```

```json
{
  "name": "netif_napi_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278301532,
      "name": "netif_napi_add",
      "external": true,
      "loc": "net/core/dev.c:6207",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278301532,
      "name": "netif_napi_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
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
void netif_napi_add(struct net_device * dev, struct napi_struct * napi, int (*)(struct napi_struct *, int) poll, int weight)
```

```json
{
  "name": "netif_napi_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netif_napi_add",
      "external": true,
      "loc": "net/core/dev.c:6207",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach",
        "drivers/net/xen-netfront.c:xennet_create_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588125076,
      "name": "netif_napi_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071588089904,
      "name": "netif_napi_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
void netif_napi_add(struct net_device * dev, struct napi_struct * napi, int (*)(struct napi_struct *, int) poll, int weight)
```

```json
{
  "name": "netif_napi_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netif_napi_add",
      "external": true,
      "loc": "net/core/dev.c:6207",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587837908,
      "name": "netif_napi_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071587802848,
      "name": "netif_napi_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
void netif_napi_add(struct net_device * dev, struct napi_struct * napi, int (*)(struct napi_struct *, int) poll, int weight)
```

```json
{
  "name": "netif_napi_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netif_napi_add",
      "external": true,
      "loc": "net/core/dev.c:6207",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach",
        "drivers/net/xen-netfront.c:xennet_create_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588456900,
      "name": "netif_napi_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071588421680,
      "name": "netif_napi_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
void netif_napi_add(struct net_device * dev, struct napi_struct * napi, int (*)(struct napi_struct *, int) poll, int weight)
```

```json
{
  "name": "netif_napi_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netif_napi_add",
      "external": true,
      "loc": "net/core/dev.c:6207",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_attach",
        "drivers/net/xen-netfront.c:xennet_create_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588592658,
      "name": "netif_napi_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071588544336,
      "name": "netif_napi_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void netif_napi_add(struct net_device * dev, struct napi_struct * napi, int (*)(struct napi_struct *, int) poll, int weight)
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
