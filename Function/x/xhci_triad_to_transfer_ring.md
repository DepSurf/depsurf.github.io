# Function: <code>xhci_triad_to_transfer_ring</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xhci_ring * xhci_triad_to_transfer_ring(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_triad_to_transfer_ring",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585494496,
      "name": "xhci_triad_to_transfer_ring",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:375",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_urb_to_transfer_ring",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585494496,
      "name": "xhci_triad_to_transfer_ring",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xhci_ring * xhci_triad_to_transfer_ring(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_triad_to_transfer_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585891104,
      "name": "xhci_triad_to_transfer_ring",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:368",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585891104,
      "name": "xhci_triad_to_transfer_ring",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xhci_ring * xhci_triad_to_transfer_ring(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_triad_to_transfer_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586080432,
      "name": "xhci_triad_to_transfer_ring",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:452",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586080432,
      "name": "xhci_triad_to_transfer_ring",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xhci_ring * xhci_triad_to_transfer_ring(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_triad_to_transfer_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586162688,
      "name": "xhci_triad_to_transfer_ring",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:451",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586162688,
      "name": "xhci_triad_to_transfer_ring",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xhci_ring * xhci_triad_to_transfer_ring(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_triad_to_transfer_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586607936,
      "name": "xhci_triad_to_transfer_ring",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:440",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586607936,
      "name": "xhci_triad_to_transfer_ring",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct xhci_ring * xhci_triad_to_transfer_ring(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_triad_to_transfer_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586874896,
      "name": "xhci_triad_to_transfer_ring",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:440",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586874896,
      "name": "xhci_triad_to_transfer_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
struct xhci_ring * xhci_triad_to_transfer_ring(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_triad_to_transfer_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587030400,
      "name": "xhci_triad_to_transfer_ring",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:440",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587030400,
      "name": "xhci_triad_to_transfer_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct xhci_ring * xhci_triad_to_transfer_ring(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_triad_to_transfer_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587311982,
      "name": "xhci_triad_to_transfer_ring",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:447",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587311982,
      "name": "xhci_triad_to_transfer_ring.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071587294320,
      "name": "xhci_triad_to_transfer_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct xhci_ring * xhci_triad_to_transfer_ring(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_triad_to_transfer_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587513240,
      "name": "xhci_triad_to_transfer_ring",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:447",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587513240,
      "name": "xhci_triad_to_transfer_ring.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071587495296,
      "name": "xhci_triad_to_transfer_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct xhci_ring * xhci_triad_to_transfer_ring(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_triad_to_transfer_ring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_triad_to_transfer_ring",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:453",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588376754,
      "name": "xhci_triad_to_transfer_ring.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071588362800,
      "name": "xhci_triad_to_transfer_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct xhci_ring * xhci_triad_to_transfer_ring(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_triad_to_transfer_ring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xhci_triad_to_transfer_ring",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:453",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591567322,
      "name": "xhci_triad_to_transfer_ring.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071588393040,
      "name": "xhci_triad_to_transfer_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct xhci_ring * xhci_triad_to_transfer_ring(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_triad_to_transfer_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588265509,
      "name": "xhci_triad_to_transfer_ring",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:516",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:prepare_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591509800,
      "name": "xhci_triad_to_transfer_ring.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071588272656,
      "name": "xhci_triad_to_transfer_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct xhci_ring * xhci_triad_to_transfer_ring(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_triad_to_transfer_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588916394,
      "name": "xhci_triad_to_transfer_ring",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:529",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592611435,
      "name": "xhci_triad_to_transfer_ring.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071588924576,
      "name": "xhci_triad_to_transfer_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct xhci_ring * xhci_triad_to_transfer_ring(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_triad_to_transfer_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590371143,
      "name": "xhci_triad_to_transfer_ring",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:529",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594494806,
      "name": "xhci_triad_to_transfer_ring.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071590358192,
      "name": "xhci_triad_to_transfer_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
struct xhci_ring * xhci_triad_to_transfer_ring(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_triad_to_transfer_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592004839,
      "name": "xhci_triad_to_transfer_ring",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:529",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591989552,
      "name": "xhci_triad_to_transfer_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
struct xhci_ring * xhci_triad_to_transfer_ring(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_triad_to_transfer_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592425575,
      "name": "xhci_triad_to_transfer_ring",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:583",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592411952,
      "name": "xhci_triad_to_transfer_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
struct xhci_ring * xhci_triad_to_transfer_ring(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_triad_to_transfer_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593169319,
      "name": "xhci_triad_to_transfer_ring",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:591",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:prepare_transfer",
        "drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds",
        "drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593155408,
      "name": "xhci_triad_to_transfer_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
struct xhci_ring * xhci_triad_to_transfer_ring(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_triad_to_transfer_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500635560,
      "name": "xhci_triad_to_transfer_ring",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:447",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500635560,
      "name": "xhci_triad_to_transfer_ring",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct xhci_ring * xhci_triad_to_transfer_ring(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_triad_to_transfer_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233094764,
      "name": "xhci_triad_to_transfer_ring",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:447",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233094764,
      "name": "xhci_triad_to_transfer_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
struct xhci_ring * xhci_triad_to_transfer_ring(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_triad_to_transfer_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294054512,
      "name": "xhci_triad_to_transfer_ring",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:447",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294054512,
      "name": "xhci_triad_to_transfer_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
struct xhci_ring * xhci_triad_to_transfer_ring(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_triad_to_transfer_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277501238,
      "name": "xhci_triad_to_transfer_ring",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:447",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277501238,
      "name": "xhci_triad_to_transfer_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct xhci_ring * xhci_triad_to_transfer_ring(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_triad_to_transfer_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587219272,
      "name": "xhci_triad_to_transfer_ring",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:447",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587219272,
      "name": "xhci_triad_to_transfer_ring.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071587201328,
      "name": "xhci_triad_to_transfer_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct xhci_ring * xhci_triad_to_transfer_ring(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_triad_to_transfer_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586978024,
      "name": "xhci_triad_to_transfer_ring",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:447",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586978024,
      "name": "xhci_triad_to_transfer_ring.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071586960080,
      "name": "xhci_triad_to_transfer_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct xhci_ring * xhci_triad_to_transfer_ring(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_triad_to_transfer_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587467800,
      "name": "xhci_triad_to_transfer_ring",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:447",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587467800,
      "name": "xhci_triad_to_transfer_ring.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071587449856,
      "name": "xhci_triad_to_transfer_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct xhci_ring * xhci_triad_to_transfer_ring(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_triad_to_transfer_ring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587575403,
      "name": "xhci_triad_to_transfer_ring",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:447",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_find_new_dequeue_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587575403,
      "name": "xhci_triad_to_transfer_ring.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071587557152,
      "name": "xhci_triad_to_transfer_ring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
