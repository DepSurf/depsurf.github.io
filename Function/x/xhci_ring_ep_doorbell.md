# Function: <code>xhci_ring_ep_doorbell</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xhci_ring_ep_doorbell(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_ring_ep_doorbell",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585492351,
      "name": "xhci_ring_ep_doorbell",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:325",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-hub.c:xhci_ring_device",
        "drivers/usb/host/xhci-hub.c:xhci_ring_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585495920,
      "name": "xhci_ring_ep_doorbell",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void xhci_ring_ep_doorbell(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_ring_ep_doorbell",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585899464,
      "name": "xhci_ring_ep_doorbell",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:314",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-hub.c:xhci_ring_device",
        "drivers/usb/host/xhci-hub.c:xhci_ring_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585891024,
      "name": "xhci_ring_ep_doorbell",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void xhci_ring_ep_doorbell(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_ring_ep_doorbell",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586088504,
      "name": "xhci_ring_ep_doorbell",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:398",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-hub.c:xhci_ring_device",
        "drivers/usb/host/xhci-hub.c:xhci_ring_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586080352,
      "name": "xhci_ring_ep_doorbell",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void xhci_ring_ep_doorbell(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_ring_ep_doorbell",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586171146,
      "name": "xhci_ring_ep_doorbell",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:397",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-hub.c:xhci_ring_device",
        "drivers/usb/host/xhci-hub.c:xhci_ring_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586162624,
      "name": "xhci_ring_ep_doorbell",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xhci_ring_ep_doorbell(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_ring_ep_doorbell",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586616465,
      "name": "xhci_ring_ep_doorbell",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:386",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-hub.c:xhci_ring_device",
        "drivers/usb/host/xhci-hub.c:xhci_ring_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586607872,
      "name": "xhci_ring_ep_doorbell",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void xhci_ring_ep_doorbell(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_ring_ep_doorbell",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586883385,
      "name": "xhci_ring_ep_doorbell",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:386",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-hub.c:xhci_ring_device",
        "drivers/usb/host/xhci-hub.c:xhci_ring_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586874832,
      "name": "xhci_ring_ep_doorbell",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void xhci_ring_ep_doorbell(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_ring_ep_doorbell",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587038953,
      "name": "xhci_ring_ep_doorbell",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:386",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-hub.c:xhci_ring_device",
        "drivers/usb/host/xhci-hub.c:xhci_ring_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587030336,
      "name": "xhci_ring_ep_doorbell",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void xhci_ring_ep_doorbell(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_ring_ep_doorbell",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587291383,
      "name": "xhci_ring_ep_doorbell",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:386",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-hub.c:xhci_ring_device",
        "drivers/usb/host/xhci-hub.c:xhci_ring_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587294224,
      "name": "xhci_ring_ep_doorbell",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xhci_ring_ep_doorbell(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_ring_ep_doorbell",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587492327,
      "name": "xhci_ring_ep_doorbell",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:386",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-hub.c:xhci_ring_device",
        "drivers/usb/host/xhci-hub.c:xhci_ring_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587495200,
      "name": "xhci_ring_ep_doorbell",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void xhci_ring_ep_doorbell(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_ring_ep_doorbell",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588359648,
      "name": "xhci_ring_ep_doorbell",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:389",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings",
        "drivers/usb/host/xhci-hub.c:xhci_ring_device",
        "drivers/usb/host/xhci-hub.c:xhci_ring_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588359648,
      "name": "xhci_ring_ep_doorbell",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void xhci_ring_ep_doorbell(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_ring_ep_doorbell",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588389968,
      "name": "xhci_ring_ep_doorbell",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:389",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings",
        "drivers/usb/host/xhci-hub.c:xhci_ring_device",
        "drivers/usb/host/xhci-hub.c:xhci_ring_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588389968,
      "name": "xhci_ring_ep_doorbell",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void xhci_ring_ep_doorbell(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_ring_ep_doorbell",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588272032,
      "name": "xhci_ring_ep_doorbell",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:413",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings",
        "drivers/usb/host/xhci-hub.c:xhci_ring_device",
        "drivers/usb/host/xhci-hub.c:xhci_ring_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588272032,
      "name": "xhci_ring_ep_doorbell",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void xhci_ring_ep_doorbell(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_ring_ep_doorbell",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588923648,
      "name": "xhci_ring_ep_doorbell",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:426",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings",
        "drivers/usb/host/xhci-hub.c:xhci_ring_device",
        "drivers/usb/host/xhci-hub.c:xhci_ring_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588923648,
      "name": "xhci_ring_ep_doorbell",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void xhci_ring_ep_doorbell(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_ring_ep_doorbell",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590354544,
      "name": "xhci_ring_ep_doorbell",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:426",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings",
        "drivers/usb/host/xhci-hub.c:xhci_ring_device",
        "drivers/usb/host/xhci-hub.c:xhci_ring_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590354544,
      "name": "xhci_ring_ep_doorbell",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
void xhci_ring_ep_doorbell(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_ring_ep_doorbell",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591985488,
      "name": "xhci_ring_ep_doorbell",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:426",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings",
        "drivers/usb/host/xhci-hub.c:xhci_ring_device",
        "drivers/usb/host/xhci-hub.c:xhci_ring_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591985488,
      "name": "xhci_ring_ep_doorbell",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
void xhci_ring_ep_doorbell(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_ring_ep_doorbell",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592407856,
      "name": "xhci_ring_ep_doorbell",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:480",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings",
        "drivers/usb/host/xhci-hub.c:xhci_ring_device",
        "drivers/usb/host/xhci-hub.c:xhci_ring_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592407856,
      "name": "xhci_ring_ep_doorbell",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
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
void xhci_ring_ep_doorbell(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_ring_ep_doorbell",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593151312,
      "name": "xhci_ring_ep_doorbell",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:488",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings",
        "drivers/usb/host/xhci-hub.c:xhci_ring_device",
        "drivers/usb/host/xhci-hub.c:xhci_ring_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593151312,
      "name": "xhci_ring_ep_doorbell",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
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
void xhci_ring_ep_doorbell(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_ring_ep_doorbell",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500632408,
      "name": "xhci_ring_ep_doorbell",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:386",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-hub.c:xhci_ring_device",
        "drivers/usb/host/xhci-hub.c:xhci_ring_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500635360,
      "name": "xhci_ring_ep_doorbell",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void xhci_ring_ep_doorbell(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_ring_ep_doorbell",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233084652,
      "name": "xhci_ring_ep_doorbell",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:386",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:giveback_first_trb",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-hub.c:xhci_ring_device",
        "drivers/usb/host/xhci-hub.c:xhci_ring_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233094636,
      "name": "xhci_ring_ep_doorbell",
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
void xhci_ring_ep_doorbell(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_ring_ep_doorbell",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294050628,
      "name": "xhci_ring_ep_doorbell",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:386",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-hub.c:xhci_ring_device",
        "drivers/usb/host/xhci-hub.c:xhci_ring_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294054384,
      "name": "xhci_ring_ep_doorbell",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void xhci_ring_ep_doorbell(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_ring_ep_doorbell",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277491322,
      "name": "xhci_ring_ep_doorbell",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:386",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-hub.c:xhci_ring_device",
        "drivers/usb/host/xhci-hub.c:xhci_ring_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277501024,
      "name": "xhci_ring_ep_doorbell",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void xhci_ring_ep_doorbell(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_ring_ep_doorbell",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587198359,
      "name": "xhci_ring_ep_doorbell",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:386",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-hub.c:xhci_ring_device",
        "drivers/usb/host/xhci-hub.c:xhci_ring_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587201232,
      "name": "xhci_ring_ep_doorbell",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void xhci_ring_ep_doorbell(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_ring_ep_doorbell",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586957111,
      "name": "xhci_ring_ep_doorbell",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:386",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-hub.c:xhci_ring_device",
        "drivers/usb/host/xhci-hub.c:xhci_ring_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586959984,
      "name": "xhci_ring_ep_doorbell",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void xhci_ring_ep_doorbell(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_ring_ep_doorbell",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587446887,
      "name": "xhci_ring_ep_doorbell",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:386",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-hub.c:xhci_ring_device",
        "drivers/usb/host/xhci-hub.c:xhci_ring_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587449760,
      "name": "xhci_ring_ep_doorbell",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void xhci_ring_ep_doorbell(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id)
```

```json
{
  "name": "xhci_ring_ep_doorbell",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587554154,
      "name": "xhci_ring_ep_doorbell",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:386",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings",
        "drivers/usb/host/xhci-ring.c:ring_doorbell_for_active_rings"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-hub.c:xhci_ring_device",
        "drivers/usb/host/xhci-hub.c:xhci_ring_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587557056,
      "name": "xhci_ring_ep_doorbell",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
