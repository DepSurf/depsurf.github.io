# Function: <code>napi_schedule_prep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "napi_schedule_prep",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585074693,
      "name": "napi_schedule_prep",
      "external": false,
      "loc": "include/linux/netdevice.h:409",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:skb_recv_done",
        "drivers/net/virtio_net.c:virtnet_netpoll",
        "drivers/net/virtio_net.c:virtnet_busy_poll",
        "drivers/net/virtio_net.c:virtnet_busy_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585119868,
      "name": "napi_schedule_prep",
      "external": false,
      "loc": "include/linux/netdevice.h:409",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:rx_refill_timeout",
        "drivers/net/xen-netfront.c:xennet_rx_interrupt",
        "drivers/net/xen-netfront.c:xennet_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586287260,
      "name": "napi_schedule_prep",
      "external": false,
      "loc": "include/linux/netdevice.h:409",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_watchdog"
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
  "name": "napi_schedule_prep",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585466397,
      "name": "napi_schedule_prep",
      "external": false,
      "loc": "include/linux/netdevice.h:414",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:virtnet_netpoll",
        "drivers/net/virtio_net.c:virtnet_busy_poll",
        "drivers/net/virtio_net.c:virtnet_busy_poll",
        "drivers/net/virtio_net.c:skb_recv_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585518215,
      "name": "napi_schedule_prep",
      "external": false,
      "loc": "include/linux/netdevice.h:414",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_rx_interrupt",
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_open",
        "drivers/net/xen-netfront.c:rx_refill_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586715068,
      "name": "napi_schedule_prep",
      "external": false,
      "loc": "include/linux/netdevice.h:414",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_watchdog",
        "net/core/dev.c:sk_busy_loop",
        "net/core/dev.c:sk_busy_loop"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
