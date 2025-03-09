# Function: <code>notify_remote_via_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void notify_remote_via_irq(int irq)
```

```json
{
  "name": "notify_remote_via_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583858992,
      "name": "notify_remote_via_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:363",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_send_IPI_one",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:netback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583858992,
      "name": "notify_remote_via_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void notify_remote_via_irq(int irq)
```

```json
{
  "name": "notify_remote_via_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584189392,
      "name": "notify_remote_via_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:363",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_send_IPI_one",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584189392,
      "name": "notify_remote_via_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void notify_remote_via_irq(int irq)
```

```json
{
  "name": "notify_remote_via_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584370880,
      "name": "notify_remote_via_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:362",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_send_IPI_one",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584370880,
      "name": "notify_remote_via_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void notify_remote_via_irq(int irq)
```

```json
{
  "name": "notify_remote_via_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584452592,
      "name": "notify_remote_via_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:354",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_send_IPI_one",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584452592,
      "name": "notify_remote_via_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void notify_remote_via_irq(int irq)
```

```json
{
  "name": "notify_remote_via_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584863184,
      "name": "notify_remote_via_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:354",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_send_IPI_one",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584863184,
      "name": "notify_remote_via_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void notify_remote_via_irq(int irq)
```

```json
{
  "name": "notify_remote_via_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585094272,
      "name": "notify_remote_via_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:354",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_send_IPI_one",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585094272,
      "name": "notify_remote_via_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void notify_remote_via_irq(int irq)
```

```json
{
  "name": "notify_remote_via_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585205056,
      "name": "notify_remote_via_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:354",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_send_IPI_one",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585205056,
      "name": "notify_remote_via_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void notify_remote_via_irq(int irq)
```

```json
{
  "name": "notify_remote_via_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585422898,
      "name": "notify_remote_via_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:355",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_send_IPI_one"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585417152,
      "name": "notify_remote_via_irq",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void notify_remote_via_irq(int irq)
```

```json
{
  "name": "notify_remote_via_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585563570,
      "name": "notify_remote_via_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:355",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_send_IPI_one"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585557872,
      "name": "notify_remote_via_irq",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void notify_remote_via_irq(int irq)
```

```json
{
  "name": "notify_remote_via_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586284866,
      "name": "notify_remote_via_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:369",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_send_IPI_one"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586276112,
      "name": "notify_remote_via_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void notify_remote_via_irq(int irq)
```

```json
{
  "name": "notify_remote_via_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586405094,
      "name": "notify_remote_via_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:534",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_send_IPI_one"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_xdp_xmit_one",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586393600,
      "name": "notify_remote_via_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void notify_remote_via_irq(int irq)
```

```json
{
  "name": "notify_remote_via_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586288326,
      "name": "notify_remote_via_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:551",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_send_IPI_one"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_xdp_xmit",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586277312,
      "name": "notify_remote_via_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void notify_remote_via_irq(int irq)
```

```json
{
  "name": "notify_remote_via_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586803927,
      "name": "notify_remote_via_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:551",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_send_IPI_one"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_xdp_xmit",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586790432,
      "name": "notify_remote_via_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void notify_remote_via_irq(int irq)
```

```json
{
  "name": "notify_remote_via_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588085879,
      "name": "notify_remote_via_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:551",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_send_IPI_one"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_xdp_xmit",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588070880,
      "name": "notify_remote_via_irq",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void notify_remote_via_irq(int irq)
```

```json
{
  "name": "notify_remote_via_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589468151,
      "name": "notify_remote_via_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:553",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_send_IPI_one"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_xdp_xmit",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589452752,
      "name": "notify_remote_via_irq",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void notify_remote_via_irq(int irq)
```

```json
{
  "name": "notify_remote_via_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589768071,
      "name": "notify_remote_via_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:554",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_send_IPI_one"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_xdp_xmit",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589752688,
      "name": "notify_remote_via_irq",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void notify_remote_via_irq(int irq)
```

```json
{
  "name": "notify_remote_via_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590093872,
      "name": "notify_remote_via_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:538",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_xdp_xmit",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590093872,
      "name": "notify_remote_via_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void notify_remote_via_irq(int irq)
```

```json
{
  "name": "notify_remote_via_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498219536,
      "name": "notify_remote_via_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:355",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_send_IPI_one",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498219536,
      "name": "notify_remote_via_irq",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void notify_remote_via_irq(int irq)
```

```json
{
  "name": "notify_remote_via_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585325282,
      "name": "notify_remote_via_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:359",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_send_IPI_one"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585319584,
      "name": "notify_remote_via_irq",
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void notify_remote_via_irq(int irq)
```

```json
{
  "name": "notify_remote_via_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585513970,
      "name": "notify_remote_via_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:355",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_send_IPI_one"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585508272,
      "name": "notify_remote_via_irq",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void notify_remote_via_irq(int irq)
```

```json
{
  "name": "notify_remote_via_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585621986,
      "name": "notify_remote_via_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:355",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_send_IPI_one"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:netback_changed",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585616288,
      "name": "notify_remote_via_irq",
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void notify_remote_via_irq(int irq)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void notify_remote_via_irq(int irq)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void notify_remote_via_irq(int irq)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void notify_remote_via_irq(int irq)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
