# Function: <code>prepare_transfer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int prepare_transfer(struct xhci_hcd * xhci, struct xhci_virt_device * xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb * urb, unsigned int td_index, gfp_t mem_flags)
```

```json
{
  "name": "prepare_transfer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585493248,
      "name": "prepare_transfer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2889",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585493248,
      "name": "prepare_transfer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
int prepare_transfer(struct xhci_hcd * xhci, struct xhci_virt_device * xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb * urb, unsigned int td_index, gfp_t mem_flags)
```

```json
{
  "name": "prepare_transfer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585888352,
      "name": "prepare_transfer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2912",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585888352,
      "name": "prepare_transfer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
int prepare_transfer(struct xhci_hcd * xhci, struct xhci_virt_device * xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb * urb, unsigned int td_index, gfp_t mem_flags)
```

```json
{
  "name": "prepare_transfer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586077456,
      "name": "prepare_transfer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2814",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586077456,
      "name": "prepare_transfer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
int prepare_transfer(struct xhci_hcd * xhci, struct xhci_virt_device * xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb * urb, unsigned int td_index, gfp_t mem_flags)
```

```json
{
  "name": "prepare_transfer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586159024,
      "name": "prepare_transfer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2916",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586159024,
      "name": "prepare_transfer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
int prepare_transfer(struct xhci_hcd * xhci, struct xhci_virt_device * xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb * urb, unsigned int td_index, gfp_t mem_flags)
```

```json
{
  "name": "prepare_transfer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586604304,
      "name": "prepare_transfer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2920",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586604304,
      "name": "prepare_transfer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
int prepare_transfer(struct xhci_hcd * xhci, struct xhci_virt_device * xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb * urb, unsigned int td_index, gfp_t mem_flags)
```

```json
{
  "name": "prepare_transfer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586869856,
      "name": "prepare_transfer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2839",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586869856,
      "name": "prepare_transfer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
int prepare_transfer(struct xhci_hcd * xhci, struct xhci_virt_device * xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb * urb, unsigned int td_index, gfp_t mem_flags)
```

```json
{
  "name": "prepare_transfer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587025168,
      "name": "prepare_transfer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2903",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587025168,
      "name": "prepare_transfer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
int prepare_transfer(struct xhci_hcd * xhci, struct xhci_virt_device * xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb * urb, unsigned int td_index, gfp_t mem_flags)
```

```json
{
  "name": "prepare_transfer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587286768,
      "name": "prepare_transfer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2949",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587286768,
      "name": "prepare_transfer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
int prepare_transfer(struct xhci_hcd * xhci, struct xhci_virt_device * xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb * urb, unsigned int td_index, gfp_t mem_flags)
```

```json
{
  "name": "prepare_transfer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587487712,
      "name": "prepare_transfer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2976",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587487712,
      "name": "prepare_transfer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
int prepare_transfer(struct xhci_hcd * xhci, struct xhci_virt_device * xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb * urb, unsigned int td_index, gfp_t mem_flags)
```

```json
{
  "name": "prepare_transfer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588350656,
      "name": "prepare_transfer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3022",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588350656,
      "name": "prepare_transfer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
int prepare_transfer(struct xhci_hcd * xhci, struct xhci_virt_device * xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb * urb, unsigned int td_index, gfp_t mem_flags)
```

```json
{
  "name": "prepare_transfer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588381504,
      "name": "prepare_transfer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3032",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588381504,
      "name": "prepare_transfer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
int prepare_transfer(struct xhci_hcd * xhci, struct xhci_virt_device * xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb * urb, unsigned int td_index, gfp_t mem_flags)
```

```json
{
  "name": "prepare_transfer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588272800,
      "name": "prepare_transfer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3220",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588272800,
      "name": "prepare_transfer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
int prepare_transfer(struct xhci_hcd * xhci, struct xhci_virt_device * xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb * urb, unsigned int td_index, gfp_t mem_flags)
```

```json
{
  "name": "prepare_transfer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588924880,
      "name": "prepare_transfer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3290",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588924880,
      "name": "prepare_transfer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
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
int prepare_transfer(struct xhci_hcd * xhci, struct xhci_virt_device * xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb * urb, unsigned int td_index, gfp_t mem_flags)
```

```json
{
  "name": "prepare_transfer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590346000,
      "name": "prepare_transfer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3225",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590346000,
      "name": "prepare_transfer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
int prepare_transfer(struct xhci_hcd * xhci, struct xhci_virt_device * xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb * urb, unsigned int td_index, gfp_t mem_flags)
```

```json
{
  "name": "prepare_transfer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591975536,
      "name": "prepare_transfer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3232",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591975536,
      "name": "prepare_transfer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
int prepare_transfer(struct xhci_hcd * xhci, struct xhci_virt_device * xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb * urb, unsigned int td_index, gfp_t mem_flags)
```

```json
{
  "name": "prepare_transfer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592396992,
      "name": "prepare_transfer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3252",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592396992,
      "name": "prepare_transfer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
int prepare_transfer(struct xhci_hcd * xhci, struct xhci_virt_device * xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb * urb, unsigned int td_index, gfp_t mem_flags)
```

```json
{
  "name": "prepare_transfer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593139968,
      "name": "prepare_transfer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:3295",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593139968,
      "name": "prepare_transfer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
int prepare_transfer(struct xhci_hcd * xhci, struct xhci_virt_device * xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb * urb, unsigned int td_index, gfp_t mem_flags)
```

```json
{
  "name": "prepare_transfer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500625288,
      "name": "prepare_transfer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2976",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500625288,
      "name": "prepare_transfer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int prepare_transfer(struct xhci_hcd * xhci, struct xhci_virt_device * xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb * urb, unsigned int td_index, gfp_t mem_flags)
```

```json
{
  "name": "prepare_transfer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233086948,
      "name": "prepare_transfer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2976",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233086948,
      "name": "prepare_transfer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
int prepare_transfer(struct xhci_hcd * xhci, struct xhci_virt_device * xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb * urb, unsigned int td_index, gfp_t mem_flags)
```

```json
{
  "name": "prepare_transfer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294042192,
      "name": "prepare_transfer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2976",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294042192,
      "name": "prepare_transfer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
int prepare_transfer(struct xhci_hcd * xhci, struct xhci_virt_device * xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb * urb, unsigned int td_index, gfp_t mem_flags)
```

```json
{
  "name": "prepare_transfer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277492300,
      "name": "prepare_transfer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2976",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277492300,
      "name": "prepare_transfer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
int prepare_transfer(struct xhci_hcd * xhci, struct xhci_virt_device * xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb * urb, unsigned int td_index, gfp_t mem_flags)
```

```json
{
  "name": "prepare_transfer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587193744,
      "name": "prepare_transfer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2976",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587193744,
      "name": "prepare_transfer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
int prepare_transfer(struct xhci_hcd * xhci, struct xhci_virt_device * xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb * urb, unsigned int td_index, gfp_t mem_flags)
```

```json
{
  "name": "prepare_transfer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586952496,
      "name": "prepare_transfer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2976",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586952496,
      "name": "prepare_transfer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
int prepare_transfer(struct xhci_hcd * xhci, struct xhci_virt_device * xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb * urb, unsigned int td_index, gfp_t mem_flags)
```

```json
{
  "name": "prepare_transfer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587442272,
      "name": "prepare_transfer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2976",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587442272,
      "name": "prepare_transfer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
int prepare_transfer(struct xhci_hcd * xhci, struct xhci_virt_device * xdev, unsigned int ep_index, unsigned int stream_id, unsigned int num_trbs, struct urb * urb, unsigned int td_index, gfp_t mem_flags)
```

```json
{
  "name": "prepare_transfer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587549280,
      "name": "prepare_transfer",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2976",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587549280,
      "name": "prepare_transfer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