bool napi_schedule_prep(struct napi_struct * n)
```

```json
{
  "name": "napi_schedule_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586879024,
      "name": "napi_schedule_prep",
      "external": true,
      "loc": "net/core/dev.c:4924",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_rx_interrupt",
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_open",
        "drivers/net/xen-netfront.c:rx_refill_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586879024,
      "name": "napi_schedule_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
bool napi_schedule_prep(struct napi_struct * n)
```

```json
{
  "name": "napi_schedule_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587003504,
      "name": "napi_schedule_prep",
      "external": true,
      "loc": "net/core/dev.c:5160",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_rx_interrupt",
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_open",
        "drivers/net/xen-netfront.c:rx_refill_timeout",
        "net/core/gro_cells.c:gro_cells_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587003504,
      "name": "napi_schedule_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
bool napi_schedule_prep(struct napi_struct * n)
```

```json
{
  "name": "napi_schedule_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587502000,
      "name": "napi_schedule_prep",
      "external": true,
      "loc": "net/core/dev.c:5301",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:xennet_rx_interrupt",
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_open",
        "drivers/net/xen-netfront.c:rx_refill_timeout",
        "net/core/gro_cells.c:gro_cells_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587502000,
      "name": "napi_schedule_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
bool napi_schedule_prep(struct napi_struct * n)
```

```json
{
  "name": "napi_schedule_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587804384,
      "name": "napi_schedule_prep",
      "external": true,
      "loc": "net/core/dev.c:5431",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:xennet_rx_interrupt",
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:rx_refill_timeout",
        "net/core/gro_cells.c:gro_cells_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587804384,
      "name": "napi_schedule_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
bool napi_schedule_prep(struct napi_struct * n)
```

```json
{
  "name": "napi_schedule_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587939936,
      "name": "napi_schedule_prep",
      "external": true,
      "loc": "net/core/dev.c:5981",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:xennet_rx_interrupt",
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:rx_refill_timeout",
        "net/core/gro_cells.c:gro_cells_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587939936,
      "name": "napi_schedule_prep",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool napi_schedule_prep(struct napi_struct * n)
```

```json
{
  "name": "napi_schedule_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588251328,
      "name": "napi_schedule_prep",
      "external": true,
      "loc": "net/core/dev.c:5991",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:xennet_rx_interrupt",
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:rx_refill_timeout",
        "net/core/gro_cells.c:gro_cells_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588251328,
      "name": "napi_schedule_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
bool napi_schedule_prep(struct napi_struct * n)
```

```json
{
  "name": "napi_schedule_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588456544,
      "name": "napi_schedule_prep",
      "external": true,
      "loc": "net/core/dev.c:5914",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:xennet_rx_interrupt",
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:rx_refill_timeout",
        "net/core/gro_cells.c:gro_cells_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588456544,
      "name": "napi_schedule_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
bool napi_schedule_prep(struct napi_struct * n)
```

```json
{
  "name": "napi_schedule_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589324176,
      "name": "napi_schedule_prep",
      "external": true,
      "loc": "net/core/dev.c:6297",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:xennet_rx_interrupt",
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_open",
        "drivers/net/xen-netfront.c:rx_refill_timeout",
        "net/core/gro_cells.c:gro_cells_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589324176,
      "name": "napi_schedule_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
bool napi_schedule_prep(struct napi_struct * n)
```

```json
{
  "name": "napi_schedule_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589323136,
      "name": "napi_schedule_prep",
      "external": true,
      "loc": "net/core/dev.c:6398",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:xennet_rx_interrupt",
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_open",
        "drivers/net/xen-netfront.c:rx_refill_timeout",
        "net/core/dev.c:napi_poll",
        "net/core/gro_cells.c:gro_cells_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589323136,
      "name": "napi_schedule_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
bool napi_schedule_prep(struct napi_struct * n)
```

```json
{
  "name": "napi_schedule_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589218880,
      "name": "napi_schedule_prep",
      "external": true,
      "loc": "net/core/dev.c:6511",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:xennet_rx_interrupt",
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_open",
        "drivers/net/xen-netfront.c:rx_refill_timeout",
        "net/core/dev.c:__napi_poll",
        "net/core/gro_cells.c:gro_cells_receive",
        "net/mptcp/protocol.c:__mptcp_check_push",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589218880,
      "name": "napi_schedule_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
bool napi_schedule_prep(struct napi_struct * n)
```

```json
{
  "name": "napi_schedule_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589942224,
      "name": "napi_schedule_prep",
      "external": true,
      "loc": "net/core/dev.c:6497",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:xennet_handle_rx",
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_open",
        "drivers/net/xen-netfront.c:rx_refill_timeout",
        "net/core/dev.c:__napi_poll",
        "net/core/gro_cells.c:gro_cells_receive",
        "net/mptcp/protocol.c:__mptcp_check_push",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589942224,
      "name": "napi_schedule_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
bool napi_schedule_prep(struct napi_struct * n)
```

```json
{
  "name": "napi_schedule_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591475936,
      "name": "napi_schedule_prep",
      "external": true,
      "loc": "net/core/dev.c:5983",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:xennet_handle_rx",
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_open",
        "drivers/net/xen-netfront.c:rx_refill_timeout",
        "net/core/dev.c:__napi_poll",
        "net/core/gro_cells.c:gro_cells_receive",
        "net/mptcp/protocol.c:__mptcp_check_push",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591475936,
      "name": "napi_schedule_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
bool napi_schedule_prep(struct napi_struct * n)
```

```json
{
  "name": "napi_schedule_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593245648,
      "name": "napi_schedule_prep",
      "external": true,
      "loc": "net/core/dev.c:5974",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:xennet_handle_rx",
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_open",
        "drivers/net/xen-netfront.c:rx_refill_timeout",
        "net/core/dev.c:__napi_poll",
        "net/core/gro_cells.c:gro_cells_receive",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593245648,
      "name": "napi_schedule_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
bool napi_schedule_prep(struct napi_struct * n)
```

```json
{
  "name": "napi_schedule_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593706336,
      "name": "napi_schedule_prep",
      "external": true,
      "loc": "net/core/dev.c:5950",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/virtio_net.c:virtnet_xdp_set",
        "drivers/net/virtio_net.c:virtnet_xdp_set",
        "drivers/net/virtio_net.c:virtnet_xdp_set",
        "drivers/net/virtio_net.c:virtnet_xdp_set",
        "drivers/net/virtio_net.c:virtnet_set_ringparam",
        "drivers/net/virtio_net.c:virtnet_set_ringparam",
        "drivers/net/virtio_net.c:virtnet_poll_tx",
        "drivers/net/virtio_net.c:virtnet_open",
        "drivers/net/virtio_net.c:virtnet_open",
        "drivers/net/virtio_net.c:virtnet_poll",
        "drivers/net/virtio_net.c:refill_work",
        "drivers/net/virtio_net.c:skb_recv_done",
        "drivers/net/virtio_net.c:skb_xmit_done",
        "drivers/net/xen-netfront.c:xennet_handle_rx",
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_open",
        "drivers/net/xen-netfront.c:rx_refill_timeout",
        "net/core/dev.c:__napi_poll",
        "net/core/gro_cells.c:gro_cells_receive",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593706336,
      "name": "napi_schedule_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
bool napi_schedule_prep(struct napi_struct * n)
```

```json
{
  "name": "napi_schedule_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594484672,
      "name": "napi_schedule_prep",
      "external": true,
      "loc": "net/core/dev.c:6032",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/virtio_net.c:virtnet_xdp_set",
        "drivers/net/virtio_net.c:virtnet_xdp_set",
        "drivers/net/virtio_net.c:virtnet_xdp_set",
        "drivers/net/virtio_net.c:virtnet_xdp_set",
        "drivers/net/virtio_net.c:virtnet_set_ringparam",
        "drivers/net/virtio_net.c:virtnet_set_ringparam",
        "drivers/net/virtio_net.c:virtnet_poll_tx",
        "drivers/net/virtio_net.c:virtnet_open",
        "drivers/net/virtio_net.c:virtnet_open",
        "drivers/net/virtio_net.c:virtnet_poll",
        "drivers/net/virtio_net.c:refill_work",
        "drivers/net/virtio_net.c:skb_recv_done",
        "drivers/net/virtio_net.c:skb_xmit_done",
        "drivers/net/xen-netfront.c:xennet_handle_rx",
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_open",
        "drivers/net/xen-netfront.c:rx_refill_timeout",
        "net/core/dev.c:__napi_poll",
        "net/core/gro_cells.c:gro_cells_receive",
        "net/mptcp/protocol.c:mptcp_finish_join",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/subflow.c:subflow_write_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594484672,
      "name": "napi_schedule_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
bool napi_schedule_prep(struct napi_struct * n)
```

```json
{
  "name": "napi_schedule_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501996800,
      "name": "napi_schedule_prep",
      "external": true,
      "loc": "net/core/dev.c:5914",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_interrupt",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_interrupt",
        "drivers/net/xen-netfront.c:xennet_rx_interrupt",
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_open",
        "drivers/net/xen-netfront.c:rx_refill_timeout",
        "net/core/gro_cells.c:gro_cells_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501996800,
      "name": "napi_schedule_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
bool napi_schedule_prep(struct napi_struct * n)
```

```json
{
  "name": "napi_schedule_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234757880,
      "name": "napi_schedule_prep",
      "external": true,
      "loc": "net/core/dev.c:5914",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_interrupt",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_rx_interrupt",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_tx_interrupt",
        "net/core/gro_cells.c:gro_cells_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234757880,
      "name": "napi_schedule_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
bool napi_schedule_prep(struct napi_struct * n)
```

```json
{
  "name": "napi_schedule_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295410048,
      "name": "napi_schedule_prep",
      "external": true,
      "loc": "net/core/dev.c:5914",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/gro_cells.c:gro_cells_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295410048,
      "name": "napi_schedule_prep",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
bool napi_schedule_prep(struct napi_struct * n)
```

```json
{
  "name": "napi_schedule_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278279850,
      "name": "napi_schedule_prep",
      "external": true,
      "loc": "net/core/dev.c:5914",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/gro_cells.c:gro_cells_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278279850,
      "name": "napi_schedule_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
bool napi_schedule_prep(struct napi_struct * n)
```

```json
{
  "name": "napi_schedule_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588063328,
      "name": "napi_schedule_prep",
      "external": true,
      "loc": "net/core/dev.c:5914",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:xennet_rx_interrupt",
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:rx_refill_timeout",
        "net/core/gro_cells.c:gro_cells_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588063328,
      "name": "napi_schedule_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
bool napi_schedule_prep(struct napi_struct * n)
```

```json
{
  "name": "napi_schedule_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587776416,
      "name": "napi_schedule_prep",
      "external": true,
      "loc": "net/core/dev.c:5914",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/gro_cells.c:gro_cells_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587776416,
      "name": "napi_schedule_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
bool napi_schedule_prep(struct napi_struct * n)
```

```json
{
  "name": "napi_schedule_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588395104,
      "name": "napi_schedule_prep",
      "external": true,
      "loc": "net/core/dev.c:5914",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:xennet_rx_interrupt",
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:rx_refill_timeout",
        "net/core/gro_cells.c:gro_cells_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588395104,
      "name": "napi_schedule_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
bool napi_schedule_prep(struct napi_struct * n)
```

```json
{
  "name": "napi_schedule_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588531120,
      "name": "napi_schedule_prep",
      "external": true,
      "loc": "net/core/dev.c:5914",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:xennet_rx_interrupt",
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:rx_refill_timeout",
        "net/core/gro_cells.c:gro_cells_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588531120,
      "name": "napi_schedule_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
bool napi_schedule_prep(struct napi_struct * n)
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
