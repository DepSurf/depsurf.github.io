# Function: <code>napi_complete_done</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void napi_complete_done(struct napi_struct * n, int work_done)
```

```json
{
  "name": "napi_complete_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586295200,
      "name": "napi_complete_done",
      "external": true,
      "loc": "net/core/dev.c:4637",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/dev.c:net_rx_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586295200,
      "name": "napi_complete_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void napi_complete_done(struct napi_struct * n, int work_done)
```

```json
{
  "name": "napi_complete_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586722464,
      "name": "napi_complete_done",
      "external": true,
      "loc": "net/core/dev.c:4918",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:sk_busy_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586722464,
      "name": "napi_complete_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
bool napi_complete_done(struct napi_struct * n, int work_done)
```

```json
{
  "name": "napi_complete_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586908992,
      "name": "napi_complete_done",
      "external": true,
      "loc": "net/core/dev.c:4977",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/dev.c:net_rx_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586908992,
      "name": "napi_complete_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
bool napi_complete_done(struct napi_struct * n, int work_done)
```

```json
{
  "name": "napi_complete_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587041008,
      "name": "napi_complete_done",
      "external": true,
      "loc": "net/core/dev.c:5196",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/dev.c:net_rx_action",
        "net/core/gro_cells.c:gro_cell_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587041008,
      "name": "napi_complete_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
bool napi_complete_done(struct napi_struct * n, int work_done)
```

```json
{
  "name": "napi_complete_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587540960,
      "name": "napi_complete_done",
      "external": true,
      "loc": "net/core/dev.c:5337",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_poll",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/dev.c:net_rx_action",
        "net/core/gro_cells.c:gro_cell_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587540960,
      "name": "napi_complete_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
bool napi_complete_done(struct napi_struct * n, int work_done)
```

```json
{
  "name": "napi_complete_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587845088,
      "name": "napi_complete_done",
      "external": true,
      "loc": "net/core/dev.c:5467",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_poll",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/dev.c:net_rx_action",
        "net/core/gro_cells.c:gro_cell_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587845088,
      "name": "napi_complete_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
bool napi_complete_done(struct napi_struct * n, int work_done)
```

```json
{
  "name": "napi_complete_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587983424,
      "name": "napi_complete_done",
      "external": true,
      "loc": "net/core/dev.c:6017",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_poll",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/dev.c:net_rx_action",
        "net/core/gro_cells.c:gro_cell_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587983424,
      "name": "napi_complete_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
bool napi_complete_done(struct napi_struct * n, int work_done)
```

```json
{
  "name": "napi_complete_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588294224,
      "name": "napi_complete_done",
      "external": true,
      "loc": "net/core/dev.c:6027",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_poll",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/dev.c:net_rx_action",
        "net/core/gro_cells.c:gro_cell_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588294224,
      "name": "napi_complete_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
bool napi_complete_done(struct napi_struct * n, int work_done)
```

```json
{
  "name": "napi_complete_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588502480,
      "name": "napi_complete_done",
      "external": true,
      "loc": "net/core/dev.c:5950",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_poll",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/dev.c:net_rx_action",
        "net/core/gro_cells.c:gro_cell_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588502480,
      "name": "napi_complete_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
bool napi_complete_done(struct napi_struct * n, int work_done)
```

```json
{
  "name": "napi_complete_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589374144,
      "name": "napi_complete_done",
      "external": true,
      "loc": "net/core/dev.c:6333",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_poll",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/dev.c:napi_poll",
        "net/core/gro_cells.c:gro_cell_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589374144,
      "name": "napi_complete_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
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
bool napi_complete_done(struct napi_struct * n, int work_done)
```

```json
{
  "name": "napi_complete_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589378768,
      "name": "napi_complete_done",
      "external": true,
      "loc": "net/core/dev.c:6434",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_poll",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/dev.c:napi_poll",
        "net/core/dev.c:napi_poll",
        "net/core/gro_cells.c:gro_cell_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589378768,
      "name": "napi_complete_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
bool napi_complete_done(struct napi_struct * n, int work_done)
```

```json
{
  "name": "napi_complete_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589273632,
      "name": "napi_complete_done",
      "external": true,
      "loc": "net/core/dev.c:6554",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_poll",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/dev.c:__napi_poll",
        "net/core/dev.c:__napi_poll",
        "net/core/gro_cells.c:gro_cell_poll",
        "net/mptcp/protocol.c:mptcp_napi_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589273632,
      "name": "napi_complete_done",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
bool napi_complete_done(struct napi_struct * n, int work_done)
```

```json
{
  "name": "napi_complete_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590001024,
      "name": "napi_complete_done",
      "external": true,
      "loc": "net/core/dev.c:6540",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_poll",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/dev.c:__napi_poll",
        "net/core/dev.c:__napi_poll",
        "net/core/gro_cells.c:gro_cell_poll",
        "net/mptcp/protocol.c:mptcp_napi_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590001024,
      "name": "napi_complete_done",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool napi_complete_done(struct napi_struct * n, int work_done)
```

```json
{
  "name": "napi_complete_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591543648,
      "name": "napi_complete_done",
      "external": true,
      "loc": "net/core/dev.c:6026",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_poll",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/dev.c:__napi_poll",
        "net/core/dev.c:__napi_poll",
        "net/core/gro_cells.c:gro_cell_poll",
        "net/mptcp/protocol.c:mptcp_napi_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591543648,
      "name": "napi_complete_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 414
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
bool napi_complete_done(struct napi_struct * n, int work_done)
```

```json
{
  "name": "napi_complete_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593317200,
      "name": "napi_complete_done",
      "external": true,
      "loc": "net/core/dev.c:6016",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_napi_poll",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/dev.c:__napi_poll",
        "net/core/dev.c:__napi_poll",
        "net/core/gro_cells.c:gro_cell_poll",
        "net/mptcp/protocol.c:mptcp_napi_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593317200,
      "name": "napi_complete_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
bool napi_complete_done(struct napi_struct * n, int work_done)
```

```json
{
  "name": "napi_complete_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593778864,
      "name": "napi_complete_done",
      "external": true,
      "loc": "net/core/dev.c:5992",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_napi_poll",
        "drivers/net/virtio_net.c:virtnet_poll_tx",
        "drivers/net/virtio_net.c:virtnet_poll_tx",
        "drivers/net/virtio_net.c:virtnet_poll",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/dev.c:__napi_poll",
        "net/core/dev.c:__napi_poll",
        "net/core/gro_cells.c:gro_cell_poll",
        "net/mptcp/protocol.c:mptcp_napi_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593778864,
      "name": "napi_complete_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
bool napi_complete_done(struct napi_struct * n, int work_done)
```

```json
{
  "name": "napi_complete_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594559312,
      "name": "napi_complete_done",
      "external": true,
      "loc": "net/core/dev.c:6074",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_napi_poll",
        "drivers/net/virtio_net.c:virtnet_poll_tx",
        "drivers/net/virtio_net.c:virtnet_poll_tx",
        "drivers/net/virtio_net.c:virtnet_poll",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/dev.c:__napi_poll",
        "net/core/dev.c:__napi_poll",
        "net/core/gro_cells.c:gro_cell_poll",
        "net/mptcp/protocol.c:mptcp_napi_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594559312,
      "name": "napi_complete_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
bool napi_complete_done(struct napi_struct * n, int work_done)
```

```json
{
  "name": "napi_complete_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502034552,
      "name": "napi_complete_done",
      "external": true,
      "loc": "net/core/dev.c:5950",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_poll",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_poll",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/dev.c:net_rx_action",
        "net/core/gro_cells.c:gro_cell_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502034552,
      "name": "napi_complete_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
bool napi_complete_done(struct napi_struct * n, int work_done)
```

```json
{
  "name": "napi_complete_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234789492,
      "name": "napi_complete_done",
      "external": true,
      "loc": "net/core/dev.c:5950",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_poll",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_rx_mq_poll",
        "net/core/dev.c:net_rx_action",
        "net/core/gro_cells.c:gro_cell_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234789492,
      "name": "napi_complete_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
bool napi_complete_done(struct napi_struct * n, int work_done)
```

```json
{
  "name": "napi_complete_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295479760,
      "name": "napi_complete_done",
      "external": true,
      "loc": "net/core/dev.c:5950",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_poll",
        "net/core/dev.c:net_rx_action",
        "net/core/gro_cells.c:gro_cell_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295479760,
      "name": "napi_complete_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 620
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
bool napi_complete_done(struct napi_struct * n, int work_done)
```

```json
{
  "name": "napi_complete_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278323356,
      "name": "napi_complete_done",
      "external": true,
      "loc": "net/core/dev.c:5950",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_poll",
        "net/core/dev.c:net_rx_action",
        "net/core/gro_cells.c:gro_cell_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278323356,
      "name": "napi_complete_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
bool napi_complete_done(struct napi_struct * n, int work_done)
```

```json
{
  "name": "napi_complete_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588109216,
      "name": "napi_complete_done",
      "external": true,
      "loc": "net/core/dev.c:5950",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_poll",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/dev.c:net_rx_action",
        "net/core/gro_cells.c:gro_cell_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588109216,
      "name": "napi_complete_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
bool napi_complete_done(struct napi_struct * n, int work_done)
```

```json
{
  "name": "napi_complete_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587822096,
      "name": "napi_complete_done",
      "external": true,
      "loc": "net/core/dev.c:5950",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_poll",
        "net/core/dev.c:net_rx_action",
        "net/core/gro_cells.c:gro_cell_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587822096,
      "name": "napi_complete_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
bool napi_complete_done(struct napi_struct * n, int work_done)
```

```json
{
  "name": "napi_complete_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588441040,
      "name": "napi_complete_done",
      "external": true,
      "loc": "net/core/dev.c:5950",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_poll",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/dev.c:net_rx_action",
        "net/core/gro_cells.c:gro_cell_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588441040,
      "name": "napi_complete_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
bool napi_complete_done(struct napi_struct * n, int work_done)
```

```json
{
  "name": "napi_complete_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588577824,
      "name": "napi_complete_done",
      "external": true,
      "loc": "net/core/dev.c:5950",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_poll",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/dev.c:net_rx_action",
        "net/core/gro_cells.c:gro_cell_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588577824,
      "name": "napi_complete_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
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
