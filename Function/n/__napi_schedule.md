# Function: <code>__napi_schedule</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __napi_schedule(struct napi_struct * n)
```

```json
{
  "name": "__napi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586287152,
      "name": "__napi_schedule",
      "external": true,
      "loc": "net/core/dev.c:4605",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:skb_recv_done",
        "drivers/net/virtio_net.c:virtnet_netpoll",
        "drivers/net/virtio_net.c:virtnet_busy_poll",
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:rx_refill_timeout",
        "drivers/net/xen-netfront.c:xennet_rx_interrupt",
        "drivers/net/xen-netfront.c:xennet_open",
        "net/core/dev.c:napi_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586287152,
      "name": "__napi_schedule",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __napi_schedule(struct napi_struct * n)
```

```json
{
  "name": "__napi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586714960,
      "name": "__napi_schedule",
      "external": true,
      "loc": "net/core/dev.c:4886",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:virtnet_netpoll",
        "drivers/net/virtio_net.c:virtnet_busy_poll",
        "drivers/net/virtio_net.c:skb_recv_done",
        "drivers/net/xen-netfront.c:xennet_rx_interrupt",
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_open",
        "drivers/net/xen-netfront.c:rx_refill_timeout",
        "net/core/dev.c:napi_watchdog",
        "net/core/dev.c:sk_busy_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586714960,
      "name": "__napi_schedule",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void __napi_schedule(struct napi_struct * n)
```

```json
{
  "name": "__napi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586900800,
      "name": "__napi_schedule",
      "external": true,
      "loc": "net/core/dev.c:4905",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_rx_interrupt",
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_open",
        "drivers/net/xen-netfront.c:rx_refill_timeout",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_complete_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586900800,
      "name": "__napi_schedule",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void __napi_schedule(struct napi_struct * n)
```

```json
{
  "name": "__napi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587026096,
      "name": "__napi_schedule",
      "external": true,
      "loc": "net/core/dev.c:5141",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_rx_interrupt",
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_open",
        "drivers/net/xen-netfront.c:rx_refill_timeout",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_complete_done",
        "net/core/gro_cells.c:gro_cells_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587026096,
      "name": "__napi_schedule",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void __napi_schedule(struct napi_struct * n)
```

```json
{
  "name": "__napi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587523552,
      "name": "__napi_schedule",
      "external": true,
      "loc": "net/core/dev.c:5282",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:xennet_rx_interrupt",
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_open",
        "drivers/net/xen-netfront.c:rx_refill_timeout",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_complete_done",
        "net/core/gro_cells.c:gro_cells_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587523552,
      "name": "__napi_schedule",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void __napi_schedule(struct napi_struct * n)
```

```json
{
  "name": "__napi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587824208,
      "name": "__napi_schedule",
      "external": true,
      "loc": "net/core/dev.c:5412",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:xennet_rx_interrupt",
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:rx_refill_timeout",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_complete_done",
        "net/core/gro_cells.c:gro_cells_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587824208,
      "name": "__napi_schedule",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void __napi_schedule(struct napi_struct * n)
```

```json
{
  "name": "__napi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587957504,
      "name": "__napi_schedule",
      "external": true,
      "loc": "net/core/dev.c:5962",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:xennet_rx_interrupt",
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:rx_refill_timeout",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_complete_done",
        "net/core/gro_cells.c:gro_cells_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587957504,
      "name": "__napi_schedule",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void __napi_schedule(struct napi_struct * n)
```

```json
{
  "name": "__napi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588272288,
      "name": "__napi_schedule",
      "external": true,
      "loc": "net/core/dev.c:5972",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:xennet_rx_interrupt",
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:rx_refill_timeout",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_complete_done",
        "net/core/gro_cells.c:gro_cells_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588272288,
      "name": "__napi_schedule",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void __napi_schedule(struct napi_struct * n)
```

```json
{
  "name": "__napi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588478704,
      "name": "__napi_schedule",
      "external": true,
      "loc": "net/core/dev.c:5895",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:xennet_rx_interrupt",
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:rx_refill_timeout",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_complete_done",
        "net/core/gro_cells.c:gro_cells_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588478704,
      "name": "__napi_schedule",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void __napi_schedule(struct napi_struct * n)
```

```json
{
  "name": "__napi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589347280,
      "name": "__napi_schedule",
      "external": true,
      "loc": "net/core/dev.c:6278",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:xennet_rx_interrupt",
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_open",
        "drivers/net/xen-netfront.c:rx_refill_timeout",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_complete_done",
        "net/core/gro_cells.c:gro_cells_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589347280,
      "name": "__napi_schedule",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void __napi_schedule(struct napi_struct * n)
```

```json
{
  "name": "__napi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589350704,
      "name": "__napi_schedule",
      "external": true,
      "loc": "net/core/dev.c:6379",
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
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_complete_done",
        "net/core/gro_cells.c:gro_cells_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589350704,
      "name": "__napi_schedule",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void __napi_schedule(struct napi_struct * n)
```

```json
{
  "name": "__napi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589256656,
      "name": "__napi_schedule",
      "external": true,
      "loc": "net/core/dev.c:6492",
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
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_complete_done",
        "net/core/gro_cells.c:gro_cells_receive",
        "net/mptcp/protocol.c:__mptcp_check_push",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589256656,
      "name": "__napi_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
void __napi_schedule(struct napi_struct * n)
```

```json
{
  "name": "__napi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589982320,
      "name": "__napi_schedule",
      "external": true,
      "loc": "net/core/dev.c:6478",
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
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_complete_done",
        "net/core/gro_cells.c:gro_cells_receive",
        "net/mptcp/protocol.c:__mptcp_check_push",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589982320,
      "name": "__napi_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void __napi_schedule(struct napi_struct * n)
```

```json
{
  "name": "__napi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591517232,
      "name": "__napi_schedule",
      "external": true,
      "loc": "net/core/dev.c:5964",
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
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_complete_done",
        "net/core/gro_cells.c:gro_cells_receive",
        "net/mptcp/protocol.c:__mptcp_check_push",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591517232,
      "name": "__napi_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void __napi_schedule(struct napi_struct * n)
```

```json
{
  "name": "__napi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593294592,
      "name": "__napi_schedule",
      "external": true,
      "loc": "net/core/dev.c:5955",
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
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_complete_done",
        "net/core/gro_cells.c:gro_cells_receive",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593294592,
      "name": "__napi_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void __napi_schedule(struct napi_struct * n)
```

```json
{
  "name": "__napi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__napi_schedule",
      "external": true,
      "loc": "net/core/dev.c:5931",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_sendmsg",
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
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_complete_done",
        "net/core/gro_cells.c:gro_cells_receive",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596854206,
      "name": "__napi_schedule.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071593749584,
      "name": "__napi_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void __napi_schedule(struct napi_struct * n)
```

```json
{
  "name": "__napi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__napi_schedule",
      "external": true,
      "loc": "net/core/dev.c:6013",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_sendmsg",
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
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_complete_done",
        "net/core/gro_cells.c:gro_cells_receive",
        "net/mptcp/protocol.c:mptcp_finish_join",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/subflow.c:subflow_write_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597779196,
      "name": "__napi_schedule.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071594527904,
      "name": "__napi_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void __napi_schedule(struct napi_struct * n)
```

```json
{
  "name": "__napi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502008048,
      "name": "__napi_schedule",
      "external": true,
      "loc": "net/core/dev.c:5895",
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
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_complete_done",
        "net/core/gro_cells.c:gro_cells_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502008048,
      "name": "__napi_schedule",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void __napi_schedule(struct napi_struct * n)
```

```json
{
  "name": "__napi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234743052,
      "name": "__napi_schedule",
      "external": true,
      "loc": "net/core/dev.c:5895",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_interrupt",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_rx_interrupt",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_tx_interrupt",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_complete_done",
        "net/core/gro_cells.c:gro_cells_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234743052,
      "name": "__napi_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void __napi_schedule(struct napi_struct * n)
```

```json
{
  "name": "__napi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295420768,
      "name": "__napi_schedule",
      "external": true,
      "loc": "net/core/dev.c:5895",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_complete_done",
        "net/core/gro_cells.c:gro_cells_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295420768,
      "name": "__napi_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void __napi_schedule(struct napi_struct * n)
```

```json
{
  "name": "__napi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278285430,
      "name": "__napi_schedule",
      "external": true,
      "loc": "net/core/dev.c:5895",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_complete_done",
        "net/core/gro_cells.c:gro_cells_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278285430,
      "name": "__napi_schedule",
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
void __napi_schedule(struct napi_struct * n)
```

```json
{
  "name": "__napi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588085488,
      "name": "__napi_schedule",
      "external": true,
      "loc": "net/core/dev.c:5895",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:xennet_rx_interrupt",
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:rx_refill_timeout",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_complete_done",
        "net/core/gro_cells.c:gro_cells_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588085488,
      "name": "__napi_schedule",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void __napi_schedule(struct napi_struct * n)
```

```json
{
  "name": "__napi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587782736,
      "name": "__napi_schedule",
      "external": true,
      "loc": "net/core/dev.c:5895",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_complete_done",
        "net/core/gro_cells.c:gro_cells_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587782736,
      "name": "__napi_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void __napi_schedule(struct napi_struct * n)
```

```json
{
  "name": "__napi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588417264,
      "name": "__napi_schedule",
      "external": true,
      "loc": "net/core/dev.c:5895",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:xennet_rx_interrupt",
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:rx_refill_timeout",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_complete_done",
        "net/core/gro_cells.c:gro_cells_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588417264,
      "name": "__napi_schedule",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void __napi_schedule(struct napi_struct * n)
```

```json
{
  "name": "__napi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588555904,
      "name": "__napi_schedule",
      "external": true,
      "loc": "net/core/dev.c:5895",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:xennet_rx_interrupt",
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:rx_refill_timeout",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:napi_complete_done",
        "net/core/gro_cells.c:gro_cells_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588555904,
      "name": "__napi_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
