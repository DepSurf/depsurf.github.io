# Function: <code>xhci_cleanup_halted_endpoint</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_cleanup_halted_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585509375,
      "name": "xhci_cleanup_halted_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1734",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:finish_td"
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
  "name": "xhci_cleanup_halted_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585904786,
      "name": "xhci_cleanup_halted_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1759",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_cleanup_halted_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586094006,
      "name": "xhci_cleanup_halted_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1775",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_cleanup_halted_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586176560,
      "name": "xhci_cleanup_halted_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1822",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586176560,
      "name": "xhci_cleanup_halted_endpoint.isra.62",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_cleanup_halted_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586621872,
      "name": "xhci_cleanup_halted_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1816",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586621872,
      "name": "xhci_cleanup_halted_endpoint.isra.58",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
void xhci_cleanup_halted_endpoint(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td * td, enum xhci_ep_reset_type reset_type)
```

```json
{
  "name": "xhci_cleanup_halted_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586888960,
      "name": "xhci_cleanup_halted_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1741",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586888960,
      "name": "xhci_cleanup_halted_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
void xhci_cleanup_halted_endpoint(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td * td, enum xhci_ep_reset_type reset_type)
```

```json
{
  "name": "xhci_cleanup_halted_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587044704,
      "name": "xhci_cleanup_halted_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1789",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587044704,
      "name": "xhci_cleanup_halted_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
void xhci_cleanup_halted_endpoint(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td * td, enum xhci_ep_reset_type reset_type)
```

```json
{
  "name": "xhci_cleanup_halted_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587304992,
      "name": "xhci_cleanup_halted_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1826",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587304992,
      "name": "xhci_cleanup_halted_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
void xhci_cleanup_halted_endpoint(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td * td, enum xhci_ep_reset_type reset_type)
```

```json
{
  "name": "xhci_cleanup_halted_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587506208,
      "name": "xhci_cleanup_halted_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1826",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587506208,
      "name": "xhci_cleanup_halted_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
void xhci_cleanup_halted_endpoint(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td * td, enum xhci_ep_reset_type reset_type)
```

```json
{
  "name": "xhci_cleanup_halted_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588354368,
      "name": "xhci_cleanup_halted_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1852",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588354368,
      "name": "xhci_cleanup_halted_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
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
void xhci_cleanup_halted_endpoint(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td * td, enum xhci_ep_reset_type reset_type)
```

```json
{
  "name": "xhci_cleanup_halted_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588385616,
      "name": "xhci_cleanup_halted_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1857",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588385616,
      "name": "xhci_cleanup_halted_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void xhci_cleanup_halted_endpoint(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td * td, enum xhci_ep_reset_type reset_type)
```

```json
{
  "name": "xhci_cleanup_halted_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500647920,
      "name": "xhci_cleanup_halted_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1826",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500647920,
      "name": "xhci_cleanup_halted_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
void xhci_cleanup_halted_endpoint(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td * td, enum xhci_ep_reset_type reset_type)
```

```json
{
  "name": "xhci_cleanup_halted_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233107208,
      "name": "xhci_cleanup_halted_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1826",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233107208,
      "name": "xhci_cleanup_halted_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
void xhci_cleanup_halted_endpoint(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td * td, enum xhci_ep_reset_type reset_type)
```

```json
{
  "name": "xhci_cleanup_halted_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294069648,
      "name": "xhci_cleanup_halted_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1826",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294069648,
      "name": "xhci_cleanup_halted_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
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
void xhci_cleanup_halted_endpoint(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td * td, enum xhci_ep_reset_type reset_type)
```

```json
{
  "name": "xhci_cleanup_halted_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277511814,
      "name": "xhci_cleanup_halted_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1826",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277511814,
      "name": "xhci_cleanup_halted_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
void xhci_cleanup_halted_endpoint(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td * td, enum xhci_ep_reset_type reset_type)
```

```json
{
  "name": "xhci_cleanup_halted_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587212240,
      "name": "xhci_cleanup_halted_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1826",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587212240,
      "name": "xhci_cleanup_halted_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
void xhci_cleanup_halted_endpoint(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td * td, enum xhci_ep_reset_type reset_type)
```

```json
{
  "name": "xhci_cleanup_halted_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586970992,
      "name": "xhci_cleanup_halted_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1826",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586970992,
      "name": "xhci_cleanup_halted_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
void xhci_cleanup_halted_endpoint(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td * td, enum xhci_ep_reset_type reset_type)
```

```json
{
  "name": "xhci_cleanup_halted_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587460768,
      "name": "xhci_cleanup_halted_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1826",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587460768,
      "name": "xhci_cleanup_halted_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
void xhci_cleanup_halted_endpoint(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td * td, enum xhci_ep_reset_type reset_type)
```

```json
{
  "name": "xhci_cleanup_halted_endpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587568336,
      "name": "xhci_cleanup_halted_endpoint",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:1826",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:handle_tx_event",
        "drivers/usb/host/xhci-ring.c:finish_td"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587568336,
      "name": "xhci_cleanup_halted_endpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
void xhci_cleanup_halted_endpoint(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td * td, enum xhci_ep_reset_type reset_type)
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
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void xhci_cleanup_halted_endpoint(struct xhci_hcd * xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td * td, enum xhci_ep_reset_type reset_type)
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
